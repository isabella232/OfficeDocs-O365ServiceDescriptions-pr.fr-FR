---
title: Gestion des destinataires, des domaines et des entreprises dans Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Lisez cet article pour en savoir plus sur la gestion des destinataires, des domaines et des entreprises dans Microsoft Exchange Online Protection des données (EOP).
ms.openlocfilehash: f58ffe829be839d8321cfc98f331d1836986e293
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652996"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>Gestion des destinataires, des domaines et des entreprises dans Exchange Online Protection

Microsoft Exchange Online Protection des données (EOP) offre plusieurs moyens de gérer vos informations de destinataire, de domaine et d’entreprise. En tant qu’administrateur, vous pouvez effectuer certaines tâches de gestion dans le Centre d’administration Exchange (EAC) et vérifier les autres tâches de gestion effectuées dans le Centre d’administration Microsoft 365.
  
Vous recherchez des informations sur toutes les fonctionnalités EOP ? Consultez la [description du service Exchange Online Protection.](exchange-online-protection-service-description.md)
  
## <a name="mail-recipients"></a>Mail recipients

Les destinataires du message sont classés en tant qu'utilisateurs ou groupes de messagerie et peuvent être gérés à l'aide de la synchronisation d'annuaires, directement dans le Centre d'administration Exchange, ou via le service Windows PowerShell à distance. Si vous gérez vos destinataires localement, vous devez synchroniser les annuaires pour que les destinataires des messages apparaissent dans le Centre d'administration Exchange. Les utilisateurs gérés uniquement dans le Centre d’administration Microsoft 365 ne sont pas consultables dans le CENTRE d’administration Microsoft, mais ils peuvent être ajoutés ou supprimés d’un groupe de rôles d’administrateur dans le CENTRE d’administration. Pour plus d'informations sur les destinataires dans EOP, consultez la rubrique [Gestion des destinataires dans Exchange Online Protection (EOP)](/microsoft-365/security/office-365-security/manage-recipients-in-eop).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

Dans EOP, vous pouvez configurer uniquement des rôles d'administrateur. Le Centre d'administration Exchange vous permet d'ajouter directement des utilisateurs à des groupes de rôles d'administrateur par défaut ou d'en supprimer. Aucune personnalisation RBAC n'est disponible. Pour plus d'informations, consultez la rubrique [Gérer les autorisations de groupe de rôles d'administrateur dans EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).
  
## <a name="domain-management"></a>Gestion de domaines

Les domaines gérés sont des domaines protégés par EOP. Le Centre d'administration Exchange permet d'afficher les domaines gérés et de modifier les types de domaines. La mise en service et la gestion des domaines se produisent dans le Centre d’administration Microsoft 365 et les modifications sont reflétées dans le CENTRE d’administration Microsoft. Pour plus d'informations, consultez la rubrique [Gérer des domaines acceptés dans EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).
  
## <a name="match-subdomains"></a>Match subdomains

Dans EOP, vous pouvez activer le flux de messagerie pour les sous-domaines d'un domaine géré. Pour plus d'informations, consultez la rubrique [Activer le flux de messagerie pour les sous-domaines dans EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Blocage du périmètre basé sur l’annuaire (DBEB)

La fonctionnalité de blocage du périmètre basé sur l’annuaire vous permet de rejeter les messages pour les destinataires non valides sur le périmètre du réseau de service. DBEB permet aux administrateurs d’ajouter des destinataires à messagerie à Microsoft et de bloquer tous les messages envoyés à des adresses de messagerie qui ne sont pas présentes dans Microsoft. Si un message est envoyé à une adresse de messagerie valide présente dans Microsoft, il continue à travers le reste des couches de filtrage de service (anti-programme malveillant, anti-courrier indésirable, règles de transport). Si l'adresse n'est pas présente, le service bloque le message avant même le filtrage, et une notification d'échec de remise (NDR) est envoyée à l'expéditeur pour l'informer que son message n'a pas été remis. 
  
L'activation de DBEB nécessite une configuration utilisateur et une configuration de domaine. Pour plus d'informations, consultez la rubrique [Utiliser le blocage du périmètre basé sur l'annuaire pour rejeter les messages envoyés à des destinataires non valides](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, consultez la description du [service Exchange Online Protection.](exchange-online-protection-service-description.md)