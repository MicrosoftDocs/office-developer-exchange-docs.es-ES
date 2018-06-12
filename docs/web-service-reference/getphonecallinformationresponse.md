---
title: GetPhoneCallInformationResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetPhoneCallInformationResponse
api_type:
- schema
ms.assetid: 17f79875-46ec-4289-b974-b3c35af429cd
description: El elemento GetPhoneCallInformationResponse define una respuesta a una única solicitud de GetPhoneCallInformation.
ms.openlocfilehash: 5a03d63198cd00997b8975b18a5ae0eb5fca1af2
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764953"
---
# <a name="getphonecallinformationresponse"></a><span data-ttu-id="9fe8b-103">GetPhoneCallInformationResponse</span><span class="sxs-lookup"><span data-stu-id="9fe8b-103">GetPhoneCallInformationResponse</span></span>

<span data-ttu-id="9fe8b-104">El elemento **GetPhoneCallInformationResponse** define una respuesta a una única solicitud de GetPhoneCallInformation.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-104">The **GetPhoneCallInformationResponse** element defines a response to a single GetPhoneCallInformation request.</span></span> 
  
```xml
<GetPhoneCallInformationResponse ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>   <PhoneCallInformation/>
</GetPhoneCallInformationResponse>
```

 <span data-ttu-id="9fe8b-105">**GetPhoneCallInformationResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-105">**GetPhoneCallInformationResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="9fe8b-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="9fe8b-106">Attributes and elements</span></span>

<span data-ttu-id="9fe8b-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="9fe8b-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="9fe8b-108">Attributes</span></span>

|<span data-ttu-id="9fe8b-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-109">**Attribute**</span></span>|<span data-ttu-id="9fe8b-110">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="9fe8b-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="9fe8b-112">Describe el estado de la respuesta.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-112">Describes the status of the response.</span></span> <br/><br/><span data-ttu-id="9fe8b-113">Los siguientes valores son válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="9fe8b-113">The following values are valid for this attribute:</span></span> <br/> <br/><span data-ttu-id="9fe8b-114">-Éxito</span><span class="sxs-lookup"><span data-stu-id="9fe8b-114">-  Success</span></span>  <br/><span data-ttu-id="9fe8b-115">-Advertencia</span><span class="sxs-lookup"><span data-stu-id="9fe8b-115">-  Warning</span></span>  <br/><span data-ttu-id="9fe8b-116">-Error</span><span class="sxs-lookup"><span data-stu-id="9fe8b-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="9fe8b-117">Valores de atributo de ResponseClass</span><span class="sxs-lookup"><span data-stu-id="9fe8b-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="9fe8b-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-118">**Value**</span></span>|<span data-ttu-id="9fe8b-119">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="9fe8b-120">**Operación correcta**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-120">**Success**</span></span> <br/> |<span data-ttu-id="9fe8b-121">Describe una solicitud que se cumplen los requisitos.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="9fe8b-122">**Warning**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-122">**Warning**</span></span> <br/> | <span data-ttu-id="9fe8b-123">Describe una solicitud que no se procesó.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-123">Describes a request that was not processed.</span></span> <span data-ttu-id="9fe8b-124">Es posible que se devuelve una advertencia si se produjo un error mientras procesaba un elemento en la solicitud y no se podrían procesar los elementos subsiguientes.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span><br/><br/> <span data-ttu-id="9fe8b-125">Los siguientes son ejemplos de fuentes de advertencias:</span><span class="sxs-lookup"><span data-stu-id="9fe8b-125">The following are examples of sources of warnings:</span></span> <br/> <br/><span data-ttu-id="9fe8b-126">-El almacén de Exchange está sin conexión durante el proceso por lotes.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="9fe8b-127">-El servicio de directorio de Active Directory está sin conexión.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-127">-  The Active Directory directory service is offline.</span></span>  <br/><span data-ttu-id="9fe8b-128">-Buzones se han movido.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="9fe8b-129">-La base de datos de mensajes (MDB) está sin conexión.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="9fe8b-130">-Una contraseña ha expirado.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="9fe8b-131">-Se superó una cuota.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="9fe8b-132">**Error**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-132">**Error**</span></span> <br/> | <span data-ttu-id="9fe8b-133">Describe una solicitud que no se cumplen los requisitos.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="9fe8b-134">Los siguientes son ejemplos de orígenes de errores:</span><span class="sxs-lookup"><span data-stu-id="9fe8b-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="9fe8b-135">-No válida Atributos o elementos</span><span class="sxs-lookup"><span data-stu-id="9fe8b-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="9fe8b-136">-Los atributos o elementos fuera del intervalo</span><span class="sxs-lookup"><span data-stu-id="9fe8b-136">-  Attributes or elements out of range</span></span>  <br/><span data-ttu-id="9fe8b-137">-Etiqueta desconocida</span><span class="sxs-lookup"><span data-stu-id="9fe8b-137">-  Unknown tag</span></span>  <br/><span data-ttu-id="9fe8b-138">-De atributo o elemento no es válido en el contexto</span><span class="sxs-lookup"><span data-stu-id="9fe8b-138">-  Attribute or element not valid in the context</span></span>  <br/><span data-ttu-id="9fe8b-139">-Intento de acceso no autorizado por parte de cualquier cliente</span><span class="sxs-lookup"><span data-stu-id="9fe8b-139">-  Unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="9fe8b-140">-Error server-side en respuesta a una llamada de cliente válida</span><span class="sxs-lookup"><span data-stu-id="9fe8b-140">-  Server-side failure in response to a valid client-side call</span></span>  <br/><br/>  <span data-ttu-id="9fe8b-141">Puede encontrar información sobre el error en los elementos [ResponseCode](responsecode.md) y [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="9fe8b-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="9fe8b-142">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="9fe8b-142">Child elements</span></span>

