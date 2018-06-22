---
title: Operación GetStreamingEvents
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetStreamingEvents
api_type:
- schema
ms.assetid: 8da95423-72bc-4034-90a8-162eedcd059b
description: Busque información sobre la EWS GetStreamingEvents operación.
ms.openlocfilehash: 0e93be7b14cb1ca6a2a9821b016f7bdc0e8d7772
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19835673"
---
# <a name="getstreamingevents-operation"></a><span data-ttu-id="9341c-103">Operación GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="9341c-103">GetStreamingEvents operation</span></span>

<span data-ttu-id="9341c-104">Obtenga información acerca de la operación de EWS **GetStreamingEvents** .</span><span class="sxs-lookup"><span data-stu-id="9341c-104">Find information about the **GetStreamingEvents** EWS operation.</span></span> 
  
<span data-ttu-id="9341c-105">La operación de **GetStreamingEvents** se usa en transmisión por secuencias de los clientes de suscripción a notificaciones de solicitud desde el servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="9341c-105">The **GetStreamingEvents** operation is used by streaming subscription clients to request notifications from the Client Access server.</span></span> <span data-ttu-id="9341c-106">La respuesta de **GetStreamingEvents** devuelve una matriz de elementos y eventos que se han producido en un buzón de correo desde la última vez la notificación.</span><span class="sxs-lookup"><span data-stu-id="9341c-106">The **GetStreamingEvents** response returns an array of items and events that have occurred in a mailbox since the last the notification.</span></span> 
  
## <a name="getstreamingevents-request-example"></a><span data-ttu-id="9341c-107">Ejemplo de solicitud de GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="9341c-107">GetStreamingEvents request example</span></span>

### <a name="description"></a><span data-ttu-id="9341c-108">Descripción</span><span class="sxs-lookup"><span data-stu-id="9341c-108">Description</span></span>

<span data-ttu-id="9341c-109">El siguiente ejemplo de una operación de **GetStreamingEvents** muestra cómo solicitar los eventos y los elementos que están asociados con una suscripción que se identifica con el identificador de suscripción.</span><span class="sxs-lookup"><span data-stu-id="9341c-109">The following example of a **GetStreamingEvents** operation shows how to request the events and items that are associated with a subscription that is identified by the subscription identifier.</span></span> 
  
### <a name="code"></a><span data-ttu-id="9341c-110">Código</span><span class="sxs-lookup"><span data-stu-id="9341c-110">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
  xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
  xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages">
  <soap:Body>
    <GetStreamingEvents xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <SubscriptionId>f6bc657d-dde1-4f94-952d-143b95d6483d</SubscriptionId>
      <ConnectionTimeout>30</ConnectionTimeout>
    </GetStreamingEvents>
  </soap:Body>
