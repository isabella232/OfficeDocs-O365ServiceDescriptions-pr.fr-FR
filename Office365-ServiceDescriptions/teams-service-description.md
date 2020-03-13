---
title: Description du service Microsoft teams
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Microsoft teams offre des fonctionnalités de messagerie instantanée, de collaboration de fichiers et de données, d’appels audio et vidéo, de réunions en ligne enrichies, d’expériences mobiles et de fonctionnalités de conférence Web étendues.
ms.openlocfilehash: cd16f511c5bd0af7c8e64cf4efd383ca48f74b30
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/12/2020
ms.locfileid: "42609985"
---
# <a name="microsoft-teams-service-description"></a>Description du service Microsoft teams

Microsoft teams est le Hub pour le travail d’équipe dans Microsoft 365. Le service teams permet des fonctions de messagerie instantanée, d’appels audio et vidéo, de réunions en ligne enrichies, d’expériences mobiles et de fonctionnalités de conférence Web étendues. En outre, teams offre des fonctionnalités de collaboration et de fichier de données et d’extensibilité, et s’intègre à Microsoft 365 et à d’autres applications Microsoft et partenaires.

Skype entreprise Online sera retiré le 31 juillet 2021, [annoncé](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) le 30 juillet 2019... Microsoft teams est un service entièrement nouveau, conçu pour le nuage dès le départ en tirant parti d’Azure et d’autres innovations de service de Microsoft. Microsoft teams est basé sur les groupes Office 365, Microsoft Graph et les mêmes sécurité, conformité et gestion au niveau de l’entreprise que le reste d’Office 365. Teams exploite les identités stockées dans Azure Active Directory (Azure AD). Ces services sont fournis par les centres de données Microsoft et sont accessibles aux utilisateurs sur un large éventail d’appareils à l’intérieur d’un réseau d’entreprise ou sur Internet. Pour plus d’informations, reportez-vous à l' [architecture teams et aux diagrammes de solutions de téléphonie](https://docs.microsoft.com/microsoftteams/teams-architecture-solutions-posters).

Microsoft conserve la sécurité de vos données et l' [accessibilité](https://www.microsoft.com/trust-center/compliance/accessibility) de nos services. Pour plus d’informations, consultez le centre de gestion de la [confidentialité Microsoft](https://www.microsoft.com/trust-center) et le [Centre d’accessibilité Office](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).

