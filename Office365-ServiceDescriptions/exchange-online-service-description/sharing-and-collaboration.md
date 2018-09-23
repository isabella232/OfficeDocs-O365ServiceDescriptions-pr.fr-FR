---
title: Partage et collaboration
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 13ab2163b76b5ccc4732659a64be5fcead01dc9d
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035531"
---
# <a name="sharing-and-collaboration"></a>Partage et collaboration

## <a name="federated-sharing"></a>Partage fédéré

Le terme fédération désigne l'infrastructure d'approbation sous-jacente qui prend en charge le partage fédéré, qui permet aux utilisateurs de Microsoft Exchange Online de partager des informations de calendrier, de disponibilité et de contact avec les destinataires d'autres organisations fédérées externes ou avec des utilisateurs disposant d'un accès à Internet. Cela comprend les organisations également hébergées par Exchange Online ou par des organisations externes Microsoft Exchange Server 2010 ou Exchange Server 2013. En utilisant les relations des organisations et les stratégies de partage, les administrateurs Exchange Online peuvent autoriser des utilisateurs à envoyer des invitations de partage de calendrier à provenant de Microsoft Outlook Web App ou Microsoft Outlook 2010 ou d'une version ultérieure.
  
> [!IMPORTANT]
>  Les organisations externes Exchange 2010 et Exchange 2013 doivent configurer une approbation de fédération avec la Microsoft Federation Gateway dans la configuration du partage fédéré. Les organisations Exchange Online ne doivent pas configurer une approbation de fédération : l'approbation de fédération avec Microsoft Federation Gateway est automatiquement créée lors de la création du client Office 365. >  Les organisations Exchange Online doivent configurer une relation d'organisation ou une stratégie de partage pour activer un partage fédéré. >  Le partage de la liste d'adresses globale (GAL) ou le déplacement des boîtes aux lettres des utilisateurs entre des organisations Exchange Online de différents clients Office 365 n'est pas pris en charge dans le partage fédéré. 
  
Pour plus d'informations sur le partage fédéré, consultez la rubrique [Partage dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Boîtes aux lettres de site

Les courriers électroniques et les documents sont généralement conservés dans deux référentiels de données uniques et indépendants. La plupart des équipes collaborent à l'aide de courriers électroniques et de documents. Le problème vient du fait que la messagerie électronique et les documents sont consultés à l'aide de différents clients. Il en résulte généralement une moindre productivité des utilisateurs et une expérience dégradée pour les utilisateurs.
  
La boîte aux lettres de site est un nouveau concept Exchange 2013 qui essaie de résoudre ce problème. Les boîtes aux lettres de site améliorent la collaboration et la productivité des utilisateurs en utilisant la même interface client pour permettre l'accès aux documents Microsoft SharePoint 2013 et à la messagerie électronique Exchange. Une boîte aux lettres de site se compose de l'appartenance à un site SharePoint (propriétaires et membres), un stockage partagé par le biais d'une boîte aux lettres Exchange 2013 pour des messages électroniques et un site SharePoint 2013 pour des documents, ainsi qu'une interface de gestion qui répond aux besoins de configuration et de cycle de vie.
  
> [!IMPORTANT]
> Votre plan Office 365 doit inclure SharePoint. Les boîtes aux lettres de site nécessitent que les utilisateurs détiennent les licences SharePoint et Exchange. 
  
Pour plus d'informations sur les boîtes aux lettres de site, consultez la rubrique [Boîtes aux lettres de site](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Dossiers publics

Dossiers publics dans Exchange Online ont été moderniser les réglementations afin de tirer parti des haute disponibilité et stockage les technologies existantes de la base de données de boîtes aux lettres. L’architecture des dossiers publics utilise des boîtes aux lettres spécifiquement conçus pour stocker la hiérarchie et le contenu des dossiers publics. Cela signifie qu’il n’est plus une base de données de dossiers publics distinctes. Réplication des dossiers publics maintenant utilise le modèle de réplication continue. Haute disponibilité pour les boîtes aux lettres de hiérarchie et le contenu est fournie par un groupe de disponibilité de base de données (DAG) dans le centre de données. Dans Exchange Online, vous êtes limité aux boîtes aux lettres de dossier public 1000. Chaque boîte aux lettres de dossier public a également une taille maximale de stockage. Pour plus d’informations, voir la section « Limites de dossier de boîte aux lettres » dans les [Limites d’Exchange Online](exchange-online-limits.md). Boîtes aux lettres de dossier public ont le même message, destinataire et limites de capacité de l’alerte en tant que boîtes aux lettres ordinaires. Pour plus d’informations, consultez la rubrique [Recipients](recipients.md). 
  
Pour plus d'informations sur les dossiers publics, consultez la rubrique [Dossiers publics](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Boîtes aux lettres partagées et de groupe

Les boîtes aux lettres partagées et de groupe permettent à un groupe d'utilisateurs spécifique de surveiller et d'envoyer en toute simplicité des messages électroniques à partir d'un compte commun, comme les adresses de messagerie publiques (par exemple, info@contoso.com ou contact@contoso.com). Quand un membre du groupe répond à un message envoyé à la boîte aux lettres partagée, la réponse semble provenir de cette dernière, et non de ce membre.
  
En règle générale, les boîtes aux lettres partagées ou de groupe ne nécessitent pas de licence utilisateur distincte. Cependant, pour activer l'archivage pour une boîte aux lettres partagée ou de groupe, vous devez lui affecter une licence Exchange Online Plan 1 ou Exchange Online Plan 2. Une fois que la licence est affectée, la taille de la boîte aux lettres augmente de façon correspondante à celle du plan de licence. Pour placer une boîte aux lettres partagée sous conservation inaltérable, vous devez lui affecter une licence Exchange Online Plan 2. Remarque : ces boîtes aux lettres de groupe ne peuvent pas être affectées à ce stade, mais doivent figurer dans votre nombre total de licences.
  
La fonctionnalité de boîte aux lettres d'archivage ne peut être utilisée que pour archiver des messages relatifs à un seul utilisateur ou une seule entité (par exemple, une boîte aux lettres partagée) avec une licence active. L'utilisation de la fonctionnalité de boîte aux lettres d'archivage pour stocker les messages de plusieurs utilisateurs ou entités est interdite. Par exemple, un administrateur informatique ne peut pas créer une boîte aux lettres partagée et permettre aux utilisateurs de la copier (via le champ Cc ou Cci, ou une règle de transport) dans le but explicite de procéder à un archivage. Notez qu'une boîte aux lettres partagée utilisée par plusieurs personnes ne stocke pas les messages de ces utilisateurs individuels. Plusieurs utilisateurs ont accès à cette boîte aux lettres partagée et peuvent envoyer des messages électroniques à partir d'elle. Par conséquent, les seuls messages électroniques stockés dans la boîte aux lettres partagée sont ceux qui sont envoyés ou reçus sur cette boîte aux lettres partagée, en tant qu'entité en soi.
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).
  

