---
title: Description du service Office 365 - Protection avancée contre les menaces
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Office 365 - Protection avancée contre les menaces est un service informatique de filtrage du courrier électronique qui vous aide à protéger votre organisation contre des virus et des programmes malveillants inconnus grâce à une protection zero-day solide.
ms.openlocfilehash: 3295bf261c9412f5881a16e3bc17088f32b4a18e
ms.sourcegitcommit: fb245074a57da585566096f6956d37325f451262
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/26/2019
ms.locfileid: "37734172"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Description du service Office 365 - Protection avancée contre les menaces

Office 365 - Protection avancée contre les menaces est un service informatique de filtrage du courrier électronique qui vous aide à protéger votre organisation contre des virus et des programmes malveillants inconnus grâce à une protection zero-day solide. Ce service comprend des fonctionnalités permettant de protéger en temps réel votre organisation contre des liens dangereux et dispose de fonctionnalités avancées de suivi d’URL et de création de rapports qui donnent aux administrateurs un aperçu du type d’attaques ayant lieu dans l’organisation.

Les principales façons d’utiliser la protection avancée contre les menaces pour la protection des messages sont les suivantes :

- Dans un scénario Office 365 ATP à filtrage uniquement, l’ATP fournit une protection de messagerie en nuage pour votre environnement Exchange Server local ou toute autre solution de messagerie SMTP locale.

- Office 365 - Protection avancée contre les menaces peut être activé pour protéger les boîtes aux lettres Exchange Online hébergées dans le cloud. Pour en savoir plus sur Exchange Online, reportez-vous à l'article [Description du service Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- Dans un déploiement hybride, le service peut être configuré pour protéger votre environnement de messagerie et contrôler le routage de messagerie lorsque vous disposez à la fois de boîtes aux lettres locales et de boîtes aux lettres dans le cloud avec Exchange Online Protection pour le filtrage des messages entrants.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilité d’Office 365 - Protection avancée contre les menaces

La protection avancée contre les menaces est incluse dans Office 365 entreprise E5, Office 365 éducation a5 et Microsoft 365 Business.

Vous pouvez ajouter ce service aux plans d'abonnement Exchange et Office 365 suivants :

- Exchange Online (plan 1)

- Exchange Online (plan 2)

- Exchange Online Kiosk

- Exchange Online Protection

- Office 365 Business Essentials

- Office 365 Business Premium

- Office 365 Entreprise E1

- Office 365 Entreprise E3

- Office 365 Entreprise F1

- Office 365 A1

- Office 365 A3

Pour acheter Office 365 - Protection avancée contre les menaces, reportez-vous à l'article [Office 365 - Protection avancée contre les menaces](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Pour comparer les fonctionnalités de tous les plans, voir [compare Office 365 for business plans](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) et [découvrir la solution Microsoft 365 Enterprise qui vous convient](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Nouveautés d'Office 365 - Protection avancée contre les menaces

Nous continuons à ajouter de nouvelles fonctionnalités à la protection avancée contre les menaces d’Office 365. Pour en savoir plus sur les nouvelles fonctionnalités disponibles pour la protection avancée contre les menaces (ou Microsoft 365 en général), consultez les ressources suivantes :

