---
title: État des services et continuité
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Les administrateurs Microsoft peuvent afficher l’état des services et savoir quand la maintenance est programmée. Les informations d’état du service sont disponibles à tout moment en se signant.
ms.openlocfilehash: ec8e03d31a300755ab741723b81651d6d6969b37
ms.sourcegitcommit: c455501e86037b0f86e0afc9d6d6d04afdfd3442
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/28/2021
ms.locfileid: "52074495"
---
# <a name="service-health-and-continuity"></a>État des services et continuité

Les administrateurs Microsoft peuvent afficher l’état des services et savoir quand la maintenance est programmée. Les informations d’état du service sont disponibles à tout moment en se signant.
  
> [!NOTE]
> Si vous utilisez Office 365 géré par 21Vianet, certaines des informations ci-dessous peuvent ne pas vous concerner. Consultez plutôt le [contrat de niveau de service 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Afficher l’état des services

La section État du service indique l’état actuel du service et des détails sur les interruptions et les pannes de service. Les informations de maintenance planifiée sont disponibles dans le centre de messages. Pour plus d'informations, consultez la rubrique [Vérifier l'état du service Office 365](/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidents de service

Un incident de service est un événement qui a une incidence sur la prestation d’un service. Les incidents de service peuvent être causés par une défaillance matérielle ou logicielle dans le centre de données Microsoft, une connexion réseau défectueux entre le client et Microsoft ou un défi majeur du centre de données, tel que le feu, le débordement ou la catastrophe régionale. La plupart des incidents de service peuvent être résolus au moyen des technologies et solutions de traitement Microsoft, dans un délai court. Cependant, certains incidents de service sont plus graves et peuvent aboutir à des pannes à plus long terme.
  
Il existe deux types de notifications concernant les moments où les services peuvent ne pas être disponibles :
  
- **Événements de maintenance planifiée :** La maintenance planifiée est une mise à jour régulière du service initié par Microsoft pour l’infrastructure et les applications logicielles. Les notifications de maintenance planifiée informent les clients du travail de service qui peut affecter les fonctionnalités d’un service Microsoft. Les clients sont avertis au plus tard cinq jours avant toute maintenance planifiée via le Centre de messages Microsoft 365 centre d’administration. Microsoft prévoit généralement une maintenance pour les périodes où l’utilisation du service est historiquement à son plus bas en fonction des fuseaux horaires régionaux. 
    
- **Temps d’arrêt non planifié :** Des incidents de service non planifiés se produisent lorsqu’un des services n’est pas disponible ou ne répond pas. 

### <a name="recent-worldwide-uptimes"></a>Temps de travail récents dans le monde

Le passage à un service cloud ne doit pas signifier perdre la possibilité de savoir ce qui se passe. Avec Office 365, ce n’est pas le cas. Notre objectif est d’être transparent dans nos opérations afin que vous pouvez surveiller l’état de votre service, suivre les problèmes et avoir une vue historique de la disponibilité. Les tableaux suivants indiquent les données récentes de temps de travail dans le monde entier.

**2021**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97% <br/> | | | |

<br>

**2020**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.98% <br/> | 99,99 %<br/> | 99.97%<br/> | 99.97%<br/> |

<br>

**2019**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97% <br/> | 99.97% <br/> | 99.98% <br/> | 99.98% <br/> |

<br>

**2018**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99,99 % <br/> | 99.98% <br/> | 99.97% <br/> | 99.98% <br/> |

<br>

**2017**

| Q1 | Q2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99,99 % <br/> | 99.97% <br/> | 99.98% <br/> | 99,99 % <br/> |

## <a name="notification-policy"></a>Stratégie de notification

Quand un incident de service se produit, Microsoft reconnaît que les communications ciblées, précises et fournies en temps utile sont critiques pour les clients. Microsoft avertit les administrateurs en mettant à jour le tableau de bord d’état du service propre au client sur le centre d Microsoft 365'administration. Les mises à jour des incidents de service sont fournies à une cadence horaire ou, si une autre cadence est requise, elle sera précisée dans la publication de communication shd. 
  
## <a name="service-health-communication-channels"></a>Canaux de communication d’état du service

### <a name="admin-app"></a>Application Administrateur

L’application d’administration pour les administrateurs de l’organisation vous permet de vous connecter à l’état du service Microsoft de votre organisation en libre-service. Les administrateurs Microsoft ont la possibilité d’afficher les informations d’état du service et les mises à jour de l’état de maintenance à partir de leurs appareils mobiles. Pour plus d’informations, consultez le [FAQ sur l’application d’administration](/office365/admin/admin-overview/admin-mobile-app).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Pack d’administration d’Office 365 pour Microsoft System Center 2012 R2

Microsoft System Center est une plateforme de gestion intégrée qui vous permet de gérer un centre de données, des appareils clients et des environnements informatiques hybrides. Les administrateurs Microsoft qui utilisent System Center ont désormais la possibilité d’importer le pack d’administration Office 365, ce qui leur permet d’afficher toutes les communications de service dans Operations Manager dans System Center. L'utilisation de cet outil vous permet d'accéder à l'état des services auxquels vous êtes abonné, aux incidents de service actifs et résolus, et aux communications de votre Centre de messages. Pour plus d’informations, obtenez le pack [d’administration Microsoft System Center pour](https://www.microsoft.com/download/details.aspx?id=43708) Office 365 dans le Centre de téléchargement Microsoft. 
  
### <a name="office-365-service-communications-api"></a>API de communications de service Office 365

L’API Office 365 Service Communications vous permet d’accéder aux communications de service comme vous le souhaitez. Avec cette API, vous avez la possibilité de créer ou de connecter vos outils aux communications de service, ce qui simplifie potentiellement la façon dont vous surveillez votre environnement. L’API Service Communications vous permet de surveiller les éléments suivants de votre environnement :
  
- État du service en temps réel
    
- Communications du centre de messages
    
Pour plus d’informations, voir la [référence Office 365 API Service Communications.](/office/office-365-management-api/office-365-service-communications-api-reference) 
  
## <a name="post-incident-reviews"></a>Analyses post-incident

L'engagement de Microsoft pour une amélioration continue implique l'analyse des incidents de service qui concernent les clients pour diminuer le risque de récidive. 
  
Les incidents de service non planifiés sont définis comme des interruptions de service à plusieurs clients qui ont une incidence sur l’utilisation du service telles que définies par nos contrats de niveau de service (SSL) et ont été déclarées en tant que telles dans le Tableau de bord d’état du service.
  
 Pour les incidents de service non planifiés qui ont eu un impact important et perceptible sur un grand nombre d’organisations, une analyse post-incident préliminaire sera livrée via votre tableau de bord d’état du service dans les 48 heures suivant la résolution de l’incident, puis une analyse post-incident finale dans les cinq jours ouvrée. Le rapport détaillé sur la pir inclut les informations ci-après : 
  
- Impact sur les clients et l'expérience utilisateur
    
- Date/Heure de début et de fin de l'incident
    
- Chronologie détaillée des mesures d’impact et de résolution
    
- Analyse des causes fondamentales et mesures prises pour une amélioration continue
    
Pour tous les autres incidents de service, le tableau de bord d’état du service fournit un résumé de clôture des incidents, y compris un résumé final de l’événement, la cause racine préliminaire, les heures de début et de fin, ainsi que des informations détaillées sur les étapes suivantes. Pour cette catégorie d'incident de service, aucune analyse post-incident n'est générée. 
  
## <a name="service-continuity"></a>Service continuity

Les offres Microsoft sont livrées par des systèmes hautement résilients qui permettent de maintenir des performances de service maximales. Les dispositions de continuité de service font partie de la conception du système. Ces dispositions permettent à Microsoft de récupérer rapidement des événements inattendus tels que la défaillance du matériel ou de l’application, l’altération des données ou d’autres incidents qui affectent les utilisateurs. Ces solutions de continuité de service s'appliquent également en cas de pannes de grande envergure (par exemple, des catastrophes naturelles ou un incident dans un centre de données Microsoft qui provoque l'arrêt de tout le centre de données).
  
