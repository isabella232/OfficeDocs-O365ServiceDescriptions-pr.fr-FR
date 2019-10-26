---
title: État des services
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Les administrateurs de Microsoft Office 365 peuvent afficher l’état des services et savoir quand la maintenance est planifiée. Les informations relatives à l’état du service sont disponibles à tout moment en se connectant à Office 365.
ms.openlocfilehash: 76e202056145aca9c4a1bbe390728e6a4e062753
ms.sourcegitcommit: fb245074a57da585566096f6956d37325f451262
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/26/2019
ms.locfileid: "37734051"
---
# <a name="service-health-and-continuity"></a>État des services

Les administrateurs de Microsoft Office 365 peuvent afficher l’état des services et savoir quand la maintenance est planifiée. Les informations relatives à l’état du service sont disponibles à tout moment en se connectant à Office 365.
  
> [!NOTE]
> Si vous utilisez Office 365 géré par 21Vianet, certaines des informations ci-dessous peuvent ne pas vous concerner. Consultez plutôt le [contrat de niveau de service 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Afficher l'état des Services

La section service Health d’Office 365 affiche l’état actuel du service et des détails sur les interruptions de service et les pannes. Les informations de maintenance planifiée sont disponibles dans le centre de messages. Pour plus d'informations, consultez la rubrique [Vérifier l'état du service Office 365](https://docs.microsoft.com/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidents de service

Un incident de service est un événement qui a une incidence sur la prestation d’un service. Les incidents de service peuvent être causés par des défaillances matérielles ou logicielles dans le centre de données Microsoft, une connexion réseau défectueuse entre le client et Microsoft, ou un défi majeur pour le centre de données, tel qu’un incendie, une inondation ou une catastrophe régionale. La plupart des incidents de service peuvent être résolus au moyen des technologies et solutions de traitement Microsoft, dans un délai court. Cependant, certains incidents de service sont plus graves et peuvent aboutir à des pannes à plus long terme.
  
Il existe deux types de notifications concernant les heures où les services peuvent ne pas être disponibles :
  
- **Événements de maintenance planifiée :** La maintenance planifiée est une mise à jour normale des services initiés par Microsoft vers les applications logicielles et d’infrastructure. Les notifications de maintenance planifiée informent les clients du travail de service susceptible d’affecter les fonctionnalités d’un service Office 365. Les clients sont informés au plus tard cinq jours avant l’avancement de toutes les opérations de maintenance planifiée via le centre de messages sur le portail d’administration Office 365. Microsoft prévoit généralement la maintenance pour les heures où l’utilisation du service est historique en fonction de ses fuseaux horaires régionaux. 
    
- **Temps d'arrêt non planifiés :** Les incidents de service non planifiés surviennent quand un des services de la suite Office 365 est indisponible ou ne répond pas. 

### <a name="recent-worldwide-uptimes"></a>Délais récents pour le monde entier

Le passage à un service Cloud ne doit pas signifier perdre la capacité à savoir ce qui se passe. Avec Office 365, il ne l’est pas. Nous souhaitons être transparents dans nos opérations afin que vous puissiez surveiller l’état de votre service, suivre les problèmes et avoir un aperçu de la disponibilité. Les tableaux suivants présentent les données de disponibilité les plus récentes dans le monde entier.

<br/>

|**2019** <br/> ||||
|:-----|:-----|:-----|:-----|
| **T1** <br/> | **2ème** <br/> |**T3** <br/> |**4e** <br/> |
| 99,97% <br/> | 99,97% <br/> |  <br/> |  <br/> |

<br/>

|**2018** <br/>||||
|:-----|:-----|:-----|:-----|
| **T1** <br/> | **2ème** <br/> |**T3** <br/> |**4e** <br/> |
| 99,99 % <br/> | 99,98% <br/> | 99,97% <br/> | 99,98% <br/> |

<br/>

|**2017** <br/> ||||
|:-----|:-----|:-----|:-----|
| **T1** <br/> | **2ème** <br/> |**T3** <br/> |**4e** <br/> |
| 99,99 % <br/> | 99,97% <br/> | 99,98% <br/> | 99,99 % <br/> |

<br/>

## <a name="notification-policy"></a>Stratégie de notification

Quand un incident de service se produit, Microsoft reconnaît que les communications ciblées, précises et fournies en temps utile sont critiques pour les clients. Microsoft informe les administrateurs d’Office 365 en mettant à jour le tableau de bord d’intégrité du service propre au client (validation) sur le portail d’administration d’Office 365. Les mises à jour des incidents de service sont fournies à une cadence horaire ou, si une cadence différente est requise, elles seront indiquées dans la publication de communication validation. 
  
## <a name="service-health-communication-channels"></a>Canaux de communication de l’état du service

### <a name="office-365-admin-app"></a>Application d’administration Office 365

L’application d’administration pour les administrateurs clients Office 365 vous permet de vous connecter à l’état du service 365 Office de votre organisation en déplacement. Les administrateurs client Office 365 pourront afficher les informations relatives à l’état du service et les mises à jour de l’état de la maintenance à partir de leurs appareils mobiles. Pour plus d'informations, consultez la [FAQ de l'application d'administration](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Pack d’administration d’Office 365 pour Microsoft System Center 2012 R2

Microsoft System Center est une plateforme de gestion intégrée qui vous permet de gérer un centre de données, des appareils clients et des environnements informatiques hybrides. Les administrateurs d’Office 365 qui utilisent System Center ont désormais la possibilité d’importer le pack d’administration d’Office 365, ce qui leur permet d’afficher toutes les communications de service dans Operations Manager dans System Center. L'utilisation de cet outil vous permet d'accéder à l'état des services auxquels vous êtes abonné, aux incidents de service actifs et résolus, et aux communications de votre Centre de messages. Pour plus d'informations, consultez le billet de blog sur les [nouveaux outils d'administration Office 365](https://www.microsoft.com/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/). 
  
### <a name="office-365-service-communications-api"></a>API de communications de service Office 365

L’API de communications de service Office 365 vous permet d’accéder aux communications des services Office 365 comme vous le souhaitez. Grâce à ce nouvel outil d'administration, vous pouvez désormais créer ou connecter vos outils aux communications de service Office 365, ce qui peut simplifier la manière dont vous surveillez votre environnement. L’API de communications de service vous permet de surveiller les éléments suivants dans votre environnement :
  
- État du service en temps réel
    
- Communications du centre de messages
    
- Avis de maintenance planifiée
    
Pour plus d'informations, consultez le billet de blog sur les [nouveaux outils d'administration Office 365](https://www.microsoft.com/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/). 
  
## <a name="post-incident-reviews"></a>Analyses post-incident

L'engagement de Microsoft pour une amélioration continue implique l'analyse des incidents de service qui concernent les clients pour diminuer le risque de récidive. 
  
Les incidents de service non planifiés sont définis comme des interruptions de service mutualisées qui influent sur l’utilisation du service définies par nos SLA de service, et qui ont été déclarées comme telles sur le tableau de bord d’intégrité des services.
  
 Pour les incidents de service non planifiés ayant un impact sur les clients qui ont eu un impact important et notable sur un grand nombre d’organisations, un examen post-incident préliminaire (PIR) sera fourni via votre tableau de bord d’état des services dans les 48 heures de l’incident. résolution, suivie d’un PIR final dans les cinq jours ouvrés. Le rapport PIR détaillé inclut : 
  
- Impact sur les clients et l'expérience utilisateur
    
- Date/Heure de début et de fin de l'incident
    
- Chronologie détaillée de l’impact et des mesures de résolution
    
- Analyse des causes fondamentales et mesures prises pour une amélioration continue
    
Pour tous les autres incidents de service, le tableau de bord d’État du service fournit un résumé de clôture des incidents incluant un résumé final de l’événement, la cause première initiale, les heures de début et de fin, ainsi que des informations détaillant les étapes suivantes. Pour cette catégorie d’incident de service, aucune analyse post-incident n’est générée. 
  
## <a name="service-continuity"></a>Continuité de service

Les offres Microsoft Office 365 sont fournies par des systèmes hautement résistants qui permettent de maintenir des performances de service optimales. Les dispositions de continuité de service font partie de la conception du système Office 365. Ces dispositions permettent à Office 365 de procéder rapidement à la récupération à partir d'événements inattendus, tels qu'une erreur du matériel ou de l'application, l'endommagement des données ou d'autres incidents qui ont une incidence sur les utilisateurs. Ces solutions de continuité de service s'appliquent également en cas de pannes de grande envergure (par exemple, des catastrophes naturelles ou un incident dans un centre de données Microsoft qui provoque l'arrêt de tout le centre de données).
  
Notez bien qu'après la récupération d'une panne de grande envergure, un certain délai doit forcément s'écouler avant la restauration de l'intégralité de la redondance du centre de données du service. Par exemple, si un incident survient dans le centre de données 1, les services sont restaurés par les ressources du centre de données 2. Cependant, il est possible qu'un certain délai s'écoule avant que le centre de données 2 ne bénéficie d'une prise en charge de la continuité du service, soit par des ressources restaurées dans le centre de données 1, soit par de nouvelles ressources dans le centre de données 3. Le [contrat de niveau de service](service-level-agreement.md) Office 365 s'applique pendant ce temps. Office 365 géré par 21Vianet est régi par un contrat de niveau de service différent. Pour plus d'informations, rendez-vous sur le [site 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Assurer la disponibilité des données

Microsoft garantit à tout moment la disponibilité des données du client par le biais des fonctionnalités suivantes :
  
- **Stockage et redondance des données :** Les données du client sont stockées dans un environnement redondant présentant de solides capacités de protection des données qui assurent leur disponibilité, la continuité des affaires et une récupération rapide. Différents niveaux de redondance des données sont mis en œuvre, depuis les disques redondants pour la protection contre les pannes de disques locaux jusqu'à la réplication continue et totale des données dans un centre de données géographiquement diversifié. 
    
- **Surveillance des données :** Les services Office 365 maintiennent des niveaux élevés de performances grâce aux actions suivantes : 
    
  - **Surveillance des bases de données :**
    
  - Processus bloqués
    
  - Perte de paquets
    
  - Processus en file d'attente
    
  - Latence de requête
    
- **Exécution de la maintenance préventive :** La maintenance préventive inclut les vérifications de la cohérence des bases de données, la compression périodique des données et les analyses des journaux d’erreurs. 
    
## <a name="support"></a>Support

Le développement Office 365 et les équipes d'exploitation sont réalisés par une organisation de support Office 365 dédié qui joue un rôle important dans l'offre aux clients d'une continuité opérationnelle. L'équipe de support détient une connaissance approfondie du service et ses applications associées, et dispose d'un accès direct aux experts Microsoft en architecture, développement et test.
  
L'organisation de support s'aligne étroitement sur les opérations et le développement des produits, offre des temps de résolution très courts et fournit un canal permettant aux clients de se faire entendre. Les commentaires des clients apportent une contribution aux processus de planification, de développement et d'exploitation.
  
- **Suivi des problèmes en ligne :** Les clients ont besoin de savoir que leurs problèmes sont pris en compte et ils doivent pouvoir suivre leur résolution en temps voulu. Le portail Office 365 fournit une interface web unique pour la prise en charge. Les clients peuvent utiliser le portail pour ajouter et surveiller les demandes de service, et recevoir les commentaires des équipes de support Microsoft. 
    
- **Auto-assistance, appuyée par le support continu de l'équipe :** Office 365 propose une large gamme de ressources et d'outils susceptibles d'aider les clients à résoudre les problèmes liés aux services sans solliciter l'aide du support Microsoft. 
    
Avant de soumettre une demande de service, les clients peuvent accéder aux articles de la base de connaissances et aux FAQ qui fournissent une aide immédiate en ce qui concerne les problèmes les plus fréquents. Ces ressources sont continuellement mises à jour avec les informations les plus récentes, ce qui permet d'éviter les temps d'attente en fournissant des solutions aux problèmes connus. Toutefois, lorsqu'un problème nécessite l'aide d'un professionnel du support, les membres de l'équipe sont disponibles pour une assistance immédiate par téléphone et par le biais du portail d'administration 24 h/24 et 7 j/7.
  
Pour plus d'informations sur le support, consultez la rubrique [Prise en charge](support.md). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour connaître les fonctionnalités disponibles dans les offres Office 365, reportez-vous à [Description du service de plateforme Office 365](office-365-platform-service-description.md).
  