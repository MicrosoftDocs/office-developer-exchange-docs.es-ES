---
title: Argumento
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Argument
api_type:
- schema
ms.assetid: 15b0bfb8-2448-4ceb-aeac-965115e0fb72
description: El elemento de argumento especifica argumentos para la acción.
ms.openlocfilehash: ed4e46a8d9897516e9c96bf3930f7d488bc06714
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/25/2018
ms.locfileid: "19763554"
---
# <a name="argument"></a><span data-ttu-id="704d7-103">Argumento</span><span class="sxs-lookup"><span data-stu-id="704d7-103">Argument</span></span>

<span data-ttu-id="704d7-104">El elemento de **argumento** especifica argumentos para la acción.</span><span class="sxs-lookup"><span data-stu-id="704d7-104">The **Argument** element specifies arguments to the action.</span></span> 
  
```xml
<Argument Value=""/>
```

 <span data-ttu-id="704d7-105">**ProtectionRuleArgumentType**</span><span class="sxs-lookup"><span data-stu-id="704d7-105">**ProtectionRuleArgumentType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="704d7-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="704d7-106">Attributes and elements</span></span>

<span data-ttu-id="704d7-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="704d7-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="704d7-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="704d7-108">Attributes</span></span>

|<span data-ttu-id="704d7-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="704d7-109">**Attribute**</span></span>|<span data-ttu-id="704d7-110">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="704d7-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="704d7-111">**Value**</span><span class="sxs-lookup"><span data-stu-id="704d7-111">**Value**</span></span> <br/> |<span data-ttu-id="704d7-112">Un valor de cadena no vacía que representa el valor de un argumento para el elemento de acción de una regla de protección.</span><span class="sxs-lookup"><span data-stu-id="704d7-112">A non-empty string value that represents the value of an argument to the action part of a protection rule.</span></span> <span data-ttu-id="704d7-113">Este atributo es necesario.</span><span class="sxs-lookup"><span data-stu-id="704d7-113">This attribute is required.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="704d7-114">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="704d7-114">Child elements</span></span>

<span data-ttu-id="704d7-115">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="704d7-115">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="704d7-116">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="704d7-116">Parent elements</span></span>

|<span data-ttu-id="704d7-117">**Element**</span><span class="sxs-lookup"><span data-stu-id="704d7-117">**Element**</span></span>|<span data-ttu-id="704d7-118">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="704d7-118">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="704d7-119">Acción (ProtectionRuleActionType)</span><span class="sxs-lookup"><span data-stu-id="704d7-119">Action (ProtectionRuleActionType)</span></span>](action-protectionruleactiontype.md) <br/> |<span data-ttu-id="704d7-120">Identifica la acción que se debe ejecutar si coincide con la parte de la condición de la regla.</span><span class="sxs-lookup"><span data-stu-id="704d7-120">Identifies what action must be executed if the condition part of the rule matches.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="704d7-121">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="704d7-121">Text value</span></span>

<span data-ttu-id="704d7-122">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="704d7-122">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="704d7-123">Comentarios</span><span class="sxs-lookup"><span data-stu-id="704d7-123">Remarks</span></span>

<span data-ttu-id="704d7-124">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="704d7-124">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="704d7-125">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="704d7-125">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="704d7-126">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="704d7-126">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="704d7-127">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="704d7-127">Schema Name</span></span>  <br/> |<span data-ttu-id="704d7-128">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="704d7-128">Types schema</span></span>  <br/> |
|<span data-ttu-id="704d7-129">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="704d7-129">Validation File</span></span>  <br/> |<span data-ttu-id="704d7-130">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="704d7-130">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="704d7-131">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="704d7-131">Can be Empty</span></span>  <br/> |<span data-ttu-id="704d7-132">False</span><span class="sxs-lookup"><span data-stu-id="704d7-132">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="704d7-133">Vea también</span><span class="sxs-lookup"><span data-stu-id="704d7-133">See also</span></span>

- [<span data-ttu-id="704d7-134">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="704d7-134">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
