---
title: Respuesta (GetOrganizationRelationship) (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
ms.assetid: e6bbe800-3cbc-48b2-87b3-2043f575e88b
description: El elemento de respuesta contiene la información de respuesta GetOrganizationRelationshipSettings operación (SOAP). El elemento de respuesta es sólo para uso interno. Este elemento no se usa en los clientes.
ms.openlocfilehash: 97bef9ab9f0b860e62646703c35d539b7922a65a
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837174"
---
# <a name="response-getorganizationrelationship-soap"></a><span data-ttu-id="71021-105">Respuesta (GetOrganizationRelationship) (SOAP)</span><span class="sxs-lookup"><span data-stu-id="71021-105">Response (GetOrganizationRelationship) (SOAP)</span></span>

<span data-ttu-id="71021-106">El elemento de **respuesta** contiene la información de respuesta de la [operación de GetOrganizationRelationshipSettings (SOAP)](getorganizationrelationshipsettings-operation-soap.md) .</span><span class="sxs-lookup"><span data-stu-id="71021-106">The **Response** element contains the [GetOrganizationRelationshipSettings operation (SOAP)](getorganizationrelationshipsettings-operation-soap.md) response information.</span></span> <span data-ttu-id="71021-107">El elemento de **respuesta** es sólo para uso interno.</span><span class="sxs-lookup"><span data-stu-id="71021-107">The **Response** element is for internal use only.</span></span> <span data-ttu-id="71021-108">Este elemento no se usa en los clientes.</span><span class="sxs-lookup"><span data-stu-id="71021-108">This element is not used by clients.</span></span> 
  
```XML
<GetOrganizationRelationshipSettingsResponse>
   <ErrorCode/>
   <ErrorMessage/>
   <OrganizationRelationshipSettingsCollection/>
</GetOrganizationRelationshipSettingResponse>
```

 <span data-ttu-id="71021-109">**GetOrganizationRelationshipSettingsResponse**</span><span class="sxs-lookup"><span data-stu-id="71021-109">**GetOrganizationRelationshipSettingsResponse**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="71021-110">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="71021-110">Attributes and elements</span></span>

<span data-ttu-id="71021-111">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="71021-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="71021-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="71021-112">Attributes</span></span>

<span data-ttu-id="71021-113">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="71021-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="71021-114">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="71021-114">Child elements</span></span>

|<span data-ttu-id="71021-115">**Element**</span><span class="sxs-lookup"><span data-stu-id="71021-115">**Element**</span></span>|<span data-ttu-id="71021-116">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="71021-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="71021-117">ErrorCode (SOAP)</span><span class="sxs-lookup"><span data-stu-id="71021-117">ErrorCode (SOAP)</span></span>](errorcode-soap.md) <br/> |<span data-ttu-id="71021-118">Representa un código de error devuelto por el servicio Detección automática.</span><span class="sxs-lookup"><span data-stu-id="71021-118">Represents an error code that is returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="71021-119">ErrorMessage (SOAP)</span><span class="sxs-lookup"><span data-stu-id="71021-119">ErrorMessage (SOAP)</span></span>](errormessage-soap.md) <br/> |<span data-ttu-id="71021-120">Representa un mensaje en el que está asociado con un código de error devuelto por el servicio Detección automática.</span><span class="sxs-lookup"><span data-stu-id="71021-120">Represents a message that is associated with an error code that is returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="71021-121">OrganizationRelationshipSettingsCollection (SOAP)</span><span class="sxs-lookup"><span data-stu-id="71021-121">OrganizationRelationshipSettingsCollection (SOAP)</span></span>](organizationrelationshipsettingscollection-soap.md) <br/> |<span data-ttu-id="71021-122">Representa una lista de relaciones de organización que coinciden con la consulta.</span><span class="sxs-lookup"><span data-stu-id="71021-122">Represents a list of organization relationships that match the query.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="71021-123">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="71021-123">Parent elements</span></span>

<span data-ttu-id="71021-124">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="71021-124">None.</span></span>
  
## <a name="text-value"></a><span data-ttu-id="71021-125">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="71021-125">Text value</span></span>

<span data-ttu-id="71021-126">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="71021-126">None.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="71021-127">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="71021-127">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="71021-128">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="71021-128">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="71021-129">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="71021-129">Schema Name</span></span>  <br/> |<span data-ttu-id="71021-130">Esquema de detección automática</span><span class="sxs-lookup"><span data-stu-id="71021-130">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="71021-131">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="71021-131">Validation File</span></span>  <br/> |<span data-ttu-id="71021-132">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="71021-132">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="71021-133">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="71021-133">Can be Empty</span></span>  <br/> |<span data-ttu-id="71021-134">Verdadero</span><span class="sxs-lookup"><span data-stu-id="71021-134">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="71021-135">Ver también</span><span class="sxs-lookup"><span data-stu-id="71021-135">See also</span></span>



[<span data-ttu-id="71021-136">Operación GetOrganizationRelationshipSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="71021-136">GetOrganizationRelationshipSettings operation (SOAP)</span></span>](getorganizationrelationshipsettings-operation-soap.md)
