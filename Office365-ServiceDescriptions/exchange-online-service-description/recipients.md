---
title: Destinataires
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: Cette rubrique décrit les fonctionnalités en relation avec les destinataires incluses dans Microsoft Exchange Online. Celles-ci comprennent les fonctions relatives au courrier électronique, aux contacts, aux groupes de distribution, au calendrier et à la programmation.
ms.openlocfilehash: 5771fd11a51ecfb8bff2b1be8a86dd3d87a51f81
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653306"
---
# <a name="recipients"></a>Destinataires

Cette rubrique décrit les fonctionnalités en relation avec les destinataires incluses dans Microsoft Exchange Online. Celles-ci comprennent les fonctions relatives au courrier électronique, aux contacts, aux groupes de distribution, au calendrier et à la programmation.
  
## <a name="email"></a>E-mail

Une boîte aux lettres est attribuée à chaque abonné Microsoft Exchange Online et des boîtes aux lettres spécialisées destinées à la planification de ressources (comme des salles de conférence) et à un accès multi-utilisateur à des adresses de messagerie partagées sont disponibles. Des limites de stockage maximales s'appliquent à la plupart des boîtes aux lettres et les administrateurs peuvent contrôler les tailles de boîtes aux lettres autorisées. Des notifications et restrictions automatiques permettent d'alerter des utilisateurs que leurs boîtes aux lettres s'approchent de la limite ou l'on déjà atteinte. Exchange Online dispose également de plusieurs types de limitations de messages, à savoir des limites de taille des messages, de débit maximal de messages et de liste de destinataires. Toutes ces fonctionnalités et les limites sont indiquées ci-dessous.
  
> [!NOTE]
> Les adresses attrape-tout ne sont plus prises en charge dans Exchange Online. En raison du filtrage des destinataires en place pour se protéger contre les messages indésirables potentiels, les adresses de messagerie qui n’existent pas dans votre organisation sont rejetées. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Types de boîtes aux lettres, limites de stockage et alertes de capacité

Le volume de stockage de boîte aux lettres disponible pour un utilisateur et la taille de boîte aux lettres par défaut sont déterminés par le type de boîte aux lettres et la licence d'abonnement de l'utilisateur . Les administrateurs peuvent réduire les tailles maximales de boîte aux lettres au niveau de chaque utilisateur ou globalement. Exchange Online fournit également des notifications quand la capacité de la boîte aux lettres d'un utilisateur est proche du maximum ou l'atteint :
  
Pour plus d’informations, voir les sections « Limites de stockage de boîtes aux lettres » et « Alertes de capacité » dans la rubrique, [Exchange Online limites.](exchange-online-limits.md)
  
### <a name="mailtips"></a>MailTips

Les infos-courrier sont des messages automatiques et informatifs qui apparaissent au-dessus de la ligne À : tandis que les utilisateurs composent ou adressent un message. Ils ont pour objet de prévenir une remise accidentelle, des violations de stratégie ou des notifications d'échec de remise inutiles. Par exemple, des infos-courrier peuvent générer une alerte si des expéditeurs tentent d'envoyer des messages à des groupes excessivement grands, à des groupes qui contiennent des destinataires externes ou à un groupe de définition qui est avec modérateur ou restreint. Pour plus d'informations, consultez la rubrique [Infos-courrier](/exchange/clients-and-mobile-in-exchange-online/mailtips/mailtips).
  
### <a name="delegate-access"></a>Accès délégué

Exchange Online prend en charge l'accès délégué : il s'agit de la possibilité qu'ont des utilisateurs de permettre à d'autres de gérer leur messagerie électronique et calendriers. L'accès délégué s'utilise habituellement entre un gestionnaire et un assistant, où l'assistant traite les messages électroniques entrants du gestionnaire et coordonne le planning de ce dernier. L’accès délégué peut être activé par Exchange Online utilisateurs dans Outlook ou Outlook sur le web, ou par les administrateurs du Centre d’administration Exchange. 
  
