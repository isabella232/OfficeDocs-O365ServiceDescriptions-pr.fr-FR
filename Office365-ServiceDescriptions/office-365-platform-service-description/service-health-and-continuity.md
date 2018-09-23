---
title: État des services
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Les administrateurs de Microsoft Office 365 peuvent afficher l’état des services et découvrez lors de la planification de maintenance. Informations d’intégrité de service sont disponibles à tout moment en vous connectant à Office 365.
ms.openlocfilehash: cc19a26f7bef070837b1dfa53df927373fd35d3e
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035658"
---
# <a name="service-health-and-continuity"></a>État des services

Les administrateurs de Microsoft Office 365 peuvent afficher l’état des services et découvrez lors de la planification de maintenance. Informations d’intégrité de service sont disponibles à tout moment en vous connectant à Office 365.
  
> [!NOTE]
> Si vous utilisez Office 365 géré par 21Vianet, certaines des informations ci-dessous peuvent ne pas vous concerner. Consultez plutôt le [contrat de niveau de service 21Vianet](http://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Afficher l'état des Services

La section de l’intégrité de Service d’Office 365 indique l’état actuel du service et plus d’informations sur les interruptions de service et des pannes. Informations de maintenance prévues sont disponibles sur le centre de messages. Pour plus d’informations, voir [Afficher le statut de vos services](https://go.microsoft.com/fwlink/p/?LinkID=270178). 
  
## <a name="service-incidents"></a>Incidents de service

Un incident de service est un événement qui affecte la remise d’un service. Incidents de service peuvent être dû à des défaillances matérielles ou logicielles dans le centre de données Microsoft, une connexion réseau défaillante entre le client et Microsoft ou un défi de centre de données principales comme incendie, flux ou catastrophe régionale. La plupart des incidents de service peuvent être gérés à l’aide de solutions de processus et de la technologie Microsoft et sont résolus au sein d’un court instant. Toutefois, certains incidents de service sont plus graves et peuvent entraîner des pannes de termes plus.
  
Il existe deux types de notifications sur les temps lorsque les services ne soient pas disponibles :
  
- **Planifié événements maintenance :** La maintenance planifiée est mises à jour régulières service initiées par Microsoft pour les applications de l’infrastructure et de logiciels. Notifications de maintenance planifiée informent les utilisateurs sur le travail de service qui peut-être affecter la fonctionnalité de service Office 365. Les clients sont communiquées au plus tard de cinq jours avant la maintenance planifiée tous les via le centre de messages sur le portail d’administration d’Office 365. Microsoft généralement des plans de maintenance pour les heures lorsque l’utilisation des services est toujours le plus basée sur fuseaux horaires régionaux. 
    
- **Temps d'arrêt non planifiés :** Les incidents de service non planifiés surviennent quand un des services de la suite Office 365 est indisponible ou ne répond pas. 
    
## <a name="notification-policy"></a>Stratégie de notification

Lorsqu’un incident de service se produit, Microsoft reconnaît que les communications en temps voulu, ciblées et précises sont critiques pour les clients. Microsoft avertit les administrateurs Office 365 en mettant à jour le tableau de bord de santé Service client spécifique (SHD) sur le portail d’administration d’Office 365. Mises à jour incidents services sont fournis sur une cadence horaire ou, si une autre cadence est requise, il sera indiqué lors de la validation de communication SHD. 
  
## <a name="service-health-communication-channels"></a>Canaux de communication de l'état du service

### <a name="office-365-admin-app"></a>Application d'administration Office 365

L’application d’administration pour les administrateurs de clients Office 365 vous donne la possibilité de se connecter à l’état du service Office 365 de votre organisation en déplacement. Les administrateurs Office 365 client auront la possibilité d’afficher le service d’intégrité des informations et la maintenance état mises à jour à partir de leurs appareils mobiles. Pour plus d’informations, consultez la [FAQ d’application d’administration](https://community.office365.com/en-us/w/manage/office-365-admin-app-faq.aspx).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Pack d'administration d'Office 365 pour Microsoft System Center 2012 R2

Microsoft System Center est une plate-forme de gestion intégrés que permet de gérer les centres de données, périphériques clients et hybride environnements informatiques en nuage. Les administrateurs Office 365 qui utilisent System Center maintenant ont la possibilité d’importer le Pack d’administration Office 365, qui leur permet d’afficher toutes les communications de service dans Operations Manager dans System Center. À l’aide de cet outil vous permet d’accéder à l’état de vos services abonnés, incidents actifs et résolus service et vos communications centre de messages. Pour plus d’informations, consultez le billet de blog [nouvel Office 365 les outils d’administration](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) . 
  
### <a name="office-365-service-communications-api"></a>API de communications de service Office 365

L’API de communications de service Office 365 vous permet d’accéder aux communications de service Office 365 comme vous le souhaitez. Grâce à ce nouvel outil d’administration, vous pouvez désormais créer ou connecter vos outils aux communications de service Office 365, ce qui peut simplifier la manière dont vous surveillez votre environnement. L’API de communications de service vous permet de surveiller les éléments suivants dans votre environnement :
  
- État du service en temps réel
    
- Communications du centre de messages
    
- Avis de maintenance planifiée
    
Pour plus d'informations, consultez le billet de blog sur les [nouveaux outils d'administration Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/). 
  
## <a name="post-incident-reviews"></a>Analyses post-incident

L'engagement de Microsoft pour une amélioration continue implique l'analyse des incidents de service qui concernent les clients pour diminuer le risque de récidive. 
  
Incidents de service non planifiées sont définis comme des interruptions de service de plusieurs clients impact sur l’utilisation des services, tel que défini par notre SLA de service et ont été déclarées comme tels dans le tableau de bord de l’intégrité de Service.
  
 Non planifié ayant un impact sur le client service incidents dans lequel il a été étendue et notable impact entre un grand nombre d’organisations, un rapport préliminaire post-incident révision (post-incident) seront remis par le biais de votre tableau de bord de l’intégrité de Service dans les 48 heures d’incident résolution, suivie d’un rapport final post-incident dans cinq jours ouvrés. Le rapport détaillé PIR comprend : 
  
- Impact sur les clients et l'expérience utilisateur
    
- Date/Heure de début et de fin de l'incident
    
- Chronologie détaillée des mesures d’impact et résolution
    
- Analyse des causes fondamentales et mesures prises pour une amélioration continue
    
Pour tous les autres incidents de service, le tableau de bord d’intégrité Service fournit un résumé de clôture de l’incident, y compris un résumé final de l’événement, causes préliminaire, début et fin des heures et informations détaillant les étapes suivantes. Pour cette catégorie d’incident de service, un rapport post-incident ne sera pas généré. 
  
## <a name="service-continuity"></a>Continuité de service

Les offres Microsoft Office 365 sont fournies par des systèmes hautement résistants qui permettent de maintenir des performances de service optimales. Les dispositions de continuité de service font partie de la conception du système Office 365. Ces dispositions permettent à Office 365 de procéder rapidement à la récupération à partir d'événements inattendus, tels qu'une erreur du matériel ou de l'application, l'endommagement des données ou d'autres incidents qui ont une incidence sur les utilisateurs. Ces solutions de continuité de service s'appliquent également en cas de pannes de grande envergure (par exemple, des catastrophes naturelles ou un incident dans un centre de données Microsoft qui provoque l'arrêt de tout le centre de données).
  
Notez bien qu'après la récupération d'une panne de grande envergure, un certain délai doit forcément s'écouler avant la restauration de l'intégralité de la redondance du centre de données du service. Par exemple, si un incident survient dans le centre de données 1, les services sont restaurés par les ressources du centre de données 2. Cependant, il est possible qu'un certain délai s'écoule avant que le centre de données 2 ne bénéficie d'une prise en charge de la continuité du service, soit par des ressources restaurées dans le centre de données 1, soit par de nouvelles ressources dans le centre de données 3. Le [contrat de niveau de service](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) Office 365 s'applique pendant ce temps. Office 365 géré par 21Vianet est régi par un contrat de niveau de service différent. Pour plus d'informations, rendez-vous sur le [site 21Vianet](http://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Assurer la disponibilité des données

Microsoft garantit à tout moment la disponibilité des données du client par le biais des fonctionnalités suivantes :
  
- **Stockage et redondance des données :** Les données du client sont stockées dans un environnement redondant présentant de solides capacités de protection des données qui assurent leur disponibilité, la continuité des affaires et une récupération rapide. Différents niveaux de redondance des données sont mis en œuvre, depuis les disques redondants pour la protection contre les pannes de disques locaux jusqu'à la réplication continue et totale des données dans un centre de données géographiquement diversifié. 
    
- **Surveillance des données :** Les services Office 365 maintiennent des niveaux élevés de performances grâce aux actions suivantes : 
    
  - **Surveillance des bases de données :**
    
  - Processus bloqués
    
  - Perte de paquets
    
  - Processus en file d'attente
    
  - Latence de requête
    
- **Exécution de la maintenance préventive :** La maintenance préventive inclut les vérifications de la cohérence des bases de données, la compression périodique des données et les analyses des journaux d'erreurs. 
    
## <a name="support"></a>Prise en charge

Les équipes de développement et d'exploitation Office 365 sont soutenues par une organisation de support Office 365 dédiée qui contribue à la continuité du service pour les clients. L'équipe de support a une connaissance approfondie du service et des applications associées, et dispose d'un accès direct aux experts Microsoft en architecture, développement et test.
  
L'organisation de support s'aligne étroitement sur les opérations et le développement des produits, offre des temps de résolution très courts et fournit un canal permettant aux clients de se faire entendre. Les commentaires des clients apportent une contribution aux processus de planification, de développement et d'exploitation.
  
- **Suivi des problèmes en ligne :** Les clients ont besoin de savoir que leurs problèmes sont pris en compte et ils doivent pouvoir suivre leur résolution en temps voulu. Le portail Office 365 fournit une interface web unique pour la prise en charge. Les clients peuvent utiliser le portail pour ajouter et surveiller les demandes de service, et recevoir les commentaires des équipes de support Microsoft. 
    
- **Auto-assistance, appuyée par le support continu de l'équipe :** Office 365 propose une large gamme de ressources et d'outils susceptibles d'aider les clients à résoudre les problèmes liés aux services sans solliciter l'aide du support Microsoft. 
    
Avant de soumettre une demande de service, les clients peuvent accéder aux articles de la base de connaissances et aux FAQ qui fournissent une aide immédiate en ce qui concerne les problèmes les plus fréquents. Ces ressources sont continuellement mises à jour avec les informations les plus récentes, ce qui permet d'éviter les temps d'attente en fournissant des solutions aux problèmes connus. Toutefois, lorsqu'un problème nécessite l'aide d'un professionnel du support, les membres de l'équipe sont disponibles pour une assistance immédiate par téléphone et par le biais du portail d'administration 24 h/24 et 7 j/7.
  
Pour plus d'informations sur le support, consultez la rubrique [Prise en charge](https://technet.microsoft.com/en-us/library/office-365-support.aspx). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans Office 365, voir [Description du service de plateforme Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

