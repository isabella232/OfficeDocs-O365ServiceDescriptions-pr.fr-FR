---
title: Partage et collaboration
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: bd1baaf7d6d2a7cc0757f156f2931d7725ee8e2c
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262717"
---
# <a name="sharing-and-collaboration"></a>Partage et collaboration

## <a name="federated-sharing"></a>Partage fédéré

La Fédération fait référence à l’infrastructure d’approbation sous-jacente qui prend en charge le partage fédéré, une méthode permettant aux utilisateurs de Microsoft Exchange Online de partager des données de calendrier de disponibilité et des informations de contact avec des destinataires d’autres organisations fédérées externes ou avec des utilisateurs disposant d’un accès à Internet. Cela comprend les organisations également hébergées par Exchange Online ou par des organisations externes Microsoft Exchange Server 2010 ou Exchange Server 2013. À l’aide des relations d’organisation et des stratégies de partage, les administrateurs Exchange Online peuvent permettre aux utilisateurs d’envoyer des invitations de partage de calendrier à partir de Microsoft Outlook sur le Web ou Microsoft Outlook 2010 ou une version ultérieure.
  
> [!IMPORTANT]
>  Les organisations externes Exchange 2010 et Exchange 2013 doivent configurer une approbation de fédération avec la Microsoft Federation Gateway dans la configuration du partage fédéré. Les organisations Exchange Online ne doivent pas configurer une approbation de fédération : l'approbation de fédération avec Microsoft Federation Gateway est automatiquement créée lors de la création du client Office 365. 
>
>  Les organisations Exchange Online doivent configurer une relation d'organisation ou une stratégie de partage pour activer un partage fédéré. 
>
>  Le partage de listes d’accès globales ou le transfert de boîtes aux lettres d’utilisateur entre des organisations Exchange Online de différents clients Office 365 ne sont pas pris en charge dans le partage fédéré. 
  
Pour plus d'informations sur le partage fédéré, consultez la rubrique [Partage dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Boîtes aux lettres de site

Les courriers électroniques et les documents sont généralement conservés dans deux référentiels de données uniques et indépendants. La plupart des équipes collaborent à l'aide de courriers électroniques et de documents. Le problème vient du fait que la messagerie électronique et les documents sont consultés à l'aide de différents clients. Il en résulte généralement une moindre productivité des utilisateurs et une expérience dégradée pour les utilisateurs.
  
La boîte aux lettres de site est un nouveau concept Exchange 2013 qui essaie de résoudre ce problème. Les boîtes aux lettres de site améliorent la collaboration et la productivité des utilisateurs en utilisant la même interface client pour permettre l'accès aux documents Microsoft SharePoint 2013 et à la messagerie électronique Exchange. Une boîte aux lettres de site se compose de l'appartenance à un site SharePoint (propriétaires et membres), un stockage partagé par le biais d'une boîte aux lettres Exchange 2013 pour des messages électroniques et un site SharePoint 2013 pour des documents, ainsi qu'une interface de gestion qui répond aux besoins de configuration et de cycle de vie.
  
> [!IMPORTANT]
> Votre plan Office 365 doit inclure SharePoint. Les boîtes aux lettres de site nécessitent que les utilisateurs détiennent les licences SharePoint et Exchange. 
  
Pour plus d'informations sur les boîtes aux lettres de site, consultez la rubrique [Boîtes aux lettres de site](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Dossiers publics

Les dossiers publics Exchange Online ont été améliorés afin de bénéficier des technologies de haute disponibilité et de stockage existantes de la base de données de boîtes aux lettres. L'architecture de dossiers publics utilise des boîtes aux lettres spécialement conçues pour stocker à la fois la hiérarchie et les contenus des dossiers publics. Ceci signifie qu'il n'existe plus de base de données indépendante de dossiers publics. La réplication des dossiers publics utilise désormais le modèle de réplication continue. C'est le groupe de disponibilité de base de données (DAG) qui fournit la haute disponibilité en termes de hiérarchie et de contenu des boîtes aux lettres dans le centre de données. Dans Exchange Online, vous êtes limité à 1000 boîtes aux lettres de dossiers publics. Chaque boîte aux lettres de dossiers publics est également limitée par une taille maximale de stockage. Pour plus d’informations, consultez la section « limites des dossiers de boîte aux lettres » dans [limites d’Exchange Online](exchange-online-limits.md). Les boîtes aux lettres de dossiers publics présentent les mêmes limites d'alerte de messages, de destinataires et de capacité que les boîtes aux lettres ordinaires. Pour plus d'informations, consultez la rubrique [Destinataires](recipients.md). 
  
Pour plus d'informations sur les dossiers publics, consultez la rubrique [Dossiers publics](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Groupes et boîtes aux lettres partagées

Les boîtes aux lettres de groupe et partagées permettent à un groupe spécifique de personnes de surveiller et d’envoyer des courriers électroniques à partir d’un compte commun, comme des adresses de messagerie publiques (par exemple, info@contoso.com ou contact@contoso.com). Lorsqu’une personne dans le groupe répond à un message envoyé à la boîte aux lettres partagée, l’e-mail semble provenir de la boîte aux lettres partagée, et non de l’utilisateur individuel.
  
En règle générale, les boîtes aux lettres de groupe ou partagées ne nécessitent pas de licence utilisateur distincte. Toutefois, pour activer une archive sur place pour un groupe ou une boîte aux lettres partagée, vous devez lui attribuer une licence Exchange Online plan 1 ou Exchange Online plan 2. Une fois que la licence est affectée, la taille de la boîte aux lettres augmente de façon correspondante à celle du plan de licence. Pour placer une boîte aux lettres partagée en conservation inaltérable, vous devez lui attribuer une licence Exchange Online plan 2. Veuillez noter que les boîtes aux lettres de groupe ne peuvent pas être affectées pour le moment, mais doivent être comptabilisées dans vos licences totales.
  
La fonctionnalité de boîte aux lettres d'archivage ne peut être utilisée que pour archiver des messages relatifs à un seul utilisateur ou une seule entité (par exemple, une boîte aux lettres partagée) avec une licence active. L'utilisation de la boîte aux lettres d'archivage pour stocker les messages de plusieurs utilisateurs ou entités est interdite. Par exemple, un administrateur informatique ne peut pas créer une boîte aux lettres partagée et permettre aux utilisateurs de la copier (via le champ Cc ou Cci, ou une règle de transport) dans le but explicite de procéder à un archivage. Notez qu’une boîte aux lettres partagée utilisée par plusieurs personnes ne stocke pas les messages de ces utilisateurs individuels. Plusieurs utilisateurs ont accès à cette boîte aux lettres partagée et peuvent envoyer des e-mails à partir d’elle. Par conséquent, les seuls messages électroniques stockés dans la boîte aux lettres partagée sont ceux qui sont envoyés vers ou à partir de cette boîte aux lettres partagée.
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, consultez la rubrique [Description du service Exchange Online](exchange-online-service-description.md).
  

