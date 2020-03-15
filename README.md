### 系统介绍：
- 支持个人网站、安卓App、微信公众号、Pc软件收款的接入，所有的资金都会实时到账您的支付宝/微信余额中，支付宝无需上传收款二维码，支持H5唤醒支付，支持回调通知、支持补单、后台功能简单。

- 支付回调通知，0手续费实时到账（不经过任何第三方，直接到账微信/支付宝余额），全部服务端源代码，支持php/java/python等语言直接接入(请使用Api版本傻瓜式接入)，监听方式非xp框架HOOK的方式，独立App监听安全无风险，无需root权限。

### 系统原理： 
- 当收到支付宝、微信、实时收款信息，客户端会实时通知服务器收款金额和方式，服务器收到有效期订单金额后处理订单状态，使用随机减免的方式区分订单（5分钟订单有效期内有相同金额的订单会随机减免0.01 - 0.10的方式用来区分订单。

### 本系统的部分核心功能：

- 1.tcp服务端支持分布式部署，让您的服务实现高可用，单机抗几万android手机连接不是问题，XP框架监控，监控需安卓7.0环境！
- 2.系统由调用接口+代收接口一体化，客户可选择使用调用接口或者代收接口
- 3.后台有手动补单工具，服务端APP监控 
- 4.多通道收款模式以及当面付账号池，多种轮训方式，
- 5.每条通道都可以独立限制风控单笔金额以及日总收入额，超出停止收款
- 6.支持支付宝，微信各种收款模式，无畏风控风险。
- 7.提供强大的后台管理，商户端，api文档等一应俱全！ 



### 使用本系统的优势：

- 1、无需对接三方通道、保障资金的安全掌控。 
- 2、0费率、不用再为三方/四方高额的手续费而感到烦恼。
- 3、资金直接到商户的个人账户、保证商户资金的安全、对于平台拓展商户有绝大优势。
- 4、灵活多变、商户可配置多个账户。系统带有账户轮询，避免风控封号风险。 
- 5、支持对系统进行功能定制、预充值式手续费设置，满足您的一切需求！  

### 在线测试
- 本项目演示地址： [点此测试](http://xmpay.jmkeji.net)

### 源码下载
- 本项目源码下载： [点此下载](http://xmpay.jmkeji.net)
