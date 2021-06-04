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
description: Ces conseils sont adaptés aux professionnels de l’informatique qui déploient des Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui traitent des données soumises aux réglementations et exigences gouvernementales, lorsque l’utilisation de Microsoft 365 Government – Cloud de la communauté du secteur public High est appropriée pour répondre à ces exigences.
ms.openlocfilehash: 357cf30350ff2a3b21d7d9326e91c2c01d119b21
ms.sourcegitcommit: f7874215059c1e5a9d383da0539f87b6f85a57e6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/25/2021
ms.locfileid: "52001910"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Plan for Microsoft 365 compliance – Cloud de la communauté du secteur public High

Ces conseils sont adaptés aux professionnels de l’informatique qui déploient des Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui traitent des données soumises aux réglementations et exigences gouvernementales, lorsque l’utilisation de Microsoft 365 Government – Cloud de la communauté du secteur public High est appropriée pour répondre à ces exigences.

> [!NOTE]
>Si votre organisation a déjà satisfait aux conditions d’éligibilité Microsoft 365 Government – Cloud de la communauté du secteur public High eligibility requirements and applied for and been accepted into the program, you can skip steps 1 and 2 and go directly to step 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Étape 1. Déterminer si votre organisation a besoin Microsoft 365 gouvernement – Cloud de la communauté du secteur public élevé et répond aux exigences d’éligibilité

L’Microsoft 365 Secteur Cloud de la communauté du secteur public environnement élevé est conforme aux exigences du gouvernement des États-Unis pour les services cloud. En plus de profiter des fonctionnalités et des fonctionnalités de Office 365, les organisations bénéficient des fonctionnalités suivantes propres à Microsoft 365 Secteur Cloud de la communauté du secteur public :

- Le contenu client de votre organisation est logiquement séparé du contenu client dans les services Office 365 commerciaux de Microsoft.
- Le contenu client de votre organisation est stocké aux États-Unis.
- L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
- Microsoft 365 Gouvernement – Cloud de la communauté du secteur public aux certifications et accréditations requises pour les clients du secteur public américain.