Les délégués peuvent avoir deux types d'accès :
  
- **Autorisations Envoyer de la part de** Le délégué peut composer des messages électroniques et entrer le nom de l'autre personne dans le champ De :, là où est afficher « [Nom du délégué] de la part de [nom de la personne] ». 
    
- **Autorisations Envoyer en tant que** Le délégué peut envoyer des messages à partir de la boîte aux lettres de l'autre personne comme s'il en était le propriétaire. Il s'agit d'un scénario classique lorsque plusieurs employés envoient des messages électroniques à partir d'une boîte aux lettres partagée existante au lieu de leur propres comptes Exchange Online. 
    
Pour plus d'informations sur la délégation d'accès, voir [Gestion des autorisations pour les destinataires](/Exchange/recipients/mailbox-permissions).
  
### <a name="inbox-rules"></a>Règles de la boîte de réception

Exchange Online autorise des utilisateurs à créer des règles de boîte de réception qui exécutent automatiquement des actions spécifiques fondées sur des critères sur les messages à mesure qu'ils arrivent. Par exemple, il est possible de créer une règle pour que tout le courrier électronique envoyé à un certain groupe de distribution soit automatiquement déplacé vers un dossier spécifique. Les utilisateurs gèrent les règles de boîte de Outlook ou Outlook sur le web. Les administrateurs ont la possibilité de bloquer certains types de règles de boîte de réception en désactivant le transfert côté serveur et/ou des réponses automatiques côté serveur. Par exemple, la désactivation du transfert côté des messages électroniques côté serveur peut empêcher les utilisateurs de transférer automatiquement le courrier électronique vers des comptes personnels. De la même manière; la désactivation des réponses automatiques côté serveur permet d'empêcher des correspondants extérieurs d'utiliser ces réponses pour identifier des adresses de messagerie valides. Ces modifications sont effectuées via Windows PowerShell à distance.
  
### <a name="clutter"></a>Courrier non trié

La fonctionnalité de courrier non trié est conçue pour vous aider à vous concentrer sur les messages les plus importants dans votre boîte de réception. Elle utilise Machine Learning pour désencombrer votre boîte de réception en déplaçant les messages à priorité faible dans un nouveau dossier appelé Courrier basse priorité. La fonctionnalité de courrier non trié respecte vos règles de courrier électronique existantes. Ainsi, si vous avez créé des règles pour organiser vos messages électroniques, celles-ci continuent de s'appliquer et la fonctionnalité de courrier non trié n'effectuera aucune action sur ces messages. Le courrier non trié est désactivé par défaut pour votre boîte de réception. Pour plus d'informations, voir [Désencombrement de votre boîte aux lettres dans Office 365](https://go.microsoft.com/fwlink/?linkid=2144145).
  
### <a name="connected-accounts"></a>Comptes connectés

La fonctionnalité Comptes connectés permet aux utilisateurs Exchange Online de connecter des comptes de messagerie externes (tels que des comptes personnels) à leurs comptes de messagerie internes dans Exchange Online, puis d’utiliser Outlook sur le web pour interagir avec tous leurs messages au même endroit. Les comptes connectés se synchronisent automatiquement lors de la connexion à Outlook sur le web ; Les utilisateurs peuvent également synchroniser manuellement les comptes à partir Outlook sur le web. Les administrateurs peuvent activer et désactiver cette fonctionnalité pour des utilisateurs spécifiques ou tous les utilisateurs via [Exchange centre d’administration.](/exchange/exchange-admin-center)
  
### <a name="inactive-mailboxes"></a>Boîtes aux lettres inactives

Exchange Online offre la possibilité de conserver indéfiniment le contenu des boîtes aux lettres supprimées. Cette fonctionnalité est appelée boîtes aux lettres inactives. Une boîte aux lettres devient inactive quand un blocage local ou une mise en attente pour litige lui est appliqué avant sa suppression. Ainsi, le contenu de la boîte aux lettres est conservé indéfiniment. Les administrateurs, les responsables de la mise en conformité ou les responsables de l'enregistrement peuvent utiliser la fonctionnalité eDiscovery locale d'Exchange Online pour accéder au contenu d'une boîte aux lettres inactive.
  
