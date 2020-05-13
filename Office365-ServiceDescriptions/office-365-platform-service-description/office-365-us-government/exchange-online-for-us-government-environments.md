---
title: Exchange Online pour les environnements gouvernementaux américains
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Cet article fournit une vue d’ensemble des différences de fonctionnalités entre le nuage des États-Unis et le nuage commercial, comme décrit dans la description du service Exchange Online.
ms.openlocfilehash: b2ea792f6a205cbe6c9031c924a22e7f6d1d3030
ms.sourcegitcommit: 1a212a9f9c8d28090bc0b7c6e20e76d1353dad2e
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/13/2020
ms.locfileid: "44213696"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online pour les environnements gouvernementaux américains

Cet article fournit une vue d’ensemble des différences de fonctionnalités entre le nuage des États-Unis et le nuage commercial, comme décrit dans la [Description du service Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description). Exchange Online est disponible pour les environnements de la communauté gouvernementale (GCC), GCC High et Department of Defense (DoD).

Pour plus d’informations sur le Cloud du gouvernement, y compris l’éligibilité et les achats, voir [Microsoft 365 Government-Comment acheter](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Pour comparer les plans gouvernementaux Office 365, consultez la rubrique [office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Pour en savoir plus sur les points de terminaison requis lors de la gestion de la connectivité réseau, reportez-vous aux points de [terminaison GCC High office 365 du gouvernement des États-Unis](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)   ou [Office 365](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

En plus de profiter des fonctionnalités et des fonctionnalités d’Office 365, les organisations bénéficient des fonctionnalités suivantes, propres aux environnements Cloud du gouvernement américain :

- Le contenu client de votre organisation est logiquement séparé du contenu client des services Office 365.

- Le contenu client de votre organisation est stocké au repos aux États-Unis.

- L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.

- Les environnements de Cloud du gouvernement sont conformes aux certifications et accréditations généralement requises pour les clients du secteur public américain.

Il est de notre intention générale de fournir toutes les fonctionnalités et fonctionnalités Exchange commerciales à l’environnement Cloud du gouvernement. Ceci étant, certaines fonctionnalités ne sont pas disponibles en raison des exigences des clients du nuage public. D’autres fonctionnalités sont disponibles dans les environnements gouvernementaux, mais ne sont pas encore disponibles. Reportez-vous aux sections suivantes pour en savoir plus sur la disponibilité des fonctionnalités dans les environnements Cloud du gouvernement.

## <a name="exchange-online-features"></a>Fonctionnalités d’Exchange Online 

Le tableau suivant décrit si les fonctionnalités Exchange Online spécifiées sont disponibles dans les environnements GCC, GCC High et DoD. Lorsqu’il existe des nuances concernant la déclaration de la prise en charge (ou une absence), un contexte supplémentaire est fourni.

|**Fonctionnalités**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|:-----|:-----|:-----|:-----|:-----|
|**[Planification et déploiement](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Déploiement hybride pris en charge|Oui|Oui|Oui|Pour la coexistence avec Exchange Server en local, Microsoft requiert l’installation d’au moins un serveur d’accès au client Exchange Server 2013 (ou Exchange Server 2016). Exchange Server 2010 et les versions antérieures ne sont pas pris en charge.|
|Migration IMAP prise en charge|Oui|Oui|Oui||
|Migration à basculement prise en charge|Oui|Oui|Oui||
|Migration intermédiaire prise en charge|Oui|Oui|Oui|La migration GSuite n’est pas prise en charge pour GCC High et DoD. Pour plus d’informations, consultez <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">la rubrique effectuer une migration GSuite</a>.|
|**[Autorisations](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Autorisations basées sur des rôles|Oui|Oui|Oui||
|Groupes de rôles|Oui|Oui|Oui||
|Stratégies d'attribution de rôle|Oui|Oui|Oui||
|**[Stratégie et conformité de message](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Archivage de boîtes aux lettres Exchange Online|Oui|Oui|Oui||
|Archivage en nuage de boîtes aux lettres locales|Oui|Oui|Oui||
|Messaging Records Management (MRM) |Oui|Oui|Oui||
|Stratégies, étiquettes et balises de rétention manuelles |Oui|Oui|Oui||
|Chiffrement des données statiques (BitLocker)|Oui|Oui|Oui||
|IRM avec Azure Information Protection|Oui|Oui|Oui|Pour plus d’informations sur les limitations du AIP dans GCC High et DoD, voir <a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Description du service Azure information protection Premium</a>.<br><br>Azure information protection n’est pas inclus dans G1/F3, mais il peut être acheté en tant que module complémentaire distinct et permet d’activer les fonctionnalités de gestion des droits relatifs à l’information (IRM) prises en charge. Certaines fonctionnalités Azure information protection nécessitent un abonnement à Office 365 ProPlus, qui n’est pas inclus dans Office 365 gouvernement G1 ou Office 365 gouvernement F3.|
|IRM via Windows Server AD RMS|Oui|Oui|Oui|Windows Server AD RMS est un serveur local qui doit être acheté et géré séparément afin d’activer les fonctionnalités IRM prises en charge.|
|Chiffrement de messages Office 365|Oui|Oui|Oui|Voir [comportement de chiffrement des messages office 365 sur les limites de la haute/DoD de GCC](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) dans cet article et les <a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">caractéristiques du chiffrement de messages Office 365 dans un déploiement de GCC High</a>, qui documentent le chiffrement des messages Office 365 lors de l’envoi de messages entre les utilisateurs de GCC High/DOD et non GCC High/DoD.|
|Clé client|Oui|Oui|Oui|Nécessite un plan de service G5.|
|S/MIME|Oui|Oui|Oui||
|Conservation inaltérable et conservation pour litige|Oui|Oui|Oui|Nécessite un plan de service G3 ou G5.|
|Découverte électronique locale|Oui|Oui|Oui||
|Règles de flux de messagerie|Oui|Oui|Oui||
|Protection contre la perte de données|Oui|Oui|Oui|Nécessite un plan de service G3 ou G5.|
|Journalisation|Oui|Oui|Oui||
|**[Protection contre le courrier indésirable et les programmes malveillants](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Protection anti-courrier indésirable intégrée|Oui|Oui|Oui||
|Customize anti-spam policies|Oui|Oui|Oui||
|Protection anti-programme malveillant intégrée|Oui|Oui|Oui||
|Customize anti-malware policies|Oui|Oui|Oui||
|Quarantaine - gestion par l'administrateur|Oui|Oui|Oui||
|Quarantaine - autogestion par l'utilisateur final|Oui|Oui|Oui||
|Protection avancée contre les menaces|Oui|Oui|Oui|Nécessite un plan de service G5 (ou un achat de module complémentaire).<br><br>La protection anti-hameçonnage pour l’emprunt d’identité d’utilisateur et de domaine et l’aide à l’usurpation n’est pas encore disponible dans GCC High et DoD.|
|**[Flux de messagerie](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Routage personnalisé du courrier sortant|Oui|Oui|Oui||
|Secure messaging with a trusted partner|Oui|Oui|Oui||
|Conditional mail routing|Oui|Oui|Oui||
|Ajout d’un partenaire à une liste sécurisée entrante|Oui|Oui|Oui||
|Routage de messagerie hybride|Oui|Oui|Oui||
|**[Destinataires](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Alertes de capacité|Oui|Oui|Oui||
|Courrier non trié|Oui|Oui|Oui||
|MailTips|Oui|Oui|Oui||
|Accès délégué|Oui|Oui|Oui||
|Règles de la boîte de réception|Oui|Oui|Oui||
|Comptes connectés|Oui|Non|Non|Cette fonctionnalité n’est pas prise en charge dans GCC High ou DoD en raison de restrictions sur les connexions sortantes vers des services tiers. Pour plus d’informations sur les fonctionnalités affectées, consultez la rubrique [Connectivity with tiers services](#connectivity-with-third-party-services) dans cet article.|
|Boîtes aux lettres inactives|Oui|Oui|Oui|Nécessite un plan de service G3 ou G5.|
|Carnet d'adresses en mode hors connexion|Oui|Oui|Oui||
|Stratégies de carnet d’adresses|Oui|Oui|Oui||
|Carnet d'adresses hiérarchique|Oui|Oui|Oui||
|Listes d’adresses et liste d’adresses globale|Oui|Oui|Oui||
|Groupes Office 365|Oui|Oui|Oui|L’accès invité aux groupes Office 365 n’est pas pris en charge dans les environnements GCC High et DoD. Pour plus d’informations, consultez la rubrique <a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure Governance Security + Identity</a>.|
|Groupes de distribution|Oui|Oui|Oui||
|Contacts externes (globaux)|Oui|Oui|Oui|Soumis aux limitations de collaboration de relation d’organisation dans les environnements GCC High et DoD. |
|Liaison de contacts avec les réseaux sociaux|Oui|Non|Non|Cette fonctionnalité n’est pas prise en charge dans GCC High ou DoD.|
|Boîtes aux lettres de ressources|Oui|Oui|Oui||
|Gestion des salles de conférence|Oui|Oui|Oui||
|Réponses d’absence du Bureau|Oui|Oui|Oui||
|Partage de calendriers Internet|Oui|Non|Non|Dans GCC High, le partage/la publication de calendrier Internet fonctionne pour la connexion entrante aux calendriers partagés par les utilisateurs de GCC High, mais pas pour les utilisateurs très élevés qui se connectent à un calendrier partagé en dehors de GCC High.<br><br>En DoD, le partage de calendrier Internet n’est pas pris en charge en raison de la condition requise pour la liste des connexions entrantes/sortantes autorisées dans cet environnement.|
|**[Fonctions de rapport et outils de dépannage](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Rapports du centre d’administration Microsoft 365|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à la section fonctionnalités de la <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">plateforme</a> de la description du service Office 365 pour le gouvernement américain pour les mises à jour/disponibilité actuelle.|
|Rapports de services Web|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à la section fonctionnalités de la <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">plateforme</a> de la description du service Office 365 pour le gouvernement américain pour les mises à jour/disponibilité actuelle.|
|Message trace|Oui|Oui|Oui||
|Rapports d’audit|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à la section fonctionnalités de la <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">plateforme</a> de la description du service Office 365 pour le gouvernement américain pour les mises à jour/disponibilité actuelle.|
|Rapports de messagerie unifiée|Oui|Non|Non||
|**[Partage et collaboration](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Partage fédéré (y compris la publication de calendrier)|Oui|Oui|Oui|Il existe des limitations à la fois de GCC High et DoD. Consultez la rubrique [Fédération de disponibilité](#freebusy-federation) dans cet article.|
|Boîtes aux lettres de site|Oui|Oui|Oui||
|Dossiers publics|Oui|Oui|Oui||
|**[Clients et appareils mobiles](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Outlook pour Windows|Oui|Oui|Oui|Pour répondre aux exigences de conformité à GCC High and DoD, vous devez exécuter au moins la version 1803 d’Office 365 ProPlus. Office 365 ProPlus n’est pas inclus dans G1 ou F3.|
|Outlook sur le web|Oui|Oui|Oui||
|Outlook pour Mac|Oui|Oui|Oui|Pour répondre aux exigences de conformité à GCC High and DoD, vous devez exécuter au moins la version 1803 d’Office 365 ProPlus. Office 365 ProPlus n’est pas inclus dans G1 ou F3.|
|Outlook pour iOS et Android|Oui|Oui|Oui||
|Exchange ActiveSync|Oui|Oui|Oui||
|Gestion des appareils mobiles pour Office 365|Oui|Oui|Oui||
|POP et IMAP|Oui|Oui|Oui||
|SMTP|Oui|Oui|Oui||
|Prise en charge des applications EWS|Oui|Oui|Oui||
|**[Services de messagerie vocale](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Messagerie vocale|Non|Non|Non|L’intégration des systèmes IP-PBX locaux avec la messagerie unifiée Exchange Online n’est pas prise en charge.|
|Intégration entre la messagerie vocale et la télécopie tierce|Non|Non|Non|L’intégration des systèmes IP-PBX locaux avec la messagerie unifiée Exchange Online n’est pas prise en charge.|
|Interopérabilité avec messagerie vocale tierce|Non|Non|Non|L’intégration des systèmes IP-PBX locaux avec la messagerie unifiée Exchange Online n’est pas prise en charge.|
|Intégration Skype entreprise|Oui|Oui|Oui||
|**[Haute disponibilité et continuité de service](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Réplication de boîtes aux lettres dans les centres de réplication|Oui|Oui|Oui||
|Récupération de boîtes aux lettres supprimées|Oui|Oui|Oui||
|Récupération d'éléments supprimés|Oui|Oui|Oui||
|Récupération d'élément unique|Oui|Oui|Oui||
|**[Interopérabilité, connectivité et compatibilité](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Présence dans OWA et Outlook|Oui|Oui|Oui||
|Interopérabilité SharePoint|Oui|Oui|Oui||
|Prise en charge de la connectivité EWS|Oui|Oui|Oui||
|Prise en charge du relais SMTP|Oui|Oui|Oui||
|**[Configuration et administration d’Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Accès au portail Microsoft Office 365|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à la section fonctionnalités de la <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">plateforme</a> de la description du service Office 365 pour le gouvernement américain pour les mises à jour/disponibilité actuelle.|
|Accès au centre d’administration Microsoft 365|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à la section fonctionnalités de la <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">plateforme</a> de la description du service Office 365 pour le gouvernement américain pour les mises à jour/disponibilité actuelle.|
|Accès au Centre d'administration Exchange|Oui|Oui|Oui||
|Accès à Windows PowerShell à distance|Oui|Oui|Oui||
|Stratégies ActiveSync pour les appareils mobiles|Oui|Oui|Oui||
|Rapports d’utilisation|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à la section fonctionnalités de la <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">plateforme</a> de la description du service Office 365 pour le gouvernement américain pour les mises à jour/disponibilité actuelle.|
|**[Extension du service-personnalisation, compléments et ressources](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**Considérations clés**|
|Compléments Outlook et MAPI Outlook|Oui|Oui|Oui|Seuls certains compléments OWA et Outlook sont disponibles dans GCC High et DoD. Consultez la rubrique [compléments dans Outlook et Outlook Web App](#add-insin-outlook-and-outlook-web-app) dans cet article.|

## <a name="feature-nuances-within-gcc-high-and-dod-environment"></a>Nuance de la fonctionnalité dans les environnements GCC High et DoD

### <a name="connectivity-with-third-party-services"></a>Connectivité avec des services tiers  

Les environnements GCC High et DoD sont tous deux des environnements restreints qui nécessitent une approbation et une configuration explicites des connexions sortantes. De plus, Microsoft ne peut pas prendre en charge les demandes d’autorisation d’accès sortant à partir de ces environnements dans les services Cloud commerciaux (Office 365, Google GSuite, les services Web Amazon, etc.).     

En raison de ces restrictions, les fonctionnalités qui dépendent de cette connectivité sortante des environnements GCC High/DoD ne sont généralement pas prises en charge, notamment : 

- Comptes connectés &mdash; les utilisateurs ne peuvent pas ajouter/synchroniser des comptes (Google, POP/IMAP, etc.). 

- Prise en charge des fournisseurs de stockage de fichiers tiers &mdash; seul le compte OneDrive entreprise de l’utilisateur *au sein de GCC High/DoD*est   accessible à partir des différents clients Outlook pour joindre ou partager des fichiers. Les comptes de stockage tiers (Dropbox, zone, Google Drive) ne peuvent pas être ajoutés. 

- La connectivité avec les réseaux sociaux, comme Facebook ou LinkedIn. 

### <a name="azure-active-directoryb2b-collaboration"></a>Collaboration B2B Azure Active Directory 

La collaboration B2B Azure Active Directory est actuellement prise en charge uniquement entre les organisations qui se trouvent à la fois dans le nuage du gouvernement américain Azure et qui prennent en charge la collaboration B2B.

En outre, les utilisateurs B2B en tant qu’invités dans les groupes Office 365 ne sont pas pris en charge dans les environnements GCC High et DoD. 

Pour plus d’informations et pour obtenir les dernières mises à jour, reportez-vous à la rubrique [Azure Governance + Identity](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity). 

### <a name="office-365-message-encryptionbehavior-across-gcc-highdod-boundary"></a>Comportement de chiffrement des messages Office 365 entre les limites de la norme GCC High/DoD 

Si vous utilisez le chiffrement de messages Office 365 dans un environnement de GCC High, tenez compte de ces caractéristiques uniques concernant l’expérience de destinataire :  

- Lors de l’envoi de messages chiffrés de GCC High ou DoD à des destinataires dans le même environnement :
    
    - Les expéditeurs peuvent chiffrer manuellement les courriers électroniques dans Outlook pour PC et Mac et Outlook sur le Web, ou les organisations peuvent configurer une stratégie pour chiffrer les messages électroniques à l’aide des règles de flux de messagerie Exchange. 
    
    - Les destinataires au sein de GCC High/DoD reçoivent la même expérience de lecture incorporée dans Outlook pour PC et Mac et Outlook sur le Web que tous les autres utilisateurs d’Office 365. 

<!-- end list -->

- Lors de l’envoi de messages chiffrés de GCC High ou DoD à des destinataires en dehors de cet environnement (notamment GCC et commercial) :
    
    - Les expéditeurs au sein de GCC High/DoD peuvent envoyer des messages chiffrés en dehors des limites de GCC High/DoD. 
    
    - Tous les destinataires en dehors de GCC High/DoD, y compris les utilisateurs Office 365 commerciaux, les utilisateurs Outlook.com et d’autres utilisateurs d’autres fournisseurs de courrier, reçoivent un message de wrapper. Ce message de wrapper redirige le destinataire vers le portail OME où le destinataire peut lire le message et y répondre. 

Pour plus d’informations et pour obtenir les dernières mises à jour, reportez-vous à la rubrique [compare versions of OME](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide).

### <a name="freebusy-federation"></a>Fédération de disponibilité

Le partage fédéré, y compris les informations de disponibilité, est actuellement soumis à plusieurs limitations importantes dans les environnements GCC High et DoD.

Dans l’environnement de GCC High :

- L’approbation de Fédération (y compris le partage de disponibilité bidirectionnel) est prise en charge entre les clients au sein de GCC haute et via une coexistence hybride (Exchange 2013 ou version ultérieure).

- Le partage fédéré n’est pas pris en charge entre les locataires dans GCC High et GCC ou Office 365 commercial. Les connexions sortantes de l’environnement de GCC High vers les nuages commerciaux (notamment GCC et Office 365 commercial) ne sont pas autorisées pour le moment. Par conséquent, les utilisateurs de GCC Highs ne peuvent pas faire la demande sortante requise à GCC/commercial pour accéder aux informations de calendrier partagées.

Dans l’environnement DoD :

  - L’approbation de Fédération (y compris le partage de disponibilité) est actuellement prise en charge uniquement entre les clients au sein de l’environnement DoD. Elle n’est pas prise en charge entre les clients DoD et les clients GCC ou commercial.

### <a name="client-configuration"></a>Configuration du client 

Des étapes supplémentaires sont impliquées dans le déploiement et la configuration d’Office ProPlus (y compris Outlook). Pour obtenir une description détaillée de ces étapes, consultez les [conseils pour le déploiement d’applications Microsoft 365 pour Enterprise dans un environnement GCC High ou DoD ](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook pour iOS et Android est également disponible pour les environnements GCC High et DoD. Pour en savoir plus sur les limitations et la gestion des fonctionnalités dans ces environnements, consultez [la rubrique utilisation d’Outlook pour iOS et Android dans le nuage communautaire du gouvernement](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud).

### <a name="add-insin-outlook-and-outlook-web-app"></a>Compléments dans Outlook et Outlook Web App  

Seuls certains compléments OWA et Outlook sont disponibles dans GCC High et DoD. Mes modèles et réunions suggérées sont disponibles et devraient fonctionner. Seuls les cinq compléments OWA par défaut sont pris en charge. L’intégration avec des applications tierces est possible, toutefois, ces intégrations ne sont pas couvertes par les promesses de conformité de Microsoft pour GCC High ou DoD. Les clients doivent se familiariser avec les pratiques de gestion de données tierces et les promesses de conformité avant de configurer le module complémentaire pour leur organisation.
