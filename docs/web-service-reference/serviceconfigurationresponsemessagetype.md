---
title: ServiceConfigurationResponseMessageType
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ServiceConfigurationResponseMessageType
api_type:
- schema
ms.assetid: ccfb0578-c648-44c2-ac4d-7620d881363e
description: El elemento ServiceConfigurationResponseMessageType contiene la configuración del servicio.
ms.openlocfilehash: fb7841f346083017319cece4479fea8bbfb6de17
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837393"
---
# <a name="serviceconfigurationresponsemessagetype"></a><span data-ttu-id="2cb35-103">ServiceConfigurationResponseMessageType</span><span class="sxs-lookup"><span data-stu-id="2cb35-103">ServiceConfigurationResponseMessageType</span></span>

<span data-ttu-id="2cb35-104">El elemento **ServiceConfigurationResponseMessageType** contiene la configuración del servicio.</span><span class="sxs-lookup"><span data-stu-id="2cb35-104">The **ServiceConfigurationResponseMessageType** element contains service configuration settings.</span></span> 
  
```XML
<ServiceConfigurationResponseMessageType ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <MailTipsConfiguration/>
   <UnifiedMessagingConfiguration/>
   <ProtectionRulesConfiguration/>
</ServiceConfigurationResponseMessageType>
```

 <span data-ttu-id="2cb35-105">**ServiceConfigurationResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="2cb35-105">**ServiceConfigurationResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="2cb35-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="2cb35-106">Attributes and elements</span></span>

<span data-ttu-id="2cb35-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="2cb35-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="2cb35-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="2cb35-108">Attributes</span></span>

