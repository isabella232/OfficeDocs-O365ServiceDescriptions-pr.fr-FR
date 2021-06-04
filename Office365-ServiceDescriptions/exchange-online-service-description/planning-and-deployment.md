---
title: Planification et déploiement
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
description: Découvrez la planification et le déploiement dans Microsoft Exchange Online.
ms.openlocfilehash: eabef8014f64295058b4f41ccd9835a8dea473d8
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652698"
---
# <a name="planning-and-deployment"></a>Planification et déploiement

## <a name="planning-for-service-changes-and-growth"></a>Planification de croissance et de changements de service

Les organisations doivent choisir des options de migration selon leurs systèmes de messagerie électronique source, l'état final souhaité (hébergement complet ou hébergement partiel), le nombre d'utilisateurs à migrer et la rapidité avec laquelle l'état final doit être atteint.
  
## <a name="deployment-options"></a>Options de déploiement

- **Déploiement en nuage uniquement** : toutes les boîtes aux lettres utilisateur de votre organisation sont hébergées Exchange Online. 
    
- **Exchange** déploiement hybride : votre organisation dispose de boîtes aux lettres utilisateur hébergées dans une organisation Exchange sur site et de boîtes aux lettres d’utilisateurs hébergées dans Exchange Online. 
    
### <a name="cloud-only"></a>Cloud uniquement

Un déploiement en nuage uniquement est un déploiement dans lequel votre organisation au sein du service Exchange Online n'est pas connectée à une organisation Exchange locale. Tous les utilisateurs et boîtes aux lettres sont hébergés et gérés dans Exchange Online et Office 365.
  
### <a name="hybrid"></a>Hybride

Disponible pour les organisations Microsoft Exchange 2003, Exchange 2007, Exchange 2010 et Exchange 2013 locales, un déploiement hybride autorise une configuration de coexistence sur le long terme avec certaines boîtes aux lettres hébergées sur site et d'autres boîtes aux lettres hébergées dans Exchange Online, ou un chemin de migration permettant d'héberger toutes les boîtes aux lettres utilisateur dans Exchange Online. Un déploiement hybride offre aux entreprises la possibilité d'étendre l'éventail de fonctionnalités proposé et le contrôle administratif qu'elles exercent dans leur organisation Microsoft Exchange locale existantes vers le nuage. Les fonctionnalités du déploiement hybride incluent un transport de messages sécurisé, des informations de disponibilité de calendrier partagées et un suivi des messages entre les organisations locales et Exchange Online.
  
Pour plus d'informations sur le déploiement hybride, consultez la rubrique [Déploiements hybrides d'Exchange Server 2013](/exchange/exchange-hybrid). Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à l'article relatif à la [configuration des fonctionnalités de déploiement hybride d'Exchange avec Office 365 géré par 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> Les organisations Exchange 2003 locales doivent installer au moins un serveur d'accès au client/de boîtes aux lettres Exchange 2010 pour configurer un déploiement hybride avec Exchange Online. Les organisations Exchange 2007 locales doivent installer au moins un serveur d'accès au client et un serveur de boîtes aux lettres Exchange 2010 ou Exchange 2013 pour configurer un déploiement hybride avec Exchange Online. Les organisations Exchange 2010 et Exchange 2013 locales prennent en charge en mode natif les déploiements hybrides avec Exchange Online. Pour plus d'informations sur la compatibilité du serveur Exchange dans les déploiements hybrides, consultez la rubrique [Conditions préalables à un déploiement hybride](/exchange/hybrid-deployment-prerequisites). > Les organisations Exchange locales doivent configurer leur organisation pour un déploiement hybride. Nous recommandons fortement aux administrateurs d'utiliser l'Assistant de déploiement de Microsoft Exchange Server et l'Assistant de configuration hybride pour configurer le déploiement hybride. Pour plus d'informations, consultez la rubrique [Assistant de déploiement Exchange Server](/exchange/exchange-deployment-assistant)
  
