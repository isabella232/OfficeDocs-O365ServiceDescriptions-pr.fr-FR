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
ms.openlocfilehash: fe1d1f5a58012498e5b0f71c9a4299e61a4456ad
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173389"
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
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).
    
- Réinitialisation du code confidentiel de la messagerie vocale à partir d'Outlook Web App et d'Outlook (voir la rubrique [Réinitialiser un code confidentiel de la messagerie vocale ](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online)). 
    
- Règles de répondeurs d’appel (voir [Autoriser les utilisateurs](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) de messagerie vocale à envoyer des appels pour plus d’informations).
    
- Messagerie vocale protégée dans Exchange Online (pour plus d’informations, voir Protéger la messagerie vocale [dans Exchange Online).](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail)
    
- Aperçu de messagerie vocale (voir [Autoriser les utilisateurs à](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) voir une transcription de messagerie vocale pour une liste des langues pris en charge).
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Accès vocal au courrier électronique, à la messagerie vocale, au calendrier, aux contacts personnels et aux groupes de contacts personnels.
    
- Recherche dans l'annuaire via Outlook Voice Access ou un standard automatique
    
Pour plus d’informations sur les fonctionnalités de messagerie vocale, [consultez la messagerie vocale dans Exchange Online.](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging)
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. 
>
> Le client doit fournir une connexion téléphonique à partir du réseau téléphonique commuté (PSTN) à l’aide d’une passerelle VoIP et d’un PBX, d’un PBX IP ou de Skype Entreprise Server 2015. 
>
> Le client doit fournir les contrôleurs de frontière de session (SBC) et vérifier qu'ils sont correctement configurés pour se connecter aux services de messagerie vocale en ligne. Cela comprend le niveau correct de sécurité en utilisant des certificats et des interfaces IP publiques et privées et en activant les ports TCP corrects avec leurs pare-feu sur site. 
>
> La messagerie vocale hébergée est disponible uniquement pour les abonnés à Exchange Online Plan 2 et Office 365 Entreprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interopérabilité avec messagerie vocale tierce

Interopérabilité avec messagerie vocale tierce
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Intégration Skype Entreprise

Les organisations peuvent acheter Skype Entreprise Online en tant que service autonome ou composant de Microsoft Office 365. Skype Entreprise 2015 local est également pris en charge. Pour en savoir plus sur Skype Entreprise Online, consultez la [description du service Skype Entreprise Online.](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, consultez la [description du service Exchange Online.](exchange-online-service-description.md)
