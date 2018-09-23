---
title: Services de messagerie vocale
ms.author: pebaum
author: pebaum
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
ms.openlocfilehash: 98591e47ece7c59581824c6df375c41c66b7d2d1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035616"
---
# <a name="voice-message-services"></a>Services de messagerie vocale

## <a name="voice-mail"></a>Messagerie vocale

Microsoft Exchange Online offre des services hébergés de messagerie vocale :
  
- Répondeur automatique (répondeur)
    
- Interface utilisateur de connexion Exchange (Outlook Voice Access)
    
- Interface utilisateur de connexion Exchange (Outlook Voice Access)
    
Interface de numérotation pour les appelants (standard automatique)
  
Les services hébergés de messagerie vocale permettent à une société de connecter son système téléphonique sur site à des services de messagerie vocale Exchange Online. Les messages vocaux sont enregistrés et conservés dans l'infrastructure Exchange Online, ce qui permet aux utilisateurs d'y accéder à partir d'Outlook, d'Outlook Web Access ou d'un téléphone mobile. Toutes les connexions téléphoniques vers Exchange Online nécessitent les protocoles de voix sur IP (VoIP). Les administrateurs peuvent connecter des PBX IP sur site ou des systèmes téléphoniques PBX en utilisant des passerelles multimédias VoIP et des contrôleurs de frontière de session (SBC) vers Exchange Online. Une passerelle multimédia VoIP n'est pas indispensable si le client a déployé un PBX IP ou si un PBX prend directement en charge le protocole VoIP et est compatible avec les services de messagerie vocale Exchange. Les contrôleurs de frontière de session (SBC) sont déployés dans le périmètre du réseau du client pour connecter un réseau téléphonique sur site et protéger les communications (et le réseau du client) contre les écoutes et les intrusions. L'interopérabilité avec les fonctionnalités vocales de Microsoft Lync Server 2010 et 2013 est également prise en charge.
  
- Les fonctionnalités des services de messagerie vocale disponibles dans Exchange Online sont similaires à celles offertes par une installation locale d'Exchange Server 2013 . Elles sont les suivantes :
    
- Lecture sur téléphone à partir d'Outlook et d"Outlook Web App
    
- Notifications d'appels en absence.
    
- Réinitialisation à partir d’Outlook sur le web et d’Outlook (voir [Réinitialiser le code PIN messagerie vocale](https://go.microsoft.com/fwlink/p/?LinkId=286328)) du code confidentiel de messagerie vocale.
    
- Réinitialisation du code confidentiel de la messagerie vocale à partir d'Outlook Web App et d'Outlook (voir la rubrique [Réinitialiser un code confidentiel de la messagerie vocale ](https://go.microsoft.com/fwlink/p/?LinkId=271794)). 
    
- Règles de répondeur automatique (pour plus de détails, voir la rubrique [Permettre à des utilisateurs de messagerie vocale de transférer des appels ](https://go.microsoft.com/fwlink/p/?LinkId=271795)). 
    
- Messagerie vocale protégée dans Exchange Online (pour plus de détails, voir la rubrique [Protection de la messagerie vocale dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796)). 
    
- Aperçu de messagerie vocale (pour obtenir la liste des langues prises en charge, voir la rubrique relative à l'[autorisation pour les utilisateurs de voir la transcription des messages vocaux](https://go.microsoft.com/fwlink/p/?LinkId=271797)). 
    
- Accès vocal au courrier électronique, à la messagerie vocale, au calendrier, aux contacts personnels et aux groupes de contacts personnels.
    
- Recherche dans l'annuaire via Outlook Voice Access ou un standard automatique
    
- Les administrateurs configurent et gèrent l'interopérabilité des services de messagerie vocale à l'aide du Centre d'administration Exchange (CAE).
    
Pour plus d'informations sur les fonctionnalités de messagerie vocale, consultez la rubrique relative à la [messagerie vocale dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> La fonctionnalité de reconnaissance automatique de la parole (ASR) n'est pas disponible dans la navigation dans les menus ou dans la recherche de répertoire pour les utilisateurs Outlook Voice Access ou les appelants à un standard automatique qui utilisent des commandes vocales. > Le client doit fournir une connexion téléphonique sur le réseau public commuté (RTC) en utilisant une passerelle VoIP et un autocommutateur standard ou IP, ou Skype Entreprise Server 2015. > Le client doit fournir les contrôleurs de frontière de session (SBC) et vérifier qu'ils sont correctement configurés pour se connecter aux services de messagerie vocale en ligne. Cela comprend le niveau correct de sécurité en utilisant des certificats et des interfaces IP publiques et privées et en activant les ports TCP corrects avec leurs pare-feu sur site. > La messagerie vocale est uniquement disponible pour les abonnés à Exchange Online Plan 2 et Office 365 Entreprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interopérabilité avec messagerie vocale tierce

Les solutions de messagerie vocale sur site d'autres fournisseurs peuvent être compatibles avec Exchange Online si elles peuvent transférer des messages vocaux par le protocole SMTP ou si elles prennent en charge les services web Microsoft Exchange. Si le système de messagerie vocale ne prend pas en charge en mode natif le transfert de messages vocaux par le protocole SMTP, il est possible de conserver sur site un serveur de messagerie pour recevoir les messages du système de messagerie vocale et les transférer ensuite dans le nuage en utilisant le protocole SMTP. Du fait que les systèmes de messagerie vocale d'autres fournisseurs utilisent le protocole MAPI/CDO pour fonctionner avec les fonctionnalités avancées de messagerie Exchange Server, les fonctionnalités complètes de ces systèmes ne seront peut-être pas disponibles lorsque le protocole SMTP est utilisé pour l'interopérabilité avec Exchange Online.
  
> [!NOTE]
> Messagerie unifiée Exchange Online de prise en charge pour les systèmes PBX tiers via des connexions directes à partir de client géré SBCs se termine par 2018 juillet. Pour plus d’informations, consultez le [arrêt de la prise en charge des contrôleurs de frontière de Session de messagerie unifiée Exchange Online](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) . 
  
## <a name="skype-for-business-integration"></a>Intégration Skype Entreprise

Les organisations peuvent acheter Skype Entreprise Online en tant que service autonome ou composant de Microsoft Office 365. Pour plus d'informations sur Skype Entreprise Online, consultez la rubrique [Description du service Skype Entreprise Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).
  

