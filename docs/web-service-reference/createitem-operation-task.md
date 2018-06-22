---
title: Operación CreateItem (tarea)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- CreateItem
api_type:
- schema
ms.assetid: 12c5da4d-290c-4a8a-a965-0bf5d55c7978
description: La operación CreateItem crea los elementos de tarea en el almacén de Exchange.
ms.openlocfilehash: 5a5203202071ae9391faa9348902424317ee96d1
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19763954"
---
# <a name="createitem-operation-task"></a><span data-ttu-id="f4016-103">Operación CreateItem (tarea)</span><span class="sxs-lookup"><span data-stu-id="f4016-103">CreateItem operation (task)</span></span>

<span data-ttu-id="f4016-104">La operación CreateItem crea los elementos de tarea en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="f4016-104">The CreateItem operation creates task items in the Exchange store.</span></span>
  
## <a name="task-createitem-request"></a><span data-ttu-id="f4016-105">Solicitud de tarea CreateItem</span><span class="sxs-lookup"><span data-stu-id="f4016-105">Task CreateItem Request</span></span>

### <a name="description"></a><span data-ttu-id="f4016-106">Descripción</span><span class="sxs-lookup"><span data-stu-id="f4016-106">Description</span></span>

<span data-ttu-id="f4016-107">El siguiente ejemplo de una solicitud CreateItem muestra cómo crear un elemento de tarea en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="f4016-107">The following example of a CreateItem request shows how to create a task item in a mailbox.</span></span>
  
### <a name="code"></a><span data-ttu-id="f4016-108">Código</span><span class="sxs-lookup"><span data-stu-id="f4016-108">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:xsd="http://www.w3.org/2001/XMLSchema"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Body>
    <CreateItem xmlns="http://schemas.microsoft.com/exchange/services/2006/messages"
                xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
                MessageDisposition="SaveOnly">
      <Items>
        <t:Task>
          <t:Subject>My task</t:Subject>
          <t:DueDate>2006-10-26T21:32:52</t:DueDate>
          <t:Status>NotStarted</t:Status>
        </t:Task>
      </Items>
    </CreateItem>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="f4016-109">Comentarios</span><span class="sxs-lookup"><span data-stu-id="f4016-109">Comments</span></span>

<span data-ttu-id="f4016-110">Las solicitudes para las tareas repetitivas se modificarán cuando se reciben por el equipo que ejecuta Microsoft Exchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="f4016-110">Requests for recurring tasks are altered when they are received by the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span> <span data-ttu-id="f4016-111">Se producen los siguientes cambios:</span><span class="sxs-lookup"><span data-stu-id="f4016-111">The following changes occur:</span></span>
  
- <span data-ttu-id="f4016-112">Se guarda sólo la fecha para la propiedad [StartDate (periodicidad)](startdate-recurrence.md) del intervalo de periodicidad de la tarea.</span><span class="sxs-lookup"><span data-stu-id="f4016-112">Only the date is saved for the [StartDate (Recurrence)](startdate-recurrence.md) property of the recurrence range of the task.</span></span> <span data-ttu-id="f4016-113">El elemento de tiempo se trunca.</span><span class="sxs-lookup"><span data-stu-id="f4016-113">The time part is truncated.</span></span> 
    
- <span data-ttu-id="f4016-114">Se pueden ajustar la propiedad [StartDate (periodicidad)](startdate-recurrence.md) , según el patrón de periodicidad.</span><span class="sxs-lookup"><span data-stu-id="f4016-114">The [StartDate (Recurrence)](startdate-recurrence.md) property may be adjusted, depending on the recurrence pattern.</span></span> <span data-ttu-id="f4016-115">Por ejemplo, si se especifica el patrón de periodicidad como todos los lunes y StartDate está establecida en 26 de octubre de 2006, que es un jueves, StartDate se ajusta a 30 de octubre de 2006, que es el próximo lunes.</span><span class="sxs-lookup"><span data-stu-id="f4016-115">For example, if the recurrence pattern is specified as every Monday and the StartDate is set to October 26, 2006, which is a Thursday, StartDate is adjusted to October 30, 2006, which is the next Monday.</span></span> 
    
- <span data-ttu-id="f4016-116">Si se establece la propiedad [StartDate](startdate.md) de la tarea, se actualiza para que coincida con la [StartDate (periodicidad)](startdate-recurrence.md) del intervalo de periodicidad.</span><span class="sxs-lookup"><span data-stu-id="f4016-116">If the [StartDate](startdate.md) property of the task is set, it is updated to match the [StartDate (Recurrence)](startdate-recurrence.md) of the recurrence range.</span></span> <span data-ttu-id="f4016-117">La propiedad [DueDate](duedate.md) de la tarea también se actualiza según el nuevo [StartDate](startdate.md).</span><span class="sxs-lookup"><span data-stu-id="f4016-117">The [DueDate](duedate.md) property of the task is also updated based on the new [StartDate](startdate.md).</span></span>
    
