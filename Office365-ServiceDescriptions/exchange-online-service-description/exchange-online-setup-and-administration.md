---
title: Configuration et administration d’Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: "Cette section décrit les contrôles d'administration et la prise en charge disponibles pour personnaliser les paramètres Exchange Online et maintenir à jour l'environnement Exchange Online d'une organisation. Elle comprend les informations sur les outils d'administration en libre-service et les fonctionnalités à disposition des organisations : responsabilités et engagements de performances de l'administrateur Microsoft et mises à niveau des services et des produits."
ms.openlocfilehash: 45707cbba47af8076312049686cb01beb6825d9e
ms.sourcegitcommit: de7d615d8967b1acc98a077337a0a2939c782481
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/29/2019
ms.locfileid: "30955743"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="dc863-104">Configuration et administration d’Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="dc863-105">Cette section décrit les contrôles d'administration et la prise en charge disponibles pour personnaliser les paramètres Exchange Online et maintenir à jour l'environnement Exchange Online d'une organisation.</span><span class="sxs-lookup"><span data-stu-id="dc863-105">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="dc863-106">Elle comprend les informations sur les outils d'administration en libre-service et les fonctionnalités à disposition des organisations : responsabilités et engagements de performances de l'administrateur Microsoft et mises à niveau des services et des produits.</span><span class="sxs-lookup"><span data-stu-id="dc863-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="dc863-107">Outils d'administration en libre-service</span><span class="sxs-lookup"><span data-stu-id="dc863-107">Self-service administration tools</span></span>

<span data-ttu-id="dc863-p103">Bien que Microsoft contrôle directement tous les Exchange Online centres de données et soit responsable des performances globales du système, il contrôle uniquement une partie des éléments réunis pour l'utilisation totale d'Office 365. Les organisations elles-mêmes sont responsables des connexions réseau aux centres de données, au réseau étendu (WAN) du client et aux réseaux locaux (LAN) du client. En outre, elles sont en charge des périphériques utilisateur et de leur configuration. Elles sont également responsables de la gestion des licences requises par utilisateur pour les fonctionnalités voulues, y compris, mais sans s'y limiter, la possibilité de gérer ces dernières, tant que l'utilisateur doit y avoir accès.</span><span class="sxs-lookup"><span data-stu-id="dc863-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="dc863-112">Exchange Online offre donc aux administrateurs du client les outils décrits ci-dessous pour gérer diverses tâches concernant la messagerie :</span><span class="sxs-lookup"><span data-stu-id="dc863-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="dc863-113">Portail Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="dc863-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="dc863-114">Centre d'administration Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="dc863-114">Microsoft 365 admin center</span></span>](#microsoft-365-admin-center)
    
