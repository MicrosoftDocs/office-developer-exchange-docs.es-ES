---
title: ItemIds
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ItemIds
api_type:
- schema
ms.assetid: 6b82122b-5544-4adf-91b7-ef2db7d5046f
description: El elemento de ItemId contiene las identidades únicas de los elementos, elementos de aparición y elementos maestros periódicos que se usan para eliminar, enviar, obtener, mover o copiar elementos en el almacén de Exchange.
ms.openlocfilehash: 1bd4d6f4593a7c3b418561269d8b29707cc6030c
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836155"
---
# <a name="itemids"></a><span data-ttu-id="c1864-103">ItemIds</span><span class="sxs-lookup"><span data-stu-id="c1864-103">ItemIds</span></span>
  
<span data-ttu-id="c1864-104">El elemento de **ItemID** contiene las identidades únicas de los elementos, elementos de aparición y elementos maestros periódicos que se usan para eliminar, enviar, obtener, mover o copiar elementos en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="c1864-104">The **ItemIds** element contains the unique identities of items, occurrence items, and recurring master items that are used to delete, send, get, move, or copy items in the Exchange store.</span></span>
  
```xml
<ItemIds>
   <ItemId/>
   <OccurrenceItemId/>
   <RecurringMasterItemId/>
</ItemIds>
```

<span data-ttu-id="c1864-105">**NonEmptyArrayOfBaseItemIdsType**</span><span class="sxs-lookup"><span data-stu-id="c1864-105">**NonEmptyArrayOfBaseItemIdsType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="c1864-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="c1864-106">Attributes and elements</span></span>

<span data-ttu-id="c1864-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="c1864-107">The following sections describe attributes, child elements, and parent elements.</span></span> 
  
### <a name="attributes"></a><span data-ttu-id="c1864-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="c1864-108">Attributes</span></span>

<span data-ttu-id="c1864-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="c1864-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="c1864-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="c1864-110">Child elements</span></span>

|<span data-ttu-id="c1864-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="c1864-111">**Element**</span></span>|<span data-ttu-id="c1864-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="c1864-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c1864-113">ItemId</span><span class="sxs-lookup"><span data-stu-id="c1864-113">ItemId</span></span>](itemid.md) <br/> |<span data-ttu-id="c1864-114">Contiene el único identificador y cambiar la clave de un elemento en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="c1864-114">Contains the unique identifier and change key of an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="c1864-115">OccurrenceItemId</span><span class="sxs-lookup"><span data-stu-id="c1864-115">OccurrenceItemId</span></span>](occurrenceitemid.md) <br/> |<span data-ttu-id="c1864-116">Identifica una sola aparición de un elemento periódico.</span><span class="sxs-lookup"><span data-stu-id="c1864-116">Identifies a single occurrence of a recurring item.</span></span>  <br/> |
|[<span data-ttu-id="c1864-117">RecurringMasterItemId</span><span class="sxs-lookup"><span data-stu-id="c1864-117">RecurringMasterItemId</span></span>](recurringmasteritemid.md) <br/> |<span data-ttu-id="c1864-118">Identifica un elemento de patrón de periodicidad mediante la identificación de uno de los identificadores de los elementos de su aparición relacionados.</span><span class="sxs-lookup"><span data-stu-id="c1864-118">Identifies a recurrence master item by identifying one of its related occurrence items' identifiers.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="c1864-119">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="c1864-119">Parent elements</span></span>

