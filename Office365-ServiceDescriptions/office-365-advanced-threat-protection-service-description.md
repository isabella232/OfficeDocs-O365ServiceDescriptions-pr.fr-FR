---
title: Description du service Office 365 - Protection avancée contre les menaces
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/20/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Office 365 - Protection avancée contre les menaces est un service informatique de filtrage du courrier électronique qui vous aide à protéger votre organisation contre des virus et des programmes malveillants inconnus grâce à une protection zero-day solide. Ce service comprend des fonctionnalités permettant de protéger en temps réel votre organisation contre des liens dangereux et dispose de fonctionnalités avancées de suivi d’URL et de création de rapports qui donnent aux administrateurs un aperçu du type d’attaques ayant lieu dans l’organisation.
ms.openlocfilehash: bf16c3593ba7ff8cb5ecc9c57b170d5ce153d77e
ms.sourcegitcommit: 0779536e4b9dc4bed4fb3c7f0767314b9a63d397
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/21/2019
ms.locfileid: "30178343"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Description du service Office 365 - Protection avancée contre les menaces

Office 365 - Protection avancée contre les menaces est un service informatique de filtrage du courrier électronique qui vous aide à protéger votre organisation contre des virus et des programmes malveillants inconnus grâce à une protection zero-day solide. Ce service comprend des fonctionnalités permettant de protéger en temps réel votre organisation contre des liens dangereux et dispose de fonctionnalités avancées de suivi d’URL et de création de rapports qui donnent aux administrateurs un aperçu du type d’attaques ayant lieu dans l’organisation.
  
Les principales façons d'utiliser la protection avancée contre les menaces pour la protection des messages sont les suivantes:
  
- Dans un scénario Office 365 ATP à filtrage uniquement, l'ATP fournit une protection de messagerie en nuage pour votre environnement Exchange Server local ou toute autre solution de messagerie SMTP locale.
    
- Office 365 - Protection avancée contre les menaces peut être activé pour protéger les boîtes aux lettres Exchange Online hébergées dans le cloud. Pour en savoir plus sur Exchange Online, reportez-vous à l'article [Description du service Exchange Online](exchange-online-service-description/exchange-online-service-description.md).
    
- Dans un déploiement hybride, le service peut être configuré pour protéger votre environnement de messagerie et contrôler le routage de messagerie lorsque vous disposez à la fois de boîtes aux lettres locales et de boîtes aux lettres dans le cloud avec Exchange Online Protection pour le filtrage des messages entrants.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilité d'Office 365 - Protection avancée contre les menaces

La protection avancée contre les menaces est incluse dans Office 365 entreprise E5, Office 365 éducation a5 et Microsoft 365 Business. 
  
Vous pouvez ajouter ce service aux plans d'abonnement Exchange et Office 365 suivants : 
  
- Exchange Online Plan 1
    
- Exchange Online (plan 2)
    
- Exchange Online Kiosk
    
- Exchange Online Protection
    
- Office 365 Business Essentials
    
- Office 365 Business Premium
    
- Office 365 Entreprise E1
    
- Office 365 Entreprise E3
    
- Office 365 Entreprise F1
    
- Office 365 A1
    
- Office 365 A3
    
Pour acheter Office 365 - Protection avancée contre les menaces, reportez-vous à l'article [Office 365 - Protection avancée contre les menaces](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).
  
