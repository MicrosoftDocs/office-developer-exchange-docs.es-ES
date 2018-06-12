---
title: TransitionsGroup
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- TransitionsGroup
api_type:
- schema
ms.assetid: 19d56080-546a-4d53-929e-363d56186759
description: El elemento TransitionsGroup representa una matriz de las transiciones de zona horaria.
ms.openlocfilehash: e5991ad7f73a1694e0d4abadd8d252acc04970e5
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19840726"
---
# <a name="transitionsgroup"></a><span data-ttu-id="c6fd8-103">TransitionsGroup</span><span class="sxs-lookup"><span data-stu-id="c6fd8-103">TransitionsGroup</span></span>

<span data-ttu-id="c6fd8-104">El elemento **TransitionsGroup** representa una matriz de las transiciones de zona horaria.</span><span class="sxs-lookup"><span data-stu-id="c6fd8-104">The **TransitionsGroup** element represents an array of time zone transitions.</span></span> 
  
```xml
<TransitionsGroup Id="">
   <AbsoluteDateTransition/>
   <RecurringDayTransition/>
   <RecurringDateTransition/>
</TransitionsGroup>
```

 <span data-ttu-id="c6fd8-105">**ArrayOfTransitionsType**</span><span class="sxs-lookup"><span data-stu-id="c6fd8-105">**ArrayOfTransitionsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="c6fd8-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="c6fd8-106">Attributes and elements</span></span>

<span data-ttu-id="c6fd8-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="c6fd8-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="c6fd8-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="c6fd8-108">Attributes</span></span>

|<span data-ttu-id="c6fd8-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="c6fd8-109">**Attribute**</span></span>|<span data-ttu-id="c6fd8-110">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="c6fd8-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="c6fd8-111">Id</span><span class="sxs-lookup"><span data-stu-id="c6fd8-111">Id</span></span>  <br/> |<span data-ttu-id="c6fd8-112">Un valor de tipo string que representa el identificador único del grupo de transiciones.</span><span class="sxs-lookup"><span data-stu-id="c6fd8-112">A string value that represents the unique identifier of the transitions group.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="c6fd8-113">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="c6fd8-113">Child elements</span></span>

|<span data-ttu-id="c6fd8-114">**Element**</span><span class="sxs-lookup"><span data-stu-id="c6fd8-114">**Element**</span></span>|<span data-ttu-id="c6fd8-115">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="c6fd8-115">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c6fd8-116">AbsoluteDateTransition</span><span class="sxs-lookup"><span data-stu-id="c6fd8-116">AbsoluteDateTransition</span></span>](absolutedatetransition.md) <br/> |<span data-ttu-id="c6fd8-117">Representa una transición de la zona horaria que se produce en una fecha específica y a una hora específica.</span><span class="sxs-lookup"><span data-stu-id="c6fd8-117">Represents a time zone transition that occurs on a specific date and at a specific time.</span></span>  <br/> |
|[<span data-ttu-id="c6fd8-118">RecurringDayTransition</span><span class="sxs-lookup"><span data-stu-id="c6fd8-118">RecurringDayTransition</span></span>](recurringdaytransition.md) <br/> |<span data-ttu-id="c6fd8-119">Representa una transición de la zona horaria que se produce en el mismo día cada año.</span><span class="sxs-lookup"><span data-stu-id="c6fd8-119">Represents a time zone transition that occurs on the same day each year.</span></span>  <br/> |
|[<span data-ttu-id="c6fd8-120">RecurringDateTransition</span><span class="sxs-lookup"><span data-stu-id="c6fd8-120">RecurringDateTransition</span></span>](recurringdatetransition.md) <br/> |<span data-ttu-id="c6fd8-121">Representa una transición de la zona horaria que se produce en un día del año especificado.</span><span class="sxs-lookup"><span data-stu-id="c6fd8-121">Represents a time zone transition that occurs on a specified day of the year.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="c6fd8-122">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="c6fd8-122">Parent elements</span></span>

|<span data-ttu-id="c6fd8-123">**Element**</span><span class="sxs-lookup"><span data-stu-id="c6fd8-123">**Element**</span></span>|<span data-ttu-id="c6fd8-124">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="c6fd8-124">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c6fd8-125">TransitionsGroups</span><span class="sxs-lookup"><span data-stu-id="c6fd8-125">TransitionsGroups</span></span>](transitionsgroups.md) <br/> |<span data-ttu-id="c6fd8-126">Representa una matriz de grupos de transición de zona horaria.</span><span class="sxs-lookup"><span data-stu-id="c6fd8-126">Represents an array of time zone transition groups.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="c6fd8-127">Notas</span><span class="sxs-lookup"><span data-stu-id="c6fd8-127">Remarks</span></span>

<span data-ttu-id="c6fd8-128">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que ejecuta Microsoft Exchange Server que tiene instalada la función del servidor acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="c6fd8-128">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="c6fd8-129">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="c6fd8-129">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c6fd8-130">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="c6fd8-130">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="c6fd8-131">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="c6fd8-131">Schema Name</span></span>  <br/> |<span data-ttu-id="c6fd8-132">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="c6fd8-132">Types schema</span></span>  <br/> |
|<span data-ttu-id="c6fd8-133">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="c6fd8-133">Validation File</span></span>  <br/> |<span data-ttu-id="c6fd8-134">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="c6fd8-134">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="c6fd8-135">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="c6fd8-135">Can be Empty</span></span>  <br/> |<span data-ttu-id="c6fd8-136">False</span><span class="sxs-lookup"><span data-stu-id="c6fd8-136">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="c6fd8-137">Ver también</span><span class="sxs-lookup"><span data-stu-id="c6fd8-137">See also</span></span>



- [<span data-ttu-id="c6fd8-138">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="c6fd8-138">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
