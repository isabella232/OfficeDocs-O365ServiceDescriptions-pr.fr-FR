---
title: Fonctionnalités de conformité et de sécurité dans Archivage Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
description: Lisez cet article pour en savoir plus sur les fonctionnalités de conformité disponibles dans Microsoft Exchange Online’archivage.
ms.openlocfilehash: 0d424823116dd670c81628eaf85d1d553fdb5b8e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653086"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Fonctionnalités de conformité et de sécurité dans Archivage Exchange Online

## <a name="compliance-features-in-exchange-online-archiving"></a>Fonctionnalités de conformité dans l'archivage Exchange Online

Cet article décrit les fonctionnalités de conformité de Microsoft Exchange Online’archivage.
  
### <a name="retention-policies"></a>Stratégies de rétention

Archivage Exchange Online offre des stratégies de rétention qui permettent aux organisations de limiter les possibilités associées à la messagerie et autres communications. Grâce à ces stratégies, les administrateurs peuvent appliquer des paramètres de rétention à des dossiers spécifiques dans les boîtes de réception des utilisateurs. Les administrateurs peuvent également donner aux utilisateurs un menu de stratégies de rétention et les laisser appliquer les stratégies à des éléments, des conversations ou des dossiers spécifiques à l’aide de Outlook 2010 ou d’une Outlook sur le web. Dans l'Archivage Exchange Online, les administrateurs gèrent les stratégies de rétention à partir de l'infrastructure sur site.
  
L'Archivage Exchange Online offre deux types de stratégies : archiver et supprimer. Ces deux types peuvent être appliqués au même élément ou dossier. Par exemple, un utilisateur peut baliser un message électronique afin qu'il soit automatiquement transféré dans l'archive personnelle après un nombre spécifié de jours, puis supprimé après un autre nombre de jours.
  
Avec Outlook 2010 et les ultérieures et Outlook sur le web, les utilisateurs peuvent appliquer des stratégies de rétention à des dossiers, des conversations ou des messages individuels, et peuvent également afficher les stratégies de rétention appliquées et les dates de suppression attendues sur les messages. Les utilisateurs des autres clients de messagerie peuvent également faire supprimer ou archiver des messages électroniques en fonction des stratégies de rétention côté serveur définies par l'administrateur, mais ils ne bénéficient pas du même niveau de visibilité et de contrôle.
  
Les fonctionnalités de stratégie de rétention disponibles dans Archivage Exchange Online sont identiques à celles d'Exchange Server 2010 Service Pack 2 (SP2) et versions ultérieures. Les administrateurs peuvent gérer les stratégies de rétention à partir des environnements locaux Exchange Server 2010 et versions ultérieures. Les dossiers gérés, ancienne approche de la gestion des enregistrements de messagerie qui a été introduite dans Exchange 2007, ne sont pas disponibles dans l'archivage Exchange Online et sont incompatibles. Pour plus d'informations, reportez-vous à la rubrique [Balises et stratégies de rétention](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
  
### <a name="in-place-hold-and-litigation-hold"></a>Archive permanente et mise en attente pour litige

Lorsqu’une situation de litige est vraisemblablement à craindre, les organisations ont pour obligation de conserver les informations pertinentes qui sont stockées électroniquement (ESI), y compris la messagerie. Cette exigence de stockage de la correspondance électronique peut se faire ressentir avant que les détails précis du litige soient connus, et la conservation s’applique généralement à un grand nombre d’éléments. Les organisations peuvent conserver tous les messages électroniques concernant un sujet spécifique, ou tous les messages de certaines personnes.
  
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
  
Pour plus d'informations, consultez la rubrique [Conservation inaltérable et conservation pour litige](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
> [!NOTE]
> Le quota par défaut pour le dossier Éléments récupérables est de 100 Go pour les utilisateurs de l'Archivage Exchange Online. 
  
### <a name="in-place-ediscovery"></a>Découverte électronique locale

