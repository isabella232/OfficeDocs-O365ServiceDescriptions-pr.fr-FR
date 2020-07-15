---
title: Flux de messagerie [EOP]
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
description: Pour la plupart des organisations qui utilisent Office 365, nous hébergeons vos boîtes aux lettres et vous vous occupez du flux de messagerie. Il s’agit de la configuration la plus simple et signifie que Microsoft gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de conserver toutes leurs boîtes aux lettres en local. Exchange Online Protection (EOP) vous permet de le faire et fournit un traitement des messages antivirus et anti-courrier indésirable dans le Cloud.
ms.openlocfilehash: 751551ef6b3ae710646b2fb63960eee5983d6c47
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132818"
---
# <a name="mail-floweop"></a>Flux de messagerie [EOP]

Pour la plupart des organisations qui utilisent Microsoft, nous hébergeons vos boîtes aux lettres et vous vous occupez du flux de messagerie. Il s’agit de la configuration la plus simple et signifie que Microsoft gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de conserver toutes leurs boîtes aux lettres en local. Exchange Online Protection (EOP) vous permet de le faire et fournit un traitement des messages antivirus et anti-courrier indésirable dans le Cloud. Pour plus d’informations et pour acheter EOP, accédez à [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Vous recherchez des informations sur la gestion de domaines ou le blocage du périmètre basé sur l'annuaire (DBEB) ? Consultez la rubrique [gestion des destinataires, des domaines et des sociétés](recipient-domain-and-company-management.md). Pour en savoir plus sur toutes les fonctionnalités EOP, consultez la rubrique [Description du service Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Routage des courriers électroniques entre Microsoft et vos propres serveurs de messagerie

Vous pouvez configurer un connecteur pour activer le flux de messagerie entre Microsoft (y compris Exchange Online ou EOP) et un serveur de messagerie SMTP tel qu’Exchange. Pour plus d'informations à ce sujet, consultez les rubriques [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? Et [configurez des connecteurs pour router les messages entre Microsoft et vos propres serveurs de messagerie](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

En tant que client EOP, vous pouvez configurer un flux de messagerie sécurisé avec un partenaire approuvé à l’aide de Microsoft Connectors. Microsoft prend en charge la communication sécurisée via le protocole TLS (Transport Layer Security) et vous pouvez créer un connecteur pour appliquer le chiffrement via TLS. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) est un protocole de chiffrement qui fournit la sécurité pour les communications sur Internet. À l’aide de connecteurs, vous pouvez configurer des certificats validés entrants et sortants TLS à l’aide de certificats validés par une autorité de certification ou une autorité de certification auto-signés. Vous pouvez également appliquer d’autres restrictions de sécurité, telles que la spécification des noms de domaine ou des plages d’adresses IP à partir desquelles votre organisation partenaire envoie du courrier. 
  
Pour plus d'informations, voir [Configurer des connecteurs pour un flux de messagerie sécurisé avec une organisation partenaire](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Saisie de l'adresse IP d'un partenaire sur une liste fiable

You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Routage du courrier conditionnel

You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Routage du courrier hybride

Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.
  
If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
L'[Assistant de déploiement Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) fournit aussi des instructions détaillées concernant la mise en service d'un déploiement hybride et de transport hybride des messages. 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).
