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
ms.openlocfilehash: d315b6e15b9b85d0a336a1a22d43eeb636b40830
ms.sourcegitcommit: 4f91480f1f2d4ce6037c42542e4d8ca1d35adc3c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/04/2020
ms.locfileid: "49576009"
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
> Vous pouvez transférer les tables d’informations de la description de service dans un classeur Excel et ajouter deux colonnes : **pertinentes pour mon organisation y/n** et **répond aux besoins de mon organisation y/n**. Vous pouvez ensuite consulter cette liste avec vos collègues afin de vous assurer que ce service répond aux besoins de votre organisation.

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

Pour répondre aux exigences de nos clients Cloud au niveau public, il existe certaines différences entre les plans d’entreprise et les forfaits Microsoft 365 Government. Consultez le tableau suivant pour voir les fonctionnalités disponibles. Voir [ici](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) pour obtenir les dernières mises à jour du produit de conformité publié sur la feuille de route Microsoft 365.<br><br>

| Domaine | Fonctionnalité | État GCC |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protection des informations**              | Client et scanneur d’étiquetage unifiés         | Available              |
|                                         | Correspondance exacte des données          | Available              |
|                                         | Classification et étiquetage automatiques pour Exchange Online, SharePoint Online et OneDrive                      | En cours de déploiement              |
|                                         | Classification et étiquetage automatiques pour l’application Office (Word, Excel, PowerPoint, Outlook) sur plusieurs plateformes (Web, Android, iOS, Windows et Mac) |  En cours de développement              |
|                                         | Classification et étiquetage automatiques pour les clients Office (mobile)                                       | Dans le backlog d’ingénierie              |
|                                         | Classification et étiquetage automatiques pour teams                            | Dans le backlog d’ingénierie |
|                                         | Analyse de la classification des données : vue d’ensemble et Explorateur de contenu                            | Dans le backlog d’ingénierie |
|                                         | Analyse : classifieurs d’apprentissage automatique avec étiquetage automatique côté service                           | Dans le backlog d’ingénierie  |
|                                         | Analytics : classifieurs d’apprentissage automatique avec étiquetage automatique dans les applications Office/côté client                           | Dans le backlog d’ingénierie  |
|                                         | Chiffrement de messages Office 365 de base (E3)                            | Available              |
|                                         | Chiffrement avancé des messages Office 365 (E5)  | Available              |
|                                         | Clé client pour Office 365    | Available |
|                                         | Ajoutez votre propre clé (BYOK) pour le cycle de vie de la mise en service des clés gérées par le client.                            | Available |
|                                         | Conserver votre propre clé (HYOK) qui s’étend sur Azure information protection et Active Directory (AD) gestion des droits pour les scénarios hautement réglementés (aperçu)                         | Available |
|                                         | Chiffrement à double clé                           | Available |
|                                         | Chiffrement : co-création sur des documents chiffrés à l’aide des applications Web WXP                           | Dans le backlog d’ingénierie |
|                                         | Protection contre la perte de données (DLP) pour les fichiers et le courrier électronique         | Available |
|                                         | DLP pour les conversations de conversation et de canal         | En cours de développement |
|                                         | Point de terminaison DLP | Dans le backlog d’ingénierie |
| **Gouvernance des informations** | Gouvernance des informations : archivage des courriers électroniques                                       | Available              |
|                                         | Gouvernance des informations : verrouillage de conservation          | Available              |
|                                         | Gouvernance des informations : importer PST                      | Available              |
|                                         | Gouvernance des informations : étiquettes de rétention sans enregistrement manuelles            | Available |
|                                         | Gouvernance des informations : Etiquettes de rétention par défaut pour SharePoint, bibliothèques, dossiers et ensembles de documents OneDrive entreprise ; Boîtes de réception Exchange ; et les groupes Office 365 | Available              |
|                                         | Gouvernance des informations : stratégies de rétention à l’ensemble de l’Organisation ; des utilisateurs ou des emplacements spécifiques ; automatiquement en fonction d’une condition spécifique (par exemple, des mots clés ou des informations sensibles); et basé sur un événement                                       | Available              |
|                                         | Gouvernance des informations : stratégies de rétention pour teams                            | Available |
|                                         | Gouvernance des informations : étiquettes de rétention à l’aide de la classification Syntex SharePoint                            | Dans le backlog d’ingénierie |
|                                         | Gouvernance des informations : stratégies de rétention avec des classifieurs dotés de la formation                            | Dans le backlog d’ingénierie |
|                                         | Gouvernance des informations : stratégies de rétention pour l’enregistrement des réunions teams                            | Dans le backlog d’ingénierie |
|                                         | Gouvernance des informations : stratégies de rétention pour Yammer                            | Dans le backlog d’ingénierie |
|                                         | Gestion des enregistrements : classification manuelle des étiquettes d’enregistrement                           | Available              |
|                                         | Gestion des enregistrements : étiquettes d’enregistrement par défaut pour SharePoint, bibliothèques, dossiers et ensembles de documents OneDrive entreprise ; et les groupes Office 365                              | Available              |
|                                         | Gestion des enregistrements : stratégies d’enregistrement automatique basées sur des conditions spécifiques (par exemple, des mots clés ou des informations sensibles); et basé sur un événement                            | Available              |
|                                         | Gestion des enregistrements : examen des dépôts  | Available              |
|                                         | Gestion des enregistrements : gestionnaire de plan de gestion de fichiers    | Available |
|                                         | Gestion des enregistrements : preuve de l’élimination                            | Available |
|                                         | Gestion des enregistrements : contrôle de version des enregistrements                            | Available |
|                                         | Gestion des enregistrements : enregistrements réglementaires (préversion publique)                         | En cours de développement |
|                                         | Gestion des enregistrements : révision de la disposition sur plusieurs étapes | Dans le backlog d’ingénierie |
|                                         | Gestion des enregistrements : utiliser la classification Syntex SharePoint pour appliquer des étiquettes d’enregistrement | Dans le backlog d’ingénierie |
| **Gestion des risques initiés**             | Référentiel sécurisé client                                | Available            |
|                                         | Gestion des risques initiés : indicateurs Office pour Teams, sites SharePoint, messagerie électronique                         | En cours de développement |
|                                         | Gestion des risques initiés : vol de données par le fait de défaire des utilisateurs                        | En cours de développement |
|                                         | Gestion des risques initiés : fuites générales de données                                | En cours de développement              |
|                                         | Gestion des risques initiés : enquête sur les alertes de gestion des risques initiés                                   | En cours de développement              |
|                                         | Gestion des risques initiés : tableau de bord de cas, Explorateur de contenu et modèles de notification | En cours de développement |
|                                         | Gestion des risques initiés : escalade pour l’enquête sur Advanced eDiscovery | En cours de développement|
|                                         | Gestion des risques initiés : indicateurs de périphérique pour l’activité sur Windows 10 Build 1809 et versions ultérieures | Dans le backlog d’ingénierie|
|                                         | Gestion des risques initiés : indicateurs pour la violation de la stratégie de sécurité (aperçu) | Dans le backlog d’ingénierie|
|                                         | Gestion des risques initiés : indicateurs pour les alertes Microsoft Defender pour les points de terminaison (aperçu) | Dans le backlog d’ingénierie|
|                                         | Gestion des risques initiés : modèles de stratégie pour les fuites de données par les utilisateurs prioritaires (aperçu) | Dans le backlog d’ingénierie |
|                                         | Gestion des risques initiés : modèles de stratégie pour les fuites de données par les utilisateurs mécontents (aperçu) | Dans le backlog d’ingénierie |
|                                         | Gestion des risques initiés : modèles de stratégie pour les violations de stratégie de sécurité générale (préversion) | Dans le backlog d’ingénierie |
|                                         | Gestion des risques initiés : modèles de stratégie pour les violations de stratégie de sécurité par les utilisateurs prioritaires, à l’aide des utilisateurs distants, des utilisateurs mécontents (aperçu) | Dans le backlog d’ingénierie |
|                                         | Gestion des risques initiés : personnalisation des stratégies (aperçu) | Dans le backlog d’ingénierie |
|                                         | Gestion des risques initiés : alertes d’exportation (aperçu) | Dans le backlog d’ingénierie |
|                                         | Gestion des risques initiés : groupes d’utilisateurs prioritaires (aperçu) | Dans le backlog d’ingénierie |
|                                         | Conformité de la communication (stratégies de supervision incluses) : créer des stratégies de client, 3 préconfiguré  | En cours de déploiement |
|                                         | Conformité de la communication (stratégies de supervision incluses) : prise en charge des messages Teams, Exchange et Remove teams | En cours de déploiement |
|                                         | Conformité de la communication (stratégies de supervision incluses) : accès aux alertes ; modèles de notifications ; Tableau de bord de stratégie de communication | En cours de déploiement  |
|                                         | Conformité de la communication (stratégies de supervision incluses) : escalade for Advanced eDiscovery | En cours de déploiement |
|                                         | Conformité de la communication (stratégies de supervision incluses) : détecter le contenu adulte | En cours de déploiement |
|                                         | Conformité de la communication : détecte les répétitions du code de violation de conduite dans le temps. | En cours de déploiement |
|                                         | Conformité des communications : prise en charge des autorisations plus granulaires | En cours de déploiement |
|                                         | Conformité des communications : analyse des données de conversation des équipes des utilisateurs avec boîte aux lettres local | En cours de déploiement |
|                                         | Conformité de la communication : conflit de modèle d’intérêt | Dans le backlog d’ingénierie |
|                                         | Conformité des communications : possibilité d’ignorer la signature de courrier électronique ou la clause d’exclusion de responsabilité | Dans le backlog d’ingénierie |
|                                         | Conformité de la communication : main de gestion des risques Insider | Dans le backlog d’ingénierie |
|                                         | Conformité des communications : vérification de l’intégrité de la stratégie et possibilité de suspendre la stratégie | Dans le backlog d’ingénierie |
|                                         | Conformité des communications : traduire le contenu d’intégrité pendant l’enquête | Dans le backlog d’ingénierie |
|                                         | Conformité de la communication : détection Burnout et suicide | Dans le backlog d’ingénierie |
|                                         | Obstacles aux informations | Dans le backlog d’ingénierie |
|                                         | Gestion des accès privilégiés                    | Dans le backlog d’ingénierie |
| **Découvrir & répondre**                  | Découverte électronique principale : conservation inaltérable                            | Available              |
|                                         | Découverte électronique principale : audit                                 | Available              |
|                                         | Découverte électronique principale : gestion des cas                                 | Available              |
|                                         | Découverte électronique principale : exportation                                          | Available              |
|                                         | Découverte électronique principale : exportation Native                                  | Available              |
|                                         | Découverte électronique principale : déchiffrement RMS                                   | Available              |
|                                         | Découverte électronique principale : Centre de gestion de la sécurité de Microsoft pour rechercher et exporter des éléments dans SharePoint et la corbeille OneDrive entreprise                                        | En cours de développement              |
|                                         | Découverte électronique avancée : traitement avancé                             | Available |
|                                         | Découverte électronique avancée : tableau de bord                                 | Available |
|                                         | Découverte électronique avancée : Threading de messagerie                   | Available |
|                                         | Découverte électronique avancée : exportation (téléchargement, exportation, ajout à un autre jeu d’affichage)                                          | Available |
|                                         | Découverte électronique avancée : filtrage                               | Available |
|                                         | Découverte électronique avancée : conservation légale pour les messages de canaux privés teams                 | Available |
|                                         | Découverte électronique avancée : identification quasi en double                                         | Available |
|                                         | Découverte électronique avancée : sources de données non privatives de cœur                                         | Available |
|                                         | Découverte électronique avancée : ingestion de non Office 365                                      | Available |
|                                         | Découverte électronique avancée : codage prédictif                                       | Available |
|                                         | Découverte électronique avancée : exportation traitée avec chargement d’un fichier                   | Available |
|                                         | Découverte électronique avancée : Redactions                        | Available |
|                                         | Découverte électronique avancée : réviser les ensembles                                     | Available |
|                                         | Découverte électronique avancée : examiner les données (données de requête, balises actives, tableau de bord) et annoter (biffer)                             | Available |
|                                         | Découverte électronique avancée : rapport de termes de recherche                        | Available |
|                                         | Découverte électronique avancée : correction d’erreur sur un seul élément                              | Available |
|                                         | EDiscovery avancée : prise en charge de l’exportation PST                              | Available |
|                                         | Découverte électronique avancée : prise en charge de contenu lié à partir de OneDrive et SharePoint Online (pièces jointes modernes)                              | Available |
|                                         | Découverte électronique avancée : balisage                              | Available |
|                                         | Découverte électronique avancée : rapports de client                              | Available |
|                                         | Découverte électronique avancée : thèmes                              | Available |
|                                         | Découverte électronique avancée : visionneuses                              | Available |
|                                         | Découverte électronique avancée : Yammer Advanced eDiscovery dans le centre de conformité Microsoft                              | Available |
|                                         | Découverte électronique avancée : Centre de mise en conformité Microsoft pour rechercher et exporter des éléments dans SharePoint et la corbeille OneDrive entreprise                              | En cours de développement |
|                                         | Découverte électronique avancée : prise en charge des réactions aux équipes                              | En cours de développement |
|                                         | Audit de base                              | Available |
|                                         | Audit avancé : accès à des événements cruciaux (par exemple, mailitemsaccessed)                              | Available |
|                                         | Audit avancé : augmentation de la bande passante par rapport à l’API activité de gestion                              | Available |
|                                         | Audit avancé : conservation légale pour les messages de canaux privés teams                               | Available |
|                                         | Audit avancé : conservation des journaux (1 an)                               | En cours de déploiement |
|                                         | Audit avancé : Centre de sécurité et conformité                               | Available |
|                                         | Audit avancé : rétention à long terme sur les journaux d’audit (10 ans)                               | Dans le backlog d’ingénierie |
|                                         | Audit avancé : événements de transfert de messages et d’envoi de messages                               | Dans le backlog d’ingénierie |
|                                         | Audit avancé : analyses d’audit traitées                               | Dans le backlog d’ingénierie |
|                                         | Audit avancé : événements de terme de recherche dans Exchange Online et SharePoint Online                              | Dans le backlog d’ingénierie |
|    **Gestion de la conformité**            | Centre de sécurité et conformité Microsoft 365                              | Available |
|                                         | Gestionnaire de conformité                              | Available |
|                                         | Microsoft Cloud App Security                              | Dans le backlog d’ingénierie |
|                                         | Prise en charge des caractères codés sur deux octets                              | Dans le backlog d’ingénierie |
|    **Partenaires**            | API Graph pour Advanced eDiscovery                              | En cours de développement |
|                                         | Connecteurs de données internes                              | Dans le backlog d’ingénierie |
|                                         | Connecteurs de données tiers                              | Dans le backlog d’ingénierie |
|                                         | API Graph pour les données d’exportation de teams                              | Dans le backlog d’ingénierie |




<sup>1</sup> le statut identifié est susceptible d’être modifié à mesure que les plans de projet et les priorités sont réévalués.<br/>

**Point de décision**: *Déterminez si les fonctionnalités de conformité répondent aux besoins de votre organisation.*
