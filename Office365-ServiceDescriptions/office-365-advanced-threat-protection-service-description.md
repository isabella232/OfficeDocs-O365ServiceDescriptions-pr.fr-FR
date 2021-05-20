---
title: Description du service Microsoft Defender pour Office 365
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 est un service de filtrage des e-mails basé sur le cloud qui aide à protéger votre organisation contre les logiciels malveillants et les virus inconnus en fournissant une protection robuste zero-day, et comprend des fonctionnalités pour protéger votre organisation contre les liens nuisibles en temps réel.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545971"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Description du service Microsoft Defender pour Office 365

Microsoft Defender for Office 365 est un service de filtrage des e-mails basé sur le cloud qui aide à protéger votre organisation contre les logiciels malveillants et les virus inconnus en fournissant une protection robuste zero-day, et comprend des fonctionnalités pour protéger votre organisation contre les liens nuisibles en temps réel. Defender for Office 365 dispose de fonctionnalités de reporting et de traçabilité d’URL riches qui donnent aux administrateurs un aperçu du type d’attaques qui se produisent dans votre organisation.

Voici les principales façons dont vous pouvez utiliser Defender pour la protection Office 365 la protection des messages :

- Dans un scénario defender for Office 365 filtrant uniquement, Defender for Office 365 offre une protection par e-mail basée sur le cloud pour votre environnement Exchange Server sur place ou toute autre solution de messagerie SMTP sur place.

- Defender for Office 365 peut être activé pour protéger les Exchange Online boîtes aux lettres hébergées dans le cloud. Pour en savoir plus sur Exchange Online, consultez la [description Exchange Online service .](exchange-online-service-description/exchange-online-service-description.md)

- Dans un déploiement hybride, Defender for Office 365 peut être configuré pour protéger votre environnement de messagerie et contrôler le routage du courrier lorsque vous avez un mélange de boîtes aux lettres sur place et cloud avec des Exchange Online Protection pour le filtrage des e-mails entrants.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender pour la Office 365 disponibles

Microsoft Defender for Office 365 Plan 2 est inclus dans Office 365 E5, Office 365 A5, Microsoft 365 E5 Sécurité et Microsoft 365 E5 comme spécifié ici: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Défenseur du Office 365 plan 1 est inclus dans Microsoft 365 Business Premium.

Vous pouvez ajouter Defender for Office 365 aux plans d’abonnement Exchange Microsoft 365 suivants :

- Exchange Online (plan 1)

- Exchange Online (plan 2)

- Exchange Online Kiosk

- Exchange Online Protection

- Microsoft 365 Business Basic

- Microsoft 365 Business Standard

- Office 365 Entreprise E1

- Office 365 Entreprise E3

- Office 365 Entreprise F3

- Office 365 A1

- Office 365 A3

