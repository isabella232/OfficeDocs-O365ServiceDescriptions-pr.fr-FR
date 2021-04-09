---
title: Plan de conformité de Microsoft 365 – GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Ces conseils sont adaptés aux professionnels de l’informatique qui déploient Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui gèrent des données soumises aux réglementations et exigences gouvernementales, où l’utilisation de Microsoft 365 Pour le gouvernement – GCC High est appropriée pour répondre à ces exigences.
ms.openlocfilehash: 016b3596829337cffb2c5a14813c5927f010e432
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652608"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Planifier la conformité Microsoft 365 : GCC High

Ces conseils sont adaptés aux professionnels de l’informatique qui déploient Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui gèrent des données soumises aux réglementations et exigences gouvernementales, où l’utilisation de Microsoft 365 Pour le gouvernement – GCC High est appropriée pour répondre à ces exigences.

> [!NOTE]
>Si votre organisation a déjà satisfait aux exigences d’éligibilité De Microsoft 365 Pour le gouvernement - GCC Les conditions d’éligibilité élevées ont été appliquées et acceptées dans le programme, vous pouvez ignorer les étapes 1 et 2 et passer directement à l’étape 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Étape 1. Déterminer si votre organisation a besoin de Microsoft 365 Pour le gouvernement – GCC High et répond aux conditions d’éligibilité

L’environnement Microsoft 365 Government - GCC High est conforme aux exigences du gouvernement des États-Unis pour les services cloud. En plus de profiter des fonctionnalités et des fonctionnalités d’Office 365, les organisations bénéficient des fonctionnalités suivantes propres à Microsoft 365 Pour le secteur public : GCC High :

- Le contenu client de votre organisation est logiquement séparé du contenu client dans les services Commerciaux Office 365 de Microsoft.
- Le contenu client de votre organisation est stocké aux États-Unis.
- L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
- Microsoft 365 Pour le gouvernement : GCC High est conforme aux certifications et accréditations requises pour les clients du secteur public américain.

