# **一、入驻成为开发者** {#s0}

使用开放平台任何能力和产品首先要入驻成为开放平台开发者。

1.打开[开放平台首页](http://open.taobao.com/)，点击[控制台](http://console.open.taobao.com/)。

![](http://img01.taobaocdn.com/top/i1/LB1U209mNn1gK0jSZKPXXXvUXXa)

2.使用淘宝账号登陆，账号必须完成支付宝账号绑定。再填写开发者基本信息，邮箱和手机。

![](http://img01.taobaocdn.com/top/i1/LB1B205mUz1gK0jSZLeXXb9kVXa)

3.完成手机验证，提交即可完成入驻。 

![](http://img01.taobaocdn.com/top/i1/LB1Rfx5mQL0gK0jSZFtXXXQCXXa)

# **二、创建应用** {#s1}

## 1.选择需要接入的类目 {#ss0}

开放平台目前将所有开放的业务分为电商后台、商家应用、无线开放以及其他4类，选择适合您业务的应用标签进行申请。

目前部分业务接入已经饱和，不对外提供应用标签的申请入口，具体开放接入说明参考[平台公告](https://open.taobao.com/anno?docId=0&docType=11) 。

![](http://img01.taobaocdn.com/top/i1/LB1Ljx8mKH2gK0jSZFEXXcqMpXa)

## 2、申请应用创建资质 {#ss1}

选择需要接入的应用类目，每个类目有相应的接入资质需求，可以查看资质要求。

![](http://img01.taobaocdn.com/top/i1/LB1ELF6mKL2gK0jSZPhXXahvXXa)

选择商家应用，可以查看类目详细开放能力。

![](http://img01.taobaocdn.com/top/i1/LB1wWOXmRr0gK0jSZFnXXbRRXXa)



## 3.创建应用 {#ss2}

资质审核通过以后，可以创建应用。

![](http://img01.taobaocdn.com/top/i1/LB1kPJ9mQL0gK0jSZFxXXXWHVXa)

![](http://img01.taobaocdn.com/top/i1/LB1JlX.mHY1gK0jSZTEXXXDQVXa)

![](http://img01.taobaocdn.com/top/i1/LB1y5l8mSf2gK0jSZFPXXXsopXa)

# 三、应用管理 {#s2}

1.进入应用管理，在概览页面的APP证书可以查看App Key和App Secret。

![](http://img01.taobaocdn.com/top/i1/LB1rXuXmHY1gK0jSZTEXXXDQVXa)

2.在页面下方功能场景，查看已获得的api权限中具体的场景介绍和API列表，以及可以申请的api权限，详细可[查阅](https://open.taobao.com/docV3.htm?docId=101269&docType=1)。

![](http://img01.taobaocdn.com/top/i1/LB1n2d_mLb2gK0jSZK9XXaEgFXa)

3、应用流量包申请。

1）appkey处于正式环境测试中状态下每天API调用次数为5000次，无法调高，必须要上线应用才有更大流量。  
2）一般类型应用上线默认流量均为100万/天，个别特殊应用类型上线流量有特殊限制。  
3）流量自助申请可以参考下图，在控制台中，满足升级要求可以直接提升流量包。  
4）流量超限，可以先通过重置流量控制紧急恢复流量。

![](http://img01.taobaocdn.com/top/i1/LB10mF8mFP7gK0jSZFjXXc5aXXa)

4、应用回调url

回调url的主要作用是在使用开放平台oAuth2.0获取获取SessionKey\(或AccessToken\)时，服务器会将登陆授权成功后的信息返回给回调地址

在应用开发调试前需要先补充应用基本信息,包括应用图标（部分应用标签下可选）、商家授权回调url（部分应用标签下可选）;

![](http://img01.taobaocdn.com/top/i1/LB1gv46mFY7gK0jSZKzXXaikpXa)



# 四、开发与测试 {#s3}

`如何正确的调用API`[查阅](https://open.taobao.com/docV3.htm?docId=101617&docType=1)  
`如何使用官方SDK进行开发`[查阅](https://open.taobao.com/docV3.htm?docId=101618&docType=1)  
`什么叫用户授权`[查阅](https://open.taobao.com/docV3.htm?docId=102635&docType=1)  
`使用沙箱环境进行测试`[查阅](http://open.taobao.com/docs/doc.htm?spm=a219a.7386781.1.26.952Q1N&treeId=231&articleId=105496&docType=1)  
`API权限申请`[查阅](https://open.taobao.com/docV3.htm?docId=101269&docType=1)

# 五、发布上线 {#s4}

应用开发测试完成后，提交并经过安全扫描通过通过后即可上线。未上线应用将会被限制API调用流量为5000次/天，3个月内未上线的应用会被系统删除。  
`部分应用类型标签需要发布服务市场给卖家订购：`[发布服务操作](http://open.taobao.com/doc2/detail?&docType=1&articleId=103283)

