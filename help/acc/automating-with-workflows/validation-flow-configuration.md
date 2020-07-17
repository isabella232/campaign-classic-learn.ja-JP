---
title: Adobe Campaignクラシックでの検証ワークフローの設定方法
seo-title: Adobe Campaignクラシックでの検証ワークフローの設定方法
description: Adobe Campaignオファーでは、マーケターが配信コンテンツ、キャンペーンターゲット、データ抽出および予算の承認を確認および提供するためのオプションがいくつか用意されています。 このチュートリアルでは、様々な承認検証ワークフローを設定する方法について説明します。
seo-description: このビデオでは、マーケティング担当者が配信コンテンツ、キャンペーンターゲット、データ抽出、予算の承認を確認して提供するための、ACCAdobeキャンペーンオファーの配信テンプレートの設定および使用方法を説明します。 このチュートリアルでは、様々な承認検証ワークフローを設定する方法について説明します。
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Adobe Campaignクラシックでの検証ワークフローの設定方法

Adobe Campaignオファーでは、マーケターが配信コンテンツ、キャンペーンターゲット、データ抽出および予算の承認を確認および提供するためのオプションがいくつか用意されています。

このチュートリアルでは、様々な承認検証ワークフローを設定する方法について説明します。

## 前提条件 {#prerequisite}

承認手順を有効にする前に、マーケティングチームは個々のレビュー担当者を定義する必要があります。

* 承認アクティビティ内のAdobe Campaignレビュー担当者の役割は、1人のレビュー担当者（演算子）または1人のレビュー担当者のグループ（演算子の役割）です。
* レビュー担当者とレビュー担当者グループは、事前に管理者の役割によるAdobe Campaignで設定されている必要があります。 これにより、キャンペーン開発者は、キャンペーンまたは配信で承認者としてレビュアーを選択できます。

## キャンペーンの承認の設定  {#configuring-approvals-for-campaigns}

キャンペーンワークフローのすべての配信に対して同じレビュー担当者のセットがある場合は、 [!DNL Campaign] 承認機能を利用します。 承認レベルで承認とレビュー担当者を設定すると、キャンペーンの実行後に、承認タスクとレビュー担当者がワークフローの各配信アクティビティに移動します。

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## 配信の承認の設定  {#configuring-approvals-for-deliveries}

配信レベルで承認を設定することもできます。 配信の承認手順とレビュー担当者がキャンペーンの承認手順とレビュー担当者と異なる場合、配信の設定がキャンペーンの設定に優先します。

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## 承認アクティビティの設定  {#configuring-an-approval-activity}

配信やキャンペーンの承認とは異なり、承認アクティビティでは、ワークフロー内での承認プロセスの作成が可能です。 これにより、配信を起動する前に、ターゲット設定の選択ロジックを承認できます。 また、必要に応じて、ワークフロー内の複数のレベルで承認を行うこともできます。

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

For more information, refer to the [Approval Documentation](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
