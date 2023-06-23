---
title: コントロールパネルのトラブルシューティング
description: コントロールパネルを使用すると、インスタンスおよび許可リストの IP アドレスごとに SFTP ストレージを監視および管理できます。
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
source-git-commit: f4e86b933660ced199c30d318445363b74c51c4b
workflow-type: tm+mt
source-wordcount: '342'
ht-degree: 100%

---


# [!UICONTROL コントロールパネル]のトラブルシューティング

## ログインとホームページ

### 症状：Experience Cloud にログインできない

**対処方法：**&#x200B;ユーザーは、自分の IMS 組織 ID（xxx）を見つける必要があります。管理者は、管理するインスタンスごとに、ユーザーを製品プロファイル「Campaign-xxx-Admins」に追加する必要があります。ユーザーがすべてのインスタンスの管理者であっても、自分自身をユーザーとして追加する必要があります。

### 症状：Experience Cloud ホームで、[!UICONTROL コントロールパネル]にアクセスするためのリンクがユーザーに表示されない

**原因**：
製品プロファイル _Campaign-xxx-Administrators/Admin_ にユーザーとして追加されるまでは、ユーザーにリンクは表示されません。

**対処方法：**
管理者が、管理する各インスタンスの製品プロファイル _Campaign-xxx-Admins_ にユーザーを追加する必要があります。ユーザーがすべてのインスタンスの管理者であっても、自分自身を「ユーザー」として追加する必要があります。

### 症状：インスタンスが [!UICONTROL コントロールパネル]に表示されない

**原因：**
おそらく、表示されないインスタンスの製品プロファイル _Campaign-xxx-Administrators/Admin_ にユーザーを「ユーザー」として追加する必要があります。

**対処方法：**&#x200B;管理者が、管理する各インスタンスの製品プロファイル _Campaign-xxx-Admins_ にユーザーを追加する必要があります。ユーザーがすべてのインスタンスの管理者であっても、自分自身を「ユーザー」として追加する必要があります。

### 役立つビデオ

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=on)

*IMS 組織 ID の確認（26 秒）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=on)

*製品プロファイル「Administrators」に管理者を追加して [!UICONTROL コントロールパネル]を使用できるようにする方法（1 分 3 秒）*

### 参考になるドキュメント

* [コントロールパネルの理解](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja)
* [[!UICONTROL コントロールパネル]に対する権限の管理](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja)

## SFTP サーバーへの接続の確立（クライアントまたは API）

SFTP サーバーに接続するには、以下が必要です。

* SFTP サーバーへの接続元となる IP アドレスを[!UICONTROL 許可リストに登録する]こと
* Adobe Campaign に登録する必要がある秘密キーと公開キーのペア
* SFTP サーバーに直接接続する場合は、SFTP クライアントソフトウェアが必要です

### 参考になるドキュメント {#helpful-docs}

* [SFTP サーバーへのログイン](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja)

