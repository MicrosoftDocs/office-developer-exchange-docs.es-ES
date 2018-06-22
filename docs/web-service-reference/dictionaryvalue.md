---
title: DictionaryValue
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DictionaryValue
api_type:
- schema
ms.assetid: f4089381-826f-4f6a-8c6d-e51b910cbe6d
description: El elemento DictionaryValue especifica el valor de diccionario para una propiedad de diccionario.
ms.openlocfilehash: 78e4cd7e5d3d8f18276912da56bafb44cda76753
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764160"
---
# <a name="dictionaryvalue"></a><span data-ttu-id="6f34d-103">DictionaryValue</span><span class="sxs-lookup"><span data-stu-id="6f34d-103">DictionaryValue</span></span>

<span data-ttu-id="6f34d-104">El elemento **DictionaryValue** especifica el valor de diccionario para una propiedad de diccionario.</span><span class="sxs-lookup"><span data-stu-id="6f34d-104">The **DictionaryValue** element specifies the dictionary value for a dictionary property.</span></span> 
  
```xml
<DictionaryValue>
   <Type/>
   <Value/>
</DictionaryValue>
```

 <span data-ttu-id="6f34d-105">**UserConfigurationDictionaryObjectType**</span><span class="sxs-lookup"><span data-stu-id="6f34d-105">**UserConfigurationDictionaryObjectType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="6f34d-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="6f34d-106">Attributes and elements</span></span>

<span data-ttu-id="6f34d-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="6f34d-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="6f34d-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="6f34d-108">Attributes</span></span>

<span data-ttu-id="6f34d-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="6f34d-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="6f34d-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="6f34d-110">Child elements</span></span>

|<span data-ttu-id="6f34d-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="6f34d-111">**Element**</span></span>|<span data-ttu-id="6f34d-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="6f34d-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="6f34d-113">Tipo (UserConfiguration)</span><span class="sxs-lookup"><span data-stu-id="6f34d-113">Type (UserConfiguration)</span></span>](type-userconfiguration.md) <br/> |<span data-ttu-id="6f34d-114">Especifica el tipo de objeto de diccionario.</span><span class="sxs-lookup"><span data-stu-id="6f34d-114">Specifies the dictionary object type.</span></span>  <br/> |
|[<span data-ttu-id="6f34d-115">Valor (UserConfiguration)</span><span class="sxs-lookup"><span data-stu-id="6f34d-115">Value (UserConfiguration)</span></span>](value-userconfiguration.md) <br/> |<span data-ttu-id="6f34d-116">Especifica el valor del objeto diccionario como una cadena.</span><span class="sxs-lookup"><span data-stu-id="6f34d-116">Specifies the dictionary object value as a string.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="6f34d-117">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="6f34d-117">Parent elements</span></span>

|<span data-ttu-id="6f34d-118">**Element**</span><span class="sxs-lookup"><span data-stu-id="6f34d-118">**Element**</span></span>|<span data-ttu-id="6f34d-119">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="6f34d-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="6f34d-120">DictionaryEntry</span><span class="sxs-lookup"><span data-stu-id="6f34d-120">DictionaryEntry</span></span>](dictionaryentry.md) <br/> |<span data-ttu-id="6f34d-121">Especifica el contenido de una propiedad de entrada único diccionario.</span><span class="sxs-lookup"><span data-stu-id="6f34d-121">Specifies the contents of a single dictionary entry property.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="6f34d-122">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="6f34d-122">Text value</span></span>

<span data-ttu-id="6f34d-123">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="6f34d-123">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="6f34d-124">Observaciones</span><span class="sxs-lookup"><span data-stu-id="6f34d-124">Remarks</span></span>

<span data-ttu-id="6f34d-125">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="6f34d-125">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="6f34d-126">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="6f34d-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6f34d-127">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="6f34d-127">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="6f34d-128">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="6f34d-128">Schema Name</span></span>  <br/> |<span data-ttu-id="6f34d-129">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="6f34d-129">Types schema</span></span>  <br/> |
|<span data-ttu-id="6f34d-130">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="6f34d-130">Validation File</span></span>  <br/> |<span data-ttu-id="6f34d-131">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="6f34d-131">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="6f34d-132">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="6f34d-132">Can be Empty</span></span>  <br/> |<span data-ttu-id="6f34d-133">False</span><span class="sxs-lookup"><span data-stu-id="6f34d-133">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="6f34d-134">Ver también</span><span class="sxs-lookup"><span data-stu-id="6f34d-134">See also</span></span>

- [<span data-ttu-id="6f34d-135">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="6f34d-135">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
