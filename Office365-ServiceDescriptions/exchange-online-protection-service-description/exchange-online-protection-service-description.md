---
title: Description du service Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Obtenez des informations sur les fonctionnalités d’Exchange Online Protection et la configuration requise. Une liste des plans qui fournissent Exchange Online Protection est incluse, ainsi qu’une comparaison des fonctionnalités de ces plans.
ms.openlocfilehash: 03eab6d8d6b0131579b8149fd444d049a90952d7
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173809"
---
# <a name="exchange-online-protection-service-description"></a>Description du service Exchange Online Protection

Obtenez des informations sur les fonctionnalités d’Exchange Online Protection et la configuration requise. Une liste des plans qui fournissent Exchange Online Protection est incluse, ainsi qu’une comparaison des fonctionnalités de ces plans.

Microsoft Exchange Online Protection (EOP) est un service de filtrage du courrier électronique dans le nuage, qui contribue à protéger votre organisation contre le courrier indésirable et les logiciels malveillants, ainsi que contre les violations de politique de messagerie. EOP peut simplifier la gestion de votre environnement de messagerie et alléger bon nombre des tâches liées à la maintenance du matériel et des logiciels locaux.

La liste suivante décrit les principales façons d’utiliser EOP pour la protection de la messagerie :

- **Dans** un scénario autonome : EOP fournit une protection de messagerie en nuage pour votre environnement de messagerie local (Exchange Server ou d’autres solutions de messagerie SMTP locales).

- **Dans le cadre de Microsoft Exchange Online**: Par défaut, EOP protège les boîtes aux lettres Exchange Online hébergées dans le cloud. Pour en savoir plus sur Exchange Online, consultez la [description du service Exchange Online.](../exchange-online-service-description/exchange-online-service-description.md)

- **Dans un** déploiement hybride : EOP peut être configuré pour protéger votre environnement de messagerie et contrôler le routage du courrier lorsque vous avez une combinaison de boîtes aux lettres sur site et cloud.

## <a name="available-plans"></a>Plans disponibles

Pour obtenir des informations détaillées sur les abonnements qui activent les utilisateurs pour Exchange Online Protection, consultez le tableau de comparaison [complet des abonnements.](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)

