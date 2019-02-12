---
title: Description du service Office 365 - Protection avancée contre les menaces
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/08/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Office 365 - Protection avancée contre les menaces est un service informatique de filtrage du courrier électronique qui vous aide à protéger votre organisation contre des virus et des programmes malveillants inconnus grâce à une protection zero-day solide. Ce service comprend des fonctionnalités permettant de protéger en temps réel votre organisation contre des liens dangereux et dispose de fonctionnalités avancées de suivi d’URL et de création de rapports qui donnent aux administrateurs un aperçu du type d’attaques ayant lieu dans l’organisation.
ms.openlocfilehash: aeddc27c0275cb21ec257878e0978961356e7a85
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/11/2019
ms.locfileid: "29884195"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Description du service Office 365 - Protection avancée contre les menaces

Office 365 - Protection avancée contre les menaces est un service informatique de filtrage du courrier électronique qui vous aide à protéger votre organisation contre des virus et des programmes malveillants inconnus grâce à une protection zero-day solide. Ce service comprend des fonctionnalités permettant de protéger en temps réel votre organisation contre des liens dangereux et dispose de fonctionnalités avancées de suivi d’URL et de création de rapports qui donnent aux administrateurs un aperçu du type d’attaques ayant lieu dans l’organisation.
  
Voici les principales manières d’utiliser DAV pour la protection de message :
  
- Dans un scénario de filtrage uniquement Office 365 DAV, DAV offre une protection de messagerie en nuage pour votre environnement de serveur Exchange local ou toute autre solution de messagerie de SMTP locale.
    
- Office 365 - Protection avancée contre les menaces peut être activé pour protéger les boîtes aux lettres Exchange Online hébergées dans le cloud. Pour en savoir plus sur Exchange Online, reportez-vous à l'article [Description du service Exchange Online](exchange-online-service-description/exchange-online-service-description.md).
    
- Dans un déploiement hybride, le service peut être configuré pour protéger votre environnement de messagerie et contrôler le routage de messagerie lorsque vous disposez à la fois de boîtes aux lettres locales et de boîtes aux lettres dans le cloud avec Exchange Online Protection pour le filtrage des messages entrants.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilité d'Office 365 - Protection avancée contre les menaces

DAV est inclus dans Office 365 entreprise E5 et 365 entreprise de Microsoft Office 365 éducation A5. 
  
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

