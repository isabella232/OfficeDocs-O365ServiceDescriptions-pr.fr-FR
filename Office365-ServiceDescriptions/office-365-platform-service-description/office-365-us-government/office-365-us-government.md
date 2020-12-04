---
title: Office 365 pour le gouvernement américain
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: En réponse aux exigences uniques et évolutives du secteur public américain, Microsoft a créé des plans Office 365 pour le gouvernement américain (ou Office 365). Cet article fournit une vue d’ensemble des fonctionnalités spécifiques aux environnements Office 365 gouvernementaux.
ms.openlocfilehash: 63cef3dfac77ae22bc413deab9d375c1cd110b46
ms.sourcegitcommit: 04f9191b177e714a8dbdd50e7a891ff295483dbe
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/03/2020
ms.locfileid: "49566676"
---
# <a name="office-365-government"></a>Office 365 pour le gouvernement

> [!IMPORTANT]
> Microsoft teams rencontre un pic énorme dans les appels en ligne et les conférences audio/vidéo en raison de l’coronavirus (COVID-19) Pandemic.<br/>
>
>En réponse à une augmentation inégalée des appels, et pour garantir la continuité et la disponibilité, Microsoft autorise les serveurs audio/vidéo de Microsoft teams à tirer parti de la capacité de traitement dans nos centres de données commerciaux, ainsi que dans nos centres de données gouvernementaux.<br/>
>
>Ces serveurs audio/vidéo résident dans les serveurs de frontière de haute accréditation Microsoft Azure FedRAMP aux États-Unis et ne stockent pas de contenu client. Toutefois, ces serveurs traitent l’audio et la vidéo pour les appels et les conférences et fonctionnent au cours de notre équipe commerciale pendant cette période intermédiaire.<br/>
>
>Les membres du personnel qualifiés et filtrés surveillent ces serveurs pour qu’ils puissent accéder aux données client en examinant tous les modules de journalisation interactifs sur ces serveurs. Personnel qualifié répondre aux exigences de GCC pour accéder au contenu du client. Pour plus d’informations sur les exigences de filtrage, voir la [Description du service GCC](gcc.md).<br/>
>
>Nous vous remercions de votre soutien, car nous nous assurons que nos services restent disponibles et fiables dans ces temps exceptionnels.<br/>

En réponse aux exigences uniques et évolutives du secteur public des États-Unis, Microsoft a créé des plans gouvernementaux Office 365 (ou Office 365). Cette description de service fournit une vue d’ensemble des fonctionnalités spécifiques aux environnements Office 365 gouvernementaux. Nous vous recommandons de lire cette description de service parallèlement aux autres [descriptions de service Microsoft 365 et Office 365](../../office-365-service-descriptions-technet-library.md).

## <a name="how-to-use-this-service-description"></a>Utilisation de la description de ce service

La description du service public Office 365 est conçue pour servir de superposition à la description de service générale d’Office 365. Elle définit les engagements uniques et les différences par rapport aux offres Office 365 Entreprise.

## <a name="about-office-365-government-environments"></a>À propos des environnements gouvernementaux Office 365

Les plans gouvernementaux Office 365 sont des abonnements mensuels et peuvent être cédés sous licence pour un nombre illimité d’utilisateurs.

- L’environnement **GCC d’Office 365** fournit la conformité aux exigences fédérales pour les services Cloud, y compris la haute FedRAMP et la configuration requise pour la justice pénale et les systèmes d’information sur la fiscalité fédérale (types de données CJI et FTI).

- Les environnements **GCC High et DoD d’Office 365** sont conformes aux directives relatives aux exigences en matière de sécurité du département de la défense, du supplément DFARS (Defense Federal acquisition Regulations) et du trafic international en matière de réglementations sur les armes (ITAR).

Outre les fonctionnalités d’Office 365, les organisations qui utilisent Office 365 Governance bénéficient des fonctionnalités suivantes, propres à Office 365 Government :

- Le contenu client de votre organisation est logiquement séparé du contenu client relevant des services commerciaux de Microsoft Office 365.

- Le contenu client de votre organisation est stocké aux États-Unis.

- L'accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.

- Office 365 le gouvernement est conforme aux certifications et accréditations requises pour les clients du secteur public américain.

## <a name="customer-eligibility"></a>Conditions d’éligibilité des clients

Office 365 Government est disponible pour (1) les entités américaines Federal, State, local, tribal et territorial territoriale, et (2) d’autres entités qui gèrent les données soumises aux réglementations et exigences gouvernementales et où l’utilisation du gouvernement 365 Office est appropriée pour répondre à ces exigences, sous réserve de validation de l’éligibilité. Les contrôles d'éligibilité menés par Microsoft consistent en la confirmation du traitement de données soumises à la Réglementation américaine sur le trafic d'armes au niveau international (ITAR), de données judiciaires soumises à la politique des services d'information sur les informations de justice criminelle (CJIS) du FBI, ou d'autre données faisant l'objet de contrôles ou de réglementations gouvernementales. Dans le cadre de ces contrôles, il peut être exigé une preuve d'enregistrement auprès du département d'État des États-Unis dans le cas des données ITAR, ou encore une caution délivrée par une entité gouvernementale ayant des exigences spécifiques en matière de gestion des données. L’environnement Office 365 DoD est destiné à l’usage exclusif du ministère de la défense des États-Unis.

Bien que les critères d’éligibilité soient cohérents entre les offres gouvernementales Office 365, Microsoft accepte uniquement les langues de contrat DFARS et ITAR pour l’environnement hautement rapide.

