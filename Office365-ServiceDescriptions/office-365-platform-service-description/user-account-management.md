---
title: User account management
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft prend en charge les méthodes suivantes pour créer, gérer et authentifier des utilisateurs.
ms.openlocfilehash: 31fe2a1df472b6fc22df5cb7ff29b8658519cbc7
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51172779"
---
# <a name="user-account-management"></a>User account management

Microsoft prend en charge les méthodes suivantes pour créer, gérer et authentifier des utilisateurs. 
  
> [!NOTE]
> Cette rubrique n’inclut pas d’informations sur les fonctionnalités de sécurité qui autorisent ou interdisent l’accès à des ressources Microsoft individuelles (par exemple, le contrôle d’accès basé sur un rôle dans Microsoft Exchange Online ou la configuration de la sécurité dans Microsoft SharePoint Online). Pour plus d’informations sur ces fonctionnalités, voir la [description du service Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) et la description du service [SharePoint Online.](../sharepoint-online-service-description/sharepoint-online-service-description.md) 
  
Si vous avez besoin d’informations sur les outils qui peuvent vous aider à effectuer des tâches administratives, consultez [Outils pour gérer les comptes Microsoft.](/office365/enterprise/manage-office-365-accounts) Pour découvrir comment effectuer des tâches de gestion quotidiennes, voir [Tâches de gestion courantes.](/office365/admin/manage/manage)
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>Vous avez besoin d’aide pour vous inscrire, installer ou désinstaller, ou annuler votre abonnement ?