Pour référence, nous avons inclus cette table principale des abonnements Office 365 qui permettent aux utilisateurs de Microsoft Teams. Pour plus d’informations, consultez la rubrique [Office 365 Licensing for Microsoft teams](https://docs.microsoft.com/microsoftteams/office-365-licensing). Pour plus d’Office 365 dans les plans gouvernementaux, consultez la rubrique [office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans). Office 365 G1 via G5 incluent l’accès aux fonctionnalités de teams.

|||||
|:-----|:-----|:-----|:-----|
|**Offres pour les petites entreprises** <br/> |**Plans d’entreprise** <br/> |**Plans d’éducation** <br/> |**Plans de développement** <br/> |
|Office 365 Business Essentials  <br/> |Office 365 Entreprise E1  <br/> |Office 365 Éducation  <br/> |Développeur Office 365  <br/> |
|Office 365 Business Premium  <br/> |Office 365 Entreprise E3  <br/> |Office 365 Éducation Plus  <br/> |   <br/> |
|Microsoft 365 pour les entreprises  <br/> |Office 365 entreprise E4 (obsolète)  <br/> |Office 365 éducation E3 (retiré)  <br/> |  <br/> |
|  <br/> |Office 365 Entreprise E5  <br/> |Office 365 Éducation E5  <br/> |  <br/> |
|  <br/> |Office 365 Entreprise F1  <br/> |  <br/> |  <br/> |

Pour obtenir des conseils détaillés sur l’implémentation des fonctionnalités du produit, consultez la [documentation d’administration de Microsoft teams](https://docs.microsoft.com/MicrosoftTeams). Cette description de service décrit les principales différences entre les services fournis dans les différentes installations Cloud. Les fonctionnalités principales de Microsoft Teams ne diffèrent pas des abonnements Office 365. La disponibilité des fonctionnalités de conformité dépend de votre niveau d’abonnement. Pour en savoir plus, consultez [la rubrique sécurité et conformité dans Microsoft teams](https://docs.microsoft.com/microsoftteams/security-compliance-overview). Pour obtenir la liste détaillée des fonctionnalités disponibles dans chaque abonnement, voir la [Description du service de plateforme Office 365](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-platform-service-description).

**Fonctionnalités vocales Cloud**: pour l’audioconférence, votre organisation doit acheter et attribuer une licence d’audioconférence à chaque utilisateur qui configurera des réunions de rendez-vous. Pour les fonctionnalités de teams qui requièrent des forfaits d’appels, chaque utilisateur doit disposer d’un système téléphonique et d’un forfait d’appels nationaux ou internationaux. Pour en savoir plus, consultez la rubrique [licences de module complémentaire Microsoft teams](https://docs.microsoft.com/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing).

**Événements en direct**: cette offre dans Office 365 remplace la diffusion de réunion Skype obsolète. Les fonctionnalités des événements en direct sont disponibles pour les plans de gestion des licences, comme indiqué dans le service de flux. Consultez les informations relatives à la [licence ici](https://docs.microsoft.com/stream/license-overview). Le service d’événements en direct est accessible via Stream, Yammer ou Microsoft Teams. Pour en savoir plus sur les fonctionnalités d’événement en direct, consultez la rubrique [événements en direct dans microsoft 365 dans Yammer, Microsoft teams et Microsoft Stream](https://docs.microsoft.com/stream/live-event-m365).

Tous les plans d’abonnement pris en charge sont éligibles pour l’accès au client Web Microsoft Teams, aux clients de bureau et aux applications mobiles.

Microsoft teams n’est pas disponible en tant que service autonome.

## <a name="feature-category-reference"></a>Référence de catégorie de fonctionnalité 

Ce tableau répertorie la disponibilité des fonctionnalités Microsoft teams dans les plans de gestion des licences ou les instances de Cloud. Certaines restrictions s’appliquent. Pour plus d’informations, consultez les notes de bas de page. Cette table peut être modifiée sans préavis. Reportez-vous à Microsoft 365 message Center notifications for Core service change Messaging et à la [documentation de référence des termes du contrat de licence Microsoft](https://www.microsoft.com/licensing/product-licensing/products).

|||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
| <br/>|**Petite entreprise** <br/> |**Plans d’entreprise** <br/> |**GCC** <br/> |**GCC-High** <br/> |**DOD** <br/> |**Enseignement** <br/> |
|Conversation  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Équipes  <br/> |Oui <br/> |Oui <br/> |Oui <br/> |Oui<sup>1</sup>  <br/> |Oui<sup>1</sup>  <br/> |Oui  <br/> |
|Canaux-standard  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Canaux-privés  <br/> |Oui  <br/> |Oui<sup>2</sup>  <br/> |N °<sup>3</sup>  <br/> |N °<sup>3</sup>  <br/> |N °<sup>3</sup>  <br/> |Oui  <br/> |
|Réunions  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Partage d’écran de bureau audio/vidéo PowerPoint <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Appels vocaux  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Audioconférence  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Applications, robots, connecteurs &  <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>4</sup>  <br/> |Oui<sup>4</sup>  <br/> |Oui<sup>4</sup>  <br/> |Oui  <br/> |
|Événements en direct  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |N °<sup>5</sup>  <br/> |N °<sup>5</sup>  <br/> |Oui  <br/> |

<sup>1</sup> Microsoft teams de GCC-High et DoD prennent en charge 2500 membres d’une équipe individuelle.<br/>
<sup>2</sup> le planificateur Microsoft n’est pas disponible actuellement pour accéder aux canaux privés.<br/>
<sup>3</sup> les canaux privés ne sont pas disponibles dans les nuages GCC pour le moment. D’autres mises à jour relatives à la disponibilité seront publiées dans le centre de messages.<br/>
<sup>4</sup> Microsoft OneNote n’est pas disponible dans DOD Clouds. Pour le moment, les applications et la publication d’application ne sont pas disponibles dans ces nuages.<br/>
<sup>5</sup> les événements en direct ne sont pas disponibles dans GCC-High ou DoD pour le moment.<br/>

## <a name="next-steps"></a>Étapes suivantes

Commencez à planifier votre déploiement de Microsoft teams en visitant la [documentation technique de Microsoft teams](https://aka.ms/SuccessWithTeams). Restez à jour sur les fonctionnalités et les fonctionnalités de teams en [rejoignant notre communauté et en visitant notre blog Microsoft teams](https://aka.ms/TeamsBlog).