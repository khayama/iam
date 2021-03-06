---

copyright:

  years: 2017, 2019

lastupdated: "2019-01-30"

keywords: user state, user status, type of user

subcollection: iam

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}


# 用户状态
{: #user_status}

邀请用户加入帐户后，根据用户的类型及其接受邀请的状态，会为他们分配状态，状态会显示在特定用户的**用户详细信息**页面上。
{:shortdesc}

|用户状态|描述
|
|:-----------|:------------|
|活动|用户已接受邀请，并分配有可在帐户内工作的访问权。|
|已禁用经典基础架构|帐户所有者或具有足够许可权的用户可以将其他用户设置为已禁用，使该用户无法再访问经典基础架构资源。该用户可以继续登录到控制台并访问平台资源。|
|仅使用 VPN|在帐户中创建但限制为仅使用设备的 VPN 访问的用户。此类型的用户无权登录控制台。|
|正在处理|此状态十分少见，表示已将用户添加到邀请，但该邀请尚未发送，而系统已创建该用户的第一个实例。|
|待处理|此状态表示已邀请用户，但该用户尚未接受邀请或尚未通过创建 {{site.data.keyword.Bluemix_notm}} 帐户加入帐户。|
{: caption="表 1. 用户状态" caption-side="top"}

有关更改用户状态的信息，请参阅[更新用户的状态](/docs/iam?topic=iam-status#status)。
