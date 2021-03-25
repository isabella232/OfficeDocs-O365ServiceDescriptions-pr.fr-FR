---
title: Création de rapports et suivi des messages dans Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Lisez cet article pour en savoir plus sur la reporting et le suivi des messages dans Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: e07b7b9f6f7bee2715314021d9a7e96a29af8b21
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173329"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Création de rapports et suivi des messages dans Exchange Online Protection

Microsoft Exchange Online Protection (EOP) offre un grand nombre de rapports qui peuvent vous aider à déterminer l'état général de votre organisation. Certains rapports sont disponibles dans le Centre d’administration Microsoft 365, tandis que d’autres sont disponibles dans le Centre d’administration Exchange (EAC).

Vous recherchez des informations sur toutes les fonctionnalités EOP ? Consultez la [description du service Exchange Online Protection.](exchange-online-protection-service-description.md)

## <a name="microsoft-365-admin-center-reports"></a>Rapports du Centre d’administration Microsoft 365

La page Rapports du Centre d’administration Microsoft 365 fournit des informations sur le trafic de messages, les détections de courrier indésirable et de programmes malveillants, ainsi que les messages affectés par les règles de flux de messagerie (également appelées règles de transport) ou les stratégies de protection contre la perte de données (DLP). Les rapports améliorés pour la protection, les règles et la prévention des pertes de données (DLP) offrent une expérience interactive des rapports aux administrateurs Exchange Online Protection. Ils fournissent des données de synthèse à partir desquelles vous pouvez accéder aux détails concernant des messages individuels.

Pour plus d’informations sur ces rapports, voir Utiliser les rapports de protection de messagerie pour afficher des données sur les programmes malveillants, le courrier indésirable et les [détections de règles.](/exchange/monitoring/use-mail-protection-reports)

## <a name="reporting-using-web-services"></a>Création de rapports à l’aide de services web

> [!NOTE]
> De nombreuses fonctionnalités de rapport basées sur REST et les cmdlets associées ont été supprimés en janvier 2018. Pour plus d’informations sur les rapports Microsoft Graph de remplacement disponibles dans Office 365, voir les sous-ressources de l’utilisation des rapports [dans Microsoft Graph.](/graph/api/resources/report)

Non disponible pour les clients EOP autonomes. Vous pouvez utiliser le service web rest/OData Tenant Reporting pour collecter par programme des rapports récapitulatifs et détaillés sur les données de messagerie, et vous pouvez afficher les données sur une page web dans un portail de gestion web personnalisé.

## <a name="message-trace"></a>Suivi des messages

La fonctionnalité de suivi des messages dans le CAE vous permet, en tant qu’administrateur, de suivre les messages électroniques quand ils passent par EOP. Elle vous aide à déterminer si un message électronique ciblé a été reçu, rejeté, différé ou remis par le service. Elle indique également les actions appliquées au message avant que ce dernier atteigne son état final. En obtenant des informations détaillées sur un message spécifique, vous pouvez répondre efficacement aux questions de vos utilisateurs, résoudre des problèmes de flux de messagerie, valider des modifications de stratégie et réduire la nécessité de demander de l'aide au support technique. Pour plus d’informations, [voir Exécuter un suivi des messages et afficher les résultats dans le Centre d’administration Exchange.](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)

## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités entre les plans, les options autonomes et les solutions sur site, consultez la description du [service Exchange Online Protection.](exchange-online-protection-service-description.md)