---
title: サーバ容量の監視
description: Campaign コントロールパネルでは、インスタンスごとに SFTP ストレージを監視および管理し、許可リストに IP アドレスを追加できます。
feature: SFTP Management
topics: Control Panel
audience: administrator
kt: 3266
thumbnail: 27270.jpg
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: 7b2c1ac95dc59ab0c9d8098d76a04af94f273dc8
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 77%

---


# サーバ容量の監視

このCampaign コントロールパネルを使用すると、SFTPストレージをインスタンスごとに監視および管理できます。

## [!UICONTROL Campaign コントロールパネル]のサブドメイン管理へのアクセス

[!UICONTROL Campaign コントロールパネル]のサブドメイン管理にアクセスするには、以下に移動します。

* [Experience Cloudホーム](https://experience.adobe.com/#/home) / [!UICONTROL ソリューション選択]: [!UICONTROL キャンペーン] / **[!UICONTROL Campaign コントロールパネルカード]** / **[!UICONTROL サブドメインと証明書]** （カード）

   または
* URL（[https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)）で直接移動

## サーバー容量の監視、IP アドレスの[!UICONTROL 許可リストへの登録]、SSH キーの追加

このビデオでは、 [!UICONTROL Adobe CampaignCampaign コントロールパネルにアクセスする方法] 、およびSFTPサーバーのストレージを監視できる場所について説明します。

>[!VIDEO](https://video.tv.adobe.com/v/27270?quality=12)

### インターフェイスの説明

**インスタンス**：管理者権限の対象となっているインスタンスのみが表示されます。

**ジョブログ**：[!UICONTROL Campaign コントロールパネル]で実行されたジョブのみが表示されます。[!UICONTROL Campaign コントロールパネル]外で実行されたジョブは含まれません（例えば、実行中のワークフローなど）。

ログには、組織の管理者が実行したジョブのみが含まれます。複数の組織がある場合、他の組織のログはジョブログには表示されません

**「ストレージ」タブ**：ヘッダーには、最もよく使用されているサーバーの上位 3 つが表示されます。4 台以上のサーバーがある場合は、「[!UICONTROL ストレージ]」タブに残りのサーバーが表示されます。

**警告メッセージ**：

* オレンジ - サーバーの使用率が 80％
* 赤 - サーバーの使用率が 90％

## その他のリソース

* [SSH 鍵の生成](./generate-ssh-key.md)
