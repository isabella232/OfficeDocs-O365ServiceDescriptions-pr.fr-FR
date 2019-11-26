---
title: Stratégie et conformité de message
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 88b02766477284ff46f69a6cedb2468ff08ff1b1
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262577"
---
# <a name="message-policy-and-compliance"></a>Stratégie et conformité de message

## <a name="archiving-exchange-online-based-mailboxes"></a>Archivage de boîtes aux lettres Exchange Online

Les boîtes aux lettres Exchange Online résident dans le nuage. Pour les archiver, vous nécessitez d'environnements d'hébergement uniques. Dans certains cas, Exchange Online peut également être utilisé pour archiver des boîtes aux lettres locales dans le nuage. Les options d'archivage d'Exchange Online sont décrites dans cette section.
  
Exchange Online intègre des fonctionnalités d'archivage pour les boîtes aux lettres en nuage, notamment la fonction d'archivage sur place qui fournit aux utilisateurs un emplacement pratique dans lequel ils peuvent stocker d'anciens messages électroniques. Une archive inaltérable est un type spécial de boîte aux lettres qui apparaît à côté des dossiers de boîte aux lettres principale d’un utilisateur dans Outlook et Outlook sur le Web. Les utilisateurs peuvent accéder à l'archive et l'explorer de la même manière que pour leurs boîtes aux lettres principales. Les fonctionnalités disponibles varient en fonction du client utilisé :
  
- **Outlook 2016, outlook 2013, outlook 2010 et Outlook sur le Web** Les utilisateurs ont accès aux fonctionnalités complètes de l’archive, ainsi qu’aux fonctionnalités de conformité associées, telles que le contrôle des stratégies de rétention et d’archivage. 
    
- **Outlook 2007** Les utilisateurs bénéficient d'une assistance élémentaire pour l'archivage local, et certaines fonctionnalités d'archivage et de conformité ne sont pas disponibles. Par exemple, les utilisateurs ne peuvent pas appliquer de stratégies de rétention ou d'archivage aux éléments de boîte aux lettres, et doivent se baser sur des stratégies configurées par l'administrateur 
    
Les administrateurs utilisent le Centre d'administration Exchange ou l'application Windows PowerShell distante pour activer la fonctionnalité d'archivage personnel pour des utilisateurs spécifiques.
  
Pour plus d'informations, voir les pages suivantes :
  
