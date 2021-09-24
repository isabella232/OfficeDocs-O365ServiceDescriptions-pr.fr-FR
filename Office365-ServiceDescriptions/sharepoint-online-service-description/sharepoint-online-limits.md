---
title: Limites de SharePoint
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Découvrez les limites SharePoint pour les plans Microsoft 365 et autonomes.
ms.openlocfilehash: 21034e34d483e63a474533e4c02444749e736936
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59669543"
---
# <a name="sharepoint-limits"></a>Limites de SharePoint

Découvrez les limites de service dans SharePoint pour Microsoft 365, consultez Limites de SharePoint.
  
## <a name="limits-by-plan"></a>Limites par offre 

| Fonctionnalité | Office 365 Business Essentials, Business Standard ou Business Premium | Microsoft 365 E3 ou E5, Office 365 E1, E3 ou E5, ou Plan 1 ou 2 SharePoint | Microsoft 365 F1 ou F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Stockage total par organisation<sup>1, 2, 6</sup> <br/> |1 To plus 10 Go par licence achetée<sup>3</sup>  <br/> |1 To plus 10 Go par licence achetée<sup>3</sup> <br/> |1 To<sup>3</sup> <br/> |
|Stockage maximal par site (collection de sites)<sup>4</sup><br/> |25 To <br/> |25 To <br/> |25 To<sup>5</sup> <br/> |
|Sites (collections de sites) par organisation  <br/> |2 millions<sup>6</sup> <br/> |2 millions<sup>6</sup> <br/> |2 millions<br/> |
|Nombre d'utilisateurs.  <br/> |Jusqu'à 300  <br/> |1 - 500 000<sup>7</sup> <br/> |1 - 500 000<sup>7</sup> <br/> |
   
