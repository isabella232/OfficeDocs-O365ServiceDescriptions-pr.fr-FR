---
title: Limites d’Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Les limites suivantes existent actuellement pour Exchange Online Protection. Ces limites ne sont pas configurables sauf indication contraire.
ms.openlocfilehash: c4bce8f7b501a7a00eea723464e20964899b3560
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653050"
---
# <a name="exchange-online-protection-limits"></a>Limites d’Exchange Online Protection

Les limites suivantes existent actuellement pour Exchange Online Protection. Ces limites ne sont pas configurables sauf indication contraire. 
  
> [!TIP]
> Pour plus d’informations sur les limites dans Exchange Online, consultez [les limites d’Exchange Online.](../exchange-online-service-description/exchange-online-limits.md) Les limites de règle de transport s'appliquent également aux clients autonomes EOP. Les limites de fréquence de messages et de débit maximal pour les destinataires dans Exchange Online ne s'appliquent pas aux clients autonomes EOP. 
  
- **Limite de** domaine : vous pouvez ajouter jusqu’à 900 domaines par client. Les sous-domaines peuvent être inclus dans cette limite de 900 ou, si nécessaire, dans le cadre d'une option de réception globale et d'une mise en correspondance des sous-domaines. Pour plus d'informations, voir [Gérer les domaines acceptés dans EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).

- **Limite de domaine distant** : vous pouvez ajouter jusqu’à 200 domaines distants par client.
    
- **Limite de taille des** messages : la taille maximale des messages pour les clients autonomes EOP, pièces jointes compris, est de 150 Mo. 
    
- **Nombre de messages** sortants envoyés : la limite du nombre de messages sortants envoyés via EOP est suffisamment élevée pour garantir que les communications électroniques normales ne sont pas traitées comme du courrier indésirable. Si vous voulez envoyer des messages électroniques commerciaux en bloc, plutôt que d'envoyer des messages sortants via EOP, nous vous recommandons d'utiliser un fournisseur de services de messagerie tiers (ESP) ou de les envoyer via vos serveurs de messagerie sur site. 
    
- **Limite de** destinataire : tant que l’hôte d’envoi peut fractionner le message en « blocs » de moins de 500 destinataires, aucune limite explicite n’est définie. Toutefois, chaque « segment » est traité comme un nouveau message. Les messages trop nombreux sur une courte période, les messages provenant d'un hôte avec une mauvaise réputation ou les messages avec un contenu douteux pourraient être limités ou bloqués. 
    
- Limite des listes d’adresses IP autorisées ou d’adresses **IP** autorisées : lors de la configuration d’une liste d’adresses IP autorisées ou d’une liste d’adresses IP bloqués dans le filtre de connexion, vous pouvez spécifier un maximum de 1 273 entrées, où une entrée est soit une adresse IP unique, soit une plage CIDR d’adresses IP de /24 à /32. 
    
- **Limite de report des** messages : les messages en attente resteront dans nos files d’attente pendant 24 heures. Les nouvelles tentatives d'envoi de message sont basées sur le type d'erreur reçu à partir du système de messagerie du destinataire. Les messages sont renvoyés toutes les 15 minutes. 
    
- **Période de rétention de mise en** quarantaine du courrier indésirable : par défaut, les messages indésirables envoyés en quarantaine sont conservés pendant 30 jours. Les administrateurs peuvent écourter ce délai via des stratégies de filtrage de contenu. 
    
- **Notifications de mise** en quarantaine du courrier indésirable pour l’utilisateur final : par défaut, si elle est activée, les notifications de mise en quarantaine du courrier indésirable de l’utilisateur final sont envoyées tous les 3 jours. Il est possible de configurer ces notifications afin qu'elles soient envoyées tous les 1 à 15 jours. 
    
- **Limites** de rapport et de suivi des messages : pour les limites de rapport et de suivi des messages, consultez la section « Disponibilité et latence des données de suivi des messages et des rapports » dans Reporting et le suivi des messages dans [Exchange Online Protection.](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection)
    
### <a name="limits-across-eop-options"></a>Limites parmi les options EOP

| Fonctionnalité | EOP autonome | Fonctionnalités EOP dans Exchange Online | Licence d’accès client Exchange Enterprise avec services |
|:-----|:-----|:-----|:-----|
|Limite de domaine  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limite de domaine distant  <br/> |200  <br/> |200  <br/> |200  <br/> |
|Limite de taille de message (pièces jointes comprises)  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |
|Limite de destinataires  <br/> |Voir « Limite de destinataires » ci-dessus.  <br/> |500 destinataires lors de l'envoi à partir d'une boîte aux lettres hébergée. Voir « Limite de destinataires » ci-dessus pour connaître d'autres scénarios.  <br/> |Voir « Limite de destinataires » ci-dessus.  <br/> |
|Nombre limite d'expéditeurs autorisés  <br/> |1 024 entrées  <br/> |1 024 entrées  <br/> ||
|Limite des expéditeurs bloqués par stratégie  <br/> |1 024 entrées  <br/> |1 024 entrées  <br/> ||
|Limite des listes d'adresses IP autorisées et bloquées  <br/> |1 273 entrées  <br/> |1 273 entrées  <br/> |1 273 entrées  <br/> |
|Limite de report de message  <br/> |1 jour, retentées toutes les 15 minutes  <br/> |1 jour, retentées toutes les 15 minutes  <br/> |1 jour, retentées toutes les 15 minutes  <br/> |
|Période de rétention du courrier indésirable en quarantaine  <br/> |30 jours par défaut, mais peut être réduit  <br/> |30 jours par défaut, mais peut être réduit  <br/> |30 jours par défaut, mais peut être réduit  <br/> |
|Notification de mise en quarantaine du courrier indésirable pour l'utilisateur final  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |
