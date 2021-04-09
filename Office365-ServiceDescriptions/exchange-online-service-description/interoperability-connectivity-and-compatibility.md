---
title: Interopérabilité, connectivité et compatibilité
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: b5dd2467010d4f7eb74ba356abc75ff54ad09cf0
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652718"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interopérabilité, connectivité et compatibilité

## <a name="interoperability-with-other-microsoft-products"></a>Interopérabilité avec d'autres produits Microsoft

### <a name="skype-for-business-online"></a>Skype Entreprise Online

Pour les clients qui ont déployé Microsoft Lync Server 2010, Lync Server 2013 ou Microsoft Office Communications Server 2007 R2 local, Microsoft Office Communicator peut se connecter à Microsoft Exchange Online à l'aide des services web Exchange afin d'accéder aux messages de notification d'absence du bureau et aux données de calendrier.
  
Lync Server 2010 et Lync Server 2013 sur site peuvent interagir avec Exchange Online de deux façons supplémentaires :
  
- Interopérabilité de la messagerie instantanée et de la présence dans Outlook sur le web
    
- Interopérabilité de la messagerie vocale
    
Pour plus d'informations sur la configuration de Skype Entreprise Server 2015 avec Exchange Online, consultez la page [Configuration de l'intégration de Skype Entreprise Server 2015 sur site avec Exchange Online](/skypeforbusiness/deploy/integrate-with-exchange-server/outlook-web-app). Pour les configurations hybrides, consultez la page [Configurations hybrides Skype Entreprise Server 2015 prises en charge](/skypeforbusiness/skype-for-business-hybrid-solutions/integration-with-exchange-and-sharepoint).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Pour les clients qui ont déployé Microsoft SharePoint Server ou SharePoint Online dans le cadre d’un plan d’abonnement, SharePoint peut se connecter à Exchange Online pour les services intégrés.
  
Pour plus d'informations sur la connexion de SharePoint à Exchange Online, visitez la page [Utiliser SharePoint Online sur un domaine personnalisé avec d'autres services](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Fonctionnalités pour la connectivité externe

Exchange Online offre les fonctionnalités suivantes permettant d'établir une connexion avec des applications et des appareils externes :
  
- **Via des protocoles de messagerie tels que SMTP, POP3, IMAP4 ou Services web Exchange** Les applications externes exécutées en local dans Azure ou dans d'autres services hébergés peuvent accéder aux données stockées avec Exchange Online à l'aide de protocoles de messagerie tels que MAPI sur HTTP, SMTP, POP3 et IMAPv4. Il est recommandé d'utiliser les services Web Exchange ou l'API gérée des services Web Exchange pour le développement d'applications. 
    
- **Comme un relais SMTP** Exchange Online peut être configuré comme un service de remise SMTP pour les e-mails envoyés à partir de passerelles de télécopie, d'appliances réseau et d'applications personnalisées. 
    
### <a name="exchange-web-services"></a>Services Web Exchange

Les services Web Exchange (EWS) constituent l'API de développement privilégiée pour Exchange Server et Exchange Online. Grâce à EWS ou à l'API gérée EWS, les administrateurs peuvent accéder aux données stockées avec Exchange Online à partir d'applications exécutées sur site dans Azure ou dans d'autres services hébergés. EWS permet aux administrateurs d’effectuer des actions spécialisées, telles que l’interrogation du contenu d’une boîte aux lettres, la publication d’un événement de calendrier, la création d’une tâche ou le déclenchement d’une action spécifique basée sur le contenu d’un message électronique. Exchange Online active la fonctionnalité EWS en octroyant des autorisations d'application aux comptes clients. Ces autorisations permettent à l'application cliente d'accéder à la boîte aux lettres de l'application et d'ajouter du contenu. L'emprunt d'identité Exchange est une méthode utilisée pour accorder des autorisations d'application. Pour plus d'informations sur la façon d'utiliser les services Web Exchange avec Exchange Online, consultez les articles techniques du Centre pour développeurs Exchange Online.
  
### <a name="smtp-relay"></a>Relais SMTP

Exchange Online peut être configuré comme un service de remise SMTP pour relayer les e-mails envoyés à partir de passerelles de télécopie, d'appliances réseau et d'applications personnalisées. Par exemple, si une application métier envoie des alertes par courrier électronique aux utilisateurs, elle peut être configurée pour utiliser Exchange Online comme système de remise du courrier. L'application ou le service doit s'identifier avec le nom d'utilisateur et mot de passe d'une boîte aux lettres Exchange Online sous licence valide, et se connecter à l'aide du protocole Transport Layer Security (TLS).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, consultez la [description du service Exchange Online.](exchange-online-service-description.md)