|<span data-ttu-id="2cb35-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="2cb35-109">**Attribute**</span></span>|<span data-ttu-id="2cb35-110">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="2cb35-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="2cb35-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="2cb35-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="2cb35-112">Describe el estado de la respuesta.</span><span class="sxs-lookup"><span data-stu-id="2cb35-112">Describes the status of the response.</span></span><br/><br/> <span data-ttu-id="2cb35-113">Los siguientes valores son válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="2cb35-113">The following values are valid for this attribute:</span></span>  <br/><br/><span data-ttu-id="2cb35-114">-Éxito</span><span class="sxs-lookup"><span data-stu-id="2cb35-114">-  Success</span></span>  <br/><span data-ttu-id="2cb35-115">-Advertencia</span><span class="sxs-lookup"><span data-stu-id="2cb35-115">-  Warning</span></span>  <br/><span data-ttu-id="2cb35-116">-Error</span><span class="sxs-lookup"><span data-stu-id="2cb35-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="2cb35-117">Valores de atributo de ResponseClass</span><span class="sxs-lookup"><span data-stu-id="2cb35-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="2cb35-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="2cb35-118">**Value**</span></span>|<span data-ttu-id="2cb35-119">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="2cb35-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="2cb35-120">**Operación correcta**</span><span class="sxs-lookup"><span data-stu-id="2cb35-120">**Success**</span></span> <br/> |<span data-ttu-id="2cb35-121">Describe una solicitud que se cumplen los requisitos.</span><span class="sxs-lookup"><span data-stu-id="2cb35-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="2cb35-122">**Warning**</span><span class="sxs-lookup"><span data-stu-id="2cb35-122">**Warning**</span></span> <br/> | <span data-ttu-id="2cb35-123">Describe una solicitud que no se procesó.</span><span class="sxs-lookup"><span data-stu-id="2cb35-123">Describes a request that was not processed.</span></span> <span data-ttu-id="2cb35-124">Es posible que se devuelve una advertencia si se produjo un error mientras procesaba un elemento en la solicitud y no se podrían procesar los elementos subsiguientes.</span><span class="sxs-lookup"><span data-stu-id="2cb35-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span> <br/><br/><span data-ttu-id="2cb35-125">Los siguientes son ejemplos de fuentes de advertencias:</span><span class="sxs-lookup"><span data-stu-id="2cb35-125">The following are examples of sources of warnings:</span></span>  <br/><br/><span data-ttu-id="2cb35-126">-El almacén de Exchange está sin conexión durante el proceso por lotes.</span><span class="sxs-lookup"><span data-stu-id="2cb35-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="2cb35-127">-Los servicios de dominio de Active Directory (AD DS) está sin conexión.</span><span class="sxs-lookup"><span data-stu-id="2cb35-127">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="2cb35-128">-Buzones se han movido.</span><span class="sxs-lookup"><span data-stu-id="2cb35-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="2cb35-129">-La base de datos de mensajes (MDB) está sin conexión.</span><span class="sxs-lookup"><span data-stu-id="2cb35-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="2cb35-130">-Una contraseña ha expirado.</span><span class="sxs-lookup"><span data-stu-id="2cb35-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="2cb35-131">-Se superó una cuota.</span><span class="sxs-lookup"><span data-stu-id="2cb35-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="2cb35-132">**Error**</span><span class="sxs-lookup"><span data-stu-id="2cb35-132">**Error**</span></span> <br/> | <span data-ttu-id="2cb35-133">Describe una solicitud que no se cumplen los requisitos.</span><span class="sxs-lookup"><span data-stu-id="2cb35-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="2cb35-134">Los siguientes son ejemplos de orígenes de errores:</span><span class="sxs-lookup"><span data-stu-id="2cb35-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="2cb35-135">-No válida Atributos o elementos</span><span class="sxs-lookup"><span data-stu-id="2cb35-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="2cb35-136">-Los atributos o elementos que están fuera del intervalo</span><span class="sxs-lookup"><span data-stu-id="2cb35-136">-  Attributes or elements that are out of range</span></span>  <br/><span data-ttu-id="2cb35-137">-Una etiqueta desconocida</span><span class="sxs-lookup"><span data-stu-id="2cb35-137">-  An unknown tag</span></span>  <br/><span data-ttu-id="2cb35-138">-Un atributo o elemento no es válido en el contexto</span><span class="sxs-lookup"><span data-stu-id="2cb35-138">-  An attribute or element is not valid in the context</span></span>  <br/><span data-ttu-id="2cb35-139">-Un intento de acceso no autorizado por cualquier cliente</span><span class="sxs-lookup"><span data-stu-id="2cb35-139">-  An unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="2cb35-140">-Un error del lado del servidor en respuesta a una llamada de cliente válida</span><span class="sxs-lookup"><span data-stu-id="2cb35-140">-  A server-side failure in response to a valid client-side call</span></span>  <br/><br/>  <span data-ttu-id="2cb35-141">Puede encontrar información sobre el error en los elementos [ResponseCode](responsecode.md) y [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="2cb35-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="2cb35-142">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="2cb35-142">Child elements</span></span>

|<span data-ttu-id="2cb35-143">**Element**</span><span class="sxs-lookup"><span data-stu-id="2cb35-143">**Element**</span></span>|<span data-ttu-id="2cb35-144">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="2cb35-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2cb35-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="2cb35-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="2cb35-146">Proporciona una descripción de texto del estado de la respuesta.</span><span class="sxs-lookup"><span data-stu-id="2cb35-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="2cb35-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="2cb35-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="2cb35-148">Proporciona un código de error que identifica el error específico que ha encontrado la solicitud.</span><span class="sxs-lookup"><span data-stu-id="2cb35-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="2cb35-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="2cb35-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="2cb35-150">Actualmente no utilizado y reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="2cb35-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="2cb35-151">Este elemento contiene un valor de 0.</span><span class="sxs-lookup"><span data-stu-id="2cb35-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="2cb35-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="2cb35-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="2cb35-153">Proporciona información de la respuesta de error adicionales.</span><span class="sxs-lookup"><span data-stu-id="2cb35-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="2cb35-154">MailTipsConfiguration (MailTipsServiceConfiguration)</span><span class="sxs-lookup"><span data-stu-id="2cb35-154">MailTipsConfiguration (MailTipsServiceConfiguration)</span></span>](mailtipsconfiguration-mailtipsserviceconfiguration.md) <br/> |<span data-ttu-id="2cb35-155">Contiene información de configuración de servicio para el servicio de sugerencias de correo.</span><span class="sxs-lookup"><span data-stu-id="2cb35-155">Contains service configuration information for the mail tips service.</span></span>  <br/> |
|[<span data-ttu-id="2cb35-156">UnifiedMessagingConfiguration</span><span class="sxs-lookup"><span data-stu-id="2cb35-156">UnifiedMessagingConfiguration</span></span>](unifiedmessagingconfiguration.md) <br/> |<span data-ttu-id="2cb35-157">Contiene información de configuración de servicio para el servicio de mensajería unificada.</span><span class="sxs-lookup"><span data-stu-id="2cb35-157">Contains service configuration information for the Unified Messaging service.</span></span>  <br/> |
|[<span data-ttu-id="2cb35-158">ProtectionRulesConfiguration</span><span class="sxs-lookup"><span data-stu-id="2cb35-158">ProtectionRulesConfiguration</span></span>](protectionrulesconfiguration.md) <br/> |<span data-ttu-id="2cb35-159">Contiene información de configuración de servicio para el servicio de protección de las reglas.</span><span class="sxs-lookup"><span data-stu-id="2cb35-159">Contains service configuration information for the protection rules service.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="2cb35-160">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="2cb35-160">Parent elements</span></span>

|<span data-ttu-id="2cb35-161">**Element**</span><span class="sxs-lookup"><span data-stu-id="2cb35-161">**Element**</span></span>|<span data-ttu-id="2cb35-162">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="2cb35-162">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2cb35-163">ResponseMessages (ArrayOfServiceConfigurationResponseMessageType)</span><span class="sxs-lookup"><span data-stu-id="2cb35-163">ResponseMessages (ArrayOfServiceConfigurationResponseMessageType)</span></span>](responsemessages-arrayofserviceconfigurationresponsemessagetype.md) <br/> |<span data-ttu-id="2cb35-164">Contiene una matriz de los mensajes de respuesta de configuración de servicio.</span><span class="sxs-lookup"><span data-stu-id="2cb35-164">Contains an array of service configuration response messages.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="2cb35-165">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="2cb35-165">Text value</span></span>

<span data-ttu-id="2cb35-166">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="2cb35-166">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="2cb35-167">Observaciones</span><span class="sxs-lookup"><span data-stu-id="2cb35-167">Remarks</span></span>

<span data-ttu-id="2cb35-168">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="2cb35-168">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="2cb35-169">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="2cb35-169">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2cb35-170">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="2cb35-170">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="2cb35-171">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="2cb35-171">Schema Name</span></span>  <br/> |<span data-ttu-id="2cb35-172">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="2cb35-172">Messages schema</span></span>  <br/> |
|<span data-ttu-id="2cb35-173">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="2cb35-173">Validation File</span></span>  <br/> |<span data-ttu-id="2cb35-174">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="2cb35-174">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="2cb35-175">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="2cb35-175">Can be Empty</span></span>  <br/> |<span data-ttu-id="2cb35-176">False</span><span class="sxs-lookup"><span data-stu-id="2cb35-176">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="2cb35-177">Ver también</span><span class="sxs-lookup"><span data-stu-id="2cb35-177">See also</span></span>

- [<span data-ttu-id="2cb35-178">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="2cb35-178">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
