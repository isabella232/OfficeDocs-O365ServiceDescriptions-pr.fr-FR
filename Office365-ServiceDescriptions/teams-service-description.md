---
title: Description du service Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: En savoir plus sur Microsoft Teams la disponibilité des services et des fonctionnalités dans Microsoft 365 et Office 365 plans.
ms.openlocfilehash: 721c4bd99fd8f81e471ea79e6725c2d6c53d1791
ms.sourcegitcommit: c455501e86037b0f86e0afc9d6d6d04afdfd3442
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/28/2021
ms.locfileid: "52074485"
---
# <a name="microsoft-teams-service-description"></a>Description du service Microsoft Teams

Microsoft Teams est le hub pour le travail d’équipe dans Microsoft 365. Le service Teams permet la messagerie instantanée, les appels audio et vidéo, les réunions en ligne enrichies, les expériences mobiles et les fonctionnalités de conférence web étendues. En outre, Teams fournit des fonctionnalités de collaboration et d’extensibilité de fichiers et de données, et s’intègre à Microsoft 365 et à d’autres applications Microsoft et partenaires.

Skype Entreprise Online se retire le 31 juillet 2021, qui a été annoncé le 30 juillet 2019. [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) Microsoft Teams est un service entièrement nouveau, conçu pour le cloud depuis le début en tirant parti d’Azure et d’autres innovations de service de Microsoft. Microsoft Teams repose sur des groupes Microsoft 365, Microsoft Graph et avec la même sécurité, la même conformité et la même gérabilité au niveau de l’entreprise que le reste Office 365. Teams utilise les identités stockées dans Azure Active Directory (Azure AD). Ces services sont livrés à partir de centres de données Microsoft et sont accessibles aux utilisateurs sur un large éventail d’appareils depuis l’intérieur d’un réseau d’entreprise ou sur Internet. Pour plus d’informations, voir les [affiches Microsoft Teams’architecture](/microsoftteams/teams-architecture-solutions-posters)et solutions de téléphonie.

Cette description de service détaille les principales différences entre les services fournis dans les différentes installations cloud. Microsoft Teams fonctionnalités principales ne diffèrent pas d’un abonnement à l’autre. La disponibilité des fonctionnalités de conformité dépend du niveau d’abonnement. Pour en savoir plus sur Teams sécurité et conformité, consultez La sécurité et [la conformité dans Microsoft Teams](/microsoftteams/security-compliance-overview).

Si les utilisateurs ont été migrés entièrement en ligne, ils doivent avoir des licences teams et Skype Entreprise Online pour une fonctionnalité Teams complète, même si Skype Entreprise Online ne sera pas utilisé.

## <a name="available-plans"></a>Plans disponibles

