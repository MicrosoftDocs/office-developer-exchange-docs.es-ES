---
title: EventCause (servicio web de mensajería unificada)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_name:
- EventCause
api_type:
- schema
ms.assetid: 7b3c1db8-cad4-4050-a50d-b06f065db530
description: El elemento EventCause contiene un valor que indica la causa de un evento de llamada en una respuesta a una solicitud de GetCallInfo operación (servicio web de mensajería unificada).
ms.openlocfilehash: dd73d93527bebb3b522ad0a6cdae5b9faee1a6a9
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764451"
---
# <a name="eventcause-um-web-service"></a><span data-ttu-id="ed6c1-103">EventCause (servicio web de mensajería unificada)</span><span class="sxs-lookup"><span data-stu-id="ed6c1-103">EventCause (UM web service)</span></span>

<span data-ttu-id="ed6c1-104">El elemento **EventCause** contiene un valor que indica la causa de un evento de llamada en una respuesta a una solicitud de [operación GetCallInfo (servicio web de mensajería unificada)](getcallinfo-operation-um-web-service.md) .</span><span class="sxs-lookup"><span data-stu-id="ed6c1-104">The **EventCause** element contains a value that indicates the cause for a call event in a response to a [GetCallInfo operation (UM web service)](getcallinfo-operation-um-web-service.md) request.</span></span> 
  
[<span data-ttu-id="ed6c1-105">GetCallInfoResponse (servicio web de mensajería unificada)</span><span class="sxs-lookup"><span data-stu-id="ed6c1-105">GetCallInfoResponse (UM web service)</span></span>](getcallinforesponse-um-web-service.md)
  
[<span data-ttu-id="ed6c1-106">EventCause (servicio web de mensajería unificada)</span><span class="sxs-lookup"><span data-stu-id="ed6c1-106">EventCause (UM web service)</span></span>](eventcause-um-web-service.md)
  
```xml
<GetCallInfoResponse>
  <EventCause/>
</GetCallInfoResponse>
```

 <span data-ttu-id="ed6c1-107">**UMEventCause**</span><span class="sxs-lookup"><span data-stu-id="ed6c1-107">**UMEventCause**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="ed6c1-108">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="ed6c1-108">Attributes and elements</span></span>

<span data-ttu-id="ed6c1-109">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="ed6c1-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="ed6c1-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="ed6c1-110">Attributes</span></span>

<span data-ttu-id="ed6c1-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="ed6c1-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="ed6c1-112">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="ed6c1-112">Child elements</span></span>

<span data-ttu-id="ed6c1-113">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="ed6c1-113">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="ed6c1-114">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="ed6c1-114">Parent elements</span></span>

|<span data-ttu-id="ed6c1-115">**Element**</span><span class="sxs-lookup"><span data-stu-id="ed6c1-115">**Element**</span></span>|<span data-ttu-id="ed6c1-116">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="ed6c1-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="ed6c1-117">GetCallInfoResponse (servicio web de mensajería unificada)</span><span class="sxs-lookup"><span data-stu-id="ed6c1-117">GetCallInfoResponse (UM web service)</span></span>](getcallinforesponse-um-web-service.md) <br/> |<span data-ttu-id="ed6c1-118">Define una respuesta a una solicitud de [operación GetCallInfo (servicio web de mensajería unificada)](getcallinfo-operation-um-web-service.md) .</span><span class="sxs-lookup"><span data-stu-id="ed6c1-118">Defines a response to a [GetCallInfo operation (UM web service)](getcallinfo-operation-um-web-service.md) request.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="ed6c1-119">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="ed6c1-119">Text value</span></span>

<span data-ttu-id="ed6c1-120">Se requiere un valor de texto.</span><span class="sxs-lookup"><span data-stu-id="ed6c1-120">A text value is required.</span></span> <span data-ttu-id="ed6c1-121">Los valores posibles son:</span><span class="sxs-lookup"><span data-stu-id="ed6c1-121">The following are the possible values:</span></span>
  
- <span data-ttu-id="ed6c1-122">None</span><span class="sxs-lookup"><span data-stu-id="ed6c1-122">None</span></span>
    
- <span data-ttu-id="ed6c1-123">UserBusy</span><span class="sxs-lookup"><span data-stu-id="ed6c1-123">UserBusy</span></span>
    
- <span data-ttu-id="ed6c1-124">NoAnswer</span><span class="sxs-lookup"><span data-stu-id="ed6c1-124">NoAnswer</span></span>
    
- <span data-ttu-id="ed6c1-125">Otro</span><span class="sxs-lookup"><span data-stu-id="ed6c1-125">Other</span></span>
    
## <a name="element-information"></a><span data-ttu-id="ed6c1-126">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="ed6c1-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ed6c1-127">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="ed6c1-127">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="ed6c1-128">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="ed6c1-128">Schema Name</span></span>  <br/> |<span data-ttu-id="ed6c1-129">Mensajes</span><span class="sxs-lookup"><span data-stu-id="ed6c1-129">Messages</span></span>  <br/> |
|<span data-ttu-id="ed6c1-130">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="ed6c1-130">Validation File</span></span>  <br/> |<span data-ttu-id="ed6c1-131">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="ed6c1-131">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="ed6c1-132">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="ed6c1-132">Can be Empty</span></span>  <br/> |<span data-ttu-id="ed6c1-133">False</span><span class="sxs-lookup"><span data-stu-id="ed6c1-133">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="ed6c1-134">Ver también</span><span class="sxs-lookup"><span data-stu-id="ed6c1-134">See also</span></span>



[<span data-ttu-id="ed6c1-135">Operación GetCallInfo (servicio web de mensajería unificada)</span><span class="sxs-lookup"><span data-stu-id="ed6c1-135">GetCallInfo operation (UM web service)</span></span>](getcallinfo-operation-um-web-service.md)
  
[<span data-ttu-id="ed6c1-136">GetCallInfoResponse (servicio web de mensajería unificada)</span><span class="sxs-lookup"><span data-stu-id="ed6c1-136">GetCallInfoResponse (UM web service)</span></span>](getcallinforesponse-um-web-service.md)