- [Boîtes aux lettres d'archivage dans Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [Activer ou désactiver une boîte aux lettres d'archivage dans Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Tailles de l'archive

Il n'est possible de stocker les données de messagerie que d'un seul utilisateur dans chaque archive personnelle. L'allocation de l'espace de stockage dépend du plan d'abonnement. Pour plus d’informations sur la taille des boîtes aux lettres d’archivage, consultez la section « limites de stockage des boîtes aux lettres » dans [limites d’Exchange Online](exchange-online-limits.md).
  
> [!IMPORTANT]
> - L'utilisation de la fonction de journalisation, des règles de transport ou des règles de transfert automatique pour copier des messages dans une boîte aux lettres Exchange Online à des fins d'archivage n'est pas autorisée. Microsoft se réserve le droit de refuser l'archivage illimité dans les cas où une archive de boîte aux lettres n'est pas utilisée dans un scénario personnel. 
> - L'archivage local exige impose certaines conditions de licence aux utilisateurs d'Outlook. Les utilisateurs d'Outlook 2007 doivent disposer de la mise à jour cumulative Office 2007 de février 2011 pour pouvoir accéder à leur archive personnelle. 
> - Exchange Online ne prend pas en charge l’applet de commande Windows PowerShell _New-MailboxImportRequest_ d’exchange Server 2010 Service Pack 1 ou une version ultérieure pour l’importation par un administrateur de fichiers. pst dans une archive personnelle. Si la boîte aux lettres principale et l'archive de l'utilisateur se situent dans Exchange Online, un administrateur peut utiliser PST Capture, un outil gratuit qui permet d'importer les données du fichier .pst bers la boîte aux lettres ou l'archive principale de l'utilisateur.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Archivage en nuage de boîtes aux lettres locales

L'utilisation d'Exchange Online pour l'archivage en nuage de boîtes aux lettres locales Exchange Server 2010 ou version ultérieure est possible avec Microsoft Exchange Online Archiving, une solution d'archivage hébergée de Microsoft. Cette dernière requiert que l'organisation locale soit en mode hybride ou configurée pour Exchange Online Archiving.
  
> [!IMPORTANT]
> Les utilisateurs possédant une boîte aux lettres locale sur un serveur de boîtes aux lettres Exchange 2010 et ayant appliqué une stratégie Dossier géré ne peuvent pas activer une archive sur place locale ou en nuage. 
  
## <a name="retention-tags-and-retention-policies"></a>Balises et stratégies de rétention

Exchange Online offre des stratégies de rétention qui permettent aux organisations de limiter les possibilités associées à la messagerie et autres communications. Grâce à ces stratégies, les administrateurs peuvent appliquer des paramètres de rétention à des dossiers spécifiques dans les boîtes de réception des utilisateurs. Les administrateurs peuvent également donner aux utilisateurs un menu de stratégies de rétention et les autoriser à appliquer les stratégies à des éléments, des conversations ou des dossiers spécifiques à l’aide d’Outlook 2010 ou version ultérieure ou d’Outlook sur le Web.
  
Dans Exchange Online, les administrateurs gèrent les stratégies de rétention à l'aide du Centre d'administration Exchange (CAE) ou de l'application Windows PowerShell distante.
  
Exchange Online propose deux types de stratégies : les stratégies d'archivage et les stratégies de suppression. Ces deux types peuvent être combinés sur le même élément ou dossier. Par exemple, un utilisateur peut baliser un message électronique afin de le déplacer automatiquement vers l'archive locale dans un certain nombre de jours et le supprimer après quelques jours d'intervalle.
  
Avec Outlook 2010 ou une version ultérieure et Outlook sur le Web, les utilisateurs peuvent appliquer des stratégies de rétention à des dossiers, des conversations ou des messages individuels. Ils peuvent également visualiser les stratégies de rétention appliquées et les dates de suppression prévues des messages. Les utilisateurs d'autres clients de messagerie peuvent uniquement archiver ou supprimer des messages électroniques en fonction des stratégies de rétention côté serveur définies par l'administrateur.
  
Les fonctionnalités de stratégie de rétention disponibles dans Exchange Online sont identiques à celles d'Exchange Server 2010 Service Pack 2 RU4. Les administrateurs peuvent utiliser Windows PowerShell à distance pour migrer les stratégies de rétention des environnements locaux Exchange Server 2010 ou version ultérieure vers Exchange Online.
  
> [!IMPORTANT]
> Les dossiers gérés, une approche plus ancienne de la gestion des enregistrements de messagerie qui a été introduite dans Exchange Server 2007, ne sont pas disponibles dans Exchange Online. 
  
Pour plus d'informations, consultez la rubrique [Balises et stratégies de rétention](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Chiffrement des données lors de leur stockage

Le chiffrement des données client Office 365 au repos est assuré par plusieurs technologies côté service, notamment BitLocker, DKM, le chiffrement de service de stockage Azure et le chiffrement de service dans Exchange Online, Skype entreprise, OneDrive entreprise et SharePoint Online. Le chiffrement de service Office 365 inclut une option permettant d’utiliser des clés de chiffrement gérées par le client qui sont stockées dans Azure Key Vault. Cette option de clé gérée par le client, appelée [clé client Office 365](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697), est disponible pour Exchange Online, SharePoint Online et OneDrive entreprise. 
  
### <a name="bitlocker"></a>BitLocker

Les serveurs Office 365 utilisent BitLocker pour chiffrer les lecteurs de disque contenant des données client au repos au niveau du volume. Le chiffrement BitLocker est une fonctionnalité de protection des données intégrée à Windows. BitLocker est l’une des technologies utilisées pour se protéger contre les menaces en cas de chute d’autres processus ou contrôles (par exemple, le contrôle d’accès ou le recyclage du matériel) susceptibles d’entraîner l’accès physique à des disques contenant des données client. Dans ce cas, BitLocker élimine le risque de vol ou d’exposition des données en raison d’ordinateurs et de disques perdus, volés ou incorrectement mis en service. 
  
### <a name="distributed-key-manager"></a>Gestionnaire de clés distribuées

En plus de BitLocker, nous utilisons une technologie appelée gestionnaire de clés distribuées (DKM). DKM est une fonctionnalité côté client qui utilise un ensemble de clés secrètes pour chiffrer et déchiffrer les informations. Seuls les membres d’un groupe de sécurité spécifique dans les services de domaine Active Directory peuvent accéder à ces clés pour déchiffrer les données chiffrées par DKM. Dans Exchange Online, seuls certains comptes de service sous lesquels les processus Exchange sont exécutés font partie de ce groupe de sécurité. Dans le cadre de la procédure opérationnelle standard dans le centre de données, les informations d’identification qui font partie de ce groupe de sécurité ne sont communiquées à aucun être humain, et par conséquent aucun être humain n’a accès aux clés qui peuvent déchiffrer les informations confidentielles.
  
## <a name="customer-key"></a>Clé client

Avec la clé client, vous contrôlez les clés de chiffrement de votre organisation, puis vous configurez Office 365 afin de les utiliser pour chiffrer vos données au repos dans les centres de données de Microsoft. Les données au repos incluent les données issues d’Exchange Online et de Skype Entreprise qui sont enregistrées dans des boîtes aux lettres et des fichiers stockés dans SharePoint Online et OneDrive Entreprise. Pour plus d’informations, reportez-vous à [la rubrique contrôle de vos données dans office 365 utilisation de la clé client](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key) et du [chiffrement de service avec la clé client pour Office 365](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq).
  
## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365

Le chiffrement de messages Office 365 permet aux utilisateurs de messagerie d’envoyer des messages électroniques chiffrés à quiconque. Nous avons annoncé de nouvelles fonctionnalités dans le chiffrement de messages Office qui tirent parti des fonctionnalités de protection dans Azure information Encryption. Ces nouvelles fonctionnalités ont fourni des expériences utilisateur améliorées qui facilitent le partage et la collaboration sur des messages protégés avec une personne à l’intérieur ou à l’extérieur de l’organisation. Les nouvelles fonctionnalités de chiffrement des messages Office ont quelques exigences de configuration. Consultez la rubrique Set up New Office 365 message Encryption Capabilities Built-Top of Azure information protection. Les clients sur le chiffrement de messages Office 365 hérité n’obtiennent pas les nouvelles fonctionnalités sans suivre les conseils de configuration fournis ci-dessus. Pour plus d’informations sur ce qui est inclus dans les nouvelles fonctionnalités de chiffrement des messages Office 365, consultez le [Forum aux questions](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) . 

Le chiffrement de messages avancé Office 365 offre une protection supplémentaire en autorisant l’expiration et la révocation des messages.  Vous pouvez également créer plusieurs modèles pour les messages électroniques chiffrés provenant de votre organisation.  Le chiffrement de messages avancé est inclus dans Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (tarification du personnel pour les personnes travaillant), Office 365 entreprise E5 (tarification du personnel pour les personnes à but lucratif) ou Office 365 éducation a5. Si votre organisation dispose d’un abonnement Office 365 qui n’inclut pas le chiffrement de messages avancé Office 365, vous pouvez acheter la conformité Microsoft 365 E5 ou le SKU Office 365 Advanced Compliance en tant que module complémentaire.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>S/MIME (Secure/Multipurpose Internet Mail Extension)

S/MIME vous aider à protéger les informations sensibles en envoyant un message signé et chiffré au sein de votre organisation. Les administrateurs peuvent utiliser une session distante de Windows PowerShell pour configurer S/MIME après avoir établi et émis des certificats PKI pour les utilisateurs. Ces certificats doivent être synchronisés à partir d'un service local de certificats Active Directory.
  
S/MIME est pris en charge sur Microsoft Edge et Internet Explorer 11. Actuellement, S/MIME n'est pas pris en charge sur Firefox, Opera et Chrome. Pour plus d'informations, consultez la rubrique [S/MIME pour la signature et le chiffrement des messages](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Archive permanente et mise en attente pour litige

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
  
Pour plus d'informations, consultez la rubrique [Conservation inaltérable et conservation pour litige](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>Découverte électronique locale

Exchange Online permet aux clients d’effectuer des recherches dans le contenu des boîtes aux lettres au sein d’une organisation à l’aide d’une interface Web. Les administrateurs ou les responsables de la conformité et de la sécurité qui sont autorisés à effectuer des recherches de découverte électronique locale (par affectation) peuvent rechercher dans les messages électroniques, les pièces jointes, les rendez-vous de calendrier, les tâches, les contacts et d'autres éléments. La découverte électronique locale permet d'effectuer une recherche simultanément dans les archives et les boîtes aux lettres principales. Les fonctionnalités de filtrage avancé incluent l'expéditeur, le destinataire, le type de message, la date d'envoi/de réception, la copie carbone/copie carbone invisible ainsi que la syntaxe KQL. Les résultats de la recherche incluent également des éléments du dossier Éléments supprimés s'ils correspondent à la requête de recherche.
  
Les résultats des recherches de découverte électronique locale peuvent être prévisualisés dans l'interface web, exportés dans un fichier PST, ou copiés dans un type spécial de boîte aux lettres appelé boîte aux lettres de découverte. Une boîte aux lettres de découverte présente un quota de 50 Go pour le stockage des résultats de la recherche. Les administrateurs peuvent également connecter Outlook à la boîte aux lettres de découverte pour accéder aux résultats de la recherche et les exporter dans un fichier .pst.
  
Les administrateurs peuvent utiliser le Centre d'administration Exchange ou l'application Windows PowerShell distante pour effectuer des recherches dans plusieurs boîtes aux lettres. Le Centre d'administration Exchange peut fournir un aperçu en lecture seule des résultats de recherche, en permettant aux administrateurs de vérifier rapidement une recherche et de la réexécuter, si nécessaire, avec différents paramètres. Après avoir optimisé une recherche, l'administrateur peut copier les résultats dans la boîte aux lettres de découverte.
  
Par défaut, une boîte aux lettres de découverte est créée pour chaque organisation. Toutefois, les administrateurs peuvent créer des boîtes aux lettres de découverte supplémentaires à l'aide de Windows PowerShell à distance. Les boîtes aux lettres de découverte ne peuvent pas être utilisées à d'autres fins que le stockage des résultats de recherche de découverte électronique locale.
  
Les administrateurs peuvent utiliser le Centre d'administration Exchange ou l'application Windows PowerShell distante pour effectuer des recherches de découverte électronique locale. Le Centre d'administration Exchange peut fournir un aperçu en lecture seule des résultats de recherche, en permettant aux administrateurs de vérifier rapidement une recherche et de la réexécuter, si nécessaire, avec différents paramètres. Après avoir optimisé une recherche, l'administrateur peut copier les résultats dans la boîte aux lettres de découverte, ou exporter les résultats de la recherche dans un fichier .PST.
  
Les administrateurs peuvent utiliser le centre d'administration Exchange ou Windows PowerShell à distance pour effectuer des recherches dans 10 000 boîtes aux lettres à la fois lors d'une recherche de découverte électronique locale. 
  
Dans Exchange Online, les utilisateurs autorisés peuvent exécuter la découverte électronique sur place et choisir l'une des actions suivantes :
  
- **Estimation des résultats de recherche** Obtenez une estimation du nombre de messages renvoyés par la recherche, y compris les statistiques de mots clés pour déterminer l'efficacité des mots clés utilisés dans la recherche et modifiez les paramètres de recherche le cas échéant. 
    
- **Aperçu des résultats de la recherche**
    
- Copiez les messages renvoyés dans les résultats de recherche à une boîte aux lettres de découverte.
    
Pour plus d'informations, consultez la rubrique [Découverte électronique locale](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Règles de flux de messagerie

Vous pouvez utiliser des règles de flux de messagerie pour rechercher des conditions spécifiques sur les messages qui transitent par votre organisation et qui agissent sur ces dernières. Les règles de flux de messagerie vous permettent d’appliquer des stratégies de messagerie aux messages électroniques, aux messages sécurisés, à la protection des systèmes de messagerie et à la prévention des fuites d’informations.
  
En raison d'obligations légales, d'exigences réglementaires ou de stratégies d'entreprise, de nombreuses organisations sont tenues d'appliquer des stratégies de messagerie afin de limiter l'interaction entre les destinataires et les expéditeurs, à l'intérieur et à l'extérieur de l'organisation. Outre la limitation des interactions entre individus, groupes de service au sein de l'organisation et autres entités externes à celle-ci, certaines organisations sont également sujettes aux exigences suivantes en relation avec la stratégie de messagerie :
  
- blocage du contenu inapproprié entrant ou sortant
    
- filtrage des informations confidentielles de l'organisation
    
- Suivi ou archivage des messages échangés avec des individus spécifiques
    
- redirection des messages entrants et sortants pour inspection avant remise
    
- application de dédits de responsabilité à des messages transitant par l'organisation
    
> [!IMPORTANT]
> Les types de fichiers de pièces jointes qui nécessitent l’installation de iFilters tiers sur le serveur de messagerie (par exemple, Adobe. pdf) ne peuvent pas être inspectés à l’aide des règles de flux de messagerie jusqu’à ce qu’un iFilter approprié soit installé. Pour plus d’informations sur les types de fichiers pris en charge par les règles de flux de messagerie, voir [utiliser des règles de flux de messagerie pour inspecter les pièces jointes des messages dans Office 365](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Pour plus d’informations sur les règles de flux de messagerie, consultez la rubrique [Mail flow rules in Exchange 2016](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Protection contre la perte de données

La fonctionnalité de protection contre la perte de données (DLP) vous permet d'identifier, de contrôler et de protéger les informations sensibles de votre organisation via une analyse de contenu approfondie. DLP est une fonctionnalité haut de gamme de plus en plus importante pour les systèmes de message d'entreprise car la messagerie essentielle comprend des données sensibles qui doivent être protégées. La fonctionnalité DLP dans Exchange Online vous permet de protéger les données sensibles sans affecter la productivité des travailleurs.
  
Vous pouvez configurer les stratégies DLP dans l'interface de gestion du Centre d'administration Exchange (CAE), qui vous permet de réaliser les opérations suivantes : 
  
- Démarrer avec un modèle de stratégie préconfigurée qui vous permet de détecter des types spécifiques d'informations sensibles, tels que des données PCI-DSS, des données Gramm-Leach-Bliley Act ou même des informations d'identification personnelle spécifiques aux paramètres régionaux.
    
- Exploiter toute la puissance des critères et des actions de règles de transport existants et ajouter de nouvelles règles de transport.
    
- Tester l'efficacité de vos stratégies DLP avant de les appliquer pleinement.
    
- Incorporer vos propres modèles de stratégie DLP personnalisés et types d'informations sensibles.
    
- Détecter des informations sensibles dans les pièces jointes, le corps du texte ou les lignes d’objet des messages, et ajuster le niveau de confiance à partir duquel Exchange Online agit.
    
- Détecter les données de formulaire sensibles à l'aide de la création d'empreintes digitales document. La création d'empreintes digitales document vous permet de créer facilement des types d'informations sensibles personnalisés à partir des formulaires texte que vous pouvez utiliser pour définir des règles de transport et des stratégies de protection contre la perte de données.
    
- Ajoutez des conseils de stratégie, qui peuvent aider à réduire les pertes de données en affichant un avertissement pour les utilisateurs d’Outlook 2016, Outlook 2013, Outlook sur le Web et OWA pour les appareils et peuvent également améliorer l’efficacité de vos stratégies en autorisant la création de rapports faux positifs. 
    
- Examiner les données relatives aux incidents dans les rapports DLP ou ajouter vos propres rapports spécifiques à l'aide d'une action de génération de rapports d'incidents.
    
Pour plus d'informations sur la stratégie DLP, consultez la rubrique [Protection contre la perte de données](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Journalisation

Vous pouvez configurer Exchange Online pour journaliser des copies de messages électroniques dans n'importe quelle boîte aux lettres externe pouvant recevoir des messages via SMTP. La journalisation peut aider votre organisation à répondre aux exigences réglementaires, légales et de conformité organisationnelle en enregistrant les communications électroniques échangées. Lors de la planification de la rétention et de la conformité de la messagerie, il est important de bien comprendre la journalisation, son intégration dans les stratégies de conformité de votre organisation et la sécurisation des messages journalisés à l'aide de votre organisation.
  
Vous pouvez gérer les règles de journal à l'aide du Centre d'administration Exchange ou de l'application Windows PowerShell distante. Vous pouvez configurer la journalisation en fonction de la liste d'utilisateurs ou de distribution, et choisir de ne consigner que les messages internes, les messages externes, ou les deux. Les messages journalisés incluent non seulement le message d'origine, mais également des informations sur l'expéditeur, les destinataires, les copies et les copies invisibles.
  
Pour garantir la réussite et la fiabilité de la solution de journalisation, vous devez effectuer les tâches suivantes :
  
- Assurez-vous que la destination de journalisation n’est pas une boîte aux lettres Exchange Online.
    
- Créez dans le répertoire de clients un objet contact pour l'adresse de messagerie cible SMTP à utiliser pour la journalisation.
    
- Créez un deuxième objet contact sous forme de boîte aux lettres de journal alternative pour capturer tous les états de journal lorsque la boîte aux lettres de journal principale n'est pas disponible.
    
- Maintenir des niveaux de gestion, de redondance, de disponibilité, de performances et de fonctionnalité adaptés à la cible SMTP pour garantir la réussite de l’acceptation des messages.
    
- Assurez l'interopérabilité respective avec le transport Exchange Server et Exchange, notamment les formats de message, l'intégration des informations sur l'expéditeur/destinataire et la conversion appropriée du contenu.
    
Pour plus d'informations sur la journalisation, consultez la rubrique [Journalisation](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  

