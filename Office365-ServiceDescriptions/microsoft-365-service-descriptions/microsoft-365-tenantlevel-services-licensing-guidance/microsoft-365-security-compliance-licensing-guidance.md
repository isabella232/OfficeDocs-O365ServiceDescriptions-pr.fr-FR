---
title: Microsoft 365 licences pour la conformité & sécurité
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
description: Cet article fournit des conseils en matière de licences Microsoft 365 conformité afin d’éviter toute interruption de service potentielle en raison d’un accès sans licence.
ms.openlocfilehash: 9126cfa8d055fe9a800a6c498e79ebf540b378d2
ms.sourcegitcommit: e072b0e70346cb60f106188fe1aef54cf2b35ee2
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/17/2021
ms.locfileid: "58371762"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365 licences pour la conformité de &amp; la sécurité

Dans le cadre de cet article, un service au niveau du client est un service en ligne qui, lorsqu’il est acheté pour un utilisateur du client (autonome ou dans le cadre de plans Office 365 ou Microsoft 365), est activé en partie ou en intégralité pour tous les utilisateurs du &mdash; &mdash; client. Bien que certains utilisateurs sans licence puissent techniquement accéder au service, une licence est requise pour tous les utilisateurs qui souhaitent bénéficier du service.

> [!NOTE]
> Certains services clients ne sont actuellement pas en mesure de limiter les avantages à des utilisateurs spécifiques. Des efforts doivent être faits pour limiter les avantages du service aux utilisateurs titulaires d’une licence. Cela permet d’éviter toute interruption de service potentielle pour votre organisation une fois que les fonctionnalités de ciblage sont disponibles.

