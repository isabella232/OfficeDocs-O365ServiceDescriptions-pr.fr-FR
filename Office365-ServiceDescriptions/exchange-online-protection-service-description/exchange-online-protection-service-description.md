---
title: Description du service de protection Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Obtenez des informations sur les fonctionnalités d’Exchange Online Protection et la configuration requise. Cet article fournit la liste des plans qui incluent Exchange Online Protection, ainsi qu’une comparaison des fonctionnalités disponibles dans ces plans.
ms.openlocfilehash: 6e7ffd6a2248acfc763a71e35ce0daba0f9b0308
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035576"
---
# <a name="exchange-online-protection-service-description"></a>Description du service de protection Exchange Online

Obtenez des informations sur les fonctionnalités d’Exchange Online Protection et la configuration requise. Cet article fournit la liste des plans qui incluent Exchange Online Protection, ainsi qu’une comparaison des fonctionnalités disponibles dans ces plans.
  
Microsoft Exchange Online Protection (EOP) est un service de filtrage du courrier électronique dans le nuage, qui contribue à protéger votre organisation contre le courrier indésirable et les logiciels malveillants, ainsi que contre les violations de politique de messagerie. EOP peut simplifier la gestion de votre environnement de messagerie et alléger bon nombre des tâches liées à la maintenance du matériel et des logiciels locaux.
  
Les principales manières d'utiliser EOP pour protéger la messagerie sont les suivantes :
  
- **Dans un scénario autonome** EOP offre une protection de messagerie en nuage pour votre environnement Exchange Server 2013 sur site, versions héritées d’Exchange Server, ou pour n’importe quel autre local solution de messagerie SMTP. 
    
- **Dans le cadre d'une installation Microsoft Exchange Online** Par défaut, EOP protège les boîtes aux lettres Exchange Online hébergées dans le nuage. Pour en savoir plus sur Exchange Online, consultez la rubrique [Description du service Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).
    
- **Dans un déploiement hybride** EOP peut être configuré pour protéger votre environnement de messagerie et contrôler le routage de messagerie quand vous disposez d'une combinaison de boîtes aux lettres locales et en nuage. 
    
