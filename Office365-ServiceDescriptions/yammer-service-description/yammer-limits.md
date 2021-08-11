---
title: Limites dans Yammer
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- yammer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Découvrez les limites de service dans Yammer pour Microsoft 365.
ms.openlocfilehash: 6ce13069239cc0b7b39adf2e9850b0cd46a12910f9dca6b61aea2600d7591402
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54702263"
---
# <a name="limits-in-yammer"></a>Limites dans Yammer

Découvrez les limites de service dans Yammer pour Microsoft 365.

## <a name="network-limits"></a>Limites du réseau

| Fonctionnalité | Détails |
|---------|---------|
| Mode natif | [Le mode natif](/yammer/configure-your-yammer-network/overview-native-mode) est recommandé pour une meilleure prise en charge à long terme. Yammer réseaux Microsoft 365 mode natif ont des fonctionnalités différentes des réseaux Yammer hérités. |
| Mise à jour en bloc pour les administrateurs réseau | Les mises à jour en bloc des utilisateurs sont pris en charge pour les réseaux en mode non natif de 2 000 utilisateurs ou moins. |
| Réseaux locaux | Les réseaux d’accueil ne peuvent pas être supprimés et recréés. |

## <a name="file-limits"></a>Limites des fichiers

| Fonctionnalité | Détails |
|---------|---------|
| Taille maximale des fichiers et stockage | La migration vers Microsoft 365 mode natif pour Yammer est recommandée pour vous assurer que tous les fichiers sont stockés dans SharePoint Online. <br/>Pour Yammer fichiers stockés dans SharePoint : <ul><li>La taille maximale d’une seule pièce jointe est de 15 gigaoctets (Go).</li><li>Il n’existe aucune limitation de dimension pour les images, mais les paramètres SharePoint taille maximale maximale de votre organisation s’appliquent.</li><li>Tout type de fichier peut être ajouté, mais l’aperçu et la modification sont limités à certains types de fichiers.</li> </ul><br/>[SharePoint limites s’appliquent](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits) Microsoft 365 les communautés [connectées](/yammer/manage-yammer-groups/yammer-and-office-365-groups) Yammer. <br/>Pour les fichiers stockés dans Yammer stockage de fichiers : <br/><ul><li>La taille maximale d’une seule pièce jointe est de 5 gigaoctets (Go) pour les réseaux Yammer Entreprise et de 100 mégaoctets (Mo) pour les Yammer de base.</li><li>Les dimensions maximales sont de 7 680 pixels de large et de 4 320 pixels de hauteur, et la taille maximale de l’image est de 10 mégaoctets (Mo).</li></ul> <br/>Pour plus d’informations sur l’utilisation des images, notamment sur les modèles et les dimensions des photos de couverture, [voir Yammer Adoption Resources](https://adoption.microsoft.com/yammer/). |
| Nombre de pièces jointes par billet | Chaque billet peut avoir un maximum de 100 fichiers. |
| Formats vidéo pris en charge | Les types de vidéo suivants sont pris en charge pour la lecture en ligne : .wmv, .avi, .mpeg, .3gp, .flv, .mov, .mp4, .mpg, .premier, .mkv, .ogv et .ogg. <br/>Yammer utilise Azure Media Services pour afficher des vidéos téléchargées dans Yammer. |
| Lecture de vidéos en ligne | Microsoft Stream, SharePoint Online, YouTube et Vimeo sont pris en charge pour la lecture en ligne. |
| Accès invité | Microsoft 365 Le mode natif pour Yammer est requis pour la prise en charge complète des invités. <br/>Les invités au niveau du réseau hérités peuvent être en situation de problèmes d’accès aux fichiers. |
| Aperçus de liens (objets Open Graph) | Les liens vers des systèmes internes qui ne peuvent pas être résolus publiquement ou nécessitant une authentification n’afficheront pas d’aperçus valides, car les métadonnées ne peuvent pas être extraites. |

## <a name="yammer-live-event-limits"></a>Yammer limites des événements en direct

| Fonctionnalité | Détails |
|---------|---------|
| Nombre de visionneuses d’événements en direct | Actuellement, la limite est de 10 000 participants. Pour les événements de plus grande taille, travaillez dans le cadre du programme [d’assistance aux événements en direct.](https://resources.techcommunity.microsoft.com/live-events/assistance/) |
| Autorisations de création d’événements en direct | L’autorisation de créer des événements en direct dans Stream est requise. <br/>Community administrateurs de Yammer peuvent créer ou planifier des événements en direct. |
| Accès invité | Les membres de votre réseau canonique peuvent créer ou participer à des événements en direct dans Yammer. |
| Sous-titre fermé | Les légendes fermées ne sont pas disponibles pour les événements en Yammer. Une prochaine mise à jour ajoutera la prise en charge des légendes fermées. |
| Durée de l’événement | 4 heures |
| Événements en direct simultanés en cours d Microsoft 365 ou Office 365 organisation | 50 événements par client |
| Limite des présentateurs ? | 100 présentateurs |

Pour plus d’informations sur les Microsoft Teams et les réunions en direct, voir [Teams Live Events](/microsoftteams/limits-specifications-teams#teams-live-events).

## <a name="yammer-community-limits"></a>Yammer limites de la communauté

| Fonctionnalité | Détails |
|---------|---------|
| Nombre de membres dans une communauté | Varie selon que la communauté est connectée à [un groupe Microsoft 365,](/yammer/manage-yammer-groups/yammer-and-office-365-groups)est une communauté dynamique [ou](/yammer/manage-yammer-groups/create-a-dynamic-group)la communauté Toute [l’entreprise.](/yammer/manage-yammer-groups/yammer-all-company-yammer-community) <br/>Limite d’appartenance à la communauté dynamique : 500 000 |
| Nombre de communautés dont vous pouvez être membre | 7,000 |
| Nombre de mises à jour via l’importation du carnet d’adresses pour ajouter plusieurs utilisateurs à la fois | 200 membres de la communauté par chargement par lot. |
| Limite des communautés dynamiques | Sans limite |
| Nombre d’administrateurs par communauté | En mode natif, les administrateurs peuvent définir un minimum. Les réseaux en mode non natif ont une limite de 100 administrateurs par communauté. |
| Nombre d’administrateurs réseau | Varie en fonction de la configuration du mode natif. Aucune limite d’administrateurs réseau. |
| Communautés connectées et Azure AD Sync | La latence avec synchronisation peut se produire avec une appartenance à la communauté de plus de 100 000. |
| Membres de l’ensemble de l’entreprise | Inclut tous les utilisateurs du client. |
| Nombre de communautés officielles | Sans limite |
| Nombre de communautés favorites | 10  |
| Community nombre limite de caractères de nom | Dépend de la convention d’attribution de noms du réseau. <br/>255 caractères maximum, préfixe compris. |
| Community de description maximale | 150 caractères |
| Community longueur des informations | Aucune limite de caractères (jusqu’à 1 Go) |
| Limite des ressources épinglées | Sans limite |
| Limite des communautés associées | Aucune limite pour les communautés normales, mais les meilleures pratiques sont 3 à 5 communautés associées. <br/>Les communautés associées ne sont pas disponibles pour toutes les entreprises. |
| Limite sur les membres en attente pour les communautés privées | Aucune limite. |
| Limites de la gestion de la communauté en mode natif | Les groupes connectés doivent être gérés à l’aide d’outils conçus pour mettre à jour Microsoft 365 groupes, notamment le portail d’administration Microsoft 365, le portail Azure AD et le module Azure AD PowerShell. |
| Publier par courrier électronique | Sans limite |

## <a name="yammer-messaging-limitations"></a>Yammer limitations de messagerie

| Fonctionnalité | Détails |
|---------|---------|
| Limite de caractères par message | 10 000 caractères maximum |
| Suppression de conversations | La suppression d’un thread entier nécessite la suppression de tous les messages. La suppression du démarrage de la conversation fait la promotion de la première réponse pour qu’elle devienne le thread starter. <br/>Les administrateurs réseau peuvent supprimer des messages d’un thread de conversation si [le mode contenu](/yammer/manage-security-and-compliance/monitor-private-content) privé est activé. <br/>Community administrateurs peuvent supprimer des messages dans la communauté qu’ils administrent. <br/>L’auteur d’origine peut uniquement supprimer ses propres billets. |
| Limite de message par thread de conversation | Une conversation peut avoir jusqu’à 10 000 billets. |
| Aperçus de liens (métadonnées Open Graph) |<ul><li>Les aperçus du contenu de lien peuvent uniquement être générés pour le contenu public et certaines ressources Microsoft 365 pris en charge.</li><li>La génération d’aperçu dépend de la réussite de l’extraction des métadonnées au moment de la publication, ce qui peut varier en fonction de la disponibilité du site auquel il est lié.</li><li>Les liens vers les systèmes à l’intérieur du pare-feu de l’organisation ou nécessitant une authentification ne sont pas pris en charge. </li><li>Les métadonnées d’aperçu de lien peuvent ne pas être mises à jour après la première utilisation du lien dans le réseau.</li></ul> |
| Mode de contenu privé | Les administrateurs vérifiés ne peuvent pas accéder au contenu privé par défaut. Le mode de contenu privé doit être activé pour accéder aux messages privés et aux communautés privées. |
| Réponses imbrmbrées et threads hérités | Les threads hérités permettent la création de nouvelles réponses imbrmbrées. Les messages « en réponse à » plus anciens restent pour l’instant en tant que commentaires de niveau supérieur. |

## <a name="external-network-limits"></a>Limites du réseau externe

| Fonctionnalité | Détails |
|---------|---------|
| External Networks | Limite de 5 réseaux externes qu’un administrateur peut créer si ces 5 réseaux externes ont un seul membre (généralement, ce membre est le créateur du réseau). <br/> S’il y a au moins un autre utilisateur dans un réseau externe, cela ne compte pas dans cette limite. |
| Fichiers | Les fichiers sont stockés dans Yammer stockage et ne sont pas accessibles via SharePoint. |
| Communautés | Les communautés ne sont pas connectées Microsoft 365 groupes. |
| Mode natif | [Les fonctionnalités et restrictions](/yammer/configure-your-yammer-network/overview-native-mode) du mode natif ne s’appliquent pas aux réseaux externes. |