Les entités qui posent des questions sur l’éligibilité pour le gouvernement d’Office 365 doivent consulter leur équipe de compte.

Lors du renouvellement du contrat d’un client pour Office 365, la revalidation de l’éligibilité est requise.

## <a name="customer-content-located-within-the-united-states"></a>Contenu client situé aux États-Unis

Les services gouvernementaux Office 365 sont fournis à partir de centres de services situés physiquement aux États-Unis. Le contenu client suivant est enregistré au repos dans des centres de données situés physiquement uniquement aux États-Unis :

- Contenu de boîte aux lettres Exchange Online (corps de courrier électronique, entrées de calendrier et contenu de pièces jointes)

- Contenu de site SharePoint Online et fichiers stockés dans ce site

- Conversations archivées Skype entreprise, documents téléchargés et sessions de tableau blanc

- Threads de conversation permanente Microsoft teams

> [!NOTE]
> Dans le cas d'une utilisation normale, Skype Entreprise ne stocke pas le contenu client, mais si ce stockage se produit, il sera réalisé dans des centres de données aux États-Unis.

Si vos utilisateurs sont situés aux États-Unis et que vous utilisez Office pour le Web (anciennement Office Web Apps) ou si vous adoptez l’utilisation des services ADFS (Active Directory Federation Services) 2,0 et que vous configurez des stratégies pour vous assurer que les utilisateurs se connectent aux services via l’authentification unique, tout contenu client temporairement mis en cache dans Office pour le Web sera situé aux

