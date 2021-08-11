---
title: Flux de messagerie
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: Pour la plupart des organisations, nous hébergeons vos boîtes aux lettres et nous nous chargeons du flux de messagerie. Il s’agit de la configuration la plus simple et signifie que Microsoft gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de configurations de flux de messagerie plus complexes pour s’assurer qu’elles sont conformes à des exigences réglementaires ou commerciales spécifiques. Vous pouvez en savoir plus sur ces options ici.
ms.openlocfilehash: fafaab4b4bec705c00df5fd47d80fd30138a8a9b6da1c1707ae4e087de8b617e
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663787"
---
# <a name="mail-flow"></a>Flux de messagerie

Pour la plupart des organisations, nous hébergeons vos boîtes aux lettres et nous nous chargeons du flux de messagerie. Il s’agit de la configuration la plus simple et signifie que Microsoft gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de configurations de flux de messagerie plus complexes pour s’assurer qu’elles sont conformes à des exigences réglementaires ou commerciales spécifiques. Vous pouvez en savoir plus sur ces options ici. 
  
## <a name="custom-routing-of-outbound-email"></a>Routage personnalisé du courrier sortant

Microsoft Exchange Online peut acheminer le courrier sortant de votre organisation via un serveur local ou un service hébergé (parfois appelé « hébergement intelligent »). Cela permet à votre organisation d’utiliser des appliances de protection contre la perte de données (DLP), d’effectuer un post-traitement personnalisé du courrier électronique sortant et de remettre le courrier électronique aux partenaires commerciaux via des réseaux privés. Exchange Online prend aussi en charge la fonctionnalité de réécriture d'adresse, qui permet d'acheminer le courrier sortant via une passerelle locale qui modifie les adresses. Cette fonctionnalité vous permet de masquer les sous-domaines, de faire apparaître le courrier électronique d’une organisation multi-domaines en tant que domaine unique ou de faire apparaître le courrier relayé par des partenaires comme s’il était envoyé depuis l’intérieur de votre organisation. Les administrateurs configurent le routage personnalisé du courrier dans le Centre d'administration Exchange (CAE).
  