- <span data-ttu-id="f4016-118">Si no está establecido el [StartDate](startdate.md) , sólo la propiedad [DueDate](duedate.md) se actualiza para que coincida con la [StartDate (periodicidad)](startdate-recurrence.md) del intervalo de periodicidad.</span><span class="sxs-lookup"><span data-stu-id="f4016-118">If the [StartDate](startdate.md) is not set, only the [DueDate](duedate.md) property is updated to match the [StartDate (Recurrence)](startdate-recurrence.md) of the recurrence range.</span></span> 
    
<span data-ttu-id="f4016-119">La siguiente tabla muestran los cambios que realiza el servidor de acceso de cliente a una tarea periódica que tiene un Task.Recurrence.Pattern de todos los lunes.</span><span class="sxs-lookup"><span data-stu-id="f4016-119">The following table shows the changes that the Client Access server makes to a recurring task that has a Task.Recurrence.Pattern of every Monday.</span></span>
  
<span data-ttu-id="f4016-120">**Cambios realizados en una tarea periódica**</span><span class="sxs-lookup"><span data-stu-id="f4016-120">**Changes to a recurring task**</span></span>

|<span data-ttu-id="f4016-121">**Propiedad**</span><span class="sxs-lookup"><span data-stu-id="f4016-121">**Property**</span></span>|<span data-ttu-id="f4016-122">**Valor original**</span><span class="sxs-lookup"><span data-stu-id="f4016-122">**Original Value**</span></span>|<span data-ttu-id="f4016-123">**Valor actualizado**</span><span class="sxs-lookup"><span data-stu-id="f4016-123">**Updated Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="f4016-124">Task.StartDate</span><span class="sxs-lookup"><span data-stu-id="f4016-124">Task.StartDate</span></span>  <br/> |<span data-ttu-id="f4016-125">1 de enero de 2006</span><span class="sxs-lookup"><span data-stu-id="f4016-125">January 1, 2006</span></span>  <br/> |<span data-ttu-id="f4016-126">30 de octubre de 2006</span><span class="sxs-lookup"><span data-stu-id="f4016-126">October 30, 2006</span></span>  <br/> |
|<span data-ttu-id="f4016-127">Task.DueDate</span><span class="sxs-lookup"><span data-stu-id="f4016-127">Task.DueDate</span></span>  <br/> |<span data-ttu-id="f4016-128">3 de enero de 2006</span><span class="sxs-lookup"><span data-stu-id="f4016-128">January 3, 2006</span></span>  <br/> |<span data-ttu-id="f4016-129">1 de noviembre de 2006</span><span class="sxs-lookup"><span data-stu-id="f4016-129">November 1, 2006</span></span>  <br/> |
|<span data-ttu-id="f4016-130">Task.Recurrence.Range.StartDate</span><span class="sxs-lookup"><span data-stu-id="f4016-130">Task.Recurrence.Range.StartDate</span></span>  <br/> |<span data-ttu-id="f4016-131">26 de octubre de 2006</span><span class="sxs-lookup"><span data-stu-id="f4016-131">October 26, 2006</span></span>  <br/> |<span data-ttu-id="f4016-132">30 de octubre de 2006</span><span class="sxs-lookup"><span data-stu-id="f4016-132">October 30, 2006</span></span>  <br/> |
   
<span data-ttu-id="f4016-133">De forma predeterminada, si no se especifica una carpeta de destino, se crean elementos de tarea en la carpeta tareas.</span><span class="sxs-lookup"><span data-stu-id="f4016-133">By default, if a destination folder is not specified, task items are created in the Tasks folder.</span></span>
  
### <a name="request-elements"></a><span data-ttu-id="f4016-134">Elementos de solicitud</span><span class="sxs-lookup"><span data-stu-id="f4016-134">Request elements</span></span>

<span data-ttu-id="f4016-135">En la solicitud se usan los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="f4016-135">The following elements are used in the request:</span></span>
  
- [<span data-ttu-id="f4016-136">CreateItem</span><span class="sxs-lookup"><span data-stu-id="f4016-136">CreateItem</span></span>](createitem.md)
    
- [<span data-ttu-id="f4016-137">Elementos (NonEmptyArrayOfAllItemsType)</span><span class="sxs-lookup"><span data-stu-id="f4016-137">Items (NonEmptyArrayOfAllItemsType)</span></span>](items-nonemptyarrayofallitemstype.md)
    
- [<span data-ttu-id="f4016-138">Tarea</span><span class="sxs-lookup"><span data-stu-id="f4016-138">Task</span></span>](task.md)
    
