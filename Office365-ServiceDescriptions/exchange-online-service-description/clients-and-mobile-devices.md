---
title: Clients et appareils mobiles
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: ad19845f7a06cfb01a74507fdb794813091c1c2b
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035626"
---
# <a name="clients-and-mobile-devices"></a>Clients et appareils mobiles

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook est un programme de messagerie qui prend en charge le calendrier, contacts, tâches et les fonctionnalités clées suivantes :
  
- **MAPI sur HTTP** Messagerie programme Interface MAPI (Application) sur HTTP permet aux utilisateurs d’Outlook de se connecter aux boîtes aux lettres Exchange Online via Internet à partir de l’extérieur du pare-feu de leur organisation. MAPI sur HTTP, le remplacement à long terme pour Outlook Anywhere. Cette méthode de connectivité offre résistance améliorée de connexion, dans l’authentification plus sécurisée, l’extensibilité, ainsi qu’améliorations pour professionnels et prend en charge. Pour plus d’informations, voir [RPC sur HTTP atteint la fin de la prise en charge dans Office 365](https://go.microsoft.com/fwlink/?linkid=863890) et [MAPI sur HTTP](https://go.microsoft.com/fwlink/?linkid=393041).
    
- **Découverte automatique** La fonctionnalité du service de découverte automatique configure automatiquement Outlook pour qu'il fonctionne avec Exchange Online. Les utilisateurs Outlook peuvent recevoir leurs paramètres de profils requis directement depuis Exchange Online lors de la première connexion avec leur adresse de messagerie électronique et leur mot de passe. Ces paramètres mettent automatiquement à jour le client Outlook à l'aide des informations nécessaires pour créer et maintenir le profil de l'utilisateur. Un certificat SSL est requis pour utiliser le service de découverte automatique. Ce certificat SSL est limité à un seul domaine primaire de SSL. 
    
- **Mode Exchange mis en cache** La fonctionnalité Mode Exchange mis en cache permet aux utilisateurs Outlook d'avoir accès aux copies locales de leurs boîtes aux lettres Exchange Online lorsqu'ils ne sont pas connectés à l'Internet. Le Mode Exchange mis en cache conserve une copie côté client des boîtes aux lettres Exchange des utilisateurs et synchronise automatiquement cette copie au serveur de messagerie électronique. Il est recommandé d'utiliser Outlook en Mode Exchange mis en cache car il présente un accès hors ligne et offre une expérience utilisateur réactive même lorsque les conditions réseau entre le client et le serveur ne sont pas idéales. 
    
Par défaut, l'accès Outlook est activé pour tous les utilisateurs. Les administrateurs peuvent désactiver l'accès de certains utilisateurs ou groupes via Windows PowerShell. Il est recommandé d'utiliser la dernière version d'Outlookavec le dernier Service Pack installépour avoir accès à Exchange Online. 
  
Pour plus d'informations sur les clients Outlook pris en charge par Exchange 2016 et Exchange Online, consultez la section « Clients pris en charge » dans [Configuration requise pour Exchange 2016](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  Outlook n'est pas fourni dans le cadre du prix d'abonnement Exchange Online. Microsoft Office Pro Plus (qui inclut Microsoft Outlook) est inclus dans certains plans Office 365 et est disponible dans le cadre d'un abonnement à part. >  Vous verrez les limitations suivantes si vous utilisez le protocole POP pour vous connecter à un compte de messagerie Exchange Online : >  Aucune information de calendrier >  Aucune informations sur la disponibilité >  Aucune liste d'adresses globale >  Aucun courrier électronique de type push >  Lors de la connexion via POP, tous les messages seront téléchargés vers le client et aucune synchronisation ne sera effectuée entre les ordinateurs multiples et les périphériques (tel qu'entre un ordinateur portable et un téléphone). 
  
## <a name="outlook-on-the-web"></a>Outlook sur le web

