---
title: 繰り返しメールキャンペーンと連続メールキャンペーンの設定方法
description: 繰り返し配信と連続配信の設定方法およびこれら 2 つのアプローチの違いについて説明します。
feature: ワークフロー
kt: 1560
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: 5fb898eca821c5078393003c41032801f8454fd5
workflow-type: ht
source-wordcount: '268'
ht-degree: 100%

---

# 繰り返しおよび連続 E メールキャンペーンの設定方法

このチュートリアルでは、繰り返し配信と連続配信の設定方法およびこれら 2 つのアプローチの違いについて説明します。

## 繰り返し配信および連続配信のトラッキング {#recurring-and-continuous-delivery-tracking}

繰り返し配信と連続配信は、連絡先データの管理方法が異なります。

* **連続配信**&#x200B;では、既存の配信に新しい受信者を追加できるので、新しい受信者を追加するたびに新しい配信を作成する必要がありません。クリエイティブはキャンペーンワークフローで直接更新でき、配信テンプレートのリソースフォルダー内のテンプレートが更新されます。

   連続配信は、単一の配信と配信ログ（broadLog）を作成し、その配信を参照するトラッキングログは、実行のたびに 1 つ追加されます。

   ![連続配信](/help/assets/delivery_continuous.jpg)

* **繰り返し配信**&#x200B;では、実行のたびに新しい配信インスタンスを作成します。例えば、ワークフローが週に 1 回実行されるようにスケジュールされている場合、1 年後には 52 件の配信が存在することになります。また、broadLog とトラッキングログは、各配信インスタンスで区切られます。

   ![繰り返し配信](/help/assets/delivery_recurring.jpg)

## 繰り返し配信の設定方法 {#how-to-set-up-a-recurring-delivery}

このビデオでは、繰り返し配信とスケジューラーアクティビティを設定する方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## 連続配信の設定方法 {#how-to-set-up-a-continuous-delivery}

このビデオでは、増分処理クエリを使用して連続配信を設定する方法について説明します。

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## その他のリソース

[ターゲティングワークフローでの繰り返し配信の作成](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/use-cases/deliveries/sending-a-birthday-email.html?lang=ja#creating-a-recurring-delivery-in-a-targeting-workflow)
