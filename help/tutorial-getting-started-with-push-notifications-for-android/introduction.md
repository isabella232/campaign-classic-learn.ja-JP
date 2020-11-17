---
title: チュートリアルAndroid向けプッシュ通知の使い始めに — はじめに
description: このチュートリアルでは、Adobe Campaign からプッシュ通知を送信し、Android アプリでこれらの通知を受信する手順について説明します。
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 217b0ec1b6f5c5e17009f1103d69726aa57dcaa4
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# チュートリアルAndroid向けプッシュ通知の使い始めに — はじめに

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

このチュートリアルでは、Adobe Campaignからアプリへの [!DNL push] 通知の送信に関する手順を説明し [!DNL Android] ます。

## 前提条件

開始する前に、次の前提条件を満たす必要があります

1) モバイルアプリケーションこのチュートリアルでは、モバイルアプリケーションの設定に必要な詳細手順については説明しません。 統合された **[!DNL Android]モバイルアプリケーションが必要になり[!DNL Campaign SDK]** ます。

   * 必要な手順の詳細については、キャンペーンSDKのモバイルアプリケーションへの [統合を参照してください](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)。

   * Experience PlatformモバイルSDKも使用できます。 詳しくは、Experience PlatformモバイルSDKを使用したプッシュチャネルの [設定のチュートリアルビデオを参照してください](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) 。

2) モバイルアプリチャネルパッケージがインストールされました

   インスタンスにモバイルアプリチャネルパッケージをインストールする必要があります。 次のビデオでは、Mobile Appチャネルがインスタンスにインストールされているかどうかを確認する方法と、インストールしていない場合は方法を説明します。

   [!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## チュートリアル

Neotripモバイルアプリのサブスクリプションを購入したお客様に向けて、パーソナライズされたプロモーションプッシュ通知を送信したいと考えてい [!DNL Android] ます。 Neotripアプリは、キャンペーンSDKを使用して設定され、Mobile Appチャネルがキャンペーンインスタンスでアクティブ化されていることを確認しました。

次の設定手順が必要です。

### 手順1:アプリの購読スキーマを拡張して、プッシュ通知をパーソナライズします。

プッシュ通知をパーソナライズするために、まずアプリ購読スキーマ [を](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) 拡張し、ユーザーがサービスを購読する際にアプリから受け取るパーソナライズ値を格納できるようにします。

### 手順2:Androidサービスを設定し、キャンペーンでモバイルアプリケーションを作成する

次に、Androidサービスを [設定し、キャンペーンでモバイルアプリケーションを作成する必要があります](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)。 この手順では、Neotripアプリをプッシュ通知のターゲットとして定義します。

### 手順3:プッシュ通知の設定と送信

これで、プッシュ通知を [設定して送信する準備が整いました](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)。

## チュートリアルの開始

**[手順1:アプリ購読スキーマの拡張](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
