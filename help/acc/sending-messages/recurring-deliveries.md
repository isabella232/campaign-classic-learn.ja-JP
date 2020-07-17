---
title: 定期的な電子メールキャンペーンと継続的な電子メールメッセージの設定方法
description: このチュートリアルでは、定期的な配信と継続的なアプローチを設定する方法、およびAdobe Campaignクラシック(ACC)の2つのアプローチの違いについて説明します。
feature: workflows
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: d1799d978a9a29f69d637178439fe770ffd4b281
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 3%

---


# 定期的な電子メールキャンペーンと継続的な電子メールメッセージの設定方法

このチュートリアルでは、定期的な配信と継続的なアプローチの設定方法、および2つのアプローチの違いについて説明します。

## 定期的および継続的な配信追跡 {#recurring-and-continuous-delivery-tracking}

定期的なデータと継続的な配信は、連絡先データの管理方法に異なります。

* **** 連続配信を使用すると、既存の配信に新しい受信者を追加でき、新しい受信者を追加するたびに新しい配信を作成する必要がなくなります。 クリエイティブはキャンペーンワークフローで直接更新でき、配信テンプレートリソースフォルダー内のテンプレートが更新されます。

   連続した配信は、SINGLE配信と配信ログ(broadLog)を作成し、その配信を参照するトラッキングログは、実行のたびに1つ追加されます。

![連続配信](/help/acc/assets/delivery_continuous.jpg)

* **定期的な配信** は、実行のたびに新しい配信インスタンスを作成します。 例えば、ワークフローが週に1回実行されるようにスケジュールされている場合、1年後に52配信になります。 また、部分的なログとトラッキングログは、各配信インスタンスで区切られます。

![反復配信](/help/acc/assets/delivery_recurring.jpg)

## 定期配信の設定方法 {#how-to-set-up-a-recurring-delivery}

このビデオでは、定期的な配信とスケジューラーアクティビティを設定する方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## 連続配信の設定方法 {#how-to-set-up-a-continuous-delivery}

このビデオでは、増分クエリを使用して連続配信を設定する方法を示します。

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## その他のリソース

[ターゲティングワークフローでの繰り返し配信の作成](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)