- [<span data-ttu-id="dc863-115">Centre d'administration Exchange</span><span class="sxs-lookup"><span data-stu-id="dc863-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="dc863-116">Windows PowerShell distant pour Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="dc863-117">Portail Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="dc863-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="dc863-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="dc863-118"></span></span>

<span data-ttu-id="dc863-119">Le portail Microsoft Office 365 ([https://portal.office.com](https://portal.office.com)) est le site web sur lequel les administrateurs et les partenaires peuvent acheter et gérer les services Office 365 et où les utilisateurs peuvent accéder aux outils de collaboration Office 365.</span><span class="sxs-lookup"><span data-stu-id="dc863-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="dc863-120">Centre d'administration Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="dc863-120">Microsoft 365 admin center</span></span>
<span data-ttu-id="dc863-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="dc863-121"></span></span>

<span data-ttu-id="dc863-122">Le centre d'administration Microsoft 365 est le portail Web à partir duquel les administrateurs de services de chaque entreprise peuvent gérer les comptes d'utilisateur et les paramètres de chaque service Office 365 auquel ils s'abonnent.</span><span class="sxs-lookup"><span data-stu-id="dc863-122">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe.</span></span> <span data-ttu-id="dc863-123">À partir du centre d'administration 365 de Microsoft, les administrateurs peuvent suivre des liens vers le centre d'administration Exchange, où ils peuvent gérer des paramètres spécifiques d'Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="dc863-123">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="dc863-124">Pour plus d'informations sur l'utilisation du centre d'administration Microsoft 365, voir la vidéo suivante: [présentation d'Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span><span class="sxs-lookup"><span data-stu-id="dc863-124">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="dc863-125">Centre d’administration Exchange</span><span class="sxs-lookup"><span data-stu-id="dc863-125">Exchange admin center</span></span>
<span data-ttu-id="dc863-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="dc863-126"></span></span>

<span data-ttu-id="dc863-p105">Exchange Online offre une console de gestion unifiée et unique qui facilite l'utilisation et optimise la gestion des déploiements sur site, en ligne ou hybrides. Dans le Centre d'administration Exchange (CAE), les administrateurs peuvent gérer les paramètres spécifiques d'Exchange.</span><span class="sxs-lookup"><span data-stu-id="dc863-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="dc863-129">Pour plus d'informations sur l'utilisation du CAE pour gérer Exchange Online, consultez la rubrique [Centre d'administration Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span><span class="sxs-lookup"><span data-stu-id="dc863-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="dc863-130">Windows PowerShell distant pour Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="dc863-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="dc863-131"></span></span>

<span data-ttu-id="dc863-p106">L'application Windows PowerShell distante permet aux administrateurs de se connecter à Exchange Online pour effectuer des tâches de gestion indisponibles ou peu pratiques dans le CAE. Cela comprend la possibilité d'automatiser des tâches répétitives, d'extraire des données de rapports personnalisés, de personnaliser des stratégies et de connecter Exchange Online à une infrastructure et des processus existants. Pour plus d'informations, voir [Connexion à Exchange Online à l'aide de Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span><span class="sxs-lookup"><span data-stu-id="dc863-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="dc863-p107">Exchange Online utilise les mêmes cmdlets Windows PowerShell qu'Exchange Server 2013, avec cependant certaines commandes et paramètres indisponibles du fait que ces fonctionnalités ne sont pas applicables dans Exchange Online. Pour la liste des cmdlets utilisables avec Exchange Online, consultez la rubrique relative aux [cmdlets Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="dc863-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="dc863-p108">Les administrateurs n'ont pas besoin d'installer d'outils de gestion ou de migration Exchange Server pour utiliser Remote Windows PowerShell. Cependant, les ordinateurs des administrateurs doivent exécuter Windows Management Framework 3.0 qui contient Windows PowerShell v3 et WinRM 3.0, ainsi que Windows .NET Framework 4.5. Ces composants sont déjà installés sur des ordinateurs exécutant Windows 8 ou Windows Server 2012. Les administrateurs peuvent télécharger manuellement ces composants pour des ordinateurs exécutant Windows 7 ou Windows Server 2008 R2.</span><span class="sxs-lookup"><span data-stu-id="dc863-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="dc863-141">Pour éviter les attaques par déni de service, vous êtes limité à trois connexions Windows PowerShell ouvertes à votre organisation Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="dc863-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="dc863-142">Fonctionnalités en libre-service pour Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="dc863-p109">Des fonctionnalités importantes disponibles pour gérer Exchange Online en utilisant le CAE, l'application Windows PowerShell distante et d'autres outils figurent ci-après. Ces outils permettent également de contrôler de nombreux autres paramètres comme l'expose ce document.</span><span class="sxs-lookup"><span data-stu-id="dc863-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="dc863-145">Stratégies de sécurité des appareils mobiles pour Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="dc863-p110">Exchange Online prend en charge les mêmes stratégies ActiveSync pour les périphériques mobiles qu'Exchange Server 2013. Les administrateurs peuvent appliquer et personnaliser ces stratégies de sécurité pour des utilisateurs et des groupes spécifiques en utilisant le CAE ou l'application Windows PowerShell distante.</span><span class="sxs-lookup"><span data-stu-id="dc863-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="dc863-148">Suivi des messages pour Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="dc863-149">Le suivi des messages au moyen des rapports de remise est décrit dans les rubriques suivantes : [Fonctions de rapport et outils de dépannage](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="dc863-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="dc863-150">Création de rapports d’utilisation pour Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="dc863-p111">Les administrateurs peuvent utiliser Remote Windows PowerShell pour récupérer des informations sur la façon dont les personnes de leurs organisations utilisent le service Exchange Online. Les informations suivantes sont disponibles :</span><span class="sxs-lookup"><span data-stu-id="dc863-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="dc863-153">Affichage de la taille de la boîte aux lettres de chaque utilisateur dans l'organisation.</span><span class="sxs-lookup"><span data-stu-id="dc863-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="dc863-154">Affichage des autorisations personnalisées définies pour les boîtes aux lettres telles que l'accès délégué.</span><span class="sxs-lookup"><span data-stu-id="dc863-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="dc863-155">Extraction de données sur l'accès des périphériques mobiles, par exemple les utilisateurs qui se connectent par Exchange ActiveSync, les périphériques qu'ils utilisent et le moment de leur dernière connexion.</span><span class="sxs-lookup"><span data-stu-id="dc863-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="dc863-p112">Les cmdlets Remote Windows PowerShell commençant par "get-" peuvent rechercher des données dans le système Exchange Online. Les administrateurs peuvent exporter ces informations à partir de Windows PowerShell au format .csv pour effectuer des analyses ou des rapports sophistiqués.</span><span class="sxs-lookup"><span data-stu-id="dc863-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="dc863-158">Pour plus d'informations sur les cmdlets Windows PowerShell utilisables avec Exchange Online, consultez la rubrique [Cmdlets Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="dc863-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="dc863-159">Audit dans Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="dc863-160">L'enregistrement d'audit est décrit dans la rubrique : [Fonctions de rapport et outils de dépannage](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="dc863-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="dc863-161">Mises à niveau des produits et services pour Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc863-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="dc863-p113">Les clients Exchange Online bénéficient de mises à niveau régulières avec les dernières technologies Exchange, y compris les nouvelles versions Exchange Server. Ces mises à niveau gratuites garantissent que les clients utilisent toujours le logiciel Exchange le plus récent.</span><span class="sxs-lookup"><span data-stu-id="dc863-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="dc863-164">Lorsque Microsoft publie une version majeure d'Exchange, les clients disposent de 12 mois pour mettre à niveau leur service avec cette nouvelle version.</span><span class="sxs-lookup"><span data-stu-id="dc863-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="dc863-165">Disponibilité des fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="dc863-165">Feature Availability</span></span>

<span data-ttu-id="dc863-166">Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="dc863-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