|<span data-ttu-id="c1864-120">**Element**</span><span class="sxs-lookup"><span data-stu-id="c1864-120">**Element**</span></span>|<span data-ttu-id="c1864-121">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="c1864-121">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c1864-122">Conversación (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="c1864-122">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="c1864-123">Representa una sola conversación.</span><span class="sxs-lookup"><span data-stu-id="c1864-123">Represents a single conversation.</span></span>  <br/> |
|[<span data-ttu-id="c1864-124">DeleteItem</span><span class="sxs-lookup"><span data-stu-id="c1864-124">DeleteItem</span></span>](deleteitem.md) <br/> |<span data-ttu-id="c1864-125">Define una solicitud para eliminar los elementos en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="c1864-125">Defines a request to delete items in the Exchange store.</span></span>  <br/> <span data-ttu-id="c1864-126">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="c1864-126">The following is the XPath expression to this element:</span></span>  <br/>  `/DeleteItem` <br/> |
|[<span data-ttu-id="c1864-127">SendItem</span><span class="sxs-lookup"><span data-stu-id="c1864-127">SendItem</span></span>](senditem.md) <br/> |<span data-ttu-id="c1864-128">El elemento raíz que define una solicitud de envío de elementos en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="c1864-128">The root element that defines a request to send items in the Exchange store.</span></span>  <br/> <span data-ttu-id="c1864-129">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="c1864-129">The following is the XPath expression to this element:</span></span>  <br/>  `/SendItem` <br/> |
|[<span data-ttu-id="c1864-130">GetItem</span><span class="sxs-lookup"><span data-stu-id="c1864-130">GetItem</span></span>](getitem.md) <br/> |<span data-ttu-id="c1864-131">Define una solicitud para obtener los elementos desde el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="c1864-131">Defines a request to get items from the Exchange store.</span></span>  <br/> <span data-ttu-id="c1864-132">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="c1864-132">The following is the XPath expression to this element:</span></span>  <br/>  `/GetItem` <br/> |
|[<span data-ttu-id="c1864-133">MoveItem</span><span class="sxs-lookup"><span data-stu-id="c1864-133">MoveItem</span></span>](moveitem.md) <br/> |<span data-ttu-id="c1864-134">Define una solicitud para mover los elementos en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="c1864-134">Defines a request to move items in the Exchange store.</span></span>  <br/> <span data-ttu-id="c1864-135">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="c1864-135">The following is the XPath expression to this element:</span></span>  <br/>  `/MoveItem` <br/> |
|[<span data-ttu-id="c1864-136">CopyItem</span><span class="sxs-lookup"><span data-stu-id="c1864-136">CopyItem</span></span>](copyitem.md) <br/> |<span data-ttu-id="c1864-137">Define una solicitud para copiar elementos en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="c1864-137">Defines a request to copy items in the Exchange store.</span></span>  <br/> <span data-ttu-id="c1864-138">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="c1864-138">The following is the XPath expression to this element:</span></span>  <br/>  `/CopyItem` <br/> |
   
## <a name="remarks"></a><span data-ttu-id="c1864-139">Notas</span><span class="sxs-lookup"><span data-stu-id="c1864-139">Remarks</span></span>

<span data-ttu-id="c1864-140">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="c1864-140">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="c1864-141">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="c1864-141">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c1864-142">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="c1864-142">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="c1864-143">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="c1864-143">Schema Name</span></span>  <br/> |<span data-ttu-id="c1864-144">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="c1864-144">Messages schema</span></span>  <br/> |
|<span data-ttu-id="c1864-145">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="c1864-145">Validation File</span></span>  <br/> |<span data-ttu-id="c1864-146">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="c1864-146">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="c1864-147">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="c1864-147">Can be Empty</span></span>  <br/> |<span data-ttu-id="c1864-148">False</span><span class="sxs-lookup"><span data-stu-id="c1864-148">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="c1864-149">Ver también</span><span class="sxs-lookup"><span data-stu-id="c1864-149">See also</span></span>

- [<span data-ttu-id="c1864-150">Operación DeleteItem</span><span class="sxs-lookup"><span data-stu-id="c1864-150">DeleteItem operation</span></span>](deleteitem-operation.md)
- [<span data-ttu-id="c1864-151">Operación SendItem</span><span class="sxs-lookup"><span data-stu-id="c1864-151">SendItem operation</span></span>](senditem-operation.md) 
- [<span data-ttu-id="c1864-152">Operación GetItem</span><span class="sxs-lookup"><span data-stu-id="c1864-152">GetItem operation</span></span>](getitem-operation.md)
- [<span data-ttu-id="c1864-153">Operación MoveItem</span><span class="sxs-lookup"><span data-stu-id="c1864-153">MoveItem operation</span></span>](moveitem-operation.md)
- [<span data-ttu-id="c1864-154">Operación CopyItem</span><span class="sxs-lookup"><span data-stu-id="c1864-154">CopyItem operation</span></span>](copyitem-operation.md)
- [<span data-ttu-id="c1864-155">Operación de FindConversation</span><span class="sxs-lookup"><span data-stu-id="c1864-155">FindConversation operation</span></span>](findconversation-operation.md)
