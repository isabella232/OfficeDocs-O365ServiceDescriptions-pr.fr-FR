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
description: Microsoft Defender pour Office 365 est un service de filtrage du courrier basé sur le Cloud qui contribue à protéger votre organisation contre les programmes malveillants et les virus inconnus en fournissant une protection fiable contre les menaces et qui inclut des fonctionnalités permettant de protéger en temps réel votre organisation contre les liens nuisibles.
ms.openlocfilehash: 1d99b59e089ecb351d436c49a4f4e3986aefa6cd
ms.sourcegitcommit: 0752cc6c082737a19c7dca24c8f3b555ea871f4f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/01/2020
ms.locfileid: "49519025"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Description du service Microsoft Defender pour Office 365

Microsoft Defender pour Office 365 est un service de filtrage du courrier basé sur le Cloud qui contribue à protéger votre organisation contre les programmes malveillants et les virus inconnus en fournissant une protection fiable contre les menaces et qui inclut des fonctionnalités permettant de protéger en temps réel votre organisation contre les liens nuisibles. Defender for Office 365 dispose de riches fonctionnalités de création de rapports et de suivi d’URL qui donnent aux administrateurs un aperçu du type d’attaques qui se produisent au sein de votre organisation.

Les principales façons d’utiliser Defender pour Office 365 pour la protection des messages sont les suivantes :

- Dans un scénario de filtrage uniquement de Defender pour Office 365, Defender for Office 365 fournit une protection de messagerie en nuage pour votre environnement Exchange Server local ou toute autre solution de messagerie SMTP locale.

- Defender pour Office 365 peut être activé pour protéger les boîtes aux lettres hébergées dans le Cloud Exchange Online. Pour en savoir plus sur Exchange Online, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- Dans un déploiement hybride, Defender pour Office 365 peut être configuré pour protéger votre environnement de messagerie et contrôler le routage des messages lorsque vous combinez des boîtes aux lettres sur site et dans le Cloud à l’aide d’Exchange Online Protection pour le filtrage du courrier électronique entrant.

## <a name="microsoft-defender-for-office-365-availability"></a>Disponibilité de Microsoft Defender pour Office 365

Defender pour Office 365 plan 2 est inclus dans Office 365 E5, Office 365 a5 et Microsoft 365 E5. Defender pour Office 365 plan 1 est inclus dans Microsoft 365 Business Premium.

Vous pouvez ajouter Defender pour Office 365 aux plans d’abonnement Exchange et Microsoft 365 suivants :

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

