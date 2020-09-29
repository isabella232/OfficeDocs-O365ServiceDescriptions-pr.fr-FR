---
title: Limites d’Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: High
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Découvrez les limites d’Exchange Online pour plusieurs types de service, notamment concernant les carnets d’adresses, le stockage en boîte aux lettres, ou encore la création de rapports et le suivi des messages, pour n’en citer que quelques-uns.
ms.openlocfilehash: e826db7c1c83a99f468379ea1f387fa4a473c025
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293790"
---
# <a name="exchange-online-limits"></a>Limites d’Exchange Online

Découvrez les limites d’Exchange Online pour plusieurs types de service, notamment concernant les carnets d’adresses, le stockage en boîte aux lettres, ou encore la création de rapports et le suivi des messages, pour n’en citer que quelques-uns.

> [!NOTE]
> Si vous avez besoin d’aide sur une tâche ou si vous résolvez un problème, les articles suivants pourront peut-être vous être utiles :
> - [Courrier électronique](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed) (pour obtenir de l’aide et envoyer des courriers électroniques)
>- [Courrier électronique dans Microsoft 365 pour les entreprises-aide de l’administrateur](https://go.microsoft.com/fwlink/?linkid=529722)
>- [Résoudre les problèmes liés à Outlook et à Microsoft 365 avec l’Assistant support et récupération Microsoft](https://diagnostics.office.com/)
>- [Envoyer des notifications d’échec de remise](https://go.microsoft.com/fwlink/?linkid=526653)
>- [Aide d’Exchange Online](https://go.microsoft.com/fwlink/?linkid=825607)<

Les limites dans Microsoft Exchange Online peuvent être classées dans l'une des catégories suivantes :

- [Limites du carnet d’adresses](#address-book-limits)

- [Limites de stockage des boîtes aux lettres](#mailbox-storage-limits)

- [Alertes de capacité](#capacity-alerts)

- [Mailbox folder limits](#mailbox-folder-limits)

- [Limites concernant les messages](#message-limits)

- [Limites de réception et d’envoi](#receiving-and-sending-limits)

- [Reporting and message trace limits](#reporting-and-message-trace-limits)

- [Limites concernant la rétention](#retention-limits)

- [Limites concernant les groupes de distribution](#distribution-group-limits)

- [Limites des règles de journal, de transport et de boîte de réception](#journal-transport-and-inbox-rule-limits)

- [Limites de modération](#moderation-limits)

- [Limites d’Exchange ActiveSync](#exchange-activesync-limits)

> [!IMPORTANT]
> - Les limites appliquées à une organisation Microsoft 365 peuvent varier en fonction de la durée de l’enregistrement de l’organisation dans le service.
> - En cas de modification d’une limite dans les centres de données Microsoft, l’application de la modification à tous les clients existants peut prendre un certain temps.
> - Vous ne pouvez pas modifier la plupart de ces limites, mais vous et vos utilisateurs devez les connaître.
> - Ces limites s'appliquent aux destinataires internes et externes.
> - Par défaut, Exchange Online Protection (EOP) protège les boîtes aux lettres Exchange Online. Pour connaître les limites qui s’appliquent aux fonctionnalités EOP dans Exchange Online, consultez la rubrique [Exchange Online Protection Limits](../exchange-online-protection-service-description/exchange-online-protection-limits.md).
> - Pour plus d’informations sur les limites de groupe Office 365, voir « comment gérer mes groupes ? » en [savoir plus sur les groupes Microsoft 365](https://go.microsoft.com/fwlink/?linkid=846714).

## <a name="address-book-limits"></a>Limites du carnet d’adresses

- **Limite de liste d’adresses**: nombre maximal de listes d’adresses pouvant être créées dans une organisation Exchange Online ou exchange Server 2013. Ce nombre inclut les listes d'adresses par défaut dans Exchange Online, par exemple Tous les contacts et Tous les groupes.

    > [!NOTE]
    > Un maximum de 20 listes d'adresses peuvent être affectées à un carnet d'adresses en mode hors connexion.

- **Limite du carnet d’adresses en mode hors**connexion : nombre maximal de carnets d’adresses en mode hors connexion pouvant être créés dans une organisation Exchange Online ou exchange Server 2013.

- **Limite des stratégies de carnet d’adresses**: nombre maximal de stratégies de carnet d’adresses (carnet) qui sont créées dans une organisation Exchange Online ou exchange Server 2013.

- **Listes d’adresses globales**: nombre maximal de listes d’adresses globales créées dans une organisation Exchange Online ou exchange Server 2013.

### <a name="address-book-limits"></a>Limites du carnet d’adresses

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite de liste d’adresses|1000|1000|1000|1000|1000|1000|
|Limite de carnet d’adresses en mode hors connexion|250|250|250|250|250|250|
|Limite de stratégies de carnet d’adresses|250|250|250|250|250|250|
|Limite de listes d’adresses globales|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>Limites de carnet d’adresses en fonction des plans autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Limite de liste d’adresses|1000|1000|1000|1000|
|Limite de carnet d’adresses en mode hors connexion|250|250|250|250|
|Limite de stratégies de carnet d’adresses|250|250|250|250|
|Limite de listes d’adresses globales|250|250|250|250|

## <a name="mailbox-storage-limits"></a>Limites de stockage des boîtes aux lettres

L'espace de stockage disponible dans une boîte aux lettres est déterminé par son type et la licence d'abonnement de l'utilisateur. Les administrateurs peuvent réduire les tailles maximales de boîte aux lettres pour chaque utilisateur ou globalement.

> [!NOTE]
> L'utilisation de la fonction de journalisation, des règles de transport ou des règles de transfert automatique pour copier des messages vers une boîte aux lettres Exchange Online à des fins d'archivage n'est pas autorisée. La boîte aux lettres d'archivage d'un utilisateur est destinée uniquement à cet utilisateur. Microsoft se réserve le droit de refuser l’archivage illimité dans les cas où la boîte aux lettres d’archivage d’un utilisateur est utilisée pour stocker des données d’archivage pour d’autres utilisateurs ou dans d’autres cas d’utilisation inappropriée.

### <a name="storage-limits"></a>Limites de stockage

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Boîtes aux lettres utilisateur|50 Go|50 Go|50 Go|100 Go|100 Go|2 Go|
|Boîtes aux lettres d’archivage<sup>7, 8</sup>|50 Go|50 Go|50 Go|Unlimited<sup>1</sup>|Unlimited<sup>1</sup>|Non disponible<sup>4</sup>|
|Boîtes aux lettres partagées<sup>10</sup>|50 Go<sup>2</sup>|50 Go<sup>2</sup>|50 Go<sup>2</sup>|50/100 Go<sup>2, 9</sup>|50/100 Go<sup>2, 9</sup>|50 Go<sup>2</sup>|
|Boîtes aux lettres de ressources|50 Go<sup>3</sup>|50 Go<sup>3</sup>|50 Go<sup>3</sup>|50 Go<sup>3,9</sup>|50 Go<sup>3,9</sup>|50 Go<sup>3</sup>|
|Boîtes aux lettres de site<sup>5</sup>|50 Go|50 Go|50 Go|50 Go|50 Go|Non disponible|
|Boîtes aux lettres de dossiers publics|50 Go<sup>6</sup>|50 Go<sup>6</sup>|50 Go<sup>6</sup>|100 Go<sup>6</sup>|100 Go<sup>6</sup>|Non disponible|
|Boîtes aux lettres de groupe|50 Go|50 Go|50 Go|50 Go|50 Go|50 Go|

> [!NOTE]
> <sup>1</sup> Au départ, chaque utilisateur reçoit 100 Go de stockage dans la boîte aux lettres d'archivage. Lorsque l’archivage à extension automatique est activé, un espace de stockage supplémentaire est ajouté automatiquement lorsque la capacité de stockage de 100 Go est atteinte. Pour plus d'informations, reportez-vous à la rubrique [Présentation de l'archivage illimité dans Office 365](https://go.microsoft.com/fwlink/?linkid=844060). <br/> <sup>2</sup> pour accéder à une boîte aux lettres partagée, un utilisateur doit disposer d’une licence Exchange Online, mais la boîte aux lettres partagée ne nécessite pas de licence distincte. Sans licence, les boîtes aux lettres partagées sont limitées à 50 Go. Pour augmenter la limite de taille de 100 Go, la boîte aux lettres partagée doit être affectée à une licence Exchange Online plan 2 ou à une licence Exchange Online plan 1 avec une licence de module complémentaire d’archivage Exchange Online. Cela vous permettra également d’activer l’archivage à extension automatique pour une quantité illimitée de capacité de stockage d’archives. De même, si vous voulez placer une boîte aux lettres partagée en conservation pour litige, la boîte aux lettres partagée doit disposer d’une licence Exchange Online plan 2 ou d’une licence Exchange Online plan 1 avec une licence de module complémentaire d’archivage Exchange Online. Si vous souhaitez appliquer des fonctionnalités avancées telles que Office 365 Advanced Threat Protection, Advanced eDiscovery ou des stratégies de rétention automatique, la boîte aux lettres partagée doit être concédée sous licence pour ces fonctionnalités. <br/> <sup>3</sup> Les boîtes aux lettres de ressources ne nécessitent pas de licence. Toutefois, sans licence, les boîtes aux lettres de ressources sont limitées à 50 Go. Pour augmenter la taille de boîte aux lettres, une licence E3 ou E5 doit être affectée. Cela augmente la boîte aux lettres à 100 Go. <br/> <sup>4</sup> Les boîtes aux lettres d’archive ne sont pas incluses dans Exchange Online Kiosk. Elles peuvent néanmoins être achetées en tant que module complémentaire via Archivage Exchange Online. Pour plus d’informations, consultez la [Description du service d’archivage Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>5</sup> les boîtes aux lettres de site ont été supprimées d’Exchange Online et de SharePoint online dans 2017. <br/> <sup>6</sup> Vous êtes limité à 1000 boîtes aux lettres de dossiers publics, et la taille totale maximale de toutes les boîtes aux lettres de dossiers publics est de 50 To. Les boîtes aux lettres par hiérarchie sont limitées à 100 boîtes aux lettres de dossiers publics. <br/> <sup>7</sup> La boîte aux lettres d'archivage ne peut être utilisée que pour archiver des messages relatifs à un seul utilisateur ou une seule entité (par exemple, une boîte aux lettres partagée) avec une licence active. L'utilisation de la boîte aux lettres d'archivage pour stocker les messages de plusieurs utilisateurs ou entités est interdite. Par exemple, un administrateur informatique ne peut pas créer une boîte aux lettres partagée et permettre aux utilisateurs de la copier (via le champ Cc ou Cci, ou une règle de transport) dans le but explicite de procéder à un archivage. Notez qu’une boîte aux lettres partagée utilisée par plusieurs personnes ne stocke pas les messages de ces utilisateurs individuels. Plusieurs utilisateurs ont accès à cette boîte aux lettres partagée et peuvent envoyer des e-mails à partir d’elle. Par conséquent, les seuls e-mails stockés dans la boîte aux lettres partagée sont ceux qui sont envoyés ou reçus sur cette boîte aux lettres partagée, en tant qu’entité *en soi*. <br/> <sup>8</sup> Si vous avez créé une stratégie de rétention dans Exchange Online, les messages ne sont automatiquement déplacés vers la boîte aux lettres d'archivage d'un utilisateur que si sa boîte aux lettres principale dépasse les 10 Mo. La stratégie de rétention ne s’exécute pas automatiquement pour les boîtes aux lettres de moins de 10 Mo. <br/> <sup>9</sup> Les boîtes aux lettres partagées et les boîtes aux lettres de ressources ne nécessitent pas de licence. Toutefois, sans licence, ces boîtes aux lettres sont limitées à 50 Go. Pour augmenter la taille de boîte aux lettres, une licence E3 ou E5 doit être affectée. Cela augmente la boîte aux lettres à 100 Go. <br/> <sup>10</sup> par défaut, les boîtes aux lettres partagées ont un compte d’utilisateur actif associé avec un mot de passe (inconnu) généré par le système. Pour bloquer la connexion pour le compte de boîte aux lettres partagé associé, consultez [la rubrique bloquer la connexion pour le compte de boîte aux lettres partagée](https://docs.microsoft.com/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

### <a name="storage-limits-across-standalone-plans"></a>Limites de stockage parmi les plans autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Boîtes aux lettres utilisateur|2 Go<sup>1</sup>|50 Go|100 Go|2 Go|
|Boîtes aux lettres de site<sup>8, 9</sup>|100 Go<sup>1</sup>|50 Go|Unlimited<sup>2</sup>|Non disponible<sup>5</sup>|
|Boîtes aux lettres partagées<sup>11</sup>|2 Go<sup>1</sup>|50 Go<sup>3</sup>|50 Go<sup>3,10</sup>|50 Go<sup>3</sup>|
|Boîtes aux lettres de ressources|2 Go<sup>1</sup>|50 Go<sup>4</sup>|50 Go<sup>4,10</sup>|50 Go<sup>4</sup>|
|Boîtes aux lettres de dossiers publics|2 Go<sup>6</sup>|50 Go<sup>7</sup>|100 Go<sup>7</sup>|Non disponible|
|Boîtes aux lettres de groupe|50 Go|50 Go|50 Go|50 Go|

> [!NOTE]
> <sup>1</sup> Ceci est la taille de boîte aux lettres par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. Il n'existe pas de limite de stockage maximale pour les boîtes aux lettres locales. <br/> <sup>2</sup> Au départ, chaque utilisateur reçoit 100 Go de stockage dans la boîte aux lettres d’archivage. Lorsque l’archivage à extension automatique est activé, un espace de stockage supplémentaire est ajouté automatiquement lorsque la capacité de stockage de 100 Go est atteinte. Pour plus d'informations, reportez-vous à la rubrique [Présentation de l'archivage illimité dans Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultez la feuille de [route Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) pour plus d’informations sur la disponibilité de l’archivage à extension automatique. <br/> <sup>3</sup> pour accéder à une boîte aux lettres partagée, un utilisateur doit disposer d’une licence Exchange Online, mais la boîte aux lettres partagée ne nécessite pas de licence distincte. Sans licence, les boîtes aux lettres partagées sont limitées à 50 Go. Pour augmenter la limite de taille de 100 Go, la boîte aux lettres partagée doit être affectée à une licence Exchange Online plan 2 ou à une licence Exchange Online plan 1 avec une licence de module complémentaire d’archivage Exchange Online. Cela vous permettra également d’activer l’archivage à extension automatique pour une quantité illimitée de capacité de stockage d’archives. De même, si vous voulez placer une boîte aux lettres partagée en conservation pour litige, la boîte aux lettres partagée doit disposer d’une licence Exchange Online plan 2 ou d’une licence Exchange Online plan 1 avec une licence de module complémentaire d’archivage Exchange Online. Si vous souhaitez appliquer des fonctionnalités avancées telles que Office 365 Advanced Threat Protection, Advanced eDiscovery ou des stratégies de rétention automatique, la boîte aux lettres partagée doit être concédée sous licence pour ces fonctionnalités. <br/> <sup>4</sup> Les boîtes aux lettres de ressources ne nécessitent pas de licence. Toutefois, sans licence, les boîtes aux lettres de ressources sont limitées à 50 Go. Pour augmenter la taille de boîte aux lettres, une licence Exchange Online Plan 2 doit être affectée. Cela augmente la boîte aux lettres à 100 Go. <br/> <sup>5</sup> Les boîtes aux lettres d’archive ne sont pas incluses dans Exchange Online Kiosk. Elles peuvent néanmoins être achetées en tant que module complémentaire via Archivage Exchange Online. Pour plus d’informations, consultez la [Description du service d’archivage Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>6</sup> Ceci est la taille de boite aux lettres par défaut pour les organisations Microsoft Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. Dans Exchange Server 2013, vous êtes limité à 100 boîtes aux lettres de dossiers publics, et la taille totale maximale de toutes les boîtes aux lettres de dossiers publics est de 50 To. <br/> <sup>7</sup> Dans Exchange Online, vous êtes limité à 1000 boîtes aux lettres de dossiers publics, et la taille totale maximale de toutes les boîtes aux lettres de dossiers publics est de 50 To.  <br/> <sup>8</sup> La boîte aux lettres d'archivage ne peut être utilisée que pour archiver des messages relatifs à un seul utilisateur ou une seule entité disposant d'une licence active. L'utilisation d’une boîte aux lettres d'archivage pour stocker les messages de plusieurs utilisateurs ou entités est interdite. Par exemple, les administrateurs informatiques ne peuvent pas créer des boîtes aux lettres partagées et permettre aux utilisateurs de copier (via le champ Cc ou Cci, ou une règle de transport) une boîte aux lettres de ce type dans le but explicite de procéder à un archivage. <br/> <sup>9</sup> Si vous avez créé une stratégie de rétention dans Exchange Online, les messages ne sont automatiquement déplacés vers la boîte aux lettres d'archivage d'un utilisateur que si sa boîte aux lettres principale dépasse les 10 Mo. La stratégie de rétention ne s’exécute pas automatiquement pour les boîtes aux lettres de moins de 10 Mo. <br/> <sup>10</sup> les boîtes aux lettres de ressources et partagées ne nécessitent pas de licence. Toutefois, sans licence, ces boîtes aux lettres sont limitées à 50 Go. Pour augmenter la taille de boîte aux lettres, une licence Exchange Online Plan 2 doit être affectée. Cela augmente la boîte aux lettres à 100 Go. <br/> <sup>11</sup> par défaut, les boîtes aux lettres partagées ont un compte d’utilisateur actif associé avec un mot de passe (inconnu) généré par le système. Pour bloquer la connexion pour le compte de boîte aux lettres partagé associé, consultez [la rubrique bloquer la connexion pour le compte de boîte aux lettres partagée](https://docs.microsoft.com/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

## <a name="capacity-alerts"></a>Alertes de capacité

Exchange Online fournit trois types de notifications lorsque la capacité de la boîte aux lettres de l'utilisateur est proche du maximum ou l'atteint :

- **Avertissement**: l’utilisateur reçoit un message d’avertissement indiquant que la boîte aux lettres approche la limite de taille maximale. Cet avertissement est destiné à inciter les utilisateurs à supprimer le courrier indésirable.

- **Interdire l’envoi**: l’utilisateur reçoit un message électronique de notification d’interdiction d’envoi lorsque la limite de taille de boîte aux lettres est atteinte. L’utilisateur ne peut pas envoyer de nouveaux messages jusqu’à ce qu’un message électronique soit suffisant pour l’amener à la taille de la boîte aux lettres.

- **Interdire l’envoi/réception**: Exchange Online rejette tous les messages entrants lorsque la limite de taille de boîte aux lettres est atteinte, et envoie une notification d’échec de remise à l’expéditeur. L'expéditeur a la possibilité d'effectuer une nouvelle tentative d'envoi du courrier ultérieurement. Pour recevoir de nouveau des messages, l'utilisateur doit supprimer des messages électroniques jusqu'à ce que la taille de la boîte aux lettres passe sous la limite.

### <a name="capacity-alerts"></a>Alertes de capacité

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Avertissement|49 Go|49 Go|49 Go|98 Go|98 Go|1,96 Go|
|Interdire l’envoi|49,5 Go|49,5 Go|49,5 Go|99 Go|99 Go|1,98 Go|
|Interdire l’envoi/la réception|50 Go|50 Go|50 Go|100 Go|100 Go|2 Go|

### <a name="capacity-alerts-across-standalone-plans"></a>Alertes de capacité parmi les plans autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Avertissement|1,9 Go<sup>1</sup>|49 Go|98 Go|1,96 Go|
|Interdire l’envoi|2 Go<sup>1</sup>|49,5 Go|99 Go|1,98 Go|
|Interdire l’envoi/la réception|2,3 Go<sup>1</sup>|50 Go|100 Go|2 Go|

> [!NOTE]
> <sup>1</sup> Ceci est la valeur par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation.

## <a name="mailbox-folder-limits"></a>Limites de dossier de boîte aux lettres

Ces limites visent à limiter les boîtes aux lettres à des dimensions connues qui peuvent être prises en charge dans Exchange Online. Le but de ces limites est d'empêcher l'existence d'un nombre infini d'éléments de boîte aux lettres par dossier, d'un nombre infini de dossiers par boîte aux lettres ou d'un nombre infini de dossiers publics par organisation Exchange Online. Pour des raisons pratiques, les limites de dossier de boîte aux lettres sont infinies et suffisantes pour prendre en charge la plupart des boîtes aux lettres Exchange Online et les boîtes aux lettres locales migrées vers Exchange Online.

- **Nombre maximal de messages par dossier de boîte aux lettres**: spécifie le nombre maximal de messages pour un dossier de boîte aux lettres. Les nouveaux messages ne peuvent pas être distribués ou enregistrés dans un dossier lorsque cette limite est atteinte.

- **Avertissement pour le nombre de messages par dossier de boîte aux lettres**: spécifie le nombre de messages qu’un dossier de boîte aux lettres peut contenir avant qu’Exchange Online envoie un message d’avertissement au propriétaire de la boîte aux lettres. Lorsque ce quota est atteint, les messages d'avertissement sont envoyés une fois par jour.

- **Nombre maximal de messages par dossier dans le dossier éléments récupérables**: spécifie le nombre maximal de messages qui peuvent être contenus dans chaque dossier dans le dossier éléments récupérables. Lorsqu'un dossier dépasse cette limite, il ne peut plus stocker de nouveaux messages. Par exemple, si le dossier Suppressions du dossier Éléments récupérables a dépassé le nombre maximal de messages et que le propriétaire de la boîte aux lettres tente de supprimer définitivement des éléments de sa boîte aux lettres, la suppression échoue.

- **Avertissement pour le nombre de messages par dossier dans le dossier éléments récupérables**: spécifie le nombre de messages que chaque dossier du dossier éléments récupérables peut contenir avant qu’Exchange Online ne consigne un événement dans le journal des événements d’application.

- **Nombre maximal de sous-dossiers par dossier de boîte aux lettres**: spécifie le nombre maximal de sous-dossiers pouvant être créés dans un dossier de boîte aux lettres. Une fois la limite atteinte, le propriétaire de la boîte aux lettres ne peut plus créer de nouveaux sous-dossiers.

- **Avertissement pour le nombre de sous-dossiers par dossier de boîte aux lettres**: spécifie le nombre de sous-dossiers pouvant être créés dans un dossier de boîte aux lettres avant qu’Exchange Online envoie un message d’avertissement au propriétaire de la boîte aux lettres. Lorsque ce quota est atteint, les messages d'avertissement sont envoyés une fois par jour.

- Taille maximale de la **hiérarchie de dossiers**: spécifie le nombre maximal de niveaux dans la hiérarchie de dossiers d’une boîte aux lettres. Une fois la limite atteinte, le propriétaire de la boîte aux lettres ne peut pas créer d'autres niveaux dans la hiérarchie de dossiers d'un dossier de boîte aux lettres.

- **Avertissement pour la profondeur de hiérarchie de dossiers**: spécifie le nombre de niveaux dans la hiérarchie de dossiers d’un dossier de boîte aux lettres qui peuvent être créés avant qu’Exchange Online envoie un message d’avertissement au propriétaire de la boîte aux lettres. Lorsque ce quota est atteint, les messages d'avertissement sont envoyés une fois par jour.

- **Nombre maximal de dossiers publics**: indique le nombre maximal de dossiers publics dans la hiérarchie de dossiers publics complète. Lorsque cette limite est atteinte, les dossiers publics existants doivent être supprimés pour pouvoir créer d'autres dossiers publics.

- **Nombre maximal de sous-dossiers par dossier public**: spécifie le nombre maximal de sous-dossiers pouvant être créés dans un dossier public. Les nouveaux sous-dossiers ne peuvent pas être créés dans un dossier public lorsque cette limite est atteinte.

- **Avertissement pour le nombre de sous-dossiers par dossier public**: spécifie le nombre de sous-dossiers pouvant être créés dans un dossier public avant qu’Exchange Online envoie un message d’avertissement au propriétaire du dossier. Si aucun propriétaire n'existe, des messages d'avertissement sont envoyés aux utilisateurs disposant d'autorisations de propriétaire. Lorsque ce quota est atteint, les messages d'avertissement sont envoyés une fois par jour.

### <a name="mailbox-folder-limits"></a>Limites de dossier de boîte aux lettres

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Nombre maximal de messages par dossier de boîte aux lettres|1 million|1 million|1 million|1 million|1 million|1 million|
|Avertissement pour le nombre de messages par dossier de boîte aux lettres|900 000|900 000|900 000|900 000|900 000|900 000|
|Nombre maximal de messages par dossier dans le dossier Éléments récupérables|3 millions|3 millions|3 millions|3 millions|3 millions|3 millions|
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres principale (pas en conservation)|30 Go|30 Go|30 Go|30 Go|30 Go|30 Go|
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres principale (en conservation)|100 Go|100 Go|100 Go|100 Go|100 Go|100 Go|
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres d’archivage (pas en conservation)|30 Go|30 Go|30 Go|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 Go|
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres d’archivage (en conservation)|100 Go<sup>1</sup>|100 Go<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|Avertissement pour le nombre de messages par dossier dans le dossier Éléments récupérables|2,75 millions|2,75 millions|2,75 millions|2,75 millions|2,75 millions|2,75 millions|
|Nombre maximal de sous-dossiers par dossier de boîte aux lettres|10 000<sup>2</sup>|10 000<sup>2</sup>|10 000<sup>2</sup>|10 000<sup>2</sup>|10 000<sup>2</sup>|10 000<sup>2</sup>|
|Avertissement pour le nombre de sous-dossiers par dossier de boîte aux lettres|9000|9000|9000|9000|9000|9000|
|Profondeur maximale de hiérarchie de dossiers|300|300|300|300|300|300|
|Avertissement pour la profondeur de hiérarchie de dossiers|250|250|250|250|250|250|
|Nombre maximal de dossiers publics|500 000|500 000|500 000|500 000|500 000|Non disponible|
|Nombre maximal de sous-dossiers par dossier public|10 000|10 000|10 000|10 000|10 000|Non disponible|
|Avertissement pour le nombre de sous-dossiers par dossier public|9000|9000|9000|9000|9000|Non disponible|

> [!NOTE]
> <sup>1</sup> Il s'agit du quota de stockage pour le dossier des éléments récupérables, et non du quota correspondant à l'ensemble de la boîte aux lettres d'archivage. Le quota de stockage de la boîte aux lettres d'archivage est illimité pour les utilisateurs disposant d'une licence Exchange Online Plan 2 ou pour les utilisateurs disposant d'un Exchange Online Plan 1 et d'une licence d'archivage Exchange Online. Pour plus d’informations pour savoir comment augmenter le quota d’éléments récupérables, voir [Augmenter le quota d’éléments récupérables pour les boîtes aux lettres en attente](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>2</sup> Le quota de stockage initial pour le dossier des éléments récupérables dans une boîte aux lettres d’archivage est de 100 Go. Lorsque l’archivage à extension automatique est activé, un espace de stockage supplémentaire est ajouté automatiquement lorsque la capacité de stockage du dossier des éléments récupérables est atteinte. Pour plus d'informations, reportez-vous à la rubrique relative à la [présentation de l'archivage illimité dans Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Pour plus d’informations sur la disponibilité de l’archivage à extension automatique, consultez la feuille de [route de Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) .
> <sup>2</sup> il s’agit d’une limite de magasin ; Il s’agit de l’une des contraintes de forme de boîte aux lettres. Il peut y avoir seulement 10 000 dossiers enfants directs pour un parent donné. Cela s’applique indépendamment de la migration ou d’autres clients créant des dossiers.

### <a name="mailbox-folder-limits-across-standalone-plans"></a>Limites de dossier de boîte aux lettres avec les plans autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Nombre maximal de messages par dossier de boîte aux lettres|Aucune limite<sup>1</sup>|1 million|1 million|1 million|
|Avertissement pour le nombre de messages par dossier de boîte aux lettres|Aucune limite|900 000|900 000|900 000|
|Nombre maximal de messages par dossier dans le dossier Éléments récupérables|Sans limite|3 millions|3 millions|3 millions|
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres principale (pas en conservation)|30 Go|30 Go|30 Go|30 Go|
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres principale (en conservation)|100 Go|100 Go|100 Go|100 Go|
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres d’archivage (pas en conservation)|30 Go|30 Go|30 Go|30 Go|
|Quota de stockage pour le dossier Éléments récupérables dans une boîte aux lettres d’archivage (en conservation)|100 Go<sup>2</sup>|100 GB<sup>2</sup>|Unlimited<sup>3</sup>|Unlimited<sup>3</sup>|
|Avertissement pour le nombre de messages par dossier dans le dossier Éléments récupérables|Sans limite|2,75 millions|2,75 millions|2,75 millions|
|Nombre maximal de sous-dossiers par dossier de boîte aux lettres|Aucune limite|1000|1000|1000|
|Avertissement pour le nombre de sous-dossiers par dossier de boîte aux lettres|Aucune limite|900|900|900|
|Profondeur maximale de hiérarchie de dossiers|Aucune limite|300|300|300|
|Avertissement pour la profondeur de hiérarchie de dossiers|Aucune limite|250|250|250|
|Nombre maximal de dossiers publics|1 000 000|100 000|100 000|Non disponible|
|Nombre maximal de sous-dossiers par dossier public|S/O|1 000|1 000|Non disponible|
|Avertissement pour le nombre de sous-dossiers par dossier public|S/O|900|900|Non disponible|

> [!NOTE]
> <sup>1</sup> Microsoft vous recommande de ne pas dépasser 1 000 000 de messages par dossier de boîte aux lettres. > <br/> <sup>2</sup> Il s’agit du quota de stockage pour le dossier Éléments récupérables, et non du quota correspondant à l’ensemble de la boîte aux lettres d’archivage. Le quota de stockage de la boîte aux lettres d'archivage est illimité pour les utilisateurs disposant d'une licence Exchange Online Plan 2 ou pour les utilisateurs disposant d'un Exchange Online Plan 1 et d'une licence d'archivage Exchange Online. Pour plus d’informations pour savoir comment augmenter le quota d’éléments récupérables, voir [Augmenter le quota d’éléments récupérables pour les boîtes aux lettres en attente](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>3</sup> Le quota de stockage initial pour le dossier des éléments récupérables dans une boîte aux lettres d’archivage est de 100 Go. Lorsque l’archivage à extension automatique est activé, un espace de stockage supplémentaire est ajouté automatiquement lorsque la capacité de stockage du dossier des éléments récupérables est atteinte. Pour plus d'informations, reportez-vous à la rubrique relative à la [présentation de l'archivage illimité dans Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Pour plus d’informations sur la disponibilité de l’archivage à extension automatique, consultez la feuille de [route de Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) .

## <a name="message-limits"></a>Limites concernant les messages

Les limites suivantes s'appliquent à chaque message électronique.

- **Limite de taille**des messages : des limites de taille de message sont nécessaires pour empêcher les messages volumineux de bloquer la remise d’autres messages et affecter les performances de service pour tous les utilisateurs. Ces limites concernent aussi les pièces jointes, et s'appliquent à toute l'organisation pour tous les messages (entrants, sortants et internes). Les messages qui dépassent cette limite ne sont pas remis, et l'expéditeur reçoit une notification d'échec de remise. Bien qu'il ne soit pas possible de configurer des limites de taille de message en les augmentant, en les diminuant ou en les définissant en fonction de l'utilisateur, les administrateurs peuvent créer des règles de transport pour limiter la taille maximale d'une pièce jointe particulière. Pour en savoir plus, consultez la rubrique [Microsoft prend en charge les messages électroniques plus volumineux](https://go.microsoft.com/fwlink/?linkid=2144144).

    > [!NOTE]
    > Certains clients de messagerie peuvent avoir des limites de taille de message inférieures ou limiter la taille d’une pièce jointe individuelle à une valeur inférieure à la limite de taille de message Exchange Online.

- **Taille limite d’en-tête de message**: spécifie la taille maximale de tous les champs d’en-tête de message dans un message. La limite actuelle est 256 Ko. Si la taille totale de tous les en-têtes de message dépasse 256 Ko, Exchange Online rejette le message avec l’erreur « 552 5.3.4 La taille d’en-tête est supérieure à la taille maximale spécifiée. » La taille du corps de message ou des pièces jointes n'est pas prise en compte. Dans la mesure où les champs d'en-tête sont en texte brut, la taille de l'en-tête est déterminée par le nombre de caractères dans chaque champ d'en-tête et le nombre total de champs d'en-tête. Chaque caractère du texte correspond à 1 octet.

- **Limite de longueur**de l’objet : nombre maximal de caractères de texte autorisés dans la ligne d’objet d’un message électronique.

- **Limite de pièces jointes**: nombre maximal de pièces jointes autorisées dans un message électronique. Même si la taille totale de toutes les pièces jointes n'enfreint pas la limite de taille de message, il existe une limite portant sur le nombre de pièces jointes autorisées dans le message. Cette limite est contrôlée par la limite de message à parties multiples.

- **Taille limite des pièces jointes**: taille de fichier maximale d’une seule pièce jointe.

    > [!NOTE]
    > Il s'agit de la taille maximale d'une seule pièce jointe. Les programmes clients individuels, y compris Outlook sur le Web, peuvent limiter la taille des pièces jointes inférieures à ce maximum. Exchange ActiveSync n'implémente pas de limite de taille pour une pièce jointe individuelle. La taille totale de toutes les pièces jointes d'un message Exchange ActiveSync doit être inférieure à la limite de taille des messages.

- **Limite de message en plusieurs**parties : nombre maximal de parties de corps de message autorisées dans un message MIME en plusieurs parties. Cette limite contrôle également le nombre maximal de fichiers en pièce jointe autorisés dans un message.

- **Limite de profondeur de message incorporé**: nombre maximal de messages électroniques transférés autorisés dans un message électronique.

### <a name="message-limits"></a>Limites concernant les messages

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite de taille des messages - Outlook|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|
|Limite de taille des messages - OWA|112 Mo<sup>1, 3</sup>|112 Mo<sup>1, 3</sup>|112 Mo<sup>1, 3</sup>|112 Mo<sup>1, 3</sup>|112 Mo<sup>1, 3</sup>|112 Mo<sup>1, 3</sup>|
|Taille limite des messages - Outlook pour Mac|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|
|Limite de taille des messages - Migration|150 Mo <sup>1, 4</sup>|150 Mo <sup>1, 4</sup>|150 Mo <sup>1, 4</sup>|150 Mo <sup>1, 4</sup>|150 Mo <sup>1, 4</sup>|150 Mo <sup>1, 4</sup>|
|Limite de taille des messages-Outlook pour iOS et Android | 33 MO| 33 MO| 33 MO| 33 MO| 33 MO| 33 MO|
|Limite de taille pour les messages chiffrés (pour les abonnés utilisant le chiffrement de messages Office 365 avec les nouvelles fonctionnalités)<sup>5</sup>|150 Mo|150 Mo|150 Mo|150 Mo|150 Mo|150 Mo|
|Limite de taille pour les messages chiffrés (pour les abonnés utilisant la version héritée du chiffrement de messages Office 365)<sup>5</sup>|25 Mo|25 Mo|25 Mo|25 Mo|25 Mo|25 Mo|
|Limite de longueur de l’objet|255 caractères|255 caractères|255 caractères|255 caractères|255 caractères|255 caractères|
|Limite du nombre de pièces jointes|250 pièces jointes|250 pièces jointes|250 pièces jointes|250 pièces jointes|250 pièces jointes|250 pièces jointes|
|Limite de taille des pièces jointes - Outlook|150 Mo|150 Mo|150 Mo|150 Mo|150 Mo|150 Mo|
|Limite de taille des pièces jointes - OWA |112 Mo<sup>3, 6</sup>|112 Mo<sup>3, 6</sup>|112 Mo<sup>3, 6</sup>|112 Mo<sup>3, 6</sup>|112 Mo<sup>3, 6</sup>|112 Mo<sup>3, 6</sup>|
|Limite de taille des pièces jointes - Outlook pour Mac|150 Mo|150 Mo|150 Mo|150 Mo|150 Mo|150 Mo|
|Limite de taille des pièces jointes-Outlook pour iOS et Android|33 MO |33 MO |33 MO |33 MO |33 MO |33 MO |
|Limite pour les messages à parties multiples|250 parties|250 parties|250 parties|250 parties|250 parties|250 parties|
|Limite de profondeur de messages incorporés|30 messages incorporés|30 messages incorporés|30 messages incorporés|30 messages incorporés|30 messages incorporés|30 messages incorporés|

> [!NOTE]
> <sup>1</sup> la taille de message maximale par défaut pour les boîtes aux lettres Microsoft est de 25 Mo. Les administrateurs Microsoft peuvent spécifier une limite personnalisée comprise entre 1 Mo et 150 Mo. Toutefois, la taille des messages que vous pouvez envoyer ou recevoir dépend des paramètres pris en charge pas votre solution ou client de messagerie. Pour plus d’informations sur la personnalisation de la taille maximale des messages autorisés pour votre organisation, consultez la rubrique [Microsoft prend en charge les messages électroniques plus volumineux](https://go.microsoft.com/fwlink/?linkid=2144144). 
<br/> <sup>2</sup> vous pouvez envoyer et recevoir jusqu’à 150 Mo de messages entre les utilisateurs (où le message ne quitte jamais les centres de donnes Microsoft). Les messages routés en dehors des centres de contenu Microsoft sont soumis à une augmentation supplémentaire de 33% de la traduction, auquel cas la taille maximale du message est de 112 Mo. <br/> 
<sup>3</sup> les comptes OWA permettent de faire en sorte que votre message soit soumis à l’augmentation du codage de 33% et limite la taille du message que vous pouvez envoyer à 25% de moins que le paramètre configuré. Par exemple, si vous personnalisez vos paramètres pour que la taille maximale des messages soit égale à 100 Mo, vous ne pouvez pas envoyer de message d’une taille supérieure à 75 Mo. 
<br/> <sup>4</sup> La taille des messages à déplacer vers Exchange Online est calculée par Exchange Online. Les versions d’Exchange antérieures à Exchange Server 2013 peuvent signaler une taille d’élément inférieure. Cette limite s’applique aux migrations basées sur le déplacement à l’aide d’un service de réplication de boîte aux lettres Exchange pris en charge. Les autres méthodes de migration (basculement, intermédiaire, IMAP, PST) et autres outils tiers sont limitées par la limite de taille des messages généraux. <br/> 
<sup>5</sup> pour plus d’informations sur OME avec de nouvelles fonctionnalités, consultez la rubrique [set up New Office 365 message Encryption Capabilities Built-Top of Azure information protection](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e). <br/> 
<sup>6</sup> les pièces jointes classiques ont une limite de 112 Mo, mais les pièces jointes des fichiers OneDrive peuvent atteindre 2 Go.


### <a name="message-limits-across-standalone-options"></a>Limites de message parmi les options autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Limite de taille des messages - Outlook|10 Mo<sup>4</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>1, 2</sup>|150 Mo<sup>2</sup>|
|Limite de taille des messages - OWA|10 Mo<sup>4</sup>|112 Mo<sup>1, 3</sup>|112 Mo<sup>1, 3</sup>|150 Mo<sup>1, 2</sup>|
|Taille limite des messages - Outlook pour Mac|10 Mo<sup>4</sup>|150 Mo|150 Mo||
|Limite de taille des messages - Migration|Non applicable|150 Mo<sup>5</sup>|150 Mo<sup>5</sup>|150 Mo<sup>5</sup>|
|Limite de taille des messages-Outlook pour iOS et Android |25 Mo |33 MO |33 MO |33 MO |
|Limite de taille pour les messages chiffrés (pour les abonnés utilisant le chiffrement de messages Office 365 avec les nouvelles fonctionnalités)<sup>6</sup>|150 Mo|150 Mo|150 Mo|150 Mo|
|Limite de taille pour les messages chiffrés (pour les abonnés utilisant la version héritée du chiffrement de messages Office 365)<sup>6</sup>|25 Mo|25 Mo|25 Mo|25 Mo|
|Limite de longueur de l’objet|255 caractères|255 caractères|255 caractères|255 caractères|
|Limite du nombre de pièces jointes|1024 attachments<sup>4</sup>|250 pièces jointes|250 pièces jointes|250 pièces jointes|
|Limite de taille des pièces jointes - Outlook|35 Mo<sup>4</sup>|150 Mo|150 Mo|150 Mo|
|Limite de taille des pièces jointes - OWA|35 Mo<sup>4</sup>|112 Mo<sup>3</sup>|112 Mo<sup>3</sup>|112 Mo<sup>3</sup>|
|Limite de taille des pièces jointes - Outlook pour Mac|35 Mo<sup>4</sup>|150 Mo|150 Mo|35 Mo|
|Limite de taille des pièces jointes-Outlook pour iOS et Android|25 Mo |33 MO|33 MO|33 MO|
|Limite pour les messages à parties multiples|250 parties|250 parties|250 parties|250 parties|
|Limite de profondeur de messages incorporés|30 messages incorporés|30 messages incorporés|30 messages incorporés|30 messages incorporés|

> [!NOTE]
> <sup>1</sup> les administrateurs Microsoft peuvent spécifier une limite personnalisée comprise entre 1 mo et 150 Mo. Toutefois, la taille des messages que vous pouvez envoyer ou recevoir dépend des paramètres pris en charge pas votre solution ou client de messagerie. Pour plus d’informations sur la personnalisation de la taille maximale des messages autorisés pour votre organisation, consultez la rubrique [Microsoft prend en charge les messages électroniques plus volumineux](https://go.microsoft.com/fwlink/?linkid=2144144). <br/> <sup>2</sup> vous pouvez envoyer et recevoir jusqu’à 150 Mo de messages entre les utilisateurs (où le message ne quitte jamais les centres de donnes Microsoft). Les messages routés en dehors des centres de contenu Microsoft sont soumis à une augmentation supplémentaire de 33% de la traduction, auquel cas la taille maximale du message est de 112 Mo. <br/> 
<sup>3</sup> les comptes OWA permettent de faire en sorte que votre message soit soumis à l’augmentation du codage de 33% et limite la taille du message que vous pouvez envoyer à 25% de moins que le paramètre configuré. Par exemple, si vous personnalisez vos paramètres pour que la taille maximale des messages soit égale à 100 Mo, vous ne pouvez pas envoyer de message d’une taille supérieure à 75 Mo. <br/> 
<sup>4</sup> il s’agit de la limite par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. <br/> 
<sup>5</sup> la taille des messages à déplacer vers Exchange Online est calculée par Exchange Online. Les versions d’Exchange antérieures à Exchange Server 2013 peuvent signaler une taille d’élément inférieure. <br/> 
<sup>6</sup> pour plus d’informations sur OME avec de nouvelles fonctionnalités, consultez la rubrique [set up New Office 365 message Encryption Capabilities Built-Top of Azure information protection](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).

## <a name="receiving-and-sending-limits"></a>Limites de réception et d’envoi

Des limites de réception et d’envoi sont appliquées pour lutter contre les vers ou les virus se trouvant dans les envois de publipostage et le courrier indésirable. Ces limites aident à protéger l’intégrité de nos systèmes et les utilisateurs.

### <a name="receiving-limits"></a>Limites de réception

Les limites de réception s’appliquent au nombre de messages qu’un utilisateur, un groupe ou un dossier public peut recevoir par heure. Cela s’applique aux messages reçus à partir d’Internet et à partir de serveurs locaux. Lorsque la limite de réception a été dépassée, tous les messages électroniques envoyés à cette boîte aux lettres reçoivent un rapport de non-remise indiquant que la boîte aux lettres a dépassé le seuil de remise maximal. Après une heure, la limite est actualisée et la boîte aux lettres est de nouveau capable de recevoir des messages.

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business standard Office | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Messages reçus|3600 messages par heure|3600 messages par heure|3600 messages par heure|3600 messages par heure|3 600 messages par heure|3 600 messages par heure|

### <a name="sending-limits"></a>Limites d’envoi

Les limites d’envoi s’appliquent au nombre de destinataires, au nombre de messages et au nombre de destinataires par message qu’un utilisateur peut envoyer à partir de son compte Exchange Online.

> [!NOTE]
> Pour les groupes de distribution stockés dans le carnet d'adresses d'une organisation, le groupe est compté comme un seul destinataire. Pour les groupes de distribution stockés dans le dossier Contacts d'une boîte aux lettres, leurs membres sont comptés individuellement.

- **Limite de taux de destinataires**: pour empêcher la remise de messages en masse non sollicités, Exchange Online a des limites de destinataires qui empêchent les utilisateurs et les applications d’envoyer de gros volumes de courriers électroniques. Ces limites sont appliquées par utilisateur pour tous les messages sortants et internes.

    > [!NOTE]
    > Les clients Exchange Online qui doivent envoyer légitimement des messages électroniques en nombre (par exemple, des bulletins d'information) doivent faire appel à des fournisseurs tiers spécialisés dans ces services.

- **Limite de destinataires**: il s’agit du nombre maximal de destinataires autorisés dans les champs à :, CC : et CCI : pour un seul message électronique.

    > [!NOTE]
    > Pour la limite de débit maximal de destinataires et le nombre maximal de destinataires, un groupe de distribution stocké dans le carnet d'adresses partagé de l'organisation compte pour un destinataire. Dans une liste de distribution personnelle, chaque destinataire est compté séparément.

- **Limite d’adresse de proxy de destinataire**: la limite d’adresse de proxy de destinataire est le nombre maximal d’alias (adresses de messagerie) dont peut disposer une boîte aux lettres de destinataire. 

- **Limite de débit de messages**: les limites de fréquence des messages déterminent le nombre de messages qu’un utilisateur peut envoyer à partir de son compte Exchange Online au cours d’une période de temps spécifiée. Cette limite permet d’empêcher la consommation des ressources système par un seul expéditeur. Si un utilisateur envoie des messages à un débit qui dépasse la limite via l'envoi de client SMTP, les messages seront rejetés et le client devra recommencer.

#### <a name="sending-limits"></a>Limites d’envoi

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite de taux de destinataires<sup>1</sup>|10 000 destinataires par jour|10 000 destinataires par jour|10 000 destinataires par jour|10 000 destinataires par jour|10 000 destinataires par jour|10 000 destinataires par jour|
|Limite de destinataires<sup>2</sup>|Personnalisable jusqu’à 1000 destinataires|Personnalisable jusqu’à 1000 destinataires|Personnalisable jusqu’à 1000 destinataires|Personnalisable jusqu’à 1000 destinataires|Personnalisable jusqu’à 1000 destinataires|Personnalisable jusqu’à 1000 destinataires|
|Limite d’adresse proxy destinataire|400|400|400|400|400|400|
|Limite de débit maximal des messages|30 messages par minute|30 messages par minute|30 messages par minute|30 messages par minute|30 messages par minute|30 messages par minute|

> [!NOTE]
> <sup>1</sup> une fois le débit maximal atteint, les messages ne peuvent pas être envoyés à partir de la boîte aux lettres jusqu’à ce que le nombre de destinataires ayant reçu des messages au cours des 24 dernières heures descend en dessous de la limite. Par exemple, un utilisateur envoie un message électronique aux destinataires 5000 à 09:00 AM, puis envoie un autre message aux destinataires 2500 à 10:00, puis envoie un autre message à 2500 destinataires à 11:00 AM, en atteignant la limite de 10 000 messages. L’utilisateur ne pourra pas renvoyer de messages jusqu’à 09:00 AM le jour suivant.
> <sup>2</sup> vous pouvez personnaliser les limites des destinataires entre 1 et 1000 pour les boîtes aux lettres existantes et pour les nouvelles boîtes aux lettres qui seront créées à l’avenir. Modifier la limite de destinataires sur les boîtes aux lettres existantes individuellement ou en bloc à l’aide du centre d’administration Exchange et personnaliser le paramètre par défaut pour les nouvelles boîtes aux lettres via PowerShell à distance. Pour plus d’informations, consultez la rubrique [limites des destinataires personnalisables dans Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).

#### <a name="sending-limits-across-standalone-options"></a>Limites d’envoi dans les options autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Limite de débit de destinataires|Aucune limite<sup>1</sup>|10 000 destinataires par jour<sup>2</sup>|10 000 destinataires par jour<sup>2</sup>|10 000 destinataires par jour<sup>2</sup>|
|Nombre maximal de destinataires|1000 destinataires<sup>1</sup>|1000 destinataires|1000 destinataires|1000 destinataires|
|Limite d’adresse proxy destinataire|400|400|400|400|
|Limite de débit maximal des messages|30 messages par minute|30 messages par minute|30 messages par minute|30 messages par minute|

> [!NOTE]
> <sup>1</sup> Ceci est la limite par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation.<br/>
<sup>2</sup> une fois le débit maximal atteint, les messages ne peuvent pas être envoyés à partir de la boîte aux lettres jusqu’à ce que le nombre de destinataires ayant reçu des messages au cours des 24 dernières heures descend en dessous de la limite. Par exemple, un utilisateur envoie un message électronique aux destinataires 5000 à 09:00 AM, puis envoie un autre message aux destinataires 2500 à 10:00, puis envoie un autre message à 2500 destinataires à 11:00 AM, en atteignant la limite de 10 000 messages. L’utilisateur ne pourra pas renvoyer de messages jusqu’à 09:00 AM le jour suivant.

## <a name="reporting-and-message-trace-limits"></a>Limites de création de rapports et de suivi de messages

Pour plus d’informations sur les rapports et les limites de suivi des messages, consultez la section « disponibilité et latence des données de suivi des rapports et des messages » dans [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=394248).

## <a name="retention-limits"></a>Limites de rétention

Ces limites contrôlent la durée pendant laquelle les éléments situés dans des dossiers spécifiques sont accessibles dans la boîte de réception.

- **Période de rétention du dossier éléments supprimés**: nombre maximal de jours pendant lesquels les éléments peuvent rester dans le dossier éléments supprimés avant leur suppression automatique.

- **Période de rétention pour les éléments supprimés du dossier éléments supprimés**: nombre maximal de jours pendant lesquels les éléments supprimés du dossier éléments supprimés sont conservés avant leur suppression définitive.

- **Période de rétention du dossier courrier indésirable**: nombre maximal de jours pendant lesquels les éléments peuvent rester dans le dossier courrier indésirable avant d’être automatiquement supprimés.

> [!NOTE]
> Une boîte aux lettres utilisateur supprimée (récupérable) &mdash; une boîte aux lettres supprimée à l’aide du centre d’administration Microsoft 365 ou de la cmdlet Remove-Mailbox dans Exchange Online PowerShell et qui se trouve toujours dans la corbeille Azure Active Directory &mdash; est récupérable dans les 30 jours.

### <a name="retention-limits"></a>Limites de rétention

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Période de rétention du dossier Éléments supprimés|Aucune limite<sup>1</sup>|Aucune limite<sup>1</sup>|Aucune limite<sup>1</sup>|Aucune limite<sup>1</sup>|Aucune limite<sup>1</sup>|Aucune limite<sup>1</sup>|
|Période de rétention pour les éléments supprimés du dossier Éléments supprimés|14 jours<sup>1</sup>|14 jours<sup>1</sup>|14 jours<sup>1</sup>|14 jours<sup>1</sup>|14 jours<sup>1</sup>|14 jours<sup>1</sup>|
|Période de rétention du dossier Courrier indésirable|30 jours|30 jours|30 jours|30 jours|30 jours|30 jours|

> [!NOTE]
> <sup>1</sup> il s’agit de la valeur par défaut pour les organisations Microsoft 365. Les administrateurs peuvent porter cette valeur à un maximum de 30 jours pour les boîtes aux lettres de leur organisation.

### <a name="retention-limits-across-standalone-options"></a>Limites de rétention parmi les options autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Période de rétention du dossier Éléments supprimés|Aucune limite<sup>1</sup>|Aucune limite<sup>1</sup>|Aucune limite<sup>1</sup>|Aucune limite<sup>1</sup>|
|Période de rétention pour les éléments supprimés du dossier Éléments supprimés|14 jours<sup>1</sup>|14 jours<sup>2</sup>|14 jours<sup>2</sup>|14 jours<sup>2</sup>|
|Période de rétention du dossier Courrier indésirable|2 ans<sup>1</sup>|30 jours|30 jours|30 jours|

> [!NOTE]
> <sup>1</sup> Il s'agit de la limite par défaut. Les administrateurs peuvent modifier cette valeur pour leur organisation.<br/> <sup>2</sup> Ceci est la valeur par défaut pour les organisations Exchange Online. Les administrateurs peuvent porter cette valeur à un maximum de 30 jours pour les boîtes aux lettres de leur organisation.

## <a name="distribution-group-limits"></a>Limites concernant les groupes de distribution

Ces limites s'appliquent aux groupes de distribution figurant dans le carnet d'adresses partagé de votre organisation.

- **Nombre maximal de membres du groupe de distribution**: le nombre total de destinataires est déterminé après l’extension du groupe de distribution.

- **Limiter l’envoi de messages à de grands groupes de distribution**: les groupes de distribution contenant le nombre de membres spécifiés par cette limite doivent disposer des options de gestion des remises ou d’approbation des messages configurées. La gestion de remise spécifie la liste des expéditeurs autorisés à envoyer des messages au groupe de distribution. L'approbation des messages spécifie un ou plusieurs modérateurs dont la tâche est d'approuver tous les messages envoyés au groupe de distribution.

- **Taille maximale des messages pour les grands groupes de distribution**: si un message est envoyé à 5 000 ou plusieurs destinataires, la taille du message ne peut pas dépasser cette limite. Si la taille du message dépasse la limite, ce dernier n'est pas remis, et l'expéditeur reçoit une notification d'échec de remise.

### <a name="distribution-group-limits"></a>Limites concernant les groupes de distribution

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Nombre maximal de membres d’un groupe de distribution<sup>1</sup>|100 000 membres|100 000 membres|100 000 membres|100 000 membres|100 000 membres|100 000 membres|
|Limite d’envoi de messages à de grands groupes de distribution|5 000 membres ou plus|5 000 membres ou plus|5 000 membres ou plus|5 000 membres ou plus|5 000 membres ou plus|5 000 membres ou plus|
|Taille maximale de message pour les groupes de distribution contenant entre 5000 et 99 999 membres|25 Mo|25 Mo|25 Mo|25 Mo|25 Mo|25 Mo|
|Taille de message maximal pour groupes de distribution avec 100 000 membres|5 Mo|5 Mo|5 Mo|5 Mo|5 Mo|5 Mo|
|Nombre maximal de propriétaires de groupe de distribution|10 |10 |10 |10 |10 |10 |
|Nombre maximal de groupes qu’un utilisateur peut créer|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup>  Si vous utilisez Azure Active Directory DirSync, le nombre maximal de membres de groupe de distribution que vous pouvez synchroniser de votre instance Active Directory locale vers Azure Active Directory est de 15 000. Si vous utilisez Azure AD Connect, ce nombre est de 50 000. <br/> <sup>2</sup> Cette limite s’applique également aux administrateurs.

### <a name="distribution-group-limits-across-standalone-options"></a>Limites concernant les groupes de distribution parmi les options autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Nombre maximal de membres d’un groupe de distribution|100 000 membres<sup>1</sup>|100 000 membres|100 000 membres|100 000 membres|
|Limite d’envoi de messages à de grands groupes de distribution|5 000 membres ou plus<sup>1</sup>|5 000 membres ou plus|5 000 membres ou plus|5 000 membres ou plus|
|Nombre maximal de propriétaires de groupe de distribution|10 |10 |10 |10 |
|Nombre maximal de groupes qu’un utilisateur peut créer|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Ceci est la limite par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation. <br/> <sup>2</sup> Cette limite s’applique également aux administrateurs.

## <a name="journal-transport-and-inbox-rule-limits"></a>Limites concernant les règles de journal, de transport et de boîte de réception

La liste suivante inclut les limites qui s’appliquent aux règles de journal, aux règles de transport (également appelées règles à l’échelle de l’organisation) et aux limites qui s’appliquent aux règles de boîte de réception. Les règles de boîte de réception sont mises en place par des utilisateurs individuels et appliquées aux messages envoyés et reçus par la boîte aux lettres de l'utilisateur individuel.

- **Nombre maximal de règles de journal**: nombre maximal de règles de journal qui peuvent exister dans l’organisation.

- **Nombre maximal de règles de transport**: nombre maximal de règles qui peuvent exister dans l’organisation.

- **Taille maximale d’une règle de transport individuelle**: nombre maximal de caractères pouvant être utilisés dans une règle de transport unique. Les caractères sont utilisés dans les conditions, les exceptions et les actions.

- **Limite de caractères pour toutes les expressions régulières utilisées dans toutes les règles de transport**: nombre total de caractères utilisés incluant toutes les expressions régulières dans toutes les conditions de règle de transport et les exceptions dans l’organisation. Il arrive qu'un petit nombre de règles utilisent des expressions régulières longues et complexes, ou qu'un grand nombre de règles utilisent des expressions régulières simples.

- **Limites d’analyse pour le contenu des pièces jointes**: les conditions de règle de transport vous permettent d’examiner le contenu des pièces jointes, mais seuls les premiers 1 Mo du texte extrait d’une pièce jointe sont inspectés. Cette limite de 1 Mo porte sur le texte extrait de la pièce jointe, pas sur la taille du fichier en pièce jointe. Par exemple, un fichier de 1 Mo peut contenir moins de 2 Mo de texte, auquel cas l'ensemble du texte sera examiné.

- **Nombre maximal de destinataires ajoutés à un message par toutes les règles de transport**: lorsqu’un message est traité par différentes règles de transport, seul un nombre fini de destinataires peut être ajouté au message. Une fois la limite atteinte, les destinataires restants ne sont pas ajoutés au message. De plus, une règle de transport ne peut pas ajouter de groupes de distribution à un message.

- **Limite**des destinataires de transfert : nombre maximal de destinataires pouvant être configurés pour une règle de boîte de réception ou de transport avec une action de redirection. Si une règle est configurée pour rediriger un message vers un nombre de destinataires supérieur à celui défini, la règle ne s'applique pas et aucun message remplissant la condition de la règle n'est redirigé vers les destinataires répertoriés dans cette dernière.
    
- **Nombre de fois qu’un message est redirigé**: nombre de fois qu’un message est redirigé, transféré ou auquel il répond automatiquement en fonction des règles de boîte de réception. Par exemple, l'utilisateur A dispose d'une règle de boîte de réception qui redirige les messages vers l'utilisateur B, en fonction de l'expéditeur. L'utilisateur B dispose d'une règle de boîte de réception qui transfère les messages à l'utilisateur C, en fonction des mots clés figurant dans la ligne Objet. Si un message remplit les deux conditions, il est envoyé uniquement à l'utilisateur B et n'est pas transféré à l'utilisateur C parce qu'une seule redirection est autorisée. Dans ce cas, le message est supprimé sans envoyer de notification d’échec de remise (NDR) à l’utilisateur B, indiquant que le message n’a pas été remis à l’utilisateur C. Nous utilisons l’en-tête X-MS-Exchange-Inbox-Rules-Loop pour déterminer le nombre de fois qu’un message a été redirigé. Cet en-tête reste également à l’échelle de l’organisation Exchange.

- **Nombre de fois qu’un message est redirigé par les règles de transport**: nombre de fois qu’un message est redirigé en fonction des règles de transport. Par exemple, l’organisation Exchange Tailspin Toys dispose d’une règle de transport pour rediriger chaque message envoyé à l’utilisateur A vers l’utilisateur B, qui se trouve dans l’organisation Exchange contoso. Dans l’organisation Exchange Contoso, une règle de transport est mise en place pour rediriger chaque message envoyé à l’utilisateur B vers l’utilisateur C, qui se trouve dans l’organisation Exchange A. Datum Corporation. Dans ce cas, le message est supprimé et une notification d’échec de remise (NDR) avec un code d’État et un message de rejet *550 5.7.128. Gestion. RejectMessage Nombre de boucles de règles de transport dépassées et message rejeté* est envoyé à l’utilisateur a. Nous utilisons l’en-tête X-MS-Exchange-transport-Rules-Loop pour déterminer le nombre de fois qu’un message a été redirigé par des règles de transport. Cet en-tête reste également à l’échelle de l’organisation Exchange.

### <a name="journal-transport-and-inbox-rule-limits"></a>Limites concernant les règles de journal, de transport et de boîte de réception

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Nombre maximal de règles de journal|300 règles|300 règles|300 règles|300 règles|300 règles|300 règles|
|Nombre maximal de règles de transport|300 règles|300 règles|300 règles|300 règles|300 règles|300 règles|
|Taille maximale d’une règle de transport|8 Ko|8 Ko|8 Ko|8 Ko|8 Ko|8 Ko|
|Limite de caractères pour l'ensemble des expressions régulières utilisées dans toutes les règles de transport|20 Ko|20 Ko|20 Ko|20 Ko|20 Ko|20 Ko|
|Limites d’analyse pour le contenu des pièces jointes|1 Mo|1 Mo|1 Mo|1 Mo|1 Mo|1 Mo|
|Nombre maximal de destinataires ajoutés à un message par l’ensemble des règles de transport|100 destinataires|100 destinataires|100 destinataires|100 destinataires|100 destinataires|100 destinataires|
|Limite des destinataires de transfert|10 destinataires|10 destinataires|10 destinataires|10 destinataires|10 destinataires|10 destinataires|
|Nombre de fois qu’un message est redirigé|1 redirection|1 redirection|1 redirection|1 redirection|1 redirection|1 redirection|
|Nombre de fois qu’un message est redirigé par les règles de transport|1 redirection|1 redirection|1 redirection|1 redirection|1 redirection|1 redirection|
|Nombre de fois qu’un message est redirigé|1 redirection|1 redirection|1 redirection|1 redirection|1 redirection|1 redirection|
|Règle de boîte de réception|256 Ko<sup>1</sup>|256 Ko<sup>1</sup>|256 Ko<sup>1</sup>|256 Ko<sup>1</sup>|256 Ko<sup>1</sup>|256 Ko<sup>1</sup>|

> [!NOTE]
> <sup>1</sup> si une boîte aux lettres a été migrée vers Exchange Online, la limite de règle de boîte de réception peut être définie sur une valeur inférieure à la valeur exo par défaut. Si c’est le cas, la valeur de la règle de boîte de réception peut être augmentée. Pour obtenir des instructions, consultez [la rubrique modifier l’espace utilisé par les règles de boîte de réception dans Exchange Online](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-on-the-web/increase-the-space-used-by-inbox-rules). 

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Limites des règles de journal, de transport et de boîte de réception parmi les options autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Nombre maximal de règles de journal|Aucune limite|50 règles|50 règles|50 règles|
|Nombre maximal de règles de transport|Sans limite|300 règles|300 règles|300 règles|
|Taille maximale d’une règle de transport|40 Ko|8 Ko|8 Ko|8 Ko|
|Limite de caractères pour l'ensemble des expressions régulières utilisées dans toutes les règles de transport|Sans limite|20 Ko|20 Ko|20 Ko|
|Nombre maximal de destinataires ajoutés à un message par l’ensemble des règles de transport|Sans limite|100 destinataires|100 destinataires|100 destinataires|
|Limite des destinataires de transfert|Sans limite|10 destinataires|10 destinataires|10 destinataires|
|Nombre de fois qu’un message est redirigé|3 redirections|1 redirection|1 redirection|1 redirection|
|Nombre de fois qu’un message est redirigé par les règles de transport|Sans limite|1 redirection|1 redirection|1 redirection|

## <a name="moderation-limits"></a>Limites de modération

Ces limites contrôlent les paramètres de modération utilisés pour l'approbation de messages appliquée aux groupes de distribution et aux règles de transport.

- **Taille maximale de la boîte aux lettres d’arbitrage**: si la boîte aux lettres d’arbitrage dépasse cette limite, les messages qui requièrent une modération sont renvoyés à l’expéditeur dans une notification d’échec de remise.

- **Nombre maximal de modérateurs**: nombre maximal de modérateurs que vous pouvez affecter à un seul groupe de distribution modéré ou pouvant être ajouté à un message à l’aide d’une règle de transport unique. Notez qu'en tant que modérateur, vous ne pouvez pas spécifier de groupe de distribution.

- **Expiration des messages en attente de modération**: par défaut, un message en attente de modération expire au bout de deux jours. Toutefois, le traitement des messages modérés ayant expiré s'effectue tous les sept jours. Cela signifie qu'un message modéré peut expirer à tout moment entre deux et neuf jours.

- **Taux maximal de messages de notification de modération expirés**: cette limite définit le nombre maximal de messages de notification pour les messages modérés expirés sur une période d’une heure. Cette limite est définie pour chaque base de données de boîtes aux lettres du centre de données.

Pendant les périodes d'utilisation intensive, certains expéditeurs risquent de ne pas recevoir de messages de notification pour les messages modérés ayant expiré. Toutefois, ces notifications sont toujours détectables à l'aide de rapports de remise.

### <a name="moderation-limits"></a>Limites de modération

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Taille maximale de la boîte aux lettres d’arbitrage|10 Go|10 Go|10 Go|10 Go|10 Go|10 Go|
|Nombre maximal de modérateurs|10 modérateurs|10 modérateurs|10 modérateurs|10 modérateurs|10 modérateurs|10 modérateurs|
|Expiration des messages en attente de modération|2 jours|2 jours|2 jours|2 jours|2 jours|2 jours|
|Débit maximal de messages de notification d’expiration du délai de modération|300 notifications d’expiration par heure|300 notifications d'expiration par heure|300 notifications d'expiration par heure|300 notifications d'expiration par heure|300 notifications d'expiration par heure|300 notifications d'expiration par heure|

### <a name="moderation-limits-across-standalone-options"></a>Limites de modération parmi les options autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Taille maximale de la boîte aux lettres d’arbitrage|Aucune limite<sup>1</sup>|10 Go|10 Go|10 Go|
|Nombre maximal de modérateurs|Sans limite|10 modérateurs|10 modérateurs|10 modérateurs|
|Expiration des messages en attente de modération|5 jours<sup>1</sup>|2 jours|2 jours|2 jours|
|Débit maximal de messages de notification d’expiration du délai de modération|300 notifications d’expiration par heure|300 notifications d'expiration par heure|300 notifications d'expiration par heure|300 notifications d'expiration par heure|

> [!NOTE]
> <sup>1</sup> Ceci est la limite par défaut pour les organisations Exchange Server 2013. Les administrateurs peuvent modifier cette valeur pour leur organisation.

## <a name="exchange-activesync-limits"></a>Limites d'ActiveSync Exchange

Les limites suivantes s'appliquent à Microsoft Exchange ActiveSync, un protocole client qui synchronise les données de boîtes aux lettres entre les appareils mobiles et Exchange.

- **Limite de l’appareil Exchange ActiveSync**: nombre maximal d’appareils Exchange ActiveSync par boîte aux lettres.

- **Limite de suppression de l’appareil Exchange ActiveSync**: nombre maximal d’appareils Exchange ActiveSync qu’un administrateur Exchange peut supprimer en un mois.

### <a name="exchange-activesync-limits"></a>Limites d'ActiveSync Exchange

| Fonctionnalité | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Entreprise E1 | Office 365 Entreprise E3 | Office 365 Entreprise E5 | Office 365 Entreprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite de l'appareil Exchange ActiveSync|100|100|100|100|100|100|
|Limite de suppression de l'appareil Exchange ActiveSync|vingtaine|vingtaine|vingtaine|vingtaine|vingtaine|vingtaine|

### <a name="exchange-activesync-limits-across-standalone-options"></a>Limites d'ActiveSync Exchange dans les options autonomes

| Fonctionnalité | Exchange Server 2013 | Exchange Online (plan 1) | Exchange Online (plan 2) | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Limite de l'appareil Exchange ActiveSync|100|100|100|100|
|Limite de suppression de l'appareil Exchange ActiveSync|vingtaine|vingtaine|vingtaine|vingtaine|