</soap:Envelope>
```

### <a name="getstreamingevents-request-elements"></a><span data-ttu-id="9341c-111">Elementos de solicitud de GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="9341c-111">GetStreamingEvents request elements</span></span>

<span data-ttu-id="9341c-112">En la solicitud se usan los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="9341c-112">The following elements are used in the request:</span></span>
  
- [<span data-ttu-id="9341c-113">GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="9341c-113">GetStreamingEvents</span></span>](getstreamingevents.md)
    
- [<span data-ttu-id="9341c-114">SubscriptionId (GetStreamingEvents)</span><span class="sxs-lookup"><span data-stu-id="9341c-114">SubscriptionId (GetStreamingEvents)</span></span>](subscriptionid-getstreamingevents.md)
    
- [<span data-ttu-id="9341c-115">ConnectionTimeout</span><span class="sxs-lookup"><span data-stu-id="9341c-115">ConnectionTimeout</span></span>](connectiontimeout.md)
    
## <a name="successful-getstreamingevents-response-example"></a><span data-ttu-id="9341c-116">Ejemplo de respuesta correcta de GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="9341c-116">Successful GetStreamingEvents response example</span></span>

### <a name="description"></a><span data-ttu-id="9341c-117">Descripción</span><span class="sxs-lookup"><span data-stu-id="9341c-117">Description</span></span>

<span data-ttu-id="9341c-118">El siguiente ejemplo de una respuesta **GetStreamingEvents** muestra las notificaciones que se envían al cliente cuando se recibe un nuevo mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="9341c-118">The following example of a **GetStreamingEvents** response shows the notifications that are sent to the client when a new email message is received.</span></span> <span data-ttu-id="9341c-119">Incluye las notificaciones para los siguientes eventos: CreatedEvent, NewMail y ModifiedEvent.</span><span class="sxs-lookup"><span data-stu-id="9341c-119">It includes notifications for the following events: CreatedEvent, NewMail, and ModifiedEvent.</span></span> 
  
### <a name="code"></a><span data-ttu-id="9341c-120">Código</span><span class="sxs-lookup"><span data-stu-id="9341c-120">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8" ?>
<soap:Header xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <ServerVersionInfo xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" MajorVersion="15" MinorVersion="0" MajorBuildNumber="775" MinorBuildNumber="7" Version="V2_4" xmlns="http://schemas.microsoft.com/exchange/services/2006/types" />
</soap:Header>
<soap:Body xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <m:GetStreamingEventsResponse xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages">
    <m:ResponseMessages>
      <m:GetStreamingEventsResponseMessage ResponseClass="Success">
        <m:ResponseCode>NoError</m:ResponseCode>
        <m:Notifications>
          <m:Notification>
            <t:SubscriptionId>f6bc657d-dde1-4f94-952d-143b95d6483d</t:SubscriptionId>
            <t:CreatedEvent>
              <t:TimeStamp>2013-09-16T04:31:29Z</t:TimeStamp>
              <t:ItemId Id="AAMkADkzNjJjODUzLWZhMDMtNDVkMS05ZDdjLWVmMDlkYjQ1Zjc4MwBGAAAAAABSSWVKrmGUTJE+MVIvofglBwDZGACZQpSgSpyNkexYe2b7AAAAAAENAADZGACZQpSgSpyNkexYe2b7AAANGFYwAAA=" ChangeKey="CQAAAA==" />
              <t:ParentFolderId Id="AQMkADkzNjJjODUzLWZhMDMtNDVkMS05ZDdjLWVmMDlkYjQ1Zjc4MwAuAAADUkllSq5hlEyRPjFSL6H4JQEA2RgAmUKUoEqcjZHsWHtm+wAAAgENAAAA" ChangeKey="AQAAAA==" />
            </t:CreatedEvent>
            <t:NewMailEvent>
              <t:TimeStamp>2013-09-16T04:31:29Z</t:TimeStamp>
              <t:ItemId Id="AAMkADkzNjJjODUzLWZhMDMtNDVkMS05ZDdjLWVmMDlkYjQ1Zjc4MwBGAAAAAABSSWVKrmGUTJE+MVIvofglBwDZGACZQpSgSpyNkexYe2b7AAAAAAENAADZGACZQpSgSpyNkexYe2b7AAANGFYwAAA=" ChangeKey="CQAAAA==" />
              <t:ParentFolderId Id="AQMkADkzNjJjODUzLWZhMDMtNDVkMS05ZDdjLWVmMDlkYjQ1Zjc4MwAuAAADUkllSq5hlEyRPjFSL6H4JQEA2RgAmUKUoEqcjZHsWHtm+wAAAgENAAAA" ChangeKey="AQAAAA==" />
            </t:NewMailEvent>
            <t:ModifiedEvent>
              <t:TimeStamp>2013-09-16T04:31:29Z</t:TimeStamp>
              <t:FolderId Id="AQMkADkzNjJjODUzLWZhMDMtNDVkMS05ZDdjLWVmMDlkYjQ1Zjc4MwAuAAADUkllSq5hlEyRPjFSL6H4JQEA2RgAmUKUoEqcjZHsWHtm+wAAAgENAAAA" ChangeKey="AQAAAA==" />
              <t:ParentFolderId Id="AQMkADkzNjJjODUzLWZhMDMtNDVkMS05ZDdjLWVmMDlkYjQ1Zjc4MwAuAAADUkllSq5hlEyRPjFSL6H4JQEA2RgAmUKUoEqcjZHsWHtm+wAAAgEJAAAA" ChangeKey="AQAAAA==" />
              <t:UnreadCount>1</t:UnreadCount>
            </t:ModifiedEvent>
          </m:Notification>
        </m:Notifications>
      </m:GetStreamingEventsResponseMessage>
    </m:ResponseMessages>
  </m:GetStreamingEventsResponse>
</soap:Body>
```

