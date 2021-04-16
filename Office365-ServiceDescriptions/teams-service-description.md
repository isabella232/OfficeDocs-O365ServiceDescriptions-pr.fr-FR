---
title: Description du service Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Découvrez la disponibilité des fonctionnalités et des services Microsoft Teams dans les plans Microsoft 365 et Office 365.
ms.openlocfilehash: 8828199a8af848dcd2bf6945b111e0fd082c7a95
ms.sourcegitcommit: c3cdb8074129fd7dff942a10a4fe8604fca563b6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/14/2021
ms.locfileid: "51767454"
---
# <a name="microsoft-teams-service-description"></a>Description du service Microsoft Teams

Microsoft Teams est le hub pour le travail d'équipe dans Microsoft 365. Le service Teams permet la messagerie instantanée, les appels audio et vidéo, les réunions en ligne enrichies, les expériences mobiles et les fonctionnalités de conférence web étendues. En outre, Teams fournit des fonctionnalités de collaboration et d'extensibilité de fichiers et de données, et s'intègre à Microsoft 365 et à d'autres applications Microsoft et partenaires.

Skype Entreprise Online se retire le 31 juillet 2021, qui a été annoncé le 30 juillet 2019. [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) Microsoft Teams est un service entièrement nouveau, conçu pour le cloud depuis le début en tirant parti d'Azure et d'autres innovations de service de Microsoft. Microsoft Teams repose sur les groupes Microsoft 365, Microsoft Graph et avec les mêmes niveaux de sécurité, de conformité et de gestion que le reste d'Office 365. Teams tire parti des identités stockées dans Azure Active Directory (Azure AD). Ces services sont livrés à partir de centres de données Microsoft et sont accessibles aux utilisateurs sur un large éventail d'appareils depuis l'intérieur d'un réseau d'entreprise ou sur Internet. Pour plus d'informations, voir les affiches sur l'architecture et les solutions téléphoniques de [Microsoft Teams.](/microsoftteams/teams-architecture-solutions-posters)

Cette description de service détaille les principales différences entre les services fournis dans les différentes installations cloud. Les fonctionnalités principales de Microsoft Teams ne diffèrent pas d'un abonnement à l'autre. La disponibilité des fonctionnalités de conformité dépend du niveau d'abonnement. Pour en savoir plus sur la sécurité et la conformité de Teams, voir [Sécurité et conformité dans Microsoft Teams.](/microsoftteams/security-compliance-overview)

Si les utilisateurs ont été migrés entièrement en ligne, ils doivent avoir à la fois des équipes et des licences Skype Entreprise Online pour une fonctionnalité Teams complète, même si Skype Entreprise Online ne sera pas utilisé.

## <a name="available-plans"></a>Plans disponibles

