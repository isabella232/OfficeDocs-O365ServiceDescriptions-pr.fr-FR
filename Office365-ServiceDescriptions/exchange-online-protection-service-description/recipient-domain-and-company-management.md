---
title: Gestion des destinataires, des domaines et des sociétés
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) offre plusieurs moyens de gérer les informations concernant les destinataires, les domaines et les entreprises. En tant qu’administrateur, vous pouvez effectuer certaines tâches de gestion dans le centre d’administration Exchange et vérifier les autres tâches de gestion effectuées dans le centre d’administration 365 de Microsoft.
ms.openlocfilehash: 84be0148636b4e345f59158af0a767e9cd2396c7
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581840"
---
# <a name="recipient-domain-and-company-management"></a>Gestion des destinataires, des domaines et des sociétés

Microsoft Exchange Online Protection (EOP) offre plusieurs moyens de gérer les informations concernant les destinataires, les domaines et les entreprises. En tant qu’administrateur, vous pouvez effectuer certaines tâches de gestion dans le centre d’administration Exchange et vérifier les autres tâches de gestion effectuées dans le centre d’administration 365 de Microsoft.
  
Vous recherchez des informations sur toutes les fonctionnalités EOP ? Consultez la rubrique [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Mail recipients

Les destinataires du message sont classés en tant qu'utilisateurs ou groupes de messagerie et peuvent être gérés à l'aide de la synchronisation d'annuaires, directement dans le Centre d'administration Exchange, ou via le service Windows PowerShell à distance. Si vous gérez vos destinataires localement, vous devez synchroniser les annuaires pour que les destinataires des messages apparaissent dans le Centre d'administration Exchange. Les utilisateurs gérés uniquement dans le centre d’administration 365 de Microsoft ne sont pas affichables dans le centre d’administration Exchange, mais ils peuvent être ajoutés ou supprimés de l’appartenance à un groupe de rôles d’administrateur dans le centre d’administration Exchange. Pour plus d'informations sur les destinataires dans EOP, consultez la rubrique [Gestion des destinataires dans Exchange Online Protection (EOP)](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

Dans EOP, vous pouvez configurer uniquement des rôles d'administrateur. Le Centre d'administration Exchange vous permet d'ajouter directement des utilisateurs à des groupes de rôles d'administrateur par défaut ou d'en supprimer. Aucune personnalisation RBAC n'est disponible. Pour plus d'informations, consultez la rubrique [Gérer les autorisations de groupe de rôles d'administrateur dans EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Gestion de domaines

Les domaines gérés sont des domaines protégés par EOP. Le Centre d'administration Exchange permet d'afficher les domaines gérés et de modifier les types de domaines. La mise en service et la gestion de domaine se produisent dans le centre d’administration 365 de Microsoft et les modifications sont reflétées dans le centre d’administration Exchange. Pour plus d'informations, consultez la rubrique [Gérer des domaines acceptés dans EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Match subdomains

Dans EOP, vous pouvez activer le flux de messagerie pour les sous-domaines d'un domaine géré. Pour plus d'informations, consultez la rubrique [Activer le flux de messagerie pour les sous-domaines dans EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Directory Based Edge Blocking (DBEB)

La fonctionnalité de blocage du périmètre basé sur l'annuaire vous permet de rejeter les messages pour les destinataires non valides sur le périmètre du réseau de service. La fonctionnalité de blocage du périmètre basé sur l'annuaire (DBEB) permet aux administrateurs d'ajouter des destinataires à extension messagerie à Office 365 et de bloquer tous les messages envoyés à des adresses de messagerie qui ne sont pas présentes dans Office 365. Si un message est envoyé à une adresse de messagerie valide présente dans Office 365, celui-ci continue à travers le reste des couches de filtrage de services (anti-programme malveillant, anti-courrier indésirable, règles de transport). Si l'adresse n'est pas présente, le service bloque le message avant même le filtrage, et une notification d'échec de remise (NDR) est envoyée à l'expéditeur pour l'informer que son message n'a pas été remis. 
  
L'activation de DBEB nécessite une configuration utilisateur et une configuration de domaine. Pour plus d'informations, consultez la rubrique [Utiliser le blocage du périmètre basé sur l'annuaire pour rejeter les messages envoyés à des destinataires non valides](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, consultez la rubrique [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).
