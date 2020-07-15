---
title: Autorisations
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132688"
---
# <a name="permissions"></a>Autorisations

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
Pour plus d'informations sur le modèle d'autorisations RBAC utilisé dans Exchange Online, consultez la rubrique [Autorisations](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Autorisations basées sur des rôles

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
Il existe deux types de rôles : rôles d'administrateur et rôles d'utilisateur final :
  
- **Rôles d'administrateur** Ces rôles comportent des autorisations qu'il est possible d'assigner à des administrateurs ou des utilisateurs spécialisés utilisant des groupes de rôles qui ont une fonction de gestion dans l'organisation Exchange Online (ex. destinataires, des ou bases de données). 
    
- **Rôles d’utilisateur final** Ces rôles, assignés à l’aide de stratégies d’attribution de rôle, permettent aux utilisateurs de gérer les aspects de leurs propres boîtes aux lettres et groupes de distribution qu’ils possèdent. Les rôles d'utilisateur final commencent par le préfixe  `My`.
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> Certains rôles disponibles dans la version sur site de Microsoft Exchange Server 2013 ne sont peut-être pas disponibles dans Exchange Online. 
  
Pour plus d'informations sur les autorisations disponibles dans Exchange Online, consultez la section [Autorisations basées sur des rôles](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Groupes de rôles

Les groupes de rôles de gestion associent les rôles de gestion à un groupe d'administrateurs ou d'utilisateurs spécialisés. Les administrateurs gèrent une organisation Exchange Online ou une configuration de destinataires étendue. Les utilisateurs spécialisés gèrent les fonctionnalités spécifiques d’Exchange Online, telles que la conformité, ou ils peuvent avoir des capacités de gestion limitées, telles que les membres du support technique, mais ne reçoivent pas de droits d’administration étendus. Les groupes de rôles associent généralement des rôles de gestion administrative permettant aux administrateurs et aux utilisateurs spécialistes de gérer la configuration de leur organisation et des destinataires. Par exemple, si les administrateurs peuvent gérer les destinataires ou utiliser les fonctionnalités de découverte des boîtes aux lettres sont contrôlées à l’aide de groupes de rôles. 
  
> [!IMPORTANT]
> Certains groupes de rôles disponibles dans la version sur site de Microsoft Exchange Server 2013 ne sont peut-être pas disponibles dans Exchange Online. 
  
Pour plus d'informations sur les groupes de rôles, consultez la section [Groupes de rôles et stratégies d'attribution de rôle](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Stratégies d'attribution des rôles

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> Certaines attributions de rôles disponibles dans la version sur site de Microsoft Exchange Server 2013 ne sont peut-être pas disponibles dans Exchange Online. 
  
Pour plus d'informations sur les stratégies d'attribution de rôle, consultez la section [Groupes de rôles et stratégies d'attribution de rôle](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  

