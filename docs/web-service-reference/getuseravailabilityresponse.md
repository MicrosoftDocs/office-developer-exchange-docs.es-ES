---
title: GetUserAvailabilityResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetUserAvailabilityResponse
api_type:
- schema
ms.assetid: 6999510a-d60e-43da-8964-57b5fb3e9d11
description: El elemento GetUserAvailabilityResponse es el elemento raíz que contiene las propiedades que definen la información de disponibilidad del usuario o sugeridas información de tiempo de la reunión.
ms.openlocfilehash: 0a30dc8ebc11b1f818b2c27b0ea68fc135ec0925
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19835684"
---
# <a name="getuseravailabilityresponse"></a><span data-ttu-id="9d665-103">GetUserAvailabilityResponse</span><span class="sxs-lookup"><span data-stu-id="9d665-103">GetUserAvailabilityResponse</span></span>

<span data-ttu-id="9d665-104">El elemento **GetUserAvailabilityResponse** es el elemento raíz que contiene las propiedades que definen la información de disponibilidad del usuario o sugeridas información de tiempo de la reunión.</span><span class="sxs-lookup"><span data-stu-id="9d665-104">The **GetUserAvailabilityResponse** element is the root element that contains the properties that define user availability information or suggested meeting time information.</span></span> 
  
```xml
<GetUserAvailabilityResponse>
   <FreeBusyResponseArray>...</FreeBusyResponseArray>
   <SuggestionsResponse>...</SuggestionsResponse>
</GetUserAvailabilityResponse>
```

 <span data-ttu-id="9d665-105">**GetUserAvailabilityResponseType**</span><span class="sxs-lookup"><span data-stu-id="9d665-105">**GetUserAvailabilityResponseType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="9d665-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="9d665-106">Attributes and elements</span></span>

<span data-ttu-id="9d665-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="9d665-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="9d665-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="9d665-108">Attributes</span></span>

<span data-ttu-id="9d665-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="9d665-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="9d665-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="9d665-110">Child elements</span></span>

|<span data-ttu-id="9d665-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="9d665-111">**Element**</span></span>|<span data-ttu-id="9d665-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="9d665-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="9d665-113">FreeBusyResponseArray</span><span class="sxs-lookup"><span data-stu-id="9d665-113">FreeBusyResponseArray</span></span>](freebusyresponsearray.md) <br/> |<span data-ttu-id="9d665-114">Contiene información sobre la disponibilidad de los usuarios solicitado y el estado de la respuesta.</span><span class="sxs-lookup"><span data-stu-id="9d665-114">Contains the requested users' availability information and the response status.</span></span>  <br/> |
|[<span data-ttu-id="9d665-115">SuggestionsResponse</span><span class="sxs-lookup"><span data-stu-id="9d665-115">SuggestionsResponse</span></span>](suggestionsresponse.md) <br/> |<span data-ttu-id="9d665-116">Contiene datos de sugerencia y la información de estado de respuesta para solicitado sugerencias de reunión.</span><span class="sxs-lookup"><span data-stu-id="9d665-116">Contains response status information and suggestion data for requested meeting suggestions.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="9d665-117">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="9d665-117">Parent elements</span></span>

<span data-ttu-id="9d665-118">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="9d665-118">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="9d665-119">Observaciones</span><span class="sxs-lookup"><span data-stu-id="9d665-119">Remarks</span></span>

<span data-ttu-id="9d665-120">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="9d665-120">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="example"></a><span data-ttu-id="9d665-121">Ejemplo</span><span class="sxs-lookup"><span data-stu-id="9d665-121">Example</span></span>

<span data-ttu-id="9d665-122">El siguiente ejemplo de una respuesta GetUserAvailability muestra una respuesta a una solicitud de GetUserAvailability.</span><span class="sxs-lookup"><span data-stu-id="9d665-122">The following example of a GetUserAvailability response shows a response to a GetUserAvailability request.</span></span>
  
