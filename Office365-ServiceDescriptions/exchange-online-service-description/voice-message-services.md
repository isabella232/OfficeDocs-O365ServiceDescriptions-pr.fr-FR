---
title: Services de messagerie vocale
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: a6245acdeaeda173f1a675d1ce34d9086e3f077a
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132548"
---
# <a name="voice-message-services"></a><span data-ttu-id="305c2-102">Services de messagerie vocale</span><span class="sxs-lookup"><span data-stu-id="305c2-102">Voice message services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="305c2-103">Messagerie vocale</span><span class="sxs-lookup"><span data-stu-id="305c2-103">Voice mail</span></span>

<span data-ttu-id="305c2-104">Microsoft Exchange Online offre des services hébergés de messagerie vocale :</span><span class="sxs-lookup"><span data-stu-id="305c2-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="305c2-105">Microsoft Exchange Online offre des services hébergés de messagerie vocale :</span><span class="sxs-lookup"><span data-stu-id="305c2-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="305c2-106">Répondeur automatique (répondeur)</span><span class="sxs-lookup"><span data-stu-id="305c2-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="305c2-107">Interface utilisateur de connexion Exchange (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="305c2-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="305c2-108">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="305c2-108">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online.</span></span> <span data-ttu-id="305c2-109">Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones.</span><span class="sxs-lookup"><span data-stu-id="305c2-109">Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones.</span></span> <span data-ttu-id="305c2-110">All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols.</span><span class="sxs-lookup"><span data-stu-id="305c2-110">All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols.</span></span> <span data-ttu-id="305c2-111">Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="305c2-111">Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online.</span></span> <span data-ttu-id="305c2-112">A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services.</span><span class="sxs-lookup"><span data-stu-id="305c2-112">A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services.</span></span> <span data-ttu-id="305c2-113">SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion.</span><span class="sxs-lookup"><span data-stu-id="305c2-113">SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion.</span></span> <span data-ttu-id="305c2-114">Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span><span class="sxs-lookup"><span data-stu-id="305c2-114">Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="305c2-115">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016.</span><span class="sxs-lookup"><span data-stu-id="305c2-115">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016.</span></span> <span data-ttu-id="305c2-116">These include:</span><span class="sxs-lookup"><span data-stu-id="305c2-116">These include:</span></span>
  
- <span data-ttu-id="305c2-117">Les fonctionnalités des services de messagerie vocale disponibles dans Exchange Online sont similaires à celles offertes par une installation locale d'Exchange Server 2013 . Elles sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="305c2-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="305c2-118">Lecture sur téléphone à partir d'Outlook et d"Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="305c2-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="305c2-119">Notifications d'appels en absence.</span><span class="sxs-lookup"><span data-stu-id="305c2-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="305c2-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span><span class="sxs-lookup"><span data-stu-id="305c2-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="305c2-121">Réinitialisation du code confidentiel de la messagerie vocale à partir d'Outlook Web App et d'Outlook (voir la rubrique [Réinitialiser un code confidentiel de la messagerie vocale ](https://go.microsoft.com/fwlink/p/?LinkId=271794)).</span><span class="sxs-lookup"><span data-stu-id="305c2-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="305c2-122">Règles de répondeur automatique (consultez la rubrique [autoriser les utilisateurs de messagerie vocale à transférer des appels](https://go.microsoft.com/fwlink/p/?LinkId=271795) pour plus de détails).</span><span class="sxs-lookup"><span data-stu-id="305c2-122">Call answering rules (see [Allow voice mail users to forward calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span>
    
- <span data-ttu-id="305c2-123">Messagerie vocale protégée dans Exchange Online (pour plus d’informations, consultez la rubrique [protection de la messagerie vocale dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) ).</span><span class="sxs-lookup"><span data-stu-id="305c2-123">Protected voice mail in Exchange Online (see [Protect voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span>
    
- <span data-ttu-id="305c2-124">Aperçu de messagerie vocale (voir [la rubrique autoriser les utilisateurs à voir la transcription de la messagerie vocale](https://go.microsoft.com/fwlink/p/?LinkId=271797) pour obtenir la liste des langues prises en charge).</span><span class="sxs-lookup"><span data-stu-id="305c2-124">Voice mail preview (see [Allow users to see a voice mail transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span>
    
- <span data-ttu-id="305c2-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span><span class="sxs-lookup"><span data-stu-id="305c2-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="305c2-126">Accès vocal au courrier électronique, à la messagerie vocale, au calendrier, aux contacts personnels et aux groupes de contacts personnels.</span><span class="sxs-lookup"><span data-stu-id="305c2-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="305c2-127">Recherche dans l'annuaire via Outlook Voice Access ou un standard automatique</span><span class="sxs-lookup"><span data-stu-id="305c2-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="305c2-128">Pour plus d’informations sur les fonctionnalités de messagerie vocale, consultez la rubrique [messagerie vocale dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span><span class="sxs-lookup"><span data-stu-id="305c2-128">For more information about voice mail features, see [Voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="305c2-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span><span class="sxs-lookup"><span data-stu-id="305c2-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span></span> 
>
> <span data-ttu-id="305c2-130">Le client doit fournir une connexion téléphonique à partir du réseau téléphonique commuté (RTC) à l’aide d’une passerelle VoIP et d’un PBX, d’un PBX IP ou de Skype entreprise Server 2015.</span><span class="sxs-lookup"><span data-stu-id="305c2-130">The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015.</span></span> 
>
> <span data-ttu-id="305c2-131">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services.</span><span class="sxs-lookup"><span data-stu-id="305c2-131">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services.</span></span> <span data-ttu-id="305c2-132">This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span><span class="sxs-lookup"><span data-stu-id="305c2-132">This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span></span> 
>
> <span data-ttu-id="305c2-133">La messagerie vocale hébergée est uniquement disponible pour les abonnés à Exchange Online plan 2 et Office 365 entreprise E3.</span><span class="sxs-lookup"><span data-stu-id="305c2-133">Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="305c2-134">Interopérabilité avec messagerie vocale tierce</span><span class="sxs-lookup"><span data-stu-id="305c2-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="305c2-135">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services.</span><span class="sxs-lookup"><span data-stu-id="305c2-135">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services.</span></span> <span data-ttu-id="305c2-136">If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP.</span><span class="sxs-lookup"><span data-stu-id="305c2-136">If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP.</span></span> <span data-ttu-id="305c2-137">Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="305c2-137">Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="305c2-138">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018.</span><span class="sxs-lookup"><span data-stu-id="305c2-138">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018.</span></span> <span data-ttu-id="305c2-139">Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span><span class="sxs-lookup"><span data-stu-id="305c2-139">Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="305c2-140">Intégration Skype Entreprise</span><span class="sxs-lookup"><span data-stu-id="305c2-140">Skype for Business integration</span></span>

<span data-ttu-id="305c2-141">Les organisations peuvent acheter Skype Entreprise Online en tant que service autonome ou composant de Microsoft Office 365.</span><span class="sxs-lookup"><span data-stu-id="305c2-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="305c2-142">Skype entreprise 2015 en local est également pris en charge.</span><span class="sxs-lookup"><span data-stu-id="305c2-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="305c2-143">Pour en savoir plus sur Skype entreprise Online, reportez-vous à la rubrique [Description du service Skype entreprise Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="305c2-143">To learn more about Skype for Business Online, see [Skype for Business Online service description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="305c2-144">Disponibilité des fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="305c2-144">Feature availability</span></span>

<span data-ttu-id="305c2-145">Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="305c2-145">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