Pour activer une boîte aux lettres inactive, cette dernière doit nécessairement faire l'objet d'une licence Exchange Online (plan 2) ou d'un abonnement à l'archivage Exchange Online pour qu'il soit possible de lui appliquer un blocage local ou une mise en attente pour litige avant sa suppression.
  
> [!IMPORTANT]
> Si un blocage n'est pas appliqué à une boîte aux lettres avant sa suppression, son contenu n'est ni conservé ni détectable. La boîte aux lettres peut être récupérée dans les 30 jours suivant sa suppression, mais, à défaut de récupération, elles est définitivement supprimée avec son contenu à l'issue de cette période. 
  
Pour plus d'informations, voir :
  
- [Gérer les boîtes aux lettres inactives dans Exchange Online](/microsoft-365/security/office-365-security/exchange-online-protection-overview)
    
- [Conservation inaltérable et conservation pour litige](/exchange/security-and-compliance/in-place-and-litigation-holds)
    
- [Découverte électronique locale](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)
    
## <a name="contacts-and-distribution-groups"></a>Contacts et groupes de distribution

### <a name="offline-address-book"></a>Carnet d'adresses en mode hors connexion

La fonctionnalité de carnet d’adresses en mode hors connexion fournit un instantané des informations Active Directory disponibles dans la Outlook d’adresses globale (LAL). Elle est cachée localement dans Outlook et devient accessible lorsqu'un utilisateur travaille en mode hors connexion.
  
### <a name="address-book-policies"></a>Stratégies de carnet d’adresses

