---
title: Limites d’Exchange Online Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Les limites suivantes existent actuellement pour Exchange Online Protection. Sauf indication contraire, elles ne sont pas configurables.
ms.openlocfilehash: fd5dbbe0f52eb7789b2e730faf76e89803033ad6
ms.sourcegitcommit: 5b1670c36e256aef7f222951a49a4411afc3bcb6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/07/2019
ms.locfileid: "36231392"
---
# <a name="exchange-online-protection-limits"></a>Limites d’Exchange Online Protection

Les limites suivantes existent actuellement pour Exchange Online Protection. Sauf indication contraire, elles ne sont pas configurables. 
  
> [!TIP]
> Pour plus d'informations sur les limites de Exchange Online, voir [Limites d'Exchange Online](../exchange-online-service-description/exchange-online-limits.md). Les limites de règle de transport s'appliquent également aux clients autonomes EOP. Les limites de fréquence de messages et de débit maximal pour les destinataires dans Exchange Online ne s'appliquent pas aux clients autonomes EOP. 
  
- **Limite de domaine** Vous pouvez ajouter jusqu'à 900 domaines par client. Les sous-domaines peuvent être inclus dans cette limite de 900 ou, si nécessaire, dans le cadre d'une option de réception globale et d'une mise en correspondance des sous-domaines. Pour plus d'informations, voir [Gérer les domaines acceptés dans EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Limite de taille de message** La taille maximale de message pour les clients autonomes EOP, pièces jointes incluses, est de 150 Mo. 
    
- **Nombre de messages sortants envoyés** La limite du nombre de messages sortants envoyés via EOP est suffisamment élevée pour garantir que la communication électronique normale n'est pas traitée en tant que courrier indésirable. Si vous voulez envoyer des messages électroniques commerciaux en bloc, plutôt que d'envoyer des messages sortants via EOP, nous vous recommandons d'utiliser un fournisseur de services de messagerie tiers (ESP) ou de les envoyer via vos serveurs de messagerie sur site. 
    
- **Limite de destinataires** Tant que l'hôte expéditeur peut fractionner le message en « segments » de moins de 500 destinataires, aucune limite explicite n'est définie. Toutefois, chaque « segment » est traité comme un nouveau message. Les messages trop nombreux sur une courte période, les messages provenant d'un hôte avec une mauvaise réputation ou les messages avec un contenu douteux pourraient être limités ou bloqués. 
    
- **Limite des listes d'adresses IP autorisées ou bloquées** Lors de la configuration d'une liste d'adresses IP autorisées ou d'une liste d'adresses IP bloquées dans le filtre de connexion, vous pouvez spécifier un maximum de 1 273 adresses IP (en gardant à l'esprit qu'une seule entrée peut couvrir toutes les adresses de 24 à 32 en utilisant une notation CIDR). 
    
- **Limite de report de message** Les messages dans le report resteront dans nos files d’attente pendant 24 heures. Les nouvelles tentatives d'envoi de message sont basées sur le type d'erreur reçu à partir du système de messagerie du destinataire. Les messages sont renvoyés toutes les 15 minutes. 
    
- **Période** de rétention de quarantaine du courrier indésirable Par défaut, les messages indésirables envoyés à la quarantaine sont conservés pendant 30 jours. Les administrateurs peuvent écourter ce délai via des stratégies de filtrage de contenu. 
    
- **Notifications de mise en quarantaine du courrier indésirable de l'utilisateur final** Par défaut, si cette option est activée, les notifications de mise en quarantaine du courrier indésirable de l'utilisateur final sont envoyées tous les 3 jours. Il est possible de configurer ces notifications afin qu'elles soient envoyées tous les 1 à 15 jours. 
    
- **Limites de suivi de message et de création de rapports** Pour connaître les limites de création de rapports et de suivi de messages, consultez la section relative à la latence et à la disponibilité des données en matière de création de rapports et de suivi des messages dans [Création de rapports et suivi des messages dans Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Limites parmi les options EOP

|**Fonctionnalité**|****EOP autonome****|****Fonctionnalités EOP dans Exchange Online****|****Licence d'accès client Exchange Enterprise avec services****|
|:-----|:-----|:-----|:-----|
|Limite de domaine  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limite de taille de message (pièces jointes comprises)  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |
|Limite de destinataires  <br/> |Voir « Limite de destinataires » ci-dessus.  <br/> |500 destinataires lors de l'envoi à partir d'une boîte aux lettres hébergée. Voir « Limite de destinataires » ci-dessus pour connaître d'autres scénarios.  <br/> |Voir « Limite de destinataires » ci-dessus.  <br/> |
|Nombre limite d'expéditeurs autorisés  <br/> |1 024 entrées  <br/> |1 024 entrées  <br/> ||
|Nombre limite d’expéditeurs bloqués par stratégie  <br/> |1 024 entrées  <br/> |1 024 entrées  <br/> ||
|Limite des listes d'adresses IP autorisées et bloquées  <br/> |1 273 entrées  <br/> |1 273 entrées  <br/> |1 273 entrées  <br/> |
|Limite de report de message  <br/> |2 jours, nouvelle tentative toutes les 15 minutes  <br/> |2 jours, nouvelle tentative toutes les 15 minutes  <br/> |2 jours, nouvelle tentative toutes les 15 minutes  <br/> |
|Période de rétention du courrier indésirable en quarantaine  <br/> |30 jours par défaut, mais peut être abaissé  <br/> |30 jours par défaut, mais peut être abaissé  <br/> |30 jours par défaut, mais peut être abaissé  <br/> |
|Notification de mise en quarantaine du courrier indésirable pour l'utilisateur final  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |3 jours par défaut, configurable entre 1 et 15 jours  <br/> |
   

