---
title: Fonctions de rapport et outils de dépannage
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online offre un large éventail de fonctionnalités de création de rapports dans et en dehors du centre d’administration Exchange.
ms.openlocfilehash: 2926a667e6a886f128de4234e7dfc911b486c474
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776865"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Fonctions de rapport et outils de dépannage

Microsoft Exchange Online offre un large éventail de fonctionnalités de création de rapports dans et en dehors du centre d’administration Exchange.
  
## <a name="reporting-features"></a>Fonctionnalités de reporting

Les clients Exchange Online peuvent accéder aux rapports dans le centre d’administration Microsoft 365, en téléchargeant un classeur de rapports Excel ou en utilisant des services Web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Création de rapports dans le centre d’administration Microsoft 365

Il existe des rapports sur la page rapports dans le centre d’administration Microsoft 365 qui fournissent des informations récapitulatives sur les boîtes aux lettres et les groupes. Par exemple, un rapport répertorie le nombre de groupes créés et supprimés par jour, semaine, mois ou an. Des rapports de synthèse sont aussi fournis pour les boîtes aux lettres nouvelles et supprimées, ainsi que pour les boîtes aux lettres actives et inactives. 
  
En outre, la page rapports du centre d’administration Microsoft 365 contient des rapports de données de messagerie, qui fournissent des informations sur le trafic des messages, les détections de courrier indésirable et les programmes malveillants et les messages affectés par les règles de transport Exchange ou la protection contre la perte de données (DLP). règles. Les rapports améliorés pour la protection, les règles et la prévention des pertes de données (DLP) offrent une utilisation interactive des rapports aux administrateurs Exchange Online. Ils fournissent des données de synthèse à partir desquelles vous pouvez accéder aux détails concernant des messages individuels.
  
Pour plus d'informations sur les rapports qui sont disponibles avec chaque abonnement Office 365, consultez la rubrique [Rapports](../office-365-platform-service-description/reports.md). Pour plus d’informations sur la page rapports dans le centre d’administration 365 de Microsoft, consultez la rubrique [afficher et télécharger des rapports sur l’utilisation des services dans office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) et [utiliser les rapports de protection du courrier électronique dans Office 365 pour afficher les données sur les programmes malveillants, le courrier indésirable et les détections de règles. ](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Rapports utilisant le classeur de rapports Excel

Vous pouvez également utiliser le classeur de rapports Excel 2013 pour afficher des rapports de synthèse avec des fonctionnalités de défilement. Toutefois, nous vous recommandons d’utiliser à la place les rapports améliorés du centre d’administration 365 Microsoft. Le classeur de rapports Excel 2013 sera obsolète à l'avenir. Pour plus d'informations de présentation et des liens permettant de télécharger et d'installer le classeur, consultez cette [page de téléchargement](https://go.microsoft.com/fwlink/p/?LinkId=271776). Pour plus d'informations sur l'utilisation du classeur, consultez la rubrique relative aux [rapports de protection de messagerie utilisant le classeur de rapports Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Reporting via les services Web

Accédez à la fois à des rapports récapitulatifs et à des rapports détaillés sur les boîtes aux lettres, les groupes et les données de messagerie en utilisant le service Web de reporting de client REST/OData, qui est une interface de programmation vous permettant de créer des rapports personnalisés. Pour plus d'informations, consultez la rubrique relative aux [services web de création de rapports Office 365](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Fonctionnalités de reporting et outils de dépannage dans le Centre d'Administration Exchange

Le Centre d'administration Exchange propose les fonctionnalités de création de rapport et les outils de dépannage suivants.
  
### <a name="trace-an-email-message"></a>Suivre un message électronique

La fonctionnalité de suivi des messages vous permet, en tant qu'administrateur, de suivre des messages électroniques lorsqu'ils sont acheminés via votre service Exchange Online. Elle vous aide à déterminer si un message électronique ciblé a été reçu, rejeté, différé ou remis par le service. Vous pouvez ainsi répondre efficacement aux questions de vos utilisateurs et résoudre les problèmes de flux de messagerie, tout en réduisant la nécessité de demander de l'aide à l'assistance technique.
  
> [!IMPORTANT]
> Dans le cadre de tendances et problèmes généraux de dépannage, utilisez les outils de reporting pour obtenir les données correspondantes. Pour des points spécifiques où les détails relatifs à un message sont requis, recourez à l'outil de suivi des messages. 
  
Pour plus d'informations sur la fonctionnalité de suivi des messages, consultez la rubrique relative au [suivi des messages électroniques](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Rapports d'audit

Vous pouvez utiliser l'enregistrement d'audit pour résoudre des problèmes de configuration en suivant les modifications spécifiques effectuées par les administrateurs et vous aider à respecter les exigences réglementaires, de conformité et en matière de litiges. Exchange Online fournit deux types d'enregistrements d'audit :
  
- Les enregistrements d'audit d'administrateur enregistrent toute action effectuée par un administrateur. Cela peut vous aider à résoudre des problèmes de configuration ou à identifier la cause de problèmes de sécurité ou de conformité. 
    
- Enregistrement d'audit dans les boîtes enregistre chaque accès à une boîte aux lettres par quelqu'un d'autre que son propriétaire. Cela peut vous aider à identifier les personnes ayant accédé à une boîte aux lettres et ce qu'elles y ont fait. 
    
Pour plus d'informations sur la journalisation d'audit, consultez la rubrique [Rapports d'audit](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Rapports de messagerie unifiée

Vous pouvez utiliser ces rapports pour surveiller et dépanner la messagerie unifiée (MU) de votre organisation Exchange Online. Pour plus d'informations, consultez la rubrique [Exécuter des rapports pour les appels vocaux](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).
  

