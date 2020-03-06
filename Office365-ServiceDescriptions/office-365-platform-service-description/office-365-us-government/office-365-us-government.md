---
title: Office 365 pour le gouvernement américain
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: En réponse aux exigences uniques et évolutives du secteur public américain, Microsoft a créé des plans Office 365 pour le gouvernement américain (ou Office 365). Cet article fournit une vue d’ensemble des fonctionnalités spécifiques aux environnements Office 365 gouvernementaux.
ms.openlocfilehash: d94134443ffa106fa162690908825ab295d733e5
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545717"
---
# <a name="office-365-us-government"></a>Office 365 pour le gouvernement américain

En réponse aux exigences uniques et évolutives du secteur public américain, Microsoft a créé des plans Office 365 pour le gouvernement américain (ou Office 365). Cette section fournit une vue d’ensemble des fonctionnalités spécifiques aux environnements Office 365 gouvernementaux. Nous vous recommandons de lire cette section supplémentaire parallèlement aux [descriptions de service Office 365 ](../../office-365-service-descriptions-technet-library.md).
  
## <a name="how-to-use-this-service-description"></a>Utilisation de cette description de service

La description du service Office 365 pour le gouvernement américain est conçue pour servir de superposition à la description de service générale d’Office 365. Elle définit les engagements uniques et les différences par rapport aux offres Office 365 Entreprise.
  
## <a name="about-office-365-us-government-environments"></a>À propos des environnements Office 365 pour le gouvernement américain

Les plans Office 365 pour le gouvernement américain sont proposés sous forme d'abonnements mensuels et peuvent être concédés sous licence pour un nombre illimité d'utilisateurs. 
  
- L’environnement **GCC d’Office 365** fournit la conformité aux exigences fédérales pour les services Cloud, notamment FedRAMP modérée et les exigences en matière de systèmes d’information sur la justice pénale et sur la fiscalité fédérale (types de données CJI et FTI). 
    
- Les environnements **GCC High et DoD d’Office 365** sont conformes aux directives relatives aux exigences en matière de sécurité du département de la défense, du supplément DFARS (Defense Federal acquisition Regulations) et du trafic international en matière de réglementations sur les armes (ITAR). 
    
Outre les caractéristiques et les fonctionnalités d'Office 365, les organisations qui utilisent Office 365 pour le gouvernement américain bénéficient des fonctionnalités suivantes, qui sont propres à Office 365 pour le gouvernement américain :
  
- Le contenu client de votre organisation est logiquement séparé du contenu client relevant des services commerciaux de Microsoft Office 365.
    
- Le contenu client de votre organisation est stocké aux États-Unis.
    
- L'accès au contenu client de votre organisation est limité à des membres du personnel de Microsoft triés sur le volet.
    
- Office 365 pour le gouvernement américain est conforme aux certifications et accréditations requises pour les clients du secteur public américain.
  
## <a name="customer-eligibility"></a>Conditions d’éligibilité des clients

Office 365 pour le gouvernement américain est disponible pour (1) les institutions publiques nationales, régionales, tribales et territoriales des États-Unis, et (2) d'autres entités qui gèrent des données soumises à des réglementations ou des exigences gouvernementales, et qui requièrent l'utilisation d'Office 365 pour le gouvernement américain pour assurer le respect de ces réglementations et exigences, sous réserve d'éligibilité. Les contrôles d'éligibilité menés par Microsoft consistent en la confirmation du traitement de données soumises à la Réglementation américaine sur le trafic d'armes au niveau international (ITAR), de données judiciaires soumises à la politique des services d'information sur les informations de justice criminelle (CJIS) du FBI, ou d'autre données faisant l'objet de contrôles ou de réglementations gouvernementales. Dans le cadre de ces contrôles, il peut être exigé une preuve d'enregistrement auprès du département d'État des États-Unis dans le cas des données ITAR, ou encore une caution délivrée par une entité gouvernementale ayant des exigences spécifiques en matière de gestion des données. Office 365 DoD-Environment est destiné à l’usage exclusif du ministère de la défense des États-Unis.
  
Bien que les critères d’éligibilité soient cohérents entre les offres gouvernementales Office 365, Microsoft accepte uniquement les langues de contrat DFARS et ITAR pour l’environnement hautement rapide.
  
En cas de questions sur ces conditions d'éligibilité pour Office 365 pour le gouvernement américain, les entités sont invitées à consulter leur équipe de compte.
  
Lors du renouvellement du contrat d'un client pour Office 365 pour le gouvernement américain, les conditions d'éligibilité doivent faire l'objet d'un nouveau contrôle.
  
## <a name="customer-content-located-within-the-united-states"></a>Contenu client situé aux États-Unis

Les services Office 365 pour le gouvernement américain sont fournis à partir de centres de données physiquement situés aux États-Unis. Le contenu client suivant est enregistré au repos dans des centres de données situés physiquement uniquement aux États-Unis : 
  
- Contenu de boîte aux lettres Exchange Online (corps de courrier électronique, entrées de calendrier et contenu de pièces jointes)
    
- Contenu de site SharePoint Online et fichiers stockés dans ce site
    
- Conversations archivées Skype entreprise, documents téléchargés et sessions de tableau blanc

- Threads de conversation permanente Microsoft teams
    
