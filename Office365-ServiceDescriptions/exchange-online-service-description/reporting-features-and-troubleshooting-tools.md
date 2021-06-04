---
title: Fonctions de rapport et outils de dépannage
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online offre une variété de fonctionnalités de rapport à la fois dans le Centre d’administration Exchange (EAC) et en dehors de celui-ci.
ms.openlocfilehash: fa80cd6c7d8e9e5f0527c478474cffe17e9204af
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652688"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Fonctions de rapport et outils de dépannage

Microsoft Exchange Online offre une variété de fonctionnalités de rapport à la fois dans le Centre d’administration Exchange (EAC) et en dehors de celui-ci.
  
## <a name="reporting-features"></a>Fonctionnalités de création de rapports

Exchange Online clients peuvent accéder aux rapports dans le Centre d’administration Microsoft 365, en téléchargeant un Excel de rapports ou à l’aide de services web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Rapports dans le Centre d’administration Microsoft 365 de gestion des rapports

La page Rapports du Centre d’administration Microsoft 365 fournit des informations récapitulatifs sur les boîtes aux lettres et les groupes. Par exemple, un rapport répertorie le nombre de groupes créés et supprimés par jour, semaine, mois ou an. Des rapports de synthèse sont aussi fournis pour les boîtes aux lettres nouvelles et supprimées, ainsi que pour les boîtes aux lettres actives et inactives. 
  
En outre, la page Rapports du Centre d’administration Microsoft 365 contient des rapports de données de messagerie, qui fournissent des informations sur le trafic des messages, les détections de courrier indésirable et de programmes malveillants, ainsi que les messages affectés par les règles de transport Exchange ou les stratégies de protection contre la perte de données (DLP). Les rapports améliorés pour la protection, les règles et la prévention des pertes de données (DLP) offrent une utilisation interactive des rapports aux administrateurs Exchange Online. Ils fournissent des données de synthèse à partir desquelles vous pouvez accéder aux détails concernant des messages individuels.
  
Pour plus d’informations sur les rapports disponibles avec chaque abonnement, voir [Rapports.](../office-365-platform-service-description/reports.md) Pour plus d’informations sur la page Rapports dans le Centre d’administration Microsoft 365, voir Afficher et télécharger des rapports sur l’utilisation des services dans [Office 365](/microsoft-365/admin/activity-reports/activity-reports) et utiliser les rapports de protection de messagerie pour afficher les données sur les programmes [malveillants,](/exchange/monitoring/use-mail-protection-reports)le courrier indésirable et les détections de règles.
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Rapports utilisant le classeur de rapports Excel

Vous pouvez également utiliser le classeur de rapports Excel 2013 pour afficher des rapports de synthèse avec des fonctionnalités de défilement. Toutefois, nous vous recommandons d’utiliser les rapports Microsoft 365 centre d’administration à la place. Le classeur de rapports Excel 2013 sera obsolète à l'avenir. Pour plus d'informations de présentation et des liens permettant de télécharger et d'installer le classeur, consultez cette [page de téléchargement](https://go.microsoft.com/fwlink/p/?LinkId=271776). Pour plus d'informations sur l'utilisation du classeur, consultez la rubrique relative aux [rapports de protection de messagerie utilisant le classeur de rapports Excel](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150)). 
  
### <a name="reporting-using-web-services"></a>Création de rapports à l’aide de services web

L’accès à des rapports récapitulatifs et détaillés sur les boîtes aux lettres, les groupes et les données de messagerie est disponible à l’aide du service web rest/OData Tenant Reporting, qui est une interface programmatique qui vous permet de créer des rapports personnalisés. Pour plus d’informations, [voir Office 365 services web de rapports.](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15))
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Fonctionnalités de reporting et outils de dépannage dans le Centre d'Administration Exchange

Le Centre d'administration Exchange propose les fonctionnalités de création de rapport et les outils de dépannage suivants.
  
### <a name="trace-an-email-message"></a>Suivre un message électronique

La fonctionnalité de suivi des messages vous permet, en tant qu’administrateur, de suivre les messages électroniques lors de leur passage par Exchange Online service. Elle vous aide à déterminer si un message électronique ciblé a été reçu, rejeté, différé ou remis par le service. Vous pouvez ainsi répondre efficacement aux questions de vos utilisateurs et résoudre les problèmes de flux de messagerie, tout en réduisant la nécessité de demander de l'aide à l'assistance technique.
  
> [!IMPORTANT]
> Dans le cadre de tendances et problèmes généraux de dépannage, utilisez les outils de reporting pour obtenir les données correspondantes. Pour des points spécifiques où les détails relatifs à un message sont requis, recourez à l'outil de suivi des messages. 
  
Pour plus d'informations sur la fonctionnalité de suivi des messages, consultez la rubrique relative au [suivi des messages électroniques](/exchange/monitoring/trace-an-email-message/trace-an-email-message).
  
### <a name="auditing-reports"></a>Rapports d'audit

Vous pouvez utiliser l'enregistrement d'audit pour résoudre des problèmes de configuration en suivant les modifications spécifiques effectuées par les administrateurs et vous aider à respecter les exigences réglementaires, de conformité et en matière de litiges. Exchange Online fournit deux types d'enregistrements d'audit :
  
- Les enregistrements d'audit d'administrateur enregistrent toute action effectuée par un administrateur. Cela peut vous aider à résoudre des problèmes de configuration ou à identifier la cause de problèmes de sécurité ou de conformité. 
    
- Enregistrement d'audit dans les boîtes enregistre chaque accès à une boîte aux lettres par quelqu'un d'autre que son propriétaire. Cela peut vous aider à identifier les personnes ayant accédé à une boîte aux lettres et ce qu'elles y ont fait. 
    
Pour plus d'informations sur la journalisation d'audit, consultez la rubrique [Rapports d'audit](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports).
  
### <a name="unified-messaging-reports"></a>Rapports de messagerie unifiée

Vous pouvez utiliser ces rapports pour surveiller et dépanner la messagerie unifiée (MU) de votre organisation Exchange Online. Pour plus d'informations, consultez la rubrique [Exécuter des rapports pour les appels vocaux](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, voir [Exchange Online description du service.](exchange-online-service-description.md)
