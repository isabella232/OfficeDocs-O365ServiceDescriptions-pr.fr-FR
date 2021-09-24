---
title: SharePoint pour les environnements pour le gouvernement américain
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Découvrez la disponibilité SharePoint fonctionnalités pour les clients cloud du gouvernement des États-Unis.
ms.openlocfilehash: 1c584c3bfd62b7573f4c9bcc0c0fb5402b2d9bef
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59673002"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint pour les environnements pour le gouvernement américain

Cet article fournit une vue d’ensemble des différences de fonctionnalités entre le cloud du gouvernement des États-Unis et le cloud commercial, comme indiqué dans la [description SharePoint service.](../../sharepoint-online-service-description/sharepoint-online-service-description.md) SharePoint est disponible pour les environnements Cloud de la communauté du secteur public (Cloud de la communauté du secteur public), Cloud de la communauté du secteur public High et DoD. 

Pour plus d’informations sur le cloud du gouvernement, y compris sur l’éligibilité et les achats, [voir Microsoft 365 secteurs](./microsoft-365-government-how-to-buy.md)publics - comment acheter . Pour comparer les Office 365 Secteur Public, voir [Office 365 Secteur Public plans.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Pour en savoir plus sur les points de terminaison requis lors de la gestion de la connectivité réseau, voir [Office 365 U.S. Government Cloud de la communauté du secteur public High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) or [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

En plus de profiter des fonctionnalités et des fonctionnalités de Office 365, les organisations bénéficient des fonctionnalités suivantes propres aux environnements cloud du gouvernement américain :

-   Le contenu client de votre organisation est logiquement séparé du contenu client dans les services Office 365 commerciaux de Microsoft.
-   Le contenu client de votre organisation est stocké aux États-Unis.
-   L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
-   Les environnements cloud du secteur public sont conformes aux certifications et accréditations requises pour les clients du secteur public américain.

Notre objectif est de fournir toutes les fonctionnalités commerciales SharePoint aux environnements cloud du gouvernement. Certaines fonctionnalités ne sont pas disponibles en raison des exigences des clients cloud du gouvernement. D’autres fonctionnalités sont disponibles dans les environnements du secteur public, mais ne sont pas encore disponibles. Reportez-vous aux sections suivantes pour en savoir plus sur la disponibilité des fonctionnalités dans les environnements cloud du secteur privé.

## <a name="developer-features"></a>Fonctionnalités de développeur

Il n’existe aucune différence connue entre les fonctionnalités de développement pour les clients commerciaux et les fonctionnalités de développement pour les clients cloud du secteur privé.

- Les connexions à des applications externes telles que des sources de données pour les applications sont limitées aux sources situées dans les limites de sécurité système pris en charge par votre environnement public.
- Services Business Connectivity (BCS) est prise en charge pour les scénarios de connectivité dans lesquels les sources de données restent accessibles à l’intérieur des limites de sécurité de votre service cloud.

Si vous utilisez des applications tierces sur des sites, examinez les déclarations de confidentialité et de conformité fournies par les tiers lors de l’évaluation de l’utilisation appropriée de ces services pour votre organisation. Les applications et services tiers peuvent impliquer le stockage, la transmission et le traitement des données client de votre organisation sur des systèmes tiers qui sont en dehors du cloud du gouvernement et qui, par conséquent, ne sont pas couverts par ses engagements en matière de conformité et de protection des données. 

## <a name="it-admin-features"></a>Fonctionnalités d’administration informatique

Voici les différences entre les fonctionnalités d’administration informatique pour les clients commerciaux et les fonctionnalités d’administration informatique pour les clients cloud du gouvernement.

- La modification d’une adresse de site n’est pas Cloud de la communauté du secteur public clients élevés
- L’outil SharePoint migration et le Gestionnaire de migration nécessitent une modification de configuration. Pour plus d’informations, voir la prise en charge [du cloud pour le gouvernement de SPMT.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io n’est pas encore pris en charge
- Multi-géo n’est pas disponible pour tous les clients cloud du gouvernement

Pour plus d’informations FastTrack migration, voir la [description Office 365 service pour le gouvernement américain.](./office-365-us-government.md#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>Fonctionnalités de sécurité et de conformité

Il n’existe aucune différence connue entre les fonctionnalités de sécurité et de conformité pour les clients commerciaux et les fonctionnalités de sécurité et de conformité pour les clients cloud du gouvernement.

Pour plus d’informations sur les fonctionnalités de sécurité et de conformité, voir [le Centre de sécurité & conformité.](../office-365-securitycompliance-center.md)

Pour plus d’informations Azure Active Directory fonctionnalités pour le gouvernement, consultez [la documentation Azure Government Security + Identity.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Pour plus d’informations sur les fonctionnalités Azure Information Protection pour le secteur public, consultez la description du service [Azure Information Protection Premium Administration.](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

Pour plus d’informations SharePoint Syntex fonctionnalités, voir la [description SharePoint Syntex service.](/office365/servicedescriptions/sharepoint-syntex-service-description/sharepoint-syntex-features)

## <a name="sites-and-content"></a>Sites et contenu

Voici les différences entre les sites et les fonctionnalités de contenu pour les clients commerciaux et les sites et les fonctionnalités de contenu pour les clients cloud du secteur privé :

- Les composants Web Parts qui reposent sur les connexions aux services Internet, tels que les composants Web Bing Cartes Amazon, Bing Cartes, Twitter et YouTube, ne fonctionneront pas comme prévu.
- La bibliothèque de biens de l’organisation n’est pas disponible
- L’ajout de listes et de pages Teams n’est pas disponible pour Cloud de la communauté du secteur public clients Haut et DoD
- Graph fonctionnalités de SharePoint Online pour Cloud de la communauté du secteur public High est actuellement désactivée. Tout service qui s’appuie sur Microsoft Graph n’est peut-être pas disponible actuellement
- Les fonctionnalités qui reposent sur les connexions aux services Internet, telles que l’onglet Images boursières, ne fonctionneront pas comme prévu.
- Les notifications d’activité de fichier et de site ne sont pas disponibles
- Le site Web d’actualités tirera uniquement les actualités du site actuel. Les actualités des sites sélectionnés ou des listes d’actualités du hub des sites associés ne sont pas disponibles pour Cloud de la communauté du secteur public clients Haut et DoD

## <a name="search-features"></a>Fonctionnalités de recherche

Voici les différences entre les fonctionnalités de recherche pour les clients commerciaux et les fonctionnalités de recherche pour les clients cloud du secteur privé :

- Recherche Microsoft n’est pas disponible dans Cloud de la communauté du secteur public.

## <a name="sharing-and-sync"></a>Partage et synchronisation

Pour plus d’informations sur les différences de fonctionnalités entre le cloud commercial et les environnements cloud du secteur privé, voir [Partage de fichiers.](./gcc-high-and-dod.md#file-sharing)

## <a name="plan-for-governance"></a>Planifier la gouvernance

Votre passage au cloud offre des expériences transformatives avec des contrôles d’administration intégrés. Déterminez vos besoins en matière de gouvernance et la façon dont vous pouvez les respecter. Pour plus [d’informations,](https://resources.techcommunity.microsoft.com/teamwork-governance/) voir Planifier la gouvernance afin de transformer le travail Microsoft 365 travail en équipe. Vous trouverez des conseils sur Office 365 groupes, SharePoint, Teams et bien plus encore.

## <a name="deploy-sharepoint-for-collaboration"></a>Déployer des SharePoint pour la collaboration

Après avoir installé votre organisation dans le cloud microsoft pour le gouvernement des États-Unis, suivez le chemin d’accès de déploiement recommandé décrit dans le centre de ressources [SharePoint’adoption.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) N’oubliez pas de vous engager avec vos champions de l’adoption et de la gestion des changements.
Vous pouvez également travailler avec [FastTrack](https://www.microsoft.com/fasttrack) ou votre partenaire choisi pour déployer le service auprès de vos utilisateurs.
Visitez le [Centre de](https://www.microsoft.com/trust-center) confidentialité Microsoft pour en savoir plus sur la façon dont Microsoft aborde la sécurité, la confidentialité et la conformité, principes fondamentaux pour la façon dont nous donnent aux organisations la possibilité de servir leurs clients.

## <a name="configuring-sharepoint-hybrid-configuration-wizard-support-for-all-government-cloud-customers"></a>Configuration de SharePoint prise en charge de l’Assistant Configuration hybride pour tous les clients cloud du gouvernement

L SharePoint de configuration hybride hybride contient la prise en charge SharePoint fonctionnalités hybrides avec des environnements SPO spéciaux.

Vous devez modifier la valeur d’un paramètre lié à l’environnement dans un **fichier.config** pour rendre les fonctionnalités hybrides SharePoint disponibles pour cet environnement. Voir [Fichier de configuration modification.](#editing-configuration-file)

> [!NOTE]
> Pour plus d’informations sur les environnements SPO spéciaux pour lesquels les SharePoint hybrides offrent une prise en charge, voir [Environnements pris en charge.](#supported-environments)

## <a name="editing-configuration-file"></a>Modification du fichier de configuration

1. Installez ou mettez à jour SharePoint’Assistant Configuration hybride.
2. Go to the folder in which the SharePoint Hybrid Configuration Wizard is installed. Par exemple, `%LOCALAPPDATA%\Apps\HybridSP\HybridSP`
3. Lancez **lemicrosoft.online.cse.hybridsp.common.dll.config** dans un éditeur de texte tel que Bloc-notes.
Le contenu de ce fichier est représenté dans la capture d’écran suivante :

:::image type="content" source="../../media/content.png" alt-text="Contenu du fichier de configuration":::

4. Modifiez la valeur du `SPOEnvironmentType` paramètre.
5. Enregistrez les modifications dans **microsoft.online.cse.hybridsp.common.dll.config** fichier.
6. Re-lancez l SharePoint de configuration hybride hybride.
   Les paramètres sont appliqués et les SharePoint hybrides sont disponibles dans l’environnement SPO configuré.

## <a name="supported-environments"></a>Environnements pris en charge

SharePoint hybrides de prise en charge des environnements SPO suivants :

- Public
- PPE
- GCC
- GccHigh
- DoD
- Personnalisé

Si un client définit la valeur sur Personnalisé, les clés et les clés sont utilisées pour définir ces points de terminaison `SPOEnvironmentType` pour cet environnement  `AuthorityEndPoint` `AADGraphEndPoint` `MSGraphEndPoint` SPO personnalisé.

Si la valeur est définie sur une valeur autre que Custom , les clés et les clés sont ignorées et l’Assistant configuration hybride SharePoint utilise des valeurs codées en dur appropriées pour ces types d’environnement `SPOEnvironmentType`  `AuthorityEndPoint` `AADGraphEndPoint` `MSGraphEndPoint` SPO.