Vous trouverez plus d’informations sur l’offre Microsoft 365 Government – Cloud de la communauté du secteur public High pour les clients du gouvernement des États-Unis dans les [plans Office 365 Secteur Public,](https://products.office.com/government/compare-office-365-government-plans)y compris les conditions d’éligibilité.

La [description Office 365 service pour le](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) gouvernement américain décrit les avantages de la plateforme, qui sont centrés sur les exigences de conformité aux États-Unis.

> [!TIP]
> Vous pouvez transférer les tables d’informations dans la description du service dans un workbook Excel et ajouter deux colonnes : Pertinent pour mon organisation **Y/N** et Répond aux besoins de mon organisation **Y/N**. Vous pouvez ensuite consulter cette liste avec vos collègues pour vérifier que ce service répond aux besoins de votre organisation.

**Points de décision**:<br/>
- *Déterminez si Microsoft 365 administration – GCC-High est approprié pour votre organisation.*
- *Confirmez que votre organisation répond aux conditions d’éligibilité.*

> [!NOTE]
> Microsoft 365 Gouvernement - Cloud de la communauté du secteur public Élevé est uniquement disponible aux États-Unis. Les clients non américains peuvent choisir parmi un certain nombre [d’Office 365 Secteur Public.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Étape 2. Demander une Microsoft 365 pour le gouvernement – GCC-High

Après avoir décidé que ce service est le bon pour votre organisation, démarrez le processus [d’application de ce service.](https://products.office.com/government/eligibility-validation)
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Étape 3. Comprendre Microsoft 365 gouvernement : GCC-High de sécurité par défaut

Nous vous recommandons de prendre le temps de consulter attentivement vos paramètres d’administration et de sécurité avant de les modifier et de prendre en compte l’impact sur la conformité avant d’apporter des modifications aux paramètres de sécurité par défaut.

**Point de** décision : déterminez si vous allez modifier l’un des paramètres de sécurité Microsoft 365 Government – GCC-High par défaut, en résolvant *d’abord l’impact* des modifications que vous pourriez apporter.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Étape 4. Comprendre les fonctionnalités actuellement indisponibles ou désactivées par défaut dans Microsoft 365 Pour le gouvernement – Cloud de la communauté du secteur public-Haut<sup>1</sup>

Pour répondre aux exigences de nos clients cloud pour le gouvernement, il existe des différences entre les plans Microsoft 365 secteur GCC-High et les plans d’entreprise. Reportez-vous au tableau suivant pour voir quelles fonctionnalités sont disponibles. Consultez [ici](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) les dernières mises à jour des produits de conformité publiées dans la feuille de route Microsoft 365 conformité.<br><br>

| Domaine | Fonctionnalité | Cloud de la communauté du secteur public État élevé |
|------|---------|-----------------|
| **Protection des informations** | Client et scanneur d’étiquetage unifié | Available |
| | Correspondance exacte des données | Available |
| Étiquetage de la sensibilité | Classification et étiquetage automatiques pour Exchange Online, SharePoint Online et OneDrive | Available |
| Étiquetage de la sensibilité | Classification et étiquetage automatiques pour les applications Office (Word, Excel, PowerPoint, Outlook) sur le web, Android, iOS, Windows et Mac | Available |
| Étiquetage de la sensibilité | Classification et étiquetage automatiques pour Office clients (Mobile) | On engineering backlog |
| Étiquetage de la sensibilité | Classification et étiquetage automatiques pour Teams, Microsoft 365 groupes et sites SharePoint sites | Available |
| Analyse | Analyse de la classification des données : vue d’ensemble et Explorateur de contenu | Available |
| Analyse | Analyse : classifieurs d’apprentissage automatique avec étiquetage automatique côté service | On engineering backlog |
| Analyse | Analyse : classifieurs d’apprentissage automatique avec étiquetage automatique Office applications/client | En cours de déploiement |
| Chiffrement | Base chiffrement de messages Office 365 (E3) | Available |
| Chiffrement | Advanced chiffrement de messages Office 365 (E5) | Available |
| Chiffrement | Clé client pour Office 365 | Available |
| Chiffrement | Clé client : chiffrement des données au repos pour Microsoft 365 | En cours de déploiement |
| Chiffrement | Apportez votre propre clé (BYOK) pour le cycle de vie de mise en service de clé gérée par le client | Available |
| Chiffrement | Chiffrement à double clé | Available |
| Chiffrement | Exchange Online service de chiffrement à l’aide de clés gérées Microsoft | Available |
| Protection contre la perte de données | Protection contre la perte de données (DLP) pour les fichiers et la messagerie | Available |
| Protection contre la perte de données | DLP pour les Teams conversation et les conversations de canal | Available |
| Protection contre la perte de données | Point de terminaison DLP | En cours de développement |
| Protection contre la perte de données | Tableau de bord Alertes | En cours de développement |
| Protection contre la perte de données | Page Vue d’ensemble | En cours de développement |
| **Gouvernance des informations** | Étendues adaptatives pour les stratégies de rétention et d’étiquetage | On engineering backlog |
| | Gouvernance des informations : archivage du courrier électronique | Available |
| | Gouvernance des informations : étiquettes de rétention par SharePoint/OneDrive Entreprise bibliothèques, dossiers et ensembles de documents ; Exchange boîtes de réception ; et Office 365 groupes | Available |
| | Gouvernance des informations : importer PST | Available |
| | Gouvernance des informations : étiquettes de rétention non-enregistrement manuelles | Available |
| | Gouvernance des informations : verrouillage de conservation | Available |
| | Gouvernance des informations : stratégies de rétention pour l’ensemble de l’organisation ; des emplacements ou des utilisateurs spécifiques ; basées automatiquement sur une condition spécifique (par exemple, des mots clés ou des informations sensibles) ; et basé sur un événement | Available |
| | Gouvernance des informations : stratégies de rétention pour Teams | En cours de déploiement |
| | Gouvernance des informations : stratégies de rétention pour l’enregistrement Teams réunion | En cours de développement |
| | Gouvernance des informations : stratégies de rétention pour Teams canaux privés | On engineering backlog |
| | Gouvernance des informations : stratégies de rétention pour Teams canaux partagés | On engineering backlog |
| | Gouvernance des informations : stratégies de rétention avec classifieurs entraidables | En cours de développement |
| | Gouvernance des informations : stratégies de rétention pour Yammer | On engineering backlog |
| Gestion des enregistrements | Possibilité de supprimer une étiquette d’enregistrement | En cours de développement |
| Gestion des enregistrements | Appliquer manuellement une étiquette d’enregistrement | Available |
| Gestion des enregistrements | Appliquer des étiquettes d’enregistrement par SharePoint, OneDrive Entreprise bibliothèques, dossiers et ensembles de documents ; et Office 365 groupes | Available |
| Gestion des enregistrements | Appliquer automatiquement des stratégies d’enregistrement en fonction de conditions spécifiques (par exemple, des mots clés ou des informations sensibles) ; et basé sur un événement | Available |
| Gestion des enregistrements | Appliquer automatiquement des stratégies d’enregistrement avec des classifieurs entraisables | En cours de développement |
| Gestion des enregistrements | Révisions avant élimination | Available |
| Gestion des enregistrements | Gestionnaire de plan de fichiers | Available |
| Gestion des enregistrements | Révision de disposition en plusieurs étapes | On engineering backlog |
| Gestion des enregistrements | Preuve de destruction | Available |
| Gestion des enregistrements | Power Automate Flow fin de la période de rétention | On engineering backlog |
| Gestion des enregistrements | Conservation et étiquetage automatique des pièces jointes cloud | On engineering backlog |
| Gestion des enregistrements | Gestion des versions des enregistrements | Available |
| Gestion des enregistrements | Enregistrements réglementaires | Available |
| Gestion des enregistrements | Utiliser la SharePoint syntex pour appliquer des étiquettes d’enregistrement | On engineering backlog |
| **Gestion des risques internes** | Référentiel sécurisé client | Available |
| Conformité des communications | Possibilité d’ignorer la signature électronique ou la clause d’exclusion de responsabilité | En cours de développement |
| Conformité des communications | Possibilité de définir une période de rétention pour une stratégie de conformité des communications | En cours de développement |
| Conformité des communications | Accéder aux alertes ; modèles de notification ; tableau de bord de stratégie de communication | Available |
| Conformité des communications | Analyser les Teams de conversation des utilisateurs avec une boîte aux lettres sur site | Available |
| Conformité des communications | Modèle de conflit d’intérêts | Available |
| Conformité des communications | Créer des stratégies client, 3 pré-configuré | Available |
| Conformité des communications | Détecter le contenu adulte | On engineering backlog |
| Conformité des communications | Détecte une violation de code de conduite répétée au fil du temps | Available |
| Conformité des communications | Faire l’objet d’une enquête pour Advanced eDiscovery | Available |
| Conformité des communications | Remise de la gestion des risques internes | On engineering backlog |
| Conformité des communications | Tirer parti de la reconnaissance optique de caractères pour extraire et évaluer des messages | En cours de développement |
| Conformité des communications | Nouvelle vue simplifiée pour les très petites entreprises | En cours de développement |
| Conformité des communications | Vérification de l’état de la stratégie et possibilité de suspendre la stratégie | On engineering backlog |
| Conformité des communications | Intégration de Power Automate | On engineering backlog |
| Conformité des communications | Prend en charge sept langues pour les classifieurs de menace, de harcèlement ciblé et de blasphémateur | On engineering backlog |
| Conformité des communications | Prise en charge des autorisations plus granulaires | Available |
| Conformité des communications | Prise en charge Teams, Exchange et possibilité de supprimer Teams message | Available |
| Conformité des communications | Microsoft Teams’intégration | On engineering backlog |
| Conformité des communications | Teams contexte de conversation | On engineering backlog |
| Conformité des communications | Traduire le contenu pendant l’examen | On engineering backlog |
| Référentiel sécurisé client | Référentiel sécurisé client | Available |
| Obstacles aux informations | Obstacles aux informations | En cours de développement |
| Gestion des risques internes | Tableau de bord de cas | Available |
| Gestion des risques internes | Vol de données par des employés quittant votre organisation | Available |
| Gestion des risques internes | Indicateurs d’appareil pour l’activité Windows 10 build 1809 et supérieures | On engineering backlog |
| Gestion des risques internes | Faire l’objet d’une enquête pour Advanced eDiscovery | Available |
| Gestion des risques internes | Exporter des alertes | On engineering backlog |
| Gestion des risques internes | Fuites de données générales | Available |
| Gestion des risques internes | Indicateurs de violation de la stratégie de sécurité | On engineering backlog |
| Gestion des risques internes | Indicateurs pour les alertes de point de terminaison Microsoft Defender | On engineering backlog |
| Gestion des risques internes | Explorateur d’activités de gestion des risques internes | En cours de développement |
| Gestion des risques internes | Explorateur de contenu de gestion des risques internes | En cours de développement |
| Gestion des risques internes | Examiner les alertes de gestion des risques internes | Available |
| Gestion des risques internes | Modèles de notifications | Available |
| Gestion des risques internes | Office d’Teams, SharePoint sites, messagerie électronique | Available |
| Gestion des risques internes | Modèles de stratégie pour les fuites de données par les utilisateurs prioritaires | On engineering backlog |
| Gestion des risques internes | Modèles de stratégie pour les fuites de données par des utilisateurs non régrunts | On engineering backlog |
| Gestion des risques internes | Modèles de stratégie pour les violations générales de stratégie de sécurité | On engineering backlog |
| Gestion des risques internes | Modèles de stratégie pour les violations de stratégie de sécurité par les utilisateurs prioritaires, les utilisateurs qui quittent le groupe, les utilisateurs non régrunts | On engineering backlog |
| Gestion des risques internes | Personnalisation de la stratégie | On engineering backlog |
| Gestion des risques internes | Groupes d’utilisateurs prioritaires | On engineering backlog |
| Gestion des risques internes | Intégration de Power Automate | En cours de développement |
| Gestion des risques internes | Microsoft Teams’intégration | On engineering backlog |
| Gestion des accès privilégiés | Gestion des accès privilégiés | On engineering backlog |
| **Réponse &amp; de découverte** | Core eDiscovery : audit | Available |
| eDiscovery | Core eDiscovery : gestion des cas | Available |
| eDiscovery | Core eDiscovery : exporter | Available |
| eDiscovery | Découverte électronique principale : conservation sur place | Available |
| eDiscovery | Core eDiscovery : exportation native | Available |
| eDiscovery | Core eDiscovery : déchiffrement RMS | Available |
| eDiscovery | Core eDiscovery : recherche | Available |
| eDiscovery | Advanced eDiscovery : traitement avancé | Available |
| eDiscovery | Advanced eDiscovery : mappage du dépositaire à la charge de travail | Available |
| eDiscovery | Advanced eDiscovery : communications des dépositaires | Available |
| eDiscovery | Advanced eDiscovery : Tableau de bord | Available |
| eDiscovery | Advanced eDiscovery : prise en charge des sur deux byte pour le chinois, le japonais et le coréen | Available |
| eDiscovery | Advanced eDiscovery : Threads de messagerie | Available |
| eDiscovery | Advanced eDiscovery : exporter (télécharger, exporter, ajouter à un autre jeu à réviser) | Available |
| eDiscovery | Advanced eDiscovery : filtrage | Available |
| eDiscovery | Advanced eDiscovery : optimisations des attentes | En cours de développement |
| eDiscovery | Advanced eDiscovery : procédure de Teams messages de canaux privés | Available |
| eDiscovery | Advanced eDiscovery : prise en charge étendue du Centre de conformité Microsoft pour rechercher et exporter des éléments dans SharePoint et OneDrive Entreprise Corbeille | En cours de développement |
| eDiscovery | Advanced eDiscovery : identification quasi-en double | Available |
| eDiscovery | Advanced eDiscovery : nouveau module de codage prédictif | On engineering backlog |
| eDiscovery | Advanced eDiscovery : sources de données non privatives | Available |
| eDiscovery | Advanced eDiscovery : ingestion non Office 365 | Available |
| eDiscovery | Advanced eDiscovery : codage prédictif | Available |
| eDiscovery | Advanced eDiscovery : exportation traitée avec fichier de chargement | Available |
| eDiscovery | Advanced eDiscovery : Actions | Available |
| eDiscovery | Advanced eDiscovery : Ensembles de révision | Available |
| eDiscovery | Advanced eDiscovery : examiner les données (données de requête, balises intelligentes, tableau de bord) et annoter (publier) | Available |
| eDiscovery | Advanced eDiscovery : rapport de terme de recherche | Available |
| eDiscovery | Advanced eDiscovery : correction des erreurs d’élément unique | Available |
| eDiscovery | Advanced eDiscovery : prise en charge de l’exportation PST | Available |
| eDiscovery | Advanced eDiscovery : prise en charge du contenu lié OneDrive et SharePoint Online (pièces jointes modernes) | Available |
| eDiscovery | Advanced eDiscovery : prise en charge Teams réactions | On engineering backlog |
| eDiscovery | Advanced eDiscovery : marquage | Available |
| eDiscovery | Advanced eDiscovery : rapports de client | Available |
| eDiscovery | Advanced eDiscovery : Thèmes | Available |
| eDiscovery | Advanced eDiscovery : visionneuses | Available |
| eDiscovery | Advanced eDiscovery : Yammer Advanced eDiscovery dans le Centre de conformité Microsoft | Available |
| Audit | Audit de base | Available |
| Audit | Audit avancé : accès à des événements essentiels (par exemple, *MailItemsAccessed)* | Available |
| Audit | Audit avancé : augmentation de la bande passante pour l’API activité de gestion | Available |
| Audit | Audit avancé : contrôle juridique pour Teams messages de canaux privés | Available |
| Audit | Audit avancé : rétention des journaux (1 an) | Available |
| Audit | Audit avancé : rétention à plus long terme dans les journaux d’audit (10 ans) | En cours de développement |
| Audit | Audit avancé : événements de publipostage et d’envoi de courrier | Available |
| Audit | Audit avancé : disponibilité du Centre Microsoft 365 sécurité et conformité | Available |
| Audit | Audit avancé : événements de terme de recherche dans Exchange Online et SharePoint Online | On engineering backlog |
| **Gestion de la conformité** | Microsoft 365 Centre de sécurité et conformité | Available |
| | Gestionnaire de conformité | Available |
| | Prise en charge des caractères sur deux byte | Available |
| | Microsoft Cloud App Security | Available |
| **Écosystème** | Graph API pour les Advanced eDiscovery | En cours de développement |
| | Graph API pour l’exportation Teams données | On engineering backlog |
| | Connecteurs de données de première partie | On engineering backlog |
| | Connecteurs de données tiers | En cours de développement |

<sup>1 L’état</sup> identifié est sujet à modification à mesure que les plans et priorités du projet sont réévalués.<br/>

**Point de décision**: *déterminez si les fonctionnalités de conformité répondent aux besoins de votre organisation.*