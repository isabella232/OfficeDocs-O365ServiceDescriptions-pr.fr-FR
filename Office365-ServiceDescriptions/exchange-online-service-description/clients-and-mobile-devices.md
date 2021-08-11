---
title: Clients et appareils mobiles
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online fonctionne avec les versions de bureau et mobiles de Outlook, ainsi que les Outlook sur le web.
ms.openlocfilehash: 3e612d9f157cb4109dfc2bef9bfa462445674dd9d19954ca9fe6ac32004ad515
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664047"
---
# <a name="clients-and-mobile-devices"></a>Clients et appareils mobiles

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook est un programme de messagerie qui inclut la prise en charge du calendrier, des contacts, des tâches et des fonctionnalités clés suivantes :
  
- **MAPI sur HTTP** - MapI (Messaging Application Program Interface) sur HTTP permet aux utilisateurs Outlook de se connecter à des boîtes aux lettres Exchange Online via Internet à partir de l’extérieur du pare-feu de leur organisation. MAPI sur HTTP, remplacement à long terme de Outlook Anywhere. Cette méthode de connectivité offre une meilleure résilience de connexion, une connexion plus sécurisée, une extensibilité, ainsi que des améliorations pour le service technique et la prise en charge. Pour en savoir plus, voir [RPC sur HTTP atteint la](/exchange/troubleshoot/administration/rpc-over-http-end-of-support) fin de la prise en charge dans Office 365 et [MAPI sur HTTP](/exchange/mapi-over-http-exchange-2013-help).

- **Découverte automatique** : la fonctionnalité de service de découverte automatique configure automatiquement les Outlook pour qu’elles fonctionnent Exchange Online. Les utilisateurs Outlook peuvent recevoir leurs paramètres de profils requis directement depuis Exchange Online lors de la première connexion avec leur adresse de messagerie électronique et leur mot de passe. Ces paramètres mettent automatiquement à jour le client Outlook à l’aide des informations nécessaires pour créer et maintenir le profil de l’utilisateur. Un certificat SSL est requis pour utiliser le service de découverte automatique. Ce certificat SSL est limité à un seul domaine primaire de SSL. 

- **Mode Exchange** mis en cache : la fonctionnalité mode Exchange mis en cache permet aux utilisateurs Outlook d’accéder aux copies locales de leurs boîtes aux lettres Exchange Online lorsqu’ils ne sont pas connectés à Internet. Le Mode Exchange mis en cache conserve une copie côté client des boîtes aux lettres Exchange des utilisateurs et synchronise automatiquement cette copie au serveur de messagerie électronique. Il est recommandé d'utiliser Outlook en Mode Exchange mis en cache car il présente un accès hors ligne et offre une expérience utilisateur réactive même lorsque les conditions réseau entre le client et le serveur ne sont pas idéales. 

Par défaut, l'accès Outlook est activé pour tous les utilisateurs. Les administrateurs peuvent désactiver l'accès de certains utilisateurs ou groupes via Windows PowerShell. Il est recommandé d'utiliser la dernière version d'Outlookavec le dernier Service Pack installépour avoir accès à Exchange Online. 
  