Pour obtenir des informations détaillées sur les abonnements qui activent Teams pour les utilisateurs, consultez Rechercher [microsoft teams pour votre entreprise.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options) Vous pouvez trouver des détails supplémentaires dans le tableau [de comparaison des solutions Microsoft.](https://go.microsoft.com/fwlink/?linkid=2139145)

Les plans pour le gouvernement qui supportent Teams incluent Office 365 G1 à G5. Pour plus d'informations, [consultez les plans Office 365 pour le gouvernement.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans)

Tous les plans d'abonnement pris en charge sont éligibles pour l'accès au client web Microsoft Teams, aux clients de bureau et aux applications mobiles.

Microsoft Teams n'est pas disponible en tant que service autonome.

## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Le tableau suivant répertorie les principales fonctionnalités de Teams disponibles dans les différents plans. Certaines mises en garde s'appliquent. Pour plus d'informations, voir les notes de bas de page. Ce tableau peut changer sans préavis.

Pour en savoir plus sur les fonctionnalités Teams par plateforme de système d'exploitation, consultez [les fonctionnalités Teams par plateforme.](https://aka.ms/teamsfeaturesbyplatform)

Pour obtenir la liste complète des fonctionnalités Teams les plus à jour dans les plans Microsoft 365 et Office 365, consultez La liste complète des fonctionnalités Microsoft Teams pour votre [entreprise.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)<br><br>

| Fonctionnalité | Plans pour les petites entreprises | Plans d'entreprise | GCC | GCC - Élevé | DOD | Plans d'enseignement |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Conversation  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Teams  <br/> |Oui <br/> |Oui <br/> |Oui <br/> |Oui<sup>1</sup>  <br/> |Oui<sup>1</sup>  <br/> |Oui  <br/> |
|Canaux - Standard  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Canaux - Privé  <br/> |Oui  <br/> |Oui<sup>2</sup>  <br/> |Oui <br/> |Non  <br/> |Non <br/> |Oui  <br/> |
|Réunions  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Partage d'écran PowerPoint Audio/Vidéo De bureau <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Appels vocaux  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>3</sup>  <br/> |Oui<sup>3</sup>  <br/> |Oui  <br/> |
|Audioconférence  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>3</sup>  <br/> |Oui<sup>3</sup>  <br/> |Oui  <br/> |
|Applications, bots & connecteurs  <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>4</sup>  <br/> |Oui<sup>4</sup>  <br/> |Oui<sup>4</sup>  <br/> |Oui  <br/> |
|Événements en direct  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non<sup>5</sup>  <br/> |Non<sup>5</sup>  <br/> |Oui  <br/> |

<sup>1</sup> Microsoft Teams dans GCC-High et DOD supportent 2 500 membres dans une équipe individuelle.<br/>
<sup>2</sup> Le Planificateur Microsoft n'est pas disponible actuellement pour accéder aux canaux privés.<br/>
<sup>3 Le</sup> routage direct doit être configuré pour que l'audioconférence et la voix Microsoft Teams fonctionnent dans GCCH et DoD.<br/>
<sup>4</sup> Les applications tierces et la publication d'applications ne sont pas disponibles dans ces clouds pour le moment.<br/>
<sup>5</sup> Événements en direct n'est pas disponible GCC-High ou DOD pour le moment.<br/>

### <a name="cloud-voice-features"></a>Fonctionnalités vocales cloud

Pour l'audioconférence, votre organisation doit acheter et attribuer une licence d'audioconférence à chaque utilisateur qui définit des réunions rendez-vous. Pour les fonctionnalités Teams qui nécessitent des forfaits d'appels, chaque utilisateur a besoin d'un système téléphonique et d'un plan d'appels nationaux ou nationaux et internationaux. Pour en savoir plus, [consultez les licences de modules de développement microsoft Teams.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

### <a name="live-events"></a>Événements en direct

Cette offre dans Office 365 remplace la diffusion de réunion Skype retirée. Les fonctionnalités d'événements en direct sont disponibles pour les plans de gestion des licences, comme détaillé dans le service Stream. Pour plus d'informations, examinez la vue [d'ensemble des licences Microsoft Stream.](/stream/license-overview) Le service d'événements en direct est accessible via Stream, Yammer ou Microsoft Teams. Pour en savoir plus sur les fonctionnalités des événements en direct, consultez les événements en direct dans [Microsoft 365 dans Yammer, Microsoft Teams et Microsoft Stream.](/stream/live-event-m365)

## <a name="learn-more"></a>En savoir plus

Pour plus d'informations sur Teams, consultez les ressources suivantes :
 
- [Documentation pour les administrateurs Microsoft Teams](/MicrosoftTeams)
- [Communauté technique Microsoft Teams](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Blog Microsoft Teams](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Termes du contrat de licence

Pour obtenir les termes et conditions de licence des produits et services achetés via les programmes de licence en volume commerciaux Microsoft, consultez le [site Termes du produit.](https://www.microsoft.com/licensing/terms/) 

### <a name="messaging"></a>Messagerie 

Pour rester informé des modifications à venir, y compris des fonctionnalités nouvelles et modifiées, de la maintenance planifiée ou d'autres annonces importantes, visitez le Centre de messages. Pour plus d'informations, voir [Centre de messages.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>Accessibilité

Microsoft s'engage à assurer la sécurité de vos données et l'accessibilité de nos services. Pour plus d'informations, voir le [Centre de confiance Microsoft](https://www.microsoft.com/trust-center) et le Centre [d'accessibilité Office.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
