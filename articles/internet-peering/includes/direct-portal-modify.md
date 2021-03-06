---
title: インクルード ファイル
titleSuffix: Azure
description: インクルード ファイル
services: internet-peering
author: prmitiki
ms.service: internet-peering
ms.topic: include
ms.date: 11/27/2019
ms.author: prmitiki
ms.openlocfilehash: 3894bf046ed4ee3f068e43dbc5bc5b7f2a1002b4
ms.sourcegitcommit: 849bb1729b89d075eed579aa36395bf4d29f3bd9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "81681052"
---
このセクションでは、Direct ピアリングで次の変更操作を実行する方法について説明します。

### <a name="add-direct-peering-connections"></a>Direct ピアリング接続を追加する
1. **[+ Add connections]\(+ 接続の追加\)** ボタンを選択し、新しいピアリング接続を構成します。
    > [!div class="mx-imgBorder"]
    > ![ピアリング リソース ビュー](../media/setup-direct-modify-addconnection.png)

1. **[Direct peering Connection]\(Direct ピアリング接続\)** フォームに入力して、 **[保存]** を選択します。 ピアリング接続の構成のヘルプについては、「Direct ピアリングを作成およびプロビジョニングする」セクションの手順を確認してください。
    > [!div class="mx-imgBorder"]
    > ![[Direct Peering Connection]\(Direct ピアリング接続\) フォーム](../media/setup-direct-modify-savenewconnection.png)

### <a name="remove-direct-peering-connections"></a>Direct ピアリング接続を削除する

接続の削除は、現在 Azure portal ではサポートされていません。 詳細については、[Microsoft ピアリング](mailto:peeringexperience@microsoft.com)にお問い合わせください。

### <a name="upgrade-or-downgrade-bandwidth-on-active-connections"></a>アクティブな接続で帯域幅をアップグレードまたはダウングレードする
1. 変更するピアリング接続を選択して、 **[...]**  >  **[接続の編集]** を選択します。
    > [!div class="mx-imgBorder"]
    > ![接続の編集](../media/setup-direct-modify-editconnection.png)

1. スライダーを移動して帯域幅を変更し、 **[保存]** を選択します。
    > [!div class="mx-imgBorder"]
    > ![帯域幅の変更](../media/setup-direct-modify-editconnectionsettings.png)

### <a name="add-ipv4-or-ipv6-session-information-on-active-connections"></a>アクティブな接続で IPv4 または IPv6 セッションの情報を追加する
1. 変更するピアリング接続を選択して、手順 1 のように **[...]**  >  **[接続の編集]** を選択します。
1. **セッション IPv4 プレフィックス**または**セッション IPv6 プレフィックス**の情報を入力し、 **[保存]** を選択します。

### <a name="remove-ipv4-or-ipv6-session-information-on-active-connections"></a>アクティブな接続で IPv4 または IPv6 セッションの情報を削除する
**セッション IPv4 プレフィックス**または**セッション IPv6 プレフィックス**の情報を削除することは、現在ポータルではサポートされていません。 詳細については、[Microsoft ピアリング](mailto:peeringexperience@microsoft.com)にお問い合わせください。
