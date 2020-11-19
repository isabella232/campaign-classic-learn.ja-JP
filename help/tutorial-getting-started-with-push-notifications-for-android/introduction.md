---
title: Android向けプッシュ通知の概要 — はじめに
description: このチュートリアルでは、Adobe Campaign からプッシュ通知を送信し、Android アプリでこれらの通知を受信する手順について説明します。
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 016f47e131df9c3a25b9131da372efaedf6cd5ad
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 11%

---


# Android向けプッシュ通知の概要 — はじめに

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. このチュートリアルでは、Adobe Campaignからアプリへの [!DNL push] 通知の送信に関する手順を説明し [!DNL Android] ます。

## 前提条件

開始する前に、次の情報が必要です。

1) **Androidモバイルアプリケーション**

   このチュートリアルでは、モバイルアプリケーションの設定に必要な詳細手順については説明しません。 統合された **[!DNL Android]モバイルアプリケーションが必要になり [!DNL Campaign SDK] ます**。

   必要な手順の詳細については、製品ドキュメントを参照してください。

   [Campaign SDK をモバイルアプリケーションに統合する](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   Experience PlatformモバイルSDKも使用できます。 詳しくは、チュートリアルビデオを参照してください。

   [Experience Platform モバイル SDK を使用したプッシュチャネルの設定](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]パッケージがインストールされた**

   パッケージをインス [!DNL Mobile App channel] トールする必要があり [!DNL Campaign] ます。 次のビデオでは、がインスタンスにインストールされているかどうかを確認する方法 [!DNL Mobile App channel] と、インストールされていない場合はその方法について説明します。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## チュートリアルの概要

個人向けのプロモーション [!DNL push] 通知を [!DNL Neotrip][!DNL Android] モバイルアプリの購読者に送信したいと考えています。 アプリ [!DNL Neotrip] はを使用して設定さ [!DNL Campaign SDK] れ、インスタンスでアクティベートさ [!DNL Mobile App channel][!DNL Campaign] れていることを確認しました。

次の設定手順が必要です。

### 手順1:アプリの購読スキーマを拡張して、 [!DNL push] 通知をパーソナライズします。

通知をパーソナライズしたいので、まずアプリ購読スキーマ [!DNL push] を [拡張し](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) 、ユーザーがサービスをサブスクライブしたときにアプリから受け取るパーソナライズ値を格納できるようにします。

### 手順2:Androidサービスを設定し、キャンペーンでモバイルアプリケーションを作成する

次に、Androidサービスを [設定し、キャンペーンでモバイルアプリケーションを作成する必要があります](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)。 この手順では、 [!DNL Neotrip] アプリをプッシュ通知のターゲットとして定義します。

### 手順3:プッシュ通知の設定と送信

これで、プッシュ通知を [設定して送信する準備が整いました](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)。

## チュートリアルの開始

手順1: [アプリ購読スキーマの拡張](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