Exchange Online prend en charge les stratégies de carnet d’adresses. Les stratégies de carnet d'adresses vous permettent de segmenter des utilisateurs en groupes spécifiques pour fournir des vues personnalisées de la liste d'adresses globale de votre organisation. Lorsque vous créez une stratégie de carnet d'adresses, vous affectez une LAG, un carnet d'adresses en mode hors connexion, une liste de pièces ainsi qu'une ou plusieurs listes d'adresses à la stratégie. Vous pouvez ensuite affecter la ABP aux utilisateurs de boîtes aux lettres, en leur donnant accès à une liste d’adresses réseau personnalisée dans Outlook et Outlook sur le web. Les administrateurs peuvent configurer les stratégies de carnet d'adresses à l'aide de l'application Windows PowerShell distante. Pour en savoir plus sur les stratégies de carnet d'adresses, voir [Carnets d'adresses dans Exchange Online](/exchange/address-books/address-books).
  
### <a name="address-lists"></a>Listes d'adresses

Exchange Online prend en charge la personnalisation des listes d’adresses et des listes d’adresses générales. Une liste d’adresses réseau est un répertoire à l’échelle de l’organisation de tous les utilisateurs à messagerie, groupes de distribution et contacts externes. Les administrateurs peuvent masquer les utilisateurs, les groupes de distribution et les contacts de la liste d’administration générale à l’aide de l’outil de synchronisation d’annuaires ou de Windows PowerShell.
  
### <a name="hierarchical-address-books"></a>Carnets d’adresses hiérarchiques

 Les carnets d’adresses hiérarchiques permettent aux utilisateurs finals de rechercher des destinataires au sein de leur organisation Exchange à l’aide d’une hiérarchie d’organisation. Les administrateurs peuvent personnaliser le carnet d'adresses par ancienneté et par rang plutôt que par listes alphabétiques. 
  
### <a name="distribution-groups-global"></a>Groupes de distribution (globaux)

Un groupe de distribution (ou liste de distribution) est un ensemble d'utilisateurs, de contacts et d'autres groupes de distribution qui sont accessibles à tous les utilisateurs au sein d'une entreprise. Les utilisateurs adressent le courrier électronique à un alias du groupe de distribution pour envoyer des messages à toutes les personnes figurant dans le groupe. Les groupes de distribution sont semblables à des groupes de distribution personnels que des individus créent dans Outlook, seules leurs listes de membres sont globalement accessibles à l'entreprise. Les administrateurs créent les groupes de distribution dans le Centre d'administration Exchange. Les groupes peuvent également être synchronisés avec Exchange Online à partir d'Active Directory local. Elles apparaissent dans lat d’Outlook. Exchange Online prend en charge des fonctionnalités avancées de groupe de distribution, y compris celles décrites ci-dessous :
  
- **Groupes de distribution restreints** Par défaut, toute personne peut envoyer des messages électroniques à un groupe de distribution. Les administrateurs ont la possibilité de modifier des autorisations pour permettre à seulement des individus spécifiques d'envoyer des messages électroniques à un groupe particulier : par exemple, pour décourager toute utilisation inappropriée de listes étendues de distribution. Les administrateurs peuvent également bloquer l'envoi de messages électroniques par des sources externes à des groupes de distribution afin de prévenir les courriers indésirables. S'agissant des groupes de distribution synchronisés à partir d'Active Directory local à l'aide de l'outil de synchronisation d'annuaire, les attributs relatifs à la restriction sont synchronisés sur le cloud automatiquement. Pour plus d'informations, voir [Gestion des groupes de distribution](/Exchange/recipients/distribution-groups).
    
- **Groupes de distribution dynamique** La liste d'appartenance pour un groupe de distribution dynamique (également appelé liste de distribution dynamique ou liste de distribution fondée sur une requête) est calculée chaque fois qu'un message est envoyé à ce groupe. Ce calcul est effectué en fonction des filtres et conditions définis par l'administrateur. Ils sont gérés dans Exchange Online via Windows PowerShell à distance. Pour plus d'informations sur les groupes de distribution dynamique, voir [Gestion des groupes de distribution dynamique](/Exchange/recipients/dynamic-distribution-groups/dynamic-distribution-groups).
    
    > [!IMPORTANT]
    > L'outil de synchronisation d'annuaire d'Office 365 ignore les groupes de distribution dynamique figurant dans Active Directory local et ne les synchronise pas dans Exchange Online. Les organisations qui utilisent l'outil de synchronisation d'annuaire doivent utiliser une convention d'affectation de noms qui écarte les conflits entre les groupes de distribution régulier qui sont gérés localement et les groupes de distribution dynamiques qui sont gérés sous Exchange Online. 
  
- **Groupes de distribution modérés** Les administrateurs peuvent sélectionner un modérateur pour réguler le flux des messages destinés à un groupe de distribution. Les groupes de distribution avec modérateur permettent à toute personne d'adresser un courrier électronique à l'alias du groupe de distribution, sauf qu'avant d'être remis aux membres du groupe, un modérateur doit consulter le message et l'approuver. Pour plus d'informations sur la modération, voir la section relative à l'approbation de messages de l'article [Gestion des groupes de distribution](/Exchange/recipients/distribution-groups).
    
- **Groupes de distribution en libre-service** Les administrateurs peuvent permettre aux utilisateurs de gérer leur propre appartenance à des groupes de distribution à partir d'une interface web. Les utilisateurs peuvent avoir la permission de créer, supprimer, rejoindre ou quitter des groupes de distribution. Ces fonctionnalités sont activées par défaut pour tous les utilisateurs d'Exchange Online. Les administrateurs peuvent les désactiver pour que seul le service informatique puisse gérer des groupes de distribution, si nécessaire. Ils peuvent également créer des stratégies de noms visant à normaliser et à gérer les noms des groupes de distribution que leurs utilisateurs créent. Par exemple, ils peuvent ajouter un préfixe ou un suffixe au nom du groupe de distribution lorsqu'il est créé ou bloquer l'usage de mots spécifiques dans le nom de groupe. 
    
    > [!IMPORTANT]
    > Des fonctionnalités en libre-service ne sont pas disponibles pour des groupes de distribution synchronisés à partir d'Active Directory local avec Exchange Online. Les organisations qui appliquent l'outil de synchronisation d'annuaire doivent utiliser une convention d'affectation de noms qui écarte les conflits entre des groupes de distribution gérés localement et des groupes de distribution gérés dans le cloud. 
  
### <a name="external-contacts-global"></a>Contacts externes (globaux)

Un contact externe est un enregistrement contenant des informations sur une personne qui travaille en dehors d'une organisation donnée. Les contacts externes sont semblables à des contacts personnels que des individus créent dans Outlook ; ils ne sont accessibles que globalement à l'entreprise. Les administrateurs créent des contacts externes à l'aide du Centre d'administration Exchange ou via l'application Windows PowerShell distante. Ces contacts peuvent également être synchronisés avec Exchange Online à partir d'Active Directory local. Elles apparaissent dans lat d’Outlook.
  
Pour plus d'informations sur les contacts externes, voir [Créer une relation d'organisation dans Exchange Online](/exchange/sharing/organization-relationships/create-an-organization-relationship).
  