L'Archivage Exchange Online prend en charge la fonction eDiscovery inaltérable pour rechercher les contenus des boîtes aux lettres dans une organisation. Avec le Centre d'administration Exchange ou Windows PowerShell à distance à partir d'un serveur Exchange 2013 local, les administrateurs ou les gestionnaires de découverte autorisés peuvent rechercher dans une boîte aux lettres toutes sortes d'éléments, notamment des e-mails, des pièces jointes, des rendez-vous, des tâches et des contacts. La fonction eDiscovery inaltérable vous permet d'effectuer une recherche simultanément dans les archives et les boîtes aux lettres principales. Les fonctionnalités de filtrage avancé incluent l'expéditeur, le récepteur, le type de message, la date d'envoi, la date de réception, la copie carbone et la copie carbone invisible, ainsi que la syntaxe Keyword Query Language (KQL). Pour plus d'informations, voir [Découverte électronique locale](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
Le Centre d'administration Exchange et Windows PowerShell à distance vous permettent d'explorer jusqu'à 5 000 boîtes aux lettres à la fois lors d'une recherche eDiscovery inaltérable. Pour en savoir plus sur l'utilisation de Windows PowerShell à distance pour exécuter des recherches eDiscovery inaltérable, consultez la rubrique [New-MailboxSearch](/powershell/module/exchange/new-mailboxsearch). 
  
> [!NOTE]
> Dans Windows PowerShell à distance, vous pouvez utiliser la cmdlet  `Search-Mailbox` pour explorer plus de 5 000 boîtes aux lettres. Pour savoir comment explorer un grand nombre de boîtes aux lettres avec Windows PowerShell à distance, consultez la rubrique [Search-Mailbox](/powershell/module/exchange/search-mailbox). 
  
Les résultats de la recherche eDiscovery inaltérable peuvent être prévisualisés dans le Centre d'administration Exchange, exportés dans un fichier .pst ou copiés dans un type spécial de boîte aux lettres appelé boîte aux lettres de découverte. Les administrateurs ou les responsables de la mise en conformité peuvent se connecter à la boîte aux lettres de découverte pour consulter les messages. Pour en savoir plus, consultez la rubrique [Créer une recherche de découverte électronique inaltérable](/microsoft-365/compliance/content-search).
  
> [!NOTE]
> Lors de la copie des résultats de la recherche pour une recherche de découverte électronique locale réalisée dans des archives ou des boîtes aux lettres en nuage et sur site, vous devez sélectionner une boîte aux lettres de découverte sur site. Les messages de la boîte aux lettres principale sur site et de l'archive en nuage sont copiés dans la boîte aux lettres de découverte sur site. 
  
Les administrateurs peuvent également rechercher et supprimer des messages inappropriés envoyés à plusieurs boîtes aux lettres dans leurs organisations. Par exemple, si des informations confidentielles concernant les salaires ont été accidentellement envoyées à tous les collaborateurs, un administrateur peut supprimer ce message des boîtes aux lettres des utilisateurs. Ce type de recherche n'est pas disponible dans le Centre d'administration Exchange. Elle doit être effectuée à l'aide de l'environnement PowerShell à distance. Pour savoir comment supprimer des messages des boîtes aux lettres des utilisateurs, consultez la rubrique [Rechercher et supprimer des messages dans Exchange 2016](/Exchange/policy-and-compliance/ediscovery/delete-messages).
  
## <a name="security-features-in-exchange-online-archiving"></a>Fonctionnalités de sécurité dans l'archivage Exchange Online

Les sections suivantes décrivent les fonctionnalités de sécurité de Microsoft Archivage Exchange Online.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Chiffrement entre serveurs sur site et archivage Exchange Online

TLS est utilisé pour chiffrer la connexion entre les serveurs de messagerie pour aider à prévenir l'usurpation et assurer la confidentialité des messages en transit. TLS est également utilisé pour sécuriser le trafic du serveur de messagerie local vers les centres de données Microsoft pour les Archivage Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Chiffrement entre clients et archivage Exchange Online

Les connexions client à l'Archivage Exchange Online utilisent les méthodes de chiffrement suivantes pour améliorer la sécurité :
  
- SSL est utilisé pour sécuriser les Outlook, les Outlook sur le web et le trafic Exchange Services Web, à l’aide du port TCP 443.
    
- Les connexions client aux serveurs locaux ne changent pas avec l'introduction de l'Archivage Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Chiffrement : S/MIME et PGP

L'Archivage Exchange Online stocke les messages Secure/Multipurpose Internet Mail Extensions (S/MIME). Toutefois, l'Archivage Exchange Online n'héberge pas les fonctionnalités S/MIME ou les clés publiques, et ne fournit ni référentiel de clés, ni gestion des clés, ni services d'annuaire de clés car tous ces services sont liés à l'infrastructure Exchange sur site.
  
De même, l'Archivage Exchange Online stocke les messages chiffrés à l'aide de solutions de chiffrement tierces côté client telles que Pretty Good Privacy (PGP).
  
### <a name="information-rights-management"></a>Gestion des droits relatifs à l’information

L'Archivage Exchange Online ne fournit pas de services de Gestion des droits relatifs à l'information (IRM), mais les administrateurs peuvent utiliser des services AD RMS (Active Directory Rights Management Services). Si un serveur AD RMS est déployé, Outlook peut communiquer directement avec ce serveur, en permettant aux utilisateurs de composer et de lire les messages protégés par IRM. Si l'interopérabilité entre le serveur AD RMS et l'environnement Exchange sur site est configurée, les utilisateurs pourront composer et lire les messages protégés par IRM.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Prise en charge de la gestion des Outlook sur le web

Les utilisateurs peuvent lire et créer des messages protégés par IRM en natif dans Outlook sur le web, comme ils le peuvent dans Outlook. Les messages protégés par IRM Outlook sur le web sont accessibles via Internet Explorer, Firefox, Safari et Chrome (sans plug-in requis). Les messages incluent la recherche en texte intégral, la vue conversation et le volet de visualisation. L'interopérabilité entre le serveur AD RMS (Active Directory Rights Management Services) et l'environnement Exchange sur site doit être configurée pour les activer.
  
#### <a name="irm-search"></a>Recherche de la Gestion des droits relatifs à l’information

Les messages protégés par la Gestion des droits relatifs à l'information (IRM) sont indexés et peuvent faire l'objet d'une recherche portant notamment sur les en-têtes, l'objet, le corps du message et les pièces jointes. Les utilisateurs peuvent rechercher des éléments protégés par IRM dans Outlook et Outlook sur le web, et les administrateurs peuvent rechercher des éléments protégés par IRM à l’aide de In-Place eDiscovery ou de la cmdlet **Search-Mailbox.**
  
### <a name="auditing"></a>Audit

L'Archivage Exchange Online fournit deux types de fonctionnalités d'audit intégrées :
  
- **Enregistrement d’audit** administrateur : la journalisation d’audit de l’administrateur permet aux clients de suivre les modifications apportées par leurs administrateurs dans l’environnement Archivage Exchange Online, y compris les modifications apportées aux rôles RBAC ou aux stratégies et paramètres Exchange. 
    
- **Enregistrement d’audit de boîte** aux lettres : l’enregistrement d’audit des boîtes aux lettres permet aux clients de suivre l’accès aux boîtes aux lettres par des utilisateurs autres que le propriétaire de la boîte aux lettres. 
    
Plusieurs rapports d'audit prédéfinis sont disponibles dans le centre d'administration Exchange, notamment Modifications de rôles d'administrateur, Mise en attente pour litige et Accès à des boîtes aux lettres par des non-propriétaires. Les administrateurs peuvent filtrer les rapports par date et par rôle, et peuvent exporter tous les événements d'audit pour les boîtes aux lettres spécifiées au format XML pour une rétention à long terme ou une génération de rapports personnalisés.
  
Par défaut, la journalisation d'audit de l'administrateur est activée et l'enregistrement d'audit des boîtes aux lettres est désactivé. Les administrateurs peuvent utiliser Windows PowerShell à distance pour activer l'enregistrement d'audit des boîtes aux lettres pour tout ou partie des boîtes aux lettres de leur organisation. Pour plus d'informations, consultez la rubrique [Rapports d'audit Exchange](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir [Archivage Exchange Online description du service.](exchange-online-archiving-service-description.md)
