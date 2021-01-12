---
title: "Centos7下Ansible部署CDH6"
date: 2021-01-12T09:52:51+08:00
draft: false
tags: ["Centos7", "CDH",]
categories: [ "CDH" ]
toc: true
---

# Centos7下Ansible部署CDH6

## 搭建YUM源

### 安装Nginx服务器

```bash
autoindes on;
```

### 获取CM YUM源rpm包

```bash
mkdir /data/cloudera_soft/CDH6.0.0/cm
cd /data/cloudera_soft/CDH6.0.0/cm
wget --recursive --no-parent --no-host-directories https://archive.cloudera.com/cm6/6.0.0/redhat7/
chmod -R ugo+rX cm6
cd /data/cloudera_soft/CDH6.0.0/cm/cm6/6.0.0
wget https://archive.cloudera.com/cm6/6.0.0/allkeys.asc
mkdir /data/cloudera_soft/CDH6.0.0/cdh
cd /data/cloudera_soft/CDH6.0.0/cdh
wget https://archive.cloudera.com/cdh6/6.0.0/parcels/CDH-6.0.0-1.cdh6.0.0.p0.537114-el7.parcel
wget https://archive.cloudera.com/cdh6/6.0.0/parcels/CDH-6.0.0-1.cdh6.0.0.p0.537114-el7.parcel.sha256
wget https://archive.cloudera.com/cdh6/6.0.0/parcels/manifest.json
```

## Ansible配置

### pip安装

```bash
mkdir /root/.pip && echo '[global]' >>  /root/.pip/pip.conf &&   echo 'index-url = https://mirrors.aliyun.com/pypi/simple' >>  /root/.pip/pip.conf &&   curl http://10.251.35.58:8900/pip/get-pip.py -o get-pip.py && python get-pip.py
```

### ansible安装

```bash
pip install ansible
```

### ansible配置

```bash
vim ~/.bash_profile
```

```bash
export ANSIBLE_CONFIG=/etc/ansible/ansible.cfg
```

```bash
mkdir /etc/ansible/ && vim /etc/ansible/ansible.cfg
```

```bash
[defaults]
inventory      = /etc/ansible/hosts
host_key_checking = False
remote_user = root
```

### 配置hosts

```bash
vim /etc/ansible/hosts
```

```bash
[cdh]
10.251.35.80
10.251.35.81
10.251.35.83
10.251.35.85
10.251.35.86
```

### 配置Ansible免密登录

```bash
ssh-keygen -t rsa -P '' -f ./id_rsa -C cm@10.251.35.1
```

```bash
ansible cdh -m authorized_key -a key="{{ lookup('file', '~/.ssh/id_rsa.pub') }} user=root" --ask-pass -u root
```

**回收权限**

```bash
ansible cdh -m authorized_key -a key="{{ lookup('file', '~/id_rsa.pub') }} user=root state=absent"  -u root
```

### 分发hosts

```bash
ansible cdh -m copy -a 'src=/etc/hosts dest=/etc/hosts' 
```

## 卸载不必要的软件

```bash
ansible cdh -m shell -a 'yum remove -y $(rpm -qa|grep mariadb) chrony'
```

## 配置

### 禁用Linux THP（Transparent HugePages）服务

```bash
ansible cdh -m shell -a 'if test -f /sys/kernel/mm/transparent_hugepage/enabled;then echo never > /sys/kernel/mm/transparent_hugepage/enabled;fi;if test -f /sys/kernel/mm/transparent_hugepage/defrag; then echo never > /sys/kernel/mm/transparent_hugepage/defrag;fi'
```

### 设置开机启动禁用THP服务

```bash
ansible cdh -m shell -a 'echo "if test -f /sys/kernel/mm/transparent_hugepage/enabled;then echo never > /sys/kernel/mm/transparent_hugepage/enabled;fi;if test -f /sys/kernel/mm/transparent_hugepage/defrag; then echo never > /sys/kernel/mm/transparent_hugepage/defrag;fi">> /etc/rc.local'
```

### 设置swap

```bash
ansible cdh -m shell -a 'echo vm.swappiness = 0 >> /etc/sysctl.conf && sysctl -p && swapoff -a'
```

## 安装配置ntp服务

