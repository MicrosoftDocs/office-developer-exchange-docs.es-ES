---
title: UpdateInboxRulesResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- UpdateInboxRulesResponse
api_type:
- schema
ms.assetid: 0947b6aa-0d95-421b-aebb-d03021ecc110
description: El elemento UpdateInboxRulesResponse define una respuesta a una solicitud de UpdateInboxRules.
ms.openlocfilehash: cd64e4546f8d9bf573062d9c982477be3fa4d925
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19840834"
---
# <a name="updateinboxrulesresponse"></a><span data-ttu-id="942c1-103">UpdateInboxRulesResponse</span><span class="sxs-lookup"><span data-stu-id="942c1-103">UpdateInboxRulesResponse</span></span>

<span data-ttu-id="942c1-104">El elemento **UpdateInboxRulesResponse** define una respuesta a una solicitud de UpdateInboxRules.</span><span class="sxs-lookup"><span data-stu-id="942c1-104">The **UpdateInboxRulesResponse** element defines a response to an UpdateInboxRules request.</span></span> 
  
```XML
<UpdateInboxRulesResponse>
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <RuleOperationErrors/>
</UpdateInboxRulesResponse>
```

 <span data-ttu-id="942c1-105">**UpdateInboxRulesResponseType**</span><span class="sxs-lookup"><span data-stu-id="942c1-105">**UpdateInboxRulesResponseType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="942c1-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="942c1-106">Attributes and elements</span></span>

<span data-ttu-id="942c1-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="942c1-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="942c1-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="942c1-108">Attributes</span></span>

