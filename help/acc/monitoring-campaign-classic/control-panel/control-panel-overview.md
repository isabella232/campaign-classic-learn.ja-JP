---
title: コントロールパネル
seo-title: コントロールパネル
description: Campaign コントロールパネルでは、インスタンスごとの SFTP ストレージと許可リストの IP アドレスを監視および管理できます。
seo-description: Campaign コントロールパネルでは、インスタンスごとの SFTP ストレージと許可リストの IP アドレスを監視および管理できます。
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: ca3b7933927914b9965f6f059293041dd1db1da2
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 57%

---


# [!UICONTROL コントロールパネル]

>[!NOTE]
>
>Adobe Campaignドキュメントでは、「[!UICONTROL whitelist]」および「[!UICONTROL blacklist]」という用語が「[!UICONTROL 許可リスト]」および「ブロックリスト」に置き換えられました。
>これらの用語の一部は、製品の UI、オプション名、内部コード、チュートリアルビデオに残っている場合があります。今後の Campaign コントロールパネルリリースで置き換えられる予定です。

The [!UICONTROL Control Panel] allows Adobe Campaign administrators to monitor key assets and perform administrative tasks, such as managing the SFTP storage by instance or [!UICONTROL allow list] IP addresses.

## Accessing [!UICONTROL Control Panel]

Campaign コントロールパネルにアクセスするには、Experience Cloud ホーム（[https://experiencecloud.adobe.com](https://experiencecloud.adobe.com)）に移動します。

* **[!UICONTROL Experience Cloudホーム]** / **[!UICONTROL クイックアクセス]**

   または
* **[!UICONTROL Experience Cloudホーム]** / [!UICONTROL ソリューション選択]: **キャンペーン** / **[!UICONTROL Campaign コントロールパネル]カード&#x200B;**

   または

* URL から直接アクセス：[https://experience.adobe.com/jp/#/controlpanel](https://experience.adobe.com/jp/#/controlpanel)

## 前提条件

開始する前に、次の前提条件を満たしておく必要があります。

### [!DNL IMS Org ID] を確認

自身の [!DNL IMS org ID] を知っておく必要があります。次のビデオでは、インスタンスの [!DNL IMS org ID] の参照場所を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*チェック[!DNL IMS Org ID]（00:26 分）*

### 管理者権限

Administrator rights are required to access to the [!UICONTROL Control Panel].
次のビデオでは、Campaign インスタンスに管理者を追加する方法を説明します

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*製品プロファイル「[!UICONTROL Administrators]」に管理者を追加してCampaign コントロールパネルを使用できるようにする方法（01:03分）*

## [!UICONTROL Campaign コントロールパネル] のチュートリアル

* **SFTPサーバーの管理**

   *サーバーの容量、[!UICONTROL 許可リスト]IPアドレスを監視し、SSHキーを追加する方法を学びます。*

   * [サーバー容量の監視、許可リストへの IP アドレスの追加、SSH 鍵の追加](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [SSH 鍵の生成](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [SFTP サーバーへの接続](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[サブドメインのデリゲート](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *[!UICONTROL サブドメインを Adobe Campaign に完全にデリゲートする方法を説明します。]*

* **[SSL 証明書の追加](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Campaign コントロールパネルを使用してサブドメインを保護するために、SSL証明書を追加する方法について説明します。*

* **[URL権限の追加](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *認証済みURLのリストに一部の外部URLを追加して、それらのURLにインスタンスを接続する方法。*

* **[インスタンスアクセスの IP 許可リストへの登録](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *IPアドレスの範囲のリストを[!UICONTROL 許可して、インスタンスへの新しい接続を設定する方法を説明します]。*

* **[Google TXT レコード管理](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *[!DNL Google TXT]キャンペーンCampaign コントロールパネルを介してアドレスに電子メールを送信するために使用するすべてのサブドメインに、[!DNL GMAIL]サイト検証レコードを追加する方法を説明します。*

* **GPG キー管理**

   *送信データの暗号化用に、特定の Campaign インスタンスに公開／秘密鍵のペアを生成してインストールする方法、および受信データの復号化用に、Campaign インスタンスに公開鍵を読み込んでインストールする方法を説明します。*

   * [データ暗号化用の GPG キーの生成とインストール](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [GPG キーを使用したデータの暗号化](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [データの復号化](./gpg-key-management/decrypting-data.md)

* **[コントロールパネルのトラブルシューティング](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *[!UICONTROL Campaign コントロールパネルのトラブルシューティング方法を説明します。]*

## その他のリソース

* [Campaign コントロールパネルのヘルプセンター](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html)