Pour acheter Microsoft Defender pour Office 365, reportez-vous à [Microsoft Defender pour office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Pour comparer les fonctionnalités de tous les plans, consultez [la rubrique outils puissants pour prendre en charge votre entreprise](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) et [transformer votre entreprise avec Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Nouveautés de Microsoft Defender pour Office 365

Nous continuons à ajouter de nouvelles fonctionnalités à Defender pour Office 365. Pour en savoir plus sur les nouvelles fonctionnalités proposées par Defender pour Office 365 (ou Microsoft 365 en général), consultez les ressources suivantes :

- [Feuille de route de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Nouveautés de Microsoft Defender pour Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Configuration requise pour Microsoft Defender pour Office 365

Defender pour Office 365 peut être utilisé avec n’importe quel agent de transfert de courrier SMTP, tel que Microsoft Exchange Server. Pour plus d’informations sur les systèmes d’exploitation, les navigateurs Web et les langues pris en charge par Defender pour Office 365, consultez les sections « navigateurs pris en charge » et « langues prises en charge » dans le [Centre d’administration Exchange dans Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilité des fonctionnalités pour les plans Office 365 de Defender

Chaque fonctionnalité est indiquée ci-dessous. La mention « Exchange Online » fait généralement référence à la famille de services  Office 365 Entreprise.<br><br>

| Fonctionnalité | Defender pour Office 365 plan 1 | Defender pour Office 365 plan 2 | Microsoft 365 E5/E5 sécurité|
|:-----|:-----|:-----|:-----|
|*Configuration, protection et détection*|
|[Pièces jointes fiables](#safe-attachments)|Oui|Oui|Oui|
|Pièces jointes fiables dans teams|Oui|Oui|Oui|
|[Liens fiables](#safe-links)|Oui|Oui|Oui|
|[Documents sécurisés](#safe-documents)|Non|Non|Oui|
|Liens fiables dans Teams|Oui|Oui|Oui|
|[ATP pour SharePoint, OneDrive et Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Oui|Oui|Oui|
|[Stratégies anti-hameçonnage](#anti-phishing-policies).|Oui|Oui|Oui|
|[Rapports en temps réel](#real-time-reports)|Oui|Oui|Oui|
|*Automatisation, recherche, correction et éducation*|
|[Suivi des menaces](#threat-trackers)|Non|Oui|Oui|
|Enquête sur les menaces (enquête avancée contre les menaces)|[Détections en temps réel](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Réponse automatique aux incidents](#automated-incident-response)|Non|Oui|Oui|
|[Simulateur d’attaques](#attack-simulator)|Non|Oui|Oui|
|*Intégration à Microsoft 365 Defender*|Non|Non|Oui|

> [!TIP]
> Vous souhaitez obtenir une liste téléchargeable des différences entre Defender pour Office 365 plan 1 et plan 2 ? [Obtenir le PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf). 

## <a name="defender-for-office-365-capabilities"></a>Fonctionnalités de Defender pour Office 365

### <a name="safe-attachments"></a>Pièces jointes sûres

[Les pièces jointes fiables](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protègent contre les programmes malveillants et les virus inconnus et fournissent une protection contre les menaces pour protéger votre système de messagerie. Tous les messages et pièces jointes sans signature de virus/programmes malveillants connus sont acheminés vers un environnement spécial où Defender pour Office 365 utilise diverses techniques d’analyse et d’analyse de machines pour détecter les intentions malveillantes. Si aucune activité suspecte n'est détectée, le message est libéré et remis à la boîte aux lettres.

> [!NOTE]
> L’analyse des pièces jointes fiables a lieu dans la région où se trouvent vos données Office 365. Pour plus d’informations sur la géographie du centre de données, voir [où se trouvent vos données ?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Liens sûrs

La fonctionnalité de [liens fiables](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) protège de manière proactive vos utilisateurs contre les URL malveillantes dans un message ou dans un document Office. La protection est activée à chaque fois qu'ils sélectionnent sur le lien ; les liens malveillants sont bloqués dynamiquement tandis que les liens fiables peuvent être ouverts.

Les liens sécurisés sont disponibles pour les URL dans les applications suivantes:

- Applications Microsoft 365 pour Enterprise sur Windows ou Mac

- Office pour le Web (Word pour le Web, Excel pour le Web, PowerPoint pour le Web et OneNote pour le Web)

- Word, Excel et PowerPoint sur Windows

- Canaux et chats Microsoft Teams

> [!NOTE]
> Les utilisateurs doivent être titulaires d’une licence pour Defender pour Office 365 <sup>\*</sup> , doivent être inclus dans les stratégies de liens fiables et doivent être connectés sur leurs appareils pour que la protection soit mise en place.
>
> <sup>\*</sup> Pour les licences Defender à l’échelle de l’Organisation pour Office 365 (par exemple, ATP_ENTERPRISE_FACULTY), vous n’avez pas besoin d’attribuer des licences Defender pour Office 365 à des utilisateurs individuels.
>
> Pour plus d’informations sur la protection des liens fiables, consultez la rubrique [liens fiables dans Microsoft Defender pour Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documents sécurisés

La fonctionnalité de [documents sûrs](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) utilise [Microsoft Defender pour le point de terminaison](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) pour analyser les documents et les fichiers ouverts en [mode protégé](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

Ce qu'il faut savoir avant de commencer

- Les documents approuvés sont désormais généralement disponibles pour les utilisateurs de la version 2004 de Office (12730. x) ou une version ultérieure. Cette fonctionnalité est désactivée par défaut et doit être activée par l’administrateur de la sécurité.

- Cette fonctionnalité est disponible uniquement pour les utilisateurs disposant de la licence de sécurité Microsoft 365 E5 ou Microsoft 365 E5 (non incluse dans les offres de Defender pour Office 365).

- Word, Excel et PowerPoint sur Windows

- Canaux et chats Microsoft Teams

> [!NOTE]
> Les utilisateurs doivent être titulaires d’une licence pour Microsoft 365 E5 ou Microsoft 365 E5 sécurité <sup>\*</sup> , doivent être inclus dans les stratégies de documents fiables et être connectés sur leurs appareils pour que la protection soit mise en place.
>
> Pour plus d’informations sur la protection des documents fiables, consultez la rubrique [documents approuvés dans Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>Protection avancée contre les menaces pour SharePoint, OneDrive et Microsoft Teams

La protection avancée contre [les menaces pour SharePoint, OneDrive et Microsoft teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) permet de détecter et de bloquer des fichiers identifiés comme étant malveillants dans les sites d’équipe et les bibliothèques de documents. En outre, la protection des liens fiables est désormais disponible dans les conversations et les canaux Microsoft Teams.

### <a name="anti-phishing-policies"></a>Politiques anti-hameçonnage

[Anti-hameçonnage](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) vérifie que les messages entrants indiquent qu’un message peut être une tentative de hameçonnage. Lorsque les utilisateurs sont couverts par les stratégies Defender pour Office 365 (pièces jointes fiables, liens fiables ou anti-hameçonnage), les messages entrants sont évalués par plusieurs modèles d’apprentissage automatique qui analysent les messages et l’action appropriée est entreprise en fonction des stratégies configurées.

### <a name="real-time-reports"></a>Rapports en temps réel

Les fonctionnalités de surveillance disponibles dans le centre de sécurité & conformité incluent des [rapports en temps réel et des](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) informations qui permettent aux administrateurs de la sécurité et de la conformité de se concentrer sur des problèmes à haute priorité, tels que les attaques de sécurité ou l’augmentation de l’activité suspecte. En plus de mettre en surbrillance les zones problématiques, les rapports intelligents et les idées contiennent des recommandations et des liens permettant d’afficher et d’explorer les données et d’effectuer des actions rapides.

### <a name="explorer"></a>Explorer

L’Explorateur (également appelé « Explorateur de menaces ») est un rapport en temps réel qui permet aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. Par défaut, ce rapport présente les données des 7 derniers jours. Toutefois, les affichages peuvent être modifiés pour afficher les données des 30 derniers jours.

L’Explorateur contient des vues, telles que des programmes malveillants (pour le courrier électronique et le contenu), des envois, des hameçons et tous les messages électroniques. Pour savoir comment Explorer compare les détections en temps réel, [Téléchargez ce PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Pour plus d’informations sur l’Explorateur (dans Microsoft Defender pour Office 365 plan 2) et les détections en temps réel (dans Microsoft Defender pour Office 365 plan 1), consultez l' [Explorateur de menaces et les détections en temps réel](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Détections en temps réel

Les détections en temps réel sont des rapports en temps réel qui permettent aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. À l’instar de l’Explorateur, ce rapport affiche par défaut les données des 7 derniers jours.

Les détections en temps réel contiennent des affichages, tels que des programmes malveillants (pour la messagerie électronique et du contenu), des envois et des hameçons. Pour voir comment les détections en temps réel sont comparées avec l’Explorateur, [Téléchargez ce PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Pour plus d’informations sur l’Explorateur (dans Microsoft Defender pour Office 365 plan 2) et les détections en temps réel (dans Microsoft Defender pour Office 365 plan 1), voir [Threat Explorer (and Real-Time Detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Suivi des menaces

Les analyseurs de [menace](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) sont des widgets informatifs et des vues qui fournissent aux utilisateurs autorisés des renseignements sur les problèmes de Cybersecurity susceptibles d’avoir un impact sur votre organisation.

### <a name="automated-incident-response"></a>Réponse automatique aux incidents

Les fonctionnalités de [réponse aux incidents automatisées](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) disponibles dans Defender for Office 365 plan 2 vous permettent d’exécuter des processus d’enquête automatisés en réponse à des menaces connues qui existent aujourd’hui. En automatisant certaines tâches d’enquête, votre équipe des opérations de sécurité peut fonctionner de manière plus efficace. Les actions de correction, telles que la suppression des messages électroniques malveillants, sont prises en approbation par votre équipe des opérations de sécurité. Pour en savoir plus, consultez [la rubrique How air fonctionne dans Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Simulateur d’attaques

Le [simulateur d’attaque](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) permet aux utilisateurs autorisés d’exécuter des scénarios d’attaque réaliste dans votre organisation. Plusieurs types d’attaques sont disponibles, y compris une attaque de Spear Phishing, une attaque par pulvérisation de mot de passe et une attaque de mot de passe en force.
