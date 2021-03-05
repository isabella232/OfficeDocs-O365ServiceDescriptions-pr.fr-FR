---
title: Centre de sécurité et de conformité
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: Le Centre de conformité de sécurité est conçu pour vous aider à gérer les fonctionnalités de conformité &amp; dans Office 365 pour votre organisation. Des liens vers les fonctionnalités de conformité SharePoint et Exchange existantes regroupent les fonctions de conformité d’Office 365.
ms.openlocfilehash: 4daf754f5472620482eced63a9970b05a4e61a6c
ms.sourcegitcommit: 02dd535b01c4ca7b19b43188ddd1a1f02c01afb5
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/05/2021
ms.locfileid: "50460193"
---
# <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Le [Centre de conformité de &amp; sécurité](https://protection.office.com/) est conçu pour vous aider à gérer les fonctionnalités de conformité dans Office 365 pour votre organisation. Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

Pour voir les options de gestion des licences pour vos utilisateurs afin de bénéficier des fonctionnalités de conformité de Microsoft 365 à partir du 1er avril 2020, téléchargez la comparaison détaillée des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>Disponibilité &amp; du Centre de conformité de sécurité pour les plans d’entreprise et d’entreprise

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Microsoft 365 Business Premium | Office 365 E1, Office 365 pour le gouvernement américain G1 | Office 365 E3, Office 365 pour le gouvernement américain G3 | Office 365 E5 | Office 365 F3, Office 365 pour le gouvernement américain F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Protection contre la perte de données pour Exchange Online, SharePoint Online et OneDrive](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>Entreprise 2</sup> | Non | Non  |Oui   | Oui | Oui | Oui | Non  |
|[Étiquettes de sensibilité manuelles](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | Non | Non  |Non   | Oui | Oui | Oui | Non  |
|[Cas eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Les détient eDiscovery (y compris les requêtes eDiscovery)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |Non   |Non   |Non  |Non   |Oui   |Oui   |Non   |
|[Exportation de la découverte électronique](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |Non   |Non   |Non   |Non   |Oui   |Oui   |Non   |
|[Audit de base](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |Oui   |Oui   |Oui|Oui   |Oui   |Oui   |Oui   |
|[Chiffrement de messages Office 365 (OME) de base](https://docs.microsoft.com/microsoft-365/compliance/ome)  |Non   |Non   |Non   |Non   |Oui  |Oui   |Non   |

<sup>1 Les</sup> journaux d’audit de tous les plans qui incluent l’audit de base (à l’exception de E5) sont conservés pendant 90 jours. Étant donné que L’E5 inclut l’audit avancé, les journaux d’audit sont conservés pendant un an. En outre, vous pouvez utiliser l’API Activité de gestion [Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) pour récupérer des événements à partir du journal d’audit unifié.

<sup>2 Nécessite</sup> un module de protection contre la perte de données Office 365.

<sup>3 Les étiquettes</sup> de niveau de sensibilité sont également incluses dans Azure Information Protection P1 et P2.

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>Disponibilité &amp; du Centre de conformité de sécurité pour les plans autonomes

| Fonctionnalité | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk | SharePoint Online (plan 1) | SharePoint Online (plan 2) | OneDrive Entreprise (plan 1) | OneDrive Entreprise (plan 2) | Skype Entreprise Online (plan 1) | Skype Entreprise Online (plan 2)|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Sécurité des applications cloud Office 365](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Oui   |
|[Gestion des menaces,](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)telle que le filtrage du courrier et la protection contre les programmes malveillants   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Gestion avancée des menaces,](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)telle que l’Explorateur de menaces pour les campagnes de hameçonnage   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non  |
|[Référentiel sécurisé client](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Gestion des appareils mobiles](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Protection contre la perte de données pour Exchange Online, SharePoint Online et OneDrive](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>Entreprise 9</sup>  |Non   |Oui   |Non   |Non   |Oui <sup>7<sup>  |Non  |Oui<sup>10</sup> |Non   |Oui   |
|[Protection contre la perte de données de communication pour Microsoft Teams](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Obstacles aux informations](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Gouvernance des informations](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>1</sup>  |Oui<sup>2</sup>  |Oui   |Oui   |Oui   |Oui   |Oui<sup>10</sup>  |Oui<sup>10</sup>  |Oui   |Oui   |
|[Gouvernance avancée des informations](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>3</sup>  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Recherche de contenu](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |Oui   |Oui   |Oui   |Oui   |Oui  | Oui<sup>10</sup>  |Oui<sup>10</sup>  |Oui   |Oui   |
|[Cas eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui<sup>10</sup>  |Oui<sup>10</sup>  |Non   |Non   |
|[Exportation de la découverte électronique](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |Non   |Oui   |Non   |Non   |Oui   |Non  |Oui<sup>10</sup> |Non<sup>4</sup>  |Non<sup>4</sup>  |
|[Les détient eDiscovery (y compris les requêtes eDiscovery)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |Non   |Oui   |Non   |Non   |Oui   |Non  |Oui<sup>10</sup> |Non<sup>4</sup>  |Non<sup>4</sup>  |
|[Découverte électronique avancée](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Archivage](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |Non   |Oui   |Non   |Oui   |Oui   |Oui<sup>10</sup> |Oui<sup>10</sup>  |Non   |Non   |
|[Audit de base](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|Oui|Oui|Oui|Oui|Oui|Oui<sup>10</sup>|Oui<sup>10</sup>|Non|Non|
|Audit avancé|Non|Non|Non|Non|Non|Non|Non|Non|Non|
|[Conformité des communications (stratégies de surveillance)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Chiffrement de messages Office 365 (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |Non   |Oui   |Non   |Non   |Oui   |Non   |Non|Non|Non|
|[Chiffrement de messages avancé Office 365](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |Non   |Non   |Non   |Non   |Oui   |Non   |Non|Non|Non|
|[Gestion des accès privilégiés](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |Non   |Non   |Non   |Non   |Oui   |Non   |Non|Non|Non|

<sup>1 La</sup> gouvernance des informations permet aux utilisateurs de créer, de publier et d’appliquer manuellement des étiquettes à des documents ; importer des données à l’aide de l’expédition de disque ou via le réseau. Ces fonctionnalités sont disponibles dans E3 et E5, avec une disponibilité limitée dans E1. Pour obtenir la liste complète des fonctionnalités disponibles dans E1, E3 et E5, consultez la comparaison détaillée des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> Nécessite l'achat du module complémentaire d'archivage Exchange Online.

<sup>3</sup> La gouvernance avancée des informations vous permet de conserver des informations importantes et de supprimer des informations non importantes en classifiant les informations en fonction d’une stratégie de rétention ou de suppression, ou les deux. Il inclut des actions intelligentes/automatisées telles que la recommandation de stratégies, l’application automatique d’étiquettes aux données, l’application d’étiquettes basées sur des types ou requêtes de données sensibles, la révision de la disposition et l’utilisation de filtres d’importation intelligents. Il inclut également la fonctionnalité de surveillance pour examiner les communications des employés à des fins de sécurité et de conformité.

<sup>4</sup> Les conversations Skype sont stockées dans le cadre de la boîte aux lettres.

<sup>5</sup> Advanced eDiscovery nécessite Office 365 E5 ou une licence de modules.

<sup>6</sup> L’archivage Skype se trouve dans la boîte aux lettres de l’utilisateur.

<sup>7 Inclut</sup> les fichiers stockés dans les référentiels Microsoft Teams.

<sup>8 Les journaux</sup> d’audit de tous les plans qui incluent l’audit de base sont conservés pendant 90 jours. En outre, vous pouvez utiliser l’API Activité de gestion [Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) pour récupérer des événements à partir du journal d’audit unifié.

<sup>9 Nécessite</sup> un module de protection contre la perte de données Office 365.

<sup>10 Limité</sup> aux fichiers stockés dans OneDrive Entreprise.

<sup>11 Une</sup> licence Exchange Online Plan 2 ou Archivage Exchange Online est nécessaire pour placer une boîte aux lettres utilisateur en conservation à l’aide d’une stratégie de rétention.
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

Le Centre de conformité est disponible dans le plan E3 pour Office 365 géré par 21Vianet.
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

Le Centre de sécurité & conformité est disponible pour Office 365 Germany. Pour plus d’informations sur Office 365 Germany, voir [Office 365 Germany.](office-365-germany.md)