> [!NOTE]
> Dans le cas d'une utilisation normale, Skype Entreprise ne stocke pas le contenu client, mais si ce stockage se produit, il sera réalisé dans des centres de données aux États-Unis. 
  
Si vos utilisateurs sont situés aux États-Unis tout en utilisant Office pour le Web (anciennement appelé Office Web Apps) ou si vous adoptez l’utilisation des services ADFS (Active Directory Federation Services) 2,0 et que vous configurez des stratégies pour vous assurer que vos utilisateurs se connectent aux services via un seul si GN-on, tout contenu client temporairement mis en cache dans Office pour le Web sera situé aux États-Unis.
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 pour le gouvernement américain et des services tiers

Office 365 permet d'intégrer des applications tierces dans des sites SharePoint Online, Skype Entreprise, les applications Office incluses dans Office 365 ProPlus (telles que Word, Excel, PowerPoint et Outlook) et Outlook Web App. En outre, Office 365 prend en charge l'intégration avec des fournisseurs de services tiers. Ces applications et services tiers peuvent impliquer le stockage, la transmission et le traitement de données client de votre organisation sur des systèmes tiers situés en dehors de l'infrastructure Office 365 et qui ne sont donc pas couverts par la conformité Office 365 et les engagements de protection des données. Nous vous recommandons de consulter les déclarations de confidentialité et de conformité fournies par les parties tierces lors de l'évaluation de l'utilisation appropriée de ces services pour votre organisation.
  
## <a name="restricted-data-access-by-administrators"></a>Accès aux données limité par les administrateurs

L’accès à Office 365 le contenu client du gouvernement américain par les administrateurs Microsoft est limité au personnel filtré. Pour plus d’informations sur les niveaux de filtrage, reportez-vous à la page Description de service pour chaque environnement respectif (GCC ou GCC High et DoD). 

  
## <a name="fasttrack-center-onboarding-assistance"></a>Assistance à l’intégration du centre FastTrack

Avec le centre FastTrack pour Office 365<sup>1</sup>, vous travaillez à distance avec des spécialistes FastTrack pour obtenir votre environnement Office 365 prêt à être utilisé et planifier le déploiement et l’utilisation au sein de votre organisation. Le processus de FastTrack propose des services pour l’adoption utilisateur et l’intégration.  
  
L’intégration se compose des éléments suivants :
  
- Intégration de base : tâches requises pour la configuration du client et l’intégration à Azure Active Directory (Azure AD) si nécessaire. L’intégration de base fournit également la ligne de base pour l’intégration d’autres services éligibles.
    
