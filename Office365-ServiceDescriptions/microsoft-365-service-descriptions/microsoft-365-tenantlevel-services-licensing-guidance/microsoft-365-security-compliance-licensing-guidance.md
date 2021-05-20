---
title: Microsoft 365 d’octroi de licences pour la sécurité et & conformité
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Cet article fournit des conseils en matière de licences Microsoft 365 conformité afin d’éviter d’éventuelles interruptions de service dues à un accès sans permis.
ms.openlocfilehash: d4ddb9c492cccef13c86e450c64a2eb6efe61eaa
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546011"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365 de licences pour la conformité à la &amp; sécurité

Aux fins du présente article, un service au niveau du locataire est un service en ligne qui, lorsqu’il est acheté pour tout utilisateur du locataire (autonome ou dans &mdash; le cadre de Office 365 ou Microsoft 365 plans) est activé en partie ou en totalité pour tous les utilisateurs du &mdash; locataire. Bien que certains utilisateurs non titulaires d’un permis puissent techniquement accéder au service, une licence est nécessaire pour tout utilisateur que vous avez l’intention de bénéficier du service.

> [!NOTE]
> Certains services aux locataires ne sont pas actuellement en mesure de limiter les avantages à des utilisateurs spécifiques. Des efforts devraient être déployés pour limiter les avantages du service aux utilisateurs titulaires d’une licence. Cela permettra d’éviter d’éventuelles interruptions de service pour votre organisation une fois que les capacités de ciblage seront disponibles.

