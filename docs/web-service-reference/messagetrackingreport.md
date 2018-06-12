---
title: MessageTrackingReport
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- MessageTrackingReport
api_type:
- schema
ms.assetid: 2740bcf6-f86d-4756-a0f2-24ed6e9b75f7
description: El elemento MessageTrackingReport contiene un solo mensaje que se devuelve en una operación de GetMessageTrackingReport.
ms.openlocfilehash: d01e0fbf099d096c7f255a8e94070e330577e6ca
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836457"
---
# <a name="messagetrackingreport"></a><span data-ttu-id="5508f-103">MessageTrackingReport</span><span class="sxs-lookup"><span data-stu-id="5508f-103">MessageTrackingReport</span></span>

<span data-ttu-id="5508f-104">El elemento **MessageTrackingReport** contiene un solo mensaje que se devuelve en una [operación de GetMessageTrackingReport](getmessagetrackingreport-operation.md).</span><span class="sxs-lookup"><span data-stu-id="5508f-104">The **MessageTrackingReport** element contains a single message that is returned in a [GetMessageTrackingReport operation](getmessagetrackingreport-operation.md).</span></span>
  
```XML
<MessageTrackingReport>
   <Sender/>
   <PurportedSender/>
   <Subject/>
   <SubmitTime/>
   <OriginalRecipients/>
   <RecipientTrackingEvents/>
   <Properties/>
</MessageTrackingReport>
```

 <span data-ttu-id="5508f-105">**MessageTrackingReportType**</span><span class="sxs-lookup"><span data-stu-id="5508f-105">**MessageTrackingReportType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="5508f-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="5508f-106">Attributes and elements</span></span>

<span data-ttu-id="5508f-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="5508f-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="5508f-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="5508f-108">Attributes</span></span>

<span data-ttu-id="5508f-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="5508f-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="5508f-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="5508f-110">Child elements</span></span>

|<span data-ttu-id="5508f-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="5508f-111">**Element**</span></span>|<span data-ttu-id="5508f-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="5508f-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="5508f-113">Remitente (EmailAddressType)</span><span class="sxs-lookup"><span data-stu-id="5508f-113">Sender (EmailAddressType)</span></span>](sender-emailaddresstype.md) <br/> |<span data-ttu-id="5508f-114">Contiene información de contacto para el remitente del mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="5508f-114">Contains contact information for the sender of the e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="5508f-115">PurportedSender</span><span class="sxs-lookup"><span data-stu-id="5508f-115">PurportedSender</span></span>](purportedsender.md) <br/> |<span data-ttu-id="5508f-116">Contiene información de contacto para el remitente presunta de un mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="5508f-116">Contains contact information for the alleged sender of an e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="5508f-117">Subject</span><span class="sxs-lookup"><span data-stu-id="5508f-117">Subject</span></span>](subject.md) <br/> |<span data-ttu-id="5508f-118">Contiene al asunto del mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="5508f-118">Contains the subject of the e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="5508f-119">SubmitTime</span><span class="sxs-lookup"><span data-stu-id="5508f-119">SubmitTime</span></span>](submittime.md) <br/> |<span data-ttu-id="5508f-120">Contiene la hora del día en que se envió el mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="5508f-120">Contains the time of day that the e-mail message was submitted.</span></span>  <br/> |
|[<span data-ttu-id="5508f-121">OriginalRecipients</span><span class="sxs-lookup"><span data-stu-id="5508f-121">OriginalRecipients</span></span>](originalrecipients.md) <br/> |<span data-ttu-id="5508f-122">Contiene una lista de los destinatarios del mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="5508f-122">Contains a list of the recipients of the e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="5508f-123">RecipientTrackingEvents</span><span class="sxs-lookup"><span data-stu-id="5508f-123">RecipientTrackingEvents</span></span>](recipienttrackingevents.md) <br/> |<span data-ttu-id="5508f-124">Contiene una lista de uno o más eventos de seguimiento para los destinatarios.</span><span class="sxs-lookup"><span data-stu-id="5508f-124">Contains a list of one or more tracking events for the recipients.</span></span>  <br/> |
|[<span data-ttu-id="5508f-125">Propiedades (ArrayOfTrackingPropertiesType)</span><span class="sxs-lookup"><span data-stu-id="5508f-125">Properties (ArrayOfTrackingPropertiesType)</span></span>](properties-arrayoftrackingpropertiestype.md) <br/> |<span data-ttu-id="5508f-126">Contiene una lista de una o varias propiedades de seguimiento.</span><span class="sxs-lookup"><span data-stu-id="5508f-126">Contains a list of one or more tracking properties.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="5508f-127">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="5508f-127">Parent elements</span></span>

|<span data-ttu-id="5508f-128">**Element**</span><span class="sxs-lookup"><span data-stu-id="5508f-128">**Element**</span></span>|<span data-ttu-id="5508f-129">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="5508f-129">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="5508f-130">GetMessageTrackingReportResponse</span><span class="sxs-lookup"><span data-stu-id="5508f-130">GetMessageTrackingReportResponse</span></span>](getmessagetrackingreportresponse.md) <br/> |<span data-ttu-id="5508f-131">Contiene el resultado de una única solicitud de [operación GetMessageTrackingReport](getmessagetrackingreport-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="5508f-131">Contains the result of a single [GetMessageTrackingReport operation](getmessagetrackingreport-operation.md) request.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="5508f-132">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="5508f-132">Text value</span></span>

<span data-ttu-id="5508f-133">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="5508f-133">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="5508f-134">Observaciones</span><span class="sxs-lookup"><span data-stu-id="5508f-134">Remarks</span></span>

<span data-ttu-id="5508f-135">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda Exchange Web Services.This elemento fue introdujo en Exchange Server 2010 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="5508f-135">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).</span></span>
  
## <a name="element-information"></a><span data-ttu-id="5508f-136">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="5508f-136">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5508f-137">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="5508f-137">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="5508f-138">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="5508f-138">Schema Name</span></span>  <br/> |<span data-ttu-id="5508f-139">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="5508f-139">Messages schema</span></span>  <br/> |
|<span data-ttu-id="5508f-140">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="5508f-140">Validation File</span></span>  <br/> |<span data-ttu-id="5508f-141">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="5508f-141">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="5508f-142">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="5508f-142">Can be Empty</span></span>  <br/> |<span data-ttu-id="5508f-143">False</span><span class="sxs-lookup"><span data-stu-id="5508f-143">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="5508f-144">Ver también</span><span class="sxs-lookup"><span data-stu-id="5508f-144">See also</span></span>



[<span data-ttu-id="5508f-145">Operación FindMessageTrackingReport</span><span class="sxs-lookup"><span data-stu-id="5508f-145">FindMessageTrackingReport operation</span></span>](findmessagetrackingreport-operation.md)
  
[<span data-ttu-id="5508f-146">Operación GetMessageTrackingReport</span><span class="sxs-lookup"><span data-stu-id="5508f-146">GetMessageTrackingReport operation</span></span>](getmessagetrackingreport-operation.md)


- [<span data-ttu-id="5508f-147">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="5508f-147">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
  
- [<span data-ttu-id="5508f-148">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="5508f-148">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