Pour acheter Exchange Online Protection, voir [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP remplace Forefront Online Protection for Exchange (FOPE). Tous les clients FOPE ont été transitionés vers EOP.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Nouveautés d'Exchange Online Protection (EOP)

La [feuille de route Microsoft 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) est une bonne ressource pour trouver des informations sur les nouvelles fonctionnalités à venir.

## <a name="exchange-online-protection-eop-plans"></a>Plans Exchange Online Protection (EOP)

EOP est disponible avec les plans d’abonnement suivants :<br><br>

| Planification | Description |
|:-----|:-----|
|[EOP autonome](https://products.office.com/exchange/exchange-email-security-spam-protection)|Service cloud distinct qui protège votre organisation de messagerie sur site.|
|[Fonctionnalités EOP dans Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|La protection intégrée pour vos boîtes aux lettres Exchange Online hébergées dans le cloud.|
|[Licence d'accès client Exchange Enterprise avec services](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Les licences de modules supplémentaires que vous achetez pour votre organisation Exchange sur site qui incluent EOP et d’autres fonctionnalités basées sur le cloud (voir la section suivante pour plus d’informations).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Fonctionnalités de la licence d’accès client Exchange Enterprise avec Services

Microsoft Exchange Enterprise CAL with Services fournit les fonctionnalités de protection de messagerie d’EOP et les fonctionnalités cloud supplémentaires suivantes :

- [Protection contre la perte de données (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Création de rapports à l'aide de services web](reporting-and-message-trace.md#reporting-using-web-services)

Pour plus d’informations sur la licence d’accès licence Exchange Enterprise avec Services, voir FAQ sur les [licences Exchange.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)

Si vous avez une licence d’accès client Exchange Enterprise avec services et que vous souhaitez configurer EOP, suivez les instructions de [l’article Configurer votre service EOP.](/microsoft-365/security/office-365-security/set-up-your-eop-service) Les étapes de configuration sont les mêmes que pour EOP autonome.

> [!NOTE]
> De nouvelles fonctionnalités pour la licence d’accès client Exchange Enterprise avec Services sont déployées en même temps qu’Exchange Online, et non EOP autonome. Les calendriers de déploiement pour EOP autonome et Exchange Online/la licence d’accès client Exchange Enterprise avec Services peuvent varier légèrement.

## <a name="requirements-for-exchange-online-protection-eop"></a>Configuration requise pour Exchange Online Protection (EOP)

EOP peut être utilisé avec n’importe quel agent de transfert de courrier SMTP, tel Microsoft Exchange Server. Pour plus d’informations sur les systèmes d’exploitation, les navigateurs web et les langues pris en charge par EOP, consultez les sections « Navigateurs pris en charge » et « Langues pris en charge » dans le Centre d’administration Exchange dans [Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="limits"></a>Limites

Pour plus d’informations sur les limites d’EOP, [consultez les limites d’Exchange Online Protection.](exchange-online-protection-limits.md)

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilité des fonctionnalités pour les différents plans Exchange Online Protection (EOP)

Chaque fonctionnalité est indiquée ci-dessous. Pour obtenir des informations plus détaillées sur les fonctionnalités EOP, cliquez sur les liens du tableau. Lorsque Exchange Online est mentionné, il s'agit généralement de la famille de services Office 365 Entreprise.<br><br>

| Fonctionnalité | EOP autonome | Fonctionnalités EOP dans Exchange Online | Licence d’accès client Exchange Enterprise avec services|
|:-----|:-----|:-----|:-----|
|[Destinataires de messages](recipient-domain-and-company-management.md#mail-recipients)|Oui<sup>1</sup>|Oui<sup>1</sup>|Oui|
|[Autorisations de groupe de rôles d'administrateur](recipient-domain-and-company-management.md#admin-role-group-permissions)|Oui<sup>2</sup>|Oui|Oui|
|[Gestion de domaines](recipient-domain-and-company-management.md#domain-management)|Oui<sup>3</sup>|Oui<sup>3</sup>|Oui<sup>3</sup>|
|[Mise en correspondance des sous-domaines](recipient-domain-and-company-management.md#match-subdomains)|Oui|Oui|Non|
|[Blocage du périmètre basé sur l'annuaire (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|Oui|Oui|Oui|
|[Règles de flux de messagerie](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|Oui<sup>4</sup>|Oui<sup>4, 6</sup>|Oui|
|[Journalisation d'audit](messaging-policy-and-compliance-servicedesc.md#audit-logging)|Oui<sup>5</sup>|Oui|Oui|
|[Protection contre la perte de données (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|Non|Oui|Oui<sup>6</sup>|
|[Chiffrement de messages Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|Oui<sup>12</sup>|Oui|Oui<sup>12</sup>|
|[Protection anti-courrier indésirable](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (intégrée)|Oui|Oui|Oui|
|[Configuration de stratégies anti-courrier indésirable](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Oui<sup>7</sup>|Oui|Oui|
|[Protection contre les programmes malveillants](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (intégrée)|Oui<sup>13</sup>|Oui|Oui|
|[Personnalisation des stratégies anti-programme malveillant](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|Oui|Oui|Oui|
|[Mise en quarantaine](anti-spam-and-anti-malware-protection-eop.md#quarantine) : gestion par l'administrateur|Oui|Oui|Oui|
|[Mise en quarantaine](anti-spam-and-anti-malware-protection-eop.md#quarantine) : autogestion par l'utilisateur final|Oui|Oui|Oui|
|[Soumission](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|Non|Oui|Non|
|[Report Message add-in for Outlook](/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|Oui|Oui|Oui|
|[Signalement de courrier indésirable dans Outlook sur le web](/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|Oui|Oui|Oui|
|[Routage du courrier électronique entre Microsoft et vos propres serveurs de messagerie](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Oui|Oui|Oui|
|[Messagerie sécurisée avec un partenaire de confiance](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Oui|Oui|Oui|
|[Saisie de l'adresse IP d'un partenaire sur une liste fiable](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Oui|Oui|Oui|
|[Routage du courrier conditionnel](mail-flow-eop.md#conditional-mail-routing)|Oui|Oui|Oui|
|[Routage du courrier hybride](mail-flow-eop.md#hybrid-mail-routing)|Oui|Oui|Oui|
|[Rapports du Centre d’administration Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Oui<sup>9</sup>|Oui<sup>10</sup>|Oui <sup>9, 10</sup>|
|[Création de rapports à l'aide de services web](reporting-and-message-trace.md#reporting-using-web-services)|Non|Oui|Oui|
|[Suivi des messages](reporting-and-message-trace.md#message-trace)|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui|
|[Accès au Centre d’administration Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Oui|Oui|Oui|
|[Accès au Centre d’administration Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center (CAE))|Oui|Oui|Oui|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Oui|Oui|Oui|

<sup>1</sup> Les utilisateurs de messagerie sont définis en tant que « Boîtes aux lettres » et, au même titre que des contacts externes, peuvent être ajoutés, supprimés et gérés directement dans le Centre d'administration Exchange (CAE). <br/>
<sup>2</sup> Aucune personnalisation RBAC. Rôles d'administrateur uniquement. <br/>
<sup>3</sup>Le CAE permet d'afficher les domaines gérés et de modifier les types de domaines. Toutes les autres gestions de domaine doivent être réalisées dans le Centre d’administration Microsoft 365.<br/>
<sup>4 Les</sup> règles de flux de messagerie (également appelées règles de transport) dans EOP sont décrites dans les règles de flux de messagerie (règles de [transport) dans Exchange Online Protection](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0). Les conditions, les exceptions et les actions de règle de flux de messagerie disponibles diffèrent légèrement entre EOP et Exchange Online. Ces différences sont notées dans les conditions de règle de flux de messagerie et les [exceptions (prédicats)](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) dans Exchange Online et les actions de règle de flux de [messagerie dans Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions).<br/>
<sup>5</sup> Les rapports d'audit EOP sont un sous-ensemble de rapports d'audit Exchange Online qui excluent les informations sur les boîtes aux lettres. <br/>
<sup>6</sup> Les conseils de stratégie DLP ne sont pas disponibles pour la licence d'accès client Exchange Enterprise avec les clients Services.  <br/>
<sup>7</sup> L'action de filtrage de contenu par défaut consiste à déplacer les messages de courrier indésirable vers le dossier Courrier indésirable des destinataires. Pour que cela fonctionne avec les boîtes aux lettres Exchange sur site, vous devez également configurer deux règles de transport dans votre organisation Exchange sur site pour détecter les en-têtes de courrier indésirable ajoutés par EOP. Pour plus d’informations, voir [Configure standalone EOP to deliver spam to the Junk Email folder in hybrid environments](/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>9</sup> Les rapports EOP sont un sous-ensemble de rapports Exchange Online qui excluent les informations sur les boîtes aux lettres.<br/>
<sup>10</sup> Comprend des rapports DLP. <br/>
<sup>12 Pris</sup> en charge pour les clients locaux qui achètent Azure Information Protection et utilisent Exchange Online Protection pour router le courrier électronique via Exchange Online. <br/>
<sup>13</sup> Analyse les messages entrants et sortants, mais pas les messages internes envoyés par un expéditeur de votre organisation à un destinataire de votre organisation. <br/>
<sup>15</sup> La configuration hybride n'est pas disponible via l'assistant de déploiement hybride, mais peut être configurée manuellement si vous disposez d'Exchange SP1.