|<span data-ttu-id="942c1-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="942c1-109">**Attribute**</span></span>|<span data-ttu-id="942c1-110">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="942c1-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="942c1-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="942c1-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="942c1-112">Describe el estado de una respuesta de la [operación de cancelación de suscripción](unsubscribe-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="942c1-112">Describes the status of an [Unsubscribe operation](unsubscribe-operation.md) response.</span></span><br/><br/> <span data-ttu-id="942c1-113">Los siguientes valores son válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="942c1-113">The following values are valid for this attribute:</span></span>  <br/><br/><span data-ttu-id="942c1-114">-Éxito</span><span class="sxs-lookup"><span data-stu-id="942c1-114">-  Success</span></span>  <br/><span data-ttu-id="942c1-115">-Advertencia</span><span class="sxs-lookup"><span data-stu-id="942c1-115">-  Warning</span></span>  <br/><span data-ttu-id="942c1-116">-Error</span><span class="sxs-lookup"><span data-stu-id="942c1-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="942c1-117">Valores de atributo de ResponseClass</span><span class="sxs-lookup"><span data-stu-id="942c1-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="942c1-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="942c1-118">**Value**</span></span>|<span data-ttu-id="942c1-119">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="942c1-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="942c1-120">**Operación correcta**</span><span class="sxs-lookup"><span data-stu-id="942c1-120">**Success**</span></span> <br/> |<span data-ttu-id="942c1-121">Describe una solicitud que se cumplen los requisitos.</span><span class="sxs-lookup"><span data-stu-id="942c1-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="942c1-122">**Warning**</span><span class="sxs-lookup"><span data-stu-id="942c1-122">**Warning**</span></span> <br/> | <span data-ttu-id="942c1-123">Describe una solicitud que no se procesó.</span><span class="sxs-lookup"><span data-stu-id="942c1-123">Describes a request that was not processed.</span></span> <span data-ttu-id="942c1-124">Es posible que se devuelve una advertencia si se produjo un error mientras procesaba un elemento en la solicitud y no se podrían procesar los elementos subsiguientes.</span><span class="sxs-lookup"><span data-stu-id="942c1-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span> <br/><br/><span data-ttu-id="942c1-125">Los siguientes son ejemplos de fuentes de advertencias:</span><span class="sxs-lookup"><span data-stu-id="942c1-125">The following are examples of sources of warnings:</span></span>  <br/><br/><span data-ttu-id="942c1-126">-El almacén de Exchange está sin conexión durante el proceso por lotes.</span><span class="sxs-lookup"><span data-stu-id="942c1-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="942c1-127">-Los servicios de dominio de Active Directory (AD DS) está sin conexión.</span><span class="sxs-lookup"><span data-stu-id="942c1-127">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="942c1-128">-Se mueven los buzones de correo.</span><span class="sxs-lookup"><span data-stu-id="942c1-128">-  Mailboxes are moved.</span></span>  <br/><span data-ttu-id="942c1-129">-La base de datos de mensajes (MDB) está sin conexión.</span><span class="sxs-lookup"><span data-stu-id="942c1-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="942c1-130">-Una contraseña ha expirado.</span><span class="sxs-lookup"><span data-stu-id="942c1-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="942c1-131">-Se ha excedido una cuota.</span><span class="sxs-lookup"><span data-stu-id="942c1-131">-  A quota is exceeded.</span></span>  <br/> |
|<span data-ttu-id="942c1-132">**Error**</span><span class="sxs-lookup"><span data-stu-id="942c1-132">**Error**</span></span> <br/> | <span data-ttu-id="942c1-133">Describe una solicitud que no se cumplen los requisitos.</span><span class="sxs-lookup"><span data-stu-id="942c1-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="942c1-134">Los siguientes son ejemplos de orígenes de errores:</span><span class="sxs-lookup"><span data-stu-id="942c1-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="942c1-135">-No válida Atributos o elementos</span><span class="sxs-lookup"><span data-stu-id="942c1-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="942c1-136">-Los atributos o elementos que están fuera del intervalo</span><span class="sxs-lookup"><span data-stu-id="942c1-136">-  Attributes or elements that are out of range</span></span>  <br/><span data-ttu-id="942c1-137">-Una etiqueta desconocida</span><span class="sxs-lookup"><span data-stu-id="942c1-137">-  An unknown tag</span></span>  <br/><span data-ttu-id="942c1-138">-Un atributo o un elemento que no es válido en el contexto</span><span class="sxs-lookup"><span data-stu-id="942c1-138">-  An attribute or element that is not valid in the context</span></span>  <br/><span data-ttu-id="942c1-139">-Un intento de acceso no autorizado por cualquier cliente</span><span class="sxs-lookup"><span data-stu-id="942c1-139">-  An unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="942c1-140">-Un error del lado del servidor en respuesta a una llamada de cliente válida</span><span class="sxs-lookup"><span data-stu-id="942c1-140">-  A server-side failure in response to a valid client-side call</span></span>  <br/> <br/> <span data-ttu-id="942c1-141">Puede encontrar información sobre el error en los elementos [ResponseCode](responsecode.md) y [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="942c1-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="942c1-142">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="942c1-142">Child elements</span></span>

|<span data-ttu-id="942c1-143">**Element**</span><span class="sxs-lookup"><span data-stu-id="942c1-143">**Element**</span></span>|<span data-ttu-id="942c1-144">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="942c1-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="942c1-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="942c1-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="942c1-146">Proporciona una descripción de texto del estado de la respuesta.</span><span class="sxs-lookup"><span data-stu-id="942c1-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="942c1-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="942c1-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="942c1-148">Proporciona información de estado acerca de la solicitud.</span><span class="sxs-lookup"><span data-stu-id="942c1-148">Provides status information about the request.</span></span>  <br/> |
|[<span data-ttu-id="942c1-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="942c1-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="942c1-150">Actualmente no se utiliza y está reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="942c1-150">Currently unused and is reserved for future use.</span></span> <span data-ttu-id="942c1-151">Contiene un valor de 0.</span><span class="sxs-lookup"><span data-stu-id="942c1-151">It contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="942c1-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="942c1-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="942c1-153">Proporciona información de la respuesta de error adicionales.</span><span class="sxs-lookup"><span data-stu-id="942c1-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="942c1-154">RuleOperationErrors</span><span class="sxs-lookup"><span data-stu-id="942c1-154">RuleOperationErrors</span></span>](ruleoperationerrors.md) <br/> |<span data-ttu-id="942c1-155">Representa una matriz de errores de validación de la regla en cada campo de regla que tiene un error.</span><span class="sxs-lookup"><span data-stu-id="942c1-155">Represents an array of rule validation errors on each rule field that has an error.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="942c1-156">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="942c1-156">Parent elements</span></span>

<span data-ttu-id="942c1-157">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="942c1-157">None.</span></span>
  
## <a name="text-value"></a><span data-ttu-id="942c1-158">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="942c1-158">Text value</span></span>

<span data-ttu-id="942c1-159">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="942c1-159">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="942c1-160">Observaciones</span><span class="sxs-lookup"><span data-stu-id="942c1-160">Remarks</span></span>

<span data-ttu-id="942c1-161">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="942c1-161">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="942c1-162">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="942c1-162">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="942c1-163">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="942c1-163">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="942c1-164">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="942c1-164">Schema name</span></span>  <br/> |<span data-ttu-id="942c1-165">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="942c1-165">Messages schema</span></span>  <br/> |
|<span data-ttu-id="942c1-166">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="942c1-166">Validation file</span></span>  <br/> |<span data-ttu-id="942c1-167">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="942c1-167">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="942c1-168">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="942c1-168">Can be empty</span></span>  <br/> |<span data-ttu-id="942c1-169">False</span><span class="sxs-lookup"><span data-stu-id="942c1-169">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="942c1-170">Ver también</span><span class="sxs-lookup"><span data-stu-id="942c1-170">See also</span></span>

- [<span data-ttu-id="942c1-171">UpdateInboxRules</span><span class="sxs-lookup"><span data-stu-id="942c1-171">UpdateInboxRules</span></span>](updateinboxrules.md)
- [<span data-ttu-id="942c1-172">Operación de UpdateInboxRules</span><span class="sxs-lookup"><span data-stu-id="942c1-172">UpdateInboxRules operation</span></span>](updateinboxrules-operation.md)
- [<span data-ttu-id="942c1-173">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="942c1-173">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
