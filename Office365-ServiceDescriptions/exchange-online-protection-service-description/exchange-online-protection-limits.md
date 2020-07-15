---
title: Limites d’Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Les limites suivantes existent actuellement pour Exchange Online Protection. Ces limites ne sont pas configurables sauf indication contraire.
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133008"
---
# <a name="exchange-online-protection-limits"></a>Limites d’Exchange Online Protection

Les limites suivantes existent actuellement pour Exchange Online Protection. Ces limites ne sont pas configurables sauf indication contraire. 
  
> [!TIP]
> Pour plus d’informations sur les limites dans Exchange Online, consultez la rubrique [limites d’Exchange Online](../exchange-online-service-description/exchange-online-limits.md). Les limites de règle de transport s'appliquent également aux clients autonomes EOP. Les limites de fréquence de messages et de débit maximal pour les destinataires dans Exchange Online ne s'appliquent pas aux clients autonomes EOP. 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Limite de taille de message** La taille maximale de message pour les clients autonomes EOP, pièces jointes incluses, est de 150 Mo. 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **Limite des listes d'adresses IP autorisées ou bloquées** Lors de la configuration d'une liste d'adresses IP autorisées ou d'une liste d'adresses IP bloquées dans le filtre de connexion, vous pouvez spécifier un maximum de 1 273 adresses IP (en gardant à l'esprit qu'une seule entrée peut couvrir toutes les adresses de 24 à 32 en utilisant une notation CIDR). 
    
- **Limite de report de message** Les messages dans le report resteront dans nos files d’attente pendant 24 heures. Les nouvelles tentatives d'envoi de message sont basées sur le type d'erreur reçu à partir du système de messagerie du destinataire. Les messages sont renvoyés toutes les 15 minutes. 
    
- **Période de rétention de quarantaine du courrier indésirable** Par défaut, les messages indésirables envoyés à la quarantaine sont conservés pendant 30 jours. Les administrateurs peuvent écourter ce délai via des stratégies de filtrage de contenu. 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **Limites de création de rapports et de suivi des messages** Pour plus d’informations sur les rapports et les limites de suivi des messages, consultez la section « disponibilité et latence des données de suivi des rapports et des messages » dans [Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Limites parmi les options EOP

|**Fonctionnalité**|****EOP autonome****|****Fonctionnalités EOP dans Exchange Online****|****Licence d'accès client Exchange Enterprise avec services****|
|:-----|:-----|:-----|:-----|
|Limite de domaine  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limite de taille de message (pièces jointes comprises)  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |
|Limite de destinataires  <br/> |Voir « Limite de destinataires » ci-dessus.  <br/> |500 destinataires lors de l'envoi à partir d'une boîte aux lettres hébergée. Voir « Limite de destinataires » ci-dessus pour connaître d'autres scénarios.  <br/> |Voir « Limite de destinataires » ci-dessus.  <br/> |
|Nombre limite d'expéditeurs autorisés  <br/> |1 024 entrées  <br/> |1 024 entrées  <br/> ||
|Nombre limite d’expéditeurs bloqués par stratégie  <br/> |1 024 entrées  <br/> |1 024 entrées  <br/> ||
|Limite des listes d'adresses IP autorisées et bloquées  <br/> |1 273 entrées  <br/> |1 273 entrées  <br/> |1 273 entrées  <br/> |
|Limite de report de message  <br/> |1 jour, nouvelle tentative toutes les 15 minutes  <br/> |1 jour, nouvelle tentative toutes les 15 minutes  <br/> |1 jour, nouvelle tentative toutes les 15 minutes  <br/> |
|Période de rétention du courrier indésirable en quarantaine  <br/> |30 jours par défaut, mais peut être abaissé  <br/> |30 jours par défaut, mais peut être abaissé  <br/> |30 jours par défaut, mais peut être abaissé  <br/> |
|Notification de mise en quarantaine du courrier indésirable pour l'utilisateur final  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |
   

