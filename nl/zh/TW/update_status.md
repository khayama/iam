---

copyright:
  years: 2018, 2019
lastupdated: "2019-01-28"

keywords: user state, user status, change user status, update user status

subcollection: iam

---


{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:note: .note}

# 更新使用者的狀態
{: #status}

使用者的已指派狀態取決於使用者是否已接受其邀請加入帳戶、他們是否為僅限 VPN 使用者，或是使用者管理者是否將使用者設為已停用標準基礎架構使用者。
{:shortdesc}

如果您具有下列存取權，則可以更新另一位使用者的狀態：

  * 「使用者管理服務」上具有「編輯者」或更高角色的 IAM 原則。
  * 您是使用者之標準基礎架構階層中的上代，而且您已獲指派「管理使用者」標準基礎架構許可權。

如需使用者狀態類型的相關資訊，請參閱[使用者狀態](/docs/iam?topic=iam-user_status#user_status)。

## 變更使用者狀態的選項
{: #status_options}

您可以選擇下列選項來更新使用者的狀態：

<dl>
<dt>作用中</dt>
<dd>使用者可以根據其已指派的存取原則及標準基礎架構許可權來完整存取 {{site.data.keyword.cloud_notm}} 主控台。</dd>
<dt>已停用標準基礎架構</dt>
<dd>使用者無法再存取標準基礎架構資源，但可以繼續登入主控台以及存取平台資源。</dd>
<dt>僅限 VPN</dt>
<dd>使用者無法登入主控台，但只要直接登入應用裝置，即可存取您指派給標準基礎架構的任何裝置及 VPN 子網路。</dd>
</dl>

將使用者從「僅限 VPN」狀態更新為「作用中」狀態時，使用者必須知道登入主控台的密碼。在大部分情況下，這是 SoftLayer ID 密碼，其可能需要重設才能使用。在使用者已有 IBM ID 的少數情況下，他們必須使用 IBM ID 及密碼登入。
{: note}

## 更新使用者的狀態
{: #update_user_status}

若要變更使用者的狀態，請完成下列步驟：

1. 從功能表列按一下**管理** &gt; **存取 (IAM)**，然後選取**使用者**。
2. 從清單選取使用者。
3. 從「使用者詳細資料」頁面，選取**使用者狀態**功能表中的一個選項。  
4. 按一下**套用**。