Outlook sur le web est une version du programme de messagerie électronique Outlook basée sur le web, utilisée avec Exchange Online. Il permet aux utilisateurs d'avoir accès à leur messagerie électronique, à leur calendrier et à leurs contacts par le biais d'un navigateur web, quel que soit le lieu de connexion à Internet. Pour plus d'informations sur les navigateurs pris en charge, consultez la rubrique [Navigateurs pris en charge dans Outlook sur le web](https://go.microsoft.com/fwlink/p/?LinkId=287032).
  
Outlook sur le web est proposé sous deux versions client, pouvant toutes les deux être utilisées avec Exchange Online :
  
- **Outlook sur web** La version standard d'Outlook sur le web fournit aux utilisateurs d'Exchange Online une expérience de messagerie tout à fait semblable à Outlook. Elle prend en charge les navigateurs les plus récents et est optimisée pour une utilisation sur des tablettes et des smartphones, ainsi que sur des ordinateurs de bureau et des ordinateurs portables. Vous pouvez lire et envoyer des messages, organiser vos contacts et planifier des rendez-vous et des réunions. Le délai d'expiration par défaut basé sur l'activité est fixé à six heures, mais il peut être [configuré par un administrateur dans Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) entre 5 minutes et 8 heures. Il dépend des interactions de l'utilisateur avec l'application web, comme un clic sur un bouton ou la sélection d'un message. Il existe également un autre délai d'expiration basé sur la sécurité. Celui-ci n'est pas configurable et ne dépend pas de l'activité de l'utilisateur. Si un utilisateur est connecté pendant 8 heures, OWA le déconnecte automatiquement et lui demande de s'authentifier à nouveau. 
    
- **Version légère d'Outlook sur le web** La version légère d'Outlook sur le web permet aux utilisateurs d'Exchange Online d'avoir accès à leur boîte aux lettres à l'aide de n'importe quel navigateur web. Vous pouvez lire et envoyer des messages, organiser vos contacts et planifier des rendez-vous et des réunions. Le délai d'expiration par défaut basé sur l'activité est fixé à six heures, mais il peut être [configuré par un administrateur dans Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) entre 5 minutes et 8 heures. Il dépend des interactions de l'utilisateur avec l'application web, comme un clic sur un bouton ou la sélection d'un message. Il existe également un autre délai d'expiration basé sur la sécurité. Celui-ci n'est pas configurable et ne dépend pas de l'activité de l'utilisateur. Si un utilisateur est connecté pendant 8 heures, la version légère d'OWA le déconnecte automatiquement et lui demande de s'authentifier à nouveau. 
    
Outlook sur le web est également disponible en versions mobiles. Pour plus d'informations, voir [cette page](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook pour Mac

Exchange Online prend en charge Microsoft Outlook pour Mac, qui fournit le courrier électronique, calendrier, un carnet d’adresses, une liste de tâches et une liste de notes.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook pour iOS, Android et Windows Phone

Exchange Online fonctionne avec les applications Outlook disponibles pour iOS, Android et Windows Phone. Sur un de ces périphériques, utilisez l’app store pour rechercher l’application Outlook. Voici une répartition par le système d’exploitation mobile.
  
