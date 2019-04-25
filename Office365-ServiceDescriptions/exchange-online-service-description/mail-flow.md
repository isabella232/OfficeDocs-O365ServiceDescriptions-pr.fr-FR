---
title: Flux de messagerie
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: Pour la plupart des organisations utilisant Office 365, nous hébergeons vos boîtes aux lettres et vous vous occupez du flux de messagerie. Il s'agit de la configuration la plus simple et signifie qu'Office 365 gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de configurations de flux de messagerie plus complexes pour s'assurer qu'elles sont conformes aux besoins spécifiques de la réglementation ou de l'entreprise. Vous pouvez en savoir plus sur ces options ici.
ms.openlocfilehash: e5b56712a3c88c91b943d681f927cea480776839
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246400"
---
# <a name="mail-flow"></a>Flux de messagerie

Pour la plupart des organisations utilisant Office 365, nous hébergeons vos boîtes aux lettres et vous vous occupez du flux de messagerie. Il s'agit de la configuration la plus simple et signifie qu'Office 365 gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de configurations de flux de messagerie plus complexes pour s'assurer qu'elles sont conformes aux besoins spécifiques de la réglementation ou de l'entreprise. Vous pouvez en savoir plus sur ces options ici. 
  
## <a name="custom-routing-of-outbound-email"></a>Routage personnalisé du courrier sortant

Microsoft Exchange Online peut acheminer le courrier sortant de votre organisation via un serveur local ou un service hébergé (parfois appelé « hébergement intelligent »). Ainsi, votre organisation peut utiliser des appliances de protection contre la perte de données, effectuer un post-traitement personnalisé du courrier sortant et remettre le courrier à des partenaires professionnels via des réseaux privés. Exchange Online prend aussi en charge la fonctionnalité de réécriture d'adresse, qui permet d'acheminer le courrier sortant via une passerelle locale qui modifie les adresses. Cette fonctionnalité vous permet de masquer les sous-domaines, de faire apparaître le courrier provenant d'une organisation à plusieurs domaines comme un courrier associé à un domaine unique, ou de faire apparaître le courrier relayé par des partenaires comme étant un courrier envoyé de l'intérieur de l'organisation. Les administrateurs configurent le routage personnalisé du courrier dans le Centre d'administration Exchange (CAE).
  
Pour plus d'informations, consultez la rubrique [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
> [!IMPORTANT]
> Exchange Online transfère le flux de messagerie vers et depuis votre organisation. 
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

En tant que client Exchange Online, vous pouvez établir un flux de messagerie sécurisé avec un partenaire de confiance en utilisant les connecteurs d'Office 365. Office 365 prend en charge la communication sécurisée par protocole TLS (Transport Layer Security). Vous pouvez créer un connecteur pour appliquer le chiffrement via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) est un protocole de chiffrement qui sécurise les communications sur Internet. Grâce aux connecteurs, vous pouvez configurer un protocole TLS entrant et sortant forcé, à l'aide de certificats validés par une autorité de certification ou auto-signés. Vous pouvez également appliquer d'autres restrictions de sécurité, par exemple en spécifiant des noms de domaine ou des plages d'adresses IP à partir desquels votre organisation partenaire envoie du courrier. 
  
Pour plus d'informations, consultez la rubrique [Set up connectors for secure mail flow with a partner organization](http://technet.microsoft.com/library/1ce4d6a4-41ba-4d1e-9ca9-e826252c1041.aspx).
  
> [!IMPORTANT]
> Il est possible qu'un certificat validé par une autorité de certification soit requis. 
  
## <a name="conditional-mail-routing"></a>Routage du courrier conditionnel

Vous pouvez acheminer le courrier vers des sites spécifiques à l'aide de connecteurs et de règles de transport. Avec un routage basé sur des critères, vous pouvez choisir un connecteur en fonction de conditions spécifiques.
  
Pour plus d'informations, consultez la rubrique [Scenario: Conditional mail routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="incoming-mail-safe-list"></a>Liste verte de courriers entrants

Vous pouvez ajouter l'adresse IP d'un partenaire de confiance à une liste verte pour être certain que les messages envoyés par le partenaire ne font pas l'objet d'un filtrage du courrier indésirable. Pour ce faire, vous pouvez utiliser la liste d'adresses IP autorisées du filtre de connexion.
  
Pour plus d'informations, consultez la rubrique [Configure the connection filter policy](http://technet.microsoft.com/library/6ae78c12-7bbe-44fa-ab13-c3768387d0e3.aspx).
  
## <a name="hybrid-email-routing"></a>Routage hybride du courrier