La page utilisation du site pour les sites SharePoint est disponible pour les plans gouvernementaux, bien que par conformité, certaines fonctionnalités de cette page soient disponibles uniquement pour les clients commerciaux. Pour plus d’informations, consultez la [page utilisation du site pour les sites SharePoint dans Microsoft 365](https://support.microsoft.com/office/2fa8ddc2-c4b3-4268-8d26-a772dc55779e).

## <a name="office-365-government-and-third-party-services"></a>Services gouvernementaux Office 365 et services tiers

Office 365 offre la possibilité d’intégrer des applications tierces dans des sites SharePoint Online, Skype entreprise, des applications Office incluses dans les applications Microsoft 365 pour Enterprise (Word, Excel, PowerPoint et Outlook, par exemple) et Outlook Web App. En outre, Office 365 prend en charge l'intégration avec des fournisseurs de services tiers. Ces applications et services tiers peuvent impliquer le stockage, la transmission et le traitement de données client de votre organisation sur des systèmes tiers situés en dehors de l'infrastructure Office 365 et qui ne sont donc pas couverts par la conformité Office 365 et les engagements de protection des données. Nous vous recommandons de consulter les déclarations de confidentialité et de conformité fournies par les parties tierces lors de l'évaluation de l'utilisation appropriée de ces services pour votre organisation.

## <a name="restricted-data-access-by-administrators"></a>Accès aux données limité par les administrateurs

L’accès au contenu client du gouvernement 365 par les administrateurs Microsoft est limité au personnel filtré. Pour plus d’informations sur les niveaux de filtrage, reportez-vous à la page Description de service pour chaque environnement respectif (GCC ou GCC High et DoD).

## <a name="fasttrack-center-onboarding-assistance"></a>Assistance à l’intégration du centre FastTrack

Avec le centre FastTrack pour Office 365<sup>1</sup>, vous travaillez à distance avec des spécialistes FastTrack pour obtenir votre environnement Office 365 prêt à être utilisé et planifier le déploiement et l’utilisation au sein de votre organisation. Le processus de FastTrack propose des services pour l’adoption utilisateur et l’intégration. 

L’intégration se compose des éléments suivants :

- Intégration de base : tâches requises pour la configuration du client et l’intégration à Azure Active Directory (Azure AD) si nécessaire. L’intégration de base fournit également la ligne de base pour l’intégration d’autres services éligibles.

- Intégration de services les tâches d’intégration de service de migration permettent de créer des scénarios dans votre client. La migration des données (y compris la messagerie électronique et les fichiers) est décrite dans la [migration de données](https://aka.ms/whatcanmigrate). <sup>2</sup>

Les services d’adoption par les utilisateurs sont composés de tâches qui fournissent des instructions pour vous permettre de vérifier que vos utilisateurs sont informés des services éligibles et peuvent les utiliser pour générer de la valeur commerciale. Cette aide est offerte en parallèle aux activités d’intégration.

Vous trouverez des informations spécifiques sur le processus du centre FastTrack [ici](https://aka.ms/whatistheprocess). Pour une répartition des rôles et des responsabilités des engagements, examinez les [responsabilités de FastTrack](https://aka.ms/whatdoesftcdo) , ainsi que [vos responsabilités](https://aka.ms/whatdowedo).

> <sup>1</sup> vous devez acheter au moins 50 licences dans la liste des [offres éligibles](https://aka.ms/whocanbenefit) pour recevoir les services FastTrack.
<br/><sup>2</sup> les services de migration de données sont disponibles pour les clients Office 365 avec 500 ou plus de licences.

## <a name="data-migrations-performed-by-fasttrack"></a>Migrations de données effectuées par FastTrack

Les clients qui choisissent l’avantage de migration [FastTrack](https://fasttrack.microsoft.com/) devront accorder l’accès à l’équipe qui gère leurs migrations de données. Ces personnes sont des citoyens américains et sont soumises aux tests de base suivants avant d’effectuer des migrations pour les clients d’Office 365 des services publics américains.<br><br>

|Filtrage des antécédents |GCC|GCC High et DoD|
|---|---|---|
|Vérification de la citoyenneté américaine|Oui|Oui|
|Vérification de l’historique des emplois|Oui|Oui|
|Vérification de l’éducation|Oui|Oui|
|Recherche de numéro de sécurité sociale (SSN)|Oui|Oui|
|Vérification de l’historique pénal (7 ans)|Oui|Oui|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 pour le gouvernement américain et Azure Government ExpressRoute

Office 365 les clients du gouvernement américain peuvent utiliser les services ExpressRoute gouvernementaux pour se connecter en privé aux services Office 365 pris en charge au lieu de se connecter sur Internet.

Pour plus d’informations, telles que les fournisseurs pris en charge, les modèles de tarification et plus encore, consultez les [informations Azure ExpressRoute](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409).

Pour plus d’informations sur la prise en charge d’Azure ExpressRoute par Office 365, consultez la rubrique [Azure ExpressRoute pour office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)

## <a name="system-requirements"></a>Configuration requise

Pour connaître la configuration requise pour installer et utiliser les plans Office 365 pour le gouvernement américain, reportez-vous à la page [Configuration requise pour Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) sur le site des produits [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409).

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Pour plus d’informations sur le centre de sécurité &amp; conformité et des liens vers des informations et une disponibilité supplémentaires, consultez la rubrique [Security &amp; Compliance Center](../../office-365-platform-service-description/office-365-securitycompliance-center.md).

## <a name="service-availability-for-each-plan"></a>Disponibilité des services pour chaque plan

Chaque plan Office 365 inclut un certain nombre de services, comme Exchange Online et SharePoint Online. Le tableau suivant présente les services disponibles dans chaque plan Office 365 pour le gouvernement américain.<br><br>

|Service Office 365|Office 365 pour le gouvernement G1|Office 365 pour le gouvernement G3|Office 365 Secteur Public G5|Office 365 gouvernement F3|
|---|---|---|---|---|
|Office pour le web|Oui|Oui|Oui|Oui|
|Applications Microsoft 365 for entreprise|Non|Oui|Oui|Non|
|Exchange Online|Oui|Oui|Oui|Oui|
|Exchange Online Protection|Oui|Oui|Oui|Oui|
|SharePoint Online|Oui|Oui|Oui|Oui|
|OneDrive Entreprise|Oui|Oui|Oui|Oui|
|Skype for Business (Instant Messaging &amp; Presence)|Oui<sup>1</sup>|Oui|Oui|Oui<sup>1</sup>|
|Système de téléphonie vocale, audioconférence|N °<sup>2</sup>|N °<sup>2</sup>|Oui<sup>5</sup>|Non|
|Power BI Pro|N °<sup>2</sup>|N °<sup>2</sup>|Oui|N °<sup>2</sup>|
|Project Online|N °<sup>2</sup>|N °<sup>2</sup>|N °<sup>2</sup>|N °<sup>2</sup>|
|Visio pour le web|N °<sup>6</sup>|N °<sup>6</sup>|N °<sup>6</sup>|N °<sup>6</sup>|
|Yammer Entreprise|N °<sup>4</sup>|N °<sup>4</sup>|N °<sup>4</sup>|N °<sup>4</sup>|

> <sup>1</sup> Skype entreprise Basic est disponible pour tous les clients. Le client de bureau Skype Entreprise est une application installée localement qui fournit des fonctionnalités de présence, de messagerie instantanée et de conférence pour les plans Office 365 comprenant Skype Entreprise Online. Les applications Microsoft 365 pour Enterprise, G3 et G5 incluent l’application Skype complète, qui inclut des fonctionnalités supplémentaires, telles que la prise en charge de la téléphonie avancée, l’archivage et les fonctionnalités de conformité. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> non inclus, mais peut être acheté en tant que module complémentaire distinct. Project Online inclut le client de bureau Project Online dans le cadre de l’abonnement.
<br/> <sup>3</sup> pas encore disponible dans les offres GCC High ou DOD, mais bientôt disponible.
<br/><sup>4</sup> Yammer Enterprise n’est pas un composant d’Office 365 le gouvernement américain, mais peut être acquis gratuitement en tant qu’offre autonome pour chaque utilisateur titulaire d’une licence pour Office 365 dans GCC. Cette offre est actuellement limitée aux clients qui achètent Office 365 GCC sous les contrats d’entreprise et les contrats d’abonnement Enterprise. Yammer n’est pas disponible dans GCC High ou DoD.
<br/><sup>5</sup> le plan d’appel est un module complémentaire.
<br/><sup>6</sup> non inclus, mais peut être acheté en tant que module complémentaire distinct. Visio pour le Web inclut l’application de bureau Visio dans le cadre de l’abonnement.

## <a name="platform-features"></a>Fonctionnalités de la plateforme 

Le tableau suivant répertorie les fonctionnalités et les services de la plateforme disponibles dans les plans Office 365 pour le gouvernement américain.<br><br>

|Fonctionnalité|Office 365 pour le gouvernement G1|Office 365 pour le gouvernement G3|Office 365 Secteur Public G5|Office 365 gouvernement F3|
|---|---|---|---|---|
|**Administration d'Office 365**|||||
|Utiliser le centre d’administration Microsoft 365 pour administrer Office 365|Oui<sup>16</sup>|Oui<sup>16</sup>|Oui|Oui<sup>16</sup>|
|Gestion des paramètres de service principal à partir d'Office 365|Oui|Oui|Oui|Oui|
|Utilisation de Windows PowerShell pour gérer Office 365|Oui|Oui|Oui|Oui|
|Protéger le contenu à l'aide d'Azure Information Protection|N °<sup>1</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|N °<sup>1</sup>|
|**[Fonctionnalités de la suite Office 365](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Réservations Microsoft|Non|Oui<sup>21</sup>|Oui<sup>21</sup>|Non|
|Courrier électronique de briefing Microsoft|Non|Non|Non|Non|
|Microsoft Power Automate|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Microsoft Forms|Oui|Oui|Oui<br/>|Oui</sup>|
|API Microsoft Graph|Oui|Oui|Oui|Oui|
|Microsoft MyAnalytics|Non|Non|Oui,<sup>17</sup>|Non|
|Microsoft Planner|Oui|Oui|Oui|Oui|
|Microsoft PowerApps|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Microsoft StaffHub|Non|Non|Non|Non<br/>|
|Microsoft Stream|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|Oui<sup>9, 15, 20</sup>|
|Microsoft Sway|Non|Non|Non|Non|
|Microsoft Teams|Oui|Oui|Oui|Oui|
|Office Delve|Oui,<sup>17</sup>|Oui,<sup>17</sup>|Oui|Oui,<sup>17</sup>|
|Groupes Office 365|Oui|Oui|Oui|Oui|
|**[Gestion des comptes d’utilisateur](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Identité de nuage|Oui|Oui|Oui|Oui|
|Identités fédérées (authentification unique)|Oui|Oui|Oui|Oui|
|Authentification multifacteur|Oui|Oui|Oui|Oui|
|Authentification par facteur de téléphone|Oui<sup>9</sup>|Oui<sup>9</sup>|Oui|Oui<sup>9</sup>|
|Configuration du bureau Office 365|Oui|Oui|Oui|Oui|
|Gestion des utilisateurs avec Office 365|Oui|Oui|Oui|Oui|
|Téléchargement en bloc à l'aide de fichiers .csv|Oui<sup>9</sup>|Oui<sup>9</sup>|Oui|Oui<sup>9</sup>|
|Outil de synchronisation d'annuaires|Oui|Oui|Oui|Oui|
|Migration Exchange (à basculement) simple|Oui|Oui|Oui|Oui|
|Supprimer des comptes à l'aide d'Office 365|Oui<sup>3</sup>|Oui<sup>3</sup>|Oui<sup>3</sup>|Oui<sup>3</sup>|
|L'administrateur peut réinitialiser le mot de passe de l'utilisateur dans Office 365 ou à l'aide de Windows PowerShell|Oui<sup>4</sup>|Oui<sup>4</sup>|Oui<sup>4</sup>|Oui<sup>4</sup>|
|Les utilisateurs peuvent modifier leur mot de passe|Oui<sup>5</sup>|Oui<sup>5</sup>|Oui<sup>5</sup>|Oui<sup>5</sup>|
|Gestion des licences|Oui<sup>7, 8</sup>|Oui<sup>7, 8</sup>|Oui<sup>7, 8</sup>|Oui<sup>7, 8</sup>|
|Gérer les groupes de sécurité dans Office 365|Oui|Oui|Oui|Oui|
|Plusieurs rôles d'administrateur disponibles|Oui|Oui|Oui|Oui|
|Autoriser un partenaire à administrer Office 365 pour vous|Oui<sup>11</sup>|Oui<sup>11</sup>|Oui<sup>11</sup>|Oui<sup>11</sup>|
|Services Azure Active Directory|Oui|Oui|Oui|Oui|
|**[Domaines](../../office-365-platform-service-description/domains.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Ajouter des domaines personnalisés de 2ème niveau, comme fourthcoffee.com|Oui|Oui|Oui|Oui|
|Ajouter des domaines personnalisés de 3ème niveau, comme marketing.fourthcoffee.com|Oui|Oui|Oui|Oui|
|Ajouter jusqu'à 900 domaines personnalisés|Oui|Oui|Oui|Oui|
|Vérification obligatoire de la possession du domaine pour les domaines personnalisés|Oui|Oui|Oui|Oui|
|**[État et continuité du service](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Status information available on the **Service health** or **Service status** page|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|
|État des alertes individuelles disponible dans le tableau de bord du centre d’administration Microsoft 365|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|
|Flux RSS **État du service**|Oui|Oui|Oui|Oui|
|**[Rapports](../../office-365-platform-service-description/reports.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Boîtes aux lettres actives et inactives|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Boîtes aux lettres supprimées et nouvelles|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Groupes nouveaux et supprimés|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Utilisation des boîtes aux lettres|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Types de connexions aux boîtes aux lettres|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Messages entrants et sortants|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Principaux expéditeurs et destinataires|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Détections de courrier indésirable|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Détections de programmes malveillants|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Principaux programmes malveillants pour le courrier électronique|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Correspondances de règles pour le courrier électronique|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Principales correspondances de règles pour le courrier électronique|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Principales correspondances de stratégies DLP pour le courrier électronique|Non|Oui<sup>15</sup>|Oui<sup>15</sup>|Non|
|Correspondances de stratégies DLP par gravité pour le courrier électronique|Non|Oui<sup>15</sup>|Oui<sup>15</sup>|Non|
|Correspondances de stratégies DLP, de remplacements et de faux positifs pour le courrier électronique|Non|Oui<sup>15</sup>|Oui<sup>15</sup>|Non|
|Principales correspondances de règles DLP pour le courrier électronique|Non|Oui<sup>15</sup>|Oui<sup>15</sup>|Non|
|Sessions de messagerie instantanée et audio|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Conférences de partage d'application, web et rendez-vous|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Sessions vidéo, de partage d'application et de transfert de fichiers|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Conférences par messagerie instantanée, audio et vidéo|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Rapports de protection de messagerie téléchargeable|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Navigateur utilisé|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Système d'exploitation utilisé|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Créer vos propres rapports à l’aide des services Web de création de rapports Microsoft 365|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|**[Mises à jour de service](../../office-365-platform-service-description/service-updates.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Mises à jour normales fournies à tous les clients|Oui|Oui|Oui|Oui|
|Notifications envoyées au centre de messages lorsqu'une action est requise|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|Oui<sup>15</sup>|
|Roadmap.office.com pour certaines mises à jour de service|N °<sup>10, 13</sup>|N °<sup>10, 13</sup>|N °<sup>10, 13</sup>|N °<sup>10, 13</sup>|
|Option permettant d’activer la publication ciblée|Oui<sup>10</sup>|Oui<sup>10</sup>|Oui<sup>10</sup>|Oui<sup>10</sup>|
|**[Aide et formation](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Aide en ligne|Oui|Oui|Oui|Oui|
|Communauté|Oui|Oui|Oui|Oui|
|Autres ressources d'aide autonome|Oui|Oui|Oui|Oui|
|Auto-formation|Oui|Oui|Oui|Oui|
|**[Réseau](../../office-365-platform-service-description/networking.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Protocoles IPv4 et IPv6|Oui|Oui|Oui|Oui|
|**Approbation**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|**[Confidentialité, sécurité et transparence](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|Gouvernance des données avancée|N °<sup>12</sup>|N °<sup>12</sup>|Oui|N °<sup>12</sup>|
|Cloud App Security|N °<sup>12, 15, 19</sup>|N °<sup>12, 15, 19</sup>|Oui<sup>15, 19</sup>|N °<sup>12, 15, 19</sup>|
|Microsoft Defender pour Office 365|N °<sup>12, 18</sup>|N °<sup>12, 18</sup>|Oui<sup>18</sup>|N °<sup>12, 18</sup>|
|Référentiel sécurisé client|N °<sup>12</sup>|N °<sup>12</sup>|Oui|N °<sup>12</sup>|
|Advanced eDiscovery|N °<sup>12</sup>|N °<sup>12</sup>|Oui|N °<sup>12</sup>|
|Score de sécurité<sup>14</sup>|Oui<sup>, 9</sup>|Oui<sup>9</sup>|Oui<sup>, 9</sup>|Oui<sup>, 9</sup>|
|Chiffrement des messages Office|Non|Oui|Oui|Non|
|Intelligence des menaces|N °<sup>12</sup>|N °<sup>12</sup>|Oui|N °<sup>12</sup>|
|**[Conformité](https://docs.microsoft.com/microsoft-365/compliance/offering-home)**|||||
|Évaluations SAS 70 / SSAE16|Oui|Oui|Oui|Oui|
|Certification ISO 27001|Oui|Oui|Oui|Oui|
|Clauses types de l'UE|Oui|Oui|Oui|Oui|
|« Sphère de sécurité » de l'UE|Oui|Oui|Oui|Oui|
|Accord associé HIPAA-Business|Oui|Oui|Oui|Oui|
|Autorisation d'exploitation FISMA|Oui|Oui|Oui|Oui|
|Accord de traitement de données Microsoft|Oui|Oui|Oui|Oui|
|PCI-DSS niveau 1|Oui|Oui|Oui|Oui|
|Données PAN sous régie PCI|Non|Non|Non|Non|
|**[Continuité de service](../../office-365-platform-service-description/service-health-and-continuity.md)**|Oui|Oui|Oui|Oui|
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Utilisation de BlackBerry Internet Service (BIS)|N °<sup>2</sup>|N °<sup>2</sup>|N °<sup>2</sup>|N °<sup>2</sup>|
|**[Partenaires](../../office-365-platform-service-description/partners.md)**|||||
|Création d'invitations à participer à la version d'évaluation et de bons de commande pour un client utilisant le plan spécifié|N °<sup>11</sup>|N °<sup>11</sup>|N °<sup>11</sup>|N °<sup>11</sup>|
|Administration déléguée|N °<sup>11</sup>|N °<sup>11</sup>|N °<sup>11</sup>|N °<sup>11</sup>|
|**[Contrat de niveau de service](../../office-365-platform-service-description/service-level-agreement.md)**|Oui|Oui|Oui|Oui|
|**[Droits d’utilisation de logiciels](../../office-365-platform-service-description/product-use-rights.md)**|Oui|Oui|Oui|Oui|

> <sup>1</sup> Azure information protection n’est pas inclus, mais peut être acheté en tant que module complémentaire distinct et permet d’activer les fonctionnalités de gestion des droits relatifs à l’information (IRM). Certaines fonctionnalités Azure information protection nécessitent un abonnement aux applications Microsoft 365 pour entreprise, qui ne sont pas incluses dans Office 365 Government ou Office 365 Government. >
<br/><sup>2</sup> les clients BBCS et bis existants peuvent continuer à utiliser le service. Les nouveaux clients ne sont pas acceptés.
<br/><sup>3</sup> si vous utilisez la synchronisation d’annuaires, vous devez supprimer des comptes ou modifier des mots de passe à l’aide d’Active Directory, plutôt que du portail Office 365 ou en utilisant le module Azure Active Directory pour Windows PowerShell.
<br/><sup>4</sup> si vous utilisez la synchronisation de mot de passe, les utilisateurs doivent changer leur mot de passe dans l’annuaire Active Directory local.
<br/><sup>5</sup> pour découvrir comment définir des stratégies de gestion de mot de passe en libre-service pour les utilisateurs, consultez la rubrique [gestion des mots de passe dans Azure ad](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/).
<br/><sup>6</sup> vous ne pouvez avoir qu’un seul site Web public avec Office 365, sauf si vous avez effectué une mise à niveau à partir d’une version antérieure d’Office 365. Dans ce cas, vous avez deux sites web publics, mais un seul d’entre eux peut être hébergé avec un nom de domaine personnalisé. Pour plus d’informations sur l’utilisation des deux sites Web pour les abonnements d’entreprise, consultez la rubrique [utilisation de vos deux sites Web publics Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Si vous disposez d’un autre abonnement, en savoir plus sur les sites Web publics pour [en savoir plus sur l’hébergement de sites Web partenaires et sur les sites Web publics dans Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009).
<br/><sup>7</sup> la réduction des sièges qui ont été achetés avec un escompte de terme peut être soumise à des frais de résiliation anticipée. Ceci n’est pas applicable aux abonnements payés sur une base mensuelle.
<br/><sup>8</sup> les plans suivants ne prennent pas en charge les modifications de siège de licence à partir du centre d’administration 365 de Microsoft : Office 365 gouvernement G1, Office 365 gouvernement G3, Office 365 Administration F3.
<br/><sup>9</sup> pas encore disponible dans GCC High, mais bientôt disponible.
<br/><sup>10</sup> pour Office 365 gouvernement G1, G3 et F3, version ciblée et la feuille de route Office 365 pour les entreprises ; Toutefois, il peut y avoir des différences ou des retards pour les mises à jour de service spécifiques en raison des [exigences de conformité](https://www.microsoft.com/trust-center).
<br/><sup>11</sup> pas encore disponible dans les offres gouvernementales Office 365, mais bientôt disponible.
<br/><sup>12</sup> non inclus, mais peut être acheté séparément en tant que module complémentaire dans GCC.
<br/><sup>13</sup> non pris en charge pour les offres gouvernementales Office 365.
<br/><sup>14</sup> disponible à l’adresse [https://securescore.office.com](https://securescore.office.com) . Nécessite des autorisations d'administration. Pour plus d'informations, consultez l'article [Présentation de Secure Score d'Office 365](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-secure-score).
).
<br/><sup>15</sup> pas encore disponible dans l’environnement DOD, mais bientôt disponible.
<br/><sup>16</sup> le centre d’administration n’inclut pas l’analyse de l’utilisation dans les environnements DoD ou GCC High.
<br/><sup>17</sup> non pris en charge pour les environnements GCC High ou DoD.
<br/><sup>18</sup> le hameçonnage pour l’emprunt d’identité d’utilisateur et de domaine et l’aide à l’usurpation ne sont pas encore disponibles dans GCC High et DoD.
<br/><sup>19</sup> pas encore disponible dans l’environnement GCC, mais bientôt disponible.
<br/><sup>20</sup> consommation uniquement pour Microsoft Stream : pas de publication ni de partage.
<br/><sup>21</sup> non disponible pour l’API Microsoft Graph ou Microsoft Teams.

## <a name="office-application-availability-and-enterprise-value"></a>Disponibilité de l’application Office et valeur entreprise

Le tableau suivant présente les fonctionnalités de l'application Office disponibles dans les plans Office 365 pour le gouvernement américain.<br><br>

|Application/fonctionnalité|Office 365 pour le gouvernement G1|Office 365 pour le gouvernement G3|Office 365 Secteur Public G5|Office 365 gouvernement F3|
|---|---|---|---|---|
|**Applications Office**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|Non|Oui|Oui|Non|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|Non|Oui|Oui|Non|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|Non|Oui|Oui|Non|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|Non|Oui|Oui|Non|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|Non|Oui|Oui|Non|
|Microsoft Forms<sup>7</sup>|Oui|Oui <br/>|Oui|Non|
|Tableau blanc Microsoft<sup>7</sup>|Non|Oui|Oui|Non|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|Non|Oui|Oui|Non|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|Non|Oui|Oui|Non|
|[Skype Entreprise](../../office-applications-service-description/office-applications.md#skype-for-business)|Oui<sup>3</sup>|Oui|Oui|Oui<sup>3</sup>|
|[Office pour Mac pour Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|Non|Oui|Oui|Non|
|[Office Mobile pour iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|Oui|Oui<sup></sup>|Oui<sup></sup>|Oui|
|[Office Mobile pour Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|Oui|Oui<sup></sup>|Oui<sup></sup>|Oui|
|[Office Mobile pour Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|Oui|Oui<sup>4</sup>|Oui<sup>4</sup>|Oui|
|Office Mobile pour tablettes Windows 10|Oui|Oui<sup></sup>|Oui<sup></sup>|Oui|
|Outlook pour iOS et Android<sup>5, 4</sup>|Oui|Oui|Oui|Oui|
|**Valeur entreprise**|**Office 365 Secteur Public G1**|**Office 365 pour le gouvernement G3**|**Office 365 Secteur Public G5**|**Office 365 gouvernement F3**|
|Cinq installations par utilisateur sur PC ou Mac|Non|Oui|Oui|Non|
|Mise en service automatisée du compte d'utilisateur|Oui|Oui|Oui|Oui|
|Interface utilisateur multilingue|Non|Oui|Oui|Non|
|Déploiement poussée du client|Non|Oui<sup>4</sup>|Oui<sup>4</sup>|Non|
|Prise en charge du client pour le serveur Exchange local|Non|Oui|Oui|Non|
|Prise en charge du client pour SharePoint local|Non|Oui|Oui|Non|
|Contrôle des mises à jour logicielles|Non|Oui|Oui|Non|
|Comparer les bases de données|Non|Oui|Oui|Non|
|Virtualisation des services Bureau|Non|Oui|Oui|Non|
|Comparer les feuilles de calcul Excel|Non|Oui|Oui|Non|
|Analyse de feuilles de calcul Excel|Non|Oui|Oui|Non|
|Archivage et conformité avec Exchange Online et SharePoint Online|Non|Oui|Oui|Non|
|Prise en charge des stratégies de groupe|Non|Oui|Oui|Non|
|Gestion des droits relatifs à l’information à l’aide d’Azure information protection|N °<sup>1</sup>|Oui<sup>6</sup>|Oui<sup>6</sup>|N °<sup>1</sup>|
|Gestion des droits relatifs à l'information à l'aide de Windows Server AD RMS|Oui<sup>2</sup>|Oui<sup>2</sup>|Oui<sup>2</sup>|Oui<sup>2</sup>|
|Prise en charge Office Add-in, ActiveX et BHO|Non|Oui|Oui|Non|
|Accès des clients OneNote aux blocs-notes sur SharePoint Server, SharePoint Online, OneDrive Entreprise et Office 365|Non|Oui|Oui|Non|
|Office Lens|Non|Non|Non|Non|
|Télémétrie Office|Non|Oui<sup>4</sup>|Oui<sup>4</sup>|Non|
|Prise en charge hors connexion pour les applications clients|Non|Oui|Oui|Non|
|Installation optimisée du client côte à côte|Non|Oui|Oui|Non|
|Power Map pour Excel|Non|Oui<sup>4</sup>|Oui<sup>4</sup>|Non|
|Power Pivot pour Excel|Non|Oui<sup>4</sup>|Oui<sup>4</sup>|Non|
|Power Query pour Excel|Non|Oui<sup>4</sup>|Oui<sup>4</sup>|Non|
|Power View pour Excel|Non|Oui<sup>4</sup>|Oui<sup>4</sup>|Non|
|Paramètres d'itinérance|Non|Oui<sup></sup>|Oui<sup></sup>|Non|
|Activation d'ordinateurs partagés|Non|Oui|Oui|Non|
|Support pour bloquer le stockage de fichiers informatiques|Non|Oui|Oui|Non|
|Mises à niveau de la version|Non|Oui<sup>4</sup>|Oui<sup>4</sup>|Non|
|Volume activation (KMS/MAK)|Non|Non|Non|Non|

> <sup>1</sup> Azure information protection n’est pas inclus, mais peut être acheté en tant que module complémentaire distinct et permet d’activer les fonctionnalités de gestion des droits relatifs à l’information (IRM). Certaines fonctionnalités Azure information protection nécessitent un abonnement aux applications Microsoft 365 pour entreprise, qui ne sont pas incluses dans Office 365 Government ou Office 365 Government.
<br/><sup>2</sup> Windows Server AD RMS est un serveur local qui doit être acheté et géré séparément afin d’activer les fonctionnalités IRM prises en charge.
<br/><sup>3</sup> Skype entreprise Basic est disponible pour tous les clients. Le client de bureau Skype Entreprise est une application installée localement qui fournit des fonctionnalités de présence, de messagerie instantanée et de conférence pour les plans Office 365 comprenant Skype Entreprise Online. Microsoft 365 Apps for Enterprise et Office 365 Enterprise E3 incluent l’application Skype complète, qui inclut des fonctionnalités supplémentaires telles que la prise en charge de la téléphonie avancée, l’archivage et les fonctionnalités de conformité. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> pas encore disponible dans les environnements GCC High ou DOD, mais bientôt disponible.
<br/><sup>5</sup> pour plus d’informations, consultez [la rubrique utilisation d’Outlook pour iOS et Android dans le nuage communautaire du gouvernement](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) .
<br/><sup>6</sup> pas encore disponible dans l’environnement DoD Office 365, mais bientôt disponible.
<br/><sup>7</sup> les applications sont entièrement disponibles dans les clouds gouvernementaux, à l’exception des fonctionnalités spécifiques qui ne sont pas disponibles pour le moment. Pour plus d’informations, consultez la rubrique [disponibilité des fonctionnalités des applications Office](#office-application-and-feature-availability-in-government-plans) .

## <a name="office-application-and-feature-availability-in-government-plans"></a>Disponibilité des fonctionnalités et des applications Office dans les plans gouvernementaux

Les applications Office suivantes sont disponibles dans les nuages des gouvernements ; Toutefois, certaines fonctionnalités basées sur le Cloud peuvent ne pas être disponibles actuellement, comme indiqué dans le tableau.<br><br>

|Application/fonctionnalité|GCC|GCC High|DOD|
|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui **ne sont** pas disponibles pour le moment :||||
|animations 3D incorporées et modèles 3D|Non|Non|Non|
|Types de données|Non|Non|Non|
|Remplissage instantané|Non|Non|Non|
|Idées (Insight services)|Non|Non|Non|
|Intégration améliorée avec Power BI (éléments visuels personnalisés, créer des graphiques PBI directement à partir d’Excel)|Non|Non|Non|
|Entrée manuscrite numérique intelligente|Non|Non|Non|
|Groupes Office 365|Non|Non|Non|
|Données graphiques croisés dynamiques connectées à des tableaux croisés|Non|Non|Non|
|PowerPivot|Non|Non|Non|
|Publier sur Power BI|Non|Non|Non|
|Collaboration en temps réel (présence, co-création régulière, conversation en document)|Non|Non|Non|
|Shared with Me|Non|Non|Non|
|Recherche intelligente|Non|Non|Non|
|Graphiques : compartimentage de soleil, cascade, histogramme, cartes, chronologie, entonnoir|Non|Non|Non|
|Historique des versions|Non|Non|Non|
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) est entièrement disponible dans les clouds gouvernementaux, à l’exception des fonctionnalités suivantes, qui **ne sont** pas disponibles pour le moment :|**GCC**|**GCC High**|**DOD**|
|Notification par courrier électronique|N °<sup>1</sup>|N °<sup>1</sup>|Non|
|Insérer une image|N °<sup>1</sup>|N °<sup>1</sup>|Non|
|Insérer une vidéo|N °<sup>1</sup>|N °<sup>1</sup>|Non|
|Mathématiques|N °<sup>1</sup>|N °<sup>1</sup>|Non|
|Intégration d’Office|N °<sup>1</sup>|N °<sup>1</sup>|Non|
|Formulaires de groupe les plus récents|N °<sup>4</sup>|Oui|Oui|
|Partage externe<sup>3</sup>|Oui|Non|Non|
|Forms Pro|Non|Non|Non|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui **ne sont** pas disponibles pour le moment :|**GCC**|**GCC High**|**DOD**|
|Recherche|Non|Non|Non|
|Entrée manuscrite numérique intelligente|Non|Non|Non|
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui **ne sont** pas disponibles pour le moment :|**GCC**|**GCC High**|**DOD**|
|Sons Office (Some)|Non|Non|Non|
|Échange dynamique de données (DDE) désactivé par défaut|Non|Non|Non|
|Dictée|N °<sup>1</sup>|N °<sup>1</sup>|N °<sup>1</sup>|
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui **ne sont** pas disponibles pour le moment :|**GCC**|**GCC High**|**DOD**|
|Recherche intelligente|Non|Non|Non|
|Sons Office (Some)|Non|Non|Non|
|modèles 3D et animations incorporées 3D|Non|Non|Non|
|Graphiques : cartes|Non|Non|Non|
|Entrée manuscrite numérique intelligente|Non|Non|Non|
|Légendes et sous-titres en direct dans PowerPoint|Non|Non|Non|
|Autocar de présentateur|Non|Non|Non|
|Shared with Me|Non|Non|Non|
|Intégration de Skype entreprise avec le partage|Non|Non|Non|
|Historique des versions|Non|Non|Non|
|Groupes Office 365|Non|Non|Non|
|Collaboration en temps réel (présence, co-création régulière, conversation en document)|Non|Non|Non|
|Dictée|N °<sup>1</sup>|N °<sup>1</sup>|N °<sup>1</sup>|
|Réutilisation de diapositives|Non|Non|Non|
|Le **tableau blanc de Microsoft** dans les clouds gouvernementaux n’est actuellement disponible que sur les clients Hub, et non sur le bureau.|**GCC**<sup>2</sup>|**GCC High**<sup>2</sup>|**DoD**<sup>2</sup>|
|Insérer des pense-bêtes, du texte et des images|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|
|Entrée manuscrite en forme et entrée manuscrite en tableau|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|
|Entrée manuscrite Beautification|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|
|Convertir une image en entrée manuscrite|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|
|Vérificateur d'accessibilité|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|Oui<sup>2</sup> <br/>|
|Modèles dynamiques (KANBAN, SWOT, etc.)|Non|Non|Non|
|Collaboration en temps réel|Non|Non|Non|
|Présence en temps réel|Non|Non|Non|
|Réactions sur le contenu|Non|Non|Non|
|Galerie de tableaux blancs, notamment partagés avec vous|Non|Non|Non|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui **ne sont** pas disponibles pour le moment :|**GCC**|**GCC High**|**DOD**|
|Recherche intelligente|Non|Non|Non|
|Recherche|Non|Non|Non|
|Sons Office|Non|Non|Non|
|modèles 3D|Non|Non|Non|
|animations 3D incorporées|Non|Non|Non|
|Recommandations|Non|Non|Non|
|Assistant C.V.|Non|Non|Non|
|Graphiques de carte|Non|Non|Non|
|Entrée manuscrite numérique intelligente|Non|Non|Non|
|Shared with Me|Non|Non|Non|
|Conversion|Non|Non|Non|
|Intégration de Skype entreprise avec le partage|Non|Non|Non|
|Historique des versions|Non|Non|Non|
|Groupes Office 365|Non|Non|Non|
|Conversation contextuelle avec co-auteurs : conversion avec les co-auteurs dans le document|Non|Non|Non|
|Dictée|N °<sup>1</sup>|N °<sup>1</sup>|N °<sup>1</sup>|

Pour la disponibilité des fonctionnalités de Microsoft teams au sein de GCC/GCC High/DoD, consultez la [Description du service Microsoft teams](https://docs.microsoft.com/office365/servicedescriptions/teams-service-description).
> <sup>1</sup> disponibilité à venir.
<br/><sup>2</sup> disponibilité sur un concentrateur de surface local (non connecté).
<br/><sup>3</sup> le partage externe est disponible pour l’environnement GCC. En savoir plus sur l’activation ou l’activation de [Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) pour votre organisation. Le partage externe est désactivé pour les environnements GCC High et DOD. les utilisateurs au sein de votre organisation peuvent effectuer les opérations suivantes : remplir un formulaire et envoyer des réponses, [dupliquer et partager un formulaire en tant que modèle](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f), [co-auteur ou collaborer sur un formulaire](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b), et [accéder aux résultats de formulaire](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).
<br/><sup>4</sup> la fonctionnalité des formulaires de groupe récents est désactivée pour l’environnement GCC. Toutefois, les utilisateurs peuvent toujours accéder aux formulaires de groupe en sélectionnant un groupe spécifique sous l’onglet Formulaires de groupe.
