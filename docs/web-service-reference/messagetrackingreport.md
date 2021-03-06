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
description: El elemento MessageTrackingReport contiene un solo mensaje que se devuelve en una operación GetMessageTrackingReport.
ms.openlocfilehash: fc3e56fbb1bee411fa31751f558f520874133076
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/03/2020
ms.locfileid: "44463219"
---
# <a name="messagetrackingreport"></a>MessageTrackingReport

El elemento **MessageTrackingReport** contiene un solo mensaje que se devuelve en una [operación GetMessageTrackingReport](getmessagetrackingreport-operation.md).
  
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

 **MessageTrackingReportType**
## <a name="attributes-and-elements"></a>Atributos y elementos

En las siguientes secciones se describen los atributos, elementos secundarios y elementos primarios.
  
### <a name="attributes"></a>Atributos

Ninguna.
  
### <a name="child-elements"></a>Elementos secundarios

|**Elemento**|**Descripción**|
|:-----|:-----|
|[Remitente (EmailAddressType)](sender-emailaddresstype.md) <br/> |Contiene la información de contacto del remitente del mensaje de correo electrónico.  <br/> |
|[PurportedSender](purportedsender.md) <br/> |Contiene la información de contacto del remitente de un mensaje de correo electrónico.  <br/> |
|[Asunto](subject.md) <br/> |Contiene el asunto del mensaje de correo electrónico.  <br/> |
|[SubmitTime](submittime.md) <br/> |Contiene la hora del día a la que se envió el mensaje de correo electrónico.  <br/> |
|[OriginalRecipients](originalrecipients.md) <br/> |Contiene una lista de los destinatarios del mensaje de correo electrónico.  <br/> |
|[RecipientTrackingEvents](recipienttrackingevents.md) <br/> |Contiene una lista de uno o más eventos de seguimiento de los destinatarios.  <br/> |
|[Propiedades (ArrayOfTrackingPropertiesType)](properties-arrayoftrackingpropertiestype.md) <br/> |Contiene una lista de una o varias propiedades de seguimiento.  <br/> |
   
### <a name="parent-elements"></a>Elementos principales

|**Elemento**|**Descripción**|
|:-----|:-----|
|[GetMessageTrackingReportResponse](getmessagetrackingreportresponse.md) <br/> |Contiene el resultado de una única solicitud de [operación GetMessageTrackingReport](getmessagetrackingreport-operation.md) .  <br/> |
   
## <a name="text-value"></a>Valor de texto

Ninguno.
  
## <a name="remarks"></a>Comentarios

El esquema que describe este elemento se encuentra en el directorio virtual de IIS que hospeda los servicios Web de Exchange. este elemento se introdujo en Exchange Server 2010 Service Pack 1 (SP1).
  
## <a name="element-information"></a>Información del elemento

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Nombre de esquema  <br/> |Esquema de mensajes  <br/> |
|Archivo de validación  <br/> |Messages. xsd  <br/> |
|Puede estar vacío  <br/> |Falso  <br/> |
   
## <a name="see-also"></a>Vea también



[Operación FindMessageTrackingReport](findmessagetrackingreport-operation.md)
  
[Operación GetMessageTrackingReport](getmessagetrackingreport-operation.md)


- [Elementos XML de EWS en Exchange](ews-xml-elements-in-exchange.md)
  
- [Elementos XML de EWS en Exchange](ews-xml-elements-in-exchange.md)