- [<span data-ttu-id="f4016-139">Subject</span><span class="sxs-lookup"><span data-stu-id="f4016-139">Subject</span></span>](subject.md)
    
- [<span data-ttu-id="f4016-140">DueDate</span><span class="sxs-lookup"><span data-stu-id="f4016-140">DueDate</span></span>](duedate.md)
    
- [<span data-ttu-id="f4016-141">Status</span><span class="sxs-lookup"><span data-stu-id="f4016-141">Status</span></span>](status.md)
    
## <a name="successful-task-createitem-response"></a><span data-ttu-id="f4016-142">Respuesta de CreateItem correcta de la tarea</span><span class="sxs-lookup"><span data-stu-id="f4016-142">Successful Task CreateItem Response</span></span>

### <a name="description"></a><span data-ttu-id="f4016-143">Descripción</span><span class="sxs-lookup"><span data-stu-id="f4016-143">Description</span></span>

<span data-ttu-id="f4016-144">En el ejemplo siguiente se muestra una respuesta correcta a la solicitud CreateItem.</span><span class="sxs-lookup"><span data-stu-id="f4016-144">The following example shows a successful response to the CreateItem request.</span></span>
  
### <a name="code"></a><span data-ttu-id="f4016-145">Código</span><span class="sxs-lookup"><span data-stu-id="f4016-145">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" MinorVersion="0" MajorBuildNumber="653" MinorBuildNumber="0" 
                         xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"/>
  </soap:Header>
  <soap:Body>
    <CreateItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
                        xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
                        xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseMessages>
        <m:CreateItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:Task>
              <t:ItemId Id="AAAtAE=" ChangeKey="EwAAABYA"/>
            </t:Task>
          </m:Items>
        </m:CreateItemResponseMessage>
      </m:ResponseMessages>
    </CreateItemResponse>
  </soap:Body>
</soap:Envelope>
```

### <a name="successful-response-elements"></a><span data-ttu-id="f4016-146">Elementos de respuesta correcta</span><span class="sxs-lookup"><span data-stu-id="f4016-146">Successful response elements</span></span>

<span data-ttu-id="f4016-147">En la respuesta se incluyen los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="f4016-147">The following elements are included in the response:</span></span>
  
- [<span data-ttu-id="f4016-148">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="f4016-148">ServerVersionInfo</span></span>](serverversioninfo.md)
    
- [<span data-ttu-id="f4016-149">CreateItemResponse</span><span class="sxs-lookup"><span data-stu-id="f4016-149">CreateItemResponse</span></span>](createitemresponse.md)
    
- [<span data-ttu-id="f4016-150">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="f4016-150">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="f4016-151">CreateItemResponseMessage</span><span class="sxs-lookup"><span data-stu-id="f4016-151">CreateItemResponseMessage</span></span>](createitemresponsemessage.md)
    
- [<span data-ttu-id="f4016-152">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="f4016-152">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="f4016-153">Elementos (NonEmptyArrayOfAllItemsType)</span><span class="sxs-lookup"><span data-stu-id="f4016-153">Items (NonEmptyArrayOfAllItemsType)</span></span>](items-nonemptyarrayofallitemstype.md)
    
- [<span data-ttu-id="f4016-154">Tarea</span><span class="sxs-lookup"><span data-stu-id="f4016-154">Task</span></span>](task.md)
    
- [<span data-ttu-id="f4016-155">ItemId</span><span class="sxs-lookup"><span data-stu-id="f4016-155">ItemId</span></span>](itemid.md)
    
## <a name="see-also"></a><span data-ttu-id="f4016-156">Ver también</span><span class="sxs-lookup"><span data-stu-id="f4016-156">See also</span></span>



[<span data-ttu-id="f4016-157">Operación CreateItem</span><span class="sxs-lookup"><span data-stu-id="f4016-157">CreateItem operation</span></span>](createitem-operation.md)


[<span data-ttu-id="f4016-158">Creación de tareas</span><span class="sxs-lookup"><span data-stu-id="f4016-158">Creating Tasks</span></span>](http://msdn.microsoft.com/library/0ef97334-e8a0-4f67-a23a-dd9e2bbad49f%28Office.15%29.aspx)
  
[<span data-ttu-id="f4016-159">Actualización de tareas</span><span class="sxs-lookup"><span data-stu-id="f4016-159">Updating Tasks</span></span>](http://msdn.microsoft.com/library/0a1bf360-d40c-4a99-929b-4c73a14394d5%28Office.15%29.aspx)
  
[<span data-ttu-id="f4016-160">Eliminación de tareas</span><span class="sxs-lookup"><span data-stu-id="f4016-160">Deleting Tasks</span></span>](http://msdn.microsoft.com/library/a3d7e25f-8a35-4901-b1d9-d31f418ab340%28Office.15%29.aspx)
