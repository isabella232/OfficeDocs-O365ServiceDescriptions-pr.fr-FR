---
title: Limites de SharePoint
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Découvrez les limites de SharePoint pour Microsoft 365 et les plans autonomes.
ms.openlocfilehash: 08d0f2f69e1f1b096b2dcd2f66cf083fa239a52e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653406"
---
# <a name="sharepoint-limits"></a>Limites de SharePoint

Découvrez les limites de service dans SharePoint pour Microsoft 365.
  
## <a name="limits-by-plan"></a>Limites par plan 

| Fonctionnalité | Microsoft 365 Business Basic, Business Standard ou Business Premium | Microsoft 365 E3 ou E5, Office 365 E1, E3 ou E5, ou SharePoint Plan 1 ou 2 | Microsoft 365 F1 ou F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Stockage total par organisation<sup>1, 2, 6</sup> <br/> |1 To plus 10 Go par licence achetée<sup>3</sup>  <br/> |1 To plus 10 Go par licence achetée<sup>3</sup> <br/> |1 To<sup>3</sup> <br/> |
|Stockage maximum par site (collection de sites)<sup>4</sup><br/> |25 To <br/> |25 To <br/> |25 To<sup>5</sup> <br/> |
|Sites (collections de sites) par organisation  <br/> |2 millions<sup>6</sup> <br/> |2 millions<sup>6</sup> <br/> |2 millions<br/> |
|Nombre d'utilisateurs.  <br/> |Jusqu'à 300  <br/> |1 - 500 000<sup>7</sup> <br/> |1 - 500 000<sup>7</sup> <br/> |
   
<sup>1</sup> [Découvrez comment trouver le stockage total et disponible pour votre organisation.](/sharepoint/manage-site-collection-storage-limits) Vous pouvez acheter une quantité illimitée de stockage SharePoint supplémentaire. Voir [Ajouter de l’espace de stockage pour votre abonnement.](/office365/admin/subscriptions-and-billing/add-storage-space) 
<br/><sup>2</sup> Nous vous recommandons de surveiller la Corbeille et de la vider régulièrement. L’espace de stockage qu’il utilise fait partie de la limite de stockage totale de l’organisation. 
<br/> <sup>3</sup> Si vous avez un abonnement Microsoft 365 et un module supplémentaire de stockage de fichiers Office 365, les quantités de stockage sont ajoutées. 
<br/> <sup>4 Il</sup> s’agit de la limite de stockage pour un site unique (précédemment appelé « collection de sites ») et non de la quantité de stockage *fournie* pour chaque site.  Cette limite s’applique à tous les types de sites, y compris les sites d’équipe connectés à un groupe Office 365 et OneDrive. Les administrateurs SharePoint peuvent [définir manuellement des limites de stockage inférieures.](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits) 
<br/> <sup>5</sup> Les employés de première ligne ne peuvent pas administrer les sites SharePoint. 
<br/> <sup>6 Sans</sup> inclure le OneDrive créé pour chaque utilisateur sous licence. 
<br/> <sup>7</sup> Si vous avez plus de 500 000 utilisateurs, contactez un représentant Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limites de service pour tous les plans

### <a name="items-in-lists-and-libraries"></a>Éléments dans les listes et les bibliothèques

Une liste peut avoir jusqu’à 30 millions d’éléments et une bibliothèque peut avoir jusqu’à 30 millions de fichiers et de dossiers. Lorsqu’une liste, une bibliothèque ou un dossier contient plus de 100 000 éléments, vous ne pouvez pas rompre l’héritage des autorisations sur la liste, la bibliothèque ou le dossier. Vous ne pouvez pas non plus ré-hériter des autorisations qui lui sont accordées. Toutefois, vous pouvez toujours rompre l’héritage sur les éléments individuels de cette liste, bibliothèque ou dossier, jusqu’au nombre maximal d’autorisations uniques dans la liste ou la bibliothèque (voir la section suivante). Pour en savoir plus sur les autres restrictions d’affichage des grandes listes, voir Gérer les grandes listes et bibliothèques [dans Office 365.](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)

