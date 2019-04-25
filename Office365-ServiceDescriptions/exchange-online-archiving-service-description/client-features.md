---
title: Fonctionnalités client dans l'archivage Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online Archiving permet aux utilisateurs de se connecter à leurs boîtes aux lettres d'archivage à partir de plusieurs appareils et plateformes. Toute connectivité réseau à l'archive de l'utilisateur se fait par Internet, et des connexions de réseau privé virtuel (VPN) ne sont pas nécessaires. Les organisations peuvent publier un serveur d'accès au client local pour permettre aux utilisateurs d'accéder à leur boîte aux lettres principale à l'aide d'Outlook Anywhere, sans nécessiter de connexion VPN. Si un accès VPN est requis pour accéder à la boîte aux lettres principale de l'utilisateur située sur un serveur local, cette exigence ne change pas.
ms.openlocfilehash: d1f304936d184dc30826d6e60552d4e186bb2a41
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/25/2019
ms.locfileid: "33245060"
---
# <a name="client-features-in-exchange-online-archiving"></a>Fonctionnalités client dans l'archivage Exchange Online

Microsoft Exchange Online Archiving permet aux utilisateurs de se connecter à leurs boîtes aux lettres d'archivage à partir de plusieurs appareils et plateformes. Toute connectivité réseau à l'archive de l'utilisateur se fait par Internet, et des connexions de réseau privé virtuel (VPN) ne sont pas nécessaires. Les organisations peuvent publier un serveur d'accès au client local pour permettre aux utilisateurs d'accéder à leur boîte aux lettres principale à l'aide d'Outlook Anywhere, sans nécessiter de connexion VPN. Si un accès VPN est requis pour accéder à la boîte aux lettres principale de l'utilisateur située sur un serveur local, cette exigence ne change pas.
  
> [!IMPORTANT]
> Microsoft se réserve le droit de bloquer ou de limiter les connexions de tout logiciel client qui a une incidence négative sur l'état du service Archivage Exchange Online. 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook est un programme riche de messagerie électronique qui inclut la prise en charge du calendrier, des contacts et de tâches. Archivage Exchange Online prend en charge Outlook 2013, Outlook 2010 et Outlook 2007. Les fonctionnalités clés incluent :
  
- **Outlook Anywhere** Outlook Anywhere permet aux utilisateurs d'Outlook de se connecter à Exchange Server et Archivage Exchange Online sur Internet sans avoir besoin d'une connexion VPN. La communication entre Outlook et Archivage Exchange Online se fait via un tunnel SSL sécurisé, à l'aide du composant réseau Windows RPC sur HTTP. 
    
- **Découverte automatique** Le service de découverte automatique Exchange configure automatiquement Outlook pour qu'il fonctionne avec Archivage Exchange Online. La découverte automatique permet aux utilisateurs d'Outlook de recevoir leurs paramètres de profil requis directement à partir d'Exchange la première fois (et à intervalles fixes par la suite) auquel ils se connectent avec leur mot de passe et leur adresse de messagerie. 
    
Outlook 2010 et versions ultérieures et Outlook Web App fournissent aux utilisateurs les fonctionnalités complètes de l'archive, ainsi que des fonctionnalités associées telles que des stratégies de rétention et d'archivage.
  
Outlook 2007 propose une prise en charge simple de l'archive, mais toutes les fonctions de conformité et d'archivage ne sont pas disponibles dans Outlook 2007. Par exemple, avec Outlook 2007, les utilisateurs ne peuvent pas appliquer de stratégies d'archivage ou de rétention aux éléments de leurs boîtes aux lettres. Ils doivent plutôt utiliser des stratégies fournies par un administrateur. Les utilisateurs d'Outlook 2007 doivent disposer de la mise à jour cumulative Office 2007 de février 2011 pour pouvoir accéder à leur archive.
  
> [!NOTE]
> Outlook n'est pas fourni avec Archivage Exchange Online. Microsoft Office 365 ProPlus (qui inclut Microsoft Outlook) est inclus dans certains plans Office 365 et est disponible dans le cadre d'un abonnement à part. Pour plus d'informations, voir [Options de plan Office 365](../office-365-platform-service-description/office-365-plan-options.md). Pour plus d'informations sur Office 365 ProPlus, voir [Description de service des applications Office](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clients pris en charge par l’archivage Exchange Online

Le tableau ci-dessous répertorie les clients pris en charge par Archivage Exchange Online:
  
|**Client**|**Prise en charge de l'archivage Exchange Online**|
|:-----|:-----|
|Outlook 2010 et versions ultérieures  <br/> |Prend en charge les dernières fonctionnalités dans Archivage Exchange Online.<sup>1</sup> <br/> |
|Outlook 2007  <br/> |Pris en charge en vue d'une utilisation avec Archivage Exchange Online.<sup>1,2</sup> <br/> |
|Outlook 2003  <br/> |Non pris en charge  <br/> |
|Outlook pour Mac 2011  <br/> |Non pris en charge  <br/> |
|Outlook pour Mac  <br/> |Pris en charge pour une utilisation avec l'archivage Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Édition Services Web  <br/> |Non pris en charge  <br/> |
|IMAP et POP  <br/> |Non pris en charge  <br/> |
|Exchange ActiveSync (périphériques mobiles)  <br/> |Non pris en charge  <br/> |
   
> [!NOTE]
> <sup>1</sup> Outlook inclus avec Microsoft Office standard n'est pas pris en charge. Pour plus d'informations, consultez la rubrique [License Requirements for Personal Archive and](https://go.microsoft.com/fwlink/?LinkId=389396)Retention Policies. > <sup>2</sup> nécessite une mise à jour pour permettre la prise en charge de l'archivage. Les utilisateurs d'Outlook 2007 ne peuvent pas afficher ou appliquer des stratégies de rétention ou d'archivage aux éléments de leurs boîtes aux lettres d'archivage; elles doivent reposer sur des stratégies configurées par l'administrateur. En outre, les utilisateurs d'Outlook 2007 ne peuvent pas effectuer des recherches dans la boîte aux lettres locale et dans l'archive en même temps. > <sup>3</sup> vous ne pouvez pas utiliser Outlook 2016 pour Mac ou Outlook pour Mac pour déplacer ou copier des dossiers, des éléments de calendrier, des contacts, des tâches ou des notes vers votre archive, ou les afficher dans la boîte aux lettres d'archivage, si les éléments qui y étaient précédemment ont été déplacés à l'aide d'une autre version d'Outlook (par exemple, Outlook 2016 pour Windows). Pour plus d'informations, consultez [la rubrique utiliser votre archive en ligne avec Outlook 2016 pour Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 
  
## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App est une version web du programme de messagerie électronique Outlook utilisé avec Exchange Online. Quel que soit l’endroit où les utilisateurs sont connectés à Internet (à la maison, au bureau ou sur la route), ils peuvent accéder à leurs courriers électroniques via Outlook Web App.
  
Les utilisateurs peuvent accéder à leur archive en se connectant à Outlook Web App en local (à l’aide de la même URL). L’archive apparaît à côté de leur boîte aux lettres principale dans Outlook Web App. Il n’existe pas de manière explicite d’accéder à l’archive directement à partir d’Outlook Web App.
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service d'archivage Exchange Online](exchange-online-archiving-service-description.md).
  

