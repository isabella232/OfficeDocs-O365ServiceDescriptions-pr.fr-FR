---
title: Exchange Online pour les environnements pour le gouvernement américain
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Cet article fournit une vue d’ensemble des différences de fonctionnalités entre le cloud du gouvernement américain et le cloud commercial, comme indiqué dans la description Exchange Online service.
ms.openlocfilehash: 2845e26e40552f364d2f8f6a0ec2746d35e13330
ms.sourcegitcommit: 0ef110d0f0a11c1943560373e0f022364053640c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/28/2021
ms.locfileid: "59986130"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online pour les environnements pour le gouvernement américain

Cet article fournit une vue d’ensemble des différences de fonctionnalités entre le cloud du gouvernement des États-Unis et le cloud commercial, comme indiqué dans la [description Exchange Online service.](../../exchange-online-service-description/exchange-online-service-description.md) Exchange Online est disponible pour les environnements Cloud de la communauté du secteur public (Cloud de la communauté du secteur public), Cloud de la communauté du secteur public High et Department of Defense (DoD).

Pour plus d’informations sur le cloud du gouvernement, notamment sur les conditions d’éligibilité et les achats, [voir Microsoft 365 Gouvernement -](./microsoft-365-government-how-to-buy.md)comment acheter . Pour comparer les Office 365 Secteur Public, voir [Office 365 Secteur Public plans.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Pour en savoir plus sur les points de terminaison requis lors de la gestion de la connectivité réseau, voir [Office 365 U.S. Government Cloud de la communauté du secteur public High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) or [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

En plus de profiter des fonctionnalités et des fonctionnalités de Office 365, les organisations bénéficient des fonctionnalités suivantes propres aux environnements cloud du gouvernement des États-Unis :

- Le contenu client de votre organisation est logiquement séparé du contenu client dans les services Office 365 commerciaux.

- Le contenu client de votre organisation est stocké au repos aux États-Unis.

- L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.

- Les environnements cloud du secteur public sont conformes aux certifications et accréditations souvent requises pour les clients du secteur public américain.

Nous avons l’intention générale de fournir toutes les fonctionnalités Exchange commerciales et commerciales à l’environnement cloud du secteur public. Cela dit, certaines fonctionnalités ne sont pas disponibles en raison des exigences des clients cloud du gouvernement. D’autres fonctionnalités sont disponibles dans les environnements du secteur public, mais ne sont pas encore disponibles. Reportez-vous aux sections suivantes pour en savoir plus sur la disponibilité des fonctionnalités dans les environnements cloud du secteur privé.

## <a name="exchange-online-features"></a>Fonctionnalités d’Exchange Online 

Le tableau suivant indique si des fonctionnalités Exchange Online spécifiées sont disponibles dans les environnements Cloud de la communauté du secteur public, Cloud de la communauté du secteur public High et DoD. Lorsqu’il existe des nuances concernant la déclaration de prise en charge (ou son absence), un contexte supplémentaire est fourni.<br><br>

| Fonctionnalité | GCC | GCC High | DoD | Considérations clés |
|:-----|:-----|:-----|:-----|:-----|
|**[Planification et déploiement](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Déploiement hybride pris en charge|Oui|Oui|Oui|Pour la coexistence avec Exchange Server sur site, Microsoft nécessite l’installation d’au moins un serveur d’accès au client Exchange Server 2013 (ou Exchange Server 2016). Exchange Server 2010 et les antérieures ne sont pas pris en charge.|
|Migration IMAP prise en charge|Oui|Oui|Oui||
|Migration à basculement prise en charge|Oui|Oui|Oui||
|Migration intermédiaire prise en charge|Oui|Oui|Oui|La migration GSuite n’est pas prise en charge pour Cloud de la communauté du secteur public High et DoD. Pour plus d’informations, <a href="/exchange/mailbox-migration/perform-g-suite-migration">voir Effectuer une migration GSuite.</a>|
|**[Autorisations](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Autorisations basées sur des rôles|Oui|Oui|Oui||
|Groupes de rôles|Oui|Oui|Oui||
|Stratégies d'attribution de rôle|Oui|Oui|Oui||
|**[Stratégie et conformité de message](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Archivage de boîtes aux lettres Exchange Online|Oui|Oui|Oui||
|Archivage en nuage de boîtes aux lettres locales|Oui|Oui|Oui||
|Messaging Records Management (MRM) |Oui|Oui|Oui||
|Stratégies, étiquettes et balises de rétention manuelle |Oui|Oui|Oui||
|Chiffrement des données statiques (BitLocker)|Oui|Oui|Oui||
|IRM avec Azure Information Protection|Oui|Oui|Oui|Pour plus d’informations sur les limitations d’AIP dans Cloud de la communauté du secteur public High et DoD, voir <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government Service Description</a>.<br><br>Azure Information Protection n’est pas inclus dans G1/F3, mais il peut être acheté en tant que module complémentaire distinct et activera les fonctionnalités de gestion des droits de l’information (IRM) prise en charge. Certaines fonctionnalités Azure Information Protection nécessitent un abonnement à Office 365 ProPlus, qui n’est pas inclus avec Office 365 Secteur public G1 ou Office 365 Secteur Public F3.|
|IRM via Windows Server AD RMS|Oui|Oui|Oui|Windows Server AD RMS est un serveur local qui doit être acheté et géré séparément pour activer les fonctionnalités IRM pris en charge.|
|Chiffrement de messages Office 365|Oui|Oui|Oui|Voir [chiffrement de messages Office 365 comportement à travers Cloud de la communauté du secteur public limite Haute/DoD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) dans cet article et les caractéristiques uniques des chiffrement de messages Office 365 <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">dans un Cloud de la communauté du secteur public Déploiement élevé</a>, qui documente les nuances de comportement chiffrement de messages Office 365 lors de l’envoi de messages entre Cloud de la communauté du secteur public utilisateurs high/dod et non Cloud de la communauté du secteur public utilisateurs high/dod.|
|Clé client|Oui|Oui|Oui|Nécessite un plan de service G5.|
|S/MIME|Oui|Oui|Oui||
|Conservation inaltérable et conservation pour litige|Oui|Oui|Oui|Nécessite un plan de service G3 ou G5.|
|Découverte électronique locale|Oui|Oui|Oui||
|Règles de flux de messagerie|Oui|Oui|Oui||
|Protection contre la perte de données|Oui|Oui|Oui|Nécessite un plan de service G3 ou G5.|
|Journalisation|Oui|Oui|Oui||
|**[Protection contre le courrier indésirable et les programmes malveillants](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Protection anti-courrier indésirable intégrée|Oui|Oui|Oui||
|Customize anti-spam policies|Oui|Oui|Oui||
|Protection anti-programme malveillant intégrée|Oui|Oui|Oui||
|Customize anti-malware policies|Oui|Oui|Oui||
|Quarantaine - gestion par l'administrateur|Oui|Oui|Oui||
|Quarantaine - autogestion par l'utilisateur final|Oui|Oui|Oui||
|Microsoft Defender pour Office 365|Oui|Oui|Oui|Nécessite un plan de service G5 (ou l’achat d’un module add-on).<br><br>L’anti-hameçonnage pour l’emprunt d’identité d’utilisateur et de domaine et la veille contre l’usurpation d’identité ne sont pas encore disponibles dans Cloud de la communauté du secteur public High et DoD.|
|**[Flux de messagerie](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Routage personnalisé du courrier sortant|Oui|Oui|Oui||
|Secure messaging with a trusted partner|Oui|Oui|Oui||
|Conditional mail routing|Oui|Oui|Oui||
|Ajout d’un partenaire à une liste fiable entrante|Oui|Oui|Oui||
|Routage de courrier hybride|Oui|Oui|Oui||
|**[Destinataires](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Alertes de capacité|Oui|Oui|Oui||
|Courrier non trié|Oui|Oui|Oui||
|MailTips|Oui|Oui|Oui||
|Accès délégué|Oui|Oui|Oui||
|Règles de la boîte de réception|Oui|Oui|Oui||
|Comptes connectés|Oui|Non|Non|Cette fonctionnalité n’est pas prise en charge dans Cloud de la communauté du secteur public High ou DoD en raison de restrictions sur les connexions sortantes à des services tiers. Pour plus d’informations sur les fonctionnalités impactées, voir Connectivité avec des [services tiers](#connectivity-with-third-party-services) dans cet article.|
|Boîtes aux lettres inactives|Oui|Oui|Oui|Nécessite un plan de service G3 ou G5.|
|Carnet d'adresses en mode hors connexion|Oui|Oui|Oui||
|Stratégies de carnet d’adresses|Oui|Oui|Oui||
|Carnet d'adresses hiérarchique|Oui|Oui|Oui||
|Listes d’adresses et liste d’adresses globale|Oui|Oui|Oui||
|Groupes Office 365|Oui|Oui|Oui|L’accès invité Office 365 groupes de sécurité n’est pas pris en charge Cloud de la communauté du secteur public environnements High et DoD. Pour plus d’informations, voir <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity</a>.|
|Groupes de distribution|Oui|Oui|Oui||
|Contacts externes (globaux)|Oui|Oui|Oui|Soumis aux limitations de collaboration de relation organisationnelle dans Cloud de la communauté du secteur public environnements Élevé et DoD. |
|Liaison de contacts avec des réseaux sociaux|Oui|Non|Non|Cette fonctionnalité n’est pas prise en charge dans Cloud de la communauté du secteur public Élevé ou DoD.|
|Boîtes aux lettres de ressources|Oui|Oui|Oui||
|Gestion des salles de conférence|Oui|Oui|Oui||
|Réponses d’in-office|Oui|Oui|Oui||
|Partage de calendrier Internet|Oui|Non|Non|Dans Cloud de la communauté du secteur public High, la publication/partage de calendriers Internet fonctionne pour la connexion entrante aux calendriers partagés par Cloud de la communauté du secteur public Utilisateurs élevés, mais pas pour les utilisateurs Cloud de la communauté du secteur public Utilisateurs élevés se connectant à un calendrier partagé en dehors Cloud de la communauté du secteur public High.<br><br>Dans DoD–Internet, le partage de calendriers n’est pas pris en charge en raison de la nécessité d’autoriser la liste des connexions entrantes/sortantes dans cet environnement.|
|**[Fonctions de rapport et outils de dépannage](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Rapports du Centre d’administration Microsoft 365|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">la</a> section des fonctionnalités de plateforme de la description Office 365 service pour le gouvernement américain pour les mises à jour/la disponibilité actuelle.|
|Rapports des services web|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">la</a> section des fonctionnalités de plateforme de la description Office 365 service pour le gouvernement américain pour les mises à jour/la disponibilité actuelle.|
|Message trace|Oui|Oui|Oui||
|Rapports d’audit|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">la</a> section des fonctionnalités de plateforme de la description Office 365 service pour le gouvernement américain pour les mises à jour/la disponibilité actuelle.|
|Rapports de messagerie unifiée|Oui|Non|Non||
|**[Partage et collaboration](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Partage fédéré (y compris la publication de calendrier)|Oui|Oui|Oui|Des limitations existent dans les deux Cloud de la communauté du secteur public High et DoD. Consultez [la fédération des heures de libre/occupé](#freebusy-federation) dans cet article.|
|Boîtes aux lettres de site|Oui|Oui|Oui||
|Dossiers publics|Oui|Oui|Oui||
|**[Clients et appareils mobiles](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|To Do sur le Web|Oui|Non|Non||
|Outlook pour Windows|Oui|Oui|Oui|Pour répondre Cloud de la communauté du secteur public exigences de conformité Élevée et DoD, vous devez avoir au moins la version 1803 de Office 365 ProPlus. Office 365 ProPlus n’est pas inclus dans G1 ou F3.|
|Outlook sur le web<sup>1</sup>|Oui|Oui|Oui||
|Outlook pour Mac|Oui|Oui|Oui|Pour répondre Cloud de la communauté du secteur public exigences de conformité Élevée et DoD, vous devez avoir au moins la version 1803 de Office 365 ProPlus. Office 365 ProPlus n’est pas inclus dans G1 ou F3.|
|Outlook pour iOS et Android|Oui|Oui|Oui||
|Exchange ActiveSync|Oui|Oui|Oui||
|Mobilité et sécurité de base pour Microsoft 365|Oui|Non|Non||
|POP et IMAP|Oui|Oui|Oui||
|SMTP|Oui|Oui|Oui||
|Prise en charge de l’application<sup>EWS 2</sup>|Oui|Oui|Oui||
|**[Services de messagerie vocale](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Messagerie vocale|Non|Non|Non|L’intégration des systèmes IP-PBX locaux Exchange Online la messagerie unifiée n’est pas prise en charge.|
|Intégration entre la messagerie vocale et la télécopie tierce|Non|Non|Non|L’intégration des systèmes IP-PBX locaux Exchange Online la messagerie unifiée n’est pas prise en charge.|
|Interopérabilité avec messagerie vocale tierce|Non|Non|Non|L’intégration des systèmes IP-PBX locaux Exchange Online la messagerie unifiée n’est pas prise en charge.|
|Skype Entreprise’intégration|Oui|Oui|Oui||
|**[Haute disponibilité et continuité de service](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Réplication de boîtes aux lettres dans les centres de données|Oui|Oui|Oui||
|Récupération de boîtes aux lettres supprimées|Oui|Oui|Oui||
|Récupération d'éléments supprimés|Oui|Oui|Oui||
|Récupération d'élément unique|Oui|Oui|Oui||
|**[Interopérabilité, connectivité et compatibilité](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Présence dans OWA et Outlook|Oui|Oui|Oui||
|interopérabilité SharePoint’équipe|Oui|Oui|Oui||
|Prise en charge de la connectivité EWS|Oui|Oui|Oui||
|Prise en charge du relais SMTP|Oui|Oui|Oui||
|**[Configuration et administration d’Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Accès au portail Microsoft Office 365|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">la</a> section des fonctionnalités de plateforme de la description Office 365 service pour le gouvernement américain pour les mises à jour/la disponibilité actuelle.|
|Centre d'administration Microsoft 365'accès|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">la</a> section des fonctionnalités de plateforme de la description Office 365 service pour le gouvernement américain pour les mises à jour/la disponibilité actuelle.|
|Accès au Centre d'administration Exchange|Oui|Oui|Oui||
|Accès à Windows PowerShell à distance|Oui|Oui|Oui||
|Stratégies ActiveSync pour les appareils mobiles|Oui|Oui|Oui||
|Rapports d’utilisation|Oui|Oui|Non|Rapports non disponibles pour DoD. Reportez-vous à <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">la</a> section des fonctionnalités de plateforme de la description Office 365 service pour le gouvernement américain pour les mises à jour/la disponibilité actuelle.|
|**[Extension du service : personnalisation, les add-ins et les ressources](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DOD**|**Considérations clés**|
|Outlook et Outlook MAPI|Oui|Oui|Oui|Seuls certains OWA et Outlook sont disponibles dans Cloud de la communauté du secteur public Haut et DoD. Voir [les Outlook et Outlook Web App](#add-insin-outlook-and-outlook-web-app) dans cet article.|

<sup>1</sup> Outlook sur le Web peut être utilisé dans les scénarios où Outlook pour Windows ne peut pas afficher les messages protégés par IRM en raison de restrictions croisées (Cloud de la communauté du secteur public Élevé/ Non Cloud de la communauté du secteur public Élevé ).</br>
<sup>2 Uniquement</sup> la sortie vers des espaces d’adresses spécifiques que le client peut prouver qu’il possède est autorisé, ce qui exclut les services tiers et les larges plages d’adresses IP utilisées par les appareils mobiles.

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>Nuances de fonctionnalités Cloud de la communauté du secteur public environnements Élevé et DoD

### <a name="connectivity-with-third-party-services"></a>Connectivité avec des services tiers  

Les Cloud de la communauté du secteur public les environnements High et DoD sont des environnements restreints qui nécessitent une approbation et une configuration explicites des connexions sortantes. En outre, Microsoft ne peut pas prendre en charge les demandes d’autoriser l’accès sortant à partir de ces environnements aux services cloud commerciaux (Commercial Office 365, Google GSuite, Amazon Web Services, et ainsi de suite).

En raison de ces restrictions, les fonctionnalités qui reposent sur cette connectivité sortante à partir des environnements Cloud de la communauté du secteur public High/DoD ne sont généralement pas pris en charge, notamment :

- Comptes connectés : les utilisateurs ne peuvent pas ajouter/synchroniser des comptes (Google, POP/IMAP, et ainsi de suite).

- Prise en charge des fournisseurs de stockage de fichiers tiers : seul le compte OneDrive Entreprise de l’utilisateur dans *Cloud de la communauté du secteur public High/DoD* est accessible à partir des différents clients Outlook dans le but d’attacher/partager des fichiers. Les comptes de stockage tiers (Dropbox, Box, Google Drive) ne peuvent pas être ajoutés.

- Connectivité avec les réseaux sociaux, tels que Facebook ou LinkedIn.

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory Collaboration B2B

Azure Active Directory La collaboration B2B est actuellement prise en charge uniquement entre les organisations qui se trouve dans le cloud Azure US Government et qui les deux la prise en charge de la collaboration B2B

En outre, les utilisateurs B2B en tant qu’invités dans Office 365 groupes ne sont pas pris en charge dans Cloud de la communauté du secteur public environnements High et DoD. 

Pour plus d’informations et les dernières mises à jour, voir [Azure Government Security + Identity](/azure/azure-government/documentation-government-services-securityandidentity).

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>chiffrement de messages Office 365 comportement à travers Cloud de la communauté du secteur public limite Haute/DoD

Si vous prévoyez d’utiliser chiffrement de messages Office 365 dans un environnement Cloud de la communauté du secteur public high, ez compte des caractéristiques uniques suivantes concernant l’expérience des destinataires :  

- Lors de l’envoi de messages chiffrés Cloud de la communauté du secteur public élevé ou DoD à des destinataires dans le même environnement :
    
    - Les expéditeurs peuvent chiffrer manuellement les messages électroniques dans Outlook pour PC et Mac et Outlook sur le web, ou les organisations peuvent configurer une stratégie pour chiffrer les messages électroniques à l’aide de Exchange règles de flux de messagerie.
    
    - Les destinataires à l’intérieur Cloud de la communauté du secteur public High/DoD bénéficient de la même expérience de lecture en ligne dans Outlook pour PC et Mac et Outlook sur le web que tous les autres utilisateurs Office 365 utilisateurs.

<!-- end list -->

- Lors de l’envoi d’e-mails chiffrés Cloud de la communauté du secteur public élevé à des destinataires en dehors de cet environnement (notamment DoD, Cloud de la communauté du secteur public commercial) :

    - Les expéditeurs à l Cloud de la communauté du secteur public élevé peuvent envoyer des messages chiffrés en dehors de la limite Cloud de la communauté du secteur public limite élevée.
    - Tous les destinataires extérieurs à Cloud de la communauté du secteur public High, y compris les utilisateurs DoD, les utilisateurs de Office 365 commerciaux, les utilisateurs Outlook.com et les autres utilisateurs d’autres fournisseurs de messagerie, reçoivent un wrapper. Ce message de wrapper redirige le destinataire vers le portail OME où le destinataire peut lire les messages et y répondre.

Pour plus d’informations et les dernières mises à jour, voir [Comparer les versions d’OME.](/microsoft-365/compliance/ome-version-comparison)

### <a name="freebusy-federation"></a>Fédération de la libre/occupé

Le partage fédéré, y compris les informations de libre/occupé, est actuellement soumis à plusieurs limitations importantes dans les environnements DoD.

Dans l’environnement Cloud de la communauté du secteur public high :

- L’accord de fédération (y compris le partage bidirectionnel des informations de libre/occupé) est pris en charge entre les clients dans Cloud de la communauté du secteur public High, les clients dans les clouds Cloud de la communauté du secteur public et commerciaux, et via la coexistence hybride (Exchange 2013 ou version ultérieure).

Dans l’environnement DoD :

  - L’accord de fédération (y compris le partage des informations de libre/occupé) est actuellement pris en charge uniquement entre les clients au sein de l’environnement DoD. Il n’est pas pris en charge entre les locataires DoD et les Cloud de la communauté du secteur public, Cloud de la communauté du secteur public élevé ou commerciaux.

### <a name="client-configuration"></a>Configuration du client

Des étapes supplémentaires sont nécessaires au déploiement et à la configuration de Office ProPlus (y compris Outlook). Pour une description détaillée de ces étapes, voir recommandations pour le déploiement de Applications Microsoft 365 pour les grandes entreprises dans un [environnement Cloud de la communauté du secteur public élevé ou DoD](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook pour iOS et Android est également disponible pour les environnements Cloud de la communauté du secteur public et DoD. Pour en savoir plus sur les limitations et la gestion des fonctionnalités dans ces environnements, voir Utilisation de Outlook pour [iOS](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)et Android dans la Cloud de la communauté du secteur public .

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Les Outlook et Outlook Web App  

Seuls certains OWA et Outlook sont disponibles dans Cloud de la communauté du secteur public Haut et DoD. Mes modèles et mes réunions suggérées sont disponibles et devraient fonctionner. Seuls les cinq OWA par défaut sont pris en charge. L’intégration avec des applications tierces est possible, toutefois, ces intégrations ne sont pas couvertes par les promesses de conformité microsoft pour Cloud de la communauté du secteur public Haut ou DoD. Les clients doivent se familiariser avec les pratiques de gestion des données tierces et les promesses de conformité avant de configurer le module add-on pour leur organisation.

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Nuances de fonctionnalités dans Cloud de la communauté du secteur public environnements de Microsoft To Do

| Fonctionnalité | Description | WW | Disponibilité dans les Cloud de la communauté du secteur public |
|:-----|:-----|:-----|:-----|
|Plateformes pris en charge|Web, Android, iOS, Mac, Windows|Tous|Web uniquement|
|Hub M365 prend en charge|Intégrations avec Outlook, Teams, Planner|Tous|Outlook, Planner (Teams disponible avec l’application Teams tâches)|
|Wunderlist Migration|Autoriser les utilisateurs wunderlist à migrer des données vers To Do sur le Web|Oui|Non|
|Notifications Push|Envoyer des notifications Push aux utilisateurs finaux pour les rappels, etc.|Oui|Non|
|Prise en charge de Helpshift|Utiliser l’interface helpshift pour créer une demande de support|Oui|Non|
|Mon jour|Planifier votre journée|Oui|Oui|
|Liste planifiée|Voir toutes les tâches à une date d’échéance|Oui|Oui|
|Liste Affectée à vous|Toutes les tâches qui vous sont affectées dans une liste partagée, le Planificateur ou WXP (futur)|Oui|Oui|
|Courrier électronique marqué|Voir les e-mails marqués dans Outlook comme tâches|Oui|Oui|
|Prise en charge de comptes multiples|Utiliser le compte d’accueil et le compte de bureau dans un volet|Oui|Oui|
|Partage de liste|Partager des listes avec des collègues de la même organisation|Oui|Oui|
|Partage entre les locataires|Partager une liste de tâches en dehors de votre organisation|Oui|Non|
|Rappels et récurrence|Définir des rappels pour votre tâche |Oui|Oui|

*Toutes les autres fonctionnalités non mentionnées sont disponibles dans les deux environnements.