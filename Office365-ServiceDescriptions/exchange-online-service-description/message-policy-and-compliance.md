---
title: Stratégie et conformité de message
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
description: Découvrez la stratégie et la conformité des messages dans Exchange Online.
ms.openlocfilehash: 22de08fb350785b63db97da7271182eb62980cae
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652708"
---
# <a name="message-policy-and-compliance"></a>Stratégie et conformité de message

## <a name="archiving-exchange-online-based-mailboxes"></a>Archivage de boîtes aux lettres Exchange Online

Les boîtes aux lettres Exchange Online résident dans le nuage. Pour les archiver, vous nécessitez d'environnements d'hébergement uniques. Dans certains cas, Exchange Online peut également être utilisé pour archiver des boîtes aux lettres locales dans le nuage. Les options d'archivage d'Exchange Online sont décrites dans cette section.
  
Exchange Online intègre des fonctionnalités d'archivage pour les boîtes aux lettres en nuage, notamment la fonction d'archivage sur place qui fournit aux utilisateurs un emplacement pratique dans lequel ils peuvent stocker d'anciens messages électroniques. Une archive In-Place est un type spécial de boîte aux lettres qui apparaît avec les dossiers de boîte aux lettres principaux d’un utilisateur dans Outlook et Outlook sur le web. Les utilisateurs peuvent accéder à l'archive et l'explorer de la même manière que pour leurs boîtes aux lettres principales. Les fonctionnalités disponibles varient en fonction du client utilisé :
  
- **Outlook 2016, Outlook 2013, Outlook 2010** et Outlook sur le web Les utilisateurs ont accès aux fonctionnalités complètes de l’archive, ainsi qu’aux fonctionnalités de conformité associées, telles que le contrôle des stratégies de rétention et d’archivage. 
    
- **Outlook 2007** Les utilisateurs bénéficient d'une assistance élémentaire pour l'archivage local, et certaines fonctionnalités d'archivage et de conformité ne sont pas disponibles. Par exemple, les utilisateurs ne peuvent pas appliquer de stratégies de rétention ou d'archivage aux éléments de boîte aux lettres, et doivent se baser sur des stratégies configurées par l'administrateur 
    
Les administrateurs utilisent le Centre d'administration Exchange ou l'application Windows PowerShell distante pour activer la fonctionnalité d'archivage personnel pour des utilisateurs spécifiques.
  
Pour plus d'informations, voir les pages suivantes :
  
