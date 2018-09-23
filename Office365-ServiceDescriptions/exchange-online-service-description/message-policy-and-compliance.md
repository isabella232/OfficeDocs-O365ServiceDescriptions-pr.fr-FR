---
title: Stratégie et conformité de message
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: fd5062df19298720417566d91667f3c3b237b164
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035706"
---
# <a name="message-policy-and-compliance"></a>Stratégie et conformité de message

## <a name="archiving-exchange-online-based-mailboxes"></a>Archivage de boîtes aux lettres Exchange Online

Les boîtes aux lettres Exchange Online résident dans le nuage. Pour les archiver, vous nécessitez d'environnements d'hébergement uniques. Dans certains cas, Exchange Online peut également être utilisé pour archiver des boîtes aux lettres locales dans le nuage. Les options d'archivage d'Exchange Online sont décrites dans cette section.
  
Exchange Online intègre des fonctionnalités d'archivage pour les boîtes aux lettres en nuage, notamment la fonction d'archivage sur place qui fournit aux utilisateurs un emplacement pratique dans lequel ils peuvent stocker d'anciens messages électroniques. La fonction d'archivage sur place est un type spécial de boîte aux lettres qui apparaît à côté des dossiers de boîtes aux lettres principales d'un utilisateur dans Outlook et Outlook Web App. Les utilisateurs peuvent accéder à l'archive et l'explorer de la même manière que pour leurs boîtes aux lettres principales. Les fonctionnalités disponibles varient en fonction du client utilisé :
  
- **Outlook 2016, Outlook 2013, Outlook 2010 et Outlook Web App** Les utilisateurs ont accès aux fonctionnalités complètes de l'archive, ainsi qu'aux fonctionnalités de conformité correspondantes, telles que le contrôle des stratégies de rétention et d'archivage. 
    
- **Outlook 2007** Les utilisateurs bénéficient d'une assistance élémentaire pour l'archivage local, et certaines fonctionnalités d'archivage et de conformité ne sont pas disponibles. Par exemple, les utilisateurs ne peuvent pas appliquer de stratégies de rétention ou d'archivage aux éléments de boîte aux lettres, et doivent se baser sur des stratégies configurées par l'administrateur 
    
Les administrateurs utilisent le Centre d'administration Exchange ou l'application Windows PowerShell distante pour activer la fonctionnalité d'archivage personnel pour des utilisateurs spécifiques.
  
Pour plus d'informations, voir les pages suivantes :
  