Pour comparer les fonctionnalités des différents plans, voir [Comparer toutes les offres Office 365 pour les entreprises](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
Pour acheter Exchange Online Protection, voir [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Vous pouvez exporter, enregistrer et imprimer des pages dans les descriptions du service Office 365. Découvrez comment [exporter plusieurs pages](https://go.microsoft.com/fwlink/?LinkId=403349).
  
> [!IMPORTANT]
> EOP remplace Forefront Online Protection for Exchange (FOPE). Tous les clients FOPE passeront à EOP. EOP offre une protection et un contrôle identiques à ceux de FOPE, ainsi que des fonctionnalités supplémentaires. Pour plus d'informations sur la transition de FOPE vers EOP, rendez-vous sur la page relative au [centre de transition Forefront Online Protection for Exchange](http://www.movetoeop.com). 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>Nouveautés d'Exchange Online Protection (EOP)

Pour plus d'informations sur les nouvelles fonctionnalités dans EOP, consultez la rubrique [Nouveautés d'Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=320390). Pour obtenir une comparaison des fonctionnalités FOPE et EOP, consultez la rubrique [Comparaison des fonctions EOP et FOPE](https://go.microsoft.com/fwlink/p/?LinkId=320391).
  
## <a name="exchange-online-protection-eop-plans"></a>Plans Exchange Online Protection (EOP)

EOP est disponible avec les plans d'abonnement suivants :
  
|**Planifier**|**Description**|
|:-----|:-----|
|[EOP autonome](https://go.microsoft.com/fwlink/p/?LinkId=294201) <br/> |Où EOP protège vos boîtes aux lettres locales.  <br/> |
|[Fonctionnalités EOP dans Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=294197) <br/> |Où EOP protège vos boîtes aux lettres hébergées sur le nuage Exchange Online.  <br/> |
|[Licence d'accès client Exchange Enterprise avec Services](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |Où EOP protège vos boîtes aux lettres locales, comme EOP autonome, et inclut des services de protection contre la perte de données (DLP) et de génération de rapports à l'aide de services web.  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>Fonctionnalités de la licence d'accès client Exchange Enterprise avec Services

La licence d'accès client Microsoft Exchange Enterprise avec Services offre les mêmes fonctionnalités de protection du courrier électronique qu'EOP pour votre environnement de messagerie local, ainsi que les fonctionnalités suivantes :
  
- [Protection contre la perte de données (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [Création de rapports à l'aide de services web](reporting-and-message-trace.md#reporting-using-web-services)
    
Pour plus d'informations sur la licence d'accès client Exchange Enterprise avec Services, consultez la rubrique [Licences d'Exchange Server 2013](https://go.microsoft.com/fwlink/p/?LinkId=293699).
  
Si vous avez une licence d'accès client Exchange Enterprise avec Services et que vous souhaitez configurer le service, suivez les instructions de [configuration de votre service EOP](https://go.microsoft.com/fwlink/p/?LinkId=320397). Les étapes de configuration sont les mêmes que pour EOP autonome.
  
> [!NOTE]
> De nouvelles fonctionnalités pour la licence d’accès client Exchange Enterprise avec Services sont déployées en même temps qu’Exchange Online, et non EOP autonome. Les calendriers de déploiement pour EOP autonome et Exchange Online/la licence d’accès client Exchange Enterprise avec Services peuvent varier légèrement. 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>Configuration requise pour Exchange Online Protection (EOP)

EOP peut être utilisé avec n'importe quel agent de transfert de courrier SMTP, tel que Microsoft Exchange Server 2013. Pour plus d'informations sur les systèmes d'exploitation, les navigateurs web et les langues pris en charge par EOP, consultez les sections « Navigateurs pris en charge » et « Langues prises en charge » dans [Centre d'administration Exchange dans Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="limits"></a>Limites

Pour connaître les limites dans EOP, consultez la rubrique [Limites d'Exchange Online Protection](exchange-online-protection-limits.md).
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilité des fonctionnalités pour les différents plans Exchange Online Protection (EOP)

Chaque fonctionnalité est indiquée ci-dessous. Pour obtenir des informations plus détaillées sur les fonctionnalités EOP, cliquez sur les liens du tableau. Lorsque Exchange Online est mentionné, il s'agit généralement de la famille de services Office 365 Entreprise.
  
|||||
|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**EOP autonome** <br/> |**Fonctionnalités EOP dans Exchange Online** <br/> |**Licence d'accès client Exchange Enterprise avec services** <br/> |
|[Destinataires de messages](recipient-domain-and-company-management.md#mail-recipients) <br/> |Oui<sup>1</sup> <br/> |Oui<sup>1</sup> <br/> |Oui  <br/> |
|[Autorisations de groupe de rôles d'administrateur](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |Oui<sup>2</sup> <br/> |Oui  <br/> |Oui  <br/> |
|[Gestion de domaines](recipient-domain-and-company-management.md#domain-management) <br/> |Oui<sup>3</sup> <br/> |Oui<sup>3</sup> <br/> |Oui<sup>3</sup> <br/> |
|[Mise en correspondance des sous-domaines](recipient-domain-and-company-management.md#match-subdomains) <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|[Blocage du périmètre basé sur l'annuaire (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Règles de transport](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |Oui<sup>3, 4, 14</sup> <br/> |Oui<sup>3, 4, 14</sup> <br/> |Oui  <br/> |
|[Journalisation d'audit](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |Oui<sup>5</sup> <br/> |Oui  <br/> |Oui  <br/> |
|[Protection contre la perte de données (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |Non  <br/> |Oui  <br/> |Oui<sup>6</sup> <br/> |
|[Chiffrement de messages Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |Oui<sup>12</sup> <br/> |Oui  <br/> |Oui<sup>12</sup> <br/> |
|[Protection anti-courrier indésirable](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (intégrée)  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Configuration de stratégies anti-courrier indésirable](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |Oui<sup>7</sup> <br/> |Oui  <br/> |Oui  <br/> |
|[Protection contre les programmes malveillants](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (intégrée)  <br/> |Oui<sup>13</sup> <br/> |Oui  <br/> |Oui  <br/> |
|[Personnalisation des stratégies anti-programme malveillant](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Mise en quarantaine](anti-spam-and-anti-malware-protection-eop.md#quarantine) : gestion par l'administrateur  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Mise en quarantaine](anti-spam-and-anti-malware-protection-eop.md#quarantine) : autogestion par l'utilisateur final  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Complément Junk Email Reporting pour Microsoft Office Outlook](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Junk Email Reporting dans Outlook Web App](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |Oui<sup>8</sup> <br/> |Aucun<sup>8</sup> <br/> |Aucun<sup>8</sup> <br/> |
|[Routage des courriers électroniques entre vos serveurs de messagerie et Office 365](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Messagerie sécurisée avec un partenaire de confiance](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Saisie de l'adresse IP d'un partenaire sur une liste fiable](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Routage du courrier conditionnel](mail-flow-eop.md#conditional-mail-routing) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Routage du courrier hybride](mail-flow-eop.md#hybrid-mail-routing) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Rapports du Centre d'administration Office 365](reporting-and-message-trace.md#office-365-admin-center-reports) <br/> |Oui<sup>9</sup> <br/> |Oui<sup>10</sup> <br/> |Oui <sup>9, 10</sup> <br/> |
|[Rapports d'application de téléchargement Excel](reporting-and-message-trace.md#excel-download-application-reports) <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>11</sup> <br/> |
|[Création de rapports à l'aide de services web](reporting-and-message-trace.md#reporting-using-web-services) <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |
|[Suivi des messages](reporting-and-message-trace.md#message-trace) <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui  <br/> |
|[Accès au Centre d'administration Office 365](administration-and-management-eop.md#access-to-the-office-365-admin-center) <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Accès au Centre d'administration Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center) (CAE)  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|[Accès à distance à Windows PowerShell](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |Oui<sup>2</sup> <br/> |Oui  <br/> |Oui  <br/> |
   
> [!NOTE]
> <sup>1</sup> messagerie utilisateurs sont définis en tant que « Boîtes aux lettres » et, ainsi que des contacts de messagerie externes, peuvent être ajoutés, supprimés et gérés directement dans le centre d’administration Exchange (CAE). <br/>Personnalisation de RBAC N° <sup>2</sup> . Rôles d’administrateur uniquement. <br/> <sup>3</sup> domaines gérés peuvent être affichés et types de domaine peuvent être modifiées dans le CAE. Toutes les autres tâches de gestion de domaine doit être effectuée dans le centre d’administration d’Office 365. <br/><sup>4</sup> les critères flexibles disponibles et les actions diffèrent EOP et Exchange Online. Pour obtenir la liste des critères disponibles et les actions dans EOP, voir [Critères de règle de Transport](https://go.microsoft.com/fwlink/p/?LinkId=320392) et de [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393). Pour obtenir la liste des critères disponibles et les actions dans Exchange Online, voir [Critères de règle de Transport](https://go.microsoft.com/fwlink/p/?LinkId=320394) et de [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395). <br/><sup>5</sup> des rapports d’audit EOP sont un sous-ensemble de rapports d’audit Exchange Online qui excluent les informations sur les boîtes aux lettres. <br/> <sup>6</sup> Les conseils de stratégie DLP ne sont pas disponibles pour la licence d'accès client Exchange Enterprise avec les clients Services.<br/><sup>7</sup> l’action de filtrage de contenu par défaut consiste à déplacer des messages indésirables vers le dossier courrier indésirable de destinataires. Pour fonctionner avec des boîtes aux lettres locales, vous devez également configurer les deux règles de Transport Exchange sur vos serveurs sur site pour détecter les en-têtes de spam ajoutés par EOP. Pour plus d’informations, voir [vérifier que le courrier indésirable est routé vers le dossier de courrier indésirable de chaque utilisateur](https://go.microsoft.com/fwlink/p/?LinkId=320396). <br/><sup>8</sup> cette fonctionnalité est disponible pour les clients Exchange Server 2013 Service Pack 1 (SP1) dont les boîtes aux lettres sont filtrées par EOP et seront bientôt disponible pour les clients Exchange Online. <br/><sup>9</sup> les rapports EOP sont un sous-ensemble de rapports Exchange Online qui excluent les informations sur les boîtes aux lettres. <br/>Les rapports DLP inclut <sup>10</sup> . <br/><sup>11</sup> Exchange Enterprise CAL avec les clients Services doivent installer le classeur en sélectionnant le service **Exchange Online** plutôt que le service **Exchange Online Protection** . <br/><sup>12</sup> prises en charge pour les clients sur site qui achètent de Protection des informations Azure et utiliser Exchange Online Protection pour router le courrier électronique via Exchange Online. <br/> <sup>13</sup> analyse les messages entrants et sortants, mais n’analyse pas les messages internes envoyés par un expéditeur de votre organisation à un destinataire dans votre organisation. <br/><sup>14</sup> les prédicats disponibles et les actions diffèrent EOP et Exchange Online. <br/> <sup>15</sup> La configuration hybride n'est pas disponible via l'assistant de déploiement hybride, mais peut être configurée manuellement si vous disposez d'Exchange SP1. 