<sup>1</sup> [Découvrez comment trouver le stockage total et disponible pour votre organisation](/sharepoint/manage-site-collection-storage-limits). Vous pouvez acheter un volume illimité de stockage SharePoint supplémentaire. Consultez [Ajouter de l’espace de stockage pour votre abonnement](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Nous vous recommandons de surveiller la Corbeille et de la vider régulièrement. L'espace de stockage qu'elle utilise fait partie de la limite totale de stockage de l'organisation. 
<br/> <sup>3</sup> Si vous disposez d’un abonnement Microsoft 365 et d’un module complémentaire Stockage de fichiers supplémentaire Office 365, les quantités de stockage sont ajoutées. 
<br/> <sup>4</sup> Il s’agit de la limite de *stockage* pour un site unique (anciennement « collection de sites »), et non la quantité de stockage *fournie* pour chaque site. Cette limite s’applique à tous les types de sites, y compris les sites d’équipe connectés à un groupe Office 365 et OneDrive. Les administrateurs SharePoint peuvent [définir manuellement des limites de stockage inférieures](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5 travailleurs</sup> de l’emploi ne peuvent pas administrer SharePoint sites. 
<br/> <sup>6</sup> Sans inclure le OneDrive créé pour chaque utilisateur sous licence. 
<br/> <sup>7</sup> Si vous avez plus de 500 000 utilisateurs, contactez un représentant Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limites de service pour tous les plans

### <a name="items-in-lists-and-libraries"></a>Éléments dans les listes et les bibliothèques

Une liste peut comporter jusqu'à 30 millions d’éléments tandis qu’une bibliothèque peut inclure jusqu'à 30 millions de fichiers et dossiers. Lorsqu’une liste, une bibliothèque ou un dossier contient plus de 100 000 éléments, vous ne pouvez pas interrompre l’héritage des autorisations sur la liste, la bibliothèque ou le dossier. Vous ne pouvez pas non plus ré-hériter des autorisations sur celui-ci. Toutefois, vous pouvez toujours interrompre l’héritage sur les éléments individuels de cette liste, bibliothèque ou dossier, jusqu’au nombre maximal d’autorisations uniques dans la liste ou la bibliothèque (voir la section suivante). Pour en savoir plus sur les autres restrictions relatives à l’affichage des listes de grande taille, voir [Gérer les listes et bibliothèques de grande taille dans Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Étendues de sécurité uniques par liste ou bibliothèque

Pour les listes volumineuses, la conception doit avoir le moins d’autorisations uniques possible et rester en dessous de 5 000 au total.

### <a name="file-size-and-file-path-length"></a>Taille du fichier et longueur du chemin d’accès au fichier

- **250 Go : Limite de chargement de fichiers.** S’applique à chaque fichier individuel chargé dans l’onglet Fichiers Microsoft Teams, les bibliothèques de documents SharePoint, les dossiers OneDrive et les conversations Yammer.

- **250 Mo : Fichier joint à un élément de liste.** S’applique aux Listes Microsoft et SharePoint, toutes deux basées sur la même plateforme de listes.

Pour en savoir plus sur les restrictions et les limites lors de l’utilisation de la nouvelle application de synchronisation OneDrive (OneDrive.exe), consultez [Noms de fichiers et types de fichiers non valides](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Déplacement et copie d’un site à l’autre

La copie/déplacement de plusieurs fichiers en une seule opération répond à trois exigences :

- Taille totale du fichier maximale de 100 Go
- Pas plus de 30 000 fichiers
- Chaque fichier doit être inférieur à 15 Go

### <a name="sync"></a>Synchronisation

Pour optimiser les performances, nous vous recommandons de stocker moins de 300 000 fichiers dans une même bibliothèque de site d’équipe ou OneDrive. Bien que SharePoint Online puisse stocker 30 millions de documents par bibliothèque, pour optimiser les performances nous vous recommandons de ne pas synchroniser plus de 300 000 fichiers répartis dans l’ensemble des bibliothèques de documents. En outre, les mêmes problèmes de performances peuvent se produire si vous avez 300 000 éléments ou plus dans toutes les bibliothèques que vous synchronisez et ce, même si vous ne synchronisez pas tous les éléments de ces bibliothèques. Si vous utilisez l’ancien client de synchronisation OneDrive Entreprise (Groove.exe), la limite de synchronisation par bibliothèque est de 20 000 éléments (y compris, 5 000 éléments par site d'équipe).

### <a name="versions"></a>Versions

50 000 versions majeures et 511 versions mineures.

### <a name="sharepoint-groups"></a>Groupes SharePoint

Un utilisateur peut appartenir à 5 000 groupes par site (collection de sites), et chaque groupe peut comporter jusqu'à 5 000 utilisateurs. Vous pouvez disposer d’un maximum de 10 000 groupes par site (collection de sites).

> [!NOTE]
> Pour le limites de groupe Azure AD, consultez [Limites de service et restrictions Azure AD](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) telles limites peuvent avoir un impact sur la gestion de l’appartenance aux sites de groupes publics et privés.

### <a name="managed-metadata"></a>Métadonnées gérées

1 million de termes au total, avec un total de 2 millions d'étiquettes de termes et 1 million de propriétés de termes (ces limites concernent les termes globaux et ceux du site combinés). 1 000 ensembles de termes globaux et 1 000 groupes globaux.

### <a name="overall-site-metadata"></a>Métadonnées globales du site

1 000 Go par site (les métadonnées atteignent rarement cette taille).

### <a name="subsites"></a>Sous-sites

2 000 par sites (collection de sites) Nous vous recommandons de créer des sites et de les organiser en hubs au lieu de créer des sous-sites. Si vous utilisez des sous-sites, nous vous recommandons de limiter leur nombre (en particulier sur les sites fortement utilisés).

> [!NOTE]
> Votre organisation est limitée à 2 000 sites hub. Vous n’avez peut-être pas besoin d’un site hub pour chaque fonction, et il est important d’effectuer une planification avant de créer des hubs. Pour plus d’informations, consultez [Planification de vos sites Hub SharePoint](/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>Applications hébergées par SharePoint

20 000 instances par organisation.

### <a name="users"></a>Utilisateurs

2 millions par collection de sites.

> [!NOTE]
> Il n’existe aucune limite distincte au nombre d’invités que vous pouvez inviter sur des sites SharePoint. Pour plus d’informations sur le partage externe, consultez [Vue d’ensemble du partage externe](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Voir aussi

[Limitations de la recherche pour SharePoint](/sharepoint/search-limits)