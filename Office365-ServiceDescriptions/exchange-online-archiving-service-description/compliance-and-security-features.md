---
title: Fonctionnalités de conformité et de sécurité dans l’archivage Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132738"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Fonctionnalités de conformité et de sécurité dans l’archivage Exchange Online

## <a name="compliance-features-in-exchange-online-archiving"></a>Fonctionnalités de conformité dans l'archivage Exchange Online

Les sections suivantes décrivent les fonctionnalités de conformité de Microsoft Archivage Exchange Online.
  
### <a name="retention-policies"></a>Stratégies de rétention

Archivage Exchange Online offre des stratégies de rétention qui permettent aux organisations de limiter les possibilités associées à la messagerie et autres communications. Grâce à ces stratégies, les administrateurs peuvent appliquer des paramètres de rétention à des dossiers spécifiques dans les boîtes de réception des utilisateurs. Les administrateurs peuvent également donner aux utilisateurs un menu de stratégies de rétention et les autoriser à appliquer les stratégies à des éléments, des conversations ou des dossiers spécifiques à l’aide d’Outlook 2010 ou version ultérieure ou d’Outlook sur le Web. Dans l'Archivage Exchange Online, les administrateurs gèrent les stratégies de rétention à partir de l'infrastructure sur site.
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
Avec Outlook 2010 et versions ultérieures et Outlook sur le Web, les utilisateurs peuvent appliquer des stratégies de rétention à des dossiers, des conversations ou des messages individuels et peuvent également afficher les stratégies de rétention appliquées et les dates de suppression attendues sur les messages. Les utilisateurs des autres clients de messagerie peuvent également faire supprimer ou archiver des messages électroniques en fonction des stratégies de rétention côté serveur définies par l'administrateur, mais ils ne bénéficient pas du même niveau de visibilité et de contrôle.
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Archive permanente et mise en attente pour litige

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
Dans Exchange Online, vous pouvez utiliser la conservation inaltérable et la conservation pour litige pour accomplir les tâches suivantes :
  
- Permettre aux utilisateurs d'être bloqués et de conserver immuablement les éléments de boîte aux lettres
    
- Conserver les éléments de boîte aux lettres supprimés par les utilisateurs ou les processus de suppression automatique, tels que la gestion des enregistrements de messagerie (MRM)
    
- Protéger les éléments de boîte aux lettres de la falsification, de la modification par un utilisateur ou des processus automatiques en enregistrant une copie de l'élément d'origine
    
- Conserver les éléments indéfiniment ou pendant une durée spécifique
    
- Garantir la transparence de la conservation des messages pour l'utilisateur sans devoir suspendre la gestion des enregistrements de messagerie
    
- Utiliser la découverte électronique locale pour rechercher des éléments de boîte aux lettres, y compris les éléments mis en attente
    
En outre, vous pouvez utiliser la conservation inaltérable pour effectuer les actions suivantes :
  
- Rechercher et bloquer les éléments correspondants aux critères spécifiés
    
- Placer un utilisateur sous plusieurs conservations inaltérables pour différentes procédures ou enquêtes
    
> [!NOTE]
> Lorsque vous placez une boîte aux lettres en conservation inaltérable ou en conservation pour litige, la conservation porte à la fois sur la boîte aux lettres d'archivage et la boîte aux lettres principale. 
  
Pour plus d'informations, consultez la rubrique [Conservation inaltérable et conservation pour litige](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
> [!NOTE]
> Le quota par défaut pour le dossier Éléments récupérables est de 100 Go pour les utilisateurs de l'Archivage Exchange Online. 
  
### <a name="in-place-ediscovery"></a>Découverte électronique locale

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Fonctionnalités de sécurité dans l'archivage Exchange Online

Les sections suivantes décrivent les fonctionnalités de sécurité de Microsoft Archivage Exchange Online.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Chiffrement entre serveurs sur site et archivage Exchange Online

TLS est utilisé pour chiffrer la connexion entre les serveurs de messagerie pour aider à prévenir l'usurpation et assurer la confidentialité des messages en transit. TLS est également utilisé pour sécuriser le trafic de serveur de messagerie local vers des centres de distribution Microsoft pour l’archivage Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Chiffrement entre clients et archivage Exchange Online

Les connexions client à l'Archivage Exchange Online utilisent les méthodes de chiffrement suivantes pour améliorer la sécurité :
  
- Le protocole SSL est utilisé pour sécuriser Outlook, Outlook sur le Web et le trafic des services Web Exchange, à l’aide du port TCP 443.
    
- Les connexions client aux serveurs locaux ne changent pas avec l'introduction de l'Archivage Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Chiffrement : S/MIME et PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
De même, l'Archivage Exchange Online stocke les messages chiffrés à l'aide de solutions de chiffrement tierces côté client telles que Pretty Good Privacy (PGP).
  
### <a name="information-rights-management"></a>Gestion des droits relatifs à l’information

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Prise en charge d’IRM dans Outlook sur le Web

Les utilisateurs peuvent lire et créer des messages protégés par IRM en mode natif dans Outlook sur le Web, tout comme ils le peuvent dans Outlook. Les messages protégés par IRM dans Outlook sur le Web sont accessibles via Internet Explorer, Firefox, Safari et chrome (sans aucun plug-in requis). Les messages incluent la recherche en texte intégral, la vue conversation et le volet de visualisation. L'interopérabilité entre le serveur AD RMS (Active Directory Rights Management Services) et l'environnement Exchange sur site doit être configurée pour les activer.
  
#### <a name="irm-search"></a>Recherche de la Gestion des droits relatifs à l’information

Les messages protégés par la Gestion des droits relatifs à l'information (IRM) sont indexés et peuvent faire l'objet d'une recherche portant notamment sur les en-têtes, l'objet, le corps du message et les pièces jointes. Les utilisateurs peuvent rechercher des éléments protégés par IRM dans Outlook et Outlook sur le Web, et les administrateurs peuvent rechercher des éléments protégés par IRM à l’aide de la découverte électronique inaltérable ou de la cmdlet **Search-Mailbox** .
  
### <a name="auditing"></a>Audit

L'Archivage Exchange Online fournit deux types de fonctionnalités d'audit intégrées :
  
- **Journalisation d'audit de l'administrateur** La journalisation d'audit de l'administrateur permet aux clients de suivre les modifications apportées par leurs administrateurs dans l'environnement d'Archivage Exchange Online, notamment les modifications aux rôles RBAC ou aux stratégies et paramètres d'Exchange. 
    
- **Journalisation d'audit de boîte aux lettres** La journalisation d'audit de boîte aux lettres permet aux clients de suivre l'accès aux boîtes aux lettres par les utilisateurs autres que le propriétaire de la boîte aux lettres. 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, voir [Description du service d’archivage Exchange Online](exchange-online-archiving-service-description.md).
  

