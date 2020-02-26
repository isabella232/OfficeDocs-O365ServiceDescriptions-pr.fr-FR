---
title: Limites de SharePoint
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Découvrez les limites de SharePoint pour Office 365 et les plans autonomes.
ms.openlocfilehash: 03cf3a792bb88d1a6c6d6048752fe2caaf695f35
ms.sourcegitcommit: 06d43eca33da7d747494beaa9847e98b99367b0d
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/26/2020
ms.locfileid: "42279867"
---
# <a name="sharepoint-limits"></a>Limites de SharePoint

Découvrez les limites de service dans SharePoint pour Microsoft 365.
  
## <a name="limits-by-plan"></a>Limites par plan 

|||||
|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials ou Business Premium** <br/> |**Office 365 entreprise E1, E3 ou E5, ou SharePoint plan 1 ou 2** <br/> | **Office 365 Entreprise F1** <br/> |
|Stockage total par organisation<sup>1, 2, 6</sup> <br/> |1 to plus 10 Go par licence achetée  <br/> |1 to plus 10 Go par licence achetée<sup>3</sup> <br/> |1 to<sup>3</sup> <br/> |
|Stockage maximal par site (collection de sites)<sup>4</sup><br/> |25 TO <br/> |25 TO <br/> |25 to<sup>5</sup> <br/> |
|Sites (collections de sites) par organisation  <br/> |2 millions<sup>6</sup> <br/> |2 millions<sup>6</sup> <br/> |2 millions<br/> |
|Nombre d'utilisateurs.  <br/> |Jusqu'à 300  <br/> |1 - 500 000<sup>7</sup> <br/> |1 - 500 000<sup>7</sup> <br/> |
   