```
<?xml version="1.0" encoding="utf-8" ?>
<GetUserAvailabilityResponse xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                             xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <FreeBusyResponseArray xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
    <FreeBusyResponse>
      <ResponseMessage ResponseClass="Success">
        <Path select="/m:GetUserAvailabilityRequest/MailboxDataArray[0]" />
      </ResponseMessage>
      <FreeBusyView>
        <FreeBusyViewType xmlns="http://schemas.microsoft.com/exchange/services/2006/types">Detailed</FreeBusyViewType>
        <CalendarEventArray xmlns="http://schemas.microsoft.com/exchange/services/2006/types">
          <CalendarEvent>
            <StartTime>2006-02-28T19:00:00-08:00</StartTime>
            <EndTime>2006-02-28T23:30:00-08:00</EndTime>
            <BusyType>OOF</BusyType>
            <IsPrivate>false</IsPrivate>
            <CalendarEventDetails>
              <ID>00000</ID>
              <Subject>Exercise</Subject>
              <Location>the gym</Location>
              <IsMeeting>false</IsMeeting>
              <IsRecurring>false</IsRecurring>
              <IsException>false</IsException>
              <IsReminderSet>true</IsReminderSet>
            </CalendarEventDetails>
          </CalendarEvent>
        </CalendarEventArray>
        <WorkingHours xmlns="http://schemas.microsoft.com/exchange/services/2006/types">
          <TimeZone>
            <Bias>480</Bias>
            <StandardTime>
              <Bias>0</Bias>
              <Time>02:00:00</Time>
              <DayOrder>5</DayOrder>
              <Month>10</Month>
              <DayOfWeek>Sunday</DayOfWeek>
            </StandardTime>
            <DaylightTime>
              <Bias>-60</Bias>
              <Time>02:00:00</Time>
              <DayOrder>1</DayOrder>
              <Month>4</Month>
              <DayOfWeek>Sunday</DayOfWeek>
            </DaylightTime>
          </TimeZone>
          <WorkingPeriodArray>
            <WorkingPeriod>
              <DayOfWeek>Monday Tuesday Wednesday Thursday Friday</DayOfWeek>
              <StartTimeInMinutes>480</StartTimeInMinutes>
              <EndTimeInMinutes>1020</EndTimeInMinutes>
            </WorkingPeriod>
          </WorkingPeriodArray>
        </WorkingHours>
      </FreeBusyView>
    </FreeBusyResponse>
  </FreeBusyResponseArray>
</GetUserAvailabilityResponse>
```

<span data-ttu-id="9d665-123">El contenido del [identificador de](id.md) elemento se ha más cortos para conservar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="9d665-123">The [ID](id.md) element contents were shortened to preserve readability.</span></span> 
  
## <a name="element-information"></a><span data-ttu-id="9d665-124">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="9d665-124">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="9d665-125">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="9d665-125">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="9d665-126">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="9d665-126">Schema Name</span></span>  <br/> |<span data-ttu-id="9d665-127">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="9d665-127">Messages schema</span></span>  <br/> |
|<span data-ttu-id="9d665-128">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="9d665-128">Validation File</span></span>  <br/> |<span data-ttu-id="9d665-129">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="9d665-129">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="9d665-130">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="9d665-130">Can be Empty</span></span>  <br/> |<span data-ttu-id="9d665-131">False</span><span class="sxs-lookup"><span data-stu-id="9d665-131">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="9d665-132">Ver también</span><span class="sxs-lookup"><span data-stu-id="9d665-132">See also</span></span>



[<span data-ttu-id="9d665-133">GetUserAvailabilityRequest</span><span class="sxs-lookup"><span data-stu-id="9d665-133">GetUserAvailabilityRequest</span></span>](getuseravailabilityrequest.md)


[<span data-ttu-id="9d665-134">Obtención de disponibilidad del usuario</span><span class="sxs-lookup"><span data-stu-id="9d665-134">Getting User Availability</span></span>](http://msdn.microsoft.com/library/d4133fcb-9b0f-4e6b-aadf-a389da83516a%28Office.15%29.aspx)
