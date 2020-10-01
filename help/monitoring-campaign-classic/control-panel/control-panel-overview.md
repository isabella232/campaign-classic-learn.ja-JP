---
title: コントロールパネル
seo-title: コントロールパネル
description: Campaign コントロールパネルでは、SFTP ストレージをインスタンス別に監視および管理したり、IP アドレスを許可リストに登録したりできます。
seo-description: Campaign コントロールパネルでは、SFTP ストレージをインスタンス別に監視および管理したり、IP アドレスを許可リストに登録したりできます。
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 98%

---


# [!UICONTROL コントロールパネル]

>[!NOTE]
>
>Adobe Campaign ドキュメントでは、「[!UICONTROL ホワイトリスト]」および「[!UICONTROL ブラックリスト]」という用語が「[!UICONTROL 許可リスト]」および「[!UICONTROL ブロックリスト]」に置き換えられました。
>これらの用語が製品の UI、オプション名、内部コード、チュートリアルビデオに残っている場合がありますが、今後の Campaign コントロールパネルリリースで置き換えられる予定です。

[!UICONTROL Campaign コントロールパネル]を使用すると、Adobe Campaign 管理者は、主要なアセットを監視したり、管理タスク（インスタンス単位の SFTP ストレージの管理や IP アドレスの[!UICONTROL 許可リストへの登録]など）を実行したりできます。

## [!UICONTROL Campaign コントロールパネル]へのアクセス

Campaign コントロールパネルにアクセスするには、Experience Cloud ホーム（[https://experiencecloud.adobe.com](https://experiencecloud.adobe.com)）に移動します。

* **[!UICONTROL Experience Cloud ホーム]**／**[!UICONTROL クイックアクセス]**

   または
* **[!UICONTROL Experience Cloud ホーム]**／[!UICONTROL ソリューション選択]：**Campaign**／**[!UICONTROL Campaign コントロールパネル]カード**

   または

* URL（[https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)）で直接移動

## 前提条件

開始する前に、次の前提条件を満たすようにしてください。

### [!DNL IMS Org ID] の確認

自分の [!DNL IMS org ID] がわかっている必要があります。次のビデオでは、インスタンスの [!DNL IMS org ID] を参照できる場所を説明しています。

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*[!DNL IMS Org ID]の確認（0 分 26 秒）*

### 管理者権限

[!UICONTROL Campaign コントロールパネル]にアクセスするには、管理者権限が必要です。
次のビデオでは、Campaign インスタンスに管理者を追加する方法を説明しています

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*製品プロファイル「[!UICONTROL Administrators]」に管理者を追加して[!UICONTROL Campaign コントロールパネル]を使用できるようにする方法（1 分 3 秒）*

## [!UICONTROL Campaign コントロールパネル]のチュートリアル

* **SFTP サーバーの管理**

   *サーバー容量を監視する方法、IP アドレスを[!UICONTROL 許可リストに登録]する方法、SSH キーを追加する方法を説明します。*

   * [サーバー容量の監視、IP アドレスの許可リストへの登録、SSH キーの追加](/help/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [SSH キーの生成](/help/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [SFTP サーバーへの接続](/help/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[サブドメインのデリゲート](/help/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *サブドメインを[!UICONTROL Adobe Campaign]* に完全にデリゲートする方法を説明します。

* **[SSL 証明書の追加](/help/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Campaign コントロールパネルで SSL 証明書を追加してサブドメインを保護する方法を説明します。*

* **[URL アクセス権限の追加](/help/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *外部の URL を承認済み URL リストに追加して、インスタンスからアクセスできるようにする方法を説明します。*

* **[許可リストへのIPアドレスの追加](/help/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *IP アドレスの範囲を[!UICONTROL 許可リストに登録]して、インスタンスへの新しい接続をセットアップする方法を説明します。*

* **[Google TXT レコード管理](/help/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *[!UICONTROL Campaign コントロールパネル]を使用して、[!DNL GMAIL]アドレス宛ての E メール送信に使用するすべてのサブドメインに[!DNL Google TXT]サイト検証レコードを追加する方法を説明します。*

* **GPG キー管理**

   *アウトバウンドデータを暗号化するために公開鍵と秘密鍵のペアを指定の Campaign インスタンスに生成しインストールする方法と、インバウンドデータを復号化するために公開鍵を Campaign インスタンスにインポートしインストールする方法を説明します。*

   * [データ暗号化用の GPG キーの生成とインストール](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [GPG キーを使用したデータの暗号化](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [データの復号化](./gpg-key-management/decrypting-data.md)

* **[Campaign コントロールパネルのトラブルシューティング](/help/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *[!UICONTROL Campaign コントロールパネル]*&#x200B;のトラブルシューティング方法を説明します。

## その他のリソース

* [Campaign コントロールパネルヘルプセンター](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html)
