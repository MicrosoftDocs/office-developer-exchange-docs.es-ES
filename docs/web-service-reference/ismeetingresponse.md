---
title: IsMeetingResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IsMeetingResponse
api_type:
- schema
ms.assetid: 85090943-81c6-4fbe-a2db-007dced6a4cf
description: El elemento IsMeetngResponsequest indica si los mensajes entrantes deben ser una respuesta a la reunión en orden para la condición o la excepción que se debe aplicar.
ms.openlocfilehash: 9040859452a48916a969b6d8e4e370b5785c1c1a
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836053"
---
# <a name="ismeetingresponse"></a><span data-ttu-id="15f65-103">IsMeetingResponse</span><span class="sxs-lookup"><span data-stu-id="15f65-103">IsMeetingResponse</span></span>

<span data-ttu-id="15f65-104">El elemento **IsMeetngResponsequest** indica si los mensajes entrantes deben ser una respuesta a la reunión en orden para la condición o la excepción que se debe aplicar.</span><span class="sxs-lookup"><span data-stu-id="15f65-104">The **IsMeetngResponsequest** element indicates whether incoming messages must be a meeting response in order for the condition or exception to apply.</span></span> 
  
```XML
<IsMeetingResponse/>true | false</IsMeetingResponse>
```

 <span data-ttu-id="15f65-105">**Boolean**</span><span class="sxs-lookup"><span data-stu-id="15f65-105">**Boolean**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="15f65-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="15f65-106">Attributes and elements</span></span>

<span data-ttu-id="15f65-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="15f65-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="15f65-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="15f65-108">Attributes</span></span>

<span data-ttu-id="15f65-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="15f65-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="15f65-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="15f65-110">Child elements</span></span>

<span data-ttu-id="15f65-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="15f65-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="15f65-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="15f65-112">Parent elements</span></span>

|<span data-ttu-id="15f65-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="15f65-113">**Element**</span></span>|<span data-ttu-id="15f65-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="15f65-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="15f65-115">Condiciones</span><span class="sxs-lookup"><span data-stu-id="15f65-115">Conditions</span></span>](conditions.md) <br/> |<span data-ttu-id="15f65-116">Representa las condiciones que, cuando se cumplen los requisitos, se activará las acciones de regla para una regla.</span><span class="sxs-lookup"><span data-stu-id="15f65-116">Represents the conditions that, when fulfilled, will trigger the rule actions for a rule.</span></span>  <br/> |
|[<span data-ttu-id="15f65-117">Excepciones</span><span class="sxs-lookup"><span data-stu-id="15f65-117">Exceptions</span></span>](exceptions.md) <br/> |<span data-ttu-id="15f65-118">Representa todas las condiciones de excepción de regla disponibles para una regla de bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="15f65-118">Represents all the available rule exception conditions for an Inbox rule.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="15f65-119">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="15f65-119">Text value</span></span>

<span data-ttu-id="15f65-120">Un valor de texto de **true** indica que el mensaje debe ser una respuesta a la reunión en orden para la condición o la excepción que se debe aplicar.</span><span class="sxs-lookup"><span data-stu-id="15f65-120">A text value of **true** indicates that the message must be a meeting response in order for the condition or exception to apply.</span></span> <span data-ttu-id="15f65-121">Un valor de texto de **false** indica que el mensaje no debe ser una respuesta a la reunión en orden para la condición o la excepción que se debe aplicar.</span><span class="sxs-lookup"><span data-stu-id="15f65-121">A text value of **false** indicates that the message must not be a meeting response in order for the condition or exception to apply.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="15f65-122">Notas</span><span class="sxs-lookup"><span data-stu-id="15f65-122">Remarks</span></span>

<span data-ttu-id="15f65-123">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="15f65-123">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="15f65-124">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="15f65-124">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="15f65-125">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="15f65-125">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="15f65-126">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="15f65-126">Schema Name</span></span>  <br/> |<span data-ttu-id="15f65-127">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="15f65-127">Messages schema</span></span>  <br/> |
|<span data-ttu-id="15f65-128">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="15f65-128">Validation File</span></span>  <br/> |<span data-ttu-id="15f65-129">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="15f65-129">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="15f65-130">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="15f65-130">Can be Empty</span></span>  <br/> |<span data-ttu-id="15f65-131">Verdadero</span><span class="sxs-lookup"><span data-stu-id="15f65-131">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="15f65-132">Ver también</span><span class="sxs-lookup"><span data-stu-id="15f65-132">See also</span></span>



- [<span data-ttu-id="15f65-133">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="15f65-133">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
