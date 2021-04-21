---
title: Environnements SharePoint pour le gouvernement américain
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Découvrez la disponibilité des fonctionnalités SharePoint pour les clients cloud du gouvernement américain.
ms.openlocfilehash: cec996804ab0d402d2bcccd89b8bbfb5e7f70905
ms.sourcegitcommit: c34f7acea5e172eb2b29ae42f71e69932def6ac0
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/20/2021
ms.locfileid: "51900774"
---
# <a name="sharepoint-for-us-government-environments"></a>Environnements SharePoint pour le gouvernement américain

Cet article fournit une vue d'ensemble des différences de fonctionnalités entre le cloud du gouvernement des États-Unis et le cloud commercial, comme indiqué dans la description du [service SharePoint.](../../sharepoint-online-service-description/sharepoint-online-service-description.md) SharePoint est disponible pour les environnements GCC (Government Community Cloud), GCC High et DoD. 

Pour plus d'informations sur le cloud pour le gouvernement, notamment sur l'éligibilité et les achats, voir [Microsoft 365 Pour le](./microsoft-365-government-how-to-buy.md)gouvernement - comment acheter . Pour comparer les plans Office 365 pour le gouvernement, consultez [les plans Office 365 Pour le gouvernement.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Pour en savoir plus sur les points de terminaison requis lors de la gestion de la connectivité réseau, voir les points de terminaison [Office 365 U.S. Government GCC High](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) ou Office [365 U.S. Government DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)points de terminaison .

En plus de profiter des fonctionnalités et des fonctionnalités d'Office 365, les organisations bénéficient des fonctionnalités suivantes propres aux environnements cloud du gouvernement américain :

-   Le contenu client de votre organisation est logiquement séparé du contenu client dans les services Commerciaux Office 365 de Microsoft.
-   Le contenu client de votre organisation est stocké aux États-Unis.
-   L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
-   Les environnements cloud du secteur public sont conformes aux certifications et accréditations requises pour les clients du secteur public américain.

Notre objectif est de fournir toutes les fonctionnalités commerciales sharePoint aux environnements cloud du secteur privé. Certaines fonctionnalités ne sont pas disponibles en raison des exigences des clients cloud du gouvernement. D'autres fonctionnalités sont disponibles dans les environnements du secteur public, mais ne sont pas encore disponibles. Reportez-vous aux sections suivantes pour en savoir plus sur la disponibilité des fonctionnalités dans les environnements cloud du secteur privé.

## <a name="developer-features"></a>Fonctionnalités de développeur

Il n'existe aucune différence connue entre les fonctionnalités de développement pour les clients commerciaux et celles des clients cloud du secteur privé.

- Les connexions à des applications externes telles que des sources de données pour les applications sont limitées aux sources situées dans les limites de sécurité système pris en charge par votre environnement public.
- Services Business Connectivity (BCS) est prise en charge pour les scénarios de connectivité dans lesquels les sources de données restent accessibles à l'intérieur des limites de sécurité de votre service cloud.

Si vous utilisez des applications tierces sur des sites, examinez les déclarations de confidentialité et de conformité fournies par les tiers lors de l'évaluation de l'utilisation appropriée de ces services pour votre organisation. Les applications et services tiers peuvent impliquer le stockage, la transmission et le traitement des données client de votre organisation sur des systèmes tiers qui sont en dehors du cloud du gouvernement et qui, par conséquent, ne sont pas couverts par ses engagements en matière de conformité et de protection des données. 

## <a name="it-admin-features"></a>Fonctionnalités d'administration informatique

Voici les différences entre les fonctionnalités d'administration informatique pour les clients commerciaux et celles des clients cloud du secteur privé.

- La modification d'une adresse de site n'est pas disponible pour les clients GCC High
- SharePoint Server hybride n'est pas disponible pour tous les clients cloud du gouvernement
- L'outil de migration SharePoint et le Gestionnaire de migration nécessitent une modification de configuration. Pour plus d'informations, voir la prise en charge [du cloud pour le gouvernement de SPMT.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io n'est pas encore pris en charge
- Multi-géo n'est pas disponible pour tous les clients cloud du gouvernement

Pour plus d'informations sur la migration FastTrack, voir la description du [service Office 365 pour le gouvernement américain.](./office-365-us-government.md#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>Fonctionnalités de sécurité et de conformité

Il n'existe aucune différence connue entre les fonctionnalités de sécurité et de conformité pour les clients commerciaux et celles pour les clients cloud du gouvernement.

Pour plus d'informations sur les fonctionnalités de sécurité et de conformité, voir [le Centre de sécurité & conformité.](../office-365-securitycompliance-center.md)

Pour plus d'informations sur les fonctionnalités Azure Active Directory pour le gouvernement, voir la documentation relative à [Azure Government Security + Identity.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Pour plus d'informations sur les fonctionnalités Azure Information Protection pour le secteur public, voir la description du [service Azure Information Protection Premium Pour le secteur public.](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Sites et contenu

Voici les différences entre les sites et les fonctionnalités de contenu pour les clients commerciaux et celles pour les clients cloud du secteur privé :

- Les composants Web Parts qui s'appuient sur des connexions aux services Internet, tels que amazon Bing, Bing Maps, Twitter et YouTube, ne fonctionneront pas comme prévu.
- La bibliothèque de biens de l'organisation n'est pas disponible
- L'ajout de listes et de pages à Teams n'est pas disponible pour les clients GCC High et DoD
- La fonctionnalité graphique dans SharePoint Online pour GCC High est actuellement désactivée. Tout service qui s'appuie sur Microsoft Graph n'est peut-être pas disponible actuellement
- Les fonctionnalités qui reposent sur les connexions aux services Internet, telles que l'onglet Images boursières, ne fonctionneront pas comme prévu.
- Les notifications d'activité de fichier et de site ne sont pas disponibles
- Le site Web d'actualités tirera uniquement les actualités du site actuel. Les actualités des sites sélectionnés ou des listes d'actualités du hub des sites associés ne sont pas disponibles pour les clients GCC High et DoD

## <a name="search-features"></a>Fonctionnalités de recherche

Voici les différences entre les fonctionnalités de recherche pour les clients commerciaux et celles des clients cloud du secteur privé :

- Recherche Microsoft n'est pas disponible dans GCC.

## <a name="sharing-and-sync"></a>Partage et synchronisation

Pour plus d'informations sur les différences de fonctionnalités entre le cloud commercial et les environnements cloud du secteur privé, voir [Partage de fichiers.](./gcc-high-and-dod.md#file-sharing)

## <a name="plan-for-governance"></a>Planifier la gouvernance

Votre passage au cloud offre des expériences transformatives avec des contrôles d'administration intégrés. Déterminez vos besoins en matière de gouvernance et la façon dont vous pouvez les respecter. Pour plus d'informations, voir Planifier la [gouvernance pour transformer le travail d'équipe avec Microsoft 365.](https://resources.techcommunity.microsoft.com/teamwork-governance/) Vous trouverez des conseils sur les groupes Office 365, SharePoint, Teams et bien plus encore.

## <a name="deploy-sharepoint-for-collaboration"></a>Déployer SharePoint pour la collaboration

Après avoir installé votre organisation dans le cloud microsoft pour le gouvernement des États-Unis, suivez le chemin d'accès de déploiement recommandé décrit dans le centre de ressources sur [l'adoption de SharePoint.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) N'oubliez pas de vous engager avec vos champions de l'adoption et de la gestion des changements.
Vous pouvez également travailler avec [FastTrack](https://www.microsoft.com/fasttrack) ou votre partenaire choisi pour déployer le service auprès de vos utilisateurs.
Visitez le [Centre de](https://www.microsoft.com/trust-center) confidentialité Microsoft pour en savoir plus sur la façon dont Microsoft aborde la sécurité, la confidentialité et la conformité, principes fondamentaux pour la façon dont nous donnent aux organisations la possibilité de servir leurs clients.
