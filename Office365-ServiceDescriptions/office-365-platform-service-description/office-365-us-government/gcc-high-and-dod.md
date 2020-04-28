---
title: Office 365 GCC High et DoD
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Découvrez les engagements uniques et les différences des environnements Office 365 GCC High et DoD par rapport à l’environnement commercial Office 365.
ms.openlocfilehash: ac769bf832d1aa3454596d5aad1c2a8b3769e6d2
ms.sourcegitcommit: a11ee730139cd7822ee69d50fa2dd554e0c239ff
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/28/2020
ms.locfileid: "43914780"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High et DoD

Pour satisfaire les exigences uniques et en constante évolution du département américain de la Défense, ainsi que des fournisseurs conservant ou traitant des informations non classées contrôlées par le département de la Défense (CUI), ou soumis aux réglementations ITAR (International Traffic in Arms Regulations), Microsoft propose des environnements GCC High et DoD. Ceux-ci sont disponibles via les licences en volume. Les organisations intéressées suivent un processus de validation pour vérifier leur admissibilité avant l’établissement d’un environnement. Les essais ne sont pas disponibles pour le moment.  
  
Veuillez contacter votre équipe de compte ou votre partenaire favori pour en savoir plus ou démarrer le processus de validation. Pour plus d’informations sur l’achat, consultez [la rubrique Microsoft 365 Government-Comment acheter](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy).
  
## <a name="how-to-use-this-service-description-section"></a>Utilisation de cette section Description du service

La description du service Office 365 pour le gouvernement américain est conçue pour servir de superposition à la description de service générale d’Office 365. Elle définit les engagements uniques et les différences par rapport aux offres Office 365 Entreprise.
  
## <a name="compliance"></a>Conformité

GCC High et DoD répondent aux critères de conformité concernant les certifications et accréditations suivantes :  
  
- Le programme fédéral de gestion des risques et d’autorisations sur FedRAMP, y compris les contrôles de sécurité et les améliorations de contrôle décrits dans la publication spéciale 800-53 de l’Institut NIST (National Institute of Standards and Technology).
    
- Les contrôles de sécurité et les améliorations apportées au contrôle pour le guide des exigences de sécurité de Cloud Computing (SRG) du département de la Défense des États-Unis pour les informations jusqu'au niveau d'impact 5 (L5).
    
Les abonnés du département de la Défense à Office 365 bénéficieront des services fournis par l’environnement exclusif du DoD satisfaisant aux exigences du guide SRG DOD L5. Les abonnés extérieurs au département de la Défense bénéficieront des services de l’environnement de la Défense du gouvernement américain, qui est évalué au niveau de L5 mais utilise la segmentation L4.
  
## <a name="background-screening"></a>Filtrage des antécédents 

Le personnel d’Office 365 ne dispose pas d’un accès permanent à l’environnement de production GCC High et DoD. Toutes les personnes demandant une élévation temporaire des autorisations qui leur accorderait l’accès au contenu client doivent d’abord faire l’objet des vérifications des antécédents suivantes.
  
|||
|:-----|:-----|
|**Recherche de personnel et vérifications d’arrière-plan de Microsoft**<sup>1</sup> <br/> |**Description** <br/> |
|Informations d'identification personnelle Citoyenneté  <br/> |Vérification de la citoyenneté américaine  <br/> |
|Vérification de l'expérience professionnelle  <br/> |Vérification de l'expérience professionnelle sur sept (7) ans  <br/> |
|Vérification de la formation professionnelle  <br/> |Vérification du plus haut diplôme obtenu  <br/> |
|Recherche du numéro de sécurité sociale américain (SSN)  <br/> |Vérification de la validité du numéro de sécurité sociale fourni  <br/> |
|Vérification du casier judiciaire  <br/> |Recherche de crimes et délits au niveau étatique, régional et local et au niveau fédéral dans le casier judiciaire sur sept (7) ans  <br/> |
|Liste du Bureau du contrôle des avoirs étrangers (OFAC)  <br/> |Validation par rapport à la liste du Département du Trésor répertoriant les groupes avec lesquels les personnes américaines ne sont pas autorisées à réaliser des transactions commerciales ou financières  <br/> |
|Liste du Bureau de l'industrie et de la sécurité (BIS)  <br/> |Validation par rapport à la liste du Département du Commerce répertoriant les individus et entités exclus de toute activité d'exportation  <br/> |
|Liste rouge du Bureau des contrôles commerciaux en matière de défense (DDTC)  <br/> |Validation par rapport à la liste du Département d'État répertoriant les individus et entités avec lesquels il est interdit de mener des activités d'exportation liées à l'industrie de la défense  <br/> |
|Vérification des empreintes digitales  <br/> |Vérification des antécédents par empreintes digitales par rapport aux bases de données du FBI  <br/> |
|Département de la Défense IT-2  <br/> |Les personnes demandant une élévation des autorisations en matière de données client ou d'accès administratif privilégié aux capacités de service DOD SRG L5 sont soumises à l'arbitrage du département de la Défense IT-2 qui prend sa décision sur la base d'une enquête niveau 3 de l'OPM  <br/> |

