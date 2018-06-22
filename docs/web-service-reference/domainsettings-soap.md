---
title: DomainSettings (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: f3d37f5a-c9ea-4ed9-a011-94d33bda64d1
description: El elemento DomainSettings representa la configuración de dominio que se ha enviado en una solicitud de detección automática o devueltas por una respuesta de detección automática.
ms.openlocfilehash: 961051399dc8babd8cba6eeaf43456071d0f40a6
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764282"
---
# <a name="domainsettings-soap"></a><span data-ttu-id="545ac-103">DomainSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="545ac-103">DomainSettings (SOAP)</span></span>

<span data-ttu-id="545ac-104">El elemento **DomainSettings** representa la configuración de dominio que se ha enviado en una solicitud de detección automática o devueltas por una respuesta de detección automática.</span><span class="sxs-lookup"><span data-stu-id="545ac-104">The **DomainSettings** element represents the domain settings that were submitted in an Autodiscover request or returned by an Autodiscover response.</span></span> 
  
```XML
<DomainSettings>
   <DomainSetting/>
</DomainSettings>
```

 <span data-ttu-id="545ac-105">**DomainSettings**</span><span class="sxs-lookup"><span data-stu-id="545ac-105">**DomainSettings**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="545ac-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="545ac-106">Attributes and elements</span></span>

<span data-ttu-id="545ac-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="545ac-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="545ac-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="545ac-108">Attributes</span></span>

<span data-ttu-id="545ac-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="545ac-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="545ac-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="545ac-110">Child elements</span></span>

|<span data-ttu-id="545ac-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="545ac-111">**Element**</span></span>|<span data-ttu-id="545ac-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="545ac-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="545ac-113">DomainSetting (SOAP)</span><span class="sxs-lookup"><span data-stu-id="545ac-113">DomainSetting (SOAP)</span></span>](domainsetting-soap.md) <br/> |<span data-ttu-id="545ac-114">Contiene la configuración de dominio que es devueltos por una solicitud de [operación GetDomainSettings (SOAP)](getdomainsettings-operation-soap.md) .</span><span class="sxs-lookup"><span data-stu-id="545ac-114">Contains domain settings that are returned by a [GetDomainSettings operation (SOAP)](getdomainsettings-operation-soap.md) request.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="545ac-115">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="545ac-115">Parent elements</span></span>

|<span data-ttu-id="545ac-116">**Element**</span><span class="sxs-lookup"><span data-stu-id="545ac-116">**Element**</span></span>|<span data-ttu-id="545ac-117">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="545ac-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="545ac-118">DomainResponse (SOAP)</span><span class="sxs-lookup"><span data-stu-id="545ac-118">DomainResponse (SOAP)</span></span>](domainresponse-soap.md) <br/> |<span data-ttu-id="545ac-119">Contiene la configuración solicitada para el dominio especificado.</span><span class="sxs-lookup"><span data-stu-id="545ac-119">Contains the requested settings for the specified domain.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="545ac-120">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="545ac-120">Text value</span></span>

<span data-ttu-id="545ac-121">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="545ac-121">None.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="545ac-122">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="545ac-122">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="545ac-123">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="545ac-123">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="545ac-124">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="545ac-124">Schema Name</span></span>  <br/> |<span data-ttu-id="545ac-125">Esquema de detección automática</span><span class="sxs-lookup"><span data-stu-id="545ac-125">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="545ac-126">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="545ac-126">Validation File</span></span>  <br/> |<span data-ttu-id="545ac-127">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="545ac-127">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="545ac-128">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="545ac-128">Can be Empty</span></span>  <br/> |<span data-ttu-id="545ac-129">Verdadero</span><span class="sxs-lookup"><span data-stu-id="545ac-129">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="545ac-130">Ver también</span><span class="sxs-lookup"><span data-stu-id="545ac-130">See also</span></span>

- [<span data-ttu-id="545ac-131">Operación GetDomainSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="545ac-131">GetDomainSettings operation (SOAP)</span></span>](getdomainsettings-operation-soap.md)
