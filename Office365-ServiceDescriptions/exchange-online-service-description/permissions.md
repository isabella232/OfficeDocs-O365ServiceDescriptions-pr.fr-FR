---
title: Autorisations
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online utilise un modèle d'autorisations de contrôle d'accès basé sur un rôle (RBAC) pour permettre aux administrateurs d'organisations de contrôler finement ce que les utilisateurs et les employés du service informatique peuvent faire dans le service. Par exemple, si un responsable de la mise en conformité est responsable des demandes de recherche de boîtes aux lettres, l'administrateur peut lui déléguer cette fonction administrative au moyen du contrôle RBAC. Exchange Online utilise le même cadre RBAC que Microsoft Exchange Server 2013.
ms.openlocfilehash: f4df8e3fdaeaf1ef18a28869465affb5e4f4e060
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43639972"
---
# <a name="permissions"></a>Autorisations

Microsoft Exchange Online utilise un modèle d'autorisations de contrôle d'accès basé sur un rôle (RBAC) pour permettre aux administrateurs d'organisations de contrôler finement ce que les utilisateurs et les employés du service informatique peuvent faire dans le service. Par exemple, si un responsable de la mise en conformité est responsable des demandes de recherche de boîtes aux lettres, l'administrateur peut lui déléguer cette fonction administrative au moyen du contrôle RBAC. Exchange Online utilise le même cadre RBAC que Microsoft Exchange Server 2013. 
  
Au niveau supérieur, le contrôle RBAC se compose de rôles de gestion, de groupes de rôles de gestion et de stratégies d'attribution des rôles de gestion. Les sections suivantes fournissent plus d'informations sur chaque composant RBAC.
  
Pour plus d'informations sur le modèle d'autorisations RBAC utilisé dans Exchange Online, consultez la rubrique [Autorisations](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Autorisations basées sur des rôles

Dans Exchange Online, les autorisations que vous accordez aux administrateurs et aux utilisateurs sont basées sur des rôles de gestion. Un rôle définit un ensemble de tâches qu'un administrateur ou un utilisateur peut effectuer. Par exemple, un rôle de gestion appelé  `Mail Recipients` définit les tâches qu'une personne peut effectuer sur un ensemble de boîtes aux lettres, contacts et groupes de distribution. Lorsqu'un rôle est assigné à un administrateur ou à un utilisateur, il obtient les autorisations associées à ce rôle. 
  
Il existe deux types de rôles : rôles d'administrateur et rôles d'utilisateur final :
  
- **Rôles d'administrateur** Ces rôles comportent des autorisations qu'il est possible d'assigner à des administrateurs ou des utilisateurs spécialisés utilisant des groupes de rôles qui ont une fonction de gestion dans l'organisation Exchange Online (ex. destinataires, des ou bases de données). 
    
- **Rôles d’utilisateur final** Ces rôles, assignés à l’aide de stratégies d’attribution de rôle, permettent aux utilisateurs de gérer les aspects de leurs propres boîtes aux lettres et groupes de distribution qu’ils possèdent. Les rôles d'utilisateur final commencent par le préfixe  `My`.
    
Les rôles concèdent aux administrateurs et utilisateurs auxquels ils sont attribués des autorisations pour effectuer des tâches en mettant à leur disposition des cmdlets. Du fait que le Centre d'administration Exchange et l'environnement de ligne de commande Exchange Management Shell utilisent des cmdlets pour gérer Exchange Online, l'accès à une cmdlet autorise l'administrateur ou l'utilisateur à effectuer des tâches dans chacune des interfaces de gestion Exchange Online.
  
Les Autorisations basées sur des rôles de Microsoft Online Services se superposent de deux façons à ceux de du contrôle RBAC de Exchange Online RBAC. D'abord, les utilisateurs qui sont des administrateurs généraux ou des administrateurs de service dans Microsoft Online reçoivent automatiquement le rôle de gestion de l'organisation dans Exchange Online. Ensuite, les utilisateurs qui sont des administrateurs d'assistance dans Microsoft Online reçoivent automatiquement le rôle d'assistance dans Exchange Online. Sinon, les deux modèles de sécurité sont gérés séparément.
  
> [!IMPORTANT]
> Certains rôles disponibles dans la version sur site de Microsoft Exchange Server 2013 ne sont peut-être pas disponibles dans Exchange Online. 
  
Pour plus d'informations sur les autorisations disponibles dans Exchange Online, consultez la section [Autorisations basées sur des rôles](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Groupes de rôles

Les groupes de rôles de gestion associent les rôles de gestion à un groupe d'administrateurs ou d'utilisateurs spécialisés. Les administrateurs gèrent une organisation Exchange Online ou une configuration de destinataires étendue. Les utilisateurs spécialisés gèrent les fonctionnalités spécifiques d’Exchange Online, telles que la conformité, ou ils peuvent avoir des capacités de gestion limitées, telles que les membres du support technique, mais ne reçoivent pas de droits d’administration étendus. Les groupes de rôles associent généralement des rôles de gestion administrative permettant aux administrateurs et aux utilisateurs spécialistes de gérer la configuration de leur organisation et des destinataires. Par exemple, si les administrateurs peuvent gérer les destinataires ou utiliser les fonctionnalités de découverte des boîtes aux lettres sont contrôlées à l’aide de groupes de rôles. 
  
> [!IMPORTANT]
> Certains groupes de rôles disponibles dans la version sur site de Microsoft Exchange Server 2013 ne sont peut-être pas disponibles dans Exchange Online. 
  
Pour plus d'informations sur les groupes de rôles, consultez la section [Groupes de rôles et stratégies d'attribution de rôle](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Stratégies d'attribution des rôles

Les stratégies d'attribution des rôles de gestion associent les rôles de gestion d'utilisateur final aux utilisateurs. Les stratégies d'attribution des rôles déterminent les rôles chargés de contrôler ce que les utilisateurs peuvent effectuer au moyen de leurs boîtes aux lettres ou de leurs groupes de distribution. Ces rôles ne gèrent pas les fonctionnalités qui ne sont pas directement associées à l'utilisateur. Lorsque vous créez une stratégie d'attribution de rôle, vous définissez tout ce qu'un utilisateur peut effectuer avec sa boîte aux lettres. Par exemple, une stratégie d'attribution de rôle peut permettre à un utilisateur d'afficher le nom complet, de configurer la messagerie vocale et des règles de boîte de réception. Une autre stratégie d'attribution de rôle peut autoriser un utilisateur à modifier l'adresse, à utiliser des messages textuels et à configurer des groupes de distribution. Tous les utilisateurs munis d'une boîte aux lettres Exchange Online, y compris les administrateurs, reçoivent une stratégie d'attribution de rôle par défaut. Vous pouvez décider de la stratégie d'attribution de rôle à attribuer par défaut, choisir les éléments que la stratégie d'attribution de rôle par défaut doit inclure, remplacer les valeurs par défaut pour certaines boîtes aux lettres ou choisir de n'attribuer aucune stratégie d'attribution de rôle par défaut.
  
> [!IMPORTANT]
> Certaines attributions de rôles disponibles dans la version sur site de Microsoft Exchange Server 2013 ne sont peut-être pas disponibles dans Exchange Online. 
  
Pour plus d'informations sur les stratégies d'attribution de rôle, consultez la section [Groupes de rôles et stratégies d'attribution de rôle](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  

