---
title: Flux de messagerie[EOP]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: La plupart des organisations qui utilisent Office 365, nous héberger vos boîtes aux lettres et prendre en charge le flux de messagerie. Il est la configuration la plus simple et signifie que Office 365 gère toutes les boîtes aux lettres et le filtrage. Cependant, certaines organisations ont besoin de conserver toutes les boîtes aux lettres sur site. Exchange Online Protection (EOP) vous permet de faire et fournit des messages anti-courrier indésirable et antivirus de traitement dans le nuage. Pour plus d’informations et d’acheter EOP, accédez à Exchange Online Protection.
ms.openlocfilehash: 6c43d308db3c4f62e4c6891cb87263560d9478a7
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035506"
---
# <a name="mail-floweop"></a>Flux de messagerie[EOP]

La plupart des organisations qui utilisent Office 365, nous héberger vos boîtes aux lettres et prendre en charge le flux de messagerie. Il est la configuration la plus simple et signifie que Office 365 gère toutes les boîtes aux lettres et le filtrage. Cependant, certaines organisations ont besoin de conserver toutes les boîtes aux lettres sur site. Exchange Online Protection (EOP) vous permet de faire et fournit des messages anti-courrier indésirable et antivirus de traitement dans le nuage. Pour plus d’informations et d’acheter EOP, accédez à [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).
  
Vous recherchez des informations sur la gestion de domaines ou le blocage du périmètre basé sur l'annuaire (DBEB) ? Consultez la rubrique [Gestion des destinataires, des domaines et des entreprises](recipient-domain-and-company-management.md). Pour en savoir plus sur toutes les fonctionnalités EOP, consultez la rubrique [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Routage des courriers électroniques entre vos serveurs de messagerie et Office 365
<a name="BKMK_outboundmailrouting"> </a>

Vous pouvez configurer un connecteur pour activer le flux de messagerie entre Office 365 (notamment Exchange Online ou EOP) et un serveur de messagerie SMTP comme Exchange. Pour plus d'informations à ce sujet, consultez les rubriques [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? et [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Messagerie sécurisée avec un partenaire de confiance
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

En tant que client EOP, vous pouvez établir un flux de messagerie sécurisé avec un partenaire de confiance en utilisant les connecteurs d'Office 365. Office 365 prend en charge la communication sécurisée par protocole TLS (Transport Layer Security). Vous pouvez créer un connecteur pour appliquer le chiffrement via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) est un protocole de chiffrement qui sécurise les communications sur Internet. Grâce aux connecteurs, vous pouvez configurer un protocole TLS entrant et sortant forcé, à l'aide de certificats validés par une autorité de certification ou auto-signés. Vous pouvez également appliquer d'autres restrictions de sécurité, par exemple en spécifiant des noms de domaine ou des plages d'adresses IP à partir desquels votre organisation partenaire envoie du courrier. 
  
Pour plus d'informations, voir [Configurer des connecteurs pour un flux de messagerie sécurisé avec une organisation partenaire](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).
  
## <a name="safe-listing-a-partners-ip-address"></a>Saisie de l'adresse IP d'un partenaire sur une liste fiable
<a name="BKMK_safelistingapartnersipaddress"> </a>

Vous pouvez ajouter l'adresse IP d'un partenaire de confiance à une liste verte pour être certain que les messages qui vous sont envoyés ne sont pas considérés comme du courrier indésirable. Pour ce faire, vous pouvez utiliser la liste d'adresses IP autorisées du filtre de connexion. Pour plus d'informations, consultez la rubrique relative à la [configuration de la stratégie de filtre de connexion](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Routage du courrier conditionnel
<a name="BKMK_conditionalmailrouting"> </a>

Vous pouvez configurer un connecteur avec une règle de transport afin de router le courrier vers un site spécifique en fonction de certaines conditions. Pour plus d'informations, consultez la rubrique [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="hybrid-mail-routing"></a>Routage du courrier hybride
<a name="BKMK_hybridmailrouting"> </a>

« Hybride » signifie que vous hébergez une partie de votre boîte aux lettres localement, et le reste dans le cloud (Exchange Online). Vous pouvez passer d'un déploiement autonome (sur site) à un déploiement hybride.
  
Si vous disposez d'un déploiement hybride, EOP vous permet de protéger vos boîtes aux lettres locales et dans le cloud. Des licences autonomes sont requises pour protéger des boîtes aux lettres locales à l'aide d'EOP. Pour plus d'informations sur le routage du courrier dans un déploiement hybride, consultez la rubrique [Routage de transport dans les déploiements hybrides Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
L'[Assistant de déploiement Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) fournit aussi des instructions détaillées concernant la mise en service d'un déploiement hybride et de transport hybride des messages. 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités
<a name="BKMK_hybridmailrouting"> </a>

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).
  