## <a name="calendar-and-scheduling"></a>Calendrier et planification

### <a name="resource-mailboxes"></a>Boîtes aux lettres de ressources

Les boîtes aux lettres de ressources (comme celles dédiées aux salles de conférence ou aux équipements physiques) représentent les salles de réunions ou d'autres installations ou ressources. Les utilisateurs peuvent réserver des salles ou des ressources en ajoutant l’alias de messagerie de la ressource aux demandes de réunion Outlook ou Outlook sur le web. Les salles de conférence et les ressources apparaissent dans lat de Outlook et Outlook sur le web.
  
Les administrateurs créent des boîtes aux lettres de ressources à l'aide du Centre d'administration Exchange ou de l'application Windows PowerShell distante. Les boîtes aux lettres peuvent également être synchronisées avec Exchange Online à partir d'Active Directory local.
  
Pour plus d'informations sur les boîtes aux lettres de ressources, voir :
  
- [Création et gestion des boîtes aux lettres de salle](/Exchange/recipients/room-mailboxes)
    
- [Gérer les boîtes aux lettres d’équipement](/Exchange/recipients/equipment-mailboxes)
    
### <a name="conference-room-management"></a>Gestion des salles de conférence

Exchange Online inclut l'Assistant Réservation de ressources qui automatise la planification des salles de conférence et d'autres ressources. Une boîte aux lettres de ressources configurée avec l'Assistant Réservation de ressources accepte, refuse ou accuse réception des demandes de réunion émises par l'organisateur de la réunion en fonction des disponibilités figurant sur le calendrier de la ressource. 
  
Les administrateurs peuvent personnaliser les réponses automatisées aux salles de conférence et configurer des stratégies de réservation Outlook sur le web. Ces stratégies incluent les critères suivants : qui peut planifier la ressource, quand elle peut être planifiée, quelles informations relatives à la réunion sont visibles sur le calendrier de la ressource et quel pourcentage de conflits est autorisé. Les administrateurs ont la possibilité de désactiver l'Assistant Réservation de ressources et d'affecter à des utilisateurs spécifiques la gestion manuelle des demandes de réunion associées à des salles de conférence.
  
Les administrateurs doivent définir et gérer les paramètres de l'Assistant Réservation de ressources via Windows PowerShell à distance.
  
### <a name="out-of-office-replies"></a>Réponses avec notification d'absence du bureau

