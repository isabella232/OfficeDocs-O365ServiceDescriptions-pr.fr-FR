---
title: Haute disponibilité et continuité de service
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online offre une prise en charge étendue de la rétention et de la récupération pour l’infrastructure de messagerie d’une organisation. Sont incluses la réplication de boîte aux lettres dans les centres de données et la possibilité de restaurer des boîtes aux lettres et éléments supprimés.
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131968"
---
# <a name="high-availability-and-business-continuity"></a>Haute disponibilité et continuité de service

Microsoft Exchange Online offre une prise en charge étendue de la rétention et de la récupération pour l’infrastructure de messagerie d’une organisation. Sont incluses la réplication de boîte aux lettres dans les centres de données et la possibilité de restaurer des boîtes aux lettres et éléments supprimés.
  
## <a name="mailbox-replication-at-data-centers"></a>Réplication de boîtes aux lettres dans les centres de données

Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.
  
For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Récupération de boîtes aux lettres supprimées

Les administrateurs peuvent supprimer des boîtes aux lettres Exchange Online en utilisant le centre d’administration Microsoft 365 pour supprimer le compte d’utilisateur correspondant ou supprimer la licence Exchange Online ou en utilisant la cmdlet **Remove-Mailbox** dans Windows PowerShell à distance. Lors de la suppression d'une boîte aux lettres, Exchange Online conserve la boîte aux lettres et son contenu pendant 30 jours par défaut. Passé ce délai de 30 jours, la boîte aux lettres n'est plus récupérable. Une boîte aux lettres récupérée contient toutes les données qui y étaient stockées au moment de sa suppression. Les administrateurs peuvent récupérer une boîte aux lettres supprimée pendant la période de rétention à l’aide du centre d’administration Microsoft 365. Pour récupérer une boîte aux lettres supprimée, les administrateurs doivent restaurer le compte d’utilisateur correspondant ou réaffecter une licence Exchange Online au compte d’utilisateur. Pour plus d'informations, consultez la rubrique [Suppression ou restauration de boîtes aux lettres utilisateur dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Récupération d'éléments supprimés

Exchange Online permet aux utilisateurs de restaurer des éléments qu’ils ont supprimés de n’importe quel dossier de messagerie, y compris le dossier éléments supprimés. Quand un élément est supprimé, il est conservé dans le dossier Éléments supprimés de l'utilisateur. Il y reste jusqu'à ce qu'il soit manuellement supprimé par l'utilisateur, ou automatiquement supprimé en raison des stratégies de rétention. Les administrateurs peuvent personnaliser les stratégies de rétention à l'aide du Centre d'administration Exchange ou de l'application Windows PowerShell distante.
  
Une fois qu'un élément a été supprimé du dossier Éléments supprimés, il est conservé dans un dossier Éléments récupérables pendant 14 jours avant d'être supprimé définitivement, mais les administrateurs peuvent étendre cette durée à un maximum de 30 jours en utilisant l'application Windows PowerShell à distance. Les utilisateurs peuvent récupérer l’élément pendant cette période à l’aide de la fonctionnalité récupérer les éléments supprimés dans Outlook sur le Web ou Outlook. Découvrez comment [modifier la période de rétention des éléments supprimés](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  