Un déploiement hybride offre aux entreprises la possibilité d'étendre dans le cloud l'éventail de fonctionnalités proposé et le contrôle administratif qu'elles exercent dans leur organisation Microsoft Exchange locale existante. Dans un transport hybride, les messages envoyés entre des destinataires d'une organisation sont authentifiés, chiffrés et transférés via le protocole TLS (Transport Layer Security) et apparaissent comme « internes » pour des composants Exchange, tels que les règles de transport, la journalisation et les stratégies de protection contre le courrier indésirable. Vous configurez le transport hybride à l'aide de l'Assistant Configuration hybride dans Exchange Server.
  
Pour plus d'informations sur le routage du courrier dans un déploiement hybride, consultez la rubrique [Routage de transport dans les déploiements hybrides Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
L'[Assistant de déploiement Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) fournit aussi des instructions détaillées concernant la mise en service d'un déploiement hybride et de transport hybride des messages. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Espace d'adressage partagé avec contrôle de routage local (MX pointe vers le site)

L'espace d'adressage partagé avec contrôle de routage local (MX pointe vers le site) représente un scénario de routage de courrier de déploiement hybride dans lequel vos boîtes aux lettres sont hébergées en partie dans Exchange Online et en partie sur site, et dans lequel le flux de messagerie Internet entrant et sortant est acheminé via l'organisation Exchange locale. Ce scénario est également appelé transport de messagerie centralisé. Dans ce scénario, Exchange Online est mis en service avec EOP, et le courrier Internet entrant est acheminé vers votre serveur de messagerie local avant d'être acheminé vers EOP, puis finalement vers des boîtes aux lettres hébergées dans Exchange Online. De plus, le courrier sortant de boîtes aux lettres Exchange Online est acheminé via l'organisation Exchange locale dans le cas de messages envoyés à des destinataires externes. Avec cette configuration, vous pouvez utiliser un espace de noms de domaine SMTP unique pour toutes les boîtes aux lettres, à la fois dans votre organisation Exchange locale et dans votre organisation Exchange Online. 
  
Pour plus d'informations sur les options de transport dans un déploiement hybride, consultez la rubrique [Options de transport dans des déploiements hybrides Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Espace d'adressage partagé sans contrôle de routage local (MX pointe vers EOP)

L'espace d'adressage partagé sans contrôle de routage local (MX pointe vers EOP) est un scénario de routage hybride du courrier, dans lequel vos boîtes aux lettres sont hébergées en partie dans le cloud à l'aide d'Exchange Online et en partie localement, et où votre enregistrement MX pointe vers EOP. Ce scénario est approprié lorsque vous utilisez le service Office 365 pour héberger certaines boîtes aux lettres de votre organisation et voulez qu'EOP protège à la fois vos boîtes aux lettres locales et dans le cloud. Dans ce scénario, le courrier envoyé à des destinataires au sein de votre organisation est initialement acheminé via EOP, où a lieu un filtrage de courrier indésirable et de stratégie avant que le courrier arrive dans vos boîtes aux lettres locales et dans le cloud. 
  
Pour plus d'informations sur les options de transport dans un déploiement hybride, consultez la rubrique [Options de transport dans des déploiements hybrides Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Dépannage d'un déploiement avec l'assistant Configuration hybride

L'utilisation de l'assistant Configuration hybride pour configurer un déploiement hybride dans Microsoft Exchange Server 2013 minimise considérablement le risque que le déploiement hybride rencontre des problèmes. Toutefois, certains points types n'appartenant pas au champ d'application de l'assistant Configuration hybride peuvent, s'ils ne sont pas correctement configurés, poser des problèmes dans un déploiement hybride. Il convient notamment de configurer correctement le serveur d'accès au client et d'installer et configurer correctement les certificats.
  
Pour plus d'informations sur le dépannage d'un déploiement avec l'Assistant Configuration hybride, consultez la rubrique [Dépannage d'un déploiement hybride](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Gestion d'une configuration hybride

Vous pouvez modifier une configuration hybride existante dans l'assistant Configuration hybride. Les scénarios incluent la désactivation du transport centralisé ou la désactivation du transport de courrier sécurisé.
  
Pour plus d'informations sur la gestion d'une configuration de déploiement hybride, consultez la rubrique [Gérer un déploiement hybride](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Conditions requises pour un déploiement hybride

Pour plus d'informations sur la configuration requise pour un déploiement hybride, consultez la rubrique [Configuration requise pour un déploiement hybride](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> Dans certaines configurations hybrides, vous devrez peut-être acheter des licences Exchange Online Protection pour vos boîtes aux lettres locales. 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les offres Office 365, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  

