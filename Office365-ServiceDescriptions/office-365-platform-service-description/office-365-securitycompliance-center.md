---
title: Centre de sécurité et conformité
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: Le centre de sécurité &amp; conformité est conçu pour vous aider à gérer les fonctionnalités de conformité dans Office 365 pour votre organisation. Des liens vers les fonctionnalités de conformité SharePoint et Exchange existantes regroupent les fonctions de conformité d’Office 365.
ms.openlocfilehash: 4537008977f19ef947ea0bae9a4164cfbe9991d4
ms.sourcegitcommit: ee08ab6a47235054d5029807ab79fba546326273
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/31/2020
ms.locfileid: "49740965"
---
# <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Le [Centre de sécurité &amp; conformité](https://protection.office.com/) est conçu pour vous aider à gérer les fonctionnalités de conformité dans Office 365 pour votre organisation. Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

Pour voir les options de licence dont les utilisateurs peuvent bénéficier des fonctionnalités de conformité de Microsoft 365 à compter du 1er avril 2020, téléchargez la comparaison de licences de conformité Microsoft 365 détaillée. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>&amp;Disponibilité du centre de sécurité conformité pour les offres professionnelles et entreprise

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Microsoft 365 Business Premium | Office 365 E1, Office 365 gouvernement américain G1 | Office 365 E3, Office 365 gouvernement américain G3 | Office 365 E5 | Office 365 F3, Office 365 gouvernement américain F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Protection contre la perte de données pour Exchange Online, SharePoint Online et OneDrive entreprise](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>2</sup> | Non | Non  |Non   | Oui | Oui | Oui | Non  |
|[Étiquettes de désensibilité manuelle](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | Non | Non  |Non   | Oui | Oui | Oui | Non  |
|[cas eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[conservations eDiscovery (y compris les conservations eDiscovery basées sur une requête)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |Non   |Non   |Non  |Non   |Oui   |Oui   |Non   |
|[Exportation de la découverte électronique](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |Non   |Non   |Non   |Non   |Oui   |Oui   |Non   |
|[Audit de base](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |Oui   |Oui   |Oui|Oui   |Oui   |Oui   |Oui   |
|[Office 365 message Encryption (OME) Basic](https://docs.microsoft.com/microsoft-365/compliance/ome)  |Non   |Non   |Non   |Non   |Oui  |Oui   |Non   |

<sup>1</sup> les journaux d’audit de tous les plans qui incluent l’audit de base (à l’exception de E5) sont conservés pendant 90 jours. Dans la mesure où E5 inclut un audit avancé, les journaux d’audit sont conservés pendant un an maximum. Vous pouvez également utiliser l' [API activité de gestion d’Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) pour récupérer des événements à partir du journal d’audit unifié.

<sup>2</sup> requiert le complément de protection contre la perte de données Office 365.

<sup>3</sup> les étiquettes de confidentialité sont également incluses dans Azure information protection P1 et P2.

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>&amp;Disponibilité du centre de sécurité conformité pour les plans autonomes

| Fonctionnalité | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk | SharePoint Online (plan 1) | SharePoint Online (plan 2) | OneDrive Entreprise (plan 1) | OneDrive Entreprise (plan 2) | Skype Entreprise Online (plan 1) | Skype Entreprise Online (plan 2)|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Sécurité de l’application cloud Office 365](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Oui   |
|[Gestion des menaces](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security), telles que le filtrage du courrier électronique et anti-programme malveillant   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Gestion avancée des menaces](https://docs.microsoft.com/office365/securitycompliance/office-365-ti), telle que l’Explorateur de menaces pour les campagnes de hameçonnage   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non  |
|[Référentiel sécurisé client](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Gestion des appareils mobiles](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |Oui   |
|[Protection contre la perte de données pour Exchange Online, SharePoint Online et OneDrive entreprise](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>9</sup>  |Non   |Oui   |Non   |Non   |Oui <sup>7<sup>  |Non  |Oui<sup>10</sup> |Non   |Oui   |
|[Protection contre la perte de données de communication pour Microsoft teams](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Obstacles aux informations](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Gouvernance des informations](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>1</sup>  |Oui<sup>2</sup>  |Oui   |Oui   |Oui   |Oui   |Oui<sup>10</sup>  |Oui<sup>10</sup>  |Oui   |Oui   |
|[Advanced Information Governance](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>3</sup>  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Recherche de contenu](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |Oui   |Oui   |Oui   |Oui   |Oui  | Oui<sup>10</sup>  |Oui<sup>10</sup>  |Oui   |Oui   |
|[cas eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Oui   |Oui   |Oui   |Oui   |Oui   |Oui<sup>10</sup>  |Oui<sup>10</sup>  |Non   |Non   |
|[Exportation de la découverte électronique](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |Non   |Oui   |Non   |Non   |Oui   |Non  |Oui<sup>10</sup> |N °<sup>4</sup>  |N °<sup>4</sup>  |
|[conservations eDiscovery (y compris les conservations eDiscovery basées sur une requête)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |Non   |Oui   |Non   |Non   |Oui   |Non  |Oui<sup>10</sup> |N °<sup>4</sup>  |N °<sup>4</sup>  |
|[Découverte électronique avancée](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Archivage](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |Non   |Oui   |Non   |Oui   |Oui   |Oui<sup>10</sup> |Oui<sup>10</sup>  |Non   |Non   |
|[Audit de base](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|Oui|Oui|Oui|Oui|Oui|Oui<sup>10</sup>|Oui<sup>10</sup>|Non|Non|
|Audit avancé|Non|Non|Non|Non|Non|Non|Non|Non|Non|
|[Conformité de la communication (stratégies de supervision)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |Non   |
|[Chiffrement de messages Office 365 (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |Non   |Non   |Non   |Non   |Oui   |Non   |Non|Non|Non|
|[Chiffrement de messages avancé Office 365](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |Non   |Non   |Non   |Non   |Oui   |Non   |Non|Non|Non|
|[Gestion des accès privilégiés](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |Non   |Non   |Non   |Non   |Oui   |Non   |Non|Non|Non|

<sup>1</sup> la gouvernance des informations permet aux utilisateurs de créer, publier et appliquer manuellement des étiquettes aux documents ; importer des données à l’aide de l’expédition de disque ou sur le réseau. Ces fonctionnalités sont disponibles dans E3 et E5, avec uniquement une disponibilité limitée dans E1. Pour obtenir la liste complète des fonctionnalités disponibles dans E1, E3 et E5, reportez-vous à la comparaison des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> Nécessite l'achat du module complémentaire d'archivage Exchange Online.

<sup>3</sup> la gouvernance des informations avancée vous permet de conserver des informations importantes et de supprimer les informations sans importance en classant les informations en fonction d’une stratégie de rétention ou de suppression ou des deux. Elle inclut des actions intelligentes/automatisées comme la recommandation de stratégies, l’application automatique d’étiquettes à des données, l’application d’étiquettes basées sur des types de données sensibles ou sur des requêtes, la révision de la disposition et l’utilisation de filtres d’importation intelligents. Elle inclut également la fonctionnalité de surveillance permettant de vérifier les communications des employés à des fins de sécurité et de conformité.

<sup>4</sup> Les conversations Skype sont stockées dans le cadre de la boîte aux lettres.

<sup>5</sup> Advanced EDiscovery nécessite Office 365 E5 ou une licence de module complémentaire.

<sup>6</sup> l’archivage Skype se trouve dans la boîte aux lettres de l’utilisateur.

<sup>7</sup> inclut les fichiers stockés dans les référentiels Microsoft Teams.

<sup>8</sup> les journaux d’audit de tous les plans qui incluent l’audit de base sont conservés pendant 90 jours. Vous pouvez également utiliser l' [API activité de gestion d’Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) pour récupérer des événements à partir du journal d’audit unifié.

<sup>9</sup> nécessite le complément de protection contre la perte de données Office 365.

<sup>10</sup> limité aux fichiers stockés dans OneDrive entreprise.

<sup>11</sup> une licence d’archivage Exchange Online plan 2 ou Exchange Online est requise pour mettre une boîte aux lettres d’utilisateur en attente à l’aide d’une stratégie de rétention.
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

Le centre de conformité est disponible dans l’offre E3 plan for Office 365 géré par 21Vianet.
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

Le centre de sécurité & conformité est disponible pour Office 365 Germany. Pour plus d’informations sur Office 365 Germany, voir [office 365 Germany](office-365-germany.md).
