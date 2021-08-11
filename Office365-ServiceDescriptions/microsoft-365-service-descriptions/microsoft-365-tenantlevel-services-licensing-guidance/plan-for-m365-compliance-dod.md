---
title: Plan de conformité de Microsoft 365 – Déploiements Département de la Défense (DoD)
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Ces conseils sont adaptés aux professionnels de l’informatique qui déploient des Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui gèrent des données soumises aux réglementations et exigences gouvernementales, lorsque l’utilisation de Microsoft 365 Government – DoD est appropriée pour répondre à ces exigences.
ms.openlocfilehash: 039fef8da2de151828cf9aa3c2cb7e39efb4789012f70666811a8a2ae5d24238
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663327"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Plan de conformité de Microsoft 365 – Déploiements Département de la Défense (DoD)

Ces conseils sont adaptés aux professionnels de l’informatique qui déploient des Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui gèrent des données soumises aux réglementations et exigences gouvernementales, lorsque l’utilisation de Microsoft 365 Government – DoD est appropriée pour répondre à ces exigences.

> [!NOTE]
> Si votre organisation a déjà satisfait aux conditions d’éligibilité Microsoft 365 Government – DoD et a été appliquée et acceptée dans le programme, vous pouvez ignorer les étapes 1 et 2 et passer directement à l’étape 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Étape 1. Déterminer si votre organisation a besoin Microsoft 365 gouvernement - DoD et répond aux exigences d’éligibilité

L’environnement Microsoft 365 Government - DoD est conforme aux exigences du gouvernement des États-Unis pour les services cloud.

En plus de profiter des fonctionnalités et des fonctionnalités de Office 365, les organisations bénéficient des fonctionnalités suivantes qui sont propres à Microsoft 365 secteur privé – DoD :

- Le contenu client de votre organisation est logiquement séparé du contenu client dans les services Office 365 commerciaux de Microsoft.
- Le contenu client de votre organisation est stocké aux États-Unis.
- L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
- Microsoft 365 Gouvernement : DoD est conforme aux certifications et accréditations requises pour les clients du secteur public américain.

