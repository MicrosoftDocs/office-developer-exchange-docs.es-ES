---
title: ArchiveItemResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 2ac58d6f-e019-4352-b82f-8ac67a171e63
description: El elemento ArchiveItemResponseMessage especifica el mensaje de respuesta a una solicitud de ArchiveItem.
ms.openlocfilehash: a7832e2cb4ec91a0871de5979fd1b418c0626aa6
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/25/2018
ms.locfileid: "19763550"
---
# <a name="archiveitemresponsemessage"></a><span data-ttu-id="2f960-103">ArchiveItemResponseMessage</span><span class="sxs-lookup"><span data-stu-id="2f960-103">ArchiveItemResponseMessage</span></span>

<span data-ttu-id="2f960-104">El elemento **ArchiveItemResponseMessage** especifica el mensaje de respuesta a una solicitud de **ArchiveItem** .</span><span class="sxs-lookup"><span data-stu-id="2f960-104">The **ArchiveItemResponseMessage** element specifies the response message to an **ArchiveItem** request.</span></span> 
  
```XML
<ArchiveItemResponseMessage ResponseClass="">
    <MessageText></MessageText>
    <ResponseCode></ResponseCode>
    <DescriptiveLinkKey></DescriptiveLinkKey>
    <MessageXml></MessageXml>
    <Items></Items>
</ArchiveItemResponseMessage>
```

 <span data-ttu-id="2f960-105">**ItemInfoResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="2f960-105">**ItemInfoResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="2f960-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="2f960-106">Attributes and elements</span></span>

<span data-ttu-id="2f960-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="2f960-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="2f960-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="2f960-108">Attributes</span></span>

|<span data-ttu-id="2f960-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="2f960-109">**Attribute**</span></span>|<span data-ttu-id="2f960-110">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="2f960-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="2f960-111">ResponseClass</span><span class="sxs-lookup"><span data-stu-id="2f960-111">ResponseClass</span></span>  <br/> |<span data-ttu-id="2f960-112">Indica la clase de la respuesta.</span><span class="sxs-lookup"><span data-stu-id="2f960-112">Indicates the class of the response.</span></span>  <br/> |
   
#### <a name="responseclass"></a><span data-ttu-id="2f960-113">ResponseClass</span><span class="sxs-lookup"><span data-stu-id="2f960-113">ResponseClass</span></span>

|<span data-ttu-id="2f960-114">**Valor**</span><span class="sxs-lookup"><span data-stu-id="2f960-114">**Value**</span></span>|<span data-ttu-id="2f960-115">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="2f960-115">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="2f960-116">Correcto</span><span class="sxs-lookup"><span data-stu-id="2f960-116">Success</span></span>  <br/> |<span data-ttu-id="2f960-117">Indica éxito.</span><span class="sxs-lookup"><span data-stu-id="2f960-117">Indicates success.</span></span>  <br/> |
|<span data-ttu-id="2f960-118">Advertencia</span><span class="sxs-lookup"><span data-stu-id="2f960-118">Warning</span></span>  <br/> |<span data-ttu-id="2f960-119">Indica una advertencia.</span><span class="sxs-lookup"><span data-stu-id="2f960-119">Indicates a warning.</span></span>  <br/> |
|<span data-ttu-id="2f960-120">Error</span><span class="sxs-lookup"><span data-stu-id="2f960-120">Error</span></span>  <br/> |<span data-ttu-id="2f960-121">Indica un error.</span><span class="sxs-lookup"><span data-stu-id="2f960-121">Indicates an error.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="2f960-122">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="2f960-122">Child elements</span></span>

|<span data-ttu-id="2f960-123">**Element**</span><span class="sxs-lookup"><span data-stu-id="2f960-123">**Element**</span></span>|<span data-ttu-id="2f960-124">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="2f960-124">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2f960-125">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="2f960-125">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="2f960-126">Actualmente no utilizado y reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="2f960-126">Currently unused and reserved for future use.</span></span>  <br/> |
|[<span data-ttu-id="2f960-127">Items</span><span class="sxs-lookup"><span data-stu-id="2f960-127">Items</span></span>](items.md) <br/> |<span data-ttu-id="2f960-128">Contiene una matriz de elementos.</span><span class="sxs-lookup"><span data-stu-id="2f960-128">Contains an array of items.</span></span>  <br/> |
|[<span data-ttu-id="2f960-129">MessageText</span><span class="sxs-lookup"><span data-stu-id="2f960-129">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="2f960-130">Proporciona una descripción de texto del estado de la respuesta.</span><span class="sxs-lookup"><span data-stu-id="2f960-130">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="2f960-131">MessageXml</span><span class="sxs-lookup"><span data-stu-id="2f960-131">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="2f960-132">Proporciona información de la respuesta de error adicionales.</span><span class="sxs-lookup"><span data-stu-id="2f960-132">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="2f960-133">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="2f960-133">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="2f960-134">Proporciona información de estado acerca de la solicitud.</span><span class="sxs-lookup"><span data-stu-id="2f960-134">Provides status information about the request.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="2f960-135">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="2f960-135">Parent elements</span></span>

|<span data-ttu-id="2f960-136">**Element**</span><span class="sxs-lookup"><span data-stu-id="2f960-136">**Element**</span></span>|<span data-ttu-id="2f960-137">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="2f960-137">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2f960-138">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="2f960-138">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="2f960-139">Contiene los mensajes de respuesta para una solicitud de servicios Web de Exchange.</span><span class="sxs-lookup"><span data-stu-id="2f960-139">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="2f960-140">Comentarios</span><span class="sxs-lookup"><span data-stu-id="2f960-140">Remarks</span></span>

<span data-ttu-id="2f960-141">Este elemento se introdujo en Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="2f960-141">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="2f960-142">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="2f960-142">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="2f960-143">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="2f960-143">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2f960-144">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="2f960-144">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="2f960-145">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="2f960-145">Schema Name</span></span>  <br/> |<span data-ttu-id="2f960-146">Esquema de mensaje</span><span class="sxs-lookup"><span data-stu-id="2f960-146">Message schema</span></span>  <br/> |
|<span data-ttu-id="2f960-147">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="2f960-147">Validation File</span></span>  <br/> |<span data-ttu-id="2f960-148">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="2f960-148">messages.xsd</span></span>  <br/> |
|<span data-ttu-id="2f960-149">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="2f960-149">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="2f960-150">Vea también</span><span class="sxs-lookup"><span data-stu-id="2f960-150">See also</span></span>

- [<span data-ttu-id="2f960-151">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="2f960-151">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