- [Boîtes aux lettres d'archivage dans Exchange Online](../exchange-online-archiving-service-description/archive-features.md)
    
- [Activer ou désactiver une boîte aux lettres d'archivage dans Exchange Online](/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Tailles de l'archive

Il n'est possible de stocker les données de messagerie que d'un seul utilisateur dans chaque archive personnelle. L'allocation de l'espace de stockage dépend du plan d'abonnement. Pour plus d’informations sur les tailles de boîtes aux lettres d’archivage, consultez la section « Limites de stockage des boîtes aux lettres [» Exchange Online limites.](exchange-online-limits.md)
  
> [!IMPORTANT]
> - L'utilisation de la fonction de journalisation, des règles de transport ou des règles de transfert automatique pour copier des messages vers une boîte aux lettres Exchange Online à des fins d'archivage n'est pas autorisée. Microsoft se réserve le droit de refuser l’archivage illimité dans les cas où une archive de boîte aux lettres n’est pas utilisée dans un scénario personnel ou dans d’autres cas d’utilisation inappropriée.
> - L'archivage local exige impose certaines conditions de licence aux utilisateurs d'Outlook. Les utilisateurs d'Outlook 2007 doivent disposer de la mise à jour cumulative Office 2007 de février 2011 pour pouvoir accéder à leur archive personnelle. 
> - Exchange Online ne prend pas en charge la cmdlet _New-MailboxImportRequest_ Windows PowerShell de Exchange Server 2010 Service Pack 1 ou ultérieur pour l’importation par l’administrateur de fichiers .pst dans une archive personnelle. Si la boîte aux lettres principale et l'archive de l'utilisateur se situent dans Exchange Online, un administrateur peut utiliser PST Capture, un outil gratuit qui permet d'importer les données du fichier .pst bers la boîte aux lettres ou l'archive principale de l'utilisateur.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Archivage en nuage de boîtes aux lettres locales

L'utilisation d'Exchange Online pour l'archivage en nuage de boîtes aux lettres locales Exchange Server 2010 ou version ultérieure est possible avec Microsoft Exchange Online Archiving, une solution d'archivage hébergée de Microsoft. Cette dernière requiert que l'organisation locale soit en mode hybride ou configurée pour Exchange Online Archiving.
  
> [!IMPORTANT]
> Les utilisateurs possédant une boîte aux lettres locale sur un serveur de boîtes aux lettres Exchange 2010 et ayant appliqué une stratégie Dossier géré ne peuvent pas activer une archive sur place locale ou en nuage. 
  
## <a name="retention-tags-and-retention-policies"></a>Balises et stratégies de rétention

Exchange Online offre des stratégies de rétention qui permettent aux organisations de limiter les possibilités associées à la messagerie et autres communications. Grâce à ces stratégies, les administrateurs peuvent appliquer des paramètres de rétention à des dossiers spécifiques dans les boîtes de réception des utilisateurs. Les administrateurs peuvent également donner aux utilisateurs un menu de stratégies de rétention et les laisser appliquer les stratégies à des éléments, des conversations ou des dossiers spécifiques à l’aide de Outlook 2010 ou d’une Outlook sur le web.
  
Dans Exchange Online, les administrateurs gèrent les stratégies de rétention à l'aide du Centre d'administration Exchange (CAE) ou de l'application Windows PowerShell distante.
  
Exchange Online propose deux types de stratégies : les stratégies d'archivage et les stratégies de suppression. Ces deux types peuvent être combinés sur le même élément ou dossier. Par exemple, un utilisateur peut baliser un message électronique afin de le déplacer automatiquement vers l'archive locale dans un certain nombre de jours et le supprimer après quelques jours d'intervalle.
  
Avec Outlook 2010 ou une Outlook sur le web, les utilisateurs peuvent appliquer des stratégies de rétention à des dossiers, des conversations ou des messages individuels. Ils peuvent également visualiser les stratégies de rétention appliquées et les dates de suppression prévues des messages. Les utilisateurs d'autres clients de messagerie peuvent uniquement archiver ou supprimer des messages électroniques en fonction des stratégies de rétention côté serveur définies par l'administrateur.
  
Les fonctionnalités de stratégie de rétention disponibles dans Exchange Online sont identiques à celles d'Exchange Server 2010 Service Pack 2 RU4. Les administrateurs peuvent utiliser Windows PowerShell à distance pour migrer les stratégies de rétention des environnements locaux Exchange Server 2010 ou version ultérieure vers Exchange Online.
  
> [!IMPORTANT]
> Les dossiers gérés, une approche plus ancienne de la gestion des enregistrements de messagerie qui a été introduite dans Exchange Server 2007, ne sont pas disponibles dans Exchange Online. 
  
Pour plus d'informations, consultez la rubrique [Balises et stratégies de rétention](/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Chiffrement des données lors de leur stockage

Le chiffrement des données client au repos est fourni par plusieurs technologies côté service, notamment BitLocker, DKM, le chiffrement de service stockage Azure et le chiffrement de service dans Exchange Online, Skype Entreprise, OneDrive Entreprise et SharePoint Online. Office 365 Le chiffrement de service inclut une option d’utilisation des clés de chiffrement gérées par le client qui sont stockées dans Azure Key Vault. Cette option de clé gérée par le client, appelée Clé [client,](/microsoft-365/compliance/customer-key-overview)est disponible pour Exchange Online, SharePoint Online et OneDrive Entreprise. 
  
### <a name="bitlocker"></a>BitLocker

Les serveurs Microsoft utilisent BitLocker chiffrer les lecteurs de disque contenant les données client au repos au niveau du volume. BitLocker chiffrement est une fonctionnalité de protection des données intégrée à Windows. BitLocker est l’une des technologies utilisées pour se protéger contre les menaces en cas de défaillances dans d’autres processus ou contrôles (par exemple, le contrôle d’accès ou le recyclage du matériel) qui peuvent conduire à une personne à accéder physiquement aux disques contenant des données client. Dans ce cas, BitLocker risque de vol ou d’exposition de données en raison de la perte, du vol ou de la désaffectation inappropriée d’ordinateurs et de disques. 
  
### <a name="distributed-key-manager"></a>Gestionnaire de clés distribuées

En plus de BitLocker, nous utilisons une technologie appelée Gestionnaire de clés distribuées (DKM). DKM est une fonctionnalité côté client qui utilise un ensemble de clés secrètes pour chiffrer et déchiffrer des informations. Seuls les membres d’un groupe de sécurité spécifique dans les services de domaine Active Directory peuvent accéder à ces clés pour déchiffrer les données chiffrées par DKM. Dans Exchange Online, seuls certains comptes de service sous lesquels les processus Exchange sont exécutés font partie de ce groupe de sécurité. Dans le cadre de la procédure opérationnelle standard dans le centre de données, les informations d’identification qui font partie de ce groupe de sécurité ne sont communiquées à aucun être humain, et par conséquent aucun être humain n’a accès aux clés qui peuvent déchiffrer les informations confidentielles.
  
## <a name="customer-key"></a>Clé client

Avec la clé client, vous contrôlez les clés de chiffrement de votre organisation, puis vous les configurez pour chiffrer vos données au repos dans les centres de données de Microsoft. Les données au repos incluent les données issues d’Exchange Online et de Skype Entreprise qui sont enregistrées dans des boîtes aux lettres et des fichiers stockés dans SharePoint Online et OneDrive Entreprise. Pour plus d’informations, voir [Contrôler vos](/office365/securitycompliance/controlling-your-data-using-customer-key) données à l’aide de la clé client et du chiffrement de service avec la clé [client FAQ.](/office365/securitycompliance/service-encryption-with-customer-key-faq)
  
## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365

chiffrement de messages Office 365 permet aux utilisateurs de messagerie d’envoyer des messages électroniques chiffrés à tout le monde. Nous avons annoncé de nouvelles fonctionnalités dans Office chiffrement de messages qui tirent parti des fonctionnalités de protection dans le chiffrement d’informations Azure. Ces nouvelles fonctionnalités fournissaient des expériences améliorées pour les utilisateurs finaux qui facilitent le partage et la collaboration sur des messages protégés avec toute personne à l’intérieur ou à l’extérieur de l’organisation. Les nouvelles fonctionnalités Office chiffrement de messages ont des exigences de configuration. Voir Configurer de nouvelles fonctionnalités chiffrement de messages Office 365 d’informations intégrées à Azure Information Protection. Les clients sur les chiffrement de messages Office 365 ne peuvent pas obtenir les nouvelles fonctionnalités sans suivre les instructions de mise en place fournies ci-dessus. Veuillez lire la [FAQ pour](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) plus d’informations sur ce qui est inclus dans les nouvelles fonctionnalités d’chiffrement de messages Office 365 héritées. 

Chiffrement avancé de messages Office 365 offre une protection supplémentaire en permettant l’expiration et la révocation des messages.  Vous pouvez également créer plusieurs modèles pour les messages électroniques chiffrés provenant de votre organisation.  Le chiffrement de messages avancé est inclus dans Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (tarifs pour le personnel à but non lucratif), Office 365 Entreprise E5 (prix du personnel pour les associations) ou Office 365 Éducation A5. Si votre organisation dispose d’un abonnement qui n’inclut pas Chiffrement avancé de messages Office 365, vous pouvez acheter Microsoft 365 E5 Conformité ou la référence Conformité avancée Office 365 SKU en tant que modules.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>S/MIME (Secure/Multipurpose Internet Mail Extension)

S/MIME vous aider à protéger les informations sensibles en envoyant un message signé et chiffré au sein de votre organisation. Les administrateurs peuvent utiliser une session distante de Windows PowerShell pour configurer S/MIME après avoir établi et émis des certificats PKI pour les utilisateurs. Ces certificats doivent être synchronisés à partir d'un service local de certificats Active Directory.
  
S/MIME est pris en charge sur Microsoft Edge et Internet Explorer 11. Actuellement, S/MIME n'est pas pris en charge sur Firefox, Opera et Chrome. Pour plus d'informations, consultez la rubrique [S/MIME pour la signature et le chiffrement des messages](/Exchange/policy-and-compliance/smime?preserve-view=true&view=exchserver-2019).
  
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
  
Pour plus d'informations, consultez la rubrique [Conservation inaltérable et conservation pour litige](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>Découverte électronique locale

Exchange Online permet aux clients de rechercher le contenu des boîtes aux lettres au sein d’une organisation à l’aide d’une interface web. Les administrateurs ou les responsables de la conformité et de la sécurité qui sont autorisés à effectuer des recherches de découverte électronique locale (par affectation) peuvent rechercher dans les messages électroniques, les pièces jointes, les rendez-vous de calendrier, les tâches, les contacts et d'autres éléments. La découverte électronique locale permet d'effectuer une recherche simultanément dans les archives et les boîtes aux lettres principales. Les fonctionnalités de filtrage avancé incluent l'expéditeur, le destinataire, le type de message, la date d'envoi/de réception, la copie carbone/copie carbone invisible ainsi que la syntaxe KQL. Les résultats de la recherche incluent également des éléments du dossier Éléments supprimés s'ils correspondent à la requête de recherche.
  
Les résultats des recherches de découverte électronique locale peuvent être prévisualisés dans l'interface web, exportés dans un fichier PST, ou copiés dans un type spécial de boîte aux lettres appelé boîte aux lettres de découverte. Une boîte aux lettres de découverte présente un quota de 50 Go pour le stockage des résultats de la recherche. Les administrateurs peuvent également connecter Outlook à la boîte aux lettres de découverte pour accéder aux résultats de la recherche et les exporter dans un fichier .pst.
  
Les administrateurs peuvent utiliser le Centre d'administration Exchange ou l'application Windows PowerShell distante pour effectuer des recherches dans plusieurs boîtes aux lettres. Le Centre d'administration Exchange peut fournir un aperçu en lecture seule des résultats de recherche, en permettant aux administrateurs de vérifier rapidement une recherche et de la réexécuter, si nécessaire, avec différents paramètres. Après avoir optimisé une recherche, l'administrateur peut copier les résultats dans la boîte aux lettres de découverte.
  
Par défaut, une boîte aux lettres de découverte est créée pour chaque organisation. Toutefois, les administrateurs peuvent créer des boîtes aux lettres de découverte supplémentaires à l'aide de Windows PowerShell à distance. Les boîtes aux lettres de découverte ne peuvent pas être utilisées à d'autres fins que le stockage des résultats de recherche de découverte électronique locale.
  
Les administrateurs peuvent utiliser le Centre d'administration Exchange ou l'application Windows PowerShell distante pour effectuer des recherches de découverte électronique locale. Le Centre d'administration Exchange peut fournir un aperçu en lecture seule des résultats de recherche, en permettant aux administrateurs de vérifier rapidement une recherche et de la réexécuter, si nécessaire, avec différents paramètres. Après avoir optimisé une recherche, l'administrateur peut copier les résultats dans la boîte aux lettres de découverte, ou exporter les résultats de la recherche dans un fichier .PST.
  
Les administrateurs peuvent utiliser le centre d'administration Exchange ou Windows PowerShell à distance pour effectuer des recherches dans 10 000 boîtes aux lettres à la fois lors d'une recherche de découverte électronique locale. 
  
Dans Exchange Online, les utilisateurs autorisés peuvent exécuter la découverte électronique sur place et choisir l'une des actions suivantes :
  
- **Estimation des résultats de recherche** Obtenez une estimation du nombre de messages renvoyés par la recherche, y compris les statistiques de mots clés pour déterminer l'efficacité des mots clés utilisés dans la recherche et modifiez les paramètres de recherche le cas échéant. 
    
- **Aperçu des résultats de la recherche**
    
- Copiez les messages renvoyés dans les résultats de recherche à une boîte aux lettres de découverte.
    
Pour plus d'informations, consultez la rubrique [Découverte électronique locale](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Règles de flux de messagerie

Vous pouvez utiliser des règles de flux de messagerie pour rechercher des conditions spécifiques sur les messages qui passent par votre organisation et agir dessus. Les règles de flux de messagerie vous permet d’appliquer des stratégies de messagerie aux messages électroniques, de sécuriser les messages, de protéger les systèmes de messagerie et d’éviter les fuites d’informations.
  
En raison d'obligations légales, d'exigences réglementaires ou de stratégies d'entreprise, de nombreuses organisations sont tenues d'appliquer des stratégies de messagerie afin de limiter l'interaction entre les destinataires et les expéditeurs, à l'intérieur et à l'extérieur de l'organisation. Outre la limitation des interactions entre individus, groupes de service au sein de l'organisation et autres entités externes à celle-ci, certaines organisations sont également sujettes aux exigences suivantes en relation avec la stratégie de messagerie :
  
- blocage du contenu inapproprié entrant ou sortant
    
- filtrage des informations confidentielles de l'organisation
    
- Suivi ou archivage des messages échangés avec des individus spécifiques
    
- redirection des messages entrants et sortants pour inspection avant remise
    
- application de dédits de responsabilité à des messages transitant par l'organisation
    
> [!IMPORTANT]
> Les types de fichiers de pièces jointes qui nécessitent l’installation d’iFilters tiers sur le serveur de messagerie (comme Adobe .pdf) ne peuvent pas être inspectés à l’aide de règles de flux de messagerie tant qu’un iFilter approprié n’est pas installé. Pour plus d’informations sur les types de fichiers pris en charge par les règles de flux de messagerie, voir Utiliser des règles de flux de messagerie pour inspecter les pièces [jointes](/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments)des messages dans Office 365 .
  
Pour plus d’informations sur les règles de flux de messagerie, consultez la rubrique [Mail flow rules in Exchange 2016](/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?preserve-view=true&view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Protection contre la perte de données

La fonctionnalité de protection contre la perte de données (DLP) vous permet d'identifier, de contrôler et de protéger les informations sensibles de votre organisation via une analyse de contenu approfondie. DLP est une fonctionnalité haut de gamme de plus en plus importante pour les systèmes de message d'entreprise car la messagerie essentielle comprend des données sensibles qui doivent être protégées. La fonctionnalité DLP dans Exchange Online vous permet de protéger les données sensibles sans affecter la productivité des travailleurs.
  
Vous pouvez configurer les stratégies DLP dans l'interface de gestion du Centre d'administration Exchange (CAE), qui vous permet de réaliser les opérations suivantes : 
  
- Démarrer avec un modèle de stratégie préconfigurée qui vous permet de détecter des types spécifiques d'informations sensibles, tels que des données PCI-DSS, des données Gramm-Leach-Bliley Act ou même des informations d'identification personnelle spécifiques aux paramètres régionaux.
    
- Exploiter toute la puissance des critères et des actions de règles de transport existants et ajouter de nouvelles règles de transport.
    
- Tester l'efficacité de vos stratégies DLP avant de les appliquer pleinement.
    
- Incorporer vos propres modèles de stratégie DLP personnalisés et types d'informations sensibles.
    
- Détectez les informations sensibles dans les pièces jointes, le corps du texte ou les lignes d’objet du message et ajustez le niveau de confiance auquel Exchange Online agir.
    
- Détecter les données de formulaire sensibles à l'aide de la création d'empreintes digitales document. La création d'empreintes digitales document vous permet de créer facilement des types d'informations sensibles personnalisés à partir des formulaires texte que vous pouvez utiliser pour définir des règles de transport et des stratégies de protection contre la perte de données.
    
- Ajoutez des Astuces de stratégie, ce qui permet de réduire la perte de données en affichant une notification à vos Outlook 2016, Outlook 2013, Outlook sur le web et OWA pour les utilisateurs d’appareils et peut également améliorer l’efficacité de vos stratégies en permettant la signalement de faux positifs. 
    
- Examiner les données relatives aux incidents dans les rapports DLP ou ajouter vos propres rapports spécifiques à l'aide d'une action de génération de rapports d'incidents.
    
Pour plus d'informations sur la stratégie DLP, consultez la rubrique [Protection contre la perte de données](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Journalisation

Vous pouvez configurer Exchange Online pour journaliser des copies de messages électroniques dans n'importe quelle boîte aux lettres externe pouvant recevoir des messages via SMTP. La journalisation peut aider votre organisation à répondre aux exigences réglementaires, légales et de conformité organisationnelle en enregistrant les communications électroniques échangées. Lors de la planification de la rétention et de la conformité de la messagerie, il est important de bien comprendre la journalisation, son intégration dans les stratégies de conformité de votre organisation et la sécurisation des messages journalisés à l'aide de votre organisation.
  
Vous pouvez gérer les règles de journal à l'aide du Centre d'administration Exchange ou de l'application Windows PowerShell distante. Vous pouvez configurer la journalisation en fonction de la liste d'utilisateurs ou de distribution, et choisir de ne consigner que les messages internes, les messages externes, ou les deux. Les messages journalisés incluent non seulement le message d'origine, mais également des informations sur l'expéditeur, les destinataires, les copies et les copies invisibles.
  
Pour garantir la réussite et la fiabilité d’une solution de journaling, vous devez effectuer les tâches suivantes :
  
- Assurez-vous que la destination de journaling n’est pas une boîte aux lettres Exchange Online de journal.
    
- Créez dans le répertoire de clients un objet contact pour l'adresse de messagerie cible SMTP à utiliser pour la journalisation.
    
- Créez un deuxième objet contact sous forme de boîte aux lettres de journal alternative pour capturer tous les états de journal lorsque la boîte aux lettres de journal principale n'est pas disponible.
    
- Maintenir des niveaux de gestion, de redondance, de disponibilité, de performances et de fonctionnalités corrects de la cible SMTP pour garantir une acceptation de messagerie réussie.
    
- Assurez l'interopérabilité respective avec le transport Exchange Server et Exchange, notamment les formats de message, l'intégration des informations sur l'expéditeur/destinataire et la conversion appropriée du contenu.
    
Pour plus d'informations sur la journalisation, consultez la rubrique [Journalisation](/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir [Exchange Online description du service.](exchange-online-service-description.md)