### <a name="getstreamingevents-response-elements"></a><span data-ttu-id="9341c-121">Elementos de respuesta GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="9341c-121">GetStreamingEvents response elements</span></span>

<span data-ttu-id="9341c-122">En la respuesta se usan los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="9341c-122">The following elements are used in the response:</span></span>
  
- [<span data-ttu-id="9341c-123">GetStreamingEventsResponse</span><span class="sxs-lookup"><span data-stu-id="9341c-123">GetStreamingEventsResponse</span></span>](getstreamingeventsresponse.md)
    
- [<span data-ttu-id="9341c-124">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="9341c-124">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="9341c-125">GetStreamingEventsResponseMessage</span><span class="sxs-lookup"><span data-stu-id="9341c-125">GetStreamingEventsResponseMessage</span></span>](getstreamingeventsresponsemessage.md)
    
- [<span data-ttu-id="9341c-126">NotesFolderPermissionLevel</span><span class="sxs-lookup"><span data-stu-id="9341c-126">NotesFolderPermissionLevel</span></span>](notesfolderpermissionlevel.md)
    
- [<span data-ttu-id="9341c-127">Notificación</span><span class="sxs-lookup"><span data-stu-id="9341c-127">Notification</span></span>](notification-ex15websvcsotherref.md)
    
- [<span data-ttu-id="9341c-128">SubscriptionId (GetStreamingEvents)</span><span class="sxs-lookup"><span data-stu-id="9341c-128">SubscriptionId (GetStreamingEvents)</span></span>](subscriptionid-getstreamingevents.md)
    
<span data-ttu-id="9341c-129">Para buscar otras opciones para el mensaje de respuesta de la operación de **GetStreamingEvents** , explore la jerarquía de esquema.</span><span class="sxs-lookup"><span data-stu-id="9341c-129">To find other options for the response message of the **GetStreamingEvents** operation, explore the schema hierarchy.</span></span> <span data-ttu-id="9341c-130">Comenzar en el elemento de [notificación](notification-ex15websvcsotherref.md) .</span><span class="sxs-lookup"><span data-stu-id="9341c-130">Start at the [Notification](notification-ex15websvcsotherref.md) element.</span></span> 
  
## <a name="getstreamingevents-error-response-example"></a><span data-ttu-id="9341c-131">Ejemplo de respuesta de error de GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="9341c-131">GetStreamingEvents error response example</span></span>

### <a name="description"></a><span data-ttu-id="9341c-132">Descripción</span><span class="sxs-lookup"><span data-stu-id="9341c-132">Description</span></span>

<span data-ttu-id="9341c-133">En el ejemplo siguiente se muestra una respuesta de error a una solicitud de **GetStreamingEvents** .</span><span class="sxs-lookup"><span data-stu-id="9341c-133">The following example shows an error response to a **GetStreamingEvents** request.</span></span> 
  
### <a name="code"></a><span data-ttu-id="9341c-134">Código</span><span class="sxs-lookup"><span data-stu-id="9341c-134">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8" ?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" MinorVersion="0" MajorBuildNumber="628" MinorBuildNumber="0" 
                         xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <GetStreamingEventsResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
                       xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
                       xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseMessages>
        <m:GetStreamingEventsResponseMessage ResponseClass="Error">
        <m:MessageText></m:MessageText>
        <m:DescriptiveLinkKey>0</m:DescriptiveLinkKey>
        <m:ResponseCode>ErrorInvalidSubscription</m:ResponseCode>
        <m:ConnectionStatus>Closed</m:ConnectionStatus>
      </m:ResponseMessages>
    </GetStreamingEventsResponse>
  </soap:Body>
