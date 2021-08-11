---
title: Stratégie et conformité de messagerie dans Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Lisez cet article pour en savoir plus sur la stratégie de messagerie et les fonctionnalités de conformité dans Microsoft Exchange Online Protection des données (EOP).
ms.openlocfilehash: fa2e4cfc9345a2dfc7d0ebf2d12a31c5aeb1da532a889a815a0ec3d6d5880c2b
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664107"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>Stratégie et conformité de messagerie dans Exchange Online Protection

Microsoft Exchange Online Protection (EOP) fournit des fonctionnalités de stratégie et de conformité de messagerie qui peuvent vous aider à gérer vos données de messagerie.

Vous recherchez des informations sur toutes les fonctionnalités EOP ? Consultez la [description Exchange Online Protection service.](exchange-online-protection-service-description.md)

## <a name="mail-flow-rules"></a>Règles de flux de messagerie

Les règles de flux de messagerie (également appelées règles de transport) vous offrent la possibilité d’appliquer vos propres stratégies propres à votre entreprise à la messagerie électronique. Les règles de flux de messagerie sont composés de critères flexibles qui vous permettent de définir des conditions, des exceptions et des actions à prendre en fonction des critères. Pour plus d’informations, voir [Règles de flux de messagerie (règles](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)de transport) dans Exchange Online Protection .

## <a name="audit-logging"></a>Journalisation d'audit

La journalisation d’audit vous permet de suivre les modifications apportées par les administrateurs à votre organisation. Ces rapports vous aident à satisfaire les exigences relatives aux réglementations, à la conformité et aux litiges. Pour plus d'informations, voir [Rapports d'audit dans EOP](/microsoft-365/security/office-365-security/auditing-reports-in-eop).

## <a name="data-loss-prevention-dlp"></a>Protection contre la perte de données (DLP)

Non disponible pour les clients EOP autonomes. La protection contre la perte de données (DLP) vous aide à identifier, à surveiller et à protéger des informations sensibles de votre organisation grâce à l'analyse approfondie du contenu. Il s'agit d'une fonctionnalité de plus en plus importante pour les systèmes de messagerie d'entreprise car certains messages électroniques vitaux contiennent des données sensibles qui doivent être protégées. La fonctionnalité DLP vous permet de protéger les données sensibles sans affecter la productivité des travailleurs.

Vous pouvez configurer des stratégies de protection contre la perte de données dans le CAE qui vous offre les possibilités suivantes :

- Démarrer avec un modèle de stratégie préconfigurée qui vous permet de détecter des types spécifiques d'informations sensibles, tels que des données PCI-DSS, des données Gramm-Leach-Bliley Act ou même des informations d'identification personnelle spécifiques aux paramètres régionaux.

- Utilisez toute la puissance des critères et des actions de règle de flux de messagerie existants et ajoutez de nouvelles règles de flux de messagerie.

- Tester l'efficacité de vos stratégies DLP avant de les appliquer pleinement.

- Incorporer vos propres modèles de stratégie DLP personnalisés et types d'informations sensibles.

- Détecter des informations sensibles dans les pièces jointes, le corps du texte ou les lignes d'objet des messages, et ajuster le niveau de confiance à partir duquel le service intervient.

- Détecter les données de formulaire sensibles à l'aide de la création d'empreintes digitales document. L’empreinte numérique de document vous permet de créer facilement des types d’informations sensibles personnalisés basés sur des formulaires texte que vous pouvez utiliser pour définir des règles de flux de messagerie et des stratégies DLP.

- Ajoutez des Astuces de stratégie, ce qui permet de réduire la perte de données en affichant une notification à vos Outlook 2013, Outlook sur le web et OWA pour les utilisateurs d’appareils et peut également améliorer l’efficacité de vos stratégies en permettant la signalement de faux positifs.

- Examiner les données relatives aux incidents dans les rapports DLP ou ajouter vos propres rapports spécifiques à l'aide d'une action de génération de rapports d'incidents.

> [!NOTE]
> Les stratégies de protection contre la perte de données s'appliquent uniquement au courrier entrant ou sortant de l'organisation. Aucune stratégie de protection contre la perte de données ne s'applique au courrier interne, sauf si vous exécutez Exchange Server 2013 avec la protection contre la perte de données localement. Cela vaut également pour les conseils de protection contre la perte de données qui informent les utilisateurs concernant de possibles violations de stratégie avant l'envoi inopiné de données sensibles à des destinataires non autorisés.

Pour en savoir plus sur la protection contre la perte de données, consultez protection contre la perte de [données dans Exchange Online](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).

## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365

chiffrement de messages Office 365, qui fait partie d’Azure Information Protection, est un service en ligne qui permet aux utilisateurs de messagerie d’envoyer des messages électroniques chiffrés à tout le monde. Les clients locaux peuvent accéder aux chiffrement de messages Office 365 en achetant Azure Information Protection et en utilisant Exchange Online Protection pour configurer le flux de messagerie via Exchange Online. Pour en savoir plus sur les chiffrement de messages Office 365 dans Exchange Online, voir chiffrement de messages Office 365 [la](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) description Exchange Online service.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Fonctionnalités de stratégie et de conformité de messagerie entre les options EOP

| Fonctionnalité | EOP autonome | Fonctionnalités EOP dans <br/> Exchange Online | Exchange Enterprise <br/> CAL avec services |
|:-----|:-----|:-----|:-----|
|Règles de flux de messagerie|Oui<sup>1</sup>|Oui<sup>1</sup>|Oui<sup>1, 3</sup>|
|Journalisation d'audit|Oui<sup>2</sup>|Oui|Oui|
|Protection contre la perte de données (DLP)|Non|Oui|Oui<sup>3</sup>|
|Chiffrement de messages Office 365|Oui<sup>4</sup>|Oui|Oui<sup>4</sup>|

> [!NOTE]
> <sup>1 Les</sup> conditions, les exceptions et les actions de règle de flux de messagerie disponibles diffèrent légèrement entre EOP et Exchange Online. Ces différences sont notées dans les conditions de règle de flux de messagerie et les [exceptions (prédicats)](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) dans Exchange Online et les actions de règle de flux de [messagerie dans Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions). <br/>
> <sup>2</sup> Les rapports d'audit EOP sont un sous-ensemble de rapports d'audit Exchange Online qui excluent les informations sur les boîtes aux lettres.<br/>
> <sup>3</sup> Les conseils de stratégie DLP ne sont pas disponibles pour la licence d'accès client Exchange Enterprise avec les clients Services.<br/>
> <sup>4 Pris</sup> en charge pour les clients locaux qui achètent le module complémentaire Azure Information Protection et utilisent Exchange Online Protection pour router le courrier électronique via Exchange Online. Pour l’expérience de bureau, en plus du module complémentaire Azure Information Protection, Applications Microsoft 365 pour les grandes entreprises doit être acheté. <br/>