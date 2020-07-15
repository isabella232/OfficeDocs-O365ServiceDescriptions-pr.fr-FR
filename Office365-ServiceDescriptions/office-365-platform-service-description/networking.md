---
title: Réseau
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft prend en charge les fonctionnalités de mise en réseau suivantes.
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132328"
---
# <a name="networking"></a>Réseau

Microsoft prend en charge les fonctionnalités de mise en réseau suivantes.
  
## <a name="ports-protocols-and-ip-addresses"></a>Ports, protocoles et adresses IP

Microsoft utilise des adresses IPv4 et IPv6. L'utilisation des adresses IPv6 est facultative et non obligatoire pour la connexion à Office 365. Toutes les fonctionnalités de Microsoft 365 ne sont pas entièrement activées avec IPv6. Pour plus d’informations sur la prise en charge D’ipv6, voir [prise en charge d’IPv6 dans les services Microsoft](https://docs.microsoft.com/office365/enterprise/ipv6-support).
  
Microsoft gère une liste d’adresses IP autorisées dans l’aide de Microsoft. Pour plus d’informations, consultez la rubrique [URL et plages d’adresses IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Pour Office 365 géré par 21Vianet, voir [URL et adresses IP pour Office 365 géré par 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Pour Office 365 Germany, voir [Points de terminaison Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made. 
  
## <a name="bandwidth-requirements"></a>Bande passante requise

Pour plus d'informations sur la configuration de bande passante requise, consultez [Planification de bande passante Internet](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Connexion à Microsoft

Toutes les connexions à Microsoft sont réalisées sur l’Internet public ou sur une connexion Azure ExpressRoute privée, et sont sécurisées par le protocole SSL, selon le cas. Azure ExpressRoute permet de se connecter directement au réseau Microsoft Global, en ignorant Internet. Un partenaire de mise en réseau Microsoft fournit la connectivité au réseau Microsoft global.
  
Pour plus d'informations sur Azure ExpressRoute, consultez la rubrique [Azure ExpressRoute pour Office 365](https://aka.ms/expressrouteoffice365).
  
### <a name="wan-accelerators"></a>Accélérateurs de WAN

Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Réseau Microsoft mondial

L’infrastructure de réseau Microsoft est composée d’un vaste portefeuille global de centres de données, de serveurs, de réseaux de distribution de contenu, de nœuds informatiques de périmètre et de réseaux à fibre optique pour fournir une distribution globale des services. L'instrumentation et le suivi avancés des services s'intègrent au plus haut niveau avec chaque composant, offrant une excellente visibilité sur le centre de données, la dorsale principale des réseaux, les échanges Internet et au-delà, afin de contribuer à la détection, au diagnostic et à la gestion des causes des perturbations qui surviennent. Le réseau est conçu de manière à maintenir une capacité suffisante, même en cas d'interruptions de réseau à grande échelle, sans aucune dégradation des performances. Pour plus d’informations, consultez la rubrique [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network). 
  
Afin de préserver la confidentialité et l’intégrité des données client, Microsoft conserve les réseaux de services grand public distincts des réseaux Microsoft. Plusieurs techniques sont utilisées pour contrôler les flux d'informations, y compris, mais sans s'y limiter :
  
- Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.
    
- Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.
    
- Pare-feu. Les pare-feu et autres points d’application de la sécurité réseau sont utilisés pour limiter les échanges de données avec les systèmes exposés à Internet et pour isoler les systèmes des systèmes principaux gérés par Microsoft. 
    
- Restrictions de protocole.
    
Pour plus d'informations, rendez-vous dans le [Centre de gestion de la confidentialité Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, voir [Microsoft 365 et Office 365 Platform Service Description](office-365-platform-service-description.md).
  