### <a name="unique-security-scopes-per-list-or-library"></a>Étendues de sécurité uniques par liste ou bibliothèque

Pour les grandes listes, concevez pour avoir le moins d’autorisations uniques possible et rester en dessous de 5 000 au total.

### <a name="file-size-and-file-path-length"></a>Taille du fichier et longueur du chemin d’accès au fichier

250 Go. Pour en savoir plus sur les restrictions et les limites lors de l’utilisation de la nouvelle application de synchronisation OneDrive (OneDrive.exe), voir Noms de fichiers et types de fichiers [non valides.](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)

### <a name="moving-and-copying-across-sites"></a>Déplacement et copie d’un site à l’autre

La copie/déplacement de plusieurs fichiers en une seule opération présente trois exigences :

- Taille totale de fichier de 100 Go au plus
- Pas plus de 30 000 fichiers
- Chaque fichier doit être inférieur à 15 Go

### <a name="sync"></a>Synchronisation

Pour optimiser les performances, nous vous recommandons de ne pas stocker plus de 300 000 fichiers dans une seule bibliothèque oneDrive ou de site d’équipe. Bien que SharePoint Online puisse stocker 30 millions de documents par bibliothèque, pour des performances optimales, nous vous recommandons de ne pas synchroniser plus de 300 000 fichiers dans toutes les bibliothèques de documents. En outre, les mêmes problèmes de performances peuvent se produire si vous avez 300 000 éléments ou plus dans toutes les bibliothèques que vous synchronisez, même si vous ne synchronisez pas tous les éléments de ces bibliothèques. Si vous utilisez le client de synchronisation OneDrive Entreprise précédent (Groove.exe), la limite de synchronisation par bibliothèque est de 20 000 éléments (y compris 5 000 éléments par site d’équipe).

### <a name="versions"></a>Versions

50 000 versions principales et 511 versions mineures.

### <a name="sharepoint-groups"></a>Groupes SharePoint

Un utilisateur peut appartenir à 5 000 groupes par site (collection de sites) et chaque groupe peut avoir jusqu’à 5 000 utilisateurs. Vous pouvez avoir jusqu’à 10 000 groupes par site (collection de sites).

> [!NOTE]
> Pour les limites des groupes Azure AD, consultez les limites et restrictions de [service Azure AD,](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) car ces limites peuvent avoir un impact sur la gestion des appartenances aux sites de groupe publics et privés.

### <a name="managed-metadata"></a>Métadonnées gérées

200 000 termes dans le magasin de termes, 1 000 ensembles de termes globaux, 1 000 groupes.

### <a name="overall-site-metadata"></a>Métadonnées globales du site

1 000 Go par site (les métadonnées atteignent rarement cette taille).

### <a name="subsites"></a>Sous-sites

2 000 par site (collection de sites). Nous vous recommandons de créer des sites et de les organiser en hubs au lieu de créer des sous-sites. Si vous utilisez des sous-sites, nous vous recommandons de limiter leur nombre (en particulier sur les sites fortement trafficked).

> [!NOTE]
> Votre organisation est limitée à 2 000 sites hub. Vous n’avez peut-être pas besoin d’un site hub pour chaque fonction et il est important d’y faire une planification avant de créer des hubs. Pour plus d’informations, consultez [La planification de vos sites hub SharePoint.](/sharepoint/planning-hub-sites)

### <a name="sharepoint-hosted-applications"></a>Applications hébergées par SharePoint

20 000 instances par organisation.

### <a name="users"></a>Utilisateurs

2 millions par collection de sites.

> [!NOTE]
> Il n’existe aucune limite distincte au nombre d’invités que vous pouvez inviter sur des sites SharePoint. Pour plus d’informations sur le partage externe, voir [Vue d’ensemble du partage externe.](/sharepoint/external-sharing-overview)

## <a name="see-also"></a>Voir aussi

[Limites de recherche pour SharePoint](/sharepoint/search-limits)