|<span data-ttu-id="9fe8b-143">**Element**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-143">**Element**</span></span>|<span data-ttu-id="9fe8b-144">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="9fe8b-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="9fe8b-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="9fe8b-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="9fe8b-146">Proporciona una descripción de texto del estado de la respuesta.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="9fe8b-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="9fe8b-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="9fe8b-148">Proporciona un código de error que identifica el error específico que ha encontrado la solicitud.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="9fe8b-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="9fe8b-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="9fe8b-150">Actualmente no utilizado y reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="9fe8b-151">Este elemento contiene un valor de 0.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="9fe8b-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="9fe8b-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="9fe8b-153">Proporciona información de la respuesta de error adicionales.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="9fe8b-154">PhoneCallInformation</span><span class="sxs-lookup"><span data-stu-id="9fe8b-154">PhoneCallInformation</span></span>](phonecallinformation.md) <br/> |<span data-ttu-id="9fe8b-155">Especifica la información de estado para una llamada de teléfono.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-155">Specifies the state information for a phone call.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="9fe8b-156">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="9fe8b-156">Parent elements</span></span>

<span data-ttu-id="9fe8b-157">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-157">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="9fe8b-158">Observaciones</span><span class="sxs-lookup"><span data-stu-id="9fe8b-158">Remarks</span></span>

<span data-ttu-id="9fe8b-159">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que ejecuta Exchange Server con la función de servidor de acceso de cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="9fe8b-159">The schema that describes this element is located in the EWS virtual directory of the computer that is running Exchange Server with the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="9fe8b-160">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="9fe8b-160">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="9fe8b-161">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="9fe8b-161">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="9fe8b-162">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="9fe8b-162">Schema Name</span></span>  <br/> |<span data-ttu-id="9fe8b-163">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="9fe8b-163">Messages schema</span></span>  <br/> |
|<span data-ttu-id="9fe8b-164">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="9fe8b-164">Validation File</span></span>  <br/> |<span data-ttu-id="9fe8b-165">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="9fe8b-165">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="9fe8b-166">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="9fe8b-166">Can be Empty</span></span>  <br/> |<span data-ttu-id="9fe8b-167">False</span><span class="sxs-lookup"><span data-stu-id="9fe8b-167">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="9fe8b-168">Ver también</span><span class="sxs-lookup"><span data-stu-id="9fe8b-168">See also</span></span>

- [<span data-ttu-id="9fe8b-169">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="9fe8b-169">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
