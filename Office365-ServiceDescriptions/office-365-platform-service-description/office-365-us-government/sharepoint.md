---
title: SharePoint pour les environnements gouvernementaux américains
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Découvrez la disponibilité des fonctionnalités SharePoint pour les clients Cloud du gouvernement américain.
ms.openlocfilehash: 310aa1589aed1156de223bed229ce99ef2f5b69a
ms.sourcegitcommit: ace6cd97a0d3823959e1629929be77489f79b520
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/25/2020
ms.locfileid: "49411603"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint pour les environnements gouvernementaux américains

Cet article fournit une vue d’ensemble des différences de fonctionnalités entre le nuage des États-Unis et le nuage commercial, comme décrit dans la [Description du service SharePoint](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description). SharePoint est disponible pour les environnements de la communauté gouvernementale (GCC), GCC High et DoD. 

Pour plus d’informations sur le Cloud du gouvernement, notamment sur l’éligibilité et les achats, voir [Microsoft 365 Government-Comment acheter](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Pour comparer les plans gouvernementaux Office 365, consultez la rubrique [office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Pour en savoir plus sur les points de terminaison requis lors de la gestion de la connectivité réseau, reportez-vous aux points de [terminaison GCC High office 365 du gouvernement des États-Unis](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) ou [Office 365](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

En plus de profiter des fonctionnalités et des fonctionnalités d’Office 365, les organisations bénéficient des fonctionnalités suivantes, propres aux environnements Cloud du gouvernement américain :

-   Le contenu client de votre organisation est logiquement séparé du contenu client des services Office 365 de Microsoft.
-   Le contenu client de votre organisation est stocké aux États-Unis.
-   L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
-   Les environnements de Cloud gouvernementaux sont conformes aux certifications et accréditations requises pour les clients du secteur public américain.

C’est notre objectif de fournir toutes les fonctionnalités et fonctionnalités SharePoint commerciales aux environnements de Cloud du gouvernement. Certaines fonctionnalités ne sont pas disponibles en raison des exigences des clients du nuage public. D’autres fonctionnalités sont disponibles dans les environnements gouvernementaux, mais ne sont pas encore disponibles. Reportez-vous aux sections suivantes pour en savoir plus sur la disponibilité des fonctionnalités dans les environnements Cloud du gouvernement.

## <a name="developer-features"></a>Fonctionnalités de développeur

Il n’existe pas de différences connues entre les fonctionnalités de développement pour les clients commerciaux et celles destinées aux clients Cloud du secteur public.

- Les connexions aux applications externes telles que les sources de données pour les compléments sont limitées aux sources situées dans les limites de sécurité système prises en charge par votre environnement gouvernemental.
- La fonctionnalité Business Connectivity Services (BCS) est prise en charge pour les scénarios de connectivité dans lesquels les sources de données restent accessibles dans la limite de sécurité pour votre service Cloud.

Si vous utilisez des applications tierces sur les sites, passez en revue les déclarations de confidentialité et de conformité fournies par les tiers lors de l’évaluation de l’utilisation appropriée de ces services pour votre organisation. Les applications et services tiers peuvent impliquer le stockage, la transmission et le traitement des données client de votre organisation sur des systèmes tiers qui se trouvent en dehors du nuage du gouvernement et qui ne sont donc pas couverts par ses engagements en matière de protection des données et de conformité. 

## <a name="it-admin-features"></a>Fonctionnalités d’administration informatique

Voici les différences entre les fonctionnalités d’administrateur informatique pour les clients commerciaux et celles destinées aux clients Cloud du secteur public.

- La modification d’une adresse de site n’est pas disponible pour les clients élevés de GCC
- SharePoint Server hybride n’est pas disponible pour tous les clients du nuage gouvernemental
- L’outil de migration SharePoint et le gestionnaire de migration nécessitent un changement de configuration. Pour plus d’informations, consultez la rubrique [SPMT Government Cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.io n’est pas encore pris en charge
- La fonction multi-géo n’est pas disponible pour tous les clients du nuage gouvernemental

Pour plus d’informations sur la migration FastTrack, voir la [Description du service Office 365 pour le gouvernement américain](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Fonctionnalités de sécurité et de conformité

Il n’existe pas de différences connues entre les fonctionnalités de sécurité et de conformité pour les clients commerciaux et celles destinées aux clients Cloud du secteur public.

Pour plus d’informations sur les fonctionnalités de sécurité et de conformité, consultez la rubrique [security & Compliance Center](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center).

Pour plus d’informations sur les fonctionnalités Azure Active Directory pour le gouvernement, consultez [la rubrique Azure Government Security + Identity documentation](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Pour plus d’informations sur les fonctionnalités Azure information protection pour le gouvernement, voir la [Description du service public Azure information protection Premium](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description). 

## <a name="sites-and-content"></a>Sites et contenu

Voici les différences entre les sites et les fonctionnalités de contenu pour les clients commerciaux et ceux pour les clients Cloud du secteur public :

- Les composants WebPart qui s’appuient sur les connexions aux services Internet, tels que les composants WebPart Amazon Kindle, Bing Maps, Twitter et YouTube, ne fonctionnent pas comme prévu
- La bibliothèque de biens de l’organisation n’est pas disponible
- L’ajout de listes et de pages à teams n’est pas disponible pour les clients de GCC High et DoD.

## <a name="search-features"></a>Fonctionnalités de recherche

Voici les différences entre les fonctionnalités de recherche pour les clients commerciaux et celles destinées aux clients Cloud du secteur public :

- L’intégration de Microsoft Search n’est pas disponible.

## <a name="sharing-and-sync"></a>Partage et synchronisation

Pour connaître les différences de fonctionnalités entre le nuage commercial et les environnements du nuage dans le secteur public, consultez la rubrique [partage de fichiers](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing).

## <a name="plan-for-governance"></a>Planifier la gouvernance

Votre migration vers le Cloud offre des expériences de transformation avec les contrôles d’administration intégrés. Déterminez vos besoins en matière de gouvernance et comment vous pouvez les répondre. Pour plus d’informations, consultez la [planification de la gouvernance afin de transformer le travail d’équipe avec Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) . Vous trouverez des conseils sur les groupes Office 365, SharePoint, teams et bien plus encore.

## <a name="deploy-sharepoint-for-collaboration"></a>Déployer SharePoint pour la collaboration

Une fois que vous avez configuré votre organisation dans le Cloud Microsoft USA Government, suivez le chemin de déploiement recommandé décrit dans le [Centre de ressources d’adoption de SharePoint](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/). N’hésitez pas à vous engager dans votre adoption et les champions responsables de la gestion des modifications.
Vous pouvez également utiliser [FastTrack](https://www.microsoft.com/fasttrack) ou le partenaire que vous avez choisi pour déployer le service auprès de vos utilisateurs.
Visitez le [Centre](https://www.microsoft.com/trust-center) de gestion de la confidentialité Microsoft pour en savoir plus sur la façon dont Microsoft aborde la sécurité, la confidentialité et la conformité, les principes fondamentaux concernant la façon dont nous aidons les organisations à répondre à leurs clients.
