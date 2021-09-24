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
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Découvrez les fonctionnalités disponibles dans Microsoft Defender pour Office 365.
ms.openlocfilehash: 591236d6028d57025d2dd7a9cfc5ef80d3617176
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671454"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Description du service Microsoft Defender pour Office 365

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Nouveautés de Microsoft Defender pour Office 365

Nous continuons à ajouter de nouvelles fonctionnalités à Defender pour Office 365. Pour en savoir plus sur les nouvelles fonctionnalités disponibles dans Defender pour Office 365 (ou Microsoft 365 en général), consultez les ressources suivantes :

- [Feuille de route de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap)

- [Nouveautés de Microsoft Defender pour Office 365 - Office 365 | Documents Microsoft](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Fonctionnalités de Defender for Office 365

### <a name="safe-attachments"></a>Pièces jointes fiables

[Coffre pièces jointes protège](/microsoft-365/security/office-365-security/atp-safe-attachments) contre les programmes malveillants et les virus inconnus et fournit une protection zero-day pour protéger votre système de messagerie. Tous les messages et pièces jointes qui n’ont pas de signature de virus/programmes malveillants connus sont acheminés vers un environnement spécial dans lequel Defender pour Office 365 utilise diverses techniques d’apprentissage automatique et d’analyse pour détecter les intentions malveillantes. Si aucune activité suspecte n'est détectée, le message est libéré et remis à la boîte aux lettres.

> [!NOTE]
> Coffre L’analyse des pièces jointes a lieu dans la même région que votre Office 365 de données. Pour plus d’informations sur la géographie du centre de données, [voir Où se trouvent vos données ?](/microsoft-365/enterprise/o365-data-locations)

### <a name="safe-links"></a>Liens fiables

La [fonctionnalité liens Coffre](/microsoft-365/security/office-365-security/atp-safe-links) protection proactive de vos utilisateurs contre les URL malveillantes dans un message ou dans Office document. La protection est activée à chaque fois qu'ils sélectionnent sur le lien ; les liens malveillants sont bloqués dynamiquement tandis que les liens fiables peuvent être ouverts.

Les liens sécurisés sont disponibles pour les URL dans les applications suivantes:

- Applications Microsoft 365 pour les grandes entreprises sur Windows mac

- Office pour le Web (Word pour le Web, Excel pour le Web, PowerPoint pour le Web et OneNote pour le Web)

- Word, Excel et PowerPoint sur Windows

- Canaux et chats Microsoft Teams

> [!NOTE]
> Les utilisateurs doivent être titulaires d’une licence Defender pour Office 365, doivent être inclus dans les stratégies de liens Coffre et doivent être connectés sur leurs appareils pour que la <sup>\*</sup> protection soit en place.
>
> <sup>\*</sup>Pour les licences Defender pour Office 365 à l’échelle de l’organisation (par exemple, ATP_ENTERPRISE_FACULTY), vous n’avez pas besoin d’affecter des licences Defender pour Office 365 à des utilisateurs individuels.
>
> Pour plus d’informations sur Coffre la protection des liens, voir Coffre [liens dans Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documents sécurisés

La [Coffre Documents](/microsoft-365/security/office-365-security/safe-docs) utilise [Microsoft Defender pour point](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) de terminaison pour analyser les documents et les fichiers ouverts en affichage [protégé.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Ce qu'il faut savoir avant de commencer

- Coffre Les documents sont désormais généralement disponibles pour les utilisateurs Office version 2004 (12730.x) ou version supérieure ! Cette fonctionnalité est éteinte par défaut et doit être activée par l’administrateur de sécurité.

- Cette fonctionnalité est uniquement disponible pour les utilisateurs ayant la licence Microsoft 365 E5 ou Microsoft 365 E5 Sécurité (non incluse dans Defender pour les plans Office 365 de licence).

- Word, Excel et PowerPoint sur Windows

- Canaux et chats Microsoft Teams

> [!NOTE]
> Les utilisateurs doivent être titulaires d’une licence Microsoft 365 E5 ou Microsoft 365 E5 Sécurité, doivent être inclus dans les stratégies Coffre Documents et doivent être connectés sur leurs appareils pour que la <sup>\*</sup> protection soit en place.
>
> Pour plus d’informations sur Coffre protection des documents, voir Coffre [Documents dans Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>Protection des SharePoint, OneDrive et des Microsoft Teams

[La protection SharePoint, OneDrive](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) et Microsoft Teams permet de détecter et de bloquer les fichiers identifiés comme malveillants dans les sites d’équipe et les bibliothèques de documents. En outre, la protection Coffre liens est désormais disponible dans les Microsoft Teams et les conversations.

### <a name="anti-phishing-policies"></a>Politiques anti-hameçonnage

[L’anti-hameçonnage recherche](/microsoft-365/security/office-365-security/atp-anti-phishing) dans les messages entrants les indicateurs qu’un message peut être une tentative d’hameçonnage. Lorsque les utilisateurs sont couverts par les stratégies defender pour Office 365 (pièces jointes Coffre, liens Coffre ou anti-hameçonnage), les messages entrants sont évalués par plusieurs modèles d’apprentissage automatique qui analysent les messages et l’action appropriée est entreprise, en fonction des stratégies configurées.

### <a name="real-time-reports"></a>Rapports en temps réel

Les [fonctionnalités](/microsoft-365/security/office-365-security/view-reports-for-atp) de surveillance disponibles dans le Centre de sécurité [&](https://protection.office.com) conformité incluent des rapports et des informations en temps réel qui donnent à vos administrateurs de sécurité et de conformité la possibilité de se concentrer sur les problèmes prioritaires, tels que les attaques de sécurité ou l’augmentation des activités suspectes. Outre la mise en évidence des problèmes, des rapports intelligents et des informations incluent des recommandations et des liens pour afficher et explorer des données et prendre des mesures rapides.

### <a name="threat-explorer"></a>Threat Explorer

L’Explorateur de menaces (également appelé Explorateur) est un rapport en temps réel qui permet aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. Par défaut, ce rapport affiche les données des sept derniers jours . Toutefois, les affichages peuvent être modifiés pour afficher les données des 30 derniers jours.

L’Explorateur contient des affichages, tels que les programmes malveillants (pour le courrier électronique et le contenu), les soumissions, le hameçonnage et tous les e-mails. Pour voir comment l’Explorateur se compare aux détections en temps réel, [téléchargez ce PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Pour plus d’informations sur l’Explorateur (dans Microsoft Defender pour Office 365 Plan 2) et les détections en temps réel (dans Microsoft Defender pour Office 365 Plan 1), voir l’Explorateur de menaces et les [détections](/microsoft-365/security/office-365-security/threat-explorer)en temps réel.

### <a name="real-time-detections"></a>Détections en temps réel

Les détections en temps réel sont des rapports en temps réel qui permettent aux utilisateurs autorisés d’identifier et d’analyser les menaces récentes. Comme dans l’Explorateur, ce rapport affiche par défaut les données des sept derniers jours.

Les détections en temps réel contiennent des affichages, tels que les programmes malveillants (pour le courrier électronique et le contenu), les soumissions et le hameçonnage. Pour comparer les détections en temps réel avec l’Explorateur, [téléchargez ce PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Pour plus d’informations sur l’Explorateur (dans Microsoft Defender pour Office 365 Plan 2) et les détections en temps réel (dans Microsoft Defender pour Office 365 Plan 1), voir l’Explorateur de menaces et les [détections](/microsoft-365/security/office-365-security/threat-explorer)en temps réel.

### <a name="threat-trackers"></a>Suivi des menaces

[Les suivis des menaces](/microsoft-365/security/office-365-security/threat-trackers) sont des widgets informatifs et des vues qui fournissent aux utilisateurs autorisés des renseignements sur les problèmes de cybersécurité qui peuvent avoir un impact sur votre organisation.

### <a name="automated-investigation--response"></a>Réponse automatisée aux & enquête

[Les fonctionnalités](/microsoft-365/security/office-365-security/office-365-air) & de réponse aux appels automatisées (AIR) disponibles dans Defender pour Office 365 Plan 2 vous permet d’exécuter des processus d’examen automatisés en réponse aux menaces connues qui existent aujourd’hui. En automatisant certaines tâches d’examen, votre équipe en charge des opérations de sécurité peut fonctionner plus efficacement. Les mesures correctives, telles que la suppression de messages électroniques malveillants, sont prises après approbation par votre équipe des opérations de sécurité. Pour plus d’informations, [voir comment AIR fonctionne dans Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Formation à la simulation d'attaque

[La formation à la simulation](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) d’attaques est un outil intelligent de gestion des risques sociaux qui automatise la création et la gestion des simulations de hameçonnage. Les simulations aident les clients à détecter, hiérarchiser et corriger les risques de hameçonnage en utilisant des hameçonnages réels et une formation hyper-ciblée pour modifier les comportements des employés.

- L’entraînement de simulation d’attaque est désormais disponible dans ww et Cloud de la communauté du secteur public (sera disponible Cloud de la communauté du secteur public le 21 juin).
- Pour plus d’informations sur la mise en place, voir Commencer à utiliser la formation sur la [simulation d’attaque.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Diverses techniques d’attaque qui appliquent des charges utiles d’hameçonnage réelles et dédupliquées sont disponibles pour répliquer le comportement d’une attaque réelle afin de rendre les simulations de hameçonnage pertinentes.
- Ce service est disponible pour les organisations qui disposent de licences Microsoft 365 E5, Office 365 E5 ou [Microsoft Defender pour Office 365 Plan 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Un sous-ensemble de fonctionnalités est proposé aux clients E3 en tant qu’essai.
- Pour en savoir plus et tester une simulation, voir [Simulation d’une attaque par hameçonnage.](/microsoft-365/security/office-365-security/attack-simulation-training)