Pour comparer les fonctionnalités entre les plans, voir [Comparaison des plans Office 365 pour les entreprises](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Nouveautés d'Office 365 - Protection avancée contre les menaces

Nous continuons à ajouter de nouvelles fonctionnalités à la protection avancée contre les menaces d'Office 365. Vous trouverez ci-dessous une liste de plusieurs nouvelles fonctionnalités, dont certaines appellent une stratégie de protection avancée contre les menaces à examiner et à mettre à jour. Pour en savoir plus sur les nouvelles fonctionnalités disponibles pour la protection avancée contre les menaces (ou Microsoft 365 en général), consultez la feuille de [route microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365).

|Mises à jour de fonctionnalité  |Éléments d'action  |
|---------|---------|
|Depuis le mois de février 2019 et le déploiement sur les prochains mois, des capacités d'aide à la décision sont ajoutées à la protection avancée contre les [menaces](https://docs.microsoft.com/office365/securitycompliance/office-365-ti) . <br>Si votre organisation ne dispose pas de la protection avancée contre les menaces, vous avez de nouvelles options à prendre en compte, notamment les plans ATP 1 et DAV 2. <br>Pour en savoir plus, consultez la rubrique relative à la [disponibilité des fonctionnalités dans les plans de protection avancée contre les menaces](#feature-availability-across-advanced-threat-protection-atp-plans) (dans cet article) et les [offres et tarifs de protection avancée contre les menaces d'Office 365](https://products.office.com/exchange/advance-threat-protection). |Vérifiez l'abonnement de votre organisation et, si nécessaire, [achetez ou modifiez un module complémentaire](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on).  |
|Depuis le mois d'octobre 2018 et le déploiement sur les prochains mois, lorsque des personnes utilisent Outlook ou Outlook Web App (OWA), les [liens fiables ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) affichent les URL d'origine, et non les URL réécrites. (Nous appelons ce rendu de liaison native.)<br>Lorsque le rendu de liens natif est disponible pour votre organisation, cette fonctionnalité fonctionne dans Outlook 365 (démarrer en un clic) et OWA.|Aucune         |
|À partir du 2018 septembre, les [pages d'avertissement ATP Office 365](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages) comportent un nouveau jeu de couleurs, des détails supplémentaires, ainsi que la possibilité de continuer sur un site malgré des avertissements et des recommandations. |Aucune         |
|Depuis la deuxième moitié de 2018, la protection [des liens fiables ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) est étendue pour s'appliquer aux URL dans Office Online (Word Online, Excel Online, PowerPoint Online et OneNote Online) et Office 365 ProPlus sur Mac.   |[Vérifier et modifier vos stratégies de liens fiables ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|À compter du 2018 mai, les fonctionnalités de mise en quarantaine &amp; dans le centre de sécurité conformité sont étendues à la protection avancée contre les menaces [pour SharePoint Online, OneDrive entreprise et Microsoft teams](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams). |[Vérifier et modifier vos stratégies de pièces jointes approuvées ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|Depuis le 2018 mars, la protection [des liens fiables ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) est étendue pour s'appliquer aux courriers électroniques envoyés entre les personnes au sein d'une organisation. |[Vérifier et modifier vos stratégies de liens fiables ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|À compter de la fin du 1er octobre 2017, la protection [des liens fiables ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) est étendue aux URL de messagerie électronique ainsi qu'aux URL des documents Office 365 ProPlus, comme Word, Excel, PowerPoint et Visio sous Windows, ainsi qu'aux applications Office sur les appareils iOS et Android.  |Assurez-vous que vous utilisez l' [authentification moderne pour Office](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Configuration requise pour Office 365 - Protection avancée contre les menaces

La protection avancée contre les menaces peut être utilisée avec n'importe quel agent de transfert de courrier SMTP, tel que Microsoft Exchange Server. Pour plus d'informations sur les systèmes d'exploitation, les navigateurs Web et les langues pris en charge par la protection avancée contre les menaces, consultez les sections «navigateurs pris en charge» et «langues prises en charge» dans le [Centre d'administration Exchange dans Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilité des fonctionnalités pour les différents plans Protection avancée contre les menaces

Chaque fonctionnalité est indiquée ci-dessous. La mention « Exchange Online » fait généralement référence à la famille de services Office 365 Entreprise.
  
|**Fonctionnalité**|**Plan de l'ATP 1**<br>(anciennement ATP)|**ATP-plan 2**<br>(anciennement intelligence des menaces <br>individuel | Office 365 Entreprise E5| 
|:-----|:-----|:-----|:-----|
| *Configuration, protection et détection* | 
|Pièces jointes fiables |Oui|Non |Non|
|Liens fiables |Oui|Non |Non | 
|Stratégies anti-hameçonnage |Oui |Non |Non |
|ATP pour SharePoint, OneDrive et Microsoft teams |Oui |Non |Non|
|Liens fiables dans teams |Oui|Non |Non |
|Rapports en temps réel |Oui |Non |Non|
|*Automatisation, recherche, correction et éducation* |
|Suivi des menaces |Non |Oui |Non |
|Explorateur (enquête avancée contre les menaces) |Non |Oui |Non |
|Analyse et réponse automatisées  |Non |Oui |Non |
|Simulateur d'attaque |Non |Oui |Non |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Fonctionnalités de Protection avancée contre les menaces

### <a name="safe-attachments"></a>Pièces jointes fiables

[Les pièces jointEs approuvéEs ATP](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) protègent contre les programmes malveillants et les virus inconnus et fournissent une protection contre les menaces pour protéger votre système de messagerie. Tous les messages et les pièces jointes sans signature de virus/programmes malveillants connus sont acheminés vers un environnement spécial où la protection avancée contre les menaces utilise diverses techniques d'analyse et d'apprentissage automatique pour détecter les intentions malveillantes. Si aucune activité suspecte n'est détectée, le message est remis à la boîte aux lettres. 

### <a name="safe-links"></a>Liens fiables

La fonctionnalité de [liens fiables ATP](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) protège de manière proactive vos utilisateurs contre les URL malveillantes dans un message ou dans un document Office. La protection reste à chaque fois qu'ils cliquent sur le lien, car les liens malveillants sont bloqués dynamiquement lorsque des liens valides sont accessibles.

### <a name="anti-phishing-policies"></a>Stratégies anti-hameçonnage

[Protection contre le hameçonnage](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) pour les messages entrants pour les indicateurs qu'un message peut être une tentative de hameçonnage. Lorsque les utilisateurs sont couverts par des stratégies ATP (pièces jointes fiables, liens fiables ou anti-hameçonnage), les messages entrants sont évalués par plusieurs modèles d'apprentissage automatique qui analysent les messages et l'action appropriée est entreprise en fonction des stratégies configurées.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP pour SharePoint, OneDrive et Microsoft Teams.

La protection avancée contre [les menaces pour SharePoint, OneDrive et Microsoft teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) permet de détecter et de bloquer des fichiers identifiés comme étant malveillants dans les sites d'équipe et les bibliothèques de documents.

### <a name="real-time-reports"></a>Rapports en temps réel

Les fonctionnalités de surveillance disponibles dans le centre de sécurité Office 365 Security & incluent des [rapports en temps réel et](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) des informations qui permettent aux administrateurs de la sécurité et de la conformité de se concentrer sur des problèmes à haute priorité, tels que des attaques de sécurité ou activité suspecte plus importante. En plus de mettre en surbrillance les zones problématiques, les rapports intelligents et les idées contiennent des recommandations et des liens permettant d'afficher et d'explorer les données et d'effectuer des actions rapides. 
  
### <a name="threat-trackers"></a>Suivi des menaces

Les analyseurs de [menace](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) sont des widgets informatifs et des vues qui fournissent aux utilisateurs autorisés des renseignements sur les problèmes de Cybersecurity susceptibles d'avoir un impact sur votre organisation.

### <a name="explorer"></a>Navigateur

[Explorateur](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (également appelé «Explorateur de menaces») est un rapport en temps réel qui permet aux utilisateurs autorisés d'identifier et d'analyser les menaces récentes. Par défaut, ce rapport affiche les données des 7 derniers jours; Toutefois, les vues peuvent être modifiées pour afficher les données des 30 derniers jours. 

### <a name="attack-simulator"></a>Simulateur d'attaque
  
Le simulateur d' [attaque](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) permet aux utilisateurs autorisés d'exécuter des scénarios d'attaque réaliste dans votre organisation. Plusieurs types d'attaques sont disponibles, y compris une attaque de Spear Phishing, une attaque par pulvérisation de mot de passe et une attaque de mot de passe en force.