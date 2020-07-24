---
title: Plan de conformité de Microsoft 365 – GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Ces conseils s’appliquent aux professionnels de l’informatique qui encouragent les déploiements d’Office 365 dans des entités gouvernementales américaines fédérales ou d’autres entités qui gèrent les données soumises aux réglementations et aux exigences gouvernementales, où l’utilisation du gouvernement Microsoft 365-GCC High est appropriée pour répondre à ces exigences.
ms.openlocfilehash: f81f2382f41d2ba1aa6fcd5dabc593b20eba7bc1
ms.sourcegitcommit: d4025c73f14b663ffcaa1ef8db4174b51debdae7
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/23/2020
ms.locfileid: "45388070"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Planifier la conformité de Microsoft 365 – GCC High

Ces conseils s’appliquent aux professionnels de l’informatique qui encouragent les déploiements d’Office 365 dans des entités gouvernementales américaines fédérales ou d’autres entités qui gèrent les données soumises aux réglementations et aux exigences gouvernementales, où l’utilisation du gouvernement Microsoft 365-GCC High est appropriée pour répondre à ces exigences.

> [!NOTE]
>Si votre organisation a déjà rempli les conditions requises pour le gouvernement de Microsoft 365 (GCC High éligibilité Requirements) et que celle-ci a été acceptée dans le programme, vous pouvez ignorer les étapes 1 et 2 et passer directement à l’étape 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Étape 1. Déterminer si votre organisation a besoin du gouvernement Microsoft 365 (GCC High) et répond aux exigences d’éligibilité

L’environnement Microsoft 365 Government High est conforme aux exigences gouvernementales américaines pour les services Cloud. En plus de profiter des fonctionnalités et des fonctionnalités d’Office 365, les organisations bénéficient des fonctionnalités suivantes, propres à Microsoft 365 Government :

- Le contenu client de votre organisation est logiquement séparé du contenu client des services Office 365 de Microsoft.
- Le contenu client de votre organisation est stocké aux États-Unis.
- L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
- Microsoft 365 Government : GCC Highs est conforme aux certifications et accréditations requises pour les clients du secteur public américain.

