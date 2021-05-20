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
description: Cette orientation s’adresse aux professionnels de l’informatique qui sont à l’origine des déploiements de Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui traitent des données soumises à des règlements et des exigences du gouvernement, lorsque l’utilisation d’Microsoft 365 un gouvernement – DoD est appropriée pour répondre à ces exigences.
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546001"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Plan de conformité de Microsoft 365 – Déploiements Département de la Défense (DoD)

Cette orientation s’adresse aux professionnels de l’informatique qui sont à l’origine des déploiements de Office 365 dans des entités du gouvernement fédéral américain ou d’autres entités qui traitent des données soumises à des règlements et des exigences du gouvernement, lorsque l’utilisation d’Microsoft 365 un gouvernement – DoD est appropriée pour répondre à ces exigences.

> [!NOTE]
> Si votre organisation a déjà satisfait aux exigences d’admissibilité du gouvernement Microsoft 365 – DoD et a présenté une demande et a été acceptée dans le programme, vous pouvez sauter les étapes 1 et 2 et passer directement à l’étape 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Étape 1. Déterminez si votre organisation a besoin Microsoft 365 gouvernement - DoD et satisfait aux exigences d’admissibilité

L Microsoft 365 environnement Government - DoD est conforme aux exigences du gouvernement américain en matière de services cloud.

En plus de profiter des caractéristiques et des capacités de Office 365, les organisations bénéficient des caractéristiques suivantes qui sont uniques à Microsoft 365 gouvernement – DoD :

- Le contenu client de votre organisation est logiquement séparé du contenu client dans les services commerciaux Office 365 de Microsoft.
- Le contenu client de votre organisation est stocké aux États-Unis.
- L’accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
- Microsoft 365 Gouvernement - Le DoD respecte les certifications et accréditations requises pour les clients du secteur public américain.

