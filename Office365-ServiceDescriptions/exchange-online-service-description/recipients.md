---
title: Destinataires
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: Cette rubrique décrit les fonctionnalités en relation avec les destinataires incluses dans Microsoft Exchange Online. Celles-ci comprennent les fonctions relatives au courrier électronique, aux contacts, aux groupes de distribution, au calendrier et à la programmation.
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132638"
---
# <a name="recipients"></a>Destinataires

Cette rubrique décrit les fonctionnalités en relation avec les destinataires incluses dans Microsoft Exchange Online. Celles-ci comprennent les fonctions relatives au courrier électronique, aux contacts, aux groupes de distribution, au calendrier et à la programmation.
  
## <a name="email"></a>E-mail

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> Les adresses attrape-tout ne sont plus prises en charge dans Exchange Online. En raison du filtrage des destinataires en place pour se protéger contre les messages de courrier indésirable potentiels, les adresses de messagerie qui n’existent pas dans votre organisation seront rejetées. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Types de boîtes aux lettres, limites de stockage et alertes de capacité

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
Pour plus d’informations, consultez les sections « limites de stockage des boîtes aux lettres » et « alertes de capacité » dans la rubrique [Exchange Online Limits](exchange-online-limits.md).
  
### <a name="mailtips"></a>MailTips

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>Accès délégué

Exchange Online prend en charge l'accès délégué : il s'agit de la possibilité qu'ont des utilisateurs de permettre à d'autres de gérer leur messagerie électronique et calendriers. L'accès délégué s'utilise habituellement entre un gestionnaire et un assistant, où l'assistant traite les messages électroniques entrants du gestionnaire et coordonne le planning de ce dernier. L’accès délégué peut être activé par les utilisateurs d’Exchange Online dans Outlook ou Outlook sur le Web, ou par les administrateurs dans le centre d’administration Exchange. 
  
Les délégués peuvent avoir deux types d'accès :
  
- **Autorisations Envoyer de la part de** Le délégué peut composer des messages électroniques et entrer le nom de l'autre personne dans le champ De :, là où est afficher « [Nom du délégué] de la part de [nom de la personne] ». 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
Pour plus d'informations sur la délégation d'accès, voir [Gestion des autorisations pour les destinataires](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx).
  
### <a name="inbox-rules"></a>Règles de la boîte de réception

Exchange Online autorise des utilisateurs à créer des règles de boîte de réception qui exécutent automatiquement des actions spécifiques fondées sur des critères sur les messages à mesure qu'ils arrivent. Par exemple, il est possible de créer une règle pour que tout le courrier électronique envoyé à un certain groupe de distribution soit automatiquement déplacé vers un dossier spécifique. Les utilisateurs gèrent les règles de boîte de réception à partir d’Outlook ou d’Outlook sur le Web. Les administrateurs ont la possibilité de bloquer certains types de règles de boîte de réception en désactivant le transfert côté serveur et/ou des réponses automatiques côté serveur. Par exemple, la désactivation du transfert côté des messages électroniques côté serveur peut empêcher les utilisateurs de transférer automatiquement le courrier électronique vers des comptes personnels. De la même manière; la désactivation des réponses automatiques côté serveur permet d'empêcher des correspondants extérieurs d'utiliser ces réponses pour identifier des adresses de messagerie valides. Ces modifications sont effectuées via Windows PowerShell à distance.
  
### <a name="clutter"></a>Courrier non trié

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>Comptes connectés

La fonctionnalité comptes connectés permet aux utilisateurs Exchange Online de connecter des comptes de messagerie externes (tels que des comptes personnels) à leurs comptes de messagerie internes dans Exchange Online, puis d’utiliser Outlook sur le Web pour interagir avec tous leurs messages dans un emplacement unique. Les comptes connectés se synchronisent automatiquement lors de la connexion à Outlook sur le Web ; les utilisateurs peuvent également synchroniser manuellement les comptes à partir d’Outlook sur le Web. Les administrateurs peuvent activer et désactiver cette fonctionnalité pour des utilisateurs spécifiques ou pour tous les utilisateurs via le [Centre d’administration Exchange](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409).
  
