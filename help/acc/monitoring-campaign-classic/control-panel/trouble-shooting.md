---
title: トラブルシューティングCampaign コントロールパネル
description: このCampaign コントロールパネルでは、インスタンスと許可リストのIPアドレス別に、SFTPストレージを監視および管理できます。
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '351'
ht-degree: 3%

---


# トラブルシューティング [!UICONTROL Campaign コントロールパネル]

## ログインとホームページ

### 症状： Experience Cloudにログインできません

**操作方法：**
ユーザーは、IMS組織ID(xxx)を探す必要があります。 管理者は、管理する各インスタンスに対して、キャンペーンプロファイル「product-xxx-Admins」にユーザーを追加する必要があります。 ユーザーがすべてのインスタンスの管理者である場合でも、ユーザーとして追加する必要がある場合があります。

### 症状： Experience Cloudホームのリンクから [!UICONTROL Campaign コントロールパネルにアクセスできないリンク] は、ユーザーに対して表示されません

**原因：**
製品プロファイル「キャンペーン-xxx — 管理者/管理者」にユーザーとして追加されるまで、ユーザーにリンクは表示されません。

**操作方法：**
管理者は、管理する各インスタンスに対して、キャンペーンプロファイル「product-xxx-Admins」にユーザーを追加する必要があります。 ユーザーがすべてのインスタンスの管理者である場合、「ユーザー」として追加する必要がある場合があります。

### 症状： インスタンスが [!UICONTROL Campaign コントロールパネルに表示されない]

**原因：**
ほとんどの場合、ユーザーは、見つからないインスタンスに対して「ユーザー」製品プロファイル「キャンペーン-xxx-Administrators/Admin」として追加する必要があります

**操作方法：**
管理者は、管理する各インスタンスに対して、キャンペーンプロファイル「product-xxx-Admins」にユーザーを追加する必要があります。 ユーザーがすべてのインスタンスの管理者である場合でも、「ユーザー」として追加する必要がある場合があります。

### 役立つビデオ

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*IMS組織IDの確認（00:26分）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*製品プロファイルの管理者が[!UICONTROL コントロールパネルを使用できるようにする方法]（01:03分）*

### 便利なドキュメント

* [Campaign コントロールパネルの検出](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [[!UICONTROL コントロールパネルに対する権限の管理]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## SFTPサーバー（クライアントまたはAPI）への接続の確立

SFTPサーバーに接続するには、次の環境が必要です。

* [!UICONTROL SFTPサーバーへの接続元のIPアドレスのリストを許可する]
* Adobe Campaignに登録する必要がある秘密鍵と公開鍵のペア
* SFTPサーバーに直接接続する場合は、SFTPクライアントソフトウェアも必要です

### 役立つドキュメント

* [SFTP サーバーへのログイン](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

