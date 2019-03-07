---
title: Services de messagerie vocale
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 3879252927a26f47cd5d92f0fbcfbdecf4466c2a
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467921"
---
# <a name="voice-message-services"></a>Services de messagerie vocale

## <a name="voice-mail"></a>Messagerie vocale

Microsoft Exchange Online offre des services hébergés de messagerie vocale :
  
- Microsoft Exchange Online offre des services hébergés de messagerie vocale :
    
- Répondeur automatique (répondeur)
    
- Interface utilisateur de connexion Exchange (Outlook Voice Access)
    
Interface de numérotation pour les appelants (standard automatique)
  
Les services hébergés de messagerie vocale permettent à une société de connecter son système téléphonique sur site à des services de messagerie vocale Exchange Online. Les messages vocaux sont enregistrés et conservés dans l'infrastructure Exchange Online, ce qui permet aux utilisateurs d'y accéder à partir d'Outlook, d'Outlook Web Access ou d'un téléphone mobile. Toutes les connexions téléphoniques vers Exchange Online nécessitent les protocoles de voix sur IP (VoIP). Les administrateurs peuvent connecter des PBX IP sur site ou des systèmes téléphoniques PBX en utilisant des passerelles multimédias VoIP et des contrôleurs de frontière de session (SBC) vers Exchange Online. Une passerelle multimédia VoIP n'est pas indispensable si le client a déployé un PBX IP ou si un PBX prend directement en charge le protocole VoIP et est compatible avec les services de messagerie vocale Exchange. Les contrôleurs de frontière de session (SBC) sont déployés dans le périmètre du réseau du client pour connecter un réseau téléphonique sur site et protéger les communications (et le réseau du client) contre les écoutes et les intrusions. L'interopérabilité avec les fonctionnalités vocales de Microsoft Lync Server 2010 et 2013 est également prise en charge.
  
- Les fonctionnalités des services de messagerie vocale disponibles dans Exchange Online sont similaires à celles offertes par une installation locale d'Exchange Server 2013 . Elles sont les suivantes :
    
- Lecture sur téléphone à partir d'Outlook et d"Outlook Web App
    
- Notifications d'appels en absence.
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
- Réinitialisation du code confidentiel de la messagerie vocale à partir d'Outlook Web App et d'Outlook (voir la rubrique [Réinitialiser un code confidentiel de la messagerie vocale ](https://go.microsoft.com/fwlink/p/?LinkId=271794)). 
    
- Indicateur de message en attente (pour plus de détails, voir la rubrique [MWI dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271795)). 
    
- Règles de répondeur automatique (pour plus de détails, voir la rubrique [Permettre à des utilisateurs de messagerie vocale de transférer des appels ](https://go.microsoft.com/fwlink/p/?LinkId=271796)). 
    
- Messagerie vocale protégée dans Exchange Online (pour plus de détails, voir la rubrique [Protection de la messagerie vocale dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271797)). 
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Accès vocal au courrier électronique, à la messagerie vocale, au calendrier, aux contacts personnels et aux groupes de contacts personnels.
    
- Recherche dans l'annuaire via Outlook Voice Access ou un standard automatique
    
For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interopérabilité avec messagerie vocale tierce

Interopérabilité avec messagerie vocale tierce
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) for more information. 
  
## <a name="skype-for-business-integration"></a>Intégration Skype Entreprise

Les organisations peuvent acheter Skype Entreprise Online en tant que service autonome ou composant de Microsoft Office 365. Pour plus d'informations sur Skype Entreprise Online, consultez la rubrique [Description du service Skype Entreprise Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).
  

