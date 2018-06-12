---
title: NumberOfMembers
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- NumberOfMembers
api_type:
- schema
ms.assetid: 845fb877-de49-4e26-8885-6f026edd9ee9
description: El elemento NumberOfMembers representa el número de usuarios, recursos y salas en una lista de distribución.
ms.openlocfilehash: 9777660b1a54bfb5afb6e569ba1009a1654bdef3
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836635"
---
# <a name="numberofmembers"></a><span data-ttu-id="601ae-103">NumberOfMembers</span><span class="sxs-lookup"><span data-stu-id="601ae-103">NumberOfMembers</span></span>

<span data-ttu-id="601ae-104">El elemento **NumberOfMembers** representa el número de usuarios, recursos y salas en una lista de distribución.</span><span class="sxs-lookup"><span data-stu-id="601ae-104">The **NumberOfMembers** element represents the number of users, resources, and rooms in a distribution list.</span></span> 
  
[<span data-ttu-id="601ae-105">GetUserAvailabilityResponse</span><span class="sxs-lookup"><span data-stu-id="601ae-105">GetUserAvailabilityResponse</span></span>](getuseravailabilityresponse.md)
  
[<span data-ttu-id="601ae-106">SuggestionsResponse</span><span class="sxs-lookup"><span data-stu-id="601ae-106">SuggestionsResponse</span></span>](suggestionsresponse.md)
  
[<span data-ttu-id="601ae-107">SuggestionDayResultArray</span><span class="sxs-lookup"><span data-stu-id="601ae-107">SuggestionDayResultArray</span></span>](suggestiondayresultarray.md)
  
[<span data-ttu-id="601ae-108">SuggestionDayResult</span><span class="sxs-lookup"><span data-stu-id="601ae-108">SuggestionDayResult</span></span>](suggestiondayresult.md)
  
[<span data-ttu-id="601ae-109">SuggestionArray</span><span class="sxs-lookup"><span data-stu-id="601ae-109">SuggestionArray</span></span>](suggestionarray.md)
  
[<span data-ttu-id="601ae-110">Sugerencia</span><span class="sxs-lookup"><span data-stu-id="601ae-110">Suggestion</span></span>](suggestion.md)
  
[<span data-ttu-id="601ae-111">AttendeeConflictDataArray</span><span class="sxs-lookup"><span data-stu-id="601ae-111">AttendeeConflictDataArray</span></span>](attendeeconflictdataarray.md)
  
[<span data-ttu-id="601ae-112">GroupAttendeeConflictData</span><span class="sxs-lookup"><span data-stu-id="601ae-112">GroupAttendeeConflictData</span></span>](groupattendeeconflictdata.md)
  
[<span data-ttu-id="601ae-113">NumberOfMembers</span><span class="sxs-lookup"><span data-stu-id="601ae-113">NumberOfMembers</span></span>](numberofmembers.md)
  
```xml
<NumberOfMembers>...</NumberOfMembers>
```

 <span data-ttu-id="601ae-114">**int**</span><span class="sxs-lookup"><span data-stu-id="601ae-114">**int**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="601ae-115">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="601ae-115">Attributes and elements</span></span>

<span data-ttu-id="601ae-116">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="601ae-116">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="601ae-117">Atributos</span><span class="sxs-lookup"><span data-stu-id="601ae-117">Attributes</span></span>

<span data-ttu-id="601ae-118">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="601ae-118">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="601ae-119">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="601ae-119">Child elements</span></span>

<span data-ttu-id="601ae-120">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="601ae-120">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="601ae-121">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="601ae-121">Parent elements</span></span>

|<span data-ttu-id="601ae-122">**Element**</span><span class="sxs-lookup"><span data-stu-id="601ae-122">**Element**</span></span>|<span data-ttu-id="601ae-123">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="601ae-123">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="601ae-124">GroupAttendeeConflictData</span><span class="sxs-lookup"><span data-stu-id="601ae-124">GroupAttendeeConflictData</span></span>](groupattendeeconflictdata.md) <br/> |<span data-ttu-id="601ae-125">Contiene información de conflicto agregado sobre el número de usuarios disponibles, el número de usuarios que tienen conflictos y el número de usuarios que no tienen información de disponibilidad en una lista de distribución para una hora de reunión sugerida.</span><span class="sxs-lookup"><span data-stu-id="601ae-125">Contains aggregate conflict information about the number of users available, the number of users who have conflicts, and the number of users who do not have availability information in a distribution list for a suggested meeting time.</span></span>  <br/> <span data-ttu-id="601ae-126">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="601ae-126">The following is the XPath expression to this element:</span></span>  <br/>  `/GetUserAvailabilityResponse/SuggestionsResponse/SuggestionDayResultArray/SuggestionDayResult[i]/SuggestionArray/Suggestion[i]/AttendeeConflictDataArray/GroupAttendeeConflictData` <br/> |
   
## <a name="remarks"></a><span data-ttu-id="601ae-127">Notas</span><span class="sxs-lookup"><span data-stu-id="601ae-127">Remarks</span></span>

<span data-ttu-id="601ae-128">El valor máximo del elemento **NumberOfMembers** es 100.</span><span class="sxs-lookup"><span data-stu-id="601ae-128">The maximum value of the **NumberOfMembers** element is 100.</span></span> 
  
<span data-ttu-id="601ae-129">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="601ae-129">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="601ae-130">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="601ae-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="601ae-131">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="601ae-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="601ae-132">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="601ae-132">Schema Name</span></span>  <br/> |<span data-ttu-id="601ae-133">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="601ae-133">Types schema</span></span>  <br/> |
|<span data-ttu-id="601ae-134">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="601ae-134">Validation File</span></span>  <br/> |<span data-ttu-id="601ae-135">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="601ae-135">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="601ae-136">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="601ae-136">Can be Empty</span></span>  <br/> |<span data-ttu-id="601ae-137">False</span><span class="sxs-lookup"><span data-stu-id="601ae-137">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="601ae-138">Ver también</span><span class="sxs-lookup"><span data-stu-id="601ae-138">See also</span></span>



[<span data-ttu-id="601ae-139">Operación GetUserAvailability</span><span class="sxs-lookup"><span data-stu-id="601ae-139">GetUserAvailability operation</span></span>](getuseravailability-operation.md)
  
[<span data-ttu-id="601ae-140">GetUserAvailabilityResponse</span><span class="sxs-lookup"><span data-stu-id="601ae-140">GetUserAvailabilityResponse</span></span>](getuseravailabilityresponse.md)


[<span data-ttu-id="601ae-141">Obtención de disponibilidad del usuario</span><span class="sxs-lookup"><span data-stu-id="601ae-141">Getting User Availability</span></span>](http://msdn.microsoft.com/library/d4133fcb-9b0f-4e6b-aadf-a389da83516a%28Office.15%29.aspx)
