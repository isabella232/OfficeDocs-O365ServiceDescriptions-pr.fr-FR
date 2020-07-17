---
title: Conseils de licence Microsoft 365 pour la conformité & la sécurité
ms.author: v-trscho
author: vtrscho
audience: ITPro
ms.topic: reference
ms.date: 7/13/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Cet article fournit des conseils en matière de licences pour la conformité de Microsoft 365 afin d’éviter une interruption potentielle des services due à un accès sans licence.
ms.openlocfilehash: 18df87a9bf867c68cf4a711c1f6c9f728d2b6655
ms.sourcegitcommit: f3cf76cada0f11efc225c246fff4346910491659
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/15/2020
ms.locfileid: "45137560"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Conseils de licence Microsoft 365 pour la conformité & la sécurité

Pour les besoins de cet article, un service au niveau du client est un service en ligne qui, &mdash; lorsqu’il est acheté pour n’importe quel utilisateur dans le client (autonome ou en tant que partie de plans Office 365 ou Microsoft 365) &mdash; est activé partiellement ou intégralement pour tous les utilisateurs du client. Bien que certains utilisateurs sans licence puissent techniquement être en mesure d’accéder au service, une licence est requise pour tous les utilisateurs que vous envisagez de bénéficier du service.

> [!NOTE]
> Certains services de client ne sont actuellement pas en mesure de limiter les avantages à des utilisateurs spécifiques. Les efforts doivent être pris pour limiter les avantages du service aux utilisateurs titulaires d’une licence. Cela permettra d’éviter une interruption potentielle des services pour votre organisation une fois que les fonctionnalités de ciblage sont disponibles.

Pour voir les options de licence dont les utilisateurs peuvent bénéficier des fonctionnalités de conformité de Microsoft 365 à compter du 1er avril 2020, téléchargez la comparaison de licences de conformité Microsoft 365 détaillée. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

