---
title: Errores
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Errors
api_type:
- schema
ms.assetid: ea37a2b5-e2d1-4089-960f-7014b9535a50
description: El elemento de errores contiene un contenedor de propiedades para almacenar los errores que se devuelven a través del servicio Web.
ms.openlocfilehash: a029492c1e3c11cc31d3501bd4ea0024ef8ecb91
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764449"
---
# <a name="errors"></a><span data-ttu-id="cc271-103">Errores</span><span class="sxs-lookup"><span data-stu-id="cc271-103">Errors</span></span>

<span data-ttu-id="cc271-104">El elemento de **errores** contiene un contenedor de propiedades para almacenar los errores que se devuelven a través del servicio Web.</span><span class="sxs-lookup"><span data-stu-id="cc271-104">The **Errors** element contains a property bag to store errors that are returned through the Web service.</span></span> 
  
[<span data-ttu-id="cc271-105">FindMessageTrackingReport</span><span class="sxs-lookup"><span data-stu-id="cc271-105">FindMessageTrackingReport</span></span>](findmessagetrackingreport.md)
  
[<span data-ttu-id="cc271-106">Errors</span><span class="sxs-lookup"><span data-stu-id="cc271-106">Errors</span></span>](errors-ex15websvcsotherref.md)
  
```xml
<Errors>
   <Properties/>
</Errors>
```

 <span data-ttu-id="cc271-107">**ArrayOfArraysOfTrackingPropertiesType**</span><span class="sxs-lookup"><span data-stu-id="cc271-107">**ArrayOfArraysOfTrackingPropertiesType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="cc271-108">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="cc271-108">Attributes and elements</span></span>

<span data-ttu-id="cc271-109">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="cc271-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="cc271-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="cc271-110">Attributes</span></span>

<span data-ttu-id="cc271-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="cc271-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="cc271-112">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="cc271-112">Child elements</span></span>

|<span data-ttu-id="cc271-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="cc271-113">**Element**</span></span>|<span data-ttu-id="cc271-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="cc271-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="cc271-115">Propiedades (ArrayOfTrackingPropertiesType)</span><span class="sxs-lookup"><span data-stu-id="cc271-115">Properties (ArrayOfTrackingPropertiesType)</span></span>](properties-arrayoftrackingpropertiestype.md) <br/> |<span data-ttu-id="cc271-116">Contiene una lista de una o varias propiedades de seguimiento.</span><span class="sxs-lookup"><span data-stu-id="cc271-116">Contains a list of one or more tracking properties.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="cc271-117">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="cc271-117">Parent elements</span></span>

|<span data-ttu-id="cc271-118">**Element**</span><span class="sxs-lookup"><span data-stu-id="cc271-118">**Element**</span></span>|<span data-ttu-id="cc271-119">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="cc271-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="cc271-120">FindMessageTrackingReportResponse</span><span class="sxs-lookup"><span data-stu-id="cc271-120">FindMessageTrackingReportResponse</span></span>](findmessagetrackingreportresponse.md) <br/> |<span data-ttu-id="cc271-121">Contiene el estado y el resultado de una única solicitud de [operación FindMessageTrackingReport](findmessagetrackingreport-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="cc271-121">Contains the status and result of a single [FindMessageTrackingReport operation](findmessagetrackingreport-operation.md) request.</span></span>  <br/> |
|[<span data-ttu-id="cc271-122">GetMessageTrackingReportResponse</span><span class="sxs-lookup"><span data-stu-id="cc271-122">GetMessageTrackingReportResponse</span></span>](getmessagetrackingreportresponse.md) <br/> |<span data-ttu-id="cc271-123">Contiene el resultado de una única solicitud de [operación GetMessageTrackingReport](getmessagetrackingreport-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="cc271-123">Contains the result of a single [GetMessageTrackingReport operation](getmessagetrackingreport-operation.md) request.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="cc271-124">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="cc271-124">Text value</span></span>

<span data-ttu-id="cc271-125">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="cc271-125">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="cc271-126">Observaciones</span><span class="sxs-lookup"><span data-stu-id="cc271-126">Remarks</span></span>

<span data-ttu-id="cc271-127">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda Exchange Web Services.This elemento fue introdujo en Exchange Server 2010 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="cc271-127">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).</span></span>
  
## <a name="element-information"></a><span data-ttu-id="cc271-128">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="cc271-128">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="cc271-129">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="cc271-129">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="cc271-130">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="cc271-130">Schema Name</span></span>  <br/> |<span data-ttu-id="cc271-131">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="cc271-131">Messages schema</span></span>  <br/> |
|<span data-ttu-id="cc271-132">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="cc271-132">Validation File</span></span>  <br/> |<span data-ttu-id="cc271-133">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="cc271-133">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="cc271-134">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="cc271-134">Can be Empty</span></span>  <br/> |<span data-ttu-id="cc271-135">False</span><span class="sxs-lookup"><span data-stu-id="cc271-135">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="cc271-136">Ver también</span><span class="sxs-lookup"><span data-stu-id="cc271-136">See also</span></span>



[<span data-ttu-id="cc271-137">Operación FindMessageTrackingReport</span><span class="sxs-lookup"><span data-stu-id="cc271-137">FindMessageTrackingReport operation</span></span>](findmessagetrackingreport-operation.md)
  
[<span data-ttu-id="cc271-138">Operación GetMessageTrackingReport</span><span class="sxs-lookup"><span data-stu-id="cc271-138">GetMessageTrackingReport operation</span></span>](getmessagetrackingreport-operation.md)


- [<span data-ttu-id="cc271-139">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="cc271-139">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