</soap:Envelope>
```

## <a name="remarks"></a><span data-ttu-id="9341c-135">Notas</span><span class="sxs-lookup"><span data-stu-id="9341c-135">Remarks</span></span>

<span data-ttu-id="9341c-136">Cuando se procesa una solicitud de **GetStreamingEvents** , el servidor de acceso de cliente lleva a cabo los siguientes pasos:</span><span class="sxs-lookup"><span data-stu-id="9341c-136">When processing a **GetStreamingEvents** request, the Client Access server performs the following steps:</span></span> 
  
1. <span data-ttu-id="9341c-137">El [SubscriptionId (GetStreamingEvents)](subscriptionid-getstreamingevents.md) de la solicitud es confirmado como una suscripción válida que se hospeda en el servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="9341c-137">The [SubscriptionId (GetStreamingEvents)](subscriptionid-getstreamingevents.md) of the request is confirmed to be a valid subscription that is hosted on the Client Access server.</span></span> <span data-ttu-id="9341c-138">Si no es así, se produce un error en la llamada **GetStreamingEvents** .</span><span class="sxs-lookup"><span data-stu-id="9341c-138">If it is not, the **GetStreamingEvents** call fails.</span></span> 
    
2. <span data-ttu-id="9341c-139">Para que tenga derechos de suplantación, se valida la dirección SMTP del usuario autenticado para la solicitud.</span><span class="sxs-lookup"><span data-stu-id="9341c-139">The SMTP address of the authenticated user for the request is validated to have impersonation rights.</span></span> <span data-ttu-id="9341c-140">Si no lo hace, se produce un error en la solicitud **GetStreamingEvents** .</span><span class="sxs-lookup"><span data-stu-id="9341c-140">If they do not, the **GetStreamingEvents** request fails.</span></span> 
    
3. <span data-ttu-id="9341c-141">La cola de suscripción se consulta para los eventos que se esperan que se envíen al cliente.</span><span class="sxs-lookup"><span data-stu-id="9341c-141">The subscription queue is queried for events that are waiting to be sent to the client.</span></span> <span data-ttu-id="9341c-142">Si la cola no está vacía, los 50 primeros eventos de la cola se extrae de la cola y codificados en una notificación.</span><span class="sxs-lookup"><span data-stu-id="9341c-142">If the queue is not empty, the first 50 events from the queue are pulled from the queue and encoded into a notification.</span></span>
    
4. <span data-ttu-id="9341c-143">Si no se encontraron eventos en la cola, un [objeto StatusEvent](statusevent.md) se genera y se codifican en una respuesta de notificación.</span><span class="sxs-lookup"><span data-stu-id="9341c-143">If no events are found in the queue, a [StatusEvent](statusevent.md) is generated and encoded into a notification response.</span></span> 
    
5. <span data-ttu-id="9341c-144">La respuesta de notificación se devuelve al cliente.</span><span class="sxs-lookup"><span data-stu-id="9341c-144">The notification response is returned to the client.</span></span>
    
6. <span data-ttu-id="9341c-145">Se quitan los eventos que se incluyen en la notificación de la cola de suscripción y se establece la marca de agua última de acceso de cliente local de servidor para la suscripción a la marca de agua del último evento que se devuelve.</span><span class="sxs-lookup"><span data-stu-id="9341c-145">The events that are included in the notification are removed from the subscription queue and the Client Access server-local last watermark for the subscription is set to the watermark of the last event that is returned.</span></span>
    
7. <span data-ttu-id="9341c-146">Se restablece el temporizador de tiempo de espera de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="9341c-146">The timeout timer for the subscription is reset.</span></span>
    
## <a name="see-also"></a><span data-ttu-id="9341c-147">Ver también</span><span class="sxs-lookup"><span data-stu-id="9341c-147">See also</span></span>



[<span data-ttu-id="9341c-148">Operación de suscripción</span><span class="sxs-lookup"><span data-stu-id="9341c-148">Subscribe operation</span></span>](subscribe-operation.md)
  
[<span data-ttu-id="9341c-149">Cancelar la operación de suscripción</span><span class="sxs-lookup"><span data-stu-id="9341c-149">Unsubscribe operation</span></span>](unsubscribe-operation.md)