- [Boîtes aux lettres d'archivage dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421)
    
- [Activer ou désactiver une boîte aux lettres d'archivage dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425)
    
### <a name="archive-sizes"></a>Tailles de l'archive

Il n'est possible de stocker les données de messagerie que d'un seul utilisateur dans chaque archive personnelle. L'allocation de l'espace de stockage dépend du plan d'abonnement. Pour plus d'informations sur les tailles de boîtes aux lettres d'archivage, consultez la section « Limites de stockage des boîtes aux lettres » dans la rubrique [Limites d'Exchange Online](exchange-online-limits.md).
  
> [!IMPORTANT]
> L'utilisation de la fonction de journalisation, des règles de transport ou des règles de transfert automatique pour copier des messages dans une boîte aux lettres Exchange Online à des fins d'archivage n'est pas autorisée. Microsoft se réserve le droit de refuser l'archivage illimité dans les cas où une archive de boîte aux lettres n'est pas utilisée dans un scénario personnel. > L'archivage local exige impose certaines conditions de licence aux utilisateurs d'Outlook. Les utilisateurs d'Outlook 2007 doivent disposer de la mise à jour cumulative Office 2007 de février 2011 pour pouvoir accéder à leur archive personnelle. > Exchange Online ne prend pas en charge la cmdlet  _New-MailboxImportRequest_ Windows PowerShell d'Exchange Server 2010 Service Pack 1 ou version ultérieure pour l'importation de fichiers .pst dans une archive personnelle effectuée par l'administrateur. Si la boîte aux lettres principale et l'archive de l'utilisateur se situent dans Exchange Online, un administrateur peut utiliser PST Capture, un outil gratuit qui permet d'importer les données du fichier .pst bers la boîte aux lettres ou l'archive principale de l'utilisateur. 
  
## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Archivage en nuage de boîtes aux lettres locales

L'utilisation d'Exchange Online pour l'archivage en nuage de boîtes aux lettres locales Exchange Server 2010 ou version ultérieure est possible avec Microsoft Exchange Online Archiving, une solution d'archivage hébergée de Microsoft. Cette dernière requiert que l'organisation locale soit en mode hybride ou configurée pour Exchange Online Archiving.
  
> [!IMPORTANT]
> Les utilisateurs possédant une boîte aux lettres locale sur un serveur de boîtes aux lettres Exchange 2010 et ayant appliqué une stratégie Dossier géré ne peuvent pas activer une archive sur place locale ou en nuage. 
  
## <a name="retention-tags-and-retention-policies"></a>Balises et stratégies de rétention

Exchange Online offre des stratégies de rétention qui permettent aux organisations de limiter les possibilités associées à la messagerie et autres communications. Grâce à ces stratégies, les administrateurs peuvent appliquer des paramètres de rétention à des dossiers spécifiques dans les boîtes de réception des utilisateurs. Les administrateurs peuvent également fournir aux utilisateurs un menu de stratégies de rétention et leur permettre d'appliquer les stratégies à des éléments, des conversations ou des dossiers spécifiques à l'aide d'Outlook 2010 ou version ultérieure ou d'Outlook Web App.
  
Dans Exchange Online, les administrateurs gèrent les stratégies de rétention à l'aide du Centre d'administration Exchange (CAE) ou de l'application Windows PowerShell distante.
  
Exchange Online propose deux types de stratégies : les stratégies d'archivage et les stratégies de suppression. Ces deux types peuvent être combinés sur le même élément ou dossier. Par exemple, un utilisateur peut baliser un message électronique afin de le déplacer automatiquement vers l'archive locale dans un certain nombre de jours et le supprimer après quelques jours d'intervalle.
  
Dans Outlook 2010 ou version ultérieure et Outlook Web App, les utilisateurs peuvent appliquer des stratégies de rétention à des dossiers, des conversations ou des messages individuels. Ils peuvent également visualiser les stratégies de rétention appliquées et les dates de suppression prévues des messages.  Les utilisateurs d'autres clients de messagerie peuvent uniquement archiver ou supprimer des messages électroniques en fonction des stratégies de rétention côté serveur définies par l'administrateur.
  
Les fonctionnalités de stratégie de rétention disponibles dans Exchange Online sont identiques à celles d'Exchange Server 2010 Service Pack 2 RU4. Les administrateurs peuvent utiliser Windows PowerShell à distance pour migrer les stratégies de rétention des environnements locaux Exchange Server 2010 ou version ultérieure vers Exchange Online.
  
> [!IMPORTANT]
> Les dossiers gérés, une approche plus ancienne de la gestion des enregistrements de messagerie qui a été introduite dans Exchange Server 2007, ne sont pas disponibles dans Exchange Online. 
  
Pour plus d'informations, consultez la rubrique [Balises et stratégies de rétention](https://go.microsoft.com/fwlink/p/?LinkId=271745).
  
## <a name="encryption-of-data-at-rest"></a>Chiffrement des données au repos

Chiffrement des données du client Office 365 au repos est fourni par plusieurs technologies côté service, y compris BitLocker, DKM, chiffrement de Service de stockage Azure et le chiffrement de service dans Exchange Online, Skype pour les entreprises, OneDrive pour les entreprises et SharePoint En ligne. Office 365 Service chiffrement inclut une option pour utiliser des clés de chiffrement gérés par le client qui sont stockés dans Azure clé coffre-fort. Cette option clée client géré, appelée [Clé de client Office 365](https://go.microsoft.com/fwlink/?linkid=863349), est disponible pour Exchange Online, SharePoint Online et OneDrive for Business. 
  
### <a name="bitlocker"></a>BitLocker

Serveurs Office 365 utilisent BitLocker pour chiffrer les lecteurs de disque contenant des données au repos au niveau du volume du client. Le chiffrement BitLocker est une fonctionnalité de protection de données qui est intégrée à Windows. BitLocker est une des technologies utilisées pour protéger contre les menaces au cas où l’indisponibilité dans d’autres processus ou les contrôles (par exemple, contrôle d’accès ou de recyclage du matériel) qui peuvent amener à une personne physique accéder sur les disques contenant les données du client. Dans ce cas, BitLocker élimine le risque de vol de données ou l’exposition en raison de disques et les ordinateurs perdus, volés ou mis hors service. 
  
### <a name="distributed-key-manager"></a>Gestionnaire de clés distribuées

En plus de BitLocker, nous utilisons une technologie appelée Gestionnaire de clé distribué (DKM). DKM est une fonctionnalité côté client qui utilise un ensemble de clés secrètes pour chiffrer et déchiffrer les informations. Seuls les membres d’un groupe de sécurité spécifiques dans les Services de domaine Active Directory peuvent accéder à ces clés pour déchiffrer les données qui sont chiffrées par DKM. Dans Exchange Online, uniquement des comptes de service sous lequel exécutent les processus Exchange font partie de ce groupe de sécurité. Dans le cadre de la procédure opérationnelle standard dans le centre de données, aucune humaines ne reçoit les informations d’identification qui font partie de ce groupe de sécurité et par conséquent aucun humain n’a accès aux clés qui peuvent déchiffrer ces clés secrètes.
  
## <a name="customer-key"></a>Clé client

Avec la clé client, vous contrôler les clés de chiffrement de votre organisation, puis configurez Office 365 pour les utiliser pour chiffrer vos données au repos dans les centres de données de Microsoft. Données au repos comprennent des données à partir d’Exchange Online et Skype pour les entreprises qui est stocké dans les boîtes aux lettres et les fichiers qui sont stockés dans SharePoint Online et OneDrive for Business. Pour plus d’informations, voir [contrôle de vos données dans Office 365 à l’aide de la clé client](https://go.microsoft.com/fwlink/?linkid=863349) et de [Service de chiffrement avec la clé client pour Office 365 FAQ](https://go.microsoft.com/fwlink/?linkid=869438).
  
## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365
<a name="bkmk_O365_MessageEncryption"> </a>

Chiffrement de messages Office 365 permet aux utilisateurs de messagerie envoyer des messages électroniques chiffrés à tout le monde. Nous avons annoncé de nouvelles fonctionnalités de chiffrement de messages Office qui exploitent les fonctionnalités de protection de chiffrement des informations Azure. Ces nouvelles fonctionnalités améliorées expériences utilisateur final qui facilitent le partager et collaborer sur des messages protégés avec tout le monde à l’intérieur ou à l’extérieur de l’organisation. Les nouvelles fonctionnalités de chiffrement de messages Office ont des exigences du programme d’installation. Voir la rubrique Set up des nouvelles fonctionnalités d’Office 365 Message Encryption greffées Azure la Protection des informations. Les clients hérités Office 365 Message Encryption ne pas recevoir les nouvelles fonctionnalités sans suivre les instructions fournies ci-dessus de paramétrage. Veuillez lire le [Forum aux questions](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) pour plus d’informations sur ce qui est inclus dans la nouvelle et fonctionnalités d’Office 365 Message Encryption héritées. 
  
## <a name="securemultipurpose-internet-mail-extensions-smime"></a>S/MIME (Secure/Multipurpose Internet Mail Extension)
<a name="bkmk_O365_MessageEncryption"> </a>

S/MIME vous aider à protéger les informations sensibles en envoyant un message signé et chiffré au sein de votre organisation. Les administrateurs peuvent utiliser une session distante de Windows PowerShell pour configurer S/MIME après avoir établi et émis des certificats PKI pour les utilisateurs. Ces certificats doivent être synchronisés à partir d'un service local de certificats Active Directory.
  
S/MIME est pris en charge par Internet Explorer 9 et versions ultérieures. Actuellement, S/MIME n'est pas pris en charge sur Firefox, Opera et Chrome. Pour plus d'informations, consultez la rubrique [S/MIME pour la signature et le chiffrement des messages](https://go.microsoft.com/fwlink/p/?LinkID=393973).
  
## <a name="in-place-hold-and-litigation-hold"></a>Conservation inaltérable et conservation pour litige
<a name="bkmk_O365_MessageEncryption"> </a>

Lorsqu'une situation de litige est vraisemblablement à craindre, les organisations ont pour obligation de conserver les informations pertinentes qui sont stockées électroniquement (ESI), y compris la messagerie. Cette exigence de stockage de la correspondance électronique peut se faire ressentir avant que les détails précis du litige soient connus, et la conservation s'applique généralement à un grand nombre d'éléments. Les organisations peuvent conserver tous les messages électroniques concernant un sujet spécifique, ou tous les messages de certaines personnes.
  
Dans Exchange Online, vous pouvez utiliser la conservation inaltérable et la conservation pour litige pour accomplir les tâches suivantes :
  
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
  
## <a name="in-place-ediscovery"></a>Découverte électronique locale
<a name="bkmk_O365_MessageEncryption"> </a>

Exchange Online permet aux utilisateurs d'explorer le contenu des boîtes aux lettres d'une organisation à l'aide d'une interface Web. Les administrateurs ou les responsables de la conformité et de la sécurité qui sont autorisés à effectuer des recherches de découverte électronique locale (par affectation) peuvent rechercher dans les messages électroniques, les pièces jointes, les rendez-vous de calendrier, les tâches, les contacts et d'autres éléments. La découverte électronique locale permet d'effectuer une recherche simultanément dans les archives et les boîtes aux lettres principales. Les fonctionnalités de filtrage avancé incluent l'expéditeur, le destinataire, le type de message, la date d'envoi/de réception, la copie carbone/copie carbone invisible ainsi que la syntaxe KQL. Les résultats de la recherche incluent également des éléments du dossier Éléments supprimés s'ils correspondent à la requête de recherche.
  
Les résultats des recherches de découverte électronique locale peuvent être prévisualisés dans l'interface web, exportés dans un fichier PST, ou copiés dans un type spécial de boîte aux lettres appelé boîte aux lettres de découverte. Une boîte aux lettres de découverte présente un quota de 50 Go pour le stockage des résultats de la recherche. Les administrateurs peuvent également connecter Outlook à la boîte aux lettres de découverte pour accéder aux résultats de la recherche et les exporter dans un fichier .pst.
  
Les administrateurs peuvent utiliser le Centre d'administration Exchange ou l'application Windows PowerShell distante pour effectuer des recherches dans plusieurs boîtes aux lettres. Le Centre d'administration Exchange peut fournir un aperçu en lecture seule des résultats de recherche, en permettant aux administrateurs de vérifier rapidement une recherche et de la réexécuter, si nécessaire, avec différents paramètres. Après avoir optimisé une recherche, l'administrateur peut copier les résultats dans la boîte aux lettres de découverte.
  
Par défaut, une boîte aux lettres de découverte est créée pour chaque organisation. Toutefois, les administrateurs peuvent créer des boîtes aux lettres de découverte supplémentaires à l'aide de Windows PowerShell à distance. Les boîtes aux lettres de découverte ne peuvent pas être utilisées à d'autres fins que le stockage des résultats de recherche de découverte électronique locale.
  
Les administrateurs peuvent utiliser le Centre d'administration Exchange ou l'application Windows PowerShell distante pour effectuer des recherches de découverte électronique locale. Le Centre d'administration Exchange peut fournir un aperçu en lecture seule des résultats de recherche, en permettant aux administrateurs de vérifier rapidement une recherche et de la réexécuter, si nécessaire, avec différents paramètres. Après avoir optimisé une recherche, l'administrateur peut copier les résultats dans la boîte aux lettres de découverte, ou exporter les résultats de la recherche dans un fichier .PST.
  
Les administrateurs peuvent utiliser le centre d'administration Exchange ou Windows PowerShell à distance pour effectuer des recherches dans 10 000 boîtes aux lettres à la fois lors d'une recherche de découverte électronique locale. 
  
Dans Exchange Online, les utilisateurs autorisés peuvent exécuter la découverte électronique sur place et choisir l'une des actions suivantes :
  
- **Estimation des résultats de recherche** Obtenez une estimation du nombre de messages renvoyés par la recherche, y compris les statistiques de mots clés pour déterminer l'efficacité des mots clés utilisés dans la recherche et modifiez les paramètres de recherche le cas échéant. 
    
- **Aperçu des résultats de la recherche**
    
- Copiez les messages renvoyés dans les résultats de recherche à une boîte aux lettres de découverte.
    
Pour plus d'informations, consultez la rubrique [Découverte électronique locale](http://go.microsoft.com/fwlink/p/?LinkId=271747).
  
## <a name="mail-flow-rules"></a>Règles de flux de messagerie
<a name="bkmk_O365_MessageEncryption"> </a>

Vous pouvez utiliser les règles de flux de messagerie pour rechercher des conditions spécifiques sur les messages qui transitent par votre organisation et les traiter. Règles de flux de messagerie vous permettent d’appliquer des stratégies de messagerie pour les messages électroniques, messages sécurisés, protéger les systèmes de messagerie et empêcher la fuite d’informations.
  
En raison d'obligations légales, d'exigences réglementaires ou de stratégies d'entreprise, de nombreuses organisations sont tenues d'appliquer des stratégies de messagerie afin de limiter l'interaction entre les destinataires et les expéditeurs, à l'intérieur et à l'extérieur de l'organisation. Outre la limitation des interactions entre individus, groupes de service au sein de l'organisation et autres entités externes à celle-ci, certaines organisations sont également sujettes aux exigences suivantes en relation avec la stratégie de messagerie :
  
- blocage du contenu inapproprié entrant ou sortant
    
- filtrage des informations confidentielles de l'organisation
    
- Suivi ou archivage des messages échangés avec des individus spécifiques
    
- redirection des messages entrants et sortants pour inspection avant remise
    
- application de dédits de responsabilité à des messages transitant par l'organisation
    
> [!IMPORTANT]
> Types de fichiers joints qui requièrent l’installation d’iFilters tiers sur le serveur de messagerie (par exemple, Adobe .pdf) ne peut pas être inspectée à l’aide de règles de flux de messagerie jusqu'à après l’installation d’un iFilter approprié. Pour plus d’informations sur les types de fichiers pris en charge par les règles de flux de messagerie, voir [utiliser les règles de flux de messagerie pour analyser les pièces jointes des messages dans Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271748). 
  
Pour plus d’informations sur les règles de flux de messagerie, consultez la rubrique [Mail flow rules in Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkId=296488).
  
## <a name="data-loss-prevention"></a>Protection contre la perte de données
<a name="bkmk_O365_MessageEncryption"> </a>

La fonctionnalité de protection contre la perte de données (DLP) vous permet d'identifier, de contrôler et de protéger les informations sensibles de votre organisation via une analyse de contenu approfondie. DLP est une fonctionnalité haut de gamme de plus en plus importante pour les systèmes de message d'entreprise car la messagerie essentielle comprend des données sensibles qui doivent être protégées. La fonctionnalité DLP d'Exchange Online vous permet de protéger les données sensibles sans affecter la productivité des collaborateurs.
  
Vous pouvez configurer les stratégies DLP dans l'interface de gestion du Centre d'administration Exchange (CAE), qui vous permet de réaliser les opérations suivantes : 
  
- Démarrer avec un modèle de stratégie préconfigurée qui vous permet de détecter des types spécifiques d'informations sensibles, tels que des données PCI-DSS, des données Gramm-Leach-Bliley Act ou même des informations d'identification personnelle spécifiques aux paramètres régionaux.
    
- Exploiter toute la puissance des critères et des actions de règles de transport existants et ajouter de nouvelles règles de transport.
    
- Tester l'efficacité de vos stratégies DLP avant de les appliquer pleinement.
    
- Incorporer vos propres modèles de stratégie DLP personnalisés et types d'informations sensibles.
    
- Détecter des informations sensibles dans les pièces jointes des messages, des corps de texte ou des lignes d’objet et ajuster le niveau de confiance à partir de laquelle Exchange Online agit.
    
- Détecter les données de formulaire sensibles à l'aide de la création d'empreintes digitales document. La création d'empreintes digitales document vous permet de créer facilement des types d'informations sensibles personnalisés à partir des formulaires texte que vous pouvez utiliser pour définir des règles de transport et des stratégies de protection contre la perte de données.
    
- Ajouter des conseils de stratégie qui permettent de réduire la perte de données en affichant une notification à vos utilisateurs Outlook 2016, Outlook 2013, Outlook Web App et OWA pour les appareils, tout en améliorant l’efficacité de vos stratégies en autorisant la création de rapports de faux-positifs.  
    
- Examiner les données relatives aux incidents dans les rapports DLP ou ajouter vos propres rapports spécifiques à l'aide d'une action de génération de rapports d'incidents.
    
Pour plus d'informations sur la stratégie DLP, consultez la rubrique [Protection contre la perte de données](https://go.microsoft.com/fwlink/p/?LinkId=271749).
  
## <a name="journaling"></a>Journalisation
<a name="bkmk_O365_MessageEncryption"> </a>

Vous pouvez configurer Exchange Online pour journaliser des copies de messages électroniques dans n'importe quelle boîte aux lettres externe pouvant recevoir des messages via SMTP. La journalisation peut aider votre organisation à répondre aux exigences réglementaires, légales et de conformité organisationnelle en enregistrant les communications électroniques échangées. Lors de la planification de la rétention et de la conformité de la messagerie, il est important de bien comprendre la journalisation, son intégration dans les stratégies de conformité de votre organisation et la sécurisation des messages journalisés à l'aide de votre organisation.
  
Vous pouvez gérer les règles de journal à l'aide du Centre d'administration Exchange ou de l'application Windows PowerShell distante. Vous pouvez configurer la journalisation en fonction de la liste d'utilisateurs ou de distribution, et choisir de ne consigner que les messages internes, les messages externes, ou les deux.   Les messages journalisés incluent non seulement le message d'origine, mais également des informations sur l'expéditeur, les destinataires, les copies et les copies invisibles.
  
Pour garantir une solution de journalisation réussie et fiable, vous devez effectuer les tâches suivantes :
  
- Assurez-vous que la destination de journalisation n’est pas une boîte aux lettres Exchange Online.
    
- Créez dans le répertoire de clients un objet contact pour l'adresse de messagerie cible SMTP à utiliser pour la journalisation.
    
- Créez un deuxième objet contact sous forme de boîte aux lettres de journal alternative pour capturer tous les états de journal lorsque la boîte aux lettres de journal principale n'est pas disponible.
    
- Maintenir la bonne gestion, de redondance, disponibilité, performances et les niveaux de fonctionnalité de la cible SMTP pour garantir l’acceptation réussie de la messagerie toujours.
    
- Assurez l'interopérabilité respective avec le transport Exchange Server et Exchange, notamment les formats de message, l'intégration des informations sur l'expéditeur/destinataire et la conversion appropriée du contenu.
    
Pour plus d'informations sur la journalisation, consultez la rubrique [Journalisation](https://go.microsoft.com/fwlink/p/?LinkId=271750).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités
<a name="bkmk_O365_MessageEncryption"> </a>

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).
  

