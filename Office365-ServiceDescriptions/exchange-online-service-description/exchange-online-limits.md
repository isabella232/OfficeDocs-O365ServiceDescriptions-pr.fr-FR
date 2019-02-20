---
title: Limites d'Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/19/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Découvrez les limites d’Exchange Online pour plusieurs types de service, notamment concernant les carnets d’adresses, le stockage en boîte aux lettres, ou encore la création de rapports et le suivi des messages, pour n’en citer que quelques-uns.
ms.openlocfilehash: 5e52414fddae0fd1482fbad3bdffa44b081c3ed5
ms.sourcegitcommit: de3d6f2aa5af01645705efe88bb41f9f3a5eef04
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/20/2019
ms.locfileid: "30103112"
---
# <a name="exchange-online-limits"></a>Limites d'Exchange Online

Découvrez les limites d’Exchange Online pour plusieurs types de service, notamment concernant les carnets d’adresses, le stockage en boîte aux lettres, ou encore la création de rapports et le suivi des messages, pour n’en citer que quelques-uns.
  
> [!NOTE]
>  Si vous avez besoin d’aide sur une tâche ou si vous résolvez un problème, les articles suivants pourront peut-être vous être utiles :  <br/> • [Courrier électronique](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US) (pour obtenir de l'aide et envoyer des courriers électroniques)  <br/> • [Courrier électronique dans Office 365 pour les entreprises-aide de l'administrateur](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   • [Résoudre les problèmes liés à Outlook et à office 365 avec l'Assistant support et récupération Microsoft pour Office 365](https://diagnostics.office.com/) <br/>  • Notifications [d'échec de remise par courrier électronique dans Office 365](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • [Aide d'Exchange Online](https://go.microsoft.com/fwlink/?linkid=825607) <br/>
  
Les limites de Microsoft Exchange Online rentrent dans l'une des catégories suivantes:
  
- [Limites du carnet d'adresses](#address-book-limits)
    
- [Limites de stockage des boîtes aux lettres](#mailbox-storage-limits)
    
- [Alertes de capacité](#capacity-alerts)
    
- [Limites de dossier de boîte aux lettres](#mailbox-folder-limits)
    
- [Limites concernant les messages](#message-limits)

- [Limites de réception et d'envoi](#receiving-and-sending-limits)
    
- [Limites de création de rapports et de suivi de messages](#reporting-and-message-trace-limits)
    
- [Limites de rétention](#retention-limits)
    
- [Limites concernant les groupes de distribution](#distribution-group-limits)
    
- [Limites des règles de journal, de transport et de boîte de réception](#journal-transport-and-inbox-rule-limits)
    
- [Limites de modération](#moderation-limits)
    
- [Limites d'Exchange ActiveSync](#exchange-activesync-limits)
    
> [!IMPORTANT]
>  • Les limites appliquées à une organisation Microsoft Office 365 peuvent varier en fonction de la durée de l'enregistrement de l'organisation dans le service.<br/> • Lorsqu'une limite est modifiée dans les centres de données Microsoft, l'application de la modification à tous les clients existants peut prendre un certain temps.<br/> • Vous ne pouvez pas modifier la plupart de ces limites, mais vous et vos utilisateurs devez les connaître.<br/> • Ces limites s'appliquent aux destinataires internes et externes.<br/> • Par défaut, Exchange Online Protection (EOP) protège les boîtes aux lettres Exchange Online. Pour connaître les limites qui s'appliquent aux fonctionnalités EOP dans Exchange Online, consultez la rubrique [Exchange Online Protection Limits](../exchange-online-protection-service-description/exchange-online-protection-limits.md).<br/> • Pour plus d'informations sur les limites de groupe Office 365, voir «comment gérer mon groups?» dans la rubrique [en savoir plus sur les groupes office 365](https://go.microsoft.com/fwlink/?linkid=846714). 
  
## <a name="address-book-limits"></a>Limites du carnet d'adresses

- **Limite de liste d'adresses** Nombre maximal de listes d'adresses pouvant être créées dans une organisation Exchange Online ou Exchange Server 2013. Ce nombre inclut les listes d'adresses par défaut dans Exchange Online, par exemple Tous les contacts et Tous les groupes. 
    
    > [!NOTE]
    > Un maximum de 20 listes d'adresses peuvent être affectées à un carnet d'adresses en mode hors connexion. 
  
- **Limite du carnet d'adresses en mode hors connexion** Nombre maximal de carnets d'adresses en mode hors connexion (OAB) pouvant être créés dans une organisation Exchange Online ou Exchange Server 2013. 
    
- **Limite de stratégies du carnet d'adresses** Nombre maximal de stratégies de carnet d'adresses (ABP) pouvant être créées dans une organisation Exchange Online ou Exchange Server 2013. 
    
- **Listes d'adresses globales** Nombre maximal d'adresses globales (LAG) pouvant être créées dans une organisation Exchange Online ou Exchange Server 2013. 
    
### <a name="address-book-limits-across-office-365-options"></a>Limites du carnet d'adresses en fonction des options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonction** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Limite de liste d'adresses  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Limite de carnet d'adresses en mode hors connexion  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite de stratégies de carnet d'adresses  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite de listes d'adresses globales  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>Limites de carnet d'adresses en fonction des plans autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Limite de liste d'adresses  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Limite de carnet d'adresses en mode hors connexion  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite de stratégies de carnet d'adresses  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite de listes d'adresses globales  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>Limites de stockage des boîtes aux lettres

L'espace de stockage disponible dans une boîte aux lettres est déterminé par son type et la licence d'abonnement de l'utilisateur. Les administrateurs peuvent réduire les tailles maximales de boîte aux lettres pour chaque utilisateur ou globalement.
  
> [!NOTE]
> L'utilisation de la fonction de journalisation, des règles de transport ou des règles de transfert automatique pour copier des messages vers une boîte aux lettres Exchange Online à des fins d'archivage n'est pas autorisée. La boîte aux lettres d'archivage d'un utilisateur est destinée uniquement à cet utilisateur. Microsoft se réserve le droit de refuser l'archivage illimité dans les cas où la boîte aux lettres d'archivage d'un utilisateur sert à stocker les données d'archivage d'autres utilisateurs. 
  
### <a name="storage-limits-across-office-365-options"></a>Limites de stockage parmi les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Boîtes aux lettres utilisateur  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |100 Go  <br/> |100 Go  <br/> |2 Go  <br/> |
|Boîte aux lettres d'archivage<sup>7, 8</sup> <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |UnLimited<sup>1</sup> <br/> |UnLimited<sup>1</sup> <br/> |Non disponible<sup>4</sup> <br/> |
|Boîtes aux lettres partagées  <br/> |50 Go<sup>2</sup> <br/> |50 Go<sup>2</sup> <br/> |50 Go<sup>2</sup> <br/> |50 Go<sup>2, 9</sup> <br/> |50 Go<sup>2, 9</sup> <br/> |50 Go<sup>2</sup> <br/> |
|Boîtes aux lettres de ressources  <br/> |50 Go<sup>3</sup> <br/> |50 Go<sup>3</sup> <br/> |50 Go<sup>3</sup> <br/> |50 Go<sup>3, 9</sup> <br/> |50 Go<sup>3, 9</sup> <br/> |50 Go<sup>3</sup> <br/> |
|Boîtes aux lettres de site<sup>5</sup> <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |Non disponible  <br/> |
|Boîtes aux lettres de dossiers publics  <br/> |50 Go<sup>6</sup> <br/> |50 Go<sup>6</sup> <br/> |50 Go<sup>6</sup> <br/> |100 Go<sup>6</sup> <br/> |100 Go<sup>6</sup> <br/> |Non disponible  <br/> |
|Boîtes aux lettres de groupe  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |
   
> [!NOTE]
> <sup>1</sup> chaque utilisateur reçoit initialement 100 Go de stockage dans la boîte aux lettres d'archivage. Lorsque l'archivage à extension automatique est activé, un espace de stockage supplémentaire est automatiquement ajouté lorsque la capacité de stockage de 100 Go est atteinte. Pour plus d'informations, reportez-vous à la rubrique [Overview of Unlimited Archiving in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Pour plus d'informations sur la disponibilité, voir la feuille de [route Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) .<br/>  <sup>2</sup> pour accéder à une boîte aux lettres partagée, un utilisateur doit disposer d'une licence Exchange Online. Les boîtes aux lettres partagées ne nécessitent pas de licence distincte. Toutefois, sans licence, les boîtes aux lettres partagées sont limitées à 50 Go. Pour augmenter la taille de la boîte aux lettres, une licence E3 ou E5 doit être affectée. Cette opération permet d'augmenter la boîte aux lettres de 100 Go. Si vous souhaitez activer la boîte aux lettres d'archivage ou mettre en attente un litige sur une boîte aux lettres partagée, une licence Exchange Online plan 2 ou Exchange Online plan 1 avec une licence d'archivage Exchange Online est requise. Si vous activez la boîte aux lettres d'archivage et l'archivage à extension automatique pour une boîte aux lettres partagée, un espace de stockage supplémentaire est automatiquement ajouté lorsque la capacité de stockage de 100 Go est atteinte pour la boîte aux lettres d'archivage.<br/>  <sup>3</sup> les boîtes aux lettres de ressources ne nécessitent pas de licence. Toutefois, sans licence, les boîtes aux lettres partagées sont limitées à 50 Go. Pour augmenter la taille de la boîte aux lettres, une licence E3 ou E5 doit être affectée. Cette opération permet d'augmenter la boîte aux lettres de 100 Go.<br/>  <sup>4</sup> les boîtes aux lettres d'archivage ne sont pas incluses dans Exchange Online Kiosk. Toutefois, ils peuvent être achetés en tant que module complémentaire via Exchange Online Archiving. Pour plus d'informations, consultez la [Description du service d'archivAge Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).<br/>  <sup>5</sup> les boîtes aux lettres de site sont créées et gérées dans SharePoint Online. Pour plus d'informations, consultez la rubrique [préparer l'utilisation de boîtes aux lettres de site dans Office 365](http://go.microsoft.com/fwlink/p/?LinkId=299131).<br/>  <sup>6</sup> vous êtes limité à 1 000 boîtes aux lettres de dossiers publics, et la taille totale maximale de toutes les boîtes aux lettres de dossiers publics est de 50 to. Hiérarchie de service les boîtes aux lettres sont limitées à 100 boîtes aux lettres de dossiers publics.<br/>  <sup>7</sup> les boîtes aux lettres d'archivage ne peuvent être utilisées que pour archiver des messages pour un seul utilisateur ou une seule entité (par exemple, une boîte aux lettres partagée) pour laquelle une licence a été appliquée. Utiliser des boîtes aux lettres d'archivage comme moyen de stocker les messages provenant de plusieurs utilisateurs ou entités est interdit. Par exemple, un administrateur informatique ne peut pas créer une boîte aux lettres partagée et faire en sorte que les utilisateurs la copie (via le champ CC ou CCI, ou via une règle de transport) pour l'archivage explicite. Notez qu'une boîte aux lettres partagée utilisée par plusieurs personnes ne stocke pas réellement le courrier électronique pour ces utilisateurs individuels. Plusieurs utilisateurs ont accès et envoient des messages électroniques en tant que boîte aux lettres partagée. Par conséquent, les seuls messages électroniques stockés dans la boîte aux lettres partagée sont ceux qui sont ** envoyés vers ou à partir de cette boîte aux lettres partagée.<br/>  <sup>8</sup> si vous avez créé une stratégie de rétention dans Exchange Online, les messages sont automatiquement déplacés vers la boîte aux lettres d'archivage d'un utilisateur uniquement si la taille de la boîte aux lettres principale de l'utilisateur est supérieure à 10 Mo. La stratégie de rétention ne s'exécute pas automatiquement pour les boîtes aux lettres dont la taille est inférieure à 10 Mo.<br/>  <sup>9</sup> les boîtes aux lettres partagées et de ressources ne nécessitent pas de licence. Toutefois, sans licence, les boîtes aux lettres partagées sont limitées à 50 Go. Pour augmenter la taille de la boîte aux lettres, une licence E3 ou E5 doit être affectée. Cette opération permet d'augmenter la boîte aux lettres de 100 Go. 
  
### <a name="storage-limits-across-standalone-plans"></a>Limites de stockage parmi les plans autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Boîtes aux lettres utilisateur  <br/> |2 Go<sup>1</sup> <br/> |50 Go  <br/> |100 Go  <br/> |2 Go  <br/> |
|Boîtes aux lettres de site<sup>8, 9</sup> <br/> |100 Go<sup>1</sup> <br/> |50 Go  <br/> |UnLimited<sup>2</sup> <br/> |Non disponible<sup>5</sup> <br/> |
|Boîtes aux lettres partagées  <br/> |2 Go<sup>1</sup> <br/> |50 Go<sup>3</sup> <br/> |50 Go<sup>3, 10</sup> <br/> |50 Go<sup>3</sup> <br/> |
|Boîtes aux lettres de ressources  <br/> |2 Go<sup>1</sup> <br/> |50 Go<sup>4</sup> <br/> |50 Go<sup>4, 10</sup> <br/> |50 Go<sup>4</sup> <br/> |
|Boîtes aux lettres de dossiers publics  <br/> |2 Go<sup>6</sup> <br/> |50 Go<sup>7</sup> <br/> |100 Go<sup>7</sup> <br/> |Non disponible  <br/> |
|Boîtes aux lettres de groupe  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |
   
> [!NOTE]
> <sup>1</sup> il s'agit de la taille de boîte aux lettres par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. Il n'y a pas de limite de stockage maximale pour les boîtes aux lettres locales.<br/>  <sup>2</sup> chaque utilisateur reçoit initialement 100 Go de stockage dans la boîte aux lettres d'archivage. Lorsque l'archivage à extension automatique est activé, un espace de stockage supplémentaire est automatiquement ajouté lorsque la capacité de stockage de 100 Go est atteinte. Pour plus d'informations, reportez-vous à la rubrique [Overview of Unlimited Archiving in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Pour plus d'informations sur la disponibilité de l'archivage à extension automatique, voir la feuille de [route Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) .<br/> <sup>3</sup> pour accéder à une boîte aux lettres partagée, un utilisateur doit disposer d'une licence Exchange Online. Les boîtes aux lettres partagées ne nécessitent pas de licence distincte. Toutefois, sans licence, les boîtes aux lettres partagées sont limitées à 50 Go. Pour augmenter la taille de la boîte aux lettres, vous devez attribuer une licence Exchange Online plan 2. Cette opération permet d'augmenter la boîte aux lettres de 100 Go. Si vous souhaitez activer la boîte aux lettres d'archivage ou mettre en attente un litige sur une boîte aux lettres partagée, une licence Exchange Online plan 2 ou Exchange Online plan 1 avec une licence d'archivage Exchange Online est requise. Si vous activez la boîte aux lettres d'archivage et l'archivage à extension automatique pour une boîte aux lettres partagée, un espace de stockage supplémentaire est automatiquement ajouté lorsque la capacité de stockage de 100 Go est atteinte pour la boîte aux lettres d'archivage.<br/> <sup>4</sup> les boîtes aux lettres de ressources ne nécessitent pas de licence. Toutefois, sans licence, les boîtes aux lettres partagées sont limitées à 50 Go. Pour augmenter la taille de la boîte aux lettres, vous devez attribuer une licence Exchange Online plan 2. Cette opération permet d'augmenter la boîte aux lettres de 100 Go.<br/>  <sup>5</sup> les boîtes aux lettres d'archivage ne sont pas incluses dans Exchange Online Kiosk. Toutefois, ils peuvent être achetés en tant que module complémentaire via Exchange Online Archiving. Pour plus d'informations, consultez la [Description du service d'archivAge Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).<br/>  <sup>6</sup> il s'agit de la taille de boîte aux lettres par défaut pour les organisations Microsoft Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. Dans Exchange Server 2013, vous êtes limité à 100 boîtes aux lettres de dossiers publics, et la taille totale maximale de toutes les boîtes aux lettres de dossiers publics est de 50 to.<br/>  <sup>7</sup> dans Exchange Online, vous êtes limité à 1 000 boîtes aux lettres de dossiers publics, et la taille totale maximale de toutes les boîtes aux lettres de dossiers publics est de 50 to.<br/>  <sup>8</sup> les boîtes aux lettres d'archivage ne peuvent être utilisées que pour archiver des messages pour un seul utilisateur ou une seule entité pour laquelle une licence a été appliquée. L'utilisation d'une boîte aux lettres d'archivage comme moyen de stocker des messages provenant de plusieurs utilisateurs ou entités est interdite. Par exemple, les administrateurs informatiques ne peuvent pas créer de boîtes aux lettres partagées et faire en sorte que les utilisateurs copient (via le champ CC ou CCI, ou via une règle de transport) une boîte aux lettres partagée à des fins d'archivage.<br/>  <sup>9</sup> si vous avez créé une stratégie de rétention dans Exchange Online, les messages sont automatiquement déplacés vers la boîte aux lettres d'archivage d'un utilisateur uniquement si la taille de la boîte aux lettres principale de l'utilisateur est supérieure à 10 Mo. La stratégie de rétention ne s'exécute pas automatiquement pour les boîtes aux lettres dont la taille est inférieure à 10 Mo.<br/>  <sup>10</sup> les boîtes aux lettres de ressources et partagées ne nécessitent pas l'attribution d'une licence. Toutefois, sans licence, ces boîtes aux lettres sont limitées à 50 Go. Pour augmenter la taille de la boîte aux lettres, vous devez attribuer une licence Exchange Online plan 2. Cette opération permet d'augmenter la boîte aux lettres de 100 Go. 
  
> [!NOTE]
> Une boîte aux lettres partagée n'est pas conçue pour une ouverture de session directe. Le compte d'utilisateur pour la boîte aux lettres partagée doit rester dans un état **désactivé** (ou «déconnecté»). 
  
## <a name="capacity-alerts"></a>Alertes de capacité

Exchange Online fournit trois types de notifications lorsque la capacité de la boîte aux lettres de l'utilisateur est proche du maximum ou l'atteint :
  
- **Avertissement** L'utilisateur reçoit un avertissement par courrier électronique signifiant que la boîte aux lettres approche la limite de taille maximale. Cet avertissement est destiné à inciter les utilisateurs à supprimer le courrier indésirable. 
    
- **Interdire l'envoi** L'utilisateur reçoit un courrier électronique de notification d'interdiction d'envoi lorsque la limite de taille de boîte aux lettres est atteinte. L'utilisateur ne peut plus envoyer de nouveaux messages tant qu'un nombre suffisant de messages électroniques n'a pas été supprimé afin de ramener la taille de la boîte aux lettres sous la limite. 
    
- **Interdire l'envoi ou la réception** Exchange Online refuse tout courrier électronique entrant lorsque la limite de taille de boîte aux lettres est atteinte, et envoie une notification d'échec de remise à l'expéditeur. L'expéditeur a la possibilité d'effectuer une nouvelle tentative d'envoi du courrier ultérieurement. Pour recevoir de nouveau des messages, l'utilisateur doit supprimer des messages électroniques jusqu'à ce que la taille de la boîte aux lettres passe sous la limite. 
    
### <a name="capacity-alerts-across-office-365-options"></a>Alertes de capacité parmi les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Avertissement  <br/> |49 Go  <br/> |49 Go  <br/> |49 Go  <br/> |98 Go  <br/> |98 Go  <br/> |1,96 Go  <br/> |
|Interdire l'envoi  <br/> |49,5 Go  <br/> |49,5 Go  <br/> |49,5 Go  <br/> |99 Go  <br/> |99 Go  <br/> |1,98 Go  <br/> |
|Interdire l'envoi/la réception  <br/> |50 Go  <br/> |50 Go  <br/> |50 Go  <br/> |100 Go  <br/> |100 Go  <br/> |2 Go  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>Alertes de capacité parmi les plans autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Avertissement  <br/> |1,9 Go<sup>1</sup> <br/> |49 Go  <br/> |98 Go  <br/> |1,96 Go  <br/> |
|Interdire l'envoi  <br/> |2 Go<sup>1</sup> <br/> |49,5 Go  <br/> |99 Go  <br/> |1,98 Go  <br/> |
|Interdire l'envoi/la réception  <br/> |2,3 Go<sup>1</sup> <br/> |50 Go  <br/> |100 Go  <br/> |2 Go  <br/> |
   
> [!NOTE]
> <sup>1</sup> Ceci est la valeur par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. 
  
## <a name="mailbox-folder-limits"></a>Limites de dossier de boîte aux lettres

Ces limites visent à limiter les boîtes aux lettres à des dimensions connues qui peuvent être prises en charge dans Exchange Online. Le but de ces limites est d'empêcher l'existence d'un nombre infini d'éléments de boîte aux lettres par dossier, d'un nombre infini de dossiers par boîte aux lettres ou d'un nombre infini de dossiers publics par organisation Exchange Online. Pour des raisons pratiques, les limites de dossier de boîte aux lettres sont infinies et suffisantes pour prendre en charge la plupart des boîtes aux lettres Exchange Online et les boîtes aux lettres locales migrées vers Exchange Online.
  
- **Nombre maximal de messages par dossier de boîte aux lettres** Indique le nombre maximal de messages pour un dossier de boîte aux lettres. Les nouveaux messages ne peuvent pas être distribués ou enregistrés dans un dossier lorsque cette limite est atteinte. 
    
- **Avertissement pour le nombre de messages par dossier de boîte aux lettres** Indique le nombre de messages qu'un dossier de boîte aux lettres peut contenir avant qu'Exchange Online envoie un message d'avertissement au propriétaire de la boîte aux lettres. Lorsque ce quota est atteint, les messages d'avertissement sont envoyés une fois par jour. 
    
- **Nombre maximal de messages par dossier dans le dossier Éléments récupérables** Indique le nombre maximal de messages que chaque dossier du dossier Éléments récupérables peut contenir. Lorsqu'un dossier dépasse cette limite, il ne peut plus stocker de nouveaux messages. Par exemple, si le dossier Suppressions du dossier Éléments récupérables a dépassé le nombre maximal de messages et que le propriétaire de la boîte aux lettres tente de supprimer définitivement des éléments de sa boîte aux lettres, la suppression échoue. 
    
- **Avertissement pour le nombre de messages par dossier dans le dossier Éléments récupérables** Indique le nombre de messages que chaque dossier du dossier Éléments récupérables peut contenir avant qu'Exchange Online consigne un événement dans le journal des événements d'application. 
    
- **Nombre maximal de sous-dossiers par dossier de boîte aux lettres** Indique le nombre maximal de sous-dossiers qui peuvent être créés dans un dossier de boîte aux lettres. Une fois la limite atteinte, le propriétaire de la boîte aux lettres ne peut plus créer de nouveaux sous-dossiers. 
    
- **Avertissement pour le nombre de sous-dossiers par dossier de boîte aux lettres** Indique le nombre de sous-dossiers qui peuvent être créés dans un dossier de boîte aux lettres avant qu'Exchange Online envoie un message d'avertissement au propriétaire de la boîte aux lettres. Lorsque ce quota est atteint, les messages d'avertissement sont envoyés une fois par jour. 
    
- **Profondeur de hiérarchie de dossiers maximale** Spécifie le nombre maximal de niveaux dans la hiérarchie de dossiers d'une boîte aux lettres. Une fois la limite atteinte, le propriétaire de la boîte aux lettres ne peut pas créer d'autres niveaux dans la hiérarchie de dossiers d'un dossier de boîte aux lettres. 
    
- **Avertissement pour la profondeur de la hiérarchie de dossiers** Indique le nombre de niveaux dans la hiérarchie de dossiers d'un dossier de boîte aux lettres qui peuvent être créés avant qu'Exchange Online envoie un message d'avertissement au propriétaire de la boîte aux lettres. Lorsque ce quota est atteint, les messages d'avertissement sont envoyés une fois par jour. 
    
- **Nombre maximal de dossiers publics** Indique le nombre maximal de dossiers publics dans la hiérarchie complète de dossiers publics. Lorsque cette limite est atteinte, les dossiers publics existants doivent être supprimés pour pouvoir créer d'autres dossiers publics. 
    
- **Nombre maximal de sous-dossiers par dossier public** Indique le nombre maximal de sous-dossiers qui peuvent être créés dans un dossier public. Les nouveaux sous-dossiers ne peuvent pas être créés dans un dossier public lorsque cette limite est atteinte. 
    
- **Avertissement pour le nombre de sous-dossiers par dossier public** Indique le nombre de sous-dossiers qui peuvent être créés dans un dossier public avant qu'Exchange Online envoie un message d'avertissement au propriétaire du dossier. Si aucun propriétaire n'existe, des messages d'avertissement sont envoyés aux utilisateurs disposant d'autorisations de propriétaire. Lorsque ce quota est atteint, les messages d'avertissement sont envoyés une fois par jour. 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>Limites de dossier de boîte aux lettres avec les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Nombre maximal de messages par dossier de boîte aux lettres  <br/> |1 million  <br/> |1 million  <br/> |1 million  <br/> |1 million  <br/> |1 million  <br/> |1 million  <br/> |
|Avertissement pour le nombre de messages par dossier de boîte aux lettres  <br/> |900 000  <br/> |900 000  <br/> |900 000  <br/> |900 000  <br/> |900 000  <br/> |900 000  <br/> |
|Nombre maximal de messages par dossier dans le dossier Éléments récupérables  <br/> |3 millions  <br/> |3 millions  <br/> |3 millions  <br/> |3 millions  <br/> |3 millions  <br/> |3 millions  <br/> |
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres principale (pas en conservation)  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres principale (en conservation)  <br/> |100 Go  <br/> |100 Go  <br/> |100 Go  <br/> |100 Go  <br/> |100 Go  <br/> |100 Go  <br/> |
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres d'archivage (pas en conservation)  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |UnLimited<sup>2</sup> <br/> |UnLimited<sup>2</sup> <br/> |30 Go  <br/> |
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres d'archivage (en conservation)  <br/> |100 Go<sup>1</sup> <br/> |100 Go<sup>1</sup> <br/> |100 Go<sup>1</sup> <br/> |UnLimited<sup>2</sup> <br/> |UnLimited<sup>2</sup> <br/> |100 Go<sup>1</sup> <br/> |
|Avertissement pour le nombre de messages par dossier dans le dossier Éléments récupérables  <br/> |2,75 millions  <br/> |2,75 millions  <br/> |2,75 millions  <br/> |2,75 millions  <br/> |2,75 millions  <br/> |2,75 millions  <br/> |
|Nombre maximal de sous-dossiers par dossier de boîte aux lettres  <br/> |10 000  <br/> |10 000  <br/> |10 000  <br/> |10 000  <br/> |10 000  <br/> |10 000  <br/> |
|Avertissement pour le nombre de sous-dossiers par dossier de boîte aux lettres  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|Profondeur maximale de hiérarchie de dossiers  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Avertissement pour la profondeur de hiérarchie de dossiers  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Nombre maximal de dossiers publics  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |Non disponible  <br/> |
|Nombre maximal de sous-dossiers par dossier public  <br/> |10 000  <br/> |10 000  <br/> |10 000  <br/> |10 000  <br/> |10 000  <br/> |Non disponible  <br/> |
|Avertissement pour le nombre de sous-dossiers par dossier public  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |Non disponible  <br/> |
   
> [!NOTE]
> <sup>1</sup> il s'agit du quota de stockage pour le dossier éléments récupérables, et non du quota pour l'intégralité de la boîte aux lettres d'archivage. Le quota de stockage pour la boîte aux lettres d'archivage est illimité pour les utilisateurs disposant d'une licence Exchange Online plan 2 ou pour les utilisateurs disposant d'une licence Exchange Online plan 1 et d'une licence d'archivage Exchange Online. Pour plus d'informations sur l'augmentation du quota éléments récupérables, consultez [la rubrique augmenter le quota des éléments récupérables pour les boîtes aux lettres en attente](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx).<br/> <sup>2</sup> le quota de stockage initial pour le dossier éléments récupérables dans une boîte aux lettres d'archivage est de 100 Go. Lorsque l'archivage à extension automatique est activé, un espace de stockage supplémentaire est automatiquement ajouté lorsque la capacité de stockage du dossier éléments récupérables est atteinte. Pour plus d'informations, reportez-vous à la rubrique [Overview of Unlimited Archiving in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Pour plus d'informations sur la disponibilité de l'archivage à extension automatique, voir la feuille de [route Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) . 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>Limites de dossier de boîte aux lettres avec les plans autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Nombre maximal de messages par dossier de boîte aux lettres  <br/> |Aucune limite<sup>1</sup> <br/> |1 million  <br/> |1 million  <br/> |1 million  <br/> |
|Avertissement pour le nombre de messages par dossier de boîte aux lettres  <br/> |Sans limite  <br/> |900 000  <br/> |900 000  <br/> |900 000  <br/> |
|Nombre maximal de messages par dossier dans le dossier Éléments récupérables  <br/> |Sans limite  <br/> |3 millions  <br/> |3 millions  <br/> |3 millions  <br/> |
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres principale (pas en conservation)  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres principale (en conservation)  <br/> |100 Go  <br/> |100 Go  <br/> |100 Go  <br/> |100 Go  <br/> |
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres d'archivage (pas en conservation)  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |30 Go  <br/> |
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres d'archivage (en conservation)  <br/> |100 Go<sup>2</sup> <br/> |100 Go<sup>2</sup> <br/> |UnLimited<sup>3</sup> <br/> |UnLimited<sup>3</sup> <br/> |
|Avertissement pour le nombre de messages par dossier dans le dossier Éléments récupérables  <br/> |Aucune limite  <br/> |2,75 millions  <br/> |2,75 million  <br/> |2,75 million  <br/> |
|Nombre maximal de sous-dossiers par dossier de boîte aux lettres  <br/> |Sans limite  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Avertissement pour le nombre de sous-dossiers par dossier de boîte aux lettres  <br/> |Sans limite  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Profondeur maximale de hiérarchie de dossiers  <br/> |Sans limite  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Avertissement pour la profondeur de hiérarchie de dossiers  <br/> |Aucune limite  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Nombre maximal de dossiers publics  <br/> |1 000 000  <br/> |100 000  <br/> |100 000  <br/> |Non disponible  <br/> |
|Nombre maximal de sous-dossiers par dossier public  <br/> |S/O  <br/> |1,000  <br/> |1 000  <br/> |Non disponible  <br/> |
|Avertissement pour le nombre de sous-dossiers par dossier public  <br/> |S/O  <br/> |900  <br/> |900  <br/> |Non disponible  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft ne recommande pas plus de 1 million messages par dossier de boîte aux lettres. Brut<br/> <sup>2</sup> il s'agit du quota de stockage pour le dossier éléments récupérables, et non du quota pour l'intégralité de la boîte aux lettres d'archivage. Le quota de stockage pour la boîte aux lettres d'archivage est illimité pour les utilisateurs disposant d'une licence Exchange Online plan 2 ou pour les utilisateurs disposant d'une licence Exchange Online plan 1 et d'une licence d'archivage Exchange Online. Pour plus d'informations sur l'augmentation du quota éléments récupérables, consultez [la rubrique augmenter le quota des éléments récupérables pour les boîtes aux lettres en attente](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx).<br/> <sup>3</sup> le quota de stockage initial pour le dossier éléments récupérables dans une boîte aux lettres d'archivage est de 100 Go. Lorsque l'archivage à extension automatique est activé, un espace de stockage supplémentaire est automatiquement ajouté lorsque la capacité de stockage du dossier éléments récupérables est atteinte. Pour plus d'informations, reportez-vous à la rubrique [Overview of Unlimited Archiving in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Pour plus d'informations sur la disponibilité de l'archivage à extension automatique, voir la feuille de [route Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) . 
  
## <a name="message-limits"></a>Limites concernant les messages

Les limites suivantes s'appliquent à chaque message électronique.
  
- **Limite de la taille des messages** Des limites de taille des messages sont nécessaires pour éviter tout blocage de remise d'autres messages, et tout risque de voir les performances du service se dégrader pour tous les utilisateurs. Ces limites concernent aussi les pièces jointes, et s'appliquent à toute l'organisation pour tous les messages (entrants, sortants et internes). Les messages qui dépassent cette limite ne sont pas remis, et l'expéditeur reçoit une notification d'échec de remise. Bien qu'il ne soit pas possible de configurer des limites de taille de message en les augmentant, en les diminuant ou en les définissant en fonction de l'utilisateur, les administrateurs peuvent créer des règles de transport pour limiter la taille maximale d'une pièce jointe particulière. Pour plus d'informations, voir l'article relatif à la [prise en charge par Office 365 de messages électroniques plus volumineux](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).
    
    > [!NOTE]
    > Certains clients de messagerie électronique peuvent avoir des limites de taille de message inférieures ou peuvent limiter la taille d'une pièce jointe individuelle à une valeur inférieure à la limite de taille de message d'Exchange Online. 
  
- **Limite de longueur de l'objet** Nombre maximal de caractères de texte autorisés dans la ligne Objet d'un message électronique. 
    
- **Limite du nombre de pièces jointes** Nombre maximal de fichiers en pièce jointe autorisés dans un message électronique. Même si la taille totale de toutes les pièces jointes n'enfreint pas la limite de taille de message, il existe une limite portant sur le nombre de pièces jointes autorisées dans le message. Cette limite est contrôlée par la limite de message à parties multiples. 
    
- **Limite de taille de pièce jointe** Taille de fichier maximale d'une seule pièce jointe. 
    
    > [!NOTE]
    > Il s'agit de la taille maximale d'une seule pièce jointe. Il est possible que certains programmes clients, dont Outlook Web App, limitent la taille des pièces jointes en dessous de ce maximum. Exchange ActiveSync n'implémente pas de limite de taille pour une pièce jointe individuelle. La taille totale de toutes les pièces jointes d'un message Exchange ActiveSync doit être inférieure à la limite de taille des messages. 
  
- **Limite de message à parties multiples** Nombre maximal de parties de corps de message autorisées dans un message à parties multiples au format MIME. Cette limite contrôle également le nombre maximal de fichiers en pièce jointe autorisés dans un message. 
    
- **Limite de profondeur de messages incorporés** Nombre maximal de messages électroniques transférés autorisés dans un message électronique. 
    
### <a name="message-limits-across-office-365-options"></a>Limites de message parmi les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Limite de taille des messages - Outlook  <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |
|Limite de taille des messages - OWA  <br/> |112 Mo<sup>1, 3</sup> <br/> |112 Mo<sup>1, 3</sup> <br/> |112 Mo<sup>1, 3</sup> <br/> |112 Mo<sup>1, 3</sup> <br/> |112 Mo<sup>1, 3</sup> <br/> |112 Mo<sup>1, 3</sup> <br/> |
|Taille limite des messages - Outlook pour Mac  <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |
|Limite de taille des messages - Migration  <br/> |150 Mo<sup>4</sup> <br/> |150 Mo<sup>4</sup> <br/> |150 Mo<sup>4</sup> <br/> |150 Mo<sup>4</sup> <br/> |150 Mo<sup>4</sup> <br/> |150 Mo<sup>4</sup> <br/> |
|Limite de taille pour les messages chiffrés (pour les abonnés utilisant le chiffrement de messages Office 365 avec les nouvelles fonctionnalités)<sup>5</sup> <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |
|Limite de taille pour les messages chiffrés (pour les abonnés utilisant la version héritée du chiffrement de messages Office 365)<sup>5</sup> <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |
|Limite de longueur de l'objet  <br/> |255 caractères  <br/> |255 caractères  <br/> |255 caractères  <br/> |255 caractères  <br/> |255 caractères  <br/> |255 caractères  <br/> |
|Limite du nombre de pièces jointes  <br/> |250 pièces jointes  <br/> |250 pièces jointes  <br/> |250 pièces jointes  <br/> |250 pièces jointes  <br/> |250 pièces jointes  <br/> |250 pièces jointes  <br/> |
|Limite de taille des pièces jointes - Outlook  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |
|Limite de taille des pièces jointes - Outlook Web App <sup>6</sup> <br/> |35 Mo  <br/> |35 Mo  <br/> |35 Mo  <br/> |35 Mo  <br/> |35 Mo  <br/> |35 Mo  <br/> |
|Limite de taille des pièces jointes - Outlook pour Mac  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |
|Limite pour les messages à parties multiples  <br/> |250 parties  <br/> |250 parties  <br/> |250 parties  <br/> |250 parties  <br/> |250 parties  <br/> |250 parties  <br/> |
|Limite de profondeur de messages incorporés  <br/> |30 messages incorporés  <br/> |30 messages incorporés  <br/> |30 messages incorporés  <br/> |30 messages incorporés  <br/> |30 messages incorporés  <br/> |30 messages incorporés  <br/> |
   
> [!NOTE]
> <sup>1</sup> la taille de message maximale par défaut pour les boîtes aux lettres Office 365 est de 25 Mo. Les administrateurs d'Office 365 peuvent spécifier une limite personnalisée comprise entre 1 Mo et 150 Mo. Toutefois, la taille du message que vous pouvez envoyer ou recevoir dépend également de ce que votre client ou solution de messagerie prend en charge. Pour plus d'informations sur la personnalisation de la taille maximale des messages autorisés pour votre organisation, consultez la rubrique [Office 365 prend désormais en charge les messages électroniques plus volumineux](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).<br/> <sup>2</sup> vous pouvez envoyer et recevoir jusqu'à 150 Mo de messages entre les utilisateurs d'Office 365 (où le message ne quitte jamais les centres de donnes Office 365). Les messages routés en dehors des centres de développement Office 365 sont soumis à un codage de traduction supplémentaire de 33%, auquel cas la taille maximale des messages est de 112 Mo.<br/> <sup>3</sup> les comptes OWA permettent de faire en sorte que votre message soit soumis à l'augmentation du codage de 33% et limite la taille du message que vous pouvez envoyer à 25% de moins que le paramètre configuré. Par exemple, si vous personnalisez vos paramètres pour une taille de message de 100 Mo maximum, vous pouvez envoyer des messages dont la taille est inférieure ou égale à 75 Mo.<br/> <sup>4</sup> La taille des messages à déplacer vers Exchange Online est calculée par Exchange Online. Les versions d’Exchange antérieures à Exchange Server 2013 peuvent signaler une taille d’élément inférieure. Cette limite s’applique aux migrations basées sur un déplacement qui utilisent un service de réplication de boîte aux lettres Exchange, quel qu’il soit. La limite générale de taille des messages s’applique à d’autres méthodes de migration (à basculement, intermédiaire, IMAP, PST) et d’autres outils tiers. <br/> <sup>5</sup> pour plus d'informations sur OME avec de nouvelles fonctionnalités, consultez la rubrique [set up New Office 365 message Encryption Capabilities Built-Top of Azure information protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US).<br/> <sup>6</sup> Vous ne pouvez pas joindre un fichier dont la taille est supérieure à 35 Mo. De même, vous ne pouvez pas joindre plusieurs fichiers dont la taille totale dépasse 35 Mo. Par exemple, si vous joignez un fichier de 34 Mo, vous pouvez uniquement joindre un autre fichier de 1 Mo. 
  
### <a name="message-limits-across-standalone-options"></a>Limites de message parmi les options autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Limite de taille des messages - Outlook  <br/> |10 Mo<sup>4</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |150 Mo<sup>2</sup> <br/> |
|Limite de taille des messages - OWA  <br/> |10 Mo<sup>4</sup> <br/> |112 Mo<sup>1, 3</sup> <br/> |112 Mo<sup>1, 3</sup> <br/> |150 Mo<sup>1, 2</sup> <br/> |
|Taille limite des messages - Outlook pour Mac  <br/> |10 Mo<sup>4</sup> <br/> |150 Mo  <br/> |150 Mo  <br/> ||
|Limite de taille des messages - Migration  <br/> |Non applicable  <br/> |150 Mo<sup>5</sup> <br/> |150 Mo<sup>5</sup> <br/> |150 Mo<sup>5</sup> <br/> |
|Limite de taille pour les messages chiffrés (pour les abonnés utilisant le chiffrement de messages Office 365 avec les nouvelles fonctionnalités)<sup>6</sup> <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |
|Limite de taille pour les messages chiffrés (pour les abonnés utilisant la version héritée du chiffrement de messages Office 365)<sup>6</sup> <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |
|Limite de longueur de l'objet  <br/> |255 caractères  <br/> |255 caractères  <br/> |255 caractères  <br/> |255 caractères  <br/> |
|Limite du nombre de pièces jointes  <br/> |1024 pièces jointes<sup>4</sup> <br/> |250 pièces jointes  <br/> |250 pièces jointes  <br/> |250 pièces jointes  <br/> |
|Limite de taille des pièces jointes - Outlook  <br/> |35 Mo<sup>4</sup> <br/> |150 Mo  <br/> |150 Mo  <br/> |150 Mo  <br/> |
|Limite de taille des pièces jointes - OWA  <br/> |35 Mo<sup>4</sup> <br/> |35 Mo  <br/> |35 Mo  <br/> |35 Mo  <br/> |
|Limite de taille des pièces jointes - Outlook pour Mac  <br/> |35 Mo<sup>4</sup> <br/> |150 Mo  <br/> |150 Mo  <br/> |35 Mo  <br/> |
|Limite pour les messages à parties multiples  <br/> |250 parties  <br/> |250 parties  <br/> |250 parties  <br/> |250 parties  <br/> |
|Limite de profondeur de messages incorporés  <br/> |30 messages incorporés  <br/> |30 messages incorporés  <br/> |30 messages incorporés  <br/> |30 messages incorporés  <br/> |
   
> [!NOTE]
> <sup>1</sup> les administrateurs d'Office 365 peuvent spécifier une limite personnalisée comprise entre 1 mo et 150 Mo. Toutefois, la taille du message que vous pouvez envoyer ou recevoir dépend également de ce que votre client ou solution de messagerie prend en charge. Pour plus d'informations sur la personnalisation de la taille maximale des messages autorisés pour votre organisation, consultez la rubrique [Office 365 prend désormais en charge les messages électroniques plus volumineux](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).<br/> <sup>2</sup> vous pouvez envoyer et recevoir jusqu'à 150 Mo de messages entre les utilisateurs d'Office 365 (où le message ne quitte jamais les centres de donnes Office 365). Les messages routés en dehors des centres de développement Office 365 sont soumis à un codage de traduction supplémentaire de 33%, auquel cas la taille maximale des messages est de 112 Mo.<br/> <sup>3</sup> les comptes OWA permettent de faire en sorte que votre message soit soumis à l'augmentation du codage de 33% et limite la taille du message que vous pouvez envoyer à 25% de moins que le paramètre configuré. Par exemple, si vous personnalisez vos paramètres pour une taille de message de 100 Mo maximum, vous pouvez envoyer des messages dont la taille est inférieure ou égale à 75 Mo.<br/> <sup>4</sup> il s'agit de la limite par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation.<br/> <sup>5</sup> la taille des messages à déplacer vers Exchange Online est calculée par Exchange Online. Les versions d'Exchange antérieures à Exchange Server 2013 peuvent indiquer une taille d'élément plus petite.<br/> <sup>6</sup> pour plus d'informations sur OME avec de nouvelles fonctionnalités, consultez la rubrique [set up New Office 365 message Encryption Capabilities Built-Top of Azure information protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US). 
  
## <a name="receiving-and-sending-limits"></a>Limites de réception et d’envoi

Des limites de réception et d’envoi sont appliquées pour lutter contre les vers ou les virus se trouvant dans les envois de publipostage et le courrier indésirable. Ces limites aident à protéger l’intégrité de nos systèmes et les utilisateurs.
  
### <a name="receiving-limits"></a>Limites de réception

Les limites de réception s'appliquent au nombre de messages qu'un utilisateur, groupe ou dossier public peut recevoir par heure. Cela s'applique à la fois pour les messages reçus à partir d'Internet et de serveurs locaux. Lorsque la limite de réception est dépassée, les e-mails envoyés à cette boîte aux lettres recevra une notification d'échec de remise indiquant que la boîte aux lettres a dépassé le seuil maximal de remise. Cette limite se réinitialise une heure après. À ce moment-là, la boîte aux lettres pourra de nouveau recevoir des messages.
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium Office** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Messages reçus  <br/> |3 600 messages par heure  <br/> |3 600 messages par heure  <br/> |3 600 messages par heure  <br/> |3 600 messages par heure  <br/> |3 600 messages par heure  <br/> |3 600 messages par heure  <br/> |
   
### <a name="sending-limits"></a>Limites d'envoi

Les limites d'envoi s'appliquent au nombre de destinataires, au nombre de messages et au nombre de destinataires par message qu'un utilisateur peut envoyer à partir de son compte Exchange Online.
  
> [!NOTE]
> Pour les groupes de distribution stockés dans le carnet d'adresses d'une organisation, le groupe est compté comme un seul destinataire. Pour les groupes de distribution stockés dans le dossier Contacts d'une boîte aux lettres, leurs membres sont comptés individuellement. 
  
- **Limite de nombre de destinataires** Pour dissuader toute remise en nombre de messages non sollicités, Exchange Online dispose de limites de destinataires qui empêchent les utilisateurs et les applications d'envoyer des quantités importantes de messages électroniques. Ces limites sont appliquées par utilisateur pour tous les messages sortants et internes. 
    
    > [!NOTE]
    > Les clients Exchange Online qui doivent envoyer légitimement des messages électroniques en nombre (par exemple, des bulletins d'information) doivent faire appel à des fournisseurs tiers spécialisés dans ces services. 
  
- **Nombre maximal de destinataires** Il s'agit du nombre maximal de destinataires autorisés dans les champs À, Cc et Cci pour un seul message électronique. 
    
    > [!NOTE]
    > Pour la limite de débit maximal de destinataires et le nombre maximal de destinataires, un groupe de distribution stocké dans le carnet d'adresses partagé de l'organisation compte pour un destinataire. Dans une liste de distribution personnelle, chaque destinataire est compté séparément. 
  
- **Limite de débit de messages** Les limites de débit de messages déterminent le nombre de messages qu'un utilisateur peut envoyer à partir de son compte Exchange Online pendant une période spécifiée. Cette limite empêche l'utilisation excessive de ressources système par un même expéditeur. Si un utilisateur envoie des messages à un débit qui dépasse la limite via l'envoi de client SMTP, les messages seront rejetés et le client devra recommencer. 
    
#### <a name="sending-limits-across-office-365-options"></a>Limites d'envoi dans les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Limite de débit de destinataires  <br/> |10 000 destinataires par jour  <br/> |10 000 destinataires par jour  <br/> |10 000 destinataires par jour  <br/> |10 000 destinataires par jour  <br/> |10 000 destinataires par jour  <br/> |10 000 destinataires par jour  <br/> |
|Nombre maximal de destinataires  <br/> |500 destinataires  <br/> |500 destinataires  <br/> |500 destinataires  <br/> |500 destinataires  <br/> |500 destinataires  <br/> |500 destinataires  <br/> |
|Limite d'adresse proxy destinataire  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|Limite de débit maximal des messages  <br/> |30 messages par minute  <br/> |30 messages par minute  <br/> |30 messages par minute  <br/> |30 messages par minute  <br/> |30 messages par minute  <br/> |30 messages par minute  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>Limites d'envoi dans les options autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Limite de débit de destinataires  <br/> |Aucune limite<sup>1</sup> <br/> |10 000 destinataires par jour  <br/> |10 000 destinataires par jour  <br/> |10 000 destinataires par jour  <br/> |
|Nombre maximal de destinataires  <br/> |500 destinataires<sup>1</sup> <br/> |500 destinataires  <br/> |500 destinataires  <br/> |500 destinataires  <br/> |
|Limite d'adresse proxy destinataire  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup> Ceci est la limite par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. 
  
## <a name="reporting-and-message-trace-limits"></a>Limites de création de rapports et de suivi de messages
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

Pour connaître les limites de création de rapports et de suivi de messages, voir la section relative à la latence et à la disponibilité des données en matière de création de rapports et de suivi des messages dans [Création de rapports et suivi des messages dans Exchange Online Protection](http://go.microsoft.com/fwlink/p/?LinkId=394248).
  
## <a name="retention-limits"></a>Limites de rétention
<a name="RetentionLimits"> </a>

Ces limites contrôlent la durée pendant laquelle les éléments situés dans des dossiers spécifiques sont accessibles dans la boîte de réception.
  
- **Période de rétention du dossier des éléments supprimés** Nombre maximal de jours pendant lesquels les éléments peuvent rester dans le dossier Éléments supprimés avant leur suppression automatique. 
    
- **Période de rétention pour les éléments supprimés du dossier éléments supprimés** Nombre maximal de jours pendant lesquels les éléments supprimés du dossier éléments supprimés sont conservés avant leur suppression définitive. 
    
- **Période de rétention du dossier de courrier indésirable** Nombre maximal de jours pendant lesquels les éléments peuvent rester dans le dossier Courrier indésirable avant leur suppression automatique. 
    
### <a name="retention-limits-across-office-365-options"></a>Limites de rétention parmi les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Période de rétention du dossier Éléments supprimés  <br/> |Aucune limite<sup>1</sup> <br/> |Aucune limite<sup>1</sup> <br/> |Aucune limite<sup>1</sup> <br/> |Aucune limite<sup>1</sup> <br/> |Aucune limite<sup>1</sup> <br/> |Aucune limite<sup>1</sup> <br/> |
|Période de rétention pour les éléments supprimés du dossier Éléments supprimés  <br/> |14 jours<sup>1</sup> <br/> |14 jours<sup>1</sup> <br/> |14 jours<sup>1</sup> <br/> |14 jours<sup>1</sup> <br/> |14 jours<sup>1</sup> <br/> |14 jours<sup>1</sup> <br/> |
|Période de rétention du dossier Courrier indésirable  <br/> |30 jours  <br/> |30 jours  <br/> |30 jours  <br/> |30 jours  <br/> |30 jours  <br/> |30 jours  <br/> |
   
> [!NOTE]
> <sup>1</sup> Il s'agit de la limite par défaut. Les administrateurs peuvent modifier cette valeur pour leur organisation. 
  
### <a name="retention-limits-across-standalone-options"></a>Limites de rétention parmi les options autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Période de rétention du dossier Éléments supprimés  <br/> |Aucune limite<sup>1</sup> <br/> |Aucune limite<sup>1</sup> <br/> |Aucune limite<sup>1</sup> <br/> |Aucune limite<sup>1</sup> <br/> |
|Période de rétention pour les éléments supprimés du dossier Éléments supprimés  <br/> |14 jours<sup>1</sup> <br/> |14 jours<sup>2</sup> <br/> |14 jours<sup>2</sup> <br/> |14 jours<sup>2</sup> <br/> |
|Période de rétention du dossier Courrier indésirable  <br/> |2 ans<sup></sup> <br/> |30 jours  <br/> |30 jours  <br/> |30 jours  <br/> |
   
> [!NOTE]
> <sup>1</sup> Il s'agit de la limite par défaut. Les administrateurs peuvent modifier cette valeur pour leur organisation.<br/> <sup>2</sup> il s'agit de la valeur par défaut pour les organisations Exchange Online. Les administrateurs peuvent modifier cette valeur à un maximum de 30 jours pour les boîtes aux lettres de leur organisation. 
  
## <a name="distribution-group-limits"></a>Limites concernant les groupes de distribution

Ces limites s'appliquent aux groupes de distribution figurant dans le carnet d'adresses partagé de votre organisation.
  
- **Nombre maximal de membres d'un groupe de distribution** Le nombre total de destinataires est déterminé après l'extension du groupe de distribution. 
    
- **Limite d'envoi de messages à de grands groupes de distribution** Pour les groupes de distribution qui contiennent le nombre de membres spécifié par cette limite, les options relatives à la gestion de remise ou à l'approbation des messages doivent être configurées. La gestion de remise spécifie la liste des expéditeurs autorisés à envoyer des messages au groupe de distribution. L'approbation des messages spécifie un ou plusieurs modérateurs dont la tâche est d'approuver tous les messages envoyés au groupe de distribution. 
    
- **Taille maximale de message pour les grands groupes de distribution** Si un message est envoyé à au moins 5 000 destinataires, la taille du message ne peut pas dépasser cette limite. Si la taille du message dépasse la limite, ce dernier n'est pas remis, et l'expéditeur reçoit une notification d'échec de remise. Le nombre total de destinataires est déterminé après l'extension du groupe de distribution. 
    
### <a name="distribution-group-limits-across-office-365-options"></a>Limites concernant les groupes de distribution parmi les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Nombre maximal de membres d'un groupe de distribution<sup>1</sup> <br/> |100 000 membres  <br/> |100 000 membres  <br/> |100 000 membres  <br/> |100 000 membres  <br/> |100 000 membres  <br/> |100 000 membres  <br/> |
|Limite d'envoi de messages à de grands groupes de distribution  <br/> |5 000 membres ou plus  <br/> |5 000 membres ou plus  <br/> |5 000 membres ou plus  <br/> |5 000 membres ou plus  <br/> |5 000 membres ou plus  <br/> |5 000 membres ou plus  <br/> |
|Taille maximale des messages pour les groupes de distribution avec 5 000 à 100 000 membres  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |
|Taille maximale des messages pour les groupes de distribution avec 100 000 ou plus de membres  <br/> |5 Mo  <br/> |5 Mo  <br/> |5 Mo  <br/> |5 Mo  <br/> |5 Mo  <br/> |5 Mo  <br/> |
|Nombre maximal de propriétaires de groupe de distribution  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|Nombre maximal de groupes qu'un utilisateur peut créer  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> si vous utilisez Azure Active Directory DirSync, le nombre maximal de membres du groupe de distribution que vous pouvez synchroniser à partir de votre Active Directory local vers Azure Active Directory est de 15 000. Si vous utilisez Azure AD Connect, ce numéro est 50 000.<br/> <sup>2</sup> Cette limite s'applique également aux administrateurs. 
  
### <a name="distribution-group-limits-across-standalone-options"></a>Limites concernant les groupes de distribution parmi les options autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Nombre maximal de membres d'un groupe de distribution  <br/> |100 000 membres<sup>1</sup> <br/> |100 000 membres  <br/> |100 000 membres  <br/> |100 000 membres  <br/> |
|Limite d'envoi de messages à de grands groupes de distribution  <br/> |5 000 membres ou plus<sup>1</sup> <br/> |5 000 membres ou plus  <br/> |5 000 membres ou plus  <br/> |5 000 membres ou plus  <br/> |
|Nombre maximal de propriétaires de groupe de distribution  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|Nombre maximal de groupes qu'un utilisateur peut créer  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Ceci est la limite par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation.<br/> <sup>2</sup> Cette limite s'applique également aux administrateurs. 
  
## <a name="journal-transport-and-inbox-rule-limits"></a>Limites concernant les règles de journal, transport et de boîte de réception

La liste suivante comprend les limites qui s'appliquent aux règles de journal, aux règles de transport, également appelées règles à l'échelle de l'organisation, ainsi que les limites qui s'appliquent aux règles de boîte de réception. Les règles de boîte de réception sont mises en place par des utilisateurs individuels et appliquées aux messages envoyés et reçus par la boîte aux lettres de l'utilisateur individuel.
  
- **Nombre maximal de règles de journal** Nombre maximal de règles de journal qui peuvent exister dans l'organisation. 
    
- **Nombre maximal de règles de transport** Nombre maximal de règles qui peuvent exister dans l'organisation. 
    
- **Taille maximale d'une règle de transport** Nombre maximal de caractères qui peuvent être utilisés dans une règle de transport. Les caractères sont utilisés dans les conditions, les exceptions et les actions. 
    
- **Limite du nombre de caractères pour l'ensemble des expressions régulières utilisées dans toutes les règles de transport** Nombre total de caractères utilisés par l'ensemble des expressions régulières dans toutes les conditions et exceptions des règles de transport au sein de l'organisation. Il arrive qu'un petit nombre de règles utilisent des expressions régulières longues et complexes, ou qu'un grand nombre de règles utilisent des expressions régulières simples. 
    
- **Limites d'analyse pour le contenu des pièces jointes** Les conditions de la règle de transport vous permettent d'examiner le contenu des pièces jointes du message, mais seul le premier Mo du texte extrait d'une pièce jointe est inspecté. Cette limite de 1 Mo porte sur le texte extrait de la pièce jointe, pas sur la taille du fichier en pièce jointe. Par exemple, un fichier de 2 Mo peut contenir moins de 1 Mo de texte, auquel cas l'ensemble du texte sera examiné. 
    
- **Nombre maximal de destinataires ajoutés à un message par l'ensemble des règles de transport** Quand un message est traité par différentes règles de transport, seul un nombre déterminé de destinataires peuvent être ajoutés au message. Une fois la limite atteinte, les destinataires restants ne sont pas ajoutés au message. De plus, une règle de transport ne peut pas ajouter de groupes de distribution à un message. 
    
- **Limite des destinataires de transfert** Nombre maximal de destinataires configurables pour une règle de boîte de réception ou de transport avec une action de redirection. Si une règle est configurée pour rediriger un message vers un nombre de destinataires supérieur à celui défini, la règle ne s'applique pas et aucun message remplissant la condition de la règle n'est redirigé vers les destinataires répertoriés dans cette dernière. 
    
- **Nombre de fois qu'un message est redirigé** Nombre de fois qu'un message est redirigé ou transféré, ou reçoit une réponse automatique sur la base des règles de boîte de réception. Par exemple, l'utilisateur A dispose d'une règle de boîte de réception qui redirige les messages vers l'utilisateur B, en fonction de l'expéditeur. L'utilisateur B dispose d'une règle de boîte de réception qui transfère les messages à l'utilisateur C, en fonction des mots clés figurant dans la ligne Objet. Si un message remplit les deux conditions, il est envoyé uniquement à l'utilisateur B et n'est pas transféré à l'utilisateur C parce qu'une seule redirection est autorisée. Dans ce cas, le message est supprimé sans envoi de notification d'échec de remise (NDR) à l'utilisateur B indiquant que le message n'a pas été remis à l'utilisateur C. 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Limites concernant les règles de journal, de transport et de boîte de réception parmi les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Nombre maximal de règles de journal  <br/> |10 règles  <br/> |10 règles  <br/> |10 règles  <br/> |10 règles  <br/> |10 règles  <br/> |10 règles  <br/> |
|Nombre maximal de règles de transport  <br/> |300 règles  <br/> |300 règles  <br/> |300 règles  <br/> |300 règles  <br/> |300 règles  <br/> |300 règles  <br/> |
|Taille maximale d'une règle de transport  <br/> |8 Ko  <br/> |8 Ko  <br/> |8 Ko  <br/> |8 Ko  <br/> |8 Ko  <br/> |8 Ko  <br/> |
|Limite de caractères pour l'ensemble des expressions régulières utilisées dans toutes les règles de transport  <br/> |20 Ko  <br/> |20 Ko  <br/> |20 Ko  <br/> |20 Ko  <br/> |20 Ko  <br/> |20 Ko  <br/> |
|Limites d'analyse pour le contenu des pièces jointes  <br/> |1 Mo  <br/> |1 Mo  <br/> |1 Mo  <br/> |1 Mo  <br/> |1 Mo  <br/> |1 Mo  <br/> |
|Nombre maximal de destinataires ajoutés à un message par l'ensemble des règles de transport  <br/> |100 destinataires  <br/> |100 destinataires  <br/> |100 destinataires  <br/> |100 destinataires  <br/> |100 destinataires  <br/> |100 destinataires  <br/> |
|Limite des destinataires de transfert  <br/> |10 destinataires  <br/> |10 destinataires  <br/> |10 destinataires  <br/> |10 destinataires  <br/> |10 destinataires  <br/> |10 destinataires  <br/> |
|Nombre de fois qu'un message est redirigé  <br/> |1 redirection  <br/> |1 redirection  <br/> |1 redirection  <br/> |1 redirection  <br/> |1 redirection  <br/> |1 redirection  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Limites concernant les règles de journal, de transport et de boîte de réception parmi les options autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Nombre maximal de règles de journal  <br/> |Aucune limite  <br/> |10 règles  <br/> |10 règles  <br/> |10 règles  <br/> |
|Nombre maximal de règles de transport  <br/> |Aucune limite  <br/> |300 règles  <br/> |300 règles  <br/> |300 règles  <br/> |
|Taille maximale d'une règle de transport  <br/> |40 Ko  <br/> |8 Ko  <br/> |8 Ko  <br/> |8 Ko  <br/> |
|Limite de caractères pour l'ensemble des expressions régulières utilisées dans toutes les règles de transport  <br/> |Aucune limite  <br/> |20 Ko  <br/> |20 Ko  <br/> |20 Ko  <br/> |
|Nombre maximal de destinataires ajoutés à un message par l'ensemble des règles de transport  <br/> |Sans limite  <br/> |100 destinataires  <br/> |100 destinataires  <br/> |100 destinataires  <br/> |
|Limite des destinataires de transfert  <br/> |Sans limite  <br/> |10 destinataires  <br/> |10 destinataires  <br/> |10 destinataires  <br/> |
|Nombre de fois qu'un message est redirigé  <br/> |3 redirections  <br/> |1 redirection  <br/> |1 redirection  <br/> |1 redirection  <br/> |
  
## <a name="moderation-limits"></a>Limites de modération
<a name="ModerationLimits"> </a>

Ces limites contrôlent les paramètres de modération utilisés pour l'approbation de messages appliquée aux groupes de distribution et aux règles de transport.
  
- **Taille maximale de la boîte aux lettres d'arbitrage** Si la boîte aux lettres d'arbitrage dépasse cette limite, les messages qui requièrent une modération sont retournés à l'expéditeur dans une notification d'échec de remise. 
    
- **Nombre maximal de modérateurs** Nombre maximal de modérateurs que vous pouvez affecter à un seul groupe de distribution modéré, ou qui peut être ajouté à un message à l'aide d'une règle de transport unique. Notez qu'en tant que modérateur, vous ne pouvez pas spécifier de groupe de distribution. 
    
- **Expiration des messages en attente de modération** Par défaut, un message en attente de modération expire après deux jours. Toutefois, le traitement des messages modérés ayant expiré s'effectue tous les sept jours. Cela signifie qu'un message modéré peut expirer à tout moment entre deux et neuf jours. 
    
- **Taux maximal de messages de notification pour les messages modérés ayant expiré** Cette limite définit le nombre maximal de messages de notification pour les messages modérés ayant expiré sur une période d'une heure. Cette limite est définie pour chaque base de données de boîtes aux lettres du centre de données. 
    
    Pendant les périodes d'utilisation intensive, certains expéditeurs risquent de ne pas recevoir de messages de notification pour les messages modérés ayant expiré. Toutefois, ces notifications sont toujours détectables à l'aide de rapports de remise.
    
### <a name="moderation-limits-across-office-365-options"></a>Limites de modération parmi les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Taille maximale de la boîte aux lettres d'arbitrage  <br/> |10 Go  <br/> |10 Go  <br/> |10 Go  <br/> |10 Go  <br/> |10 Go  <br/> |10 Go  <br/> |
|Nombre maximal de modérateurs  <br/> |10 modérateurs  <br/> |10 modérateurs  <br/> |10 modérateurs  <br/> |10 modérateurs  <br/> |10 modérateurs  <br/> |10 modérateurs  <br/> |
|Expiration des messages en attente de modération  <br/> |2 jours  <br/> |2 jours  <br/> |2 jours  <br/> |2 jours  <br/> |2 jours  <br/> |2 jours  <br/> |
|Débit maximal de messages de notification d'expiration du délai de modération  <br/> |300 notifications d'expiration par heure  <br/> |300 notifications d'expiration par heure  <br/> |300 notifications d'expiration par heure  <br/> |300 notifications d'expiration par heure  <br/> |300 notifications d'expiration par heure  <br/> |300 notifications d'expiration par heure  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>Limites de modération parmi les options autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Taille maximale de la boîte aux lettres d'arbitrage  <br/> |Aucune limite<sup>1</sup> <br/> |10 Go  <br/> |10 Go  <br/> |10 Go  <br/> |
|Nombre maximal de modérateurs  <br/> |Aucune limite  <br/> |10 modérateurs  <br/> |10 modérateurs  <br/> |10 modérateurs  <br/> |
|Expiration des messages en attente de modération  <br/> |5 jours<sup>1</sup> <br/> |2 jours  <br/> |2 jours  <br/> |2 jours  <br/> |
|Débit maximal de messages de notification d'expiration du délai de modération  <br/> |300 notifications d'expiration par heure  <br/> |300 notifications d'expiration par heure  <br/> |300 notifications d'expiration par heure  <br/> |300 notifications d'expiration par heure  <br/> |
   
> [!NOTE]
> <sup>1</sup> Ceci est la limite par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. 
  
## <a name="exchange-activesync-limits"></a>Limites d'ActiveSync Exchange
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

Les limites suivantes s'appliquent à Microsoft Exchange ActiveSync, un protocole client qui synchronise les données de boîtes aux lettres entre les appareils mobiles et Exchange. 
  
- Limite de l'appareil **Exchange ActiveSync** Le nombre maximal d'appareils Exchange ActiveSync par boîte aux lettres. 
    
- Limite de suppression de l'appareil **Exchange ActiveSync** Le nombre maximal d'appareils Exchange ActiveSync qu'un administrateur Exchange peut supprimer en un mois. 
    
- **Limite des pièces jointes Exchange ActiveSync** La taille maximale d'une pièce jointe de message qui peut être envoyée ou reçue par un appareil Exchange ActiveSync. 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>Limites d'ActiveSync Exchange dans les options Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Entreprise E1** <br/> |**Office 365 Entreprise E3** <br/> |**Office 365 Entreprise E5** <br/> |**Office 365 Entreprise F1** <br/> |
|Limite de l'appareil Exchange ActiveSync  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Limite de suppression de l'appareil Exchange ActiveSync  <br/> |vingtaine  <br/> |vingtaine  <br/> |vingtaine  <br/> |vingtaine  <br/> |vingtaine  <br/> |vingtaine  <br/> |
|Limite des pièces jointes Exchange ActiveSync  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>Limites d'ActiveSync Exchange dans les options autonomes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online Kiosk** <br/> |
|Limite de l'appareil Exchange ActiveSync  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Limite de suppression de l'appareil Exchange ActiveSync  <br/> |vingtaine  <br/> |vingtaine  <br/> |vingtaine  <br/> |vingtaine  <br/> |
|Limite des pièces jointes Exchange ActiveSync  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |25 Mo  <br/> |
