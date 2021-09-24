---
title: Description du service d’archivage Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Lisez cet article pour en savoir plus sur Microsoft Exchange Online’archivage.
ms.openlocfilehash: 5030c265b309641a0d69e79c1aa8942c45360550
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670690"
---
# <a name="exchange-online-archiving-service-description"></a>Description du service d’archivage Exchange Online

Microsoft Exchange Online L’archivage est une solution d’archivage Microsoft 365 de niveau entreprise basée sur le cloud pour les organisations qui ont déployé Microsoft Exchange Server 2019, Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 et ultérieures) ou souscrire à certains plans Exchange Online ou Microsoft365. L'Archivage Exchange Online aide ces organisations à faire face à leurs défis de découverte électronique, de réglementation, de conformité et d'archivage tout en simplifiant l'infrastructure sur site et en réduisant ainsi les coûts et la charge que représente l'informatique.
  
En tant que service en ligne Microsoft, l'archivage Exchange Online est conçu pour aider à répondre aux besoins grandissants de sécurité, de fiabilité et de productivité des utilisateurs. Pour plus d’informations sur Microsoft 365, y compris les fonctionnalités communes à tous les services en ligne Microsoft, voir Microsoft 365 et Office 365 description du [service de plateforme.](../office-365-platform-service-description/office-365-platform-service-description.md)
  
