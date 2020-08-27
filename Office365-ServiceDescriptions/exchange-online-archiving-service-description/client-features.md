---
title: Fonctionnalités client dans l’archivage Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online Archiving permet aux utilisateurs de se connecter à leurs boîtes aux lettres d’archivage à partir de plusieurs appareils et plateformes. Toute la connectivité réseau à l’archive de l’utilisateur se produit sur Internet, et les connexions de réseau privé virtuel (VPN) ne sont pas requises. Les organisations peuvent publier un serveur d'accès au client local pour permettre aux utilisateurs d'accéder à leur boîte aux lettres principale à l'aide d'Outlook Anywhere, sans nécessiter de connexion VPN. Si un accès VPN est requis pour accéder à la boîte aux lettres principale de l'utilisateur située sur un serveur local, cette exigence ne change pas.
ms.openlocfilehash: 6f29f434f5b6515460ee526450fba4a50bb6c191
ms.sourcegitcommit: e2ebd2f3e4b6e2ec76a29498dc276fa0f05f18a3
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/26/2020
ms.locfileid: "47255901"
---
# <a name="client-features-in-exchange-online-archiving"></a>Fonctionnalités client dans l’archivage Exchange Online

Microsoft Exchange Online Archiving permet aux utilisateurs de se connecter à leurs boîtes aux lettres d’archivage à partir de plusieurs appareils et plateformes. Toute la connectivité réseau à l’archive de l’utilisateur se produit sur Internet, et les connexions de réseau privé virtuel (VPN) ne sont pas requises. Les organisations peuvent publier un serveur d'accès au client local pour permettre aux utilisateurs d'accéder à leur boîte aux lettres principale à l'aide d'Outlook Anywhere, sans nécessiter de connexion VPN. Si un accès VPN est requis pour accéder à la boîte aux lettres principale de l'utilisateur située sur un serveur local, cette exigence ne change pas.
  
> [!IMPORTANT]
> Microsoft se réserve le droit de bloquer ou de limiter les connexions de tout logiciel client qui a une incidence négative sur l'état du service Archivage Exchange Online.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook est un programme riche de messagerie électronique qui inclut la prise en charge du calendrier, des contacts et de tâches. Archivage Exchange Online prend en charge Outlook 2013, Outlook 2010 et Outlook 2007. Les fonctionnalités clés incluent :
  
- **Outlook Anywhere** Outlook Anywhere permet aux utilisateurs d’Outlook de se connecter à Exchange Server et à l’archivage Exchange Online sur Internet sans avoir besoin d’une connexion VPN. La communication entre Outlook et Archivage Exchange Online se fait via un tunnel SSL sécurisé, à l'aide du composant réseau Windows RPC sur HTTP.    
- **Découverte automatique** Le service de découverte automatique Exchange configure automatiquement Outlook pour qu'il fonctionne avec Archivage Exchange Online. La découverte automatique permet aux utilisateurs d’Outlook de recevoir les paramètres de profil requis directement à partir d’Exchange la première fois (et à intervalles réguliers par la suite) qu’ils se connectent avec leur adresse de messagerie et leur mot de passe. 

Outlook 2010 et versions ultérieures et Outlook sur le Web fournissent aux utilisateurs les fonctionnalités complètes de l’archive, ainsi que des fonctionnalités associées telles que les stratégies de rétention et d’archivage.
  
Outlook 2007 propose une prise en charge simple de l'archive, mais toutes les fonctions de conformité et d'archivage ne sont pas disponibles dans Outlook 2007. Par exemple, avec Outlook 2007, les utilisateurs ne peuvent pas appliquer de stratégies d'archivage ou de rétention aux éléments de leurs boîtes aux lettres. Ils doivent plutôt utiliser des stratégies fournies par un administrateur. Les utilisateurs d'Outlook 2007 doivent disposer de la mise à jour cumulative Office 2007 de février 2011 pour pouvoir accéder à leur archive.
  
> [!NOTE]
> Outlook n'est pas fourni avec Archivage Exchange Online. Microsoft 365 apps pour entreprises (qui inclut Microsoft Outlook) est inclus dans certains plans et peut être acheté séparément en tant qu’abonnement séparé. Pour plus d’informations, consultez la rubrique [options de plan Microsoft 365](../office-365-platform-service-description/office-365-plan-options.md). Pour plus d’informations sur les applications Microsoft 365 pour Enterprise, voir la [Description du service d’applications Office](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clients pris en charge par l’archivage Exchange Online

Le tableau ci-dessous répertorie les clients pris en charge par Archivage Exchange Online:
  
|**Client**|**Prise en charge de l'archivage Exchange Online**|
|:-----|:-----|
|Outlook 2013 et versions ultérieures  <br/> |Prend en charge les dernières fonctionnalités dans Archivage Exchange Online.<sup>1</sup> <br/> |
|Outlook 2010  <br/> |Prend en charge les dernières fonctionnalités dans l’archivage Exchange Online uniquement jusqu’à octobre 13, 2020|
|Outlook 2007  <br/> |Non pris en charge |
|Outlook 2003  <br/> |Non pris en charge  <br/> |
|Outlook pour Mac 2011  <br/> |Non pris en charge  <br/> |
|Outlook pour Mac  <br/> |Pris en charge pour une utilisation avec l’archivage Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Édition Services Web  <br/> |Non pris en charge  <br/> |
|IMAP et POP  <br/> |Non pris en charge  <br/> |
|Exchange ActiveSync (appareils mobiles)  <br/> |Non pris en charge  <br/> |
   
> [!NOTE]
> <sup>1</sup> Outlook inclus avec Microsoft Office standard n’est pas pris en charge. Pour plus d’informations, consultez la rubrique [License Requirements for Personal Archive and Retention Policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> nécessite une mise à jour pour permettre la prise en charge de l’archivage. Les utilisateurs d’Outlook 2007 ne peuvent pas afficher ou appliquer des stratégies de rétention ou d’archivage aux éléments de leurs boîtes aux lettres d’archivage ; elles doivent reposer sur des stratégies configurées par l’administrateur. En outre, les utilisateurs d’Outlook 2007 ne peuvent pas effectuer des recherches dans la boîte aux lettres locale et dans l’archive en même temps. <br/> 
<sup>3</sup> vous ne pouvez pas utiliser Outlook 2016 pour Mac ou Outlook pour Mac pour déplacer ou copier des dossiers, des éléments de calendrier, des contacts, des tâches ou des notes vers votre archive, ou les afficher dans la boîte aux lettres d’archivage, si les éléments y ont été précédemment déplacés à l’aide d’une autre version d’Outlook (par exemple, Outlook 2016 pour Windows). Pour plus d’informations, consultez [la rubrique utiliser votre archive en ligne avec Outlook 2016 pour Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-on-the-web"></a>Outlook sur le web

Outlook sur le web est une version du programme de messagerie électronique Outlook basée sur le web, utilisée avec Exchange Online. Lorsque les utilisateurs sont connectés à Internet &mdash; depuis leur domicile, au bureau ou sur la route, &mdash; ils peuvent accéder à leur messagerie via Outlook sur le Web.
  
Les utilisateurs peuvent accéder à leur archive en se connectant à Outlook sur le Web local (à l’aide de la même URL). L’archive apparaît avec sa boîte aux lettres principale dans Outlook sur le Web. Il n’existe pas de moyen explicite d’accéder à l’archive directement à partir d’Outlook sur le Web.
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, voir [Description du service d’archivage Exchange Online](exchange-online-archiving-service-description.md).