La protection des identités Azure Active Directory est une fonctionnalité du plan Azure Active Directory Premium P2 qui vous permet de détecter les vulnérabilités potentielles affectant les identités de votre organisation, de configurer des réponses automatiques pour détecter les actions suspectes liées aux identités de votre organisation et d’examiner les incidents suspects et de prendre les mesures appropriées pour les résoudre.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité de SECOPS bénéficient d’un affichage consolidé des utilisateurs avec indicateur et des événements de risque basés sur des algorithmes d’apprentissage automatique. Les utilisateurs finaux bénéficient de la protection automatique offerte par un accès conditionnel basé sur des risques et la sécurité améliorée offerte par les vulnérabilités.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Enterprise Mobility + Security E5/a5, Microsoft 365 E5/a5, Microsoft 365 E5/a5 Security et Azure Active Directory Premium plan 2 permettent à un utilisateur de bénéficier de la protection des identités Azure Active Directory.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités de protection des identités Azure AD sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur Azure AD Identity Protection, voir [qu’est-ce que Azure Active Directory Identity Protection ?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs peuvent étendre la protection des identités Azure AD en affectant des stratégies de risque qui définissent le niveau des réinitialisations de mot de passe et autorisent l’accès aux utilisateurs sous licence uniquement. Pour obtenir des instructions sur l’étendue des déploiements Azure AD Identity Protection, consultez [la rubrique Configure the sign-in Risk Policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-advanced-threat-protection"></a>Azure Advanced Threat Protection

La protection avancée contre les menaces (ATP) est un service Cloud qui permet de protéger les environnements hybrides d’entreprise contre plusieurs types de menaces informatiques ciblées avancées et de menaces Insiders.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité d’SecOp bénéficient de la capacité d’Azure ATP à détecter et à examiner les menaces avancées, les identités compromises et les actions malveillantes. Les utilisateurs finaux bénéficient de leurs données surveillées par Azure ATP.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Enterprise Mobility + Security E5/a5, Microsoft 365 E5/a5, Microsoft 365 E5/a5 Security et Azure protection avancée contre les menaces pour les utilisateurs fournissent les droits nécessaires à Azure ATP.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités Azure ATP sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration d’Azure ATP, voir [Create Your Azure ATP instance](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les services ATP Azure ne sont actuellement pas en mesure de limiter les fonctionnalités à des utilisateurs spécifiques. Vous devez accorder une licence à chaque utilisateur que vous envisagez de bénéficier.

## <a name="office-365-advanced-threat-protection"></a>Office 365 – Protection avancée contre les menaces

La protection avancée contre les menaces (ATP) permet de protéger les organisations contre des attaques sophistiquées telles que le hameçonnage et les programmes malveillants de jour zéro jour. La fonctionnalité ATP fournit également des informations exploitables en mettant en corrélation les signaux provenant d’un large éventail de données pour identifier, hiérarchiser et fournir des recommandations sur la façon de résoudre les menaces potentielles.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

ATP protège les utilisateurs contre les attaques sophistiquées telles que le hameçonnage et les programmes malveillants de jour zéro jour. Pour obtenir la liste complète des services fournis dans plan 1 et plan 2, consultez la rubrique [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ? 

Office 365 Advanced Threat Protection, Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Security, Microsoft 365 Business Premium et Office 365 les plans de protection avancée contre les menaces 1 et 2 permettent à un utilisateur de bénéficier de la protection avancée contre les menaces.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités ATP sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration des stratégies ATP pour les utilisateurs sous licence, consultez la rubrique [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

À l’étendue ATP, suivez les stratégies de déploiement des pièces jointes fiables et des liens fiables :

- Pour plus d’informations sur la configuration des liens fiables pour les utilisateurs sous licence, consultez la rubrique [set up Office 365 ATP Safe Links Policies](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-links-policies).

- Pour plus d’informations sur la configuration des pièces jointes fiables pour les utilisateurs sous licence, consultez la rubrique [set up Office 365 ATP Safe Attachments Policies](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-attachments-policies).

## <a name="office-365-cloud-app-security"></a>Sécurité de l’application cloud Office 365

Office 365 Cloud App Security (OCAS) est un sous-ensemble de la sécurité des applications Cloud de Microsoft, avec des fonctionnalités limitées à Office 365 et sans sécurité supplémentaire pour les applications Cloud tierces et les services IaaS.

OCAS donne aux organisations une visibilité sur leurs applications et services de Cloud de productivité, fournit des analyses sophistiquées pour identifier et combattre les menaces informatiques, et leur permet de contrôler la façon dont les données circulent &mdash; dans Office 365.

Pour comparer les fonctionnalités, consultez la rubrique [differences between Microsoft Cloud App Security and Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

OCAS les identifie, fournit une protection contre les menaces dans Office 365 et contrôle les applications qui ont l’autorisation d’accéder aux données.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Office 365 E5/a5/G5 fournit les droits nécessaires pour qu’un utilisateur bénéficie de OCAS.
Pour plus d’informations, reportez-vous à la feuille de données [Microsoft Cloud App Security Licensing](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités OCAS sont activées au niveau du client pour tous les utilisateurs au sein du client.

Pour plus d’informations sur la configuration du service, voir [Basic Setup for Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs peuvent étendre les déploiements OCAS pour appliquer la manière dont certaines applications sont consultées et limiter les groupes d’utilisateurs surveillés par la sécurité des applications Cloud d’Office 365. Pour plus d’informations, reportez-vous à la rubrique [déploiement étendu](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) est une solution CASB (Cloud Access Security Broker) qui donne aux organisations une visibilité sur leurs applications et services Cloud, fournit des analyses sophistiquées pour identifier et combattre les menaces informatiques, et leur permet de contrôler la façon dont les données transitent &mdash; dans n’importe quelle application Cloud.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

MCAS identifie et évalue l’ombre, fournit une protection contre les menaces entre les applications Cloud First et tierces, et protège les informations des applications Cloud de première et tierces.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

MCAS, Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Security, Microsoft 365 E5/a5/G5 la conformité et la protection des informations Microsoft 365 fournissent les droits nécessaires à un utilisateur pour bénéficier de MCAS.

Azure AD P1 fournit les droits permettant à un utilisateur de bénéficier des fonctionnalités de découverte dans MCAS.

Pour bénéficier des fonctionnalités de contrôle d’application d’accès conditionnel dans MCAS, les utilisateurs doivent également être titulaires d’une licence pour Azure Active Directory P1, inclus dans Enterprise Mobility + Security E3/a3/G3, Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E3/a3/G3, Microsoft 365 E5/a5/G5 et Microsoft 365 E5/a5/G5 Security.

Pour bénéficier de l’étiquetage automatique, les utilisateurs doivent disposer d’une licence pour Azure information protection P2, inclus dans Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5/G5, conformité Microsoft 365 E5/a5/G5, et Microsoft 365 la protection et la gouvernance des informations.

Pour plus d’informations, reportez-vous à la feuille de données [Microsoft Cloud App Security Licensing](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités MCAS sont activées au niveau du client pour tous les utilisateurs au sein du client.

Pour plus d’informations sur la configuration des stratégies de sécurité de l’application Cloud Microsoft pour les utilisateurs titulaires d’une licence, voir [Microsoft Cloud App Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs peuvent étendre les déploiements MCAS aux utilisateurs titulaires d’une licence à l’aide des fonctionnalités de déploiement étendues disponibles dans le service. Pour plus d’informations, reportez-vous à la rubrique [déploiement étendu](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-defender-atp"></a>Microsoft Defender – Protection avancée contre les menaces

Microsoft Defender ATP est une solution de sécurité de point de terminaison qui inclut une évaluation et une gestion des vulnérabilités basées sur des risques ; fonctionnalités de réduction de la surface d’attaque ; protection de nouvelle génération basée sur le comportement et le Cloud ; détection et réponse aux points de terminaison (EDR); l’analyse et la correction automatiques ; et services de chasse gérés. Consultez la page [Microsoft Defender ATP](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?rtc=1) pour en savoir plus.

### <a name="which-users-benefit-from-the-service"></a>Quels sont les utilisateurs qui bénéficient du service ?

Les utilisateurs sous licence de Windows 10 entreprise E5, Windows 10 éducation a5, Microsoft 365 E5 (M365 E5) qui incluent Windows 10 entreprise E5, Microsoft 365 E5 sécurité, Microsoft 365 a5 (M365 a5) peuvent bénéficier de Microsoft Defender ATP.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité de SecOP tirent parti des fonctionnalités de sécurité de point de terminaison de Microsoft Defender ATP pour effectuer une protection préventive, une détection après effraction, une enquête automatisée et une réponse aux menaces avancées. Les utilisateurs finaux bénéficient d’événements malveillants surveillés par Microsoft Defender ATP.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités ATP de Microsoft Defender sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur le déploiement, reportez-vous au [Guide de déploiement](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs ATP de Microsoft Defender peuvent utiliser le [contrôle d’accès basé sur un rôle (RBAC)](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) pour créer des rôles et des groupes au sein de l’équipe des opérations de sécurité pour accorder un accès approprié au centre de sécurité Microsoft Defender.

## <a name="information-protection"></a>Protection des informations

La protection des informations aide les organisations à découvrir, classer, étiqueter et protéger des documents et e-mails sensibles. Les administrateurs peuvent définir des règles et des conditions pour appliquer les étiquettes automatiquement, les utilisateurs peuvent appliquer des étiquettes manuellement ou une combinaison des deux peuvent être utilisées, où les utilisateurs reçoivent des recommandations sur l’application d’étiquettes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs ont la possibilité d’appliquer manuellement des étiquettes de confidentialité à leur contenu ou de classer automatiquement leur contenu.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 E5/a5/G5/E3/a3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/a5/E3/a3/F3, AIP plan 1 et AIP plan 2 fournissent les droits permettant à un utilisateur de tirer parti de l’étiquetage de la sensibilité manuelle.

Microsoft 365 E5/a5/G5/E3/a3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP plan 1 et AIP plan 2 permettent à un utilisateur de tirer parti de l’application et de l’affichage des étiquettes de confidentialité dans Power BI et de protéger les données lors de leur exportation de Power BI vers Excel, PowerPoint ou PDF. 

> [!NOTE]
> Power BI est inclus avec Microsoft 365 E5/a5/G5 ; dans tous les autres plans, Power BI doit être concédé sous licence séparément.

Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Compliance, Microsoft 365 information Protection and Governance, Office 365 E5, Office 365 Advanced Compliance, Enterprise Mobility + Security E5 et AIP plan 2 fournissent les droits permettant à un utilisateur de tirer parti de l’étiquetage de la sensibilité automatique.

Pour obtenir des droits spécifiques par licence, reportez-vous à la comparaison des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) N’inclut pas de droits à la classification automatique basée sur l’apprentissage de machine (classifieur de formation).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités de protection des informations sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration des stratégies pour les utilisateurs sous licence, consultez la rubrique activation de la gestion des droits Azure.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Sauf en cas d’utilisation de la fonctionnalité de scanneur AIP, les stratégies peuvent être étendues à des groupes ou des utilisateurs et des registres spécifiques peuvent être modifiées pour empêcher les utilisateurs sans licence d’exécuter des fonctionnalités de classification ou d’étiquetage. Pour obtenir des instructions sur la façon d’étendre les déploiements AIP, consultez [la rubrique Configuration de la stratégie Azure information protection](https://docs.microsoft.com/azure/information-protection/configure-policy).

Pour la fonctionnalité de scanneur AIP, Microsoft ne s’engage pas à fournir des fonctionnalités de classification, d’étiquetage ou de protection des fichiers aux utilisateurs qui ne sont pas titulaires d’une licence.

## <a name="information-governance"></a>Gouvernance des informations

La gouvernance des informations aide les organisations à gérer leurs risques en détectant, en classant, en étiquetant et en gérant leurs données. La gouvernance des informations permet aux organisations de respecter les exigences métiers et réglementaires, ainsi que de réduire leur surface d’attaque en fournissant des fonctionnalités de rétention et de suppression dans leurs données Microsoft 365 et tierces.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité de classer les données à des fins de rétention afin de respecter des stratégies et des réglementations spécifiques.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 F3/Business Premium, Office 365 E1/a1/F3 et les plans Exchange autonomes permettent à un utilisateur d’appliquer manuellement des étiquettes de rétention non enregistrée aux données de boîte aux lettres.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/a1/F3 et les plans SharePoint autonomes fournissent les droits permettant à un utilisateur d’appliquer manuellement des étiquettes de rétention non enregistrée aux fichiers dans SharePoint ou OneDrive. 

Microsoft 365 E5/a5/E3/a3/Business Premium, Office 365 E5/a5/E3/a3, Exchange plan 2 et archivage Exchange Online permettent aux utilisateurs de bénéficier d’une stratégie de rétention de boîte aux lettres de base ou à l’échelle de l’organisation et/ou d’appliquer manuellement une étiquette de rétention non enregistrée aux données de boîte aux lettres.

Microsoft 365 E5/a5/E3/a3, Office 365 E5/a5/E3/a3 et SharePoint plan 2 permettent à un utilisateur de bénéficier d’une stratégie de rétention SharePoint ou OneDrive de base et/ou d’appliquer manuellement une étiquette de rétention non enregistrée aux fichiers dans SharePoint ou OneDrive.

Microsoft 365 E5/a5/E3/a3 et Office 365 E5/a5/E3/a3 permettent à un utilisateur de bénéficier d’une stratégie de rétention de teams.

Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance, Microsoft 365 information Protection and Governance, Office 365 E5/a5 et Office 365 Advanced Compliance permettent aux utilisateurs d’appliquer automatiquement des étiquettes ou des stratégies de rétention. application d’étiquettes ou de stratégies de rétention par défaut, démarrage de la période de rétention d’une étiquette de rétention basée sur un événement personnalisé, déclenchant une révision de disposition manuelle à la fin de la période de rétention de l’étiquette, importation de données tierces via des connecteurs de données natifs

Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance, Microsoft 365 information Protection and Governance permet à un utilisateur de tirer parti de l’application automatique d’étiquettes de rétention basées sur des classifieurs avec apprentissage.

Pour obtenir des droits spécifiques par licence, reportez-vous à la comparaison des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités de gouvernance des informations sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de la gouvernance des informations pour l’application de l’étiquetage automatique et des stratégies pour les utilisateurs titulaires d’une licence, voir [Manage information Governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les fonctionnalités de gouvernance des informations peuvent être appliquées aux utilisateurs titulaires d’une licence dans des emplacements spécifiques (sites d’équipe, sites de groupe, etc.). Pour plus d’informations sur la configuration de la gouvernance des informations pour l’application de l’étiquetage automatique et des stratégies pour les utilisateurs titulaires d’une licence, voir [Manage information Governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gestion des enregistrements

La gestion des enregistrements aide les organisations à répondre à leurs obligations d’archivage réglementaire et de découverte, de classement, d’étiquetage, de rétention et de suppression Defensible dans leurs données Microsoft 365 et tierces.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance, Microsoft 365 information Protection and Governance, Office 365 E5/a5, Office 365 Advanced Compliance fournit les droits nécessaires pour qu’un utilisateur bénéficie de la gestion des enregistrements, notamment la déclaration d’éléments en tant qu’enregistrements, l’application automatique d’étiquettes de rétention ou d’enregistrement et l’exécution de processus de révision de destruction

Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance, Microsoft 365 information Protection and Governance permet à un utilisateur de bénéficier de l’application automatique d’étiquettes de rétention ou d’enregistrement basées sur des classifieurs formés.

Pour obtenir des droits spécifiques par licence, reportez-vous à la comparaison des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité de déclarer le contenu comme un enregistrement et de gérer son processus d’enregistrement complet à partir de la définition et de la déclaration des stratégies par le biais de la destruction Defensible.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités de gestion des enregistrements sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de la gestion des enregistrements pour qu’elle s’applique aux utilisateurs sous licence, consultez la rubrique [gestion des enregistrements dans Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les fonctionnalités de gestion des enregistrements peuvent être appliquées aux utilisateurs titulaires d’une licence dans des emplacements spécifiques (sites d’équipe, sites de groupe, etc.). Pour plus d’informations sur la configuration de la gestion des enregistrements pour qu’elle s’applique aux utilisateurs sous licence, consultez la rubrique [gestion des enregistrements dans Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

## <a name="ediscovery"></a>eDiscovery

eDiscovery fournit des solutions d’enquête et de découverte électronique pour les services informatiques et juridiques au sein de sociétés afin d’identifier, de collecter, de conserver, de réduire et de consulter le contenu lié à une enquête ou un litige avant l’exportation à partir du système Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Un utilisateur bénéficie d’Advanced eDiscovery lorsque l’utilisateur est sélectionné en tant que dépositaire de données (une personne ayant le contrôle administratif d’un document ou d’un fichier électronique) pour un cas.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 E5/a5/G5/E3/a3/G3, Office 365 E5/a5/G5/E3/a3/G3 et Office 365 Advanced Compliance fournissent les droits dont dispose l’utilisateur pour bénéficier de la découverte électronique de base.
Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformité, Microsoft 365 E5/a5 eDiscovery et audit, Office 365 E5/a5/G5 et Office 365 Advanced Compliance fournissent les droits nécessaires à un utilisateur pour bénéficier de la fonctionnalité eDiscovery avancée.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités avancées de découverte électronique sont activées au niveau du client pour tous les utilisateurs au sein du client lorsque les administrateurs affectent des autorisations eDiscovery dans le centre de conformité & Compliance Center.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

les administrateurs eDiscovery peuvent sélectionner des utilisateurs spécifiques comme dépositaires de données pour un cas à l’aide de l’outil de gestion des dépositaires intégré dans Advanced eDiscovery, comme décrit dans [Add dépositaires to a Advanced eDiscovery case](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case).

## <a name="office-365-customer-key"></a>Clé client Office 365

La clé client vous permet de contrôler les clés de chiffrement de votre organisation et de configurer Office 365 afin de les utiliser pour chiffrer vos données au repos dans les centres de données de Microsoft. En d’autres termes, la clé client vous permet d’ajouter une couche de chiffrement qui vous appartient, à l’aide de vos propres clés. Les données de Rest incluent des données à partir d’Exchange Online et de Skype entreprise, qui sont stockées dans des boîtes aux lettres et des fichiers dans SharePoint Online et OneDrive entreprise.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la clé client en faisant en sorte que leurs données soient chiffrées au niveau de la couche d’application à l’aide de clés de chiffrement fournies, contrôlées et gérées par leur propre organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance, Microsoft 365 information Protection and Governance, Office 365 E5/a5 et Office 365 Advanced Compliance fournissent les droits nécessaires à un utilisateur pour bénéficier de la clé client. Pour tirer pleinement parti de la clé client, vous devez également disposer d’un abonnement pour le coffre-fort des clés Azure.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Les clés de chiffrement de clés client Office 365 peuvent être activées pour toutes les données stockées dans les boîtes aux lettres Exchange Online et Skype entreprise, ainsi que pour les fichiers SharePoint Online, OneDrive entreprise et Teams. Pour plus d’informations sur la clé client Office 365, notamment sur la façon de commencer, consultez la rubrique [service Encryption with Customer Key in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Pour attribuer des clés de chiffrement aux données d’une organisation Office 365 et/ou Microsoft 365 pour les utilisateurs titulaires d’une licence, suivez les instructions de déploiement des clés de chiffrement de clé du client.

- Pour les fichiers SharePoint Online, OneDrive entreprise et Teams, les fichiers sur un ou plusieurs sites peuvent être chiffrés à l’aide de la clé client.

- Pour Exchange Online et Skype entreprise, les boîtes aux lettres peuvent être chiffrées à l’aide de la clé client.

## <a name="office-365-customer-lockbox"></a>Demandes Customer Lockbox dans Office 365

Le référentiel sécurisé du client fournit une couche supplémentaire de contrôle en offrant aux clients la possibilité d’accorder une autorisation d’accès explicite pour les opérations de service. En démontrant que des procédures sont en place pour autoriser l’accès explicite aux données, le référentiel sécurisé du client peut également aider les organisations à respecter certaines obligations de conformité telles que HIPAA et FEDRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient du référentiel sécurisé du client s’assurer que personne de Microsoft ne peut accéder à leur contenu pour effectuer une opération de service sans l’approbation explicite du client. Le référentiel sécurisé du client place le client dans le flux de travail d’approbation pour les demandes d’accès à son contenu. Parfois, des ingénieurs Microsoft sont impliqués lors du processus de prise en charge pour dépanner et résoudre les problèmes signalés par les clients. Dans la plupart des cas, les problèmes sont résolus par des outils de télémétrie et de débogage complets que Microsoft a en place pour ses services. Toutefois, dans certains cas, un ingénieur Microsoft peut accéder au contenu client pour déterminer la cause première et résoudre le problème. Customer Lockbox nécessite l’intervention de l’ingénieur pour demander l’accès au client en tant que dernière étape du flux de travail d’approbation. Les organisations peuvent ainsi approuver ou refuser ces demandes, ce qui leur permet de contrôler directement si un ingénieur Microsoft peut accéder aux données de l’utilisateur final de l’organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, conformité Microsoft 365 E5/a5/G5, gestion des risques Insider de Microsoft 365 et Office 365 Advanced Compliance fournissent les droits dont dispose un utilisateur pour bénéficier du référentiel sécurisé du client.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Les administrateurs peuvent activer les contrôles de référentiel sécurisé du client dans le centre d’administration Microsoft 365. Pour plus d’informations, consultez la rubrique [Customer Lockbox in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests). Lorsque le référentiel sécurisé est activé, Microsoft est tenu d’obtenir l’approbation d’une organisation avant d’accéder à son contenu.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Microsoft fournit des demandes d’approbation de contrôle d’accès au client pour les utilisateurs de votre organisation.

## <a name="privileged-access-management-in-office-365"></a>Gestion des accès privilégiés dans Office 365

La [gestion des accès privilégiés](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) fournit un contrôle d’accès granulaire sur les tâches d’administration privilégiée dans Office 365. Une fois le PAM activé, les utilisateurs doivent demander un accès juste-à-temps par le biais d’un flux de travail d’approbation hautement étendu et lié au temps afin de réaliser des tâches élevées et privilégiées.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

L’activation de PAM permet aux organisations de fonctionner avec des privilèges autonomes. Les utilisateurs bénéficient de la couche de défense supplémentaire contre les vulnérabilités résultant d’un accès administratif permanent qui procure un accès non plus fiable à leurs données.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ? 

Office 365 E5/a5, Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance et Microsoft 365 E5/a5 information protection et gouvernance fournissent les droits dont dispose l’utilisateur pour pouvoir bénéficier de PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités de PAM sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration des stratégies de PAM, consultez la rubrique [prise en main de la gestion des accès privilégiés](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les clients peuvent gérer le module PAM par utilisateur grâce à des stratégies de groupe et d’accès approbateur, qui peuvent être appliquées aux utilisateurs sous licence. Pour plus d’informations, consultez la rubrique [gestion des accès privilégiés dans Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 protection contre la perte de données pour Exchange Online, SharePoint Online et OneDrive entreprise

Avec la protection contre la perte de données (DLP) d’Office 365 pour Exchange Online, SharePoint Online et OneDrive entreprise, les organisations peuvent identifier, surveiller et protéger automatiquement les informations sensibles dans les e-mails et les fichiers (y compris les fichiers stockés dans les référentiels de fichiers Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de DLP pour Exchange Online, SharePoint Online et OneDrive entreprise lorsque leurs courriers électroniques et fichiers sont inspectés pour obtenir des informations sensibles, comme configuré dans la stratégie DLP de l’organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 a1/E3/a3/Business, Office 365 E3/a3 et Office 365 la protection contre la perte de données fournit les droits permettant à un utilisateur de bénéficier d’Office 365 DLP pour Exchange Online, SharePoint Online et OneDrive entreprise.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les messages électroniques Exchange Online, les sites SharePoint et les comptes OneDrive sont des *emplacements activés (charges de travail)* pour ces fonctionnalités DLP pour tous les utilisateurs au sein du client. Pour plus d’informations sur l’utilisation des stratégies DLP, consultez la rubrique [vue d’ensemble de la protection contre la perte de données](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs et les utilisateurs exclus dans le centre de sécurité & de sécurité, sous emplacements de **protection contre la perte de données**  >  **Locations**.

## <a name="communication-data-loss-prevention-for-teams"></a>Protection contre la perte de données de communication pour teams

Avec la communication DLP pour Teams, les organisations peuvent bloquer les conversations et les messages de canal contenant des informations sensibles, telles que des informations financières, des informations d’identification personnelle, des informations relatives à la santé ou d’autres informations confidentielles.

### <a name="which-users-benefit-from-the-service"></a>Quels sont les utilisateurs qui bénéficient du service ?

Les utilisateurs titulaires d’une licence Office 365 E5/a5, Microsoft 365 E5/a5, Microsoft 365 information Protection and Governance et Office 365 Advanced Compliance peuvent tirer parti de la gestion de la communication DLP pour Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs bénéficient des informations sensibles dans leurs messages de conversation et de canal sortants inspectés pour obtenir des informations sensibles, comme configuré dans la stratégie DLP de l’organisation.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, la conversation de teams et les messages de canal sont un *emplacement activé (charge de travail)* pour ces fonctionnalités DLP pour tous les utilisateurs au sein du client. Pour plus d’informations sur l’utilisation des stratégies DLP, consultez la rubrique [vue d’ensemble de la protection contre la perte de données](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs et les utilisateurs exclus dans le centre de sécurité & de sécurité, sous emplacements de **protection contre la perte de données**  >  **Locations**.

## <a name="information-barriers"></a>Obstacles aux informations

Les barrières d’informations sont des stratégies qu’un administrateur peut configurer pour empêcher des personnes ou des groupes de communiquer entre eux. Ceci est utile si, par exemple, un service gère des informations qui ne doivent pas être partagées avec d’autres services, ou si un groupe ne doit pas être en mesure de communiquer avec des contacts externes. Les stratégies de barrière des informations empêchent également les recherches et la découverte. Cela signifie que si vous tentez de communiquer avec une personne avec laquelle vous ne devez pas communiquer, vous ne trouverez pas cet utilisateur dans le sélecteur de personnes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient des fonctionnalités de conformité avancées des barrières d’information lorsqu’ils ne sont pas autorisés à communiquer avec d’autres personnes. Par exemple :

| Scénario | Qui a besoin d’une licence ? |
|:-------|:------|
| Deux groupes (groupe 1 et groupe 2) ne peuvent pas communiquer les uns avec les autres (autrement dit, les utilisateurs du groupe 1 ne sont pas autorisés à communiquer avec les utilisateurs du groupe 2, et les utilisateurs du groupe 2 ne sont pas autorisés à communiquer avec les utilisateurs du groupe 1. | Utilisateurs dans les groupes 1 et 2 ||

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance, Microsoft 365 la gestion des risques internes, Office 365 E5/a5 et Office 365 Advanced Compliance fournissent les droits permettant à un utilisateur de tirer parti des barrières de l’information.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Les administrateurs créent et gèrent des stratégies de barrière des informations à l’aide des applets de commande PowerShell dans le centre de sécurité & conformité. Les administrateurs doivent se voir attribuer le rôle administrateur général de Microsoft 365 entreprise, administrateur général Office 365 ou administrateur de conformité pour créer une stratégie de barrière des informations. Par défaut, ces stratégies s’appliquent à tous les utilisateurs du client. Pour plus d’informations sur les barrières d’informations, consultez la rubrique [barrières relatives aux informations dans Microsoft teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs et les utilisateurs exclus dans le centre de sécurité & conformité. Par exemple, si tous les utilisateurs disposent d’une licence pour Office 365 E3 et qu’aucun ne dispose d’une licence pour Office 365 Advanced Compliance/E5, ils n’ont pas besoin de créer de stratégies de barrière des informations pour l’organisation. Pour plus d’informations, consultez la rubrique [barrières relatives aux informations dans Microsoft teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365

Le chiffrement des messages Office 365 (OME) est un service basé sur Azure Rights Management (Azure RMS) qui vous permet d’envoyer des messages chiffrés à des personnes internes ou externes à votre organisation, quelle que soit l’adresse de messagerie de destination (Gmail, Yahoo! Mail, Outlook.com, etc.).

Pour afficher les messages chiffrés, les destinataires peuvent obtenir un code secret à usage unique, se connecter à l’aide d’un compte Microsoft ou se connecter à l’aide d’un compte professionnel ou scolaire associé à Office 365. Les destinataires peuvent également envoyer des réponses chiffrées. Ils n’ont pas besoin d’un abonnement pour afficher les messages chiffrés ou envoyer des réponses chiffrées.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs de messages bénéficient d’un contrôle supplémentaire sur les messages électroniques sensibles fournis par le chiffrement de messages Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 E3/a3, Office 365 E3/a3 et Azure information Protection Plan 1 fournissent les droits permettant à un utilisateur de bénéficier du chiffrement de messages Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Les administrateurs créent et gèrent les stratégies de chiffrement des messages Office 365 dans le centre d’administration Exchange sous règles de **flux de messagerie**  >  **Rules**. Par défaut, ces règles s’appliquent à tous les utilisateurs du client. Pour plus d’informations sur la configuration des nouvelles fonctionnalités de chiffrement de messages Office 365, consultez la rubrique [set up New office 365 message Encryption Capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs doivent appliquer des règles de flux de messagerie pour le chiffrement de messages Office 365 uniquement aux utilisateurs titulaires d’une licence. Pour plus d’informations sur la définition des règles de flux de messagerie, voir [définir des règles de flux de messagerie pour chiffrer les messages électroniques dans Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Chiffrement avancé de messages Office 365

Office 365 Advanced message Encryption aide les clients à respecter les obligations de conformité nécessitant des contrôles plus souples pour les destinataires externes et leur accès aux messages chiffrés. Avec le chiffrement de messages avancé, les administrateurs peuvent contrôler les messages électroniques sensibles partagés en dehors de l’organisation à l’aide de stratégies automatiques pouvant détecter des types d’informations sensibles (par exemple, des informations d’identification personnelle ou des ID d’intégrité ou financières) ou utiliser des mots clés pour améliorer la protection en appliquant des modèles de courrier personnalisés et en expirant l’accès à des e-mails chiffrés En outre, les administrateurs peuvent contrôler les messages électroniques chiffrés accessibles en externe via un portail Web sécurisé en révoquant l’accès à tout moment.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs de messages bénéficient d’un contrôle supplémentaire sur les messages électroniques sensibles fournis par le chiffrement de messages avancé.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Office 365 E5/a5, Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance, Microsoft 365 information Protection and Governance et Office 365 Advanced Compliance fournissent les droits nécessaires pour qu’un utilisateur bénéficie du chiffrement avancé des messages.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Les administrateurs créent et gèrent des stratégies de chiffrement de messages avancées dans le centre d’administration Exchange sous règles de flux de messagerie. Par défaut, ces règles s’appliquent à tous les utilisateurs sur le client. Pour plus d’informations sur la configuration des nouvelles fonctionnalités de chiffrement des messages, consultez la rubrique [set up New Office 365 message Encryption Capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs doivent appliquer des règles de flux de messagerie pour le chiffrement de messages avancé uniquement aux utilisateurs titulaires d’une licence. Pour plus d’informations sur la définition des règles de flux de messagerie, voir [définir des règles de flux de messagerie pour chiffrer les messages électroniques dans Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Conformité des communications

La conformité de la communication dans Microsoft 365 aide à réduire les risques de communication en vous aidant à détecter, capturer et prendre des mesures correctives pour les messages inappropriés dans votre organisation. Vous pouvez définir des stratégies spécifiques qui capturent les messages internes et externes, Microsoft teams ou les communications tierces au sein de votre organisation. Les relecteurs peuvent prendre des mesures correctives appropriées pour s’assurer qu’elles sont conformes aux standards de messages de votre organisation.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les spécialistes de la conformité bénéficient du service en faisant en sorte que les communications de l’Organisation soient surveillées par les stratégies de conformité des communications.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Office 365 E5/a5, Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance et Microsoft 365 Insider Management fournissent les droits permettant à un utilisateur de bénéficier de la conformité de la communication.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Les administrateurs et les spécialistes de la conformité créent des stratégies de conformité de communication dans le centre de conformité Microsoft 365. Ces stratégies définissent les communications et les utilisateurs qui font l’objet d’un examen au sein de l’organisation, définissent les conditions personnalisées que les communications doivent respecter et indiquent qui doit effectuer des révisions.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Les administrateurs choisissent des utilisateurs ou des groupes spécifiques à inclure dans une stratégie de conformité de communication. Lors du choix d’un groupe, il peut également sélectionner des utilisateurs spécifiques dans le groupe à exclure de la stratégie de conformité des communications. Pour plus d’informations sur les stratégies de conformité de communication, consultez [la rubrique communication compliance in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Gestion des risques internes

La gestion des risques initiés est une solution dans Microsoft 365 qui permet de réduire les risques internes en vous permettant de détecter, d’examiner et de prendre des mesures pour les activités à risque au sein de votre organisation.
Les stratégies personnalisées vous permettent de détecter et de prendre des mesures contre les activités malveillantes et malveillantes dans votre organisation, notamment en transférant des cas à Microsoft Advanced eDiscovery si nécessaire. Les analystes de risques de votre organisation peuvent rapidement prendre des mesures appropriées pour s’assurer que les utilisateurs sont conformes aux normes de conformité de votre organisation.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la surveillance des risques de leurs activités.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits pour qu’un utilisateur bénéficie du service ?

Microsoft 365 E5/a5, Microsoft 365 E5/a5 Compliance, et Microsoft 365 la gestion des risques internes de Microsoft, fournit les droits nécessaires pour permettre à un utilisateur de tirer parti de la gestion des risques inSided.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Les stratégies de gestion des risques internes doivent être créées dans le centre de conformité Microsoft 365 et affectées aux utilisateurs.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Lors de la création d’une stratégie dans le centre de conformité Microsoft 365, dans la page **choisir les utilisateurs et les groupes** , sélectionnez **choisir les utilisateurs ou les groupes** pour sélectionner uniquement les utilisateurs sous licence ou, si tous vos utilisateurs disposent d’une licence, vous pouvez activer la case à cocher **tous les utilisateurs et les groupes à extension messagerie** . Pour plus d’informations, consultez la rubrique [prise en main de la gestion des risques initiés](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Stratégies d’accès conditionnel

L’accès conditionnel est l’outil utilisé par Azure Active Directory pour rassembler des signaux, prendre des décisions et appliquer des stratégies d’organisation. L’accès conditionnel est au cœur du plan de contrôle d’identité. Les stratégies d’accès conditionnel les plus simples sont les instructions If-Then. Si un utilisateur souhaite accéder à une ressource, il doit effectuer une action. Exemple : un responsable de la paie souhaite accéder à l’application de paie et est requis pour effectuer l’authentification multifacteur pour y accéder.

### <a name="which-users-benefit-from-the-service"></a>Quels sont les utilisateurs qui bénéficient du service ?

Les utilisateurs sous licence de Enterprise Mobility + Security E3/a3, Microsoft 365 F3/E3/a3/Business Premium et Azure Active Directory Premium plan 1 peuvent bénéficier de stratégies d’accès conditionnel. Les utilisateurs titulaires d’une licence Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5, Microsoft E5 Security et Azure Active Directory Premium plan 2 peuvent bénéficier de la protection des identités (stratégies d’accès conditionnel basées sur les risques).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les experts en matière de sécurité, analystes et professionnels de la sécurité, ont la possibilité d’appliquer des stratégies organisationnelles aux utilisateurs, ce qui les oblige à répondre à certains critères avant d’accorder un accès au contenu de l’entreprise. Les utilisateurs finals peuvent accéder à leur travail où et quand ils choisissent, tout en protégeant les ressources de l’organisation.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, les fonctionnalités d’accès conditionnel sont activées au niveau du client pour tous les utilisateurs au sein du client.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

Pour la protection des identités et l’accès conditionnel, un utilisateur doit être inclus dans un groupe ou ajouté à une stratégie d’accès conditionnel. La condition Users and groups est obligatoire dans une stratégie d’accès conditionnel. Dans votre stratégie, vous pouvez sélectionner **tous les utilisateurs** ou des utilisateurs et des groupes spécifiques. Vous devez sélectionner uniquement les utilisateurs et les groupes sous licence appropriée. Pour plus d’informations, consultez la rubrique [Quelles sont les conditions d’accès conditionnel Azure Active Directory ?](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Audit avancé

Advanced audit in Microsoft 365 fournit une rétention d’un an des journaux d’audit pour les activités de l’utilisateur et de l’administrateur, et permet de créer des stratégies de rétention de journal d’audit personnalisées pour gérer la rétention des journaux d’audit pour d’autres services Microsoft 365. Il permet également d’accéder à des événements cruciaux pour les enquêtes et un accès à bande passante élevée à l’API activité de gestion d’Office 365. Pour plus d’informations, consultez la rubrique [audit avancé dans Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

### <a name="which-users-benefit-from-the-service"></a>Quels sont les utilisateurs qui bénéficient du service ?

Les utilisateurs titulaires d’une licence Office 365 E5, Microsoft 365 E5, conformité à la réglementation Microsoft 365 E5 et Microsoft 365 eDiscovery et audit peuvent tirer parti de l’audit avancé.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Un utilisateur bénéficie d’un audit avancé car les enregistrements d’audit liés à l’activité de l’utilisateur dans les services Microsoft 365 peuvent être conservés pendant un an maximum. En outre, les événements d’audit à valeur élevée sont enregistrés dans un journal, par exemple lorsque des éléments sont consultés ou lus dans la boîte aux lettres d’un utilisateur. Pour plus d’informations, consultez la rubrique [audit avancé dans Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il configuré/déployé ?

Par défaut, l’audit avancé est activé au niveau du client pour toutes les organisations disposant d’un abonnement Office 365 ou Microsoft 365 E5, et fournit automatiquement une rétention d’un an des journaux d’audit pour les activités (effectuées par les utilisateurs disposant de la licence appropriée) dans Azure Active Directory, Exchange et SharePoint. En outre, les organisations peuvent utiliser des stratégies de rétention du journal d’audit pour gérer la période de rétention des enregistrements d’audit générés par l’activité dans d’autres services Microsoft 365. Pour plus d’informations, voir [gérer les stratégies de rétention du journal d’audit](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour ce service ?

La rétention d’un an des journaux d’audit et l’audit des événements cruciaux s’appliquent uniquement aux utilisateurs disposant de la licence appropriée. En outre, les administrateurs peuvent utiliser des stratégies de rétention du journal d’audit pour spécifier des durées de rétention plus courtes pour les journaux d’audit d’utilisateurs spécifiques.
