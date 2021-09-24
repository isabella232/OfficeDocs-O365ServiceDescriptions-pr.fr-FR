---
title: Haute disponibilité et continuité de service
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online offre une prise en charge complète de la rétention et de la récupération pour l’infrastructure de messagerie d’une organisation. Sont incluses la réplication de boîte aux lettres dans les centres de données et la possibilité de restaurer des boîtes aux lettres et éléments supprimés.
ms.openlocfilehash: f856c0bce99fc119ad1498daaf355541d40aac86
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671985"
---
# <a name="high-availability-and-business-continuity"></a>Haute disponibilité et continuité de service

Microsoft Exchange Online offre une prise en charge complète de la rétention et de la récupération pour l’infrastructure de messagerie d’une organisation. Sont incluses la réplication de boîte aux lettres dans les centres de données et la possibilité de restaurer des boîtes aux lettres et éléments supprimés.
  
## <a name="mailbox-replication-at-data-centers"></a>Réplication de boîtes aux lettres dans les centres de données

Les boîtes aux lettres Exchange Online sont continuellement répliquées vers plusieurs copies de bases de données, dans des centres de données Microsoft éparpillés géographiquement, afin de fournir la possibilité de restaurer des données dans l'éventualité d'une défaillance d'infrastructure de messagerie locale. Pour les défaillances de grande envergure, des procédures de gestion de continuité de service sont lancées.
  
Pour plus d'informations sur la manière dont Microsoft protège vos données, consultez la rubrique [Centre de gestion de la confidentialité d'Office 365](https://go.microsoft.com/fwlink/p/?LinkId=299135). Si vous utilisez Office 365 géré par 21Vianet, accédez au [centre de gestion de la confidentialité 21Vianet](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Récupération de boîtes aux lettres supprimées

Les administrateurs peuvent supprimer des boîtes aux lettres Exchange Online à l’aide du Centre d'administration Microsoft 365 pour supprimer le compte d’utilisateur correspondant ou la licence Exchange Online, ou à l’aide de la cmdlet **Remove-Mailbox** dans les Windows PowerShell distants. Lors de la suppression d'une boîte aux lettres, Exchange Online conserve la boîte aux lettres et son contenu pendant 30 jours par défaut. Passé ce délai de 30 jours, la boîte aux lettres n'est plus récupérable. Une boîte aux lettres récupérée contient toutes les données qui y étaient stockées au moment de sa suppression. Les administrateurs peuvent récupérer une boîte aux lettres supprimée au cours de la période de rétention à l’aide du Centre d'administration Microsoft 365. Pour récupérer une boîte aux lettres supprimée, les administrateurs doivent restaurer le compte d’utilisateur correspondant ou réaffecter une licence Exchange Online au compte d’utilisateur. Pour plus d'informations, consultez la rubrique [Suppression ou restauration de boîtes aux lettres utilisateur dans Exchange Online](/exchange/recipients-in-exchange-online/delete-or-restore-mailboxes).
  
## <a name="deleted-item-recovery"></a>Récupération d'éléments supprimés

Exchange Online permet aux utilisateurs de restaurer les éléments qu’ils ont supprimés de n’importe quel dossier de messagerie, y compris le dossier Éléments supprimés. Quand un élément est supprimé, il est conservé dans le dossier Éléments supprimés de l'utilisateur. Il y reste jusqu'à ce qu'il soit manuellement supprimé par l'utilisateur, ou automatiquement supprimé en raison des stratégies de rétention. Les administrateurs peuvent personnaliser les stratégies de rétention à l'aide du Centre d'administration Exchange ou de l'application Windows PowerShell distante.
  
Une fois qu'un élément a été supprimé du dossier Éléments supprimés, il est conservé dans un dossier Éléments récupérables pendant 14 jours avant d'être supprimé définitivement, mais les administrateurs peuvent étendre cette durée à un maximum de 30 jours en utilisant l'application Windows PowerShell à distance. Les utilisateurs peuvent récupérer l’élément pendant cette période à l’aide de la fonctionnalité Récupérer les éléments supprimés dans Outlook sur le web ou Outlook. Découvrez comment [modifier la période de rétention des éléments supprimés](/exchange/recipients-in-exchange-online/manage-user-mailboxes/change-deleted-item-retention).
  
Si un utilisateur a manuellement supprimé un élément du dossier Éléments récupérables, un administrateur peut le récupérer pendant la même période à l'aide de la fonctionnalité de récupération d'un élément unique et de l'application Windows PowerShell distante. Par défaut, la récupération d'élément unique est activée lors de la création d'une boîte aux lettres. Pour plus d'informations, voir [Activation ou désactivation de la récupération d'élément unique pour une boîte aux lettres](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-single-item-recovery).
  
Pour conserver les messages au-delà de 30 jours dans le dossier Éléments récupérables, les organisations peuvent implémenter une période de conservation du courrier électronique plus longue ou des blocages locaux avec un facteur temps. Pour en savoir plus, consultez la page [Placement d'une boîte aux lettres en blocage sur place (In-Place Hold)](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir [Exchange Online description du service.](exchange-online-service-description.md)