Pour plus d’informations sur les clients Outlook pris en charge par Exchange 2016 et Exchange Online, voir [System Requirements for Office](https://products.office.com/office-system-requirements). 

Microsoft 365 est conçu pour fonctionner avec les navigateurs et les versions les plus récents de Office. Si vous utilisez des navigateurs et des versions plus anciens Office qui ne sont pas dans le support standard :

- Microsoft ne vous empêche pas délibérément de vous connecter au service, mais la qualité de votre expérience peut diminuer au fil du temps.
- Microsoft ne fournira pas de mises à jour logicielles pour résoudre les problèmes non liés à la sécurité.

> [!IMPORTANT]
> Outlook n'est pas fourni dans le cadre du prix d'abonnement Exchange Online. Applications Microsoft 365 pour les grandes entreprises (qui inclut Microsoft Outlook) est inclus dans certains plans et peut être acheté en tant qu’abonnement distinct. Vous verrez les limitations suivantes si vous utilisez le protocole POP pour vous connecter à un compte de messagerie Exchange Online :
> - Aucune information de calendrier
>- Aucune informations sur la disponibilité
>- Aucune liste d’adresses globale
>- Aucun courrier électronique de type push
>- Lors de la connexion via POP, tous les messages seront téléchargés vers le client et aucune synchronisation ne sera effectuée entre les ordinateurs multiples et les périphériques (tel qu'entre un ordinateur portable et un téléphone). 
  
## <a name="outlook-on-the-web"></a>Outlook sur le web

Outlook sur le web est une version du programme de messagerie électronique Outlook basée sur le web, utilisée avec Exchange Online. Il permet aux utilisateurs d’accéder à leurs e-mails, calendriers et contacts via un navigateur web à partir de l’endroit où ils se connectent à Internet. Pour plus d'informations sur les navigateurs pris en charge, consultez la rubrique [Navigateurs pris en charge dans Outlook sur le web](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
Outlook sur le web est proposé sous deux versions client, pouvant toutes les deux être utilisées avec Exchange Online :
  
- **Outlook sur le web** - La version standard de Outlook sur le web offre aux utilisateurs Exchange Online une expérience de messagerie très similaire à celle des Outlook utilisateurs. Il prend en charge la plupart des navigateurs web plus récents et est optimisé pour une utilisation sur les tablettes et les smartphones, ainsi que sur les ordinateurs de bureau et les ordinateurs portables. Les utilisateurs peuvent lire et envoyer des messages, organiser des contacts et planifier des rendez-vous et des réunions. Le délai d’accès basé sur l’activité par défaut est de six heures, mais il peut être configuré par un administrateur en [Windows PowerShell](/powershell/module/exchange/set-organizationconfig) de 5 à 8 heures. Ce délai dépend des interactions de l’utilisateur au sein de l’application web, telles que la sélection d’un bouton ou la sélection d’un message. Il existe également un délai d’accès à la sécurité distinct, qui n’est pas configurable et se produit quelle que soit l’activité de l’utilisateur. Si un utilisateur est connecté pendant 8 heures, OWA déconnecte automatiquement l’utilisateur et demande une nouvelle authentification. 

- **La version légère de Outlook sur le web** - La version light de Outlook sur le web permet aux utilisateurs Exchange Online d’accéder à la boîte aux lettres à l’aide de presque n’importe quel navigateur web. Les utilisateurs peuvent lire et envoyer des messages, organiser des contacts et planifier des rendez-vous et des réunions. Le délai d’accès basé sur l’activité par défaut est de six heures, mais il peut être configuré par un administrateur en [Windows PowerShell](/powershell/module/exchange/set-organizationconfig) de 5 à 8 heures. Ce délai dépend des interactions de l’utilisateur au sein de l’application web, telles que la sélection d’un bouton ou la sélection d’un message. Il existe également un délai d’accès à la sécurité distinct, qui n’est pas configurable et se produit quelle que soit l’activité de l’utilisateur. Si un utilisateur est connecté pendant 8 heures, la version light de OWA déconnecte automatiquement l’utilisateur et demande une nouvelle authentification. 

Outlook sur le web est également disponible en versions mobiles. Pour plus d'informations, voir [cette page](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook pour Mac

Exchange Online prend en charge Microsoft Outlook pour Mac, qui fournit un courrier électronique, un calendrier, un carnet d’adresses, une liste de tâches et une liste de notes.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook pour iOS, Android et Windows Phone

Exchange Online fonctionne avec Outlook applications disponibles pour iOS, Android et Windows Phone. Sur l’un de ces appareils, utilisez le Magasin d’applications pour trouver l’Outlook appl’application. Voici une répartition par système d’exploitation mobile.<br><br>
  
| Appareil | Android | iOS | Windows Phone |
|:-----|:-----|:-----|:-----|
|Outlook d’application mobile  <br/> |Oui  <br/> [Obtenir Outlook pour Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Oui  <br/> [Obtenir Outlook pour iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Intégré  <br/> |
|Applications de messagerie intégrées compatibles avec Exchange Online  <br/> |Application Gmail/Application de messagerie Samsung  <br/> |Application de messagerie iOS  <br/> |Outlook Courrier, calendrier, contacts  <br/> |
|Informations supplémentaires  <br/> |[Configuration mobile Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone ou iPad configuration](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone configuration](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

Il existe également des options d’utilisation Exchange Online appareils, notamment Blackberry.
  
### <a name="feature-availability"></a>Disponibilité des fonctionnalités

Outlook offre aux utilisateurs l’expérience de courrier électronique et de calendrier rapide et intuitive qu’ils attendent d’une application mobile moderne, tout en étant la seule application à prendre en charge les meilleures fonctionnalités. Il s’agit de la seule application de messagerie spécialement conçue pour prendre en charge l’expérience Microsoft complète, offrant aux utilisateurs une expérience cohérente du bureau à l’appareil mobile. Outlook est intégré à Intune, à la mobilité et à la sécurité d’entreprise et aux contrôles Exchange pour préserver la sécurité des données et des utilisateurs.
  
Avec Outlook, les utilisateurs peuvent :
  
- Gérez leur journée entière à partir d’un appareil mobile.

- Connecter aux applications et services dont ils ont besoin pour être productifs, tout en conservant leurs informations personnelles et de travail séparées et sécurisées.

Avec Outlook pour iOS, Outlook pour Android ou Outlook pour Windows Phone, les utilisateurs peuvent : 
  
- Bénéficier d’une boîte de réception axée sur la priorité des messages électroniques importants

- Personnaliser les mouvements de balayage pour qu’ils correspondent à leurs habitudes de messagerie uniques

- Créer des itinéraires de voyage qui peuvent être ajoutés directement au calendrier, avec des informations clés disponibles en un coup d’œil

- RSVP aux réunions à partir de la boîte de réception.

- Utiliser des icônes intuitives dans les rendez-vous de courrier électronique et de calendrier qui les aident à traiter rapidement des informations

- Utiliser une expérience de Outlook cohérente et familière sur tous les appareils

- Lancer et rejoindre facilement des Skype à partir du calendrier

- Lire et répondre aux messages électroniques chiffrés et protégés par IRM

- Partager des fichiers stockés dans OneDrive Entreprise

- Définir les réponses automatiques en tapant

- Afficher et gérer les calendriers partagés et délégués

- Rechercher la liste d’adresses globale de son entreprise en quelques clics

- Afficher la disponibilité de votre collègue et planifier une heure de réunion qui fonctionne pour tout le monde

- Voir les invités accepter, provisoirement et refuser l’état

- Partager des calendriers directement à partir de leurs téléphones

- Démarrer et rejoindre Skype réunions directement à partir d’un calendrier

- Accéder aux calendriers personnels et personnels au même endroit, sans changer d’application
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online prend en charge le protocole Microsoft Exchange ActiveSync qui synchronise les données de boîte aux lettres entre les périphériques mobiles et Exchange Online, de sorte que les utilisateurs peuvent avoir accès à leur messagerie électronique, à leur calendrier, à leurs contacts et à leurs tâches où qu'ils soient.
  
Une large gamme d'appareils mobiles fonctionnent avec Exchange ActiveSync, y compris les appareils Microsoft Windows Phone, Apple iPhone et iPad et les téléphones et tablettes Android. Outre les téléphones et appareils mobiles, l’application de messagerie dans Windows Phone utilise Exchange ActiveSync pour se connecter à Exchange Online. Une liste complète des accords de licence Exchange ActiveSync est disponible sur le site de gestion des licences Exchange ActiveSync.
  
Pour plus d’informations sur Exchange ActiveSync, [voir Exchange ActiveSync](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online).
  
> [!IMPORTANT]
> Le nombre maximal d'appareils Exchange ActiveSync par boîte aux lettres est de 100. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Applications développées avec Exchange Web Services (EWS)

 Les applications développées au moyen d'Exchange Web Services (EWS) ou de l'API gérée par EWS permettent aux administrateurs d'avoir accès aux données stockées avec Exchange Online depuis des applications qui s'exécutent localement, dans Azure ou dans d'autres services hébergés. 
  
Pour plus d'informations sur les applications développées avec les services Web Exchange, consultez la rubrique [Services web dans Exchange](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange).
  
## <a name="pop-and-imap"></a>POP et IMAP

Exchange Online prend en charge l'accès aux boîtes aux lettres via les protocoles POP3 et IMAP4. L'accès POP et IMAP requiert le chiffrement à l'aide de SSL. POP est activé par défaut pour tous les utilisateurs. Les utilisateurs peuvent afficher les paramètres de connexion POP et IMAP dans Outlook sur le web. Les administrateurs peuvent désactiver l'accès POP et IMAP pour chaque utilisateur.
  
Pour plus d'informations sur la connectivité POP3 et IMAP4 consultez la rubrique [POP3 et IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help).
  
## <a name="smtp"></a>SMTP

Le protocole SMTP (Simple Mail Transfer) permet d'envoyer des messages sortants à des clients qui se connectent à Exchange Online via IMAP ou POP. Il s'agit du principal protocole d'acheminement et de livraison via Exchange Server. Exchange Online prend en charge deux types de services relais SMTP pour les applications clients internes autorisés qui exige un abonnement de messagerie SMTP :
  
- Abonnement de messagerie SMTP pour les utilisateurs dans l'environnement géré.

- Relais de message SMTP authentifié à des adresses en dehors de l'environnement géré.

> [!IMPORTANT]
> Les adresses IP des serveurs source autorisés sont obligatoires pour permettre le relais SMTP. Le chiffrement et l'authentification TLS (Transport Layer Security) sont requis pour toute utilisation de SMTP pour l'envoi un message électronique. 
  
## <a name="blackberry-devices"></a>Appareils BlackBerry

Le courrier électronique est disponible sur les appareils BlackBerry &reg; via Exchange ActiveSync. Pour en savoir plus sur vos options, consultez les rubriques ci-après :
  
- [Configurer le courrier électronique sur un appareil BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)

- [Configurer le courrier électronique sur un système d’exploitation BlackBerry 7.1 et les antérieures](https://go.microsoft.com/fwlink/?linkid=863403)

Pour plus d'informations, consultez la rubrique [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Si vous utilisez Office 365 géré par 21Vianet en Chine, BlackBerry Business Cloud Services n'est pas disponible, mais vous pouvez utiliser des appareils Exchange ActiveSync ou un produit Research in Motion (RIM, la solution de messagerie sans fil pour BlackBerry) pour exécuter Blackberry Enterprise Server (initialisation). 
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir [Exchange Online description du service.](exchange-online-service-description.md)
