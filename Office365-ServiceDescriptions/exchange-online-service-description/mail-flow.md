---
title: Flux de messagerie
ms.author: office365servicedesc
author: pamelaar
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
description: Pour la plupart des organisations, nous hébergeons vos boîtes aux lettres et vous vous occupez du flux de messagerie. Il s’agit de la configuration la plus simple et signifie que Microsoft gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de configurations de flux de messagerie plus complexes pour s’assurer qu’elles sont conformes aux besoins spécifiques de la réglementation ou de l’entreprise. Vous pouvez en savoir plus sur ces options ici.
ms.openlocfilehash: 1ada5a3199e6ae65c6aaa99873f13a4025366a8d
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132718"
---
# <a name="mail-flow"></a>Flux de messagerie

Pour la plupart des organisations, nous hébergeons vos boîtes aux lettres et vous vous occupez du flux de messagerie. Il s’agit de la configuration la plus simple et signifie que Microsoft gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de configurations de flux de messagerie plus complexes pour s’assurer qu’elles sont conformes aux besoins spécifiques de la réglementation ou de l’entreprise. Vous pouvez en savoir plus sur ces options ici. 
  
## <a name="custom-routing-of-outbound-email"></a>Routage personnalisé du courrier sortant

Microsoft Exchange Online peut acheminer le courrier sortant de votre organisation via un serveur local ou un service hébergé (parfois appelé « hébergement intelligent »). Cela permet à votre organisation d’utiliser des appliances de protection contre la perte de données (DLP), d’effectuer un post-traitement personnalisé du courrier électronique sortant et de livrer des courriers électroniques à des partenaires commerciaux via des réseaux privés. Exchange Online prend aussi en charge la fonctionnalité de réécriture d'adresse, qui permet d'acheminer le courrier sortant via une passerelle locale qui modifie les adresses. Cette fonctionnalité vous permet de masquer des sous-domaines, de faire en sorte que les messages provenant d’une organisation à plusieurs domaines apparaissent sous la forme d’un seul domaine ou que le courrier relayé par un partenaire apparaisse comme s’il était envoyé de l’intérieur de votre organisation. Les administrateurs configurent le routage personnalisé du courrier dans le Centre d'administration Exchange (CAE).
  
Pour plus d’informations, reportez-vous [à configurer des connecteurs pour router les messages entre Microsoft et vos propres serveurs de messagerie](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
> [!IMPORTANT]
> Exchange Online transfère le flux de messagerie vers et depuis votre organisation. Si votre domaine de destinataire est hébergé dans Exchange Online avec des enregistrements DNS MX pointant vers Exchange Online Protection, le flux de messagerie de votre client vers le destinataire ne transite pas sur Internet.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

En tant que client Exchange Online, vous pouvez configurer un flux de messagerie sécurisé avec un partenaire approuvé à l’aide de Microsoft Connectors. Microsoft prend en charge la communication sécurisée via le protocole TLS (Transport Layer Security) et vous pouvez créer un connecteur pour appliquer le chiffrement via TLS. [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) est un protocole de chiffrement qui fournit la sécurité pour les communications sur Internet. À l’aide de connecteurs, vous pouvez configurer des certificats validés entrants et sortants TLS à l’aide de certificats validés par une autorité de certification ou une autorité de certification auto-signés. Vous pouvez également appliquer d’autres restrictions de sécurité, telles que la spécification des noms de domaine ou des plages d’adresses IP à partir desquelles votre organisation partenaire envoie du courrier. 
  
Pour plus d'informations, consultez la rubrique [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Il est possible qu'un certificat validé par une autorité de certification soit requis. 
  
## <a name="conditional-mail-routing"></a>Routage du courrier conditionnel

You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.
  
Pour plus d'informations, consultez la rubrique [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Liste verte de courriers entrants

You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.
  
Pour plus d'informations, consultez la rubrique [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Routage hybride du courrier

A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.
  
Pour plus d'informations sur le routage du courrier dans un déploiement hybride, consultez la rubrique [Routage de transport dans les déploiements hybrides Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
L'[Assistant de déploiement Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) fournit aussi des instructions détaillées concernant la mise en service d'un déploiement hybride et de transport hybride des messages. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Espace d'adressage partagé avec contrôle de routage local (MX pointe vers le site)

L’espace d’adressage partagé avec un contrôle de routage local (MX pointe vers local) est un scénario de routage de messagerie de déploiement hybride dans lequel vos boîtes aux lettres sont hébergées partiellement dans Exchange Online et partiellement en local, et le flux de messagerie Internet entrant et sortant est routé via l’organisation Exchange locale. Ce scénario est également appelé transport de messagerie centralisé. Dans ce scénario, Exchange Online est configuré avec EOP et le courrier Internet entrant est acheminé vers votre serveur de messagerie local avant d’être routé vers EOP et enfin vers des boîtes aux lettres hébergées dans Exchange Online. De plus, le courrier sortant de boîtes aux lettres Exchange Online est acheminé via l'organisation Exchange locale dans le cas de messages envoyés à des destinataires externes. Avec cette configuration, vous pouvez utiliser un espace de noms de domaine SMTP unique pour toutes les boîtes aux lettres, à la fois dans votre organisation Exchange locale et dans votre organisation Exchange Online. 
  
Pour plus d'informations sur les options de transport dans un déploiement hybride, consultez la rubrique [Options de transport dans des déploiements hybrides Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Espace d'adressage partagé sans contrôle de routage local (MX pointe vers EOP)

L'espace d'adressage partagé sans contrôle de routage local (MX pointe vers EOP) est un scénario de routage hybride du courrier, dans lequel vos boîtes aux lettres sont hébergées en partie dans le cloud à l'aide d'Exchange Online et en partie localement, et où votre enregistrement MX pointe vers EOP. Ce scénario est approprié lorsque vous utilisez Microsoft pour héberger certaines boîtes aux lettres de votre organisation et que vous souhaitez que EOP protège à la fois vos boîtes aux lettres locales et en nuage. Dans ce scénario, le courrier envoyé à des destinataires au sein de votre organisation est initialement acheminé via EOP, où a lieu un filtrage de courrier indésirable et de stratégie avant que le courrier arrive dans vos boîtes aux lettres locales et dans le cloud. 
  
Pour plus d'informations sur les options de transport dans un déploiement hybride, consultez la rubrique [Options de transport dans des déploiements hybrides Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Dépannage d'un déploiement avec l'assistant Configuration hybride

Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.
  
Pour plus d'informations sur le dépannage d'un déploiement avec l'Assistant Configuration hybride, consultez la rubrique [Dépannage d'un déploiement hybride](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Gestion d'une configuration hybride

You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.
  
Pour plus d'informations sur la gestion d'une configuration de déploiement hybride, consultez la rubrique [Gérer un déploiement hybride](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Conditions requises pour un déploiement hybride

Pour plus d'informations sur la configuration requise pour un déploiement hybride, consultez la rubrique [Configuration requise pour un déploiement hybride](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> Dans certaines configurations hybrides, vous devrez peut-être acheter des licences Exchange Online Protection pour vos boîtes aux lettres locales. 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  