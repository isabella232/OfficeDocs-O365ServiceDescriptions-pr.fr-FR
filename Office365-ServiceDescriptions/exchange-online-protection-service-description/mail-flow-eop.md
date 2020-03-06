---
title: Flux de messagerie [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Pour la plupart des organisations qui utilisent Office 365, nous hébergeons vos boîtes aux lettres et vous vous occupez du flux de messagerie. Il s’agit de la configuration la plus simple et signifie qu’Office 365 gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de conserver toutes leurs boîtes aux lettres en local. Exchange Online Protection (EOP) vous permet de le faire et fournit un traitement des messages antivirus et anti-courrier indésirable dans le Cloud.
ms.openlocfilehash: c6a41df3e8b8c157d599f6a9d55be4b7f826e1d9
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545817"
---
# <a name="mail-floweop"></a>Flux de messagerie [EOP]

Pour la plupart des organisations qui utilisent Office 365, nous hébergeons vos boîtes aux lettres et vous vous occupez du flux de messagerie. Il s’agit de la configuration la plus simple et signifie qu’Office 365 gère toutes les boîtes aux lettres et le filtrage. Toutefois, certaines organisations ont besoin de conserver toutes leurs boîtes aux lettres en local. Exchange Online Protection (EOP) vous permet de le faire et fournit un traitement des messages antivirus et anti-courrier indésirable dans le Cloud. Pour plus d’informations et pour acheter EOP, accédez à [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Vous recherchez des informations sur la gestion de domaines ou le blocage du périmètre basé sur l'annuaire (DBEB) ? Consultez la rubrique [gestion des destinataires, des domaines et des sociétés](recipient-domain-and-company-management.md). Pour en savoir plus sur toutes les fonctionnalités EOP, consultez la rubrique [Description du service Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Routage des courriers électroniques entre vos serveurs de messagerie et Office 365

Vous pouvez configurer un connecteur pour activer le flux de messagerie entre Office 365 (notamment Exchange Online ou EOP) et un serveur de messagerie SMTP comme Exchange. Pour plus d'informations à ce sujet, consultez les rubriques [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? et [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Messagerie sécurisée avec un partenaire de confiance

En tant que client EOP, vous pouvez configurer un flux de messagerie sécurisé avec un partenaire approuvé à l’aide des connecteurs Office 365. Office 365 prend en charge la communication sécurisée via le protocole TLS (Transport Layer Security) et vous pouvez créer un connecteur pour appliquer le chiffrement via TLS. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) est un protocole de chiffrement qui fournit la sécurité pour les communications sur Internet. À l’aide de connecteurs, vous pouvez configurer des certificats validés entrants et sortants TLS à l’aide de certificats validés par une autorité de certification ou une autorité de certification auto-signés. Vous pouvez également appliquer d’autres restrictions de sécurité, telles que la spécification des noms de domaine ou des plages d’adresses IP à partir desquelles votre organisation partenaire envoie du courrier. 
  
Pour plus d'informations, voir [Configurer des connecteurs pour un flux de messagerie sécurisé avec une organisation partenaire](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Saisie de l'adresse IP d'un partenaire sur une liste fiable

Vous pouvez ajouter l'adresse IP d'un partenaire de confiance à une liste verte pour être certain que les messages qui vous sont envoyés ne sont pas considérés comme du courrier indésirable. Pour ce faire, vous pouvez utiliser la liste d'adresses IP autorisées du filtre de connexion. Pour plus d'informations, consultez la rubrique relative à la [configuration de la stratégie de filtre de connexion](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Routage du courrier conditionnel

Vous pouvez configurer un connecteur avec une règle de transport afin de router le courrier vers un site spécifique en fonction de certaines conditions. Pour plus d'informations, consultez la rubrique [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Routage du courrier hybride

« Hybride » signifie que vous hébergez une partie de votre boîte aux lettres localement, et le reste dans le cloud (Exchange Online). Vous pouvez passer d'un déploiement autonome (sur site) à un déploiement hybride.
  
Si vous disposez d'un déploiement hybride, EOP vous permet de protéger vos boîtes aux lettres locales et dans le cloud. Des licences autonomes sont requises pour protéger des boîtes aux lettres locales à l'aide d'EOP. Pour plus d'informations sur le routage du courrier dans un déploiement hybride, consultez la rubrique [Routage de transport dans les déploiements hybrides Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
L'[Assistant de déploiement Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) fournit aussi des instructions détaillées concernant la mise en service d'un déploiement hybride et de transport hybride des messages. 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, consultez la rubrique [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).
