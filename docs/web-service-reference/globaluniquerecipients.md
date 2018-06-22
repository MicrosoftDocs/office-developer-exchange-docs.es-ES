---
title: GlobalUniqueRecipients
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GlobalUniqueRecipients
api_type:
- schema
ms.assetid: 67379c1c-85d9-4b11-8f17-ad9d24904788
description: El elemento GlobalUniqueRecipients contiene la lista de destinatarios de una conversación agregada a través de un buzón de correo.
ms.openlocfilehash: 5eb6e60d3ece8d8369f4603e36ffaaf72a3e459d
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19835742"
---
# <a name="globaluniquerecipients"></a><span data-ttu-id="353d7-103">GlobalUniqueRecipients</span><span class="sxs-lookup"><span data-stu-id="353d7-103">GlobalUniqueRecipients</span></span>

<span data-ttu-id="353d7-104">El elemento **GlobalUniqueRecipients** contiene la lista de destinatarios de una conversación agregada a través de un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="353d7-104">The **GlobalUniqueRecipients** element contains the recipient list of a conversation aggregated across a mailbox.</span></span> 
  
[<span data-ttu-id="353d7-105">FindConversationResponse</span><span class="sxs-lookup"><span data-stu-id="353d7-105">FindConversationResponse</span></span>](findconversationresponse.md)
  
[<span data-ttu-id="353d7-106">Conversaciones</span><span class="sxs-lookup"><span data-stu-id="353d7-106">Conversations</span></span>](conversations-ex15websvcsotherref.md)
  
[<span data-ttu-id="353d7-107">Conversación (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="353d7-107">Conversation (ConversationType)</span></span>](conversation-conversationtype.md)
  
[<span data-ttu-id="353d7-108">GlobalUniqueRecipients</span><span class="sxs-lookup"><span data-stu-id="353d7-108">GlobalUniqueRecipients</span></span>](globaluniquerecipients.md)
  
```XML
<GlobalUniqueRecipients>
   <String/>
</GlobalUniqueRecipients>
```

 <span data-ttu-id="353d7-109">**ArrayOfStringsType**</span><span class="sxs-lookup"><span data-stu-id="353d7-109">**ArrayOfStringsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="353d7-110">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="353d7-110">Attributes and elements</span></span>

<span data-ttu-id="353d7-111">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="353d7-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="353d7-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="353d7-112">Attributes</span></span>

<span data-ttu-id="353d7-113">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="353d7-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="353d7-114">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="353d7-114">Child elements</span></span>

|<span data-ttu-id="353d7-115">**Element**</span><span class="sxs-lookup"><span data-stu-id="353d7-115">**Element**</span></span>|<span data-ttu-id="353d7-116">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="353d7-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="353d7-117">String</span><span class="sxs-lookup"><span data-stu-id="353d7-117">String</span></span>](string.md) <br/> |<span data-ttu-id="353d7-118">Contiene a un destinatario de la misma conversación.</span><span class="sxs-lookup"><span data-stu-id="353d7-118">Contains a single conversation recipient.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="353d7-119">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="353d7-119">Parent elements</span></span>

|<span data-ttu-id="353d7-120">**Element**</span><span class="sxs-lookup"><span data-stu-id="353d7-120">**Element**</span></span>|<span data-ttu-id="353d7-121">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="353d7-121">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="353d7-122">Conversación (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="353d7-122">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="353d7-123">Representa una sola conversación.</span><span class="sxs-lookup"><span data-stu-id="353d7-123">Represents a single conversation.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="353d7-124">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="353d7-124">Text value</span></span>

<span data-ttu-id="353d7-125">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="353d7-125">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="353d7-126">Observaciones</span><span class="sxs-lookup"><span data-stu-id="353d7-126">Remarks</span></span>

<span data-ttu-id="353d7-127">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda Exchange Web Services.This elemento fue introdujo en Exchange Server 2010 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="353d7-127">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).</span></span>
  
## <a name="element-information"></a><span data-ttu-id="353d7-128">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="353d7-128">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="353d7-129">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="353d7-129">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="353d7-130">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="353d7-130">Schema name</span></span>  <br/> |<span data-ttu-id="353d7-131">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="353d7-131">Types schema</span></span>  <br/> |
|<span data-ttu-id="353d7-132">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="353d7-132">Validation file</span></span>  <br/> |<span data-ttu-id="353d7-133">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="353d7-133">types.xsd</span></span>  <br/> |
|<span data-ttu-id="353d7-134">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="353d7-134">Can be empty</span></span>  <br/> |<span data-ttu-id="353d7-135">False</span><span class="sxs-lookup"><span data-stu-id="353d7-135">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="353d7-136">Ver también</span><span class="sxs-lookup"><span data-stu-id="353d7-136">See also</span></span>



[<span data-ttu-id="353d7-137">Operación de FindConversation</span><span class="sxs-lookup"><span data-stu-id="353d7-137">FindConversation operation</span></span>](findconversation-operation.md)
  
[<span data-ttu-id="353d7-138">Operación ApplyConversationAction</span><span class="sxs-lookup"><span data-stu-id="353d7-138">ApplyConversationAction operation</span></span>](applyconversationaction-operation.md)


[<span data-ttu-id="353d7-139">Conversaciones de EWS</span><span class="sxs-lookup"><span data-stu-id="353d7-139">Conversations in EWS</span></span>](http://msdn.microsoft.com/library/91e64629-db6c-4c94-9dcb-d386232e8467%28Office.15%29.aspx)