### 安装

```bash
ansible cdh -m shell -a 'yum install -y ntp'
```

### 配置ntp

```bash
vim /etc/ntp.conf 
```

```bash
server time.pool.aliyun.com
```

```bash
ansible cdh -m copy -a 'src=/etc/ntp.conf dest=/etc/ntp.conf'
```

### 启动ntp服务

```bash
ansible cdh -m systemd -a 'name=ntpd state=started enabled=true'
```

### 检查ntp服务

```bash
ansible cdh -m shell -a 'ntpstat'
```

## MySQL安装

### 配置MySQL源

```bash
ansible cdh -m shell -a 'rpm -ivh https://repo.mysql.com//mysql80-community-release-el7-3.noarch.rpm && yum makecache'
```

### MySQL节点修改为源为5.7版本

```bash
vim /etc/yum.repos.d/mysql-community.repo 
```

```bash
# Enable to use MySQL 5.7
[mysql57-community]
name=MySQL 5.7 Community Server
baseurl=http://repo.mysql.com/yum/mysql-5.7-community/el/7/$basearch/
enabled=1
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-mysql

[mysql80-community]
name=MySQL 8.0 Community Server
baseurl=http://repo.mysql.com/yum/mysql-8.0-community/el/7/$basearch/
enabled=0
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-mysql
```

### 安装MySQL客户端、JDBC驱动

```bash
ansible cdh -m shell -a 'yum install -y mysql'
ansible cdh -m shell -a 'yum install -y java-headless'
ansible cdh -m shell -a 'rpm -ivh https://mysql.com/Downloads/Connector-J/mysql-connector-java-8.0.18-1.el7.noarch.rpm'
```

### 安装MySQL-Server5.7

```bash
yum install mysql-server
```

### 修改MySQL配置

```bash
mkdir /data/mysql && chown -R mysql. /data/mysql
```

```bash
vim /etc/my.cnf
```

```bash
[mysqld]
datadir=/data/mysql/data
socket=/var/lib/mysql/mysql.sock
transaction-isolation = READ-COMMITTED
# Disabling symbolic-links is recommended to prevent assorted security risks;
# to do so, uncomment this line:
symbolic-links = 0

key_buffer_size = 32M
max_allowed_packet = 32M
thread_stack = 256K
thread_cache_size = 64
query_cache_limit = 8M
query_cache_size = 64M
query_cache_type = 1

max_connections = 550
#expire_logs_days = 10
#max_binlog_size = 100M

#log_bin should be on a disk with enough free space.
#Replace '/var/lib/mysql/mysql_binary_log' with an appropriate path for your
#system and chown the specified folder to the mysql user.
log_bin=/data/mysql/mysql_binary_log

#In later versions of MySQL, if you enable the binary log and do not set
#a server_id, MySQL will not start. The server_id must be unique within
#the replicating group.
server_id=1

binlog_format = row

read_buffer_size = 2M
read_rnd_buffer_size = 16M
sort_buffer_size = 8M
join_buffer_size = 8M

# InnoDB settings
innodb_file_per_table = 1
innodb_flush_log_at_trx_commit  = 2
innodb_log_buffer_size = 64M
innodb_buffer_pool_size = 4G
innodb_thread_concurrency = 8
innodb_flush_method = O_DIRECT
innodb_log_file_size = 512M

[mysqld_safe]
log-error=/var/log/mysqld.log
pid-file=/var/run/mysqld/mysqld.pid

sql_mode=STRICT_ALL_TABLES
```

```bash
systemctl start mysqld
systemctl enable mysqld
```

### 修改root密码

```bash
# cat /var/log/mysqld.log |grep password
2019-11-04T12:13:53.053832Z 1 [Note] A temporary password is generated for root@localhost: ZsxL0gkqdU:;

mysqladmin -u root -p'jE%IxE;(=3hF' password 新密码

```

### 忘记密码

```bash
vim /etc/my.cnf
 
[mysqld]
skip-grant-tables
```

```bash
systemctl restart mysqld
```

```bash
mysql
mysql> use mysql;
mysql> UPDATE user SET authentication_string=PASSWORD('密码') where USER='root';  
mysql> FLUSH PRIVILEGES;
mysql> exit
```