Vous trouverez plus d’informations sur le site Microsoft 365 Government-GCC High offer for US Government customers at [Office 365 Government plans](https://products.office.com/government/compare-office-365-government-plans), y compris sur les conditions d’éligibilité.

La [Description de service Office 365 pour le gouvernement américain](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) décrit les avantages de la plateforme, qui sont centrés sur les exigences de conformité aux États-Unis.

> [!TIP]
> Vous pouvez transférer les tables d’informations de la description de service dans un classeur Excel et ajouter deux colonnes : **pertinentes pour mon organisation y/n**   et **répond aux besoins de mon organisation y/n**. Vous pouvez ensuite consulter cette liste avec vos collègues afin de vous assurer que ce service répond aux besoins de votre organisation.

**Points de décision**:<br/>
- *Déterminez si le gouvernement Microsoft 365-GCC-High est adapté à votre organisation.*
- *Vérifiez que votre organisation répond aux conditions d’éligibilité.*

> [!NOTE]
> Microsoft 365 Government-GCC High est uniquement disponible aux États-Unis. Les clients gouvernementaux non américains peuvent choisir parmi un certain nombre de [plans gouvernementaux Office 365](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Étape 2. S’appliquer pour le gouvernement Microsoft 365-GCC-High

Après avoir décidé que ce service est approprié pour votre organisation, lancez le processus d' [application de ce](https://products.office.com/government/eligibility-validation)service.
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Étape 3. Comprendre le gouvernement Microsoft 365 : GCC-paramètres de sécurité par défaut élevés

Nous vous recommandons de prendre le temps de vérifier soigneusement vos paramètres d’administrateur et de sécurité avant de les modifier et de prendre en compte l’impact sur la conformité avant de modifier les paramètres de sécurité par défaut.

**Point de décision**: *Déterminez si vous allez modifier les paramètres par défaut du gouvernement Microsoft 365 (GCC-High Security), ce qui vous permettra de mieux comprendre l’impact de toutes les modifications que vous pourriez apporter.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Étape 4. Comprendre les fonctionnalités actuellement indisponibles ou désactivées par défaut dans Microsoft 365 Government-GCC-High<sup>1</sup>

Pour répondre aux exigences de nos clients Cloud au niveau public, il existe certaines différences entre les plans Microsoft 365 Government, GCC-High et Enterprise. Consultez le tableau suivant pour voir les fonctionnalités disponibles.

|                                         | Fonctionnalité                                         | État élevé de GCC        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protection des informations & gouvernance** | Archivage                                       | Available              |
|                                         | Étiquettes et stratégies manuelles<sup>2</sup>          | Available              |
|                                         | Application automatique d’étiquettes                      | Dans le backlog d’ingénierie |
|                                         | Étiquettes basées sur des types de données sensibles            | Dans le backlog d’ingénierie |
|                                         | Étiquettes et stratégies associées basées sur les requêtes | Dans le backlog d’ingénierie |
|                                         | Plan de gestion de fichiers                                       | Dans le backlog d’ingénierie |
|                                         | Stratégies recommandées                            | Dans le backlog d’ingénierie |
|                                         | Filtres d’importation actifs                            | Dans le backlog d’ingénierie |
|                                         | Rétention basée sur des événements                           | Dans le backlog d’ingénierie |
|                                         | Révisions avant élimination                              | Dans le backlog d’ingénierie |
|                                         | Obstacles aux informations                            | Available              |
|                                         | Protection contre la perte de données (DLP) pour les fichiers et le courrier électronique  | Available              |
|                                         | DLP pour les conversations de conversation et de canal    | Dans le backlog d’ingénierie |
|                                         | Correspondance exacte des données DLP                            | Dans le backlog d’ingénierie |
|                                         | Explorateur d’activité des étiquettes                         | Dans le backlog d’ingénierie |
|                                         | Classifieurs entraînables                           | Dans le backlog d’ingénierie |
|                                         | Étiquettes de confidentialité et d’étiquetage unifiées         | Dans le backlog d’ingénierie |
| **Gestion des risques internes**             | Chiffrement de messages avancé                     | Available              |
|                                         | Gestion des risques internes                         | Dans le backlog d’ingénierie |
|                                         | Conformité des communications                        | Dans le backlog d’ingénierie |
|                                         | Référentiel sécurisé client                                | Available              |
|                                         | Clé client                                    | Available              |
|                                         | Gestion des accès privilégiés                    | Dans le backlog d’ingénierie |
| **Découvrir & répondre**                  | Découverte électronique principale : conservation inaltérable                            | Available              |
|                                         | Découverte électronique principale : gestion des cas                                 | Available              |
|                                         | Découverte électronique principale : recherche                                          | Available              |
|                                         | Découverte électronique principale : exportation                                          | Available              |
|                                         | Découverte électronique principale : déchiffrement RMS                                  | Available              |
|                                         | Découverte électronique principale : exportation Native                                   | Available              |
|                                         | Découverte électronique principale : traitement avancé                             | Available              |
|                                         | Découverte électronique avancée : Threading de messagerie                                 | Available |
|                                         | Découverte électronique avancée : identification quasi en double                   | Available |
|                                         | Découverte électronique avancée : thèmes                                          | Available |
|                                         | Découverte électronique avancée : codage prédictif                               | Available |
|                                         | Découverte électronique avancée : exportation traitée avec chargement d’un fichier                 | Available |
|                                         | Découverte électronique avancée : balisage                                         | Available |
|                                         | Découverte électronique avancée : visionneuses                                         | Available |
|                                         | Découverte électronique avancée : Redactions                                      | Available |
|                                         | Découverte électronique avancée : filtrage                                       | Available |
|                                         | Découverte électronique avancée : mise en correspondance des dépositaires et des charges de travail                   | Available |
|                                         | Découverte électronique avancée : communications des dépositaires                        | Available |
|                                         | Découverte électronique avancée : réviser les ensembles                                     | Available |
|                                         | Découverte électronique avancée : révision et annotation                             | Available |
|                                         | Découverte électronique avancée : ingestion de non Office 365                        | Available |
|                                         | Découverte électronique avancée : rapport de termes de recherche                              | Available |
| **Gestion de la conformité**               | Score de conformité                                | Dans le backlog d’ingénierie |

<sup>1</sup> le statut identifié est susceptible d’être modifié à mesure que les plans de projet et les priorités sont réévalués.<br/>
<sup>2</sup> l’application manuelle des étiquettes nécessite le [client Azure information protection (AIP) version 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history). 


**Point de décision**: *Déterminez si les fonctionnalités de conformité répondent aux besoins de votre organisation.*
