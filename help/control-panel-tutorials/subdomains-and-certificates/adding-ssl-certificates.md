---
title: SSL 証明書の追加
description: サブドメインを保護するために SSL 証明書を追加する方法を学びます。
feature: コントロールパネル
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Administrator
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/adding-ssl-certificates.html
exl-id: 9ba485fb-be26-4f3c-a9de-844fecaec20d
source-git-commit: 3757eaf573dab5139bad084b664475c6a7de4b02
workflow-type: ht
source-wordcount: '220'
ht-degree: 100%

---

# SSL 証明書の追加

Adobe [!UICONTROL Campaign コントロールパネル]では、SSL 証明書を追加してサブドメインを保護できます。

## Campaign コントロールパネルのサブドメイン管理へのアクセス

Campaign コントロールパネルのサブドメイン管理にアクセスするには、以下に移動します。

* [Experience Cloud ホーム](https://experience.adobe.com/#/home)／ソリューション選択：**[!DNL Campaign]**／**[!UICONTROL Campaign コントロールパネル]**&#x200B;カード／**[!UICONTROL サブドメインおよび証明書]**&#x200B;カード

   または
* URL（[https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)）で直接移動

## SSL 証明書の追加手順

SSL 証明書の追加には、次の 3 つの手順が必要です。

### 1. 証明書署名要求の生成

SSL 証明書を購入するには、証明書署名要求（CSR）が必要です。保護しようとしているインスタンスとサブドメインごとに生成する必要があります。

次のビデオでは、Campaign コントロールパネルで証明書署名要求を生成する方法を説明しています。

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*証明書署名要求の生成（2 分 36 秒）*

### 2. SSL 証明書の購入

CSR を取得したら、組織の承認を得た認証局から SSL 証明書を購入する必要があります。

### 3. SSL 証明書のインストール

SSL 証明書を取得したら、保護しようとしているサブドメイン用に SSL 証明書をインストールする必要があります。

次のビデオでは、[!UICONTROL Campaign コントロールパネル]で SSL 証明書をインストールする方法を説明しています。

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*SSL 証明書のインストール（1 分 25 秒）*

## その他のリソース

* [完全なサブドメインのデリゲーション（ビデオ）](./subdomain-delegation.md)
* [サブドメインの SSL 証明書の更新（ドキュメント）](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html?lang=ja)