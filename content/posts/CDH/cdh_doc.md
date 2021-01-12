---
title: "[转载]从入门到精通 - Fayson带你玩转CDH"
date: 2021-01-11T09:52:51+08:00
draft: false
tags: ["Hadoop", "CDH","大数据"]
categories: ["CDH"]
toc: true
---

[**微信公众号目录**](https://mp.weixin.qq.com/s/XtL6y9J_sbOgX2BYfgTtYA)

[**腾讯云开发者**](https://cloud.tencent.com/developer/user/1522219)



## **规划设计**

**1.1.on-premise部署规划**


0001-《[CDH网络要求(Lenovo参考架构)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247483653&idx=1&sn=f2f35bf9ac30e5e61fc5c569f53a9dab&chksm=ec2ad10cdb5d581a7355ba7056ed4b3e30f9bd1bc5412532cfe690f3c9a42000418e8afd4dba&scene=21#wechat_redirect)》

0062-《[如何为Hadoop集群选择正确的硬件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485329&idx=1&sn=7d4fb9f9ea3f1fb08d2aaa0a808f9302&chksm=ec2ad798db5d5e8e67859afbffa977ff86db86a0e667840dbf0bb9dfc89262dd4ee4fee0a06b&scene=21#wechat_redirect)》

0158-《[如何给Hadoop集群划分角色](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487209&idx=1&sn=a9d7b1cba01526fe1b1fb7a085dd9e9c&chksm=ec2adee0db5d57f687ef5be19077dfc2f94428950c7b95865f62d790bd46363ee6e039341702&scene=21#wechat_redirect)》

**1.2.on private cloud部署规划**

0200- 《[如何在VMware上部署Hadoop](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488093&idx=1&sn=9b0497104edaf7720d441b4e3223d24a&chksm=ec2ac254db5d4b42831eba7cd9c8bdcafe2c429ca9865767cf5ff2ac8856635b88be785e8771&scene=21#wechat_redirect)》

**1.3.on public cloud部署规划**

0195- 《[公有云中的Hadoop](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487940&idx=1&sn=57c2a1a76f006f76d4b649c802a2951c&chksm=ec2ac1cddb5d48dbf447e9e6283a080a5913bed095c7d8ec79c10598b66cb0fedaff6b0249f0&scene=21#wechat_redirect)》

## **安装/升级/卸载**

**2.1.安装**

0002-《[CENTOS7.2安装CDH5.10和Kudu1.2(一)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247483731&idx=1&sn=e5a80a84cf54b69d21c7af56ca6c63b4&chksm=ec2ad15adb5d584c95978010108181386bd2697abadc1107985ce3cc264def70929af70f7e07&scene=21#wechat_redirect)》

0002-《[CENTOS7.2安装CDH5.10和Kudu1.2(二)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247483731&idx=2&sn=f88151af779e21beabd00645aea3b62f&chksm=ec2ad15adb5d584c63addfb568f1e8faf537a9f25acc765e8083b18cddd9c612474fc4b95f00&scene=21#wechat_redirect)》

0024-《[CENTOS6.5安装CDH5.12.1(一)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484386&idx=1&sn=8cf1a8fd4847c5cb5d03774bea12119a&chksm=ec2ad3ebdb5d5afd2efe93ef442113e9c5e284626ec02b715b54a99d104104a6c42eb7350b05&scene=21#wechat_redirect)》

0025-《[CENTOS6.5安装CDH5.12.1(二)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484459&idx=1&sn=02632f0e7909fc912e80bd8904e50279&chksm=ec2ad422db5d5d34680430cf6cb42f31be78486c854d021fbc27be47c815f4589aa4755f1901&scene=21#wechat_redirect)》

0030-《[如何在CDH中安装Kudu&Spark2&Kafka](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484809&idx=1&sn=b126d97ab27c0b96e7c1b8ef4948ef71&chksm=ec2ad580db5d5c96bc8aade109fd416ad09956b061a804a9a901734cdc28deddf4e8a2bd1c68&scene=21#wechat_redirect)》

0072-《[CDH安装前置准备](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485512&idx=1&sn=9e953a7eb8b3b2a64a011550ab7da184&chksm=ec2ad841db5d51573f5913d14c33135180bca023de1c349fc431f561c055d1d085527107b66e&scene=21#wechat_redirect)》

0073-《[CentOS6.5安装CDH5.13](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485557&idx=1&sn=539fd04afd3000d7c83a28f9b461a86d&chksm=ec2ad87cdb5d516a071c453afb7acb6dcca4b3fda6539d4d86bf83451f18fa5411c553c7065e&scene=21#wechat_redirect)》

0167-《[如何在Redhat7.3安装CDH5.14](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487399&idx=1&sn=24121261b009147418e9d8e58ca26d24&chksm=ec2adfaedb5d56b86a3c6668ce2884f6200a6978da1f8f80cc2595c9ddb025e21c8ee5b2a552&scene=21#wechat_redirect)》

0270- 《[如何在Redhat7.4安装CDH6.0.0_beta1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489747&idx=1&sn=5382c7136f100f736f4eeb4efedad783&chksm=ec2ac8dadb5d41ccb083d3180a48adbf33afd3f464cc431347112d7d35de1ef05ca717cd379c&scene=21#wechat_redirect)》

0317- 《[如何在Redhat7.4安装CDH5.15](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491089&idx=1&sn=0a3e99e7c1523387b57467fd4f3d0943&chksm=ec2ace18db5d470ec4057b87e6fc2242d556a93e94720fa9713c5a0c06f979c1612f65ff569b&scene=21#wechat_redirect)》

0377- 《[如何在Redhat7.4安装CDH6.0](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492267&idx=1&sn=78f3a0332c2a78166d7c9e14c5f875a4&chksm=ec2932a2db5ebbb43bd9c1b80a24cd4432df49fdf2b18b875a9ca38b16f5b1cbbffd34237c76&scene=21#wechat_redirect)》

0470- 《[0470-如何在Redhat7.4安装CDH5.16.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494224&idx=1&sn=80125939910073360fffe8ef37261e1d&chksm=ec293a59db5eb34fc8ed43c23727351a190acab4e6d701adf707dd04d932698ef45810356518&scene=21#wechat_redirect)》

0491- 《[0491-如何在Redhat7.4安装CDH6.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495280&idx=1&sn=e1d09b47cc18a2d6e862d21501b44475&chksm=ec293e79db5eb76f6267a8ac4309b920e291f2f5c792eb02a64feec6af72892d625fdf4c1085&scene=21#wechat_redirect)》

《[0549-6.1-如何在SUSE12 SP3安装CDH6.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496329&idx=1&sn=245435eaac3f26f67b38f6144e3a07f5&chksm=ec292280db5eab9634794c457f5822a9e055c6ca82abf21f593a50c4fc6f18511b3234a7a317&scene=21#wechat_redirect)》

《[0610-6.2.0-如何在Redhat7.4安装CDH6.2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497568&idx=1&sn=2bdfde716afca6b38910362c59af0cc1&chksm=ec292769db5eae7f6b6e02cab4c8d6891198fd90c685e226ddacda2b2b054ac86e2b93dda628&scene=21#wechat_redirect)》

《[0719-5.10.0-如何在RedHat7.2使用rpm安装CDH(无CM)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500313&idx=1&sn=e8df6a491ce2ef948af1c98ed56b188d&chksm=ec291210db5e9b06bbecd23674915e3c8d7f98b85118da0382a8568328268a1aa96aba9d629d&scene=21#wechat_redirect)》

《[0720-5.10.0-如何在RedHat7.2使用rpm安装CDH(有CM)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500480&idx=1&sn=475e57598dcab21d79866589cf3b4205&chksm=ec2912c9db5e9bdfdcc9108d46721790e0ba6a6d70693dabef2e8a497f4b57177f8a957c3e6c&scene=21#wechat_redirect)》

《[0721-5.10.0-CM接管rpm方式安装的无CM的CDH集群](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500616&idx=1&sn=0e68594f55d2a0847a72eea5ff68b948&chksm=ec291341db5e9a57aa6c43eb0cbf6f060f482b16127b31f3667537679c82b60ca8df0c5d6561&scene=21#wechat_redirect)》

《[0722-6.2.0-如何在RedHat7.2使用rpm安装CDH(无CM)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500734&idx=1&sn=4b3a21fcce4d2fdf078963ae194d8fe8&chksm=ec2913b7db5e9aa1a987a498f3016ac2064eab5077b6b44e14a09779227d60f960fb191ca7bf&scene=21#wechat_redirect)》

《[0723-6.2.0-如何在RedHat7.2使用rpm安装CDH(有CM)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500781&idx=1&sn=361af7574b7d359838e220c34f31babc&chksm=ec2913e4db5e9af24b885f01f2c1786330ffed6c682271595a12b9e8e5d1e0c1fdf1225fb1a2&scene=21#wechat_redirect)》

《[0724-6.2.0-CM接管rpm方式安装的无CM的CDH集群](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500908&idx=1&sn=f6a8f79266567df7e1dfd5478de6819e&chksm=ec291465db5e9d73d6a3ae62cdd8b4c640499501bd443c22fb5f938c1b5fd4aa258eef9244a8&scene=21#wechat_redirect)》

《[0728-6.3.0-如何在Redhat7.4安装CDH6.3](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501071&idx=1&sn=c29f64eac82e1034b2b131c6f903c57f&chksm=ec291506db5e9c10f0331789c3701f6354d4396ce2f23459b4bd554e91f38d29e6182109dcb5&scene=21#wechat_redirect)》

《[0733-7.0.3-如何在Redhat7.6中安装CDP DC7.0.3](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501195&idx=1&sn=bd0ef99643ba5aefd61d43364d5b9118&chksm=ec291582db5e9c9425152812e5563b97963ec0d2663719c6c32455a2aca2ad9aaad79b6bedb5&scene=21#wechat_redirect)》

《[0753-6.3.3-如何在Redhat7.6安装CDH6.3.3](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501681&idx=1&sn=677f5cea1a0a3657345d48c626ca6e95&chksm=ec291778db5e9e6e1a5be174e7eb93864d0a2e8889a43f6fd0c640242a3f50d1b8490b399464&scene=21#wechat_redirect)》

《[0798-7.1.2-如何在Redhat7.8中安装CDP DC](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502806&idx=1&sn=85ba2c46bc204395a9b5eb5faa78efdd&chksm=ec291bdfdb5e92c9ddda7e5dda28fdbd29b2f49e8697126d50646789507cee494596e87a6171&scene=21#wechat_redirect)》



**2.2.一键安装**



**2.3.升级**

0009-《[如何升级Cloudera Manager和CDH](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484135&idx=1&sn=a701525a61743198d32ed21d85eeda5d&chksm=ec2ad2eedb5d5bf8945abc519fb7079c87d4feee48f341656cba3f906933cf75efcb346b1433&scene=21#wechat_redirect)》

0095-《[如何通过CM升级Kafka0.11及Spark2.2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486091&idx=1&sn=d08ec43614d4ff4a522c8983b52052d2&chksm=ec2ada82db5d53943caa0a751e783389643edf7eea4165d1f6204590a606718277bcf0c8b5b6&scene=21#wechat_redirect)》

0171- 《[如何使用Cloudera Manager升级Spark2.1版本至Spark2.2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487453&idx=1&sn=5204f4f4896cedcd1312008c731ab07e&chksm=ec2adfd4db5d56c2dd5e1eb0dc19cff3825fdce966c46be05e2184174cc19ec1af84ae996e4f&scene=21#wechat_redirect)》

0284- 《[CDH集群跨多版本滚动升级](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490242&idx=1&sn=e348a2672bd6781253b3836673f24a30&chksm=ec2acacbdb5d43dde0291cb3fb4e0a03dbe0e24eb5710c103cc07ea00284fd49b8b0187e2789&scene=21#wechat_redirect)》

《[0594-6.1.0-如何从CDH6.1.0升级到CDH6.2.0](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497130&idx=1&sn=1c592e92a56ce0fde1c0d09839de9e4f&chksm=ec2925a3db5eacb546d3c2fc10b85dff76618ff6e2bd02938b0621a27163f8f2a9bdb3f386a6&scene=21#wechat_redirect)》



**2.4.迁移**


0007-《[如何迁移Cloudera Manager节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247483970&idx=1&sn=6d847a32e90ab485713f02f0b676110c&chksm=ec2ad24bdb5d5b5d24b51349494d8f3e0a5873a8ea739d283d5eea41d9aac6d96bbcedda5d1f&scene=21#wechat_redirect)》

**2.5.卸载**




0008-《[如何卸载CDH(附一键卸载github源码)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484118&idx=1&sn=e7109978013a286fe1f172f99459c45a&chksm=ec2ad2dfdb5d5bc96fcaeb6ce2ed42a025e1d95ab251372fb4769c29434f0d84fb66bbfec1d2&scene=21#wechat_redirect)》

《[0609-6.1.0-如何卸载CDH6.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497490&idx=1&sn=be70e314a97e47d32388e1f341852ac3&chksm=ec29271bdb5eae0dd541eb348cdb6c453b13cc8560bb5a211a63907971cebd0e80bcba4965bc&scene=21#wechat_redirect)》

《[0621-6.2.0-如何卸载CDH6.2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497780&idx=1&sn=3462cde7c04f8211bd5cecfecbd8caa8&chksm=ec29283ddb5ea12b163d48e9ce2a082be0618b9e583b0139b77bc185d5a5a68557d960bec99b&scene=21#wechat_redirect)》

《[0725-5.16.2-如何卸载CDH5.16.2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500955&idx=1&sn=7e742cfecbdd31db7ecdbb36d9350f86&chksm=ec291492db5e9d84b52a5a70cc66e1bae96e8f435fee47c3dbdd96ef8893a68a8b5f27fbada4&scene=21#wechat_redirect)》

《[0818-7.1.1-如何卸载CDP](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503243&idx=1&sn=c37b7ef9e38bde0e2d662c29cff7353e&chksm=ec291d82db5e949451612445adbd21e5eacc6a5fcf81cce99c0cdae13a6bd552d845dce4d314&scene=21#wechat_redirect)》

## **Cloudera Manager**

**3.1.产品介绍**

0053-《[CDH5.13和CM5.13的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485205&idx=1&sn=7280c18e14347e32619476e084d5819c&chksm=ec2ad71cdb5d5e0ae7fa3278726760632f5eb98b99c1fab3285c5a597203827454da92025f7d&scene=21#wechat_redirect)》

0160-《[CDH5.14和CM5.14的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487265&idx=1&sn=d4d2eaeda0434c2e83b732241cc57162&chksm=ec2adf28db5d563e06dcc68198f86d45f492311063869728311842b72f6e7ecd7c4c38b3f255&scene=21#wechat_redirect)》

0216- 《[Cloudera Manager管理控制台](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488437&idx=1&sn=ce35a699b363cbbff7966bbd61e79d0b&chksm=ec2ac3bcdb5d4aaa5a07fee2f356690d63d90d823801503073dbc0aef435a4aa0a43081b8645&scene=21#wechat_redirect)》

0217- 《[Cloudera Manager首页](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488461&idx=1&sn=9259d9127ffd17a5e2a182a4ea4ba533&chksm=ec2ac3c4db5d4ad273a4c1caea387e54cb07316c71b29496e7a83ab8318609051e705938fe72&scene=21#wechat_redirect)》

0269- 《[Cloudera Enterprise 6 Beta发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489680&idx=1&sn=8a214d352972d930f2f4ef2502a141c4&chksm=ec2ac899db5d418f954b4c3a8089e6578b7e498965840d03de9d0a31999d512adfad84aa0a3f&scene=21#wechat_redirect)》

0274- 《[CDH5弃用的项目](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489917&idx=1&sn=035645ad4703bd93d79c062476793fd2&chksm=ec2ac974db5d40627c63a783d80963912e1ce1b36d06fbdc9681ee3d0cb454739e7ae081ac18&scene=21#wechat_redirect)》

0303- 《[CDH5.15和CM5.15的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490765&idx=1&sn=c976f5d5445290bb60644b6c9c23d808&chksm=ec2accc4db5d45d2c0851484d1e1df3be6885f7206c712f7573d96b03b86ee0bce1e67d42103&scene=21#wechat_redirect)》

0336- 《[Kudu1.7的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491475&idx=1&sn=e58736f1e06a3ac576e48d239220523a&chksm=ec2acf9adb5d468c678b983619df9279da8a1bd4aba9fe7fdc6cecf50e8f4a9d3c4d62b19605&scene=21#wechat_redirect)》

0365- 《[关于CDH相关服务启动用户的说明](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491993&idx=3&sn=9b189e480e8b15f7edb283e76185a14e&chksm=ec293190db5eb88699906fd4f6e554d15e67ba7ee3360d170d76d937b3334a53d863186dc6a7&scene=21#wechat_redirect)》

0376- 《[Cloudera Enterprise 6正式发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492195&idx=1&sn=000a802363af7a599b90745747eb98a5&chksm=ec29326adb5ebb7cac4ef40439d647b16d2f65ebdc7af71d1f5c6c1ad9c59c56c5e907fc3f1f&scene=21#wechat_redirect)》

0427- 《[CDH6中的第三方库](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493189&idx=1&sn=b022fa6ad6c2aec8197b2303375fcbc1&chksm=ec29364cdb5ebf5afd4dbcf6775d04b26c93733f45ff993c24b5955128514fa0da9b6d41ad9d&scene=21#wechat_redirect)》

0444- 《[Cloudera产品支持生命周期策略](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493479&idx=1&sn=3b2aa3b429a33fb8b296aef09b11fd7d&chksm=ec29376edb5ebe782ab15bdfb1195c2f06937ebaaf76cc6eddd8b084a95c7342e2ccca7162c2&scene=21#wechat_redirect)》

0466- 《[0466-CDH5.16.1和CM5.16.1的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494080&idx=1&sn=86bbb2da1cb184c1ecbfd9804ee43811&chksm=ec2939c9db5eb0df825ce68866a8d972fa60e88cceb6d9e4136f39accd119fad053028b25564&scene=21#wechat_redirect)》

0487- 《[0487-CDH6.1的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495158&idx=1&sn=db40f26a2b939699c01760a662b4986d&chksm=ec293dffdb5eb4e9e1e0d782caeee73703ad29d1c8b6d2c89951e186420021eb629fb5bc5252&scene=21#wechat_redirect)》

0488- 《[0488-Cloudera Manager6.1的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495162&idx=1&sn=90c466bc0574c3304b59fb5d66c800b0&chksm=ec293df3db5eb4e57b836f619748665d1fc5e5c0926e4e1df59d147dff66f5274cac08e46010&scene=21#wechat_redirect)》

0509- 《[0509-深入分析CDH的安装目录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495580&idx=1&sn=58b1b1d9496da9b77fb2d7a4fbaf5b94&chksm=ec293f95db5eb68384acd10811c693bd2caeea234a1be99ff9d49933ee2e59c9be0ce323a6cf&scene=21#wechat_redirect)》

《[0585-Cloudera Enterprise 6.2.0发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496913&idx=1&sn=afc27f70bd802fa5a5b514b75ed4652b&chksm=ec2924d8db5eadce801caaf96e9be068ce5fc68819bbe7b808996848efed2517b79cd2836262&scene=21#wechat_redirect)》

《[0589-Cloudera Manager6.2的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497005&idx=1&sn=d493ce20cf7a27b07294ac5e5df13557&chksm=ec292524db5eac32235160726330b92f51662028333b865a5b1ca94df96294ea41bf22c6554d&scene=21#wechat_redirect)》

《[0593-CDH5与CDH6对比](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497070&idx=1&sn=3002941ac8725605e66bf3f62b019859&chksm=ec292567db5eac719bed262ed4f59b3290b9404dddebcabb77ac7034234bf93bc865530f59e8&scene=21#wechat_redirect)》

《[0595-CDH6.2的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497136&idx=1&sn=96b394929868c9bbce4dfbee9da90dad&chksm=ec2925b9db5eacafeec9eaecaa66b9c3c79380d6cbeb1c7d4d5c99d3f386651020ccef39d07b&scene=21#wechat_redirect)》

《[0603-Cloudera Flow Management和Cloudera Edge Management正式发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497370&idx=1&sn=4f052178a61814c4980042dc75e85758&chksm=ec292693db5eaf852714e55925963a3c6731e4fced7369fdbdaa7afbed8779c8ca0b01568c33&scene=21#wechat_redirect)》

《[0667-6.2.0-什么是Cloudera虚拟私有集群和SDX](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498814&idx=1&sn=731d191844ece242f731b1851aa3bd99&chksm=ec292c37db5ea52138a372f3657722178ed0b3e89cc5b48ad7782ed2b0e9aa261c2955858e1c&scene=21#wechat_redirect)》

《[0682-Cloudera Enterprise 6.3.0发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499099&idx=1&sn=0d0310e6b4b49f6ce7f643d71c9ace02&chksm=ec292d52db5ea444bd8dc57215f4bafffb713d9b00d2a40945e28e0ebe1e33b1d3210012c8b9&scene=21#wechat_redirect)》

《[0685-6.2.0-什么是Cloudera虚拟私有集群和SDX-续](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499162&idx=1&sn=8f53eec3db94b1938d0a4636dc3244d6&chksm=ec292d93db5ea485e476ae2112a036d9f45e476cf9d1538ac76200e42394778cf6522e2735e6&scene=21#wechat_redirect)》

《[Cloudera Streams Management正式GA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499809&idx=1&sn=1174f03445ae77085c4cd9ae1a0bb5f9&chksm=ec291028db5e993e5237ca88f32fe4ed0a68ab1df358769e7639564c9b8a3e03dd4df60fe176&scene=21#wechat_redirect)》

《[0717-6.3.0-Cloudera Manager 6.3的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500175&idx=1&sn=513bfcd9da70a6d654602b77666967b4&chksm=ec291186db5e98901c5de719b025ad85866c20bff665719038ebbeb360863cfb8ffe6697e364&scene=21#wechat_redirect)》

《[0718-6.3.0-CDH6.3的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500179&idx=1&sn=a009d8ba63a2dcb36362f77129347bbf&chksm=ec29119adb5e988cd8ab6fc126c32023b9c1c4cd9ca51f0b8665889ad78318d69f837630dcfb&scene=21#wechat_redirect)》

《[0732-Cloudera  Data Center7.0今天正式GA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501132&idx=1&sn=1a77db8242470094cc5582d16d10ed29&chksm=ec291545db5e9c53496de16c4afb6c2dc542f0535d20adb172993c74092bed8985f1ec04a15a&scene=21#wechat_redirect)》

《[CSP2.0-什么是CSM-01](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501204&idx=1&sn=6851fd5a4253eb7ca3e31d9220aac787&chksm=ec29159ddb5e9c8bbad5fff2006c0ca26811769d6de22f2610f4cac1c3aedd689d31c7d84947&scene=21#wechat_redirect)》

《[0735-什么是Cloudera Management Service - 1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501227&idx=1&sn=e1bcfe9c7ffeb70d0209f3807476d5d1&chksm=ec2915a2db5e9cb4fce3f73545336652c11408fc633ba08932b86671b6a66595653726377f66&scene=21#wechat_redirect)》

《[0743-Cloudera Enterprise 6.3.3发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501349&idx=1&sn=514cd526a3ee03b951702ea9d14ab951&chksm=ec29162cdb5e9f3a5775b16df789085fd315545910c4e5c9cfd4c20e06141102d1516107078a&scene=21#wechat_redirect)》

《[0781-Cloudera  Data Center7.1.1正式GA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502397&idx=1&sn=8e8ede45b8b9bcb51617951662d9f4cc&chksm=ec291a34db5e93227f82efac16260ede1e249f0fb2b8ad6c992bf1bc93b36c8fbca7a064ec2a&scene=21#wechat_redirect)》

《[0802-Cloudera  Data Center7.1.3正式GA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502887&idx=1&sn=b8bf2d1f2222f4f0726a47e0f54ed8d7&chksm=ec291c2edb5e9538945374027c6eddf586f7c7f07d7b4fa20c3a36fa2ff2619b47f80d21bdf4&scene=21#wechat_redirect)》

《[0814-基于CDP7.1.3的Spark3.0正式发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503146&idx=1&sn=b5d084d0bb084ffa433092112291be51&chksm=ec291d23db5e9435f67b5c8fdbf3ed23ddfcd4fd9490c30c3c943ae43dab4c30a6a5d85e5fa3&scene=21#wechat_redirect)》

**3.2.扩容**

0080-《[如何在CDH集群中加入异构设备](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485756&idx=1&sn=11d28b87c73424478c7477bc6f111ffb&chksm=ec2ad935db5d502340945a7cffa5ea35589ec255b13e96d9dcace28c8ef168ea178316937a6a&scene=21#wechat_redirect)》

0089-《[如何给CDH集群增加Gateway节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485917&idx=1&sn=9e73e97029f58eeea004f5be4ffa45eb&chksm=ec2ad9d4db5d50c21bf967e835e963409c16e78bc2cbbda3c6a50d07f577532fd44d5fc9278c&scene=21#wechat_redirect)》

0110-《[如何给Kerberos环境下的CDH集群添加Gateway节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486320&idx=1&sn=9017f32f2e035fab859ba69392a8bf16&chksm=ec2adb79db5d526f6f7f122ea81ba622dd91d1ddfca7a6c2864cf73a6f861643812e2618b98f&scene=21#wechat_redirect)》

0112-《[如何在非Kerberos环境下对CDH进行扩容](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486394&idx=1&sn=bfd95038660b9974269b5718566da8ed&chksm=ec2adbb3db5d52a56138bf2ad731f7f8e4827c0de69e4a6d86bb2bd20974d423ec344cbe473e&scene=21#wechat_redirect)》

0126-《[如何为Kerberos环境的CDH集群在线扩容数据节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486682&idx=1&sn=de44a67e46af1d0debba4dfa40b6b5ff&chksm=ec2adcd3db5d55c5ed527a4b94f18fa0ccfa227219792b760f6a5eef964372eee43cd84747a9&scene=21#wechat_redirect)》

0344- 《[如何Redhat7的CDH集群中扩容增加Redhat6的节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491671&idx=1&sn=776fc70e872b8eb68c8bff37209c1c01&chksm=ec29305edb5eb948176211741e2c13331de06ef8ba9645ac4b452dfa14ed31cf8ecbf5e8fc5d&scene=21#wechat_redirect)》

0461- 《[0461-CDH6.0扩容异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493794&idx=2&sn=acc80c49f79905c70085aba7e3f4f4c8&chksm=ec2938abdb5eb1bd465ed1d6489244b05fb1810a9f1d970ff404f415021dc363f78a43e4ba8d&scene=21#wechat_redirect)》

《[0567-6.1.0-非Kerberos环境下集群外跨操作系统的Gateway节点配置](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496622&idx=1&sn=24dbb7d6383bf122c3646cc4fb3b8857&chksm=ec2923a7db5eaab118073df7e9ea37c0fcee5308baaebaac26ebf7fc832c6bbc2ca081fe65e7&scene=21#wechat_redirect)》

《[0571-5.16.1-Redhat7的CDH集群外配置Kerberos环境SUSE12的Gateway节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496694&idx=1&sn=ce073e647f19491f9a65a65634397d9f&chksm=ec2923ffdb5eaae9759cfaeb8ac3b6f61553781dd7e7131502c15803e9fb2e29cf836fa1e70d&scene=21#wechat_redirect)》

0297- 《[如何在CDH集群外配置非Kerberos环境的Gateway节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490591&idx=1&sn=d8da8404cffb1169a27892102f1cd598&chksm=ec2acc16db5d45007c0689a6062689070936f43ac278e869686a015806ed3cb93d53c585c2e0&scene=21#wechat_redirect)》

0306- 《[如何在CDH集群外配置Kerberos环境的Gateway节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490795&idx=1&sn=e17c0574c2c6a4a58256de1ba7ff83bc&chksm=ec2acce2db5d45f43902903b1e420576e5e552d5b3fd7fa7f5196d3b5dcab1fbbf84386a6096&scene=21#wechat_redirect)》

**3.3.减容**


0115-《[如何使用Cloudera Manager在线为集群减容](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486448&idx=1&sn=0925710214d7a215b233fcdf8c60fc95&chksm=ec2adbf9db5d52efc0f4a3634f2ac64f420a7d328c31cb1afd92c63d6c70d54a885f98dbb694&scene=21#wechat_redirect)》

**3.4.使用**

0003-《[如何在CDH中使用LZO压缩](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247483781&idx=1&sn=dadf927aacb0e93d9901c2ec0ee915a4&chksm=ec2ad18cdb5d589a5915e1591708f0b1c8ee323c407cbd3ffe62c11644300d19bfcc0e1861f7&scene=21#wechat_redirect)》

0036-《[如何通过CM API优雅的获取元数据库密码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484894&idx=1&sn=69fcd92cedec639197437f7b0daa3fc8&chksm=ec2ad5d7db5d5cc1f3b6825bd62e151aa7f821d505c4202595e113765148094615a86285b0bf&scene=21#wechat_redirect)》

0040-《[如何重置Cloudera Manager的admin密码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484965&idx=1&sn=f9a59d14351766f24081cd89a5307f64&chksm=ec2ad62cdb5d5f3aa8720086287f5ebd3b84d78d1b8fbca083de85c74c47362456245c0d6dd2&scene=21#wechat_redirect)》

0088-《[如何将CDH集群JAVA升级至JDK8](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485886&idx=1&sn=15ae709b285872f9b038a0011f703c26&chksm=ec2ad9b7db5d50a12f54d65a75561dca16e547ad8bc691c8658eb194993fe12f62808de9b89c&scene=21#wechat_redirect)》

0090-《[如何将CDH从企业版降级为免费版](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485942&idx=1&sn=33d7019db4b3b67cda064efe8452872e&chksm=ec2ad9ffdb5d50e934ad0de44568a067591a3672d0c833a9db95f277c7a74a30f87aa82068d6&scene=21#wechat_redirect)》

0091-《[如何将Kerberos环境下CDH集群JAVA升级至JDK8](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485967&idx=1&sn=eb23e9913f7298d37daf255625e54f1e&chksm=ec2ada06db5d531015e66dd6af30fd37a0be7869d23416482efe15c310bcaf2370f1ce57990f&scene=21#wechat_redirect)》

0096-《[如何使用Cloudera Manager启用HDFS的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486124&idx=1&sn=bb5fc5a1343176eacd694f0568437a6d&chksm=ec2adaa5db5d53b3e92c8a101a0efdecbf79ba5d29378c6eace46a4542f158aec049e505c0de&scene=21#wechat_redirect)》

0098-《[如何使用Cloudera Manager禁用HDFS HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486160&idx=1&sn=c1ffd55e0d5c8036591629cc7e7be22f&chksm=ec2adad9db5d53cf57e85f867050f581063180cb3b559ddbac8c444bc6fc934a5de86e209011&scene=21#wechat_redirect)》

0100-《[如何使用Cloudera Manager启用YARN的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486188&idx=1&sn=9568740650b3cb457f474cecc049ad95&chksm=ec2adae5db5d53f39e95d0d28f912a7575ee393bb6a9453cc3af25f71ecacf0a618208346011&scene=21#wechat_redirect)》

0104-《[如何使用Cloudera Manager禁用YARN的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486224&idx=1&sn=b59139109ce7f05c621e4ba83059be09&chksm=ec2adb19db5d520f0d2c2ce80bb166ba56d9dbaded0c75fdb7bcc397545f9105829f140cb47e&scene=21#wechat_redirect)》

0117-《[如何修改CDH集群的DataNoe节点HOSTNAME](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486485&idx=1&sn=d2bc57da0d0f4ece911554c7396c9a41&chksm=ec2adc1cdb5d550a56f0faf43f43d833f1076ad7458e50eaab9fca1a933b81a556d8b1037c14&scene=21#wechat_redirect)》

0163-《[如何修改CDH集群的IP地址](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487280&idx=1&sn=52e9fdc58a880c6450763831eee28225&chksm=ec2adf39db5d562feb479c3341916f73fa20df4510a2974be5ca96f4458a036dc66100ad357b&scene=21#wechat_redirect)》

0187- 《[如何降级Cloudera Manager和CDH](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487785&idx=1&sn=267ee966e531d68c7a2164d19494db93&chksm=ec2ac120db5d4836dde6f0625ba71eadcef87790aff10c6124e26f59c0062e1c6b19ed9cb61d&scene=21#wechat_redirect)》

0271- 《[如何修改Kerberos的CDH集群的HOSTNAME](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489870&idx=1&sn=aa876289f09916b14b8528f01b172c7f&chksm=ec2ac947db5d4051bacc8c7a93fb7daf0b4ccb0134933f43e65764b3ed87875c413b4d1afb33&scene=21#wechat_redirect)》

0300- 《[如何在CDH集群中为数据节点热插拔硬盘](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490670&idx=1&sn=3160c8469ee0b0984916282954365c92&chksm=ec2acc67db5d4571f648ca726d0cae5bb0f4c4a535af007a2ffd6f363e0c7b3033af92e70d5f&scene=21#wechat_redirect)》

0311- 《[如何在CDH集群外配置非Kerberos环境的Spark2和Kafka客户端环境](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490925&idx=1&sn=d447f08bcd5adc0b0ae6e25b502dd6dc&chksm=ec2acd64db5d447272a5f76c904a6c30df0d2002a013becf9cefdb924b9268fcfc3ec26b15da&scene=21#wechat_redirect)》

0314- 《[如何在CDH集群外配置Kerberos环境的Spark2和Kafka客户端环境](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490974&idx=1&sn=bda1eff02b0c7bcad17267f09f22a8b0&chksm=ec2acd97db5d4481ea66f197b11223bc13780464f8e94880671956ff183e4291c137320ab968&scene=21#wechat_redirect)》

0332- 《[如何修改CDH集群元数据库地址](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491423&idx=1&sn=fcab6050eab8832e3100b600061a3ad7&chksm=ec2acf56db5d4640af341aa85304678acff2167dbfddc23ea8a4fd7b3326b12f19e62612f14e&scene=21#wechat_redirect)》

0349- 《[如何迁移CDH的opt目录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491727&idx=1&sn=c11f9e1ef59bebe4d4db899c0b75d54c&chksm=ec293086db5eb990fd66a7ff09e8a9d0c4cbc083f822de29db840a11b6010beaa06af88afb2b&scene=21#wechat_redirect)》

0392- 《[CDH集群升级JDK8后CM服务的JDK版本指定分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492582&idx=2&sn=14a13dbb2ce62c8625e496c95e01d38a&chksm=ec2933efdb5ebaf99e5d5f963f50318608dd1227fce4fba0dc8b6d883289f8c4bb2fb5097058&scene=21#wechat_redirect)》

0400- 《[如何修改Cloudera Manager的时区](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492761&idx=2&sn=7419ad1720753a8229fb00d15aaf0335&chksm=ec293490db5ebd8617e86c814b6cfd391da1f9d93a00e097ef42730026cdb7b13f23323e5a56&scene=21#wechat_redirect)》

0442- 《[如何使用Cloudera Manger自定义部署Parcel包](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493458&idx=1&sn=d836f9fecd6423c9cc65edd965fad45a&chksm=ec29375bdb5ebe4d4d8974bc2612324761d699c589f804f614a8c25b90d729fc4b6a376aaece&scene=21#wechat_redirect)》

0446- 《[如何在Kerberos环境下修改启用HA的CDH集群HOSTNAME](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493547&idx=1&sn=fc1fe7440d516318822ee14a787aac1a&chksm=ec2937a2db5ebeb42bbcad288440ed45d4400474c858d0c4dd8e4c56b0449a5bd66a5504f2c1&scene=21#wechat_redirect)》

0449- 《[如何在Kerberos环境的CDH集群外跨OS版本中在指定目录配置HDFS的Gateway节点](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493592&idx=1&sn=4586cc11334416ea4943d68688eac2c2&chksm=ec2937d1db5ebec72f28256f766182852306cfce13e18e4a94ec33bddc0cb25daec0a2d4df70&scene=21#wechat_redirect)》

0456- 《[如何使用Cloudera Manager为Hadoop服务角色启用远程JMX访问](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493670&idx=1&sn=f10134bc886a27f26d56f6ef49d92bad&chksm=ec29382fdb5eb1397517244869a4fd96e4098043e5ef7c834a7a4fe245b998fb6da0c1c0f686&scene=21#wechat_redirect)》

0457- 《[0457-如何使用Cloudera Manager手动收集诊断包](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493687&idx=1&sn=15058f9abc0ebc939a87dd619b3b2c59&chksm=ec29383edb5eb128a596f79b132c0cfabb806aab6ce632dc3b6a2d94c933c01ee7fd03602f09&scene=21#wechat_redirect)》

0486- 《[0486-如何将Kerberos的CDH5.16.1从Oracle JDK 1.8迁移至OpenJDK 1.8](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495153&idx=1&sn=d0e6163f1e7083f955597ac483b0d9fa&chksm=ec293df8db5eb4eed03ea9d4ee7a8df2b00a46ec344412ed8e84285c0a01b78306d2c6566cfd&scene=21#wechat_redirect)》

0497- 《[0497-如何将Kerberos的CDH6.1从Oracle JDK 1.8迁移至OpenJDK 1.8](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495419&idx=1&sn=f37f2f64bac596d7cba7c949487e7eb1&chksm=ec293ef2db5eb7e4336833a183ccda1492c96c1fcba85421c575b942557dd64b3b6f269b996d&scene=21#wechat_redirect)》

0515- 《[0515-如何对Cloudera Manager的数据库密码进行脱敏](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495640&idx=1&sn=f5e0f66e2875c98a695f55d52b2e28ce&chksm=ec293fd1db5eb6c7a7065ce053c74084e2d3cef12642994d6f5212d31bc713e2d20d5e634588&scene=21#wechat_redirect)》

0517- 《[0517-如何在CDH5中使用单用户模式](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495673&idx=2&sn=b63dac4b6ea37f7c874d341948bfe3d1&chksm=ec293ff0db5eb6e6f7663f34ef80441f1691a4f739c7f8051600a6174e2d56ab5d1b6a993063&scene=21#wechat_redirect)》

0520- 《[0520-如何使用非root用户启动CM的Server和Agent服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495742&idx=1&sn=b48a045865d6199b93a264346bb2d625&chksm=ec292037db5ea92106835d94b27932340cf189e885456a867d5305a560a18bdcb412b80fe870&scene=21#wechat_redirect)》

《[0541-6.1.0-如何为Cloudera Manager设置反向代理](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496165&idx=2&sn=e5ce4b2a5751aafa50236d6f93b00b0d&chksm=ec2921ecdb5ea8fae63cd77f0a05f75b9faa15f7cc0638e3ff707080b34b6151142f0137cf6e&scene=21#wechat_redirect)》

《[0545-Cloudera Manager中Entryopy警告处理](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496227&idx=1&sn=d32d252f262385db7bd53d7ff80b233e&chksm=ec29222adb5eab3ccf20f4ba224bb4d66ab310b804cfa3943ada0f02f59acafc9619bc0daef8&scene=21#wechat_redirect)》

《[0546-6.1-使用Cloudera Manager API启停组件说明](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496251&idx=1&sn=8b3d931d47919b84034298700ca67013&chksm=ec292232db5eab2409156410a2282c2c1f7de4ac385669b463802a288870a17255f918f89d2e&scene=21#wechat_redirect)》

《[0547-CM Server和Agent服务停止脚本说明](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496259&idx=1&sn=6c4dc2e162052dde93c7038473a64cf2&chksm=ec29224adb5eab5cd4168e4f38361e334ab363d982245cb24b5ed99e9fac48ff6bf0e31daaba&scene=21#wechat_redirect)》

《[0548-5.13.1-如何使用普通用户管理CM server和agent服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496278&idx=1&sn=c2cdae51658128803d02eba2716bb27e&chksm=ec29225fdb5eab49a7436ebefe6c638b1cfea1d8239b8c2d664765546b425c09d6f5ae3dad1f&scene=21#wechat_redirect)》

《[0551-6.1-普通用户配置kill CDH集群进程权限](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496363&idx=1&sn=be3670675dfbeaf2471b71258e010b84&chksm=ec2922a2db5eabb44091af3d60f88872b28fb8f041effd7ba7527200888f5f0cd95ee79aa013&scene=21#wechat_redirect)》

《[0591-5.16.1-如何通过CM的API 获取集群告警信息](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497063&idx=1&sn=069320bc263e0735d145253069c0ed65&chksm=ec29256edb5eac78cc030c3bde0c2ac96f783f6933af65f662d496ad942baa90c5b921c247d8&scene=21#wechat_redirect)》

《[0597-5.16.1-如何在CM界面自定义图表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497210&idx=1&sn=4a7bfff163d20331a01479dc7a9f4489&chksm=ec2925f3db5eace58bc7d1a953e607c3800110c1d6d13ada048988672a8a1e3c4fec875d00c0&scene=21#wechat_redirect)》

《[0605-5.16.1-CM告警SNMP中DateAndTime类型解析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497408&idx=1&sn=a674e700ee45864948615fa8535a57b2&chksm=ec2926c9db5eafdf532fc553ea8cca385e2ca318c12f32b56ef0a17ec66ff23f1832bc98968f&scene=21#wechat_redirect)》

《[0629-6.2-如何使用CM API接口获取集群所有节点内存和磁盘使用情况](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497968&idx=2&sn=0c272f743794d00a2ec17b59c497a430&chksm=ec2928f9db5ea1efc2e5563932a99ce0c90d4f45140598b394d62a2782890ae3a16e4bbb2195&scene=21#wechat_redirect)》

《[0638-6.1.0-Cloudera Manager配置TLS](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498141&idx=1&sn=e6303c2c19777a073704b1e1691f179c&chksm=ec292994db5ea082b334cf445011b1afa322afc899d543bdbe9472a7f889d8956e03e3b8d222&scene=21#wechat_redirect)》

《[0642-6.2-如何在CM界面创建触发器](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498235&idx=1&sn=ff8f7a8a264ca5612ca2fd4a600d8480&chksm=ec2929f2db5ea0e439c6e010875a5d033fa7ccfd34b499a441f38d935db82333ca699e128a50&scene=21#wechat_redirect)》

《[0654-6.2.0-如何通过CM API获取集群事件并入库到MySQL](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498432&idx=1&sn=ae3a9ba36375894387efda636405f489&chksm=ec292ac9db5ea3df6f9d35927420ede584d74d1200379df31c2c03a95f564a028b84818e8657&scene=21#wechat_redirect)》

《[0707-如何安装Grafana并使用Cloudera Manager datasource插件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499961&idx=1&sn=8efbb2d0092b627448aafa8c0e0a3e08&chksm=ec2910b0db5e99a6d509c783fd13184b3587753c7c93da861dda8a25dca7a8a9268c992a1c4f&scene=21#wechat_redirect)》

《[0730-5.16.2-如何禁用CDH中的静态资源池](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501111&idx=1&sn=02ea2e8f5ddce20c87e0615c2a7b8a1b&chksm=ec29153edb5e9c28034bf81f7ba596aa081d961126e84a891611466845331d82500d15602b01&scene=21#wechat_redirect)》



**3.5.异常分析**

0023-《[HOSTS配置问题导致集群异常故障分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484385&idx=1&sn=9f78cecfd7430960af0e9f8027018a45&chksm=ec2ad3e8db5d5afeebda6d24a9cb95f83c444f1ed3d1aaaa3110b8b39ff39dfb279bbaaef8ed&scene=21#wechat_redirect)》

0034-《[CM启动报InnoDB engine not found分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484859&idx=1&sn=ef08edb6a30379b8297554fcaa69f329&chksm=ec2ad5b2db5d5ca430b83017ed8323f1b645ae27f4e738154682557aeee1252f6dd15d720c4b&scene=21#wechat_redirect)》

0044-《[CDH高可用集群误删NameNode故障恢复](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485038&idx=1&sn=89a425c250e8500d1a5e698438f0b69c&chksm=ec2ad667db5d5f71e2bf63f3a5a61e69c22b9f5da3105c5c7341b405418f814e006da3c8d629&scene=21#wechat_redirect)》

0086-《[Cloudera Manager Server服务在RedHat7状态显示异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485834&idx=1&sn=d93c2a3d407988c00063eaa2f721cc5f&chksm=ec2ad983db5d509521c420bcbdbf333bf3a8792bda31188bd82f7089b5509c0ad45d9c9fea51&scene=21#wechat_redirect)》

0170- 《[Cloudera Manager分发Parcel异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487430&idx=1&sn=a24ce6f41265134fa04364c9cbf8cb9f&chksm=ec2adfcfdb5d56d92be2e94fb7f9c9610d008a2db920d25c4d40a98168e2f6091454d58eb337&scene=21#wechat_redirect)》

0196- 《[CDH内存调拨过度警告分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487957&idx=1&sn=fa0e6201ad4183d4f4ed5ecfc8b5ee93&chksm=ec2ac1dcdb5d48ca9b9e1ccc30b61b9536ec39244dc6d7acf2a453d96f33e9055b225a4336f8&scene=21#wechat_redirect)》

0350- 《[Redhat7.4安装CDH6.0_beta1时分发Parcel异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491764&idx=1&sn=14c1f412f1897761bec7ee5bcf221a7f&chksm=ec2930bddb5eb9abff172473430a3c65144434c4997b11db72b8225e876fad73afd76ee64fd1&scene=21#wechat_redirect)》

0378- 《[Cloudera Agent服务异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492268&idx=1&sn=57c6cd17d5746a766d571cd42f0d2dfa&chksm=ec2932a5db5ebbb360e2a316765921bc40bb8e054b5750e84b07c296b7e9fddb16df7bb9b770&scene=21#wechat_redirect)》

0379- 《[CM部署客户端配置失败异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492282&idx=1&sn=1c9b4632d4a3d6814c45688783738bcd&chksm=ec2932b3db5ebba5540289339f4d7ce4201f53bd14cde2abf29153d8c25b308506516abb4dcd&scene=21#wechat_redirect)》

0476- 《[0476-Cloudera Agent服务tmpfs文件系统cm_processes空间不足分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494572&idx=1&sn=e6354a9a382cff8478879535810a24b3&chksm=ec293ba5db5eb2b3299c6626cebb89b06c64ae5faaa5520e2023a41680164a96da5e0f278d64&scene=21#wechat_redirect)》

0519-《[0519-如何解决Cloudera Manager主机页面出现重复主机异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495722&idx=1&sn=1bdb299284332be0fbcd5faa8fd30462&chksm=ec292023db5ea9355cbbc158e9d838118996f3d3282609fc1eac15e23335350696a432aacf43&scene=21#wechat_redirect)》

《[0565-6.1.0-NFS异常导致Host Monitor及Agent服务错误](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496587&idx=2&sn=b24bbbd2f29c7cb9b451a5e333e50e60&chksm=ec292382db5eaa94a09365e0b6dd1b89a59f61f0441278a78ef7740e040b78448b8dd0ebd396&scene=21#wechat_redirect)》

《[0577-5.16.1-使用Cloudera Manager配置自定义csd目录异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496806&idx=1&sn=09e64a598866ef767742f3f70a630935&chksm=ec29246fdb5ead791794e56368072b4182796852d67083b4598e791c5d0eaa29c30b535339d0&scene=21#wechat_redirect)》

《[0587-6.1.0-CM 管理界面中Impala 的查看SQL查询详细异常问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496984&idx=1&sn=73989ab27a2327d00c586aca8611011b&chksm=ec292511db5eac0770a28a54a80aa436feb68a967333a83dbaa916951aa350ec0fb01b7239dc&scene=21#wechat_redirect)》

《[0601-6.1.0-解除授权后的机器重新加入集群异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497349&idx=1&sn=16957cb539754f3148a59fd90e3d5cee&chksm=ec29268cdb5eaf9a59c95665ecc8d86707dc86049a5d2d6b8aa62b2862f79facf436b8af98fc&scene=21#wechat_redirect)》

《[0615-5.16.1-如何修改Cloudera Manager中图表查询的时间序列限制数](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497654&idx=1&sn=c23cb50f11dbfee783b98409f0148d18&chksm=ec2927bfdb5eaea9d5d498bb73ff86f85f7e9076986e70f14512e3b7af744dd2e5057b2ddb5d&scene=21#wechat_redirect)》

《[0637-5.16.1-CDH集群中var目录占用空间大问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498070&idx=1&sn=617b8f581bf3eaa30a59267555dad138&chksm=ec29295fdb5ea049b1f20e858d8acbee88fa07ede031f0cbec5e664b05ab0d1d835ba3a9abb0&scene=21#wechat_redirect)》

《[0669-6.2.0-集群中部分节点hadoop命令无法使用问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498854&idx=1&sn=14917062c2b75320756bf7bc9601a251&chksm=ec292c6fdb5ea5794c9e2df06d8be625cbb67b20a78947ccfa8cabfcdce46994845a99debb6d&scene=21#wechat_redirect)》

《[0705-5.16.2-HDFS文件浏览器异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499883&idx=1&sn=d78bb02c6b3cc91700317b58d1a94e5e&chksm=ec291062db5e997494e7699791fec48ace930976f82ff250ab522efefd642fe2fdc5867dc88e&scene=21#wechat_redirect)》

## **Navigator**

**4.1.Navigator安装**

0197- 《[Cloudera Navigator介绍与安装](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487976&idx=1&sn=76c5f7ceb1fb30d839d62ef0a25d2960&chksm=ec2ac1e1db5d48f7ff50545e01d793bd8da3382a566b76805275b12209cd681c66fdb8ef2ac3&scene=21#wechat_redirect)》



**4.2.Navigator使用**

0203- 《[Navigator的使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488174&idx=1&sn=9833a4a6e7c48a1f7ded9f998d320122&chksm=ec2ac2a7db5d4bb1045fa13f6444f54cb85532031b97b87389313111835dc0b45295c10f358b&scene=21#wechat_redirect)》

0205- 《[Cloudera Navigator异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488207&idx=1&sn=fe765d6bb8b6e1b6f4909f1996843fe1&chksm=ec2ac2c6db5d4bd04dbfbbe962e48f39f3f8a3402209ffa702bb3210291acb94b4749baf5ca4&scene=21#wechat_redirect)》

0396- 《[Navigator发布审计数据到Kafka并使用Flume入HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492669&idx=1&sn=518df4b56634da7fdb6b33681bc26d41&chksm=ec293434db5ebd22e2571377354746e15045ab327497c43c4c67ff7b51e84c8a024b3e1a3b87&scene=21#wechat_redirect)》

0399- 《[如何合理的设置Navigator Metadata Server的Heap](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492751&idx=1&sn=805ff10e0d5e90ba55252cb6a70b818a&chksm=ec293486db5ebd90fbdf1355983aa7ba803675d9a76c4db50e4562e027f9c3f6037ba55963b7&scene=21#wechat_redirect)》

《[0655-6.2.0-CDH6.2安装Navigator无法访问异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498444&idx=1&sn=e287b0beb29f9295e30859c23c44fd7f&chksm=ec292ac5db5ea3d3f065a8f432a56c310c505bc833deec541d78cdf3a4d3825ce4ebe3f059ad&scene=21#wechat_redirect)》

《[0698-6.2.0-Navigator审计日志查看对应用户的操作](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499752&idx=1&sn=4c709837f8e3593aa5a83f22dc159b0e&chksm=ec292fe1db5ea6f7ae5e2c6be4c9e919708568aacbb42950b020ae3f3a8188af2234c7845441&scene=21#wechat_redirect)》

《[0771-5.16.2-如何关闭Navigator的审计日志功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502138&idx=1&sn=7cc70df97e80c01d6e0291225071d73c&chksm=ec291933db5e902532c6febf2e8e0a57460cba2b05eaad7ff23614043bff596317a647b6ed94&scene=21#wechat_redirect)》

## **数据科学**

**5.1.基础环境**

0012-《[什么是数据科学工作台？为什么数据科学家需要它？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484180&idx=1&sn=76e859f93fd8c25ce08de2589dea96da&chksm=ec2ad31ddb5d5a0b311fba0193b24605b61d712b86cfd6eb48c592d181c602655fcd8447419b&scene=21#wechat_redirect)》

0038-《[如何在CDH集群安装Anaconda&搭建Python私有源](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484963&idx=1&sn=3fbfcecc6c80be41538437fa046cac83&chksm=ec2ad62adb5d5f3c4825415472a3f30c3be62da2259d25aa721f95e74c17955f94c4be8e1852&scene=21#wechat_redirect)》

0049-《[什么是sparklyr](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485126&idx=1&sn=676f4bbfe8b6e000e02f7176f913cb23&chksm=ec2ad6cfdb5d5fd9f85f88e462cf187262e44e6c0be3e78a4f0fbc7b189e54461a851c45336b&scene=21#wechat_redirect)》

0050-《[如何在Redhat中配置R环境](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485165&idx=1&sn=609644a6118481ec09b6be036e20e0e6&chksm=ec2ad6e4db5d5ff2b0bba4c85cdf838feeb56e31d50250ac095e4e7fef871b624a7512a8bb1c&scene=21#wechat_redirect)》

0051-《[如何在Redhat中安装R的包及搭建R的私有源](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485176&idx=1&sn=cc846c81d4f701c07144f566ae2ef72d&chksm=ec2ad6f1db5d5fe79a5cf632e0fa66d19518d36ac399d658bcaab2211e0e5020edc2d00f8923&scene=21#wechat_redirect)》

0052-《[如何使用R连接Hive与Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485199&idx=1&sn=cef0ced75ff7727c6a9b7c7289dd84db&chksm=ec2ad706db5d5e1009a337368e8ee8a56c7a121e297efcfc98e026cdba6d8fd3cc3712ab7046&scene=21#wechat_redirect)》

0057-《[PySpark数据类型转换异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485229&idx=1&sn=2e0c485de52499919398b90277a01e48&chksm=ec2ad724db5d5e32ae725b8a1760962c495a56193f836aec519540d5a97503da626fda112f80&scene=21#wechat_redirect)》

0118-《[如何在CDH集群上部署Python3运行环境及运行Python作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486512&idx=1&sn=1c90ba2b5812bcdae79279e8283367d4&chksm=ec2adc39db5d552f88909c2d149f99301ad1b0a3d70466ecf0709ef811c74cbbcb1d5f2d9177&scene=21#wechat_redirect)》

0334- 《[CDH集群升级Python3异常问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491452&idx=1&sn=44242b766bb85ef0bd1dc3b5cde7821f&chksm=ec2acf75db5d4663efb3d4e7f88139b27ac3177d7a081e978ea68725d8247880780be285b328&scene=21#wechat_redirect)》

0339- 《[Python3环境通过JDBC访问非Kerberos环境的Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491597&idx=1&sn=e57c0a370da85b590cba389713d7e338&chksm=ec293004db5eb912698941220d77f4ca14ce2bc51cb35573caf8ab1990a480a0560c554b6a5a&scene=21#wechat_redirect)》

0340- 《[Python3通过JDBC访问非Kerberos环境的Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491607&idx=1&sn=811e207bfeb6bad316b77b70afe7258d&chksm=ec29301edb5eb9086110a9760c179ee064f3f6a1d1cfe7c900090a75023b90dcb1150a4a9e02&scene=21#wechat_redirect)》

0473- 《[0473-如何使用Python3访问Kerberos环境的Hive和Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494434&idx=1&sn=3ae33ee6272410971515221c0e630cd2&chksm=ec293b2bdb5eb23dbc579e3ac454a2d9a103bca3fccdd684eb14f74bfa96d696f3cbc8103cc3&scene=21#wechat_redirect)》

0490- 《[0490-如何为GPU环境编译CUDA9.2的TensorFlow1.8与1.12](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495202&idx=1&sn=d8265a37c930d99d2ee1c17b53bd4abb&chksm=ec293e2bdb5eb73d194ada562d888465fa5ff9d59a675f233f0a4c1bbd77fe35ada01286b119&scene=21#wechat_redirect)》

0499- 《[0499-如何使用潜水艇在Hadoop之上愉快的玩耍深度学习](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495461&idx=1&sn=412b1c6c4e20f05de1c399054a1e80ef&chksm=ec293f2cdb5eb63a0c2a0a3889429505797be52891dbead25809f89710f7b0e913da8b04ca42&scene=21#wechat_redirect)》

《[0570-如何在CDH集群上部署Python3.6.1环境及运行Pyspark作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496668&idx=1&sn=4461854378270ea0741e91047a541b9b&chksm=ec2923d5db5eaac30108f19e44ea763ea6e06f26089437ef9b6a1f44204ed1e259efd2fc59ef&scene=21#wechat_redirect)》



**5.2.CDSW**

**5.2.1.安装/升级/卸载**

0037-《[如何在Windows Server2008搭建DNS服务并配置泛域名解析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484962&idx=1&sn=8ff9542fa7359a8752c4460c699efd97&chksm=ec2ad62bdb5d5f3d3cb1305dd0b52433fd3174243ca40d495a5adb57d2fabaa27ed3844f25fa&scene=21#wechat_redirect)》

0047-《[如何利用Dnsmasq构建小型集群的本地DNS服务器](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485109&idx=1&sn=3d5a8e35e72468fcf2857d76903c85f3&chksm=ec2ad6bcdb5d5faab9c20baa96e55b98ca891398b084c5a46aeebefbc6994a9e518b68bb9685&scene=21#wechat_redirect)》

0077-《[如何在Windows Server2012搭建DNS服务并配置泛域名解析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485679&idx=1&sn=c641d6f5fa5da2ed897a4e04d641bfb8&chksm=ec2ad8e6db5d51f0791f0d3aadc30a9a8edf6be4050ecbbad260a8efa21b49549ac9c29dbcef&scene=21#wechat_redirect)》

0078-《[如何在CDH5.13中安装CDSW1.2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485710&idx=1&sn=eedcbbf0fe26e97bfbf59aaf08cd8151&chksm=ec2ad907db5d5011dfab0b8b99b556a61492a45e20ef95c5dbde402d0f55748ff8c9deecf0dd&scene=21#wechat_redirect)》

0172- 《[如何在RedHat6上使用Bind搭建DNS服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487475&idx=1&sn=27fd1b2a05c28b11d646447b3917fc8a&chksm=ec2adffadb5d56ecde23360f42eea54cf879ccc6ef30ee6197195ebddb279b6770c2bedf69e6&scene=21#wechat_redirect)》

0174- 《[如何在RedHat7上使用Bind搭建DNS服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487533&idx=1&sn=2e89de7b54e3569167f24269690b444f&chksm=ec2ac024db5d49321393f8adf14e2cf4e476f329680854c3b73ca0a6c4fc2ae6d36a1199bec6&scene=21#wechat_redirect)》

0323- 《[如何在CDH5.14中安装CDSW1.3](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491255&idx=1&sn=34ba394dd86062c219e57b0438a9e25c&chksm=ec2acebedb5d47a8d0f58bcf13d51b48848ae85e62bf7ee2ce359c0cced027342c0f22588a56&scene=21#wechat_redirect)》

0325- 《[如何在CDH5.15中安装CDSW1.4](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491312&idx=1&sn=33c8a1e61ba350118abc8f0dc83062b6&chksm=ec2acef9db5d47ef53763921624e3221589d89dee960869fe3818cf4b1e5822652f37bda4d8e&scene=21#wechat_redirect)》

0390- 《[如何通过CM升级CDSW1.2.2至1.4](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492551&idx=1&sn=4337711b40c9f6d826b5f2c0e38e4a8d&chksm=ec2933cedb5ebad89306a233753893649207d838956ff36058fc88f2963a7ed5845ff334e59a&scene=21#wechat_redirect)》

0478- 《[0478-如何在CDH5.16.1中安装CDSW1.4.2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494715&idx=1&sn=e35dbaf8748ca3b86e16c25a3b9c85e8&chksm=ec293c32db5eb5243adc31202cf6207f18e6fc8ff2b24cfb173d2ddb014ce019dd2503c3eff5&scene=21#wechat_redirect)》

《[0573-5.16.1-如何将CDSW从1.4.2升级到1.5](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496750&idx=1&sn=24d19db104e9d0b59b0916b2d6b00789&chksm=ec292427db5ead311db696440c7e822bf00088b2ce04b571fd1c1dac92f4947828ce2f582b47&scene=21#wechat_redirect)》

《[0574-5.16.1-CDSW1.4升级1.5版本db-migrate镜像启动失败问题解决](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496766&idx=1&sn=fc269b97e6eb4d0c9042e820df54da13&chksm=ec292437db5ead21013342e7d23804005ffc761aabe78509bfb7249bef3aeb7590520f5ec473&scene=21#wechat_redirect)》

《[0584-5.16.1-如何卸载CDSW1.5](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496908&idx=1&sn=a3ba53cbb533871c462377eaad9fee2a&chksm=ec2924c5db5eadd3c222d542193ff74194bdc1effdf685bf75d383955671251f7aad39d0e557&scene=21#wechat_redirect)》

《[0586-5.16.1-如何在CDH5.16.1中安装CDSW1.5](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496958&idx=1&sn=d15c3bc68b1ae114e2105f7e1367a34a&chksm=ec2924f7db5eade1c0ef0653875e356e5706d794fff81e3257733020c8120225afc1583f0610&scene=21#wechat_redirect)》

《[0600-6.1.0-如何在CDH6.1中安装CDSW1.5](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497324&idx=1&sn=229e06e5c2b4b3db1e86cee48cf152f0&chksm=ec292665db5eaf73070bd67993b8d0b5a2de27b8b2a4f3154d122ebf77b77da06952a4d62d68&scene=21#wechat_redirect)》

《[0602-6.1.0-如何卸载CDSW1.5](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497364&idx=1&sn=22e9f6a4056cf991adf935745f7bd555&chksm=ec29269ddb5eaf8b9211dfd2db13e7640daa6e31ef21340a769fc1b58470c18b9b0aa35df0aa&scene=21#wechat_redirect)》

《[0666-6.2.0-如何在CDH6.2.0上安装CDSW1.5](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498806&idx=1&sn=1b75554bdc16b8be417f49f6140c9f1f&chksm=ec292c3fdb5ea529c23c1a8975989f83d042791baf370209a75114917a7f8d7c292c1f18d694&scene=21#wechat_redirect)》

《[0668-6.2.0-如何在CDH6.2.0上卸载CDSW1.5](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498834&idx=1&sn=aca5be8475ebc527e50b6065b10d128e&chksm=ec292c5bdb5ea54d1d5d49ea2da82ffa9557bd328b38ecc0e11d1d467bfa4323f62c402f9674&scene=21#wechat_redirect)》

《[0774-5.16.1-如何将CDSW从1.6升级到1.7](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502198&idx=1&sn=5e3435fa50d73693945cc42f35e0ccc1&chksm=ec29197fdb5e90697ba9b5489670f052315ab11a4652bd262a2f5b20fb267ca0eac8dc459683&scene=21#wechat_redirect)》

《[0776-6.2.0-如何在CDH6.2.0上安装CDSW1.6](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502266&idx=1&sn=e5a67295e845f1ca72bb225ad36ad17a&chksm=ec2919b3db5e90a5859860c580d7711cc255991b856ffda7436e110e7c60dfaa61e9fc9d322f&scene=21#wechat_redirect)》

《[0820-CDSW在Session中运行代码超过一次就报错问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503264&idx=1&sn=9ea6bf380d7ecdc1cf33a595bf8be99e&chksm=ec291da9db5e94bf7b043bf12f0b5027d73b9d354928234e95908845d4d8db5a4d87d9eb4f43&scene=21#wechat_redirect)》



**5.2.2.产品介绍**

0063-《[CDSW1.2的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485332&idx=1&sn=98a60bdedce8564b803d6e1332337177&chksm=ec2ad79ddb5d5e8bbcbda60c74a052d2fcdd64b58770db7f8399630e210ec50a144e54ec2a98&scene=21#wechat_redirect)》

0165-《[CDSW1.3的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487330&idx=1&sn=9411766eeb1c4436035fe7d8a9bcdb91&chksm=ec2adf6bdb5d567d06ff59d83808a705d6421bdee5947a35600ea64d21e79169c9c1ca9cef75&scene=21#wechat_redirect)》

0304- 《[如何在CDSW中使用GPU运行深度学习](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490770&idx=1&sn=72510ab1f8a28550b359e60d9502bfce&chksm=ec2accdbdb5d45cdf7481584df243aa96db41ce49015e4cf7ca6514e9298afcf5c7d1e760abf&scene=21#wechat_redirect)》

0313- 《[CDSW1.4的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490946&idx=1&sn=9c0c5d7e97e19bffe345be0d00cff6b1&chksm=ec2acd8bdb5d449d12b2ab6bdca858155634a66194f74fd897fb7fdce8f3f4ab7a6f0f1f8658&scene=21#wechat_redirect)》

0355- 《[Hadoop之上的模型训练 - CDSW1.4新功能模块](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491833&idx=2&sn=744a4e93b97710b0bedbb73057a8be2b&chksm=ec2930f0db5eb9e6913e0f94f5e61f469775f7281791a6bce1c162f9120e7653450c1711394f&scene=21#wechat_redirect)》

0357- 《[Hadoop之上的模型部署 - CDSW1.4新功能模块](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491860&idx=1&sn=758465807819730053a5b0a0905f2a00&chksm=ec29311ddb5eb80b11baf2e147e33e55143951df251bf36cc6bb5fea4291f9c010bd6c45033a&scene=21#wechat_redirect)》

《[0544-CDSW1.5的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496217&idx=1&sn=4b1b33ae58310ae817642618ded79da7&chksm=ec292210db5eab06f8666d749a30675b188f147bbe5fcae26738e30aee924afa8084031c29f2&scene=21#wechat_redirect)》

《[CDSW1.6的新特性](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498707&idx=1&sn=8e86a04e748000136ef02d796b764e7a&chksm=ec292bdadb5ea2cc9502dd012b60592e5baa0268091469856381552e49549fd5083d20079f2a&scene=21#wechat_redirect)》

《[0677-在CDSW1.6中使用你喜爱的编辑器](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499024&idx=1&sn=29a51da399ddd0eb6a79e05859956b5b&chksm=ec292d19db5ea40ffc74ce3d81f9d4eedb8395daee114c28f6ecfddde6232f34a7f33a3d2ae1&scene=21#wechat_redirect)》

《[0716-1.6.0-CDSW1.6的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500170&idx=1&sn=d04e1f88005662b0c74ada16c611284a&chksm=ec291183db5e98951f090b8190fb43a3d750e1554d6e6cad6f95265e34a991bd0fe5d47a4076&scene=21#wechat_redirect)》

《[0773-1.7.2-CDSW1.7的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502158&idx=1&sn=738daaec5eb004d1d49a30c6822cb26f&chksm=ec291947db5e90512794c19c6c7dc26dfb5964245b428e69aeeb135802b214289987ffb520a9&scene=21#wechat_redirect)》

《[0799-1.8-CDSW1.8的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502838&idx=1&sn=b6cd8d4f986043a93c4640f083334b3f&chksm=ec291bffdb5e92e94f8767014749895b67436415af36a197f5053da42473fcfc2e8abc7b1498&scene=21#wechat_redirect)》

《[0815-CML中的模型共享和MLOps简介](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503165&idx=1&sn=ca9faa8b063ea7170445e903c0bf44a1&chksm=ec291d34db5e94220a06c46a80c52ca8fb92ae46e4aac39aec947da6597194e17c1125bb1429&scene=21#wechat_redirect)》



**5.2.3.使用**

0042-《[如何在CDSW中使用R绘制直方图](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484991&idx=1&sn=c0b40a128650f29337f7da00042657d3&chksm=ec2ad636db5d5f206a50a04e6c7d97781587fa57cf2c434d2a1e6d2e68fa059f449673c8b250&scene=21#wechat_redirect)》

0054-《[如何使用CDSW在CDH集群通过sparklyr提交R的Spark作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485219&idx=1&sn=b58d5dc9422b49dedb60882b4243bec1&chksm=ec2ad72adb5d5e3c237489db13fbd976f4798b1f161c6b82bc8aa45caf8e2ddc6366fea9ef7e&scene=21#wechat_redirect)》

0055-《[如何使用CDSW在CDH中分布式运行所有R代码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485227&idx=1&sn=8873abfeddc8f3c04a4b640baa955a65&chksm=ec2ad722db5d5e34897733bfe0e405665c14f87ac733c577ba4ac366f576a4c1824f970d8206&scene=21#wechat_redirect)》

0059-《[如何基于CDSW基础镜像定制Docker](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485304&idx=1&sn=96a6e7c66c20c04ec74eedf92b23daf8&chksm=ec2ad771db5d5e67688044a007588413f4c7a9032a20069fb35767b1759ef8b2687eae3c0ce9&scene=21#wechat_redirect)》

0151-《[如何使用Nginx实现CDSW的跨网段访问](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487119&idx=1&sn=034fd8c0571547a437546c6ca1462c78&chksm=ec2ade86db5d5790158cc4fbff98d73f31cd1a048194e56ddf20af182553931cb9ca1f79d7be&scene=21#wechat_redirect)》

0156-《[如何修改CDSW服务的DNS和HOSTNAME](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487173&idx=1&sn=fadd5d8814fea44314af54a93f4d0459&chksm=ec2adeccdb5d57da9928c2fe5bc620fbeee39c551b1280f17cdf5bb7534bf1fd6e889f765fe3&scene=21#wechat_redirect)》

0159-《[如何在CDSW上运行TensorFlow](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487255&idx=1&sn=27c80ed149d05913a6b696f281f66d3e&chksm=ec2adf1edb5d5608c418aeb0bcd9d249462d8bedb14a963e303d7ad57bd929fda98a9f841f71&scene=21#wechat_redirect)》

0161-《[如何在CDSW中定制Docker镜像](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487266&idx=1&sn=af6f9cea810b1add3d01f78231b55eee&chksm=ec2adf2bdb5d563de2fccde915b6a75e43acc63303cce6dbd5a4e7ed494d221a12e97d844ad5&scene=21#wechat_redirect)》

0175- 《[如何在CDSW上创建Git工程](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487569&idx=1&sn=07e5cb5c2a262a72a2fbae5b5d5393fe&chksm=ec2ac058db5d494e357e8f54f85aa04c2715574f76f312a650122b129a014785dda5fd5ad3bd&scene=21#wechat_redirect)》

0265- 《[如何在CDSW上创建Git工程并提交代码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489629&idx=1&sn=2578aca6f9bbe5d6a2aeea1872ceb49c&chksm=ec2ac854db5d414287cde21c4e08968652d15e095d91db37bf699b11bf1e10730f40f127f988&scene=21#wechat_redirect)》

0327- 《[如何在CDH中使用PySpark分布式运行GridSearch算法](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491339&idx=1&sn=0c639f2f7901fc3cd8d79953e4cc6c0f&chksm=ec2acf02db5d46148af82b724e8c8c27c16491df4fb877265ab0f9df03b9f930436336ce7434&scene=21#wechat_redirect)》

0331- 《[如何在CDSW上分布式运行GridSearch算法](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491400&idx=1&sn=306a79f7c6bdd86a825b81fdc0dd5676&chksm=ec2acf41db5d4657dad052be2f77de61dd8da902551f9ff10eee7640a302cdab3fa41e194cfd&scene=21#wechat_redirect)》

0333- 《[如何在CDSW上调试失败或卡住的Spark应用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491436&idx=1&sn=3c2b5259d9a5137afb7e9a643cc49814&chksm=ec2acf65db5d4673c342a759a9da0128f8faf7d1f17cbc340aafb8000e5a9644e67cf211e46c&scene=21#wechat_redirect)》

0347- 《[后台查找CDSW中用户的审计日志](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491708&idx=1&sn=0ed8d8ef39b96fe8bbb23ecebd62d97c&chksm=ec293075db5eb963957e1012fd973d1d2a33c3161616000b43326c5b4be3929397e561b750c2&scene=21#wechat_redirect)》

0350- 《[如何通过CM将CDSW从1.3升级至1.4](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491795&idx=1&sn=63ac142824eb4e5adb2da508925d14ec&chksm=ec2930dadb5eb9cc2ab1b71a73a2c6ca8357058ee0ac06c32dab47dde6b479673595c4432e0e&scene=21#wechat_redirect)》

0356- 《[CDSW1.4的Experiments功能使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491849&idx=1&sn=0dcc52377a65c3e0a3c7e9859a294bdb&chksm=ec293100db5eb816f4d712ca24b3d9e0ebbbf2c1c8348e0561c7e98be2cca6dfae1cfc225dec&scene=21#wechat_redirect)》

0358- 《[CDSW1.4的Models功能-创建和部署模型(QuickStart)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491879&idx=1&sn=2dc84c5b272bf42190df334116f6d91a&chksm=ec29312edb5eb8387883a6a004936daeeb4a0bdba09c5a422e3f87fa0c6e349b8994899d5f78&scene=21#wechat_redirect)》

0359- 《[模型训练和部署-Iris数据集](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491903&idx=1&sn=94149f9f5af93bf34a69e393948d903e&chksm=ec293136db5eb8203186e848466333b5060112c5ca806c709f845f33c12f90105af90852f003&scene=21#wechat_redirect)》

0393- 《[如何为CDSW的数据目录扩容](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492621&idx=2&sn=d6121143d3f01267676a427ecbdb340c&chksm=ec293404db5ebd12554e73a5ec153b3fa3131ffb84adea721c7fb151359698cc4dfa56b64b25&scene=21#wechat_redirect)》

0430- 《[如何修改CDSW会话的时区](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493280&idx=1&sn=a4e8893d1557832f66ac59e3ee53f51a&chksm=ec2936a9db5ebfbf3a6c80e40674d3f4321efc565f5854f455f310f8817d435bfdbd3d567a93&scene=21#wechat_redirect)》

0489- 《[0489-CDSW中用户Session访问外部数据目录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495176&idx=1&sn=ee4ca0d91e2f6dca6f4472492c544304&chksm=ec293e01db5eb71768fc88c59260805ae1cc89f96333c9c2efb1eb6c3bbd539c4c9855f0be80&scene=21#wechat_redirect)》

0502- 《[0502-CDSW中访问Kerberos环境下的Kafka](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495504&idx=1&sn=ec4ecd2338b53831a7f2500a6a4b56ca&chksm=ec293f59db5eb64fd6a3da2cf40f545315ad98bd982f1b04360d3a15ee6540070c8cb32bab2d&scene=21#wechat_redirect)》

《[0580-5.16.1-通过CDSW API获取所有用户的Project详细信息](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496848&idx=1&sn=c7fbf1c9d81e0e66fc2493fc73bfed6b&chksm=ec292499db5ead8ffa00a01cfe579d90aa514edd8185900c4a0f32bb55a28f8d965d42d2490c&scene=21#wechat_redirect)》

《[0581-5.16.1-关于CDSW监控指标API接口描述](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496860&idx=1&sn=5670ec51c30426fd99b4d1e049cef4ad&chksm=ec292495db5ead83aa1ec4ebc6315ff2434fb2d1473359c7eb79bb3a61ddea00648b9f5e4291&scene=21#wechat_redirect)》

《[0582-5.16.1-1.4.2-后台脚本无感知为CDSW用户绑定Kerberos账号(keytab认证)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496872&idx=1&sn=2fd54248b86ebb0c36a8641c38de8a73&chksm=ec2924a1db5eadb7344b981dc228912b7084d28a9a1bf6d292c7ab80136d295f34450adddd1a&scene=21#wechat_redirect)》

《[0583-5.16.1-1.4.2-后台脚本无感知为CDSW用户绑定Kerberos账号(密码认证)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496887&idx=1&sn=bade444d4fe9a8b7e6ca0c3b860f344a&chksm=ec2924bedb5eada83f88e4d35ac1bf9ab0af669821655d3daf714f9092e58cea176b664c84fb&scene=21#wechat_redirect)》

《[0646-6.1.1-如何查看CDSW中其它用户创建的Public工程](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498332&idx=1&sn=29fcca1b1fa4f23f9aab2228cfd033a0&chksm=ec292a55db5ea343b49671647d45ffcd28b45faa62e874bf02c8e2722f619dbb4c0fb53f1f07&scene=21#wechat_redirect)》

《[0649-6.1.1-在C6集群中CDSW的Terminal执行hadoop命令异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498372&idx=1&sn=57a1d5748829efb9bb519a43072c1cff&chksm=ec292a8ddb5ea39bf12a3a52e3060d14382b5abbd3f7f574e288fe1e89084d739bc876646789&scene=21#wechat_redirect)》

《[0662-6.2.0-CDSW集成Active Directory后登录异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498697&idx=1&sn=b32886cb3c6f837e79dd3751f1d05e27&chksm=ec292bc0db5ea2d6a5c4743ca294cfd381ecb20413a2482c46f35e1763575439e22420bd0ba9&scene=21#wechat_redirect)》

《[0663-6.2.0-通过Nginx获取CDSW的登录信息](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498726&idx=1&sn=4c8056e036dfc7e4407ca270adeae560&chksm=ec292befdb5ea2f94abbe7e41f818e53816d737d137a910f7b64cd60cb30fb924f5e16a7cbf6&scene=21#wechat_redirect)》

《[0670-6.2.0-如何获取CDSW中每个Session输出的LiveLog日志](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498863&idx=1&sn=5ed7bf16fb6ddb36078fb9d0d8cc23ea&chksm=ec292c66db5ea570c558474cfe6674c5aa0cd4c229601e5e979d6ef930acdb700e8b232bb9f2&scene=21#wechat_redirect)》

《[0672-5.16.1-CDSW中Run Experiments异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498924&idx=1&sn=8078c064144d2dfa81fe1e29053091a2&chksm=ec292ca5db5ea5b3374ff15bf630c73cb4ca8c2a33626bedf0e8fdcca68784f3176e602a3f19&scene=21#wechat_redirect)》

《[0673-6.2.0-通过Nginx获取CDSW的登录信息(续)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498943&idx=1&sn=ce1e6bf0f792f1717eaca057c15d50ce&chksm=ec292cb6db5ea5a051446fe437773b0ad260868b78a77241f908fc341263a2377636e352b6ed&scene=21#wechat_redirect)》

《[0679-6.2.0-通过Nginx获取CDSW的登录信息-续-2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499063&idx=1&sn=c43b8eb75d73387c1ebbab7a84ff66f1&chksm=ec292d3edb5ea428eeb4d4431e4b14adecde97e9891f94457a73bb752b8a75270c15b810fe31&scene=21#wechat_redirect)》

《[0683-6.2.0-通过Nginx获取CDSW的登录信息-续-3](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499113&idx=1&sn=58d795e56ea61b4d1bb9e08f7a563c7d&chksm=ec292d60db5ea476e192450e8fda0f0f5ff8bd25f32ce293c8e061709d5f950adeef5e44997a&scene=21#wechat_redirect)》

《[0690-TensorFlow之车牌识别案例](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499293&idx=1&sn=cdc1271921c82406568a02dad7383de8&chksm=ec292e14db5ea7025920f4209a2fed9185f7e40b3a24f9d8138384df99df56e15c1588cc555a&scene=21#wechat_redirect)》

《[0689-1.4.0-CDSW目录迁移变更技术手册](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499326&idx=1&sn=93e88714d43648e01f9a66737efc4638&chksm=ec292e37db5ea721e141fbe4e21493acc21896e58ac63cf4dfd75f0fe5957c1a7a763ac2af45&scene=21#wechat_redirect)》

《[0691-1.4.0-GPU环境下CDSW运行TensorFlow案例](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499327&idx=1&sn=7680496432306aeb2d3cb5fbf43aa318&chksm=ec292e36db5ea720a407630d271e05c083d208bed6bb0af3e2ce324f0d0e09f526f11654cff6&scene=21#wechat_redirect)》

《[0714-1.5.0-CDSW数据库登录失败异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500149&idx=1&sn=f6e27cb29996f20ee2f8fcf06325c943&chksm=ec29117cdb5e986ab9cf2e5d16b2da650c4fcf7cf3b80679650b65ee90711bc97ce36ec7380c&scene=21#wechat_redirect)》

《[0729-6.3.0-如何修改CDSW1.6中Docker服务的默认网关](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501088&idx=1&sn=b78c3fe252f28c6bd60532b48307b2d2&chksm=ec291529db5e9c3f024128debe40761e5fa505f28b1d76d919c58e4735456db13394c92bc172&scene=21#wechat_redirect)》

《[0736-1.6.1-如何配置CDSW使用本地的Pycharm](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501273&idx=1&sn=1c3eb3b4c2668999294805b33b762c49&chksm=ec2915d0db5e9cc6d9378093cbdf754cad412e3b2adde86662d189c7d545aaa1f11ca6b63893&scene=21#wechat_redirect)》

《[0737-1.6.1-CDSW分布式计算](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501292&idx=1&sn=b1d1a0fe1e463909dd6f3f0829112cb3&chksm=ec2915e5db5e9cf3ca3b307d08c6e84d09bfe43c6a4ead973d91e734860183adbc349ee85db7&scene=21#wechat_redirect)》

《[0739-CDSW本地数据目录权限问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501311&idx=1&sn=e693737bb58b8461e626b199d258f97d&chksm=ec2915f6db5e9ce0215cd7cf2eafe487b716f3fb461c9629585cbdb03e03262b04d4ef62f698&scene=21#wechat_redirect)》

《[0740-1.6.1-CDSW中定制docker无法使用Jupyter Notebook问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501322&idx=1&sn=4550a9e561e0f9a7c9e6b225d4680dbe&chksm=ec291603db5e9f15b7e7a8a5abb64f0067a2adfe2f7902a3ce9619c8b3093739baefb3a16cf3&scene=21#wechat_redirect)》

《[0772-1.7.2-如何让CDSW的PySpark自动适配Python版本](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502153&idx=1&sn=2c634d733a5a2144faf993c5d7adb5f4&chksm=ec291940db5e905649c7b0c31691feb10a97a4c546771311e2c9d202bc4e83c157f14dfe2604&scene=21#wechat_redirect)》

《[0775-1.7.2-CDSW的Prometheus和Grafana功能介绍](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502223&idx=1&sn=080e88c0a70c7debf3c4d82a6ac9c3f0&chksm=ec291986db5e9090ef1aa34a272991d2875b3ded89a8bc21f76e2f3028c2536976e07ba40b31&scene=21#wechat_redirect)》

《[0806-6.2.0-如何停止CDSW的Session](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502945&idx=1&sn=9c81a84a5ad304cc94db776531288902&chksm=ec291c68db5e957e98dda1e1f6a0df6a6dcf486b74e34126d8b93d8eb4aaf1ca4254f2fa3f0d&scene=21#wechat_redirect)》

《[0807-6.2.0-CDSW中Session列表和team分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502964&idx=1&sn=358f9299e3dc52cb0687d213293e9901&chksm=ec291c7ddb5e956b17ffb5bcf5fd6d825c92010d5c69725f577f9807c766b90d5e5d648f6efd&scene=21#wechat_redirect)》

《[0812-5.16.2-如何获取CDSW上提交Spark作业的真实用户](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503139&idx=1&sn=12896c5fa83f1933a5d8041700c62fda&chksm=ec291d2adb5e943cca6964bbb67d73da57b2f73a662129a45539196fcb90c272cacf7376141d&scene=21#wechat_redirect)》

## **元数据库**

**6.1.MySQL**

0029-《[如何实现CDH元数据库MySQL的主备](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484806&idx=1&sn=04714c756e0999ec68785a916f9bdbe3&chksm=ec2ad58fdb5d5c9960d690402cab9d010bda3c7c6e8ec2d9687f73771508dd67bd4a9cb8f6f7&scene=21#wechat_redirect)》

0058-《[如何在CDH集群的非元数据库节点安装MySQL5.7.12](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485244&idx=1&sn=949da5c28b56e36f0f158e824a386750&chksm=ec2ad735db5d5e23c324fa1c18a93e08fa922910b52c5da14ccf5a6fcb22595819917b013b20&scene=21#wechat_redirect)》

0134-《[如何实现CDH元数据库MySQL的主主互备](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486821&idx=1&sn=0df0720a5c1b6b52678d83d55147646b&chksm=ec2add6cdb5d547a32762d324a75e979b3b256e64a5ced43d9f0ec3516b3ea4e856ac4901289&scene=21#wechat_redirect)》

0135-《[如何实现CDH元数据库MySQL的高可用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486857&idx=1&sn=9f980c677ec0b32466829ece7c55761b&chksm=ec2add80db5d5496a30ad518e067be74ab138570144b92ea63bef7cd7b8b0710b68d40a4f62e&scene=21#wechat_redirect)》

0136-《[如何修改CM及CDH元数据库配置](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486877&idx=1&sn=38a36ed5dfd8f60b1513b2414163c7b0&chksm=ec2add94db5d54821255984e9d4df271cef6bb1d3846f561751c9fe95ecec36471b8ffdd97e6&scene=21#wechat_redirect)》

《[0618-6.1.1-如何在CDH6集群内节点安装MySQL5.7.22](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497709&idx=1&sn=d1dc7d6ba10e3229958636e433673dbb&chksm=ec2927e4db5eaef2319049049b7fcad54ed7b8f28498a2ace47489d1b957e6e25340a5c18576&scene=21#wechat_redirect)》

《[0619-MySQL5.7.22主从配置](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497728&idx=1&sn=db180d0b7ef75c15c66b80d3d8691344&chksm=ec292809db5ea11f9ecdd7d48f81d887f5961f4e5e41cf6dca7c4a46ff9120a4c886e3e327a4&scene=21#wechat_redirect)》

《[0694-5.10.2--如何将CM内嵌PostgreSQL服务迁移至外部PostgreSQL服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499433&idx=1&sn=c3dfc929d81690e9b0550ea0ef447a0e&chksm=ec292ea0db5ea7b621328206106196355058a8440be96b1cf9c11fd6015c5e3b334764d68910&scene=21#wechat_redirect)》

《[0695-5.10.2-如何将CM的外部PostgreSQL数据库迁移至MySQL服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499511&idx=1&sn=4e7a4666c938514f4f4a959d0837ac68&chksm=ec292efedb5ea7e8406d1bc39a754e6029bfa6a0eadcb8f8e8ab076ecd866efd0863c8476b68&scene=21#wechat_redirect)》

[《0708-5.16.2-如何将CM内嵌PostgreSQL服务迁移至外部PostgreSQL服务》](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500013&idx=1&sn=18cf15184a91fd0cc6af733636061297&chksm=ec2910e4db5e99f2d45d8d006a2651f836a89ce26b7738a816e55b94ea90ef65ba21cb15c120&scene=21#wechat_redirect)

[《0709-5.16.2-如何将CM的外部PostgreSQL数据库迁移至MySQL服务》](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500086&idx=1&sn=2b2e11c19330482762dc030834c0049f&chksm=ec29113fdb5e9829c92554c55fe6585ede656937fe41ba63f88429b653b0614ca04a89527834&scene=21#wechat_redirect)

[《0710-6.3.0-如何将CM内嵌PostgreSQL服务迁移至外部PostgreSQL服务》](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500092&idx=1&sn=098c0478f46f68aa4c3d281a39252c61&chksm=ec291135db5e9823191ee80339e949905c60b6bdea5baa6935d802d2a476de2e4b3068e56738&scene=21#wechat_redirect)

[《0711-6.3.0-如何将CM的外部PostgreSQL数据库迁移至MySQL服务》](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500115&idx=1&sn=f3a355e4e7fde46378252253ff5b5a31&chksm=ec29115adb5e984c7e51cd28ba27934c52971c84c6813f23e412d66ae1da86b8eadd066acc6c&scene=21#wechat_redirect)

《[0789-不停止MySQL服务重做备库的方法](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502611&idx=1&sn=ef12356eb9cb5dc5abcaa6a2b9672dfc&chksm=ec291b1adb5e920cd654c483489b8568de11254de406fd6019d5f30b5573a4d7a93e52641e6b&scene=21#wechat_redirect)》

## **Hadoop组件**

**7.1.Hive**

0004-《[Hive表字段Comment中文乱码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247483793&idx=1&sn=d11f5a14de01206507811b295ad70bad&chksm=ec2ad198db5d588e5354d2d4003cd168c78fd1eb7d3fadd6fe4b1a84770496bd5e15a340c731&scene=21#wechat_redirect)》

0010-《[Hive多分隔符支持示例](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484155&idx=1&sn=ac863cc62a99fa9f3b174f7e5e15aa40&chksm=ec2ad2f2db5d5be4bac04b1a37dba1d85f0c22a92f8709e9bb1fb63ed7635b585cbb26d61243&scene=21#wechat_redirect)》

0011-《[如何在Hive&Impala中使用UDF](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484173&idx=1&sn=e3eff15c962402831da2064827e8357e&chksm=ec2ad304db5d5a12dd31549610ca8dbdd7e1e3fa84ee9cfd7ff940d2360be343a84c7e2d9a66&scene=21#wechat_redirect)》

0014-《[Hive中的Timestamp类型日期与Impala中显示不一致分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484249&idx=1&sn=2763a473dcbfef1423f2c6b7b500be9c&chksm=ec2ad350db5d5a463f8a8590a6ae150470f18d83a9e69f475685abd898a6e98dba6e1712c818&scene=21#wechat_redirect)》

0026-《[Hive使用十六进制分隔符异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484499&idx=1&sn=71ceb41e4a0a3575b9cc233ce0e1bcb2&chksm=ec2ad45adb5d5d4ca681f377909d00f1741a6ab2ccc367229f23e25e1cdffccab22856e73270&scene=21#wechat_redirect)》

0043-《[如何在CDH中使用HPLSQL实现存储过程](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485033&idx=1&sn=43c4f03a4b22c48afd6b0569eb013147&chksm=ec2ad660db5d5f764cf676a43b7766cb316c4102c66706d28b80569523a5dfef4cb9240fde81&scene=21#wechat_redirect)》

0083-《[如何使用HAProxy实现HiveServer2负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485800&idx=1&sn=13e968108e25fcad2db12b16baf9216b&chksm=ec2ad961db5d5077ee93f0f3f5b7d041de5cc9fec34b7541cc8b2299d77da5cfbc3a15c762a2&scene=21#wechat_redirect)》

0084-《[如何使用Zookeeper实现HiveServer2的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485808&idx=1&sn=5d8c6c65ed04e750768e5219983f0f75&chksm=ec2ad979db5d506f51637090d51ac55d00f3947b42b6f26d1f2bcb66f95d4679ffa114d8fe95&scene=21#wechat_redirect)》

0099-《[如何使用java代码通过JDBC连接Hive(附github源码)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486173&idx=1&sn=abe65e0ab05aa06897d19b4a36c014c6&chksm=ec2adad4db5d53c2cd1a6d6b6c9081f19c12b3745493d0b3eab0e7ae2be08c489f13fd4e9066&scene=21#wechat_redirect)》

0102-《[Hive中的Timestamp类型日期与Impala中显示不一致分析（补充）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486217&idx=1&sn=965476a7a1d0ffd16cf5eb6ee4bbb2c6&chksm=ec2adb00db5d5216d20f5a41891da2bf33f19239eac4833fe0238a21371f27949e2935dfe2f2&scene=21#wechat_redirect)》

0143- 《[Hive事务管理避坑指南](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487009&idx=1&sn=f1495aeb37e1cd194b35df3f46ab87e2&chksm=ec2ade28db5d573e643be04732fd118f866e339908583c125ffd579a346babed503d0cc5ed5b&scene=21#wechat_redirect)》

0144-《[Hive Load本地数据文件异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487018&idx=1&sn=d0417adb890c2d851d49e06df4c51500&chksm=ec2ade23db5d57358c9e03af23a5fd9da6e6da5bd9ee1e1c0ccd5e7c10923ecca0361e60199b&scene=21#wechat_redirect)》

0146-《[如何向Hive表加载数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487050&idx=1&sn=adacde2e7a2ead5d54ca71fd1ef5776f&chksm=ec2ade43db5d5755434de14f1872c9f428dc7007cb98506d6f5b3297b7331ffaaebc6ea089a4&scene=21#wechat_redirect)》

0149-《[如何使用java代码通过JDBC访问Sentry环境下的Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487084&idx=1&sn=505e8f09723f9a65d1b390bc12c63eed&chksm=ec2ade65db5d5773c3830afc43cf783172dcd13c5fec82ef33043ed191493c6b101a0406d5b8&scene=21#wechat_redirect)》

0180- 《[Hive与Impala的关键字](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487720&idx=1&sn=7b1185134455381a126d8b7a2933701e&chksm=ec2ac0e1db5d49f722dad23dd0c3391c7971ec44d5b0b80e8ba5b84112a513196fcd22f1d70b&scene=21#wechat_redirect)》

0181- 《[如何在Kerberos环境下使用Haproxy实现HiveServer2负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487721&idx=1&sn=f6f2308e4ca3f18e3f9ccf394393dfda&chksm=ec2ac0e0db5d49f6b020d4be73dce3bd3ed5f254b05a77554e3afa6a62bab57376e596cfc244&scene=21#wechat_redirect)》

0190- 《[如何获取Hive正在执行或者已结束的的MapReduce作业的SQL语句](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487835&idx=1&sn=f3a793f4c6f51ebe03a0d3bea661f2e0&chksm=ec2ac152db5d484484ff438e79fe7535d630e75d30a9d4e26fc0aac4a8587e17400e55dc470c&scene=21#wechat_redirect)》

0204- 《[如何编译及使用hive-testbench生成Hive基准测试数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488190&idx=1&sn=3f34824bdadbfa0823823121f86cafd4&chksm=ec2ac2b7db5d4ba1484d6a6cf3161fdb90798d2605d2e79fa8bf633d32766c42cc8e2b41e206&scene=21#wechat_redirect)》

0210- 《[使用Hive SQL插入动态分区的Parquet表OOM异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488282&idx=1&sn=e1da38f69ba3ab38aff476daed5eb983&chksm=ec2ac313db5d4a05081e92a26fd0a5527db377976f37db7a61007b6138aeacc739f57d4e0555&scene=21#wechat_redirect)》

0240- 《[如何使用HAProxy实现HiveServer2服务的LDAP和Kerberos认证负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489065&idx=1&sn=68ebc8a1d7010d331962a358a9748775&chksm=ec2ac620db5d4f36d9e0620a4e73b4e0a2f870a926ef6037ec8fb4b50c9bbd751166ffd23dca&scene=21#wechat_redirect)》

0246- 《[在同时使用Hive+Sentry,因HMS死锁导致的高并发写入工作负载时,查询速度缓慢或者停滞](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489158&idx=1&sn=a841bd1823e6859f1d50a637ba47d072&chksm=ec2ac68fdb5d4f99aec7aba780d15c9e10730dc7778f8801a6ecfd6eef72f4e0a152d8f47408&scene=21#wechat_redirect)》

0247- 《[Parquet格式表重命名列名后Hive查询列数据显示NULL异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489169&idx=1&sn=22e0fee6c83de261763930321dfcfc8d&chksm=ec2ac698db5d4f8e917ec5f9ad97de0f770806dd31ef61f48fdb228f722452d337991ad60377&scene=21#wechat_redirect)》

0249- 《[如何在CDH集群中安装Hive2.3.3](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489211&idx=1&sn=d4900efbe5c9f311ad7d9d39e1466a4a&chksm=ec2ac6b2db5d4fa4f4b00ad6ab38e76fd0dfdec42c84b0a87dd013cd058588e365e2ea47e3f8&scene=21#wechat_redirect)》

0250- 《[如何在Hive中生成Parquet表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489244&idx=1&sn=476b0a12d6a665729e0c739047bd91c6&chksm=ec2ac6d5db5d4fc3760d8d3438c720aca9ee9df6cc6964304a8559838be1809a90a66da2b44c&scene=21#wechat_redirect)》

0261- 《[如何强制Hive使用指定时区而非操作系统时区](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489551&idx=1&sn=ecfb9b470ee23aef41b8df8f5d0a65ee&chksm=ec2ac806db5d41103dd74abda76eb76749a183f2fd56a05dfd72f1597e35acfe893ad8c168bf&scene=21#wechat_redirect)》

0263- 《[Hive2.2.0如何与CDH集群中的Spark1.6集成](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489577&idx=1&sn=c14f4d1f594b67c3e41debced078f0ac&chksm=ec2ac820db5d41368798ba510ef1e4ebab50d2dd8874ad7590f35e930ae071f0422ed84d547d&scene=21#wechat_redirect)》

0315- 《[如何为Hive2启用Kerberos认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490986&idx=1&sn=7cf5bb15aab041703ee00348414df91f&chksm=ec2acda3db5d44b5b09f9f1098a4aecb83a47332cfa9dc8427f72a780b379fa57d2bda32d1d4&scene=21#wechat_redirect)》

0343- 《[HiveServer2服务异常日志分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491634&idx=1&sn=b0f4022546bf21c9e2be2559238125ad&chksm=ec29303bdb5eb92dbbaa11b7823f68e657cb5d8c9a7f610d7560194143d3213f6ef5fa8c952d&scene=21#wechat_redirect)》

0364- 《[如何使用Nginx实现HiveServer2负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491993&idx=2&sn=a2adc2a0d1528adebdbe478ab1420b5a&chksm=ec293190db5eb8868b7d63d5df6e663f6f14fd1b57cb4aff69e4148197657f4cdedbb81892ad&scene=21#wechat_redirect)》

0375- 《[非Kerberos环境下Hive2.2.0 On Tez集成](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492176&idx=1&sn=0c5e2ccb6ae136044675a1e7031698c2&chksm=ec293259db5ebb4f7d68298f55a4d503f47ff24bc9c1d2a792f6926ff508ce5fe574cb4fbfb3&scene=21#wechat_redirect)》

0381- 《[如何编译适用于CDH的Tez版本并集成Kerberos环境的Hive2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492312&idx=1&sn=1c921be12f6b510c8331922f17b04fc4&chksm=ec2932d1db5ebbc7447bda46be522dad87ba57d5afd4e946d93b5c3dacb3028bb674b512bb4c&scene=21#wechat_redirect)》

0401- 《[Hive CLI禁用补充说明](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492773&idx=1&sn=57eefcb0ab2057d75e277bd79086e075&chksm=ec2934acdb5ebdba41be6f0d480c90f751b60f4fabf68b83251cb8d3a0f24d936f35b46b9f83&scene=21#wechat_redirect)》

0407- 《[如何在Beeline中使用自定义变量](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492835&idx=1&sn=b3b4f1392dd14b0a75de3ea988874d4f&chksm=ec2934eadb5ebdfca9833ca241c391b10307d0d4410b14d4fbd2278692685063d5c6460a025d&scene=21#wechat_redirect)》

0428- 《[如何为Hive CLI运行时指定日志目录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493199&idx=1&sn=7dffe68e47c568827f95a3a3b91a7deb&chksm=ec293646db5ebf5074f401663eaac32afc1a2c5b717e3b92bafa0ea8b599a28adcc1fa200c0c&scene=21#wechat_redirect)》

0435- 《[Hive创建外部表CSV数据中列含有逗号问题处理](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493365&idx=1&sn=4c8c5e21ca2bcc381718e9edf06cc4d7&chksm=ec2936fcdb5ebfea4e24e8cec378e2a54bfc5bb3400a4bba782da9b41a7c4f1150f444f669dc&scene=21#wechat_redirect)》

0436- 《[如何在Hive中使用Map类型](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493375&idx=1&sn=9e70f1ad5b51f9f65cc8b047aa73b184&chksm=ec2936f6db5ebfe0eda880d631af9393bbb8ccf610d03b7bc7ebc1638069d5c67d34bd600933&scene=21#wechat_redirect)》

0437- 《[如何在Hive中使用Struct类型](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493384&idx=1&sn=370b7f16bef0303e9598ba13afc49014&chksm=ec293701db5ebe176e660a38ef9bc10e4a15c44a260040a1ee6cdd175ddae3824c77bd3e41ef&scene=21#wechat_redirect)》

0447- 《[答应我，别在CDH5中使用ORC好吗](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493557&idx=1&sn=eca97bffc7e264a6594578fbc18f7496&chksm=ec2937bcdb5ebeaa7baa0f1a2a9ed153775c2099c4e25c5d4999738d9be6a4543d1101227bd4&scene=21#wechat_redirect)》

0448- 《[Hive作业产生的临时数据占用HDFS空间大问题处理](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493566&idx=1&sn=abfca5a672a1725ff2a5e046b8bae368&chksm=ec2937b7db5ebea1d620a68787da8f5ae5c4607b365c833c59c515e5149edf289523f92ce5d8&scene=21#wechat_redirect)》

0458- 《[0458-Hive数据类型校验问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493702&idx=1&sn=645449d5f7ea0dcd71aba540f9955049&chksm=ec29384fdb5eb1599ec9c57c770ac0a5992ed91c149bc263c0e1fdf678c962bb659f7fda4dfd&scene=21#wechat_redirect)》

0472- 《[0472-Hive中TimeStamp精度问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494364&idx=1&sn=38a1da543f8d1ff120dabd741add0e23&chksm=ec293ad5db5eb3c3c584c7489b0fa06639f627f293970cfb08ea1eb003f37b1befaff2a7afa9&scene=21#wechat_redirect)》

0496- 《[0496-使用Parquet矢量化为Hive加速](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495392&idx=1&sn=eb72f4faf1650957756b65c44d616130&chksm=ec293ee9db5eb7ffe694b74f61851ca9351e39d451941bdd73355485757311d70e4f94c5ab07&scene=21#wechat_redirect)》

0505- 《[0505-使用Apache Hive3实现跨数据库的联邦查询](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495525&idx=1&sn=379f9ad0eacfc7a4b680c0309ba4905a&chksm=ec293f6cdb5eb67a28ac63cc3461a1b4e4dd0f5ea5c9f163091932cf3df9b9242fc9ec38475e&scene=21#wechat_redirect)》

0507- 《[0507-Hive查询json格式表执行MapReduce任务错误问题分析和解决](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495549&idx=1&sn=af41ed10f98339c67e681a2c36cb1f9c&chksm=ec293f74db5eb66274ece8a62efbe27a40a365c647a1f0092ade5aa0a504be0588b646d4977f&scene=21#wechat_redirect)》

0514- 《[0514-Hive On Spark无法创建Spark Client问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495630&idx=1&sn=bf4ba1b0d97928792b4adcad0f8443d2&chksm=ec293fc7db5eb6d1251600819bfca47b6796d464e695d6f5f26ec6fc261aeb55c8a24351f10c&scene=21#wechat_redirect)》

0516- 《[0516-如何查看Hive中某个角色所有已授权的组](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495669&idx=1&sn=149bc9cbee3a34fef53601bc5a92404b&chksm=ec293ffcdb5eb6ea1d4143fbc044a97a0040c37b435a795268a1e6a2e46cffc741ea6caf3c92&scene=21#wechat_redirect)》

《[0537-5.15.0-查询Parquet格式表异常问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496119&idx=1&sn=91440bdc814fc33d695218d5938bed70&chksm=ec2921bedb5ea8a86006f910b5a1999c646429801c56badc0a304b35fa4dd53fda150d48b18c&scene=21#wechat_redirect)》

《[0556-6.1.0-Hive On Spark修改作业临时配置文件生成目录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496429&idx=1&sn=06f1ffd708c4116428217a648bb5c217&chksm=ec2922e4db5eabf218c6c557f8091c9e31eab3920fb01caa01ce89ca3e8f152c0c76252a6da9&scene=21#wechat_redirect)》

《[0572-5.16.1-Hive中decimal类型字段.0结尾数据显示异常问题处理](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496705&idx=1&sn=7f6dbc28acd7f7c27c53e4ded556e175&chksm=ec292408db5ead1e8a352fc08f5b75293b4997cae14a416134fc6e5b8eb919cc89f7732df943&scene=21#wechat_redirect)》

《[0607-6.1.0-如何将ORC格式且使用了DATE类型的Hive表转为Parquet表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497432&idx=1&sn=5c0c2665aa2b30edc32728c83716316a&chksm=ec2926d1db5eafc76f2bd9e102bf928eb6f4a7531716ec0cd233a359b0677f2829207c810e8b&scene=21#wechat_redirect)》

《[0608-6.1.0-如何将ORC格式且使用了DATE类型的Hive表转为Parquet表（续）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497446&idx=1&sn=b3eb3632338cfd01eb1fee0928b36af1&chksm=ec2926efdb5eaff9823796822cb914cad48bf0f8a9c5bb011011c5e26024e28b25c07e9d5949&scene=21#wechat_redirect)》

《[0631-6.2-如何确认一个Parquet文件是否被压缩](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497999&idx=1&sn=13af9f87cb36dac07ef04d599def0ff5&chksm=ec292906db5ea01027239562d7d040d485fd47d1b254173aaeea93ae2f5a3d3c4c38328bc63f&scene=21#wechat_redirect)》

《[0632-6.2-通过Hive生成的Snappy表Impala无法访问异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498018&idx=1&sn=89fdddd344efc02fa029e9527bfa4fe9&chksm=ec29292bdb5ea03d1bf103bba35fe0bf651a1fae8ccee26c88f70b0c5c43a507590d98d08d23&scene=21#wechat_redirect)》

《[0650-6.2.0-通过UDF实现Hive&Impala的中文拼音排序](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498387&idx=1&sn=101f4cebf3801f291b6431a137e23c9b&chksm=ec292a9adb5ea38ce82636a0159a671b35cb87af13813e628223cc1ac7df82f57b8f29e48261&scene=21#wechat_redirect)》

《[0653-5.16.1-Hive Staging目录占用大量HDFS空间问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498414&idx=1&sn=1946a4dd9b627dcccc04a926147e6a96&chksm=ec292aa7db5ea3b1ec0b1a5e4b8a3c73f72072ac1b0def18b1ea38a399c5d852cf46b586f278&scene=21#wechat_redirect)》

《[0656-6.2.0-如何配置Haproxy高可用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498481&idx=1&sn=be7482de64bddd8ce6c3c14978b8f0d2&chksm=ec292af8db5ea3ee7bdbff07aee50e7a34756eab471c0b278183827f20f5c985e68292f407b4&scene=21#wechat_redirect)》

《[0659-6.2.0-Hive处理JSON格式数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498568&idx=1&sn=1cb6d2549b443dbe62becb9376429889&chksm=ec292b41db5ea257f80224380f9cde0fc80b99c1510da990130c9b99b18f5ba7adc732f6a864&scene=21#wechat_redirect)》

《[0665-6.2.0-如何在CDH中配置HMS高可用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498762&idx=1&sn=10ebf5adf8e9bb4adc76dbd8d97734cd&chksm=ec292c03db5ea515e952616a2cc6743bee5d000b6020eb4294a39271d0a41bdd3bf8784f23a2&scene=21#wechat_redirect)》

《[0671-6.2.0-如何将CDH5.12的Hive元数据迁移到CDH6.2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498912&idx=1&sn=be3bec34e4ef54a1943cddfb52a18a2c&chksm=ec292ca9db5ea5bfdb2ed791fe558824b09e2bae5cbff680f66ac5543751629d1a32394a5ccf&scene=21#wechat_redirect)》

《[0687-5.16.1-Hive分桶问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499212&idx=1&sn=bbef06dc0f8aa8131e35ed5883ae4a29&chksm=ec292dc5db5ea4d3cf615a38fe0abb2db135aeba288fd3f8f0dfff592438ab7d31fecbf6f3dc&scene=21#wechat_redirect)》

《[0738-6.2.0-如何在Hive中使用多分隔符](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501304&idx=1&sn=ca34a1f013073716b7ffae7452d1dfe0&chksm=ec2915f1db5e9ce72ebb5abedc7bbe91e7156af29a64a8a1ad4d805f0d2568128741d8e6238d&scene=21#wechat_redirect)》

《[0754-5.16.2-Hive中使用Substr拆分含中文乱码字符串报错异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501708&idx=2&sn=ad7c1d88c5861264c527b9de91f91ee2&chksm=ec291785db5e9e93b108f9837664b1e1c4e5e862f8438bb6213fa4c725287df0ae0acb72b2b9&scene=21#wechat_redirect)》

《[0756-7.0.3-HiveServer2无法启动异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501755&idx=1&sn=51ebfb66e4a5f2a0469a580ffec8640e&chksm=ec2917b2db5e9ea4a2eebed7aa724f1337d4da18f9f9ad2d2fa1a861de6d62c7f783ca4c1b40&scene=21#wechat_redirect)》

《[0767-Hive ACID vs. Delta Lake](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502029&idx=1&sn=bcfbe6fffc898df36cff19b2c947e2a9&chksm=ec2918c4db5e91d202641321b68d3f174762fd9d16bdc86938b9eb30de76409bbbc5689a5e11&scene=21#wechat_redirect)》

《[0777-5.16.2-Hive中使用Date函数用于条件查询结果异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502311&idx=1&sn=fd70aad49a63cd6df77031335f6f45ad&chksm=ec2919eedb5e90f8c95f959d30d52d72514865b2f7ae27140d1c844d8c8e693515d9924463b8&scene=21#wechat_redirect)》

《[0791-5.13.1-Hive视图执行show create table被截断异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502632&idx=1&sn=04260c50e061ea21b37a575f5c7a07be&chksm=ec291b21db5e9237da3b4205c7559ea26ca0ace83877b62f42c42ec1f23819153e15f11ea5a6&scene=21#wechat_redirect)》

《[0816-CDP Hive3升级说明](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503176&idx=1&sn=a19d5a984ec67d209c6173b142508bff&chksm=ec291d41db5e94573bfa634a064025897cfd7444c3b0c530401fa3e95b30e5409a516b1cd159&scene=21#wechat_redirect)》



**7.2.Impala**

0039-《[如何使用Python Impyla客户端连接Hive和Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484964&idx=1&sn=4d766e476632aefe6ef4ced9adfe8b9c&chksm=ec2ad62ddb5d5f3b9405069c19fbc7ce3e32147526732a14874ba9f5c1b4037fb2a3c9b272b4&scene=21#wechat_redirect)》

0070-《[如何使用Beeline连接Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485477&idx=1&sn=a3a9805fd51acd11352926e99680b01f&chksm=ec2ad82cdb5d513aedf059d1e08e9beb4be25c58c6edb149a91893016f2764484804f859ccc4&scene=21#wechat_redirect)》

0081-《[如何使用Nginx实现Impala负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485775&idx=1&sn=fddf2d54e1f715a53a4901db9524d4ea&chksm=ec2ad946db5d50508dfce75e702d906540abf8f8259604d9c5eed98a38ac386b87bea1496908&scene=21#wechat_redirect)》

0082-《[如何使用HAProxy实现Impala的负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485788&idx=1&sn=c37d0e3cd7688d90bfa9f93c81eaf3c9&chksm=ec2ad955db5d5043f808294c4a3c1f8e7a06e57c280ebf2a7b555cd5ca172d9211f4fe6958a9&scene=21#wechat_redirect)》

0097-《[如何使用java代码通过JDBC连接Impala(附Github源码)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486137&idx=1&sn=1909e83e4196b6d0d3bdd083c7e373ac&chksm=ec2adab0db5d53a636501d63ceb66d538732bbaa4a3e6a1fd7526bc01fe80528e416898796a1&scene=21#wechat_redirect)》

0113-《[Impala升级为Apache顶级项目](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486393&idx=1&sn=578c179e12c0a4c3d5c12c7750e22a11&chksm=ec2adbb0db5d52a6fd700a5f3b7eb8a3eeaae34a589ed6deb1b78df2e211fc5da17defd17b75&scene=21#wechat_redirect)》

0124-《[如何使用HAProxy实现Kerberos环境下的Impala负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486616&idx=1&sn=980a09cdfc2ef76db0a7ef3c0f0adebc&chksm=ec2adc91db5d55878077c671c0051543facb8f997ff6c04ed0f04338d1f394e32a8a948216b6&scene=21#wechat_redirect)》

0131-《[如何在Kerberos的Linux上安装及配置Impala的ODBC驱动](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486776&idx=1&sn=66b65d0663f5bd456db0c462bc967888&chksm=ec2add31db5d542756e31b2da064bdca57d899de45a90834d3b900f67dc521a9bf21adbd9509&scene=21#wechat_redirect)》

0147-《[如何使用Java访问集成OpenLDAP并启用Sentry的Impala和Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487064&idx=1&sn=c02bfcd54696ad82f7db01061bfc8937&chksm=ec2ade51db5d574735dd1ebd0eaef82eed5676d40ff1a1510513634af5f906227700d8366136&scene=21#wechat_redirect)》

0154-《[如何在Impala中实现拉链表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487145&idx=1&sn=c97cd183dd77268b96f6095f659c0c7b&chksm=ec2adea0db5d57b670c8f1a94775b558896e26e7ba27de01c7042479968e6a67073ea77de7a9&scene=21#wechat_redirect)》

0162-《[使用Java代码通过JDBC连接只启用Sentry的Impala异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487267&idx=1&sn=1668b7e7ec3d61fee17ecfb181853aaa&chksm=ec2adf2adb5d563c62b6a5d55323e8b7a927beb9211c7f2d17474517e859b339223b5edcb7dc&scene=21#wechat_redirect)》

0206- 《[Impala的Short-Circuit Reads](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488216&idx=1&sn=3e464809a1122fc4f7c4dbbb0facbe9c&chksm=ec2ac2d1db5d4bc781009aab3d6d919ed36b5763a1cef84ff40c357a5491a034616c15012117&scene=21#wechat_redirect)》

0224- 《[Hive与Impala对VARCHAR/CHAR存放中文字符解析不一致问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488705&idx=1&sn=f9f175dbf25b762af9554d4069f8d94d&chksm=ec2ac4c8db5d4ddeb9e51f69cba73007a2e8e8eccc279cc1277486835b573546c186acbfe322&scene=21#wechat_redirect)》

0242- 《[Impala TPC-DS基准测试](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489095&idx=1&sn=5af481742664f79146c58f425c9429d3&chksm=ec2ac64edb5d4f58860db96ae4b452fda70b108527e4cc78c1978461ed62e67fcf997631d270&scene=21#wechat_redirect)》

0248- 《[如何在Impala中使用Parquet表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489186&idx=1&sn=55daaea9da465972b2c86b35aead958d&chksm=ec2ac6abdb5d4fbd1420e65846829cec98c9eb5812828f48538be4098e7ac7da5e5814d1b4ce&scene=21#wechat_redirect)》

0275- 《[当Impala碰到由Hive生成的timestamp数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489928&idx=1&sn=621feb86f011b7bf068acd41cd66625b&chksm=ec2ac981db5d409770309d1f9cf730c215459aba8d6c1562b7ea631d7f314330585658078c53&scene=21#wechat_redirect)》

0276- 《[由Impala-3316导致的并发查询缓慢问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489959&idx=1&sn=ca9690b1b1d710feea1ada0e3ed4930e&chksm=ec2ac9aedb5d40b8fc356bf89f3bcf11ffbb72b2948dfc6a5aa52d96a94db2dc7d511bbc2339&scene=21#wechat_redirect)》

0277- 《[Impala并发查询缓慢问题解决方案](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490010&idx=1&sn=6cbf6155e4bd15cc7dde11b66a2e143f&chksm=ec2ac9d3db5d40c567751ea643e5702d59fa7fbb2945f895b8d6149e67e21d0154363cd7e5ca&scene=21#wechat_redirect)》

0312- 《[如何在Kerberos环境下使用Spark2通过JDBC访问Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490942&idx=1&sn=8eb07cd4f9eff424b517aa753546cb5c&chksm=ec2acd77db5d446114160756187abf05ea68074dbbff25f8237ef7c1972a993589d2ccdae0b6&scene=21#wechat_redirect)》

0326- 《[如何为Impala Daemon服务配置Executor和Coordinator角色](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491327&idx=1&sn=aa48d8b596574941652a0c8a5f8f30e4&chksm=ec2acef6db5d47e08a0180a7e8cd30ee1a2106535d8db65120e8f7b78fc3ea0fc0bb980718b5&scene=21#wechat_redirect)》

0337- 《[Impala最佳实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491585&idx=1&sn=16a55845c203763a7cb28b535a11b2b6&chksm=ec293008db5eb91e702b9d0c60fbea039a0a164157ab282b2bff2f4a51aaf85241fa191b59f3&scene=21#wechat_redirect)》

0397- 《[Python2使用Impyla访问集成OpenLDAP并启用Sentry的Impala服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492732&idx=1&sn=c0550450f0c7b17c912a33ca2ecc71de&chksm=ec293475db5ebd63c52658bea2dc110d0adee4c7afe7bd5cfaf7a1786afba6fea53db0715721&scene=21#wechat_redirect)》

0405- 《[如何使用Impala合并小文件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492818&idx=1&sn=d3eba30d0689e96c32d287feea744149&chksm=ec2934dbdb5ebdcd4fadd95fb1a871e4f260b0f8ba066ab6fd8099ea379972248289a4d30a0a&scene=21#wechat_redirect)》

0433- 《[Kerberos环境下Impala Daemon在CDH5.15版本中KRPC端口27000异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493321&idx=1&sn=505ea12b96712824834aa80d0245bf35&chksm=ec2936c0db5ebfd6de6d5c89a18289ba995306552129b49b7d4389b7d3db7c16e7fc03411f30&scene=21#wechat_redirect)》

0440- 《[如何启用Impala的动态资源池](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493426&idx=1&sn=679d5ca5cb17fa0315e09f6fc29172d0&chksm=ec29373bdb5ebe2d7e38726e27894f7c9ecceb56c0db15c8ef4142b9c58815cdd3110766b854&scene=21#wechat_redirect)》

0441- 《[Impala动态资源池及放置规则使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493447&idx=1&sn=dc9eb9e7cc5c899f3036fde16fe3887b&chksm=ec29374edb5ebe580480d7ef2df18a06dfd36478763362c75f03f2f021fd2d8b1adda2d6bf90&scene=21#wechat_redirect)》

0518-《[0518-如何在Impala中使用UDF获取SessionId](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495696&idx=2&sn=ef23c9741b91029f22855de038036f12&chksm=ec292019db5ea90ff4833d0b77b9879f863bcfa146a3d88dcc844d2eb6e5dd9a90e9f4395304&scene=21#wechat_redirect)》

《[0680-5.16.1-impala-shell导出数据存在中文异常问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499072&idx=1&sn=bb8faceb2acde017cd19194e19f477de&chksm=ec292d49db5ea45f0a66e0ee05a0cb9b65c0fecd961a931e73a1a09a457b128ac127640f3879&scene=21#wechat_redirect)》

《[0746-5.16.2-Impala中查询监控状态检查告警解析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501375&idx=1&sn=2772b7ecf60db62fa2a248c64b260371&chksm=ec291636db5e9f2083cfe57db264a96575a5fdd2e49f0714ad1581da7f759ad26ac89ec1b503&scene=21#wechat_redirect)》

《[0757-6.3.3-如何配置impala自动同步HMS元数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501774&idx=1&sn=5c75d6e6389feb9bcd3c13209475965e&chksm=ec2917c7db5e9ed11ae698ad523428f9844ffc3b5a961de170d0ec6880f3ac0885cd714f0cd6&scene=21#wechat_redirect)》

《[0758-5.16.2-Impala的invalidate与refresh介绍](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501810&idx=1&sn=419babe7612de8cb7916a21ea039991a&chksm=ec2917fbdb5e9eed66f8bf837e7453713271c80bae6394ddf11519d399eaa1b9771efb9104f4&scene=21#wechat_redirect)》

《[0762-5.16.2-Impala查询HBase表字段顺序不正确异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501890&idx=1&sn=f362f749b64955af6d541c294b6971cf&chksm=ec29184bdb5e915dab31a4d717d5bc93eaa39b91a0b0caf7a7c34a2f7223677f700364b1499a&scene=21#wechat_redirect)》

《[0794-5.16.2-Hive和Imapla查询decimal类型结果不同异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502833&idx=1&sn=9bfde4c0556e525f1d6baf5a7c35afd3&chksm=ec291bf8db5e92ee16744b6cd548e91a56dc14fe958117631fa73baf95ba6ff3c0c56f96b5d4&scene=21#wechat_redirect)》

《[0805-CDH5中的Parquet迁移至CDP中兼容性验证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502919&idx=1&sn=8d4586d1dab1cafe8e9ff2665b754983&chksm=ec291c4edb5e9558b5d2e5edfbe22a5712889ac2296c0f23ed9d56efd0e369980797e96839ce&scene=21#wechat_redirect)》

《[0810-5.15.1-Impala执行invalidate metadata异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503067&idx=1&sn=722b6b3dd5271e2046949c8eedccea02&chksm=ec291cd2db5e95c4bb704670a9a7e0df3bbfb9cf82ac6012d9b07713e48046af7b77075ff675&scene=21#wechat_redirect)》

《[0817-6.3.3-Impala执行DDL慢问题分析报告](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503187&idx=1&sn=7b0c6a7efe86698845a0a7178a6e66b0&chksm=ec291d5adb5e944c45cdecf426cf37f363e9cf4f59345587cd1335495dc39037ea47c50556cf&scene=21#wechat_redirect)》

《[0821-7.1.1-Impala多并发查询异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503294&idx=1&sn=d8645ea09fefdd7d9255673fe24f002f&chksm=ec291db7db5e94a1a83da70931617374a78e2fed75e1923cfd6310ace5d02832c3be4892eba6&scene=21#wechat_redirect)》



**7.3.HBase**

0045-《[Cloudera Labs中的Phoenix](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485039&idx=1&sn=f6eba9bc7fdea9008c28974e5aaff371&chksm=ec2ad666db5d5f700044d7f0f74ef6f9d0bc12466a34b75ab80b29e413f35e6b9ddfa85b7b04&scene=21#wechat_redirect)》

0066-《[如何使用Java连接Kerberos的HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485435&idx=1&sn=8e7d292cd875e5f9e3f24b4e6f9080f3&chksm=ec2ad7f2db5d5ee42590b1f60a2557b391140ade872c682b4fe7cbb883ee11c54d0dcd531f25&scene=21#wechat_redirect)》

0071-《[如何在CDH中使用HBase快照](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485478&idx=1&sn=7eb4d071f0d1df9b99aa58a62ab10e5e&chksm=ec2ad82fdb5d5139e0475ab330a73faf2ee34cc3e9223b8ef7eae3b0c1095f924af8fef3252d&scene=21#wechat_redirect)》

0046-《[如何在CDH中使用Phoenix](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485108&idx=1&sn=695e9cdb9c9b5f3078e9dad6ce7dd434&chksm=ec2ad6bddb5d5fab2ef88e39dafc260fd05a5927898e86b067395e331c9116c2ac911c38a547&scene=21#wechat_redirect)》

0254- 《[如何使用HBase存储文本文件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489360&idx=1&sn=54e97d9d5c36fbf1ad5e49deb7af9c92&chksm=ec2ac759db5d4e4f3ea2754e32d339a2e684cf4e15ba992a6e904937e2566bcbcae8f5349ff9&scene=21#wechat_redirect)》

0258- 《[如何使用HBase存储图片](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489438&idx=1&sn=239b03cd3d3c784f109af591dc05cf4c&chksm=ec2ac797db5d4e81ffb7ea80ccb2981f898ff9486ca719fe0988ab44649a8bc6f2293a62c6d5&scene=21#wechat_redirect)》

0266- 《[如何使用Java调用HBase的 Endpoint Coprocessor](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489642&idx=1&sn=b9da33743724fd4e75312d7d9b0eb3f5&chksm=ec2ac863db5d4175b9aad8bdd8cec4cb49da9b71077f0910a88af32413ecde7a4477e7975af3&scene=21#wechat_redirect)》

0268- 《[如何开发HBase Endpoint类型的Coprocessor以及部署使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489676&idx=1&sn=c97f7c120edc3072344aff454f4cdfa4&chksm=ec2ac885db5d41939089290aca115e6bd369f71525314975f7463a6d1cf6a0d37e858497d6cd&scene=21#wechat_redirect)》

0307- 《[如何使用Phoenix在CDH的HBase中创建二级索引](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490823&idx=1&sn=58f23b3356cd7bea272709ee1779628c&chksm=ec2acd0edb5d44184b56947a6586a44176af1ceae6bb1651f07af3318ce670a4950c1b966d5c&scene=21#wechat_redirect)》

0308- 《[如何在CDH5.14.2中安装Phoenix4.14.0](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490860&idx=1&sn=512abd484bd5dbd922f5c3054ea1d3d8&chksm=ec2acd25db5d44331a1f4a1c778206b1eca3aa7250ee229470885e7f54752ae5e7872a52066a&scene=21#wechat_redirect)》

0321- 《[如何在CDH中使用HBase的ACLs进行授权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491202&idx=1&sn=31f44e24430e58e5814964f8aec13d78&chksm=ec2ace8bdb5d479d66a517ae7706a490d2f154369f317c79f46af49ee646d7cbe50c4b8b08c1&scene=21#wechat_redirect)》

0322- 《[如何在CDH中使用HBase的Quotas设置资源请求限制](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491220&idx=1&sn=25a467d65a6eeeda631e7e161196c3d2&chksm=ec2ace9ddb5d478bb046403358dd90c3eb28dbfea6d78ff7e763ccf61b9630b3799c506c0612&scene=21#wechat_redirect)》

0346- 《[使用Spark通过BulkLoad快速导入数据到HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491698&idx=1&sn=38f4bca784eb5c55bd158b2884230900&chksm=ec29307bdb5eb96d5fa32420d70b1b75545895478fb9aa052acae150bf72af5c1f407d280385&scene=21#wechat_redirect)》

0454- 《[如何使用Java访问非Kerberos环境的HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493652&idx=1&sn=4468152b16703a4ea55b83ba89f642bc&chksm=ec29381ddb5eb10b50a176617d51f63651ede4f2265ac6735bc5e42fc389133841cef56cebdd&scene=21#wechat_redirect)》

《[0539-5.15.0-HBase-Spark无法在Spark2编译通过问题解决](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496144&idx=1&sn=86c945b2672ffde3a0e642e1c3da664c&chksm=ec2921d9db5ea8cf39c59428a27145a769c89a3091b3fdcfd1e749a00aa5721361572f159568&scene=21#wechat_redirect)》

《[0540-5.15.0-Spark2使用HBase-Spark访问HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496157&idx=1&sn=6dbc4ec81d8456c61d81813b66fca30c&chksm=ec2921d4db5ea8c22718ed9e56b1b1f4d790b44cf2a9452c5b153f3bf568150c92059a7aa70e&scene=21#wechat_redirect)》

《[0674-5.16.2-如何在CDH5中使用Phoenix4.14.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498974&idx=1&sn=a5629d8938c0c013659bef250017369b&chksm=ec292cd7db5ea5c1db9068a7701e5878bc99f4d43245dd34b9c38edde5fc85958436e3924cac&scene=21#wechat_redirect)》

《[0676-5.16.2-Apache Phoenix for CDH](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499012&idx=1&sn=aaf83b7110a4cadd0adc5f60e5839615&chksm=ec292d0ddb5ea41b96245f6e6b164343b6fd8241956584a35743612f13c16faaeedc3d933949&scene=21#wechat_redirect)》

《[0693-6.2.0-如何将Hive数据导入HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499380&idx=1&sn=73b268e98a8c645ee4ce5d40c7920527&chksm=ec292e7ddb5ea76bf7556b2b0d2ce387b4f9318790f4738c79dde5a908c424ee5efc592fe384&scene=21#wechat_redirect)》

《[0712-6.2.0-HBase快照异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500130&idx=1&sn=292987074bd524654c478e71ebf8bcbc&chksm=ec29116bdb5e987da8a8b49d73f44cf0008f23212d29a68c6afac53ef84bd67f7bc29fec14f7&scene=21#wechat_redirect)》

《[0713-6.2.0-HBase的Thrift Server启动问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500140&idx=1&sn=10e8a85b05cf88ac93c48e0882b0d567&chksm=ec291165db5e9873b99c2d9ee4c47d356068218e591481e08d51d20a6ff322b97fb3c83b191d&scene=21#wechat_redirect)》

《[0779-5.14.4-HMaster无法成为Active异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502354&idx=1&sn=9ac02c85433298d7c68a994668665037&chksm=ec291a1bdb5e930d1cc65f2e5586339ae89b0665e8934149cdf935992bc8f58213762989fcd1&scene=21#wechat_redirect)》



**7.4.Hue**

0056-《[如何重置Hue用户密码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485228&idx=1&sn=8b786511f419d4d1aff64ff90be68583&chksm=ec2ad725db5d5e33c97da03a40b6a3fb7f0cc3c79710094cc5e885c251922592d75f75a1921d&scene=21#wechat_redirect)》

0152-《[如何在Hue中配置已启用SSL的HttpFS服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487120&idx=1&sn=5747b067e3dbee89254d0133f42196f7&chksm=ec2ade99db5d578f0b700b257bde004417144a7576c8738d5e8ef9d8a412c86e5bff2259dbf2&scene=21#wechat_redirect)》

0153-《[Hue禁止用户下载数据问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487128&idx=1&sn=4369aecbe733c97abc3376676f87b39b&chksm=ec2ade91db5d57875361b32977360215220b7f937527b4715176ffc8b47cc94b3cbd572db681&scene=21#wechat_redirect)》

0164-《[如何在Hue中配置HiveServer2的负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487291&idx=1&sn=4519e327d48414bec9f257801babab94&chksm=ec2adf32db5d562441dc843f1523dceae5a6f3ca9387f180aa89a4deb6932eae0b445a1875d3&scene=21#wechat_redirect)》

0168-《[如何在Hue中配置Impala的负载均衡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487410&idx=1&sn=b689e59c47932cf3528d8a57b81a7a23&chksm=ec2adfbbdb5d56ad696e2d1fcfff073295c8a8b17953fbe8e4cd381b21c37d8dafc23ccad616&scene=21#wechat_redirect)》

0236- 《[Hue中无法删除用户异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488991&idx=1&sn=99715ce5be8f8969dd38bd4a009d4fa0&chksm=ec2ac5d6db5d4cc0b8e0eb77554d1e4b228f6bbc3fb2b859b3506767b552f1b1c054d9a8fcc7&scene=21#wechat_redirect)》

0241- 《[如何开启Hue的Debug模式](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489078&idx=1&sn=063b3fd37d3332ed77bf2391a44f57a3&chksm=ec2ac63fdb5d4f2913dc47ca77a1215954eb9896cb3f4e0f2160fdb3c54bc4d155e851c32390&scene=21#wechat_redirect)》

0251- 《[如何在Hue中集成配置Hive2.3.3服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489243&idx=1&sn=2a3c4ba215feeba7b25e3571a3d4ecbe&chksm=ec2ac6d2db5d4fc4b01a486b678f9e6e660a50a4010be38b71783601acdc627cc9ddada7e469&scene=21#wechat_redirect)》

0328- 《[如何在退出Hue后关闭Spark会话](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491352&idx=1&sn=5c7caf1514fd62508f8e31b9298c7c49&chksm=ec2acf11db5d4607d2ff5c5aa6fc84624c0fe5d90dd9e8265f1f5ab8cd3f0b8f5701609c5ac7&scene=21#wechat_redirect)》

0395- 《[在Kerberos环境下Hue与HBase集成](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492655&idx=2&sn=578d31d0e493ded7649a1d55112501f5&chksm=ec293426db5ebd305f538f969327ad502b525407ea38670b8c8b45fc73cdfd706825222842f5&scene=21#wechat_redirect)》

0402- 《[如何修改Hue的时区](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492781&idx=2&sn=5dbde84134eb8c285070ea0f060e234b&chksm=ec2934a4db5ebdb20e48e797d7a55f5e32a3ed17b97518c5b7acbfb0f043fe8562df1fe416c6&scene=21#wechat_redirect)》

0408- 《[如何在Hue中集成第三方Web应用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492851&idx=1&sn=62c04f3e7d5c0014577b50834b7d9b3e&chksm=ec2934fadb5ebdec7893b4cb39db51c652d2babd7bcae77d17e7abdcc1b9d852d1edb3eb589e&scene=21#wechat_redirect)》

0422- 《[如何为Hue添加自定义Banner](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493116&idx=1&sn=b939d15a824abe3628cb7a41ea4dacde&chksm=ec2935f5db5ebce3c2b2480b3a5bc69c973401dbbdb3e110aaf6ccf2e5e0fdbb01759c8e8fee&scene=21#wechat_redirect)》

0431- 《[如何在Hue中添加Spark Notebook](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493297&idx=1&sn=cb1bda233f27765db8635661e765bf52&chksm=ec2936b8db5ebfae7d2a80a356610a0ad29fbfd9fbccb093b9e2c5b0e6c05631686bb6fd8b7b&scene=21#wechat_redirect)》

0450- 《[如何在Hue中调优Impala和Hive查询](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493600&idx=1&sn=3964b9803a77200d925bd50640dbe6fe&chksm=ec2937e9db5ebeff287b7565b36bc5aee94b6e83052e9ff6f9502b0e4d184d4b6b890d4ec16b&scene=21#wechat_redirect)》

0475- 《[0475-如何统一Hue和Oozie的时区](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494473&idx=1&sn=02c7c0a7da6264771884e2a70f514041&chksm=ec293b40db5eb2562559581384007e21b836c10856054d8e291923245b5ce4eb5f59cd8e5d81&scene=21#wechat_redirect)》

0498- 《[0498-Hue Sqoop1的编辑器中执行Sqoop作业失败问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495440&idx=1&sn=7055864cf475c23c8466cac216c64fb1&chksm=ec293f19db5eb60fe6d7de50516dbc9c1fa9e76e093ef9feb2b29b8f87592f37a7e3df044576&scene=21#wechat_redirect)》

0506- 《[0506-如何将Hue4.0版本中默认执行引擎设置为Hive而非Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495535&idx=1&sn=1477e953a3b2b24999b58a30356592b5&chksm=ec293f66db5eb6702664a09577843408ddfb7de7cdfba456fe2d8a3cc6c5d9625cda4f5a77a2&scene=21#wechat_redirect)》

《[0536-5.15.0-如何使用Hue集成RDBMS数据库](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496101&idx=1&sn=2aed4a74f4ff054f3055f93758ea1326&chksm=ec2921acdb5ea8ba14d0b89fa25d307dfe9530e52827bfcea26fb5aad30b58f5b54cfd988d54&scene=21#wechat_redirect)》

《[0635-5.16.1-Hue集成HBase出现Api Error异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498051&idx=1&sn=ad28b5bc4424ad2ad9e4298fe69d1691&chksm=ec29294adb5ea05cc82419470c7ef29d8e3b181724b987077b5086dc0991b220dcff95fb774f&scene=21#wechat_redirect)》

0636- 《[6.1.1-Hue上SQL查询结果显示不全异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498063&idx=1&sn=8168a14cab3f6864b6eff853044f8ee2&chksm=ec292946db5ea050ef84aeecdeee455a4369e62b4aff0c45da433447fe3ca42f842227a55b9d&scene=21#wechat_redirect)》

《[0640-6.1.1-Hue上SQL查询结果显示不全异常分析-补充](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498167&idx=1&sn=d3effb6cc4638e7fe21d32ff1b1a404b&chksm=ec2929bedb5ea0a86379deda776cf54d60e4156288a43c811a23be7df40f36ec22d61addb319&scene=21#wechat_redirect)》

《[0647-6.1.1-Hue集成HBase出现Api Error异常分析(续)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498342&idx=1&sn=1dd7b2289f04ef6a60f46f79050ca143&chksm=ec292a6fdb5ea37927ae71005c95f33e9ad63358f7a4f8e9ed7920dad9da8c5aab54791da228&scene=21#wechat_redirect)》

《[0681-6.2.0-如何在HDFS自动创建用户主目录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499094&idx=1&sn=64df897c7e365ce9baa6c33845b80dd2&chksm=ec292d5fdb5ea44943572911db12f1e2d1aae4b4ae477c5722bef73561681320ef63f75c78fb&scene=21#wechat_redirect)》

《[0783-6.2.0-如何在Hue中集成HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502446&idx=1&sn=5c5eaf4f9278af1671e6fbc4b1138eef&chksm=ec291a67db5e9371d326fa65cace066ec54b04a1780d9dc2b2316a4ffc221c9f3f01b92a5401&scene=21#wechat_redirect)》



**7.5.Sqoop**

0121-《[Sqoop抽取Hive Parquet表数据到MySQL异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486556&idx=1&sn=243809a65939ed6e436466e01a941800&chksm=ec2adc55db5d55435c599a5a4b0c929a4ff2f57123a252ec2a82adf8f8cea966970514e9e59a&scene=21#wechat_redirect)》

0193- 《[如何使用Sqoop2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487918&idx=1&sn=d5c10a21557e5bf1c46ca1058533ec37&chksm=ec2ac1a7db5d48b1768f6834c9eac029194cdab2fe9cb13ade06f338645082c739307500cb30&scene=21#wechat_redirect)》

0342- 《[Sqoop抽数到Hive表异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491627&idx=1&sn=5a2b1ab2bbc3cf701a559b76b03c66e4&chksm=ec293022db5eb9341d35b46077e52190ee1694b202e1e0a1c2dfa8b8b2d2f02a7d3c026a3466&scene=21#wechat_redirect)》

0348- 《[Sqoop抽数到Hive表异常分析(之二)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491721&idx=1&sn=771c21ff11c7c4735fbd7c85eed29a07&chksm=ec293080db5eb996be6e46d6bce7f3171bfc1ca0ee9f9925f66372846fc7ec30366aed93a236&scene=21#wechat_redirect)》

0425- 《[如何清理Sqoop脚本产生的临时编译目录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493161&idx=1&sn=e1c858d1596b69cb22c8e5ca1e7c74b7&chksm=ec293620db5ebf361b7ab70c042d0cf9973c8e08dcaf966ea77eeedcb847ad6a61327e030ed4&scene=21#wechat_redirect)》

《[0657-6.2.0-Sqoop导入Parquet文件Hive查询为null问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498501&idx=1&sn=43744ab714938a80740d948bef523c02&chksm=ec292b0cdb5ea21aa2a648898a126c24cbca83bffa67b1e17604a269720c2d2a9ce113b5e25c&scene=21#wechat_redirect)》



**7.6.Solr**

0103-《[如何使用Java代码访问CDH的Solr服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486223&idx=1&sn=49140cc8c553cd55ad251ac75c452684&chksm=ec2adb06db5d5210e374431495de196b544ee2b52a619080cdd54ad89b2766d4d136a5393047&scene=21#wechat_redirect)》

0114-《[如何使用Hue通过数据文件创建Collections](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486413&idx=1&sn=34d16fd739d1aeccb117c74dd675ba96&chksm=ec2adbc4db5d52d2ac8ef19c462ab3775945e46065146d8e91f05b88dd6fbbe0397714962e50&scene=21#wechat_redirect)》

0252- 《[如何在CDH中使用Solr对HDFS中的JSON数据建立全文索引](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489275&idx=1&sn=192900938dcc87556543edffc2775ec9&chksm=ec2ac6f2db5d4fe4a6a3b526a56f3d760c2e43ce93c6e94ef12430e0e200f880140dc9bd17cc&scene=21#wechat_redirect)》

0253- 《[如何使用Flume准实时建立Solr的全文索引](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489313&idx=1&sn=133b4374b182829e974e268b032f3258&chksm=ec2ac728db5d4e3e1b59764e5ea9516b5dc4d8c9d9f7c61a887af541f2388d01c8d39a79a9b5&scene=21#wechat_redirect)》

0256- 《[如何使用Lily HBase Indexer对HBase中的数据在Solr中建立索引](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489380&idx=1&sn=1be8ce70478d294e224a279625bb2627&chksm=ec2ac76ddb5d4e7b5f2f353339e1454e3d1df3b52a2709cd0821bf7e07cdaf09aa55b75dc767&scene=21#wechat_redirect)》

0293- 《[如何在Kerberos下使用Solr](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490471&idx=1&sn=b333f9717275473c46641ebdba9d24dc&chksm=ec2acbaedb5d42b81dfa69225b46d39dd0311cb016d4f625f6080a4cefb452db5bce0f58b29b&scene=21#wechat_redirect)》

0301- 《[使用命令行创建collection时Sentry给Solr赋权的问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490691&idx=1&sn=f6459e00a17f42eadfbdd226563f784d&chksm=ec2acc8adb5d459c23dbb8eb763aa49dc8b82274dd1993bea85b0d0ba342cd0721f573b435d7&scene=21#wechat_redirect)》

0504- 《[0504-使用Pulse为数据管道实现主动告警](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495518&idx=1&sn=bd0138ebc12b277a1739bfac6f4f8109&chksm=ec293f57db5eb6417689a708b6ef68a475dfde6a3eacbbe277c068acc42428b760b5279571b4&scene=21#wechat_redirect)》

《[0700-6.2.0-使用Solr7对多种格式文件建立全文索引](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499784&idx=1&sn=b3bc31333fd1b371624bb9ccbf452c6d&chksm=ec291001db5e99177c5e9a3d8c2f30b90edff4535337e68b712e2856012f18f3eb75e669187d&scene=21#wechat_redirect)》

《[0701-6.2.0-使用Solr7对结构化csv文件建立全文索引](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499802&idx=1&sn=d862452609eee96d28b87c35420711e6&chksm=ec291013db5e9905b57b7537eb96d18314b62b0ab3ac0d05f7dfedf5f4d326b0588c4ed538aa&scene=21#wechat_redirect)》

《[0703-6.2.0-使用Sentry为Solr进行赋权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499847&idx=1&sn=3fd9b4baf872cfb221df1cb82a8b3278&chksm=ec29104edb5e9958d04be84a8bc9a02206094f7b38aed2bfe3c5537a7b223cf722c9d4fdda62&scene=21#wechat_redirect)》



**7.7.Oozie**

0060-《[如何使用Hue创建Spark1和Spark2的Oozie工作流](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485305&idx=1&sn=00b512e7392a6eaa69f81b15c25ee2b7&chksm=ec2ad770db5d5e6667fb2d9b954db88204b8408b0fef75986bc4f6978d875587352dfdcb0919&scene=21#wechat_redirect)》

0061-《[如何使用Hue创建Spark2的Oozie工作流（补充）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485325&idx=1&sn=706c8405d62209a1fd9f065acff39c17&chksm=ec2ad784db5d5e92d4ff820152929ae91959b0fd460b04212e7d025f772bab4c9991adad58a9&scene=21#wechat_redirect)》

0075-《[如何在Hue中创建Ssh的Oozie工作流](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485589&idx=1&sn=bcbec1391ca7cca0a87a18a901fe6fce&chksm=ec2ad89cdb5d518aeb8f26117dcfe7176500f245a1b2ff23be7b1e68e6dca6f900475bbebbef&scene=21#wechat_redirect)》

0119-《[如何使用Hue上创建一个完整Oozie工作流](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486534&idx=1&sn=368e14163577c8fa87c1a6e1fad546ab&chksm=ec2adc4fdb5d5559775041391305606fb97cf1fc2a9651c733c6ae15f1739d3b381170e0d573&scene=21#wechat_redirect)》

0120-《[Hue中使用Oozie创建Ssh工作流时sudo命令执行失败问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486553&idx=1&sn=89a3798502a17405d27a2a8d474fc806&chksm=ec2adc50db5d5546129990ccda305befe31f0d60f3ed12f5d1783f5252d5c30859f7692daaae&scene=21#wechat_redirect)》

0123-《[Hue中使用Oozie创建Shell工作流在脚本中切换不同用户](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486600&idx=1&sn=b4140e2bea60e7d20707716d6c4fac24&chksm=ec2adc81db5d5597c4a9d5c0c429a7bf2cd502a1abeacf402aa2151a6a7155dc6fb598697fa1&scene=21#wechat_redirect)》

0132-《[使用Hue创建Ssh的Oozie工作流时重定向输出日志报错分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486786&idx=1&sn=92858c55f0417322c8dbd3814e1ce4ae&chksm=ec2add4bdb5d545d89586dd760de7ea7351c72a75a25f1fc95820de6e5fa0a3a02c674f7bc37&scene=21#wechat_redirect)》

0133-《[在Kerberos环境使用Hue通过Oozie执行Sqoop作业报错异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486794&idx=1&sn=91f2b1909aec4b416608745ac50f01ee&chksm=ec2add43db5d54553bd92bc7fe4c0167c966cba327f06420fb90a7cd8016fc484289b0471a80&scene=21#wechat_redirect)》

0184- 《[如何使用Oozie API接口向非Kerberos环境的CDH集群提交Spark作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487724&idx=1&sn=eed5801cce1dcdc2211afc63a28be654&chksm=ec2ac0e5db5d49f380d12b29215cd21f6d92bc2eb6c55b52a998da295d6d668b8f7140a7f570&scene=21#wechat_redirect)》

0185- 《[如何使用Oozie API接口向非Kerberos环境的CDH集群提交Java作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487725&idx=1&sn=c4aba0123b790c2b8bdee7fa78b2ee81&chksm=ec2ac0e4db5d49f292261c590871b2c06167e85ad998a35f5e091d1685fdf062c026ecbde5b2&scene=21#wechat_redirect)》

0186- 《[如何使用Oozie API接口向非Kerberos环境的CDH集群提交Shell工作流](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487726&idx=1&sn=79f961a7f491eb69a74879e41f32f208&chksm=ec2ac0e7db5d49f13d92e0da808aa170f2a1738dff20139697ad16fb062bafbdaa880bdace78&scene=21#wechat_redirect)》

0188- 《[如何使用Oozie API接口向Kerberos环境的CDH集群提交Spark作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487799&idx=1&sn=69db2dd086816ce2fa4c84140df942ef&chksm=ec2ac13edb5d4828bc438ab7358c0f0ae070c6c786535d549a971200ff06f7375304c79626ec&scene=21#wechat_redirect)》

0189- 《[如何启用Oozie的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487819&idx=1&sn=71267d0336c234b3ff30bca1302640fe&chksm=ec2ac142db5d48540d90083405182c427916d0952e5ab47d555e5ede273ac664f59cbeba978c&scene=21#wechat_redirect)》

0194- 《[如何使用Oozie API接口向Kerberos集群提交Java程序](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487931&idx=1&sn=1b698b84ebddc416b827ae847e7e60f1&chksm=ec2ac1b2db5d48a4d5403d804f07786ae674378d5208af987a02afc74561a77861a2646c98b7&scene=21#wechat_redirect)》

0202- 《[如何使用Oozie API接口向Kerberos环境的CDH集群提交Spark2作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488122&idx=1&sn=85c471b8144c5e7f2c8e78e9f03abd74&chksm=ec2ac273db5d4b65ac2274070d7809f6f1c40c90336a49512949abae0e6c541bee1c11c82a1c&scene=21#wechat_redirect)》

0207- 《[如何使用Oozie API接口向Kerberos环境的CDH集群提交Shell作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488230&idx=1&sn=000ccb5892ee3faefd35822e7e1b2ba6&chksm=ec2ac2efdb5d4bf9ffe4e9ad94a2359a38377da56d5707254cf03faff7e531ea5e16357c3ed1&scene=21#wechat_redirect)》

0296- 《[如何在Oozie中创建有依赖的WorkFlow](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490566&idx=1&sn=2c2d20c94b708fb7f80a71c2fbe0923d&chksm=ec2acc0fdb5d4519cf91d81022c236553c6ae0876c42923af60bc8bfa6d03ef375f1d7edbd1e&scene=21#wechat_redirect)》

0462- 《[0462-如何在Hue中创建Shell Action工作流续](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493798&idx=2&sn=a3382bc9984ca2e0f74cd46037b0d820&chksm=ec2938afdb5eb1b9d614260755f279929b6597fe01db6a61e7c2cc4301b8e56b4f290ba7ea32&scene=21#wechat_redirect)》

《[0535-5.15.0-Oozie中创建Ssh Action指定ssh端口号](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496090&idx=1&sn=c2e4852ae163d53d6ddfcc349f5b224a&chksm=ec292193db5ea885301580b2f9db4bdb00535b2ad961c5532ed64b568bdad580666691264e0d&scene=21#wechat_redirect)》

《[0590-6.1.0-C6升级过程中Oozie共享库的问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497020&idx=1&sn=15b53c1bbeb4b1dd47628a5b5e28fc7d&chksm=ec292535db5eac23620bdce150723b6bc238c96c5594677876eb1f4fa9829e2e3c77d15c7c5a&scene=21#wechat_redirect)》

《[0782-5.16.2-Oozie配置Sqoop定时任务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502429&idx=1&sn=124c4397c327911bcd28361f9f56683c&chksm=ec291a54db5e9342eb0551d596aa6c37a41af9f8f0340ff653326c18223d38e7deb7597a8b33&scene=21#wechat_redirect)》

《[0800-5.16.2-如何禁用Hue中Oozie的部分Action](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502848&idx=1&sn=c9a0a79f825e529c2dec15d4558163ce&chksm=ec291c09db5e951fd1cee5eba0ba7d6ab9d915e9d50fa1485015d651c73fb4b6939b1bcb2de5&scene=21#wechat_redirect)》



**7.8.HDFS**

0068-《[如何在CDH集群使用HDFS快照](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485437&idx=1&sn=e7c1e091fadafbedb0e68760cd7d4927&chksm=ec2ad7f4db5d5ee2ce4f7c1005f3ae349d7240f0b25bc0e1786d1827db0c1368d92b3b92d369&scene=21#wechat_redirect)》

0105-《[如何使用Java代码访问HDFS.docx](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486235&idx=1&sn=8c30514bcbefa25bdeff565957acf04b&chksm=ec2adb12db5d5204ad767723c60a9a41da967b7e75c9ae4e640e5be95bf6b93ebc94ad05e81e&scene=21#wechat_redirect)》

0125-《[如何在集群外节点跨网段向HDFS写数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486636&idx=1&sn=c2f94ee6f512e055b642350e2425e51e&chksm=ec2adca5db5d55b30b60c872a09bba5c7de71d5e945cbdf8213f841c05eba4a14bd0f9d9860c&scene=21#wechat_redirect)》

0130-《[如何将HDFS文件系统挂载到Linux本地文件系统](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486757&idx=1&sn=362f0c04778ac2cab81844c62570c18e&chksm=ec2add2cdb5d543aa0dd8afcce7b60b955a70962d576d95c479d7683e7f9a36f236e35765940&scene=21#wechat_redirect)》

0148-《[如何为HttpFS服务配置SSL](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487077&idx=1&sn=fd62ae494426c02e4845b0fa846cedff&chksm=ec2ade6cdb5d577a589e2761fd6da1e7727ee451c17be633d7de614d47a253c2430ebac3a5b3&scene=21#wechat_redirect)》

0209- 《[JournalNode的edits目录没有格式化异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488270&idx=1&sn=79b25b0281eeeaa287d9ec2ffe685710&chksm=ec2ac307db5d4a114dbf1052c2634e8dd0867f5fe6eb886a519140d0f590166fb257e1c7ba46&scene=21#wechat_redirect)》

0243- 《[Slow ReadProcessor&Error Slow BlockReceiver错误日志分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489099&idx=1&sn=2e1fd131b295470834d48184636ee6ac&chksm=ec2ac642db5d4f54616267c821ed05b9741c0eb09c919a784c915ff14bdd29408a08f03b518f&scene=21#wechat_redirect)》

0262- 《[HDFS部署最佳实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489557&idx=1&sn=65ff210ef504b82aee1435a0ae142747&chksm=ec2ac81cdb5d410af2148c3906e18daacb9dfd315df5c1b87aba69300f84458fcb17420884f5&scene=21#wechat_redirect)》

0264- 《[如何修改启用了高可用HDFS的NameService ID](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489613&idx=1&sn=4e05ab677e6f5c518c28d3bb66be5e99&chksm=ec2ac844db5d41525edd7996b8b3a6bcaa7dbc7acbc30d631dabfd57297a0a23cf81de920cbe&scene=21#wechat_redirect)》

0292- 《[如何使用Java API访问HDFS为目录设置配额](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490460&idx=1&sn=40041b4447b82da31201357541a52dbd&chksm=ec2acb95db5d4283d856aaebdb07b06e865ae9d55db0e298c8cff67d5286a7f63f96c0737e2a&scene=21#wechat_redirect)》

0341- 《[集群JournalNode服务重启导致NameNode挂掉分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491618&idx=1&sn=94881ce701931f529c7ed6053137ac7d&chksm=ec29302bdb5eb93d1c298c5f9ec736c1af3cb4be9fd6790e542964f6fb1ed6a881020962b56a&scene=21#wechat_redirect)》

0360- 《[NameNode Metadata备份和恢复最佳实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491916&idx=1&sn=4cf81b529f5d593bba4af1078039689f&chksm=ec293145db5eb85370707cf32ed333c41005a754b0f264eb541cea8d1032e6ab60c50da1ed3d&scene=21#wechat_redirect)》

0403- 《[如何在Hadoop中处理小文件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492796&idx=1&sn=5e15a9060f234d24c1fb112d9158970c&chksm=ec2934b5db5ebda381ced8a99e0170229e57c0692a03d73a087853f99a09a3ee9d4e83d57267&scene=21#wechat_redirect)》

0409- 《[如何指定Hadoop命令行日志输出级别](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492879&idx=1&sn=4500086b88f867a2102f44e88cfb914d&chksm=ec293506db5ebc105de96ebefae0a10a7539b0c57205ffd035ab2a18896d1bde993ac0eeff1a&scene=21#wechat_redirect)》

0432- 《[什么是HDFS的纠删码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493315&idx=1&sn=d0db04489c2cae2d7f11e683f77b62c6&chksm=ec2936cadb5ebfdc0ddc80f4489d48bf61140f4e29ff8c6b445b294a0fa621945fd13d2f8329&scene=21#wechat_redirect)》

0435- 《[如何在CDH6.0中使用纠删码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493355&idx=1&sn=7dd8864669e65931606000eeb629b8a0&chksm=ec2936e2db5ebff4a23e951e5479e850d89849bb86c03a9ad466e9bd09e613391fab657e226d&scene=21#wechat_redirect)》

0443- 《[CM上HDFS容量显示与实际命令不一致问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493474&idx=1&sn=36e021679464ba421bde04e547c0d280&chksm=ec29376bdb5ebe7da26a1ae989731aa724e5a5adf9fc1d93adb03d7577550d105c83c88672ff&scene=21#wechat_redirect)》

0451- 《[如何使用Scala代码访问Kerberos环境的HDFS](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493616&idx=1&sn=eedc1f29c961896f8374bd59f3e65d64&chksm=ec2937f9db5ebeefc4312bfe44eb95cad588ec9569ac6111844652ee32b6ca1e71fe04e1811c&scene=21#wechat_redirect)》

0455- 《[如何在Hadoop中处理小文件-续](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493657&idx=1&sn=1ed62012b73bc966949a7f5df469106a&chksm=ec293810db5eb10688beabd5495c6ee84aa73161d76283add0aee347c03d28f5bab802789e76&scene=21#wechat_redirect)》

0460- 《[0460-HDFS纠删码的机架感知](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493787&idx=1&sn=174abf70561bd4b6c4d83d4a81626710&chksm=ec293892db5eb1848a912459de16b5f6d18bd2abdcae89a838f3cae94d58e799bdff67306526&scene=21#wechat_redirect)》

0464- 《[0464-如何离线分析HDFS的FsImage查找集群小文件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493966&idx=1&sn=dd02b485d7037fcddb56d93b212e555c&chksm=ec293947db5eb0516112d725c33f1339de7c1d0d45b76d6fb11f9defe3f4e71fd2fbb876d3d4&scene=21#wechat_redirect)》

0482- 《[0482-HDFS上一次检查点异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494877&idx=1&sn=a0b250a4bcae9c71ab6073763c43af0f&chksm=ec293cd4db5eb5c223fc0dcb161f05440f3e0052b55c458e2b37297520bcb1838e1f7a888337&scene=21#wechat_redirect)》

0494- 《[0494-如何恢复HDFS中节点正常解除授权丢失的数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495334&idx=1&sn=2dea8d2f71dfbb24a90d5a7bc3227bbd&chksm=ec293eafdb5eb7b91e75afdfc77c2a77a9d9027b3172c7bf92b6ef20e93fd0ebebdf48119f22&scene=21#wechat_redirect)》

0508- 《[0508-如何使用Hadoop的Archive处理小文件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495566&idx=1&sn=3532cba8d7166ca0372117c6b229c656&chksm=ec293f87db5eb691643383aa93c61c2998d58643d592526c4823144a30f85bdedf6deec7fdca&scene=21#wechat_redirect)》

0512- 《[0512-使用Python访问Kerberos环境下的HDFS](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495614&idx=2&sn=f5bd3ce67878fa9977bdb36393775de6&chksm=ec293fb7db5eb6a1a8263dfc9ff4ffda2d9f69339e09a7bc82b656742a9c3e6b2f7b829fda7f&scene=21#wechat_redirect)》

0521- 《[0521-Hadoop命令无法访问HDFS路径诡异问题解决](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495752&idx=1&sn=e6e76936a34c1d2a8b01791f3de90bc0&chksm=ec292041db5ea95794e8d4fbd2335118dfb77e9723c12b725bf022981b548f7bd3dce9cb2e78&scene=21#wechat_redirect)》

《[0524-6.1-如何使用Cloudera Manager启用HDFS的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495814&idx=2&sn=9147b220b1a82b59b8b6b298b1a48c0a&chksm=ec29208fdb5ea9999faa3416e37caa2af3b3d962129f8692389f072e6db27a696bd0d42247ab&scene=21#wechat_redirect)》

《[0525-6.1-如何使用Cloudera Manager禁用HDFS的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495838&idx=1&sn=07ace4c40c3327c19f195eaca85d84f8&chksm=ec292097db5ea9812fa57f6493ca25116cb124eb54bc0bc1beb8991fe0fd354c95dee804eb21&scene=21#wechat_redirect)》

《[0526-6.1-如果你不小心删了一个NameNode1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495873&idx=1&sn=2aa2057c70e954baa3cecd4ab2a8c170&chksm=ec2920c8db5ea9deb61c51a76d2d170df51ff7ff78f4ec9223123ee829791ff199a989b7d9ac&scene=21#wechat_redirect)》

《[0527-6.1-如果你不小心删了一个NameNode2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495907&idx=1&sn=e6325dfb60423a93ae2e2203c3899d90&chksm=ec2920eadb5ea9fccabb291eb0653f08b3f5342eca68897049a493ce0b4cfb00ab9fb4545109&scene=21#wechat_redirect)》

《[0528-6.1-如何迁移NameNode相关角色](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495920&idx=1&sn=314994063bf1ea679979ecb9f3b9930b&chksm=ec2920f9db5ea9efe8209ded14738c62bb3f676b1794941b0caf2b8d29c863c01a57e3989af5&scene=21#wechat_redirect)》

《[0530-6.1-如何只是迁移NameNode或JournalNode](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495950&idx=1&sn=7b541f4c629d243c2a9cf7157d150eb5&chksm=ec292107db5ea81166999c6f73c95578a63cd7e78e20d80c8dfd9a5cdd75e729b1825b4b5d1f&scene=21#wechat_redirect)》

《[0531-6.1-如何手动迁移JournalNode](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495974&idx=2&sn=e218979fd5faf7f173ce9997ea77d8e8&chksm=ec29212fdb5ea8393875338247fa65f097f97f934080d58bd74f26d390a40d725db005e9141f&scene=21#wechat_redirect)》

《[0532-6.1-如果你的NameNode服务器坏了并且无法恢复](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496030&idx=1&sn=79ed25755854de08aa4672eccf0fd5be&chksm=ec292157db5ea8410d813d62bf42ab93b3ba4171949ceef2584299b3efac08ca7a2306afa6c3&scene=21#wechat_redirect)》

《[0550-6.1-如何将普通用户增加到HDFS的超级用户组supergroup](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496339&idx=1&sn=3c8fcf36475ade4626ff16491b188a4f&chksm=ec29229adb5eab8cae0a66800d99535a034b07fa8802fdf0a8bdf45a1852d7d0b4bc7cda6375&scene=21#wechat_redirect)》

《[0564-6.1.0-HDFS超级用户(Superuser)和HDFS管理员(Administrator)的区别](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496575&idx=1&sn=ba872ef5f58b5cf6a5cb86600d2d57a9&chksm=ec292376db5eaa60549e3600690a4db673295d1bffdc9d8e4354176cd078784b64ec80d89de1&scene=21#wechat_redirect)》

《[0598-6.2.0-如何基于FTP的方式访问CDH中HDFS文件系统](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497240&idx=1&sn=5aebd568d52f44aceef99f231fca7233&chksm=ec292611db5eaf0737fd0b8d9a0c55fca2ab9e1c2dd2f8817055c0eadee0611d21efc5f03586&scene=21#wechat_redirect)》

《[0599-5.14.4-HDFS出现大量BrokenPipe异常处理](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497277&idx=1&sn=35f0737fedc01880ba651f64153859ae&chksm=ec292634db5eaf220f54f56c27cc6543154066823d314ba77dc7e54df92292a149edc4568565&scene=21#wechat_redirect)》

《[0616-6.2.0-如何基于FTP的方式访问CDH中HDFS文件系统(续)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497671&idx=1&sn=ea1cfecca220dcdbd7d91818b63fcffa&chksm=ec2927cedb5eaed854843c3df92aff605466fb5da7b2690e28bc89483964b6fb152295d80627&scene=21#wechat_redirect)》

《[0630-6.2-什么是HDFS ACL](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497983&idx=1&sn=1c5ff9042022c63df11b84e8c9950132&chksm=ec2928f6db5ea1e020b22c2b5fd05325dcc228da50150640cbdc6a5f9e5ed8ad313aa555bbf8&scene=21#wechat_redirect)》

《[0658-5.16.1-如何使用CM设置HDFS目录配额](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498515&idx=1&sn=af48f2bd4f1a005af446159db643ee81&chksm=ec292b1adb5ea20c12c7586f5c00b5dc69f50b1d285c7447f3a95d6a7ac74b5a249843fe6e4d&scene=21#wechat_redirect)》

《[0675-6.2.0-什么是HDFS分层存储](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499006&idx=1&sn=dbe4d0d23efc06f1d11a8acbf345d71c&chksm=ec292cf7db5ea5e19dfb0628e5c4e4fb330d3650d215c5c515875919571834096a8e0f5e6082&scene=21#wechat_redirect)》

《[0678-6.2.0-如何在CDH中使用HDFS分层存储](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499048&idx=1&sn=01623ed3b336ced4de7dfc821d23a3d8&chksm=ec292d21db5ea43735c7bbec7af0f809900699194a4c057dd6526af736e3cf3fcef2f72be8d7&scene=21#wechat_redirect)》

《[0692-5.16.1-外部客户端跨网段访问Hadoop集群方式(续)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499365&idx=1&sn=464f66df2f1f63a3b47a41d6e29fe1e0&chksm=ec292e6cdb5ea77a9d32931812bdc4a799080ac9b93f2798109984d1e03e218a0701a3593133&scene=21#wechat_redirect)》

《[0704-5.16.2-如何使用Hive合并小文件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499869&idx=1&sn=4ad3d8406fac59957c6b471f8f50753c&chksm=ec291054db5e9942e3ccc486101a1a369461ead324db7a9243154e096e686208a2e69aeb7f66&scene=21#wechat_redirect)》

《[0731-6.3.0-关于HDFS ACL的32个条目限制说明](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501120&idx=1&sn=a3256b9ac439830428dfbca31e0ed506&chksm=ec291549db5e9c5f9489938163636a6611835c7e631bb2d897f44c68de189f17ce4cc1a85da5&scene=21#wechat_redirect)》

《[0786-5.16.2-HDFS Default ACL继承与umask冲突问题分析及解决](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502481&idx=2&sn=5c214b77920c7a21c8b590ab60b733fa&chksm=ec291a98db5e938e1f88aee903faed9af1441fa6b059c6aa3ff365a7febe408caee01086a679&scene=21#wechat_redirect)》

《[0790-5.16.2-NameNode服务的edits不同步异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502627&idx=1&sn=8c422f0d4f6019795e616601ca9a81b5&chksm=ec291b2adb5e923cda6eadbed3d650586611980c194239c75298f89d2a5f4f39e7ff63a9201c&scene=21#wechat_redirect)》



**7.9.Kudu**

0020-《[使用JDBC向Kudu表插入中文字符-双引号的秘密](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484358&idx=1&sn=c7722cb3519b7efe2b0c932ac55f5bce&chksm=ec2ad3cfdb5d5ad96a6c5848dc4b450e52f2418d51fe8c9d69573da2ec54dba24c8eda6eba61&scene=21#wechat_redirect)》

0021-《[使用JDBC向Kudu表插入中文字符-cast的秘密](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484360&idx=1&sn=c4f1e91c73ca47de7f77e93b93495cf9&chksm=ec2ad3c1db5d5ad7c7f97b70006454e273bc191423505c20569f7bd5b52eef35646640c0ce1d&scene=21#wechat_redirect)》

0085-《[如何在Kudu1.5中使用Sentry授权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485826&idx=1&sn=89fa626b33f49fb1f81ba8c918ccad0a&chksm=ec2ad98bdb5d509da9ae68328526925f0e31a8bb3edf50ae2e2896e01bd8864d0925c5addbb3&scene=21#wechat_redirect)》

0128-《[如何迁移Kudu1.2的WAL和Data目录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486723&idx=1&sn=ebfae8921813c9de78e47f640ed79516&chksm=ec2add0adb5d541cd2eea5e89d432ca1ab789c4bbe0660bfe5f1de5b2fa7c0434a0eff5ca0e1&scene=21#wechat_redirect)》

0267- 《[如何使用Java API访问CDH的Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489658&idx=1&sn=0c72573377185f044cf01fda460e4a0e&chksm=ec2ac873db5d4165c5d96edeef9af4811e512db5e7f675794a6be21a71f579a8bf2f77edf3d6&scene=21#wechat_redirect)》

0452- 《[如何使用Java代码访问Kerberos环境下的Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493634&idx=1&sn=e0c28169586a6afdb4f0c5e753473638&chksm=ec29380bdb5eb11d2e21d40a2be7c60602b2c30af11c32321e4bd505d4ee99e1ec0207965442&scene=21#wechat_redirect)》

《[0538-5.15.0-Spark2 KuduContext访问Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496133&idx=1&sn=2eb1f83badca8f95ecea86f0e9dee2de&chksm=ec2921ccdb5ea8da2e811e2db9b7facd4a54db7d4f23c6f8e55bbd748083c532fa9aa7985010&scene=21#wechat_redirect)》

《[0611-5.16.1-Kudu表执行COMPUTE STATS 命令异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497580&idx=1&sn=bdf1e679e0f89d74a41458c48a5fa19a&chksm=ec292765db5eae734963491d350f4a81dda72bfb75d71d3b17b42ebae088951cced7a408cf93&scene=21#wechat_redirect)》

《[0792-5.16.2-如何通过Hive跨集群迁移Kudu表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502643&idx=1&sn=bc8ee9455c93bea46908f1cc9ccf98cd&chksm=ec291b3adb5e922cb5b0005734fea52873314b1e68d2635f70d0e0d6142f71d76a6e8d640ef0&scene=21#wechat_redirect)》



**7.10.Kafka**

0022-《[如何永久删除Kafka的Topic](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484384&idx=1&sn=334edf7ff79758f2173e02371b1f6675&chksm=ec2ad3e9db5d5aff35c472d7601226ccf027de230c2cac8232d60cc943be5d2b77dc912e9001&scene=21#wechat_redirect)》

0065-《[如何通过Cloudera Manager为Kafka启用Kerberos及使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485371&idx=1&sn=e4c7cc77c2354634059295d5cf63b815&chksm=ec2ad7b2db5d5ea46406cb9d26c95f7d6cf52740e90a131f97909bbfaa10c8d4a751cc2bf1e8&scene=21#wechat_redirect)》

0069-《[如何使用Java连接Kerberos的Kafka](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485439&idx=1&sn=d8a0cafdb988b0b04fb42f1e41fed35b&chksm=ec2ad7f6db5d5ee071ca4e131635080c73971e2ee9c385b43859493f316f4c1248d947cf255e&scene=21#wechat_redirect)》

0324- 《[如何在CDH中为Kafka设置流量配额](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491270&idx=1&sn=fefc9a600d49810eeac40586f0eb1680&chksm=ec2acecfdb5d47d9c1c35b836f4405bb085bd71c4f62060131484412dea91b03fb484fa115bc&scene=21#wechat_redirect)》

0362- 《[如何查看Kafka的Topic消费情况](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491973&idx=2&sn=c3dcc326b419860f0e9ac98ae21e840f&chksm=ec29318cdb5eb89ad04892a409ff090e8a6171366fb933b8c6b4e341ce21e43c0e603bf44449&scene=21#wechat_redirect)》

0363- 《[如何在Spark Streaming应用中使用Kudu管理Kafka的Offset](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491973&idx=1&sn=aa30019fba49de1e9803e2dc97c72956&chksm=ec29318cdb5eb89a6d05bb8cbfb9aa7ab6da9819a1030169703bcda3a52751bc73d8d1e44559&scene=21#wechat_redirect)》

0370- 《[如何实现Kafka的Partition重分配](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492074&idx=1&sn=b4fb1dd1ae2ae9870896bd36bbb0ef24&chksm=ec2931e3db5eb8f5eae0366e872d2dc920a709608288992aa6112e9d5d00333a69d9d3c0ca70&scene=21#wechat_redirect)》

0374- 《[如何在CDH集群中部署Kafka Manager](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492158&idx=1&sn=24a37a621d8f06c29e72aab96cb82029&chksm=ec293237db5ebb21f4772ca996383b9effd9ef70d1ef05a9b5bd81a8066ddae6b2d7bfde3d4e&scene=21#wechat_redirect)》

0383- 《[如何通过CM升级CDK至3.1.0(Kafka-1.0.1)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492375&idx=1&sn=3af008984af15aac68e69e5aa58731c3&chksm=ec29331edb5eba08b264bfa4f11573ecd8f75b048ee276b8e48fbef8a1b2ccc9590fdc632179&scene=21#wechat_redirect)》

0404- 《[如何规划设置Kafka Broker的heap size](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492802&idx=1&sn=a31fd99344a315db0dd92eed8a4f626f&chksm=ec2934cbdb5ebddd17e15cc82189cd7e860f3b10ef5df206ee5cc312f16dc5598f7f734c052b&scene=21#wechat_redirect)》

0500- 《[0500-使用Python2访问Kerberos环境下的Kafka](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495475&idx=1&sn=f889461ce032bc79f13e5b78f86aef35&chksm=ec293f3adb5eb62cf3d2a9380f924f63de74321216a42cc5bd7ef4536bd26f767febda2851d5&scene=21#wechat_redirect)》

0501- 《[0501-使用Python访问Kerberos环境下的Kafka(二)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495489&idx=1&sn=8f9a294081cb605630c8b2167cf07ba8&chksm=ec293f48db5eb65ee00a6714289ec30ed813c0c7d948c1003d9801088c92e318be03d358c54d&scene=21#wechat_redirect)》

《[0542-6.1.0-非安全环境下Kafka管理工具Kafka Eagle安装使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496198&idx=1&sn=36715914f351e96ad0d2cc7c688e1949&chksm=ec29220fdb5eab19c050cf5e69b56014802d20d15bc83197d96bf13b9cdf891f635bcf94c02b&scene=21#wechat_redirect)》

《[0543-5.15.0-Kerberos环境下Kafka管理工具Kafka Eagle安装使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496212&idx=1&sn=7b16844d1db18c50e91ac0ed903436e5&chksm=ec29221ddb5eab0b02ba4613df0f86699c453ea7a6f0837745c4a08bce479976266f0f616a17&scene=21#wechat_redirect)》

《[0726-6.3.0-如何在CDH6.3中安装Streams Messaging Manager(SMM)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500986&idx=1&sn=cf1c64f094ea08fc69d53b02734da339&chksm=ec2914b3db5e9da535daf52c2f2680af4a6820fe41c4e77233c40ce5850268602d8c17ae0e3e&scene=21#wechat_redirect)》

《[如何在一个Kafka Broker的log.dir中移动partition数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501201&idx=1&sn=87e7c4c6f7263a15ee955dc8a57680a5&chksm=ec291598db5e9c8e97df6fddd79c6e5ff5fdcddb50563d38e6066b2a70cf82d2753bbad895ed&scene=21#wechat_redirect)》

《[0748-5.14.4-Kafka的扩容和缩容](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501501&idx=1&sn=9b360e88a79f954dc090e10b4ca5211b&chksm=ec2916b4db5e9fa2a255469c71f9fd46d15f8dd74a0ae3e860d57f4b6929c0369dcff758a338&scene=21#wechat_redirect)》

《[0749-5.14.4-如何实现Kafka Broker节点磁盘数据Balance](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501524&idx=1&sn=77315b54717818261a2b65b951286037&chksm=ec2916dddb5e9fcb2b7d314cda234d9c0adf25c45b2cb17f2f8829b49290687afd07f68d339d&scene=21#wechat_redirect)》

《[0759-Kafka2.3性能测试](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501818&idx=1&sn=67e17543566a7f14af6594a69ba27771&chksm=ec2917f3db5e9ee5e3620acc140d960d6302c234f04d0ec7884dcf7391f88549af84e8865ed5&scene=21#wechat_redirect)》

《[0766-6.3.3-如何实现Kafka跨网络访问](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502020&idx=1&sn=219510598a9c944a57627aefaf983fa1&chksm=ec2918cddb5e91dbfe090c8106087a1d395c9703b37562f2e38b4bfd43fdb13bc6ed071ba885&scene=21#wechat_redirect)》

《[0780-6.3.3-如何在离线环境下安装Streams Message Manager(SMM)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502389&idx=1&sn=2d84576076ab41875273b08329c551b7&chksm=ec291a3cdb5e932ac4a951d459b8d6592b939c0751c89e6851ce1e565a6c11f3e2618e8693b9&scene=21#wechat_redirect)》

《[0788-7.1.1-CDP安装SMM服务启动异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502586&idx=1&sn=16e53783e9fa2d7016e55ef2afba1535&chksm=ec291af3db5e93e591e80eb595b59adf21bdfad64b049bcb2fdbc1b575631e6740ad62028fbd&scene=21#wechat_redirect)》



**7.11.YARN**

0019-《[Yarn的JobHistory目录权限问题导致MapReduce作业异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484326&idx=1&sn=7444df7614437a5ad35f9d0c87c5cf2b&chksm=ec2ad3afdb5d5ab98106d45e6c058d445989258cb67309efb738919e83e52f22c57884629b0e&scene=21#wechat_redirect)》

0107-《[如何跨平台在本地开发环境提交MapReduce作业到CDH集群](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486257&idx=1&sn=4269786efc005fcedcf5dcf56c4d98d9&chksm=ec2adb38db5d522e1ce68681f4336c0a9744799aac6e1f19628a85f2b7e1d15c4960ceea53fd&scene=21#wechat_redirect)》

0108-《[如何使用hadoop命令向CDH集群提交MapReduce作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486271&idx=1&sn=5d3c407edc9c54d98c5bb81b12d4fdc0&chksm=ec2adb36db5d5220a102634f148df4aa9db007687356ccc4cf8c27d64aabd7dc308f24a84144&scene=21#wechat_redirect)》

0109-《[如何使用java命令从非集群节点向CDH集群提交MapReduce作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486286&idx=1&sn=f4b4a19a6044aefb4e5539ba58fccfc7&chksm=ec2adb47db5d525171db04aaef0a603a6fb621761628ae7bce61e0501b27f8a4e3c5db0723ac&scene=21#wechat_redirect)》

0129-《[如何在HDFS上查看YARN历史作业运行日志](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486738&idx=1&sn=d2f2dca5ba9ed34cd175e7d3535786f0&chksm=ec2add1bdb5d540d6071356d98631b5393790890d3326eb2cccb8adb37b0717c50dc9e86514d&scene=21#wechat_redirect)》

0291- 《[如何使用Cloudera Manager设置使用YARN队列的ACL](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490436&idx=1&sn=db264867fa87300ce9a4992509beebc9&chksm=ec2acb8ddb5d429b4834b7c83dbd40b9b83e7b01d88fdc1f44f9960c7aa61458fb8f8d952c10&scene=21#wechat_redirect)》

0353- 《[如何使用curl命令调用CM的API动态配置Yarn资源池](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491821&idx=1&sn=50b18a40e7afb76a3ae76daadefeb08a&chksm=ec2930e4db5eb9f2959e0886229643e07d0a1eee2f115613b87cc8fd592097ffe9d31d47f528&scene=21#wechat_redirect)》

0354- 《[如何使用Java调用CM的API动态配置Yarn资源池](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491828&idx=1&sn=ae811a24fa2f341bfe8f6e2cb0c2031a&chksm=ec2930fddb5eb9ebb82ab9fc5ec9b92adef4608c262c8930717e24c825e1b2e5933f7a9374c4&scene=21#wechat_redirect)》

0369- 《[如何在CDH中配置YARN动态资源池的计划规则](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492055&idx=1&sn=b43913b4e10fd774da33101e40fd25ef&chksm=ec2931dedb5eb8c8ab63318ea95fd7168ae0706e575f870771519b702da82a5d0e34d1bcc263&scene=21#wechat_redirect)》

0421- 《[如何在不重启Yarn服务的情况下启用DEBUG日志记录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493107&idx=1&sn=4bcdef1fdf8f339c5c07bb411104b770&chksm=ec2935fadb5ebcec0e7b56bf629a5ba802cfd015648ff795795a29475465f94657c0c424be88&scene=21#wechat_redirect)》

0426- 《[如何在Cloudera Manager中配置Yarn放置规则](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493182&idx=1&sn=a7eb64d814acadc3029b9501f618c908&chksm=ec293637db5ebf2106f3f47c3a12fd1a5f344f51ef769a1f6b92a41f2b9ebda6e7413899da58&scene=21#wechat_redirect)》

《[0529-5.15.0-这次玩儿大了，找不回了](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495934&idx=1&sn=bacdb245acdd959b77f3e9dd94ca84a9&chksm=ec2920f7db5ea9e1add86f9803579c678e31dcb055a3af1d5dddc7506bc1904853d03694b886&scene=21#wechat_redirect)》

《[0533-6.1-如何使用Cloudera Manager启用YARN的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496062&idx=1&sn=1d314ce11b00249a35388f9a5fb81633&chksm=ec292177db5ea861f9cf04022e425d54e7db7454990c08afe058bc443b0c51fc6f4c38b781c5&scene=21#wechat_redirect)》

《[0534-6.1-如何使用Cloudera Manager禁用YARN的HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496073&idx=2&sn=fd0210d67faf7dcc69dd5e6acf8cbae1&chksm=ec292180db5ea896a9875acf2683f1395f2296a76b9637cef33ee3c24610fd4cda4f4c62d193&scene=21#wechat_redirect)》

《[0588-6.1.0-命令行动态指定MapReduce运行参数无效问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497001&idx=1&sn=0491c9f8d003964f9a853ff807664a98&chksm=ec292520db5eac361e475ff28790376999e2b5d3f3923a400d3ac4d91ad3fb018e9ca6f0c756&scene=21#wechat_redirect)》

《[0606-6.1.0-NodeManager丢失文件启动失败异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497418&idx=1&sn=c0b0dbd853a002b116c99f954b6e6439&chksm=ec2926c3db5eafd5d9b7ad5d1915436ed3b8c02752c68d48c0b19698b1c44fb316c01e0fa026&scene=21#wechat_redirect)》

《[0620-5.16.1-如何设置MR作业的Map或Reduce日志级别](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497736&idx=1&sn=cfc14ce040363aa2513f5d73ae90fc5b&chksm=ec292801db5ea11732d4f1bac044fb727a06b2d799460a028260b36afa824ff6c6d0dd82f0ce&scene=21#wechat_redirect)》

《[0652-5.16.1-目录挂载点nosuid参数导致NodeManage启动失败异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498402&idx=1&sn=bd48c1e92e7768b364ba7515090045cc&chksm=ec292aabdb5ea3bd8660f2cf507d6ee96d9ba69bab35b8be8774a7aca0f22ec721e8c616d159&scene=21#wechat_redirect)》

《[0747-5.16.2-YARN日志聚合目录说明](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501430&idx=1&sn=3e112dcaeac2c5a9221613f2e9d31278&chksm=ec29167fdb5e9f694b094f3f84d136a2633d224d1ebf6883e61e7eb64d865b4b50e7b2deae1c&scene=21#wechat_redirect)》

《[0760-7.0.3-如何使用Cloudera Manager设置使用YARN队列的ACL](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501846&idx=1&sn=d15a5e5a94130ab95f643cea978572c1&chksm=ec29181fdb5e9109ccdf620289940dd3d2d08d2636a940ee4c98dd1d0c376ac19aa6149aa042&scene=21#wechat_redirect)》

《[0761-7.0.3-如何使用YARN Queue Manager UI配置集群资源](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501883&idx=1&sn=d968a8f81c2e7686e4d62c56e7fecc1e&chksm=ec291832db5e9124d5ef5480ef04414ef0783f97ada988da03785b21c47e1be86819b93fd4b8&scene=21#wechat_redirect)》

《[0770-Apache YuniKorn (Incubating) 0.8发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502112&idx=1&sn=a74f0ee9da6fd5ab3d0f35d7a67b25b1&chksm=ec291929db5e903f071b7da9a49305c9fe3bbd2c47af6e0af8c2e602274795ed326da565fb4b&scene=21#wechat_redirect)》



***\*7.12.Spark\****

0016-《[Avro序列化&反序列化和Spark读取Avro数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484262&idx=1&sn=4a51f7164415cb510a44113f0015b877&chksm=ec2ad36fdb5d5a79bf52174087e801f2e8a784139d141c747b7dee4c232009fbd1ddae7d5fb3&scene=21#wechat_redirect)》

0017-《[Spark的HistoryServer不能查看到所有历史作业分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484263&idx=1&sn=7d6441ab1ed4707c3fee552dcc445f1e&chksm=ec2ad36edb5d5a78ee3bfb0271750c9905ebc8c9041198c1eede0474c4a4da89c8a04d2d6f2f&scene=21#wechat_redirect)》

0041-《[如何使用Intellij搭建Spark开发环境](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484966&idx=1&sn=5fe4b2699cfa6b88491b46d44d3ab77c&chksm=ec2ad62fdb5d5f39089e4d8d6c11858a8663079f4358eca104e57fe95ce8aed089b7fdea4880&scene=21#wechat_redirect)》

0064-《[如何通过Cloudera Manager配置Spark1和Spark2的运行环境](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485357&idx=1&sn=33429b8ef94b68a0d8c64e5ef76aa4a0&chksm=ec2ad7a4db5d5eb284bece2f47c0c40e437fbcea2f18e963366291b20cc8ae495e6d0eaa8bc6&scene=21#wechat_redirect)》

0079-《[如何在CDH中启用Spark Thrift](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485731&idx=1&sn=00014c98f0ace15018c82a79ea02a7d9&chksm=ec2ad92adb5d503c56dd0b7e42b84cc0690087f2eea0a698e7bd16890cc89f7e20e0a641c734&scene=21#wechat_redirect)》

0176- 《[Livy，基于Apache Spark的开源REST服务，加入Cloudera Labs](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487592&idx=1&sn=7963efaa5288d456fb59f0acceb01731&chksm=ec2ac061db5d4977c6a7783e2961cadc3ee09a5a3939bbfa941fa7537f4af05d64bccea9f1f7&scene=21#wechat_redirect)》

0177- 《[如何编译Livy并在非Kerberos环境的CDH集群中安装](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487626&idx=1&sn=ec203849eaf4fa6809058b89e0a0776f&chksm=ec2ac083db5d4995d11d08a38362ba90332a8bcec9b02875f40f87878f2ad3d9055a2e384097&scene=21#wechat_redirect)》

0178- 《[如何通过Livy的RESTful API接口向非Kerberos环境的CDH集群提交作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487686&idx=1&sn=2d64bcdb7cced159508fd98b7e1ad623&chksm=ec2ac0cfdb5d49d944bcb74173c8914c8a9fbda3743cde459aeb053253237875101558a8147e&scene=21#wechat_redirect)》

0182- 《[如何在Kerberos环境的CDH集群部署Livy](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487722&idx=1&sn=e17aa3cb46a8924d296f9ab9b8ba1588&chksm=ec2ac0e3db5d49f51f5ac299e9619c7a25f354290117a127f5c1b49a467d1f2e9479f4654210&scene=21#wechat_redirect)》

0183- 《[如何通过Livy的RESTful API接口向Kerberos环境的CDH集群提交作业](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487723&idx=1&sn=f38eb15dd240dcc0a403221d77ad9fe5&chksm=ec2ac0e2db5d49f401311818ae5934ca49a8802b25ef39d8a25965af0ba1d5e254030b7e9df6&scene=21#wechat_redirect)》

0278- 《[如何在Kerberos环境下的CDH集群部署Spark1.6 Thrift及spark-sql客户端](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490036&idx=1&sn=754dc2a3138c20e10a717780aa58c8fe&chksm=ec2ac9fddb5d40ebe5e409257d99016d5670c8c9dedfaef1035ab9c8e46b5bf9af09092deed6&scene=21#wechat_redirect)》

0280- 《[如何在Kerberos环境下的CDH集群部署Spark2.1的Thrift及spark-sql客户端](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490081&idx=1&sn=863a4aa895d320a77f1e37a3a14e1fd7&chksm=ec2aca28db5d433e292d09c1847f29cdea66d369784af9e7bdfc8ef96be8d11ff73e5008ae58&scene=21#wechat_redirect)》

0281- 《[如何在Kerberos环境下的CDH集群部署Spark2.1的Thrift及spark-sql客户端](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490110&idx=1&sn=6f354a99cc04cba71d2a899515a68fe7&chksm=ec2aca37db5d4321caeab129feee5715c252ad165aa221474c8e019f61b795116bae87a2f262&scene=21#wechat_redirect)》

0285- 《[如何使用java连接Kerberos和非kerberos和kerberos的Spark1.6 ThriftServer](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490265&idx=1&sn=3a49ed0d35b397b1c440ca803634f30d&chksm=ec2acad0db5d43c669d1b0f2e51dec72e77ccbe07e4cd45aed9e474bd9c1348dc96a59bf6776&scene=21#wechat_redirect)》

0373- 《[如何指定Spark2作业中Driver和Executor使用指定范围内端口](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492135&idx=1&sn=6e135b6ceb2495e0d62ed8937bb7fd25&chksm=ec29322edb5ebb385d7c264e381fc731e6d9cebf49972d039115338c1800d4c67fb7702ea2c7&scene=21#wechat_redirect)》

0438- 《[如何指定Spark1作业中Driver和Executor使用指定范围内端口](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493395&idx=1&sn=48d6aaadcf363c85a31a9a8c8fb2eddd&chksm=ec29371adb5ebe0c9206d6835ce907e1d7984b4beb580f0dd4d1251cf7bf4a5b5fbefb740260&scene=21#wechat_redirect)》

0445- 《[如何为Spark应用启用Kerberos的Debug日志](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493490&idx=1&sn=de8191b5425287cc1f02fae4403d5e98&chksm=ec29377bdb5ebe6da2b5319568b4782f047004ef521004639786645baea4c392e369f437cccf&scene=21#wechat_redirect)》

0483- 《[0483-如何指定PySpark的Python运行环境](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494921&idx=1&sn=11f07514eb0521fb2eb490e81afeb8dc&chksm=ec293d00db5eb41624a9415205e5c0466755ab4ca300c995678f25b0d28b0cb9cad5339866af&scene=21#wechat_redirect)》

0485- 《[0485-如何在代码中指定PySpark的Python运行环境](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495123&idx=1&sn=c5848683b7ea4693879719de638470db&chksm=ec293ddadb5eb4cc29f979a24fa3d3cc8c8634647d07b94b047a19faf7de99a86ff84745ea87&scene=21#wechat_redirect)》

0510- 《[0510-Spark应用访问Hive报错异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495596&idx=2&sn=6a13cdf4f81c9612c964275fa24ebcb9&chksm=ec293fa5db5eb6b3a6b5e4f10059d6307216ee90528face701ab9962e62ade55ebf2453fb4cf&scene=21#wechat_redirect)》

《[0639-6.1.1-Spark读取由Impala创建的Parquet文件异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498155&idx=1&sn=6d56bfddb89b7e527fcc5ff3d00af0e9&chksm=ec2929a2db5ea0b40c60129a33ce8253e68db20b24438f11cfdb3cd95be2c44b098b95d17f17&scene=21#wechat_redirect)》

《[0643-Spark SQL Thrift简介](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498257&idx=1&sn=591d0685a194baf3fd71101dab09bc6b&chksm=ec292a18db5ea30e747f09c6ae7360484f6cc51b8dd0bdc872339c9e5fe678396417be8ba3f4&scene=21#wechat_redirect)》

《[0644-5.16.1-如何在CDH5中使用Spark2.4 Thrift](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498290&idx=1&sn=fc68896235381aff10c23157e0622089&chksm=ec292a3bdb5ea32d90e5621ade2842584d536f2c4263150573e285555156df1cef27bb7fc7c0&scene=21#wechat_redirect)》

《[0645-6.2.0-为什么我在CDH6上使用Spark2.4 Thrift失败了](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498321&idx=1&sn=cf455c1ec98cfbcdba64f52f01399912&chksm=ec292a58db5ea34e7e3b183af3f925a6fc3b97ae213f5d9ed183995d23cada6374798bf16179&scene=21#wechat_redirect)》

《[0764-HDP Spark 2.3.2访问外部Hive 2的配置及验证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501977&idx=1&sn=e885b072448a06166894fef4205e2774&chksm=ec291890db5e918680d775ce6638b106e5ea0c92590602c2f1a297ace1ddc5665c70aa7ce57d&scene=21#wechat_redirect)》

《[0778-7.0.3-如何在CDP中实现你的第一个Spark例子](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502330&idx=1&sn=ecd580b3441592cb1de8df42bd6898c7&chksm=ec2919f3db5e90e545ebf57eb0a9326071a5914693174ab8f0509d8cb1c883c8d59b7235add7&scene=21#wechat_redirect)》

《[0785-基于CDP7.1.1的Spark3.0技术预览版本发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502458&idx=1&sn=2d62620461971c4dad8ad7fa44a94560&chksm=ec291a73db5e93657a972a4f9f3e6a2748c8aae37d70112bf22e72bad721ddd00a4ee03fc21e&scene=21#wechat_redirect)》



***\*7.13.Zookeeper\****







0006-《[Zookeeper指标分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247483854&idx=1&sn=9362310c2715e04060dd58f25ee9e5bb&chksm=ec2ad1c7db5d58d1caec15ca32e9f5b6fb150a1b1f8ea5025e59ba5cd4c43b4cba3f0fc0ccde&scene=21#wechat_redirect)》

0101-《[Kerberos环境下删除ZooKeeper服务注册信息问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486195&idx=1&sn=8e86535a9a56ce050825ca6afe4c0099&chksm=ec2adafadb5d53ecfd253a3b49664d4c0d273a99f6623b9ae45a5aa503380be169c4f766041e&scene=21#wechat_redirect)》

0239- 《[集群启用Kerberos后对Zookeeper的Znode操作异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489047&idx=1&sn=6e7b3b35408b1b7d09f8c9cf4e18e38a&chksm=ec2ac61edb5d4f086fb350eb90717c71c722ec47d54f7c079b6dc82f8f06cf6c4250e0b5a75c&scene=21#wechat_redirect)》

0381- 《[如何通过CM迁移Zookeeper服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492327&idx=1&sn=4f846a1cdde0d7d51658930df604b47f&chksm=ec2932eedb5ebbf8ea5de34269b66d7dcd204063091d7148b848c578d96fc1fc3dc2f3ad0fb9&scene=21#wechat_redirect)》

《[0793-5.16.2-如何迁移单个Zookeeper实例](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502666&idx=1&sn=39c9c34401a62de6e464e51672baa2ce&chksm=ec291b43db5e92552452045fc2f6c789419f0c76a957e0acef44f83fc48d2fa69c2a9a69f8b4&scene=21#wechat_redirect)》



***\*7.14.NiFi\****





《[0622-什么是Apache NiFi](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497787&idx=1&sn=d556f0adb0fb500f8a71147eac836508&chksm=ec292832db5ea12402cfdea0d2f20a60161f0f34808644986149e6f67a0d953acbb3a682df5b&scene=21#wechat_redirect)》

《[0623-6.2.0-如何在CDH中安装CFM](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497836&idx=1&sn=c2ed4fb1da413bcb317ddd5c9a7a5193&chksm=ec292865db5ea173b48ec603ad3914b93cd90b0ebddca63d211b61358cd29f781bb6399bbb53&scene=21#wechat_redirect)》

《[0624-6.2.0-NiFi处理器介绍与实操](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497869&idx=1&sn=2ce9d1a0f25a0c934605a13e95ff7fa0&chksm=ec292884db5ea192ea42503b8a224a22b4bc3c91f02e48ba36f02c901b6686c073f1eec49492&scene=21#wechat_redirect)》

《[0625-6.2.0-Hello NiFi-第一个NiFi例子](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497894&idx=1&sn=bbc2f885077429e407e61e9b7fbff233&chksm=ec2928afdb5ea1b93cbeae1f62b72631f5deb17155a1d401e6258975f9fcdba5f16fa399fa44&scene=21#wechat_redirect)》

《[0755-如何使用Cloudera Edge Management](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501741&idx=1&sn=0ce144a7247400c8e858991411224cff&chksm=ec2917a4db5e9eb2dbdf7b3d48d4813fd04078d04ba51d161f573b1b51de5f5c263385089d4c&scene=21#wechat_redirect)》



***\*7.14.Flink\****





《[0727-6.3.0-在CDH上运行你的第一个Flink例子](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501008&idx=1&sn=80087fcd503815b8ee707244702e767a&chksm=ec2914d9db5e9dcf584a9f839d07dc5a5911338fbb4f7687ec98acb736ef314d44fd6a257dfe&scene=21#wechat_redirect)》

《[如何获得Cloudera的Flink Parcel包](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501132&idx=2&sn=5e4e6f1a00ecdaf3da77c67e9db0a757&chksm=ec291545db5e9c53e6388049edb5cdcf040fc5f67ffba5009e234d29615ecae896e057a84587&scene=21#wechat_redirect)》

《[0750-7.0.3-如何在CDP DC7.0.3集群部署Flink1.9.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501550&idx=1&sn=38112fb0769e239d6b2f5164d2b51a55&chksm=ec2916e7db5e9ff193e27b72bee64bed8b7cfe01b80f6e4afc1dc7f864dab27654cdc78a6b7d&scene=21#wechat_redirect)》



**7.15.WXM**





《[0787-6.3.3-如何在本地集群安装Workload Experience Manager(WXM)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502550&idx=1&sn=c80418d5bed23721e2e4699782e2ec47&chksm=ec291adfdb5e93c9ef9b247d8755654187757dd05ef82a584e2cf7c0e33984f92267e45b0403&scene=21#wechat_redirect)》



**7.16. Atlas**





《[0797-使用HDP或CDP的Atlas采集CDH6的元数据和血缘](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502744&idx=1&sn=f33fafd6fe40de871fe34ba87d285cb1&chksm=ec291b91db5e92879f8b544bce248a650492f0a159fd2260779267662ff71f9b7817bf4f5bd3&scene=21#wechat_redirect)》

《[0819-使用CDP7.1.3的Atlas采集CDH5.15.1的元数据和血缘](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503258&idx=1&sn=12dd12ab1a931b4dfb6024760219fb54&chksm=ec291d93db5e9485ac69a154262d77eb350d97255954c6456296365a991b8a1e31c15389a2cf&scene=21#wechat_redirect)》



## **多租户**

***\*8.1.静态资源管理\****







计划中...![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)



***\*8.2.动态资源管理/YARN\****







计划中...![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)



***\*8.3.动态资源管理/Impala\****







计划中...![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)



***\*8.4.安全\****

《[0784-CDP安全管理工具介绍](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502451&idx=1&sn=92d8493eab435cee66c72fa1252b1dad&chksm=ec291a7adb5e936c28f4efd92f95bcde77436494bb871227e175162d79aa354e0201ace3fea9&scene=21#wechat_redirect)》



***\**\*\*\*8.4.1.认证\*\*\*\*\****

***\*8.4.1.1.Kerberos\****







0005-《[Windows Kerberos客户端配置并访问CDH](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247483853&idx=1&sn=442a8ba87c922857253a437affe42506&chksm=ec2ad1c4db5d58d2933ae5cde4ab1a7443c944e94aca85b51cbd8e9f4f3772162a39074da49d&scene=21#wechat_redirect)》

0027-《[如何在CDH集群启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484735&idx=1&sn=b021eb28562d566b5d3c97f3d4024905&chksm=ec2ad536db5d5c2017b61638eeb3bbc5640cff080e2a376923f3cb06ba4e57211fee4fc027e8&scene=21#wechat_redirect)》

0087-《[如何配置Kerberos服务的高可用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485861&idx=1&sn=bb930a497f63ac5e63ed20c64643eec5&chksm=ec2ad9acdb5d50ba9f3989f582bd041373733a2916b9e9eee1cb83d8195b3f50dcee9c95e83c&scene=21#wechat_redirect)》

0173- 《[如何在Redhat7.3的CDH5.14中启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487514&idx=1&sn=10c67e4e6456c32d4d4375925c3544aa&chksm=ec2ac013db5d490584631e58745e7306e991605decd7e0931865fb7dc04eb00b29eb074eb221&scene=21#wechat_redirect)》

0271- 《[如何禁用CDH集群Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489817&idx=1&sn=e526d7fb471016b3db3fd61be3b77441&chksm=ec2ac910db5d40069f927fe8f69cd3728eddea50997523952b56fad0ccc58bfcdd75bae39f0f&scene=21#wechat_redirect)》

0273- 《[如何在CDH6.0.0-beta1中启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489911&idx=1&sn=ddbcccaea06a27b14900c997e60a1c25&chksm=ec2ac97edb5d4068d121d375d6f9484edb8c6f242de3026d72405f93c2fe26495dddae243829&scene=21#wechat_redirect)》

0319- 《[如何在Redhat7.4的CDH5.15中启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491142&idx=1&sn=61f64b37b4ed548ccbb7f92d57406885&chksm=ec2ace4fdb5d4759cf3dd697c55fc62dd18bcf7f7bc4c966e55d032ad7f58c16ad0da5ec8dfb&scene=21#wechat_redirect)》

0345- 《[如何将CDH集群的KDC从RedHat7迁移到RedHat6](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491686&idx=1&sn=33e9db982560db9190d3fedf3bbb6bf7&chksm=ec29306fdb5eb9792cd3715169befe1be549ef7aa1e8008e91ec2fae3fe34c66312c7a6919b2&scene=21#wechat_redirect)》

0389- 《[如何在CDH6.0中启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492524&idx=1&sn=73c086bd458614f26d488a86e76f4905&chksm=ec2933a5db5ebab38c0a69863f0a709140fc74788c798b39ba252c33ca543ecf4f1a3f867bea&scene=21#wechat_redirect)》

0477- 《[0477-如何在Redhat7.4的CDH5.16.1中启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494672&idx=1&sn=80b97ca91e97d94392d4c78695565844&chksm=ec293c19db5eb50fc094ac1a2fd97912110f2990183d329ded95f24269a77a3d6c56cd751acb&scene=21#wechat_redirect)》

0495- 《[0495-如何在CDH6.1中启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495377&idx=1&sn=7370d0fd397132718ad3023c451c4f78&chksm=ec293ed8db5eb7ce3f3799c5e130db5cbb10965efcdc6993d77cb3c60ca759907ee4977f97eb&scene=21#wechat_redirect)》

《[0552-5.15.0-同一OS用户下不同Kerberos用户执行脚本Principal串掉问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496372&idx=1&sn=2f836a0a83b345594cbcb21645f55194&chksm=ec2922bddb5eabab38dee3aa20ddd9c9799d58c7cab3f6707df1e9322a0105b1bed3c48d7267&scene=21#wechat_redirect)》

《[0553-6.1.0-如何使用Java代码同时访问安全和非安全CDH集群](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496384&idx=1&sn=09a1b860a4ab0ba51f51f0a809727ec4&chksm=ec2922c9db5eabdf3ea39ea11b0e39c1cb2e0f3d84848d13db32aa66856a8b32c8c30d9eb693&scene=21#wechat_redirect)》

《[0554-6.1.0-同一java进程中同时访问认证和非认证集群的问题（续）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496396&idx=1&sn=3e891e8447a08aae9e8d2a067bf47191&chksm=ec2922c5db5eabd3bba454cfe9085a968ecce0bc65474f6ea594423425ea7f389b3ae3f54dd5&scene=21#wechat_redirect)》

《[0555-6.1.0-使用Python并发访问认证和非认证集群](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496402&idx=1&sn=5f3f9e9e0262a3f143485a77a8a2285d&chksm=ec2922dbdb5eabcde43e1fce6bc1dd882f23bc14851630361acfe4d84dc4b440203ef860a066&scene=21#wechat_redirect)》

《[0578-5.15.1-Kerberos环境下Java应用程序认证超时异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496816&idx=1&sn=867ada468669c12213b3ae5324a0179e&chksm=ec292479db5ead6fd69307204c9d21a0f896e09966a590b4b171daec7c6e3fc623be79b0f2a9&scene=21#wechat_redirect)》

《[0579-5.15.1-Java 应用程序中修改Kerberos ticket_lifetime参数无效异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496839&idx=1&sn=77bb439c345e07658f15d1fbf9525413&chksm=ec29248edb5ead988e011b082524c25c319283daa6b401143eeece8b61da367510f594017a71&scene=21#wechat_redirect)》

《[0592-5.16.1-如何配置Kerberos高可用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497063&idx=2&sn=98d712cd884055766a03b3e520f46cdb&chksm=ec29256edb5eac785acb30fb7aff55d91d024ebae779df364d8101c4f80a1613022a227f435e&scene=21#wechat_redirect)》

《[0596-6.2.0-如何在CDH6.2中禁用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497187&idx=1&sn=62892966647bcf6d366a162dccbe65db&chksm=ec2925eadb5eacfc15c88bb355a4be6c92a5853f6243a486f28425d6ca2c68fff81860142395&scene=21#wechat_redirect)》

《[0614-5.16.1-同一OS用户并行Shell脚本中kinit不同的Principal串掉问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497645&idx=1&sn=0660cb69f2fca453bc647f7ac326301c&chksm=ec2927a4db5eaeb2f50e3afe50352e78ddc02b255b2dc5edc9a95187d8b3810b51475a469f57&scene=21#wechat_redirect)》

《[0627-如何跳过HiveServer2 WebUI的Kerberos验证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497919&idx=1&sn=24e45127662bc926c82c97721222c5a2&chksm=ec2928b6db5ea1a0cc118642471cbba01302f5527cdcd6351b9ee6905322ffc047f189c6a1c9&scene=21#wechat_redirect)》

《[0628-6.2-如何在CDH6.2中启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497961&idx=1&sn=193fbf3199d296acf4aa93e2237bf974&chksm=ec2928e0db5ea1f69d5bb4f567368ea2276ce15917a6b52e8a7761bbe9692fe02baaab598c22&scene=21#wechat_redirect)》

《[0641-5.16.1-如何禁用CDH5.16.1的Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498212&idx=1&sn=068a21410f4ba10e604d867a69d3fbb5&chksm=ec2929eddb5ea0fb5362a275bb328808771bf032641e209754e5528aa403763396967a3c1d4d&scene=21#wechat_redirect)》

《[0686-6.2.0-如何为CDH集群的JDK安装JCE策略文件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499193&idx=1&sn=eac58ccd5b23272f6d7951bb995817cc&chksm=ec292db0db5ea4a620b70b88f9926f6ec5b75727a4a4a80b4c0cae3c39d48d7ea43d1466a7bf&scene=21#wechat_redirect)》

《[0706-6.2.0-Windows Kerberos客户端配置并访问CDH](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499934&idx=1&sn=101cac775c2e1c5bdf8a004986e0f111&chksm=ec291097db5e9981559cc25db90e456f4f21cb3d1149dc474aa1d4046eb12f660b5c7a4f5e71&scene=21#wechat_redirect)》

《[0734-5.16.1-集群外客户端跨网段向Kerberos环境的Hadoop集群提交作业（续）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501222&idx=1&sn=8b76900f54c934b20dd3a0df6cd75bbf&chksm=ec2915afdb5e9cb905c7498efc393376b7b4733eabc540e31b0c107df23d95bf7cec63749998&scene=21#wechat_redirect)》

《[0751-7.0.3-如何在CDP DC7.0.3中启用Kerberos](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501581&idx=1&sn=57c8a9f9433529259a2b115452746caf&chksm=ec291704db5e9e1288b96950b8970a83948d85648ecb1e5772bec4330f086b50571a831c8e50&scene=21#wechat_redirect)》



***\*8.4.1.2.OpenLDAP\****







0137-《[1.如何在CentOS6.5安装OpenLDAP并配置客户端](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486919&idx=1&sn=3bb31ebea466b8f218ee7a3f09c50dac&chksm=ec2addcedb5d54d8cef30688a1c0b2e1e83699696e403a209100fa0d5878e44180bfe9b48755&scene=21#wechat_redirect)》

0138-《[2.OpenLDAP集成SSH登录并使用SSSD同步用户](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486920&idx=1&sn=10a6a3f9c8970619b4fe8702e650d7f9&chksm=ec2addc1db5d54d739c924e11e4844b5d97e28ce05e4e0e6e55c1c59dd7d3eafffc1684b3325&scene=21#wechat_redirect)》

0139-《[3.如何实现OpenLDAP的主主同步](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486942&idx=1&sn=0179d7e946ea3e938f3d943f19c523d5&chksm=ec2addd7db5d54c1e5cebb7d5ccab538115b8553ed65276a21f04600e5451616e81190cdb3dc&scene=21#wechat_redirect)》

0140-《[4. 如何为Hive配置OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486964&idx=1&sn=56e9061c549043d2a05b251ab1cfb1a6&chksm=ec2addfddb5d54eb148233209ece54dd0c515c534c1e2f9038ac70c4b7c7d9024c561dd40b9b&scene=21#wechat_redirect)》

0141-《[5.如何为Impala配置OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486973&idx=1&sn=af950732b28a18dc9b628bf0f0f09197&chksm=ec2addf4db5d54e2c722059f307571aa9dbbc2f0e2badc37e9bb001e55ac0b793ba78df91147&scene=21#wechat_redirect)》

0142-《[6.如何为Hue配置OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487008&idx=1&sn=b6e2f9a401352d6781a8aa2133ab3924&chksm=ec2ade29db5d573f53d859cfb0103cda6da32246c3d0f0d0fec39597b551f83878ee9018003f&scene=21#wechat_redirect)》

0150-《[7.如何在OpenLDAP中实现将一个用户添加到多个组](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487095&idx=1&sn=4d59949200afe3f48d899734e84ea93a&chksm=ec2ade7edb5d5768ee55958afc35d7e1b61f16dbfeb4ab0c2497a8865fce73200df2ad17e680&scene=21#wechat_redirect)》

0166-《[如何集成OpenLDAP+Sentry.docx](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487331&idx=1&sn=1f956cacbff1ad2994e529e21989ce87&chksm=ec2adf6adb5d567c789bad59e64c7f19256d13173dacb01263993a2887b59dc1b57f7057699d&scene=21#wechat_redirect)》

0226- 《[1.如何在RedHat7上安装OpenLDA并配置客户端](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488759&idx=1&sn=26139ca87d4fb3d19c78178ea07cd0cd&chksm=ec2ac4fedb5d4de871236fea9b15140cbd529c57d1292b4ae1d64e6f4ba2d595730066e4b9c9&scene=21#wechat_redirect)》

0227- 《[2.如何在RedHat7中实现OpenLDAP集成SSH登录并使用sssd同步用户](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488780&idx=1&sn=bbce4474b62ba35962ecbcf94598222e&chksm=ec2ac505db5d4c139927a5bb630eea9d1cdc16e6d8620351cb882b5cf181c9475969fe629416&scene=21#wechat_redirect)》

0229- 《[3.如何RedHat7上实现OpenLDAP的主主同步](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488809&idx=1&sn=5cb2c35e0784e93f277a6cd94e3d434a&chksm=ec2ac520db5d4c36f2674ff02a21c8f107f31439e0099d011226054ae32ab372e4730e5380af&scene=21#wechat_redirect)》

0233- 《[4.如何为Hive集成RedHat7的OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488924&idx=1&sn=1b3efd1e71a80a051ff01dd7351a9722&chksm=ec2ac595db5d4c838b583c7e4cb5e323ad41d5b497a64f275a35e3a0625d09eaf4565782677b&scene=21#wechat_redirect)》

0234- 《[5.如何为Impala集成Redhat7的OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488933&idx=1&sn=d176adad53cad036f059f93eaad8536d&chksm=ec2ac5acdb5d4cbadc3a38efe5315923b02e47a7ef617b83dc15cfcf12bead70e2d949ae3179&scene=21#wechat_redirect)》

0235- 《[6.如何为Hue集成RedHat7的OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488980&idx=1&sn=f952704d3bc186bf93b2e199d7ac5142&chksm=ec2ac5dddb5d4ccbb9663ff68156aabbffd09aa69c680ddb100ea62018ff2d81354c20d072aa&scene=21#wechat_redirect)》

0237- 《[7.如何在RedHat7的OpenLDAP中实现将一个用户添加到多个组](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489004&idx=1&sn=a3cfd2ec1f8eb2860f9182521f160f82&chksm=ec2ac5e5db5d4cf3af24db994ee911638f463a3c29c8bee14bd4387d2f5c06d33c4ae2aeea67&scene=21#wechat_redirect)》

0238- 《[8.如何使用RedHat7的OpenLDAP和Sentry权限集成](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489032&idx=1&sn=203ed1d6899bf704bd30a5b43321ad54&chksm=ec2ac601db5d4f17f06247a6bf23f5318a3abf1613c851e06836981bfdfab619089ff5172b90&scene=21#wechat_redirect)》

0361- 《[9.如何为Navigator集成RedHat7的OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491942&idx=1&sn=98c1c890928279c6bcb214954b8e3b50&chksm=ec29316fdb5eb879c1eeaacc348f4655acfb780cbfb8738404aa4b26961196afce6b39b02f8a&scene=21#wechat_redirect)》

0367- 《[10.如何在OpenLDAP启用MemberOf](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492025&idx=1&sn=570146059a70d6d8823e44af2a1f3ae5&chksm=ec2931b0db5eb8a636a2d139ed9cc5132a7bc86b6b9d6c173e1573b9490bd9ca2b31fbd92314&scene=21#wechat_redirect)》

0368- 《[11.如何为CDSW集成RedHat7的OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492039&idx=1&sn=c23977e6f042c25e067c48765aa98c75&chksm=ec2931cedb5eb8d8cec8beaa0364bf40979c5107baf0f3c14bc83397467a4d0c2129537a6f27&scene=21#wechat_redirect)》

0371- 《[12.OpenLDAP管理工具Phpldapadmin的安装及使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492103&idx=1&sn=1f9ee7117d9f2c4db5847e3bf8a5a6c8&chksm=ec29320edb5ebb18ac915d5e69073e035cf379130c96d9aa032eaf2b15de4962f7e924dfe2f1&scene=21#wechat_redirect)》

0386- 《[13.一键添加OpenLDAP用户及Kerberos账号](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492447&idx=1&sn=d1749bea154cb6d4289a88ea06759745&chksm=ec293356db5eba404d2efe119eb0d14d847ac9721477f358afbe230bf600c2bedf280d50a9f2&scene=21#wechat_redirect)》

0424- 《[14.如何为Cloudera Manager集成OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493143&idx=1&sn=ff895542c041421cd291c0b156a70da1&chksm=ec29361edb5ebf08599284aff2c94ba582c0a0efc3451197ef13d50f0d5310b418314495673b&scene=21#wechat_redirect)》

0492- 《[OpenLDAP管理工具之LDAP Admin](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495303&idx=1&sn=0bf1b49b68efea3bba5adb045f000ed3&chksm=ec293e8edb5eb7983fc0b2eaea3254471504f4a4212a9077e83df5ec08259e5682addda850d8&scene=21#wechat_redirect)》

《[0626-如何监控OpenLDAP主主同步状态](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497910&idx=1&sn=9dac9a4af6f1600bb7f68b9009528109&chksm=ec2928bfdb5ea1a9d3e166253cbe471ceaef7dda520468f182421b521701e72ed05df251cf0f&scene=21#wechat_redirect)》

《[0688-6.2.0-特殊用户名在Hue和YARN中测试](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499237&idx=1&sn=9968185c4b3f457459f023592828606f&chksm=ec292decdb5ea4faae29a478ed850d8c2120c9e501b9d8b1140e56b275fef8ae3f047954a72e&scene=21#wechat_redirect)》

《[0804-6.2.0-如何为CDSW1.6集成RedHat7的OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502898&idx=1&sn=cd37aee1b3a4883eec2b2b0eb1d92abd&chksm=ec291c3bdb5e952d50292f91dfb86e10b792d1b4634a7ddfff9c9300a0817006dbb341ed72d3&scene=21#wechat_redirect)》



***\*8.4.1.3.AD\****







0410- 《[01-如何在Window Server 2012 R2搭建Acitve Directory域服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492884&idx=2&sn=659e3f54e4669e197adb027663d8604a&chksm=ec29351ddb5ebc0b8928ad8bb02f1466da1affb00c37f4c7154aa20920dd8613fad604c24334&scene=21#wechat_redirect)》

0411- 《[02-Active Directory安装证书服务并配置](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492912&idx=1&sn=c40701086bf6f43c0db53463560f5dc2&chksm=ec293539db5ebc2f820cf716376dd3c675aae418399508db21a5992e188964d1afb95faffa66&scene=21#wechat_redirect)》

0412- 《[03-Active Directory的使用与验证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492951&idx=1&sn=57d4d77e185cd6e8cd132088555c1df0&chksm=ec29355edb5ebc48f0d60602dac54c66503db1830780ff42f84ff1394b995c8d2905c1898dca&scene=21#wechat_redirect)》

0413- 《[04-如何在RedHat7上配置OpenLDAP客户端及集成SSSD服务和集成SSH登录](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492976&idx=1&sn=d55c4704cd8d8af4be376b5582b5f30a&chksm=ec293579db5ebc6f351195d194988ec5039e48c1695543df4e015b3f676c8d236cf55133709c&scene=21#wechat_redirect)》

0414- 《[05-如何为Hive集成AD认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492990&idx=1&sn=b962ba568a47130b20d5bd9a27ded9a0&chksm=ec293577db5ebc61ef4550fe15f66a161c91565cb767069fb00439f66b319c688a7c4258e9a1&scene=21#wechat_redirect)》

0415- 《[06-如何为Impala集成AD认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493000&idx=1&sn=db62f4f50e9d11fce8b47ff841ce7ff0&chksm=ec293581db5ebc97b12fa8385bf03e62cfc5b2d1a04086b55ccc04ce94780ccea0f03074f687&scene=21#wechat_redirect)》

0416- 《[07-如何为Hue集成AD认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493025&idx=1&sn=824a0a340fe560302b91f4de23d2dfdc&chksm=ec2935a8db5ebcbee47d249d04e1dd110ee5ad093399148b7864c537498cdd54bddfabac9ee1&scene=21#wechat_redirect)》

0417- 《[08-如何为Navigator集成Active Directory认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493045&idx=1&sn=de67d2223df41fe925fb566716c65f59&chksm=ec2935bcdb5ebcaa05232876292ecae221e3617534b6be5ca187ba000b3fdeeb874d140ead5e&scene=21#wechat_redirect)》

0418- 《[09-如何为CDSW集成Active Directory认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493058&idx=1&sn=1fbe2c233333b8b65795a981ebb1ef9f&chksm=ec2935cbdb5ebcdd6bd2a60f5e13a00488f8b985c0f8f2d08f4f14601c0961bb588db8326118&scene=21#wechat_redirect)》

0419- 《[如何将CDH中集成的RedHat7版Kerberos切换至Active Directory的Kerberos认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493079&idx=1&sn=324521d79ef0a3381bf244b85eaf7333&chksm=ec2935dedb5ebcc89dedc2ec90528a2fe7069c9b15ff2adcbd6c4bbd7f4215c222596c84a7c5&scene=21#wechat_redirect)》

0420- 《[如何为CDH集成Active Directory的Kerberos认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493099&idx=1&sn=de181474d2131d4820663cf6c50c618d&chksm=ec2935e2db5ebcf4f584d1cdbcec9698618b793a71482b82a13c74ac4388eb0b0b4660b57522&scene=21#wechat_redirect)》

0423- 《[11-如何为Cloudera Manager集成Active Directory认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493130&idx=1&sn=7438a9c37b8c215ac622ef741891402e&chksm=ec293603db5ebf154e34598e97081b8fdfb0e99f8ea7c90201e1d60c541d425e189845140aa3&scene=21#wechat_redirect)》



***\*8.4.1.4.FreeIPA\****





《[0558-01-如何在Redhat7上安装FreeIPA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496472&idx=1&sn=93ceb211f9bc632010cf57ad459ebfd0&chksm=ec292311db5eaa07db64ad978d4c68ffaa93a07977fb59915f7560b7d98b597dbd5e9917f5c2&scene=21#wechat_redirect)》

《[0559-02-如何在Redhat7上安装FreeIPA的客户端](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496488&idx=1&sn=a20bf4c51d15b4dd383ccb4615293436&chksm=ec292321db5eaa37e7c23b2ee615fb2072ccd87285ac801ca53c7eeb65538482c0f9fd2648e9&scene=21#wechat_redirect)》

《[0560-03-如何使用root用户重置FreeIPA admin密码](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496501&idx=1&sn=a222bc8ca4b3ad42e89e22652e068501&chksm=ec29233cdb5eaa2a8d63f73340b8f8e71a259a1bdeb87895fb1755ab04a52872538141452805&scene=21#wechat_redirect)》

《[0561-04-如何将CDH集成的KDC迁移至FreeIPA的Kerberos认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496529&idx=1&sn=8a11fde8838a863de6dd47595ebb592d&chksm=ec292358db5eaa4eae1766d3ad5a7a426b1f3f201ac3d0723fea4c63f6a90aa100bf83dc8032&scene=21#wechat_redirect)》

《[0562-05-5.15.0-如何为Hive集成FreeIPA的用户认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496543&idx=1&sn=a6d5e597a60cdb6679e2e8c4a1d26ea5&chksm=ec292356db5eaa404fba6c5bd39c32ca027c4ba35a3b3d961375fd28e88b8237ed8b64e32a62&scene=21#wechat_redirect)》

《[0563-06-如何在FreeIPA上管理域名解析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496557&idx=1&sn=9c85192bebd449eba6876d7eaf5ac474&chksm=ec292364db5eaa727cb0312c43f91925e86b8ac85500d638d168c5512ed8e17900d7ea1b70d1&scene=21#wechat_redirect)》

《[0566-07-5.15.0-如何为Impala集成FreeIPA的用户认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496599&idx=2&sn=c38367e8771b82563eeea9a19f8e2f17&chksm=ec29239edb5eaa88a1a6ba90d13a557f2baa3af2b585dfd22511fa36850fa4d1007f968ee687&scene=21#wechat_redirect)》



**8.4.1.5.SAML**





0191- 《[如何使用Shibboleth搭建IDP服务并集成OpenLDAP](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487857&idx=1&sn=99920666006cdda79f59e8196e111579&chksm=ec2ac178db5d486ebde79099680d6aa83d3c3b51277787b3f7a0d1abd6414fcdc3241296003f&scene=21#wechat_redirect)》

0192- 《[如何使用SAML配置Cloudera Manager的身份验证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487884&idx=1&sn=9d5265c4a2700821c59601a8bfa66503&chksm=ec2ac185db5d48938555a89ca0c81242253636e2c4054c8d8ff4df7df74874e6b0dcb52b6ae1&scene=21#wechat_redirect)》

0199- 《[如何使用SAML配置CDSW的身份验证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488078&idx=1&sn=d5b912478093d90b33865e6758354ee3&chksm=ec2ac247db5d4b51211cc64f1347c72aa55c0a733d184f0edf78f7dd79c0e99f8f1f148cb398&scene=21#wechat_redirect)》



***\**\*\*\*8.4.2.授权\*\*\*\*\****







0015-《[如何使用Sentry管理Hive外部表权限](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484261&idx=1&sn=516703b6fc8e467e1a64b305ded3d2b2&chksm=ec2ad36cdb5d5a7ae99dcf0ca82bea4de51f455d9788f1369ec130eedeb42f042f2bb8d06251&scene=21#wechat_redirect)》

0028-《[如何在CDH未启用认证的情况下安装及使用Sentry](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484800&idx=1&sn=c746f6eac50167fe5fc0aa70c1ab85e2&chksm=ec2ad589db5d5c9f2004468999958eb3f7c87c0721b74b9e9546aeef7fae2140b001ab259d31&scene=21#wechat_redirect)》

0031-《[如何在CDH启用Kerberos的情况下安装及使用Sentry(一)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484811&idx=1&sn=5d54f0b0e85c2264033575c1b051b5b1&chksm=ec2ad582db5d5c94e7919faca495d4a5a8de21592cd1f95f93c02b98d92686238826a6a3c1fc&scene=21#wechat_redirect)》

0032-《[如何在CDH启用Kerberos的情况下安装及使用Sentry(二)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484822&idx=1&sn=2742a260068bd78d101bc1f1f24ee309&chksm=ec2ad59fdb5d5c897f7ffb2fad38e861caf798732a9f6eca984e93e6c67d3adf765a9e4c94b5&scene=21#wechat_redirect)》

0033-《[如何在Hue中使用Sentry](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484858&idx=1&sn=b7a7b821f38e1d5c657f9f829812add3&chksm=ec2ad5b3db5d5ca5c99730c22f2d68c99e54c3ce723fb3a014dd884f891f9a4059248a840253&scene=21#wechat_redirect)》

0035-《[如何使用Sentry管理Hive外部表（补充）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484860&idx=1&sn=0bf3e42c2a923f5e3a6d87744a86611b&chksm=ec2ad5b5db5d5ca38b8602ddebf91f8b153e1a31781a201504701dbba1e84f2438a26d391aab&scene=21#wechat_redirect)》

0067-《[Sentry赋予server1权限给hive以外用户时ACL不同步问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485436&idx=1&sn=84c4a9ab742179efcd928d9e2f80022c&chksm=ec2ad7f5db5d5ee32b726dd78c634e0022b8c082ac35a3583d70e3e954b86d832e527adaceba&scene=21#wechat_redirect)》

0074-《[如何在启用Sentry的CDH集群中使用UDF](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485588&idx=1&sn=023e7946760e624a2580ec62d2836e25&chksm=ec2ad89ddb5d518ba894113a0ba9639dbd49ac8112a769111487cf35377e427e16c1c09ed48d&scene=21#wechat_redirect)》

0155-《[如何查看集成Sentry后Hive作业的真实用户](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487159&idx=1&sn=81894787bd14fefeda4815fd29880e72&chksm=ec2adebedb5d57a8b9c24f8d53d23c83b13c19b9b907b65692c9e3f46c071faac48be70ee807&scene=21#wechat_redirect)》

0208- 《[如何使用Sentry实现Hive/Impala的数据脱敏](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488263&idx=1&sn=2dffec2d8ec88b12e25fec390a36e26a&chksm=ec2ac30edb5d4a1882fc73018bc11818c8ec9689ca546076eb7f01e01f7c20fd4daad18f4b8f&scene=21#wechat_redirect)》

0225- 《[如何使用Sentry通过视图实现Impala的行级授权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488722&idx=1&sn=128baec685aa50742286fadeb2eab55f&chksm=ec2ac4dbdb5d4dcd3ed6be1ff9dd5e46219d0dff374959b799897696ccd6717ac479e253429b&scene=21#wechat_redirect)》

0279- 《[如何在Kerberos的CDH使用Sentry实现Spark SQL的权限控制](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490054&idx=1&sn=d7ccb9b00a9a31a80fa7995c2f018663&chksm=ec2aca0fdb5d43195ebacea1d5ebefb92c5b82366c8844aea3ee03d0072ab04fe61d6e7ff71c&scene=21#wechat_redirect)》

0294- 《[如何使用Sentry为Solr赋权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490505&idx=1&sn=4440d015993ec16f140d7b1f5eede6eb&chksm=ec2acbc0db5d42d610906b85ce871b60220221d4ed264207cc15b4ecf47bbae909638d02a2ed&scene=21#wechat_redirect)》

0298- 《[如何使用Sentry为Kafka赋权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490617&idx=1&sn=1cd09334bfa8edcb454daf444f85da89&chksm=ec2acc30db5d4526e6ea9f4edfb50745922bc424da673eb6d197b6a0b6bed4ff2eaba838ad56&scene=21#wechat_redirect)》

0304- 《[如何在Hue中使用Sentry为Solr赋权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490766&idx=1&sn=d24313eda74ac847a5573a160ee673a5&chksm=ec2accc7db5d45d10349e7d6c527e40cb7b29a52f9237ba047429a631cb714d3e18463566dd6&scene=21#wechat_redirect)》

0406- 《[如何使用Sentry管理Hive仓库目录外的其他目录的acl同步](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492829&idx=1&sn=a1a47c053fa133285bff6e24d02d7a08&chksm=ec2934d4db5ebdc2698628e44a709c1a20031cb1f85fcb30ad7eb1565acde2d4cbf3ef0099a7&scene=21#wechat_redirect)》

0439- 《[Hive启用Sentry后如何限制用户提交Yarn资源池](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493412&idx=1&sn=b7b2adffbd55a4f3c7203c94f7c1068c&chksm=ec29372ddb5ebe3ba2d9ff54b759c438b3012bb7cec696e15cc98775a640c3a5dc4ae65802ec&scene=21#wechat_redirect)》

0493- 《[0493-如何在Sentry中使用WITH GRANT OPTION命令](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495319&idx=1&sn=6602bf6d021a1ff2459f7d032e9b548e&chksm=ec293e9edb5eb788ac7d4aeee920c529b8a57139cb4f0b3c559b3c4ee3ea2992e7934c2ee041&scene=21#wechat_redirect)》

《[0568-普通用户在Sentry中使用show roles 命令查看失败异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496634&idx=2&sn=66639a33ff76660fdbb16943e3109a37&chksm=ec2923b3db5eaaa50990cd2af9e0e3998c9a584d53ad0b6613f46ccd509b8149d51b1e013d42&scene=21#wechat_redirect)》

《[0569-5.15.1-开启Sentry后LOAD DATA异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496645&idx=2&sn=b791cbd4d4ee5a0a6ef69ad89822abbe&chksm=ec2923ccdb5eaada4a542c246172c1412c7ecf4570789ae102161282e717fb415d76401cf912&scene=21#wechat_redirect)》

《[0575-5.16.1-Hive中只有create权限却能查看到非自己创建表的异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496783&idx=1&sn=c829dea005e4e91555e2c3b93c79644a&chksm=ec292446db5ead503298a3efea98c5a1b7efef960e9cfb732321eff592410034f9f2308202e7&scene=21#wechat_redirect)》

《[0576-6.1.0-Hive Comment中文乱码补充](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496795&idx=1&sn=38525f913936b45d423b71892edf587c&chksm=ec292452db5ead44b0abbb91ac295af455586682cc9237ba33f9f69ca76996cca02e267feae6&scene=21#wechat_redirect)》

《[0617-6.1.0-使用Sentry给Solr的collection赋予Query权限后查询异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497689&idx=2&sn=980a05563044341b47c2f9fb51c048e5&chksm=ec2927d0db5eaec67ac384d6b1b9e1bc06e4ce218f4d1b5ddff773e9a9e0f0ef94c9761af2c0&scene=21#wechat_redirect)》

《[0633-6.2.0-什么是Apache Sentry](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498026&idx=1&sn=c213e855e35a0b2c9b3ccb546c30731f&chksm=ec292923db5ea035d39844431a54babd002741e1cb3baa4bdb9a686980c14f290b3e5ff3a857&scene=21#wechat_redirect)》

《[0634-6.2.0-如何在CDH中安装Sentry服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498041&idx=1&sn=ad2ae616fb6345c329f985b97647e364&chksm=ec292930db5ea026ecb656bb24b4010f6817759f5bda79f4734377380860393b3e0440f4fa2f&scene=21#wechat_redirect)》

《[0648-6.2.0-配置Senty服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498360&idx=1&sn=d14d2e4a6e2eda89025c2c670cc8bc3e&chksm=ec292a71db5ea367c27065041537733b59ac7316ae73695561d5f7addd7731d59da5575e11ad&scene=21#wechat_redirect)》

《[0651-6.2.0-启用Sentry后Impala执行SQL失败问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498395&idx=1&sn=cb3a610b6f65a4d171d564776a6d45b0&chksm=ec292a92db5ea38414cbb9fc272c19bfdbfb44c16786f4dc0f4059cbafc68eac743cabf6a282&scene=21#wechat_redirect)》

《[660-6.2.0-无法在启用Sentry的集群中使用TRANSFORM问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498591&idx=1&sn=9d6847da449de2e1b53387b1a7e57e9a&chksm=ec292b56db5ea240278983ec4dc5b5c1787d88ce5c5e16c1739d777745fdf4979279ff0f33e2&scene=21#wechat_redirect)》

《[0664-6.2.0-用户有CREATE权限建表后但无HDFS文件的ACL访问权限异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498739&idx=1&sn=e1cf192254dcd9369c489a7632a2f37d&chksm=ec292bfadb5ea2ec9943c6dc7e6d5f6c366abdc59e5486b272670180ee8783f81b564406b6f3&scene=21#wechat_redirect)》

《[0715-6.2.0-用户有CREATE权限建表后无HDFS文件的ACL访问权限异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500165&idx=1&sn=742c6111cdcee147259d4db4512f9a29&chksm=ec29118cdb5e989a35908972e35a418428c7364a0b86c186cdd2ad31f1d7f0dbb7ed1743592c&scene=21#wechat_redirect)》

《[0741-什么是Apache Ranger - 1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501338&idx=1&sn=8b0e1f9450735e5a5ba1536b555ec021&chksm=ec291613db5e9f05c4ecf25daf081161fddbb8a7a9e9e17299d5d15d01f1e6c22cc0a2c73229&scene=21#wechat_redirect)》

《[0742-什么是Apache Ranger - 2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501344&idx=1&sn=943ee4145fd4536d0bf1c1be3e274e7e&chksm=ec291629db5e9f3f3c7528542138b49f17064e1ddd00dce48eaed9b13e1a2d94f566b809a5ea&scene=21#wechat_redirect)》

《[0745-什么是Apache Ranger - 3](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501360&idx=1&sn=7f0d41eb76883f373469ddaadf0d931e&chksm=ec291639db5e9f2f1128abd4be0bbd5b0546789c2478d4604783b7f7b21732f039da6f5c2b07&scene=21#wechat_redirect)》

《[0801-什么是Apache Ranger - 4 - Resource vs Tag Based Policies](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502875&idx=1&sn=989878cae6ded2da124d8ea574880ead&chksm=ec291c12db5e9504970e63d02d63c32eef0113e2397d04455202fdb9d5f9d99b886f9a0e4283&scene=21#wechat_redirect)》

《[0803-什么是Apache Ranger -  5 - Hive Plugin](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502888&idx=1&sn=58e349a40e7116532147d11984c96dac&chksm=ec291c21db5e95371ac2c47d8d48402ef892a6f94b23d83bbfcb1d6b0d187e8c494726aff72d&scene=21#wechat_redirect)》

《[0752-7.0.3-如何在CDP DC7.0.3安装Ranger](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501602&idx=1&sn=f6aaa8f3bce372040453310f1ab991a1&chksm=ec29172bdb5e9e3d1b5ab7fdffe820b7008fccd857684ec46a5bfa6af8780827922dcb1cf015&scene=21#wechat_redirect)》

《[0763-7.0.3-如何为Ranger集成RedHat7的OpenLDAP认证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501964&idx=1&sn=4abb7e7819e15714b87b2fb4b9422a83&chksm=ec291885db5e9193912b3be65a1a008833aebcf5824ced3c6cb64aadacc8090d46ce66769e42&scene=21#wechat_redirect)》

《[0765-7.0.3-如何在Kerberos环境下用Ranger对Hive中的列使用自定义UDF脱敏](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501994&idx=1&sn=9e0176d9edfdc1bb4221b5959575f5c5&chksm=ec2918a3db5e91b568d457b29e1d752a9e7c1d187b3a4b309eeb2009ced80151f13c6fd74a36&scene=21#wechat_redirect)》

《[0768-7.0.3-如何在Kerberos环境下用Ranger给Hive授权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502064&idx=1&sn=fb52e3ae99feeccbd1fd81cf785a31e2&chksm=ec2918f9db5e91ef14dc8f3efaab5872c32a9cca814e903b3fc03eeff35e28aefbe50d887ab3&scene=21#wechat_redirect)》

《[0769-7.0.3-如何在Kerberos环境下用Ranger完成对Hive的行过滤及列脱敏](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502104&idx=1&sn=645a60ddb7c090198db71ff5fcd45458&chksm=ec291911db5e900754b066fc3ec007ff5d759815357ce8b5dab66d46bc643a6c9bb35dc387fb&scene=21#wechat_redirect)》

《[0809-7.1.3-Ranger页面功能介绍](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503031&idx=1&sn=bd3db0b157de9bcbb9c316a7a69e3c3d&chksm=ec291cbedb5e95a8fcff021a66d0426ae828909961c84a9fcc51ccd0af892ab5d7939c3c2bdf&scene=21#wechat_redirect)》

《[0811-7.1.3-如何使用Ranger给HDFS授权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503100&idx=1&sn=83a452a39fe10af2225b45bb26da2957&chksm=ec291cf5db5e95e39c0eb4dde43f5ed8029c81ec3a024b4e98c4faf7a00a052f13dad58babf1&scene=21#wechat_redirect)》

《[0812-7.1.3-如何使用Ranger给HBase授权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503125&idx=1&sn=aa94633321862c4fd073b6b985c14e95&chksm=ec291d1cdb5e940a6d8a8d5913b6db8c070c449c89a4656ff6390a1536234375615d6aafa87d&scene=21#wechat_redirect)》



***\*8.4.3.加密\****







0092-《[什么是HDFS透明加密](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485971&idx=1&sn=3f30fa5ee67ef18d4efe70866a676e06&chksm=ec2ada1adb5d530ce640fee931e9fcb1853aa7ead426d5bc8d1d792c94d31ce66600f460cba2&scene=21#wechat_redirect)》

0111-《[如何在CDH实现HDFS透明加密](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486355&idx=1&sn=36ff225a2e7935f1896559f7314556bd&chksm=ec2adb9adb5d528c89e90874ef69a857be69739c64578edae365c56f28cd94524e727e68a1c7&scene=21#wechat_redirect)》



***\*8.4.4.审计\****







***\*8.5.集群资源使用报告\****







0157-《[如何在CM中启用YARN的使用率报告](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487199&idx=1&sn=aa399c71cf48a59e74d765c7b1f960df&chksm=ec2aded6db5d57c0f0897fcbb7fc5bda3472c3bef7bfff2964b599f186be8bce0f9ac89b4d7d&scene=21#wechat_redirect)》

## **灾备**

***\*9.1.介绍\****







0244- 《[如何部署active-active的Hadoop集群](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489111&idx=1&sn=a915e8c73b3dbd74add38edbe7feca81&chksm=ec2ac65edb5d4f48f13590fdf545873b8392d6dac957cea0927aea22926b4adb4fd43dafee50&scene=21#wechat_redirect)》



**9.2.HDFS**





0013-《[如何在Kerberos与非Kerberos的CDH集群BDR不可用时复制数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484227&idx=1&sn=27d2a53e818ec5f865d68cedf18c22bd&chksm=ec2ad34adb5d5a5c491e384b947578719cbb568237554dd7dbd2e31bd628814b3245999003f6&scene=21#wechat_redirect)》

《[0661-6.2.0-Hadoop数据备份与恢复](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498681&idx=1&sn=f69a2de42feb31685c1462393417dec5&chksm=ec292bb0db5ea2a6240dba7b760614e521b14396130ced0974a5b8cca5a5f3eb884dfd92427c&scene=21#wechat_redirect)》



***\*9.2.HBase\****







0076-《[如何使用HBase快照实现跨集群全量与增量数据迁移](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485678&idx=1&sn=8e630c35bd060da7ce2401591b75a8a5&chksm=ec2ad8e7db5d51f1e0f5ebe0facd3f540153fc6a099dc892aea99dfcc241397549f9ae980edc&scene=21#wechat_redirect)》

## **运维**

***\*10.1.监控\****







0211- 《[Cloudera Manager监控介绍](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488286&idx=1&sn=ef701cc00d7b1c1d93d4dd15a4b74f52&chksm=ec2ac317db5d4a01389d9a221f9a4f250f43916dd79bed4dab5b7221d9aac41948ff504ec755&scene=21#wechat_redirect)》

0212- 《[Cloudera Manager的时间轴](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488306&idx=1&sn=353404a8ce789116d0563837b23a6f04&chksm=ec2ac33bdb5d4a2d8db8e787eaa5da4a273c84b23021c015508acfcda18606feb7bd005c6361&scene=21#wechat_redirect)》

0213- 《[Cloudera Manager的运行状况测试](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488330&idx=1&sn=7e4f13526dbfce9eb96c431eaec13d2c&chksm=ec2ac343db5d4a5527d449a7b9b41564cde57204a8cdaf6a457f9cff293c8cd4c88c462ee55c&scene=21#wechat_redirect)》

0218- 《[使用Cloudera Manager查看集群，服务，角色和主机的图表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488498&idx=1&sn=c6ff1522a18934767d4947a6daa03f3a&chksm=ec2ac3fbdb5d4aed8d45f55c2a76e3bccec4ef782cb4b878e50ee95cab2b46d72f07c83789f8&scene=21#wechat_redirect)》

0289- 《[如何使用Cloudera Manager监控服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490380&idx=1&sn=eacee481a3fcf8e323392f3eae982ff4&chksm=ec2acb45db5d4253559a0d6dcf157adaf269500a50f9c998cdc4b69d608c05a73e3c403ee640&scene=21#wechat_redirect)》



***\*10.2.告警\****







0259- 《[如何通过Cloudera Manager配置使用SNMP方式转发告警](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489479&idx=1&sn=7e1d1c226dbea5eac34797584d1be2fe&chksm=ec2ac7cedb5d4ed82749cd6d63d177531a9cca93eb5de0182fb6a68d07974369694172f99791&scene=21#wechat_redirect)》

0372- 《[CM告警SNMP对接补充](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492121&idx=1&sn=375ce58cb7b87a94efa4ccbfd6f93894&chksm=ec293210db5ebb06ed38d90b8f1456f48a7f44edac010305fa6ca036eab9678686ddb00d3905&scene=21#wechat_redirect)》

0394- 《[如何为CDH集群配置警报邮箱](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492640&idx=2&sn=f8326f43c01e56ce747eefe937569cb7&chksm=ec293429db5ebd3f487e97dbf09dc4853d47443dc006750ec3c891b97210a26092b3581ad120&scene=21#wechat_redirect)》

《[0523-5.15-为Cloudera Manager配置自定义告警脚本](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495781&idx=1&sn=ed7d3e60cd1f4db2429ea4e8c5d2620b&chksm=ec29206cdb5ea97a1e1230c82cd817943ec83f139fcb3fa1cbe3bb3a99adff0537de76d8fe4f&scene=21#wechat_redirect)》

## **外部工具集成**

***\*11.1.Tableau\****







0093-《[如何安装Tableau并连接CDH的Hive/Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486022&idx=1&sn=52f29bf3788d1693349ba13c4f98de36&chksm=ec2ada4fdb5d5359175ac939bc8e965f361a3ac16a54c31d06597ec8f1f0ecc11bb21dab4e11&scene=21#wechat_redirect)》

0094-《[如何通过Tableau连接Kerberos的Hive/Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486063&idx=1&sn=98c4daa23d62937b57e19ac53f9adf66&chksm=ec2ada66db5d53705b220cfaecbaa9d77bbfb9898d8e024545a1bd3db29014b78175299d576b&scene=21#wechat_redirect)》

**
**

**11.2.SAS**





0198- 《[如何安装SAS并配置连接Hive/Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488053&idx=1&sn=70ffd9e1d78058645674b4caed034e7f&chksm=ec2ac23cdb5d4b2a32e1a64e30e151617357b9321b72c3177dada80a5589895ac777ba98538a&scene=21#wechat_redirect)》

《[0696-5.16.1-如何使用SAS连接CDH5.16.1集群的Hive和Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499596&idx=1&sn=ab1e2a7866f49ddce389171517666d45&chksm=ec292f45db5ea653728e3ab448d69f12b3433274b64c6d84058c12f5bd0879d3c11d7d82ecfc&scene=21#wechat_redirect)》

《[0697-6.2.0-如何使用SAS连接CDH6.2.0集群的Hive和Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499686&idx=1&sn=4fe978952affd3d12c91d852fdcb178d&chksm=ec292fafdb5ea6b94c7791293038afc48fd6bb5b3388a0d2d3a56b857435c02dfb7ad93ab508&scene=21#wechat_redirect)》



**11.3.Azkaban**





0214- 《[如何编译安装Azkaban服务](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488369&idx=1&sn=2191be3f9880e16e994046f205b1841a&chksm=ec2ac378db5d4a6e392467a2d0b097aa30fb0c88b16306c26da91bf59e0742cc23dd031cdf5e&scene=21#wechat_redirect)》

0215- 《[如何编译Azkaban插件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488388&idx=1&sn=91e5e2e3b01bf0ee5bd2303f17c50324&chksm=ec2ac38ddb5d4a9b89f4f73183378ca0067d5a0eccfaa079e91a44842bb883660e63f297e3b3&scene=21#wechat_redirect)》

0219- 《[如何在Azkaban中安装HDFS插件以及与CDH集成](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488515&idx=1&sn=5e17d1f2b2469aa708a1631ef5e43c96&chksm=ec2ac40adb5d4d1cf9d41359924e1db5680cdb415decb6fa094597f8615938813c4c2e8674dc&scene=21#wechat_redirect)》

0222- 《[如何在Azkaban安装插件(二)](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488674&idx=1&sn=37c49a7ea0955554dc1e9f1cb41cfda0&chksm=ec2ac4abdb5d4dbd0dd182fe010722063dcb067c974383bee8ae08e50b8c46bdc44091020aed&scene=21#wechat_redirect)》

0223- 《[Azkaban的使用及Command作业创建](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488693&idx=1&sn=b7a0352aaad9644b257540be036a3d58&chksm=ec2ac4bcdb5d4daaf4f0706ef5281d42ad31a9dd66c9b7a665adb7cd6a65e8c5e9cd1f56d78c&scene=21#wechat_redirect)》



**11.4.SmartBI**





0257- 《[如何安装SmartBI并连接到Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489419&idx=1&sn=1b0cbd7b35b2046cce6d33958e4f3a0d&chksm=ec2ac782db5d4e9467d72182834ca402cbd2ee78d66003c5ccdb8189126a78e0226c00174fab&scene=21#wechat_redirect)》





**11.4.StreamSets**





0220- 《[如何在CDH中安装和使用StreamSets](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488566&idx=1&sn=8c4350eb654453b2317de2b347b6e525&chksm=ec2ac43fdb5d4d2964e2b074d02faaeebe202c2ba3565ac00f589b696644bdbfa8f6f4d9754e&scene=21#wechat_redirect)》

0231- 《[如何使用StreamSets从MySQL增量更新数据到Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488852&idx=1&sn=77d75561820c60c5d9f3eddaf7023dc0&chksm=ec2ac55ddb5d4c4be46b46ae4439d7405deaf51c203c44295f2eabdd3622672977ad58d547da&scene=21#wechat_redirect)》

0232- 《[如何使用StreamSets实现MySQL中变化数据实时写入Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488901&idx=1&sn=58e8038e11b6b628c99001c696124c66&chksm=ec2ac58cdb5d4c9a1ca678cfb089681542d1b7d3f543af35b71999065f5b3c7a020ced5c8fca&scene=21#wechat_redirect)》

0255- 《[如何使用StreamSets实时采集Kafka并入库Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489340&idx=1&sn=6ab88e12768add3dda48ee9782f8c3ac&chksm=ec2ac735db5d4e23eada0d30899d4a4fbdabdd062acc5ed42e784c281b0769560e44b68a2828&scene=21#wechat_redirect)》

0282- 《[如何使用StreamSets实现MySQL中变化数据实时写入HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490146&idx=1&sn=2e890590da6ed3f96805c95f194a1869&chksm=ec2aca6bdb5d437dc32c7ae50f19d0785558faa5241d0fea11c38a75a62e4a8affa1df93cd8a&scene=21#wechat_redirect)》

0299- 《[如何使用StreamSets实时采集Kafka数据并写入Hive表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490655&idx=1&sn=ecfd89ecef9f89968f59f5503f09eb2e&chksm=ec2acc56db5d4540e59108f48e163554aa708acd79b2c6b8ef28f2b25dab930a4299dd435945&scene=21#wechat_redirect)》

0302 -《[如何使用StreamSets实时采集Kafka中嵌套JSON数据并写入Hive表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490761&idx=1&sn=ef7bdb59d529e7fde384649306602b08&chksm=ec2accc0db5d45d60a7dce37bc102953ba5b7f4d1bba58cf373074f7811d3b674eb9c49bbe70&scene=21#wechat_redirect)》

0320- 《[如何使用StreamSets实现Oracle中变化数据实时写入Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491173&idx=1&sn=9b416b68bb89582519128bab58abf8ac&chksm=ec2ace6cdb5d477a8d83c11d49d590790e545e35c05e1e7f09c7cd7c49b38b174c7f0fd53c48&scene=21#wechat_redirect)》

《[0604-6.1.0-如何使用StreamSets实时采集指定数据目录文件并写入库Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497396&idx=1&sn=ae6527fa7ab4ef6d7970f00f9762afbc&chksm=ec2926bddb5eafab42be5fcedcfa8df31d5bb48b438c884a2cca29bf3a7c8a038d7469df141d&scene=21#wechat_redirect)》



**11.5.Kylin**





0260- 《[如何在CDH中部署及使用Kylin](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489540&idx=1&sn=a9a2c9bbb065987cd8756635c146800d&chksm=ec2ac80ddb5d411b69c49b17d7a3d4ae0807aa7427739320241076fa9f4f217a7a46e1154b04&scene=21#wechat_redirect)》

0295- 《[如何在启用Kerberos的CDH中部署及使用Kylin](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490548&idx=1&sn=4660373343914470862ba630930ab5ed&chksm=ec2acbfddb5d42eb1fbe9c121e57921ad50d4bbf5c0f7007360fc27793a9856a2feabd02b4d1&scene=21#wechat_redirect)》



**11.6.Presto**





0316- 《[如何在CDH集群中部署Presto](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491020&idx=1&sn=5c7ae5eea0335dfab22b7da48301817d&chksm=ec2acdc5db5d44d374a83c41c2269d2f0092317a7b64db9bdab5c8cf77be4206b333d1820328&scene=21#wechat_redirect)》

0318- 《[如何为Presto集成Kerberos环境下的Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491103&idx=1&sn=be62dbac972df9d30b339ff02237b261&chksm=ec2ace16db5d4700bf0b2fec56409190791b3e3ff793a0733fccd78fae7a62ae108c6172abd6&scene=21#wechat_redirect)》



**11.7.Juypter**





0382- 《[如何在非安全的CDH集群中部署Jupyter并集成Spark2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492353&idx=1&sn=f8de800f855b2c3b1178963367ea1af3&chksm=ec293308db5eba1e0cc76d853a4822438206cce145fee083c208a2c45d31e6f5fb79dce04e4e&scene=21#wechat_redirect)》

0384- 《[如何在非安全的CDH集群中部署多用户JupyterHub服务并集成Spark2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492425&idx=1&sn=256bd293bf0e6ed92ca2cbaee4ace611&chksm=ec293340db5eba56324879e92875ade9333cfec2aedc00d9a7bcda0d2b5eaf8e793f0451e667&scene=21#wechat_redirect)》

0385- 《[JupyterHub与OpenLDAP集成](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492438&idx=1&sn=021415e83b4e12846bff4ee56d4b07ca&chksm=ec29335fdb5eba49aa6d6c996677cc685dec469f82a120e44767215fbb188ee752bfb778a19a&scene=21#wechat_redirect)》

0391- 《[Jupyter Notebook与Livy集成](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492570&idx=1&sn=3ed01fbdeeb0863440ad7634da03f28e&chksm=ec2933d3db5ebac53d8d4162c923256fd5dbf0128226bc365f053dd5ce497c96938252b4b9bd&scene=21#wechat_redirect)》

0398- 《[JupyterLab的安装及使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492744&idx=1&sn=490cb9504f3aec947c72ff470024143d&chksm=ec293481db5ebd9761ea18601396d453cc772e81df3999fcfd40e6b2c625db38f4acda4374cd&scene=21#wechat_redirect)》



**11.8.Livy+Zeppelin**





0387- 《[如何打包Livy和Zeppelin的Parcel包](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492460&idx=1&sn=291e108656728226abb70b05425ffc81&chksm=ec293365db5eba73e92bb20da69033392c04e8cee162223c53c6099d3642b0d54d19a4cda683&scene=21#wechat_redirect)》

0389- 《[如何在CM中使用Parcel包部署Livy及验证](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492482&idx=1&sn=47999d8a05b5806481737f68de445232&chksm=ec29338bdb5eba9d37ea3c0fa633452ff990d9d19074bba40337109b7537d1ac95e90475ca25&scene=21#wechat_redirect)》

0393- 《[如何在CM中使用Parcel包部署Zeppelin及使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492621&idx=1&sn=c209425624269b0e3e917aab3e0e47c7&chksm=ec293404db5ebd12a88f23a0fc951e29651f8a85d47f929d2c6709358723359979fdcd923480&scene=21#wechat_redirect)》

**
**

***\*11.9.SQL开发工具\****





0459- 《[0459-如何使用SQuirreL通过JDBC连接CDH的Hive（方式一）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493732&idx=1&sn=dd3bfc7dbd3900a6943a7c0f174d7f74&chksm=ec29386ddb5eb17b995e8f7ee1e244e46e11c99031be7af59cd19945a4bc20d107bffa6e781a&scene=21#wechat_redirect)》

0463- 《[0463-如何使用SQuirreL通过JDBC连接CDH的Hive（方式二）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493917&idx=1&sn=3e0dd8992d0ae826e1fedbcbea55a087&chksm=ec293914db5eb00275218eb97c35f8b8204ef4194a1549592c4ceae90ea78f2e0ac60f296677&scene=21#wechat_redirect)》

0465- 《[0465-如何使用SQuirreL访问Kerberos环境下的Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493993&idx=1&sn=ce73333b67e71da7f851f01a515c8e12&chksm=ec293960db5eb0768496c59a9db0bfad435ff579123d26fe25cab65a497f37a7c297e1471ff6&scene=21#wechat_redirect)》

0467- 《[Hadoop SQL客户端工具之Dbeaver安装及使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494102&idx=1&sn=db955394eb1d7ebcbf6946b6dd60d07d&chksm=ec2939dfdb5eb0c9d4a4080eb4d86e458bc8d928167ae50b6b5ca39b115a9d0502ac1d43ce5b&scene=21#wechat_redirect)》

0468- 《[0468-如何使用DBeaver访问Kerberos环境下的Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494128&idx=1&sn=63e61afded9ce2e735d23809f54d20df&chksm=ec2939f9db5eb0efceed6fc81a2ef9813483d9ca3ebbdb6f7f612572ff5340b84923d26dbbcc&scene=21#wechat_redirect)》

0469- 《[0469-如何使用DBeaver访问Kerberos环境下的Impala](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494147&idx=1&sn=0711e6e097d9ad51c3d670e380c9b269&chksm=ec293a0adb5eb31c7a2ffa79fee004019cf7173ee1fd9d766cb4ac26cc8873dc6d405a657e7d&scene=21#wechat_redirect)》

《[0557-6.1.0-Kerberos环境下SQL客户端DBeaver配置异常分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496448&idx=1&sn=c8a849f5c0258aafaf2c43ea1250a8c2&chksm=ec292309db5eaa1f8a02fd73499c1a35a9bf8738a15b294b52066df145d39586d55b9f4b76d7&scene=21#wechat_redirect)》

0474- 《[0474-如何使用SQL Developer访问Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494459&idx=1&sn=862ee745ff318f8be1df52efefc94a23&chksm=ec293b32db5eb2247f0373e7af5d5499727860a56d955bdfef9a044873bb4316715f4a906688&scene=21#wechat_redirect)》



**11.10.Airflow**





《[0612-如何在RedHat7.4上安装airflow](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497603&idx=1&sn=60adc2efa3621464bfadd2ed4fb695d5&chksm=ec29278adb5eae9c3c86114c764e9948b0a6a4108e9c43b26f3d1163dd5f84d604ab9b5fd4fc&scene=21#wechat_redirect)》

《[0613-Airflow集成自动生成DAG插件](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497628&idx=1&sn=3794c7301adba4cae8369ab5f2a686a4&chksm=ec292795db5eae83bd5879727f6870bf7f9b841596e3b96b892b9c52a1ef502a6b5274dbcb5a&scene=21#wechat_redirect)》



**11.11.Nginx**





[《0684-如何配置Nginx高可用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499150&idx=1&sn=3d124d654b53767e44d8fa0f8c9cf98d&chksm=ec292d87db5ea491b10cbef81662361f069777b14be179f8597ff65a740d7da18479a5b20249&scene=21#wechat_redirect)》



**11.12.ElasticSearch**





[《5.16.2-如何在CDH中安装ElasticSearch](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502720&idx=1&sn=278fb496d581634b77ec14969c89ea7c&chksm=ec291b89db5e929febbc51589a869afe9a29028fd164748b4e2cb78d701da348041c157bdc05&scene=21#wechat_redirect)》

《[5.16.2-如何制作ElasticSearch的Parcel和csd](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502720&idx=2&sn=80bcd815364a59048f95f1d9c27620f8&chksm=ec291b89db5e929f2055992b4502b9db531572a328742740bda3aba316c70adcf4650e41bb85&scene=21#wechat_redirect)》

## **应用场景**

***\*12.1.实时\****







0116-《[如何在Kerberos环境使用Flume采集Kafka数据并写入HDFS](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486469&idx=1&sn=a88387ecf74df0f6139be0742fc50634&chksm=ec2adc0cdb5d551ac184c36d0b905b53df8a133ab005bc4aa6fa5b5730be45cb356d3aeda0fa&scene=21#wechat_redirect)》

0122-《[非Kerberos环境下Kafka数据到Flume进Hive表](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486599&idx=1&sn=a45adda9f6a2d955c8073b493b3bf246&chksm=ec2adc8edb5d55984a2536203b61d3b7886db3f649a92e439cd99369f8eaa3a5c0920c4fbf0b&scene=21#wechat_redirect)》

0145-《[如何使用Spark Streaming读取HBase的数据并写入到HDFS](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487031&idx=1&sn=6cf09e448b1f74a57e32375401bb9fd2&chksm=ec2ade3edb5d57283497e984b61df284fa3ca918ed6a189c12e3369cdb49e17bbef975116c3d&scene=21#wechat_redirect)》

0283- 《[SparkStreaming读Kafka数据写HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490167&idx=1&sn=40c06fc00495a503fa4eb6cce724f698&chksm=ec2aca7edb5d4368c5cad73a1c0afc4a3907a0c433005e2062638163cca9ff4d5f9017370a9d&scene=21#wechat_redirect)》
0286- 《[SparkStreaming读Kafka数据写Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490289&idx=1&sn=e1d00dd722bea8f4933ec9860dfd1a9d&chksm=ec2acaf8db5d43ee4be479460fe23523df26b3d136f877db12cd9ac4317389e5ef57ee932a59&scene=21#wechat_redirect)》

0287- 《[如何使用Flume采集Kafka数据写入Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490308&idx=1&sn=ed1a6b7edfab019a12f9c9aba9611a5b&chksm=ec2acb0ddb5d421bfb00456e67daac6b2724e3ab67ba9bffe2b19dd3fadbb1071fc9694cbefe&scene=21#wechat_redirect)》

0288- 《[如何使用Flume采集Kafka数据写入HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490323&idx=1&sn=cdb20a0fcd6311030f6174bef798f99b&chksm=ec2acb1adb5d420cb8dfac5e35194b17cff9749991d2d6b782ccca0821a5f5d6e6d098a6cec5&scene=21#wechat_redirect)》

0290- 《[如何在Kerberos环境下使用Flume采集Kafka数据写入HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490402&idx=1&sn=9e4e8fc35aa483f26ea5418df1528a0c&chksm=ec2acb6bdb5d427d9c3d333c0543c912ab16b9c5f30e01cb93cddcecdc2ceea0d11645021f93&scene=21#wechat_redirect)》

0309- 《[Spark2Streaming读Kerberos环境的Kafka并写数据到Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490880&idx=1&sn=84c64463981bff2b63f6cb1118cad707&chksm=ec2acd49db5d445f71200a4c01113d28a9c633cf9dd20fcfe0d833a4672b17b4edd7e6c4d519&scene=21#wechat_redirect)》

0310- 《[Spark2Streaming读Kerberos环境的Kafka并写数据到HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247490903&idx=1&sn=2219f3ab03f1761bc51520dcb72e7962&chksm=ec2acd5edb5d4448d78080501bc4eb3285efa4385cabed348147a1215d14a680ce002985a80d&scene=21#wechat_redirect)》

0330- 《[Spark2Streaming读Kerberos环境的Kafka并写数据到Hive](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491380&idx=1&sn=0450194ccdb493eb0e55964a54fadf87&chksm=ec2acf3ddb5d462b260fde7b8c3f6ec7c5f6e9243ec9c299112eca5e8666692e274fbb20411e&scene=21#wechat_redirect)》

0335- 《[Spark2Streaming读Kerberos环境的Kafka并写数据到HDFS](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491471&idx=1&sn=dc059fc1248afff8f50cf5f4386c2036&chksm=ec2acf86db5d4690be155588c77ee1a2d1bb4ecbbc0d456af96da021078db5e02b5699b2be42&scene=21#wechat_redirect)》

0338-《[Spark2Streaming读Kafka并写入到HBase](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491585&idx=2&sn=c288a801d70d66f417794d5946c44b05&chksm=ec293008db5eb91e861731a77cbfd6365b6cebfcb8a5404a2700ef03907002e9cd0b451f4e66&scene=21#wechat_redirect)》

0352- 《[Spark2Streaming读非Kerberos环境的Kafka并写数据到Kudu](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491810&idx=1&sn=2b7894cb8480230a276040fb94dabccc&chksm=ec2930ebdb5eb9fd1ae3f5bc470ab02b0864c24f2c3a1a88575e0d43c3e462c187145c71a776&scene=21#wechat_redirect)》





## **基准测试**





0245- 《[如何使用HiBench进行基准测试](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489153&idx=1&sn=fd19cad4b162d1cdef69420504d9b99c&chksm=ec2ac688db5d4f9e9c66f7c6834e6964fb3694b9a6f48c88cfc20263b0ff122f068959341489&scene=21#wechat_redirect)》

0201- 《[如何编译及使用TPC-DS生成测试数据](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488108&idx=1&sn=8f34c674bc12990d61a8f4de4ca3c728&chksm=ec2ac265db5d4b731b93c4b7da0b3a24f0bf200274dd763531873bb4dd205e37d704ea2719b6&scene=21#wechat_redirect)》







## **HDP**



0048- 《[Hortonworks联合Jethro扩充其数据仓库解决方案](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485118&idx=1&sn=5fff93677aaea7cebdf04863c7e0363e&chksm=ec2ad6b7db5d5fa1cfae6bb339784c7f3e55d6d54e3c0b5609d6ae5562bd450776756fdd661d&scene=21#wechat_redirect)》

0222- 《[如何在Centos7.2安装HDP2.6](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488674&idx=2&sn=a7eedc164839fa16d355b529889d5c02&chksm=ec2ac4abdb5d4dbd65ff671990a5fa85c793f6d4326302b1619b2fb8962f0daa289d034cd9b6&scene=21#wechat_redirect)》

0230- 《[Hortonworks去年第四季度以及全年财报](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488813&idx=1&sn=2ae0e8ce6a66687177d2b800d81edae4&chksm=ec2ac524db5d4c323cbbd06e59b73ae1585dfa976244b10a46cfc55fdb67a0f2c55f8ffc4144&scene=21#wechat_redirect)》

0329- 《[Hortonworks正式发布HDP3.0](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491362&idx=1&sn=472a0fed3dc2f4009cedbd70ce436773&chksm=ec2acf2bdb5d463d05be14e6ea3f197406b329560fa82c1de4eaf5c09a44f349bc6188d3fa14&scene=21#wechat_redirect)》

0429- 《[如何在Redhat7.4安装HDP3.0.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493270&idx=1&sn=2528d8cc840c47259b1414f29dffcc3e&chksm=ec29369fdb5ebf89eba68be99ded96192d339469ea87fc174520c817c744366c1556328b6d56&scene=21#wechat_redirect)》

0479- 《[0479-如何禁用HDP2.6.5的HDFS HA](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494766&idx=1&sn=25dc8fbad316270a03d5b9a190ab2775&chksm=ec293c67db5eb5712663fd622e7654dc3892955bf3eb8d0d7a18a9b0bd33ef38bb5531ad54c0&scene=21#wechat_redirect)》

0480- 《[0480-如何从HDP2.6.5原地迁移到CDH5.16.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494816&idx=1&sn=5565b6f89069dc72971b9910b0f598f1&chksm=ec293ca9db5eb5bf0186e7d56ae24615fa24e90cf2a4f544d142fe3551520ccc74d8ff48146d&scene=21#wechat_redirect)》

0481- 《[0481-如何从HDP2.6.5原地升级到CDH6.0.1](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247494864&idx=1&sn=c92554d4ba64502d8fdea1d29f6d0c45&chksm=ec293cd9db5eb5cfa770bc810430809a17be08c625fce418583b6e719717260fb90800aa6af0&scene=21#wechat_redirect)》







## **其他**





0018- 《[大数据售前的中年危机](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247484268&idx=1&sn=29e4ace3de0c7ab9a7b08ba63c6ba16b&chksm=ec2ad365db5d5a73febf528056dc94462af2f932a49a8eced05c9e7a160a80a3250ac6b83023&scene=21#wechat_redirect)》

0059- 《[工程师的一天](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247485304&idx=2&sn=45457443b8a9b31ff8cf975a8bcfbfa6&chksm=ec2ad771db5d5e67e55043a27bf45cc50454cadaefe6170ae0ea76013770b9a5fb2eb24f277d&scene=21#wechat_redirect)》

0106- 《[总用户数破1000，后台数据公布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247486244&idx=1&sn=9b5218c630099690b9d44cd86b13e714&chksm=ec2adb2ddb5d523bd57bd1c142192cc426bd61aab629a15d72aed0e3d866e1e54bee5267c365&scene=21#wechat_redirect)》

0179- 《[Fayson给大家拜年](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247487719&idx=1&sn=cc6ec1ebabc1056d8862ad7543434b49&chksm=ec2ac0eedb5d49f81b9fe528bff7863412d84aa8ff407b5470d259cc0c0ab5a92d91b8fa26ad&scene=21#wechat_redirect)》

0221- 《[冲上云霄](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488576&idx=1&sn=01ae0dac7c5981630edeebf6003e71e0&chksm=ec2ac449db5d4d5f14e24ba8bb5b87f78019fa8b7fdaa9baed51c002761b458bb6c0c3148a1c&scene=21#wechat_redirect)》

0228- 《[Cloudera去年第四季度以及全年财报](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247488784&idx=1&sn=ea3c44f0baae14fcd2b76a5d23613c10&chksm=ec2ac519db5d4c0fdcb93382bca1aa369998ff37f32043728d3b1ff394a8c0695644b43865de&scene=21#wechat_redirect)》

0259- 《[如何在DELL R730服务器上使用U盘安装linux操作系统](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247489479&idx=2&sn=48844a7bbacf70d800e2eb03aa40c9cf&chksm=ec2ac7cedb5d4ed84bbe676a5911d19b242608f3f639c4593adc88c421e8e5c9c7d8e6b40ecd&scene=21#wechat_redirect)》

0366- 《[周年庆](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492011&idx=1&sn=4c71f8f11cd7417e6a3a36bf9737b094&chksm=ec2931a2db5eb8b401b584489f5028a62a01fde04a3e40d4d58887f87e0518a40bec3e70ef97&scene=21#wechat_redirect)》

《[简单说一下ClickHouse](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492773&idx=2&sn=39ffd11f5cbefbc233ff568ea99bc286&chksm=ec2934acdb5ebdbaf6d24501a376feb20b1d505ec715c007046e6045ef990d9e8e1646f5a214&scene=21#wechat_redirect)》

0453- 《[Java收费，Hadoop怎么办？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493640&idx=1&sn=85d17feb211ce28e3ace5a1d33f31f9a&chksm=ec293801db5eb1174d6f959d872c67b704c55ac067a05d8188d0011d2b961b2ff90971d50cde&scene=21#wechat_redirect)》

0462- 《[【简报】CDH和HDP的合并提前终止反垄断法的等待期](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493794&idx=1&sn=4d38808639027475f29f6fce8e18f174&chksm=ec2938abdb5eb1bd2f8dc35e3e4a76a55a2abd19c1378ad5287fa9ca1c8efb12549024a67326&scene=21#wechat_redirect)》

0484- 《[0484-Cloudera和Hortonworks合并后面临的选择](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495122&idx=1&sn=45492a558e35cf6326e31e73227dd558&chksm=ec293ddbdb5eb4cd56d3a0557bb9cc6e393d1e60c145f59ddb12f8fa23edd0ad56b75a08b942&scene=21#wechat_redirect)》

0503- 《[Cloudera与Hortonworks合并完成](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495510&idx=1&sn=f48bef6deb3215d349018314f68af5ab&chksm=ec293f5fdb5eb6492c6aff42243a1748692be3460f8f4b4da347b632e0f56123fe569e726b11&scene=21#wechat_redirect)》

0511- 《[0511-正式合并完成后Cloudera推出新的大数据平台CDP](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495604&idx=1&sn=a6a61cbd3e732c3b93b6075dd6c4210d&chksm=ec293fbddb5eb6abd8ce2f780f333d5260c1ffc55adf910a05225fe191decf7b9093804abf2a&scene=21#wechat_redirect)》

0513- 《[0513-开源软件如何统治世界](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495623&idx=1&sn=5f3482dd432edc92923cb0190212ba1c&chksm=ec293fcedb5eb6d89cea10c2f5186ae10de5d701d28282e7433549651be937c2cc6bb660254c&scene=21#wechat_redirect)》

0516- 《[融资数千万的小象科技了解一下](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495669&idx=2&sn=359d2d951a4ee09bb315e0c1d9e6fb7e&chksm=ec293ffcdb5eb6ea8f3a5e6d5a8a1480b7e8cc8801291184f54701b0353e5d5567b850e90bfb&scene=21#wechat_redirect)》

《[0522-Confluent获D轮融资1.25亿，估值25亿](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495759&idx=1&sn=554d8c40e28a881d7517f17e187a61ce&chksm=ec292046db5ea9505eac9d60a88d05943f9bfd94937bec02e36ea0e2d15a5a0b1ecc8d8f1fca&scene=21#wechat_redirect)》

《[Fayson给大家拜年](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496041&idx=1&sn=9052018e0a955962f2d91205043ec66e&chksm=ec292160db5ea87602ddab79618c1051bb169466f03c478acf76d8ea77b438fc279017a2ed57&scene=21#wechat_redirect)》

《[新年](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496046&idx=1&sn=d9bf66a850fe939c1e3db0133add4f8b&chksm=ec292167db5ea871039909f1f22544dd61f269e982e02babb85b4d80b344c5c04fec2f52458b&scene=21#wechat_redirect)》

《[Hadoop已死，Hadoop万岁](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499757&idx=1&sn=eee1bb4ea970196b6b4844f4d2b974d1&chksm=ec292fe4db5ea6f222b3bcd79cd77e2a13538b73003b9d05287e86f9ba4e3d7e4eb70d372637&scene=21#wechat_redirect)》

《[Cloudera PS招贤纳士:4名 Solutions Consultant/ Architect](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499813&idx=1&sn=df7d372e0b3a08e694130d38d64599a2&chksm=ec29102cdb5e993ae88525f6100c2762956997a3861d2b8b0e383b3127e7c8c1aaaa9204dc25&scene=21#wechat_redirect)》





## **转载**





《[刘汨春：AI大数据在企业全链业务中的应用和价值（上）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491833&idx=1&sn=37adc91d94510d2b14ec31dbfc59922b&chksm=ec2930f0db5eb9e674141e49a1a2ece40d52bb8eae2c681b1166011d75ee602389aa3ef6b5fb&scene=21#wechat_redirect)》

《[HDFS添加 NFS Gateway 角色实例启动失败问题及解决办法](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491903&idx=2&sn=d7aa62f23f489c8c5fc20d32c5d51bce&chksm=ec293136db5eb82074488287419b20f19dfbb64278398389d566484e3c459e074313a149e8e0&scene=21#wechat_redirect)》

《[近期文章内容预告](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491903&idx=3&sn=878f1e68df035d8916e9dbbb786d7a89&chksm=ec293136db5eb82031e9b6754013eec9e85a639b31db1bad267953a9e158da197e75054b00a2&scene=21#wechat_redirect)》

《[安装CDSW数据磁盘初始化异常问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491903&idx=4&sn=960701011a24eecc89abbc187d18076c&chksm=ec293136db5eb82066a06bac55a19cd86f5cf28758b153c8fcbd9d161dbe4a3fb74bedf8dbb6&scene=21#wechat_redirect)》

《[安装CDSW数据磁盘初始化异常问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491903&idx=4&sn=960701011a24eecc89abbc187d18076c&chksm=ec293136db5eb82066a06bac55a19cd86f5cf28758b153c8fcbd9d161dbe4a3fb74bedf8dbb6&scene=21#wechat_redirect)》

《[重庆某项目生产集群扩容问题总结及复盘](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491903&idx=5&sn=008d5a4d15e81fb3e6f631302794edde&chksm=ec293136db5eb820779ef686ba383a79356c6dbc8e0e075137218cf8f76532e2c98e49f56fa8&scene=21#wechat_redirect)》

《[如何为CDH集群配置机架感知](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491903&idx=6&sn=6248fa11df061bf81be364c2173c2d37&chksm=ec293136db5eb820cc1bc2174d6ca3f7545c3aeb5e99fe8d36beb568ee6c76b5b8383bca93e9&scene=21#wechat_redirect)》

《[HDFS运行Balancer失败及问题解决办法](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247491903&idx=7&sn=a52684700af78b9e5712a2b407760d4d&chksm=ec293136db5eb8204c6edcecb48cc15ce4c61844c435838e7ef49f7f045f3bae9dde11c2eaa1&scene=21#wechat_redirect)》

《[如何为服务器硬盘配置RAID或JBOD模式](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492121&idx=2&sn=49358cbf6e34048d77df4f966f2c4880&chksm=ec293210db5ebb060302ae8d0767d4a495e605512b50fca34bb85a05a6eece99abe7062cafc8&scene=21#wechat_redirect)》

《[如何在HP dl380 Gen9服务器上安装Redhat 7.2并配置软RAID](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492121&idx=3&sn=53469b5a154d4572c71f93654688a643&chksm=ec293210db5ebb06a42ed23ea01ce1f6df69ba7511394056cafcbe942bf986c17179da807d5b&scene=21#wechat_redirect)》
《[如何使用Sentry为包含特殊字符的用户组授权](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492121&idx=4&sn=333b413ea802443324bef06afa6007dd&chksm=ec293210db5ebb069248e5f89e99e6374d23a27dbc653305cd8e675e95c686ac2d7f4849e510&scene=21#wechat_redirect)》

《[如何为Hadoop集群服务器绑定双万兆网卡](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492121&idx=5&sn=58e5453cf41720b2124296a9e3bbde05&chksm=ec293210db5ebb068c13a319b1f7ad166064b831aa4dd953c7ba52a9e4f111201481309a6a49&scene=21#wechat_redirect)》

《[如何使用Shell脚本判断HDFS文件/目录是否存在](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492121&idx=6&sn=6dfb30a6900b825f03f06b8984735a11&chksm=ec293210db5ebb06a781a3b98da4a3ff3e1d2f17d0737a3c4ea7080471e1fffc590c6bc8132d&scene=21#wechat_redirect)》

《[由MasterProcWals状态日志过多导致的HBase Master重启失败问题](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492121&idx=7&sn=08e44416189568c3cced8d5d7f21749c&chksm=ec293210db5ebb068b6ae62e5017add87413404d9535dc2efbab97ce1fec545212e30a9bf60b&scene=21#wechat_redirect)》

《[聊聊个人对安装部署CDH集群前置准备的理解](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492121&idx=8&sn=7c4fa9fc222ede005b4cc30497f3bee3&chksm=ec293210db5ebb06f44ca59f32f3a6400ee2a2960f660bc7b17d482694c9771ed9e163edda6e&scene=21#wechat_redirect)》

《[CDH集群安装YARN无法正常启动及解决办法](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492135&idx=2&sn=18bbcbf763ca2e6b46bf3df78830e7a3&chksm=ec29322edb5ebb38753294c4d57d398e5852efb91a331cdcc35bdb902161e25f90bea7103e6d&scene=21#wechat_redirect)》

《[LDAP用户组信息异常导致Sentry授权失效问题分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492135&idx=3&sn=21226c16447fe1fa8f3c3516d7c176cd&chksm=ec29322edb5ebb384e73632a5e5b6caae2b97f7e9147c1eed094712ecc6c889d1820b86cf3e9&scene=21#wechat_redirect)》

《[HDFS Federation（联邦）简介](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492135&idx=4&sn=ee96877a2461972e4ff73cc85e42f9cd&chksm=ec29322edb5ebb381d4acc2071e8db68bf8fb489ffa1216855a25e2207262165534e90c91536&scene=21#wechat_redirect)》

《[如何禁止Namenode格式化](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492135&idx=5&sn=f7605604b5af35482e38037d6d4900fe&chksm=ec29322edb5ebb38056c2f7aa31995ffd81310b444c105b6d4dc175a1f45cb2f64f903efc159&scene=21#wechat_redirect)》

《[如何通过CM为HDFS启用Federation](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492135&idx=6&sn=3178632491544b406ad40ef3da8dfba1&chksm=ec29322edb5ebb38556165f87344fc8760e293596f83f7cf30f99846776e1c3305d3f1d12cd9&scene=21#wechat_redirect)》

《[如何通过CM禁用Federation](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492135&idx=7&sn=0ac5148a27cdf2be91389103319f9c57&chksm=ec29322edb5ebb3854c3c8c8021be1e9986f5ab0f95a83cd62baad45d61122061df661cd450a&scene=21#wechat_redirect)》

《[回顾·基于Impala平台打造交互查询系统](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492582&idx=1&sn=4087ffd7094690410918e0af49a8fa25&chksm=ec2933efdb5ebaf907eaf5c29c694a915a08e28fe62faf2750461c28b022993b5f7ae49132b4&scene=21#wechat_redirect)》

《[Spark Streaming VS Flink](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492640&idx=1&sn=810d7a5d5ab9fcf283b1cc2d186c1e88&chksm=ec293429db5ebd3faed7673683541d365f6fbdfc4c90c42222da97d876b54ea9ede006b3b52c&scene=21#wechat_redirect)》

《[30PB数据1年内迁移到Spark，eBay的经验有何可借鉴之处？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492655&idx=1&sn=07f2868df1da21fc4d9bd837b5198dca&chksm=ec293426db5ebd303c8abdbf3664a50d6581b66ee2f550ae866b3f8e2decceabb5a3d2e4123e&scene=21#wechat_redirect)》

《[潘国庆：如何实现端对端的 exactly once？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492669&idx=2&sn=b332758406723849317b4862443b8132&chksm=ec293434db5ebd221c0412de879efd4b0664a5ca200991d63c83373fd04550e76d37ae9d0321&scene=21#wechat_redirect)》

《[Spark2.4的新功能](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492732&idx=2&sn=72602fd6bc4cea6f3b9f6ca1249de0c8&chksm=ec293475db5ebd636dc3bf6772a725e816141b801a80c326e150b3946c3b4fa62e17d5aafe72&scene=21#wechat_redirect)》

《[杭州造云记](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492761&idx=1&sn=b9c7007600e33d94b96dd0d6de4822ea&chksm=ec293490db5ebd86b93183b4422e1059f8a77b95e7ad6fe26dc38f613e62908f410f876ff764&scene=21#wechat_redirect)》

《[首发 | OceanBase 2.0 重磅发布，全面降低金融业务向分布式架构转型的技术风险](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492781&idx=1&sn=31a713cd0fa59dd636c5e2da04a2b29a&chksm=ec2934a4db5ebdb2a7f95e763647b3ac53c751fea53421ae8ac8c4f2e795e4ec535348cb3861&scene=21#wechat_redirect)》

《[Cloudera与Hortonworks合并](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492884&idx=1&sn=671e4fe77747d3f7cb92b57bc7169f7a&chksm=ec29351ddb5ebc0b52ba3dc223c210417f190e4579bd2ddd340d5c7d87b8b1bc7d5f1b97604e&scene=21#wechat_redirect)》

《[两大数据平台Cloudera和Hortonworks宣布合并，计划创建首个企业数据云](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492912&idx=2&sn=59b918eae16b8e3f133e763a19b01f65&chksm=ec293539db5ebc2f086012a08932f0956fa6f4c9206ea3b6e7693d10c40760fb7b81308c7ca3&scene=21#wechat_redirect)》

《[重磅！Cloudera、Hortonworks 合并 ！免费的好日子不多了](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492951&idx=2&sn=bac862b38545217034a18c73b6b33fda&chksm=ec29355edb5ebc480b49599dc94e31f112d5cc1019887d2a2ec51e75a814ab5088235f835437&scene=21#wechat_redirect)》

《[大新闻！Elasticsearch上市！](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247492976&idx=2&sn=e9c642fd4e12e441229c2145fe3c2d44&chksm=ec293579db5ebc6fc829eee12a09f26ca70d00a2616876ccbc4aec0e821d05f3188fca5a0e70&scene=21#wechat_redirect)》

《[大数据凉了？No，流式计算浪潮才刚刚开始！](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493025&idx=2&sn=1bde92d832db35162507838c01e1b343&chksm=ec2935a8db5ebcbe9c0057499124df42b0d93dbdc792da2540de104cf4e7c2caec73572cc2fe&scene=21#wechat_redirect)》

《[YARN 资源调度那些事儿](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247493045&idx=2&sn=396573d757bceb46f1b3137e2f22d79c&chksm=ec2935bcdb5ebcaa64a653d04b45d0101be6c49d2f2e434198c385d1bc977d6b48d0cf5680ed&scene=21#wechat_redirect)》

《[SparkSQL 在有赞的实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495596&idx=1&sn=bf85df7246213eff6a6b7dc438e35dc2&chksm=ec293fa5db5eb6b34694ab625b135055a77e02e676fecef970ab8e6cb2543d053bbd394203bd&scene=21#wechat_redirect)》

《[Flink 在有赞实时计算的实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495673&idx=1&sn=8458bdfb9c6372ae22bc9d285859c4d9&chksm=ec293ff0db5eb6e6f86aefd51b44313732bbc081c60444e23a0ad34d21c5ee2168b0b305ca4a&scene=21#wechat_redirect)》

《[有赞大数据平台安全建设实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495696&idx=1&sn=a6255e5dabb19a27dc5dea2f939b0c2c&chksm=ec292019db5ea90f9b3cc7e6908c3095eb369d1a098b809c218f24af11b24c795d9c02a6920a&scene=21#wechat_redirect)》

《[人工智障 2 : 你看到的AI与智能无关](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495814&idx=1&sn=b8cc738501bfcf06781f34cfad492e28&chksm=ec29208fdb5ea999c911b20f892076614e00f7878f97f2a304dd628b648ee54cffc445207f51&scene=21#wechat_redirect)》

《[Spark Streaming 在数据平台日志解析功能的应用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247495974&idx=1&sn=0bcfd6189bcf8d4a6b3fa0f7d3bcdc18&chksm=ec29212fdb5ea839c876ebf1b742ad6f8a30a88aed56a30be0b894805c64912c664fbb9703bb&scene=21#wechat_redirect)》

《[HBase 写吞吐场景资源消耗量化分析及优化](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496073&idx=1&sn=738ea06e044640091e6d9fbbdc89f6ea&chksm=ec292180db5ea8969c49ccc499d6c0f2b06b06200d24d38a1ed7e201a39be4668fae51ded0c2&scene=21#wechat_redirect)》

《[Druid 在有赞的实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496165&idx=1&sn=90c196f682a846cdf90e4307c0f14f63&chksm=ec2921ecdb5ea8fa4ed665a0a8e241e23a77ae54d5239f80d78e978750da90dbba37e52c8245&scene=21#wechat_redirect)》

《[HBase 读流程解析与优化的最佳实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496587&idx=1&sn=fa62a4ab7e69b7500408350a2f395650&chksm=ec292382db5eaa94906d50af44c9ef03e28e21a37f92ecb44eb9715586272a2f98bb2127b6a2&scene=21#wechat_redirect)》

《[Flume 在有赞大数据的实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496599&idx=1&sn=5288573878c6082e39289a8ecb6ed3a2&chksm=ec29239edb5eaa88cd9ee8a285e099a7f74cbaa7e253fc20bf4b93fd41fe048097b78b847b23&scene=21#wechat_redirect)》

《[Druid Segment Balance 及其代价计算函数分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496634&idx=1&sn=a825c4e30918fd7166d22ca20a2d7268&chksm=ec2923b3db5eaaa516ba5535013b90d65b6874a0868f7d0fc5c6e560c308b9b7464bb3d15e91&scene=21#wechat_redirect)》

《[浅析 Spark Shuffle 内存使用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247496645&idx=1&sn=e25a6aa3c182b8db18ca974bff723a29&chksm=ec2923ccdb5eaadac5add1ea627f9c9e36ac08a90696a67aec0520119cb0f65f1edbee754a62&scene=21#wechat_redirect)》

《[重磅 | Apache Spark 社区期待的 Delta Lake 开源了](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497671&idx=2&sn=a94077cc141e82701bbdc5beb120f0fc&chksm=ec2927cedb5eaed8e36dda64d229a77bc0c9e76a8c2e4640fe164163d4f4aa1e8a9255632611&scene=21#wechat_redirect)》

《[解读2018：13家开源框架谁能统一流计算？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497689&idx=1&sn=651bb99e39f696a994f1bf836de75920&chksm=ec2927d0db5eaec64a9fe4d17e5b1b98786af49b047e6fde464393b84869a788ccd6694b7526&scene=21#wechat_redirect)》

《[从Storm到Flink，有赞五年实时计算效率提升实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247497968&idx=1&sn=d88229aa510c9d8382705bc754a731e5&chksm=ec2928f9db5ea1ef2eb5f5c5761d40e4890f60af83fa7109895ab9356a718ddcd82785279cca&scene=21#wechat_redirect)》

《[0643-转载-余利华：网易大数据平台架构实践分享](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498257&idx=2&sn=e13fe6b4db2db598852f59d5357ab31d&chksm=ec292a18db5ea30efce52f01de3fc1f3cd400f85b2f3ca28367690377a60d8631f50fe4b5611&scene=21#wechat_redirect)》

《[【生活现场】从洗袜子到hbase存储原理解析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498342&idx=2&sn=0137390492a49d2d9fe8d26d4c7c1743&chksm=ec292a6fdb5ea379be45df4c881463591d302e1950c51fd5e1c1d1c05d3fa7373a10df86c9e3&scene=21#wechat_redirect)》

《[OLAP 分析已死？真的真的么？!](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498416&idx=1&sn=901716a69cf629a802fd15ebbf639663&chksm=ec292ab9db5ea3afff6590502bbe29c321bc6edf0551463351623d9f38a888728704e4bccc9c&scene=21#wechat_redirect)》

《[DataX在有赞大数据平台的实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498418&idx=1&sn=14bb6782549ea74d7ac9fba34108e293&chksm=ec292abbdb5ea3ad575de03bc3e589ba7d6819da2715d31a72a2ee3128db5748c45758fde728&scene=21#wechat_redirect)》

《[我是如何成为Apache Kudu committer & PMC的？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498517&idx=1&sn=efd759f31b114f5e52ccfb531e8c0919&chksm=ec292b1cdb5ea20a60fb1049f700d228175d138dcefb58a3f66173a3307729e17fcb86e24f3f&scene=21#wechat_redirect)》

《[Zeppelin: 让大数据插上机器学习的翅膀](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498519&idx=1&sn=4b12ad511536bc6cad602087a8a5eac5&chksm=ec292b1edb5ea208e425a586a049fe0c601e0a2660e8fda1f222781a4368129f61dc9a6b77b6&scene=21#wechat_redirect)》

《[你为什么还在用存储过程？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498709&idx=1&sn=36fd1414b1ad11861268ced76b94a71a&chksm=ec292bdcdb5ea2ca889cca522374619c6a61e334cc52d624742c168a91e51b4870b0dffcf1ef&scene=21#wechat_redirect)》

《[你是一直认为 count(1) 比 count(*) 效率高么？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498711&idx=1&sn=55f072afbffd5774b50b58834674bc01&chksm=ec292bdedb5ea2c8e8a4c22b4ecaa84a07dae95570fe33b6b67c021a6174481c7ea6b494a29c&scene=21#wechat_redirect)》

《[从这个角度，我终于理解为什么需要Kafka这样的东西了!](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498816&idx=1&sn=4d44490a014a9f322061da7147b67ff4&chksm=ec292c49db5ea55f4ae540e834e5a8bf0aaaadcc57d724279efec979d2cc6abf1a83ca473d8b&scene=21#wechat_redirect)》

《[干货 | 每天十亿级数据更新，秒出查询结果，ClickHouse在携程酒店的应用](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498818&idx=1&sn=3c8ef1cac1f2e4f509112d886e5e631f&chksm=ec292c4bdb5ea55d6c11e7bdf3feabf7b80de8b00b3248712b110879ee5274ff1d239ba7a1b1&scene=21#wechat_redirect)》

《[Apache Druid 0.15.0版本发布](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498836&idx=1&sn=da82d22f9c90e27900cfb4e1f1d8abc6&chksm=ec292c5ddb5ea54b09d64455f117c2f7e034f0742f12a75bce25d62348e7ea6fa0209218dc9b&scene=21#wechat_redirect)》

《[Cloudera对开源的承诺](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498870&idx=1&sn=024d4885b3391d3eb47a200f7071265f&chksm=ec292c7fdb5ea56960a2f4a643b07bc5fe0648bc54b141894fe5d33863af5ab9b87c1c9e2648&scene=21#wechat_redirect)》

《[Cloudera独家回应：Hadoop到底怎么了？](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498872&idx=1&sn=f174ae64a800ebd0299d491defb80590&chksm=ec292c71db5ea5673a6a0e816bc81ae12003ab53decc9f1245b897b15f01e6d901164ca91afb&scene=21#wechat_redirect)》

《[微博基于ClickHouse灵活监控百亿流量下的业务指标](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498874&idx=1&sn=c98b5808d0276b07696022085e7304bc&chksm=ec292c73db5ea565b7adcb0ca9feea3f130a7762401d0cace12586d6fbe94aa38ab4405bc9ae&scene=21#wechat_redirect)》

《[史上最全-mysql迁移到clickhouse的5种办法](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498991&idx=1&sn=3375d71b98154f7c582b7f11e485a3c0&chksm=ec292ce6db5ea5f0b9526d0ae081b00c2af4c5b4d4b1f35f4cdb676a291cc34524001e56aa47&scene=21#wechat_redirect)》

《[SQL on Hadoop在快手大数据平台的实践与优化](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498995&idx=1&sn=35b17e2485bd3ac2424776febbfa0e34&chksm=ec292cfadb5ea5ec3fb9363e2849638246b5e00f26530dfc3c301e46891078ec36767479ce2f&scene=21#wechat_redirect)》

《[YuniKorn：一个通用的资源调度程序](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247498999&idx=1&sn=7dd52bf01fc2c2ee73f9b13d47942aee&chksm=ec292cfedb5ea5e83c2df51ae677780ea2f36e8331bea2a21c36718275295aec99910e5a8a1f&scene=21#wechat_redirect)》

《[HDFS Router-based Federation](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499050&idx=1&sn=4bc3337f59e53db39270a778ac768c64&chksm=ec292d23db5ea435dfce5c7f4dfae5acc2dcb8d7fef1551fbcb6aa6c867c2eac30639d04b97c&scene=21#wechat_redirect)》

《[Hive在DB-Engine的排名已经超过Teradata](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499052&idx=1&sn=d4912113a085a4420cab9c89960e618f&chksm=ec292d25db5ea4330ae3f6f71700e68bb323c0604ba9db22200b692f96f6fb0deb6912872ef0&scene=21#wechat_redirect)》

《[独家｜手把手教你赋能Jupyter Notebooks！（附代码）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499195&idx=1&sn=84183c7af4f55f890b909091e640d8cc&chksm=ec292db2db5ea4a4b83d0fa3c26604f738bcbc8a42b19a76bb4cd70857e0b07f825f8b18c96c&scene=21#wechat_redirect)》

《[快手 HBase 在千亿级用户特征数据分析中的应用与实践](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247499382&idx=1&sn=d17a5a3f58fed447c664169d4fd0a6d4&chksm=ec292e7fdb5ea769d7a70a3996f23a4b4eb22a06a755fefd617c049a7c17081bc0cb9f74b21b&scene=21#wechat_redirect)》

《[Hadoop 对象存储 Ozone](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500181&idx=1&sn=11f7032f6220286d6c2575e966f9ad88&chksm=ec29119cdb5e988a39abae41d7eb55540b0e1e46427b479ddcb6fde8ebfa2256ec8ca2932ffe&scene=21#wechat_redirect)》

《[Kafka异地双活深度讲解 - Mirrormaker V2](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500183&idx=1&sn=92f6b8e4c22ef9c3ae8b21d93025ec95&chksm=ec29119edb5e98886edb9761bfc0ae9caf09c3200cb7c7495c6557cffe1b406e2d1a8fb441ff&scene=21#wechat_redirect)》

《[Apache Submarine](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500910&idx=1&sn=8696d2c9f8e363cdf8833b4a9f81400b&chksm=ec291467db5e9d71878799e0b70dd5f2660e09ffca5fdbd2e63fd24ed2727a5181e7463702a3&scene=21#wechat_redirect)》

《[Impala查询卡顿分析案例](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247500912&idx=1&sn=414400b4a72d8ac50d29cee53a7bf2d8&chksm=ec291479db5e9d6f302ebb57aac2199f576aa55c8953f839da7818955bc7cf4fb05413b6f75a&scene=21#wechat_redirect)》

《[如何对CDH集群中的Impala打印线程堆栈](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501073&idx=1&sn=c5551218a3242576fb99d86fc7e4bae7&chksm=ec291518db5e9c0e6707fb8dcb57bd153ff7a780d5c22ee537cc131b97c749fc699e2b4ad6b4&scene=21#wechat_redirect)》

《[Delta Lake - 数据湖的数据可靠性](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501090&idx=1&sn=3b823925684f772aa214269820e48faf&chksm=ec29152bdb5e9c3db94a6737bd37467303917f2227aa04e7439fc7beda5ed5d2bea7a9fa1e11&scene=21#wechat_redirect)》

《[Impala元数据简介](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501229&idx=1&sn=c24551b555ee16ffc73b10c682bec62a&chksm=ec2915a4db5e9cb210abcf55f75929bf01f89534f764ff378ade064f1fd60a31a86495ad1a12&scene=21#wechat_redirect)》

《[一步一步理解Impala query profile（一）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501239&idx=1&sn=9e361f77e045c8cb7fee686177ed73e6&chksm=ec2915bedb5e9ca8867adebdb4af15ebac96690055c308e348b9e6336bcef500b9a28ab3d93a&scene=21#wechat_redirect)》

《[一步一步理解Impala query profile（二）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501243&idx=1&sn=3741bc7876c766bf162803179570ba33&chksm=ec2915b2db5e9ca4d1f8bd0f77ab88a9abf2b0de63f83f89748a01fc2a8130545368ccd46e7d&scene=21#wechat_redirect)》

《[一步一步理解 Impala query profile（三）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501247&idx=1&sn=f5b3188a7a933b4ac8dc2de7a5e62856&chksm=ec2915b6db5e9ca099fcdcc1078c6ccb005e03e8dc85e29317260bb80b49fc1008864c155ab5&scene=21#wechat_redirect)》

《[HBase Bulkload 实践探讨](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501275&idx=1&sn=b17aa21b344a4bd378500f1485aa49f8&chksm=ec2915d2db5e9cc4d6d89a0bb9cb1b44a28ab442021abea07a58a20d070aed830b61d8c73ac4&scene=21#wechat_redirect)》

《[接着！！大数据入门实用技术栈全在这里了](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501326&idx=1&sn=e706b09ce4d983e1007fca304b01aea2&chksm=ec291607db5e9f11b9d99136b4df533ae9cda671c163d73ba19d7170486bfcc2e02f18abcf8f&scene=21#wechat_redirect)》

《[最新消息！Cloudera 全球发行版正式集成 Apache Flink](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501328&idx=1&sn=ebb37d6b7dfbda25aac0d961e985ec1a&chksm=ec291619db5e9f0f3ebeef4581844c3a13d6325c54d27fc22242a67e31897ad521fdce24ba1f&scene=21#wechat_redirect)》

《[从开发到生产上线，如何确定集群大小?](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501362&idx=1&sn=aee9ab7a8166fdd8cba9dfff85921418&chksm=ec29163bdb5e9f2d82a37de15d18ba61ef9b074507a39487076a80513922618f8735a75b2cc2&scene=21#wechat_redirect)》

《[Hive 终于等来了 Flink](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501364&idx=1&sn=6640ea6698460e5126fac6936d0d45cd&chksm=ec29163ddb5e9f2b24453e968dcc75b565e4910add180271a1472f1593e97d9b17551005839d&scene=21#wechat_redirect)》

《[一步一步理解 Impala query profile（四）](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501380&idx=1&sn=6df86240b348ca9e0490fa5037d150a5&chksm=ec29164ddb5e9f5b73c7ae777349bf146873cf52d482b79e779abab049004675f7bb20e38c1b&scene=21#wechat_redirect)》

《[Apache Flink 1.10.0 重磅发布,年度最大规模版本升级！](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501382&idx=1&sn=d79d3f6600bc725efa09f02110c97d52&chksm=ec29164fdb5e9f598fb62113f3892d2c586feaca5a9151fdc2e62c68a647b785dca437385b8e&scene=21#wechat_redirect)》

《[PySpark工作原理](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501389&idx=1&sn=ced4f416b7a8ab9a243013f577109286&chksm=ec291644db5e9f52e2dcf687040ce01de326b5ffe60d7a2af70ac20bb87724a88153ba64af7c&scene=21#wechat_redirect)》

《[如何在CDH5.16.2中部署Apache Dolphin Scheduler 1.2.0](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501432&idx=1&sn=c20b19b49b11af5f583e430dfd240876&chksm=ec291671db5e9f6785e48e8c73ceec02c3eb12c6be07459a57bbb9238584b3ae2aadd8a7529d&scene=21#wechat_redirect)》

《[Calcite技术研究](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501446&idx=2&sn=b81c166c8cb426accb27239b3f333f14&chksm=ec29168fdb5e9f9994975567a66907ff767f2b1b1c84d667fea85e730690134ed14e28e7e3e0&scene=21#wechat_redirect)》

《[PySpark启动过程解密](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501446&idx=1&sn=c8020ecdd562d77e0485f6575c43f102&chksm=ec29168fdb5e9f99decd056f4e95e0d74de94e2de7ceb4050c83063d4e6112d8b6f039ad8b56&scene=21#wechat_redirect)》

《[Flink 1.10 新特性研究](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501683&idx=1&sn=3cb43a35cdfb11f3daff321be6675a29&chksm=ec29177adb5e9e6cab99e053c3c1027cb19c1862eb2aef3d57cf0315463351ae1ba11e12270d&scene=21#wechat_redirect)》

《[SparkSql读取hive表tblproperties异常](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501710&idx=1&sn=d7f7a325fbbbf1385e2e38748971ee5b&chksm=ec291787db5e9e91ca61af6a881a9e7753a8f75ec5bf98007083dc1bc3945eea82ffcea3df52&scene=21#wechat_redirect)》

《[Dolphin Scheduler 1.2.0 部署参数分析](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501712&idx=1&sn=45bb06ef1a2ce3a8905cbcb89f0c2d25&chksm=ec291799db5e9e8f2d6b0ac2a1f6d38b55a724bb1d71decdb335d5e6f39bb6d1c67775f5b999&scene=21#wechat_redirect)》

《[Dolphin Scheduler秒级别工作流异常处理](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501714&idx=1&sn=9aea14e39f1d143da52c4e12913df09d&chksm=ec29179bdb5e9e8daeb2e3b8fb7bdd401447825ee66b2a5a2e523f2e6026627941091666f138&scene=21#wechat_redirect)》

《[Impala元数据缓存的生命周期](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501716&idx=1&sn=e65750a4c95a3631913838076be36925&chksm=ec29179ddb5e9e8ba3b4236bd9481069e6bfc2d042f95fc1ba6c8dee684456b66ba5ca3151d5&scene=21#wechat_redirect)》

《[一次Impala upsert kudu执行缓慢问题排查总结](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501718&idx=1&sn=b212ad480bacc400f433694844417158&chksm=ec29179fdb5e9e8950ff5259dcad5380854bca106308a5e745bb4306246687b84e5dc71fe666&scene=21#wechat_redirect)》

《[在Apache Kudu上对时间序列工作负载进行基准测试](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501790&idx=1&sn=a74c509237b69847c4a771c69258a569&chksm=ec2917d7db5e9ec169ab3bb5deee42a91998e5d7c11e055ee96978e86bddf49342b3268cc6d5&scene=21#wechat_redirect)》

《[推荐升级四部曲之 CM 升级，收藏了！](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502003&idx=2&sn=0f8d760a402e9cb8f99f1633e99c571a&chksm=ec2918badb5e91ac15e7569f06ed70fc57ec0e79a3cf880e6745df4069bf2961da3f2fb67aab&scene=21#wechat_redirect)》

《[推荐升级四部曲之 CDH 升级重头戏，收藏了！](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502153&idx=3&sn=d001b2309ba99dcb89f7c43b8b7eed62&chksm=ec291940db5e90561b926ac67ec1f16f188a0489de9c8d739c43248a49cc43c188ddcc7ba399&scene=21#wechat_redirect)》

《[Impala 3.4的新功能和社区进展](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502153&idx=2&sn=e58b6774c5a253e4092acb54fea0842f&chksm=ec291940db5e905641e795f96a840993fa9d1a840c96db717e6e0286a773c548b7048560b316&scene=21#wechat_redirect)》

《[推荐升级四部曲之 CDH 手动升级，奔涌吧！](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502158&idx=2&sn=6e8d891cbc1f1ff0fbcb33899ea6751d&chksm=ec291947db5e90513c632f805e1ba699d04b87564ec0d8ba2922dc5582776dc62e4fe11957ab&scene=21#wechat_redirect)》

《[Hadoop 3.x 时代，EC 露个脸呗！](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502198&idx=2&sn=8a5cdf19a7bb0c89f8bf6bb32016b4a3&chksm=ec29197fdb5e906926080413f8944f837a077906ddbdce7137fe4485a29b4c978c6f15cd84c4&scene=21#wechat_redirect)》

《[重磅 | Hadoop的第二个十年](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247501430&idx=2&sn=0bc64003af658a4da8dc28f010eb42f4&chksm=ec29167fdb5e9f692b0a25a62eba0b1ab22a0b21f7c1073a86000f3c9516753ca7684fa6ad67&scene=21#wechat_redirect)》

《[全国首个！广东移动1000+大数据集群成功升级！](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247502832&idx=2&sn=aac619a645110fa91854fcfe603866ba&chksm=ec291bf9db5e92efe681d271a32b128eb52ff969c71d741a520e8d054aa9c914137a9eaac49a&scene=21#wechat_redirect)》

《[聊聊自主可控和开源](http://mp.weixin.qq.com/s?__biz=MzI4OTY3MTUyNg==&mid=2247503181&idx=1&sn=05f20ff80d83feb650bd7af948c4cad9&chksm=ec291d44db5e945201719ad265c591e0c4f997a60a8a840fd8f14cc00641c52f252f54d31f17&scene=21#wechat_redirect)》



> Fayson的github：
>
> https://github.com/fayson/cdhproject