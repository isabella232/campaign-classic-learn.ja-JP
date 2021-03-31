---
title: Campaign コントロールパネルのトラブルシューティング
description: Campaign コントロールパネルでは、SFTP ストレージをインスタンス別に監視および管理したり、IP アドレスを許可リストに登録したりできます。
feature: コントロールパネル
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
role: 管理者
level: 経験豊富な
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
translation-type: ht
source-git-commit: 8847c322c63adb23ea33679714336d0aaac20100
workflow-type: ht
source-wordcount: '355'
ht-degree: 100%

---


# [!UICONTROL Campaign コントロールパネル]のトラブルシューティング

## ログインとホームページ

### 症状：Experience Cloud にログインできない

**対処方法**：
ユーザーが、自分の IMS 組織 ID（xxx）を特定する必要があります。管理者が、管理する各インスタンスの製品プロファイル「Campaign-xxx-Admins」にユーザーを追加する必要があります。ユーザーがすべてのインスタンスの管理者であっても、場合によっては、自分自身をユーザーとして追加する必要があります。

### 症状：Experience Cloud ホームで、[!UICONTROL Campaign コントロールパネル]にアクセスするためのリンクがユーザーに表示されない

**原因**：
製品プロファイル _Campaign-xxx-Administrators/Admin_ にユーザーとして追加されるまでは、ユーザーにリンクは表示されません。

**対処方法**：
管理者が、管理する各インスタンスの製品プロファイル _Campaign-xxx-Admins_ にユーザーを追加する必要があります。ユーザーがすべてのインスタンスの管理者であっても、場合によっては、自分自身を「ユーザー」として追加する必要があります。

### 症状：インスタンスが [!UICONTROL Campaign コントロールパネル]に表示されない

**原因**：
ほとんどの場合、表示されないインスタンスの製品プロファイル _Campaign-xxx-Administrators/Admin_ にユーザーを「ユーザー」として追加する必要があります。

**対処方法**：
管理者が、管理する各インスタンスの製品プロファイル _Campaign-xxx-Admins_ にユーザーを追加する必要があります。ユーザーがすべてのインスタンスの管理者であっても、場合によっては、自分自身を「ユーザー」として追加する必要があります。

### 参考になるビデオ

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS 組織 ID の確認（26 秒）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*製品プロファイル「Administrators」に管理者を追加して [!UICONTROL Campaign コントロールパネル]を使用できるようにする方法（1 分 3 秒）*

### 参考になるドキュメント

* [コントロールパネルの理解](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html)
* [[!UICONTROL Campaign コントロールパネル]に対する権限の管理](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html)

## SFTP サーバーへの接続の確立（クライアントまたは API）

SFTP サーバーに接続するには、以下が必要です。

* SFTP サーバーへの接続元となる IP アドレスを[!UICONTROL 許可リストに登録する]こと
* Adobe Campaign に登録する必要がある秘密鍵と公開鍵のペア
* SFTP サーバーに直接接続する場合は、SFTP クライアントソフトウェアも必要

### 参考になるドキュメント{#helpful-docs}

* [SFTP サーバーへのログイン](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html#LoggingintoyourSFTPserver)