## <a name="migration-options"></a>Options de migration

Les organisations doivent choisir des options de migration selon leurs systèmes de messagerie électronique source, l'état final souhaité (hébergement complet ou hébergement partiel), le nombre d'utilisateurs à migrer et la rapidité avec laquelle l'état final doit être atteint. Les options de migration possibles sont les suivantes :
  
- **Migration IMAP** : migrer les données de boîtes aux lettres des systèmes de messagerie IMAP vers Exchange Online. 
    
- Migration à Exchange à **cutover** : migrer des boîtes aux lettres de Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 et des systèmes Exchange hébergés vers Exchange Online dans une seule migration à cutover. 
    
-  Migration Exchange par étapes : effectuez une migration par étapes pour migrer des boîtes aux lettres à partir de Exchange Server 2003 ou Exchange Server 2007 à l’aide d’outils de migration web et de modifications minimales apportées à l’infrastructure locale. 
    
- **Migration de déplacement à distance** : migrer des boîtes aux lettres Exchange vers des boîtes aux lettres Exchange Online dans un déploiement hybride Exchange local. Vous devez mettre en place un déploiement hybride Exchange pour recourir à une migration de déplacement à distance. 
    
Pour plus d'informations sur la migration des e-mails et des boîtes aux lettres vers Exchange Online, voir [Migration de boîtes aux lettres vers Exchange Online](https://support.office.com/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Migration IMAP

Exchange Online propose un outil à extension Web pour la migration des données de boîtes aux lettres à partir de systèmes de messagerie électronique prenant en charge IMAP. Il guide les administrateurs tout au long des étapes de migration suivantes : 
  
1. Création de boîtes aux lettres dans le nuage pour des utilisateurs de l'organisation (en général, cette opération est réalisée en téléchargeant un fichier .csv ou à l'aide de Windows PowerShell à distance.
    
2. Entrée des paramètres de connexion du serveur distant.
    
3. Utilisation d'un fichier CSV pour spécifier les boîtes aux lettres dont les données doivent être migrées vers des boîtes aux lettres Exchange Online.
    
4. Une fois ces informations entrées, Exchange Online commence à migrer le contenu d'une boîte aux lettres via IMAP (la migration ne concerne ni les éléments du calendrier, les contacts, les tâches ni tout autre élément sans rapport avec le courrier électronique).
    