Pour plus d’informations, voir [Configurer des connecteurs pour router le courrier entre Microsoft et vos propres serveurs de messagerie.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
> [!IMPORTANT]
> Exchange Online transfère le flux de messagerie vers et depuis votre organisation. Si votre domaine de destinataire est hébergé dans Exchange Online avec des enregistrements MX DNS pointant vers Exchange Online Protection, le flux de messagerie entre votre client et le destinataire ne circule pas sur Internet.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

En tant Exchange Online client, vous pouvez configurer un flux de messagerie sécurisé avec un partenaire approuvé à l’aide de connecteurs Microsoft. Microsoft prend en charge la communication sécurisée via TLS (Transport Layer Security), et vous pouvez créer un connecteur pour appliquer le chiffrement via TLS. [TLS est](/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) un protocole de chiffrement qui assure la sécurité des communications sur Internet. À l’aide de connecteurs, vous pouvez configurer le TLS entrant forcé et le TLS sortant à l’aide de certificats auto-signés ou validés par l’autorité de certification. Vous pouvez également appliquer d’autres restrictions de sécurité, telles que la spécification de noms de domaine ou de plages d’adresses IP à partir des duquel votre organisation partenaire envoie des messages. 
  
Pour plus d'informations, consultez la rubrique [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Il est possible qu'un certificat validé par une autorité de certification soit requis. 
  
## <a name="conditional-mail-routing"></a>Routage du courrier conditionnel

Vous pouvez acheminer le courrier vers des sites spécifiques à l'aide de connecteurs et de règles de transport. Avec un routage basé sur des critères, vous pouvez choisir un connecteur en fonction de conditions spécifiques.
  
Pour plus d'informations, consultez la rubrique [Scenario: Conditional mail routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Liste verte de courriers entrants

Vous pouvez ajouter l'adresse IP d'un partenaire de confiance à une liste verte pour être certain que les messages envoyés par le partenaire ne font pas l'objet d'un filtrage du courrier indésirable. Pour ce faire, vous pouvez utiliser la liste d'adresses IP autorisées du filtre de connexion.
  
Pour plus d'informations, consultez la rubrique [Configure the connection filter policy](/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Routage hybride du courrier

Un déploiement hybride offre aux entreprises la possibilité d'étendre dans le cloud l'éventail de fonctionnalités proposé et le contrôle administratif qu'elles exercent dans leur organisation Microsoft Exchange locale existante. Dans un transport hybride, les messages envoyés entre des destinataires d'une organisation sont authentifiés, chiffrés et transférés via le protocole TLS (Transport Layer Security) et apparaissent comme « internes » pour des composants Exchange, tels que les règles de transport, la journalisation et les stratégies de protection contre le courrier indésirable. Vous configurez le transport hybride à l'aide de l'Assistant Configuration hybride dans Exchange Server.
  
Pour plus d'informations sur le routage du courrier dans un déploiement hybride, consultez la rubrique [Routage de transport dans les déploiements hybrides Exchange](/exchange/transport-routing).
  
L'[Assistant de déploiement Microsoft Exchange Server](/exchange/exchange-deployment-assistant) fournit aussi des instructions détaillées concernant la mise en service d'un déploiement hybride et de transport hybride des messages. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Espace d'adressage partagé avec contrôle de routage local (MX pointe vers le site)

L’espace d’adressas partagé avec le contrôle de routage local (MX pointe vers l’local) est un scénario de routage de messagerie de déploiement hybride dans lequel vos boîtes aux lettres sont hébergées partiellement dans Exchange Online et partiellement en local, et le flux de messagerie Internet entrant et sortant est acheminé via l’organisation Exchange sur site. Ce scénario est également appelé transport de messagerie centralisé. Dans ce scénario, Exchange Online est mis en service avec EOP et le courrier Internet entrant est acheminé vers votre serveur de messagerie local avant d’être acheminé vers EOP et enfin vers les boîtes aux lettres hébergées dans Exchange Online. De plus, le courrier sortant de boîtes aux lettres Exchange Online est acheminé via l'organisation Exchange locale dans le cas de messages envoyés à des destinataires externes. Avec cette configuration, vous pouvez utiliser un espace de noms de domaine SMTP unique pour toutes les boîtes aux lettres, à la fois dans votre organisation Exchange locale et dans votre organisation Exchange Online. 
  
Pour plus d'informations sur les options de transport dans un déploiement hybride, consultez la rubrique [Options de transport dans des déploiements hybrides Exchange](/exchange/transport-options).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Espace d'adressage partagé sans contrôle de routage local (MX pointe vers EOP)

L'espace d'adressage partagé sans contrôle de routage local (MX pointe vers EOP) est un scénario de routage hybride du courrier, dans lequel vos boîtes aux lettres sont hébergées en partie dans le cloud à l'aide d'Exchange Online et en partie localement, et où votre enregistrement MX pointe vers EOP. Ce scénario est approprié lorsque vous utilisez Microsoft pour héberger certaines boîtes aux lettres de votre organisation et que vous souhaitez qu’EOP protège vos boîtes aux lettres sur site et en nuage. Dans ce scénario, le courrier envoyé à des destinataires au sein de votre organisation est initialement acheminé via EOP, où a lieu un filtrage de courrier indésirable et de stratégie avant que le courrier arrive dans vos boîtes aux lettres locales et dans le cloud. 
  
Pour plus d'informations sur les options de transport dans un déploiement hybride, consultez la rubrique [Options de transport dans des déploiements hybrides Exchange](/exchange/transport-options).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Dépannage d'un déploiement avec l'assistant Configuration hybride

L'utilisation de l'assistant Configuration hybride pour configurer un déploiement hybride dans Microsoft Exchange Server 2013 minimise considérablement le risque que le déploiement hybride rencontre des problèmes. Toutefois, certains points types n'appartenant pas au champ d'application de l'assistant Configuration hybride peuvent, s'ils ne sont pas correctement configurés, poser des problèmes dans un déploiement hybride. Il convient notamment de configurer correctement le serveur d'accès au client et d'installer et configurer correctement les certificats.
  
Pour plus d'informations sur le dépannage d'un déploiement avec l'Assistant Configuration hybride, consultez la rubrique [Dépannage d'un déploiement hybride](/exchange/hybrid-deployment/troubleshoot-a-hybrid-deployment).
  
### <a name="managing-a-hybrid-configuration"></a>Gestion d'une configuration hybride

Vous pouvez modifier une configuration hybride existante dans l'assistant Configuration hybride. Les scénarios incluent la désactivation du transport centralisé ou la désactivation du transport de courrier sécurisé.
  
Pour plus d'informations sur la gestion d'une configuration de déploiement hybride, consultez la rubrique [Gérer un déploiement hybride](/previous-versions/exchange-server/exchange-150/jj200791(v=exchg.150)).
  
### <a name="hybrid-deployment-requirements"></a>Conditions requises pour un déploiement hybride

Pour plus d'informations sur la configuration requise pour un déploiement hybride, consultez la rubrique [Configuration requise pour un déploiement hybride](/exchange/hybrid-deployment-prerequisites).
  
> [!IMPORTANT]
> Dans certaines configurations hybrides, vous devrez peut-être acheter des licences Exchange Online Protection pour vos boîtes aux lettres locales. 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, consultez la [description Exchange Online service.](exchange-online-service-description.md)
