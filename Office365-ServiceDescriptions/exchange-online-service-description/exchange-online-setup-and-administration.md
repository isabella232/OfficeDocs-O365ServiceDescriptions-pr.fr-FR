---
title: Configuration et administration d’Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: "Cet article décrit les contrôles d’administration et la prise en charge disponibles pour personnaliser les paramètres Exchange Online et maintenir à jour l’environnement Exchange Online d’une organisation. Elle comprend les informations sur les outils d'administration en libre-service et les fonctionnalités à disposition des organisations : responsabilités et engagements de performances de l'administrateur Microsoft et mises à niveau des services et des produits."
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132999"
---
# <a name="exchange-online-setup-and-administration"></a>Configuration et administration d’Exchange Online

Cet article décrit les contrôles d’administration et la prise en charge disponibles pour personnaliser les paramètres Exchange Online et maintenir à jour l’environnement Exchange Online d’une organisation. Elle comprend les informations sur les outils d'administration en libre-service et les fonctionnalités à disposition des organisations : responsabilités et engagements de performances de l'administrateur Microsoft et mises à niveau des services et des produits.
  
## <a name="self-service-administration-tools"></a>Outils d'administration en libre-service

Bien que Microsoft contrôle directement tous les centres de données Exchange Online et est responsable des performances globales du système, il ne peut contrôler qu’une partie des éléments qui se combinent pour fournir l’expérience totale pour les utilisateurs. Les organisations elles-mêmes sont responsables des connexions réseau aux centres de données, au réseau étendu (WAN) du client et aux réseaux locaux (LAN) du client. En outre, elles sont en charge des périphériques utilisateur et de leur configuration.Elles sont également responsables de la gestion des licences requises par utilisateur pour les fonctionnalités voulues, y compris, mais sans s'y limiter, la possibilité de gérer ces dernières, tant que l'utilisateur doit y avoir accès.
  
Exchange Online offre donc aux administrateurs du client les outils décrits ci-dessous pour gérer diverses tâches concernant la messagerie :
  
- [Portail Microsoft Office 365](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Centre d’administration Microsoft 365](#microsoft-365-admin-center)
    
- [Centre d'administration Exchange](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Windows PowerShell distant pour Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Portail Microsoft Office 365

Le portail Microsoft Office 365 ([https://portal.office.com](https://portal.office.com)) est le site web sur lequel les administrateurs et les partenaires peuvent acheter et gérer les services Office 365 et où les utilisateurs peuvent accéder aux outils de collaboration Office 365.
  
### <a name="microsoft-365-admin-center"></a>Centre d’administration Microsoft 365

Le centre d’administration Microsoft 365 est le portail Web à partir duquel les administrateurs de services de chaque entreprise peuvent gérer les comptes d’utilisateur et les paramètres de chacun des services Microsoft auxquels ils s’abonnent. À partir du centre d’administration 365 de Microsoft, les administrateurs peuvent suivre des liens vers le centre d’administration Exchange, où ils peuvent gérer des paramètres spécifiques d’Exchange Online. Pour plus d’informations sur l’utilisation du centre d’administration Microsoft 365, voir la vidéo suivante : [présentation d’Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).
  
### <a name="exchange-admin-center"></a>Centre d'administration Exchange

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
Pour plus d'informations sur l'utilisation du CAE pour gérer Exchange Online, consultez la rubrique [Centre d'administration Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Windows PowerShell distant pour Exchange Online

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> Pour éviter les attaques par déni de service, vous êtes limité à trois connexions Windows PowerShell ouvertes à votre organisation Exchange Online. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Fonctionnalités en libre-service pour Exchange Online

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Stratégies de sécurité des appareils mobiles pour Exchange Online

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Suivi des messages pour Exchange Online

Le suivi des messages via la fonctionnalité de rapports de remise est décrit dans la rubrique suivante : [Reporting features and Troubleshooting tools](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Création de rapports d’utilisation pour Exchange Online

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- Affichage de la taille de la boîte aux lettres de chaque utilisateur dans l'organisation.
    
- Affichage des autorisations personnalisées définies pour les boîtes aux lettres telles que l'accès délégué.
    
- Extraction de données sur l'accès des périphériques mobiles, par exemple les utilisateurs qui se connectent par Exchange ActiveSync, les périphériques qu'ils utilisent et le moment de leur dernière connexion.
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
Pour plus d'informations sur les cmdlets Windows PowerShell utilisables avec Exchange Online, consultez la rubrique [Cmdlets Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
### <a name="auditing-for-exchange-online"></a>Audit dans Exchange Online

La fonctionnalité de journalisation d’audit est décrite dans la rubrique suivante : [fonctionnalités de création de rapports et outils de dépannage](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Mises à niveau des produits et services pour Exchange Online

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
Lorsque Microsoft publie une version majeure d'Exchange, les clients disposent de 12 mois pour mettre à niveau leur service avec cette nouvelle version.
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  