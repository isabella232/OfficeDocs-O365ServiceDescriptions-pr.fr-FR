---
title: Fonctionnalités d'archivage dans l'archivage Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: Les sections suivantes décrivent les fonctionnalités d’archivage d’archivage Microsoft Exchange Online.
ms.openlocfilehash: 2bffa9fccb2c040fde4edcf8a5c80f3bc109bba2
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035589"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="4f32b-103">Fonctionnalités d'archivage dans l'archivage Exchange Online</span><span class="sxs-lookup"><span data-stu-id="4f32b-103">Archive Features in Exchange Online Archiving</span></span>

<span data-ttu-id="4f32b-104">Les sections suivantes décrivent les fonctionnalités d’archivage d’archivage Microsoft Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4f32b-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="4f32b-105">Boîte aux lettres d'archivage</span><span class="sxs-lookup"><span data-stu-id="4f32b-105">Archive mailbox</span></span>

<span data-ttu-id="4f32b-p101">L'Archivage Exchange Online offre aux utilisateurs des capacités d'archivage avancées avec la fonctionnalité de boîte aux lettres d'archivage. Une boîte aux lettres d'archivage est une boîte aux lettres spécialisée qui apparaît à côté des dossiers de la boîte aux lettres principale des utilisateurs dans Outlook ou Outlook Web App. Les utilisateurs peuvent accéder à l'archive de la même manière qu'ils accèdent à leur boîte aux lettres principale. En outre, ils peuvent effectuer des recherches dans leurs archives et leurs boîtes aux lettres principales.</span><span class="sxs-lookup"><span data-stu-id="4f32b-p101">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature. An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook Web App. Users can access the archive in the same way that they access their primary mailboxes. In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="4f32b-p102">Les administrateurs peuvent utiliser le Centre d'administration Exchange (CAE) ou Windows PowerShell à distance afin d'activer la fonctionnalité d'archivage pour des utilisateurs spécifiques. Pour plus d'informations, reportez-vous à la rubrique [Activer ou désactiver une boîte aux lettres d'archivage dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span><span class="sxs-lookup"><span data-stu-id="4f32b-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="4f32b-p103">L'utilisation de la fonction de journalisation, des règles de transport ou des règles de transfert automatique pour copier des messages dans Archivage Exchange Online à des fins d'archivage n'est pas autorisée. >  La boîte aux lettres d'archivage d'un utilisateur est destinée uniquement à cet utilisateur. Microsoft se réserve le droit de refuser l'archivage illimité dans les cas où la boîte aux lettres d'archivage d'un utilisateur sert à stocker les données d'archivage d'autres utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="4f32b-p103">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted. >  A user's archive mailbox is intended for just that user. Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users.</span></span> 
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="4f32b-115">Déplacer des messages vers l'archivage Exchange Online</span><span class="sxs-lookup"><span data-stu-id="4f32b-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="4f32b-p104">Les utilisateurs peuvent glisser-déplacer des messages à partir de fichiers .pst dans l'archive pour faciliter l'accès en ligne. Ils peuvent également déplacer automatiquement des éléments de messagerie de la boîte aux lettres principale vers la boîte aux lettres d'archivage à l'aide de stratégies d'archivage, de manière à réduire la taille et à améliorer les performances de la boîte aux lettres principale. Si ce comportement est différent de celui d'Exchange Hosted Archive, ce qui entraîne la création d'une copie secondaire de chaque message de l'archive, les conditions requises en matière de conservation peuvent être satisfaites dans les deux cas. Pour plus de détails sur les méthodes supplémentaires de déplacement des messages dans l'archive, reportez-vous à la rubrique [Boîtes aux lettres d'archivage dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).</span><span class="sxs-lookup"><span data-stu-id="4f32b-p104">Users can drag and drop messages from .pst files into the archive, for easy online access. Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox. While this behavior is different than Exchange Hosted Archive, which will create a secondary copy of each message in the archive, retention requirements can be achieved in either scenario. For details on additional methods to move messages into the archive, see [Archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).</span></span>
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="4f32b-120">Importer des données dans l'archive</span><span class="sxs-lookup"><span data-stu-id="4f32b-120">Import data to the archive</span></span>

<span data-ttu-id="4f32b-121">Les utilisateurs peuvent importer des données comme suit :</span><span class="sxs-lookup"><span data-stu-id="4f32b-121">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="4f32b-122">importer des données à partir d'un fichier .pst à l'aide de l'Assistant Importation et exportation d'Outlook ;</span><span class="sxs-lookup"><span data-stu-id="4f32b-122">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="4f32b-123">faire glisser des messages électroniques des fichiers .PST dans l'archive ;</span><span class="sxs-lookup"><span data-stu-id="4f32b-123">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="4f32b-124">faire glisser des messages électroniques de la boîte aux lettres principale dans l'archive ;</span><span class="sxs-lookup"><span data-stu-id="4f32b-124">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="4f32b-p105">laisser les stratégies d'archivage transférer automatiquement des messages électroniques de la boîte aux lettres principale, en fonction de l'ancienneté des messages. Pour plus d'informations, reportez-vous à la rubrique [Balises et stratégies de rétention](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span><span class="sxs-lookup"><span data-stu-id="4f32b-p105">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span></span>
    
> [!NOTE]
> <span data-ttu-id="4f32b-p106">Les administrateurs peuvent également utiliser le service Office 365 pour importer des fichiers .pst dans les boîtes aux lettres d'archivage informatiques des utilisateurs. Pour plus d'informations, reportez-vous à la rubrique [Utiliser le chargement réseau pour importer des fichiers PST vers Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span><span class="sxs-lookup"><span data-stu-id="4f32b-p106">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="4f32b-129">Récupération d'éléments supprimés</span><span class="sxs-lookup"><span data-stu-id="4f32b-129">Deleted item recovery</span></span>

<span data-ttu-id="4f32b-p107">Les utilisateurs peuvent restaurer les éléments qu'ils ont supprimés de tous les dossiers Courrier de leur archive. Quand un élément est supprimé, il est conservé dans le dossier Éléments supprimés de l'archive. Il y reste jusqu'à ce qu'il soit manuellement supprimé par l'utilisateur, ou automatiquement supprimé en raison des stratégies de rétention.</span><span class="sxs-lookup"><span data-stu-id="4f32b-p107">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="4f32b-p108">Une fois un élément supprimé du dossier Éléments supprimés de l'archive, il est conservé dans le dossier Éléments récupérables de l'archive pendant 14 jours supplémentaires avant d'être définitivement supprimé. Les utilisateurs peuvent récupérer ces éléments à l'aide de la fonctionnalité **Récupérer les éléments supprimés** dans Microsoft Outlook ou Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="4f32b-p108">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook Web App.</span></span> 
  
<span data-ttu-id="4f32b-p109">Si un utilisateur a purgé manuellement un élément du dossier des éléments récupérables, un administrateur peut le récupérer au cours d'une période de 14 jours à l'aide de la fonctionnalité appelée Récupération d'élément unique. Cette fonctionnalité permet aux administrateurs d'effectuer une recherche dans plusieurs boîtes aux lettres pour trouver les éléments purgés, puis d'utiliser la cmdlet Windows PowerShell  `Search-Mailbox` pour déplacer les éléments de la boîte aux lettres de découverte vers les boîtes aux lettres des utilisateurs. Pour plus d'informations, reportez-vous à la rubrique [Activation de la récupération d'élément unique pour une boîte aux lettres](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span><span class="sxs-lookup"><span data-stu-id="4f32b-p109">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="4f32b-p110">La période de récupération d'élément unique par défaut est de 14 jours, mais elle peut être personnalisée dans certains cas. >  Si un administrateur a placé la boîte aux lettres d'un utilisateur en conservation inaltérable ou en conservation pour litige, les éléments purgés sont conservés indéfiniment et la période de 14 jours ne s'applique pas.</span><span class="sxs-lookup"><span data-stu-id="4f32b-p110">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances. >  If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="4f32b-140">Récupération de boîtes aux lettres supprimées</span><span class="sxs-lookup"><span data-stu-id="4f32b-140">Deleted mailbox recovery</span></span>

<span data-ttu-id="4f32b-p111">Lorsque les administrateurs suppriment des utilisateurs du serveur Exchange local, les archives de ces derniers sont également supprimées. Si les boîtes aux lettres d'archivage supprimées doivent être récupérées, l'équipe de support technique Office 365 peut effectuer cette récupération. Une archive récupérée contiendra tous les courriers qui y étaient stockés au moment de sa suppression.</span><span class="sxs-lookup"><span data-stu-id="4f32b-p111">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="4f32b-p112">Les administrateurs disposent de 30 jours à partir de la suppression de la boîte aux lettres d'un utilisateur pour demander la récupération de la boîte aux lettres d'archivage. Passé ce délai de 30 jours, la boîte aux lettres d'archivage n'est plus récupérable.</span><span class="sxs-lookup"><span data-stu-id="4f32b-p112">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="4f32b-146">Redondance du service de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="4f32b-146">Mailbox service redundancy</span></span>

<span data-ttu-id="4f32b-p113">Boîtes aux lettres d’archivage dans l’archivage Exchange Online sont répliqués vers plusieurs copies de base de données, dans les centres de données Microsoft géographiquement dispersés, pour fournir des capacités de restauration des données en cas d’échec de l’infrastructure de messagerie. Pour les échecs à grande échelle, gestion de la continuité d’activité est déclenchée.</span><span class="sxs-lookup"><span data-stu-id="4f32b-p113">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure. For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="4f32b-149">Disponibilité des fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="4f32b-149">Feature Availability</span></span>

<span data-ttu-id="4f32b-150">Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service d'archivage Exchange Online](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="4f32b-150">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  
