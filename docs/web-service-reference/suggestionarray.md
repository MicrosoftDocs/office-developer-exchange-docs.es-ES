---
title: SuggestionArray
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- SuggestionArray
api_type:
- schema
ms.assetid: c1c26008-7b14-4563-8db5-bceb0f475b1b
description: El elemento SuggestionArray contiene una matriz de sugerencias de reunión.
ms.openlocfilehash: d595ae77de293a1975e15102f3f2c3395e6da633
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19840598"
---
# <a name="suggestionarray"></a><span data-ttu-id="11ea9-103">SuggestionArray</span><span class="sxs-lookup"><span data-stu-id="11ea9-103">SuggestionArray</span></span>

<span data-ttu-id="11ea9-104">El elemento **SuggestionArray** contiene una matriz de sugerencias de reunión.</span><span class="sxs-lookup"><span data-stu-id="11ea9-104">The **SuggestionArray** element contains an array of meeting suggestions.</span></span> 
  
[<span data-ttu-id="11ea9-105">GetUserAvailabilityResponse</span><span class="sxs-lookup"><span data-stu-id="11ea9-105">GetUserAvailabilityResponse</span></span>](getuseravailabilityresponse.md)
  
[<span data-ttu-id="11ea9-106">SuggestionsResponse</span><span class="sxs-lookup"><span data-stu-id="11ea9-106">SuggestionsResponse</span></span>](suggestionsresponse.md)
  
[<span data-ttu-id="11ea9-107">SuggestionDayResultArray</span><span class="sxs-lookup"><span data-stu-id="11ea9-107">SuggestionDayResultArray</span></span>](suggestiondayresultarray.md)
  
[<span data-ttu-id="11ea9-108">SuggestionDayResult</span><span class="sxs-lookup"><span data-stu-id="11ea9-108">SuggestionDayResult</span></span>](suggestiondayresult.md)
  
[<span data-ttu-id="11ea9-109">SuggestionArray</span><span class="sxs-lookup"><span data-stu-id="11ea9-109">SuggestionArray</span></span>](suggestionarray.md)
  
```xml
<SuggestionArray>
   <Suggestion>...</Suggestion>
</SuggestionArray>
```

 <span data-ttu-id="11ea9-110">**ArrayOfSuggestion**</span><span class="sxs-lookup"><span data-stu-id="11ea9-110">**ArrayOfSuggestion**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="11ea9-111">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="11ea9-111">Attributes and elements</span></span>

<span data-ttu-id="11ea9-112">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="11ea9-112">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="11ea9-113">Atributos</span><span class="sxs-lookup"><span data-stu-id="11ea9-113">Attributes</span></span>

<span data-ttu-id="11ea9-114">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="11ea9-114">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="11ea9-115">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="11ea9-115">Child elements</span></span>

|<span data-ttu-id="11ea9-116">**Element**</span><span class="sxs-lookup"><span data-stu-id="11ea9-116">**Element**</span></span>|<span data-ttu-id="11ea9-117">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="11ea9-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="11ea9-118">Sugerencia</span><span class="sxs-lookup"><span data-stu-id="11ea9-118">Suggestion</span></span>](suggestion.md) <br/> |<span data-ttu-id="11ea9-119">Representa una sugerencia de reunión única.</span><span class="sxs-lookup"><span data-stu-id="11ea9-119">Represents a single meeting suggestion.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="11ea9-120">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="11ea9-120">Parent elements</span></span>

|<span data-ttu-id="11ea9-121">**Element**</span><span class="sxs-lookup"><span data-stu-id="11ea9-121">**Element**</span></span>|<span data-ttu-id="11ea9-122">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="11ea9-122">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="11ea9-123">SuggestionDayResult</span><span class="sxs-lookup"><span data-stu-id="11ea9-123">SuggestionDayResult</span></span>](suggestiondayresult.md) <br/> |<span data-ttu-id="11ea9-124">Representa un solo día que contiene las horas de reunión sugerida.</span><span class="sxs-lookup"><span data-stu-id="11ea9-124">Represents a single day that contains suggested meeting times.</span></span>  <br/> <span data-ttu-id="11ea9-125">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="11ea9-125">The following is the XPath expression to this element:</span></span>  <br/>  `/GetUserAvailabilityResponse/SuggestionsResponse/SuggestionDayResultArray/SuggestionDayResult[i]` <br/> |
   
## <a name="remarks"></a><span data-ttu-id="11ea9-126">Notas</span><span class="sxs-lookup"><span data-stu-id="11ea9-126">Remarks</span></span>

<span data-ttu-id="11ea9-127">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="11ea9-127">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="11ea9-128">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="11ea9-128">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="11ea9-129">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="11ea9-129">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="11ea9-130">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="11ea9-130">Schema Name</span></span>  <br/> |<span data-ttu-id="11ea9-131">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="11ea9-131">Types schema</span></span>  <br/> |
|<span data-ttu-id="11ea9-132">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="11ea9-132">Validation File</span></span>  <br/> |<span data-ttu-id="11ea9-133">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="11ea9-133">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="11ea9-134">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="11ea9-134">Can be Empty</span></span>  <br/> |<span data-ttu-id="11ea9-135">False</span><span class="sxs-lookup"><span data-stu-id="11ea9-135">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="11ea9-136">Ver también</span><span class="sxs-lookup"><span data-stu-id="11ea9-136">See also</span></span>



[<span data-ttu-id="11ea9-137">Operación GetUserAvailability</span><span class="sxs-lookup"><span data-stu-id="11ea9-137">GetUserAvailability operation</span></span>](getuseravailability-operation.md)
  
[<span data-ttu-id="11ea9-138">GetUserAvailabilityResponse</span><span class="sxs-lookup"><span data-stu-id="11ea9-138">GetUserAvailabilityResponse</span></span>](getuseravailabilityresponse.md)


[<span data-ttu-id="11ea9-139">Obtención de disponibilidad del usuario</span><span class="sxs-lookup"><span data-stu-id="11ea9-139">Getting User Availability</span></span>](http://msdn.microsoft.com/library/d4133fcb-9b0f-4e6b-aadf-a389da83516a%28Office.15%29.aspx)
