---
title: Services de messagerie vocale
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 7087de4dbcc4955d8c66ce4b4a9c4c12e763aa38
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442559"
---
# <a name="voice-message-services"></a><span data-ttu-id="bc4b5-102">Services de messagerie vocale</span><span class="sxs-lookup"><span data-stu-id="bc4b5-102">Voice Message Services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="bc4b5-103">Messagerie vocale</span><span class="sxs-lookup"><span data-stu-id="bc4b5-103">Voice mail</span></span>

<span data-ttu-id="bc4b5-104">Microsoft Exchange Online offre des services hébergés de messagerie vocale :</span><span class="sxs-lookup"><span data-stu-id="bc4b5-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="bc4b5-105">Microsoft Exchange Online offre des services hébergés de messagerie vocale :</span><span class="sxs-lookup"><span data-stu-id="bc4b5-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="bc4b5-106">Répondeur automatique (répondeur)</span><span class="sxs-lookup"><span data-stu-id="bc4b5-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="bc4b5-107">Interface utilisateur de connexion Exchange (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="bc4b5-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="bc4b5-p101">Interface de numérotation pour les appelants (standard automatique)</span><span class="sxs-lookup"><span data-stu-id="bc4b5-p101">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="bc4b5-p102">Les services hébergés de messagerie vocale permettent à une société de connecter son système téléphonique sur site à des services de messagerie vocale Exchange Online. Les messages vocaux sont enregistrés et conservés dans l'infrastructure Exchange Online, ce qui permet aux utilisateurs d'y accéder à partir d'Outlook, d'Outlook Web Access ou d'un téléphone mobile. Toutes les connexions téléphoniques vers Exchange Online nécessitent les protocoles de voix sur IP (VoIP). Les administrateurs peuvent connecter des PBX IP sur site ou des systèmes téléphoniques PBX en utilisant des passerelles multimédias VoIP et des contrôleurs de frontière de session (SBC) vers Exchange Online. Une passerelle multimédia VoIP n'est pas indispensable si le client a déployé un PBX IP ou si un PBX prend directement en charge le protocole VoIP et est compatible avec les services de messagerie vocale Exchange. Les contrôleurs de frontière de session (SBC) sont déployés dans le périmètre du réseau du client pour connecter un réseau téléphonique sur site et protéger les communications (et le réseau du client) contre les écoutes et les intrusions. L'interopérabilité avec les fonctionnalités vocales de Microsoft Lync Server 2010 et 2013 est également prise en charge.</span><span class="sxs-lookup"><span data-stu-id="bc4b5-p102">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:</span></span>
  
- <span data-ttu-id="bc4b5-117">Les fonctionnalités des services de messagerie vocale disponibles dans Exchange Online sont similaires à celles offertes par une installation locale d'Exchange Server 2013 . Elles sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="bc4b5-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="bc4b5-118">Lecture sur téléphone à partir d'Outlook et d"Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="bc4b5-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="bc4b5-119">Notifications d'appels en absence.</span><span class="sxs-lookup"><span data-stu-id="bc4b5-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="bc4b5-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span><span class="sxs-lookup"><span data-stu-id="bc4b5-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="bc4b5-121">Réinitialisation du code confidentiel de la messagerie vocale à partir d'Outlook Web App et d'Outlook (voir la rubrique [Réinitialiser un code confidentiel de la messagerie vocale ](https://go.microsoft.com/fwlink/p/?LinkId=271794)).</span><span class="sxs-lookup"><span data-stu-id="bc4b5-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="bc4b5-122">Indicateur de message en attente (pour plus de détails, voir la rubrique [MWI dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271795)).</span><span class="sxs-lookup"><span data-stu-id="bc4b5-122">Call Answering Rules (see [Allow Voice Mail Users to Forward Calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span> 
    
- <span data-ttu-id="bc4b5-123">Règles de répondeur automatique (pour plus de détails, voir la rubrique [Permettre à des utilisateurs de messagerie vocale de transférer des appels ](https://go.microsoft.com/fwlink/p/?LinkId=271796)).</span><span class="sxs-lookup"><span data-stu-id="bc4b5-123">Protected Voice Mail in Exchange Online (see [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span> 
    
- <span data-ttu-id="bc4b5-124">Messagerie vocale protégée dans Exchange Online (pour plus de détails, voir la rubrique [Protection de la messagerie vocale dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271797)).</span><span class="sxs-lookup"><span data-stu-id="bc4b5-124">Voice Mail Preview (see [Allow Users to See a Voice Mail Transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span> 
    
- <span data-ttu-id="bc4b5-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span><span class="sxs-lookup"><span data-stu-id="bc4b5-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="bc4b5-126">Accès vocal au courrier électronique, à la messagerie vocale, au calendrier, aux contacts personnels et aux groupes de contacts personnels.</span><span class="sxs-lookup"><span data-stu-id="bc4b5-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="bc4b5-127">Recherche dans l'annuaire via Outlook Voice Access ou un standard automatique</span><span class="sxs-lookup"><span data-stu-id="bc4b5-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="bc4b5-128">For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span><span class="sxs-lookup"><span data-stu-id="bc4b5-128">For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="bc4b5-p103">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span><span class="sxs-lookup"><span data-stu-id="bc4b5-p103">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="bc4b5-134">Interopérabilité avec messagerie vocale tierce</span><span class="sxs-lookup"><span data-stu-id="bc4b5-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="bc4b5-p104">Interopérabilité avec messagerie vocale tierce</span><span class="sxs-lookup"><span data-stu-id="bc4b5-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="bc4b5-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span><span class="sxs-lookup"><span data-stu-id="bc4b5-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="bc4b5-140">Intégration Skype Entreprise</span><span class="sxs-lookup"><span data-stu-id="bc4b5-140">Skype for Business integration</span></span>

<span data-ttu-id="bc4b5-p106">Les organisations peuvent acheter Skype Entreprise Online en tant que service autonome ou composant de Microsoft Office 365. Pour plus d'informations sur Skype Entreprise Online, consultez la rubrique [Description du service Skype Entreprise Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="bc4b5-p106">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365. Skype for Business 2015 on-premises is also supported. To learn more about Skype for Business Online, see [Skype for Business Online Service Description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="bc4b5-144">Disponibilité des fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="bc4b5-144">Feature Availability</span></span>

<span data-ttu-id="bc4b5-145">Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="bc4b5-145">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

