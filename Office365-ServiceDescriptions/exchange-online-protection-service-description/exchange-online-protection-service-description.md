---
title: Description du service Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Obtenez des informations sur les fonctionnalités d’Exchange Online Protection et la configuration requise. Une liste des plans qui fournissent des Exchange Online Protection, ainsi qu’une comparaison des fonctionnalités de ces plans sont incluses.
ms.openlocfilehash: a82468c95f8d674bb2e4b27abc668074f222b419
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670710"
---
# <a name="exchange-online-protection-service-description"></a>Description du service Exchange Online Protection

Obtenez des informations sur les fonctionnalités d’Exchange Online Protection et la configuration requise. Une liste des plans qui fournissent des Exchange Online Protection, ainsi qu’une comparaison des fonctionnalités de ces plans sont incluses.

Microsoft Exchange Online Protection (EOP) est un service de filtrage de courrier électronique basé sur le cloud qui contribue à protéger votre organisation contre le courrier indésirable et les programmes malveillants et inclut des fonctionnalités pour protéger votre organisation contre les violations de stratégie de messagerie. EOP peut simplifier la gestion de votre environnement de messagerie et alléger bon nombre des tâches liées à la maintenance du matériel et des logiciels locaux.

La liste suivante décrit les principales façons d’utiliser EOP pour la protection de la messagerie :

- **Dans** un scénario autonome : EOP fournit une protection de messagerie en nuage pour votre environnement de messagerie local (Exchange Server ou d’autres solutions de messagerie SMTP locales).

- **Dans le cadre de Microsoft Exchange Online**: Par défaut, EOP protège Exchange Online boîtes aux lettres hébergées dans le cloud. Pour en savoir plus sur Exchange Online, voir la [description Exchange Online service.](../exchange-online-service-description/exchange-online-service-description.md)

- **Dans un** déploiement hybride : EOP peut être configuré pour protéger votre environnement de messagerie et contrôler le routage du courrier lorsque vous avez une combinaison de boîtes aux lettres sur site et cloud.

## <a name="available-plans"></a>Plans disponibles

