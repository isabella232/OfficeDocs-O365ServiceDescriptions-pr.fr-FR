---
title: Domaines
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Lorsque vous ajoutez un domaine, un Assistant pas à pas vous permet d’ajouter des utilisateurs et de convertir vos adresses e-mail et d’autres services au nom de votre entreprise. Lorsque vous avez terminé l’Assistant, votre courrier électronique professionnel commence à arriver à Microsoft au lieu d’être envoyé à votre fournisseur de messagerie actuel. Pour plus d’informations, voir Ajouter vos utilisateurs et domaines à Microsoft. Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à l'article relatif à la vérification de votre domaine.
ms.openlocfilehash: 57df3e7fb22e8a576099432b8cdc7c84a8462bad
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51172989"
---
# <a name="domains"></a>Domaines

Lorsque vous ajoutez un domaine, un Assistant pas à pas vous permet d’ajouter des utilisateurs et de convertir vos adresses de messagerie et d’autres services au nom de votre entreprise. Une fois l’Assistant terminé, le courrier électronique de votre entreprise commence à arriver à Microsoft au lieu d’être envoyé à votre fournisseur de messagerie actuel. Pour en savoir plus, voir [Ajouter vos utilisateurs et domaines à Microsoft.](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611) Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à l'article relatif à la [vérification de votre domaine](/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Domaines personnalisés

Vous pouvez ajouter jusqu’à 900 domaines à votre abonnement (y compris les sous-domaines). Vous ne pouvez pas ajouter à Microsoft 365 un domaine que vous utilisez déjà dans un autre service cloud Microsoft. Cela signifie que vous ne pouvez pas ajouter le même domaine à plusieurs abonnements. Pour plus d’informations, [voir Forum aux questions sur les domaines.](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)
  
### <a name="second-and-third-level-domains"></a>Domaines de deuxième et de troisième niveau

Avec Office 365 Entreprise et Microsoft 365 Apps for business, vous pouvez ajouter n’importe quel domaine de niveau, y compris les domaines de troisième niveau tels que marketing.contoso.com. Voir [Ajouter des sous-domaines personnalisés ou plusieurs domaines à Microsoft.](/office365/admin/setup/domains-faq) Si vous utilisez Office 365 géré par 21Vianet, voir [Ajouter des sous-domaines ou plusieurs domaines personnalisés à Office 365 géré par 21Vianet](/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Vérification de domaine et gestion des enregistrements DNS

Avec Microsoft 365, vous pouvez gérer tous vos enregistrements DNS auprès de votre fournisseur d’hébergement DNS ou choisir de configurer et de gérer les enregistrements DNS de votre domaine pour vous. Si vous continuez à gérer les enregistrements, vous modifiez des enregistrements spécifiques pour qu’ils pointent vers les services Microsoft selon vos besoins. Pour obtenir la liste des bureaux d’enregistrement de domaines pour lesquels nous fournissons des instructions pas à pas pour ajouter les enregistrements, y compris les valeurs spécifiques à utiliser pour chaque enregistrement, voir Créer des enregistrements [DNS](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) ou, si vous utilisez Office 365 géré par 21Vianet, voir Créer des enregistrements DNS auprès d’un fournisseur pour Office 365 géré par 21Vianet. 
  
Si Microsoft gère les enregistrements DNS de votre domaine à votre place, vous devez d’abord changer les enregistrements de serveurs de noms de votre domaine pour qu’ils pointent vers Microsoft, puis Microsoft définit vos services, puis les enregistrements DNS de votre domaine sont gérés chez Microsoft.
  
Si votre domaine est enregistré auprès de GoDaddy, Microsoft peut créer les enregistrements requis pour vous auprès de GoDaddy. 
  
Quel que soit l’endroit où vos enregistrements DNS sont hébergés, vous pouvez configurer les enregistrements DNS pour utiliser votre domaine pour l’URL d’un site web public hébergé sur Microsoft ou avec un autre fournisseur d’hébergement. 
  
Microsoft vérifie de manière proactive vos enregistrements DNS pour rechercher et résoudre les problèmes DNS. Si vos enregistrements DNS ne correspondent pas à ce que nous attendons d’eux, vous recevrez une notification dans le Centre d’administration Microsoft 365, ainsi que des informations qui vous indiquent comment résoudre les problèmes éventuels qui ont été identifiés.
  
Pour plus d’informations, voir Comment Microsoft gère les enregistrements [DNS](/office365/admin/setup/domains-faq) ou, pour Office 365 géré par 21Vianet, voir Créer des enregistrements [DNS pour Office 365](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)lorsque vous gérez vos enregistrements DNS.
  
## <a name="sharing-a-domain"></a>Partage d’un domaine

Vous pouvez piloter certaines adresses de messagerie pour un domaine sur Microsoft, et d’autres sur votre fournisseur de messagerie précédent. Cette procédure est recommandée uniquement pour une utilisation au cours d’un projet pilote, car elle nécessite des étapes de configuration supplémentaires et présente certaines limitations pour les services Microsoft. Pour plus d’informations, reportez-vous aux rubriques suivantes :
  
- [Pilote Microsoft 365 pour une petite entreprise](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Piloter Microsoft 365 pour une grande entreprise (à l’aide de FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Microsoft 365 pour les entreprises, les options autonomes et les solutions sur site, consultez la description du service de plateforme [Microsoft 365 et Office 365.](office-365-platform-service-description.md)
