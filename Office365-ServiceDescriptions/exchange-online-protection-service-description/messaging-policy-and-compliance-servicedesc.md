---
title: Stratégie et conformité de messagerie
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) fournit des fonctionnalités de stratégie et de conformité de messagerie qui peuvent vous aider à gérer vos données de messagerie.
ms.openlocfilehash: a37ad3c1bcecb73f7c903b553bdcb43935dc9ed7
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246120"
---
# <a name="messaging-policy-and-compliance"></a>Stratégie et conformité de messagerie

Microsoft Exchange Online Protection (EOP) fournit des fonctionnalités de stratégie et de conformité de messagerie qui peuvent vous aider à gérer vos données de messagerie.
  
Vous recherchez des informations sur toutes les fonctionnalités EOP ? Consultez la rubrique [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="transport-rules"></a>Règles de transport
<a name="BKMK_transportrules"> </a>

Les règles de transport vous offrent toute la flexibilité pour appliquer les stratégies de messagerie de votre propre organisation. Les règles de transport sont composées de critères flexibles qui vous permettent de définir des conditions et des exceptions, ainsi que des actions à exécuter en fonction des critères. Pour plus d'informations sur les règles de transport dans EOP, consultez la rubrique [Règles de transport](https://go.microsoft.com/fwlink/p/?LinkId=320399).
  
## <a name="audit-logging"></a>Journalisation d'audit
<a name="BKMK_auditlogging"> </a>

La journalisation d'audit vous permet de suivre les modifications apportées par les administrateurs à votre organisation. Ces rapports vous aident à satisfaire les exigences relatives aux réglementations, à la conformité et aux litiges. Pour plus d'informations, consultez la rubrique [Rapports d'audit dans EOP](https://go.microsoft.com/fwlink/p/?LinkId=314258).
  
## <a name="data-loss-prevention-dlp"></a>Protection contre la perte de données (DLP)
<a name="BKMK_datalossprevention"> </a>

Non disponible pour les clients EOP autonomes. La protection contre la perte de données (DLP) vous aide à identifier, à surveiller et à protéger des informations sensibles de votre organisation grâce à l'analyse approfondie du contenu. Il s'agit d'une fonctionnalité de plus en plus importante pour les systèmes de messagerie d'entreprise car certains messages électroniques vitaux contiennent des données sensibles qui doivent être protégées. La fonctionnalité de protection contre la perte de données vous permet de protéger les données sensibles sans affecter la productivité de vos collaborateurs.
  
Vous pouvez configurer des stratégies de protection contre la perte de données dans le CAE qui vous offre les possibilités suivantes :
  
- Démarrer avec un modèle de stratégie préconfigurée qui vous permet de détecter des types spécifiques d'informations sensibles, tels que des données PCI-DSS, des données Gramm-Leach-Bliley Act ou même des informations d'identification personnelle spécifiques aux paramètres régionaux.
    
- Exploiter toute la puissance des critères et des actions de règles de transport existants et ajouter de nouvelles règles de transport.
    
- Tester l'efficacité de vos stratégies DLP avant de les appliquer pleinement.
    
- Incorporer vos propres modèles de stratégie DLP personnalisés et types d'informations sensibles.
    
- Détecter des informations sensibles dans les pièces jointes, le corps du texte ou les lignes d'objet des messages, et ajuster le niveau de confiance à partir duquel le service intervient.
    
- Détecter les données de formulaire sensibles à l'aide de la création d'empreintes digitales document. La création d'empreintes digitales document vous permet de créer facilement des types d'informations sensibles personnalisés à partir des formulaires texte que vous pouvez utiliser pour définir des règles de transport et des stratégies de protection contre la perte de données.
    
- Ajouter des conseils de stratégie qui permettent de réduire la perte de données en affichant une notification à vos utilisateurs Outlook 2013, Outlook Web App et OWA pour les périphériques ainsi que d'améliorer l'efficacité de vos stratégies en autorisant la création de rapports de faux-positifs.
    
- Examiner les données relatives aux incidents dans les rapports DLP ou ajouter vos propres rapports spécifiques à l'aide d'une action de génération de rapports d'incidents.
    
> [!NOTE]
> Les stratégies de protection contre la perte de données s'appliquent uniquement au courrier entrant ou sortant de l'organisation. Aucune stratégie de protection contre la perte de données ne s'applique au courrier interne, sauf si vous exécutez Exchange Server 2013 avec la protection contre la perte de données localement. Cela vaut également pour les conseils de protection contre la perte de données qui informent les utilisateurs concernant de possibles violations de stratégie avant l'envoi inopiné de données sensibles à des destinataires non autorisés. 
  
Pour plus d'informations sur la protection contre la perte de données, consultez la rubrique [Protection contre la perte de données](https://go.microsoft.com/fwlink/p/?LinkId=320398).
  
## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365
<a name="BKMK_OME_in_EOP"> </a>

Le chiffrement de messages Office 365, qui fait partie d'Azure information protection, est un service en ligne qui permet aux utilisateurs de messagerie d'envoyer des messages électroniques chiffrés à tous. Les clients locaux peuvent accéder au chiffrement de messages Office 365 en achetant Azure information protection et en utilisant Exchange Online Protection pour configurer le flux de messagerie via Exchange Online. Pour en savoir plus sur le chiffrement de messages Office 365 dans Exchange Online, consultez la rubrique [office 365 message](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) Encryption dans la description du service Exchange Online. 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Fonctionnalités de stratégie et de conformité de messagerie entre les options EOP
<a name="BKMK_OME_in_EOP"> </a>

|**Fonctionnalité**|**EOP autonome**|**Fonctionnalités EOP dans Exchange Online**|**Licence d'accès client Exchange Enterprise avec Services**|
|:-----|:-----|:-----|:-----|
|Règles de transport  <br/> |Oui<sup>1</sup> <br/> |Oui<sup>1</sup> <br/> |Oui  <br/> |
|Journalisation d'audit  <br/> |Oui<sup>2</sup> <br/> |Oui  <br/> |Oui  <br/> |
|Protection contre la perte de données (DLP)  <br/> |Non  <br/> |Oui  <br/> |Oui<sup>3</sup> <br/> |
|Chiffrement de messages Office 365  <br/> |Oui<sup>4</sup> <br/> |Oui  <br/> |Oui<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Les actions et les conditions disponibles diffèrent entre EOP et Exchange Online. Pour obtenir une liste des conditions et des actions disponibles dans EOP, consultez les rubriques [Conditions de règle de transport (prédicats)](https://go.microsoft.com/fwlink/p/?LinkId=320392) et [Actions de règles de transport](https://go.microsoft.com/fwlink/p/?LinkId=320393). Pour obtenir une liste des critères et des actions disponibles dans Exchange Online, consultez les rubriques [Critères de règles de transport](https://go.microsoft.com/fwlink/p/?LinkId=320394) et [Actions de règles de transport](https://go.microsoft.com/fwlink/p/?LinkId=320395). <br/>
> <sup>2</sup> Les rapports d'audit EOP sont un sous-ensemble de rapports d'audit Exchange Online qui excluent les informations sur les boîtes aux lettres. <br/>
> <sup>3</sup> Les conseils de stratégie DLP ne sont pas disponibles pour la licence d'accès client Exchange Enterprise avec les clients Services. <br/>
> <sup>4</sup> pris en charge pour les clients locaux qui achètent le module complémentaire Azure information protection et utilisent Exchange Online Protection pour acheminer le courrier électronique via Exchange Online. Pour l'expérience utilisateur, outre le complément Azure information protection, Office 365 proPlus doit être acheté. <br/>
  

