---
title: IsOutOfDate
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IsOutOfDate
api_type:
- schema
ms.assetid: 2b6005a6-56a9-4848-b998-32908c13e2e2
description: El elemento IsOutOfDate indica si un mensaje de la reunión, solicitud, respuesta o cancelación no está actualizada.
ms.openlocfilehash: 0a6b2670cc3eb260002821bab31d652177902de1
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836110"
---
# <a name="isoutofdate"></a><span data-ttu-id="ba4b2-103">IsOutOfDate</span><span class="sxs-lookup"><span data-stu-id="ba4b2-103">IsOutOfDate</span></span>

<span data-ttu-id="ba4b2-104">El elemento **IsOutOfDate** indica si un mensaje de la reunión, solicitud, respuesta o cancelación no está actualizada.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-104">The **IsOutOfDate** element indicates whether a meeting message, request, response, or cancellation is out-of-date.</span></span> 
  
```xml
<IsOutOfDate/>
```

 <span data-ttu-id="ba4b2-105">**Boolean**</span><span class="sxs-lookup"><span data-stu-id="ba4b2-105">**Boolean**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="ba4b2-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="ba4b2-106">Attributes and elements</span></span>

<span data-ttu-id="ba4b2-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="ba4b2-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="ba4b2-108">Attributes</span></span>

<span data-ttu-id="ba4b2-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="ba4b2-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="ba4b2-110">Child elements</span></span>

<span data-ttu-id="ba4b2-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="ba4b2-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="ba4b2-112">Parent elements</span></span>

|<span data-ttu-id="ba4b2-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="ba4b2-113">**Element**</span></span>|<span data-ttu-id="ba4b2-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="ba4b2-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="ba4b2-115">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="ba4b2-115">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="ba4b2-116">Representa la cancelación de la reunión en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-116">Represents a meeting cancellation in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="ba4b2-117">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="ba4b2-117">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="ba4b2-118">Representa una reunión en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-118">Represents a meeting in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="ba4b2-119">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="ba4b2-119">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="ba4b2-120">Representa una convocatoria de reunión en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-120">Represents a meeting request in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="ba4b2-121">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="ba4b2-121">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="ba4b2-122">Representa una respuesta a la reunión en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-122">Represents a meeting response in the Exchange store.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="ba4b2-123">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="ba4b2-123">Text value</span></span>

<span data-ttu-id="ba4b2-124">Un valor de texto de **true** indica que el elemento de reunión está obsoleto.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-124">A text value of **true** indicates that the meeting item is out-of-date.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="ba4b2-125">Notas</span><span class="sxs-lookup"><span data-stu-id="ba4b2-125">Remarks</span></span>

<span data-ttu-id="ba4b2-126">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="ba4b2-126">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="ba4b2-127">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="ba4b2-127">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ba4b2-128">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="ba4b2-128">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="ba4b2-129">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="ba4b2-129">Schema Name</span></span>  <br/> |<span data-ttu-id="ba4b2-130">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="ba4b2-130">Types schema</span></span>  <br/> |
|<span data-ttu-id="ba4b2-131">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="ba4b2-131">Validation File</span></span>  <br/> |<span data-ttu-id="ba4b2-132">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="ba4b2-132">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="ba4b2-133">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="ba4b2-133">Can be Empty</span></span>  <br/> |<span data-ttu-id="ba4b2-134">False</span><span class="sxs-lookup"><span data-stu-id="ba4b2-134">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="ba4b2-135">Ver también</span><span class="sxs-lookup"><span data-stu-id="ba4b2-135">See also</span></span>



- [<span data-ttu-id="ba4b2-136">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="ba4b2-136">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