Vous trouverez plus d’informations sur l’offre Microsoft 365 Government – GCC High pour les clients du gouvernement des États-Unis dans les [plans Office 365](https://products.office.com/government/compare-office-365-government-plans)pour le gouvernement, y compris les conditions d’éligibilité.

La [description du service Office 365](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) pour le gouvernement américain décrit les avantages de la plateforme, qui sont centrés sur les exigences de conformité aux États-Unis.

> [!TIP]
> Vous pouvez transférer les tables d’informations dans la description du service dans un manuel Excel et ajouter deux colonnes : Pertinentes pour mon organisation **Y/N** et Répond aux besoins de mon organisation **Y/N**. Vous pouvez ensuite consulter cette liste avec vos collègues pour vérifier que ce service répond aux besoins de votre organisation.

**Points de décision**:<br/>
- *Déterminez si Microsoft 365 Pour le GCC-High est approprié pour votre organisation.*
- *Confirmez que votre organisation répond aux conditions d’éligibilité.*

> [!NOTE]
> Microsoft 365 Pour le gouvernement - GCC High est uniquement disponible aux États-Unis. Les clients non américains peuvent choisir parmi un certain nombre [d’plans Office 365 pour le gouvernement.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Étape 2. Demander à Microsoft 365 Pour le gouvernement – GCC-High

Après avoir décidé que ce service est le bon pour votre organisation, démarrez le processus [d’application de ce service.](https://products.office.com/government/eligibility-validation)
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Étape 3. Comprendre Microsoft 365 Pour le gouvernement : GCC-High de sécurité par défaut

Nous vous recommandons de prendre le temps de consulter attentivement vos paramètres d’administration et de sécurité avant de les modifier et de prendre en compte l’impact sur la conformité avant d’apporter des modifications aux paramètres de sécurité par défaut.

**Point de** décision : déterminez si vous allez modifier l’un des paramètres de sécurité microsoft 365 pour le gouvernement de Microsoft 365 par défaut GCC-High, en résolvant *d’abord l’impact* des modifications que vous pourriez apporter.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Étape 4. Comprendre les fonctionnalités actuellement indisponibles ou désactivées par défaut dans Microsoft 365 Pour le gouvernement : GCC-High<sup>1</sup>

Pour répondre aux exigences de nos clients cloud pour le gouvernement, il existe des différences entre les plans Microsoft 365 Pour le gouvernement – GCC-High et les plans d’entreprise. Reportez-vous au tableau suivant pour voir quelles fonctionnalités sont disponibles. Consultez [ici](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) les dernières mises à jour des produits de conformité publiées dans la feuille de route Microsoft 365.<br><br>

| Domaine                                    | Fonctionnalité                                         | État GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protection des informations**              | Client et scanneur d’étiquetage unifié         | Available              |
|                                         | Correspondance exacte des données          | Available              |
|                                         | Classification et étiquetage automatiques pour Exchange Online, SharePoint Online et OneDrive                      | En cours de déploiement              |
|                                         | Classification et étiquetage automatiques pour les applications Office (Word, Excel, PowerPoint, Outlook) sur le web, Android, iOS, Windows et Mac            | En cours de développement |
|                                         | Classification et étiquetage automatiques pour les clients Office (mobile)                                       | On engineering backlog              |
|                                         | Classification et étiquetage automatiques pour Teams                            | On engineering backlog |
|                                         | Analyse de la classification des données : vue d’ensemble et Explorateur de contenu                            | On engineering backlog |
|                                         | Analyse : classifieurs d’apprentissage automatique avec étiquetage automatique côté service                           | On engineering backlog  |
|                                         | Analyse : classifieurs d’apprentissage automatique avec étiquetage automatique côté client/applications Office                           | On engineering backlog  |
|                                         | Chiffrement de messages Office 365 de base (E3)                            | Available              |
|                                         | Chiffrement de messages Office 365 avancé (E5)  | Available              |
|                                         | Clé client pour Office 365    | Available |
|                                         | Apportez votre propre clé (BYOK) pour le cycle de vie de mise en service de clé gérée par le client                            | Available |
|                                         | Hold Your Own Key (HYOK) qui couvre Azure Information Protection et Active Directory (AD) Rights Management pour les scénarios hautement réglementés (prévisualisation)                         | Available |
|                                         | Chiffrement à double clé                           | Available |
|                                         | Chiffrement : co-auteur sur des documents chiffrés à l’aide d’applications web WXP         | On engineering backlog |
|                                         | Protection contre la perte de données (DLP) pour les fichiers et la messagerie         | Available |
|                                         | DLP pour les conversations et les conversations de canal Teams | On engineering backlog |
|                                         | Point de terminaison DLP | On engineering backlog |
| **Gouvernance des informations** | Gouvernance des informations : archivage du courrier électronique                                       | Available              |
|                                         | Gouvernance des informations : verrouillage de conservation          | Available              |
|                                         | Gouvernance des informations : importer PST                      | Available              |
|                                         | Gouvernance des informations : étiquettes de rétention non-enregistrement manuelles            | Available |
|                                         | Gouvernance des informations : étiquettes de rétention par défaut pour les bibliothèques, dossiers et ensembles de documents SharePoint/OneDrive Entreprise ; Boîtes de réception Exchange ; et groupes Office 365 | Available              |
|                                         | Gouvernance des informations : stratégies de rétention pour l’ensemble de l’organisation ; des emplacements ou des utilisateurs spécifiques ; basées automatiquement sur une condition spécifique (par exemple, des mots clés ou des informations sensibles) ; et basé sur un événement                                       | Available              |
|                                         | Gouvernance des informations : stratégies de rétention pour Teams                            | On engineering backlog |
|                                         | Gouvernance des informations : étiquettes de rétention à l’aide de la classification syntex SharePoint                            | On engineering backlog |
|                                         | Gouvernance des informations : stratégies de rétention avec classifieurs entraidables                            | On engineering backlog |
|                                         | Gouvernance des informations : stratégies de rétention pour l’enregistrement des réunions Teams                            | On engineering backlog |
|                                         | Gouvernance des informations : stratégies de rétention pour Yammer                            | On engineering backlog |
|                                         | Gestion des enregistrements : classification manuelle des étiquettes d’enregistrements                           | Available              |
|                                         | Gestion des enregistrements : étiquettes d’enregistrements par défaut pour SharePoint, les bibliothèques OneDrive Entreprise, les dossiers et les ensembles de documents ; et groupes Office 365                              | Available              |
|                                         | Gestion des enregistrements : stratégies d’enregistrement automatique basées sur des conditions spécifiques (par exemple, des mots clés ou des informations sensibles) ; et basé sur un événement                            | Available              |
|                                         | Gestion des enregistrements : révision de la disposition  | Available              |
|                                         | Gestion des enregistrements : gestionnaire de plan de gestion de fichiers    | Available |
|                                         | Gestion des enregistrements : preuve de destruction                            | Available |
|                                         | Gestion des enregistrements : gestion des versions des enregistrements                         | Available |
|                                         | Gestion des enregistrements : enregistrements réglementaires                         | On engineering backlog |
|                                         | Gestion des enregistrements : révision de la disposition en plusieurs étapes | On engineering backlog |
|                                         | Gestion des enregistrements : utiliser la classification SharePoint Syntex pour appliquer des étiquettes d’enregistrement | On engineering backlog |
| **Gestion des risques internes**             | Référentiel sécurisé client                                | Available            |
|                                         | Gestion des risques internes : indicateurs Office pour Teams, sites SharePoint, messagerie électronique                         | En cours de développement |
|                                         | Gestion des risques internes : vol de données par des utilisateurs qui quittent le site                        | En cours de développement |
|                                         | Gestion des risques internes : fuites générales de données                                | En cours de développement              |
|                                         | Gestion des risques internes : examiner les alertes de gestion des risques internes                                   | En cours de développement              |
|                                         | Gestion des risques internes : tableau de bord de cas, explorateur de contenu et modèles d’avis | En cours de développement |
|                                         | Gestion des risques internes : escalade pour examen pour Advanced eDiscovery | En cours de développement|
|                                         | Gestion des risques internes : indicateurs d’appareil pour l’activité sur Windows 10 build 1809 et supérieures | On engineering backlog|
|                                         | Gestion des risques internes : indicateurs de violation de stratégie de sécurité (aperçu) | On engineering backlog|
|                                         | Gestion des risques internes : indicateurs pour les alertes de point de terminaison Microsoft Defender (aperçu) | On engineering backlog|
|                                         | Gestion des risques internes : modèles de stratégie pour les fuites de données par les utilisateurs prioritaires (aperçu) | On engineering backlog |
|                                         | Gestion des risques internes : modèles de stratégie pour les fuites de données par les utilisateurs non résusés (aperçu) | On engineering backlog |
|                                         | Gestion des risques internes : modèles de stratégie pour les violations générales de stratégie de sécurité (aperçu) | On engineering backlog |
|                                         | Gestion des risques internes : modèles de stratégie pour les violations de stratégie de sécurité par les utilisateurs prioritaires, les utilisateurs qui quittent le programme, les utilisateurs non régrunts (prévisualisation) | On engineering backlog |
|                                         | Gestion des risques internes : personnalisation des stratégies (prévisualisation) | On engineering backlog |
|                                         | Gestion des risques internes : exporter des alertes (aperçu) | On engineering backlog |
|                                         | Gestion des risques internes : groupes d’utilisateurs prioritaires (prévisualisation) | On engineering backlog |
|                                         | Conformité des communications (incl. stratégies de surveillance) : créer des stratégies client, 3 pré-configuré  | En cours de développement |
|                                         | Conformité des communications (incl. stratégies de surveillance) : prise en charge de Teams, Exchange et suppression du message Teams | En cours de développement |
|                                         | Conformité des communications (incl. stratégies de surveillance) : alertes d’accès ; modèles de notification ; tableau de bord de stratégie de communication | En cours de développement  |
|                                         | Conformité des communications (incl. stratégies de surveillance) : escalade pour examen pour Advanced eDiscovery | En cours de développement |
|                                         | Conformité des communications (incl. stratégies de surveillance) : détecter le contenu pour adultes | En cours de développement |
|                                         | Conformité des communications (incl. stratégies de surveillance) : détecte les violations répétées de code de conduite au fil du temps | En cours de déploiement |
|                                         | Conformité des communications (incl. stratégies de surveillance) : prise en charge des autorisations plus granulaires | En cours de déploiement |
|                                         | Conformité des communications (incl. stratégies de surveillance) : analyser les données de conversation Teams des utilisateurs avec une boîte aux lettres sur site | En cours de déploiement |
|                                         | Conformité des communications (incl. stratégies de surveillance) : modèle de conflit d’intérêt | On engineering backlog |
|                                         | Conformité des communications (incl. stratégies de surveillance) : possibilité d’ignorer la signature électronique ou la clause d’exclusion de responsabilité | On engineering backlog |
|                                         | Conformité des communications (incl. stratégies de surveillance) : remise de la gestion des risques internes | On engineering backlog |
|                                         | Conformité des communications (incl. stratégies de surveillance) : vérification de l’état de la stratégie et possibilité de suspendre la stratégie | On engineering backlog |
|                                         | Conformité des communications (incl. stratégies de surveillance) : traduire le contenu d’état d’santé pendant l’examen | On engineering backlog |
|                                         | Conformité des communications (incl. stratégies de surveillance) : détection de l’incendie et de l’incendie | On engineering backlog |
|                                         | Obstacles aux informations | On engineering backlog |
|                                         | Gestion des accès privilégiés                    | On engineering backlog |
| **Découvrir les & répondre**                  | Découverte électronique principale : conservation sur place                            | Available              |
|                                         | Core eDiscovery : gestion des cas                                 | Available              |
|                                         | Core eDiscovery : recherche                                          | Available              |
|                                         | Core eDiscovery : exporter                                          | Available              |
|                                         | Core eDiscovery : déchiffrement RMS                                  | Available              |
|                                         | Core eDiscovery : exportation native                                   | Available              |
|                                         | Core eDiscovery : audit                                        | Available              |
|                                         | Découverte électronique principale : prise en charge étendue du Centre de conformité Microsoft pour rechercher et exporter des éléments dans la Corbeille SharePoint et OneDrive Entreprise                                        | En cours de développement              |
|                                         | Advanced eDiscovery : traitement avancé                             | Available |
|                                         | Advanced eDiscovery : mappage du dépositaire à la charge de travail                             | Available |
|                                         | Advanced eDiscovery : communications des dépositaires                             | Available |
|                                         | Advanced eDiscovery : Tableau de bord                             | Available |
|                                         | Advanced eDiscovery : threads de messagerie                                 | Available |
|                                         | Advanced eDiscovery : exporter (télécharger, exporter, ajouter à un autre jeu à réviser)                   | Available |
|                                         | Advanced eDiscovery : filtrage                                          | Available |
|                                         | Advanced eDiscovery: Legal Hold for Teams private channels messages                               | Available |
|                                         | Advanced eDiscovery : identification quasi-en double                 | Available |
|                                         | Advanced eDiscovery : sources de données non privatives                                         | Available |
|                                         | Advanced eDiscovery : ingestion non Office 365                                         | Available |
|                                         | Advanced eDiscovery : codage prédictif                                      | Available |
|                                         | Advanced eDiscovery : exportation traitée avec le fichier de chargement                                       | Available |
|                                         | Advanced eDiscovery : Redactions                   | Available |
|                                         | Advanced eDiscovery : ensembles de révision                        | Available |
|                                         | Advanced eDiscovery : examiner les données (données de requête, balises intelligentes, tableau de bord) et annoter (redact)                                     | Available |
|                                         | Advanced eDiscovery : rapport de terme de recherche                             | Available |
|                                         | Advanced eDiscovery : correction des erreurs d’élément unique                        | Available |
|                                         | Advanced eDiscovery : prise en charge de l’exportation PST                              | En cours de déploiement |
|                                         | Advanced eDiscovery : prise en charge du contenu lié à partir de OneDrive et SharePoint Online (pièces jointes modernes)                              | Available |
|                                         | Advanced eDiscovery : marquage                              | Available |
|                                         | Advanced eDiscovery : rapports de client                              | Available |
|                                         | Advanced eDiscovery : thèmes                               | Available |
|                                         | Advanced eDiscovery : visionneuses                              | Available |
|                                         | Advanced eDiscovery : Yammer advanced eDiscovery dans le Centre de conformité Microsoft                              | Available |
|                                         | Advanced eDiscovery : prise en charge de LAXK/Double byte pour Advanced eDiscovery                              | En cours de développement |
|                                         | Advanced eDiscovery : prise en charge des réactions teams                             | En cours de développement |
|                                         | Découverte électronique avancée : prise en charge étendue du Centre de conformité Microsoft pour rechercher et exporter des éléments dans la Corbeille SharePoint et OneDrive Entreprise                               | On engineering backlog |
|                                         | Audit de base                              | Available |
|                                         | Audit avancé : accès à des événements essentiels (par exemple, mailitemsaccessed)                              | Available |
|                                         | Audit avancé : augmentation de la bande passante pour l’API activité de gestion                              | Available |
|                                         | Audit avancé : obligation légale pour les messages de canaux privés Teams                              | Available |
|                                         | Audit avancé : rétention des journaux (1 an)                              | En cours de déploiement |
|                                         | Audit avancé : disponibilité du Centre de sécurité et conformité                              | Available |
|                                         | Audit avancé : rétention à plus long terme dans les journaux d’audit (10 ans)                              | On engineering backlog |
|                                         | Audit avancé : événements de publipostage et d’envoi de courrier                              | On engineering backlog |
|                                         | Audit avancé : informations d’audit traitées                              | On engineering backlog |
|                                         | Audit avancé : événements de terme de recherche dans Exchange Online et SharePoint Online                              | On engineering backlog |
|    **Gestion de la conformité**            | Centre de sécurité et conformité Microsoft 365                              | Available |
|                                         | Gestionnaire de conformité                                 | Available              |
|                                         | Microsoft Cloud App Security                                 | Available              |
|                                         | Prise en charge des caractères sur deux byte                                 | On engineering backlog              |
|    **Écosystème**            | API Graph pour Advanced eDiscovery                              | En cours de développement |
|                                         | Connecteurs de données de première partie                                 | On engineering backlog              |
|                                         | Connecteurs de données tiers                                 | On engineering backlog              |
|                                         | API Graph pour les données d’exportation Teams                                 | On engineering backlog              |

<sup>1 L’état</sup> identifié est sujet à modification à mesure que les plans et priorités du projet sont réévalués.<br/>

**Point de décision**: *déterminez si les fonctionnalités de conformité répondent aux besoins de votre organisation.*