Notez bien qu'après la récupération d'une panne de grande envergure, un certain délai doit forcément s'écouler avant la restauration de l'intégralité de la redondance du centre de données du service. Par exemple, si un incident survient dans le centre de données 1, les services sont restaurés par les ressources du centre de données 2. Cependant, il est possible qu'un certain délai s'écoule avant que le centre de données 2 ne bénéficie d'une prise en charge de la continuité du service, soit par des ressources restaurées dans le centre de données 1, soit par de nouvelles ressources dans le centre de données 3. Le contrat [de niveau de service](service-level-agreement.md) (SLA) Microsoft s’applique pendant ce temps. Office 365 géré par 21Vianet est régi par un contrat de niveau de service différent. Pour plus d’informations, voir [le site 21Vianet.](https://www.21vbluecloud.com/office365/O365-SLA/) 
  
## <a name="ensuring-data-availability"></a>Assurer la disponibilité des données

Microsoft garantit à tout moment la disponibilité des données du client par le biais des fonctionnalités suivantes :
  
- **Stockage et redondance des données :** Les données du client sont stockées dans un environnement redondant présentant de solides capacités de protection des données qui assurent leur disponibilité, la continuité des affaires et une récupération rapide. Différents niveaux de redondance des données sont mis en œuvre, depuis les disques redondants pour la protection contre les pannes de disques locaux jusqu'à la réplication continue et totale des données dans un centre de données géographiquement diversifié. 
    
