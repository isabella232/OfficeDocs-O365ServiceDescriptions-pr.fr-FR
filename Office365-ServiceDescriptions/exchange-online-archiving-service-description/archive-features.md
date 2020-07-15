---
title: Fonctionnalités d’archivage dans l’archivage Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: Les sections suivantes décrivent les fonctionnalités d’archivage de Microsoft Exchange Online Archiving.
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131528"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Fonctionnalités d’archivage dans l’archivage Exchange Online

Les sections suivantes décrivent les fonctionnalités d’archivage de Microsoft Exchange Online Archiving.
  
## <a name="archive-mailbox"></a>Boîte aux lettres d'archivage

L'Archivage Exchange Online offre aux utilisateurs des capacités d'archivage avancées avec la fonctionnalité de boîte aux lettres d'archivage. Une boîte aux lettres d’archivage est une boîte aux lettres spécialisée qui apparaît à côté des dossiers de la boîte aux lettres principale des utilisateurs dans Outlook ou Outlook sur le Web. Les utilisateurs peuvent accéder à l'archive de la même manière qu'ils accèdent à leur boîte aux lettres principale. En outre, ils peuvent effectuer des recherches dans leurs archives et leurs boîtes aux lettres principales.
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  L'utilisation de la fonction de journalisation, des règles de transport ou des règles de transfert automatique pour copier des messages dans Archivage Exchange Online à des fins d'archivage n'est pas autorisée. <br/>
>  La boîte aux lettres d'archivage d'un utilisateur est destinée uniquement à cet utilisateur. Microsoft se réserve le droit de refuser l’archivage illimité dans les cas où la boîte aux lettres d’archivage d’un utilisateur est utilisée pour stocker des données d’archivage pour d’autres utilisateurs ou dans d’autres cas d’utilisation inappropriée.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Déplacer des messages vers l’archivage Exchange Online

Les utilisateurs peuvent glisser-déplacer des messages à partir de fichiers .pst dans l’archive pour faciliter l’accès en ligne. Ils peuvent également déplacer automatiquement des éléments de messagerie de la boîte aux lettres principale vers la boîte aux lettres d'archivage à l'aide de stratégies d'archivage, de manière à réduire la taille et à améliorer les performances de la boîte aux lettres principale. 
  
### <a name="import-data-to-the-archive"></a>Importer des données dans l’archive

Les utilisateurs peuvent importer des données comme suit :
  
- importer des données à partir d'un fichier .pst à l'aide de l'Assistant Importation et exportation d'Outlook ;
    
- faire glisser des messages électroniques des fichiers .PST dans l'archive ;
    
- faire glisser des messages électroniques de la boîte aux lettres principale dans l'archive ;
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Récupération d'éléments supprimés

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
Une fois un élément supprimé du dossier Éléments supprimés de l'archive, il est conservé dans le dossier Éléments récupérables de l'archive pendant 14 jours supplémentaires avant d'être définitivement supprimé. Les utilisateurs peuvent récupérer ces éléments à l’aide de la fonctionnalité **récupérer les éléments supprimés** dans Microsoft Outlook ou Outlook sur le Web. 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  La période de récupération d'élément unique par défaut est de 14 jours, mais elle peut être personnalisée dans certains cas. <br/>
>  Si un administrateur a placé la boîte aux lettres d’un utilisateur en conservation inaltérable ou en conservation pour litige, les éléments purgés sont conservés indéfiniment et la fenêtre de 14 jours ne s’applique pas. 
  
## <a name="deleted-mailbox-recovery"></a>Récupération de boîtes aux lettres supprimées

Lorsque les administrateurs suppriment des utilisateurs du serveur Exchange local, les archives de ces derniers sont également supprimées. Si les boîtes aux lettres d’archivage supprimées doivent être récupérées, l’équipe du support technique Microsoft peut effectuer cette récupération. Une archive récupérée contiendra tous les courriers qui y étaient stockés au moment de sa suppression.
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>Redondance du service de boîte aux lettres

Les boîtes aux lettres d'archivage dans Archivage Exchange Online sont répliquées vers plusieurs copies de bases de données, dans des centres de données Microsoft éparpillés géographiquement, afin de fournir la possibilité de restaurer des données dans l'éventualité d'une défaillance d'infrastructure de messagerie. Pour les défaillances de grande envergure, la gestion de continuité d'activité est lancée. 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, voir [Description du service d’archivage Exchange Online](exchange-online-archiving-service-description.md).
  
