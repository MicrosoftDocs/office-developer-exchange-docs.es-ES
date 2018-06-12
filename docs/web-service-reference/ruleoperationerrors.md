---
title: RuleOperationErrors
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: f15c7b9e-a670-4a11-bb62-2a298c91f142
description: El elemento RuleOperationErrors representa una matriz de errores de validación de la regla en cada campo de regla que tiene un error.
ms.openlocfilehash: 7dc85b5cd84af5ad00511a3df2b31ee3541e12b7
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837261"
---
# <a name="ruleoperationerrors"></a><span data-ttu-id="96cf2-103">RuleOperationErrors</span><span class="sxs-lookup"><span data-stu-id="96cf2-103">RuleOperationErrors</span></span>

<span data-ttu-id="96cf2-104">El elemento **RuleOperationErrors** representa una matriz de errores de validación de la regla en cada campo de regla que tiene un error.</span><span class="sxs-lookup"><span data-stu-id="96cf2-104">The **RuleOperationErrors** element represents an array of rule validation errors on each rule field that has an error.</span></span> 
  
[<span data-ttu-id="96cf2-105">UpdateInboxRulesResponse</span><span class="sxs-lookup"><span data-stu-id="96cf2-105">UpdateInboxRulesResponse</span></span>](updateinboxrulesresponse.md)
  
[<span data-ttu-id="96cf2-106">RuleOperationErrors</span><span class="sxs-lookup"><span data-stu-id="96cf2-106">RuleOperationErrors</span></span>](ruleoperationerrors.md)
  
```XML
<RuleOperationErrors>
    <RuleOperationError>
</RuleOperationErrors>
```

 <span data-ttu-id="96cf2-107">**ArrayOfRuleOperationErrorsType**</span><span class="sxs-lookup"><span data-stu-id="96cf2-107">**ArrayOfRuleOperationErrorsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="96cf2-108">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="96cf2-108">Attributes and elements</span></span>

<span data-ttu-id="96cf2-109">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="96cf2-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="96cf2-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="96cf2-110">Attributes</span></span>

<span data-ttu-id="96cf2-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="96cf2-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="96cf2-112">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="96cf2-112">Child elements</span></span>

|<span data-ttu-id="96cf2-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="96cf2-113">**Element**</span></span>|<span data-ttu-id="96cf2-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="96cf2-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="96cf2-115">RuleOperationError</span><span class="sxs-lookup"><span data-stu-id="96cf2-115">RuleOperationError</span></span>](ruleoperationerror.md) <br/> |<span data-ttu-id="96cf2-116">Representa un error de la operación de regla.</span><span class="sxs-lookup"><span data-stu-id="96cf2-116">Represents a rule operation error.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="96cf2-117">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="96cf2-117">Parent elements</span></span>

|<span data-ttu-id="96cf2-118">**Element**</span><span class="sxs-lookup"><span data-stu-id="96cf2-118">**Element**</span></span>|<span data-ttu-id="96cf2-119">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="96cf2-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="96cf2-120">UpdateInboxRulesResponse</span><span class="sxs-lookup"><span data-stu-id="96cf2-120">UpdateInboxRulesResponse</span></span>](updateinboxrulesresponse.md) <br/> |<span data-ttu-id="96cf2-121">Define una respuesta a una solicitud de [UpdateInboxRules](updateinboxrules.md) .</span><span class="sxs-lookup"><span data-stu-id="96cf2-121">Defines a response to an [UpdateInboxRules](updateinboxrules.md) request.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="96cf2-122">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="96cf2-122">Text value</span></span>

<span data-ttu-id="96cf2-123">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="96cf2-123">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="96cf2-124">Observaciones</span><span class="sxs-lookup"><span data-stu-id="96cf2-124">Remarks</span></span>

<span data-ttu-id="96cf2-125">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="96cf2-125">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="96cf2-126">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="96cf2-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="96cf2-127">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="96cf2-127">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="96cf2-128">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="96cf2-128">Schema name</span></span>  <br/> |<span data-ttu-id="96cf2-129">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="96cf2-129">Messages schema</span></span>  <br/> |
|<span data-ttu-id="96cf2-130">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="96cf2-130">Validation file</span></span>  <br/> |<span data-ttu-id="96cf2-131">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="96cf2-131">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="96cf2-132">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="96cf2-132">Can be empty</span></span>  <br/> |<span data-ttu-id="96cf2-133">Verdadero</span><span class="sxs-lookup"><span data-stu-id="96cf2-133">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="96cf2-134">Ver también</span><span class="sxs-lookup"><span data-stu-id="96cf2-134">See also</span></span>



[<span data-ttu-id="96cf2-135">UpdateInboxRules</span><span class="sxs-lookup"><span data-stu-id="96cf2-135">UpdateInboxRules</span></span>](updateinboxrules.md)


- [<span data-ttu-id="96cf2-136">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="96cf2-136">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