- **Surveillance des données : services Microsoft** maintenir des niveaux de performances élevés en surveillant : 
    
  - Databases
    
  - Processus bloqués
    
  - Perte de paquets
    
  - Processus en file d'attente
    
  - Latence de requête
    
- **Exécution de la maintenance préventive :** La maintenance préventive inclut les vérifications de la cohérence des bases de données, la compression périodique des données et les analyses des journaux d’erreurs. 
    
## <a name="support"></a>Support

Les équipes de développement et d’exploitation Microsoft sont complétées par une organisation de support dédiée, qui joue un rôle important dans la continuité des activités des clients. L'équipe de support détient une connaissance approfondie du service et ses applications associées, et dispose d'un accès direct aux experts Microsoft en architecture, développement et test.
  
L'organisation de support correspond étroitement aux opérations et au développement produits, offre des temps de résolution très courts et fournit un canal permettant aux clients de se faire entendre. Les commentaires des clients contribuent à la planification, le développement et les processus d'exploitation.
  
- **Suivi des problèmes en ligne :** Les clients ont besoin de savoir que leurs problèmes sont pris en compte et ils doivent pouvoir suivre leur résolution en temps voulu. Le Microsoft 365'administration centrale fournit une interface web unique pour la prise en charge. Les clients peuvent utiliser le portail pour ajouter et surveiller les demandes de service et recevoir les commentaires des équipes de support Microsoft. 
    
- **Autonome, soutenu par le support continu du personnel :** Microsoft offre un large éventail de ressources et d’outils autonomes qui peuvent aider les clients à résoudre les problèmes liés au service sans nécessiter le support de Microsoft. 
    
Avant d'entrer une demande de service, les clients ont accès aux articles de la base de données et aux FAQ qui fournissent une aide immédiate en ce qui concerne les problèmes les plus fréquents. Ces ressources sont continuellement mises à jour avec les informations les plus récentes, permettant ainsi d'éviter les temps d'attente en fournissant des solutions aux problèmes connus. Toutefois, lorsqu'un problème survient et requiert l'aide d'une assistance professionnelle, les membres de l'équipe sont disponibles pour une assistance immédiate par téléphone et par le biais du portail d'administration 24h/24 et 7j/7.
  
Pour plus d’informations sur le support, consultez [l’article de support.](support.md) 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les différents plans, voir [Microsoft 365 et Office 365 description du service de plateforme.](office-365-platform-service-description.md)
