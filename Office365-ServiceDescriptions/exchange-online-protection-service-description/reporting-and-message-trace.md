---
title: Création de rapports et suivi des messages
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) offre un grand nombre de rapports qui peuvent vous aider à déterminer l'état général de votre organisation. Certains rapports sont disponibles dans le centre d’administration 365 de Microsoft, tandis que d’autres sont disponibles dans le centre d’administration Exchange.
ms.openlocfilehash: 58e1c33b331c9bb05bd45893357bba9b5cca9945
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43638941"
---
# <a name="reporting-and-message-trace"></a>Création de rapports et suivi des messages

Microsoft Exchange Online Protection (EOP) offre un grand nombre de rapports qui peuvent vous aider à déterminer l'état général de votre organisation. Certains rapports sont disponibles dans le centre d’administration 365 de Microsoft, tandis que d’autres sont disponibles dans le centre d’administration Exchange.

Vous recherchez des informations sur toutes les fonctionnalités EOP ? Consultez la rubrique [Description du service Exchange Online Protection](exchange-online-protection-service-description.md).

## <a name="microsoft-365-admin-center-reports"></a>Rapports du centre d’administration Microsoft 365

La page rapports dans le centre d’administration Microsoft 365 fournit des informations sur le trafic des messages, les détections de courrier indésirable et les programmes malveillants, ainsi que sur les messages affectés par les règles de flux de messagerie (également appelées règles de transport) ou par les stratégies de protection contre la perte de données. Les rapports améliorés pour la protection, les règles et la prévention des pertes de données (DLP) offrent une expérience interactive des rapports aux administrateurs Exchange Online Protection. Ils fournissent des données de synthèse à partir desquelles vous pouvez accéder aux détails concernant des messages individuels.

Pour plus d’informations sur ces rapports, voir [utiliser les rapports de protection du courrier électronique pour afficher les données sur les programmes malveillants, le courrier indésirable et les détections de règles](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports).

## <a name="reporting-using-web-services"></a>Création de rapports à l’aide de services web

> [!NOTE]
> De nombreuses fonctionnalités de création de rapports basées sur REST et les cmdlets associées ont été déconseillées en janvier 2018. Pour plus d’informations sur les rapports de remplacement disponibles de Microsoft Graph dans Office 365, voir les sous-rubriques relatives à l’utilisation [des rapports d’utilisation dans Microsoft Graph](https://go.microsoft.com/fwlink/p/?LinkID=865135).

Non disponible pour les clients EOP autonomes. Vous pouvez utiliser le service Web REST/OData client Reporting pour collecter des rapports de synthèse et des rapports détaillés sur les données de messagerie, et vous pouvez afficher les données sur une page Web dans un portail de gestion Web personnalisé.

## <a name="message-trace"></a>Suivi des messages

La fonctionnalité de suivi des messages dans le centre d’administration Exchange vous permet, en tant qu’administrateur, de suivre les messages électroniques lors de leur transmission via EOP. Elle vous aide à déterminer si un message électronique ciblé a été reçu, rejeté, différé ou remis par le service. Elle indique également les actions appliquées au message avant que ce dernier atteigne son état final. En obtenant des informations détaillées sur un message spécifique, vous pouvez répondre efficacement aux questions de vos utilisateurs, résoudre des problèmes de flux de messagerie, valider des modifications de stratégie et réduire la nécessité de demander de l'aide au support technique. Pour plus d’informations, consultez [la rubrique exécution d’un suivi de message et affichage des résultats dans le centre d’administration Exchange](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).

## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans, les options autonomes et les solutions locales, consultez la rubrique [Description du service de protection Exchange Online](exchange-online-protection-service-description.md).