### <a name="inactive-mailboxes"></a>Boîtes aux lettres inactives

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
Pour activer une boîte aux lettres inactive, cette dernière doit nécessairement faire l'objet d'une licence Exchange Online (plan 2) ou d'un abonnement à l'archivage Exchange Online pour qu'il soit possible de lui appliquer un blocage local ou une mise en attente pour litige avant sa suppression.
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
Pour plus d'informations, voir :
  
- [Gestion des boîtes aux lettres inactives dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [Conservation inaltérable et conservation pour litige](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [Découverte électronique locale](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>Contacts et groupes de distribution

### <a name="offline-address-book"></a>Carnet d'adresses en mode hors connexion

La fonctionnalité carnet d’adresses en mode hors connexion fournit une capture instantanée des informations Active Directory disponibles dans la liste d’adresses globale (LAG) d’Outlook. Elle est cachée localement dans Outlook et devient accessible lorsqu'un utilisateur travaille en mode hors connexion.
  
### <a name="address-book-policies"></a>Stratégies de carnet d’adresses

Exchange Online prend en charge les stratégies de carnet d’adresses. Les stratégies de carnet d'adresses vous permettent de segmenter des utilisateurs en groupes spécifiques pour fournir des vues personnalisées de la liste d'adresses globale de votre organisation. Lorsque vous créez une stratégie de carnet d'adresses, vous affectez une LAG, un carnet d'adresses en mode hors connexion, une liste de pièces ainsi qu'une ou plusieurs listes d'adresses à la stratégie. Vous pouvez ensuite affecter le carnet aux utilisateurs de boîtes aux lettres, en leur donnant accès à une liste d’adresses globale personnalisée dans Outlook et Outlook sur le Web. Les administrateurs peuvent configurer les stratégies de carnet d'adresses à l'aide de l'application Windows PowerShell distante. Pour en savoir plus sur les stratégies de carnet d'adresses, voir [Carnets d'adresses dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=394203).
  
### <a name="address-lists"></a>Listes d'adresses

Exchange Online prend en charge la personnalisation des listes d’adresses et des GAL. Une liste d’adresses globale est un répertoire à l’échelle de l’organisation de tous les utilisateurs à extension messagerie, des groupes de distribution et des contacts externes. Les administrateurs peuvent masquer des utilisateurs, des groupes de distribution et des contacts de la liste d’adresses globale à l’aide de l’outil de synchronisation d’annuaires ou de Windows PowerShell à distance.
  
### <a name="hierarchical-address-books"></a>Carnets d’adresses hiérarchiques

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>Groupes de distribution (globaux)

Un groupe de distribution (ou liste de distribution) est un ensemble d'utilisateurs, de contacts et d'autres groupes de distribution qui sont accessibles à tous les utilisateurs au sein d'une entreprise. Les utilisateurs adressent le courrier électronique à un alias du groupe de distribution pour envoyer des messages à toutes les personnes figurant dans le groupe. Les groupes de distribution sont semblables à des groupes de distribution personnels que des individus créent dans Outlook, seules leurs listes de membres sont globalement accessibles à l'entreprise. Les administrateurs créent les groupes de distribution dans le Centre d'administration Exchange. Les groupes peuvent également être synchronisés avec Exchange Online à partir d'Active Directory local. Ils apparaissent dans la liste d’adresses globale dans Outlook. Exchange Online prend en charge des fonctionnalités avancées de groupe de distribution, y compris celles décrites ci-dessous :
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>Contacts externes (globaux)

Un contact externe est un enregistrement contenant des informations sur une personne qui travaille en dehors d'une organisation donnée. Les contacts externes sont semblables à des contacts personnels que des individus créent dans Outlook ; ils ne sont accessibles que globalement à l'entreprise. Les administrateurs créent des contacts externes à l'aide du Centre d'administration Exchange ou via l'application Windows PowerShell distante. Ces contacts peuvent également être synchronisés avec Exchange Online à partir d'Active Directory local. Ils apparaissent dans la liste d’adresses globale dans Outlook.
  
Pour plus d'informations sur les contacts externes, voir [Créer une relation d'organisation dans Exchange Online](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx).
  
## <a name="calendar-and-scheduling"></a>Calendrier et planification

### <a name="resource-mailboxes"></a>Boîtes aux lettres de ressources

Les boîtes aux lettres de ressources (comme celles dédiées aux salles de conférence ou aux équipements physiques) représentent les salles de réunions ou d'autres installations ou ressources. Les utilisateurs peuvent réserver des salles ou des ressources en ajoutant l’alias de messagerie de la ressource aux demandes de réunion dans Outlook ou Outlook sur le Web. Les salles de conférence et les ressources apparaissent dans la liste d’adresses globale dans Outlook et Outlook sur le Web.
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
Pour plus d'informations sur les boîtes aux lettres de ressources, voir :
  
- [Création et gestion des boîtes aux lettres de salle](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [Gérer les boîtes aux lettres d’équipement](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>Gestion des salles de conférence

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
Les administrateurs peuvent personnaliser les réponses automatiques des salles de conférence et configurer des stratégies de réservation dans Outlook sur le Web. Ces stratégies incluent les critères suivants : qui peut planifier la ressource, quand elle peut être planifiée, quelles informations relatives à la réunion sont visibles sur le calendrier de la ressource et quel pourcentage de conflits est autorisé. Les administrateurs ont la possibilité de désactiver l'Assistant Réservation de ressources et d'affecter à des utilisateurs spécifiques la gestion manuelle des demandes de réunion associées à des salles de conférence.
  
Les administrateurs doivent définir et gérer les paramètres de l'Assistant Réservation de ressources via Windows PowerShell à distance.
  
### <a name="out-of-office-replies"></a>Réponses avec notification d'absence du bureau

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>Partage du calendrier

Les utilisateurs peuvent partager leur calendrier personnel selon l'une des deux manières suivantes :
  
- **Partage de calendrier fédéré** La Fédération fait référence à l’infrastructure d’approbation sous-jacente qui prend en charge le partage fédéré, méthode facile pour les utilisateurs Exchange de partager les données de calendrier et les informations de contact avec des destinataires d’autres organisations fédérées externes. Il s’agit notamment des organisations ou organisations Exchange Online exécutant Exchange Server 2010 ou Exchange Server 2013 en local. Les administrateurs Exchange Online n’ont pas besoin de configurer une approbation avec Microsoft Federation Gateway, car cette approbation est préconfigurée pour tous les clients Exchange Online lors de la création du service Microsoft. Une stratégie de partage par défaut permet aux utilisateurs d’envoyer des invitations de partage de calendrier à partir d’Outlook sur le Web ou Outlook 2010. Les administrateurs utilisent Windows PowerShell à distance pour désactiver cette stratégie ou pour configurer le niveau des données de calendrier de disponibilité que les utilisateurs peuvent partager. Les administrateurs peuvent également créer une relation organisationnelle organisationnelle avec une autre organisation fédérée, ce qui permet au niveau souhaité d’informations de disponibilité pour chaque utilisateur d’être visible, sans que des utilisateurs individuels aient besoin d’effectuer une invitation de partage. Dans l’étendue des stratégies de partage définies par l’administrateur et/ou les relations organisationnelles de l’organisation, les utilisateurs peuvent limiter individuellement les détails de leur partage. 
    
- **Partage de calendrier Internet** Exchange Online permet à ses utilisateurs de publier leurs calendriers au format iCal pour un accès anonyme par toute personne intérieure ou extérieure à l'organisation. Les destinataires peuvent utiliser Exchange, une autre plate-forme ou tout simplement un navigateur Web. Les utilisateurs Exchange Online peuvent également s’abonner à des calendriers que d’autres ont publiés sur les emplacements Internet via iCal. Ce partage de calendrier personnel diffère du partage de calendrier fédéré qui est configuré par un administrateur, et fournit un partage disponible/occupé d'organisation à organisation. Aucun utilisateur ne peut publier des données de calendrier au format iCal tant que l’administrateur n’a pas défini et appliqué une stratégie de partage l’autorisant. Les administrateurs peuvent désactiver la publication iCal et des abonnements iCal pour des utilisateurs d'une organisation à l'aide de Windows PowerShell à distance.
    
Pour plus d'informations sur le partage fédéré, consultez la rubrique [Partage dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 - Recherche de salles

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- Il est possible de créer une liste de salles à l'aide de Windows PowerShell à distance. 
    
- Tout groupe de distribution qui ne contient que des salles peut être converti en une liste de salles via Windows PowerShell à distance.
    
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  