Les messages de notification d'absence du bureau sont des réponses automatiques à des messages entrants qu'Exchange Online envoie pour le compte d'un utilisateur. Les utilisateurs peuvent planifier des messages de notification d'absence du bureau avec des heures de début et de fin spécifiques et configurer des messages de notification d'absence du bureau distincts adressés aux destinataires internes ou externes. Ils peuvent également définir des messages de notification d'absence du bureau à partir d'appareils mobiles prenant en charge Exchange ActiveSync. La reconnaissance des courriers indésirables et des listes de mailing au sein d'Exchange Online empêche l'envoi par les utilisateurs de messages de notification d'absence du bureau sur des listes de mailing étendues et auprès d'expéditeurs potentiels de courrier indésirable. Les administrateurs peuvent également empêcher les utilisateurs d'envoyer des messages de notification d'absence du bureau à des utilisateurs externes via Windows PowerShell à distance.
  
### <a name="calendar-sharing"></a>Partage du calendrier

Les utilisateurs peuvent partager leur calendrier personnel selon l'une des deux manières suivantes :
  
- **Partage de calendrier fédéré** La fédération fait référence à l’infrastructure d’confiance sous-jacente qui prend en charge le partage fédéré, une méthode simple pour les utilisateurs Exchange partager des données de calendrier de libre/occupé et des informations de contact avec des destinataires dans d’autres organisations fédérées externes. Cela inclut Exchange Online organisations ou organisations exécutant Exchange Server 2010 ou Exchange Server 2013 en local. Exchange Online administrateurs n’ont pas besoin de configurer une relation d’Microsoft Federation Gateway car cette confiance est pré-configurée pour tous les clients Exchange Online lors de la création du service Microsoft. Une stratégie de partage par défaut permet aux utilisateurs d’envoyer des invitations de partage de calendrier Outlook sur le web ou Outlook 2010. Les administrateurs utilisent des Windows PowerShell pour désactiver cette stratégie ou pour configurer le niveau de données de calendrier de libre/occupé que les utilisateurs peuvent partager. Les administrateurs peuvent également créer une relation organisation-organisation avec une autre organisation fédérée, ce qui permet au niveau souhaité d’informations de libre/occupé pour chaque utilisateur d’être visible entre les organisations sans qu’il soit nécessaire pour des utilisateurs individuels d’effectuer une invitation de partage. Dans le cadre des stratégies de partage définies par l’administrateur et/ou des relations organisation-organisation, les utilisateurs peuvent limiter individuellement les détails de leur partage. 
    
- **Partage de calendrier Internet** Exchange Online permet à ses utilisateurs de publier leurs calendriers au format iCal pour un accès anonyme par toute personne intérieure ou extérieure à l'organisation. Les destinataires peuvent utiliser Exchange, une autre plate-forme ou tout simplement un navigateur Web. Exchange Online utilisateurs peuvent également s’abonner à des calendriers que d’autres ont publiés sur des emplacements Internet via iCal. Ce partage de calendrier personnel diffère du partage de calendrier fédéré qui est configuré par un administrateur, et fournit un partage disponible/occupé d'organisation à organisation. Aucun utilisateur ne peut publier de données de calendrier au format iCal tant que l’administrateur n’a pas définie et appliqué une stratégie de partage qui l’autorise. Les administrateurs peuvent désactiver la publication iCal et des abonnements iCal pour des utilisateurs d'une organisation à l'aide de Windows PowerShell à distance.
    
Pour plus d'informations sur le partage fédéré, consultez la rubrique [Partage dans Exchange Online](/exchange/sharing/sharing).
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 - Recherche de salles

Exchange Online prend en charge la fonctionnalité Recherche de salles d'Outlook 2010, qui range les salles dans des listes (par exemple, une liste intitulée « Bâtiment à 5 salles ») afin de faciliter la recherche d'une salle à proximité lors de la planification d'une réunion. Pour apparaître dans la liste de salles, un groupe de distribution doit être spécifiquement marqué selon l'une des deux méthodes : 
  
- Il est possible de créer une liste de salles à l'aide de Windows PowerShell à distance. 
    
- Tout groupe de distribution qui ne contient que des salles peut être converti en une liste de salles via Windows PowerShell à distance.
    
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir [Exchange Online description du service.](exchange-online-service-description.md)