Le tableau suivant présente les plans qui incluent des Exchange Online Protection vous permet de choisir la solution qui répond le mieux aux besoins de votre organisation. Pour obtenir des informations détaillées sur le plan, [voir Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

Pour obtenir des informations détaillées sur les abonnements qui permettent aux utilisateurs d’Exchange Online Protection, consultez le tableau de comparaison [complet des abonnements.](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)

### <a name="exchange-enterprise-cal-with-services-features"></a>Fonctionnalités de la licence d’accès client Exchange Enterprise avec Services

Microsoft Exchange Enterprise CAL avec Services fournit les fonctionnalités de protection de messagerie d’EOP et les fonctionnalités cloud supplémentaires suivantes :

- [Protection contre la perte de données](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Création de rapports à l'aide de services web](reporting-and-message-trace.md#reporting-using-web-services)

Pour plus d’informations sur Exchange Enterprise licence d’accès avec licences services, voir Exchange faq sur les [licences.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)

Si vous avez Exchange Enterprise licences d’accès client avec services et que vous souhaitez mettre en service EOP, suivez les instructions de l’article [Configurer votre service EOP.](/microsoft-365/security/office-365-security/set-up-your-eop-service) Les étapes de configuration sont les mêmes que pour EOP autonome.

> [!NOTE]
> De nouvelles fonctionnalités pour la licence d’accès client Exchange Enterprise avec Services sont déployées en même temps qu’Exchange Online, et non EOP autonome. Les calendriers de déploiement pour EOP autonome et Exchange Online/la licence d’accès client Exchange Enterprise avec Services peuvent varier légèrement.

## <a name="requirements-for-exchange-online-protection-eop"></a>Configuration requise pour Exchange Online Protection (EOP)

EOP peut être utilisé avec n’importe quel agent de transfert de courrier SMTP, comme Microsoft Exchange Server. Pour plus d’informations sur les systèmes d’exploitation, les navigateurs web et les langues pris en charge par EOP, consultez les sections « Navigateurs pris en charge » et « Langues pris en charge » dans le Centre d’administration Exchange dans [Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Limites

Pour les limites dans EOP, [voir Exchange Online Protection limites.](exchange-online-protection-limits.md)

## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Le tableau suivant répertorie les principales fonctionnalités Exchange Online Protection disponibles dans les différents plans. Certaines mises en garde s’appliquent. Pour plus d’informations, consultez les notes de bas de page. Cette table peut changer sans préavis. Pour obtenir la liste complète des fonctionnalités les plus à jour, voir Outils puissants [pour prendre en charge votre entreprise.](https://products.office.com/business/compare-more-office-365-for-business-plans)

| Fonctionnalité | EOP autonome | EOP dans EE CAL w/ Services | Fonctionnalités EOP dans Exchange Online |
|:-----|:-----|:-----|:-----|
|**Protection**||||
|Stratégies anti-programme malveillant (intégrées et personnalisées)|Oui|Oui|Oui|
|Stratégies anti-courrier indésirable entrantes (intégrées et personnalisées)|Oui|Oui|Oui|
|Stratégies anti-courrier indésirable sortantes (intégrées et personnalisées)|Oui|Oui|Oui|
|Filtrage des connexions (liste d’adresses IP et liste d’adresses IP bloqués)|Oui|Oui|Oui|
|Stratégies anti-hameçonnage (intégrées et personnalisées)|Oui|Oui|Oui|
|Protection contre l’usurpation d’usurpation (intégrée et personnalisée)|Oui|Oui|Oui|
|Purge automatique sans heure (ZAP) pour les programmes malveillants, le courrier indésirable et les messages de hameçonnage<sup>remis 10</sup>|Non|Non|Oui|
|Stratégies de sécurité prédéfinies|Oui|Oui|Oui|
|Analyseur de configuration pour les politiques de protection|Oui|Oui|Oui|
|Liste Autoriser/Bloquer du client|Oui|Oui|Oui|
|Listes de blocage pour les expéditeurs de messages|Oui|Oui|Oui|
|Autoriser les listes pour les expéditeurs de messages|Oui|Oui|Oui|
|Blocage du bord|Oui|Oui|Oui|
|Blocage du edge basé sur l’annuaire (DBEB) pour les destinataires inexistants|Oui|Oui|Oui|
|**Mise en quarantaine et soumissions**||||
|Envoi de<sup>l’administrateur 10</sup>|Non|Non|Oui|
|Envoi d’utilisateur (boîte aux lettres<sup>personnalisée) 10</sup>|Non|Non|Oui|
|Mise en quarantaine de l’administrateur|Oui|Oui|Oui|
|Mise en quarantaine de l’utilisateur final|Oui|Oui|Oui|
|Report Message add-in and Report Phishing add-in for Outlook|Oui|Oui|Oui|
|**Flux de messagerie**||||
|Règles de flux de messagerie (règles de transport)<sup>4</sup>|Oui|Oui<sup>6</sup>|Oui|
|Domaines acceptés<sup>3</sup> |Oui|Oui|Oui|
|Connecteurs|Oui|Oui|Oui|
|Filtrage amélioré pour les connecteurs (ignorer la liste)|Oui|Oui|Oui|
|**Analyse**||||
|Message trace|Oui|Oui|Oui|
|Rapports de sécurité et de courrier électronique dans le Centre d'administration Microsoft 365|Oui<sup>7</sup>|Oui<sup>7, 8</sup>|Oui<sup>8</sup>|
|Rapports de sécurité dans le centre de Microsoft 365 de sécurité|Oui<sup>7</sup>|Oui<sup>7, 8</sup>|Oui<sup>8</sup>|
|Rapports de courrier électronique dans le EAC|Oui<sup>7</sup>|Oui<sup>7, 8</sup>|Oui<sup>8</sup>|
|Journalisation d’audit<sup>de l’administrateur 5</sup>|Oui|Oui|Oui|
|**Utilisateurs**||||
|Utilisateurs de messagerie et contacts<sup>de messagerie 1</sup>|Oui|Oui|Oui|
|Boîtes aux lettres|Non|Non|Oui<sup>1a</sup>|
|Contrôle d’accès basé sur un rôle (RBAC)<sup>2</sup>|Oui|Oui|Oui|
|**Conformité**||||
|Protection contre la perte de données pour le courrier électronique|Non|Oui|Oui|
|Chiffrement de messages Office 365|Non<sup>9</sup>|Non<sup>9</sup>|Oui|
|**Administration**||||
|Centre d’administration Microsoft 365|Oui|Oui|Oui|
|Centre d’administration Exchange|Oui|Oui|Oui|
|Centre de sécurité Microsoft 365|Oui|Oui|Oui|
|PowerShell autonome Exchange Online Protection autonome|Oui|Non|Non|
|Exchange Online PowerShell|Non|Oui|Oui|

<sup>1 Vous</sup> créez, supprimez et modifiez des utilisateurs de messagerie et des contacts de messagerie dans le EAC. <br/>
<sup>1a Vous créez</sup> et supprimez des boîtes aux lettres dans le Centre d'administration Microsoft 365. Vous pouvez modifier des boîtes aux lettres existantes dans le EAC. <br/>
<sup>2 In</sup> standalone EOP and EE CAL with Services, there are no end-user roles or role assignment policies.<br/>
<sup>3 Vous</sup> ajoutez et supprimez des domaines dans le Centre d'administration Microsoft 365.  Dans le EAC, vous configurez les domaines en tant que domaines faisant autorité ou non.<br/>
<sup>4</sup> Quelques conditions de règle, exceptions et actions ne sont pas disponibles dans EOP autonome ou EOP dans EE cal avec Services. Ces différences sont clairement notées dans Exchange Online de règle de flux de messagerie. <br/>
<sup>5</sup> In standalone EOP and EE CAL with Services:

- Les rapports d’audit de boîte aux lettres ne sont pas disponibles.
- Le rapport du groupe de rôles Administrateur et le rapport du journal d’audit de l’administrateur sont les seuls rapports d’audit de l’administrateur dans leAC.
- Exportation du journal d’audit disponible uniquement via PowerShell. <br/>

<sup>6 conseils</sup> de stratégie DLP ne sont pas disponibles dans EE cal avec Services. <br/>
<sup>7 Les</sup> rapports dans EOP autonome et EE cal avec services sont un sous-ensemble de rapports Exchange Online (rapports qui traitent des boîtes aux lettres).<br/>
<sup>8 Inclut</sup> les rapports DLP. <br/>
<sup>9</sup> Vous pouvez acheter Azure Information Protection en tant qu’abonnement de module complémentaire et utiliser OME si vous configurez votre environnement de messagerie local pour router le courrier électronique vers et depuis Internet via EOP. <br/>
<sup>10 Cette</sup> fonctionnalité nécessite l’Exchange Online boîtes aux lettres. <br/>

## <a name="learn-more"></a>Si vous souhaitez en savoir plus

Pour plus d’informations Exchange Online Protection, consultez les ressources suivantes :

La [Microsoft 365 est](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) une bonne ressource pour trouver des informations sur les nouvelles fonctionnalités à venir.

### <a name="licensing-terms"></a>Termes du contrat de licence

Pour connaître les conditions générales de licence pour les produits et services achetés par le biais des Programmes de Licences en Volume Commerciaux Microsoft, consultez le site [Conditions générales du produit](https://www.microsoft.com/licensing/terms/).

### <a name="messaging"></a>Messagerie

Pour suivre les modifications à venir, notamment les fonctionnalités nouvelles et modifiées, la maintenance planifiée ou d’autres annonces importantes, visitez le Centre de messages. Pour plus d’informations, consultez [Centre de messages](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Accessibilité

Microsoft s’engage à garantir la sécurité de vos données et l’[accessibilité](https://www.microsoft.com/trust-center/compliance/accessibility) de nos services. Pour plus d’informations, consultez le [Centre de gestion de la confidentialité Microsoft](https://www.microsoft.com/trust-center) et le [Centre d’accessibilité Office](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