<sup>1</sup> [Découvrez comment trouver le total et la disponibilité de stockage pour votre organisation](/sharepoint/manage-site-collection-storage-limits). Vous pouvez acheter une quantité illimitée de stockage SharePoint supplémentaire. Consultez la rubrique [Modifier l'espace de stockage pour votre abonnement](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Nous vous recommandons de surveiller la Corbeille et de la vider régulièrement. L’espace de stockage qu’il utilise fait partie de la limite de stockage totale de l’organisation. 
<br/> <sup>3</sup> si vous disposez d’un abonnement Office 365 et d’un complément de stockage de fichiers supplémentaire Office 365, les volumes de stockage sont ajoutés. 
<br/> <sup>4</sup> il s’agit de la *limite* de stockage pour un seul site (précédemment appelée « collection de sites »), et non de la quantité de stockage *fournie* pour chaque site. Cette limite s’applique à tous les types de sites, y compris les sites d’équipe connectés à un groupe Office 365 et OneDrive. Les administrateurs SharePoint peuvent [définir manuellement des limites de stockage inférieures](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> les employés terrain ne peuvent pas administrer les sites SharePoint. 
<br/> <sup>6</sup> n’inclut pas le OneDrive créé pour chaque utilisateur sous licence. 
<br/> <sup>7</sup> Si vous avez plus de 500 000 utilisateurs, contactez un représentant Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limites de service pour tous les plans

### <a name="items-in-lists-and-libraries"></a>Éléments dans des listes et des bibliothèques

Une liste peut comporter jusqu’à 30 millions éléments et une bibliothèque peut avoir jusqu’à 30 millions fichiers et dossiers. Lorsqu’une liste, une bibliothèque ou un dossier contient plus de 100 000 éléments, vous ne pouvez pas annuler l’héritage des autorisations sur la liste, la bibliothèque ou le dossier. Vous ne pouvez pas non plus hériter des autorisations sur ce dernier. Toutefois, vous pouvez toujours bloquer l’héritage sur les éléments individuels de cette liste, bibliothèque ou dossier, jusqu’au nombre maximal d’autorisations uniques dans la liste ou la bibliothèque (voir la section suivante). Pour en savoir plus sur les autres restrictions relatives à l’affichage des grandes listes, voir [gérer les grandes listes et les bibliothèques dans Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). 

> [!NOTE]
> Il n’y a pas de limite au nombre de bibliothèques de documents que vous pouvez avoir sur un site.

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>Autorisations uniques pour les éléments d’une liste ou d’une bibliothèque

La limite prise en charge est de 50 000, mais la limite générale recommandée est de 5 000. Les modifications apportées à plus de 5 000 éléments uniques à la fois sont plus longues. Pour les grandes listes, la conception a le moins d’autorisations uniques possible.

### <a name="file-size-and-file-path-length"></a>Taille du fichier et longueur du chemin d’accès du fichier

15 GO. La taille maximale des fichiers joints aux éléments de liste est de 250 Mo. Pour en savoir plus sur les restrictions et les limites liées à l’utilisation de la nouvelle application de synchronisation OneDrive (OneDrive. exe), voir [noms de fichiers et types de fichiers non valides](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Transfert et copie sur plusieurs sites

100 Go par opération. Le navigateur Web doit rester ouvert.

### <a name="sync"></a>Synchronisation

**Nouvelle application de synchronisation OneDrive** : pour des performances optimales, nous vous recommandons de ne pas stocker plus de 300 000 fichiers dans toutes les bibliothèques de documents synchronisées, même si vous utilisez des fichiers à la demande ou si vous choisissez uniquement certains dossiers dans les bibliothèques à synchroniser.

**Ancienne application de synchronisation OneDrive entreprise (Groove. exe)** : vous pouvez synchroniser jusqu’à 20 000 éléments au total dans toutes les bibliothèques synchronisées. Cela inclut les bibliothèques OneDrive, les bibliothèques de sites d’équipe, ou les deux. Indépendamment de la limite de synchronisation globale, le nombre d’éléments pouvant être synchronisés pour chaque type de bibliothèque est limité :

   - Vous pouvez synchroniser jusqu’à 20 000 éléments dans une bibliothèque OneDrive. Cela inclut les dossiers et les fichiers. 
   - Vous pouvez synchroniser jusqu’à 5 000 éléments dans une bibliothèque SharePoint. Cela inclut les dossiers et les fichiers. Il s’agit des bibliothèques que vous trouvez sur différents sites SharePoint, telles que les sites d’équipe et les sites communautaires, les bibliothèques créées par d’autres personnes ou celles que vous avez créées à partir de votre page de sites. Vous pouvez synchroniser plusieurs bibliothèques SharePoint. Tous les sites d’équipe que vous synchronisez sont également décomptés par rapport à la limite globale de 20 000 des éléments dans toutes les bibliothèques synchronisées.

> [!NOTE]
> Si les utilisateurs doivent synchroniser des fichiers dans des bibliothèques de documents qui contiennent des centaines de milliers de fichiers, vous pouvez « masquer » les dossiers de l’application de synchronisation en définissant le niveau d’autorisation des dossiers sur « lecture restreinte ». 

### <a name="versions"></a>Versions

50 000 versions principales et 511 versions mineures.

### <a name="sharepoint-groups"></a>Groupes SharePoint

Un utilisateur peut appartenir à des groupes 5 000 et chaque groupe peut avoir jusqu’à 5 000 utilisateurs. Vous pouvez avoir jusqu’à 10 000 groupes par site (collection de sites).

> [!NOTE]
> Pour les limites du groupe Azure AD, voir [limites et restrictions des services Azure ad](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) dans la mesure où ces limites peuvent avoir un impact sur la gestion de l’appartenance aux sites des groupes publics et privés. 

### <a name="managed-metadata"></a>Métadonnées gérées

200 000 termes dans le magasin de termes, 1 000 ensembles de termes globaux, 1 000 groupes.

### <a name="subsites"></a>Sous-sites 

2 000 par site (collection de sites). Nous vous recommandons de créer des sites et de les organiser en hubs au lieu de créer des sous-sites. Si vous utilisez des sous-sites, nous vous recommandons de limiter leur nombre (en particulier sur les sites très un).

### <a name="sharepoint-hosted-applications"></a>Applications hébergées SharePoint

20 000 instances par organisation.

### <a name="people-editing-a-document-at-the-same-time"></a>Personnes modifiant un document en même temps

99 les personnes peuvent avoir un document ouvert pour modification en même temps. Si plus de 10 personnes modifient simultanément un document, leurs modifications sont plus susceptibles de se produire et l’expérience utilisateur se dégrade progressivement.

### <a name="users"></a>Utilisateurs

2 millions par site (collection de sites).
   
> [!NOTE]
> Il n’y a pas de limite au nombre d’invités que vous pouvez inviter sur les sites SharePoint. Pour plus d’informations sur le partage externe, consultez la rubrique [vue d’ensemble du partage externe](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Consultez aussi

[Limites de recherche pour SharePoint](/sharepoint/search-limits)