Pour plus d'informations sur la migration IMAP, voir [Migration du courrier électronique à partir d'un serveur IMAP vers des boîtes aux lettres Exchange Online](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) et [Déplacer d'autres types de boîtes aux lettres IMAP](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Pour éviter une sur-utilisation des ressources et de la bande passante du serveur distant pendant la migration, Exchange Online crée moins de 10 connexions vers le serveur IMAP. 
  
### <a name="cutover-exchange-migration"></a>Migration Exchange à basculement

Exchange Online propose un outil à extension Web pour la migration des données à partir d'environnements Exchange Server 2003, Exchange Server 2007 ou Exchange Server 2010 locaux. Il guide l'administrateur tout au long des étapes de migration suivantes :
  
1. Grâce à l'adresse de messagerie et aux informations d'identification d'un compte administrateur local, Exchange Online se connecte à l'organisation de messagerie électronique locale via le service Découverte automatique.
    
2. Exchange Online utilise une connexion RPC/HTTP pour lire les informations d'annuaire dans le serveur distant et crée des boîtes aux lettres dans Exchange Online.
    
3. Exchange Online synchronise le contenu de la boîte aux lettres avec les boîtes aux lettres du nuage. Les utilisateurs restent connectés à leurs boîtes aux lettres d'origine tandis que leurs données sont migrées vers Exchange Online.
    
4. Une fois la migration initiale terminée, toutes les modifications sont synchronisées avec le nuage toutes les 24 heures, tant que l'administrateur n'a pas arrêté ou supprimé le lot de migration.
    
Pour basculer les utilisateurs vers leurs boîtes aux lettres cloud, les administrateurs configurent leur enregistrement MX pour qu’il pointe vers Microsoft et reconfigurent les profils des utilisateurs dans Outlook. Lorsque les utilisateurs basculent vers leurs boîtes aux lettres en nuage, leurs dossiers hors connexion locaux (fichiers .ost) se resynchronisent, ce qui se traduit par le téléchargement de la messagerie migrée dans le poste de travail du client. Les utilisateurs peuvent répondre à des messages anciens de leurs boîtes aux lettres après la migration.
  
Pour plus d'informations sur la migration à basculement Exchange, voir [Ce que vous devez savoir sur une migration de messagerie à basculement vers Office 365](https://support.office.com/article/365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> Une organisation peut migrer un maximum de 2 000 boîtes aux lettres Exchange 2003, 2007, 2010 ou 2013 vers le nuage à l'aide d'une migration Exchange à basculement. > Exchange Online doit se connecter à un serveur Exchange local, ce qui signifie que le serveur local doit posséder un certificat émis par une autorité de certification approuvée et une adresse IP publique. 
  
### <a name="staged-exchange-migration"></a>Migration Exchange progressive

Grâce à la migration progressive, il est possible de migrer les utilisateurs vers le nuage à l'aide de l'outil de migration Exchange à extension Web et de l'outil de synchronisation d'annuaires. Au lieu de migrer tous les utilisateurs en une fois, à l'instar d'une migration Exchange à basculement, les administrateurs effectuent une migration des utilisateurs par lots. Pour cela, il faut télécharger un fichier .csv pour spécifier une liste partielle des utilisateurs à migrer. Lors d'une migration progressive, tous les utilisateurs d'une organisation peuvent partager le même nom de domaine de messagerie électronique.
  
La migration Exchange progressive impose l'utilisation par les administrateurs de l'Outil de synchronisation d'annuaires Microsoft Online Services. Ainsi, les utilisateurs bénéficient d'une liste d'adresses globale unifiée dans laquelle l'environnement en ligne est en permanence synchronisé avec l'environnement local.
  
Pour plus d'informations sur les migrations Exchange intermédiaires, voir [Ce que vous devez savoir sur une migration de messagerie intermédiaire](https://support.office.com/en-ie/article/365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Il est impossible pour des organisations de migrer des boîtes aux lettres Exchange 2010 et 2013 à l'aide d'une migration Exchange progressive. Si votre organisation compte moins de 2 000 boîtes aux lettres Exchange 2010 ou 2013, vous pouvez effectuer une migration Exchange à basculement. Si elle compte plus de 2 000 boîtes aux lettres Exchange 2010 ou 2013, implémentez un déploiement hybride. > Au cours d'une migration, les administrateurs doivent utiliser l'outil de synchronisation d'annuaires Microsoft Online Services pour fournir aux utilisateurs une liste d'adresses globale unifiée dans laquelle l'environnement en ligne est en permanence synchronisé avec l'environnement local. 
  
## <a name="migration-tools"></a>Outils de migration

Microsoft propose plusieurs outils permettant de migrer un environnement de messagerie électronique existant vers Exchange Online. L'outil le plus approprié à utiliser dépend de l'environnement actuel de l'organisation et des objectifs de déploiement :
  
- **Tableau** de bord de migration : les administrateurs peuvent utiliser le tableau de bord de migration dans le Centre d’administration Exchange pour gérer la migration de boîtes aux lettres vers Exchange Online lors d’une migration à Exchange à Exchange étapes. Ils peuvent également utiliser le tableau de bord pour migrer le contenu des boîtes aux lettres des utilisateurs vers des boîtes aux lettres Exchange Online existantes à partir d'un serveur IMAP local. Le tableau de bord offre aux administrateurs les fonctionnalités suivantes : 
    
  - **Créez et démarrez plusieurs lots** de migration : les administrateurs peuvent créer et mettre en file d’attente jusqu’à 100 lots de migration. Un seul lot de migration est exécuté à la fois, mais les administrateurs ont toujours la possibilité de mettre plusieurs lots en file d'attente, de sorte que lorsqu'un lot de migration se termine, l'exécution du lot suivant dans la file d'attente démarre. 
    
  - Redémarrez un lot de **migration** avec des échecs : après la synchronisation initiale d’un lot de migration, où les éléments sont copiés à partir de boîtes aux lettres sur site vers les boîtes aux lettres cloud pour chaque utilisateur du lot de migration, certaines boîtes aux lettres risquent d’échouer à la synchronisation. Les administrateurs ont la possibilité de redémarrer ce lot de migration pour tenter de synchroniser les boîtes aux lettres en échec. 
    
  - Obtenir des détails sur les éléments **ignorés** : pour les migrations IMAP, les migrations à cutover et les migrations par étapes, le tableau de bord de migration affiche des informations sur les éléments spécifiques qui ont été ignorés, notamment la raison et l’emplacement de l’élément dans la boîte aux lettres de l’utilisateur. 
    
  - **Ouvrir des rapports de migration** : les administrateurs peuvent ouvrir les statistiques de migration ou le rapport d’erreurs de migration pour un lot de migration directement à partir du tableau de bord. 
    
  - **Modifier** un lot de migration : si un lot de migration pour une migration Exchange ou une migration IMAP se trouve dans la file d’attente de migration mais n’est pas en cours d’exécution, les administrateurs peuvent modifier le lot de migration. 
    
- **Azure Active Directory Sync** : l’outil de synchronisation Azure Active Directory joue un rôle important dans la migration vers des scénarios de messagerie hybride qui utilisent à la fois Exchange Online et une boîte aux Exchange Server. L'outil exécute une synchronisation monodirectionnelle d'Active Directory local vers Exchange Online. Une fois la migration terminée, les administrateurs doivent seulement utiliser Exchange Online pour gérer des groupes et utilisateurs Active Directory. L'outil fournit également aux utilisateurs une liste d'adresses globale unifiée dans laquelle l'environnement en ligne est en permanence synchronisé avec l'environnement local. 
    
    Pour plus d'informations sur l'Outil de synchronisation Windows Azure Active Directory, consultez la rubrique [Synchronisation d'annuaires : Feuille de route](/azure/active-directory/hybrid/whatis-hybrid-identity).
    
- **Assistant Configuration hybride** : l’Assistant Configuration hybride rationalise le processus de déploiement hybride en simplifiant la configuration des fonctionnalités et des services locaux et Exchange Online local. Introduit dans Exchange Server 2010 Service Pack 2, l'Assistant de configuration hybride est exécuté uniquement dans des organisations locales ; ses composants sont les suivants : 
    
  - Un Assistant Centre d'administration Exchange (EAC) qui guide les administrateurs de bout en bout tout au long du processus de configuration d'un déploiement hybride.
    
  - Un ensemble de commandes de l'environnement de ligne de commande Exchange Management Shell (EMS) qui orchestre le processus de configuration.
    
    Pour plus d'informations sur l'Assistant de configuration hybride, consultez la rubrique [Assistant de configuration hybride](/exchange/hybrid-configuration-wizard).
    
- **Remote Windows PowerShell** - Dans le cadre de la mise à jour Exchange Online service de décembre 2011, les Windows PowerShell distants peuvent être utilisées pour résoudre les erreurs de migration. Par exemple, des administrateurs peuvent afficher des informations de diagnostic relatives à des lots de migration ainsi que des statistiques de migration et des informations de diagnostic pour des utilisateurs en fonction de leurs adresses SMTP principales. 
    
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, consultez la Exchange Online [description du service.](exchange-online-service-description.md)