Vous trouverez plus d’informations sur l’offre Microsoft 365 Government - DoD pour les clients du gouvernement des États-Unis dans les [plans Office 365 Secteur Public,](https://products.office.com/government/compare-office-365-government-plans)y compris les conditions d’éligibilité.

La [description Office 365 service pour le](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) gouvernement américain décrit les avantages de la plateforme, qui sont centrés sur les exigences de conformité aux États-Unis.

> [!TIP]
> Vous pouvez transférer les tables d’informations dans la description du service dans un workbook Excel et ajouter deux colonnes : Pertinent pour mon organisation **Y/N** et Répond aux besoins de mon organisation **Y/N**. Vous pouvez ensuite consulter cette liste avec vos collègues pour vérifier que ce service répond aux besoins de votre organisation.

**Points de décision**:<br/>
- *Déterminez si Microsoft 365 administration - DoD est approprié pour votre organisation.*
- *Confirmez que votre organisation répond aux conditions d’éligibilité.*

> [!NOTE]
> Microsoft 365 Gouvernement - DoD est uniquement disponible aux États-Unis. Les clients non américains peuvent choisir parmi un certain nombre [d’Office 365 Secteur Public.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Étape 2. Demander une Microsoft 365 pour le gouvernement - DoD

Après avoir décidé que ce service est le bon pour votre organisation, démarrez le processus [d’application de ce service.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Étape 3 : Comprendre Microsoft 365 administration : paramètres de sécurité par défaut du DoD

Nous vous recommandons de prendre le temps de consulter attentivement vos paramètres d’administration et de sécurité avant de les modifier et de prendre en compte l’impact sur la conformité avant d’apporter des modifications aux paramètres de sécurité par défaut.

**Point de** décision : déterminez si vous allez modifier l’un des paramètres de sécurité Microsoft 365 Government - DoD par défaut, en résolvant *d’abord l’impact* des modifications que vous pourriez apporter.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Étape 4. Comprendre les fonctionnalités actuellement indisponibles ou désactivées par défaut dans Microsoft 365 Gouvernement – DoD<sup>1</sup>

Pour répondre aux exigences de nos clients cloud pour le gouvernement, il existe des différences entre les plans Microsoft 365 secteur privé - DoD et Entreprise. Reportez-vous au tableau suivant pour voir quelles fonctionnalités sont disponibles. Consultez [ici](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) les dernières mises à jour des produits de conformité publiées Microsoft 365 feuille de route.<br><br>

| Zone | Fonctionnalité | État du dod |
|------|---------|------------|
| **Protection des informations** | Client et scanneur d’étiquetage unifié | Available |
| | Correspondance exacte des données | Available |
| | Classification et étiquetage automatiques pour Exchange Online, SharePoint Online et OneDrive Entreprise | En cours de déploiement |
| | Classification et étiquetage automatiques pour les applications Office (Word, Excel, PowerPoint, Outlook) sur les plateformes (web, Windows et Mac) | Available |
| | Classification et étiquetage automatiques pour les clients Office - Mobile | On engineering backlog |
| | Classification et étiquetage automatiques pour Teams, Microsoft 365 groupes et sites SharePoint sites | Available |
| | Étiquetage obligatoire | Available |
| | Étiquetage de sensibilité manuelle dans Office applications (iOS, Android, Windows) | Available |
| | Configuration des étiquettes de sensibilité pour la protection de chiffrement uniquement sur Outlook messages | En cours de déploiement |
| **Analyse** | Classification des données : vue d’ensemble et Explorateur de contenu | En cours de déploiement |
| | Analyse : classifieurs d’apprentissage automatique avec étiquetage automatique côté service | En cours de développement |
| | Analyse : classifieurs d’apprentissage automatique avec étiquetage automatique Office applications/client | En cours de déploiement |
| **Chiffrement** | Base chiffrement de messages Office 365 (E3) | Available |
| | Advanced chiffrement de messages Office 365 (E5) | Available |
| | Apportez votre propre clé (BYOK) pour le cycle de vie de mise en service de clé gérée par le client | Available |
| | Clé client pour Office 365 | Available |
| | Chiffrement à double clé | Available |
| **Protection contre la perte de données** | Protection contre la perte de données (DLP) pour les fichiers et la messagerie | Available |
| | DLP pour les Teams conversation et les conversations de canal | Available |
| | DLP : tableau de bord Alertes | En cours de déploiement |
| | Point de terminaison DLP | En cours de développement |
| | DLP sur place | On engineering backlog |
| | Page Vue d’ensemble de la DLP | En cours de développement |
| **Gouvernance des informations** | Gouvernance des informations : archivage du courrier électronique | Available |
| | Gouvernance des informations : verrouillage de conservation | Available |
| | Gouvernance des informations : importer PST | Available |
| | Gouvernance des informations : appliquer manuellement des étiquettes de rétention non-enregistrement | Available |
| | Gouvernance des informations : appliquer des étiquettes de rétention par SharePoint/OneDrive Entreprise bibliothèques, dossiers et ensembles de documents ; Exchange boîtes de réception ; et Office 365 groupes | Available |
| | Gouvernance des informations : appliquer une seule étiquette de rétention par défaut à l’ensemble de l’organisation ; des emplacements ou des utilisateurs spécifiques ; et automatiquement en fonction d’une condition spécifique (par exemple, des mots clés ou des informations sensibles) ; | Available |
| | Gouvernance des informations : appliquer une étiquette par défaut pour Exchange boîtes de réception | Available |
| | Gouvernance des informations : révision de disposition en plusieurs étapes | On engineering backlog |
| | Gouvernance des informations : stratégies de rétention avec classifieurs entraidables | En cours de développement |
| | Gouvernance des informations : stratégies de rétention pour Teams conversation | En cours de déploiement |
| | Gouvernance des informations : stratégies de rétention pour l’enregistrement Teams réunion | Available |
| | Gouvernance des informations : stratégies de rétention pour Teams messages de canal privé | On engineering backlog |
| | Gouvernance des informations : stratégies de rétention et d’étiquetage étendues adaptatives | En cours de développement |
| | Gestion des enregistrements : appliquer manuellement une étiquette d’enregistrement | Available |
| | Gestion des enregistrements : appliquer une étiquette d’enregistrement par SharePoint, OneDrive Entreprise bibliothèques, dossiers et ensembles de documents ; et Office 365 groupes | Available |
| | Gestion des enregistrements : stratégies d’enregistrement automatique basées sur des conditions spécifiques (par exemple, des mots clés ou des informations sensibles) ; et basé sur un événement | Available |
| | Gestion des enregistrements : révision de la disposition | Available |
| | Gestion des enregistrements : gestionnaire de plan de gestion de fichiers | Available |
| | Gestion des enregistrements : preuve de destruction | Available |
| | Gestion des enregistrements : gestion des versions des enregistrements | Available |
| | Gestion des enregistrements : enregistrements réglementaires | Available |
| | Gestion des enregistrements : utiliser SharePoint Syntex classification pour appliquer des étiquettes d’enregistrement | On engineering backlog |
| **Gestion des risques internes** | Référentiel sécurisé client | Available |
| | Gestion des risques internes : tableau de bord de cas, Explorateur de contenu et modèles d’avis | En cours de déploiement |
| | Gestion des risques internes : faire l’objet d’une enquête pour Advanced eDiscovery | En cours de déploiement |
| | Gestion des risques internes : vol de données par des utilisateurs qui quittent le site | En cours de déploiement |
| | Gestion des risques internes : fuites générales de données | En cours de déploiement |
| | Gestion des risques internes : examiner les alertes de gestion des risques internes | En cours de déploiement |
| | Gestion des risques internes : indicateurs Office pour les Teams, les sites SharePoint, la messagerie électronique | En cours de déploiement |
| | Explorateur d’activités de gestion des risques internes | On engineering backlog |
| | Gestion des risques internes : indicateurs d’appareil pour l’activité Windows 10 build 1809 et supérieure | On engineering backlog |
| | Gestion des risques internes : indicateurs pour les alertes de point de terminaison Microsoft Defender | On engineering backlog |
| | Gestion des risques internes : indicateurs de violation de la stratégie de sécurité | On engineering backlog |
| | Gestion des risques internes : modèles de stratégie pour les fuites de données par des utilisateurs non régrunts | On engineering backlog |
| | Gestion des risques internes : modèles de stratégie pour les fuites de données par les utilisateurs prioritaires | On engineering backlog |
| | Gestion des risques internes : modèles de stratégie pour les violations générales de stratégie de sécurité | On engineering backlog |
| | Gestion des risques internes : modèles de stratégie pour les violations de stratégie de sécurité par les utilisateurs prioritaires, les utilisateurs qui quittent le programme, les utilisateurs non régrunts (prévisualisation) | On engineering backlog |
| | Gestion des risques internes : personnalisation des stratégies | On engineering backlog |
| | Gestion des risques internes : exporter des alertes | On engineering backlog |
| | Gestion des risques internes : intégration Microsoft Teams interne | On engineering backlog |
| | Gestion des risques internes : groupes d’utilisateurs prioritaires | On engineering backlog |
| | Conformité des communications : créer des stratégies client, 3 pré-configuré | Available |
| | Conformité des communications : prise en charge Teams, Exchange et suppression Teams message | Available |
| | Conformité des communications : alertes d’accès ; modèles de notification ; tableau de bord de stratégie de communication | Available |
| | Conformité des communications : faire l’objet d’une enquête pour Advanced eDiscovery | Available |
| | Conformité des communications : détecte les violations répétées de code de conduite au fil du temps | Available |
| | Conformité des communications : prise en charge des autorisations plus granulaires | Available |
| | Conformité des communications : analyser Teams de conversation des utilisateurs avec une boîte aux lettres sur site | Available |
| | Conformité des communications : modèle de conflit d’intérêts | Available |
| | Conformité des communications : possibilité d’ignorer la signature électronique ou la clause d’exclusion de responsabilité | En cours de développement |
| | Conformité des communications : possibilité de définir une période de rétention pour une stratégie de conformité des communications | On engineering backlog |
| | Conformité des communications : détecter le contenu adulte | On engineering backlog |
| | Conformité des communications : remise de la gestion des risques internes | En cours de développement |
| | Conformité des communications : vérification de l’état de la stratégie et possibilité de suspendre la stratégie | En cours de développement |
| | Conformité des communications : prise en charge de 7 langues pour les classifieurs de menaces, de harcèlement ciblé et de blasphèmes | En cours de développement |
| | Conformité des communications : traduire le contenu d’état au cours de l’examen | En cours de développement |
| | Obstacles aux informations | En cours de déploiement |
| | Gestion des accès privilégiés | On engineering backlog |
| **Découvrir les & répondre** | Découverte électronique principale : conservation sur place | Available |
| | Core eDiscovery : gestion des cas | Available |
| | Core eDiscovery : recherche | Available |
| | Core eDiscovery : exporter | Available |
| | Core eDiscovery : déchiffrement RMS | Available |
| | Core eDiscovery : exportation native | Available |
| | Core eDiscovery : audit | Available |
| | Core eDiscovery : limites de conformité pour les OneDrive Entreprise | En cours de déploiement |
| | Advanced eDiscovery : traitement avancé | Available |
| | Advanced eDiscovery : prise en charge des nombres d’Advanced eDiscovery | Available |
| | Advanced eDiscovery : mappage du dépositaire à la charge de travail | Available |
| | Advanced eDiscovery : communications des dépositaires | Available |
| | Advanced eDiscovery : Tableau de bord | Available |
| | Advanced eDiscovery : Threads de messagerie | Available |
| | Advanced eDiscovery : exporter (télécharger, exporter, ajouter à un autre jeu à réviser) | Available |
| | Advanced eDiscovery : filtrage | Available |
| | Advanced eDiscovery : identification quasi-en double | Available |
| | Advanced eDiscovery : codage prédictif | Available |
| | Advanced eDiscovery : exportation traitée avec fichier de chargement | Available |
| | Advanced eDiscovery : Actions | Available |
| | Advanced eDiscovery : Ensembles de révision | Available |
| | Advanced eDiscovery : révision et annoter | Available |
| | Advanced eDiscovery : rapport de terme de recherche | Available |
| | Advanced eDiscovery : prise en charge du contenu lié OneDrive et SharePoint Online (pièces jointes modernes) | Available |
| | Advanced eDiscovery : marquage | Available |
| | Advanced eDiscovery : prise en charge Teams réactions | Available |
| | Advanced eDiscovery : rapports de client | Available |
| | Advanced eDiscovery : Thèmes | Available |
| | Advanced eDiscovery : visionneuses | Available |
| | Advanced eDiscovery : Yammer Advanced eDiscovery dans le Centre de conformité Microsoft | Available |
| | Advanced eDiscovery : Optimisation des attentes | En cours de développement |
| | Advanced eDiscovery : prise en charge étendue du Centre de conformité Microsoft pour la recherche et l’exportation d’éléments dans SharePoint, OneDrive Entreprise, Corbeille au cœur et Advanced eDiscovery | En cours de développement |
| | Advanced eDiscovery : procédure de Teams messages de canaux privés | En cours de développement |
| | Advanced eDiscovery : nouveau module de codage prédictif | En cours de développement |
| | Advanced eDiscovery : ingestion non Office 365 | On engineering backlog |
| | Advanced eDiscovery : rapports de client | En cours de développement |
| | Audit de base | Available |
| | Audit avancé : accès à des événements essentiels (par exemple, mailitemsaccessed) | Available |
| | Audit avancé : augmentation de la bande passante pour l’API activité de gestion | Available |
| | Audit avancé : rétention des journaux (1 an) | Available |
| | Audit avancé : événements de publipostage et d’envoi de courrier | Available |
| | Audit avancé : disponibilité du Centre de sécurité et conformité | Available |
| | Audit avancé : rétention à plus long terme dans les journaux d’audit (10 ans) | En cours de développement |
| | Audit avancé : événements de terme de recherche dans Exchange Online et SharePoint Online | On engineering backlog |
| **Gestion de la conformité** | Microsoft 365 Centre de sécurité et conformité | Available |
| | Microsoft Cloud App Security | En cours de développement |
| | Gestionnaire de conformité | Available |
| | Prise en charge des caractères sur deux byte | Available |
| **Écosystème** | Connecteurs de données de première partie : RH | Available |
| | Connecteurs de données de première partie : Instant Bloomberg, Bloomberg Mail, pages LinkedIn Business, ICE Chat | On engineering backlog |
| | Connecteurs de données tiers | On engineering backlog |
| | Graph API pour les Advanced eDiscovery | En cours de développement |
| | Graph API pour l’exportation Teams données | On engineering backlog |

<sup>1 L’état</sup> identifié est sujet à modification à mesure que les plans et priorités du projet sont réévalués.<br/>

**Point de décision**: *déterminez si les fonctionnalités de conformité répondent aux besoins de votre organisation.*