Pour obtenir des informations détaillées sur les abonnements qui permettent aux utilisateurs d’Teams, voir Rechercher les Microsoft Teams [pour votre entreprise.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options) Vous pouvez trouver des détails supplémentaires dans le tableau [de comparaison des solutions Microsoft.](https://go.microsoft.com/fwlink/?linkid=2139145)

Les plans du gouvernement qui Teams sont Office 365 G1 à G5. Pour plus d’informations, [voir Office 365 Secteur Public plans.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans)

Tous les plans d’abonnement pris en charge peuvent accéder au client web Microsoft Teams, aux clients de bureau et aux applications mobiles.

Microsoft Teams n’est pas disponible en tant que service autonome.

## <a name="feature-availability"></a>Disponibilité des fonctionnalités

Le tableau suivant répertorie les principales fonctionnalités Teams disponibles dans les différents plans. Certaines mises en garde s’appliquent. Pour plus d’informations, voir les notes de bas de page. Ce tableau peut changer sans préavis.

Pour en savoir plus sur Teams fonctionnalités par plateforme de système d’exploitation, voir [Teams fonctionnalités par plateforme.](https://aka.ms/teamsfeaturesbyplatform)

Pour obtenir la liste complète des fonctionnalités de Teams à jour dans les plans Microsoft 365 et Office 365, consultez La liste complète des fonctionnalités Microsoft Teams pour votre [entreprise.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)<br><br>

| Fonctionnalité | Plans pour les petites entreprises | Enterprise plans | GCC | Cloud de la communauté du secteur public - Élevé | DOD | Plans d’enseignement |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Conversation  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Équipes  <br/> |Oui <br/> |Oui <br/> |Oui <br/> |Oui<sup>1</sup>  <br/> |Oui<sup>1</sup>  <br/> |Oui  <br/> |
|Canaux - Standard  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Canaux - Privé  <br/> |Oui  <br/> |Oui<sup>2</sup>  <br/> |Oui <br/> |Non  <br/> |Non <br/> |Oui  <br/> |
|Réunions  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Partage d’écran PowerPoint ordinateur de bureau audio/vidéo <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Appels vocaux  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>3</sup>  <br/> |Oui<sup>3</sup>  <br/> |Oui  <br/> |
|Audioconférence  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>3</sup>  <br/> |Oui<sup>3</sup>  <br/> |Oui  <br/> |
|Applications, bots & connecteurs  <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>4</sup>  <br/> |Oui<sup>4</sup>  <br/> |Oui<sup>4</sup>  <br/> |Oui  <br/> |
|Événements en direct  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non<sup>5</sup>  <br/> |Non<sup>5</sup>  <br/> |Oui  <br/> |

<sup>1 Microsoft Teams</sup> dans GCC-High et DOD 2 500 membres dans une équipe individuelle.<br/>
<sup>2</sup> Le Planificateur Microsoft n’est pas disponible actuellement pour accéder aux canaux privés.<br/>
<sup>3 Le</sup> routage direct doit être configuré pour que Microsoft Teams audioconférence fonctionne dans GCCH et DoD.<br/>
<sup>4</sup> Les applications tierces et la publication d’applications ne sont pas disponibles dans ces clouds pour le moment. Les connecteurs ne sont pas pris en charge dans GCCH et DOD.<br/>
<sup>5</sup> Événements en direct n’est pas disponible GCC-High ou DOD pour le moment.<br/>

### <a name="cloud-voice-features"></a>Fonctionnalités vocales cloud

Pour l’audioconférence, votre organisation doit acheter et attribuer une licence d’audioconférence à chaque utilisateur qui définit des réunions rendez-vous. Pour Teams fonctionnalités nécessitant des forfaits d’appels, chaque utilisateur a besoin d’un système téléphonique et d’un plan d’appels nationaux ou nationaux et internationaux. Pour en savoir plus, [voir Microsoft Teams licences de modules.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

### <a name="live-events"></a>Événements en direct

Cette offre dans Office 365 remplace la diffusion Réunion Skype retirée. Les fonctionnalités d’événements en direct sont disponibles pour les plans de gestion des licences, comme détaillé dans le service Stream. Pour plus d’informations, examinez la vue [d’ensemble des licences Microsoft Stream.](/stream/license-overview) Le service d’événements en direct est accessible via Stream, Yammer ou Microsoft Teams. Pour en savoir plus sur les fonctionnalités des événements en direct, consultez les événements en direct Microsoft 365 dans [Yammer, Microsoft Teams et Microsoft Stream.](/stream/live-event-m365) Pour en savoir plus sur la planification des événements en direct, y compris sur les licences requises, voir Planifier les événements en direct [dans Microsoft Teams](/microsoftteams/teams-live-events/plan-for-teams-live-events).

## <a name="learn-more"></a>En savoir plus

Pour plus d’informations Teams, consultez les ressources suivantes :
 
- [Documentation pour les administrateurs Microsoft Teams](/MicrosoftTeams)
- [Microsoft Teams communauté technique locale](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Microsoft Teams blog](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Termes du contrat de licence

Pour obtenir les termes et conditions de licence des produits et services achetés via les programmes de licence en volume commerciaux Microsoft, consultez le [site Termes du produit.](https://www.microsoft.com/licensing/terms/) 

### <a name="messaging"></a>Messagerie

Pour rester informé des modifications à venir, y compris des fonctionnalités nouvelles et modifiées, de la maintenance planifiée ou d’autres annonces importantes, visitez le Centre de messages. Pour plus d’informations, voir [Centre de messages.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>Accessibilité

Microsoft s’engage à assurer la sécurité de vos données et l’accessibilité de nos services. Pour plus d’informations, voir le [Centre de](https://www.microsoft.com/trust-center) confiance Microsoft et le [centre Office’accessibilité.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
