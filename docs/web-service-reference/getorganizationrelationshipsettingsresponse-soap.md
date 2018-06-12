---
title: GetOrganizationRelationshipSettingsResponse (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
ms.assetid: 2f43b817-92c2-4e04-8095-479d790f768c
description: El elemento GetOrganizationRelationshipSettingsResponse contiene la respuesta de la operación (SOAP) GetOrganizationRelationshipSettings. El elemento GetOrganizationRelationshipSettingsResponse es sólo para uso interno. Este elemento no se usa en los clientes.
ms.openlocfilehash: 907113df2186a93345c6e0bc7dd470909508bd38
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764924"
---
# <a name="getorganizationrelationshipsettingsresponse-soap"></a><span data-ttu-id="d3625-105">GetOrganizationRelationshipSettingsResponse (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d3625-105">GetOrganizationRelationshipSettingsResponse (SOAP)</span></span>

<span data-ttu-id="d3625-106">El elemento **GetOrganizationRelationshipSettingsResponse** contiene la respuesta de la [operación de GetOrganizationRelationshipSettings (SOAP)](getorganizationrelationshipsettings-operation-soap.md) .</span><span class="sxs-lookup"><span data-stu-id="d3625-106">The **GetOrganizationRelationshipSettingsResponse** element contains the [GetOrganizationRelationshipSettings operation (SOAP)](getorganizationrelationshipsettings-operation-soap.md) response.</span></span> <span data-ttu-id="d3625-107">El elemento **GetOrganizationRelationshipSettingsResponse** es sólo para uso interno.</span><span class="sxs-lookup"><span data-stu-id="d3625-107">The **GetOrganizationRelationshipSettingsResponse** element is for internal use only.</span></span> <span data-ttu-id="d3625-108">Este elemento no se usa en los clientes.</span><span class="sxs-lookup"><span data-stu-id="d3625-108">This element is not used by clients.</span></span> 
  
```XML
<GetOrganizationRelationshipSettingResponse>
   <ErrorCode/>
   <ErrorMessage/>
   <OrganizationRelationshipSettingsCollection/>
</GetOrganizationRelationshipSettingResponse>
```

 <span data-ttu-id="d3625-109">**GetOrganizationRelationshipSettingsResponse**</span><span class="sxs-lookup"><span data-stu-id="d3625-109">**GetOrganizationRelationshipSettingsResponse**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="d3625-110">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="d3625-110">Attributes and elements</span></span>

<span data-ttu-id="d3625-111">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="d3625-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="d3625-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="d3625-112">Attributes</span></span>

<span data-ttu-id="d3625-113">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="d3625-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="d3625-114">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="d3625-114">Child elements</span></span>

|<span data-ttu-id="d3625-115">**Element**</span><span class="sxs-lookup"><span data-stu-id="d3625-115">**Element**</span></span>|<span data-ttu-id="d3625-116">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="d3625-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d3625-117">ErrorCode (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d3625-117">ErrorCode (SOAP)</span></span>](errorcode-soap.md) <br/> |<span data-ttu-id="d3625-118">Representa un código de error devuelto por el servicio Detección automática.</span><span class="sxs-lookup"><span data-stu-id="d3625-118">Represents an error code that is returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="d3625-119">ErrorMessage (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d3625-119">ErrorMessage (SOAP)</span></span>](errormessage-soap.md) <br/> |<span data-ttu-id="d3625-120">Representa un mensaje en el que está asociado con un código de error devuelto por el servicio Detección automática.</span><span class="sxs-lookup"><span data-stu-id="d3625-120">Represents a message that is associated with an error code that is returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="d3625-121">OrganizationRelationshipSettingsCollection (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d3625-121">OrganizationRelationshipSettingsCollection (SOAP)</span></span>](organizationrelationshipsettingscollection-soap.md) <br/> |<span data-ttu-id="d3625-122">Representa una colección de relaciones de organización que coinciden con la consulta.</span><span class="sxs-lookup"><span data-stu-id="d3625-122">Represents a collection of organization relationships that match the query.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="d3625-123">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="d3625-123">Parent elements</span></span>

<span data-ttu-id="d3625-124">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="d3625-124">None.</span></span>
  
## <a name="text-value"></a><span data-ttu-id="d3625-125">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="d3625-125">Text value</span></span>

<span data-ttu-id="d3625-126">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="d3625-126">None.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="d3625-127">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="d3625-127">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d3625-128">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="d3625-128">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="d3625-129">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="d3625-129">Schema Name</span></span>  <br/> |<span data-ttu-id="d3625-130">Esquema de detección automática</span><span class="sxs-lookup"><span data-stu-id="d3625-130">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="d3625-131">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="d3625-131">Validation File</span></span>  <br/> |<span data-ttu-id="d3625-132">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="d3625-132">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="d3625-133">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="d3625-133">Can be Empty</span></span>  <br/> |<span data-ttu-id="d3625-134">Verdadero</span><span class="sxs-lookup"><span data-stu-id="d3625-134">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="d3625-135">Ver también</span><span class="sxs-lookup"><span data-stu-id="d3625-135">See also</span></span>



[<span data-ttu-id="d3625-136">Operación GetOrganizationRelationshipSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d3625-136">GetOrganizationRelationshipSettings operation (SOAP)</span></span>](getorganizationrelationshipsettings-operation-soap.md)