- Intégration de services les tâches d’intégration de service de migration permettent de créer des scénarios dans votre client. La migration des données (y compris la messagerie électronique et les fichiers) est décrite dans la [migration de données](https://aka.ms/whatcanmigrate). <sup>2</sup>

Les services d’adoption par les utilisateurs sont composés de tâches qui fournissent des instructions pour vous permettre de vérifier que vos utilisateurs sont informés des services éligibles et peuvent les utiliser pour générer de la valeur commerciale. Cette aide est offerte en parallèle aux activités d’intégration.
  
Vous trouverez des informations spécifiques sur le processus du centre FastTrack [ici](https://aka.ms/whatistheprocess). Pour une répartition des rôles et des responsabilités des engagements, veuillez consulter les [responsabilités de FastTrack](https://aka.ms/whatdoesftcdo) ainsi que [vos responsabilités](https://aka.ms/whatdowedo).
  
> <sup>1</sup> vous devez acheter au moins 50 licences dans la liste des [offres éligibles](https://aka.ms/whocanbenefit) pour recevoir les services FastTrack.
<br/><sup>2</sup> les services de migration de données sont disponibles pour les clients Office 365 avec 500 ou plus de licences.
  
## <a name="data-migrations-performed-by-fasttrack"></a>Migrations de données effectuées par FastTrack

Les clients qui choisissent l’avantage de migration [FastTrack](https://fasttrack.microsoft.com/) devront accorder l’accès à l’équipe qui gère leurs migrations de données. Ces personnes sont des citoyens américains et sont soumises aux tests de base suivants avant d’effectuer des migrations pour les clients d’Office 365 des services publics américains.
  
||||
|:-----|:-----|:-----|
|**Filtrage en arrière-plan** <br/> |**GCC** <br/> |**GCC High et DoD** <br/> |
|Vérification de la citoyenneté américaine  <br/> |Oui  <br/> |Oui  <br/> |
|Vérification de l’historique des emplois  <br/> |Oui  <br/> |Oui  <br/> |
|Vérification de l’éducation  <br/> |Oui  <br/> |Oui  <br/> |
|Recherche de numéro de sécurité sociale (SSN)  <br/> |Oui  <br/> |Oui  <br/> |
|Vérification de l’historique pénal (7 ans)  <br/> |Oui  <br/> |Oui  <br/> |
     
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 pour le gouvernement américain et Azure Government ExpressRoute

Office 365 les clients du gouvernement américain peuvent utiliser les services ExpressRoute gouvernementaux pour se connecter en privé aux services Office 365 pris en charge au lieu de se connecter sur Internet.
  
Pour plus d’informations, telles que les fournisseurs pris en charge, les modèles de tarification et plus encore, consultez les [informations Azure ExpressRoute](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409).
  
Pour plus d’informations sur la prise en charge d’Azure ExpressRoute par Office 365, consultez la rubrique [Azure ExpressRoute pour office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)
  
## <a name="system-requirements"></a>Configuration requise

Pour connaître la configuration requise pour installer et utiliser les plans Office 365 pour le gouvernement américain, reportez-vous à la page [Configuration requise pour Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) sur le site des produits [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409). 
  
## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Pour plus d’informations sur &amp; le centre de sécurité conformité et des liens vers des informations supplémentaires et une disponibilité, voir [Centre de sécurité &amp; conformité Office 365](../../office-365-platform-service-description/office-365-securitycompliance-center.md).
  
## <a name="service-availability-for-each-plan"></a>Disponibilité des services pour chaque plan

Chaque plan Office 365 inclut un certain nombre de services, comme Exchange Online et SharePoint Online. Le tableau suivant présente les services disponibles dans chaque plan Office 365 pour le gouvernement américain.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Services Office 365** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Office pour le web  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Office 365 ProPlus  <br/> |Non <br/> |Oui <br/> |Oui <br/> |Non  <br/> |
|Exchange Online  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Exchange Online Protection  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|SharePoint Online  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|OneDrive Entreprise  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |Oui<sup>1</sup> <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>1</sup> <br/> |
| Système de téléphonie vocale, audioconférence  <br/> |N °<sup>2</sup> <br/> |N °<sup>2</sup> <br/> |Oui <sup>5</sup> <br/> |Non  <br/> |
|Power BI Pro  <br/> |N °<sup>2</sup> <br/> |N °<sup>2</sup> <br/> |Oui  <br/> |N °<sup>2</sup> <br/> |
|Project Online  <br/> |N °<sup>2</sup> <br/> |N °<sup>2</sup> <br/> |N °<sup>2</sup> <br/> |N °<sup>2</sup> <br/> |
|Visio pour le web  <br/> |N °<sup>6</sup> <br/> |N °<sup>6</sup> <br/> |N °<sup>6</sup> <br/> |N °<sup>6</sup> <br/> |
|Yammer Enterprise  <br/> |N °<sup>4</sup> <br/> |N °<sup>4</sup> <br/> |N °<sup>4</sup> <br/> |N °<sup>4</sup> <br/> |
   
> <sup>1</sup> Skype entreprise Basic est disponible pour tous les clients. Le client de bureau Skype Entreprise est une application installée localement qui fournit des fonctionnalités de présence, de messagerie instantanée et de conférence pour les plans Office 365 comprenant Skype Entreprise Online. Office 365 ProPlus, G3 et G5 incluent l’application Skype complète, qui inclut des fonctionnalités supplémentaires, telles que la prise en charge de la téléphonie avancée, l’archivage et les fonctionnalités de conformité. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> non inclus, mais peut être acheté en tant que module complémentaire distinct. Project Online inclut le client de bureau Project Online dans le cadre de l’abonnement.
<br/> <sup>3</sup> pas encore disponible dans les offres GCC High ou DOD, mais bientôt disponible. 
<br/><sup>4</sup> Yammer Enterprise n’est pas un composant d’Office 365 le gouvernement américain, mais peut être acquis gratuitement en tant qu’offre autonome pour chaque utilisateur titulaire d’une licence pour Office 365 dans GCC. Cette offre est actuellement limitée aux clients qui achètent Office 365 GCC sous les contrats d’entreprise et les contrats d’abonnement Enterprise. Yammer n’est pas disponible dans GCC High ou DoD.
<br/><sup>5</sup> le plan d’appel est un module complémentaire. 
<br/><sup>6</sup> non inclus, mais peut être acheté en tant que module complémentaire distinct. Visio pour le Web inclut l’application de bureau Visio dans le cadre de l’abonnement.

## <a name="platform-features"></a>Fonctionnalités de la plateforme 

Le tableau suivant répertorie les fonctionnalités et les services de la plateforme disponibles dans les plans Office 365 pour le gouvernement américain.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|**Administration d'Office 365** <br/> |||||
|Utiliser le centre d’administration Microsoft 365 pour administrer Office 365  <br/> |Oui<sup>16</sup> <br/> |Oui<sup>16</sup> <br/> |Oui  <br/> |Oui<sup>16</sup> <br/> |
|Gestion des paramètres de service principal à partir d'Office 365  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Utilisation de Windows PowerShell pour gérer Office 365  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Protéger le contenu à l'aide d'Azure Information Protection  <br/> |N °<sup>1</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup>  <br/> |N °<sup>1</sup> <br/> |
|**[Fonctionnalités de la suite Office 365](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Réservations Microsoft  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |
|Courrier électronique de briefing Microsoft  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |
|Microsoft Power Automate  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Microsoft Forms  <br/> |Oui <br/> |Oui <br/> |Oui<br/> |Oui</sup> <br/> |
|API Microsoft Graph  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Microsoft MyAnalytics  <br/> |Non <br/> |Non <br/> |Oui,<sup>17</sup> <br/> |Non <br/> |
|Microsoft Planner  <br/> |Oui <br/> |Oui <br/> |Oui <br/> |Oui <br/> |
|Microsoft PowerApps  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Microsoft StaffHub  <br/> |Non <br/> |Non <br/> |Non <br/> |Non<br/> |
|Microsoft Stream  <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>9, 15, 20</sup>  <br/> |
|Microsoft Sway  <br/> |Non <br/> |Non <br/> |Non <br/> |Non <br/> |
|Microsoft Teams  <br/> |Oui <br/> |Oui <br/> |Oui <br/> |Oui <br/> |
|Office Delve  <br/> |Oui,<sup>17</sup> <br/> |Oui,<sup>17</sup> <br/> |Oui  <br/> |Oui,<sup>17</sup> <br/> |
|Groupes Office 365  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|**[Gestion des comptes d’utilisateur](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Identité de nuage  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Identités fédérées (authentification unique)  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|	Authentification multifacteur  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Authentification par facteur de téléphone  <br/> |Oui<sup>9</sup> <br/> |Oui<sup>9</sup> <br/> |Oui  <br/> |Oui<sup>9</sup> <br/> |
|Configuration du bureau Office 365  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Gestion des utilisateurs avec Office 365  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Téléchargement en bloc à l'aide de fichiers .csv  <br/> |Oui<sup>9</sup> <br/> |Oui<sup>9</sup> <br/> |Oui  <br/> |Oui<sup>9</sup> <br/> |
|Outil de synchronisation d'annuaires  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Migration Exchange (à basculement) simple  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Supprimer des comptes à l'aide d'Office 365  <br/> |Oui <sup>3</sup> <br/> |Oui <sup>3</sup> <br/> |Oui <sup>3</sup> <br/> |Oui<sup>3</sup> <br/> |
|L'administrateur peut réinitialiser le mot de passe de l'utilisateur dans Office 365 ou à l'aide de Windows PowerShell  <br/> |Oui <sup>4</sup> <br/> |Oui <sup>4</sup> <br/> |Oui <sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |
|Les utilisateurs peuvent modifier leur mot de passe  <br/> |Oui <sup>5</sup> <br/> |Oui <sup>5</sup> <br/> |Oui <sup>5</sup> <br/> |Oui<sup>5</sup> <br/> |
|Gestion des licences  <br/> |Oui<sup>7, 8</sup> <br/> |Oui<sup>7, 8</sup> <br/> |Oui<sup>7, 8</sup> <br/> |Oui<sup>7, 8</sup> <br/> |
|Gérer les groupes de sécurité dans Office 365  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Plusieurs rôles d'administrateur disponibles  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Autoriser un partenaire à administrer Office 365 pour vous  <br/> |Oui<sup>11</sup> <br/> |Oui<sup>11</sup> <br/> |Oui<sup>11</sup> <br/> |Oui<sup>11</sup> <br/> |
|Services Azure Active Directory  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|**[Domaines](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Ajouter des domaines personnalisés de 2ème niveau, comme fourthcoffee.com  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Ajouter des domaines personnalisés de 3ème niveau, comme marketing.fourthcoffee.com  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Ajouter jusqu'à 900 domaines personnalisés  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Vérification obligatoire de la possession du domaine pour les domaines personnalisés  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|**[État et continuité du service](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Status information available on the **Service health** or **Service status** page  <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |
|État des alertes individuelles disponible dans le tableau de bord du centre d’administration Microsoft 365  <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |
|Flux RSS **État du service**  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|**[Rapports](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Boîtes aux lettres actives et inactives  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Boîtes aux lettres supprimées et nouvelles  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Groupes nouveaux et supprimés  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Utilisation des boîtes aux lettres  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Types de connexions aux boîtes aux lettres  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Messages entrants et sortants  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Principaux expéditeurs et destinataires  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Détections de courrier indésirable  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Détections de programmes malveillants  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Principaux programmes malveillants pour le courrier électronique  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Correspondances de règles pour le courrier électronique  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Principales correspondances de règles pour le courrier électronique  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Principales correspondances de stratégies DLP pour le courrier électronique  <br/> |Non  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Non <br/> |
|Correspondances de stratégies DLP par gravité pour le courrier électronique  <br/> |Non  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Non <br/> |
|Correspondances de stratégies DLP, de remplacements et de faux positifs pour le courrier électronique  <br/> |Non  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Non <br/> |
|Principales correspondances de règles DLP pour le courrier électronique  <br/> |Non  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Non <br/> |
|Sessions de messagerie instantanée et audio  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Conférences de partage d'application, web et rendez-vous  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Sessions vidéo, de partage d'application et de transfert de fichiers  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Conférences par messagerie instantanée, audio et vidéo  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Rapports de protection de messagerie téléchargeable  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Navigateur utilisé  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Système d'exploitation utilisé  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Créer vos rapports à l'aide des services web de rapport Office 365  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|**[Mises à jour de service](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Mises à jour normales fournies à tous les clients  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Notifications envoyées au centre de messages lorsqu'une action est requise  <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |Oui<sup>15</sup> <br/> |
|Roadmap.office.com pour certaines mises à jour de service  <br/> |N °<sup>10, 13</sup> <br/> |N °<sup>10, 13</sup> <br/> |N °<sup>10, 13</sup> <br/> |N °<sup>10, 13</sup> <br/> |
|Option permettant d’activer la publication ciblée  <br/> |Oui<sup>10</sup> <br/> |Oui<sup>10</sup> <br/> |Oui<sup>10</sup> <br/> |Oui<sup>10</sup> <br/> |
|**[Aide et formation](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Aide en ligne  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Communauté  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Autres ressources d'aide autonome  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Auto-formation  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|**[Réseau](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Protocoles IPv4 et IPv6  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|**Approbation** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|**[Confidentialité, sécurité et transparence](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|Gouvernance des données avancée  <br/> |N °<sup>12</sup> <br/> |N °<sup>12</sup> <br/> |Oui <br/> |N °<sup>12</sup> <br/> |
|Sécurité de l’application cloud  <br/> |N °<sup>12, 15, 19</sup> <br/> |N °<sup>12, 15, 19</sup> <br/> |Oui<sup>15, 19</sup> <br/> |N °<sup>12, 15, 19</sup> <br/> |
|Protection avancée contre les menaces  <br/> |N °<sup>12, 18</sup> <br/> |N °<sup>12, 18</sup> <br/> |Oui<sup>18</sup>  <br/> |N °<sup>12, 18</sup> <br/> |
|Référentiel sécurisé de client  <br/> |N °<sup>12</sup> <br/> |N °<sup>12</sup> <br/> |Oui <br/> |N °<sup>12</sup> <br/> |
|Office 365 Advanced eDiscovery  <br/> |N °<sup>12</sup> <br/> |N °<sup>12</sup> <br/> |Oui  <br/> |N °<sup>12</sup> <br/> |
|Score de sécurité<sup>14</sup> <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>9</sup> <br/> |Oui<sup>, 9</sup> <br/> |Oui<sup>, 9</sup> <br/> |
|Chiffrement des messages Office  <br/> |Non  <br/> |Oui <br/> |Oui <br/> |Non  <br/> |
|Intelligence des menaces  <br/> |N °<sup>12</sup> <br/> |N °<sup>12</sup> <br/> |Oui <br/> |N °<sup>12</sup> <br/> |
|**[Conformité](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|Évaluations SAS 70 / SSAE16  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Certification ISO 27001  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Clauses types de l'UE  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|« Sphère de sécurité » de l'UE  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Accord associé HIPAA-Business  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Autorisation d'exploitation FISMA  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Accord de traitement de données Microsoft  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|PCI-DSS niveau 1  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Données PAN sous régie PCI  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |
|**[Continuité de service](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Utilisation de BlackBerry Internet Service (BIS)  <br/> |N °<sup>2</sup> <br/> |N °<sup>2</sup> <br/> |N °<sup>2</sup> <br/> |N °<sup>2</sup> <br/> |
|**[Partenaires](../../office-365-platform-service-description/partners.md)** <br/> |||||
|Création d'invitations à participer à la version d'évaluation et de bons de commande pour un client utilisant le plan spécifié  <br/> |N °<sup>11</sup> <br/> |N °<sup>11</sup> <br/> |N °<sup>11</sup> <br/> |N °<sup>11</sup> <br/> |
|Administration déléguée  <br/> |N °<sup>11</sup> <br/> |N °<sup>11</sup> <br/> |N °<sup>11</sup> <br/> |N °<sup>11</sup> <br/> |
|**[Contrat de niveau de service](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|**[Droits d’utilisation de logiciels](../../office-365-platform-service-description/product-use-rights.md)** <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
   
> <sup>1</sup> Azure information protection n’est pas inclus, mais peut être acheté en tant que module complémentaire distinct et permet d’activer les fonctionnalités de gestion des droits relatifs à l’information (IRM). Certaines fonctionnalités Azure information protection nécessitent un abonnement à Office 365 ProPlus, qui n’est pas inclus dans Office 365 gouvernement G1 ou Office 365 Government F1. > 
<br/><sup>2</sup> les clients BBCS et bis existants peuvent continuer à utiliser le service. Les nouveaux clients ne sont pas acceptés. 
<br/><sup>3</sup> si vous utilisez la synchronisation d’annuaires, vous devez supprimer des comptes ou modifier des mots de passe à l’aide d’Active Directory, plutôt que du portail Office 365 ou en utilisant le module Azure Active Directory pour Windows PowerShell. 
<br/><sup>4</sup> si vous utilisez la synchronisation de mot de passe, les utilisateurs doivent changer leur mot de passe dans l’annuaire Active Directory local. 
<br/><sup>5</sup> pour découvrir comment définir des stratégies de gestion de mot de passe en libre-service pour les utilisateurs, consultez la rubrique [gestion des mots de passe dans Azure ad](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/). 
<br/><sup>6</sup> vous ne pouvez avoir qu’un seul site Web public avec Office 365, sauf si vous avez effectué une mise à niveau à partir d’une version antérieure d’Office 365. Dans ce cas, vous avez deux sites web publics, mais un seul d’entre eux peut être hébergé avec un nom de domaine personnalisé. Pour plus d’informations sur l’utilisation des deux sites Web pour les abonnements d’entreprise, consultez la rubrique [utilisation de vos deux sites Web publics Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Si vous disposez d’un autre abonnement, en savoir plus sur les sites Web publics pour [en savoir plus sur l’hébergement de sites Web partenaires et sur les sites Web publics dans Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009). 
<br/><sup>7</sup> la réduction des sièges qui ont été achetés avec un escompte de terme peut être soumise à des frais de résiliation anticipée. Ceci n’est pas applicable aux abonnements payés sur une base mensuelle. 
<br/><sup>8</sup> les plans suivants ne prennent pas en charge les modifications de siège de licence à partir du centre d’administration 365 de Microsoft : Office 365 gouvernement G1, Office 365 gouvernement G3, Office 365 gouvernement F1. 
<br/><sup>9</sup> pas encore disponible dans GCC High, mais bientôt disponible.
<br/><sup>10</sup> pour Office 365 gouvernement G1, G3 et F1, version ciblée et la feuille de route Office 365 pour les entreprises ; Toutefois, il peut y avoir des différences ou des retards pour les mises à jour de service spécifiques en raison des [exigences de conformité](https://www.microsoft.com/trust-center).
<br/><sup>11</sup> pas encore disponible dans les offres gouvernementales Office 365, mais bientôt disponible. 
<br/><sup>12</sup> non inclus, mais peut être acheté séparément en tant que module complémentaire dans GCC. 
<br/><sup>13</sup> non pris en charge pour les offres gouvernementales Office 365. 
<br/><sup>14</sup> disponible à [https://securescore.office.com](https://securescore.office.com)l’adresse. Nécessite des autorisations d'administration. Pour plus d'informations, consultez l'article [Présentation de Secure Score d'Office 365](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-secure-score).
). 
<br/><sup>15</sup> pas encore disponible dans l’environnement DOD, mais bientôt disponible. 
<br/><sup>16</sup> le centre d’administration n’inclut pas l’analyse de l’utilisation dans les environnements DoD ou GCC High.
<br/><sup>17</sup> non pris en charge pour les environnements GCC High ou DoD.
<br/><sup>18</sup> le hameçonnage pour l’emprunt d’identité d’utilisateur et de domaine et l’aide à l’usurpation ne sont pas encore disponibles dans GCC High et DoD.
<br/><sup>19</sup> pas encore disponible dans l’environnement GCC, mais bientôt disponible.
<br/><sup>20</sup> consommation uniquement pour Microsoft Stream : pas de publication ni de partage. 
  
## <a name="office-application-availability-and-enterprise-value"></a>Disponibilité de l’application Office et valeur entreprise

Le tableau suivant présente les fonctionnalités de l'application Office disponibles dans les plans Office 365 pour le gouvernement américain.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Fonctionnalité** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|**Applications Office** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup> <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup> <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup> <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup> <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup> <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Microsoft Forms<sup>7</sup>| Oui <br/> | Oui <br/>| Oui <br/> | Non <br/> |
|Tableau blanc Microsoft<sup>7</sup>| Non <br/> | Oui <br/> | Oui <br/> | Non <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|[Skype Entreprise](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |Oui<sup>3</sup> <br/> |Oui  <br/> |Oui  <br/> |Oui<sup>3</sup> <br/> |
|[Office pour Mac pour Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57) <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|[Office Mobile pour iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |Oui  <br/> |Oui<sup></sup> <br/> |Oui<sup></sup> <br/> |Oui  <br/> |
|[Office Mobile pour Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |Oui  <br/> |Oui<sup></sup> <br/> |Oui<sup></sup> <br/> |Oui  <br/> |
|[Office Mobile pour Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |Oui  <br/> |Oui<sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |Oui  <br/> |
|Office Mobile pour tablettes Windows 10 <br/> |Oui  <br/> |Oui<sup></sup> <br/> |Oui<sup></sup> <br/> |Oui  <br/> |
|Outlook pour iOS et Android<sup>5, 4</sup>  <br/> |Oui <br/> |Oui <br/> |Oui <br/> |Oui <br/> |
|**Valeur entreprise** <br/> |**Office 365 Secteur Public G1** <br/> |**Office 365 pour le gouvernement G3** <br/> |**Office 365 Secteur Public G5** <br/> |**Office 365 gouvernement F1** <br/> |
|Cinq installations par utilisateur sur PC ou Mac  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Mise en service automatisée du compte d'utilisateur  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |Oui  <br/> |
|Interface utilisateur multilingue  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Déploiement poussée du client  <br/> |Non  <br/> |Oui<sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |Non  <br/> |
|Prise en charge du client pour le serveur Exchange local  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Prise en charge du client pour SharePoint local  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Contrôle des mises à jour logicielles  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Comparer les bases de données  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Virtualisation des services Bureau  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Comparer les feuilles de calcul Excel  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Analyse de feuilles de calcul Excel  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Archivage et conformité avec Exchange Online et SharePoint Online  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Prise en charge des stratégies de groupe  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Gestion des droits relatifs à l’information à l’aide d’Azure information protection  <br/> |N °<sup>1</sup> <br/> |Oui<sup>6</sup> <br/> |Oui<sup>6</sup> <br/> |N °<sup>1</sup> <br/> |
|Gestion des droits relatifs à l'information à l'aide de Windows Server AD RMS  <br/> |Oui<sup>2</sup> <br/> |Oui<sup>2</sup> <br/> |Oui<sup>2</sup> <br/> |Oui<sup>2</sup> <br/> |
|Prise en charge Office Add-in, ActiveX et BHO  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Accès des clients OneNote aux blocs-notes sur SharePoint Server, SharePoint Online, OneDrive Entreprise et Office 365  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Office Lens  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |
|Télémétrie Office  <br/> |Non  <br/> |Oui<sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |Non  <br/> |
|Prise en charge hors connexion pour les applications clients  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Installation optimisée du client côte à côte  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Power Map pour Excel  <br/> |Non  <br/> |Oui<sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |Non  <br/> |
|Power Pivot pour Excel  <br/> |Non  <br/> |Oui<sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |Non  <br/> |
|Power Query pour Excel  <br/> |Non  <br/> |Oui<sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |Non  <br/> |
|Power View pour Excel  <br/> |Non  <br/> |Oui<sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |Non  <br/> |
|Paramètres d'itinérance  <br/> |Non  <br/> |Oui<sup></sup> <br/> |Oui<sup></sup> <br/> |Non  <br/> |
|Activation d'ordinateurs partagés  <br/> |Non  <br/> |Oui <br/> |Oui <br/> |Non  <br/> |
|Support pour bloquer le stockage de fichiers informatiques  <br/> |Non  <br/> |Oui  <br/> |Oui  <br/> |Non  <br/> |
|Mises à niveau de la version  <br/> |Non  <br/> |Oui<sup>4</sup> <br/> |Oui<sup>4</sup> <br/> |Non  <br/> |
|Volume activation (KMS/MAK)  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |Non  <br/> |
   
> <sup>1</sup> Azure information protection n’est pas inclus, mais peut être acheté en tant que module complémentaire distinct et permet d’activer les fonctionnalités de gestion des droits relatifs à l’information (IRM). Certaines fonctionnalités Azure information protection nécessitent un abonnement à Office 365 ProPlus, qui n’est pas inclus dans Office 365 gouvernement G1 ou Office 365 Government F1. 
<br/><sup>2</sup> Windows Server AD RMS est un serveur local qui doit être acheté et géré séparément afin d’activer les fonctionnalités IRM prises en charge. 
<br/><sup>3</sup> Skype entreprise Basic est disponible pour tous les clients. Le client de bureau Skype Entreprise est une application installée localement qui fournit des fonctionnalités de présence, de messagerie instantanée et de conférence pour les plans Office 365 comprenant Skype Entreprise Online. Office 365 ProPlus et Office 365 Enterprise E3 incluent l’application Skype complète, qui inclut des fonctionnalités supplémentaires, telles que la prise en charge de la téléphonie avancée, l’archivage et les fonctionnalités de conformité. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables). 
<br/><sup>4</sup> pas encore disponible dans les environnements GCC High ou DOD, mais bientôt disponible.
<br/><sup>5</sup> pour plus d’informations, consultez [la rubrique utilisation d’Outlook pour iOS et Android dans le nuage communautaire du gouvernement](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) .
<br/><sup>6</sup> pas encore disponible dans l’environnement DoD Office 365, mais bientôt disponible.
<br/><sup>7</sup> les applications sont entièrement disponibles dans les clouds gouvernementaux, à l’exception des fonctionnalités spécifiques qui ne sont pas disponibles pour le moment. Pour plus d’informations, consultez la rubrique [disponibilité des fonctionnalités des applications Office](#office-application-and-feature-availability-in-government-plans) .

## <a name="office-application-and-feature-availability-in-government-plans"></a>Disponibilité des fonctionnalités et des applications Office dans les plans gouvernementaux

Les applications Office suivantes sont disponibles dans les nuages des gouvernements ; Toutefois, certaines fonctionnalités basées sur le Cloud peuvent ne pas être disponibles actuellement, comme indiqué dans le tableau.

|||||
|-----|-----|-----|-----|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui ne sont pas disponibles pour le moment : | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|animations 3D incorporées et modèles 3D | Non <br/> | Non <br/> | Non <br/> |
|Types de données | Non <br/> | Non <br/> | Non <br/> |
|Remplissage instantané | Non <br/> | Non <br/> | Non <br/> |
|Idées (Insight services) | Non <br/> | Non <br/> | Non <br/> |
|Intégration améliorée avec PowerBI (éléments visuels personnalisés, créer des graphiques PBI directement à partir d’Excel) | Non <br/> | Non <br/> | Non <br/> |
|Entrée manuscrite numérique intelligente | Non <br/> | Non <br/> | Non <br/> |
|Groupes Office 365 | Non <br/> | Non <br/> | Non <br/> |
|Données graphiques croisés dynamiques connectées à des tableaux croisés | Non <br/> | Non <br/> | Non <br/> |
|PowerPivot | Non <br/> | Non <br/> | Non <br/> |
|Publier sur PowerBI | Non <br/> | Non <br/> | Non <br/> |
|Collaboration en temps réel (présence, co-création régulière, conversation en document) | Non <br/> | Non <br/> | Non <br/> |
|Shared with Me | Non <br/> | Non <br/> | Non <br/> |
|Recherche intelligente | Non <br/> | Non <br/> | Non <br/> |
|Graphiques : compartimentage de soleil, cascade, histogramme, cartes, chronologie, entonnoir | Non <br/> | Non <br/> | Non <br/> |
|Historique des versions | Non <br/> | Non <br/> | Non <br/> |
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) est entièrement disponible dans les clouds gouvernementaux, à l’exception des fonctionnalités suivantes, qui ne sont pas disponibles pour le moment : | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Notification par courrier électronique | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> | Non <br/> | 
|Insérer une image | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> | Non <br/> |
|Insérer une vidéo | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> | Non <br/> |
|Mathématiques | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> | Non <br/> |
|Intégration d’Office | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> | Non <br/> |
|Formulaires de groupe les plus récents | N °<sup>4</sup> <br/> | Oui <br/> | Oui <br/> |
|Partage externe <sup>3</sup> | Oui <br/> | Non <br/> | Non <br/> |
|Forms Pro | Non | Non | Non |
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui ne sont pas disponibles pour le moment : | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Recherche | Non <br/> | Non <br/> | Non <br/> |
|Entrée manuscrite numérique intelligente | Non <br/> | Non <br/> | Non <br/> |
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui ne sont pas disponibles pour le moment : | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Sons Office (Some) | Non <br/> | Non <br/> | Non <br/> |
|Échange dynamique de données (DDE) désactivé par défaut | Non <br/> | Non <br/> | Non <br/> |
|Dictée | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> |
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui ne sont pas disponibles pour le moment : | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Recherche intelligente | Non <br/> | Non <br/> | Non <br/> |
|Sons Office (Some) | Non <br/> | Non <br/> | Non <br/> |
|modèles 3D et animations incorporées 3D | Non <br/> | Non <br/> | Non <br/> |
|Graphiques : cartes | Non <br/> | Non <br/> | Non <br/> |
|Entrée manuscrite numérique intelligente | Non <br/> | Non <br/> | Non <br/> |
|Légendes et sous-titres en direct dans PowerPoint | Non <br/> | Non <br/> | Non <br/> |
|Autocar de présentateur | Non <br/> | Non <br/> | Non <br/> |
|Shared with Me | Non <br/> | Non <br/> | Non <br/> |
|Intégration de Skype entreprise avec le partage | Non <br/> | Non <br/> | Non <br/> |
|Historique des versions | Non <br/> | Non <br/> | Non <br/> |
|Groupes Office 365 | Non <br/> | Non <br/> | Non <br/> |
|Collaboration en temps réel (présence, co-création régulière, conversation en document) | Non <br/> | Non <br/> | Non <br/> |
|Dictée | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> |
|Réutilisation de diapositives | Non <br/> | Non <br/> | Non <br/> |
|Le **tableau blanc de Microsoft** dans les clouds gouvernementaux n’est actuellement disponible que sur les clients Hub, et non sur le bureau. | **GCC**<sup>2</sup> <br/> | **GCC High**<sup>2</sup> <br/> | **DoD**<sup>2</sup> <br/> |
|Insérer des pense-bêtes, du texte et des images | Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>|
|Entrée manuscrite en forme et entrée manuscrite en tableau | Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>|
|Entrée manuscrite Beautification | Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>|
|Convertir une image en entrée manuscrite | Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>|
|Vérificateur d'accessibilité | Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>| Oui<sup>2</sup> <br/>|
|Modèles dynamiques (KANBAN, SWOT, etc.) | Non <br/> | Non <br/> | Non <br/> |
|Collaboration en temps réel | Non <br/> | Non <br/> | Non <br/> |
|Présence en temps réel | Non <br/> | Non <br/> | Non <br/> |
|Réactions sur le contenu | Non <br/> | Non <br/> | Non <br/> |
|Galerie de tableaux blancs, notamment partagés avec vous | Non <br/> | Non <br/> | Non <br/> |
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) est entièrement disponible dans les nuages du gouvernement, à l’exception des fonctionnalités suivantes, qui ne sont pas disponibles pour le moment : | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Recherche intelligente | Non <br/> | Non <br/> | Non <br/> |
|Recherche | Non <br/> | Non <br/> | Non <br/> |
|Sons Office  | Non <br/> | Non <br/> | Non <br/> |
|modèles 3D | Non <br/> | Non <br/> | Non <br/> |
|animations 3D incorporées  | Non <br/> | Non <br/> | Non <br/> |
|Recommandations  | Non <br/> | Non <br/> | Non <br/> |
|Assistant C.V. | Non <br/> | Non <br/> | Non <br/> |
|Graphiques de carte | Non <br/> | Non <br/> | Non <br/> |
|Entrée manuscrite numérique intelligente | Non <br/> | Non <br/> | Non <br/> |
|Shared with Me | Non <br/> | Non <br/> | Non <br/> |
|Conversion | Non <br/> | Non <br/> | Non <br/> |
|Intégration de Skype entreprise avec le partage | Non <br/> | Non <br/> | Non <br/> |
|Historique des versions | Non <br/> | Non <br/> | Non <br/> |
|Groupes Office 365 | Non <br/> | Non <br/> | Non <br/> |
|Conversation contextuelle avec co-auteurs : conversion avec les co-auteurs dans le document | Non <br/> | Non <br/> | Non <br/> |
|Dictée | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> | N °<sup>1</sup> <br/> |

><sup>1</sup> disponibilité à venir.
<br/><sup>2</sup> disponibilité sur un concentrateur de surface local (non connecté).
<br/><sup>3</sup> le partage externe est disponible pour l’environnement GCC. En savoir plus sur l’activation ou l’activation de [Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) pour votre organisation. Le partage externe est désactivé pour les environnements GCC High et DOD. les utilisateurs au sein de votre organisation peuvent effectuer les opérations suivantes : remplir un formulaire et envoyer des réponses, [dupliquer et partager un formulaire en tant que modèle](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f), [co-auteur ou collaborer sur un formulaire](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b), et [accéder aux résultats de formulaire](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).
<br/><sup>4</sup> la fonctionnalité des formulaires de groupe récents est désactivée pour l’environnement GCC. Toutefois, les utilisateurs peuvent toujours accéder aux formulaires de groupe en sélectionnant un groupe spécifique sous l’onglet Formulaires de groupe.