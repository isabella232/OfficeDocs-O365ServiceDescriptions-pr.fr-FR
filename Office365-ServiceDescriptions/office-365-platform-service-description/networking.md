---
title: Réseau
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft prend en charge les fonctionnalités réseau suivantes.
ms.openlocfilehash: 63222b4554ed6abc9c20392061359bf849ca6518
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59673078"
---
# <a name="networking"></a>Mise en réseau

Microsoft prend en charge les fonctionnalités réseau suivantes.
  
## <a name="ports-protocols-and-ip-addresses"></a>Ports, protocoles et adresses IP

Microsoft utilise les adresses IPv4 et IPv6. L'utilisation des adresses IPv6 est facultative et non obligatoire pour la connexion à Office 365. Les fonctionnalités Microsoft 365 ne sont pas toutes entièrement activées à l’aide d’IPv6. Pour plus d’informations sur la prise en charge d’Ipv6, voir la prise en charge [d’IPv6 dans services Microsoft](/office365/enterprise/ipv6-support).
  
Microsoft conserve une liste d’adresses IP autorisées dans l’aide de Microsoft. Pour plus d’informations, [voir URL et plages d’adresses IP.](/office365/enterprise/urls-and-ip-address-ranges) Pour Office 365 géré par 21Vianet, voir [URL et adresses IP pour Office 365 géré par 21Vianet](/office365/enterprise/managing-office-365-endpoints). Pour Office 365 Germany, voir [Points de terminaison Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Nous vous recommandons fortement d'activer le routage vers les noms de domaines racine répertoriés dans l'article mentionné ci-dessus (comme \*.Outlook.com, \*.MicrosoftOnline.com et \*.SharePoint.com), au lieu de procéder au routage vers des sous-réseaux d'adresses IP spécifiques. Le fait d'utiliser des sous-réseaux d'adresses IP risque d'entraîner des temps d'indisponibilité pour vos utilisateurs lors de l'apport de modifications. 
  
## <a name="bandwidth-requirements"></a>Bande passante requise

Pour plus d'informations sur la configuration de bande passante requise, consultez [Planification de bande passante Internet](/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Connexion à Microsoft

Toutes les connexions à Microsoft sont réalisées via Internet public ou via une connexion Azure ExpressRoute privée et sont sécurisées par SSL, selon le cas. Azure ExpressRoute permet de se connecter directement au réseau Microsoft global, en contournant Internet. Un partenaire de mise en réseau Microsoft fournit la connectivité au réseau Microsoft global.
  
Pour plus d'informations sur Azure ExpressRoute, consultez la rubrique [Azure ExpressRoute pour Office 365](/microsoft-365/enterprise/azure-expressroute).
  
### <a name="wan-accelerators"></a>Accélérateurs de WAN

Microsoft ne prend pas en charge l'accélération de réseaux étendus (WAN) et d'appareils de mise en cache détenus par les clients avec Office 365. Si vous décidez d'utiliser un contrôleur d'optimisation de WAN en vue d'augmenter les performances dans des conditions de latence élevée ou de faible bande passante, vous devrez le désactiver pendant la résolution des demandes de service avec Microsoft, et travailler avec votre fournisseur d'appareils pour toute assistance relative à ces appareils. Pour plus d'informations, consultez la rubrique [Accélération de réseaux étendus (WAN) et dispositifs de mise en cache avec Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Réseau Microsoft mondial

L’infrastructure réseau Microsoft se compose d’un large portefeuille global de centres de données, de serveurs, de réseaux de distribution de contenu, de serveurs edge computing et de réseaux de fibre optique pour fournir une distribution globale des services. L'instrumentation et le suivi avancés des services s'intègrent au plus haut niveau avec chaque composant, offrant une excellente visibilité sur le centre de données, la dorsale principale des réseaux, les échanges Internet et au-delà, afin de contribuer à la détection, au diagnostic et à la gestion des causes des perturbations qui surviennent. Le réseau est conçu de manière à maintenir une capacité suffisante, même en cas d'interruptions de réseau à grande échelle, sans aucune dégradation des performances. Pour plus d’informations, voir [Microsoft Global Network](/azure/networking/microsoft-global-network). 
  
Pour maintenir la confidentialité et l’intégrité des données client, Microsoft conserve les réseaux de services grand public séparés des réseaux Microsoft. Plusieurs techniques sont utilisées pour contrôler les flux d'informations, y compris, mais sans s'y limiter :
  
- Séparation physique. Des segments réseau sont physiquement séparés par des routeurs qui sont configurés de manière à empêcher tout motif récurrent de communication spécifique.
    
- Séparation logique. La technologie de réseau local virtuel (VLAN) est utilisée pour séparer encore davantage les communications.
    
- Pare-feu. Les pare-feu et autres points d’application de la sécurité réseau sont utilisés pour limiter les échanges de données avec les systèmes exposés à Internet et pour isoler les systèmes des systèmes principaux gérés par Microsoft. 
    
- Restrictions de protocole.
    
Pour plus d'informations, rendez-vous dans le [Centre de gestion de la confidentialité Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les différents plans, voir [Microsoft 365 et Office 365 description du service de plateforme.](office-365-platform-service-description.md)
