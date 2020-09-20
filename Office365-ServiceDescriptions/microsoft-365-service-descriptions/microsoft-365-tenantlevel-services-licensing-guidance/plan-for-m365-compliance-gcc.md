---
title: Plan de conformité de Microsoft 365 – GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Ces conseils s’appliquent aux professionnels de l’informatique qui encouragent les déploiements d’Office 365 dans les entités américaines Federal, State, local, tribal ou territoriale territoriale ou d’autres entités qui gèrent les données soumises aux réglementations et aux exigences gouvernementales, où l’utilisation du gouvernement Microsoft 365-GCC est appropriée pour répondre à ces exigences.
ms.openlocfilehash: af09151b0ab1060c5a00c60d0b05bbd69c3300c0
ms.sourcegitcommit: 638bacac9e663444f7a094d5887476d8a87e3b58
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/18/2020
ms.locfileid: "47962133"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Planifier la conformité de Microsoft 365 (GCC)

Ces conseils s’appliquent aux professionnels de l’informatique qui encouragent les déploiements d’Office 365 dans les entités américaines Federal, State, local, tribal ou territoriale territoriale ou d’autres entités qui gèrent les données soumises aux réglementations et aux exigences gouvernementales, où l’utilisation du gouvernement Microsoft 365-GCC est appropriée pour répondre à ces exigences.

> [!NOTE]
> Si votre organisation a déjà rempli les conditions d’éligibilité du gouvernement Microsoft 365 et que celle-ci est demandée et acceptée dans le programme, vous pouvez ignorer les étapes 1 et 2 et passer directement à l’étape 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Étape 1. Déterminer si votre organisation a besoin de Microsoft 365 Government-GCC et répond aux exigences d’éligibilité

L’environnement Microsoft 365 Government-GCC est conforme aux exigences gouvernementales américaines en matière de services Cloud, notamment FedRAMP modéré et les exigences en matière de loi pénale et de systèmes d’information sur la fiscalité fédérale (types de données CJI et FTI).

En plus de profiter des fonctionnalités et des fonctionnalités d’Office 365, les organisations bénéficient des fonctionnalités suivantes, propres à Microsoft 365 Government :

- Le contenu client de votre organisation est logiquement séparé du contenu client des services Office 365 de Microsoft.

- Le contenu client de votre organisation est stocké aux États-Unis.

- L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.

- Microsoft 365 Government-GCC est conforme aux certifications et accréditations requises pour les clients du secteur public américain.