Pour voir les options de gestion des licences pour vos utilisateurs afin de bénéficier des fonctionnalités Microsoft 365 conformité, téléchargez [le Microsoft 365 comparaison.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory La protection des identités est une fonctionnalité du plan Azure Active Directory Premium P2 qui vous permet de détecter les vulnérabilités potentielles affectant les identités de votre organisation, de configurer des réponses automatisées aux actions suspectes détectées liées aux identités de votre organisation, d’examiner les incidents suspects et de prendre les mesures appropriées pour les résoudre.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité SecOps bénéficient d’affichages consolidés d’utilisateurs marqués et d’événements de risque basés sur des algorithmes d’apprentissage automatique. Les utilisateurs finaux bénéficient de la protection automatique fournie par l’accès conditionnel basé sur les risques et de la sécurité améliorée fournie en agissant sur les vulnérabilités.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security et Azure Active Directory Premium Plan 2 fournissent les droits à un utilisateur pour bénéficier de Azure Active Directory Identity Protection.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités Azure AD Identity Protection sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur Azure AD Identity Protection, voir [Qu’est-ce que Identity Protection ?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent définir l’étendue d’Azure AD Identity Protection en attribuant des stratégies de risque qui définissent le niveau de réinitialisation des mots de passe et en permettant l’accès aux utilisateurs sous licence uniquement. Pour obtenir des instructions sur l’étendue des déploiements Azure AD Identity Protection, voir Comment configurer et activer des stratégies [de risque.](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Gouvernance des identités

Azure Active Directory La gouvernance des identités vous permet d’équilibrer les besoins de votre organisation en matière de sécurité et de productivité des employés avec les processus et la visibilité qui leur sont nécessaires. Il utilise la gestion des droits, les révisions d’accès, la gestion des identités privilégiées et les stratégies de conditions d’utilisation pour s’assurer que les bonnes personnes disposent d’un accès aux ressources appropriées.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Azure Active Directory La gouvernance des identités augmente la productivité des utilisateurs en rendant plus facile la demande d’accès aux applications, groupes et Microsoft Teams un seul package d’accès. Les utilisateurs peuvent également être configurés en tant qu’approuveurs, sans impliquer d’administrateurs. Pour les révisions d’accès, les utilisateurs peuvent passer en revue les appartenances à des groupes avec des recommandations intelligentes pour prendre des mesures à intervalles réguliers.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security et Azure Active Directory Premium Plan 2 fournissent aux utilisateurs les droits dont ils ont besoin pour bénéficier de Azure Active Directory Identity Governance.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les fonctionnalités de gouvernance d’identité Azure AD sont activées au niveau du client, mais implémentées par utilisateur. Pour plus d’informations sur la gouvernance des identités Azure AD, voir [Qu’est-ce qu’Azure AD Identity Governance ?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent affecter l’étendue de la gouvernance des identités Azure AD en attribuant des packages d’accès, des révisions d’accès ou une gestion privilégiée des identités pour les utilisateurs sous licence uniquement. Pour obtenir des instructions sur l’étendue des déploiements azure AD Identity Governance, voir :

- [Conditions requises pour la gestion des droits Azure AD](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Conditions requises pour la licence de révision de l’accès à Azure AD](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Conditions requises pour les licences d’utilisation Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender pour l’identité

Microsoft Defender for Identity (anciennement Azure Advanced Threat Protection) est un service cloud qui permet de protéger les environnements hybrides d’entreprise contre plusieurs types de cyberattaques ciblées avancées et de menaces internes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité SecOp bénéficient de la capacité de Microsoft Defender for Identity à détecter et examiner les menaces avancées, les identités compromises et les actions malveillantes internes. Les utilisateurs finaux bénéficient de la surveillance de leurs données par Microsoft Defender for Identity.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security et Microsoft Defender for Identity for Users fournissent les droits pour bénéficier de Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de Microsoft Defender pour l’identité sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration d’Azure ATP, voir [Créer votre instance de Microsoft Defender pour l’identité.](/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Microsoft Defender pour les services d’identité n’est actuellement pas capable de limiter les fonctionnalités à des utilisateurs spécifiques. Vous devez obtenir une licence pour chaque utilisateur dont vous avez l’intention d’en bénéficier.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender pour Office 365

Microsoft Defender for Office 365 (anciennement Office 365 Protection avancée contre les menaces) permet de protéger les organisations contre les attaques sophistiquées telles que le hameçonnage et les programmes malveillants « zero-day ». Microsoft Defender pour Office 365 fournit également des informations actionnables en corrélant les signaux provenant d’un large éventail de données pour vous aider à identifier, hiérarchiser et fournir des recommandations sur la façon de traiter les menaces potentielles.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Microsoft Defender pour Office 365 protège les utilisateurs contre les attaques sophistiquées telles que le hameçonnage et les programmes malveillants « zero-day ». Pour obtenir la liste complète des services fournis dans les plans 1 et 2, consultez [Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ? 

Les plans Microsoft Defender pour Office 365 1 et 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, sécurité Microsoft 365 E5/A5/G5 et Microsoft 365 Business Premium fournissent aux utilisateurs les droits de bénéficier de Microsoft Defender pour Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de Microsoft Defender Office 365 sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de Microsoft Defender pour les stratégies Office 365 pour les utilisateurs sous licence, consultez [Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Pour étenduer Microsoft Defender à Office 365, suivez les stratégies de déploiement Coffre liens Coffre pièces jointes :

- Pour plus d’informations sur la configuration Coffre liens vers les utilisateurs sous licence, voir Coffre Liens vers [Microsoft Defender pour Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Pour plus d’informations sur la configuration Coffre pièces jointes pour les utilisateurs sous licence, voir Coffre [pièces jointes](/microsoft-365/security/office-365-security/atp-safe-attachments)dans Microsoft Defender pour Office 365 .

## <a name="office-365-cloud-app-security"></a>Sécurité de l’application cloud Office 365

Sécurité des applications cloud Office 365 (OCAS) est un sous-ensemble de Microsoft Cloud App Security, avec des fonctionnalités limitées à Office 365 et sans sécurité supplémentaire pour les applications cloud tierces et les services IaaS.

OCAS offre aux organisations une visibilité sur leurs applications et services cloud de productivité, fournit des analyses sophistiquées pour identifier et lutter contre les cybermenaces et leur permet de contrôler la façon dont les données circulent dans &mdash; Office 365.

Pour comparer les [fonctionnalités,](/cloud-app-security/editions-cloud-app-security-o365)voir Différences entre Microsoft Cloud App Security et Sécurité des applications cloud Office 365 .

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

OCAS découvre shadow IT, fournit une protection contre les menaces dans Office 365 et peut contrôler quelles applications sont autorisées à accéder aux données.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Office 365 E5/A3/A5/G5 fournissent aux utilisateurs les droits de bénéficier d’OCAS.
Pour plus d’informations, consultez [la Microsoft Cloud App Security de données de licences.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités OCAS sont activées au niveau du client pour tous les utilisateurs au sein du client.

Pour plus d’informations sur la configuration du service, voir [Configuration de](/cloud-app-security/general-setup)base Sécurité des applications cloud .

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent limiter les déploiements OCAS pour appliquer la façon dont certaines applications sont accessibles et limiter les groupes d’utilisateurs surveillés par Sécurité des applications cloud Office 365. Pour plus d’informations, voir [Déploiement dans l’étendue.](/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) est une solution Cloud Access Security Broker (CASB) qui donne aux organisations une visibilité sur leurs applications et services cloud, fournit des analyses sophistiquées pour identifier et lutter contre les cybermenaces et leur permet de contrôler la façon dont les données circulent dans n’importe quelle application &mdash; cloud.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

MCAS découvre et évalue le service informatique de l’ombre, fournit une protection contre les menaces dans les applications cloud tierces et tierces, et protège les informations sur les applications cloud tierces et de premier niveau.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance, and Microsoft 365 Information Protection and Governance provide the rights for a user to benefit from MCAS.

Azure AD P1 fournit aux utilisateurs les droits de bénéficier des fonctionnalités de découverte dans MCAS.

Pour bénéficier des fonctionnalités de contrôle d’application d’accès conditionnel dans MCAS, les utilisateurs doivent également être titulaires d’une licence Azure Active Directory P1, incluse dans Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 et Microsoft 365 E5/A5/G5 Security.

Pour bénéficier de l’étiquetage côté client automatique, les utilisateurs doivent être titulaires d’une licence Azure Information Protection P2, incluse dans Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 Information Protection and Governance.

> [!NOTE]
> L’étiquetage automatique côté serveur nécessite la protection des informations Office 365 - Premium licences ( `MIP_S_CLP2` ou `efb0351d-3b08-4503-993d-383af8de41e3` ). Pour référence, voir Noms de produits [et identificateurs de plan de service pour la gestion des licences.](/azure/active-directory/enterprise-users/licensing-service-plan-reference)

Pour plus d’informations, consultez [la Microsoft Cloud App Security de données de licences.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités MCAS sont activées au niveau du client pour tous les utilisateurs au sein du client.

Pour plus d’informations sur la configuration Microsoft Cloud App Security stratégies de licence pour les utilisateurs sous licence, [voir Microsoft Cloud App Security vue d’ensemble.](/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent étendue les déploiements MCAS aux utilisateurs titulaires d’une licence à l’aide des fonctionnalités de déploiement étendues disponibles dans le service. Pour plus d’informations, voir [Déploiement dans l’étendue.](/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Gestionnaire de conformité

[Le Gestionnaire de conformité Microsoft](https://compliance.microsoft.com/compliancemanager) est une fonctionnalité du [Centre de conformité Microsoft 365](/microsoft-365/compliance/microsoft-365-compliance-center) qui vous permet de gérer les exigences de conformité de votre organisation avec plus de simplicité et de commodité. Le Gestionnaire de conformité peut vous aider tout au long de votre parcours de conformité, de l’inventaire de vos risques de protection des données à la gestion des complexités de l’implémentation des contrôles, à la mise à jour des réglementations et des certifications et à la gestion des rapports aux auditeurs.

Le Gestionnaire de conformité simplifie la conformité et réduit les risques en fournissant :

- Des évaluations préétablies pour les normes et réglementations sectorielles et régionales courantes ou des évaluations personnalisées pour répondre à vos besoins uniques en matière de conformité.
- Fonctionnalités de flux de travail pour vous aider à évaluer efficacement vos risques à l’aide d’un seul outil.
- Recommandations détaillées détaillées sur les suggestions d’actions d’amélioration pour vous aider à vous conformer aux normes et réglementations les plus pertinentes pour votre organisation. Pour les actions gérées par Microsoft, vous verrez les détails de l’implémentation et les résultats de l’audit.
- Un score de conformité basé sur les risques pour vous aider à comprendre votre posture de conformité en mesurant votre progression dans l’exécution des actions d’amélioration.

### <a name="who-can-access-compliance-manager"></a>Qui pouvez-vous accéder au Gestionnaire de conformité ?

Le Gestionnaire de conformité est disponible pour les organisations titulaires de licences Office 365 et Microsoft 365, ainsi que pour les clients Cloud de la communauté du secteur public (Cloud de la communauté du secteur public), Cloud de la communauté du secteur public High et Department of Defense (DoD). La disponibilité de l’évaluation et les fonctionnalités de gestion dépendent de votre contrat de licence.

### <a name="compliance-manager--premium-assessments"></a>Gestionnaire de conformité – Évaluations Premium de conformité

Premium Les évaluations sont une valeur ajoutée pour le Gestionnaire de conformité et de l’aide :

- Traduire des exigences réglementaires complexes en contrôles spécifiques
- Suggérer des actions d’amélioration recommandées
- Fournir une mesure quantifiable de conformité par rapport aux réglementations

Le Gestionnaire de conformité a plus de 300 évaluations Premium que les clients peuvent utiliser pour évaluer leur conformité avec un large éventail de réglementations et normes mondiales, régionales et industrielles.

Tout client avec un abonnement incluant une licence Microsoft Exchange Online peut acheter le Gestionnaire de conformité Premium évaluations.

### <a name="what-premium-assessments-are-available"></a>Quelles Premium d’évaluation sont disponibles ?

Voici la liste [des évaluations Premium.](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates)

### <a name="what-assessments-are-included-by-default-free-of-cost"></a>Quelles évaluations sont incluses par défaut (gratuitement) ?

Certaines évaluations sont incluses dans le cadre du Gestionnaire de conformité et du type de licence client. Pour plus d’informations, voir le tableau ci-dessous :

| Type de licence | Modèles d’évaluation (inclus par défaut) |
|:-----|:-----|
|<ul><li>Microsoft 365 ou Office 365 A1/E1/F1/G1</li><li>Microsoft 365 ou Office 365 A3/E3/F3/G3</li></ul>|<ul><li>Base de référence de protection des données</li></ul>|
|<ul><li>Microsoft 365 ou Office 365 A5/E5/G5</li><li>Microsoft 365 A5 conformité E5/F5/G5</li><li>Microsoft 365 A5 eDiscovery et audit E5/F5/G5</li><li>Microsoft 365 A5/E5/F5/G5 Gestion des risques internes</li><li>Microsoft 365 A5/E5/F5/G5 Information Protection and Governance</li></ul>|<ul><li>Base de référence de protection des données</li><li>RGPD de l'UE</li><li>NIST 800-53</li><li>ISO 27001</li><li>Évaluations des clients</li><li>CmMC de niveau 1 à 5 (disponible uniquement pour G5)</li></ul>|

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender pour point de terminaison

Microsoft Defender pour le point de terminaison (anciennement Microsoft Defender ATP) est une solution de sécurité de point de terminaison qui inclut des évaluations et des gestion des vulnérabilités basées sur les risques . fonctionnalités de réduction de la surface d’attaque ; protection de nouvelle génération basée sur le comportement et basée sur le cloud ; protection évolutive des points de terminaison (PEPT) ; examen et correction automatiques ; et les services de recherche gérés. Pour en [savoir plus, consultez](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) la page Microsoft Defender pour le point de terminaison.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs sous licence de Windows 10 Entreprise E5, Windows 10 Éducation A5, Microsoft 365 E5/G5, qui inclut Windows 10 Entreprise E5, Microsoft 365 E5/A5/G5 Security, peuvent bénéficier de Microsoft Defender pour endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes et les professionnels de la sécurité SecOps bénéficient des fonctionnalités de sécurité des points de terminaison de Microsoft Defender for Endpoint pour assurer la protection préventive, la détection post-violation, l’examen automatisé et la réponse aux menaces avancées. Les utilisateurs finaux bénéficient d’événements malveillants surveillés par Microsoft Defender for Endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de Microsoft Defender pour le point de terminaison sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur le déploiement, voir [Phases de déploiement.](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs microsoft Defender pour les points de terminaison peuvent utiliser le contrôle d’accès basé sur un rôle (RBAC) pour créer des rôles et des groupes au sein de l’équipe des opérations de sécurité afin d’accorder un accès approprié à l’Centre de sécurité Microsoft Defender. Pour plus d’informations, voir [Gérer l’accès au portail à l’aide du contrôle d’accès basé sur les rôles.](/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365 classification des données : Vue d’ensemble de &amp; l’Explorateur d’activités de contenu

Les fonctionnalités analytiques de classification des données sont disponibles dans Centre de conformité Microsoft 365 expérience utilisateur. Vue d’ensemble des emplacements de contenu numérique et des étiquettes et types d’informations sensibles les plus courants. L’Explorateur de contenu offre une visibilité sur la quantité et les types de données sensibles et permet aux utilisateurs de filtrer par étiquette ou type de sensibilité pour obtenir une vue détaillée des emplacements où les données sensibles sont stockées. L’Explorateur d’activités affiche les activités liées aux données et étiquettes sensibles, telles que les rétrogradations d’étiquettes ou le partage externe qui peuvent exposer votre contenu à des risques.

L’Explorateur d’activités fournit un volet unique de verre aux administrateurs pour obtenir une visibilité sur les activités liées aux informations sensibles utilisées par les utilisateurs finaux. Ces données incluent les activités des étiquettes, les journaux de protection contre la perte de données (DLP), l’étiquetage automatique, la protection contre la perte de données et bien plus encore.

L’Explorateur de contenu permet aux administrateurs d’indexer les documents sensibles stockés dans les charges de travail Microsoft 365 et d’identifier les informations sensibles qu’ils stockent. En outre, l’Explorateur de contenu permet d’identifier les documents classés avec des étiquettes de sensibilité et de rétention.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les administrateurs de la protection des informations et de la conformité peuvent accéder au service pour accéder à ces journaux et données indexées pour comprendre où les données sensibles sont stockées et quelles activités sont liées à ces données et effectuées par les utilisateurs finaux.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Les utilisateurs titulaires d’une licence Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, gouvernance et gouvernance de la Office 365 E5 protection des informations Microsoft 365 E5/A5/G5 peuvent tirer parti de l’analyse de la classification des Microsoft 365 &amp; données. 

Microsoft 365 E3/A3/G3 et Office 365 E3/A3/G3 permettent aux utilisateurs de bénéficier uniquement de l’agrégation de données de l’Explorateur de contenu.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités De l’Explorateur de contenu de vue d’ensemble et d’activité sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de l’analyse de la classification des données pour les utilisateurs sous licence, voir :

- **Explorateur de contenu**: [démarrer avec l’Explorateur de contenu - Microsoft 365 conformité | Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **Explorateur d’activités**: [démarrer avec l’Explorateur d’activités - Microsoft 365 conformité | Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **Notes de publication sur la classification des données**: notes de publication de classification des données - Microsoft 365 conformité [| Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Cette fonctionnalité doit être étendue aux utilisateurs qui utilisent activement la solution dans Microsoft 365 portail de conformité.

## <a name="information-protection"></a>Protection des informations

La protection des informations permet aux organisations de découvrir, classifier, étiqueter et protéger les documents et e-mails sensibles. Les administrateurs peuvent définir des règles et des conditions pour appliquer automatiquement des étiquettes, les utilisateurs peuvent appliquer des étiquettes manuellement ou une combinaison des deux peut être utilisée, où les utilisateurs ont des recommandations sur l’application d’étiquettes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité d’appliquer manuellement des étiquettes de sensibilité à leur contenu ou de classer automatiquement leur contenu.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 et AIP Plan 2 fournissent aux utilisateurs les droits de bénéficier de l’étiquetage de sensibilité manuel.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 et AIP Plan 2 permettent à un utilisateur de bénéficier de l’application et de l’affichage d’étiquettes de sensibilité dans Power BI et de protéger les données lorsqu’elles sont exportées de Power BI vers Excel, PowerPoint ou PDF.

Microsoft 365 Business Premium et Enterprise Mobility fournissent les droits d’utilisation du module [PowerShell AIPService](/powershell/azure/aip/overview#aipservice) pour administrer le service Azure Rights Management protection des informations azure.

> [!NOTE]
> Power BI est inclus avec Microsoft 365 E5/A5/G5 ; dans tous les autres plans, les Power BI doivent être sous licence séparément.

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, protection des informations Microsoft 365 E5/A5/G5, gouvernance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 et plan AIP 2 fournissent aux utilisateurs les droits de bénéficier de l’étiquetage de sensibilité automatique.

La protection des informations n’inclut pas les droits à la classification automatique basée sur Machine Learning (classifieurs entraidables).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de protection des informations sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration des stratégies pour les utilisateurs sous licence, voir Activating Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Sauf en cas d’utilisation de la fonctionnalité de scanneur AIP, les stratégies peuvent être limitées à des groupes spécifiques, ou des utilisateurs et registres peuvent être modifiés pour empêcher les utilisateurs sans permis d’utiliser des fonctionnalités de classification ou d’étiquetage.

Pour la fonctionnalité de scanneur AIP, Microsoft ne s’engage pas à fournir des fonctionnalités de classification de fichier, d’étiquetage ou de protection aux utilisateurs qui ne disposent pas d’une licence.

Pour plus d’informations, voir [Créer et publier](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy) des étiquettes de sensibilité et Comprendre le scanneur d’étiquetage unifié Azure Information [Protection.](/azure/information-protection/deploy-aip-scanner)

## <a name="information-governance"></a>Gouvernance des informations

La gouvernance des informations permet aux organisations de gérer leurs risques par la découverte, la classification, l’étiquetage et la gouvernance de leurs données. La gouvernance des informations permet aux organisations de répondre aux exigences commerciales et réglementaires, ainsi que de réduire leur surface d’attaque en fournissant des fonctionnalités de rétention et de suppression dans leurs données Microsoft 365 et tierces.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité de classer des données à des fins de rétention afin de respecter des stratégies et réglementations spécifiques.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

les plans Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 et Exchange autonomes offrent aux utilisateurs les droits de bénéficier de l’application manuelle d’étiquettes de rétention non-enregistrement aux données de boîte aux lettres.

les plans Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 et SharePoint autonome fournissent les droits dont un utilisateur peut bénéficier pour appliquer manuellement des étiquettes de rétention non-enregistrement à des fichiers en SharePoint ou OneDrive. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plan 2 et Archivage Exchange Online fournissent aux utilisateurs les droits de bénéficier d’une stratégie de rétention de boîte aux lettres de base à l’échelle de l’organisation ou à l’échelle de l’emplacement et/ou d’appliquer manuellement une étiquette de rétention sans enregistrement aux données de boîte aux lettres.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 et SharePoint Plan 2 permettent à un utilisateur de bénéficier d’une stratégie de rétention SharePoint ou OneDrive de base et/ou d’appliquer manuellement une étiquette de rétention sans enregistrement aux fichiers dans SharePoint ou OneDrive.

Les organisations peuvent utiliser des stratégies de rétention pour conserver ou supprimer Teams messages en fonction de leurs stratégies. Cela inclut la gestion des messages dans Teams conversations et conversations.

Les licences suivantes permettent à un utilisateur de bénéficier d’une stratégie Teams rétention :

- Microsoft 365 E5/G5/A5/E3/G3/A3
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

Notez que pour les utilisateurs titulaires des licences suivantes, la période de rétention ou de suppression minimale prise en charge est de 30 jours :

- Microsoft 365 F1/F3, Business Basic, Business Standard et Business Premium
- Office 365 E1/G1 et F3

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, Microsoft 365 Protection des informations et gouvernance E5/A5/G5, et Office 365 E5/A5 fournissent aux utilisateurs les droits de bénéficier de l’application automatique d’étiquettes ou de stratégies de rétention, de l’application d’étiquettes ou de stratégies de rétention par défaut, du démarrage de la période de rétention d’une étiquette basée sur un événement personnalisé, du déclenchement d’une révision manuelle à la fin de la période de rétention de l’étiquette, de l’importation de données tierces via des connecteurs de données natives, de la déclaration d’un fichier comme enregistrement, de la découverte du contenu étiqueté et de la surveillance de l’activité d’étiquetage.

Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5, la protection des informations Microsoft 365 E5/A5/G5 et la gouvernance fournissent aux utilisateurs les droits nécessaires pour bénéficier de l’application automatique d’étiquettes de rétention basées sur des classifieurs entraisables.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de gouvernance des informations sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de la gouvernance des informations afin d’appliquer l’ingage automatique et les stratégies pour les utilisateurs sous licence, voir Gouvernance des informations [Microsoft dans Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les fonctionnalités de gouvernance des informations peuvent être appliquées aux utilisateurs sous licence à des emplacements spécifiques (sites d’équipe, sites de groupe, etc.). Pour plus d’informations sur la configuration de la gouvernance des informations afin d’appliquer l’ingage automatique et les stratégies pour les utilisateurs sous licence, voir Gouvernance des informations [Microsoft dans Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gestion des enregistrements

La gestion des enregistrements aide les organisations à respecter leurs obligations commerciales et réglementaires en matière de conservation des enregistrements par le biais de la découverte, de la classification, de l’étiquetage, de la rétention et de la suppression à l’échelle de leurs Microsoft 365 et de leurs données tierces.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, conformité Microsoft 365 E5/A5/G5, Microsoft 365 Information Protection and Governance E5/A5/G5 et Office 365 E5/A5/G5 fournissent aux utilisateurs les droits de bénéficier de la gestion des enregistrements, y compris la déclaration d’éléments en tant qu’enregistrements ou enregistrements réglementaires, l’application automatique d’étiquettes de rétention ou d’enregistrements et l’exécution de processus de révision de disposition (à l’exclusion de l’application automatique d’une étiquette de rétention basée sur des classifieurs entra nessables).

Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5 et la gouvernance et la protection des informations Microsoft 365 fournissent aux utilisateurs les droits nécessaires pour bénéficier de l’application automatique d’étiquettes de rétention ou d’enregistrement basées sur des classifieurs entraisables.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la possibilité de déclarer du contenu en tant qu’enregistrement et de gérer leur processus d’enregistrements complet à partir de la définition et de la déclaration de stratégie par le biais d’une élimination de stratégie.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités de gestion des enregistrements sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration de la gestion des enregistrements à appliquer aux utilisateurs sous licence, voir En savoir plus sur la gestion des enregistrements [dans Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les fonctionnalités de gestion des enregistrements peuvent être appliquées aux utilisateurs sous licence à des emplacements spécifiques (sites d’équipe, sites de groupe, etc.). Pour plus d’informations sur la configuration de la gestion des enregistrements à appliquer aux utilisateurs sous licence, voir En savoir plus sur la gestion des enregistrements [dans Microsoft 365](/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Connecteurs de données 

Microsoft fournit des connecteurs de données tiers qui peuvent être configurés dans le Centre de conformité Microsoft 365. Pour obtenir la liste des connecteurs de données fournis par Microsoft, consultez la table [des connecteurs de données tiers.](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) Ce tableau récapitule également les solutions de conformité que vous pouvez appliquer aux données tierces après avoir importé et archivé des données dans Microsoft 365, ainsi que des liens vers les instructions pas à pas pour chaque connecteur.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Le principal avantage de l’utilisation de connecteurs de données pour importer et archiver des données tierces dans Microsoft 365 est que vous pouvez appliquer différentes solutions de conformité Microsoft 365 aux données après leur importation. Cela permet de s’assurer que les données non-Microsoft de votre organisation sont conformes aux réglementations et normes qui affectent votre organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Les licences suivantes permettent à un utilisateur de bénéficier des connecteurs de données :

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5 gouvernance de la protection des informations A5/G5 &amp;
- Microsoft 365 E5 conformité A5/G5
- Microsoft 365 E5/A5/G5 Insider Risk Management
- Microsoft 365 E5/A5/G5 eDiscovery et Audit
- Office 365 E5/A5/G5

Pour les connecteurs de données dans le Centre de conformité de sécurité Microsoft 365 qui sont fournis par un partenaire Microsoft, votre organisation a besoin d’une relation professionnelle avec le partenaire avant de pouvoir déployer ces &amp; connecteurs.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les connecteurs sont configurés à l’aide du Centre de conformité de &amp; sécurité et du catalogue de connecteurs.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les services connecteurs de données sont une valeur au niveau du client. Chaque utilisateur destiné à bénéficier de ce service doit être titulaire d’une licence.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>API microsoft Graph pour la protection contre Teams perte de données (DLP)

Plus tôt cette année, nous avons annoncé la prévisualisation publique de l’API de notification de modification Graph Microsoft pour les [messages Teams](https://go.microsoft.com/fwlink/?linkid=2143888). Cette API permet aux développeurs de créer des applications qui peuvent écouter Microsoft Teams messages en temps quasi réel et activer les implémentations de scénarios DLP pour les clients et les logiciels indépendants. En outre, Microsoft Graph l’API patch permet d’appliquer des actions DLP Teams messages.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les fonctionnalités de protection contre la perte de données [(DLP)](/microsoft-365/compliance/dlp-microsoft-teams) sont largement utilisées dans Microsoft Teams, en particulier lorsque les organisations ont été décalées vers le travail à distance. Si votre organisation dispose d’une DLP, vous pouvez désormais définir des stratégies qui empêchent les personnes de partager des informations sensibles dans un canal Microsoft Teams ou une session de conversation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Vous aurez besoin de l’une des licences suivantes pour obtenir la prise en charge de la protection DLP dans Teams chat :

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5 conformité A5/G5/F5
- Microsoft 365 F5 Security & Compliance
- Microsoft 365 E5/A5/G5 Information Protection and Governance
- Office 365 E5/A5/G5

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

L’accès à l’API est configuré au niveau du client.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Microsoft Graph API pour Teams DLP est une valeur au niveau du client. Chaque utilisateur destiné à bénéficier de ce service doit être titulaire d’une licence.

## <a name="ediscovery"></a>eDiscovery

eDiscovery fournit des solutions d’examen et eDiscovery aux services informatiques et juridiques au sein d’entreprises pour identifier, collecter, conserver, réduire et examiner le contenu lié à un examen ou à un litige avant d’exporter hors du système Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Un utilisateur bénéficie de Advanced eDiscovery lorsqu’il est sélectionné en tant que dépositaire de données (une personne ayant le contrôle administratif d’un document ou d’un fichier électronique) pour un cas.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 fournissent les droits d’un utilisateur pour bénéficier de core eDiscovery.

Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5, la découverte électronique et l’audit Microsoft 365 E5/A5/G5 et Office 365 E5/A5/G5 fournissent les droits d’un utilisateur pour bénéficier de Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, Advanced eDiscovery fonctionnalités de découverte électronique sont activées au niveau du client pour tous les utilisateurs au sein du client lorsque les administrateurs attribuent des autorisations eDiscovery dans le Centre de conformité de &amp; sécurité.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs eDiscovery peuvent sélectionner des utilisateurs spécifiques en tant que dépositaires de données pour un cas à l’aide de l’outil de gestion des dépositaires intégré dans Advanced eDiscovery comme décrit dans Ajouter des dépositaires à un cas [Advanced eDiscovery.](/microsoft-365/compliance/add-custodians-to-case)

## <a name="customer-key-for-microsoft-365"></a>Clé client pour Microsoft 365

Avec la clé client, vous contrôlez les clés de chiffrement de votre organisation et configurez les Microsoft 365 les utiliser pour chiffrer vos données au repos dans les centres de données Microsoft. En d’autres termes, la clé client vous permet d’ajouter une couche de chiffrement qui vous appartient, à l’aide de vos propres clés. Les données au repos incluent les données provenant de Exchange Online et Skype Entreprise stockées dans des boîtes aux lettres et des fichiers au sein de SharePoint Online et OneDrive Entreprise.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la clé client en chiffrant leurs données au repos au niveau de la couche application à l’aide de clés de chiffrement fournies, contrôlées et gérées par leur propre organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5, la gouvernance et la protection des informations Microsoft 365 E5/A5/G5 et Office 365 E5/A5/G5 fournissent les droits d’un utilisateur pour bénéficier de la clé client. Pour bénéficier pleinement de la clé client, vous devez également avoir un abonnement à Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

La clé client pour Microsoft 365 clés de chiffrement peut être activée pour toutes les données stockées dans les boîtes aux lettres Exchange Online et Skype Entreprise, ainsi que pour les fichiers SharePoint Online, OneDrive Entreprise et Teams. Pour plus d’informations sur la clé client, notamment sur la façon de commencer, voir Chiffrement de [service avec clé client.](/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Pour Exchange Online et Skype Entreprise, les boîtes aux lettres peuvent être chiffrées à l’aide de la clé client. Vous devez configurer Azure avant de pouvoir utiliser la clé client pour Microsoft 365. Voir [Configurer la](/microsoft-365/compliance/customer-key-set-up) clé client pour les étapes à suivre pour créer et configurer les ressources Azure requises et les étapes de configuration de la clé client dans Microsoft 365. Une fois l’installation d’Azure terminée, déterminez la stratégie et, par conséquent, les clés à affecter aux boîtes aux lettres et aux fichiers de votre organisation. Pour plus d’informations sur la clé client et le contenu concernant les données de Exchange Online, Skype Entreprise, SharePoint Online, OneDrive Entreprise et Teams, voir Chiffrement de [service](/microsoft-365/compliance/customer-key-overview)avec clé client.

## <a name="office-365-customer-lockbox"></a>Customer Lockbox dans Office 365

Customer Lockbox fournit une couche de contrôle supplémentaire en offrant aux clients la possibilité d’accorder une autorisation d’accès explicite pour les opérations de service. En montrant que des procédures sont en place pour l’autorisation d’accès aux données explicite, Customer Lockbox peut également aider les organisations à respecter certaines obligations de conformité telles que HIPAA et FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Customer Lockbox garantit que personne chez Microsoft ne peut accéder au contenu client pour effectuer une opération de service sans l’approbation explicite du client. Customer Lockbox amène le client dans le flux de travail d’approbation pour les demandes d’accès à son contenu. Parfois, les ingénieurs Microsoft sont impliqués pendant le processus de support pour résoudre les problèmes signalés par le client. Dans la plupart des cas, les problèmes sont résolus par le biais d’outils de télémétrie et de débogage étendus que Microsoft a mis en place pour ses services. Toutefois, dans certains cas, un ingénieur Microsoft peut avoir besoin d’accéder au contenu du client pour déterminer la cause première et résoudre le problème. Customer Lockbox nécessite l’intervention de l’ingénieur pour demander l’accès au client en tant que dernière étape du flux de travail d’approbation. Cela permet aux organisations d’approuver ou de refuser ces demandes, ce qui leur permet de contrôler directement si un ingénieur Microsoft peut accéder aux données de l’utilisateur final de l’organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5 et la gestion des risques internes Microsoft 365 E5/A5/G5 offrent aux utilisateurs les droits de bénéficier du Customer Lockbox.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs peuvent activer Customer Lockbox dans le Centre d’administration Microsoft 365. Pour plus d’informations, voir [Customer Lockbox dans Office 365](/microsoft-365/compliance/customer-lockbox-requests). Lorsque Customer Lockbox est allumé, Microsoft doit obtenir l’approbation d’une organisation avant d’accéder à son contenu.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Actuellement, le service Customer Lockbox ne peut pas être limité à des utilisateurs spécifiques. Bien que les services clients ne soient actuellement pas capables de limiter les avantages à des utilisateurs spécifiques, des efforts doivent être faits pour limiter les avantages du service aux utilisateurs titulaires d’une licence. Cela permet d’éviter les interruptions de service potentielles une fois que les fonctionnalités de ciblage sont disponibles.

## <a name="privileged-access-management-in-office-365"></a>Gestion des accès privilégiés dans Office 365

[La gestion des accès privilégiés (PAM)](/microsoft-365/compliance/privileged-access-management-configuration) fournit un contrôle d’accès granulaire sur les tâches d’administration privilégiées Office 365. Après avoir autorisé PAM, pour effectuer des tâches avec élévation de privilèges et privilégiées, les utilisateurs doivent demander un accès juste-à-temps via un flux de travail d’approbation hautement limité et limité dans le temps.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

L’activation du PAM permet aux organisations de fonctionner sans privilège permanent. Les utilisateurs bénéficient de la couche de défense supplémentaire contre les vulnérabilités résultant de l’accès administratif permanent qui fournit un accès illimité à leurs données.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ? 

Office 365 E5/A5, Microsoft 365 E5/A5, conformité Microsoft 365 E5/A5 et protection et gouvernance des informations Microsoft 365 E5/A5 fournissent les droits d’un utilisateur pour tirer parti de PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités PAM sont activées au niveau du client pour tous les utilisateurs au sein du client. Pour plus d’informations sur la configuration des stratégies PAM, voir Prise en charge de la [gestion des accès privilégiés.](/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les clients peuvent gérer le PAM par utilisateur par le biais du groupe d’approbation et des stratégies d’accès, qui peuvent être appliquées aux utilisateurs sous licence. Pour plus d’informations, [voir Privileged access management dans Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Chiffrement à double clé pour Microsoft 365 

Le chiffrement à double clé Microsoft 365 vous permet de protéger vos données hautement sensibles afin de répondre à des exigences spécialisées et de maintenir un contrôle total de votre clé de chiffrement. Le chiffrement à double clé utilise deux clés pour protéger vos données, avec une clé dans votre contrôle et la seconde clé stockée en toute sécurité par Microsoft Azure. Pour afficher les données, vous devez avoir accès aux deux clés. Étant donné que Microsoft ne peut accéder qu’à une seule clé, votre clé et vos données ne sont pas disponibles pour Microsoft, ce qui garantit que vous avez un contrôle total sur la confidentialité et la sécurité de vos données.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient du chiffrement à double clé en étant en mesure de migrer leurs données chiffrées vers le cloud, ce qui empêche l’accès de tiers tant que la clé reste sous le contrôle des utilisateurs. Les utilisateurs peuvent protéger et consommer du contenu chiffré à double clé similaire à tout autre contenu protégé par une étiquette de sensibilité.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5, la protection et la gouvernance des informations Microsoft 365 E5/A5/G5 et Office 365 E5/A5/G5 fournissent les droits d’un utilisateur pour bénéficier du chiffrement à double clé.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Le chiffrement à double clé prend en charge la version de bureau Microsoft Office pour Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Pour affecter des clés de chiffrement aux données au sein d’une Office 365 et/ou d’une Microsoft 365 pour les utilisateurs sous licence, suivez les instructions de déploiement du chiffrement à double clé.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 protection contre la perte de données pour Exchange Online, SharePoint Online et OneDrive Entreprise

Avec la protection contre la perte de données (DLP) Office 365 pour Exchange Online, SharePoint Online et OneDrive Entreprise, les organisations peuvent identifier, surveiller et protéger automatiquement les informations sensibles dans les e-mails et les fichiers (y compris les fichiers stockés dans des référentiels de fichiers Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient de la DLP pour Exchange Online, SharePoint Online et OneDrive Entreprise lorsque leurs messages électroniques et fichiers sont inspectés pour des informations sensibles, comme configuré dans la stratégie DLP de l’organisation.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 et la protection contre la perte de données Office 365 permettent à un utilisateur de bénéficier de la protection contre la perte de données Office 365 pour Exchange Online, SharePoint Online et OneDrive Entreprise.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, Exchange Online courriers électroniques, les sites SharePoint et les comptes OneDrive sont des *emplacements (charges de travail) activés* pour ces fonctionnalités DLP pour tous les utilisateurs au sein du client. Pour plus d’informations sur l’utilisation des stratégies DLP, voir [Vue d’ensemble de la protection contre la perte de données.](/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs inclus et les utilisateurs exclus dans le Centre de conformité de sécurité, sous Emplacements de &amp; protection contre la perte **de**  >  **données.**

## <a name="communication-data-loss-prevention-for-teams"></a>Protection contre la perte de données de communication Teams

Avec la DLP de communication pour Teams, les organisations peuvent bloquer les conversations et les messages de canal qui contiennent des informations sensibles, telles que des informations financières, des informations d’identification personnelle, des informations relatives à la santé ou d’autres informations confidentielles.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs sous licence de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security + Compliance et Microsoft 365 E5/A5/G5 Information Protection and Governance peuvent bénéficier de la communication DLP pour Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs bénéficient de la recherche d’informations sensibles dans leurs messages de conversation et de canal sortants, tel que configuré dans la stratégie DLP de l’organisation.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, Teams messages de conversation et de canal sont un emplacement (charge de *travail)* activé pour ces fonctionnalités DLP pour tous les utilisateurs au sein du client. Pour plus d’informations sur l’utilisation des stratégies DLP, voir [Vue d’ensemble de la protection contre la perte de données.](/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs inclus et les utilisateurs exclus dans le Centre de conformité de sécurité, sous Emplacements de &amp; protection contre la perte **de**  >  **données.**

## <a name="information-barriers"></a>Obstacles aux informations

Le cloisonnement de l’information est la définition de stratégies qu’un administrateur peut configurer pour empêcher des individus ou des groupes de communiquer entre eux. Cela est utile si, par exemple, un service gère des informations qui ne doivent pas être partagées avec d’autres services, ou si un groupe doit être empêché de communiquer avec des contacts externes. Les stratégies de obstacle à l’information empêchent également les recherche et la découverte. Cela signifie que si vous tentez de communiquer avec une personne avec qui vous ne devez pas communiquer, vous ne trouverez pas cet utilisateur dans le s picker de personnes.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs bénéficient des fonctionnalités avancées de conformité des obstacles aux informations lorsqu’ils ne peuvent pas communiquer avec d’autres personnes. Des stratégies de obstacles à l’information peuvent être définies pour empêcher certains segments d’utilisateurs de communiquer avec chacun d’eux ou permettre à des segments spécifiques de communiquer uniquement avec certains autres segments. Pour plus d’informations sur la définition des stratégies d’obstacle aux informations, voir [Définir des stratégies de obstacle à l’information.](/microsoft-365/compliance/information-barriers-policies) Pour les scénarios dans lesquels deux groupes ne peuvent pas communiquer entre eux, les utilisateurs des deux groupes ont besoin d’une licence pour bénéficier du service (voir l’exemple ci-dessous).<br><br>

| Scénario | Qui nécessite une licence ? |
|:------|:------|
| Deux groupes (Groupe 1 et Groupe 2) ne peuvent pas communiquer entre eux (autrement dit, les utilisateurs du groupe 1 ne peuvent pas communiquer avec les utilisateurs du groupe 2, et les utilisateurs du groupe 2 ne peuvent pas communiquer avec les utilisateurs du groupe &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1. | Utilisateurs du groupe &nbsp; 1 et du &nbsp; groupe 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5, la gestion des risques internes Microsoft 365 E5/A5/G5 et Office 365 E5/A5/G5, fournissent les droits d’un utilisateur pour tirer parti des obstacles à l’information.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs créent et gèrent des stratégies d’obstacle aux informations à l’aide des cmdlets PowerShell dans le Centre de &amp; conformité de la sécurité. Les administrateurs doivent se voir attribuer Microsoft 365 Entreprise administrateur général, administrateur Office 365 administrateur général ou administrateur de conformité pour créer une stratégie d’obstacle aux informations. Par défaut, ces stratégies s’appliquent à tous les utilisateurs du client. Pour plus d’informations sur les obstacles à l’information, consultez [la](/MicrosoftTeams/information-barriers-in-teams)Microsoft Teams .

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs peuvent personnaliser les emplacements (charges de travail), les utilisateurs inclus et les utilisateurs exclus dans le Centre de conformité &amp; de sécurité. Par exemple, si tous les utilisateurs sont titulaires d’une licence Office 365 E3 et qu’aucun utilisateur n’est titulaire d’une licence Conformité avancée Office 365/E5, ils n’ont pas besoin de créer de stratégies d’obstacle à l’information pour l’organisation. Si vous souhaitez en savoir plus, veuillez consulter la rubrique [Information barriers in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams) (Cloisonnements de l’information dans Microsoft Teams).

## <a name="office-365-message-encryption"></a>Chiffrement de messages Office 365

Le chiffrement des messages Office 365 (OME) est un service basé sur Azure Rights Management (Azure RMS) qui vous permet d’envoyer des messages chiffrés à des personnes internes ou externes à votre organisation, quelle que soit l’adresse de messagerie de destination (Gmail, Yahoo! Mail, Outlook.com, etc.).

Pour afficher les messages chiffrés, les destinataires peuvent obtenir un code secret à usage unique, se connecter à l’aide d’un compte Microsoft ou se connecter à l’aide d’un compte professionnel ou scolaire associé à Office 365. Les destinataires peuvent également envoyer des réponses chiffrées. Ils n’ont pas besoin d’un abonnement pour afficher les messages chiffrés ou envoyer des réponses chiffrées.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs de messages bénéficient du contrôle supplémentaire sur les e-mails sensibles fournis par chiffrement de messages Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 et Azure Information Protection Plan 1 fournissent les droits dont un utilisateur peut bénéficier chiffrement de messages Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs créent et gèrent des stratégies chiffrement de messages Office 365 dans le centre d Exchange’administration sous **Règles de flux de**  >  **messagerie.** Par défaut, ces règles s’appliquent à tous les utilisateurs du client. Pour plus d’informations sur la configuration de chiffrement de messages Office 365 nouvelles fonctionnalités de chiffrement de messages, voir Configurer les nouvelles [fonctionnalités de chiffrement de messages.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs doivent appliquer des règles de flux de messagerie chiffrement de messages Office 365 uniquement aux utilisateurs titulaires d’une licence. Pour plus d’informations sur la définition des règles de flux de messagerie, voir Définir des règles de flux de messagerie [pour chiffrer les messages électroniques.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Chiffrement avancé de messages Office 365

Chiffrement avancé de messages Office 365 permet aux clients de respecter les obligations de conformité qui nécessitent des contrôles plus flexibles sur les destinataires externes et leur accès aux e-mails chiffrés. Avec le chiffrement de messages avancé, les administrateurs peuvent contrôler les e-mails sensibles partagés en dehors de l’organisation à l’aide de stratégies automatiques qui peuvent détecter des types d’informations sensibles (par exemple, des informations d’identification personnelle ou des ID financiers ou d’état), ou ils peuvent utiliser des mots clés pour améliorer la protection en appliquant des modèles de courrier personnalisés et en arrivant à expiration de l’accès aux messages électroniques chiffrés via un portail web sécurisé. En outre, les administrateurs peuvent contrôler davantage les e-mails chiffrés accessibles en externe via un portail web sécurisé en révoquer l’accès à tout moment.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les expéditeurs de messages bénéficient du contrôle supplémentaire sur les e-mails sensibles fourni par le chiffrement de messages avancé.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance et Microsoft 365 E5/A5/G5 Information Protection and Governance fournissent aux utilisateurs le droit de bénéficier du chiffrement de messages avancé.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs créent et gèrent des stratégies de chiffrement de messages avancés dans Exchange centre d’administration sous **Règles de flux de**  >  **messagerie.** Par défaut, ces règles s’appliquent à tous les utilisateurs du client. Pour plus d’informations sur la configuration des nouvelles fonctionnalités de chiffrement de messages, voir [Configurer de chiffrement de messages Office 365 nouvelles fonctionnalités.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs doivent appliquer des règles de flux de messagerie pour le chiffrement de messages avancé uniquement aux utilisateurs titulaires d’une licence. Pour plus d’informations sur la définition des règles de flux de messagerie, voir Définir des règles de flux de messagerie pour chiffrer les [messages électroniques Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Conformité des communications

La conformité des communications Microsoft 365 réduire les risques de communication en vous aidant à détecter, capturer et prendre des mesures correctives pour les messages inappropriés dans votre organisation. Vous pouvez définir des stratégies spécifiques qui capturent les messages électroniques internes et externes, les Microsoft Teams ou les communications tierces dans votre organisation. Les réviseurs peuvent prendre les mesures correctives appropriées pour s’assurer qu’ils sont conformes aux normes de message de votre organisation.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les spécialistes de la conformité bénéficient du service en faisant surveiller les communications de l’organisation par les stratégies de conformité des communications.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5 et la gestion des risques internes Microsoft 365 E5/A5/G5 fournissent les droits d’un utilisateur pour bénéficier de la conformité des communications.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les administrateurs et les spécialistes de la conformité créent des stratégies de conformité des communications dans Centre de conformité Microsoft 365. Ces stratégies définissent les communications et les utilisateurs qui sont soumis à révision dans l’organisation, définissent des conditions personnalisées que les communications doivent respecter et spécifient qui doit effectuer les révisions.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Les administrateurs choisissent des utilisateurs ou des groupes spécifiques à inclure dans une stratégie de conformité des communications. Lors du choix d’un groupe, ils peuvent également sélectionner des utilisateurs spécifiques du groupe à exclure de la stratégie de conformité des communications. Pour plus d’informations sur les stratégies de conformité des communications, voir La mise en place de la conformité des [communications dans Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Gestion des risques internes

La gestion des risques internes est une solution dans Microsoft 365 qui vous permet de minimiser les risques internes en vous permettant de détecter, d’examiner et d’agir sur les activités à risque dans votre organisation.

Les stratégies personnalisées vous permettent de détecter et d’agir sur les activités malveillantes et par inadvertance risquées dans votre organisation, y compris la escalade de cas vers Microsoft Advanced eDiscovery, si nécessaire. Les analystes de risque de votre organisation peuvent rapidement prendre les mesures appropriées pour s’assurer que les utilisateurs sont conformes aux normes de conformité de votre organisation.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs peuvent tirer parti du fait que leurs activités sont surveillées pour les risques.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quelles licences fournissent les droits d’un utilisateur pour bénéficier du service ?

Microsoft 365 E5/A5/G5, la conformité Microsoft 365 E5/A5/G5 et la gestion des risques internes Microsoft 365 E5/A5/G5 permettent à un utilisateur de bénéficier de la gestion des risques internes.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Les stratégies de gestion des risques internes doivent être créées dans le Centre de conformité Microsoft 365 et affectées aux utilisateurs.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Lorsque vous créez une stratégie dans le Centre de conformité Microsoft 365, dans  la **page** Choisir des utilisateurs et des groupes, sélectionnez Choisir des utilisateurs ou des groupes pour sélectionner uniquement les utilisateurs sous licence, ou, si tous vos utilisateurs sont titulaires d’une licence, vous pouvez activer la case à cocher Tous les utilisateurs et groupes à messagerie.  Pour plus d’informations, voir [Prise en charge de la gestion des risques internes.](/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Stratégies d’accès conditionnel

L’accès conditionnel est un outil utilisé par Azure Virtual Directory pour regrouper des signaux, prendre des décisions et appliquer des stratégies d’organisation. L’accès conditionnel est au cœur du contrôle piloté par l’identité. Les stratégies d’accès conditionnel, à leur niveau le plus simple, sont des instructions if-then. Si un utilisateur souhaite accéder à une ressource, il doit effectuer une action. Exemple : un responsable de paie souhaite accéder à l’application de paie et doit effectuer une authentification multifacteur pour y accéder.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs titulaires d’une licence Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium et Azure Active Directory Premium Plan 1 peuvent bénéficier des stratégies d’accès conditionnel. Les utilisateurs sous licence de Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security et Azure Active Directory Premium Plan 2 peuvent bénéficier de la Protection des identités (stratégies d’accès conditionnel basées sur les risques).

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les analystes des opérations de sécurité et les professionnels de la sécurité bénéficient de la possibilité d’appliquer des stratégies organisationnelles sur les utilisateurs, en exigeant qu’ils répondent à certains critères avant d’accorder l’accès au contenu d’entreprise. Les utilisateurs finaux bénéficient de la possibilité d’accéder à leur travail où qu’ils choisissent, tout en protégeant les biens de l’organisation.

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, les fonctionnalités d’accès conditionnel sont activées au niveau du client pour tous les utilisateurs au sein du client.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

Pour la protection des identités et l’accès conditionnel spécifiquement, un utilisateur doit être inclus dans un groupe ou ajouté à une stratégie d’accès conditionnel. La condition utilisateurs et groupes est obligatoire dans une stratégie d’accès conditionnel. Dans votre stratégie, vous pouvez sélectionner tous **les** utilisateurs ou des utilisateurs et groupes spécifiques. Vous devez sélectionner uniquement les utilisateurs et groupes sous licence appropriés. Pour plus d’informations, voir [Accès conditionnel : Conditions](/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Audit avancé

L’audit avancé dans Microsoft 365 permet de conserver pendant un an les journaux d’audit pour les activités des utilisateurs et des administrateurs et offre la possibilité de créer des stratégies de rétention de journal d’audit personnalisées pour gérer la rétention des journaux d’audit pour d’autres services Microsoft 365. Il fournit également l’accès à des événements essentiels pour les enquêtes et un accès à bande passante élevée à l Office 365 API Activité de gestion. Pour plus d’informations, [voir Audit avancé dans Microsoft 365](/microsoft-365/compliance/advanced-audit).

Vous pouvez également activer une période de rétention de 10 ans avec une référence (SKU) de modules. La référence (SKU) du module de module module est requise à partir du début de l’année 2021.

### <a name="which-users-benefit-from-the-service"></a>Quels utilisateurs bénéficient du service ?

Les utilisateurs sous licence de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security + Compliance et Microsoft 365 E5/A5/A5 eDiscovery and Audit peuvent bénéficier de l’audit avancé.

Les utilisateurs titulaires d’une licence Avec audit avancé et le module de rétention du journal d’audit de 10 ans peuvent bénéficier de la rétention du journal d’audit pendant 10 ans.

### <a name="how-do-users-benefit-from-the-service"></a>Comment les utilisateurs bénéficient-ils du service ?

Les utilisateurs profitent de l’audit avancé, car les enregistrements d’audit liés à l’activité des utilisateurs dans Microsoft 365 services peuvent être conservés pendant un an. En outre, les événements d’audit à valeur élevée sont enregistrés, par exemple lorsque des éléments de la boîte aux lettres d’un utilisateur sont accessibles ou lus. Pour plus d’informations, [voir Audit avancé dans Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Comment le service est-il mis en service/déployé ?

Par défaut, l’audit avancé est activé au niveau du client pour toutes les organisations qui disposent d’un abonnement Office 365 ou Microsoft 365 E5/A5/G5, et fournit automatiquement une rétention d’un an des journaux d’audit pour les activités (effectuées par les utilisateurs avec la licence appropriée) dans Azure Active Directory, Exchange et SharePoint. En outre, les organisations peuvent utiliser des stratégies de rétention du journal d’audit pour gérer la période de rétention des enregistrements d’audit générés par l’activité dans d’Microsoft 365 services. La fonctionnalité rétention du journal d’audit de 10 ans est également activée à l’aide des mêmes stratégies de rétention. Pour plus d’informations, voir [gérer les stratégies de rétention du journal d’audit](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Comment le service peut-il être appliqué uniquement aux utilisateurs du client qui sont titulaires d’une licence pour le service ?

La rétention d’un an des journaux d’audit et l’audit des événements essentiels s’appliquent uniquement aux utilisateurs titulaires de la licence appropriée. En outre, les administrateurs peuvent utiliser des stratégies de rétention du journal d’audit pour spécifier des durées de rétention plus courtes pour les journaux d’audit d’utilisateurs spécifiques.

La rétention de 10 ans des journaux d’audit s’applique uniquement aux utilisateurs titulaires de la licence de modules add-on appropriée. La référence (SKU) du module de module module est requise à partir du début de l’année 2021.
