---
title: GlobalFlagStatus
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GlobalFlagStatus
api_type:
- schema
ms.assetid: 3ba300f3-3355-4cab-9e77-0dcc2902e712
description: El elemento GlobalFlagStatus contiene el estado del indicador agregada para todos los elementos de la conversación en un buzón de correo.
ms.openlocfilehash: 0c560c065463b8b619f96ecef73d1120b216ca35
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/21/2018
ms.locfileid: "19835713"
---
# <a name="globalflagstatus"></a><span data-ttu-id="e76dd-103">GlobalFlagStatus</span><span class="sxs-lookup"><span data-stu-id="e76dd-103">GlobalFlagStatus</span></span>

<span data-ttu-id="e76dd-104">El elemento **GlobalFlagStatus** contiene el estado del indicador agregada para todos los elementos de la conversación en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="e76dd-104">The **GlobalFlagStatus** element contains the aggregated flag status for all conversation items in a mailbox.</span></span> 
  
[<span data-ttu-id="e76dd-105">FindConversationResponse</span><span class="sxs-lookup"><span data-stu-id="e76dd-105">FindConversationResponse</span></span>](findconversationresponse.md)
  
[<span data-ttu-id="e76dd-106">Conversaciones</span><span class="sxs-lookup"><span data-stu-id="e76dd-106">Conversations</span></span>](conversations-ex15websvcsotherref.md)
  
[<span data-ttu-id="e76dd-107">Conversación (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="e76dd-107">Conversation (ConversationType)</span></span>](conversation-conversationtype.md)
  
[<span data-ttu-id="e76dd-108">GlobalFlagStatus</span><span class="sxs-lookup"><span data-stu-id="e76dd-108">GlobalFlagStatus</span></span>](globalflagstatus.md)
  
```XML
<GlobalFlagStatus> NotFlagged | Flagged | Complete </GlobalFlagStatus>
```

 <span data-ttu-id="e76dd-109">**FlagStatusType**</span><span class="sxs-lookup"><span data-stu-id="e76dd-109">**FlagStatusType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="e76dd-110">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="e76dd-110">Attributes and elements</span></span>

<span data-ttu-id="e76dd-111">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="e76dd-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="e76dd-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="e76dd-112">Attributes</span></span>

<span data-ttu-id="e76dd-113">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="e76dd-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="e76dd-114">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="e76dd-114">Child elements</span></span>

<span data-ttu-id="e76dd-115">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="e76dd-115">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="e76dd-116">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="e76dd-116">Parent elements</span></span>

|<span data-ttu-id="e76dd-117">**Element**</span><span class="sxs-lookup"><span data-stu-id="e76dd-117">**Element**</span></span>|<span data-ttu-id="e76dd-118">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="e76dd-118">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e76dd-119">Conversación (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="e76dd-119">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="e76dd-120">Representa una sola conversación.</span><span class="sxs-lookup"><span data-stu-id="e76dd-120">Represents a single conversation.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="e76dd-121">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="e76dd-121">Text value</span></span>

<span data-ttu-id="e76dd-122">El valor de texto del elemento **GlobalFlagStatus** es el estado del indicador agregados por los elementos de conversación en la carpeta actual.</span><span class="sxs-lookup"><span data-stu-id="e76dd-122">The text value of the **GlobalFlagStatus** element is the aggregated flag status for conversation items in the current folder.</span></span> <span data-ttu-id="e76dd-123">Los siguientes son los valores de texto posibles:</span><span class="sxs-lookup"><span data-stu-id="e76dd-123">The following are the possible text values:</span></span> 
  
- <span data-ttu-id="e76dd-124">**NotFlagged** - indica el estado de marca no.</span><span class="sxs-lookup"><span data-stu-id="e76dd-124">**NotFlagged** - Indicates the not-flagged status.</span></span> 
    
- <span data-ttu-id="e76dd-125">**Marcado** - indica el estado marcado.</span><span class="sxs-lookup"><span data-stu-id="e76dd-125">**Flagged** - Indicates the flagged status.</span></span> 
    
- <span data-ttu-id="e76dd-126">**Completo** - indica el estado del indicador completa.</span><span class="sxs-lookup"><span data-stu-id="e76dd-126">**Complete** - Indicates the complete flag status.</span></span> 
    
## <a name="remarks"></a><span data-ttu-id="e76dd-127">Comentarios</span><span class="sxs-lookup"><span data-stu-id="e76dd-127">Remarks</span></span>

<span data-ttu-id="e76dd-128">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda Exchange Web Services.This elemento fue introdujo en Exchange Server 2010 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="e76dd-128">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).</span></span>
  
## <a name="element-information"></a><span data-ttu-id="e76dd-129">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="e76dd-129">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="e76dd-130">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="e76dd-130">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="e76dd-131">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="e76dd-131">Schema name</span></span>  <br/> |<span data-ttu-id="e76dd-132">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="e76dd-132">Types schema</span></span>  <br/> |
|<span data-ttu-id="e76dd-133">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="e76dd-133">Validation file</span></span>  <br/> |<span data-ttu-id="e76dd-134">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="e76dd-134">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="e76dd-135">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="e76dd-135">Can be empty</span></span>  <br/> |<span data-ttu-id="e76dd-136">False</span><span class="sxs-lookup"><span data-stu-id="e76dd-136">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="e76dd-137">Vea también</span><span class="sxs-lookup"><span data-stu-id="e76dd-137">See also</span></span>



[<span data-ttu-id="e76dd-138">Operación de FindConversation</span><span class="sxs-lookup"><span data-stu-id="e76dd-138">FindConversation operation</span></span>](findconversation-operation.md)
  
[<span data-ttu-id="e76dd-139">Operación ApplyConversationAction</span><span class="sxs-lookup"><span data-stu-id="e76dd-139">ApplyConversationAction operation</span></span>](applyconversationaction-operation.md)


[<span data-ttu-id="e76dd-140">Conversaciones de EWS</span><span class="sxs-lookup"><span data-stu-id="e76dd-140">Conversations in EWS</span></span>](http://msdn.microsoft.com/library/91e64629-db6c-4c94-9dcb-d386232e8467%28Office.15%29.aspx)