移除`skip-grant-tables`后重启MySQL

### 进入MySQL后需要重新设置密码

```sql
mysql> ALTER USER USER() IDENTIFIED BY '密码';
```

### 修改密码策略

```sql
mysql> show VARIABLES like "%password%";
set global validate_password_policy=0;
set global validate_password_policy=0;
set global validate_password_length=0;
```

## 安装系统依赖

```bash
ansible cdh -m shell -a 'yum install -y mysql-devel python-devel cyrus-sasl-plain  cyrus-sasl-devel  cyrus-sasl-gssapi && pip install psycopg2==2.7.5 --ignore-installed'
```

## 配置CDH yum源

### 配置

```bash
vim /etc/yum.repos.d/cloudera-repo.repo

[cloudera-repo]
name=cloudera-repo
baseurl=http://ip:8900/CDH6.0.0/cm/cm6/6.0.0/redhat7/yum/
enabled=1
gpgcheck=0
```

### 分发

```bash
ansible cdh -m copy -a 'src=/etc/yum.repos.d/cloudera-repo.repo dest=/etc/yum.repos.d/cloudera-repo.repo'
```

### 安装JDK（此时可以不安装，安装向导再安装）

```bash
ansible cdh -m shell -a 'yum install -y oracle-j2sdk1.8'
```

## 安装CDH

###安装CM-Agent

```bash
ansible cdh -m shell -a 'yum install -y cloudera-manager-daemons cloudera-manager-agent' 
```

### 安装CM Server

```bash
yum install -y cloudera-manager-server
```

### 初始化SCM数据库

```bash
/opt/cloudera/cm/schema/scm_prepare_database.sh mysql -uroot -p密码 scm scm scm@2020
```

### 启动CM

```bash
systemctl start cloudera-scm-server
```

### 查看启动日志

```bash
tail -f /var/log/cloudera-scm-server/cloudera-scm-server.log 

INFO WebServerImpl:org.eclipse.jetty.server.Server: Started @147388ms
INFO WebServerImpl:com.cloudera.server.cmf.WebServerImpl: Started Jetty server.
```

### 访问CM

http://cm:7180

### 配置软件仓库

### 安装JDK

### 安装CDH

### 创建MySQL库

```sql
CREATE DATABASE metastore DEFAULT CHARACTER SET utf8 DEFAULT COLLATE utf8_general_ci;
GRANT ALL ON metastore.* TO 'hive'@'%' IDENTIFIED BY 'hive@2020';

CREATE DATABASE hue DEFAULT CHARACTER SET utf8 DEFAULT COLLATE utf8_general_ci;
GRANT ALL ON hue.* TO 'hue'@'%' IDENTIFIED BY 'hue@2020';

CREATE DATABASE sentry DEFAULT CHARACTER SET utf8 DEFAULT COLLATE utf8_general_ci;
GRANT ALL ON sentry.* TO 'sentry'@'%' IDENTIFIED BY 'sentry@2020';

CREATE DATABASE oozie DEFAULT CHARACTER SET utf8 DEFAULT COLLATE utf8_general_ci;
GRANT ALL ON oozie.* TO 'oozie'@'%' IDENTIFIED BY 'oozie@2020';

CREATE DATABASE amon DEFAULT CHARACTER SET utf8 DEFAULT COLLATE utf8_general_ci;
GRANT ALL ON amon.* TO 'amon'@'%' IDENTIFIED BY 'amon@2020';
```

## LDAP客户端配置

```bash
ansible new -m shell -a "yum -y install openldap-clients sssd authconfig nss-pam-ldapd && echo 'URI ldap://ldap.cdh.prd.bjds.lan' >> /etc/openldap/ldap.conf &&  echo 'BASE dc=test,dc=com' >> /etc/openldap/ldap.conf && authconfig --enablesssd --enablesssdauth  --enableldap --enableldapauth --disableforcelegacy --disableldaptls --disablekrb5 --ldapserver ldap://ldap.cdh.prd.bjds.lan --ldapbasedn 'dc=test,dc=com' --enablemkhomedir --update && chmod 600 /etc/sssd/sssd.conf && systemctl start sssd && systemctl enable sssd" 
```





