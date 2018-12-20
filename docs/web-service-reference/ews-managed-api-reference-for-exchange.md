---
title: Referencia de la API administrada de Servicios Web de Exchange (EWS)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: c6ca36f4-a67c-4e3c-aae7-9ead7b704e15
description: Obtenga información sobre los espacios de nombres que se incluyen en la API administrada de EWS.
ms.openlocfilehash: 78797ba5124cb47da5430491d3be23bbaf0371a7
ms.sourcegitcommit: 25cbbc6707e4ec0621c5c46baf7fe49be42d3297
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/07/2018
ms.locfileid: "25440986"
---
# <a name="ews-managed-api-reference"></a><span data-ttu-id="5a5b5-103">Referencia de la API administrada de EWS</span><span class="sxs-lookup"><span data-stu-id="5a5b5-103">EWS Managed API reference</span></span>

<span data-ttu-id="5a5b5-104">**Se aplica a**: API administrada de EWS | Exchange Online | Exchange Server 2007 | Exchange Server 2010 | Exchange Server 2013 | Office 365</span><span class="sxs-lookup"><span data-stu-id="5a5b5-104">**Applies to**: EWS Managed API | Exchange Online | Exchange Server 2007 | Exchange Server 2010 | Exchange Server 2013 | Office 365</span></span>

<span data-ttu-id="5a5b5-105">La API administrada de Servicios Web de Exchange (EWS) incluye dos API: Microsoft.Exchange.WebServices.dll y Microsoft.Exchange.WebServices.Auth.dll.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-105">The Exchange Web Services (EWS) Managed API includes two APIs: Microsoft.Exchange.WebServices.dll and Microsoft.Exchange.WebServices.Auth.dll.</span></span>

## <a name="ews-managed-api-namespaces"></a><span data-ttu-id="5a5b5-106">Los espacios de nombres de la API administrada de EWS</span><span class="sxs-lookup"><span data-stu-id="5a5b5-106">EWS Managed API</span></span>