Pour acheter Microsoft Defender pour Office 365, voir [Microsoft Defender pour Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Pour plus d’informations sur les abonnements qui permettent aux utilisateurs de Microsoft Defender pour Office 365, consultez le tableau de [comparaison d’abonnement complet](https://go.microsoft.com/fwlink/?linkid=2139145).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Nouveautés dans Microsoft Defender pour Office 365

Nous continuons d’ajouter de nouvelles fonctionnalités à Defender for Office 365. Pour en savoir plus sur les nouvelles fonctionnalités à venir à Defender Office 365 (ou Microsoft 365 en général), voir les ressources suivantes:

- [Feuille de route de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Nouveautés dans Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Exigences pour Microsoft Defender pour Office 365

Defender for Office 365 peut être utilisé avec n’importe quel agent de transfert de courrier SMTP, comme Microsoft Exchange Server. Pour plus d’informations sur les systèmes d’exploitation, les navigateurs Web et les langues pris en charge par Defender for Office 365, consultez les sections « Navigateurs pris en charge » et « Langues prises en [charge » dans Exchange un centre d’administration en Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilité des fonctionnalités sur defender pour Office 365 plans

Chaque fonctionnalité est indiquée ci-dessous. La mention « Exchange Online » fait généralement référence à la famille de services  Office 365 Entreprise.<br><br>

| Fonctionnalité | Microsoft Defender pour Office 365 Plan 1 | Microsoft Defender pour Office 365 Plan 2 | Microsoft 365 E5 / Sécurité A5|
|:-----|:-----|:-----|:-----|
|*Configuration, protection et détection*|
|[Pièces jointes fiables](#safe-attachments)|Oui|Oui|Oui|
|Pièces jointes sûres dans Teams|Oui|Oui|Oui|
|[Liens fiables](#safe-links)|Oui|Oui|Oui|
|[Documents sécurisés](#safe-documents)|Non|Non|Oui|
|Liens fiables dans Teams|Oui|Oui|Oui|
|[ATP pour SharePoint, OneDrive et Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Oui|Oui|Oui|
|[Stratégies anti-hameçonnage](#anti-phishing-policies).|Oui|Oui|Oui|
|[Rapports en temps réel](#real-time-reports)|Oui|Oui|Oui|
|*Automatisation, enquête, assainissement et éducation*|
|[Suivi des menaces](#threat-trackers)|Non|Oui|Oui|
|Enquête sur les menaces (enquête avancée sur les menaces)|[Détections en temps réel](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Réponse automatisée en cas d’incident](#automated-incident-response)|Non|Oui|Oui|
|[Formation à la simulation d’attaque](#attack-simulation-training)|Non|Oui|Oui|
|*Intégration avec [Microsoft 365 Défenseur](/microsoft-365/security/mtp/microsoft-threat-protection)*|Non|Oui|Oui|

> [!NOTE]
> Si votre locataire n’Office de Microsoft Defender que pour une licence d’essai P2 ou Office 365 une licence d’essai E5, sans autre licence éligible pour Microsoft 365 Defender, vous ne pourrez pas accéder à Microsoft 365 Defender. Pour en savoir plus sur la licence MTP, [consultez Microsoft 365 exigences defender](/microsoft-365/security/mtp/prerequisites).

## <a name="defender-for-office-365-capabilities"></a>Défenseur des capacités Office 365'argent

### <a name="safe-attachments"></a>Pièces jointes fiables

[Safe Attachments protège](/microsoft-365/security/office-365-security/atp-safe-attachments) contre les logiciels malveillants et les virus inconnus, et fournit une protection de jour zéro pour protéger votre système de messagerie. Tous les messages et pièces jointes qui n’ont pas de signature de virus/malware connue sont acheminés vers un environnement spécial où Defender for Office 365 utilise une variété de techniques d’apprentissage automatique et d’analyse pour détecter les intentions malveillantes. Si aucune activité suspecte n'est détectée, le message est libéré et remis à la boîte aux lettres.

> [!NOTE]
> La numérisation des pièces jointes sûres a lieu dans la même région où Office 365 données résident. Pour plus d’informations sur la géographie des centres de données, [voir Où se trouvent vos données ?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Liens sûrs

La [fonction Liens](/microsoft-365/security/office-365-security/atp-safe-links) sûrs protège proactivement vos utilisateurs contre les URL malveillantes dans un message ou dans un document Office malveillant. La protection est activée à chaque fois qu'ils sélectionnent sur le lien ; les liens malveillants sont bloqués dynamiquement tandis que les liens fiables peuvent être ouverts.

Les liens sécurisés sont disponibles pour les URL dans les applications suivantes:

- Applications Microsoft 365 pour les grandes entreprises sur Windows ou Mac

- Office pour le Web (Word pour le Web, Excel pour le Web, PowerPoint pour le Web et OneNote pour le Web)

- Mot, Excel, et PowerPoint sur Windows

- Canaux et chats Microsoft Teams

> [!NOTE]
> Les utilisateurs doivent être autorisés pour Defender for Office 365 <sup>\*</sup> , doivent être inclus dans les politiques de liens sûrs, et doivent être connectés sur leurs appareils pour la protection d’être en place.
>
> <sup>\*</sup>Pour les licences Defender for Office 365 (par exemple, ATP_ENTERPRISE_FACULTY), vous n’avez pas besoin d’attribuer des licences Defender for Office 365 à des utilisateurs individuels.
>
> Pour plus d’informations sur la protection des liens sûrs, [consultez les liens sûrs dans Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documents sécurisés

La [fonction Documents sûrs](/microsoft-365/security/office-365-security/safe-docs) utilise Microsoft Defender pour [Endpoint pour](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) numériser les documents et les fichiers qui sont ouverts dans La vue [protégée](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

Ce qu'il faut savoir avant de commencer

- Safe Documents est maintenant généralement disponible pour les utilisateurs avec Office version 2004 (12730.x) ou plus! Cette fonctionnalité est éteinte par défaut et devra être activée par l’administrateur de sécurité.

- Cette fonctionnalité n’est disponible que pour les utilisateurs avec la Microsoft 365 E5 ou Microsoft 365 E5 Sécurité licence (non incluse dans Defender for Office 365 plans).

- Mot, Excel, et PowerPoint sur Windows

- Canaux et chats Microsoft Teams

> [!NOTE]
> Les utilisateurs doivent être titulaires d’une licence pour Microsoft 365 E5 ou Microsoft 365 E5 Sécurité , doivent être inclus dans les politiques de documents sûrs et doivent être connectés à leurs appareils <sup>\*</sup> pour que la protection soit en place.
>
> Pour plus d’informations sur la protection des documents sûrs, [consultez les documents sûrs dans Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>Protection avancée contre les menaces pour SharePoint, OneDrive et Microsoft Teams

[ATP pour les SharePoint, OneDrive et Microsoft Teams permet de](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) détecter et de bloquer les fichiers identifiés comme malveillants dans les sites d’équipe et les bibliothèques de documents. En outre, la protection Safe Links est désormais disponible dans les Microsoft Teams et les chats.

### <a name="anti-phishing-policies"></a>Politiques anti-hameçonnage

[Anti-phishing vérifie](/microsoft-365/security/office-365-security/atp-anti-phishing) les messages entrants pour les indicateurs qu’un message peut être une tentative de phishing. Lorsque les utilisateurs sont couverts par les stratégies Defender for Office 365 (pièces jointes sûres, liens sûrs ou anti-phishing), les messages entrants sont évalués par plusieurs modèles d’apprentissage automatique qui analysent les messages et les mesures appropriées sont prises, en fonction des stratégies configurées.

### <a name="real-time-reports"></a>Rapports en temps réel

Les fonctionnalités de surveillance disponibles dans le Security & Compliance Center () incluent des rapports et des informations en temps réel qui permettent à vos [https://protection.office.com](https://protection.office.com) administrateurs de sécurité et de conformité de se concentrer sur des questions hautement prioritaires, telles que les attaques de sécurité ou l’augmentation des activités suspectes. [](/microsoft-365/security/office-365-security/view-reports-for-atp) En plus de mettre en évidence les problèmes, les rapports et les idées intelligents comprennent des recommandations et des liens pour afficher et explorer les données et prendre des mesures rapides.

### <a name="explorer"></a>Explorer

L’Explorateur (également appelé « Explorateur de menaces ») est un rapport en temps réel qui permet aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. Par défaut, ce rapport affiche les données des sept derniers jours; toutefois, les vues peuvent être modifiées pour afficher les données des 30 derniers jours.

Explorer contient des vues, telles que malware (pour le courrier électronique et le contenu), Soumissions, Phish, et tous les e-mails. Pour voir comment Explorer se compare aux détections en temps réel, [téléchargez ce PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Pour plus d’informations sur Explorer (dans Microsoft Defender for Office 365 Plan 2) et les détections en temps réel (dans Microsoft Defender for Office 365 Plan 1), consultez [Threat Explorer et les détections en temps réel](/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Détections en temps réel

Les détections en temps réel sont des rapports en temps réel qui permettent aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. Semblable à Explorer, par défaut, ce rapport affiche les données des sept derniers jours.

Les détections en temps réel contiennent des vues, telles que malware (pour le courrier électronique et le contenu), Soumissions et Phish. Pour voir comment les détections en temps réel se comparent à Explorer, [téléchargez ce PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Pour plus d’informations sur Explorer (dans Microsoft Defender for Office 365 Plan 2) et les détections en temps réel (dans Microsoft Defender pour Office 365 Plan 1), [voir Threat Explorer (et détections en temps réel).](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Suivi des menaces

[Les trackers de menaces](/microsoft-365/security/office-365-security/threat-trackers) sont des widgets et des vues informatifs qui fournissent aux utilisateurs autorisés des informations sur les problèmes de cybersécurité qui pourraient avoir un impact sur votre organisation.

### <a name="automated-incident-response"></a>Réponse automatisée en cas d’incident

[Les capacités automatisées](/microsoft-365/security/office-365-security/office-365-air) d’intervention en cas d’incident (AIR) disponibles dans Defender for Office 365 Plan 2 vous permettent d’exécuter des processus d’enquête automatisés en réponse aux menaces bien connues qui existent aujourd’hui. En automatiser certaines tâches d’enquête, votre équipe des opérations de sécurité peut fonctionner plus efficacement et plus efficacement. Les mesures correctives, telles que la suppression des messages électroniques malveillants, sont prises sur approbation par votre équipe des opérations de sécurité. Pour en savoir plus, [voir Comment fonctionne AIR dans Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Formation à la simulation d’attaque

[La formation en simulation d’attaque](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) est un outil intelligent de gestion des risques sociaux qui automatise la création et la gestion de simulations de phishing. Les simulations aident les clients à détecter, hiérarchiser et corriger les risques d’hameçonnage en utilisant des leurres phish du monde réel et une formation hyper ciblée pour changer les comportements des employés.

- La formation en simulation d’attaque est maintenant disponible dans ww et Cloud de la communauté du secteur public (sera en Cloud de la communauté du secteur public à partir du 21 juin).
- Pour plus d’informations sur la façon de commencer, voir [Démarrer à l’aide de la formation de simulation d’attaque](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).
- Diverses techniques d’attaque qui appliquent des charges utiles de phishing déarmées et réelles sont disponibles qui reproduisent le comportement des attaquants du monde réel pour rendre les simulations de phishing pertinentes.
- Ce service est disponible pour les organisations qui ont des licences Microsoft 365 E5, Office 365 E5 ou [Microsoft Defender pour Office 365 licences Plan 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Un sous-ensemble de fonctionnalités est offert aux clients de l’E3 à titre d’essai.
- Pour en savoir plus et essayer une simulation, voir [Simuler une attaque de phishing](/microsoft-365/security/office-365-security/attack-simulation-training).