Vous trouverez plus d’informations sur l’offre de Microsoft 365 Government-GCC pour les clients du gouvernement américain sur [Office 365 Government](https://products.office.com/government/compare-office-365-government-plans), y compris sur les conditions d’éligibilité.

La [Description de service Office 365 pour le gouvernement américain](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) décrit les avantages de la plateforme, qui sont centrés sur les exigences de conformité aux États-Unis.

> [!TIP]
> Vous pouvez transférer les tables d’informations de la description de service dans un classeur Excel et ajouter deux colonnes : **pertinentes pour mon organisation y/n**   et **répond aux besoins de mon organisation y/n**. Vous pouvez ensuite consulter cette liste avec vos collègues afin de vous assurer que ce service répond aux besoins de votre organisation.

> [!NOTE]
> Microsoft 365 Government-GCC est uniquement disponible aux États-Unis. Les clients gouvernementaux non américains peuvent choisir parmi un certain nombre de [plans gouvernementaux Office 365](https://products.office.com/government/compare-office-365-government-plans).

**Points de décision**: <br/>
- *Déterminez si le gouvernement Microsoft 365 est adapté à votre organisation.*
- *Vérifiez que votre organisation répond aux conditions d’éligibilité.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Étape 2. S’appliquer pour le gouvernement Microsoft 365-GCC

Après avoir décidé que ce service est approprié pour votre organisation, lancez le processus d' [application de ce](https://products.office.com/government/eligibility-validation)service.

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Étape 3. Comprendre le gouvernement Microsoft 365-paramètres de sécurité par défaut GCC

Nous vous recommandons de prendre le temps de vérifier soigneusement vos paramètres d’administrateur et de sécurité avant de les modifier et de prendre en compte l’impact sur la conformité avant de modifier les paramètres de sécurité par défaut.

**Point de décision**: *Déterminez si vous allez modifier les paramètres de sécurité du gouvernement Microsoft 365 par défaut, afin de comprendre tout d’abord l’impact des modifications que vous pourriez apporter.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Étape 4. Comprendre les fonctionnalités actuellement indisponibles ou désactivées par défaut dans Microsoft 365 gouvernement – GCC<sup>1</sup>

Pour répondre aux exigences de nos clients Cloud au niveau public, il existe certaines différences entre les plans d’entreprise et les forfaits Microsoft 365 Government. Consultez le tableau suivant pour voir les fonctionnalités disponibles.

|                                         | **Fonctionnalité**                                     | **État GCC**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protection des informations**              | Étiquettes de confidentialité et d’étiquetage unifiées         | Available              |
|                                         | Étiquettes de conteneur pour SharePoint Online, groupes Office          | En cours de déploiement              |
|                                         | Étiquetage automatique basé sur les types de données sensibles pour Excel Online, SharePoint Online, OneDrive entreprise                      | En cours de déploiement              |
|                                         | Étiquettes basées sur des types de données sensibles pour les clients Office Win32 et Mac            | Dans le backlog d’ingénierie |
|                                         | Étiquetage automatique basé sur des types de données sensibles pour Win 32, Mac |  Dans le backlog d’ingénierie              |
|                                         | Étiquetage automatique basé sur des types de données sensibles pour teams                                       |Dans le backlog d’ingénierie              |
|                                         | Étiquetage automatique basé sur les types de données sensibles pour les appareils mobiles                            |Dans le backlog d’ingénierie |
|                                         | Étiquettes et stratégies associées basées sur les requêtes                            | Available |
|                                         | Explorateur d’activité des étiquettes                           | Dans le backlog d’ingénierie  |
|                                         | Classifieurs entraînables                              | Dans le backlog d’ingénierie              |
|                                         | Chiffrement de messages Office 365 de base (E3)                            | Available              |
|                                         | Chiffrement avancé des messages Office 365 (E5)  | Available              |
|                                         | Clé client pour Office 365    | Available |
|                                         | Ajoutez votre propre clé (BYOK) pour le cycle de vie de la mise en service des clés gérées par le client.                            | Available |
|                                         | Conserver votre propre clé (HYOK) qui s’étend sur Azure information protection et Active Directory (AD) gestion des droits pour les scénarios hautement réglementés (aperçu)                         | Available |
|                                         | Chiffrement à double clé                           | Dans le backlog d’ingénierie |
|                                         | Protection contre la perte de données (DLP) pour les fichiers et le courrier électronique         | Available |
|                                         | DLP pour les conversations de conversation et de canal         | En cours de déploiement |
|                                         | Correspondance exacte des données DLP | Dans le backlog d’ingénierie |
|                                         | Point de terminaison DLP | Dans le backlog d’ingénierie |
| **Gouvernance des informations** | Archivage des courriers électroniques                                       | Available              |
|                                         | Verrouillage de conservation          | Available              |
|                                         | Importer des fichiers PST                      | Available              |
|                                         | Étiquettes de rétention non enreg.            | Available |
|                                         | Étiquettes de rétention par défaut pour les bibliothèques, les dossiers et les ensembles de documents SharePoint/OneDrive entreprise ; Boîtes de réception Exchange ; et les groupes Office 365 | Available              |
|                                         | Stratégies de rétention à l’ensemble de l’Organisation ; des utilisateurs ou des emplacements spécifiques ; et automatiquement en fonction d’une condition spécifique (par exemple, des mots clés ou des informations sensibles)                                       | Available              |
|                                         | Stratégies de rétention avec classificateur de formation                            | Dans le backlog d’ingénierie |
|                                         | Stratégies de rétention pour Yammer et Teams                            | Dans le backlog d’ingénierie |
|                                         | Étiquettes des enregistrements manuels                           | Available              |
|                                         | Étiquettes d’enregistrement par défaut pour SharePoint, les bibliothèques, les dossiers et les ensembles de documents OneDrive entreprise ; et les groupes Office 365                              | Available              |
|                                         | Des stratégies d’enregistrement automatiques basées sur des conditions spécifiques (par exemple, des mots clés ou des informations sensibles); et basé sur un événement                            | Available              |
|                                         | Révisions avant élimination  | Available              |
|                                         | Gestionnaire de plan de fichiers    | Available |
|                                         | Preuve de l’élimination                            | Available |
|                                         | Enregistrements réglementaires                         | Dans le backlog d’ingénierie |
|                                         | Application des licences de gestion des enregistrements                           | Dans le backlog d’ingénierie |
|                                         | Révision de la destruction des enregistrements en plusieurs étapes | Dans le backlog d’ingénierie |
|                                         | Explorateur d’activité des étiquettes | Dans le backlog d’ingénierie |
|                                         | Classifieurs entraînables | Dans le backlog d’ingénierie |
|                                         | Étiquettes de confidentialité et d’étiquetage unifiées         | Dans le backlog d’ingénierie |
| **Gestion des risques internes**             | Référentiel sécurisé client                                | Available            |
|                                         | Indicateurs Office pour Teams, sites SharePoint, messagerie électronique                         | En cours de déploiement |
|                                         | Vol de données en faisant part des utilisateurs                        | En cours de déploiement |
|                                         | Fuites de données générales                                | En cours de déploiement              |
|                                         | Analyser les alertes de gestion des risques internes                                   | En cours de déploiement              
|                                         | Tableau de bord des cas d’Insider gestion des risques, Explorateur de contenu et modèles d’avis | En cours de déploiement |
|                                         | Escalade de l’enquête pour la découverte électronique avancée | En cours de déploiement|
|                                         | Fuites de données par les utilisateurs prioritaires (aperçu) | dans le backlog d’ingénierie |
|                                         | Fuites de données par les utilisateurs mécontents (aperçu) | dans le backlog d’ingénierie |
|                                         | Violations de stratégie de sécurité générale (préversion) | dans le backlog d’ingénierie |
|                                         | Violations de stratégie de sécurité par des utilisateurs prioritaires, à l’aide d’utilisateurs distants, d’utilisateurs mécontents (aperçu) | dans le backlog d’ingénierie |
|                                         | Personnalisation de stratégie (aperçu) | dans le backlog d’ingénierie |
|                                         | Exporter des alertes (aperçu) | dans le backlog d’ingénierie |
|                                         | Groupes d’utilisateurs prioritaires (aperçu) | dans le backlog d’ingénierie |
|                                         | Créer des stratégies de client, 3 préconfigurés pour la conformité de la communication (stratégies de supervision incluses)  | En cours de déploiement |
|                                         | Conformité de la communication (y compris les stratégies de supervision) prise en charge de teams, Exchange et supprimer les messages teams | En cours de déploiement |
|                                         | Les alertes d’accès à la conformité de la communication (y compris les stratégies de supervision); modèles de notifications ; Tableau de bord de stratégie de communication | En cours de déploiement  |
|                                         | Conformité de la communication (y compris les stratégies de supervision) escalade de l’enquête pour la découverte électronique avancée | En cours de déploiement |
|                                         | Conformité de la communication (stratégies de supervision incluses) détecter le contenu adulte | En cours de déploiement |
|                                         | Obstacles aux informations | Dans le backlog d’ingénierie |
|                                         | Gestion des accès privilégiés                    | Dans le backlog d’ingénierie |
| **Découvrir & répondre**                  | Découverte électronique principale : conservation inaltérable                            | Available              |
|                                         | Découverte électronique principale : gestion des cas                                 | Available              |
|                                         | Découverte électronique principale : recherche                                          | Available              |
|                                         | Découverte électronique principale : exportation                                          | Available              |
|                                         | Découverte électronique principale : déchiffrement RMS                                  | Available              |
|                                         | Découverte électronique principale : exportation Native                                   | Available              |
|                                         | Découverte électronique principale : audit                                        | Available              |
|                                         | Découverte électronique avancée : traitement avancé                             | Available |
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
|                                         | Audit de base                              | Available |
|                                         | Audit avancé : accès à des événements cruciaux (par exemple, mailitemsaccessed)                              | En cours de déploiement |
|                                         | Conservation du journal d’audit avancé (1 an)                               | En cours de déploiement |
|                                         | Audit avancé augmentation de la bande passante par rapport à l’API activité de gestion                              | En cours de déploiement |
|    **Gestion de la conformité**            | Gestionnaire de conformité et score                              | Dans le backlog d’ingénierie |




<sup>1</sup> le statut identifié est susceptible d’être modifié à mesure que les plans de projet et les priorités sont réévalués.<br/>
<sup>2</sup> l’application manuelle des étiquettes nécessite le [client Azure information protection (AIP) version 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Point de décision**: *Déterminez si les fonctionnalités de conformité répondent aux besoins de votre organisation.*
