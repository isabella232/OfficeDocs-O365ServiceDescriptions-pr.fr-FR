---
title: Description du service Microsoft Defender pour Office 365
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender pour Office 365 est un service de filtrage du courrier électronique basé sur le cloud qui permet de protéger votre organisation contre les programmes malveillants et les virus inconnus en offrant une protection zero-day robuste et inclut des fonctionnalités pour protéger votre organisation contre les liens dangereux en temps réel.
ms.openlocfilehash: fd2869eb98b64fca4f241339497486a392815402
ms.sourcegitcommit: bab0eaae59d5c801f88eadbd29fd0d16de387c82
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/07/2021
ms.locfileid: "49780008"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Description du service Microsoft Defender pour Office 365

Microsoft Defender pour Office 365 est un service de filtrage du courrier électronique basé sur le cloud qui permet de protéger votre organisation contre les programmes malveillants et les virus inconnus en offrant une protection zero-day robuste et inclut des fonctionnalités pour protéger votre organisation contre les liens dangereux en temps réel. Defender pour Office 365 offre de riches fonctionnalités de suivi d’URL et de rapports qui donnent aux administrateurs des informations sur le type d’attaques qui se produisent dans votre organisation.

Les principaux moyens d’utiliser Defender pour Office 365 pour la protection des messages sont les suivants :

- Dans un scénario de filtrage Defender pour Office 365 uniquement, Defender pour Office 365 fournit une protection de messagerie en nuage pour votre environnement Exchange Server local ou toute autre solution de messagerie SMTP locale.

- Defender pour Office 365 peut être activé pour protéger les boîtes aux lettres Exchange Online hébergées dans le cloud. Pour en savoir plus sur Exchange Online, consultez la [description du service Exchange Online.](exchange-online-service-description/exchange-online-service-description.md)

- Dans un déploiement hybride, Defender pour Office 365 peut être configuré pour protéger votre environnement de messagerie et contrôler le routage des messages lorsque vous avez une combinaison de boîtes aux lettres sur site et cloud avec Exchange Online Protection pour le filtrage des messages entrants.

## <a name="microsoft-defender-for-office-365-availability"></a>Disponibilité de Microsoft Defender pour Office 365

Defender pour Office 365 Plan 2 est inclus dans Office 365 E5, Office 365 A5 et Microsoft 365 E5. Defender pour Office 365 Plan 1 est inclus dans Microsoft 365 Business Premium.

Vous pouvez ajouter Defender pour Office 365 aux plans d’abonnement Exchange et Microsoft 365 suivants :

- Exchange Online (plan 1)

- Exchange Online (plan 2)

- Exchange Online Kiosk

- Exchange Online Protection

- Microsoft 365 Business Basic

- Microsoft 365 Business Standard

- Office 365 Entreprise E1

- Office 365 Entreprise E3

- Office 365 Entreprise F3

- Office 365 A1

- Office 365 A3

