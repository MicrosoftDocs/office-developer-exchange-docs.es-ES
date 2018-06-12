---
title: UniqueSenders
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- UniqueSenders
api_type:
- schema
ms.assetid: 1f55f2fe-b2f2-4169-83c1-fa5c752bd695
description: El elemento UniqueSenders contiene una lista de todos los remitentes de los elementos de una conversación en la carpeta actual. Este elemento es de sólo lectura.
ms.openlocfilehash: b75846534141e23e6d8158bc36f0ef60bcb1d7ad
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19840777"
---
# <a name="uniquesenders"></a><span data-ttu-id="bbd9d-104">UniqueSenders</span><span class="sxs-lookup"><span data-stu-id="bbd9d-104">UniqueSenders</span></span>

<span data-ttu-id="bbd9d-105">El elemento **UniqueSenders** contiene una lista de todos los remitentes de los elementos de una conversación en la carpeta actual.</span><span class="sxs-lookup"><span data-stu-id="bbd9d-105">The **UniqueSenders** element contains a list of all the senders of conversation items in the current folder.</span></span> <span data-ttu-id="bbd9d-106">Este elemento es de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="bbd9d-106">This element is read-only.</span></span> 
  
[<span data-ttu-id="bbd9d-107">FindConversationResponse</span><span class="sxs-lookup"><span data-stu-id="bbd9d-107">FindConversationResponse</span></span>](findconversationresponse.md)
  
[<span data-ttu-id="bbd9d-108">Conversaciones</span><span class="sxs-lookup"><span data-stu-id="bbd9d-108">Conversations</span></span>](conversations-ex15websvcsotherref.md)
  
[<span data-ttu-id="bbd9d-109">Conversación (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="bbd9d-109">Conversation (ConversationType)</span></span>](conversation-conversationtype.md)
  
[<span data-ttu-id="bbd9d-110">UniqueSenders</span><span class="sxs-lookup"><span data-stu-id="bbd9d-110">UniqueSenders</span></span>](uniquesenders.md)
  
```XML
<UniqueSenders>
   <String/>
</UniqueSenders>
```

 <span data-ttu-id="bbd9d-111">**ArrayOfStringsType**</span><span class="sxs-lookup"><span data-stu-id="bbd9d-111">**ArrayOfStringsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="bbd9d-112">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="bbd9d-112">Attributes and elements</span></span>

<span data-ttu-id="bbd9d-113">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="bbd9d-113">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="bbd9d-114">Atributos</span><span class="sxs-lookup"><span data-stu-id="bbd9d-114">Attributes</span></span>

<span data-ttu-id="bbd9d-115">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="bbd9d-115">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="bbd9d-116">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="bbd9d-116">Child elements</span></span>

|<span data-ttu-id="bbd9d-117">**Element**</span><span class="sxs-lookup"><span data-stu-id="bbd9d-117">**Element**</span></span>|<span data-ttu-id="bbd9d-118">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="bbd9d-118">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="bbd9d-119">String</span><span class="sxs-lookup"><span data-stu-id="bbd9d-119">String</span></span>](string.md) <br/> |<span data-ttu-id="bbd9d-120">Contiene un remitente conversación único.</span><span class="sxs-lookup"><span data-stu-id="bbd9d-120">Contains a single conversation sender.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="bbd9d-121">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="bbd9d-121">Parent elements</span></span>

|<span data-ttu-id="bbd9d-122">**Element**</span><span class="sxs-lookup"><span data-stu-id="bbd9d-122">**Element**</span></span>|<span data-ttu-id="bbd9d-123">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="bbd9d-123">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="bbd9d-124">Conversación (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="bbd9d-124">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="bbd9d-125">Representa una sola conversación.</span><span class="sxs-lookup"><span data-stu-id="bbd9d-125">Represents a single conversation.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="bbd9d-126">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="bbd9d-126">Text value</span></span>

<span data-ttu-id="bbd9d-127">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="bbd9d-127">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="bbd9d-128">Observaciones</span><span class="sxs-lookup"><span data-stu-id="bbd9d-128">Remarks</span></span>

<span data-ttu-id="bbd9d-129">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda Exchange Web Services.This elemento fue introdujo en Exchange Server 2010 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="bbd9d-129">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).</span></span>
  
## <a name="element-information"></a><span data-ttu-id="bbd9d-130">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="bbd9d-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="bbd9d-131">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="bbd9d-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="bbd9d-132">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="bbd9d-132">Schema name</span></span>  <br/> |<span data-ttu-id="bbd9d-133">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="bbd9d-133">Types schema</span></span>  <br/> |
|<span data-ttu-id="bbd9d-134">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="bbd9d-134">Validation file</span></span>  <br/> |<span data-ttu-id="bbd9d-135">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="bbd9d-135">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="bbd9d-136">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="bbd9d-136">Can be empty</span></span>  <br/> |<span data-ttu-id="bbd9d-137">False</span><span class="sxs-lookup"><span data-stu-id="bbd9d-137">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="bbd9d-138">Ver también</span><span class="sxs-lookup"><span data-stu-id="bbd9d-138">See also</span></span>



[<span data-ttu-id="bbd9d-139">Operación de FindConversation</span><span class="sxs-lookup"><span data-stu-id="bbd9d-139">FindConversation operation</span></span>](findconversation-operation.md)
  
[<span data-ttu-id="bbd9d-140">Operación ApplyConversationAction</span><span class="sxs-lookup"><span data-stu-id="bbd9d-140">ApplyConversationAction operation</span></span>](applyconversationaction-operation.md)


[<span data-ttu-id="bbd9d-141">Conversaciones de EWS</span><span class="sxs-lookup"><span data-stu-id="bbd9d-141">Conversations in EWS</span></span>](http://msdn.microsoft.com/library/91e64629-db6c-4c94-9dcb-d386232e8467%28Office.15%29.aspx)
