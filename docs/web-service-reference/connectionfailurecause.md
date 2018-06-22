---
title: ConnectionFailureCause
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ConnectionFailureCause
api_type:
- schema
ms.assetid: d2160c8a-015c-4964-b7f7-93478764a173
description: El elemento ConnectionFailureCause especifica la razón de una desconexión de una llamada telefónica.
ms.openlocfilehash: 54b4f5b89efdb42ef82dbef8f1af14a39c0ccc6a
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19763774"
---
# <a name="connectionfailurecause"></a><span data-ttu-id="5129d-103">ConnectionFailureCause</span><span class="sxs-lookup"><span data-stu-id="5129d-103">ConnectionFailureCause</span></span>

<span data-ttu-id="5129d-104">El elemento **ConnectionFailureCause** especifica la razón de una desconexión de una llamada telefónica.</span><span class="sxs-lookup"><span data-stu-id="5129d-104">The **ConnectionFailureCause** element specifies the reason for a disconnection from a telephone call.</span></span> 
  
```xml
<ConnectionFailureCause>None or UserBusy or NoAnswer or Unavailable or Other</ConnectionFailureCause>
```

 <span data-ttu-id="5129d-105">**ConnectionFailureCauseType**</span><span class="sxs-lookup"><span data-stu-id="5129d-105">**ConnectionFailureCauseType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="5129d-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="5129d-106">Attributes and elements</span></span>

<span data-ttu-id="5129d-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="5129d-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="5129d-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="5129d-108">Attributes</span></span>

<span data-ttu-id="5129d-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="5129d-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="5129d-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="5129d-110">Child elements</span></span>

<span data-ttu-id="5129d-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="5129d-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="5129d-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="5129d-112">Parent elements</span></span>

|<span data-ttu-id="5129d-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="5129d-113">**Element**</span></span>|<span data-ttu-id="5129d-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="5129d-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="5129d-115">PhoneCallInformation</span><span class="sxs-lookup"><span data-stu-id="5129d-115">PhoneCallInformation</span></span>](phonecallinformation.md) <br/> |<span data-ttu-id="5129d-116">Especifica la información de estado para una llamada de teléfono.</span><span class="sxs-lookup"><span data-stu-id="5129d-116">Specifies the state information for a telephone call.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="5129d-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="5129d-117">Text value</span></span>

<span data-ttu-id="5129d-118">En la siguiente tabla se enumera los valores posibles para el elemento **ConnectionFailureCause** .</span><span class="sxs-lookup"><span data-stu-id="5129d-118">The following table lists the possible values for the **ConnectionFailureCause** element.</span></span> 
  
<span data-ttu-id="5129d-119">**Valores de elemento ConnectionFailureCause**</span><span class="sxs-lookup"><span data-stu-id="5129d-119">**ConnectionFailureCause element values**</span></span>

|<span data-ttu-id="5129d-120">**Valor**</span><span class="sxs-lookup"><span data-stu-id="5129d-120">**Value**</span></span>|<span data-ttu-id="5129d-121">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="5129d-121">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="5129d-122">None</span><span class="sxs-lookup"><span data-stu-id="5129d-122">None</span></span>  <br/> |<span data-ttu-id="5129d-123">Estado de llamada no está desconectado o no se conoce la razón por la desconexión.</span><span class="sxs-lookup"><span data-stu-id="5129d-123">Call state is not disconnected or the disconnect reason is not known.</span></span>  <br/> |
|<span data-ttu-id="5129d-124">UserBusy</span><span class="sxs-lookup"><span data-stu-id="5129d-124">UserBusy</span></span>  <br/> |<span data-ttu-id="5129d-125">La línea de terceros llamada estaba ocupada.</span><span class="sxs-lookup"><span data-stu-id="5129d-125">The called party line was busy.</span></span>  <br/> |
|<span data-ttu-id="5129d-126">NoAnswer</span><span class="sxs-lookup"><span data-stu-id="5129d-126">NoAnswer</span></span>  <br/> |<span data-ttu-id="5129d-127">El receptor no ha respondido.</span><span class="sxs-lookup"><span data-stu-id="5129d-127">The called party did not answer.</span></span>  <br/> |
|<span data-ttu-id="5129d-128">No disponible</span><span class="sxs-lookup"><span data-stu-id="5129d-128">Unavailable</span></span>  <br/> |<span data-ttu-id="5129d-129">El número de receptor no estaba disponible.</span><span class="sxs-lookup"><span data-stu-id="5129d-129">The called party number was not available.</span></span>  <br/> |
|<span data-ttu-id="5129d-130">Otro</span><span class="sxs-lookup"><span data-stu-id="5129d-130">Other</span></span>  <br/> |<span data-ttu-id="5129d-131">Denominaba por otros motivos desconectar.</span><span class="sxs-lookup"><span data-stu-id="5129d-131">Catch-all for other disconnect reasons.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="5129d-132">Notas</span><span class="sxs-lookup"><span data-stu-id="5129d-132">Remarks</span></span>

<span data-ttu-id="5129d-133">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="5129d-133">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="5129d-134">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="5129d-134">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5129d-135">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="5129d-135">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="5129d-136">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="5129d-136">Schema Name</span></span>  <br/> |<span data-ttu-id="5129d-137">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="5129d-137">Types schema</span></span>  <br/> |
|<span data-ttu-id="5129d-138">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="5129d-138">Validation File</span></span>  <br/> |<span data-ttu-id="5129d-139">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="5129d-139">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="5129d-140">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="5129d-140">Can be Empty</span></span>  <br/> |<span data-ttu-id="5129d-141">False</span><span class="sxs-lookup"><span data-stu-id="5129d-141">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="5129d-142">Ver también</span><span class="sxs-lookup"><span data-stu-id="5129d-142">See also</span></span>



- [<span data-ttu-id="5129d-143">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="5129d-143">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
