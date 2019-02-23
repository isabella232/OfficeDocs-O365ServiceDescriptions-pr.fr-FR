---
title: Gestion des destinataires, des domaines et des entreprises
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) offre plusieurs moyens de gérer les informations concernant les destinataires, les domaines et les entreprises. En tant qu'administrateur, vous pouvez effectuer certaines tâches de gestion dans le centre d'administration Exchange et vérifier les autres tâches de gestion effectuées dans le centre d'administration 365 de Microsoft.
ms.openlocfilehash: fcae2c3ad93b977fb197089e2c8809b74ada7bd7
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210327"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="410e7-104">Gestion des destinataires, des domaines et des entreprises</span><span class="sxs-lookup"><span data-stu-id="410e7-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="410e7-p102">Microsoft Exchange Online Protection (EOP) offre plusieurs moyens de gérer les informations concernant les destinataires, les domaines et les entreprises. En tant qu'administrateur, vous pouvez effectuer certaines tâches de gestion dans le centre d'administration Exchange et vérifier les autres tâches de gestion effectuées dans le centre d'administration 365 de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="410e7-p102">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information. As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="410e7-p103">Vous recherchez des informations sur toutes les fonctionnalités EOP ? Consultez la rubrique [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="410e7-p103">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="410e7-109">Destinataires de messages</span><span class="sxs-lookup"><span data-stu-id="410e7-109">Mail recipients</span></span>
<span data-ttu-id="410e7-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="410e7-110"></span></span>

<span data-ttu-id="410e7-p104">Les destinataires de messagerie sont catégorisés comme utilisateurs ou groupes de messagerie et peuvent être gérés via la synchronisation d'annuaires, directement dans le centre d'administration Exchange ou via Windows PowerShell à distance. Si vous gérez vos destinataires en local, vous devez exécuter la synchronisation d'annuaires pour que vos destinataires de messages soient reflétés dans le centre d'administration Exchange. Les utilisateurs gérés uniquement dans le centre d'administration 365 de Microsoft ne sont pas affichables dans le centre d'administration Exchange, mais ils peuvent être ajoutés ou supprimés de l'appartenance à un groupe de rôles d'administrateur dans le centre d'administration Exchange. Pour plus d'informations sur les destinataires dans EOP, consultez la rubrique [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="410e7-p104">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell. If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC. Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC. For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="410e7-115">Autorisations de groupe de rôles d'administrateur</span><span class="sxs-lookup"><span data-stu-id="410e7-115">Admin role group permissions</span></span>
<span data-ttu-id="410e7-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="410e7-116"></span></span>

<span data-ttu-id="410e7-p105">Dans EOP, vous pouvez configurer uniquement des rôles d'administrateur. Le Centre d'administration Exchange vous permet d'ajouter directement des utilisateurs à des groupes de rôles d'administrateur par défaut ou d'en supprimer. Aucune personnalisation RBAC n'est disponible. Pour plus d'informations, consultez la rubrique [Gérer les autorisations de groupe de rôles d'administrateur dans EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="410e7-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="410e7-121">Gestion de domaines</span><span class="sxs-lookup"><span data-stu-id="410e7-121">Domain management</span></span>
<span data-ttu-id="410e7-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="410e7-122"></span></span>

<span data-ttu-id="410e7-p106">Les domaines gérés sont des domaines protégés par EOP. Les domaines gérés peuvent être affichés et les types de domaine peuvent être modifiés dans le centre d'administration Exchange. La mise en service et la gestion de domaine se produisent dans le centre d'administration 365 de Microsoft et les modifications sont reflétées dans le centre d'administration Exchange. Pour plus d'informations, consultez la rubrique [afficher ou modifier des domaines gérés dans EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="410e7-p106">Managed domains are domains that are protected by EOP. Managed domains can be viewed and domain types can be edited in the EAC. Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC. For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="410e7-127">Mise en correspondance des sous-domaines</span><span class="sxs-lookup"><span data-stu-id="410e7-127">Match subdomains</span></span>
<span data-ttu-id="410e7-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="410e7-128"></span></span>

<span data-ttu-id="410e7-p107">Dans EOP, vous pouvez activer le flux de messagerie pour les sous-domaines d'un domaine géré. Pour plus d'informations, consultez la rubrique [Activer le flux de messagerie pour les sous-domaines dans EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="410e7-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="410e7-131">Blocage du périmètre basé sur l'annuaire (DBEB)</span><span class="sxs-lookup"><span data-stu-id="410e7-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="410e7-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="410e7-132"></span></span>

<span data-ttu-id="410e7-p108">La fonctionnalité de blocage du périmètre basé sur l'annuaire vous permet de rejeter les messages pour les destinataires non valides sur le périmètre du réseau de service. La fonctionnalité de blocage du périmètre basé sur l'annuaire (DBEB) permet aux administrateurs d'ajouter des destinataires à extension messagerie à Office 365 et de bloquer tous les messages envoyés à des adresses de messagerie qui ne sont pas présentes dans Office 365. Si un message est envoyé à une adresse de messagerie valide présente dans Office 365, celui-ci continue à travers le reste des couches de filtrage de services (anti-programme malveillant, anti-courrier indésirable, règles de transport). Si l'adresse n'est pas présente, le service bloque le message avant même le filtrage, et une notification d'échec de remise (NDR) est envoyée à l'expéditeur pour l'informer que son message n'a pas été remis.</span><span class="sxs-lookup"><span data-stu-id="410e7-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="410e7-p109">L'activation de DBEB nécessite une configuration utilisateur et une configuration de domaine. Pour plus d'informations, consultez la rubrique [Utiliser le blocage du périmètre basé sur l'annuaire pour rejeter les messages envoyés à des destinataires non valides](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="410e7-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="410e7-139">Disponibilité des fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="410e7-139">Feature Availability</span></span>
<span data-ttu-id="410e7-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="410e7-140"></span></span>

<span data-ttu-id="410e7-141">Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="410e7-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