Vous pouvez trouver plus d’informations sur l’offre Microsoft 365 gouvernement - DoD pour les clients du gouvernement américain [à Office 365 Secteur Public, y](https://products.office.com/government/compare-office-365-government-plans)compris les conditions d’admissibilité.

La [description Office 365 service du gouvernement des États-Unis](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) décrit les avantages de la plate-forme, qui sont centrés sur le respect des exigences de conformité aux États-Unis.

> [!TIP]
> Vous pouvez transférer les tableaux d’information dans la description du service dans un cahier de travail Excel et ajouter deux colonnes : **Pertinent pour mon organisation Y/N et** répond aux besoins de mon organisation **Y/N**. Ensuite, vous pouvez consulter cette liste avec vos collègues pour confirmer que ce service répond aux besoins de votre organisation.

**Points de décision**:<br/>
- *Décidez si Microsoft 365 gouvernement - DoD convient à votre organisation.*
- *Confirmez que votre organisation répond aux exigences d’admissibilité.*

> [!NOTE]
> Microsoft 365 Gouvernement - Le DoD n’est disponible qu’aux États-Unis. Les clients non-US Government peuvent choisir parmi un certain nombre [de plans Office 365 Secteur Public’argent.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Étape 2. Faire une demande Microsoft 365 gouvernement fédéral - DoD

Ayant décidé que ce service est bon pour votre organisation, commencez le processus de [demande de ce service](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Étape 3. Comprendre Microsoft 365 gouvernement - Paramètres de sécurité par défaut du DoD

Nous vous recommandons de prendre le temps d’examiner attentivement vos paramètres d’administration et de sécurité avant de les modifier et d’examiner l’impact sur la conformité avant d’apporter des modifications aux paramètres de sécurité par défaut.

**Point de décision**: *Décidez si vous modifierez l’un des paramètres de sécurité par défaut du gouvernement Microsoft 365 - DoD, en décidant de comprendre d’abord l’impact de toutes les modifications que vous pourriez apporter.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Étape 4. Comprendre quelles capacités sont actuellement indisponibles ou désactivées par défaut dans Microsoft 365 gouvernement – DoD<sup>1</sup>

Pour répondre aux exigences de nos clients du cloud gouvernemental, il existe certaines différences entre les plans Microsoft 365 gouvernement - DoD et d’entreprise. Consultez le tableau suivant pour voir quelles fonctionnalités sont disponibles. Consultez [ici les](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) dernières mises à jour des produits de conformité publiées sur Microsoft 365 feuille de route.<br><br>

| Domaine | Fonctionnalité | Statut DoD |
|------|---------|------------|
| **Protection des informations** | Client et scanner d’étiquetage unifiés | Available |
| | Correspondance exacte des données | Available |
| | Classification et étiquetage automatiques pour les Exchange Online, SharePoint en ligne et OneDrive Entreprise | En cours de déploiement |
| | Classification et étiquetage automatiques pour les applications Office (Word, Excel, PowerPoint, Outlook) sur toutes les plateformes (web, Windows et Mac) | Available |
| | Classification et étiquetage automatiques pour Office clients - Mobile | Sur le carnet de commandes de l’ingénierie |
| | Classification et étiquetage automatiques pour les Teams, Microsoft 365 groupes et SharePoint sites | Available |
| | Étiquetage obligatoire | Available |
| | Étiquetage manuel de sensibilité dans Office applications (iOS, Android, Windows) | Available |
| | Configuration de l’étiquette de sensibilité pour la protection cryptée uniquement sur Outlook messages | En cours de déploiement |
| **Analyse** | Classification des données : Aperçu et explorateur de contenu | En cours de déploiement |
| | Analytique : Classificateurs d’apprentissage automatique avec étiquetage automatique côté service | En développement |
| | Analytique : Classificateurs d’apprentissage automatique avec étiquetage automatique Office applications/client | En cours de déploiement |
| **Chiffrement** | Base chiffrement de messages Office 365 (E3) | Available |
| | Advanced chiffrement de messages Office 365 (E5) | Available |
| | Apportez votre propre clé (BYOK) pour le cycle de vie de l’approvisionnement clé géré par le client | Available |
| | Clé client pour Office 365 | Available |
| | Chiffrement à double clé | Available |
| **Protection contre la perte de données** | Prévention des pertes de données (DLP) pour les fichiers et les courriels | Available |
| | DLP pour les conversations Teams chat et les canaux | Available |
| | DLP: Tableau de bord alertes | En cours de déploiement |
| | Point final DLP | En développement |
| | DLP On-prem | Sur le carnet de commandes de l’ingénierie |
| | Page d’aperçu DLP | En développement |
| **Gouvernance des informations** | Gouvernance de l’information : Archivage par courriel | Available |
| | Gouvernance de l’information : verrouillage de préservation | Available |
| | Gouvernance de l’information : PST d’importation | Available |
| | Gouvernance de l’information : Appliquez manuellement les étiquettes de rétention des documents non | Available |
| | Gouvernance de l’information : Appliquez des étiquettes de conservation par défaut pour SharePoint/OneDrive Entreprise bibliothèques, les dossiers et les ensembles de documents; Exchange boîtes de réception; et Office 365 groupes | Available |
| | Gouvernance de l’information : Appliquer une étiquette de rétention par défaut unique à l’ensemble de l’organisation; emplacements ou utilisateurs spécifiques; et automatiquement basé sur des conditions spécifiques (par exemple, mots clés ou informations sensibles) | Available |
| | Gouvernance de l’information : Appliquez une étiquette par défaut pour Exchange boîtes de réception | Available |
| | Gouvernance de l’information : examen des dispositions en plusieurs étapes | Sur le carnet de commandes de l’ingénierie |
| | Gouvernance de l’information : Politiques de rétention avec classificateurs formables | En développement |
| | Gouvernance de l’information : politiques de rétention pour Teams chat | En cours de déploiement |
| | Gouvernance de l’information : Politiques de conservation pour Teams’enregistrement des Teams réunion | Available |
| | Gouvernance de l’information : Politiques de rétention Teams messages sur les chaînes privées | Sur le carnet de commandes de l’ingénierie |
| | Gouvernance de l’information : Stratégies de conservation et d’étiquetage portées adaptatives | En développement |
| | Gestion des dossiers : Appliquez manuellement la maison de disques | Available |
| | Gestion des dossiers : Appliquez une maison de disques par défaut pour les SharePoint, OneDrive Entreprise bibliothèques, les dossiers et les ensembles de documents; et Office 365 groupes | Available |
| | Gestion des dossiers : Stratégies d’enregistrement automatiques basées sur des conditions spécifiques (par exemple, mots clés ou informations sensibles); et sur la base d’un événement | Available |
| | Gestion des dossiers : Examen des dispositions | Available |
| | Gestion des dossiers : Gestionnaire de plan de fichiers | Available |
| | Gestion des dossiers : preuve d’élimination | Available |
| | Gestion des dossiers : Version des enregistrements | Available |
| | Gestion des dossiers : Dossiers réglementaires | Available |
| | Gestion des dossiers : Utilisez SharePoint classification Syntex pour appliquer les maisons de disques | Sur le carnet de commandes de l’ingénierie |
| **Gestion des risques internes** | Référentiel sécurisé client | Available |
| | Gestion des risques internes : tableau de bord de cas, explorateur de contenu et modèles d’avis | En cours de déploiement |
| | Gestion des risques d’initiés : escalade pour une enquête Advanced eDiscovery | En cours de déploiement |
| | Gestion des risques internes : vol de données par les utilisateurs au départ | En cours de déploiement |
| | Gestion des risques internes : fuites générales de données | En cours de déploiement |
| | Gestion des risques internes : Enquêter sur les alertes de gestion des risques internes | En cours de déploiement |
| | Gestion des risques internes : Office indicateurs pour les Teams, les sites SharePoint, la messagerie électronique | En cours de déploiement |
| | Explorateur d’activités de gestion des risques d’initiés | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques d’initiés : Indicateurs d’Windows 10 build 1809 et plus | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques internes : indicateurs pour Microsoft Defender pour les alertes endpoint | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques internes : indicateurs de violation de la politique de sécurité | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques internes : modèles de stratégie s’il y a des fuites de données par des utilisateurs mécontents | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques internes : modèles de stratégie s’il y a des fuites de données par les utilisateurs prioritaires | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques internes : modèles de politique s’il y a violation générale de la politique de sécurité | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques internes : modèles de stratégie s’il s’y a des violations des stratégies de sécurité commises par les utilisateurs prioritaires, les utilisateurs sortants et les utilisateurs mécontents (aperçu) | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques d’initiés : Personnalisation des politiques | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques internes : alertes à l’exportation | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques d’initiés : Microsoft Teams intégration | Sur le carnet de commandes de l’ingénierie |
| | Gestion des risques internes : groupes d’utilisateurs prioritaires | Sur le carnet de commandes de l’ingénierie |
| | Conformité à la communication : Créer des stratégies clients, 3 préconfigurées | Available |
| | Conformité à la communication : Prise en charge Teams, Exchange et suppression Teams message | Available |
| | Conformité aux communications : alertes d’accès; modèles d’avis; tableau de bord des politiques de communication | Available |
| | Conformité aux communications : Escalade pour enquête pour Advanced eDiscovery | Available |
| | Conformité à la communication : détecte une violation répétée du code de conduite au fil du temps | Available |
| | Conformité à la communication : prise en charge d’autorisations plus granulaires | Available |
| | Conformité à la communication : analyser Teams données de chat des utilisateurs avec la boîte aux lettres prém | Available |
| | Conformité aux communications : modèle de conflit d’intérêts | Available |
| | Conformité à la communication : Capacité d’ignorer la signature ou la clause de non-responsabilité par courriel | En développement |
| | Conformité aux communications : capacité de fixer une période de conservation pour une politique de conformité aux communications | Sur le carnet de commandes de l’ingénierie |
| | Conformité à la communication : Détecter le contenu pour adultes | Sur le carnet de commandes de l’ingénierie |
| | Conformité à la communication : transfert de la gestion des risques d’initiés | En développement |
| | Conformité à la communication : bilan de santé des politiques et capacité de mettre en pause la politique | En développement |
| | Conformité à la communication : Prise en charge de 7 langues pour les personnes menacées, le harcèlement ciblé et les classificateurs de jurons | En développement |
| | Conformité à la communication : traduire le contenu de la santé pendant l’enquête | En développement |
| | Obstacles aux informations | En cours de déploiement |
| | Gestion des accès privilégiés | Sur le carnet de commandes de l’ingénierie |
| **Découvrez & répondre** | Core eDiscovery: Préservation en place | Available |
| | Core eDiscovery: Gestion de cas | Available |
| | Core eDiscovery: Recherche | Available |
| | Core eDiscovery: Exportation | Available |
| | Core eDiscovery: Décryptage RMS | Available |
| | EDiscovery de base : Exportation indigène | Available |
| | Core eDiscovery: Auditing | Available |
| | Core eDiscovery: Limites de conformité pour OneDrive Entreprise | En cours de déploiement |
| | Advanced eDiscovery: Traitement avancé | Available |
| | Advanced eDiscovery: CJK / Double prise en charge de l’octet pour Advanced eDiscovery | Available |
| | Advanced eDiscovery : Dépositaire de la cartographie de la charge de travail | Available |
| | Advanced eDiscovery : Communications des gardiens | Available |
| | Advanced eDiscovery: Tableau de bord | Available |
| | Advanced eDiscovery: Threading email | Available |
| | Advanced eDiscovery: Export (télécharger, exporter, ajouter à un autre ensemble d’examen) | Available |
| | Advanced eDiscovery: Filtrage | Available |
| | Advanced eDiscovery : Identification quasi dupliquée | Available |
| | Advanced eDiscovery : Codage prédictif | Available |
| | Advanced eDiscovery: Exportation traitée avec fichier de charge | Available |
| | Advanced eDiscovery: Redactions | Available |
| | Advanced eDiscovery : Ensembles d’examen | Available |
| | Advanced eDiscovery: Revoir et annoter | Available |
| | Advanced eDiscovery: Rapport de durée de recherche | Available |
| | Advanced eDiscovery : Prise en charge du contenu lié OneDrive et SharePoint Online (pièces jointes modernes) | Available |
| | Advanced eDiscovery: Marquage | Available |
| | Advanced eDiscovery: Teams réactions soutiennent | Available |
| | Advanced eDiscovery: Rapports des locataires | Available |
| | Advanced eDiscovery: Thèmes | Available |
| | Advanced eDiscovery: Téléspectateurs | Available |
| | Advanced eDiscovery : Yammer Advanced eDiscovery dans le Centre de conformité Microsoft | Available |
| | Advanced eDiscovery : Optimiser les | En développement |
| | Advanced eDiscovery : Microsoft Compliance Center a élargi son soutien à la recherche et à l’exportation d’articles en SharePoint, OneDrive Entreprise, Recycle Bin in Core et Advanced eDiscovery | En développement |
| | Advanced eDiscovery: Prise légale pour les Teams messages des chaînes privées | En développement |
| | Advanced eDiscovery : Nouveau module de codage prédictif | En développement |
| | Advanced eDiscovery: Ingestion Office 365 non-Office 365 | Sur le carnet de commandes de l’ingénierie |
| | Advanced eDiscovery: Rapports des locataires | En développement |
| | Audit de base | Available |
| | Audit avancé : Accès à des événements cruciaux (par exemple, mailitemsaccessed) | Available |
| | Audit avancé : Augmentation de la bande passante à l’API activité de gestion | Available |
| | Audit avancé : Conservation du journal (1 an) | Available |
| | Audit avancé : Envoyer le courrier et envoyer des événements par la poste | Available |
| | Audit avancé : disponibilité du Centre de sécurité et de conformité | Available |
| | Vérification avancée : Conservation à plus long terme des registres de vérification (10 ans) | En développement |
| | Audit avancé : Événements à terme de recherche en Exchange Online et SharePoint en ligne | Sur le carnet de commandes de l’ingénierie |
| **Gestion de la conformité** | Microsoft 365 Centre de sécurité et de conformité | Available |
| | Microsoft Cloud App Security | En développement |
| | Gestionnaire de conformité | Available |
| | Prise en charge des personnages d’au-être double | Available |
| **écosystème** | Connecteurs de données de première partie : RH | Available |
| | Connecteurs de données de première partie : Instant Bloomberg, Bloomberg Mail, LinkedIn Business pages, ICE Chat | Sur le carnet de commandes de l’ingénierie |
| | Connecteurs de données tiers | Sur le carnet de commandes de l’ingénierie |
| | Graph API pour Advanced eDiscovery | En développement |
| | Graph API pour les données Teams’exportation | Sur le carnet de commandes de l’ingénierie |

<sup>1 L’état</sup> identifié peut être changé au fur et à mesure que les plans et les priorités du projet sont réévalués.<br/>

**Point de décision**: *Décidez si les caractéristiques de conformité répondent aux besoins de votre organisation.*
