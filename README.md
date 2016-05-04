# alipay-drupal-userpoint
使用Drupal开发完成实现了Drupal集成支付宝，通过支付宝进行积分充值功能的Drupal模块，具体功能描述如下：

1、Drupal集成支付宝在线对账户进行积分充值；

2、Drupal实现充值卡充值：通过销售充值卡给客户，客户在Drupal网站上输入充值卡密码的方式充值；

3、支付宝充值、充值卡充值集成userpoint 模块：解决了从支付宝充值->获得积分->通过积分消费的整个流程。

4、充值日志记录：个人可以查看充值、消费记录，管理员可以查看所有用户的积分增/减记录；

正在开发的功能：

1、扩展支付宝充值后，积分消费的相关功能，如开发接口，以实现其他模块调用消费接口；

2、支持消费时选择支付宝支付或者积分支付；

3、支持同一订单，同时使用积分余额和支付宝进行支付，适用于积分不足以支付订单全部金额的情况。

4、在drupal开发中，经常遇到虚拟物品交易、游戏币交易、电子书书购买、在线预约、网上挂号等应用，这些实际应用使用Drupal的电子商务模块很不合适，Drupal自带的电子商务模块也不太适合中国国情，我的目的是希望通过支付宝充值及交易这个模块，在Drupal开发中解决以上问题。
详见：http://www.5188jxt.com/technology/85.htm
