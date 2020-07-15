---
title: Planification et déploiement
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132658"
---
# <a name="planning-and-deployment"></a>Planification et déploiement

## <a name="planning-for-service-changes-and-growth"></a>Planification de croissance et de changements de service

Les organisations doivent choisir des options de migration selon leurs systèmes de messagerie électronique source, l'état final souhaité (hébergement complet ou hébergement partiel), le nombre d'utilisateurs à migrer et la rapidité avec laquelle l'état final doit être atteint.
  
## <a name="deployment-options"></a>Options de déploiement

- **Déploiement en nuage uniquement** Toutes les boîtes aux lettres utilisateur de votre entreprise sont hébergées dans Exchange Online. 
    
- **Déploiement hybride Exchange** Certaines boîtes aux lettres utilisateur de votre entreprise sont hébergées dans une organisation Exchange locale tandis que d'autres sont hébergées dans Exchange Online. 
    
### <a name="cloud-only"></a>Cloud uniquement

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>Hybride

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>Options de migration

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **Migration IMAP** Migration de données de boîtes aux lettres vers Exchange Online à partir de systèmes de messagerie électronique à extension IMAP. 
    
- **Migration Exchange à basculement** Migration de boîtes aux lettres à partir de systèmes Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 et de systèmes Exchange hébergés vers Exchange Online en une même opération de migration à basculement. 
    
- **Migration Exchange progressive** Effectuez une migration progressive pour migrer des boîtes aux lettres à partir d'Exchange Server 2003 ou Exchange Server 2007 avec des outils de migration à extension Web et avec un minimum de modifications apportées à l'infrastructure locale. 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
Pour plus d'informations sur la migration des e-mails et des boîtes aux lettres vers Exchange Online, voir [Migration de boîtes aux lettres vers Exchange Online](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Migration IMAP

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. Création de boîtes aux lettres dans le nuage pour des utilisateurs de l'organisation (en général, cette opération est réalisée en téléchargeant un fichier .csv ou à l'aide de Windows PowerShell à distance.
    
2. Entrée des paramètres de connexion du serveur distant.
    
3. Utilisation d'un fichier CSV pour spécifier les boîtes aux lettres dont les données doivent être migrées vers des boîtes aux lettres Exchange Online.
    
4. Une fois ces informations entrées, Exchange Online commence à migrer le contenu d'une boîte aux lettres via IMAP (la migration ne concerne ni les éléments du calendrier, les contacts, les tâches ni tout autre élément sans rapport avec le courrier électronique).
    
Pour plus d'informations sur la migration IMAP, voir [Migration du courrier électronique à partir d'un serveur IMAP vers des boîtes aux lettres Exchange Online](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) et [Déplacer d'autres types de boîtes aux lettres IMAP](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Pour éviter une sur-utilisation des ressources et de la bande passante du serveur distant pendant la migration, Exchange Online crée moins de 10 connexions vers le serveur IMAP. 
  
### <a name="cutover-exchange-migration"></a>Migration Exchange à basculement

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. Grâce à l'adresse de messagerie et aux informations d'identification d'un compte administrateur local, Exchange Online se connecte à l'organisation de messagerie électronique locale via le service Découverte automatique.
    
2. Exchange Online utilise une connexion RPC/HTTP pour lire les informations d'annuaire dans le serveur distant et crée des boîtes aux lettres dans Exchange Online.
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. Une fois la migration initiale terminée, toutes les modifications sont synchronisées avec le nuage toutes les 24 heures, tant que l'administrateur n'a pas arrêté ou supprimé le lot de migration.
    
Pour faire basculer les utilisateurs vers leurs boîtes aux lettres en nuage, les administrateurs configurent leur enregistrement MX de sorte qu’il pointe vers Microsoft et reconfigure les profils des utilisateurs dans Outlook. Lorsque les utilisateurs basculent vers leurs boîtes aux lettres en nuage, leurs dossiers hors connexion locaux (fichiers .ost) se resynchronisent, ce qui se traduit par le téléchargement de la messagerie migrée dans le poste de travail du client. Les utilisateurs peuvent répondre à des messages anciens de leurs boîtes aux lettres après la migration.
  
Pour plus d'informations sur la migration à basculement Exchange, voir [Ce que vous devez savoir sur une migration de messagerie à basculement vers Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>Migration Exchange progressive

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
Pour plus d'informations sur les migrations Exchange intermédiaires, voir [Ce que vous devez savoir sur une migration de messagerie intermédiaire](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>Outils de migration

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **Obtention de détails sur des éléments ignorés** S'agissant des migrations IMAP, à basculement et progressives, le tableau de bord de migration affiche des informations sur des éléments spécifiques qui ont été ignorés, notamment le motif et l'emplacement de l'élément dans la boîte aux lettres de l'utilisateur. 
    
  - **Ouvrir des rapports de migrations** Les administrateurs peuvent ouvrir des statistiques de migration ou le rapport d'erreurs de migration pour un lot de migration directement à partir du tableau de bord. 
    
  - **Modifier un lot de migration** Si un lot de migration associé à une migration Exchange progressive ou une migration IMAP est dans la file d'attente de migration, sans être actuellement exécuté, les administrateurs peuvent encore modifier le lot de migration. 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    Pour plus d'informations sur l'Outil de synchronisation Windows Azure Active Directory, consultez la rubrique [Synchronisation d'annuaires : Feuille de route](https://go.microsoft.com/fwlink/p/?LinkId=287034).
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - Un Assistant Centre d'administration Exchange (EAC) qui guide les administrateurs de bout en bout tout au long du processus de configuration d'un déploiement hybride.
    
  - Un ensemble de commandes de l'environnement de ligne de commande Exchange Management Shell (EMS) qui orchestre le processus de configuration.
    
    Pour plus d'informations sur l'Assistant de configuration hybride, consultez la rubrique [Assistant de configuration hybride](https://go.microsoft.com/fwlink/p/?LinkId=271734).
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  

