---
title: コントロールパネル
seo-title: コントロールパネル
description: このCampaign コントロールパネルでは、インスタンスと許可リストのIPアドレス別に、SFTPストレージを監視および管理できます。
seo-description: このCampaign コントロールパネルでは、インスタンスと許可リストのIPアドレス別に、SFTPストレージを監視および管理できます。
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '485'
ht-degree: 7%

---


# [!UICONTROL コントロールパネル]

>[!NOTE]
>
>Adobe Campaignドキュメントでは、「[!UICONTROL whitelist]」および「[!UICONTROL blacklist]」という用語が「[!UICONTROL 許可リスト]」および「ブロックリスト」に置き換えられました。
>これらの用語の一部は、製品のUI、オプション名、内部コード、チュートリアルビデオに残っている場合があります。 今後のCampaign コントロールパネルリリースで置き換えられる予定です。

この [!UICONTROL Campaign コントロールパネルを使用すると、Adobe Campaign管理者は、主要なアセットを監視し、インスタンス別や] 許可リスト  IPアドレス別のSFTPストレージ管理などの管理タスクを実行できます。

## Accessing [!UICONTROL Control Panel]

Campaign コントロールパネルにアクセスするには、Experience Cloudホームに移動します。 [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloudホーム]** / **[!UICONTROL クイックアクセス]**

   または
* **[!UICONTROL Experience Cloudホーム]** / [!UICONTROL ソリューション選択]: **キャンペーン** / **[!UICONTROL Campaign コントロールパネル]カード&#x200B;**

   または

* URLから直接： [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## 前提条件

開始する前に、次の前提条件を満たします。

### 確認 [!DNL IMS Org ID]

君のことを知る必要がある [!DNL IMS org ID]。 次のビデオでは、インスタンスの参照場所を説明し [!DNL IMS org ID]ます。

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*チェック[!DNL IMS Org ID]（00:26分）*

### 管理者権限

管理者権限は、 [!UICONTROL Campaign コントロールパネルへのアクセスに必要です]。
次のビデオでは、キャンペーンインスタンスに管理者を追加する方法を説明します

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*製品プロファイル「[!UICONTROL Administrators]」に管理者を追加してCampaign コントロールパネルを使用できるようにする方法（01:03分）*

## [!UICONTROL Campaign コントロールパネル] のチュートリアル

* **SFTPサーバーの管理**

   *サーバーの容量、[!UICONTROL 許可リスト]IPアドレスを監視し、SSHキーを追加する方法を学びます。*

   * [サーバの容量の監視、IPアドレスの一覧表示、SSHキーの追加を許可](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [SSHキーの生成](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [SFTPサーバーへの接続](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[サブドメインの委任](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *サブドメインを[!UICONTROL Adobe Campaignに完全に委任する方法を学びます。]*

* **[SSL証明書の追加](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Campaign コントロールパネルを使用してサブドメインを保護するために、SSL証明書を追加する方法について説明します。*

* **[SSL 証明書の管理](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *サブドメインのSSL証明書のステータスを表示し、更新を要求する方法について説明します。*

* **[URL権限の追加](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *認証済みURLのリストに一部の外部URLを追加して、それらのURLにインスタンスを接続する方法。*

* **[インスタンスアクセスの IP 許可リストへの登録](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *IPアドレスの範囲のリストを[!UICONTROL 許可して、インスタンスへの新しい接続を設定する方法を説明します]。*

* **[Google TXT レコード管理](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *[!DNL Google TXT]キャンペーンCampaign コントロールパネルを介してアドレスに電子メールを送信するために使用するすべてのサブドメインに、[!DNL GMAIL]サイト検証レコードを追加する方法を説明します。*

* **GPGキー管理**

   *送信データの暗号化用に指定したキャンペーンインスタンスに公開鍵と秘密鍵のペアを生成してインストールする方法、および受信データの復号化用にキャンペーンインスタンスに公開鍵を読み込んでインストールする方法を説明します。*

   * [データ暗号化用のGPGキーの生成とインストール](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [GPGキーを使用したデータの暗号化](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [データの復号化](./gpg-key-management/decrypting-data.md)

* **[コントロールパネルのトラブルシューティング](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *[!UICONTROL Campaign コントロールパネルのトラブルシューティング方法を理解する&#x200B;]*

## その他のリソース

* [Campaign コントロールパネルヘルプセンター](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html)
