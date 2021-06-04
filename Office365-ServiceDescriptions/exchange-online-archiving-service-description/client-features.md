---
title: Fonctionnalités client dans Archivage Exchange Online
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
description: Lisez cet article pour en savoir plus sur les fonctionnalités client disponibles dans Microsoft Exchange Online’archivage.
ms.openlocfilehash: 54f066562b08eeeed90b8c9b465c4740bcc3f0df
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293636"
---
# <a name="client-features-in-exchange-online-archiving"></a>Fonctionnalités client dans Archivage Exchange Online

Microsoft Exchange Online L’archivage permet aux utilisateurs de se connecter à leurs boîtes aux lettres d’archivage à partir de divers appareils et plateformes. Toute la connectivité réseau à l’archive de l’utilisateur se produit sur Internet, et les connexions de réseau privé virtuel (VPN) ne sont pas requises. Les organisations peuvent publier un serveur d'accès au client local pour permettre aux utilisateurs d'accéder à leur boîte aux lettres principale à l'aide d'Outlook Anywhere, sans nécessiter de connexion VPN. Si un accès VPN est requis pour accéder à la boîte aux lettres principale de l'utilisateur située sur un serveur local, cette exigence ne change pas.
  
> [!IMPORTANT]
> Microsoft se réserve le droit de bloquer ou de limiter les connexions de tout logiciel client qui a une incidence négative sur l'état du service Archivage Exchange Online.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook est un programme riche de messagerie électronique qui inclut la prise en charge du calendrier, des contacts et de tâches. Archivage Exchange Online prend en charge Outlook 2013, Outlook 2010 et Outlook 2007. Les fonctionnalités clés incluent :
  
- **Outlook Anywhere** - Outlook Anywhere permet aux utilisateurs Outlook de se connecter à Exchange Server et Archivage Exchange Online via Internet sans avoir besoin d’une connexion VPN. La communication entre Outlook et Archivage Exchange Online se fait via un tunnel SSL sécurisé, à l'aide du composant réseau Windows RPC sur HTTP.    
- **Découverte automatique** : le service Exchange de découverte automatique configure automatiquement Outlook pour fonctionner avec Archivage Exchange Online. La découverte automatique permet aux utilisateurs Outlook de recevoir leurs paramètres de profil requis directement à partir de Exchange la première fois (et à intervalles fixes par la suite) qu’ils se connectent avec leur adresse e-mail et leur mot de passe. 

Outlook 2010 et les ultérieures et Outlook sur le web fournissent aux utilisateurs les fonctionnalités complètes de l’archive, ainsi que les fonctionnalités associées telles que les stratégies de rétention et d’archivage.
  
Outlook 2007 propose une prise en charge simple de l'archive, mais toutes les fonctions de conformité et d'archivage ne sont pas disponibles dans Outlook 2007. Par exemple, avec Outlook 2007, les utilisateurs ne peuvent pas appliquer de stratégies d'archivage ou de rétention aux éléments de leurs boîtes aux lettres. Ils doivent plutôt utiliser des stratégies fournies par un administrateur. Les utilisateurs d'Outlook 2007 doivent disposer de la mise à jour cumulative Office 2007 de février 2011 pour pouvoir accéder à leur archive.
  
> [!NOTE]
> Outlook n'est pas fourni avec Archivage Exchange Online. Applications Microsoft 365 pour les grandes entreprises (qui inclut Microsoft Outlook) est inclus dans certains plans et peut être acheté séparément. Pour plus d’informations, [voir Microsoft 365 options de plan.](../office-365-platform-service-description/office-365-plan-options.md) Pour plus d’informations sur Applications Microsoft 365 pour les grandes entreprises, voir la [description du service Office applications.](../office-applications-service-description/office-applications-service-description.md) 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clients pris en charge par l’archivage Exchange Online

Le tableau ci-dessous répertorie les clients pris en charge par Archivage Exchange Online:<br><br>
  
| Client | Prise en charge EOA |
|:-----|:-----|
|Outlook 2013 et ultérieures  <br/> |Prend en charge les dernières fonctionnalités dans Archivage Exchange Online.<sup>1</sup> <br/> |
|Outlook 2010  <br/> |Prend en charge les dernières fonctionnalités Archivage Exchange Online jusqu’au 13 octobre 2020|
|Outlook 2007  <br/> |Non pris en charge |
|Outlook 2003  <br/> |Non pris en charge  <br/> |
|Outlook pour Mac 2011  <br/> |Non pris en charge  <br/> |
|Outlook pour Mac  <br/> |Pris en charge pour une utilisation avec Archivage Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Édition Services Web  <br/> |Non pris en charge  <br/> |
|IMAP et POP  <br/> |Non pris en charge  <br/> |
|Exchange ActiveSync (appareils mobiles)  <br/> |Non pris en charge  <br/> |
   
> [!NOTE]
> <sup>1 Outlook</sup> inclus dans Microsoft Office Standard n’est pas pris en charge. Pour en savoir plus, consultez [La licence requise pour les stratégies d’archivage personnel et de rétention.](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99) <br/> 
<sup>2 Nécessite</sup> une mise à jour pour activer la prise en charge de l’archivage. Outlook utilisateurs 2007 ne peuvent pas afficher ou appliquer des stratégies de rétention ou d’archivage à des éléments dans leurs boîtes aux lettres d’archivage ; ils doivent s’appuyer sur des stratégies provisionnées par l’administrateur. En outre, Outlook 2007 utilisateurs ne peuvent pas rechercher la boîte aux lettres et l’archive en même temps dans la boîte aux lettres sur site. <br/> 
<sup>3</sup> Vous ne pouvez pas utiliser Outlook 2016 pour Mac ou Outlook pour Mac pour déplacer ou copier des dossiers, des éléments de calendrier, des contacts, des tâches ou des notes dans votre archive, ni les afficher dans la boîte aux lettres d’archivage, si les éléments y ont été précédemment déplacés à l’aide d’une autre version de Outlook (par exemple, Outlook 2016 pour Windows). Pour plus d’informations, [voir Utiliser votre archive en ligne avec Outlook 2016 pour Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-on-the-web"></a>Outlook sur le web

Outlook sur le web est une version du programme de messagerie électronique Outlook basée sur le web, utilisée avec Exchange Online. Quel que soit l’endroit où les utilisateurs sont connectés à Internet à la maison, au bureau ou sur la route, ils peuvent accéder à leur courrier électronique par le biais Outlook &mdash; &mdash; sur le web.
  
Les utilisateurs peuvent accéder à leur archive en se Outlook sur le web local (à l’aide de la même URL). L’archive apparaît en même temps que leur boîte aux lettres principale Outlook sur le web. Il n’existe aucun moyen explicite d’accéder à l’archive directement Outlook sur le web.
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir [Archivage Exchange Online description du service.](exchange-online-archiving-service-description.md)