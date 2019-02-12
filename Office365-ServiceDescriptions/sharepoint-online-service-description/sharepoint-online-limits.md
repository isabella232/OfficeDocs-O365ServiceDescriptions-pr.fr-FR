---
title: Limites de SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Découvrez les limites de SharePoint Online pour les plans Office 365 Entreprise et pour les plans autonomes.
ms.openlocfilehash: 9d960aa50bef0b200fef2afe63ac1732cf201582
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/12/2019
ms.locfileid: "25848689"
---
# <a name="sharepoint-online-limits"></a>Limites de SharePoint Online

Rechercher les limites de SharePoint pour les plans Office 365 et les plans autonomes de SharePoint Online.
  
## <a name="limits-by-plan"></a>Limites par plan

|||||
|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 entreprise Essentials ou entreprise Premium** <br/> |**Office 365 entreprise E1, E3, ou E5 ou SharePoint Exchange Online-Plan 1 ou 2** <br/> | **Office 365 Entreprise F1** <br/> |
|Stockage<sup>1, 2</sup> <br/> |1 To par organisation plus de 10 Go par licence acheté  <br/> |1 To par organisation plus de 10 Go par licence acheté<sup>3</sup> <br/> |1 To par organisation <sup>3</sup> <br/> |
|Stockage pour les collections de sites  <br/> |Jusqu'à 25 To par collection de sites ou groupe<sup>4</sup> <br/> |Jusqu'à 25 To par collection de sites ou groupe<sup>4</sup> <br/> |Jusqu'à 25 To par collection de sites ou groupe<sup>5</sup> <br/> |
|Collections de sites par l’organisation  <br/> |500 000<sup>6</sup> <br/> |500 000<sup>6</sup> <br/> |500,000<br/> |
|Nombre d'utilisateurs.  <br/> |Jusqu'à 300  <br/> |1 - 500 000<sup>7</sup> <br/> |1 - 500 000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> vous pouvez acheter un nombre illimité de stockage SharePoint Online supplémentaire. Consultez [l’espace de stockage de modification de votre abonnement](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C).<br/><sup>2</sup> nous vous recommandons de surveillance de la Corbeille et régulièrement le vidage. Il utilise l’espace de stockage fait partie de la limite de stockage des fichiers de l’organisation.<br/> <sup>3</sup> Lorsque vous possédez un abonnement Office 365 et un plan autonome SharePoint Online, les volumes de stockage sont additionnés.<br/><sup>4</sup> les administrateurs SharePoint Online peuvent définir des limites de stockage pour les collections de sites.<br/> <sup>5</sup> travailleurs kiosk ne peut pas administrer les collections de sites SharePoint Online. Vous devez au moins une licence d’utilisateur d’entreprise pour gérer les collections de sites kiosk.<br/> <sup>6</sup> Les collections de sites OneDrive Entreprise créées pour chaque utilisateur sous licence ne sont pas comprises.<br/><sup>7</sup> Si vous avez plus de 500 000 utilisateurs, contactez un représentant Microsoft. 
  

  
## <a name="service-limits-for-all-plans"></a>Limites du service pour tous les plans

- **Éléments dans les listes et bibliothèques** - liste peut avoir jusqu'à 30 millions d’éléments et une bibliothèque peut avoir jusqu'à 30 millions de fichiers et dossiers. Affichages peuvent avoir jusqu'à 12 colonnes de recherche. Pour plus d’informations sur les restrictions pour l’affichage des listes volumineuses, voir [Gérer les grandes listes et bibliothèques dans Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Pour plus d’informations sur les caractères qui ne peut pas être utilisé dans les noms de fichiers, voir [les caractères non valides dans les noms de fichiers et de dossiers](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Taille du fichier et longueur de chemin d’accès de fichier** - 15 Go. Pour en savoir plus sur les limites et restrictions lors de l’utilisation du nouveau client de synchronisation OneDrive (OneDrive.exe), voir [les noms de fichiers non valide et les types de fichiers dans OneDrive, OneDrive entreprise et SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Synchronisation** - pour des performances optimales, nous vous recommandons de stocker pas plus de 300 000 fichiers dans une seule bibliothèque de site OneDrive ou de l’équipe. Bien que SharePoint Online peuvent stocker les documents 30 millions par bibliothèque, pour des performances optimales nous vous recommandons la synchronisation pas plus de 300 000 fichiers parmi toutes les bibliothèques de documents. En outre, les problèmes de performances même peuvent se produire si vous avez au moins 300 000 éléments parmi toutes les bibliothèques que vous synchronisez, même si vous vous synchronisez pas tous les éléments dans ces bibliothèques. Si vous utilisez le précédent OneDrive pour le client de synchronisation Business (Groove.exe), la limite de synchronisation par bibliothèque est de 20 000 éléments (y compris les 5 000 éléments par site d’équipe).

- **Versions** - 50 000 versions principales et secondaires 511.

- **Groupes SharePoint** - un utilisateur peut appartenir aux groupes de 5 000, et chaque groupe peut comporter jusqu'à 5 000 utilisateurs. Vous pouvez avoir jusqu'à 10 000 groupes par collection de sites.

- **Métadonnées gérées** - 200 000 termes dans le magasin de termes, 1 000 ensembles de termes global, groupes de 1 000.

- **Sous-sites** - jusqu'à 2 000 par collection de sites.

- **Applications hébergées de SharePoint** - 20 000 instances par l’organisation.

- **Étendues de sécurité uniques par liste ou bibliothèque** - 5 000. Pour les grandes listes, concevez à posséder des autorisations uniques aussi peu que possible.

- **Utilisateurs** : 2 millions par collection de sites.

> [!NOTE]
> [!REMARQUE] Il n'y a pas de limite au nombre d'utilisateurs externes que vous pouvez inviter sur vos collections de sites SharePoint Online. Pour plus d'informations, voir [Gérer le partage externe pour votre environnement SharePoint Online](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Voir aussi

[Limites de la recherche de SharePoint Online](/sharepoint/search-limits)