- [Feuille de route Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Nouveautés d’Office 365 - Protection avancée contre les menaces](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Configuration requise pour Office 365 - Protection avancée contre les menaces

La protection avancée contre les menaces peut être utilisée avec n’importe quel agent de transfert de courrier SMTP, tel que Microsoft Exchange Server. Pour plus d'informations sur les systèmes d'exploitation, les navigateurs web et les langues pris en charge par ce service, voir les sections « Navigateurs pris en charge » et « Langues prises en charge dans EOP » de l'article [Centre d'administration Exchange dans Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilité des fonctionnalités pour les différents plans Protection avancée contre les menaces

Chaque fonctionnalité est indiquée ci-dessous. La mention « Exchange Online » fait généralement référence à la famille de services Office 365 Entreprise.

|**Fonctionnalité**|**Plan de l’ATP 1**<br>(anciennement ATP)|**ATP-plan 2**<br>(anciennement intelligence des menaces <br>individuel| Office 365 Entreprise E5|
|:-----|:-----|:-----|:-----|
|*Configuration, protection et détection*|
|Pièces jointes fiables|Oui|Oui|Oui|
|Liens fiables|Oui|Oui|Oui|
|Stratégies anti-hameçonnage|Oui|Oui|Oui|
|ATP pour SharePoint, OneDrive et Microsoft teams|Oui|Oui|Oui|
|Pièces jointes fiables dans teams|Oui|Oui|Oui|
|Liens fiables dans teams|Non|Non|Non|
|Rapports en temps réel|Oui|Oui|Oui|
|*Automatisation, recherche, correction et éducation*|
|Suivi des menaces|Non|Oui|Oui|
|Explorateur (enquête avancée contre les menaces)|Non|Oui|Oui|
|Réponse automatique aux incidents|Non|Oui|Oui|
|Simulateur d’attaque|Non|Oui|Oui|

## <a name="advanced-threat-protection-atp-capabilities"></a>Fonctionnalités de protection avancée contre les menaces (ATP)

### <a name="safe-attachments"></a>Pièces jointes fiables

[Les pièces jointes approuvées ATP](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) protègent contre les programmes malveillants et les virus inconnus et fournissent une protection contre les menaces pour protéger votre système de messagerie. L'ensemble des messages et pièces jointes qui ne comportent pas de signature connue de virus/programme malveillant sont acheminés vers un environnement spécial dans lequel le service Protection avancée contre les menaces utilise diverses techniques d'analyse et de Machine Learning pour détecter des intentions malveillantes. Si aucune activité suspecte n'est détectée, le message est libéré et remis à la boîte aux lettres.

> [!NOTE]
> L’analyse des pièces jointes approuvées ATP a lieu dans la région où se trouvent vos données Office 365. Pour plus d’informations sur la géographie du centre de données, voir [où se trouvent vos données ?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Liens fiables

La fonctionnalité de [liens fiables ATP](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) protège de manière proactive vos utilisateurs contre les URL malveillantes dans un message ou dans un document Office. La protection reste chaque fois qu’elle sélectionne le lien, car les liens malveillants sont bloqués de manière dynamique alors que des liens valides sont accessibles.

Les liens fiables sont disponibles pour les URL dans les applications suivantes :

- Office 365 ProPlus sur Windows ou Mac

- Office pour le Web (Word pour le Web, Excel pour le Web, PowerPoint pour le Web et OneNote pour le Web)

- Word, Excel, PowerPoint et Visio sous Windows, ainsi que des applications Office sur des appareils iOS et Android

> [!NOTE]
> Les utilisateurs doivent disposer d’une<sup>\*</sup>licence pour la protection avancée contre les menaces, doivent être inclus dans les stratégies de liens fiables ATP et être connectés sur leurs appareils pour que la protection soit mise en place.

<sup>\*</sup>Pour les licences ATP à l’échelle de l’organisation (par exemple, ATP_ENTERPRISE_FACULTY), vous n’avez pas besoin d’attribuer des licences ATP à des utilisateurs individuels.

### <a name="anti-phishing-policies"></a>Stratégies anti-hameçonnage

[Protection contre le hameçonnage](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) pour les messages entrants pour les indicateurs qu’un message peut être une tentative de hameçonnage. Lorsque les utilisateurs sont couverts par des stratégies ATP (pièces jointes fiables, liens fiables ou anti-hameçonnage), les messages entrants sont évalués par plusieurs modèles d’apprentissage automatique qui analysent les messages et l’action appropriée est entreprise en fonction des stratégies configurées.

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP pour SharePoint, OneDrive et Microsoft Teams.

La protection avancée contre [les menaces pour SharePoint, OneDrive et Microsoft teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) permet de détecter et de bloquer des fichiers identifiés comme étant malveillants dans les sites d’équipe et les bibliothèques de documents.

### <a name="real-time-reports"></a>Rapports en temps réel

Les fonctionnalités de surveillance disponibles dans le centre de sécurité & conformité Office 365 incluent des [rapports en temps réel et des](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) informations qui permettent aux administrateurs de la sécurité et de la conformité de se concentrer sur des problèmes à haute priorité, tels que les attaques de sécurité ou l’augmentation activité suspecte. En plus de mettre en surbrillance les zones problématiques, les rapports intelligents et les idées contiennent des recommandations et des liens permettant d’afficher et d’explorer les données et d’effectuer des actions rapides.

### <a name="threat-trackers"></a>Suivi des menaces

Les analyseurs de [menace](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) sont des widgets informatifs et des vues qui fournissent aux utilisateurs autorisés des renseignements sur les problèmes de Cybersecurity susceptibles d’avoir un impact sur votre organisation.

### <a name="explorer"></a>Explorer

L’Explorateur (également appelé Explorateur de menaces) est un rapport en temps réel qui permet aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. Par défaut, ce rapport affiche les données des 7 derniers jours ; Toutefois, les vues peuvent être modifiées pour afficher les données des 30 derniers jours.

Pour plus d’informations sur l’Explorateur (dans Office 365 Advanced Threat Protection Plan 2) et les détections en temps réel (dans Office 365 Advanced Threat Protection Plan 1), voir [Threat Explorer (and Real-Time Detections)](https://docs.microsoft.com/office365/securitycompliance/threat-explorer).

### <a name="attack-simulator"></a>Simulateur d’attaque

Le [simulateur d’attaque](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) permet aux utilisateurs autorisés d’exécuter des scénarios d’attaque réaliste dans votre organisation. Plusieurs types d’attaques sont disponibles, y compris une attaque de Spear Phishing, une attaque par pulvérisation de mot de passe et une attaque de mot de passe en force.