|<span data-ttu-id="5a5b5-107">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="5a5b5-107">Namespace</span></span> |<span data-ttu-id="5a5b5-108">Descripción</span><span class="sxs-lookup"><span data-stu-id="5a5b5-108">Description</span></span> |
|:---------|:-----------|
|[<span data-ttu-id="5a5b5-109">Microsoft.Exchange.WebServices.Auth.Validation</span><span class="sxs-lookup"><span data-stu-id="5a5b5-109">Microsoft.Exchange.WebServices.Auth.Validation</span></span>](https://docs.microsoft.com/dotnet/api/microsoft.exchange.webservices.auth.validation?view=exchange-ews-api) |<span data-ttu-id="5a5b5-110">Contiene los tipos y los métodos que se usan para validar los token de identidad de usuario enviados desde un servidor de Exchange.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-110">Contains types and methods that are used to validate user identity tokens sent from an Exchange server.</span></span> <span data-ttu-id="5a5b5-111">El espacio de nombre Microsoft.Exchange.WebServices.Auth.Validation es aplicable a los clientes que tienen Exchange Online y versiones de Exchange a partir de Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-111">The Microsoft.Exchange.WebServices.Auth.Validation namespace is applicable to clients that target Exchange Online and versions of Exchange starting with Exchange Server 2013.</span></span> <span data-ttu-id="5a5b5-112">Este espacio de nombre se incluye en la API de Microsoft.Exchange.WebServices.Auth.dll.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-112">This namespace is included in the Microsoft.Exchange.WebServices.Auth.dll API.</span></span>|
|[<span data-ttu-id="5a5b5-113">Microsoft.Exchange.WebServices.Autodiscover</span><span class="sxs-lookup"><span data-stu-id="5a5b5-113">Microsoft.Exchange.WebServices.Autodiscover</span></span>](https://docs.microsoft.com/dotnet/api/microsoft.exchange.webservices.autodiscover?view=exchange-ews-api)|<span data-ttu-id="5a5b5-114">Contiene tipos que se usan para comunicarse con el servicio de detección automática hospedado por un servidor de Exchange.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-114">Contains types that are used to communicate with the Autodiscover service that is hosted by an Exchange Server.</span></span> <span data-ttu-id="5a5b5-115">Este espacio de nombres también se usa para buscar objetos de punto de conexión de servicio en servicios de dominio de Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="5a5b5-115">This namespace is also used to look up service connection point objects in Active Directory Doman Services (AD DS).</span></span> <span data-ttu-id="5a5b5-116">Los servicios de detección automática proporcionan información de configuración a los clientes EWS.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-116">The Autodiscover services provide configuration information to EWS clients.</span></span> <span data-ttu-id="5a5b5-117">Esto permite a los clientes dirigirse a la dirección URL del servicio correspondiente.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-117">This enables the clients to target the appropriate service URL.</span></span><br/><br/><span data-ttu-id="5a5b5-118">La funcionalidad del espacio de nombres puede usarse para dirigir el servicio de detección automática de POX introducido en Microsoft Exchange Server 2007, la búsqueda de objeto de punto de conexión de servicio si el cliente está unido al dominio o el punto de conexión de detección automática de SOAP se introdujo en Exchange Server 2010.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-118">The namespace functionality can be used to target the POX Autodiscover service introduced in Microsoft Exchange Server 2007, the service connection point object lookup if the client is domain joined, or the SOAP Autodiscover endpoint introduced in Exchange Server 2010.</span></span> <span data-ttu-id="5a5b5-119">El tipo de este espacio de nombres principal es la [clase AutodiscoverService](https://docs.microsoft.com/dotnet/api/microsoft.exchange.webservices.autodiscover.autodiscoverservice?view=exchange-ews-api).</span><span class="sxs-lookup"><span data-stu-id="5a5b5-119">The main type in this namespace is the [AutodiscoverService class](https://docs.microsoft.com/dotnet/api/microsoft.exchange.webservices.autodiscover.autodiscoverservice?view=exchange-ews-api).</span></span> <span data-ttu-id="5a5b5-120">Este espacio de nombre se incluye en la API de Microsoft.Exchange.WebServices.dll.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-120">This namespace is included in the Microsoft.Exchange.WebServices.dll API.</span></span>|
|[<span data-ttu-id="5a5b5-121">Microsoft.Exchange.WebServices.Data</span><span class="sxs-lookup"><span data-stu-id="5a5b5-121">Microsoft.Exchange.WebServices.Data</span></span>](https://docs.microsoft.com/dotnet/api/microsoft.exchange.webservices.data?view=exchange-ews-api)| <span data-ttu-id="5a5b5-122">Contiene tipos que se usan para comunicarse con un servidor de Exchange mediante EWS.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-122">Contains types that are used to communicate with an Exchange server by means of EWS.</span></span> <span data-ttu-id="5a5b5-123">Este espacio de nombres proporciona la funcionalidad de la API administrada de EWS principal.</span><span class="sxs-lookup"><span data-stu-id="5a5b5-123">This namespace provides the core EWS Managed API functionality.</span></span> <span data-ttu-id="5a5b5-124">El tipo de este espacio de nombres principal es la [clase ExchangeService](https://docs.microsoft.com/dotnet/api/microsoft.exchange.webservices.data.exchangeservice?view=exchange-ews-api).</span><span class="sxs-lookup"><span data-stu-id="5a5b5-124">The main type in this namespace is the [ExchangeService class](https://docs.microsoft.com/dotnet/api/microsoft.exchange.webservices.data.exchangeservice?view=exchange-ews-api).</span></span>|

## <a name="see-also"></a><span data-ttu-id="5a5b5-125">Vea también</span><span class="sxs-lookup"><span data-stu-id="5a5b5-125">See also</span></span>

- [<span data-ttu-id="5a5b5-126">Referencia de servicios web para Exchange</span><span class="sxs-lookup"><span data-stu-id="5a5b5-126">Web services reference for Exchange</span></span>](web-services-reference-for-exchange.md)
- [<span data-ttu-id="5a5b5-127">Explorar la API administrada de EWS, EWS y servicios web de Exchange</span><span class="sxs-lookup"><span data-stu-id="5a5b5-127">Explore the EWS Managed API, EWS, and web services in Exchange</span></span>](../exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange.md)
- [<span data-ttu-id="5a5b5-128">Novedades de EWS y otros servicios web de Exchange</span><span class="sxs-lookup"><span data-stu-id="5a5b5-128">What’s new in EWS and other web services in Exchange</span></span>](../exchange-web-services/whats-new-in-ews-and-other-web-services-in-exchange.md)
- [<span data-ttu-id="5a5b5-129">Empezar a usar los servicios web de Exchange</span><span class="sxs-lookup"><span data-stu-id="5a5b5-129">Start using web services in Exchange</span></span>](../exchange-web-services/start-using-web-services-in-exchange.md)
- [<span data-ttu-id="5a5b5-130">Desarrollo de clientes de servicios web de Exchange</span><span class="sxs-lookup"><span data-stu-id="5a5b5-130">Develop web service clients for Exchange</span></span>](../exchange-web-services/develop-web-service-clients-for-exchange.md)
