---
title: Conseils sur les licences Microsoft 365 pour la conformité & sécurité
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Cet article fournit des conseils en matière de licences pour la conformité de Microsoft 365 afin d’éviter les interruptions de service potentielles en raison d’un accès sans licence.
ms.openlocfilehash: 68bbb37734f1fc708e0b05ef3b152cf878757b48
ms.sourcegitcommit: 96a8a38f35778b455814b6174b8e68e2feda8746
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/09/2021
ms.locfileid: "50572720"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Conseils sur les licences Microsoft 365 pour la conformité de &amp; la sécurité

Dans le cadre de cet article, un service au niveau du client est un service en ligne qui, lorsqu’il est acheté pour un utilisateur du client (autonome ou dans le cadre de &mdash; plans Office 365 ou Microsoft 365), est activé en partie ou en intégralité pour tous les utilisateurs du &mdash; client. Bien que certains utilisateurs sans licence puissent techniquement être en mesure d’accéder au service, une licence est requise pour tous les utilisateurs qui souhaitent bénéficier du service.

> [!NOTE]
> Certains services clients ne sont actuellement pas en mesure de limiter les avantages à des utilisateurs spécifiques. Des efforts doivent être faits pour limiter les avantages du service aux utilisateurs titulaires d’une licence. Cela permet d’éviter toute interruption de service potentielle pour votre organisation une fois que les fonctionnalités de ciblage sont disponibles.

