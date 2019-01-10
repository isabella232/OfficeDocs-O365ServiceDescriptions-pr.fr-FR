---
title: Description du service Office 365 - Protection avancée contre les menaces
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 01/02/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Office 365 - Protection avancée contre les menaces est un service informatique de filtrage du courrier électronique qui vous aide à protéger votre organisation contre des virus et des programmes malveillants inconnus grâce à une protection zero-day solide. Ce service comprend des fonctionnalités permettant de protéger en temps réel votre organisation contre des liens dangereux et dispose de fonctionnalités avancées de suivi d’URL et de création de rapports qui donnent aux administrateurs un aperçu du type d’attaques ayant lieu dans l’organisation.
ms.openlocfilehash: f8a44cdebebafe575f5c22a3a491671f57b05d49
ms.sourcegitcommit: d1d7309e864398e7d029956231cbaee054a2a0cf
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/09/2019
ms.locfileid: "27784866"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Description du service Office 365 - Protection avancée contre les menaces

Office 365 - Protection avancée contre les menaces est un service informatique de filtrage du courrier électronique qui vous aide à protéger votre organisation contre des virus et des programmes malveillants inconnus grâce à une protection zero-day solide. Ce service comprend des fonctionnalités permettant de protéger en temps réel votre organisation contre des liens dangereux et dispose de fonctionnalités avancées de suivi d’URL et de création de rapports qui donnent aux administrateurs un aperçu du type d’attaques ayant lieu dans l’organisation.
  
Voici les principales manières d’utiliser DAV pour la protection de message :
  
- Dans le cas où vous utilisez Office 365 - Protection avancée contre les menaces à des fins de filtrage uniquement, le service fournit une protection informatique du courrier électronique pour votre environnement Exchange Server 2013 local, les versions d'Exchange Server héritées ou pour toute autre solution de messagerie SMTP locale.
    
- Office 365 - Protection avancée contre les menaces peut être activé pour protéger les boîtes aux lettres Exchange Online hébergées dans le cloud. Pour en savoir plus sur Exchange Online, reportez-vous à l'article [Description du service Exchange Online](exchange-online-service-description/exchange-online-service-description.md).
    
- Dans un déploiement hybride, le service peut être configuré pour protéger votre environnement de messagerie et contrôler le routage de messagerie lorsque vous disposez à la fois de boîtes aux lettres locales et de boîtes aux lettres dans le cloud avec Exchange Online Protection pour le filtrage des messages entrants.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilité d'Office 365 - Protection avancée contre les menaces

DAV est inclus dans Office 365 entreprise E5 et 365 entreprise de Microsoft Office 365 éducation A5. 
  
> [!NOTE]
> Fonctionnalités de DAV dépendant du client dans Microsoft 365 Business sera disponible 2018 été. 
  
Vous pouvez ajouter ce service aux plans d'abonnement Exchange et Office 365 suivants : 
  
- Exchange Online Plan 1
    
- Exchange Online Plan 2
    
- Exchange Online Kiosk
    
- Exchange Online Protection
    
- Office 365 Business Essentials
    
- Office 365 Business Premium
    
- Office 365 Entreprise E1
    
- Office 365 Entreprise E3
    
- Office 365 Entreprise F1
    
- Office 365 A1
    
- Office 365 A3
    
Pour acheter Office 365 - Protection avancée contre les menaces, reportez-vous à l'article [Office 365 - Protection avancée contre les menaces](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Pour comparer les fonctionnalités entre les plans, voir [Comparaison des plans Office 365 pour les entreprises](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Nouveautés d'Office 365 - Protection avancée contre les menaces

Pour plus d’informations sur les nouvelles fonctionnalités dans DAV, voir [nouvelles fonctionnalités de DAV](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp).
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Configuration requise pour Office 365 - Protection avancée contre les menaces

Le service peut être utilisé avec n'importe quel agent de transfert de messagerie SMTP, tel que Microsoft Exchange Server 2013. Pour plus d'informations sur les systèmes d'exploitation, les navigateurs web et les langues pris en charge par ce service, voir les sections « Navigateurs pris en charge » et « Langues prises en charge dans EOP » de l'article [Centre d'administration Exchange dans Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilité des fonctionnalités pour les différents plans Protection avancée contre les menaces

Chaque fonctionnalité est indiquée ci-dessous. La mention « Exchange Online » fait généralement référence à la famille de services Office 365 Entreprise.
  
|**Fonctionnalité**|**Service Protection avancée contre les menaces autonome**|**Exchange Online Protection**|
|:-----|:-----|:-----|
|Liens fiables  <br/> |Oui  <br/> |Non  <br/> |
|Pièces jointes fiables  <br/> |Oui  <br/> |Non  <br/> |
|Veille contre l'usurpation d'identité  <br/> |Oui  <br/> |Non  <br/> |
|Quarantaine  <br/> |Oui  <br/> |Oui  <br/> |
|Fonctionnalités anti-hameçonnage avancées  <br/> |Oui  <br/> |Non  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a>Fonctionnalités de Protection avancée contre les menaces

### <a name="safe-links"></a>Liens fiables

La fonctionnalité Liens fiables du service Protection avancée contre les menaces protège de façon proactive les utilisateurs contre les liens hypertexte malveillants contenus dans un message. La protection est activée à chaque fois qu’ils cliquent sur le lien ; les liens malveillants sont bloqués dynamiquement tandis que les liens fiables peuvent être ouverts.
  
### <a name="safe-attachments"></a>Pièces jointes fiables

La fonctionnalité de pièces jointes fiables offre une protection contre les programmes malveillants et les virus inconnus, ainsi que contre la vulnérabilité jour zéro afin de protéger votre système de messagerie. L'ensemble des messages et pièces jointes qui ne comportent pas de signature connue de virus/programme malveillant sont acheminés vers un environnement spécial dans lequel le service Protection avancée contre les menaces utilise diverses techniques d'analyse et de Machine Learning pour détecter des intentions malveillantes. Si aucune activité suspecte n'est détectée, le message est libéré et remis à la boîte aux lettres. 
  
### <a name="spoof-intelligence"></a>Veille contre l'usurpation d'identité

Aide à la décision usurpation d’identité détecte lorsqu’un expéditeur apparaît pour envoyer des messages au nom d’un ou plusieurs comptes d’utilisateurs dans l’un des domaines de votre organisation. Elle vous permet de passer en revue tous les expéditeurs sont l’usurpation de votre domaine et puis cliquez sur Autoriser l’expéditeur continuer ou bloquer l’expéditeur. Aide à la décision usurpation d’identité n’est disponible dans la sécurité &amp; centre de conformité dans la page Paramètres de blocage du courrier indésirable.
  
### <a name="quarantine"></a>Quarantaine

Les messages détectés par le service Office 365 comme étant du courrier indésirable, du courrier en nombre ou des messages de hameçonnage, ceux contenant des logiciels malveillants ou encore ceux qui répondent aux critères d’une règle de flux de messagerie peuvent être envoyés en quarantaine. Par défaut, Office 365 envoie les messages de hameçonnage et les messages contenant des programmes malveillants directement en quarantaine. Les utilisateurs autorisés peuvent afficher, supprimer ou gérer les e-mails envoyés en quarantaine.
  
### <a name="advanced-anti-phishing-capabilities"></a>Fonctionnalités anti-hameçonnage avancées

Cette fonctionnalité utilise des modèles d'apprentissage automatique pour détecter les messages de hameçonnage. 
  
