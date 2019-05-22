---
title: Limites de SharePoint Online
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Découvrez les limites de SharePoint Online pour les plans Office 365 Entreprise et pour les plans autonomes.
ms.openlocfilehash: 5c89f7fa92a91a780be9350e16be87e537370586
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342533"
---
# <a name="sharepoint-online-limits"></a>Limites de SharePoint Online

Découvrez les limites de SharePoint pour les plans Office 365 et les plans autonomes SharePoint Online.
  
## <a name="limits-by-plan"></a>Limites par plan

|||||
|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Business Essentials ou Business Premium** <br/> |**Office 365 entreprise E1, E3 ou E5, ou SharePoint Online plan 1 ou 2** <br/> | **Office 365 Entreprise F1** <br/> |
|Stockage<sup>1, 2</sup> <br/> |1 to par organisation, plus 10 Go par licence achetée  <br/> |1 to par organisation, plus 10 Go par licence achetée<sup>3</sup> <br/> |1 To par organisation <sup>3</sup> <br/> |
|Stockage pour les collections de sites  <br/> |Jusqu'à 25 To par collection de sites ou groupe<sup>4</sup> <br/> |Jusqu'à 25 To par collection de sites ou groupe<sup>4</sup> <br/> |Jusqu'à 25 To par collection de sites ou groupe<sup>5</sup> <br/> |
|Collections de sites par organisation  <br/> |500 000<sup>6</sup> <br/> |500 000<sup>6</sup> <br/> |500 000<br/> |
|Nombre d'utilisateurs.  <br/> |Jusqu'à 300  <br/> |1 - 500 000<sup>7</sup> <br/> |1 - 500 000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Vous pouvez acheter un volume illimité de stockage SharePoint Online supplémentaire. Consultez la rubrique [Modifier l'espace de stockage pour votre abonnement](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C). 
<br/><sup>2</sup> Nous vous recommandons de surveiller la Corbeille et de la vider régulièrement. L'espace de stockage qu'elle utilise fait partie de la limite totale de stockage de fichiers de l'organisation. 
<br/> <sup>3</sup> Lorsque vous possédez un abonnement Office 365 et un plan autonome SharePoint Online, les volumes de stockage sont additionnés. 
<br/><sup>4</sup> les administrateurs de SharePoint Online peuvent définir des limites de stockage pour les sites et les collections de sites.
<br/> <sup>5</sup> Les collaborateurs Kiosk ne peuvent pas administrer les collections de sites SharePoint Online. Vous devez disposer d'au moins une licence utilisateur Enterprise pour gérer les collections de sites Kiosk. 
<br/> <sup>6</sup> Les collections de sites OneDrive Entreprise créées pour chaque utilisateur sous licence ne sont pas comprises. 
<br/><sup>7</sup> Si vous avez plus de 500 000 utilisateurs, contactez un représentant Microsoft. 
  

  
## <a name="service-limits-for-all-plans"></a>Limites de service pour tous les plans

- **Éléments dans des listes et des bibliothèques** : une liste peut comporter jusqu’à 30 millions éléments et une bibliothèque peut comporter jusqu’à 30 millions fichiers et dossiers. Après 100, 00 éléments sont ajoutés à une liste, une bibliothèque ou un dossier, l’héritage des autorisations pour la liste, la bibliothèque ou le dossier ne peut pas être modifié. Pour en savoir plus sur les autres restrictions relatives à l’affichage des grandes listes, voir [gérer les grandes listes et les bibliothèques dans Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Pour plus d’informations sur les caractères qui ne peuvent pas être utilisés dans les noms de fichiers, voir [caractères non valides dans les noms de fichier et de dossier](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Taille du fichier et longueur du chemin d’accès du fichier** -15 Go. Pour en savoir plus sur les restrictions et les limites de l’utilisation du nouveau client de synchronisation OneDrive (OneDrive. exe), voir [noms de fichiers et types de fichiers non valides dans onedrive, Onedrive entreprise et SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- Le **transfert et la copie sur plusieurs collections de sites** : 100 Go par opération. Le navigateur Web doit rester ouvert.

- **Synchronisation** : pour des performances optimales, nous vous recommandons de ne pas stocker plus de 300 000 fichiers dans une bibliothèque OneDrive ou une bibliothèque de sites d’équipe. Bien que SharePoint Online puisse stocker 30 millions documents par bibliothèque, pour des performances optimales, nous vous recommandons de synchroniser un maximum de 300 000 fichiers dans toutes les bibliothèques de documents. En outre, les mêmes problèmes de performances peuvent se produire si vous avez 300 000 éléments ou plus dans toutes les bibliothèques que vous synchronisez, même si vous ne synchronisez pas tous les éléments de ces bibliothèques. Si vous utilisez le client de synchronisation OneDrive entreprise précédent (Groove. exe), la limite de synchronisation par bibliothèque est de 20 000 éléments (y compris 5 000 éléments par site d’équipe).

- Versions principales de **versions** 50 000 et 511.

- **Groupes SharePoint** : un utilisateur peut appartenir à des groupes 5 000 et chaque groupe peut avoir jusqu’à 5 000 utilisateurs. Vous pouvez avoir jusqu’à 10 000 groupes par collection de sites.

- **Metadata gérée** -200 000 termes dans le magasin de termes, 1 000 ensembles de termes globaux, 1 000 groupes.

- **Sous-sites** : jusqu’à 2 000 par collection de sites.

- **Applications hébergées SharePoint** -20 000 instances par organisation.

- **Étendues de sécurité uniques par liste ou par bibliothèque** -5 000. Pour les grandes listes, la conception a le moins d’autorisations uniques possible.

- **Utilisateurs** -2 millions par collection de sites.

> [!NOTE]
> Il n’y a pas de limite au nombre d’utilisateurs externes que vous pouvez inviter à vos collections de sites SharePoint Online. Pour obtenir plus d’informations, consultez l’article [Gérer le partage externe pour votre environnement SharePoint Online](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Voir aussi

[Limites de recherche pour SharePoint Online](/sharepoint/search-limits)
