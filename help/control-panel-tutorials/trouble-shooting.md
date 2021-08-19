---
title: Campaign コントロールパネルのトラブルシューティング
description: Campaign コントロールパネル
feature: コントロールパネル
kt: 2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
exl-id: 016e8b77-20df-4ca5-b5e7-fe2f3e7ba7a3
source-git-commit: 2f8ae3d47e4debf71311f341d3c02ff3a7f5297a
workflow-type: tm+mt
source-wordcount: '334'
ht-degree: 40%

---

# [!UICONTROL Campaign コントロールパネル]のトラブルシューティング

## ログインとホームページ

### 症状：Experience Cloud

**対処方法：**
ユーザーは、自分のIMS Org ID(xxx)を特定する必要があります。管理者は、管理する各インスタンスの製品プロファイル「Campaign-xxx-Admins」にユーザーを追加する必要があります。 ユーザーがすべてのインスタンスの管理者である場合は、自分自身をユーザーとして追加する必要があります。

### 症状：Experience Cloud ホームで、[!UICONTROL Campaign コントロールパネル]にアクセスするためのリンクがユーザーに表示されない

**原因：**
製品プロファイル _Campaign-xxx-Administrators/Adminにユーザーとして追加されるまで、ユーザーにはリンクが表示されません_。

**対処方法：**
管理者は、管理する各インスタンスの製品プロファイル _Campaign-xxx-_  Adminsにユーザーを追加する必要があります。ユーザーがすべてのインスタンスの管理者である場合は、自分自身をユーザーとして追加する必要があります。

### 症状：インスタンスが [!UICONTROL Campaign コントロールパネル]に表示されない

**原因：**
ユーザーは、見つからないインスタンスの ** userProductプロフ _ァイルCampaign-xxx-Administrators/_ Adminとして追加される必要がある可能性が高い

**対処方法：**
管理者は、管理する各インスタンスの製品プロファイル _Campaign-xxx-_  Adminsにユーザーを追加する必要があります。ユーザーがすべてのインスタンスの管理者である場合、自分自身を「ユーザー」として追加する必要があります。

### 参考になるビデオ

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS 組織 ID の確認（26 秒）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*製品プロファイル「Administrators」に管理者を追加して [!UICONTROL Campaign コントロールパネル]を使用できるようにする方法（1 分 3 秒）*

### 参考になるドキュメント

* [コントロールパネルの理解](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja)
* [[!UICONTROL Campaign コントロールパネル]に対する権限の管理](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## SFTP サーバーへの接続の確立（クライアントまたは API）

SFTP サーバーに接続するには、以下が必要です。

* SFTP サーバーへの接続元となる IP アドレスを[!UICONTROL 許可リストに登録する]こと
* Adobe Campaignに登録する必要がある秘密鍵と公開鍵のペア
* SFTPサーバーに直接接続するには、SFTPクライアントソフトウェアも必要です

### 参考になるドキュメント {#helpful-docs}

* [SFTP サーバーへのログイン](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
