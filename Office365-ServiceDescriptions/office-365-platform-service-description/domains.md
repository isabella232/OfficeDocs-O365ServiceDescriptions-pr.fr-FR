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
description: Lorsque vous ajoutez un domaine, un assistant étape par étape vous permet d’ajouter des utilisateurs et de convertir vos adresses de messagerie et d’autres services en nom professionnel. Lorsque vous avez terminé l’Assistant, votre courrier professionnel commence à Microsoft au lieu de passer à votre fournisseur de messagerie actuel. Pour plus d’informations, consultez la rubrique ajouter des utilisateurs et des domaines à Microsoft. Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à l'article relatif à la vérification de votre domaine.
ms.openlocfilehash: 109dd15af75c8e3e04406a63c8868e010c12b9c5
ms.sourcegitcommit: 6a9c3c47e7526de046787ad0f02b9c008e541c34
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/31/2020
ms.locfileid: "46531217"
---
# <a name="domains"></a>Domaines

Lorsque vous ajoutez un domaine, un assistant étape par étape vous permet d’ajouter des utilisateurs et de convertir vos adresses de messagerie et d’autres services en nom professionnel. Lorsque vous avez terminé l’Assistant, votre courrier professionnel commence à Microsoft au lieu de passer à votre fournisseur de messagerie actuel. Pour plus d’informations, consultez [la rubrique ajouter des utilisateurs et des domaines à Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à l'article relatif à la [vérification de votre domaine](https://docs.microsoft.com/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Domaines personnalisés

Vous pouvez ajouter jusqu’à 900 domaines à votre abonnement (y compris les sous-domaines). Vous ne pouvez pas ajouter un domaine à Microsoft 365 que vous utilisez déjà dans un autre service Cloud Microsoft. Cela signifie que vous ne pouvez pas ajouter le même domaine à plusieurs abonnements. Pour plus d’informations, consultez la section [Forum aux questions sur les domaines](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domaines de deuxième et de troisième niveau

Avec Office 365 Enterprise et Microsoft 365 Apps for Business, vous pouvez ajouter n’importe quel domaine de niveau, y compris des domaines de troisième niveau tels que marketing.contoso.com. Consultez la rubrique [Ajouter des sous-domaines personnalisés ou plusieurs domaines à Microsoft](https://docs.microsoft.com/office365/admin/setup/domains-faq). Si vous utilisez Office 365 géré par 21Vianet, voir [Ajouter des sous-domaines ou plusieurs domaines personnalisés à Office 365 géré par 21Vianet](https://docs.microsoft.com/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Vérification de domaine et gestion des enregistrements DNS

Avec Microsoft 365, vous pouvez gérer tous vos enregistrements DNS auprès de votre fournisseur d’hébergement DNS ou choisir de configurer Microsoft et de gérer les enregistrements DNS de votre domaine pour vous. Si vous continuez à gérer les enregistrements, vous modifiez des enregistrements spécifiques afin qu’ils pointent vers les services Microsoft selon vos besoins. Pour obtenir la liste des registres de domaine pour lesquels nous fournissons des instructions étape par étape pour ajouter les enregistrements, notamment les valeurs spécifiques à utiliser pour chaque enregistrement, consultez la rubrique créer des enregistrements [DNS](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) ou, si vous utilisez Office 365 géré par 21ViaNet, consultez la rubrique créer des enregistrements DNS auprès d’un fournisseur pour Office 365 géré par 21ViaNet. 
  
Si Microsoft gère les enregistrements DNS de votre domaine, vous devez d’abord basculer les enregistrements de serveur de noms de votre domaine pour qu’ils pointent vers Microsoft, puis Microsoft configure vos services et que les enregistrements DNS de votre domaine soient gérés chez Microsoft.
  
Si votre domaine est inscrit sur GoDaddy, Microsoft peut créer les enregistrements nécessaires pour vous sur GoDaddy. 
  
Quelle que soit l’emplacement où vos enregistrements DNS sont hébergés, vous pouvez configurer les enregistrements DNS de sorte qu’ils utilisent votre domaine pour l’URL d’un site Web public hébergé sur Microsoft ou avec un fournisseur d’hébergement différent. 
  
Microsoft vérifie de manière proactive vos enregistrements DNS pour trouver et résoudre les problèmes liés au DNS. Si vos enregistrements DNS ne correspondent pas à ce que nous attendions, vous recevrez une notification dans le centre d’administration 365 de Microsoft, ainsi que des informations qui vous expliquent comment résoudre les problèmes susceptibles d’être identifiés.
  
Pour plus d’informations, consultez la rubrique relative à [la gestion des enregistrements DNS par Microsoft](https://docs.microsoft.com/office365/admin/setup/domains-faq) ou, pour Office 365 géré par 21ViaNet, consultez la rubrique [créer des enregistrements dns pour Office 365 lors de la gestion de vos enregistrements DNS](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Partage d’un domaine

Vous pouvez piloter certaines adresses de messagerie pour un domaine sur Microsoft et d’autres sur votre fournisseur de messagerie précédent. Cette option est recommandée pour une utilisation au cours d’un projet pilote, car elle nécessite des étapes de configuration supplémentaires et présente certaines limitations pour les services Microsoft. Si vous souhaitez plus d’informations, reportez-vous aux rubriques suivantes :
  
- [Pilote Microsoft 365 pour une petite entreprise](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilote Microsoft 365 pour une grande entreprise (avec FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans d’entreprise, les options autonomes et les solutions locales de Microsoft 365, voir [microsoft 365 et Office 365 Platform Service Description](office-365-platform-service-description.md).
  

