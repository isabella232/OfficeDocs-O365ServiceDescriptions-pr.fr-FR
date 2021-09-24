---
title: Plan de conformité de Microsoft 365 – Déploiements Département de la Défense (DoD)
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Ces conseils sont adaptés aux professionnels de l’informatique qui déploient des Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui gèrent des données soumises aux réglementations et exigences gouvernementales, lorsque l’utilisation de Microsoft 365 Government – DoD est appropriée pour répondre à ces exigences.
ms.openlocfilehash: 6ad0f21c8cbd9cf6690af4664c958c4ffdab7746
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671614"
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
> Microsoft 365 Gouvernement - DoD est disponible uniquement aux États-Unis. Les clients non américains peuvent choisir parmi un certain nombre [d’Office 365 Secteur Public.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Étape 2. Demander une Microsoft 365 pour le gouvernement - DoD

Après avoir décidé que ce service est le bon pour votre organisation, démarrez le processus [d’application de ce service.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Étape 3. Comprendre Microsoft 365 administration : paramètres de sécurité par défaut du DoD

Nous vous recommandons de prendre le temps de consulter attentivement vos paramètres d’administration et de sécurité avant de les modifier et de prendre en compte l’impact sur la conformité avant d’apporter des modifications aux paramètres de sécurité par défaut.

**Point de** décision : déterminez si vous allez modifier l’un des paramètres de sécurité Microsoft 365 Government - DoD par défaut, en résolvant *d’abord l’impact* des modifications que vous pourriez apporter.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Étape 4. Comprendre quelles fonctionnalités sont actuellement indisponibles ou désactivées par défaut dans Microsoft 365 Administration – DoD<sup>1</sup>

Pour répondre aux exigences de nos clients cloud pour le gouvernement, il existe des différences entre les plans Microsoft 365 secteur privé - DoD et Entreprise. Reportez-vous au tableau suivant pour voir quelles fonctionnalités sont disponibles. Consultez [ici](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) les dernières mises à jour des produits de conformité publiées Microsoft 365 feuille de route.<br><br>

| Zone  | Fonctionnalité  | État du dod  |
|-------|----------|-------------|
| **Protection des informations**  | | |
| Types d’informations sensibles  | Correspondance exacte des données  | Disponible  |
| Étiquetage de la sensibilité  | Classification et étiquetage automatiques pour Exchange Online, SharePoint Online et OneDrive Entreprise  | Disponible |
| | Classification et étiquetage automatiques pour Office applications (Word, Excel, PowerPoint, Outlook) sur les plateformes (Web, Windows et Mac)  | Disponible  |
| | Classification et étiquetage automatiques pour les clients Office - Mobile  | On engineering backlog  |
| | Classification et étiquetage automatiques pour Teams, Microsoft 365 groupes et sites SharePoint sites  | Disponible  |
| | Étiquetage obligatoire  | Disponible  |
| | Étiquetage de sensibilité manuelle dans Office applications (iOS, Android, Windows)  | Disponible  |
| | Configuration des étiquettes de sensibilité pour la protection de chiffrement uniquement sur Outlook messages  | Disponible  |
| | Client et scanneur d’étiquetage unifié  | Disponible  |
| Analyse  | Classification des données : vue d’ensemble et Explorateur de contenu  | En cours de déploiement  |
| | Analyse : classifieurs d’apprentissage automatique avec étiquetage automatique Office applications/client  | En cours de développement |
| Chiffrement  | Base chiffrement de messages Office 365 (E3)  | Disponible  |
| | Advanced chiffrement de messages Office 365 (E5)  | Disponible  |
| | Apportez votre propre clé (BYOK) pour le cycle de vie de mise en service de clé gérée par le client  | Disponible  |
| | Clé client pour Office 365  | Disponible  |
| | Clé client pour le chiffrement Microsoft 365 charges de travail multiples | En cours de développement  |
| | Clé client pour SharePoint Online et OneDrive Entreprise | Disponible |
| | Chiffrement à double clé  | Disponible  |
| Protection contre la perte de données  | Protection contre la perte de données (DLP) pour les fichiers et la messagerie  | Disponible  |
| | DLP : tableau de bord d’alertes et expérience d’alerte  | Disponible  |
| | DLP pour les Teams conversation et les conversations de canal  | Disponible  |
| | Point de terminaison DLP (prévisualisation publique)  | La préversion publique |
| | Page Vue d’ensemble de la DLP  | En cours de déploiement  |
| **Gouvernance des informations**  | | |
| Gouvernance des informations  | Gouvernance des informations : étendues adaptatives pour les stratégies de rétention et d’étiquetage | On engineering backlog  |
| | Gouvernance des informations : appliquer une étiquette par défaut pour Exchange boîtes de réception  | Disponible  |
| | Gouvernance des informations : archivage du courrier électronique  | Disponible  |
| | Gouvernance des informations : importer PST  | Disponible  |
| | Gouvernance des informations : verrouillage de conservation  | Disponible  |
| | Gouvernance des informations : stratégies de rétention avec classifieurs entraidables  | En cours de développement  |
| | Gouvernance des informations : stratégies de rétention pour Teams conversation  | Disponible  |
| | Gouvernance des informations : stratégies de rétention pour l’enregistrement Teams réunion  | Disponible  |
| | Gouvernance des informations : stratégies de rétention pour Teams messages de canal privé  | En cours de développement  |
| | Gouvernance des informations : stratégies de rétention et d’étiquetage étendues adaptatives  | En cours de développement  |
| Gestion des enregistrements  | Gestion des enregistrements : appliquer manuellement une étiquette d’enregistrement  | Disponible  |
| | Gestion des enregistrements : appliquer une étiquette d’enregistrement par SharePoint, OneDrive Entreprise bibliothèques, dossiers et ensembles de documents ; et Office 365 groupes  | Disponible  |
| | Gestion des enregistrements : stratégies d’enregistrement automatique basées sur des conditions spécifiques (par exemple, des mots clés ou des informations sensibles) ; et basé sur un événement  | Disponible  |
| | Gestion des enregistrements : révision de la disposition  | Disponible  |
| | Gestion des enregistrements : gestionnaire de plan de gestion de fichiers  | Disponible  |
| | Gestion des enregistrements : révision de la disposition en plusieurs étapes  | En cours de développement  |
| | Gestion des enregistrements : conservation et étiquetage automatique des pièces jointes dans le cloud  | En cours de développement  |
| | Gestion des enregistrements : preuve de destruction  | Disponible  |
| | Gestion des enregistrements : gestion des versions des enregistrements  | Disponible  |
| | Gestion des enregistrements : enregistrements réglementaires  | Disponible  |
| **Gestion des risques**  | | |
| Référentiel sécurisé client | Référentiel sécurisé client  | Disponible  |
| Conformité des communications  | Conformité des communications : possibilité de définir une période de rétention pour une stratégie de conformité des communications (prévisualisation publique)  | On engineering backlog  |
| | Conformité des communications : alertes d’accès ; modèles de notification ; tableau de bord de stratégie de communication  | Disponible  |
| | Conformité des communications : analyser Teams de conversation des utilisateurs avec une boîte aux lettres sur site  | Disponible  |
| | Conformité des communications : modèle de conflit d’intérêts  | Disponible  |
| | Conformité des communications : créer des stratégies client, 3 pré-configuré  | Disponible  |
| | Conformité des communications : détecter le contenu adulte  | On engineering backlog  |
| | Conformité des communications : détecte les violations répétées de code de conduite au fil du temps  | Disponible  |
| | Conformité des communications : faire l’objet d’une enquête pour Advanced eDiscovery  | Disponible  |
| | Conformité des communications : tirer parti de la reconnaissance optique de caractères (OCR) pour extraire et évaluer des messages  | Disponible  |
| | Conformité des communications : intégration Microsoft Teams’entreprise  | En cours de développement  |
| | Conformité des communications : vérification de l’état de la stratégie et possibilité de suspendre la stratégie  | En cours de développement  |
| | Conformité des communications : intégration Power Automate’entreprise  | On engineering backlog  |
| | Conformité des communications : types d’informations sensibles par rapport d’emplacement  | En cours de développement  |
| | Conformité des communications : prise en charge Teams, Exchange et suppression Teams message  | Disponible  |
| | Conformité des communications : prise en charge des autorisations plus granulaires  | Disponible  |
| | Conformité des communications : prise en charge de 7 langues pour les classifieurs de menaces, de harcèlement ciblé et de blasphèmes  | Disponible  |
| | Conformité des communications : traduire le contenu d’état au cours de l’examen  | En cours de développement  |
| Obstacles à l’information  | Obstacles à l’information  | En cours de déploiement  |
| Gestion des risques internes  | Gestion des risques internes : journal d’audit  | Préversion publique  |
| | Gestion des risques internes : tableau de bord de cas  | Disponible  |
| | Gestion des risques internes : données exposés dans l’Explorateur d’activités  | Préversion publique  |
| | Gestion des risques internes : données exposés dans l’Explorateur de contenu  | En cours de développement  |
| | Gestion des risques internes : vol de données par des utilisateurs qui quittent le site  | Disponible  |
| | Gestion des risques internes : indicateurs d’appareil pour l’activité Windows 10 points de terminaison  | En cours de développement  |
| | Gestion des risques internes : escalader pour les Advanced eDiscovery  | Disponible  |
| | Gestion des risques internes : exporter des alertes  | Préversion publique  |
| | Gestion des risques internes : fuites générales de données  | Disponible  |
| | Gestion des risques internes : prise en charge intelligente des paramètres de domaine dans la gestion des risques internes  | La préversion publique  |
| | Gestion des risques internes : indicateurs pour les alertes de point de terminaison Microsoft Defender  | On engineering backlog  |
| | Gestion des risques internes : indicateurs de violation de la stratégie de sécurité  | En cours de développement  |
| | Gestion des risques internes : indicateurs pour l Windows 10 des points de terminaison | La préversion publique  |
| | Gestion des risques internes : examiner les alertes de gestion des risques internes  | Disponible  |
| | Gestion des risques internes : intégration Microsoft Teams et Power Automate interne  | En cours de développement  |
| | Gestion des risques internes : prise en charge des déclencheurs natifs Azure Active Directory suppression de compte | Préversion publique  |
| | Gestion des risques internes : modèles de notification  | Disponible  |
| | Gestion des risques internes : indicateurs Office pour les Teams, les sites SharePoint, la messagerie électronique  | Disponible  |
| | Gestion des risques internes : modèles de stratégie pour les fuites de données par des utilisateurs non régrunts  | On engineering backlog  |
| | Gestion des risques internes : modèles de stratégie pour les fuites de données par les utilisateurs prioritaires  | Préversion publique  |
| | Gestion des risques internes : modèles de stratégie pour les violations générales de stratégie de sécurité  | On engineering backlog  |
| | Gestion des risques internes : modèles de stratégie pour les violations de stratégie de sécurité par les utilisateurs prioritaires et les utilisateurs qui quittent la stratégie | Préversion publique |
| | Gestion des risques internes : modèles de stratégie pour les violations de stratégie de sécurité par les utilisateurs non régrunts | On engineering backlog  |
| | Gestion des risques internes : personnalisation des stratégies, vérification de l’état de la stratégie et assistant de création de stratégie améliorée  | Préversion publique  |
| | Gestion des risques internes : groupes d’utilisateurs prioritaires  | Préversion publique  |
| | Gestion des risques internes : prise en charge des déclencheurs natifs pour Azure Active Directory suppression de compte | Préversion publique  |
| | Gestion des risques internes : piste d’audit « Surveiller l’observeur » | Préversion publique  |
| **Découvrir les & répondre**  | | |
| eDiscovery | Core eDiscovery : audit  | Disponible  |
| | Core eDiscovery : gestion des cas  | Disponible  |
| | Découverte électronique principale : limites de conformité dans OneDrive Entreprise  | Disponible  |
| | Core eDiscovery : exporter  | Disponible  |
| | Découverte électronique principale : conservation sur place  | Disponible  |
| | Core eDiscovery : exportation native  | Disponible  |
| | Core eDiscovery : déchiffrement RMS  | Disponible  |
| | Core eDiscovery : recherche  | Disponible  |
| | Advanced eDiscovery : traitement avancé  | Disponible  |
| | Advanced eDiscovery : mappage du dépositaire à la charge de travail  | Disponible  |
| | Advanced eDiscovery : communications des dépositaires  | Disponible  |
| | Advanced eDiscovery : Tableau de bord  | Disponible  |
| | Advanced eDiscovery : fonctionnalités de purge des données pour Microsoft Teams  | On engineering backlog  |
| | Advanced eDiscovery : analyse/indexation approfondie  | Disponible  |
| | Advanced eDiscovery : prise en charge des sur deux byte pour le chinois, le japonais et le coréen  | Disponible  |
| | Advanced eDiscovery : Threads de messagerie  | Disponible  |
| | Advanced eDiscovery : exporter (télécharger, exporter, ajouter à un autre jeu à réviser)  | Disponible  |
| | Advanced eDiscovery : filtrage  | Disponible  |
| | Advanced eDiscovery : optimisations des attentes  | En cours de développement  |
| | Advanced eDiscovery : procédure de Teams messages de canaux privés  | En cours de développement  |
| | Advanced eDiscovery : prise en charge étendue du Centre de conformité Microsoft pour la recherche et l’exportation d’éléments dans SharePoint, OneDrive Entreprise, Corbeille au cœur et Advanced eDiscovery  | En cours de développement  |
| | Advanced eDiscovery : identification quasi-en double  | Disponible  |
| | Advanced eDiscovery : nouveau module de codage prédictif  | En cours de développement  |
| | Advanced eDiscovery : sources de données non privatives  | Disponible  |
| | Advanced eDiscovery : ingestion non Office 365  | On engineering backlog  |
| | Advanced eDiscovery : codage prédictif  | Disponible  |
| | Advanced eDiscovery : exportation traitée avec fichier de chargement  | Disponible  |
| | Advanced eDiscovery : Actions  | Disponible  |
| | Advanced eDiscovery : Ensembles de révision  | Disponible  |
| | Advanced eDiscovery : examiner les données (données de requête, balises intelligentes, tableau de bord) et annoter (publier)  | Disponible  |
| | Advanced eDiscovery : rapport de terme de recherche  | Disponible  |
| | Advanced eDiscovery : prise en charge du contenu lié OneDrive et SharePoint Online (pièces jointes modernes)  | Disponible  |
| | Advanced eDiscovery : prise en charge Teams réactions  | On engineering backlog  |
| | Advanced eDiscovery : marquage  | Disponible  |
| | Advanced eDiscovery : rapports de client  | Disponible  |
| | Advanced eDiscovery : Thèmes  | Disponible  |
| | Advanced eDiscovery : visionneuses  | Disponible  |
| | Advanced eDiscovery : Yammer Advanced eDiscovery dans le Centre de conformité Microsoft  | Disponible  |
| Audit  | Audit de base  | Disponible  |
| | Audit avancé : accès à des événements essentiels (par exemple, mailitemsaccessed)  | Disponible  |
| | Audit avancé : augmentation de la bande passante pour l’API activité de gestion  | Disponible  |
| | Audit avancé : rétention des journaux (1 an)  | Disponible  |
| | Audit avancé : rétention à plus long terme dans les journaux d’audit (10 ans)  | En cours de déploiement  |
| | Audit avancé : événements de publipostage et d’envoi de courrier  | Disponible  |
| | Audit avancé : disponibilité du Centre de sécurité et conformité  | Disponible  |
| | Audit avancé : événements de terme de recherche dans Exchange Online et SharePoint Online  | En cours de développement  |
| | Audit avancé : Teams réactions sur les messages  | On engineering backlog  |
| **Gestion de la conformité** | | |
| Gestion de la conformité  | Centre de conformité Microsoft 365  | Disponible  |
| | Microsoft Cloud App Security  | Disponible  |
| | Gestionnaire de conformité  | Disponible  |
| | Prise en charge des caractères sur deux byte  | Disponible  |
| **Écosystème** | | |
| Écosystème  | Connecteurs de données de première partie : RH  | En cours de développement |
| | Connecteurs de données first-party : badging physique  | En cours de développement  |
| | Graph API pour les Advanced eDiscovery  | On engineering backlog  |

<sup>1 L’état</sup> identifié est sujet à modification à mesure que les plans et priorités du projet sont réévalués.<br/>

**Point de décision**: *déterminez si les fonctionnalités de conformité répondent aux besoins de votre organisation.*
