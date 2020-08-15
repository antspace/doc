## 1、概述 {#ss0}

```
为了保障淘宝开放平台（即Taobao Open Platform，以下简称“TOP”）用户（以下可简称“平台用户”）的数据安全和运营信息安全，淘宝开放平台除继续对API使用资源全面优化外，同时将数据同步资源纳入全面优化范畴，持续提高开发者合理利用平台资源的能力，推动TOP更加良性的发展。 2017年1月1日开始，淘宝将维持开放平台对所有调用TOP接口的开发者的API收费，同时对所有使用数据同步服务的开发者启动收费，从而帮助平台用户建立更为合理的运营机制，使其最终受益。此外为了鼓励新业务以及扶持中小开发者的快速成长，淘宝将对符合条件的开发者适用优惠政策，让整个开放平台的生态体系更加健康有序地发展。 具体收费说明：[开放平台技术服务费规则](https://open.taobao.com/docV3.htm?docId=104559&docType=1)
```

## 2、费用查看 {#ss1}

进入开放平台控制台，点击个人中心--费用中心 --技术服务费

![](http://img01.taobaocdn.com/top/i1/LB1sr.NMbr1gK0jSZR0XXbP8XXa)

## 3、技术服务费的支付与结算 {#ss2}

1. 技术服务费收费采用如下两种可选模式： 
   * 预充值方式，请开发者提前进行充值，充值方法参见（
     [链接](http://open.taobao.com/doc/detail.htm?id=102039)
     ）
   * 支付宝代扣。您可以在控制台签署支付宝代扣服务协议，开通代扣服务，系统每日将从您的支付宝账户根据您的实际消耗情况进行扣费。
2. 开发者Appkey调用API的情况或者每日新增订单量的情况一旦满足任一计费条件的，淘宝将按照收费细则从充值余额或支付宝账户中按日扣费。 

![](http://img01.taobaocdn.com/top/i1/LB10K4Af8fH8KJjy1XbXXbLdXXa)

## 4、欠费处理规则 {#ss3}

为避免欠费对开发者的应用/或开发者的应用的订购用户造成影响，淘宝制定了技术服务费的缴费及欠费处理规则，相关内容以平台公示的《[开放平台技术服务费欠费处理规则》](https://open.taobao.com/docV3.htm?docId=102106&docType=1)为准。

## 5、FAQ: {#ss4}

1、当日新增订单量是怎么理解？

答：每个应用当日新增订单量包括两部分：\(1\)推送的当日新增推送用户的历史订单量；（2）推送的所有推送用户的当日新增订单量”。

2、数据同步服务中哪些业务会被计费？新增分销订单会被计费吗？

答：只统计淘宝/天猫交易订单。数据同步服务中的商品/分销/经销/退款等业务不会被统计计费。

3、父子订单的情况，如何统计计费？

答：只统计新增主订单的情况。

4、去哪里查看账单？

答：控制台--技术服务费管理页面，选择：数据同步服务费用账单。

5、去哪里进行充值缴费？

答：控制台--收费管理页面，点：充值完成。建议开通支付宝代扣，以免充值不及时欠费处罚对应于的使用造成影响。

6、去哪里申请发票？

答：开票地址：[https://pay.taobao.com/servicer/userScBill.htm?servicerindex=servicer\#/invoice-info?\_k=vfhcq2](https://pay.taobao.com/servicer/userScBill.htm?servicerindex=servicer#/invoice-info?_k=vfhcq2)

具体操作参考文档[//open.taobao.com/docs/doc.htm?spm=a219a.7386797.0.0.mWdVic&treeId=1&articleId=102178&docType=1](https://open.taobao.com/docV3.htm?docId=102178&docType=1)

7、发票抬头去哪里维护修改?

答：参考文档[//open.taobao.com/docs/doc.htm?spm=a219a.7386797.0.0.dWNvG3&treeId=1&articleId=101105&docType=1](https://open.taobao.com/docV3.htm?docId=101105&docType=1)