Pour acheter Archivage Exchange Online, voir [Archivage Exchange Online pour le serveur.](https://products.office.com/exchange/microsoft-exchange-online-archiving-email)
  
## <a name="available-plans"></a>Plans disponibles

Pour obtenir des informations détaillées sur les abonnements qui permettent aux utilisateurs d’Archivage Exchange Online, consultez le tableau de comparaison complet [des abonnements.](https://go.microsoft.com/fwlink/?linkid=2139145)
  
> [!TIP]
> Vous pouvez exporter, enregistrer et imprimer des pages dans les descriptions de service. Découvrez comment exporter [les résultats de recherche de contenu.](/office365/securitycompliance/export-search-results) 
  
## <a name="exchange-online-archiving-plans"></a>Plans d’archivage Exchange Online

L'Archivage Exchange Online est disponible dans les plans suivants.<br><br>
  
| Planification | Description |
|:-----|:-----|
|**Archivage Exchange Online pour Exchange Server** <br/> |Archive en nuage pour les utilisateurs ayant des boîtes aux lettres principales dans Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 ou Exchange 2010 (SP2 ou ultérieur). <br/> Si vous souhaitez ajouter une archive basée sur le cloud à une boîte aux lettres principale située sur un serveur Exchange local, vous devez configurer un déploiement hybride. Pour plus d’informations sur les déploiements hybrides, [voir Exchange Server déploiements hybrides.](/exchange/exchange-hybrid) <br/> |
|**Archivage Exchange Online pour Exchange Server (via Enterprise CAL Suite).** <br/> |Archive en nuage pour les utilisateurs ayant des boîtes aux lettres principales dans Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 ou Exchange 2010 (SP2 ou ultérieur). Pour plus d’informations, [voir Licences d’accès au client et Licences de gestion.](https://www.microsoft.com/licensing/product-licensing/client-access-license) <br/> |
|**Archivage Exchange Online pour Exchange Online** <br/> | Archive en nuage et archive sur place en tant que module de prise en compte pour les plans<sup>suivants 1,2,3</sup>:<br/> Exchange Online (plan 1) <br/> Exchange Online Kiosk <br/> Microsoft 365 Business Basic <br/> Microsoft 365 Business Standard <br/> Microsoft 365 Business Premium <br/> Office 365 E1 <br/> Office 365 A1 <br/> Office 365 G1 <br/> Office 365 F3 <br/> Microsoft 365 F3<br/> <b>Remarque :</b> Les plans suivants incluent déjà l’archivage et ne nécessitent pas Archivage Exchange Online en tant qu’modules suivants :<br/>Office 365 A3 <br/> Office 365 A5 <br/> Office 365 E3 <br/> Office 365 E5 <br/> Exchange Online (plan 2) <br/>Microsoft 365 E3 <br/> Microsoft 365 E5 <br/> Microsoft 365 Conformité F5 <br/> Pour plus d’informations sur les fonctionnalités d’archivage Exchange Online boîtes aux lettres, voir fonctionnalités d’archivage dans [Archivage Exchange Online](./archive-features.md).|

<sup>1</sup> Le déploiement hybride n'est pas requis pour les organisations en nuage uniquement sans boîte aux lettres située sur un serveur Exchange local. Toutefois, s'il existe des boîtes aux lettres locales, le déploiement hybride est requis.
<br/>
<sup>2</sup> Exchange Online Plan 1, Office 365 E1/A1/G1 et Microsoft 365 Business Basic/Standard/Premium ont une limite de taille pour la boîte aux lettres et l’archive. Pour plus d’informations, voir [Limites d’Exchange Online](../exchange-online-service-description/exchange-online-limits.md). L'Archivage Exchange Online pour le module complémentaire Exchange Online ajoute une archive informatique illimitée et une [Conservation inaltérable et conservation pour litige](compliance-and-security-features.md#in-place-hold-and-litigation-hold).
<br/>
<sup>3 Inclut</sup> les plans Cloud de la communauté du secteur public, Cloud de la communauté du secteur public-High et DoD pour le gouvernement des États-Unis.

Vous recherchez des informations sur tous Microsoft 365 plans ? Microsoft 365 est disponible dans différents plans pour répondre au mieux aux besoins de votre organisation. Pour plus d’informations sur les différents plans, notamment sur les options de plan autonome et sur le passage d’un plan à un autre, voir Office 365 [options de plan.](../office-365-platform-service-description/office-365-plan-options.md)
  
## <a name="requirements"></a>Configuration requise

Pour utiliser Archivage Exchange Online pour Exchange Server, les boîtes aux lettres utilisateur doivent résider sur Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 ou Exchange Server 2010 (SP2) ou ultérieure).
  
### <a name="federated-identity-and-single-sign-on"></a>Identité fédérée et authentification unique

Les administrateurs peuvent utiliser une approche d’authentification unique pour l’authentification avec Active Directory local. Pour ce faire, les administrateurs peuvent configurer les services AD FS (Active Directory Federation Services) locaux (un service Microsoft Windows Server 2008) pour se fédérer avec le &reg; Microsoft Federation Gateway. Une fois les services de fédération Active Directory configurés, tous les utilisateurs dont les identités sont basées sur le domaine fédéré peuvent utiliser leur logo d’entreprise existant pour s’authentifier automatiquement Office 365.
  
### <a name="user-subscriptions"></a>Abonnements utilisateur

Chaque utilisateur qui accède au service d'Archivage Exchange Online doit posséder un abonnement d'Archivage Exchange Online. Chaque abonnement d'archivage de courrier électronique peut être utilisé uniquement pour le stockage des données de messagerie d'un utilisateur.
  
## <a name="unlimited-archive-storage-quota"></a>Quota de stockage d’archive illimité

 La fonctionnalité d'archivage illimité (appelée *archivage à extension automatique*) fournit un espace de stockage supplémentaire dans les boîtes aux lettres d'archivage. Au départ, chaque abonné à l’archivage Exchange Online reçoit 100 Go de stockage dans la boîte aux lettres d’archivage. Lorsque l’archivage à extension automatique est allumé, un espace de stockage supplémentaire est automatiquement ajouté lorsque la capacité de stockage de 100 Go est atteinte. Dans Exchange déploiements hybrides, l’archivage à extension automatique est uniquement pris en charge pour les boîtes aux lettres d’archivage informatiques lorsque la boîte aux lettres de l’utilisateur local réside sur Exchange Server 2019, Exchange Server 2016 ou Exchange Server 2013 (SP1 ou version ultérieure). Pour plus d’informations, voir [Vue d’ensemble d’un archivage illimité](/office365/securitycompliance/unlimited-archiving).
  
> [!IMPORTANT]
> Les administrateurs ne peuvent pas ajuster le quota de stockage.<br/>
> L’archivage à extension automatique n’est pas pris en charge pour les boîtes aux lettres résidant Exchange Server 2010.
  
> [!IMPORTANT]
> L’archivage à extension automatique est uniquement pris en charge pour les boîtes aux lettres utilisées pour des utilisateurs individuels ou des boîtes aux lettres partagées avec un taux de croissance qui ne dépasse pas 1 Go *&nbsp; par jour.* L'utilisation de la fonction de journalisation, des règles de transport ou des règles de transfert automatique pour copier des messages dans Archivage Exchange Online à des fins d'archivage n'est pas autorisée. La boîte aux lettres d'archivage d'un utilisateur est destinée uniquement à cet utilisateur. Microsoft se réserve le droit de refuser l’archivage illimité dans les cas où la boîte aux lettres d’archivage d’un utilisateur sert à stocker les données d’archivage d’autres utilisateurs ou dans d’autres cas d’utilisation inappropriée.
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Disponibilité des fonctionnalités pour les différents plans d’archivage Exchange Online

| Fonctionnalité | Archivage Exchange Online pour Exchange Server<sup>1</sup> | Archivage Exchange Online pour Exchange Online<sup>2</sup> |
|:-----|:-----|:-----|
|**[Fonctionnalités d’archivage dans Archivage Exchange Online](archive-features.md)** <br/> |||
|Boîte aux lettres d'archivage  <br/> |Oui  <br/> |Oui  <br/> |
|Déplacer des messages à l’aide de la stratégie d’archivage  <br/> |Oui  <br/> |Oui  <br/> |
|Importer des données dans l'archive  <br/> |Oui  <br/> |Oui  <br/> |
|Récupération d'éléments supprimés  <br/> |Oui  <br/> |Oui  <br/> |
|Récupération de boîtes aux lettres supprimées  <br/> |Oui  <br/> |Oui  <br/> |
|Sauvegarde de boîtes aux lettres  <br/> |Oui  <br/> |Oui  <br/> |
|**[Fonctionnalités client dans Archivage Exchange Online](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |Oui  <br/> |Oui  <br/> |
|Outlook sur le web  <br/> |Oui  <br/> |Oui  <br/> |
|**[Fonctionnalités de conformité et de sécurité dans Archivage Exchange Online](compliance-and-security-features.md)** <br/> |||
|Stratégies de rétention  <br/> |Oui  <br/> |Oui  <br/> |
|Conservation inaltérable et conservation pour litige<sup>6</sup> <br/> |Oui  <br/> |Oui  <br/> |
|Découverte électronique locale  <br/> |Oui  <br/> |Oui  <br/> |
|Chiffrement entre serveurs sur site et archivage Exchange Online  <br/> |Oui  <br/> |Oui  <br/> |
|Chiffrement entre clients et archivage Exchange Online  <br/> |Oui  <br/> |Oui  <br/> |
|Chiffrement : S/MIME et PGP  <br/> |Oui  <br/> |Oui  <br/> |
|IRM avec Azure Information Protection  <br/> |Non  <br/> |Non<sup>4</sup> <br/> |
|IRM via Windows Server AD RMS  <br/> |Oui<sup>5</sup> <br/> |Oui<sup>5</sup> <br/> |
|Audit  <br/> |Oui  <br/> |Oui  <br/> |
   

<sup>1</sup> Les boîtes aux lettres utilisateur doivent résider sur Exchange 2010 SP2 ou version ultérieure.
<br/>
<sup>2</sup> Une archive In-Place ne peut être utilisée que pour archiver le courrier électronique d’un utilisateur ou d’une entité unique pour lequel une licence a été appliquée. L'utilisation de la fonctionnalité d'archivage local pour stocker les messages de plusieurs utilisateurs ou entités est interdite. Par exemple, les administrateurs informatiques ne peuvent pas créer des boîtes aux lettres partagées et permettre aux utilisateurs de copier (via le champ Cc ou Cci, ou une règle de transport) une boîte aux lettres de ce type dans le but explicite de procéder à un archivage. <br/> 
<sup>3</sup> Pour obtenir la liste des versions de Microsoft Outlook pris en charge, voir [fonctionnalités](client-features.md)client dans Archivage Exchange Online . <br/>
<sup>4</sup> Azure Information Protection n’est pas inclus, mais peut être acheté en tant que module complémentaire distinct et activera les fonctionnalités de gestion des droits de l’information (IRM) prise en charge. Certaines fonctionnalités Azure Information Protection nécessitent un abonnement à Applications Microsoft 365 pour les grandes entreprises, qui n’est pas inclus dans Microsoft 365 Business Basic, Microsoft 365 Business Standard, Office 365 Entreprise E1, Office 365 Éducation ou Office 365 Entreprise F3. <br/>
<sup>5</sup> Windows Server AD RMS est un serveur local qui doit être acheté et géré séparément afin d'activer les fonctionnalités IRM prises en charge. <br/>
<sup>6</sup> Lorsque vous placez une boîte aux lettres en conservation inaltérable ou en conservation pour litige, la conservation porte à la fois sur la boîte aux lettres d'archivage et la boîte aux lettres principale.