|||||
|:-----|:-----|:-----|:-----|
|Appareil  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Disponibilité d’application mobile Outlook  <br/> |Oui  <br/> [Obtenir d’Outlook pour Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Oui  <br/> [Obtenir d’Outlook pour iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Intégré  <br/> |
|Applications de messagerie intégrée compatibles avec Exchange Online  <br/> |Application de messagerie application/Samsung Gmail  <br/> |application de messagerie iOS  <br/> |Outlook courrier, calendrier, contacts  <br/> |
|Plus d’informations  <br/> |[Programme d’installation mobile Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[programme d’installation iPhone ou iPad](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Programme d’installation de Windows Phone](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
Il existe également des options permettant d’utiliser Exchange Online avec les périphériques, y compris les Blackberry.
  
### <a name="feature-availability"></a>Disponibilité des fonctionnalités

Outlook permet aux utilisateurs de l’expérience de messagerie et calendrier rapide et intuitive qu’ils attendent à partir d’une application mobile moderne, tout en cours de l’application uniquement pour prendre en charge les meilleures fonctionnalités d’Office 365. Il est la seule application de messagerie spécifiquement conçue pour prendre en charge l’expérience Office 365 complète, offrant aux utilisateurs une expérience cohérente de bureau pour mobiles. Outlook est intégré à Intune mobilité d’entreprise et de sécurité et contrôles Exchange pour protéger les données et les utilisateurs.
  
Outlook permet aux utilisateurs de :
  
- Gérer leur journée entière à partir d’un appareil mobile.
    
- Se connecter pour les applications et les services que dont ils ont besoin d’être productifs, tout en conservant leur travail et les informations personnelles distincte et sécurisée.
    
Avec Outlook pour iOS, Outlook pour Android ou Outlook pour Windows Phone, les utilisateurs peuvent : 
  
- Tirer parti d’une boîte de réception focus e-mail priorités importantes
    
- Personnaliser des mouvements effectuez un balayage correspondant à leurs habitudes de messagerie unique
    
- Créer des itinéraires de voyages qui peuvent être ajoutés directement au calendrier, avec les informations de clé en un coup de œil
    
- RÉPONDRE à des réunions à partir de la boîte de réception.
    
- Utilisez les icônes intuitives dans le message électronique et les rendez-vous du calendrier qui leur permettent de traitent les informations rapidement
    
- Utiliser une expérience cohérente et familière d’Outlook sur tous les périphériques
    
- Facilement lancer et participer à des réunions de Skype à partir du calendrier
    
- Lire et répondre à IRM chiffré et protégé les messages électroniques
    
- Partager des fichiers stockés dans OneDrive entreprise
    
- Définir des réponses automatiques d’un clic
    
- Afficher et gérer les calendriers partagés et déléguées
    
- Recherche de liste d’adresses globale de leur entreprise avec quelques clics
    
- Afficher la disponibilité d’un collègue et planifier une heure de réunion qui fonctionne pour tout le monde
    
- Voir invités accepter, provisoire et refuser l’état
    
- Partager des calendriers directement depuis leurs téléphones
    
- Démarrer et joindre à droite de réunions Skype à partir d’un calendrier
    
- Travail d’accès et les calendriers personnels dans un seul emplacement, sans basculer entre les applications
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online prend en charge le protocole Microsoft Exchange ActiveSync qui synchronise les données de boîte aux lettres entre les périphériques mobiles et Exchange Online, de sorte que les utilisateurs peuvent avoir accès à leur messagerie électronique, à leur calendrier, à leurs contacts et à leurs tâches où qu'ils soient.
  
Un large éventail d’appareils mobiles fonctionnent avec Exchange ActiveSync, y compris Microsoft Windows Phone, Apple iPhone et iPad, Android téléphones et des tablettes. En plus de téléphones et appareils mobiles, l’application de messagerie dans Windows Phone utilise Exchange ActiveSync pour se connecter à Exchange Online. Une liste complète des détenteurs de licences Exchange ActiveSync en cours est disponible sur le site de gestion de licences Exchange ActiveSync.
  
Pour plus d’informations sur Exchange ActiveSync, consultez [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).
  
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
  
## <a name="blackberry-devices"></a>Appareils BlackBerry®

Courrier électronique Office 365 est disponible sur les appareils BlackBerry® via Exchange ActiveSync. Pour savoir quelles sont vos options, voir les rubriques suivantes :
  
- [Configurer la messagerie sur un BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [Configurer la messagerie sur un BlackBerry 7.1 système d’exploitation et versions antérieures](https://go.microsoft.com/fwlink/?linkid=863403)
    
Pour plus d'informations, consultez la rubrique [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Si vous utilisez Office 365 géré par 21Vianet en Chine, BlackBerry Business Cloud Services n'est pas disponible, mais vous pouvez utiliser des appareils Exchange ActiveSync ou un produit Research in Motion (RIM, la solution de messagerie sans fil pour BlackBerry) pour exécuter Blackberry Enterprise Server (initialisation). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).
  

