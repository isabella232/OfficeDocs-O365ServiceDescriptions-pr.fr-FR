---
title: Réseau
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 prend en charge les fonctionnalités de mise en réseau suivantes.
ms.openlocfilehash: f2343872faac2b1b289c37b8dc91240fa030482d
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262897"
---
# <a name="networking"></a><span data-ttu-id="aa7ab-103">Réseau</span><span class="sxs-lookup"><span data-stu-id="aa7ab-103">Networking</span></span>

<span data-ttu-id="aa7ab-104">Microsoft Office 365 prend en charge les fonctionnalités de mise en réseau suivantes.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="aa7ab-105">Ports, protocoles et adresses IP</span><span class="sxs-lookup"><span data-stu-id="aa7ab-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="aa7ab-p101">Office 365 utilise des adresses IPv4 et IPv6. L'utilisation des adresses IPv6 est facultative et non obligatoire pour la connexion à Office 365. Les fonctionnalités Office 365 ne sont pas toutes pleinement activées si vous utilisez IPv6. Pour plus d'informations sur la prise en charge d'IPv6 dans Office 365, consultez la rubrique [Prise en charge du protocole IPv6 dans les services Office 365](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span><span class="sxs-lookup"><span data-stu-id="aa7ab-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="aa7ab-p102">Office 365 conserve une liste d'adresses IP autorisées dans l'aide Office 365. Pour plus d'informations, voir [URL et plages d'adresses IP Office 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Pour Office 365 géré par 21Vianet, voir [URL et adresses IP pour Office 365 géré par 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Pour Office 365 Germany, voir [Points de terminaison Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span><span class="sxs-lookup"><span data-stu-id="aa7ab-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="aa7ab-p103">Nous vous recommandons fortement d'activer le routage vers les noms de domaines racine répertoriés dans l'article mentionné ci-dessus (comme \*.Outlook.com, \*.MicrosoftOnline.com et \*.SharePoint.com), au lieu de procéder au routage vers des sous-réseaux d'adresses IP spécifiques. Le fait d'utiliser des sous-réseaux d'adresses IP risque d'entraîner des temps d'indisponibilité pour vos utilisateurs lors de l'apport de modifications.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="aa7ab-116">Bande passante requise</span><span class="sxs-lookup"><span data-stu-id="aa7ab-116">Bandwidth requirements</span></span>

<span data-ttu-id="aa7ab-117">Pour plus d'informations sur la configuration de bande passante requise, consultez [Planification de bande passante Internet](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span><span class="sxs-lookup"><span data-stu-id="aa7ab-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="aa7ab-118">Connexion à Office 365</span><span class="sxs-lookup"><span data-stu-id="aa7ab-118">Connecting to Office 365</span></span>

<span data-ttu-id="aa7ab-119">Toutes les connexions à Office 365 sont réalisées sur l’Internet public ou sur une connexion Azure ExpressRoute privée, et sont sécurisées par le protocole SSL, selon le cas.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-119">All Connections to Office 365 are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="aa7ab-120">Azure ExpressRoute permet de se connecter directement au réseau Microsoft Global, en ignorant Internet.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="aa7ab-121">Un partenaire de mise en réseau Microsoft fournit la connectivité au réseau Microsoft global.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="aa7ab-122">Pour plus d'informations sur Azure ExpressRoute, consultez la rubrique [Azure ExpressRoute pour Office 365](https://aka.ms/expressrouteoffice365).</span><span class="sxs-lookup"><span data-stu-id="aa7ab-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="aa7ab-123">Accélérateurs de WAN</span><span class="sxs-lookup"><span data-stu-id="aa7ab-123">WAN accelerators</span></span>

<span data-ttu-id="aa7ab-p105">Microsoft ne prend pas en charge l'accélération de réseaux étendus (WAN) et d'appareils de mise en cache détenus par les clients avec Office 365. Si vous décidez d'utiliser un contrôleur d'optimisation de WAN en vue d'augmenter les performances dans des conditions de latence élevée ou de faible bande passante, vous devrez le désactiver pendant la résolution des demandes de service avec Microsoft, et travailler avec votre fournisseur d'appareils pour toute assistance relative à ces appareils. Pour plus d'informations, consultez la rubrique [Accélération de réseaux étendus (WAN) et dispositifs de mise en cache avec Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span><span class="sxs-lookup"><span data-stu-id="aa7ab-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="aa7ab-127">Réseau Microsoft mondial</span><span class="sxs-lookup"><span data-stu-id="aa7ab-127">The global Microsoft network</span></span>

<span data-ttu-id="aa7ab-128">L'infrastructure réseau Office 365 se compose d'un large portefeuille mondial de centres de données, serveurs, réseaux de distribution de contenu, nœuds périphériques et réseaux à fibre optique qui fournit une distribution internationale de services.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-128">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="aa7ab-129">L'instrumentation et le suivi avancés des services s'intègrent au plus haut niveau avec chaque composant, offrant une excellente visibilité sur le centre de données, la dorsale principale des réseaux, les échanges Internet et au-delà, afin de contribuer à la détection, au diagnostic et à la gestion des causes des perturbations qui surviennent.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="aa7ab-130">Le réseau est conçu de manière à maintenir une capacité suffisante, même en cas d'interruptions de réseau à grande échelle, sans aucune dégradation des performances.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="aa7ab-131">Pour plus d’informations, consultez la rubrique [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span><span class="sxs-lookup"><span data-stu-id="aa7ab-131">For more information, see [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="aa7ab-p107">Pour assurer la confidentialité et l'intégrité des données des clients, Microsoft garde les réseaux de services client séparés des réseaux Office 365. Plusieurs techniques sont utilisées pour contrôler les flux d'informations, y compris, mais sans s'y limiter :</span><span class="sxs-lookup"><span data-stu-id="aa7ab-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="aa7ab-p108">Séparation physique. Des segments réseau sont physiquement séparés par des routeurs qui sont configurés de manière à empêcher tout motif récurrent de communication spécifique.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="aa7ab-p109">Séparation logique. La technologie de réseau local virtuel (VLAN) est utilisée pour séparer encore davantage les communications.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="aa7ab-138">Pare-feu.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-138">Firewalls.</span></span> <span data-ttu-id="aa7ab-139">Les pare-feu et autres points d’application de la sécurité réseau sont utilisés pour limiter les échanges de données avec les systèmes exposés à Internet et pour isoler les systèmes des systèmes principaux gérés par Microsoft.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="aa7ab-140">Restrictions de protocole.</span><span class="sxs-lookup"><span data-stu-id="aa7ab-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="aa7ab-141">Pour plus d'informations, rendez-vous dans le [Centre de gestion de la confidentialité Office 365](https://www.microsoft.com/trust-center).</span><span class="sxs-lookup"><span data-stu-id="aa7ab-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="aa7ab-142">Disponibilité des fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="aa7ab-142">Feature availability</span></span>

<span data-ttu-id="aa7ab-143">Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, voir [Description du service de plateforme office 365](office-365-platform-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="aa7ab-143">To view feature availability across Office 365 plans, see [Office 365 platform service description](office-365-platform-service-description.md).</span></span>
  