À partir de février 2019 et présentant plusieurs mois suivant, fonctionnalités d’aide à la décision de menace sont ajoutées à DAV. En outre, si votre organisation ne dispose pas actuellement DAV, vous aurez nouvelles options à prendre en compte, y compris DAV Plan 1 et DAV Plan 2. Pour plus d’informations, voir [plans Office 365 avancée protection contre les menaces et les prix](https://products.office.com/en-us/exchange/advance-threat-protection#pmg-allup-content) et la [disponibilité des fonctionnalités dans les plans de Protection de menace avancées (DAV)](#feature-availability-across-advanced-threat-protection-atp-plans).

Pour plus d’informations sur les nouvelles fonctionnalités dans DAV, voir [nouvelles fonctionnalités de DAV](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp).
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Configuration requise pour Office 365 - Protection avancée contre les menaces

Le service peut être utilisé avec n'importe quel agent de transfert de messagerie SMTP, tel que Microsoft Exchange Server 2013. Pour plus d'informations sur les systèmes d'exploitation, les navigateurs web et les langues pris en charge par ce service, voir les sections « Navigateurs pris en charge » et « Langues prises en charge dans EOP » de l'article [Centre d'administration Exchange dans Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilité des fonctionnalités pour les différents plans Protection avancée contre les menaces

Chaque fonctionnalité est indiquée ci-dessous. La mention « Exchange Online » fait généralement référence à la famille de services Office 365 Entreprise.
  
|**Fonctionnalité**|**DAV Plan 1**<br>(anciennement DAV autonome)|**DAV Plan 2**<br>(anciennement menace aide à la décision <br>autonome) | Office 365 Entreprise E5| 
|:-----|:-----|:-----|:-----|
| *Configuration, la Protection et la détection* | 
|Pièces jointes fiables |Oui|Non |Non|
|Liens fiables |Oui|Non |Non | 
|Stratégies anti-hameçonnage |Oui |Non |Non |
|DAV pour SharePoint, OneDrive et les équipes Microsoft |Oui |Non |Non|
|Liens fiables dans les équipes |Oui|Non |Non |
|Rapports en temps réel |Oui |Non |Non|
|*Automation, enquête, mise à jour et formation* |
|Menaces suivis |Non |Oui |Non |
|Explorateur de solutions (avancée enquête menace) |Non |Oui |Non |
|Enquête automatisé et réponse  |Non |Oui |Non |
|Attaque Simulator |Non |Oui |Non |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Fonctionnalités de Protection avancée contre les menaces

### <a name="safe-attachments"></a>Pièces jointes fiables

[Pièces jointes sûres DAV](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) contre les virus et les programmes malveillants inconnus et offre une protection zéro jour pour protéger votre système de messagerie. Tous les messages et pièces jointes qui n’ont pas une signature antivirus/programmes malveillants connus sont routés vers un environnement spécial où DAV utilise de diverses techniques d’apprentissage et analyse de la machine à détecter malveillantes. Si aucune activité suspecte n’est détectée, le message est publié pour la remise de la boîte aux lettres. 

### <a name="safe-links"></a>Liens fiables

La fonctionnalité [Liens fiables DAV](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) proactive protège vos utilisateurs des URL malveillantes dans un message ou dans un document Office. La protection reste chaque fois qu’ils cliquent sur le lien, que les liens malveillants sont bloquées dynamiquement tandis que les liens bonne est accessible.

### <a name="anti-phishing-policies"></a>Stratégies anti-hameçonnage

[DAV anti-hameçonnage](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) vérifie les messages entrants pour les indicateurs qu’un message peut être une tentative de hameçonnage. Lorsque les utilisateurs sont couverts par les stratégies DAV (pièces jointes fiables, liens sans échec ou anti-hameçonnage), les messages entrants sont évaluées par ordinateur plusieurs modèles qui analysent les messages de la formation et l’action appropriée est effectuée, selon les stratégies configurées.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP pour SharePoint, OneDrive et Microsoft Teams.

[DAV pour SharePoint, OneDrive et les équipes Microsoft](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) permet de détecter et de bloquer les fichiers qui sont identifiés comme malveillants dans les sites d’équipe et des bibliothèques de documents.

### <a name="real-time-reports"></a>Rapports en temps réel

Surveillance des fonctionnalités disponibles dans le cadre sécurité Office 365 & centre de conformité incluent les [analyses et des rapports en temps réel](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) qui permettent de sécurité et conformité aux administrateurs de se concentrer sur les problèmes de haute priorité, tels que les attaques de sécurité ou augmentation de l’activité suspecte. Met en évidence les zones à problème, analyses et des rapports intelligents incluent des liens pour afficher et Explorer les données et également effectuer les actions rapides et des recommandations. 
  
### <a name="threat-trackers"></a>Menaces suivis

[Menaces suivis](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) sont informatifs widgets et les affichages permettant aux utilisateurs autorisés d’aide à la décision sur les problèmes de sécurité qui pourraient affecter votre organisation.

### <a name="explorer"></a>Explorateur de solutions

[Explorateur de solutions](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (également appelé Threat Explorer) est un rapport en temps réel que permet aux utilisateurs autorisés pour identifier et analyser les menaces récents. Par défaut, ce rapport affiche les données pour les 7 derniers jours ; Toutefois, les vues peuvent être modifiés pour afficher les données pour les 30 derniers jours. 

### <a name="attack-simulator"></a>Attaque Simulator
  
[Attaque Simulator](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) permet à des utilisateurs autorisés à exécuter des scénarios d’attaque réaliste dans votre organisation. Différents types d’attaques sont disponibles, y compris une attaque par hameçonnage de la sonde de nom complet, une attaque par mot de passe-Jet et une attaque par mot de passe en force brute.