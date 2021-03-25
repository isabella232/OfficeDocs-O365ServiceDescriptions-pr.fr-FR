---
title: Flux de messagerie dans Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Lisez cet article pour en savoir plus sur le flux de messagerie dans Microsoft Exchange Online Protection des données (EOP).
ms.openlocfilehash: 1d8cbe7d3483ee0cfc73e8cea372e0d36dbc7b6d
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173789"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Flux de messagerie dans Exchange Online Protection

Pour la plupart des organisations qui utilisent Microsoft, nous hébergeons vos boîtes aux lettres et nous nous chargeons du flux de messagerie. Il s’agit de la configuration la plus simple et signifie que Microsoft gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de conserver toutes leurs boîtes aux lettres localement. Exchange Online Protection (EOP) vous permet de le faire et fournit un traitement de courrier antivirus et anti-courrier indésirable dans le cloud. Pour plus d’informations et pour acheter EOP, go to [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Vous recherchez des informations sur la gestion de domaines ou le blocage du périmètre basé sur l'annuaire (DBEB) ? Consultez [la gestion des destinataires, des domaines et des entreprises.](recipient-domain-and-company-management.md) Pour en savoir plus sur toutes les fonctionnalités EOP, consultez la description du [service Exchange Online Protection.](exchange-online-protection-service-description.md)
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Routage du courrier électronique entre Microsoft et vos propres serveurs de messagerie

Vous pouvez configurer un connecteur pour activer le flux de messagerie entre Microsoft (y compris Exchange Online ou EOP) et un serveur de messagerie SMTP tel qu’Exchange. Pour plus d'informations à ce sujet, consultez les rubriques [Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? Et [configurer des connecteurs pour router le courrier entre Microsoft et vos propres serveurs de messagerie.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

En tant que client EOP, vous pouvez configurer un flux de messagerie sécurisé avec un partenaire approuvé à l’aide de connecteurs Microsoft. Microsoft prend en charge la communication sécurisée via TLS (Transport Layer Security), et vous pouvez créer un connecteur pour appliquer le chiffrement via TLS. [TLS est](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) un protocole de chiffrement qui assure la sécurité des communications sur Internet. À l’aide de connecteurs, vous pouvez configurer le TLS entrant forcé et le TLS sortant à l’aide de certificats auto-signés ou validés par l’autorité de certification. Vous pouvez également appliquer d’autres restrictions de sécurité, telles que la spécification de noms de domaine ou de plages d’adresses IP à partir des duquel votre organisation partenaire envoie des messages. 
  
Pour plus d'informations, voir [Configurer des connecteurs pour un flux de messagerie sécurisé avec une organisation partenaire](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Saisie de l'adresse IP d'un partenaire sur une liste fiable

Vous pouvez ajouter l'adresse IP d'un partenaire de confiance à une liste verte pour être certain que les messages qui vous sont envoyés ne sont pas considérés comme du courrier indésirable. Pour ce faire, vous pouvez utiliser la liste d'adresses IP autorisées du filtre de connexion. Pour plus d'informations, consultez la rubrique relative à la [configuration de la stratégie de filtre de connexion](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy).
  
## <a name="conditional-mail-routing"></a>Routage du courrier conditionnel

Vous pouvez configurer un connecteur avec une règle de transport afin de router le courrier vers un site spécifique en fonction de certaines conditions. Pour plus d'informations, consultez la rubrique [Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Routage du courrier hybride

« Hybride » signifie que vous hébergez une partie de votre boîte aux lettres localement, et le reste dans le cloud (Exchange Online). Vous pouvez passer d'un déploiement autonome (sur site) à un déploiement hybride.
  
Si vous disposez d'un déploiement hybride, EOP vous permet de protéger vos boîtes aux lettres locales et dans le cloud. Des licences autonomes sont requises pour protéger des boîtes aux lettres locales à l'aide d'EOP. Pour plus d'informations sur le routage du courrier dans un déploiement hybride, consultez la rubrique [Routage de transport dans les déploiements hybrides Exchange](/exchange/transport-routing).
  
L'[Assistant de déploiement Microsoft Exchange Server](/exchange/exchange-deployment-assistant) fournit aussi des instructions détaillées concernant la mise en service d'un déploiement hybride et de transport hybride des messages. 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, consultez la description du [service Exchange Online Protection.](exchange-online-protection-service-description.md)