Pour voir les options de gestion des licences pour vos utilisateurs afin de bénéficier des fonctionnalités de conformité de Microsoft 365 à partir du 1er avril 2020, téléchargez la comparaison détaillée des licences de conformité Microsoft 365. [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection est une fonctionnalité du plan Azure Active Directory Premium P2 qui vous permet de détecter les vulnérabilités potentielles affectant les identités de votre organisation, de configurer des réponses automatisées aux actions suspectes détectées liées aux identités de votre organisation, d’examiner les incidents suspects et de prendre les mesures appropriées pour les résoudre.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité SecOps bénéficient d’affichages consolidés d’utilisateurs marqués et d’événements à risque basés sur des algorithmes d’apprentissage automatique. Les utilisateurs finaux bénéficient de la protection automatique fournie par l’accès conditionnel basé sur les risques et de la sécurité améliorée fournie en agissant sur les vulnérabilités.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security et Azure Active Directory Premium Plan 2 fournissent les droits d’un utilisateur pour bénéficier d’Azure Active Directory Identity Protection.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités Azure AD Identity Protection sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur Azure AD Identity Protection, voir [Qu’est-ce que Identity Protection ?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent définir l’étendue d’Azure AD Identity Protection en attribuant des stratégies de risque qui définissent le niveau de réinitialisation de mot de passe et en permettant l’accès aux utilisateurs sous licence uniquement. Pour obtenir des instructions sur l’étendue des déploiements Azure AD Identity Protection, voir Comment configurer et activer des stratégies [de risque.](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Gouvernance des identités Azure Active Directory

La gouvernance des identités Azure Active Directory vous permet d’équilibrer les besoins de votre organisation en matière de sécurité et de productivité des employés avec les processus et la visibilité qui leur sont nécessaires. Il utilise la gestion des droits, les révisions d’accès, la gestion des identités privilégiées et les stratégies de conditions d’utilisation pour s’assurer que les bonnes personnes disposent d’un accès aux ressources appropriées.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

La gouvernance des identités Azure Active Directory augmente la productivité des utilisateurs en rendant plus facile la demande d’accès aux applications, groupes et Microsoft Teams dans un seul package d’accès. Les utilisateurs peuvent également être configurés en tant qu’approuveurs, sans impliquer d’administrateurs. Pour les révisions d’accès, les utilisateurs peuvent passer en revue les appartenances à des groupes avec des recommandations intelligentes pour prendre des mesures à intervalles réguliers.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security et Azure Active Directory Premium Plan 2 fournissent les droits d’un utilisateur pour bénéficier de la gouvernance des identités Azure Active Directory.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les fonctionnalités de gouvernance d’identité Azure AD sont activées au niveau du client, mais implémentées par utilisateur. Pour plus d’informations sur la gouvernance des identités Azure AD, voir [Qu’est-ce qu’Azure AD Identity Governance ?](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent affecter l’étendue de la gouvernance des identités Azure AD en attribuant des packages d’accès, des révisions d’accès ou une gestion privilégiée des identités pour les utilisateurs sous licence uniquement. Pour obtenir des instructions sur l’étendue des déploiements azure AD Identity Governance, voir :

- [Conditions requises pour la gestion des droits Azure AD](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Conditions requises pour la licence de révision de l’accès à Azure AD](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Conditions de licence requises pour utiliser Privileged Identity Management](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender pour l’identité

Microsoft Defender for Identity (anciennement Azure Advanced Threat Protection) est un service cloud qui permet de protéger les environnements hybrides d’entreprise contre plusieurs types de cyberattaques ciblées avancées et de menaces internes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité SecOp bénéficient de la capacité de Microsoft Defender for Identity à détecter et examiner les menaces avancées, les identités compromises et les actions malveillantes internes. Les utilisateurs finaux bénéficient de la surveillance de leurs données par Microsoft Defender for Identity.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security et Microsoft Defender for Identity for Users fournissent les droits pour bénéficier de Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de Microsoft Defender pour l’identité sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration d’Azure ATP, voir [Créer votre instance de Microsoft Defender pour l’identité.](https://docs.microsoft.com/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Microsoft Defender pour les services d’identité n’est actuellement pas capable de limiter les fonctionnalités à des utilisateurs spécifiques. Vous devez obtenir une licence pour chaque utilisateur dont vous avez l’intention de bénéficier.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender pour Office 365

Microsoft Defender pour Office 365 (anciennement Office 365 - Protection avancée contre les menaces) permet de protéger les organisations contre les attaques sophistiquées telles que le hameçonnage et les programmes malveillants zero-day. Microsoft Defender pour Office 365 fournit également des informations actionnables en corrélant les signaux provenant d’un large éventail de données pour vous aider à identifier, hiérarchiser et fournir des recommandations sur la façon de traiter les menaces potentielles.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Microsoft Defender pour Office 365 protège les utilisateurs contre les attaques sophistiquées telles que le hameçonnage et les programmes malveillants « zero-day ». Pour obtenir la liste complète des services fournis dans les plans 1 et 2, consultez [Microsoft Defender pour Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ? 

Microsoft Defender pour Office 365 Plans 1 et 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security et Microsoft 365 Business Premium fournissent aux utilisateurs les droits de bénéficier de Microsoft Defender pour Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de Microsoft Defender pour Office 365 sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration des stratégies Microsoft Defender pour Office 365 pour les utilisateurs sous licence, voir [Microsoft Defender pour Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Pour mettre en œuvre Microsoft Defender pour Office 365, suivez les stratégies de déploiement des liens sécurisés et des pièces jointes sécurisées :

- Pour plus d’informations sur la configuration des liens sécurisés pour les utilisateurs titulaires d’une licence, voir Liens sécurisés [dans Microsoft Defender pour Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

- Pour plus d’informations sur la configuration des pièces jointes sécurisées pour les utilisateurs titulaires d’une licence, voir [Pièces jointes sécurisées dans Microsoft Defender pour Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)

## <a name="office-365-cloud-app-security"></a>Sécurité de l’application cloud Office 365

Office 365 Cloud App Security (OCAS) est un sous-ensemble de Microsoft Cloud App Security, avec des fonctionnalités limitées à Office 365 et sans sécurité supplémentaire pour les applications cloud tierces et les services IaaS.

OCAS offre aux organisations une visibilité sur leurs applications et services cloud de productivité, fournit des analyses sophistiquées pour identifier et lutter contre les cybermenaces et leur permet de contrôler la façon dont les données circulent dans &mdash; Office 365.

Pour comparer les [fonctionnalités, voir Différences entre Microsoft Cloud App Security et Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

OCAS découvre shadow IT, offre une protection contre les menaces dans Office 365 et peut contrôler les applications autorisées à accéder aux données.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Office 365 E5/A3/A5/G5 permet à un utilisateur de bénéficier de OCAS.
Pour plus d’informations, voir la feuille de données de gestion des licences Microsoft [Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités OCAS sont activées au niveau du client pour tous les utilisateurs au sein du client.

Pour plus d’informations sur la configuration du service, voir Configuration de base [pour Cloud App Security.](https://docs.microsoft.com/cloud-app-security/general-setup)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent limiter les déploiements OCAS pour appliquer la façon dont certaines applications sont accessibles et limiter les groupes d’utilisateurs surveillés par La sécurité des applications cloud Office 365. Pour plus d’informations, voir [Déploiement dans l’étendue.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) est une solution Cloud Access Security Broker (CASB) qui donne aux organisations une visibilité sur leurs applications et services cloud, fournit des analyses sophistiquées pour identifier et lutter contre les cybermenaces et leur permet de contrôler la façon dont les données circulent dans n’importe quelle application &mdash; cloud.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

MCAS découvre et évalue le service informatique de l’ombre, fournit une protection contre les menaces dans les applications cloud tierces et tierces, et protège les informations sur les applications cloud tierces et de premier niveau.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 Information Protection and Governance fournissent les droits pour qu’un utilisateur bénéficie de MCAS.

Azure AD P1 fournit aux utilisateurs les droits de bénéficier des fonctionnalités de découverte dans MCAS.

Pour bénéficier des fonctionnalités de contrôle d’application d’accès conditionnel dans MCAS, les utilisateurs doivent également avoir une licence Azure Active Directory P1, incluse dans Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 Security et Microsoft 365 E5/A5/G5 Security.

Pour bénéficier de l’étiquetage côté client automatique, les utilisateurs doivent être titulaires d’une licence Azure Information Protection P2, incluse dans Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 Information Protection and Governance.

> [!NOTE]
> L’étiquetage automatique côté serveur nécessite la protection des informations pour Office 365 - Licences Premium ( `MIP_S_CLP2` ou `efb0351d-3b08-4503-993d-383af8de41e3` ). Pour référence, voir Noms de produits [et identificateurs de plan de service pour la gestion des licences.](https://docs.microsoft.com/azure/active-directory/enterprise-users/licensing-service-plan-reference)

Pour plus d’informations, voir la feuille de données de gestion des licences Microsoft [Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités MCAS sont activées au niveau du client pour tous les utilisateurs au sein du client.

Pour plus d’informations sur la configuration des stratégies Microsoft Cloud App Security pour les utilisateurs titulaires d’une licence, voir La vue [d’ensemble de Microsoft Cloud App Security.](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent étendue les déploiements MCAS aux utilisateurs titulaires d’une licence à l’aide des fonctionnalités de déploiement étendues disponibles dans le service. Pour plus d’informations, voir [Déploiement dans l’étendue.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Gestionnaire de conformité

Simplifiez la conformité et réduisez les risques avec le Gestionnaire de conformité. Le Gestionnaire de conformité aide les organisations à répondre aux exigences de réglementations, de normes, de stratégies d’entreprise ou d’autres cadres de contrôle souhaités.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Voici les avantages pour les utilisateurs du service Gestionnaire de conformité :

- Traduit des réglementations complexes, des normes, des stratégies d’entreprise ou d’autres cadres de contrôle souhaités en langage simple
- Permet d’accéder à une vaste bibliothèque d’évaluations et d’évaluations personnalisées pré-personnalisées pour répondre à des besoins de conformité uniques
- Cartes des contrôles réglementaires aux actions d’amélioration recommandées
- Fournit des instructions pas à pas sur la façon d’implémenter les solutions pour répondre aux exigences réglementaires
- Aide les utilisateurs à hiérarchiser les actions qui auront le plus d’impact sur leur conformité organisationnelle en associant un score à chaque action

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Les clients titulaires de licences E1 et E3/G3 pourront accéder uniquement à l’évaluation de référence de la protection des données par défaut. Les clients titulaires de licences Office 365 E5/A5 et Microsoft 365 E5/A5 (conformité, gouvernance de la protection des informations & et références eDiscovery et audit incluses) pourront accéder aux évaluations prédécises de protection des données, R GDPR, NIST 800-53 et ISO 27001. Les clients ayant Office 365 G5 et Microsoft 365 G5 pourront accéder aux niveaux de référence de protection des données, RGPD, NIST 800-53, ISO 27001 et Certification du modèle de maturité de la cybersécurité (CMMC) de 1 à 5 évaluations prédé nos jours. La fonctionnalité d’évaluation personnalisée et les évaluations premium sont réservées aux clients Office 365 E5/A5/G5 et Microsoft 365 E5/A5/G5. Les évaluations Premium, telles que modéré FedRAMP, FedRAMP élevé et autres, seront disponibles à l’achat pour les clients titulaires de licences E5/A5/G5 au cours du premier semestre 2021 via VL, CSP et WebDirect. Contactez votre vendeur Microsoft ou votre partenaire Microsoft pour l’acheter via les canaux VL ou CSP, respectivement. Pour acheter via WebDirect, voir [WebDirect.](https://aka.ms/ComplianceManager/WebDirect)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Le Gestionnaire de conformité est provisioné par défaut pour votre client. Les administrateurs définissent des autorisations utilisateur et attribuent des rôles afin que les utilisateurs non administrateurs de votre organisation peuvent commencer à utiliser le Gestionnaire de conformité. Pour plus d’informations, consultez La mise en place du Gestionnaire de conformité : définir des [autorisations utilisateur et attribuer des rôles.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender pour point de terminaison

Microsoft Defender pour point de terminaison (anciennement Microsoft Defender ATP) est une solution de sécurité de point de terminaison qui inclut une évaluation et une gestion des vulnérabilités basées sur les risques . fonctionnalités de réduction de la surface d’attaque ; protection de nouvelle génération basée sur le comportement et basée sur le cloud ; détection et réponse des points de terminaison (EDR) ; examen et correction automatiques ; et les services de recherche gérés. Pour en [savoir plus, consultez](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) la page Microsoft Defender pour le point de terminaison.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs sous licence de Windows 10 Entreprise E5, Windows 10 Éducation A5, Microsoft 365 E5/G5, qui inclut Windows 10 Entreprise E5, Microsoft 365 E5/A5/Sécurité G5, peuvent bénéficier de Microsoft Defender pour endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité SecOps bénéficient des fonctionnalités de sécurité des points de terminaison de Microsoft Defender for Endpoint pour assurer la protection préventive, la détection post-violation, l’examen automatisé et la réponse aux menaces avancées. Les utilisateurs finaux bénéficient d’événements malveillants surveillés par Microsoft Defender for Endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de Microsoft Defender pour le point de terminaison sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur le déploiement, voir [Phases de déploiement.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs microsoft Defender pour points de terminaison peuvent utiliser le contrôle d’accès basé sur les rôles (RBAC) pour créer des rôles et des groupes au sein de l’équipe des opérations de sécurité afin d’accorder un accès approprié au Centre de sécurité Microsoft Defender. Pour plus d’informations, voir [Gérer l’accès au portail à l’aide du contrôle d’accès basé sur les rôles.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Analyse de la classification des données Microsoft 365 : Vue d’ensemble de &amp; l’Explorateur d’activités de contenu  

Les fonctionnalités analytiques de classification des données sont disponibles dans l’expérience du Centre de conformité Microsoft 365. Vue d’ensemble des emplacements de contenu numérique et des étiquettes et types d’informations sensibles les plus courants. L’Explorateur de contenu offre une visibilité sur la quantité et les types de données sensibles et permet aux utilisateurs de filtrer par étiquette ou type de sensibilité pour obtenir une vue détaillée des emplacements où les données sensibles sont stockées. L’Explorateur d’activités affiche les activités liées aux données sensibles et aux étiquettes, telles que les rétrogradations d’étiquettes ou le partage externe qui peuvent exposer votre contenu à des risques.

L’Explorateur d’activités fournit un volet unique de verre aux administrateurs pour obtenir une visibilité sur les activités liées aux informations sensibles utilisées par les utilisateurs finaux. Ces données incluent les activités des étiquettes, les journaux de protection contre la perte de données (DLP), l’étiquetage automatique, le point de terminaison DLP et bien plus encore.

L’Explorateur de contenu permet aux administrateurs d’indexer les documents sensibles stockés dans les charges de travail Microsoft 365 pris en charge et d’identifier les informations sensibles qu’ils stockent. En outre, l’Explorateur de contenu permet d’identifier les documents classés avec des étiquettes de sensibilité et de rétention.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les administrateurs de la protection des informations et de la conformité peuvent accéder au service pour accéder à ces journaux et données indexées pour comprendre où les données sensibles sont stockées et quelles activités sont liées à ces données et effectuées par les utilisateurs finaux.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Les utilisateurs titulaires d’une licence Microsoft 365 E5/A5/G5, Conformité Microsoft 365 E5/A5/G5, Gouvernance de la protection des informations Microsoft 365 E5/A5/G5 et Office 365 E5 peuvent bénéficier de l’analyse de classification des données &amp; Microsoft 365. 

Microsoft 365 E3/A3/G3 et Office 365 E3/A3/G3 permettent aux utilisateurs de bénéficier uniquement de l’agrégation de données de l’Explorateur de contenu.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de l’Explorateur de contenu et d’activité de vue d’ensemble sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de l’analyse de la classification des données pour les utilisateurs sous licence, voir :

- **Explorateur de contenu**: [démarrer avec l’Explorateur de contenu - Microsoft 365 Compliance | Microsoft Docs](https://docs.microsoft.com/microsoft-365/compliance/data-classification-content-explorer).
- **Explorateur d’activités** [: démarrer avec l’Explorateur d’activités - Microsoft 365 Compliance | Microsoft Docs](https://docs.microsoft.com/microsoft-365/compliance/data-classification-activity-explorer).
- **Notes de publication relatives à la classification des** données : notes de publication relatives à la classification des données - Conformité microsoft [365 | Microsoft Docs](https://docs.microsoft.com/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Cette fonctionnalité doit être étendue aux utilisateurs qui utilisent activement la solution dans le portail de conformité Microsoft 365.

## <a name="information-protection"></a>Protection des informations

La protection des informations permet aux organisations de découvrir, classifier, étiqueter et protéger les documents et e-mails sensibles. Les administrateurs peuvent définir des règles et des conditions pour appliquer automatiquement des étiquettes, les utilisateurs peuvent appliquer des étiquettes manuellement ou une combinaison des deux peut être utilisée, où les utilisateurs ont des recommandations sur l’application d’étiquettes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité d’appliquer manuellement des étiquettes de sensibilité à leur contenu ou de classer automatiquement leur contenu.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 et AIP Plan 2 fournissent les droits pour qu’un utilisateur bénéficie de l’étiquetage de sensibilité manuelle.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 et AIP Plan 2 permettent à un utilisateur de bénéficier de l’application et de l’affichage d’étiquettes de sensibilité dans Power BI et de protéger les données lorsqu’elles sont exportées de Power BI vers Excel, PowerPoint ou PDF. 

> [!NOTE]
> Power BI est inclus dans Microsoft 365 E5/A5/G5 ; Dans tous les autres plans, Power BI doit être titulaire d’une licence distincte.

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Information Protection et gouvernance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 et AIP Plan 2 fournissent les droits pour qu’un utilisateur bénéficie de l’étiquetage de sensibilité automatique.

Pour obtenir des droits spécifiques par licence, consultez la comparaison détaillée des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) N’inclut pas les droits à la classification automatique basée sur l’apprentissage automatique (classifieurs entraidables).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de protection des informations sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration des stratégies pour les utilisateurs sous licence, voir Activation d’Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Sauf en cas d’utilisation de la fonctionnalité de scanneur AIP, les stratégies peuvent être limitées à des groupes spécifiques, ou des utilisateurs et registres peuvent être modifiés pour empêcher les utilisateurs sans permis d’utiliser des fonctionnalités de classification ou d’étiquetage. Pour obtenir des instructions sur l’étendue des déploiements AIP, voir [Configuration de la stratégie Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy).

Pour la fonctionnalité de scanneur AIP, Microsoft ne s’engage pas à fournir des fonctionnalités de classification de fichier, d’étiquetage ou de protection aux utilisateurs qui ne disposent pas d’une licence.

## <a name="information-governance"></a>Gouvernance des informations

La gouvernance des informations permet aux organisations de gérer leurs risques par la découverte, la classification, l’étiquetage et la gouvernance de leurs données. La gouvernance des informations permet aux organisations de répondre aux exigences commerciales et réglementaires, ainsi que de réduire leur surface d’attaque en fournissant des fonctionnalités de rétention et de suppression dans leurs données Microsoft 365 et tierces.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité de classer des données à des fins de rétention afin de respecter des stratégies et réglementations spécifiques.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Les plans Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 et les plans Exchange autonomes offrent aux utilisateurs les droits de bénéficier de l’application manuelle d’étiquettes de rétention non-enregistrement aux données de boîte aux lettres.

Les plans Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 et les plans SharePoint autonomes offrent aux utilisateurs les droits de bénéficier de l’application manuelle d’étiquettes de rétention sans enregistrement aux fichiers dans SharePoint ou OneDrive. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plan 2 et Archivage Exchange Online fournissent les droits d’un utilisateur pour bénéficier d’une stratégie de rétention de boîte aux lettres de base à l’échelle de l’organisation ou à l’échelle de l’emplacement et/ou pour appliquer manuellement une étiquette de rétention non-enregistrement aux données de boîte aux lettres.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 et SharePoint Plan 2 fournissent aux utilisateurs les droits de bénéficier d’une stratégie de rétention SharePoint ou OneDrive de base et/ou d’appliquer manuellement une étiquette de rétention sans enregistrement aux fichiers dans SharePoint ou OneDrive.

Microsoft 365 E5/A5/G5/E3/A3 et Office 365 E5/A5/G5/E3/A3 fournissent les droits d’un utilisateur pour bénéficier d’une stratégie de rétention Teams.

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, Microsoft 365 Information Protection and Governance E5/A5/G5, Et Office 365 E5/A5 offre aux utilisateurs les droits de bénéficier de l’application automatique d’étiquettes ou de stratégies de rétention, de l’application d’étiquettes ou de stratégies de rétention par défaut, du démarrage de la période de rétention d’une étiquette basée sur un événement personnalisé, du déclenchement d’une révision manuelle à la fin de la période de rétention de l’étiquette, de l’importation de données tierces via des connecteurs de données natives, de la déclaration d’un fichier d’un enregistrement, de la découverte du contenu étiqueté et de la surveillance de l’activité d’étiquetage.

Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5, la protection des informations Microsoft 365 E5/A5/G5 et la gouvernance fournissent aux utilisateurs les droits de bénéficier de l’application automatique d’étiquettes de rétention basées sur des classifieurs entraisables.

Pour obtenir des droits spécifiques par licence, consultez la comparaison détaillée des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de gouvernance des informations sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de la gouvernance des informations afin d’appliquer l’auto-beling et les stratégies pour les utilisateurs sous licence, voir Gouvernance des informations [Microsoft dans Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les fonctionnalités de gouvernance des informations peuvent être appliquées aux utilisateurs sous licence à des emplacements spécifiques (sites d’équipe, sites de groupe, etc.). Pour plus d’informations sur la configuration de la gouvernance des informations afin d’appliquer l’auto-beling et les stratégies pour les utilisateurs sous licence, voir Gouvernance des informations [Microsoft dans Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gestion des enregistrements

La gestion des enregistrements aide les organisations à respecter leurs obligations commerciales et réglementaires en matière de conservation des enregistrements par le biais de la découverte, de la classification, de l’étiquetage, de la rétention et de la suppression à l’échelle de leurs données Microsoft 365 et tierces.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, La conformité Microsoft 365 E5/A5/G5, Microsoft 365 Information Protection and Governance E5/A5/G5 et Office 365 E5/A5/G5 fournissent les droits d’un utilisateur pour bénéficier de la gestion des enregistrements, y compris la déclaration d’éléments en tant qu’enregistrements ou enregistrements réglementaires, l’application automatique d’étiquettes de rétention ou d’enregistrements et l’exécution de processus de révision de la disposition (à l’exclusion de l’application automatique d’une étiquette de rétention basée sur des classifieurs entra nessables).

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5 et Microsoft 365 Information Protection and Governance fournissent les droits pour qu’un utilisateur bénéficie de l’application automatique d’étiquettes de rétention ou d’enregistrement basées sur des classifieurs entraisables.

Pour obtenir des droits spécifiques par licence, consultez la comparaison détaillée des licences de conformité Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité de déclarer du contenu en tant qu’enregistrement et de gérer leur processus d’enregistrements complets à partir de la définition et de la déclaration de stratégie par le biais d’une élimination de stratégie.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de gestion des enregistrements sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de la gestion des enregistrements à appliquer pour les utilisateurs sous licence, voir En savoir plus sur la gestion des enregistrements [dans Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les fonctionnalités de gestion des enregistrements peuvent être appliquées aux utilisateurs sous licence à des emplacements spécifiques (sites d’équipe, sites de groupe, etc.). Pour plus d’informations sur la configuration de la gestion des enregistrements à appliquer pour les utilisateurs sous licence, voir En savoir plus sur la gestion des enregistrements [dans Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Connecteurs de données 

Microsoft fournit des connecteurs de données tiers qui peuvent être configurés dans le Centre de conformité Microsoft 365. Pour obtenir la liste des connecteurs de données fournis par Microsoft, consultez la table [des connecteurs de données tiers.](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) Ce tableau récapitule également les solutions de conformité que vous pouvez appliquer aux données tierces après avoir importé et archivé des données dans Microsoft 365, ainsi que des liens vers les instructions pas à pas pour chaque connecteur.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Le principal avantage de l’utilisation de connecteurs de données pour importer et archiver des données tierces dans Microsoft 365 est que vous pouvez appliquer différentes solutions de conformité Microsoft 365 aux données après leur importation. Cela permet de s’assurer que les données non Microsoft de votre organisation sont conformes aux réglementations et normes qui affectent votre organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Les licences suivantes permettent à un utilisateur de bénéficier des connecteurs de données :

- Microsoft 365 E5/A5/G5
- Gouvernance de la protection des informations Microsoft 365 E5/A5/G5 &amp;
- Conformité Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Gestion des risques internes
- EDiscovery et audit Microsoft 365 E5/A5/G5
- Office 365 E5/A5/G5

Pour les connecteurs de données dans le Centre de conformité de sécurité Microsoft 365 fournis par un partenaire Microsoft, votre organisation aura besoin d’une relation professionnelle avec le partenaire avant de pouvoir déployer ces &amp; connecteurs.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les connecteurs sont configurés à l’aide du Centre de conformité de &amp; sécurité et du catalogue de connecteurs.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les services connecteurs de données sont une valeur au niveau du client. Chaque utilisateur destiné à bénéficier de ce service doit être titulaire d’une licence.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>API Microsoft Graph pour la protection contre la perte de données (DLP) Teams

Plus tôt cette année, nous avons annoncé la prévisualisation publique de l’API de notification de modification [de Microsoft Graph pour les messages dans Teams.](https://go.microsoft.com/fwlink/?linkid=2143888) Cette API permet aux développeurs de créer des applications qui peuvent écouter les messages De Microsoft Teams en temps quasi réel et d’activer les implémentations de scénarios DLP pour les clients et les professionnels de l’informatique. En outre, l’API de correctif Microsoft Graph permet d’appliquer des actions DLP aux messages Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les fonctionnalités de protection contre la perte de données [(DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) sont largement utilisées dans Microsoft Teams, en particulier lorsque les organisations ont été décalées vers le travail à distance. Si votre organisation dispose de DLP, vous pouvez désormais définir des stratégies qui empêchent les personnes de partager des informations sensibles dans un canal ou une session de conversation Microsoft Teams.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Vous aurez besoin de l’une des licences suivantes pour obtenir la prise en charge de la protection DLP dans Teams Chat :

- Microsoft 365 E5/A5/G5
- Conformité Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Information Protection and Governance
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

L’accès à l’API est configuré au niveau du client.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

L’API Microsoft Graph pour Teams DLP est une valeur au niveau du client. Chaque utilisateur destiné à bénéficier de ce service doit être titulaire d’une licence.

## <a name="ediscovery"></a>eDiscovery

eDiscovery fournit des solutions d’examen et eDiscovery pour les services informatiques et juridiques au sein d’entreprises afin d’identifier, collecter, conserver, réduire et examiner le contenu lié à un examen ou à un litige avant l’exportation hors du système Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Un utilisateur bénéficie d’Advanced eDiscovery lorsque l’utilisateur est sélectionné en tant que dépositaire de données (une personne ayant le contrôle administratif d’un document ou d’un fichier électronique) pour un cas.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 fournissent les droits d’un utilisateur pour bénéficier de core eDiscovery.

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 eDiscovery and Audit et Office 365 E5/A5/G5 fournissent les droits d’un utilisateur pour bénéficier d’Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités Advanced eDiscovery sont activées au niveau du client pour tous les utilisateurs au sein du client lorsque les administrateurs attribuent des autorisations eDiscovery dans le Centre de conformité de &amp; sécurité.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs eDiscovery peuvent sélectionner des utilisateurs spécifiques en tant que dépositaires de données pour un cas à l’aide de l’outil de gestion des dépositaires intégré dans Advanced eDiscovery, comme décrit dans Ajouter des dépositaires à un cas [Advanced eDiscovery.](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)

## <a name="office-365-customer-key"></a>Clé client Office 365

Avec la clé client, vous contrôlez les clés de chiffrement de votre organisation et configurez Office 365 pour les utiliser pour chiffrer vos données au repos dans les centres de données Microsoft. En d’autres termes, la clé client vous permet d’ajouter une couche de chiffrement qui vous appartient, à l’aide de vos propres clés. Les données au repos incluent les données d’Exchange Online et de Skype Entreprise stockées dans des boîtes aux lettres et des fichiers dans SharePoint Online et OneDrive Entreprise.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la clé client en chiffrant leurs données au repos au niveau de la couche application à l’aide de clés de chiffrement fournies, contrôlées et gérées par leur propre organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Information Protection and Governance et Office 365 E5/A5/G5 fournissent les droits d’un utilisateur pour bénéficier de la clé client. Pour bénéficier pleinement de la clé client, vous devez également avoir un abonnement à Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les clés de chiffrement de clé client Office 365 peuvent être activées pour toutes les données stockées dans les boîtes aux lettres Exchange Online et Skype Entreprise, ainsi que pour les fichiers SharePoint Online, OneDrive Entreprise et Teams. Pour plus d’informations sur la clé client Office 365, notamment sur la façon de commencer, voir Chiffrement de [service avec clé client.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Pour Exchange Online et Skype Entreprise, les boîtes aux lettres peuvent être chiffrées à l’aide de la clé client. Vous devez configurer Azure avant de pouvoir utiliser la clé client pour Office 365. Voir [Configurer la clé](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) client pour les étapes à suivre pour créer et configurer les ressources Azure requises et les étapes de configuration de la clé client dans Office 365. Une fois l’installation d’Azure terminée, déterminez la stratégie et, par conséquent, les clés à affecter aux boîtes aux lettres et aux fichiers de votre organisation. Les boîtes aux lettres et les fichiers pour lesquels vous n’affectez pas de stratégie utiliseront des stratégies de chiffrement contrôlées et gérées par Microsoft. Pour plus d’informations sur la clé client ou pour une vue d’ensemble, voir Chiffrement de [service avec clé client.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

## <a name="office-365-customer-lockbox"></a>Demandes Customer Lockbox dans Office 365

Customer Lockbox fournit une couche de contrôle supplémentaire en offrant aux clients la possibilité d’accorder une autorisation d’accès explicite pour les opérations de service. En montrant que des procédures sont en place pour l’autorisation d’accès aux données explicite, Customer Lockbox peut également aider les organisations à respecter certaines obligations de conformité telles que HIPAA et FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Customer Lockbox garantit que personne chez Microsoft ne peut accéder au contenu client pour effectuer une opération de service sans l’approbation explicite du client. Customer Lockbox amène le client dans le flux de travail d’approbation pour les demandes d’accès à son contenu. Parfois, les ingénieurs Microsoft sont impliqués pendant le processus de support pour résoudre les problèmes signalés par le client. Dans la plupart des cas, les problèmes sont résolus par le biais d’outils de télémétrie et de débogage étendus que Microsoft a mis en place pour ses services. Toutefois, dans certains cas, un ingénieur Microsoft peut avoir besoin d’accéder au contenu du client pour déterminer la cause première et résoudre le problème. Customer Lockbox nécessite l’intervention de l’ingénieur pour demander l’accès au client en tant que dernière étape du flux de travail d’approbation. Cela permet aux organisations d’approuver ou de refuser ces demandes, ce qui leur permet de contrôler directement si un ingénieur Microsoft peut accéder aux données de l’utilisateur final de l’organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5/G5 Insider Risk Management fournissent les droits à un utilisateur pour bénéficier de Customer Lockbox.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs peuvent activer Customer Lockbox dans le Centre d’administration Microsoft 365. Pour plus d’informations, voir [Customer Lockbox dans Office 365.](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests) Lorsque Customer Lockbox est allumé, Microsoft doit obtenir l’approbation d’une organisation avant d’accéder à son contenu.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Actuellement, le service Customer Lockbox ne peut pas être limité à des utilisateurs spécifiques. Vous devez obtenir une licence pour chaque utilisateur dont vous avez l’intention de bénéficier.

## <a name="privileged-access-management-in-office-365"></a>Gestion des accès privilégiés dans Office 365

[La gestion des accès privilégiés (PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) fournit un contrôle d’accès granulaire sur les tâches d’administration privilégiées dans Office 365. Après avoir autorisé PAM, pour effectuer des tâches avec élévation de privilèges et privilégiées, les utilisateurs doivent demander un accès juste-à-temps via un flux de travail d’approbation hautement limité et limité dans le temps.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

L’activation du PAM permet aux organisations de fonctionner sans privilège permanent. Les utilisateurs bénéficient de la couche de défense supplémentaire contre les vulnérabilités résultant de l’accès administratif permanent qui fournit un accès illimité à leurs données.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ? 

Office 365 E5/A5, Microsoft 365 E5/A5, Conformité Microsoft 365 E5/A5 et Microsoft 365 E5/A5 Information Protection and Governance fournissent les droits d’un utilisateur pour bénéficier du PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités PAM sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration des stratégies PAM, voir Prise en charge de la [gestion des accès privilégiés.](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les clients peuvent gérer le PAM par utilisateur par le biais du groupe d’approbation et des stratégies d’accès, qui peuvent être appliquées aux utilisateurs sous licence. Pour plus d’informations, [voir Privileged access management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Chiffrement à double clé pour Microsoft 365 

Le chiffrement à double clé pour Microsoft 365 vous permet de protéger vos données hautement sensibles afin de répondre à des exigences spécialisées et de maintenir un contrôle total de votre clé de chiffrement. Le chiffrement à double clé utilise deux clés pour protéger vos données, avec une clé dans votre contrôle et la seconde clé stockée en toute sécurité par Microsoft Azure. Pour afficher les données, vous devez avoir accès aux deux clés. Étant donné que Microsoft ne peut accéder qu’à une seule clé, votre clé et vos données ne sont pas disponibles pour Microsoft, ce qui garantit que vous avez un contrôle total sur la confidentialité et la sécurité de vos données.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient du chiffrement à double clé en étant en mesure de migrer leurs données chiffrées vers le cloud, ce qui empêche l’accès de tiers tant que la clé reste sous le contrôle des utilisateurs. Les utilisateurs peuvent protéger et consommer du contenu chiffré à double clé similaire à tout autre contenu protégé par une étiquette de sensibilité.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Information Protection and Governance et Office 365 E5/A5/G5 fournissent les droits d’un utilisateur pour bénéficier du chiffrement à double clé.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Le chiffrement à double clé prend en charge la version de bureau Microsoft Office pour Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Pour affecter des clés de chiffrement à des données au sein d’une organisation Office 365 et/ou Microsoft 365 pour les utilisateurs sous licence, suivez les instructions de déploiement du chiffrement à double clé.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Protection contre la perte de données Office 365 pour Exchange Online, SharePoint Online et OneDrive Entreprise

Avec la protection contre la perte de données Office 365 (DLP) pour Exchange Online, SharePoint Online et OneDrive Entreprise, les organisations peuvent identifier, surveiller et protéger automatiquement les informations sensibles dans les e-mails et les fichiers (y compris les fichiers stockés dans les référentiels de fichiers Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la DLP pour Exchange Online, SharePoint Online et OneDrive Entreprise lorsque leurs messages électroniques et fichiers sont inspectés pour des informations sensibles, comme configuré dans la stratégie DLP de l’organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 et Office 365 Protection contre la perte de données offrent aux utilisateurs le droit de bénéficier de la protection contre la perte de données Office 365 pour Exchange Online, SharePoint Online et OneDrive Entreprise.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les e-mails Exchange Online, les sites SharePoint et les comptes OneDrive sont des *emplacements (charges de travail) activés* pour ces fonctionnalités DLP pour tous les utilisateurs au sein du client. Pour plus d’informations sur l’utilisation des stratégies DLP, voir [Vue d’ensemble de la protection contre la perte de données.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent personnaliser des emplacements (charges de travail), des utilisateurs inclus et des utilisateurs exclus dans le Centre de conformité de sécurité, sous Emplacements de &amp; protection contre la perte **de**  >  **données.**

## <a name="communication-data-loss-prevention-for-teams"></a>Protection contre la perte de données de communication pour Teams

Avec la DLP de communication pour Teams, les organisations peuvent bloquer les conversations et les messages de canal qui contiennent des informations sensibles, telles que des informations financières, des informations d’identification personnelle, des informations relatives à la santé ou d’autres informations confidentielles.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs sous licence d’Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 et Microsoft 365 E5/A5/G5 Information Protection and Governance peuvent bénéficier de la DLP de communication pour Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs bénéficient de la recherche d’informations sensibles dans leurs messages de conversation et de canal sortants, tel que configuré dans la stratégie DLP de l’organisation.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les messages de conversation et de canal Teams sont un emplacement (charge de *travail)* activé pour ces fonctionnalités DLP pour tous les utilisateurs au sein du client. Pour plus d’informations sur l’utilisation des stratégies DLP, voir [Vue d’ensemble de la protection contre la perte de données.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent personnaliser des emplacements (charges de travail), des utilisateurs inclus et des utilisateurs exclus dans le Centre de conformité de sécurité, sous Emplacements de &amp; protection contre la perte **de**  >  **données.**

## <a name="information-barriers"></a>Obstacles aux informations

Le cloisonnement de l’information est la définition de stratégies qu’un administrateur peut configurer pour empêcher des individus ou des groupes de communiquer entre eux. Cela est utile si, par exemple, un service gère des informations qui ne doivent pas être partagées avec d’autres services, ou si un groupe doit être empêché de communiquer avec des contacts externes. Les stratégies de obstacle à l’information empêchent également les recherche et la découverte. Cela signifie que si vous tentez de communiquer avec une personne avec qui vous ne devez pas communiquer, vous ne trouverez pas cet utilisateur dans le s sélectionneur de personnes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient des fonctionnalités avancées de conformité des obstacles aux informations lorsqu’ils ne peuvent pas communiquer avec d’autres personnes. Des stratégies de obstacles à l’information peuvent être définies pour empêcher certains segments d’utilisateurs de communiquer avec chacun d’eux ou permettre à des segments spécifiques de communiquer uniquement avec certains autres segments. Pour plus d’informations sur la définition des stratégies d’obstacle aux informations, voir [Définir des stratégies de obstacle à l’information.](https://docs.microsoft.com/microsoft-365/compliance/information-barriers-policies) Pour les scénarios dans lesquels deux groupes ne peuvent pas communiquer entre eux, les utilisateurs des deux groupes ont besoin d’une licence pour bénéficier du service (voir l’exemple ci-dessous).<br><br>

| Scénario | Qui a besoin d’une licence ? |
|:------|:------|
| Deux groupes (Groupe 1 et Groupe 2) ne peuvent pas communiquer entre eux (autrement dit, les utilisateurs du groupe 1 ne peuvent pas communiquer avec les utilisateurs du groupe 2, et les utilisateurs du groupe 2 ne peuvent pas communiquer avec les utilisateurs du groupe &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1. | Utilisateurs du groupe &nbsp; 1 et du &nbsp; groupe 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Insider Risk Management et Office 365 E5/A5/G5, fournissent les droits pour qu’un utilisateur bénéficie des obstacles à l’information.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs créent et gèrent des stratégies d’obstacle aux informations à l’aide des cmdlets PowerShell dans le Centre de &amp; conformité de la sécurité. Les administrateurs doivent avoir le rôle Administrateur général Microsoft 365 Entreprise, Administrateur général Office 365 ou Administrateur de conformité pour créer une stratégie d’obstacle aux informations. Par défaut, ces stratégies s’appliquent à tous les utilisateurs du client. Pour plus d’informations sur les obstacles aux informations, voir [Obstacles à l’information dans Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs inclus et les utilisateurs exclus dans le Centre de conformité &amp; de sécurité. Par exemple, si tous les utilisateurs sont titulaires d’une licence Office 365 E3 et qu’aucun utilisateur n’est titulaire d’une licence Office 365 Conformité avancée/E5, ils n’ont pas besoin de créer de stratégies de obstacle aux informations pour l’organisation. Si vous souhaitez en savoir plus, veuillez consulter la rubrique [Information barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams) (Cloisonnements de l’information dans Microsoft Teams).

## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365

Le chiffrement des messages Office 365 (OME) est un service basé sur Azure Rights Management (Azure RMS) qui vous permet d’envoyer des messages chiffrés à des personnes internes ou externes à votre organisation, quelle que soit l’adresse de messagerie de destination (Gmail, Yahoo! Mail, Outlook.com, etc.).

Pour afficher les messages chiffrés, les destinataires peuvent obtenir un code secret à usage unique, se connecter à l’aide d’un compte Microsoft ou se connecter à l’aide d’un compte professionnel ou scolaire associé à Office 365. Les destinataires peuvent également envoyer des réponses chiffrées. Ils n’ont pas besoin d’un abonnement pour afficher les messages chiffrés ou envoyer des réponses chiffrées.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs de messages bénéficient du contrôle supplémentaire sur les e-mails sensibles fournis par le chiffrement de messages Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 et Azure Information Protection Plan 1 fournissent les droits pour qu’un utilisateur bénéficie du chiffrement de messages Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs créent et gèrent les stratégies de chiffrement de messages Office 365 dans le Centre d’administration Exchange sous **Règles de flux de**  >  **messagerie.** Par défaut, ces règles s’appliquent à tous les utilisateurs du client. Pour plus d’informations sur la configuration des nouvelles fonctionnalités de chiffrement de messages Office 365, voir Configurer les nouvelles [fonctionnalités de chiffrement de messages.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs doivent appliquer des règles de flux de messagerie pour le chiffrement de messages Office 365 uniquement aux utilisateurs titulaires d’une licence. Pour plus d’informations sur la définition des règles de flux de messagerie, voir Définir des règles de flux de messagerie [pour chiffrer les messages électroniques.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Chiffrement avancé de messages Office 365

Le chiffrement de messages avancé Office 365 aide les clients à respecter les obligations de conformité qui nécessitent des contrôles plus flexibles sur les destinataires externes et leur accès aux e-mails chiffrés. Avec le chiffrement de messages avancé, les administrateurs peuvent contrôler les e-mails sensibles partagés en dehors de l’organisation à l’aide de stratégies automatiques qui peuvent détecter des types d’informations sensibles (par exemple, des informations d’identification personnelle ou des ID financiers ou d’état), ou ils peuvent utiliser des mots clés pour améliorer la protection en appliquant des modèles de courrier personnalisés et en arrivant à expiration de l’accès aux messages électroniques chiffrés via un portail web sécurisé. En outre, les administrateurs peuvent contrôler davantage les e-mails chiffrés accessibles en externe via un portail web sécurisé en révoquer l’accès à tout moment.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs de messages bénéficient du contrôle supplémentaire sur les e-mails sensibles fourni par le chiffrement de messages avancé.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5/G5 Information Protection and Governance fournissent aux utilisateurs les droits de bénéficier du chiffrement avancé des messages.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs créent et gèrent des stratégies de chiffrement de messages avancés dans le Centre d’administration Exchange sous **Règles de flux de**  >  **messagerie.** Par défaut, ces règles s’appliquent à tous les utilisateurs du client. Pour plus d’informations sur la configuration des nouvelles fonctionnalités de chiffrement de messages, voir Configurer les nouvelles fonctionnalités de chiffrement de [messages Office 365.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs doivent appliquer des règles de flux de messagerie pour le chiffrement de messages avancé uniquement aux utilisateurs titulaires d’une licence. Pour plus d’informations sur la définition des règles de flux de messagerie, voir Définir des règles de flux de messagerie pour chiffrer les messages électroniques [dans Office 365.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>Conformité des communications

La conformité des communications dans Microsoft 365 permet de réduire les risques de communication en vous aidant à détecter, capturer et prendre des mesures correctives pour les messages inappropriés dans votre organisation. Vous pouvez définir des stratégies spécifiques qui capturent le courrier électronique interne et externe, Microsoft Teams ou des communications tierces dans votre organisation. Les réviseurs peuvent prendre les mesures correctives appropriées pour s’assurer qu’ils sont conformes aux normes de message de votre organisation.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les spécialistes de la conformité bénéficient du service en faisant surveiller les communications de l’organisation par les stratégies de conformité des communications.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5/G5 Insider Risk Management fournissent les droits d’un utilisateur pour bénéficier de la conformité des communications.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs et les spécialistes de la conformité créent des stratégies de conformité des communications dans le Centre de conformité Microsoft 365. Ces stratégies définissent les communications et les utilisateurs qui sont soumis à révision dans l’organisation, définissent des conditions personnalisées que les communications doivent respecter et spécifient qui doit effectuer les révisions.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs choisissent des utilisateurs ou des groupes spécifiques à inclure dans une stratégie de conformité des communications. Lors du choix d’un groupe, il peut également sélectionner des utilisateurs spécifiques du groupe à exclure de la stratégie de conformité des communications. Pour plus d’informations sur les stratégies de conformité des communications, consultez La mise en place de la [conformité des communications dans Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)

## <a name="insider-risk-management"></a>Gestion des risques internes

La gestion des risques internes est une solution de Microsoft 365 qui vous permet de minimiser les risques internes en vous permettant de détecter, d’examiner et d’agir sur les activités à risque dans votre organisation.

Les stratégies personnalisées vous permettent de détecter et de prendre des mesures sur les activités malveillantes et par inadvertance à risque dans votre organisation, y compris la escalade de cas vers Microsoft Advanced eDiscovery, si nécessaire. Les analystes des risques de votre organisation peuvent rapidement prendre les mesures appropriées pour s’assurer que les utilisateurs sont conformes aux normes de conformité de votre organisation.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs peuvent tirer parti du fait que leurs activités sont surveillées pour les risques.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5 et Microsoft 365 E5/A5/G5 Insider Risk Management fournissent les droits d’un utilisateur pour bénéficier de la gestion des risques internes.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les stratégies de gestion des risques internes doivent être créées dans le Centre de conformité Microsoft 365 et affectées aux utilisateurs.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Lorsque vous créez une stratégie dans le Centre de conformité Microsoft  365, dans la **page** Choisir des utilisateurs et des groupes,  sélectionnez Choisir des utilisateurs ou des groupes pour sélectionner uniquement les utilisateurs sous licence, ou, si tous vos utilisateurs sont titulaires d’une licence, vous pouvez activer la case à cocher Tous les utilisateurs et groupes à messagerie. Pour plus d’informations, voir [Prise en charge de la gestion des risques internes.](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Stratégies d’accès conditionnel

L’accès conditionnel est l’outil utilisé par Azure Active Directory pour rassembler les signaux, prendre des décisions et appliquer des stratégies organisationnelles. L’accès conditionnel est au cœur du contrôle piloté par l’identité. Les stratégies d’accès conditionnel, à leur niveau le plus simple, sont des instructions if-then. Si un utilisateur souhaite accéder à une ressource, il doit effectuer une action. Exemple : un responsable de paie souhaite accéder à l’application de paie et doit effectuer une authentification multifacteur pour y accéder.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs titulaires d’une licence Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium et Azure Active Directory Premium Plan 1 peuvent bénéficier des stratégies d’accès conditionnel. Les utilisateurs titulaires d’une licence Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security et Azure Active Directory Premium Plan 2 peuvent bénéficier de identity protection (stratégies d’accès conditionnel basées sur les risques).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes des opérations de sécurité et les professionnels de la sécurité bénéficient de la possibilité d’appliquer des stratégies organisationnelles sur les utilisateurs, en exigeant qu’ils répondent à certains critères avant d’accorder l’accès au contenu d’entreprise. Les utilisateurs finaux bénéficient de la possibilité d’accéder à leur travail où qu’ils choisissent, tout en protégeant les biens de l’organisation.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités d’accès conditionnel sont activées au niveau du client pour tous les utilisateurs au sein du client.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Pour la protection des identités et l’accès conditionnel spécifiquement, un utilisateur doit être inclus dans un groupe ou ajouté à une stratégie d’accès conditionnel. La condition utilisateurs et groupes est obligatoire dans une stratégie d’accès conditionnel. Dans votre stratégie, vous pouvez sélectionner tous **les** utilisateurs ou des utilisateurs et groupes spécifiques. Vous devez sélectionner uniquement les utilisateurs et groupes sous licence appropriés. Pour plus d’informations, voir [Accès conditionnel : Conditions](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Audit avancé

L’audit avancé dans Microsoft 365 permet de conserver pendant un an les journaux d’audit pour les activités des utilisateurs et des administrateurs et offre la possibilité de créer des stratégies de rétention de journal d’audit personnalisées pour gérer la rétention des journaux d’audit pour d’autres services Microsoft 365. Il fournit également l’accès à des événements essentiels pour les enquêtes et un accès à bande passante élevée à l’API Activité de gestion Office 365. Pour plus d’informations, [voir Audit avancé dans Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

Vous pouvez également activer une période de rétention de 10 ans avec une référence (SKU) de modules. La référence (SKU) du module de module module est requise à partir du début de l’année 2021.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs titulaires d’une licence Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5 eDiscovery and Audit peuvent bénéficier de l’audit avancé.

Les utilisateurs titulaires d’une licence Avec audit avancé et le module de rétention du journal d’audit de 10 ans peuvent bénéficier de la rétention du journal d’audit pendant 10 ans.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs profitent de l’audit avancé, car les enregistrements d’audit liés à l’activité des utilisateurs dans les services Microsoft 365 peuvent être conservés pendant un an. En outre, les événements d’audit à valeur élevée sont enregistrés, par exemple lorsque des éléments de la boîte aux lettres d’un utilisateur sont accessibles ou lus. Pour plus d’informations, [voir Audit avancé dans Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, l’audit avancé est activé au niveau du client pour toutes les organisations qui disposent d’un abonnement Office 365 ou Microsoft 365 E5/A5/G5, et fournit automatiquement une conservation d’un an des journaux d’audit pour les activités (effectuées par les utilisateurs avec la licence appropriée) dans Azure Active Directory, Exchange et SharePoint. En outre, les organisations peuvent utiliser des stratégies de rétention du journal d’audit pour gérer la période de rétention des enregistrements d’audit générés par l’activité dans d’autres services Microsoft 365. La fonctionnalité rétention du journal d’audit de 10 ans est également activée à l’aide des mêmes stratégies de rétention. Pour plus d’informations, voir [gérer les stratégies de rétention du journal d’audit](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

La rétention d’un an des journaux d’audit et l’audit des événements essentiels s’appliquent uniquement aux utilisateurs titulaires de la licence appropriée. En outre, les administrateurs peuvent utiliser des stratégies de rétention du journal d’audit pour spécifier des durées de rétention plus courtes pour les journaux d’audit d’utilisateurs spécifiques.

La rétention de 10 ans des journaux d’audit s’applique uniquement aux utilisateurs titulaires de la licence de modules add-on appropriée. La référence (SKU) du module de module module est requise à partir du début de l’année 2021.
