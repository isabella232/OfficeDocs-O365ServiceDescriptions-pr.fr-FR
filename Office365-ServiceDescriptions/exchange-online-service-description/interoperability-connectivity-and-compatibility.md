---
title: Interopérabilité, connectivité et compatibilité
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 38ab8f7baf16c5bf837bca9310a0d34a5e25469f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776795"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="d8441-102">Interopérabilité, connectivité et compatibilité</span><span class="sxs-lookup"><span data-stu-id="d8441-102">Interoperability, Connectivity, and Compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="d8441-103">Interopérabilité avec d'autres produits Microsoft</span><span class="sxs-lookup"><span data-stu-id="d8441-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="d8441-104">Skype Entreprise Online</span><span class="sxs-lookup"><span data-stu-id="d8441-104">Skype for Business Online</span></span>

<span data-ttu-id="d8441-105">Pour les clients qui ont déployé Microsoft Lync Server 2010, Lync Server 2013 ou Microsoft Office Communications Server 2007 R2 local, Microsoft Office Communicator peut se connecter à Microsoft Exchange Online à l'aide des services web Exchange afin d'accéder aux messages de notification d'absence du bureau et aux données de calendrier.</span><span class="sxs-lookup"><span data-stu-id="d8441-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="d8441-106">Lync Server 2010 et Lync Server 2013 sur site peuvent interagir avec Exchange Online de deux façons supplémentaires :</span><span class="sxs-lookup"><span data-stu-id="d8441-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="d8441-107">Interopérabilité des informations de présence et de messagerie instantanée dans Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="d8441-107">IM and presence interoperability in Outlook Web App</span></span>
    
- <span data-ttu-id="d8441-108">Interopérabilité de la messagerie vocale</span><span class="sxs-lookup"><span data-stu-id="d8441-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="d8441-p101">Pour plus d'informations sur la configuration de Skype Entreprise Server 2015 avec Exchange Online, consultez la page [Configuration de l'intégration de Skype Entreprise Server 2015 sur site avec Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). Pour les configurations hybrides, consultez la page [Configurations hybrides Skype Entreprise Server 2015 prises en charge](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="d8441-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="d8441-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="d8441-111">Microsoft SharePoint</span></span>

<span data-ttu-id="d8441-112">Pour les clients qui ont déployé Microsoft SharePoint Server ou SharePoint Online dans le cadre d'un abonnement Office 365, SharePoint peut se connecter à Exchange Online afin d'accéder aux services intégrés.</span><span class="sxs-lookup"><span data-stu-id="d8441-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an Office 365 subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="d8441-113">Pour plus d'informations sur la connexion de SharePoint à Exchange Online, visitez la page [Utiliser SharePoint Online sur un domaine personnalisé avec d'autres services](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="d8441-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="d8441-114">Fonctionnalités pour la connectivité externe</span><span class="sxs-lookup"><span data-stu-id="d8441-114">Features for external connectivity</span></span>

<span data-ttu-id="d8441-115">Exchange Online offre les fonctionnalités suivantes permettant d'établir une connexion avec des applications et des appareils externes :</span><span class="sxs-lookup"><span data-stu-id="d8441-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="d8441-p102">**Via des protocoles de messagerie tels que SMTP, POP3, IMAP4 ou Services web Exchange** Les applications externes exécutées en local dans Azure ou dans d'autres services hébergés peuvent accéder aux données stockées avec Exchange Online à l'aide de protocoles de messagerie tels que MAPI sur HTTP, SMTP, POP3 et IMAPv4. Il est recommandé d'utiliser les services Web Exchange ou l'API gérée des services Web Exchange pour le développement d'applications.</span><span class="sxs-lookup"><span data-stu-id="d8441-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="d8441-118">**Comme un relais SMTP** Exchange Online peut être configuré comme un service de remise SMTP pour les e-mails envoyés à partir de passerelles de télécopie, d'appliances réseau et d'applications personnalisées.</span><span class="sxs-lookup"><span data-stu-id="d8441-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="d8441-119">Services Web Exchange</span><span class="sxs-lookup"><span data-stu-id="d8441-119">Exchange Web Services</span></span>

<span data-ttu-id="d8441-p103">Les services Web Exchange (EWS) constituent l'API de développement privilégiée pour Exchange Server et Exchange Online. Grâce à EWS ou à l'API gérée EWS, les administrateurs peuvent accéder aux données stockées avec Exchange Online à partir d'applications exécutées sur site dans Azure ou dans d'autres services hébergés. EWS permet aux administrateurs d'effectuer des actions spécialisées, par exemple interroger le contenu d'une boîte aux lettres, publier un événement de calendrier, créer une tâche ou déclencher une action spécifique en fonction du contenu d'un e-mail. Exchange Online active la fonctionnalité EWS en octroyant des autorisations d'application aux comptes clients. Ces autorisations permettent à l'application cliente d'accéder à la boîte aux lettres de l'application et d'ajouter du contenu. L'emprunt d'identité Exchange est une méthode utilisée pour accorder des autorisations d'application. Pour plus d'informations sur la façon d'utiliser les services Web Exchange avec Exchange Online, consultez les articles techniques du Centre pour développeurs Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d8441-p103">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online. Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services. EWS enables administrators to perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message. Exchange Online enables EWS functionality by granting application permissions to customer accounts. These permissions allow the customer application to access the application mailbox and add content. Exchange Impersonation is one method used to grant application permissions. For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="d8441-127">Relais SMTP</span><span class="sxs-lookup"><span data-stu-id="d8441-127">SMTP relay</span></span>

<span data-ttu-id="d8441-p104">Exchange Online peut être configuré comme un service de remise SMTP pour relayer les e-mails envoyés à partir de passerelles de télécopie, d'appliances réseau et d'applications personnalisées. Par exemple, si une application métier envoie des alertes par courrier électronique aux utilisateurs, elle peut être configurée pour utiliser Exchange Online comme système de remise du courrier. L'application ou le service doit s'identifier avec le nom d'utilisateur et mot de passe d'une boîte aux lettres Exchange Online sous licence valide, et se connecter à l'aide du protocole Transport Layer Security (TLS).</span><span class="sxs-lookup"><span data-stu-id="d8441-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="d8441-131">Disponibilité des fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="d8441-131">Feature Availability</span></span>

<span data-ttu-id="d8441-132">Pour afficher la disponibilité des fonctionnalités dans les plans Office 365, les options autonomes et les solutions locales, voir [Description du service Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="d8441-132">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