Obtenir de l’aide [: la signature de](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4)l’installation ou de la  |  [désinstallation d’Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)annuler Office  |  [365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Pour d’autres problèmes, visitez le centre [de support Microsoft.](https://support.microsoft.com/contactus/) Pour obtenir une assistance technique pour Office 365 opéré par 21Vianet en Chine, contactez l'[équipe de support technique 21Vianet](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Pour Office 365 Germany, contactez l'[équipe du support technique d'Office 365 Germany](https://support.office.com/article/83ef2266-2543-48d7-a41a-1b56b403a8e9). 
  
## <a name="sign-in-options"></a>Options de connexion

Microsoft dispose de deux systèmes qui peuvent être utilisés pour les identités des utilisateurs :
  
- Compte scolaire ou professionnels **(identité cloud)** : les utilisateurs reçoivent les informations d’identification du cloud Azure Active Directory (distinctes des autres informations d’identification de bureau ou d’entreprise) pour se connexion aux services cloud de Microsoft. Il s'agit de l'identité par défaut, recommandée afin de minimiser la complexité du déploiement. Les mots de passe des comptes professionnels ou scolaires respectent la stratégie de mots de passe Azure Active Directory [stratégie de mot de passe](/previous-versions/azure/jj943764(v=azure.100)).
    
- Compte fédéré **(identité** fédérée) : pour tous les abonnements dans les organisations avec Active Directory local qui utilisent l' sign-on unique (SSO), les utilisateurs peuvent se connectent aux services Microsoft à l’aide de leurs informations d’identification Active Directory. Active Directory d'entreprise stocke et commande la stratégie de mot de passe. Pour plus d'informations sur l'authentification unique, voir [Feuille de route pour l'authentification unique](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Le type d'identité affecte non seulement l'expérience utilisateur et les options de gestion du compte utilisateur, mais également les conditions requises en termes de matériels et de logiciels et d'autres considérations concernant le déploiement.
  
### <a name="custom-domains-and-identity-options"></a>Domaines personnalisés et options d’identité

Lorsque vous créez un utilisateur, son nom et son adresse de messagerie sont affectés au domaine par défaut tel qu’il est définie dans le Centre d’administration Microsoft 365. Pour en savoir plus, voir [Ajouter vos utilisateurs et votre domaine.](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611) 
  
Par défaut, l’abonnement utilise <*nom* de société .onmicrosoft.com qui a >  été créé avec le compte. Si vous utilisez Office 365 géré par 21Vianet en Chine, le domaine par défaut est <nom d’entreprise > **.onmsChina.cn**. Si vous utilisez Office 365 Germany, le domaine par défaut est <*nom d’entreprise* > **.onmicrosoft.de**. Vous pouvez ajouter un ou plusieurs domaines personnalisés à Microsoft au lieu de conserver le domaine **onmicrosoft.com** et affecter des utilisateurs pour se connecter avec l’un des domaines validés. Chaque domaine attribué de l'utilisateur est l'adresse de messagerie qui doit apparaître sur les messages électroniques envoyés et reçus. 
  
Vous pouvez héberger jusqu’à 900 domaines Internet enregistrés, chacun représenté par un espace de noms différent. 
  
Pour les organisations utilisant l'authentification unique, tous les utilisateurs d'un domaine doivent utiliser le même système d'identité : l'identité cloud (en nuage) ou l'identité fédérée. Par exemple, vous pouvez avoir un groupe d’utilisateurs qui n’a besoin que d’une identité cloud, car ils n’accèdent pas aux systèmes locaux, et un autre groupe d’utilisateurs qui utilisent Microsoft et les systèmes locaux. Vous ajoutez deux domaines à Office 365, tels que **contractors.contoso.com** et **staff.contoso.com,** et vous ne configureriez l' sso que pour l’un d’entre eux. La totalité d'un domaine peut être converti d'une identité cloud (en nuage) à une identité fédérée ou d'une identité fédérée à une identité cloud (en nuage).
  
Pour plus d'informations à propos des domaines dans Office 365, voir la description du service [Domaines](domains.md). 
  
## <a name="authentication"></a>Authentification

À l’exception des sites Internet pour l’accès anonyme créés avec SharePoint Online, les utilisateurs doivent être authentifiés lors de l’accès aux services Microsoft. 
  
- **Authentification moderne** : l’authentification moderne apporte une authentification basée sur la bibliothèque d’authentification Microsoft aux applications clientes Office sur toutes les plateformes. Cela active des fonctionnalités de connexion telles que MFA (Multi-Factor Authentication), des fournisseurs d'identité tiers SAML avec des applications clientes Office et l'authentification par carte à puce et basée sur des certificats. Microsoft Outlook n'a plus besoin non plus d'utiliser le protocole d'authentification de base. Pour plus d’informations, notamment sur la disponibilité de l’authentification moderne dans les applications Office, voir Fonctionnement de l’authentification moderne pour les applications [clientes Office 2013 et Office 2016.](/office365/enterprise/modern-auth-for-office-2013-and-2016)
    
    L’authentification moderne est désactivée par défaut pour Exchange Online. Pour savoir comment l’activer ou la désactiver, voir [Activer l’authentification moderne dans Exchange Online.](/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)
    
- **Authentification d’identité cloud** : les utilisateurs avec des identités cloud sont authentifiés à l’aide d’une demande/réponse traditionnelle. Le navigateur web est redirigé vers le service de signature Microsoft, où vous tapez le nom d’utilisateur et le mot de passe de votre compte scolaire ou scolaire. Le service de connexion authentifie vos informations d'identification et génère un jeton de service que le navigateur web adresse au service demandé pour vous y connecter. 
    
- **Authentification** d’identité fédérée : les utilisateurs avec des identités fédérées sont authentifiés à l’aide des services AD FS (Active Directory Federation Services) 2.0 ou d’autres services d’jetons de sécurité. Le navigateur web est redirigé vers le service de signature Microsoft, où vous tapez votre ID d’entreprise sous la forme d’un nom d’utilisateur principal (UPN), *par exemple : isabel@contoso.com*. Le service de connexion détermine que vous appartenez à un domaine fédéré et propose de vous rediriger vers un serveur de fédération local pour l'authentification. Si vous êtes connecté au bureau (joint au domaine), vous êtes authentifié (à l’aide de Kerberos ou NTLMv2) et le service d’jetons de sécurité local génère un jeton d’accès, que le navigateur web publie au service de authentification Microsoft. Grâce au jeton d'ouverture de session, le service de connexion génère un jeton de service que le navigateur web adresse au service demandé pour vous y connecter. Pour obtenir la liste des services d'émission de jeton de sécurité disponibles, voir [Feuille de route pour l'authentification unique](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Microsoft utilise l’authentification basée sur les formulaires et le trafic d’authentification sur le réseau est toujours chiffré avec TLS/SSL à l’aide du port 443. Le trafic d’authentification utilise un pourcentage négligeable de bande passante pour les services Microsoft. 
  
### <a name="multi-factor-authentication"></a>Authentification multifacteur

Avec l’authentification multifacteur, les utilisateurs doivent reconnaître un appel téléphonique, un SMS ou une notification d’application sur leur smartphone après avoir correctement entré leur mot de passe. Ce n'est qu'après cette deuxième authentification que l'utilisateur peut se connecter. Les administrateurs Microsoft peuvent inscrire des utilisateurs pour l’authentification multifacteur dans le Centre d’administration Microsoft 365. En savoir plus sur [l’authentification multifacteur.](/office365/admin/security-and-compliance/set-up-multi-factor-authentication)
  
### <a name="rich-client-authentication"></a>Authentification des clients riches

Pour les clients riches comme des applications de bureau Microsoft Office, l'authentification peut se produire de deux manières :
  
- **assistant Microsoft Online Services Sign-In** - L’Assistant De se connectez, qui est installé par le programme d’installation de bureau, contient un service client qui obtient un jeton de service du service de signature et le renvoie au client riche. 
    
  - Si vous avez une identité cloud, vous recevez une invite d’informations d’identification que le service client envoie au service de connexion pour authentification (à l’aide de WS-Trust).
    
  - Si vous avez une identité fédérée, le service client contacte d’abord le serveur AD FS 2.0 pour authentifier les informations d’identification (à l’aide de Kerberos ou NTLMv2) et obtenir un jeton de connexion qui est envoyé au service de connexion (à l’aide de WS-Federation et WS-Trust).
    
- **Authentification de base/proxy sur SSL** : le client Outlook transmet les informations d’identification d’authentification de base sur SSL à Exchange Online. Exchange Online proxys the authentication request to the identity platform, and then to on-premises Active Directory Federation Server (for SSO). 
    
Pour garantir une découverte et une authentification correctes des services Microsoft, les administrateurs doivent appliquer un ensemble de composants et de mises à jour à chaque station de travail qui utilise des clients enrichis (tels que Microsoft Office 2010) et se connecte à Office 365. La configuration du bureau est un outil automatisé qui permet de configurer les stations de travail avec les mises à jour requises. Pour plus d’informations, voir [Utiliser mes applications de bureau Office actuelles.](https://support.office.com/article/3324b8b8-dceb-45e2-ac24-c642720108f7)
  
### <a name="sign-in-experience"></a>Expérience de connexion

L’expérience de la sign-in change en fonction du type d’identité utilisé :<br><br>
  
| Service | Identité de nuage | Identité fédérée |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Outlook 2010 ou Office 2007 sous Windows 7  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Outlook 2010 ou Office Outlook 2007 sous Windows Vista  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|POP, IMAP, Outlook pour Mac  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Expériences web : Centre d’administration Microsoft 365 / Outlook sur le web/ SharePoint Online/ Office pour le web  <br/> |Connexion à chaque session de navigateur<sup>4</sup> <br/> |Connexion à chaque session <sup>3</sup> <br/> |
|Office 2010 ou Office 2007 à l'aide de SharePoint Online  <br/> |Connexion à chaque session SharePoint Online<sup>4</sup> <br/> |Connexion à chaque session SharePoint Online<sup>3</sup> <br/> |
|Skype Entreprise Online  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Aucune invite de commande  <br/> |
|Outlook pour Mac  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Lorsque vous y êtes invité pour la première fois, vous pouvez enregistrer votre mot de passe pour une utilisation ultérieure. Vous ne recevrez pas d’autre invite tant que le mot de passe reste inchangé. <br/> 
<sup>2 Vous entrez</sup> vos informations d’identification d’entreprise. Vous pouvez enregistrer votre mot de passe et vous ne recevrez pas d’autre invite tant que le mot de passe reste inchangé. <br/> 
<sup>3</sup> Toutes les applications nécessitent que vous entiez ou sélectionniez votre nom d’utilisateur pour vous inscrire. Vous n’êtes pas invité à saisir votre mot de passe si votre ordinateur est joint au domaine. Si vous **sélectionnez Maintenir la signature,** vous n’êtes pas invité à vous le faire tant que vous n’avez pas ouvert la signature. <br/> 
<sup>4</sup> If you select **Keep me signed in** you will not be prompted again until you sign out. 
  
## <a name="create-user-accounts"></a>Create user accounts

Il existe plusieurs façons d’ajouter des utilisateurs. Pour en savoir plus, consultez Ajouter des utilisateurs individuellement ou en bloc [:](/office365/admin/add-users/add-users) aide de l’administrateur et ajout, suppression et gestion des utilisateurs dans la prévisualisation du Centre d’administration [Microsoft 365.](https://support.office.com/article/6e80db58-c36b-4add-b1c8-cc5135f111f3) Si vous utilisez Office 365 géré par 21Vianet en Chine, consultez l'article relatif à la [création ou la modification de comptes d'utilisateurs dans Office 365 géré par 21Vianet - Aide de l'administrateur](/office365/admin/add-users/add-users).
  
## <a name="delete-user-accounts"></a>Supprimer des comptes d’utilisateur

La manière dont vous supprimez des comptes dépend de l'usage ou non de la synchronisation d'annuaires : 
  
- Si vous n’utilisez pas la synchronisation d’annuaires, les comptes peuvent être supprimés à l’aide de la page d’administration ou de Windows PowerShell.
    
- Si vous utilisez la synchronisation d'annuaires, vous devez supprimer des utilisateurs à partir d'Active Directory sur site au lieu d'Office 365.
    
Une fois supprimé, le compte devient inactif. Vous pouvez toujours restaurer le compte jusqu'à environ 30 jours après l'avoir supprimé. Pour plus d’informations sur la suppression [](/office365/admin/add-users/delete-a-user) et la [](/office365/admin/add-users/restore-user) restauration de comptes, voir Supprimer des utilisateurs et Restaurer des utilisateurs ou, si vous utilisez Office 365 géré par 21Vianet en Chine, voir Créer ou modifier des comptes d’utilisateurs dans Office 365 géré par [21Vianet -](/office365/admin/add-users/add-users)Aide de l’administrateur.
  
## <a name="password-management"></a>Gestion des mots de passe

Les stratégies et procédures de gestion des mots de passe dépendent du système d’identité.
  
### <a name="cloud-identity-password-management"></a>Gestion des mots de passe d’identité cloud
  
Si des identités cloud (en nuage) sont utilisées ; les mots de passe sont générés automatiquement lors de la création du compte.
  
- Pour les règles qui s'appliquent aux mots de passe d'identité cloud (en nuage), voir [Stratégie de mot de passe](/previous-versions/azure/jj943764(v=azure.100)).
    
- Pour renforcer la sécurité, les utilisateurs doivent modifier leur mot de passe lorsqu’ils accèdent pour la première fois aux services Microsoft. Par conséquent, pour que les utilisateurs accèdent aux services Microsoft, ils doivent se connecter au Centre d’administration Microsoft 365, où ils sont invités à modifier leur mot de passe.
    
- Les administrateurs peuvent définir la stratégie d'expiration des mots de passe. Pour plus d'informations, consultez l'article [Définir la stratégie d'expiration des mots de passe pour votre organisation](/office365/admin/manage/set-password-expiration-policy).
    
Plusieurs outils permettent aux utilisateurs possédant une identité cloud (en nuage) de réinitialiser leur mot de passe :
  
- **L’administrateur** réinitialise le mot de passe : si les utilisateurs perdent ou oublient leur mot de passe, les administrateurs peuvent réinitialiser les mots de passe des utilisateurs dans le Centre d’administration ou à l’aide Windows PowerShell. Les utilisateurs peuvent uniquement changer leur propre mot de passe que s'ils connaissent leur mot de passe actuel. 
    
    Pour les plans d’entreprise, si les administrateurs perdent ou oublient leur mot de passe, un autre administrateur ayant le rôle Administrateur général peut réinitialiser les mots de passe des administrateurs dans le Centre d’administration Microsoft 365 ou à l’aide de Windows PowerShell. Pour plus d'informations, voir [Réinitialiser les mots de passe des administrateurs](/office365/admin/add-users/reset-passwords). Si vous travaillez dans Office 365 géré par 21Vianet en Chine, reportez-vous à l'article relatif à la [modification ou la réinitialisation des mots de passe dans Office 365 géré par 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **L’utilisateur** modifie les mots de passe avec Outlook sur le web - La page Options d’Outlook sur le web inclut un lien hypertexte Modifier le mot de passe, qui redirige les utilisateurs vers la page Modifier le mot **de** passe. L'utilisateur doit connaître son mot de passe précédent. Pour plus d'informations, voir [Modifier le mot de passe](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Si vous utilisez Office 365 géré par 21Vianet en Chine, reportez-vous à l'article relatif à la [modification ou la réinitialisation des mots de passe dans Office 365 géré par 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
-  Droits de réinitialisation de mot de passe basés sur les rôles  : pour les plans d’entreprise, les utilisateurs autorisés tels que le personnel du service d’aide peuvent se voir attribuer le droit d’utilisateur Réinitialiser le mot de passe et le droit de modifier les mots de passe à l’aide de rôles prédéfinisés ou personnalisés sans devenir des administrateurs de services complets. Par défaut, dans les plans d’entreprise, les administrateurs ayant le rôle Administrateur général, Administrateur de mots de passe ou Administrateur de gestion des utilisateurs peuvent modifier les mots de passe. Pour plus d'informations, consultez la rubrique [Affectation de rôles d'administrateur](/office365/admin/add-users/assign-admin-roles).
    
- **Réinitialisez les mots de passe Windows PowerShell** - Les administrateurs de service peuvent utiliser Windows PowerShell pour réinitialiser les mots de passe. 
    
### <a name="federated-identity-password-management"></a>Gestion des mots de passe d’identité fédérée
  
Si des identités fédérées sont utilisées, les mots de passe sont gérés dans Active Directory. Le service d’jetons de sécurité local négocie l’authentification avec Federation Gateway sans transmettre les mots de passe Active Directory locaux des utilisateurs via Internet à Office 365. Des stratégies de mot de passe locales sont utilisées, ou, pour les clients web, une identification à deux facteurs. Outlook sur le web n’inclut pas de lien hypertexte Modifier le mot de passe. Pour changer leurs mots de passe, les utilisateurs se servent des outils locaux standard ou des options de connexion au bureau de leur PC.
  
Si vous avez activé la synchronisation d’annuaires avec l’ynchronisation unique [(SSO)](/previous-versions/azure/azure-services/dn441213(v=azure.100)) dans votre environnement d’organisation et qu’une panne a un impact sur votre fournisseur d’identité fédéré, la sauvegarde de synchronisation des mots de passe pour la signature fédérée offre la possibilité de basculer manuellement votre domaine sur Synchronisation des mots de passe. L’utilisation de la synchronisation des mots de passe permet à vos utilisateurs d’accéder pendant que la panne est corrigée. Découvrez [comment passer de l'Sign-On à la synchronisation de mot de passe.](https://go.microsoft.com/fwlink/p/?LinkId=509832)
  
## <a name="license-management"></a>Gestion des licences

Une licence permet à un utilisateur d’accéder à un ensemble de services Microsoft. Un administrateur attribue une licence à chaque utilisateur pour le service auquel l'utilisateur a besoin d'avoir accès. Par exemple, vous pouvez attribuer à un utilisateur un accès à Skype Entreprise Online, mais pas à SharePoint Online.
  
Les administrateurs de facturation Microsoft peuvent apporter des modifications aux détails de l’abonnement, tels que le nombre de licences utilisateur et le nombre de services supplémentaires que votre entreprise utilise. Consultez [Attribuer ou supprimer une licence.](/office365/admin/subscriptions-and-billing/assign-licenses-to-users) Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à l'article relatif à [l'affectation ou la suppression de licences dans Office 365 géré par 21Vianet](/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gestion des groupes

Les groupes de sécurité sont utilisés dans SharePoint Online pour contrôler l'accès aux sites. Les groupes de sécurité peuvent être créés dans le Centre d’administration Microsoft 365. Pour plus d'informations sur les groupes de sécurité, voir [Créer, modifier ou supprimer un groupe de sécurité](/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Rôles d'administrateur

Office 365 pour entreprise suit un modèle de contrôle d’accès basé sur un rôle (RBAC) : les autorisations et les fonctionnalités sont définies par les rôles de gestion. La personne s'inscrivant à Office 365 pour son organisation devient automatiquement un administrateur global ou un administrateur de niveau supérieur. Il y a cinq rôles d'administrateur : administrateur général, administrateur de facturation, administrateur de mots de passe, administrateur de services fédérés et administrateur de gestion des utilisateurs. Pour plus d’informations sur les rôles d’administrateur dans Office 365 pour les entreprises, notamment sur leur application à l’administration Exchange Online, SharePoint Online et Skype Entreprise Online, voir Attribution de rôles [d’administrateur.](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)) Si vous utilisez Office 365 géré par 21Vianet en Chine, consultez la rubrique [Attribuer des rôles d'administrateur dans Office 365 pour les entreprises](/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Administration déléguée et prise en charge pour des partenaires

Des partenaires peuvent être autorisés à administrer des comptes pour le compte de clients. Le client n’a pas besoin d’un compte d’utilisateur pour l’utilisation des partenaires et n’utilise pas de licence lors de l’octroi d’une autorité d’administration déléguée. Les partenaires peuvent attribuer un accès complet ou limité aux utilisateurs au sein de leur organisation. Un accès limité inclut des droits permettant de réinitialiser des mots de passe, de gérer des demandes de service et de surveiller l'état du service. 
  
> [!NOTE]
> La possibilité d’utiliser et de spécifier un partenaire comme administrateur délégué dépend de la région. 
  
## <a name="azure-active-directory-services"></a>Services Azure Active Directory

Azure Active Directory apporte à Office 365 des fonctionnalités complètes de gestion des identités et des accès. Il combine des services d'annuaire, une gouvernance des identités avancée, une gestion d'accès aux applications et une plateforme complète basée sur des normes pour les développeurs. Pour en savoir plus sur les fonctionnalités AD d’Office 365, consultez La marque de page de signature et la réinitialisation du mot de passe en [libre-service de l’utilisateur]() https://go.microsoft.com/fwlink/?linkid=2144147 cloud. En savoir plus sur les [éditions gratuite, de base et Premium d'Azure Active Directory](/previous-versions/azure/dn532272(v=azure.100)). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir la description du service de plateforme [Microsoft 365 et Office 365.](office-365-platform-service-description.md)
