---
title: Gestion des comptes d'utilisateur
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft Office 365 prend en charge les méthodes suivantes pour la création, la gestion et l'authentification des utilisateurs.
ms.openlocfilehash: 76a47ba99c9b163c98b7370407d3390c20235ed5
ms.sourcegitcommit: a6d9057a955ca220db9e4dbc29cd9ea0053616fc
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/10/2019
ms.locfileid: "31764852"
---
# <a name="user-account-management"></a>Gestion des comptes d'utilisateur

Microsoft Office 365 prend en charge les méthodes suivantes pour la création, la gestion et l'authentification des utilisateurs. 
  
> [!NOTE]
> Dans cette rubrique, vous ne trouverez pas d'informations sur les fonctionnalités de sécurité qui autorisent ou interdisent l'accès à des ressources Office 365 individuelles (par exemple, le contrôle d'accès basé sur les rôles dans Microsoft Exchange Online ou la configuration de la sécurité dans Microsoft SharePoint Online). Pour plus d'informations sur ces fonctionnalités, consultez les rubriques [Description du service Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) et [Description du service SharePoint Online](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Si vous avez besoin d'informations sur les outils qui peuvent vous aider à effectuer des tâches administratives, consultez l'article [Outils permettant de gérer les comptes Office 365](https://go.microsoft.com/fwlink/?linkid=847777). Pour découvrir comment effectuer des tâches de gestion quotidiennes, consultez l'article [Tâches de gestion courantes dans Office 365](https://go.microsoft.com/fwlink/?linkid=847778).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>Besoin d’aide pour la connexion, l’installation, la désinstallation ou l’annulation de votre abonnement ?

Obtenir de l'aide pour [se connecter à Office 365](http://go.microsoft.com/fwlink/?LinkID=529144&amp;clcid=0x409) | [Installer ou désinstaller Office](http://go.microsoft.com/fwlink/?LinkID=827202&amp;clcid=0x409) | [Annuler votre abonnement Office 365](https://support.office.com/en-us/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Pour d'autres problèmes avec Office 365 visitez le [centre de support Microsoft](https://go.microsoft.com/fwlink/?LinkID=808783). Pour obtenir une assistance technique pour Office 365 opéré par 21Vianet en Chine, contactez l'[équipe de support technique 21Vianet](https://support.office.com/en-US/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Pour Office 365 Germany, contactez l'[équipe du support technique d'Office 365 Germany](https://support.office.com/en-us/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Options de connexion

Office 365 possède deux systèmes qui peuvent être utilisés pour les identités des utilisateurs :
  
- **Compte professionnel ou scolaire (identité cloud)** Les utilisateurs reçoivent des informations d'identification de cloud (en nuage) Azure Active Directory (distinctes des informations d'identification du bureau ou d'entreprise) pour se connecter à Office 365 et à d'autres Services de cloud computing Microsoft. Il s'agit de l'identité par défaut, recommandée afin de minimiser la complexité du déploiement. Les mots de passe des comptes professionnels ou scolaires respectent la stratégie de mots de passe Azure Active Directory [stratégie de mot de passe](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409).
    
- **Compte fédéré (identité fédérée)** Pour tous les abonnements dans des organisations avec Active Directory en local utilisant l'authentification unique, les utilisateurs peuvent se connecter aux services Office 365 à l'aide de leurs informations d'identification Active Directory. Active Directory d'entreprise stocke et commande la stratégie de mot de passe. Pour plus d'informations sur l'authentification unique, voir [Feuille de route pour l'authentification unique](https://go.microsoft.com/fwlink/p/?LinkID=270015).
    
Le type d'identité affecte non seulement l'expérience utilisateur et les options de gestion du compte utilisateur, mais également les conditions requises en termes de matériels et de logiciels et d'autres considérations concernant le déploiement.
  
### <a name="custom-domains-and-identity-options"></a>Domaines personnalisés et options d’identité

Lorsque vous créez un utilisateur, le nom de connexion et l'adresse de messagerie de l'utilisateur sont affectés au domaine par défaut comme défini dans le centre d'administration 365 de Microsoft. Pour en savoir plus, voir [Ajouter un domaine et des utilisateurs à l'aide de la configuration d'Office 365](https://support.office.com/en-us/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Par défaut, l'abonnement Office 365 utilise le domaine \< _company name_\> **.onmicrosoft.com** qui a été créé avec le compte.\* Il est possible d'ajouter un ou plusieurs domaines personnalisés à Office 365 au lieu de conserver le domaine onmicrosoft.com, et d'affecter des utilisateurs pour qu'ils se connectent avec l'un des domaines validés. Chaque domaine attribué de l'utilisateur est l'adresse de messagerie qui doit apparaître sur les messages électroniques envoyés et reçus. 
  
Vous pouvez héberger jusqu'à 900 domaines Internet inscrits dans Office 365, chacun étant représenté par un espace de noms différent. 
  
Pour les organisations utilisant l'authentification unique, tous les utilisateurs d'un domaine doivent utiliser le même système d'identité : l'identité cloud (en nuage) ou l'identité fédérée. Par exemple, vous pourriez avoir un groupe d'utilisateurs qui requiert uniquement une identité cloud (en nuage) parce que ces utilisateurs n'accèdent pas aux systèmes locaux (sur site) et un autre groupe d'utilisateurs qui utilise Office 365 et des systèmes locaux. Vous ajoutez deux domaines à Office 365, tels que contractors.contoso.com et staff.contoso.com, et vous configurez uniquement SSO pour l'un d'entre eux. La totalité d'un domaine peut être converti d'une identité cloud (en nuage) à une identité fédérée ou d'une identité fédérée à une identité cloud (en nuage).
  
Pour plus d'informations à propos des domaines dans Office 365, voir la description du service [Domaines](domains.md). 
  
\* Si vous utilisez Office 365 géré par 21Vianet en Chine, le domaine par défaut est \<nom_entreprise\> **.onmsChina.cn**. Si vous utilisez Office 365 Germany, le domaine par défaut est \<nom_entreprise\> **.onmicrosoft.de**
  
## <a name="authentication"></a>Authentification

À l'exception des sites Internet permettant un accès anonyme créé avec SharePoint Online, les utilisateurs doivent être authentifiés lorsqu'ils accèdent à des services Office 365. 
  
- **Authentification moderne** L'authentification moderne permet de prendre en charge la connexion ADAL (Active Directory Authentication Library) sur des applications clientes Office sur plusieurs plateformes. Cela active des fonctionnalités de connexion telles que MFA (Multi-Factor Authentication), des fournisseurs d'identité tiers SAML avec des applications clientes Office et l'authentification par carte à puce et basée sur des certificats. Microsoft Outlook n'a plus besoin non plus d'utiliser le protocole d'authentification de base. Pour plus d'informations, notamment sur la disponibilité de l'authentification moderne sur des applications Office, voir la page relative au [fonctionnement de l'authentification modernes pour les applications clientes Office 2013 et Office 2016](http://go.microsoft.com/fwlink/?LinkID=717892&amp;clcid=0x409) et à l' [utilisation de l'authentification moderne d'Office 365 avec les clients Office](http://go.microsoft.com/fwlink/?LinkID=717893&amp;clcid=0x409).
    
    L'authentification moderne n'est pas activée par défaut pour Exchange Online. Pour savoir comment l'activer, voir [Activer Exchange Online pour l'authentification moderne](http://go.microsoft.com/fwlink/?LinkID=717894&amp;clcid=0x409).
    
- **Authentification d'identité cloud (en nuage)** L'authentification des utilisateurs avec des identités cloud (en nuage) s'effectue via l'authentification par stimulation/réponse traditionnelle. Le navigateur web est redirigé vers le service de connexion de Office 365, dans lequel vous entrez les nom d'utilisateur et mot de passe de votre compte professionnel ou scolaire. Le service de connexion authentifie vos informations d'identification et génère un jeton de service que le navigateur web adresse au service demandé pour vous y connecter. 
    
- **Authentification d'identité fédérée** L'authentification des utilisateurs avec des identités fédérés s'effectue à l'aide de Services ADFS (Active Directory Federation Services) 2.0 ou d'autres services d'émission de jeton de sécurité. Le navigateur Web est redirigé vers le service de connexion Office 365, où vous tapez votre ID d'entreprise sous la forme d'un nom d'utilisateur principal (UPN, par exemple isabel@contoso.com). Le service de connexion détermine que vous appartenez à un domaine fédéré et propose de vous rediriger vers un serveur de fédération local pour l'authentification. Si vous avez ouvert une session sur le bureau (domaine joint), vous êtes authentifié (via Kerberos ou NTLMv2) et le service d'émission de jeton de sécurité local génère un jeton d'ouverture de session que le navigateur web adresse au service de connexion de Microsoft Office 365. Grâce au jeton d'ouverture de session, le service de connexion génère un jeton de service que le navigateur web adresse au service demandé pour vous y connecter. Pour obtenir la liste des services d'émission de jeton de sécurité disponibles, voir [Feuille de route pour l'authentification unique](https://go.microsoft.com/fwlink/p/?LinkID=270015).
    
Office 365 utilise une authentification basée sur les formulaires et le trafic des authentifications sur le réseau est toujours chiffré avec TLS/SSL via le port 443. Le trafic des authentifications utilise un pourcentage négligeable de la bande passante pour les services Microsoft Office 365. 
  
### <a name="multi-factor-authentication-for-office-365"></a>Multi-Factor Authentication pour Office 365

Avec l'authentification multiFacteur pour Office 365, les utilisateurs doivent accuser réception d'un appel téléphonique, d'un message texte ou d'une notification d'application sur leur smartphone après avoir entré correctement leur mot de passe. Ce n'est qu'après cette deuxième authentification que l'utilisateur peut se connecter. Les administrateurs d'Office 365 peuvent inscrire des utilisateurs pour l'authentification multifacteur dans le centre d'administration Microsoft 365. En savoir plus sur [Multi-Factor Authentication dans Office 365](https://go.microsoft.com/fwlink/p/?LinkId=392429).
  
### <a name="rich-client-authentication"></a>Authentification des clients riches

Pour les clients riches comme des applications de bureau Microsoft Office, l'authentification peut se produire de deux manières :
  
- **Assistant de connexion Microsoft Online Services** L'Assistant de connexion qui est installé par configuration du bureau Office 365, contient un service client qui obtient un jeton de service du service de connexion de Microsoft Office 365 et le renvoie au client riche. 
    
  - Si vous disposez d'une identité cloud (en nuage), vous êtes invité à entrer vos informations d'identification que le service client envoie ensuite au service de connexion de Microsoft Office 365 pour authentification (via WS-Trust).
    
  - Si vous disposez d'une identité fédérée, le service client contacte tout d'abord le serveur AD FS 2.0 pour authentifier les informations d'identification (via Kerberos ou NTLMv2) et obtient un jeton d'ouverture de session qui est envoyé ensuite au service de connexion Office 365 (via WS-Federation et WS-Trust).
    
- **Authentification de base/proxy via SSL** Le client Outlook transmet les informations d'authentification de base via SSL à Exchange Online. Exchange Online envoie par proxy la demande d'authentification à la plateforme d'identité Office 365, puis au serveur de fédération Active Directory local (pour SSO). 
    
Afin de garantir une découverte et une authentification correctes des services Office 365, les administrateurs doivent appliquer un ensemble de composants et de mises à jour à chaque station de travail qui utilise des clients riches (comme Microsoft Office 2010) et se connecte à Office 365. La configuration du bureau Office 365 est un outil automatique permettant de configurer des stations de travail avec les mises à jour requises. Pour plus d'informations, voir [Utiliser mes applications de bureau Office avec Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270049).
  
### <a name="sign-in-experience"></a>Expérience de connexion

L'expérience de connexion change selon le type d'identité Office 365 étant utilisée :
  
||**Identité cloud (en nuage)**|**Identité fédérée**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Outlook 2010 ou Office 2007 sous Windows 7  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Outlook 2010 ou Office Outlook 2007 sous Windows Vista  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|POP, IMAP, Outlook pour Mac  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
|Expériences Web : portail Office 365 / Outlook Web App / SharePoint Online / Office Online  <br/> |Connexion à chaque session de navigateur<sup>4</sup> <br/> |Connexion à chaque session <sup>3</sup> <br/> |
|Office 2010 ou Office 2007 à l'aide de SharePoint Online  <br/> |Connexion à chaque session SharePoint Online<sup>4</sup> <br/> |Connexion à chaque session SharePoint Online<sup>3</sup> <br/> |
|Skype Entreprise Online  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Aucune invite de commande  <br/> |
|Outlook pour Mac  <br/> |Connexion à chaque session <sup>1</sup> <br/> |Connexion à chaque session <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> A la première invite, vous pouvez enregistrer votre mot de passe pour un usage ultérieur. Vous ne recevrez pas d'autre invite tant que le mot de passe reste inchangé. > <sup>2</sup> Entrez vos informations d'identification d'entreprise. Vous pouvez enregistrer votre mot de passe et vous ne recevrez pas d'autre invite tant que le mot de passe reste inchangé. > <sup>3</sup> Toutes les applications vous demandent d'entrer votre nom d'utilisateur ou de cliquer pour se connecter. Vous n'êtes pas invité à saisir votre mot de passe si votre ordinateur est joint au domaine. Si vous cliquez sur **Maintenir la connexion**, l'invite n'apparaît pas tant que vous restez connecté. > <sup>4</sup> Si vous cliquez sur **Maintenir la connexion**, l'invite n'apparaît pas tant que vous restez connecté. 
  
## <a name="creating-user-accounts"></a>Création des comptes d’utilisateur

Il existe plusieurs façons d’ajouter des utilisateurs à Office 365. Pour en savoir plus, consultez la rubrique [Ajouter des utilisateurs individuellement ou en bloc à Office 365-aide de l'administrateur](https://go.microsoft.com/fwlink/p/?linkid=860006) et [Ajouter, supprimer et gérer les utilisateurs dans la version d'évaluation du centre d'administration Microsoft 365](http://go.microsoft.com/fwlink/?LinkID=624101&amp;clcid=0x409). Si vous utilisez Office 365 géré par 21Vianet en Chine, consultez l'article relatif à la [création ou la modification de comptes d'utilisateurs dans Office 365 géré par 21Vianet - Aide de l'administrateur](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409).
  
## <a name="deleting-accounts"></a>Suppression de comptes

La manière dont vous supprimez des comptes dépend de l'usage ou non de la synchronisation d'annuaires : 
  
- Si vous n'utilisez pas la synchronisation d'annuaires, vous pouvez supprimer des comptes à l'aide de la page Administration de Microsoft Office 365 ou en utilisant Windows PowerShell.
    
- Si vous utilisez la synchronisation d'annuaires, vous devez supprimer des utilisateurs à partir d'Active Directory sur site au lieu d'Office 365.
    
Une fois supprimé, le compte devient inactif. Vous pouvez toujours restaurer le compte jusqu'à environ 30 jours après l'avoir supprimé. Pour plus d'informations sur la suppression et la restauration des comptes, voir [Supprimer ou restaurer des utilisateurs dans Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270053) ou, si vous utilisez Office 365 géré par 21Vianet en Chine, reportez-vous à l'article d'aide aux administrateurs [Créer ou modifier des comptes d'utilisateurs dans Office 365 géré par 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409).
  
## <a name="password-management"></a>Gestion des mots de passe

Les stratégies et procédures de gestion des mots de passe dépendent du système d’identité.
  
 **Gestion des mots de passe d’identité cloud (en nuage) :**
  
Si des identités cloud (en nuage) sont utilisées ; les mots de passe sont générés automatiquement lors de la création du compte.
  
- Pour les règles qui s'appliquent aux mots de passe d'identité cloud (en nuage), voir [Stratégie de mot de passe](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409).
    
- Pour renforcer la sécurité, les utilisateurs doivent changer leurs mots de passe la première fois qu'ils accèdent aux services Office 365. En conséquence, avant de pouvoir accéder aux services Office 365, les utilisateurs doivent se connecter au portail Office 365, où ils sont invités à changer leurs mots de passe.
    
- Les administrateurs peuvent définir la stratégie d'expiration des mots de passe. Pour plus d'informations, consultez l'article [Définir la stratégie d'expiration des mots de passe pour votre organisation](https://go.microsoft.com/fwlink/p/?LinkID=285381).
    
Plusieurs outils permettent aux utilisateurs possédant une identité cloud (en nuage) de réinitialiser leur mot de passe :
  
- **Mot de passe réinitialisé par l'administrateur** Si un utilisateur perd ou oubli son mot de passe, l'administrateur peut réinitialiser le mot de passe de l'utilisateur dans le portail Office 365 ou à l'aide de Windows PowerShell. Les utilisateurs peuvent uniquement changer leur propre mot de passe que s'ils connaissent leur mot de passe actuel. 
    
    Pour les plans d'entreprise, si les administrateurs perdent ou oublient leur mot de passe, un autre administrateur disposant du rôle administrateur général peut réinitialiser les mots de passe des administrateurs dans le centre d'administration 365 de Microsoft ou à l'aide de Windows PowerShell. Pour plus d'informations, voir [Réinitialiser les mots de passe des administrateurs](https://go.microsoft.com/fwlink/p/?LinkID=270062). Si vous travaillez dans Office 365 géré par 21Vianet en Chine, reportez-vous à l'article relatif à la [modification ou la réinitialisation des mots de passe dans Office 365 géré par 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409).
    
- **L'utilisateur modifie son mot de passe avec Outlook Web App** La page des options d'Outlook Web App contient un lien hypertexte Changer le mot de passe qui redirige les utilisateurs vers la page **Changer le mot de passe**. L'utilisateur doit connaître son mot de passe précédent. Pour plus d'informations, voir [Modifier le mot de passe](https://go.microsoft.com/fwlink/p/?LinkID=270063). Si vous utilisez Office 365 géré par 21Vianet en Chine, reportez-vous à l'article relatif à la [modification ou la réinitialisation des mots de passe dans Office 365 géré par 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409).
    
- **Droits de réinitialisation de mots de passe basés sur des rôles** Pour les plans Entreprise, les utilisateurs autorisés comme le personnel du support technique peuvent se voir attribuer le droit d'utilisateur **Réinitialiser le mot de passe** et le droit de changer des mots de passe en utilisant des rôles Office 365 prédéfinis ou personnalisés, sans pour autant devenir pleinement des administrateurs de services fédérés. Par défaut dans les plans Entreprise, les administrateurs ayant le rôle d'administrateur général, d'administrateur de mots de passe ou d'administrateur de gestion des utilisateurs peuvent modifier les mots de passe. Pour plus d'informations, consultez la rubrique [Affectation de rôles d'administrateur](https://go.microsoft.com/fwlink/p/?LinkID=270061).
    
- **Réinitialisation des mots de passe à l'aide de Windows PowerShell** Les administrateurs de services fédérés peuvent utiliser Windows PowerShell pour réinitialiser des mots de passe. 
    
 **Gestion des mots de passe des identités fédérées :**
  
Si des identités fédérées sont utilisées, les mots de passe sont gérés dans Active Directory. Le service d'émission de jeton de sécurité local négocie l'authentification avec la passerelle Office 365 Federation Gateway sans transférer les mots de passe d'Active Directory sur site des utilisateurs via Internet vers Office 365. Des stratégies de mot de passe locales sont utilisées, ou, pour les clients web, une identification à deux facteurs. Outlook Web App n'inclut pas de lien hypertexte Modifier le mot de passe. Pour changer leurs mots de passe, les utilisateurs se servent des outils locaux standard ou des options de connexion au bureau de leur PC.
  
Si le [scénario de synchronisation d'annuaires avec authentification unique](https://go.microsoft.com/fwlink/p/?LinkId=509831) est activé dans votre environnement Office 365 et qu'une panne touche votre fournisseur d'identité fédéré, la sauvegarde de synchronisation de mot de passe pour la connexion fédérée offre la possibilité de passer manuellement votre domaine à la synchronisation de mot de passe. L'utilisation de la synchronisation de mot de passe permettra à vos utilisateurs d'accéder à Office 365 pendant la réparation de la panne. Apprenez à [basculer de l'authentification unique à la synchronisation de mot de passe](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Gestion des licences

Une licence Office 365 donne à un utilisateur un accès à un ensemble de services Office 365. Un administrateur attribue une licence à chaque utilisateur pour le service auquel l'utilisateur a besoin d'avoir accès. Par exemple, vous pouvez attribuer à un utilisateur un accès à Skype Entreprise Online, mais pas à SharePoint Online.
  
Les administrateurs de facturation Office 365 peuvent apporter des modifications aux détails de l'abonnement, comme le nombre de licences utilisateur et le nombre de services supplémentaires utilisés par votre entreprise. Consultez [Attribuer ou supprimer des licences dans Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270069). Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à l'article relatif à [l'affectation ou la suppression de licences dans Office 365 géré par 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730747&amp;clcid=0x409).
  
## <a name="group-management"></a>Gestion des groupes

Les groupes de sécurité sont utilisés dans SharePoint Online pour contrôler l'accès aux sites. Vous pouvez créer des groupes de sécurité dans le centre d'administration Microsoft 365. Pour plus d'informations sur les groupes de sécurité, voir [Créer, modifier ou supprimer un groupe de sécurité](http://go.microsoft.com/fwlink/?LinkID=733611&amp;clcid=0x409).
  
## <a name="administrator-roles"></a>Rôles d'administrateur

Office 365 Entreprise suit un modèle RBAC (contrôle d'accès basé sur un rôle) : les autorisations et les fonctionnalités sont définies par les rôles de gestion. La personne s'inscrivant à Office 365 pour son organisation devient automatiquement un administrateur global ou un administrateur de niveau supérieur. Il y a cinq rôles d'administrateur : administrateur général, administrateur de facturation, administrateur de mots de passe, administrateur de services fédérés et administrateur de gestion des utilisateurs. Pour plus d'informations sur les rôles d'administrateur dans Office 365 Entreprise, notamment sur leur application à l'administration Exchange Online, SharePoint Online et Skype Entreprise Online, consultez la rubrique [Attribuer des rôles d'administrateur dans Office 365 pour les entreprises](https://go.microsoft.com/fwlink/p/?LinkID=282732). Si vous utilisez Office 365 géré par 21Vianet en Chine, consultez la rubrique [Attribuer des rôles d'administrateur dans Office 365 pour les entreprises](https://go.microsoft.com/fwlink/p/?linkid=270061).
  
## <a name="delegated-administration-and-support-for-partners"></a>Administration déléguée et prise en charge pour des partenaires

Des partenaires peuvent être autorisés à administrer des comptes pour le compte de clients. Le client ne nécessite pas de compte d'utilisateur à l'usage du partenaire et ne consomme donc pas de licence Office 365 en accordant une autorité d'administration déléguée. Les partenaires peuvent attribuer un accès complet ou limité aux utilisateurs au sein de leur organisation. Un accès limité inclut des droits permettant de réinitialiser des mots de passe, de gérer des demandes de service et de surveiller l'état du service. 
  
> [!NOTE]
> La possibilité d’utiliser et de spécifier un partenaire comme administrateur délégué dépend de la région. 
  
## <a name="azure-active-directory-services"></a>Services Azure Active Directory

Azure Active Directory apporte à Office 365 des fonctionnalités complètes de gestion des identités et des accès. Il combine des services d'annuaire, une gouvernance des identités avancée, une gestion d'accès aux applications et une plateforme complète basée sur des normes pour les développeurs. Pour plus d'informations sur les fonctionnalités d'Active Directory dans Office 365, voir la page relative à [la personnalisation de la page de connexion et à la réinitialisation du mot de passe libre-service d'utilisateur du nuage](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). En savoir plus sur les [éditions gratuite, de base et Premium d'Azure Active Directory](https://msdn.microsoft.com/en-us/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités selon les plans Office 365, les options autonomes et les solutions locales, voir [Description du service de plateforme Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  