Pour acheter Microsoft Defender pour Office 365, consultez [Microsoft Defender pour Office 365.](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

Pour comparer les fonctionnalités entre les plans, voir [Outils puissants](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) pour prendre en charge votre entreprise et Transformer votre entreprise [avec Microsoft 365.](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Nouveautés de Microsoft Defender pour Office 365

Nous continuons à ajouter de nouvelles fonctionnalités à Defender pour Office 365. Pour en savoir plus sur les nouvelles fonctionnalités disponibles dans Defender pour Office 365 (ou Microsoft 365 en général), consultez les ressources suivantes :

- [Feuille de route de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Nouveautés de Microsoft Defender pour Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Conditions requises pour Microsoft Defender pour Office 365

Defender pour Office 365 peut être utilisé avec n’importe quel agent de transfert de courrier SMTP, tel Microsoft Exchange Server. Pour plus d’informations sur les systèmes d’exploitation, les navigateurs web et les langues pris en charge par Defender pour Office 365, consultez les sections « Navigateurs pris en charge » et « Langues pris en charge » dans le Centre d’administration Exchange dans [Exchange Online Protection.](https://go.microsoft.com/fwlink/p/?LinkId=282381)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilité des fonctionnalités dans les plans Defender pour Office 365

Chaque fonctionnalité est indiquée ci-dessous. La mention « Exchange Online » fait généralement référence à la famille de services  Office 365 Entreprise.<br><br>

| Fonctionnalité | Defender pour Office 365 Plan 1 | Defender pour Office 365 Plan 2 | Sécurité Microsoft 365 E5 /E5|
|:-----|:-----|:-----|:-----|
|*Configuration, protection et détection*|
|[Pièces jointes fiables](#safe-attachments)|Oui|Oui|Oui|
|Pièces jointes sécurisées dans Teams|Oui|Oui|Oui|
|[Liens fiables](#safe-links)|Oui|Oui|Oui|
|[Documents sécurisés](#safe-documents)|Non|Non|Oui|
|Liens fiables dans Teams|Oui|Oui|Oui|
|[ATP pour SharePoint, OneDrive et Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Oui|Oui|Oui|
|[Stratégies anti-hameçonnage](#anti-phishing-policies).|Oui|Oui|Oui|
|[Rapports en temps réel](#real-time-reports)|Oui|Oui|Oui|
|*Automatisation, examen, correction et éducation*|
|[Suivi des menaces](#threat-trackers)|Non|Oui|Oui|
|Examen des menaces (examen avancé des menaces)|[Détections en temps réel](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Réponse automatisée aux incidents](#automated-incident-response)|Non|Oui|Oui|
|[Simulateur d’attaques](#attack-simulator)|Non|Oui|Oui|
|*Intégration à Microsoft 365 Defender*|Non|Oui|Oui|

> [!TIP]
> Vous souhaitez obtenir une liste téléchargeable des différences entre Defender pour Office 365 Plan 1 et Plan 2 ? [Obtenir le FICHIER PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

> [!NOTE]
> Si votre client dispose uniquement d’une licence d’essai Office ATP P2 ou d’une licence d’essai Office 365 E5, sans autre licence éligible pour la Protection Microsoft contre les menaces, vous ne pourrez pas accéder à la Protection Microsoft contre les menaces. Pour en savoir plus sur la licence MTP, voir <https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites>

## <a name="defender-for-office-365-capabilities"></a>Fonctionnalités de Defender pour Office 365

### <a name="safe-attachments"></a>Pièces jointes sûres

[La fonction Pièces jointes sécurisées](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protège contre les programmes malveillants et les virus inconnus et fournit une protection zero-day pour protéger votre système de messagerie. Tous les messages et pièces jointes qui n’ont pas de signature de virus/programmes malveillants connus sont acheminés vers un environnement spécial dans lequel Defender pour Office 365 utilise diverses techniques d’apprentissage automatique et d’analyse pour détecter les intentions malveillantes. Si aucune activité suspecte n'est détectée, le message est libéré et remis à la boîte aux lettres.

> [!NOTE]
> L’analyse des pièces jointes sécurisées a lieu dans la même région que vos données Office 365. Pour plus d’informations sur la géographie du centre de données, [voir Où se trouvent vos données ?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Liens sûrs

La [fonctionnalité Liens sécurisés](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) protège de manière proactive vos utilisateurs contre les URL malveillantes dans un message ou dans un document Office. La protection est activée à chaque fois qu'ils sélectionnent sur le lien ; les liens malveillants sont bloqués dynamiquement tandis que les liens fiables peuvent être ouverts.

Les liens sécurisés sont disponibles pour les URL dans les applications suivantes:

- Applications Microsoft 365 pour les entreprises sur Windows ou Mac

- Office pour le Web (Word pour le Web, Excel pour le Web, PowerPoint pour le Web et OneNote pour le Web)

- Word, Excel et PowerPoint sur Windows

- Canaux et chats Microsoft Teams

> [!NOTE]
> Les utilisateurs doivent être titulaires d’une licence Defender pour Office 365, être inclus dans les stratégies de liens sécurisés et être connectés sur leurs appareils pour que la <sup>\*</sup> protection soit en place.
>
> <sup>\*</sup> Pour les licences Defender pour Office 365 à l’échelle de l’organisation (par exemple, ATP_ENTERPRISE_FACULTY), vous n’avez pas besoin d’affecter des licences Defender pour Office 365 à des utilisateurs individuels.
>
> Pour plus d’informations sur la protection contre les liens sécurisés, voir [Liens sécurisés dans Microsoft Defender pour Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Documents sécurisés

La [fonctionnalité Documents sécurisés](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) utilise [Microsoft Defender pour le point](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) de terminaison pour analyser les documents et les fichiers ouverts en [affichage protégé.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Ce qu'il faut savoir avant de commencer

- Les documents sécurisés sont désormais généralement disponibles pour les utilisateurs avec Office Version 2004 (12730.x) ou version supérieure ! Cette fonctionnalité est éteinte par défaut et doit être activée par l’administrateur de sécurité.

- Cette fonctionnalité est uniquement disponible pour les utilisateurs titulaires de la licence Microsoft 365 E5 ou Microsoft 365 E5 Security (non incluse dans les plans Defender pour Office 365).

- Word, Excel et PowerPoint sur Windows

- Canaux et chats Microsoft Teams

> [!NOTE]
> Les utilisateurs doivent être titulaires d’une licence Microsoft 365 E5 ou Microsoft 365 E5 Security, doivent être inclus dans les stratégies de documents sécurisés et doivent être connectés sur leurs appareils pour que la protection soit en <sup>\*</sup> place.
>
> Pour plus d’informations sur la protection des documents sécurisés, voir Documents sécurisés [dans Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>Protection avancée contre les menaces pour SharePoint, OneDrive et Microsoft Teams

[AtP pour SharePoint, OneDrive](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  et Microsoft Teams permet de détecter et de bloquer les fichiers identifiés comme malveillants dans les sites d’équipe et les bibliothèques de documents. En outre, la protection contre les liens sécurisés est désormais disponible dans les canaux et conversations Microsoft Teams.

### <a name="anti-phishing-policies"></a>Politiques anti-hameçonnage

[L’anti-hameçonnage recherche](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) dans les messages entrants les indicateurs qu’un message peut être une tentative de hameçonnage. Lorsque les utilisateurs sont couverts par les stratégies De Defender pour Office 365 (pièces jointes sécurisées, liens sécurisés ou anti-hameçonnage), les messages entrants sont évalués par plusieurs modèles d’apprentissage automatique qui analysent les messages et l’action appropriée est entreprise, en fonction des stratégies configurées.

### <a name="real-time-reports"></a>Rapports en temps réel

Les [fonctionnalités](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) de surveillance disponibles dans le Centre de sécurité & conformité incluent des rapports et des informations en temps réel qui donnent à vos administrateurs de sécurité et de conformité la possibilité de se concentrer sur les problèmes prioritaires, tels que les attaques de sécurité ou l’augmentation des activités suspectes. Outre la mise en évidence des problèmes, les rapports intelligents et les informations incluent des recommandations et des liens pour afficher et explorer des données et prendre des mesures rapides.

### <a name="explorer"></a>Explorer

L’Explorateur (également appelé « Explorateur de menaces ») est un rapport en temps réel qui permet aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. Par défaut, ce rapport présente les données des 7 derniers jours. Toutefois, les affichages peuvent être modifiés pour afficher les données des 30 derniers jours.

L’Explorateur contient des affichages, tels que les programmes malveillants (pour le courrier électronique et le contenu), les soumissions, le hameçonnage et tous les e-mails. Pour voir comment l’Explorateur se compare aux détections en temps réel, [téléchargez ce PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Pour plus d’informations sur l’Explorateur (dans Microsoft Defender pour Office 365 Plan 2) et les détections en temps réel (dans Microsoft Defender pour Office 365 Plan 1), voir l’Explorateur de menaces et les [détections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)en temps réel.

### <a name="real-time-detections"></a>Détections en temps réel

Les détections en temps réel sont des rapports en temps réel qui permettent aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. À l’instar de l’Explorateur, ce rapport affiche par défaut les données des 7 derniers jours.

Les détections en temps réel contiennent des affichages, tels que les programmes malveillants (pour le courrier électronique et le contenu), les soumissions et le hameçonnage. Pour comparer les détections en temps réel avec l’Explorateur, [téléchargez ce PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Pour plus d’informations sur l’Explorateur (dans Microsoft Defender pour Office 365 Plan 2) et les détections en temps réel (dans Microsoft Defender pour Office 365 Plan 1), voir Explorateur de [menaces (et détections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)en temps réel).

### <a name="threat-trackers"></a>Suivi des menaces

[Les suivis des menaces](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) sont des widgets informatifs et des vues qui fournissent aux utilisateurs autorisés des renseignements sur les problèmes de cybersécurité qui peuvent avoir un impact sur votre organisation.

### <a name="automated-incident-response"></a>Réponse automatisée aux incidents

Les fonctionnalités de réponse automatisée aux [incidents](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) disponibles dans Defender pour Office 365 Plan 2 vous permet d’exécuter des processus d’examen automatisés en réponse aux menaces connues qui existent aujourd’hui. Grâce à l’automatisation de certaines tâches d’examen, votre équipe en charge des opérations de sécurité peut fonctionner plus efficacement. Les mesures correctives, telles que la suppression de messages électroniques malveillants, sont prises après approbation par votre équipe des opérations de sécurité. Pour plus d’informations, voir [fonctionnement d’AIR dans Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulator"></a>Simulateur d’attaques

[Le Simulateur](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) d’attaques permet aux utilisateurs autorisés d’exécuter des scénarios d’attaque réalistes dans votre organisation. Plusieurs types d’attaques sont disponibles, notamment une attaque par harponnage de nom complet, une attaque par pulvérisation de mot de passe et une attaque par mot de passe par force brute.