Pour voir les options d’octroi de licences à vos utilisateurs pour qu’ils bénéficient de Microsoft 365 de conformité, téléchargez la comparaison détaillée des licences Microsoft 365 conformité. [(PDF)](https://www.microsoft.com/download/details.aspx?id=103010)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=103006)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory La protection de l’identité est une caractéristique du plan P2 Azure Active Directory Premium qui vous permet de détecter les vulnérabilités potentielles affectant l’identité de votre organisation, de configurer des réponses automatisées aux actions suspectes détectées liées à l’identité de votre organisation, d’enquêter sur les incidents suspects et de prendre les mesures appropriées pour les résoudre.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité de SecOps bénéficient d’une vue consolidée des utilisateurs signalés et d’événements de risque basés sur des algorithmes d’apprentissage automatique. Les utilisateurs finaux bénéficient de la protection automatique offerte par l’accès conditionnel fondé sur le risque et de l’amélioration de la sécurité assurée par l’action sur les vulnérabilités.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security et Azure Active Directory Premium Plan 2 offrent à un utilisateur le droit de bénéficier d’une protection Azure Active Directory’identité.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités de protection de l’identité AD Azure sont activées au niveau du locataire pour tous les utilisateurs du locataire. Pour plus d’informations sur la protection de l’identité de la ANNONCE Azure, voir [Qu’est-ce que la protection de l’identité ?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs peuvent définir la protection de l’identité D’Annonce Azure en attribuant des stratégies de risque qui définissent le niveau de réinitialisation des mots de passe et en permettant l’accès uniquement aux utilisateurs autorisés. Pour obtenir des instructions sur la façon d’activer les déploiements de protection d’identité D’Azure, consultez [Comment configurer et activer les stratégies de risque](/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Gouvernance de l’identité

Azure Active Directory La gouvernance d’identité vous permet d’équilibrer les besoins de sécurité et de productivité des employés de votre organisation avec les bons processus et la bonne visibilité. Il utilise la gestion des droits, les examens de l’accès, la gestion privilégiée de l’identité et les politiques sur les conditions d’utilisation pour s’assurer que les bonnes personnes ont le bon accès aux bonnes ressources.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Azure Active Directory La gouvernance d’identité augmente la productivité des utilisateurs en leur rendant plus facile la demande d’accès aux applications, aux groupes et aux Microsoft Teams dans un seul paquet d’accès. Les utilisateurs peuvent également être configurés en tant qu’approbateurs, sans impliquer les administrateurs. Pour les avis d’accès, les utilisateurs peuvent examiner les membres des groupes avec des recommandations intelligentes pour prendre des mesures à intervalles réguliers.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security et Azure Active Directory Premium Plan 2 offrent aux utilisateurs le droit de bénéficier d’une gouvernance Azure Active Directory identitaire.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Les fonctionnalités de gouvernance d’identité D’Azure AD sont activées au niveau des locataires mais implémentées par utilisateur. Pour plus d’informations sur la gouvernance de l’identité de la ANNONCE Azure, [voir Qu’est-ce que la gouvernance de l’identité de la ANNONCE Azure ?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs peuvent élargir la gouvernance de l’identité de la DA Azure en attribuant des packages d’accès, des avis d’accès ou une gestion d’identité privilégiée pour les utilisateurs autorisés uniquement. Pour obtenir des instructions sur la façon d’élargir les déploiements de gouvernance d’identité d’Azure AD, voir :

- [Exigences de licence de gestion des droits Azure AD](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Exigences de licence d’examen de l’accès à l’accès Azure AD](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Exigences de licence pour l’Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender pour l’identité

Microsoft Defender for Identity (anciennement Azure Advanced Threat Protection) est un service cloud qui aide à protéger les environnements hybrides d’entreprise contre de multiples types de cyberattaques ciblées avancées et de menaces internes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité de SecOp bénéficient de la capacité de Microsoft Defender for Identity à détecter et à enquêter sur les menaces avancées, les identités compromises et les actions d’initiés malveillantes. Les utilisateurs finaux bénéficient d’une surveillance de leurs données par Microsoft Defender for Identity.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security et Microsoft Defender for Identity for Users offrent les droits de bénéficier de Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités Microsoft Defender for Identity sont activées au niveau du locataire pour tous les utilisateurs du locataire. Pour plus d’informations sur la configuration d’Azure ATP, consultez [Créer votre Microsoft Defender pour l’instance Identité](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les services Microsoft Defender for Identity ne sont actuellement pas en mesure de limiter les capacités à des utilisateurs spécifiques. Vous devez autoriser tous les utilisateurs dont vous avez l’intention de bénéficier.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender pour Office 365

Microsoft Defender for Office 365 (anciennement Office 365 Advanced Threat Protection) aide à protéger les organisations contre les attaques sophistiquées telles que le phishing et les logiciels malveillants zero-day. Microsoft Defender for Office 365 fournit également des informations exploitables en corrélant les signaux d’un large éventail de données pour aider à identifier, hiérarchiser et fournir des recommandations sur la façon de faire face aux menaces potentielles.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Microsoft Defender for Office 365 les utilisateurs contre les attaques sophistiquées telles que le phishing et les logiciels malveillants zero-day. Pour la liste complète des services fournis dans les plan 1 et plan 2, consultez [Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ? 

Microsoft Defender for Office 365 Plans 1 et 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security et Microsoft 365 Business Premium offrent aux utilisateurs les droits de bénéficier de Microsoft Defender pour Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, Microsoft Defender pour les Office 365 sont activées au niveau du locataire pour tous les utilisateurs au sein du locataire. Pour plus d’informations sur la configuration de Microsoft Defender pour Office 365 politiques pour les utilisateurs sous licence, [consultez Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Pour champ d’application Microsoft Defender Office 365, suivez les stratégies de déploiement des liens sûrs et des pièces jointes sûres :

- Pour plus d’informations sur la configuration de liens sûrs pour les utilisateurs sous licence, [consultez Safe Links dans Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Pour plus d’informations sur la configuration des pièces jointes sûres pour les utilisateurs autorisés, [consultez les pièces jointes sûres dans Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/atp-safe-attachments).

## <a name="office-365-cloud-app-security"></a>Sécurité de l’application cloud Office 365

Sécurité des applications cloud Office 365 (OCAS) est un sous-ensemble de Microsoft Cloud App Security, avec des fonctionnalités limitées à Office 365 et sans sécurité supplémentaire pour les applications cloud tierces et les services IaaS.

OCAS donne aux organisations une visibilité sur leurs applications et services cloud de productivité, fournit des analyses sophistiquées pour identifier et combattre les cybermenaces, et leur permet de contrôler la façon dont les données &mdash; se propagent à travers Office 365.

Pour comparer les fonctionnalités, [voir Différences entre Microsoft Cloud App Security et Sécurité des applications cloud Office 365](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

OCAS découvre Shadow IT, offre une protection contre les menaces à travers Office 365, et peut contrôler quelles applications ont la permission d’accéder aux données.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Office 365 E5/A3/A5/G5 offrent à un utilisateur le droit de bénéficier de l’OCAS.
Pour plus d’informations, consultez la [fiche Microsoft Cloud App Security de licences de licences](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités OCAS sont activées au niveau du locataire pour tous les utilisateurs du locataire.

Pour plus d’informations sur la configuration du service, voir [configuration de base pour Sécurité des applications cloud](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs peuvent mettre en étendue les déploiements OCAS pour faire respecter l’accès à certaines applications et limiter les groupes d’utilisateurs surveillés par Sécurité des applications cloud Office 365. Pour plus d’informations, voir [Déploiement scoped](/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) est une solution cloud access security broker (CASB) qui donne aux entreprises une visibilité sur leurs applications et services cloud, fournit des analyses sophistiquées pour identifier et combattre les cybermenaces, et leur permet de contrôler la façon dont les données circulent &mdash; sur n’importe quelle application cloud.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

MCAS découvre et évalue Shadow IT, offre une protection contre les menaces dans les applications cloud de première et de troisième parties et protège les informations sur les applications cloud de première et de troisième parties.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 Information Protection and Governance offrent aux utilisateurs le droit de bénéficier du MCAS.

Azure AD P1 offre aux utilisateurs le droit de bénéficier des fonctionnalités Discovery de MCAS.

Pour bénéficier des capacités de contrôle des applications d’accès conditionnel dans le MCAS, les utilisateurs doivent également être autorisés pour Azure Active Directory P1, qui est inclus dans Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5, et Microsoft 365 E5/A5/G5 Security.

Pour bénéficier de l’étiquetage automatique côté client, les utilisateurs doivent être agréés pour Azure Information Protection P2, qui est inclus dans Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, et Microsoft 365 Information Protection and Governance.

> [!NOTE]
> L’étiquetage automatique côté serveur nécessite une protection de l’information pour Office 365 - Premium licences `MIP_S_CLP2` (ou `efb0351d-3b08-4503-993d-383af8de41e3` ). Pour référence, consultez les noms [de produits et les identificateurs de plan de service pour l’octroi de licences.](/azure/active-directory/enterprise-users/licensing-service-plan-reference)

Pour plus d’informations, consultez la [fiche Microsoft Cloud App Security de licences de licences](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités MCAS sont activées au niveau du locataire pour tous les utilisateurs du locataire.

Pour plus d’informations sur la configuration Microsoft Cloud App Security politiques pour les utilisateurs titulaires d’une licence, [consultez Microsoft Cloud App Security vue d’ensemble](/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs peuvent mettre en portée les déploiements MCAS aux utilisateurs autorisés en utilisant les capacités de déploiement étendues disponibles dans le service. Pour plus d’informations, voir [Déploiement scoped](/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Gestionnaire de conformité

Simplifiez la conformité et aidez à réduire les risques avec le gestionnaire de la conformité. Compliance Manager aide les organisations à satisfaire aux exigences de réglementation, de normes, de politiques de l’entreprise ou d’autres cadres de contrôle souhaités.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Voici les avantages pour les utilisateurs du service Compliance Manager :

- Traduit des réglementations, des normes, des politiques d’entreprise ou d’autres cadres de contrôle souhaités en langage simple
- Donne accès à une vaste bibliothèque d’évaluations et d’évaluations personnalisées pour répondre à des besoins uniques en matière de conformité
- Cartes réglementaires aux mesures d’amélioration recommandées
- Fournit des conseils étape par étape sur la façon de mettre en œuvre les solutions pour répondre aux exigences réglementaires
- Aide les utilisateurs à prioriser les actions qui auront le plus d’impact sur leur conformité organisationnelle en associant un score à chaque action

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Les clients titulaires de licences E1 et E3/G3 ne pourront accéder qu’à l’évaluation de base de protection des données par défaut. Les clients Office 365 titulaires de licences E5/A5 et Microsoft 365 E5/A5 (conformité, & gouvernance de la protection des informations et SDS eDiscovery et Audit inclus) pourront accéder aux évaluations de base de la protection des données, gdpr, NIST 800-53 et ISO 27001. Les clients ayant un G5 et Microsoft 365 un G5 Office 365 pourront accéder aux niveaux 1 à 53 de la certification du modèle de maturité en matière de cybersécurité (CMMC) de base, gdpr, NIST 800-53, ISO 27001 et certification du modèle de maturité de cybersécurité (CMMC). La fonction d’évaluation personnalisée et les évaluations premium sont réservées aux Office 365 E5/A5/G5 et Microsoft 365 E5/A5/G5. Premium évaluations, telles que FedRAMP Moderate, FedRAMP High et d’autres, seront disponibles à l’achat pour les clients titulaires de licences E5/A5/G5 au cours du premier semestre 2021 via VL, CSP et WebDirect. Contactez votre vendeur Microsoft ou Microsoft Partner pour acheter via les canaux VL ou CSP, respectivement. Pour acheter via WebDirect, voir [WebDirect](https://aka.ms/ComplianceManager/WebDirect).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Le gestionnaire de la conformité est provisionné par défaut pour votre locataire. Les administrateurs définissez les autorisations utilisateur et attribuent des rôles afin que les utilisateurs non administrateurs de votre organisation puissent commencer à utiliser Compliance Manager. Pour plus d’informations, voir [Démarrer avec Compliance Manager : Définir les autorisations utilisateur et attribuer des rôles](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender pour point de terminaison

Microsoft Defender for Endpoint (anciennement Microsoft Defender ATP) est une solution de sécurité de point de terminaison qui inclut des informations et une évaluation basées sur gestion des vulnérabilités le risque; capacités de réduction de surface d’attaque; protection de nouvelle génération basée sur le comportement et alimentée par le cloud; protection évolutive des points de terminaison (PEPT); enquête et assainissement automatiques; et géré les services de chasse. Consultez la page [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) pour en savoir plus.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs autorisés de Windows 10 Entreprise E5, Windows 10 Éducation A5, Microsoft 365 E5/G5, qui comprend Windows 10 Entreprise E5, Microsoft 365 E5/A5/G5 Security, peuvent bénéficier de Microsoft Defender pour Endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité de SecOps bénéficient des capacités de sécurité de Microsoft Defender pour Endpoint afin d’assurer la protection préventive, la détection post-violation, les enquêtes automatisées et la réponse aux menaces avancées. Les utilisateurs finaux bénéficient d’événements malveillants surveillés par Microsoft Defender pour Endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités Microsoft Defender for Endpoint sont activées au niveau du locataire pour tous les utilisateurs du locataire. Pour plus d’informations sur le déploiement, [voir Phases de déploiement](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Microsoft Defender pour les administrateurs Endpoint peut utiliser le contrôle d’accès basé sur les rôles (RBAC) pour créer des rôles et des groupes au sein de l’équipe des opérations de sécurité afin d’accorder un accès approprié aux Centre de sécurité Microsoft Defender. Pour plus d’informations, consultez Gérer [l’accès au portail à l’aide d’un contrôle d’accès basé sur les fonctions](/windows/security/threat-protection/microsoft-defender-atp/rbac).

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365 de classification des données : Aperçu de l’explorateur &amp; d’activité de contenu

Les capacités d’analyse de classification des données sont disponibles dans Microsoft 365 de centre de conformité. Vue d’ensemble montre l’emplacement du contenu numérique et les types d’informations sensibles les plus courants et les étiquettes présentes. Content Explorer offre une visibilité sur la quantité et les types de données sensibles et permet aux utilisateurs de filtrer par étiquette ou type de sensibilité pour obtenir une vue détaillée des endroits où les données sensibles sont stockées. Activity Explorer affiche les activités liées aux données et étiquettes sensibles, telles que les dégradations d’étiquettes ou le partage externe qui pourraient exposer votre contenu à des risques.

Activity Explorer fournit un seul vitre pour les administrateurs afin d’obtenir une visibilité sur les activités liées aux informations sensibles qui sont utilisées par les utilisateurs finaux. Ces données comprennent les activités d’étiquetage, les journaux de prévention des pertes de données (DLP), l’étiquetage automatique, le DLP endpoint et plus encore.

Content Explorer offre aux administrateurs la possibilité d’indexer les documents sensibles stockés dans les Microsoft 365 charge de travail supportées et d’identifier les informations sensibles qu’ils stockent. En outre, Content Explorer aide à identifier les documents classifiés avec des étiquettes de sensibilité et de rétention.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les administrateurs de la protection de l’information et de la conformité peuvent accéder au service pour accéder à ces journaux et données indexées afin de comprendre où les données sensibles sont stockées et quelles activités sont liées à ces données et exécutées par les utilisateurs finaux.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Les utilisateurs titulaires d’une licence de conformité Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Information Protection &amp; Governance et Office 365 E5 peuvent bénéficier d’analyses de classification des données Microsoft 365. 

Microsoft 365 E3/A3/G3 et Office 365 E3/A3/G3 permettent aux utilisateurs de bénéficier uniquement de l’agrégation de données Content Explorer.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités Overview Content et Activity Explorer sont activées au niveau du locataire pour tous les utilisateurs du locataire. Pour plus d’informations sur la configuration de l’analyse de classification des données pour les utilisateurs titulaires d’une licence, voir :

- **Content Explorer**: [Démarrer avec l’explorateur de contenu - Microsoft 365 Compliance | Docs Microsoft](/microsoft-365/compliance/data-classification-content-explorer).
- **Explorateur d’activités** [: Démarrer avec l’explorateur d’activités - Microsoft 365 compliance | Docs Microsoft](/microsoft-365/compliance/data-classification-activity-explorer).
- **Notes de publication de classification des** données : Notes de publication de classification des données - Microsoft 365 conformité [| Docs Microsoft](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Cette fonctionnalité doit être étendue aux utilisateurs qui utilisent activement la solution dans le Microsoft 365 de conformité.

## <a name="information-protection"></a>Protection des informations

La protection de l’information aide les organisations à découvrir, classer, étiqueter et protéger les documents et courriels sensibles. Les administrateurs peuvent définir des règles et des conditions pour appliquer automatiquement les étiquettes, les utilisateurs peuvent appliquer les étiquettes manuellement, ou une combinaison des deux peuvent être utilisées, où les utilisateurs reçoivent des recommandations sur l’application des étiquettes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité d’appliquer manuellement des étiquettes de sensibilité à leur contenu ou en faisant classer automatiquement leur contenu.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 et AIP Plan 2 offrent aux utilisateurs le droit de bénéficier de l’étiquetage de sensibilité manuelle.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 et AIP Plan 2 offrent aux utilisateurs le droit de bénéficier de l’application et de la visualisation d’étiquettes sensibles en Power BI et de protéger les données lorsqu’elles sont exportées de Power BI à Excel, PowerPoint ou PDF. 

> [!NOTE]
> Power BI est inclus avec Microsoft 365 E5/A5/G5; dans tous les autres régimes, Power BI doivent être titulaires d’un permis séparément.

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, protection de l’information Microsoft 365 E5/A5/G5, gouvernance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 et plan 2 de l’AIP offrent aux utilisateurs le droit de bénéficier de l’étiquetage automatique de sensibilité.

Pour des droits spécifiques par licence, consultez les données détaillées Microsoft 365 de licences de conformité. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) N’inclut pas les droits à la classification automatique basés sur Machine Learning (classificateurs ferroviaires).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités de protection de l’information sont activées au niveau du locataire pour tous les utilisateurs du locataire. Pour plus d’informations sur les stratégies de configuration pour les utilisateurs sous licence, voir Activation Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Sauf lors de l’utilisation de la fonction de scanner AIP, les stratégies peuvent être étendues à des groupes ou utilisateurs spécifiques et les registres peuvent être modifiés pour empêcher les utilisateurs non autorisés d’exécuter des fonctionnalités de classification ou d’étiquetage. Pour obtenir des instructions sur la façon d’étendue des déploiements AIP, consultez [la stratégie de protection de l’information Azure](/azure/information-protection/configure-policy).

Pour la fonction de scanner AIP, Microsoft ne s’engage pas à fournir des capacités de classification, d’étiquetage ou de protection des fichiers aux utilisateurs qui ne sont pas titulaires d’une licence.

## <a name="information-governance"></a>Gouvernance de l’information

La gouvernance de l’information aide les organisations à gérer leurs risques en découvrant, classant, étiquetant et régissant leurs données. La gouvernance de l’information permet aux organisations de satisfaire aux exigences commerciales et réglementaires et de réduire leur surface d’attaque en fournissant des capacités de conservation et de suppression dans leurs Microsoft 365 et leurs données tierces.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la capacité de classer les données à des fins de conservation afin de respecter des politiques et des règlements spécifiques.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 et les plans Exchange autonomes offrent à un utilisateur le droit de bénéficier de l’application manuelle d’étiquettes de rétention non enregistreurs aux données de la boîte aux lettres.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 et les plans SharePoint autonomes offrent aux utilisateurs le droit de bénéficier de l’application manuelle d’étiquettes de rétention de documents aux fichiers en SharePoint ou en OneDrive. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plan 2 et Archivage Exchange Online offrent à un utilisateur le droit de bénéficier d’une politique de conservation de la boîte aux lettres à l’échelle de l’organisation ou à l’échelle de l’emplacement et/ou d’appliquer manuellement une étiquette de rétention non enregistrée aux données de la boîte aux lettres.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 et SharePoint Plan 2 offrent aux utilisateurs le droit de bénéficier d’une politique de base de rétention de SharePoint ou de OneDrive et/ou d’appliquer manuellement une étiquette de rétention de documents aux fichiers en SharePoint ou en OneDrive.

Microsoft 365 E5/A5/G5/E3/A3 et Office 365 E5/A5/G5/E3/A3 offrent aux utilisateurs le droit de bénéficier d’une politique de rétention Teams' Œuvre.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5, et Office 365 E5/A5 offrent à un utilisateur le droit de bénéficier de l’application automatique d’étiquettes ou de politiques de rétention, de l’application d’étiquettes ou de politiques de rétention par défaut, du début de la période de conservation d’une étiquette de rétention basée sur un événement personnalisé, du déclenchement d’un examen manuel de la disposition à la fin de la période de conservation de l’étiquette, de l’importation de données tierce par l’intermédiaire de connecteurs de données natifs, de la déclaration d’un fichier d’un enregistrement, de la découverte de contenu étiqueté et de la surveillance de l’activité d’étiquetage.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection, and Governance offrent aux utilisateurs le droit de bénéficier de l’application automatique d’étiquettes de rétention basées sur des classificateurs ferroviaires.

Pour des droits spécifiques par licence, consultez les données détaillées Microsoft 365 de licences de conformité. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités de gouvernance de l’information sont activées au niveau du locataire pour tous les utilisateurs du locataire. Pour plus d’informations sur la configuration de la gouvernance de l’information pour appliquer l’autoétiquetage et les politiques pour les utilisateurs titulaires [d’une licence, voir Microsoft Information Governance Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les fonctionnalités de gouvernance de l’information peuvent être appliquées aux utilisateurs titulaires d’une licence dans des endroits spécifiques (sites d’équipe, sites de groupe, etc.). Pour plus d’informations sur la configuration de la gouvernance de l’information pour appliquer l’autoétiquetage et les politiques pour les utilisateurs titulaires [d’une licence, voir Microsoft Information Governance Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gestion des enregistrements

La gestion des dossiers aide les organisations à s’acquitter de leurs obligations en matière de tenue de dossiers commerciaux et réglementaires en découvrant, classant, étiquetant, conservant et défendant leurs capacités de suppression dans leurs données Microsoft 365 et tierces parties.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5, et Office 365 E5/A5/G5 offrent aux utilisateurs le droit de bénéficier de la gestion des dossiers, y compris la déclaration d’éléments comme documents ou dossiers réglementaires, l’application automatique de étiquettes de conservation ou de dossier et l’exécution de processus d’examen des dispositions (à l’exclusion de l’application automatique d’une étiquette de conservation basée sur des classificateurs ferroviaires).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 Information Protection and Governance offrent à un utilisateur le droit de bénéficier de l’application automatique de étiquettes de rétention ou de disques basées sur des classificateurs ferroviaires.

Pour des droits spécifiques par licence, consultez les données détaillées Microsoft 365 de licences de conformité. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la capacité de déclarer le contenu en tant qu’enregistrement et de gérer leur processus complet d’enregistrement à partir de la définition de la stratégie et de la déclaration par le biais de l’élimination défendable.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités de gestion des dossiers sont activées au niveau du locataire pour tous les utilisateurs du locataire. Pour plus d’informations sur la configuration de la gestion des dossiers pour demander aux utilisateurs autorisés, [voir En savoir plus sur la gestion des Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les fonctionnalités de gestion des dossiers peuvent être appliquées aux utilisateurs titulaires d’une licence dans des endroits spécifiques (sites d’équipe, sites de groupe, etc.). Pour plus d’informations sur la configuration de la gestion des dossiers pour demander aux utilisateurs autorisés, [voir En savoir plus sur la gestion des Microsoft 365](/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Connecteurs de données 

Microsoft fournit des connecteurs de données tiers qui peuvent être configurés dans le centre Microsoft 365 de conformité. Pour une liste de connecteurs de données fournis par Microsoft, consultez le tableau [des connecteurs de données tiers.](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) Ce tableau résume également les solutions de conformité que vous pouvez appliquer aux données tierce après avoir importé et archivé des données en Microsoft 365, et des liens vers les instructions étape par étape pour chaque connecteur.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Le principal avantage de l’utilisation de connecteurs de données pour importer et archiver des données tierce en Microsoft 365 est que vous pouvez appliquer diverses solutions de conformité Microsoft 365 aux données après leur importation. Cela permet de s’assurer que les données non Microsoft de votre organisation sont conformes aux réglementations et aux normes qui affectent votre organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Les licences suivantes offrent aux utilisateurs le droit de bénéficier de connecteurs de données :

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Gouvernance de la protection des &amp; informations
- Microsoft 365 E5/A5/G5 Conformité
- Microsoft 365 E5/A5/G5 Insider Risk Management
- Microsoft 365 E5/A5/G5 eDiscovery and Audit
- Office 365 E5/A5/G5

Pour les connecteurs de données du Microsoft 365 Security &amp; Compliance Center fournis par un partenaire Microsoft, votre organisation aura besoin d’une relation d’affaires avec le partenaire avant de pouvoir déployer ces connecteurs.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Les connecteurs sont configurés à l’aide du centre &amp; de conformité de sécurité et du catalogue connecteur.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les services data connectors sont une valeur au niveau des locataires. Chaque utilisateur destiné à bénéficier de ce service doit être autorisé.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Microsoft Graph API pour la prévention Teams perte de données (DLP)

Plus tôt cette année, [nous avons annoncé l’aperçu public de l’API de notification de Graph Microsoft pour les messages dans Teams](https://go.microsoft.com/fwlink/?linkid=2143888). Cette API permet aux développeurs de créer des applications qui peuvent écouter des messages Microsoft Teams en temps quasi réel et permettre des implémentations de scénarios DLP pour les clients et les ISV. En outre, Microsoft Graph Patch API permet d’appliquer des actions DLP Teams messages.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

[Les capacités de prévention des pertes de données (DLP)](/microsoft-365/compliance/dlp-microsoft-teams) sont largement utilisées dans Microsoft Teams, en particulier lorsque les organisations se sont tournées vers le travail à distance. Si votre organisation dispose de DLP, vous pouvez désormais définir des stratégies qui empêchent les gens de partager des informations sensibles dans un canal Microsoft Teams ou une session de chat.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Vous aurez besoin de l’une des licences suivantes pour obtenir une prise en charge de la protection DLP dans Teams Chat :

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Conformité
- Microsoft 365 E5/A5/G5 Protection de l’information et gouvernance
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

L’accès api est configuré au niveau du locataire.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Microsoft Graph API pour Teams DLP est une valeur au niveau des locataires. Chaque utilisateur destiné à bénéficier de ce service doit être autorisé.

## <a name="ediscovery"></a>eDiscovery

eDiscovery fournit des solutions d’enquête et d’eDiscovery aux services informatiques et juridiques au sein des sociétés afin d’identifier, de collecter, de préserver, de réduire et d’examiner le contenu lié à une enquête ou à un litige avant l’exportation hors du système Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Un utilisateur bénéficie d’Advanced eDiscovery lorsque l’utilisateur est sélectionné comme dépositaire de données (une personne ayant le contrôle administratif d’un document ou d’un fichier électronique) pour une affaire.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 offrent aux utilisateurs les droits de bénéficier de Core eDiscovery.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 eDiscovery and Audit, et Office 365 E5/A5/G5 offrent aux utilisateurs le droit de bénéficier de Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, Advanced eDiscovery fonctionnalités sont activées au niveau du locataire pour tous les utilisateurs du locataire lorsque les administrateurs attribuent des autorisations eDiscovery dans le Centre de &amp; conformité de sécurité.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs eDiscovery peuvent sélectionner des utilisateurs spécifiques comme dépositaires de données pour un cas en utilisant l’outil de gestion de dépositaire intégré dans Advanced eDiscovery tel que [décrit dans Ajouter les dépositaires à un Advanced eDiscovery de données](/microsoft-365/compliance/add-custodians-to-case).

## <a name="customer-key-for-microsoft-365"></a>Clé client pour Microsoft 365

Avec Customer Key, vous contrôlez les clés de chiffrement de votre organisation et configurez des Microsoft 365 pour les utiliser pour chiffrer vos données au repos dans les centres de données Microsoft. En d’autres termes, customer key vous permet d’ajouter une couche de cryptage qui vous appartient, en utilisant vos propres clés. Les données au repos comprennent les données de Exchange Online et Skype Entreprise qui sont stockées dans des boîtes aux lettres et des fichiers dans SharePoint en ligne et OneDrive Entreprise.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la clé client en faisant leurs données à la couche d’application à l’aide de clés de cryptage fournies, contrôlées et gérées par leur propre organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance, et Office 365 E5/A5/G5 offrent aux utilisateurs le droit de bénéficier de la clé client. Pour bénéficier pleinement de la clé client, vous devez également avoir un abonnement pour Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

La clé client pour Microsoft 365 clés de cryptage peut être activée pour toutes les données stockées dans les boîtes aux lettres Exchange Online et Skype Entreprise, ainsi que pour les fichiers SharePoint en ligne, OneDrive Entreprise et Teams. Pour plus d’informations sur la clé client, y compris la façon de commencer, voir le [chiffrement du service avec la clé client](/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Pour Exchange Online et Skype Entreprise, les boîtes aux lettres peuvent être cryptées à l’aide de la clé client. Vous devez configurer Azure avant de pouvoir utiliser la clé client pour Microsoft 365. Consultez [Configurer la clé client](/microsoft-365/compliance/customer-key-set-up) pour les étapes que vous devez suivre pour créer et configurer les ressources Azure requises et les étapes de mise en place de la clé client dans Microsoft 365. Une fois que vous avez terminé la configuration Azure, déterminez quelle stratégie et, par conséquent, quelles clés attribuer aux boîtes aux lettres et aux fichiers de votre organisation. Pour plus d’informations sur la clé client et le contenu concernant les données de Exchange Online, Skype Entreprise, SharePoint Online, OneDrive Entreprise et Teams, consultez [le chiffrement du service avec clé client](/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Demandes Customer Lockbox dans Office 365

Customer Lockbox fournit une couche de contrôle supplémentaire en offrant aux clients la possibilité de donner une autorisation d’accès explicite pour les opérations de service. En démontrant que des procédures sont en place pour l’autorisation explicite d’accès aux données, Customer Lockbox peut également aider les organisations à respecter certaines obligations de conformité telles que HIPAA et FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Customer Lockbox garantit que personne chez Microsoft ne peut accéder au contenu client pour effectuer une opération de service sans l’approbation explicite du client. Customer Lockbox amène le client dans le workflow d’approbation pour les demandes d’accès à leur contenu. Occasionnellement, les ingénieurs Microsoft sont impliqués dans le processus de support pour résoudre et résoudre les problèmes signalés par le client. Dans la plupart des cas, les problèmes sont résolus par des outils étendus de télémétrie et de débogage que Microsoft a mis en place pour ses services. Toutefois, il peut y avoir des cas qui nécessitent un ingénieur Microsoft pour accéder au contenu du client pour déterminer la cause profonde et résoudre le problème. Customer Lockbox nécessite l’intervention de l’ingénieur pour demander l’accès au client en tant que dernière étape du flux de travail d’approbation. Cela donne aux organisations la possibilité d’approuver ou de refuser ces demandes, ce qui leur donne un contrôle direct sur la possibilité pour un ingénieur Microsoft d’accéder aux données de l’utilisateur final des organisations.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5/G5 Insider Risk Management offrent aux utilisateurs le droit de bénéficier de Customer Lockbox.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Les administrateurs peuvent activer customer lockbox dans le centre d Microsoft 365'administration. Pour plus d’informations, [voir Customer Lockbox dans Office 365](/microsoft-365/compliance/customer-lockbox-requests). Lorsque customer lockbox est activé, Microsoft est tenu d’obtenir l’approbation d’une organisation avant d’accéder à l’un de leurs contenus.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Actuellement, le service Customer Lockbox ne peut pas être limité à des utilisateurs spécifiques. Vous devez autoriser tous les utilisateurs dont vous avez l’intention de bénéficier.

## <a name="privileged-access-management-in-office-365"></a>Gestion des accès privilégiés dans Office 365

[La gestion privilégiée de l’accès (PAM)](/microsoft-365/compliance/privileged-access-management-configuration) offre un contrôle d’accès granulaire sur les tâches administratives privilégiées dans Office 365. Après avoir permis à PAM d’accomplir des tâches élevées et privilégiées, les utilisateurs devront demander un accès juste à temps grâce à un workflow d’approbation hautement étendue et limité dans le temps.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

L’activation de PAM permet aux organisations de fonctionner sans privilèges permanents. Les utilisateurs bénéficient de la couche supplémentaire de défense contre les vulnérabilités découlant de l’accès administratif permanent qui fournit un accès illimité à leurs données.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance et Microsoft 365 E5/A5 Information Protection and Governance offrent aux utilisateurs le droit de bénéficier du PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités PAM sont activées au niveau du locataire pour tous les utilisateurs du locataire. Pour plus d’informations sur la configuration des politiques PAM, voir [Démarrer avec la gestion privilégiée de l’accès](/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les clients peuvent gérer PAM par utilisateur par le biais de politiques de groupe d’approbation et d’accès, qui peuvent être appliquées aux utilisateurs titulaires d’une licence. Pour plus d’informations, consultez [la gestion de l’accès privilégié dans Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Cryptage double clé pour Microsoft 365 

Le chiffrement double clé pour Microsoft 365 vous permet de protéger vos données hautement sensibles pour répondre à des exigences spécialisées et de garder le contrôle total de votre clé de chiffrement. Double Key Encryption utilise deux clés pour protéger vos données, avec une clé dans votre contrôle et la deuxième clé stockée en toute sécurité par Microsoft Azure. Pour afficher les données, vous devez avoir accès aux deux touches. Étant donné que Microsoft ne peut accéder qu’à une seule clé, votre clé et aussi vos données ne sont pas disponibles pour Microsoft, ce qui garantit un contrôle total sur la confidentialité et la sécurité de vos données.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient d’un chiffrement double clé en étant en mesure de migrer leurs données chiffrées vers le cloud, ce qui empêche l’accès de tiers tant que la clé reste en contrôle des utilisateurs. Les utilisateurs peuvent protéger et consommer du contenu crypté double clé similaire à tout autre contenu protégé par l’étiquette de sensibilité.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance, et Office 365 E5/A5/G5 offrent aux utilisateurs le droit de bénéficier du chiffrement à double clé.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Double Key Encryption prend en charge la version bureau de Microsoft Office pour Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Pour attribuer des clés de chiffrement aux données d’une Office 365 et/ou d’une organisation Microsoft 365 pour les utilisateurs titulaires d’une licence, suivez les instructions de déploiement du chiffrement à double clé.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 prévention des pertes de données pour Exchange Online, SharePoint en ligne et OneDrive Entreprise

Grâce à la prévention des pertes de données Office 365 (DLP) pour Exchange Online, SharePoint Online et OneDrive Entreprise, les organisations peuvent identifier, surveiller et protéger automatiquement les informations sensibles sur les e-mails et les fichiers (y compris les fichiers stockés dans des dépôts de fichiers Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de DLP pour Exchange Online, SharePoint Online et OneDrive Entreprise lorsque leurs e-mails et fichiers sont inspectés pour obtenir des informations sensibles, telles que configurées dans la politique DLP de l’organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 et Office 365 Data Loss Prevention offrent aux utilisateurs le droit de bénéficier d’un DLP Office 365 pour Exchange Online, SharePoint Online et OneDrive Entreprise.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les Exchange Online, les sites SharePoint et les comptes OneDrive sont *des emplacements activés (charges de travail) pour* ces fonctionnalités DLP pour tous les utilisateurs du locataire. Pour plus d’informations sur l’utilisation des politiques DLP, voir [Aperçu de la prévention des pertes de données](/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs inclus et les utilisateurs exclus du Centre de &amp; conformité à la sécurité, dans le cadre des lieux **de prévention des pertes**  >  **de données.**

## <a name="communication-data-loss-prevention-for-teams"></a>Prévention des pertes de données de communication pour Teams

Avec communication DLP pour Teams, les organisations peuvent bloquer les conversations et canaliser les messages qui contiennent des informations sensibles, telles que des informations financières, des informations d’identification personnelle, des informations liées à la santé, ou d’autres informations confidentielles.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs titulaires d’une licence de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 et Microsoft 365 E5/A5/G5 Information Protection and Governance peuvent bénéficier du DLP communication pour Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs bénéficient d’informations sensibles dans leur chat sortant et de messages de canal inspectés pour les informations sensibles, telles que configurées dans la politique DLP de l’organisation.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les messages Teams chat et de canal sont un *emplacement activé (charge de travail) pour* ces fonctionnalités DLP pour tous les utilisateurs au sein du locataire. Pour plus d’informations sur l’utilisation des politiques DLP, voir [Aperçu de la prévention des pertes de données](/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs inclus et les utilisateurs exclus du Centre de &amp; conformité à la sécurité, dans le cadre des lieux **de prévention des pertes**  >  **de données.**

## <a name="information-barriers"></a>Obstacles aux informations

Le cloisonnement de l’information est la définition de stratégies qu’un administrateur peut configurer pour empêcher des individus ou des groupes de communiquer entre eux. Cela est utile si, par exemple, un ministère traite de l’information qui ne devrait pas être partagée avec d’autres ministères, ou si un groupe doit être empêché de communiquer avec des contacts externes. Les politiques de barrière de l’information empêchent également les recherches et les découvertes. Cela signifie que si vous essayez de communiquer avec quelqu’un avec qui vous ne devriez pas communiquer, vous ne trouverez pas cet utilisateur dans le cueilleur de personnes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient des capacités avancées de conformité des obstacles à l’information lorsqu’ils sont empêchés de communiquer avec d’autres personnes. Les stratégies d’obstacles à l’information peuvent être définies pour empêcher certains segments d’utilisateurs de communiquer avec chacun d’eux ou pour permettre à des segments spécifiques de communiquer uniquement avec certains autres segments. Pour plus d’informations sur la définition des politiques d’obstacle à l’information, voir [Définir les politiques d’obstacle à l’information](/microsoft-365/compliance/information-barriers-policies). Pour les scénarios dans lesquels deux groupes ne peuvent pas communiquer entre eux, les utilisateurs des deux groupes ont besoin d’une licence pour bénéficier du service (voir ci-dessous l’exemple).<br><br>

| Scénario | Qui a besoin d’une licence? |
|:------|:------|
| Deux groupes (groupe 1 et groupe 2) ne peuvent pas communiquer entre eux &nbsp; &nbsp; (c’est-à-dire que &nbsp; les utilisateurs du groupe 1 sont empêchés de communiquer avec les utilisateurs du groupe &nbsp; 2, et les utilisateurs du groupe 2 ne &nbsp; peuvent pas communiquer avec les utilisateurs du groupe &nbsp; 1. | Utilisateurs du groupe &nbsp; 1 et du groupe &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management et Office 365 E5/A5/G5, offrent aux utilisateurs le droit de bénéficier d’obstacles à l’information.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Les administrateurs créent et gèrent des stratégies de barrière d’information en utilisant des cmdlets PowerShell dans le Centre de &amp; conformité de sécurité. Les administrateurs doivent se voir attribuer le rôle Microsoft 365 Entreprise’administrateur mondial, Office 365'administrateur mondial ou administrateur de la conformité pour créer une stratégie de barrière d’information. Par défaut, ces politiques s’appliquent à tous les utilisateurs du locataire. Pour plus d’informations sur les obstacles à [l’information, voir Obstacles à l’information Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs inclus et les utilisateurs exclus dans le Centre de &amp; conformité de sécurité. Par exemple, si tous les utilisateurs sont titulaires d’une licence pour Office 365 E3 et qu’aucun n’est autorisé pour Conformité avancée Office 365/E5, ils n’auraient pas besoin de créer des politiques de barrière d’information pour l’organisation. Si vous souhaitez en savoir plus, veuillez consulter la rubrique [Information barriers in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams) (Cloisonnements de l’information dans Microsoft Teams).

## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365

Le chiffrement des messages Office 365 (OME) est un service basé sur Azure Rights Management (Azure RMS) qui vous permet d’envoyer des messages chiffrés à des personnes internes ou externes à votre organisation, quelle que soit l’adresse de messagerie de destination (Gmail, Yahoo! Mail, Outlook.com, etc.).

Pour afficher les messages chiffrés, les destinataires peuvent obtenir un code secret à usage unique, se connecter à l’aide d’un compte Microsoft ou se connecter à l’aide d’un compte professionnel ou scolaire associé à Office 365. Les destinataires peuvent également envoyer des réponses chiffrées. Ils n’ont pas besoin d’un abonnement pour afficher des messages chiffrés ou envoyer des réponses chiffrées.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs de messages bénéficient du contrôle supplémentaire sur les e-mails sensibles fournis par chiffrement de messages Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 et Azure Information Protection Plan 1 offrent aux utilisateurs le droit de bénéficier d’chiffrement de messages Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Les administrateurs créent et gèrent les chiffrement de messages Office 365 dans le centre d’administration Exchange sous les règles **de flux de**  >  **messagerie**. Par défaut, ces règles s’appliquent à tous les utilisateurs du locataire. Pour plus d’informations sur la mise en place de nouvelles chiffrement de messages Office 365, voir Configurer [de nouvelles fonctionnalités de cryptage de messages](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs doivent appliquer des règles de flux de messagerie pour chiffrement de messages Office 365 uniquement aux utilisateurs titulaires d’une licence. Pour plus d’informations sur la définition des règles de flux de messagerie, [consultez Définir les règles de flux de messagerie pour chiffrer les messages électroniques](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Chiffrement avancé de messages Office 365

Chiffrement avancé de messages Office 365 les clients à respecter leurs obligations de conformité qui exigent des contrôles plus flexibles sur les destinataires externes et leur accès aux e-mails cryptés. Grâce au chiffrement avancé des messages, les administrateurs peuvent contrôler les e-mails sensibles partagés en dehors de l’organisation en utilisant des stratégies automatiques qui peuvent détecter les types d’informations sensibles (par exemple, identifier personnellement des informations, ou des identifiants financiers ou sanitaires), ou ils peuvent utiliser des mots clés pour améliorer la protection en appliquant des modèles de messagerie personnalisés et en expirant l’accès aux e-mails cryptés via un portail Web sécurisé. En outre, les administrateurs peuvent contrôler davantage les e-mails cryptés accessibles à l’extérieur via un portail Web sécurisé en révoquant l’accès à tout moment.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs de messages bénéficient du contrôle supplémentaire sur les e-mails sensibles fournis par advanced message encryption.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5 et Microsoft 365 E5/A5/G5 Protection et gouvernance de l’information offrent aux utilisateurs le droit de bénéficier du chiffrement avancé des messages.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Les administrateurs créent et gèrent des stratégies avancées de cryptage de messages dans le Exchange d’administration sous les **règles de flux** de  >  **messagerie**. Par défaut, ces règles s’appliquent à tous les utilisateurs du locataire. Pour plus d’informations sur la mise en place de nouvelles fonctionnalités de cryptage de [messages, voir Configurer de nouvelles fonctionnalités chiffrement de messages Office 365'environnement](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs ne doivent appliquer les règles de flux de messagerie pour le chiffrement avancé des messages qu’aux utilisateurs autorisés. Pour plus d’informations sur la définition des règles de flux de messagerie, [consultez Définir les règles de flux de messagerie pour chiffrer les messages électroniques dans Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Conformité des communications

La conformité aux communications Microsoft 365 contribue à minimiser les risques de communication en vous aidant à détecter, capturer et prendre des mesures correctives pour les messages inappropriés dans votre organisation. Vous pouvez définir des stratégies spécifiques qui capturent les communications internes et externes Microsoft Teams, les communications par ordinateur ou les communications tierce dans votre organisation. Les examinateurs peuvent prendre les mesures d’assainissement appropriées pour s’assurer qu’ils sont conformes aux normes de message de votre organisation.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les spécialistes de la conformité bénéficient du service en faisant surveiller les communications de l’organisation par des politiques de conformité aux communications.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5/G5 Insider Risk Management offrent aux utilisateurs le droit de bénéficier de la conformité aux communications.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Les administrateurs et les spécialistes de la conformité créent des politiques de conformité de communication dans Microsoft 365 de conformité. Ces stratégies définissent les communications et les utilisateurs qui sont soumis à l’examen au cours de l’organisation, définissent les conditions personnalisées que les communications doivent respecter et précisent qui doit effectuer des examens.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Les administrateurs choisissent des utilisateurs ou des groupes spécifiques à inclure dans une politique de conformité aux communications. Lors du choix d’un groupe, ils peuvent également sélectionner des utilisateurs spécifiques du groupe à exclure de la politique de conformité aux communications. Pour plus d’informations sur les politiques de conformité aux communications, [voir Démarrer avec la conformité aux communications dans Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Gestion des risques internes

La gestion des risques d’initiés est une solution en Microsoft 365 qui aide à minimiser les risques internes en vous permettant de détecter, d’enquêter et de prendre des mesures sur les activités risquées de votre organisation.

Les stratégies personnalisées vous permettent de détecter et de prendre des mesures sur les activités malveillantes et risquées par inadvertance dans votre organisation, y compris l’escalade des cas à Microsoft Advanced eDiscovery, si nécessaire. Les analystes des risques de votre organisation peuvent rapidement prendre les mesures appropriées pour s’assurer que les utilisateurs sont conformes aux normes de conformité de votre organisation.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient d’une surveillance des risques dans leurs activités.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences donnent le droit à un utilisateur de bénéficier du service ?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5/G5 Insider Risk Management offrent aux utilisateurs le droit de bénéficier de la gestion des risques d’initiés.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Les stratégies de gestion des risques d’initiés doivent être créées dans Microsoft 365 de conformité et attribuées aux utilisateurs.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Lors de la création d’une stratégie dans le centre de conformité Microsoft 365, sur la page **Choisir les utilisateurs et les** groupes, **sélectionnez Choisir les utilisateurs ou les groupes** pour sélectionner uniquement les utilisateurs sous licence, ou, si tous vos utilisateurs sont autorisés, vous pouvez sélectionner la case à **cochée Tous les utilisateurs et groupes de messagerie.** Pour plus d’informations, voir [Démarrer avec la gestion des risques d’initiés](/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Stratégies d’accès conditionnel

L’accès conditionnel est l’outil utilisé Azure Active Directory pour rassembler les signaux, prendre des décisions et appliquer les politiques organisationnelles. L’accès conditionnel est au cœur du contrôle identitaire. Les politiques d’accès conditionnel, dans leur plus simple, sont des relevés if-then. Si un utilisateur veut accéder à une ressource, il doit effectuer une action. Exemple : Un gestionnaire de paie veut accéder à l’application de paie et doit effectuer une authentification multifaction pour y accéder.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs titulaires d’une licence Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium et Azure Active Directory Premium plan 1 peuvent bénéficier de politiques d’accès conditionnel. Les utilisateurs agréés de Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security et Azure Active Directory Premium Plan 2 peuvent bénéficier de la protection de l’identité (politiques d’accès conditionnel basées sur le risque).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes des opérations de sécurité et les professionnels de la sécurité bénéficient de la capacité d’appliquer des politiques organisationnelles aux utilisateurs, les obligeant à satisfaire à certains critères avant d’accorder l’accès au contenu de l’entreprise. Les utilisateurs finaux bénéficient de pouvoir accéder à leur travail où et quand ils le souhaitent, tout en protégeant les actifs de l’organisation.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, les fonctionnalités d’accès conditionnel sont activées au niveau du locataire pour tous les utilisateurs du locataire.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

Pour la protection de l’identité et l’accès conditionnel en particulier, un utilisateur doit être inclus dans un groupe ou être ajouté à une politique d’accès conditionnel. La condition des utilisateurs et des groupes est obligatoire dans une politique d’accès conditionnel. Dans votre stratégie, vous pouvez sélectionner tous les **utilisateurs ou** utilisateurs et groupes spécifiques. Vous ne devez sélectionner que les utilisateurs et les groupes sous licence appropriée. Pour plus d’informations, voir [Accès conditionnel : Conditions](/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Audit avancé

Advanced Audit in Microsoft 365 permet de conservation d’un an des journaux d’audit pour les activités des utilisateurs et des administrateurs et offre la possibilité de créer des stratégies personnalisées de conservation des journaux de vérification pour gérer la conservation du journal de vérification pour d’autres services Microsoft 365. Il donne également accès à des événements cruciaux pour les enquêtes et à un accès à bande passante élevée à l’API Office 365'activité de gestion des ressources. Pour plus d’informations, [voir Advanced Audit en Microsoft 365](/microsoft-365/compliance/advanced-audit).

Vous pouvez également activer une période de rétention de 10 ans avec un SKU add-on. L’add-on SKU sera nécessaire à partir du début de 2021.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs titulaires d’une licence de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5/G5 eDiscovery and Audit peuvent bénéficier d’un audit avancé.

Les utilisateurs titulaires d’une licence avec audit avancé et l’add-on de conservation du journal d’audit de 10 ans peuvent bénéficier d’une conservation de journal de vérification de 10 ans.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient d’audit avancé car les dossiers d’audit liés à l’activité des utilisateurs dans Microsoft 365 services peuvent être conservés jusqu’à un an. En outre, des événements d’audit de grande valeur sont enregistrés, par exemple lorsque des éléments de la boîte aux lettres d’un utilisateur sont consultés ou lus. Pour plus d’informations, [voir Advanced Audit en Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis à disposition ou déployé?

Par défaut, Advanced Audit est activé au niveau des locataires pour toutes les organisations qui ont un abonnement Office 365 ou Microsoft 365 E5/A5/G5, et fournit automatiquement une conservation d’un an des journaux d’audit pour les activités (effectuées par les utilisateurs avec la licence appropriée) en Azure Active Directory, Exchange et SharePoint. De plus, les organisations peuvent utiliser les politiques de conservation des journaux de vérification pour gérer la période de conservation des dossiers de vérification générés par l’activité dans d’autres services Microsoft 365'investissement. La fonctionnalité de conservation du journal d’audit de 10 ans est également activée à l’aide des mêmes stratégies de conservation. Pour plus d’informations, voir [gérer les stratégies de rétention du journal d’audit](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du locataire titulaires d’une licence pour le service?

La conservation d’un an des journaux d’audit et la vérification d’événements cruciaux ne s’appliquent qu’aux utilisateurs titulaires de la licence appropriée. En outre, les administrateurs peuvent utiliser des stratégies de conservation du journal d’audit pour spécifier des durées de conservation plus courtes pour les journaux d’audit d’utilisateurs spécifiques.

La conservation des journaux d’audit sur 10 ans ne s’applique qu’aux utilisateurs titulaires de la licence d’ajout appropriée. L’add-on SKU sera nécessaire à partir de début 2021.