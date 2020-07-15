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
# <a name="voice-message-services"></a>Services de messagerie vocale

## <a name="voice-mail"></a>Messagerie vocale

Microsoft Exchange Online offre des services hébergés de messagerie vocale :
  
- Microsoft Exchange Online offre des services hébergés de messagerie vocale :
    
- Répondeur automatique (répondeur)
    
- Interface utilisateur de connexion Exchange (Outlook Voice Access)
    
Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.
  
The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:
  
- Les fonctionnalités des services de messagerie vocale disponibles dans Exchange Online sont similaires à celles offertes par une installation locale d'Exchange Server 2013 . Elles sont les suivantes :
    
- Lecture sur téléphone à partir d'Outlook et d"Outlook Web App
    
- Notifications d'appels en absence.
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
- Réinitialisation du code confidentiel de la messagerie vocale à partir d'Outlook Web App et d'Outlook (voir la rubrique [Réinitialiser un code confidentiel de la messagerie vocale ](https://go.microsoft.com/fwlink/p/?LinkId=271794)). 
    
- Règles de répondeur automatique (consultez la rubrique [autoriser les utilisateurs de messagerie vocale à transférer des appels](https://go.microsoft.com/fwlink/p/?LinkId=271795) pour plus de détails).
    
- Messagerie vocale protégée dans Exchange Online (pour plus d’informations, consultez la rubrique [protection de la messagerie vocale dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) ).
    
- Aperçu de messagerie vocale (voir [la rubrique autoriser les utilisateurs à voir la transcription de la messagerie vocale](https://go.microsoft.com/fwlink/p/?LinkId=271797) pour obtenir la liste des langues prises en charge).
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Accès vocal au courrier électronique, à la messagerie vocale, au calendrier, aux contacts personnels et aux groupes de contacts personnels.
    
- Recherche dans l'annuaire via Outlook Voice Access ou un standard automatique
    
Pour plus d’informations sur les fonctionnalités de messagerie vocale, consultez la rubrique [messagerie vocale dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. 
>
> Le client doit fournir une connexion téléphonique à partir du réseau téléphonique commuté (RTC) à l’aide d’une passerelle VoIP et d’un PBX, d’un PBX IP ou de Skype entreprise Server 2015. 
>
> The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. 
>
> La messagerie vocale hébergée est uniquement disponible pour les abonnés à Exchange Online plan 2 et Office 365 entreprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interopérabilité avec messagerie vocale tierce

On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Intégration Skype Entreprise

Les organisations peuvent acheter Skype Entreprise Online en tant que service autonome ou composant de Microsoft Office 365. Skype entreprise 2015 en local est également pris en charge. Pour en savoir plus sur Skype entreprise Online, reportez-vous à la rubrique [Description du service Skype entreprise Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  

