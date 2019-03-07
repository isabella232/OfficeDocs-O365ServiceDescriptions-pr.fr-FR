---
title: Domaines
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/10/2017
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Lorsque vous ajoutez un domaine, un assistant vous permet d’ajouter des utilisateurs et de convertir vos adresses de messagerie Office 365 et d’autres services pour que le nom de votre entreprise y figure. Une fois l'assistant terminé, vos courriers électroniques professionnels commencent à être dirigés vers Office 365 au lieu de votre fournisseur de messagerie actuel. Pour plus d'informations, voir Ajouter vos utilisateurs et votre domaine à Office 365. Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à la rubrique Verify Your Domain.
ms.openlocfilehash: 1dc6d23afea52dd292d97b414e5b491d6d332dd7
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466371"
---
# <a name="domains"></a>Domaines

Lorsque vous ajoutez un domaine, un assistant vous permet d’ajouter des utilisateurs et de convertir vos adresses de messagerie Office 365 et d’autres services pour que le nom de votre entreprise y figure. Une fois l’assistant terminé, vos courriers électroniques professionnels commencent à être dirigés vers Office 365 au lieu de votre fournisseur de messagerie actuel. Pour plus d'informations, voir [Ajouter vos utilisateurs et votre domaine à Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Si vous utilisez Office 365 géré par 21Vianet, reportez-vous à l'article relatif à la [vérification de votre domaine](http://go.microsoft.com/fwlink/?LinkID=733344&amp;clcid=0x409).
  
## <a name="custom-domains"></a>Domaines personnalisés
<a name="BKMK_CustomDomains"> </a>

Vous pouvez ajouter jusqu'à 900 domaines à votre abonnement Office 365. Cependant, vous ne pouvez pas ajouter à Office 365 un domaine que vous utilisez déjà dans un autre service cloud de Microsoft. Cela signifie que vous ne pouvez pas ajouter le même domaine à plusieurs abonnements Office 365. Pour plus d'informations, consultez la section [Forum aux questions sur les domaines](https://support.office.com/en-us/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domaines de deuxième et de troisième niveau
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

Avec Office 365 Entreprise et Office 365 Business, vous pouvez ajouter un domaine de n'importe quel niveau, y compris des domaines de troisième niveau tels que marketing.contoso.com. Voir [Ajouter des sous-domaines ou plusieurs domaines personnalisés à Office 365](http://go.microsoft.com/fwlink/?LinkID=733345&amp;clcid=0x409). Si vous utilisez Office 365 géré par 21Vianet, voir [Ajouter des sous-domaines ou plusieurs domaines personnalisés à Office 365 géré par 21Vianet](http://go.microsoft.com/fwlink/?LinkID=733346&amp;clcid=0x409).
  
## <a name="domain-verification-and-managing-dns-records"></a>Vérification de domaine et gestion des enregistrements DNS
<a name="BKMK_ManagingDNSRecords"> </a>

Avec Office 365, vous pouvez gérer tous vos enregistrements DNS au niveau de votre fournisseur d'hébergement DNS ou choisir que Office 365 configure et gère les enregistrements DNS de votre domaine pour vous. Si vous continuez à gérer les enregistrements, vous modifiez des enregistrements spécifiques pour qu'ils pointent vers les services Office 365, le cas échéant. Pour obtenir la liste des bureaux d'enregistrement de domaines pour lesquels nous fournissons des instructions étape par étape pour ajouter des enregistrements, notamment les valeurs spécifiques à utiliser pour chaque enregistrement, consultez la rubrique [Créer des enregistrements DNS auprès d'un fournisseur d'hébergement DNS pour Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270173) ou, si vous utilisez Office 365 géré par 21Vianet, consultez la rubrique relative à la création des enregistrements DNS auprès d'un fournisseur d'hébergement DNS pour Office 365 géré par .21Vianet. 
  
Si Office 365 gère les enregistrements DNS de votre domaine pour vous, vous devez d'abord basculer les enregistrements de serveur de noms de votre domaine pour qu'ils pointent vers Office 365, puis Office 365 configure vos services Office 365 et les enregistrements DNS de votre domaine sont gérés au niveau d'Office 365.
  
Si votre domaine est inscrit sur Go Daddy, Office 365 peut créer les enregistrements nécessaires pour vous sur Go Daddy. 
  
Peu importe où vos enregistrements DNS sont hébergés, vous pouvez les configurer pour qu'ils utilisent votre domaine pour l'URL d'un site web public hébergé sur Office 365 ou un fournisseur d'hébergement différent. 
  
Office 365 vérifie vos enregistrements DNS de façon proactive pour rechercher les problèmes liés à DNS et les résoudre. Si vos enregistrements DNS ne correspondent pas à ce que nous attendions, vous recevrez une notification dans le centre d'administration 365 de Microsoft, ainsi que des informations qui vous expliquent comment résoudre les problèmes susceptibles d'être identifiés.
  
Pour plus d'informations, consultez la [FAQ sur les domaines](https://go.microsoft.com/fwlink/p/?LinkID=270144) ou, pour Office 365 géré par 21Vianet, consultez la rubrique relative à la [création d'enregistrements DNS pour Office 365 lorsque vous gérez vos enregistrements DNS](http://go.microsoft.com/fwlink/?LinkID=817326&amp;clcid=0x409).
  
## <a name="sharing-a-domain"></a>Partage d’un domaine
<a name="BKMK_ManagingDNSRecords"> </a>

Vous pouvez piloter Office 365 avec quelques adresses de messagerie pour un domaine sur Office 365 et quelques-unes sur votre fournisseur de messagerie précédent. Cette option est recommandée pour une utilisation au cours d'un projet pilote d'Office 365, car elle nécessite des étapes de configuration supplémentaires et présente certaines limitations pour les services 365 Office. Pour plus d'informations, consultez les rubriques suivantes :
  
- [Essai pilote d'Office 365 pour une petite entreprise](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilote Office 365 pour une grande entreprise (avec FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilité des fonctionnalités
<a name="BKMK_ManagingDNSRecords"> </a>

Pour afficher la disponibilité des fonctionnalités selon les plans Office 365, les options autonomes et les solutions locales, voir [Description du service de plateforme Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

