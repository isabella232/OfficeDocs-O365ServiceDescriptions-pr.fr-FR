---
title: Partage et collaboration
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 25df0c4b4ff71ce8b3543cf7810bb0a4dd3c45fbe1037e1fd8bad4e586dd6292
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663637"
---
# <a name="sharing-and-collaboration"></a>Partage et collaboration

## <a name="federated-sharing"></a>Partage fédéré

La fédération fait référence à l’infrastructure d’confiance sous-jacente qui prend en charge le partage fédéré, une méthode pour que les utilisateurs Microsoft Exchange Online partagent des données de calendrier de libre/occupé et des informations de contact avec des destinataires d’autres organisations fédérées externes ou avec des utilisateurs qui ont accès à Internet. Cela comprend les organisations également hébergées par Exchange Online ou par des organisations externes Microsoft Exchange Server 2010 ou Exchange Server 2013. À l’aide des relations organisationnelles et des stratégies de partage, les administrateurs Exchange Online peuvent permettre aux utilisateurs d’envoyer des invitations de partage de calendrier à partir de Microsoft Outlook sur le web ou Microsoft Outlook 2010 ou une Microsoft Outlook 2010 ultérieure.
  
> [!IMPORTANT]
>  Les organisations externes Exchange 2010 et Exchange 2013 doivent configurer une approbation de fédération avec la Microsoft Federation Gateway dans la configuration du partage fédéré. Exchange Online organisations n’ont pas besoin de configurer une relation d’organisation de fédération : l’Microsoft Federation Gateway de fédération est automatiquement créée lors de la création de l Microsoft 365 de fédération. 
>
>  Les organisations Exchange Online doivent configurer une relation d'organisation ou une stratégie de partage pour activer un partage fédéré. 
>
>  Le partage de listes d’accès globales (LAL) ou le déplacement de boîtes aux lettres d’utilisateurs entre Exchange Online organisations dans différents plans Microsoft n’est pas pris en charge dans le partage fédéré. 
  
Pour plus d'informations sur le partage fédéré, consultez la rubrique [Partage dans Exchange Online](/exchange/sharing/sharing).
  
## <a name="site-mailboxes"></a>Boîtes aux lettres de site

Les courriers électroniques et les documents sont généralement conservés dans deux référentiels de données uniques et indépendants. La plupart des équipes collaborent à l'aide de courriers électroniques et de documents. Le problème vient du fait que la messagerie électronique et les documents sont consultés à l'aide de différents clients. Il en résulte généralement une moindre productivité des utilisateurs et une expérience dégradée pour les utilisateurs.
  
La boîte aux lettres de site est un nouveau concept Exchange 2013 qui essaie de résoudre ce problème. Les boîtes aux lettres de site améliorent la collaboration et la productivité des utilisateurs en utilisant la même interface client pour permettre l'accès aux documents Microsoft SharePoint 2013 et à la messagerie électronique Exchange. Une boîte aux lettres de site se compose de l'appartenance à un site SharePoint (propriétaires et membres), un stockage partagé par le biais d'une boîte aux lettres Exchange 2013 pour des messages électroniques et un site SharePoint 2013 pour des documents, ainsi qu'une interface de gestion qui répond aux besoins de configuration et de cycle de vie.
  
> [!IMPORTANT]
> Votre plan doit inclure des SharePoint. Les boîtes aux lettres de site nécessitent que les utilisateurs détiennent les licences SharePoint et Exchange. 
  
Pour plus d'informations sur les boîtes aux lettres de site, consultez la rubrique [Boîtes aux lettres de site](/exchange/collaboration-exo/collaboration-exo).
  
## <a name="public-folders"></a>Dossiers publics

Les dossiers publics Exchange Online ont été améliorés afin de bénéficier des technologies de haute disponibilité et de stockage existantes de la base de données de boîtes aux lettres. L'architecture de dossiers publics utilise des boîtes aux lettres spécialement conçues pour stocker à la fois la hiérarchie et les contenus des dossiers publics. Ceci signifie qu'il n'existe plus de base de données indépendante de dossiers publics. La réplication des dossiers publics utilise désormais le modèle de réplication continue. C'est le groupe de disponibilité de base de données (DAG) qui fournit la haute disponibilité en termes de hiérarchie et de contenu des boîtes aux lettres dans le centre de données. Dans Exchange Online, vous êtes limité à 1 000 boîtes aux lettres de dossiers publics. Chaque boîte aux lettres de dossiers publics est également limitée par une taille maximale de stockage. Pour plus d’informations, consultez la section « Limites des dossiers de boîtes aux lettres » [Exchange Online limites.](exchange-online-limits.md) Les boîtes aux lettres de dossiers publics présentent les mêmes limites d'alerte de messages, de destinataires et de capacité que les boîtes aux lettres ordinaires. Pour plus d'informations, consultez la rubrique [Destinataires](recipients.md). 
  
Pour plus d'informations sur les dossiers publics, consultez la rubrique [Dossiers publics](/exchange/collaboration-exo/public-folders/public-folders).
  
## <a name="group-and-shared-mailboxes"></a>Boîtes aux lettres partagées et de groupe

Les boîtes aux lettres partagées et de groupe rendent facile pour un groupe spécifique de personnes de surveiller et d’envoyer des messages électroniques à partir d’un compte commun, comme les adresses de messagerie publiques (par exemple, info@contoso.com ou contact@contoso.com). Lorsqu’une personne du groupe répond à un message envoyé à la boîte aux lettres partagée, le message semble être issu de la boîte aux lettres partagée, et non de l’utilisateur individuel.
  
En règle générale, les boîtes aux lettres partagées ou de groupe ne nécessitent pas de licence utilisateur distincte. Toutefois, pour activer In-Place archive d’un groupe ou d’une boîte aux lettres partagée, vous devez lui attribuer une licence Exchange Online Plan 1 ou Exchange Online Plan 2. Une fois que la licence est affectée, la taille de la boîte aux lettres augmente de façon correspondante à celle du plan de licence. Pour placer une boîte aux lettres partagée en In-Place' attente, vous devez lui affecter Exchange Online licence Plan 2. Notez que les boîtes aux lettres de groupe ne peuvent pas être affectées pour le moment, mais qu’elles doivent être pris en compte dans le nombre total de licences.
  
La fonctionnalité de boîte aux lettres d'archivage ne peut être utilisée que pour archiver des messages relatifs à un seul utilisateur ou une seule entité (par exemple, une boîte aux lettres partagée) avec une licence active. L'utilisation de la boîte aux lettres d'archivage pour stocker les messages de plusieurs utilisateurs ou entités est interdite. Par exemple, un administrateur informatique ne peut pas créer une boîte aux lettres partagée et permettre aux utilisateurs de la copier (via le champ Cc ou Cci, ou une règle de transport) dans le but explicite de procéder à un archivage. Notez qu’une boîte aux lettres partagée utilisée par plusieurs personnes ne stocke pas les messages de ces utilisateurs individuels. Plusieurs utilisateurs ont accès à cette boîte aux lettres partagée et peuvent envoyer des e-mails à partir d’elle. Par conséquent, les seuls e-mails stockés dans la boîte aux lettres partagée sont ceux qui sont envoyés ou reçus sur cette boîte aux lettres partagée, en tant qu’entité en soi.
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir [Exchange Online description du service.](exchange-online-service-description.md)