<sup>1</sup> concerne uniquement le personnel disposant d’un accès temporaire ou permanent au contenu client hébergé dans Office 365 US GCC-High or DoD Clouds.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>Nuances de fonctionnalités basées sur une architecture cloud compatible

Les abonnements dans les environnements GCC High et DoD incluent les fonctionnalités principales d’Exchange Online, SharePoint et Skype entreprise. Étant donné les exigences de certification et d’accréditation accrues de l’infrastructure, certaines fonctionnalités diffèrent entre les offres commerciales générales d’Office 365 et celles qui sont disponibles dans GCC High et DoD.
  
### <a name="exchange-online"></a>Exchange Online

 **Prise en charge de la messagerie unifiée Exchange Online pour le système IP-PBX local**: l'intégration des systèmes IP-PBX locaux avec la messagerie unifiée Exchange Online n'est pas prise en charge dans les abonnements GCC High et DoD. 
  
### <a name="file-sharing"></a>Partage de fichiers

Les utilisateurs disposent de plusieurs options pour partager des fichiers et des dossiers dans SharePoint et OneDrive. Toutes les options sont disponibles dans les environnements GCC High et DoD. Pour en savoir plus sur la gestion de ces options, consultez la rubrique [Manage Sharing Settings](/sharepoint/turn-external-sharing-on-or-off). Lorsque les utilisateurs partagent l’option « personnes spécifiques » et sélectionnent des personnes à l’extérieur de l’organisation, SharePoint envoie généralement un code de vérification dans le message électronique. Les destinataires doivent entrer le code pour accéder à l’élément partagé. C’est le cas lorsque les utilisateurs dans les grandes organisations GCC partagent des personnes dans des organisations non GCC, et inversement. (Pour plus d’informations sur l’expérience de partage externe, voir [que se passe-t-il lorsque les utilisateurs partagent](/sharepoint/external-sharing-overview#what-happens-when-users-share).) Toutefois, lorsqu’un utilisateur d’une organisation GCC-High partage des personnes dans une autre organisation GCC-High, un compte invité est créé pour le destinataire dans Azure AD, et il se connecte avec son nom d’utilisateur et son mot de passe. 

Les [demandes de fichiers](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) ne sont pas disponibles pour le gouvernement Office 365.

En outre, les adresses de messagerie électronique non GCC associées aux profils utilisateur ne sont pas prises en charge et n’autorisent pas l’envoi de messages électroniques d’alerte. Par exemple, l’utilisateur local A reçoit une adresse de messagerie Gmail, puis est synchronisée avec une organisation Azure GCC High. L’utilisateur A accède à une bibliothèque et crée une alerte pour les modifications. L’alerte n’est pas envoyée à l’adresse Gmail.
  

### <a name="skype-for-business-online"></a>Skype Entreprise Online

 **PSTN Calling &amp; PSTN Conferencing** - Due to the requirement to use the Public Switched Telephone Network (PSTN) for telephony-oriented services, PSTN Calling &amp; PSTN Conferencing services are currently not available in GCC High and DoD.

### <a name="microsoft-teams"></a>Microsoft Teams

**Système téléphonique et conférence audio (via le routage direct)**: le système téléphonique et l’audioconférence pour les environnements GCC High et DoD sont fournis via le routage direct. Pour plus d’informations, consultez la documentation relative au niveau de service ici :

- [Système téléphonique via le routage direct](https://docs.microsoft.com/microsoftteams/here-s-what-you-get-with-phone-system)
- [Audioconférence avec routage direct pour GCC High et DoD](https://docs.microsoft.com/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>Identité

L’authentification multifacteur avec un modèle d’identité fédéré permet d’utiliser des cartes PIV et CAC.
  
### <a name="yammer"></a>Yammer

Yammer Enterprise n’est pas disponible dans les environnements GCC High et DoD.
  
## <a name="customer-support"></a>Service client

Microsoft vous rappelle de ne pas partager d’informations contrôlées, sensibles ou confidentielles avec le personnel du support technique dans le cadre de votre incident de support technique lors de l’utilisation d’Office 365 GCC High/DOD, au moins jusqu’à ce que vous confirmiez l’autorisation de l’agent de support technique à consulter ou accéder à ces données.

Microsoft s’engage à protéger votre [confidentialité](https://privacy.microsoft.com/privacystatement)). Toutefois, la prise en charge du service GCC High/DoD de Office 365 n’est pas incluse dans la limite d’accréditation de service et ne fournit pas de services de conformité FedRAMP, DOD SRG, ITAR, IRS 1075 ou CJIS.
