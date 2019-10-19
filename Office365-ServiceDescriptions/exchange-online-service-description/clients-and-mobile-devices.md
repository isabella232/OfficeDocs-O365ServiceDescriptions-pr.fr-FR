---
title: Clients et appareils mobiles
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 0b5768720514572299814dd5ecd9c3a200f1958a
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581920"
---
# <a name="clients-and-mobile-devices"></a>Clients et appareils mobiles

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook est un programme de messagerie électronique qui inclut la prise en charge du calendrier, des contacts, des tâches et des fonctionnalités clés suivantes :
  
- **MAPI sur http** L’interface MAPI (Messaging Application Program Interface) sur HTTP permet aux utilisateurs d’Outlook de se connecter à des boîtes aux lettres Exchange Online sur Internet depuis l’extérieur du pare-feu de leur organisation. MAPI sur HTTP, le remplacement à long terme pour Outlook Anywhere. Cette méthode de connectivité offre une résilience de connexion améliorée, une authentification plus sécurisée, une extensibilité, ainsi que des améliorations pour le service informatique et la prise en charge. Pour en savoir plus, consultez la rubrique [RPC sur http atteint la fin de la prise en charge dans Office 365](https://go.microsoft.com/fwlink/?linkid=863890) et [MAPI sur http](https://go.microsoft.com/fwlink/?linkid=393041).

- **Découverte automatique** La fonctionnalité du service de découverte automatique configure automatiquement Outlook pour qu'il fonctionne avec Exchange Online. Les utilisateurs Outlook peuvent recevoir leurs paramètres de profils requis directement depuis Exchange Online lors de la première connexion avec leur adresse de messagerie électronique et leur mot de passe. Ces paramètres mettent automatiquement à jour le client Outlook à l'aide des informations nécessaires pour créer et maintenir le profil de l'utilisateur. Un certificat SSL est requis pour utiliser le service de découverte automatique. Ce certificat SSL est limité à un seul domaine primaire de SSL. 

- **Mode Exchange mis en cache** La fonctionnalité de mode Exchange mis en cache permet aux utilisateurs d’Outlook d’accéder à des copies locales de leurs boîtes aux lettres Exchange Online lorsqu’ils ne sont pas connectés à Internet. Le Mode Exchange mis en cache conserve une copie côté client des boîtes aux lettres Exchange des utilisateurs et synchronise automatiquement cette copie au serveur de messagerie électronique. Il est recommandé d'utiliser Outlook en Mode Exchange mis en cache car il présente un accès hors ligne et offre une expérience utilisateur réactive même lorsque les conditions réseau entre le client et le serveur ne sont pas idéales. 

Par défaut, l'accès Outlook est activé pour tous les utilisateurs. Les administrateurs peuvent désactiver l'accès de certains utilisateurs ou groupes via Windows PowerShell. Il est recommandé d'utiliser la dernière version d'Outlookavec le dernier Service Pack installépour avoir accès à Exchange Online. 
  
Pour plus d'informations sur les clients Outlook pris en charge par Exchange 2016 et Exchange Online, consultez la section « Clients pris en charge » dans [Configuration requise pour Exchange 2016](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  Outlook n'est pas fourni dans le cadre du prix d'abonnement Exchange Online. Microsoft Office Pro Plus (qui inclut Microsoft Outlook) est inclus dans certains plans Office 365 et est disponible dans le cadre d'un abonnement à part. Si vous utilisez POP pour se connecter à un compte de messagerie Exchange Online, les limitations suivantes s’affichent : > aucune information de calendrier > aucune information de disponibilité > pas de liste d’adresses globale > aucun courrier électronique n' > lors de la connexion via POP, tous les messages seront téléchargés t o le client et il n’y aura pas de synchronisation entre plusieurs ordinateurs ou appareils (par exemple, entre un ordinateur portable et un téléphone). 
  
## <a name="outlook-on-the-web"></a>Outlook sur le web

Outlook sur le web est une version du programme de messagerie électronique Outlook basée sur le web, utilisée avec Exchange Online. Il permet aux utilisateurs d’accéder à leurs courriers électroniques, calendrier et contacts par le biais d’un navigateur Web où qu’ils se connectent à Internet. Pour plus d'informations sur les navigateurs pris en charge, consultez la rubrique [Navigateurs pris en charge dans Outlook sur le web](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
Outlook sur le web est proposé sous deux versions client, pouvant toutes les deux être utilisées avec Exchange Online :
  
- **Outlook sur le Web** La version standard d’Outlook sur le Web fournit aux utilisateurs d’Exchange Online une expérience de messagerie semblable à celle des utilisateurs d’Outlook. Il prend en charge la plupart des navigateurs Web et est optimisé pour une utilisation sur des tablettes et des smartphones, ainsi que des ordinateurs de bureau et des ordinateurs portables. Les utilisateurs peuvent lire et envoyer des messages, organiser des contacts, et planifier des rendez-vous et des réunions. Le délai d’expiration basé sur l’activité par défaut est défini sur six heures, mais il peut être [configuré par un administrateur dans Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutes à 8 heures. Ce délai d’attente dépend des interactions de l’utilisateur au sein de l’application Web, telles que la sélection d’un bouton ou la sélection d’un message. Il existe également un délai d’expiration de sécurité distinct, qui n’est pas configurable et qui se produit indépendamment de l’activité de l’utilisateur. Si un utilisateur est connecté pendant 8 heures, OWA journalise automatiquement l’utilisateur et demande une nouvelle authentification. 

- **Version Light d’Outlook sur le Web** La version Light d’Outlook sur le Web permet aux utilisateurs Exchange Online d’accéder à la boîte aux lettres à l’aide de quasiment n’importe quel navigateur Web. Les utilisateurs peuvent lire et envoyer des messages, organiser des contacts, et planifier des rendez-vous et des réunions. Le délai d’expiration basé sur l’activité par défaut est défini sur six heures, mais il peut être [configuré par un administrateur dans Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutes à 8 heures. Ce délai d’attente dépend des interactions de l’utilisateur au sein de l’application Web, telles que la sélection d’un bouton ou la sélection d’un message. Il existe également un délai d’expiration de sécurité distinct, qui n’est pas configurable et qui se produit indépendamment de l’activité de l’utilisateur. Si un utilisateur est connecté pendant 8 heures, la version Light d’OWA journalise automatiquement l’utilisateur et demande une nouvelle authentification. 

Outlook sur le web est également disponible en versions mobiles. Pour plus d'informations, voir [cette page](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook pour Mac

Exchange Online prend en charge Microsoft Outlook pour Mac, qui fournit un courrier électronique, un calendrier, un carnet d’adresses, une liste de tâches et une liste de notes.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook pour iOS, Android et Windows Phone

Exchange Online fonctionne avec les applications Outlook disponibles pour iOS, Android et Windows Phone. Sur l’un de ces appareils, utilisez l’App Store pour trouver l’application Outlook. Voici une ventilation par le système d’exploitation mobile.
  
|||||
|:-----|:-----|:-----|:-----|
|Appareil  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Disponibilité de l’application mobile Outlook  <br/> |Oui  <br/> [Obtenir Outlook pour Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Oui  <br/> [Obtenir Outlook pour iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Intégré  <br/> |
|Applications de messagerie intégrées compatibles avec Exchange Online  <br/> |Application de messagerie Gmail App/Samsung  <br/> |application de messagerie iOS  <br/> |Courrier, calendrier, contacts Outlook  <br/> |
|Plus d’informations  <br/> |[Configuration d’Android Mobile](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[programme d’installation de iPhone ou iPad](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Configuration de Windows Phone](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

Il existe également des options pour l’utilisation d’Exchange Online avec des appareils, notamment BlackBerry.
  
### <a name="feature-availability"></a>Disponibilité des fonctionnalités

Outlook offre aux utilisateurs l’expérience de messagerie et de calendrier rapide et intuitive qu’ils attendent d’une application mobile moderne, tout en étant la seule application à prendre en charge les meilleures fonctionnalités d’Office 365. Il s’agit de la seule application de messagerie spécifiquement conçue pour prendre en charge l’expérience complète d’Office 365, offrant ainsi aux utilisateurs une expérience cohérente entre l’ordinateur de bureau et mobile. Outlook est intégré à Intune, à la mobilité et à la sécurité d’entreprise, ainsi qu’aux contrôles Exchange pour garantir la sécurité des données et des utilisateurs.
  
Avec Outlook, les utilisateurs peuvent :
  
- Gérer toute la journée à partir d’un appareil mobile.

- Connectez-vous aux applications et services dont ils ont besoin pour être productif, tout en gardant leurs informations personnelles et professionnelles séparées et sécurisées.

Avec Outlook pour iOS, Outlook pour Android ou Outlook pour Windows Phone, les utilisateurs peuvent : 
  
- Tirer parti d’une boîte de réception prioritaire présentant des priorités importantes pour les messages électroniques

- Personnaliser les mouvements de balayage en fonction de leurs habitudes de messagerie uniques

- Créer des itinéraires de voyage pouvant être ajoutés directement au calendrier, avec des informations clés disponibles en un clin d’œil

- RSVP aux réunions à partir de la boîte de réception.

- Utiliser des icônes intuitives dans les courriers électroniques et les rendez-vous de calendrier qui les aident à traiter les informations rapidement

- Utiliser une expérience Outlook cohérente et familière sur tous les appareils

- Lancer et rejoindre facilement des réunions Skype à partir du calendrier

- Lire et répondre aux e-mails chiffrés et protégés IRM

- Partager des fichiers stockés dans OneDrive entreprise

- Définir des réponses automatiques avec un TAP

- Afficher et gérer des calendriers partagés et délégués

- Rechercher dans la liste d’adresses globale de la société en quelques clics

- Affichage de la disponibilité et de la planification d’une heure de réunion qui s’appliquent à tous les collaborateurs

- Voir l’état des invités sur les invités, les provisoires et les refusés

- Partager des calendriers directement à partir de leurs téléphones

- Démarrer et rejoindre des réunions Skype directement à partir d’un calendrier

- Accéder à des calendriers personnels et professionnels à un seul endroit, sans changer d’application
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online prend en charge le protocole Microsoft Exchange ActiveSync qui synchronise les données de boîte aux lettres entre les périphériques mobiles et Exchange Online, de sorte que les utilisateurs peuvent avoir accès à leur messagerie électronique, à leur calendrier, à leurs contacts et à leurs tâches où qu'ils soient.
  
Une large gamme d'appareils mobiles fonctionnent avec Exchange ActiveSync, y compris les appareils Microsoft Windows Phone, Apple iPhone et iPad et les téléphones et tablettes Android. En plus des téléphones et appareils mobiles, l’application de messagerie dans Windows Phone utilise Exchange ActiveSync pour se connecter à Exchange Online. Une liste complète des accords de licence Exchange ActiveSync est disponible sur le site de gestion des licences Exchange ActiveSync.
  
Pour plus d’informations sur Exchange ActiveSync, consultez la rubrique [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).
  
> [!IMPORTANT]
> Le nombre maximal d'appareils Exchange ActiveSync par boîte aux lettres est de 100. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Applications développées avec Exchange Web Services (EWS)

 Les applications développées au moyen d'Exchange Web Services (EWS) ou de l'API gérée par EWS permettent aux administrateurs d'avoir accès aux données stockées avec Exchange Online depuis des applications qui s'exécutent localement, dans Azure ou dans d'autres services hébergés. 
  
Pour plus d'informations sur les applications développées avec les services Web Exchange, consultez la rubrique [Services web dans Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).
  
## <a name="pop-and-imap"></a>POP et IMAP

Exchange Online prend en charge l'accès aux boîtes aux lettres via les protocoles POP3 et IMAP4. L'accès POP et IMAP requiert le chiffrement à l'aide de SSL. POP est activé par défaut pour tous les utilisateurs. Les utilisateurs peuvent afficher les paramètres de connexion POP et IMAP dans Outlook sur le web. Les administrateurs peuvent désactiver l'accès POP et IMAP pour chaque utilisateur.
  
Pour plus d'informations sur la connectivité POP3 et IMAP4 consultez la rubrique [POP3 et IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).
  
## <a name="smtp"></a>SMTP

Le protocole SMTP (Simple Mail Transfer) permet d'envoyer des messages sortants à des clients qui se connectent à Exchange Online via IMAP ou POP. Il s'agit du principal protocole d'acheminement et de livraison via Exchange Server. Exchange Online prend en charge deux types de services relais SMTP pour les applications clients internes autorisés qui exige un abonnement de messagerie SMTP :
  
- Abonnement de messagerie SMTP pour les utilisateurs dans l'environnement géré.

- Relais de message SMTP authentifié à des adresses en dehors de l'environnement géré.

> [!IMPORTANT]
> Les adresses IP des serveurs source autorisés sont obligatoires pour permettre le relais SMTP. Le chiffrement et l'authentification TLS (Transport Layer Security) sont requis pour toute utilisation de SMTP pour l'envoi un message électronique. 
  
## <a name="blackberry-devices"></a>Appareils® BlackBerry

Le courrier Office 365 est disponible sur les appareils BlackBerry® via Exchange ActiveSync. Pour connaître les options disponibles, consultez les rubriques suivantes :
  
- [Configurer le courrier électronique sur un appareil BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)

- [Configurer le courrier électronique sur un BlackBerry Device 7,1 OS et versions antérieures](https://go.microsoft.com/fwlink/?linkid=863403)

Pour plus d'informations, consultez la rubrique [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Si vous utilisez Office 365 géré par 21Vianet en Chine, BlackBerry Business Cloud Services n'est pas disponible, mais vous pouvez utiliser des appareils Exchange ActiveSync ou un produit Research in Motion (RIM, la solution de messagerie sans fil pour BlackBerry) pour exécuter Blackberry Enterprise Server (initialisation). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  