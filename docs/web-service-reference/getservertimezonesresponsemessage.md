---
title: GetServerTimeZonesResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetServerTimeZonesResponseMessage
api_type:
- schema
ms.assetid: eb2592b2-144f-4c33-8df7-8e70dce7ab55
description: El elemento GetServerTimeZonesResponseMessage contiene el estado y el resultado de una única solicitud de operación GetServerTimeZones.
ms.openlocfilehash: de032c961f6fffa5b4f0607a17fe48630510fda9
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/03/2020
ms.locfileid: "44460921"
---
# <a name="getservertimezonesresponsemessage"></a>GetServerTimeZonesResponseMessage

El elemento **GetServerTimeZonesResponseMessage** contiene el estado y el resultado de una única solicitud de [operación GetServerTimeZones](getservertimezones-operation.md) . 
  
```XML
<GetServerTimeZonesResponseMessage ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <TimeZoneDefinitions/>
</GetServerTimeZonesResponseMessage>
```

 **GetServerTimeZonesResponseMessageType**
## <a name="attributes-and-elements"></a>Atributos y elementos

En las siguientes secciones se describen los atributos, elementos secundarios y elementos primarios.
  
### <a name="attributes"></a>Atributos

|**Atributo**|**Descripción**|
|:-----|:-----|
|**ResponseClass** <br/> | Describe el estado de la respuesta. <br/><br/>Los siguientes valores son válidos para este atributo:  <br/><br/>-Correcto  <br/>-ADVERTENCIA  <br/>-Error  <br/> |
   
#### <a name="responseclass-attribute-values"></a>Valores del atributo ResponseClass

|**Valor**|**Descripción**|
|:-----|:-----|
|**Success** <br/> |Describe una solicitud que se ha completado.  <br/> |
|**Advertencia** <br/> | Describe una solicitud que no se ha procesado. Se puede devolver una advertencia si se produjo un error al procesar un elemento de la solicitud y no se pudieron procesar los siguientes elementos.<br/><br/> Los siguientes son ejemplos de fuentes de advertencias: <br/> <br/>-El almacén de Exchange está sin conexión durante el lote.  <br/>-Los servicios de dominio de Active Directory (AD DS) están sin conexión.  <br/>-Se movieron los buzones.  <br/>-La base de datos de mensajes (MDB) está sin conexión.  <br/>-Una contraseña ha expirado.  <br/>-Se ha superado la cuota.  <br/> |
|**Error** <br/> | Describe una solicitud que no se puede cumplir. <br/><br/>Los siguientes son ejemplos de orígenes de errores:  <br/><br/>-Atributos o elementos no válidos  <br/>-Atributos o elementos fuera del intervalo  <br/>-Una etiqueta desconocida  <br/>-Un atributo o elemento que no es válido en el contexto  <br/>-Un intento de acceso no autorizado por parte de cualquier cliente  <br/>-Un error del servidor en respuesta a una llamada válida del lado cliente  <br/><br/>  La información sobre el error se puede encontrar en los elementos [ResponseCode](responsecode.md) y [MessageText](messagetext.md) .  <br/> |
   
### <a name="child-elements"></a>Elementos secundarios

|**Elemento**|**Descripción**|
|:-----|:-----|
|[MessageText](messagetext.md) <br/> |Proporciona una descripción de texto del estado de la respuesta.  <br/> |
|[ResponseCode](responsecode.md) <br/> |Proporciona un código de error que identifica el error específico que ha encontrado la solicitud.  <br/> |
|[DescriptiveLinkKey](descriptivelinkkey.md) <br/> |Actualmente no está en uso y reservado para uso futuro. Este elemento contiene un valor de 0.  <br/> |
|[MessageXml](messagexml.md) <br/> |Proporciona información de respuesta de error adicional.  <br/> |
|[TimeZoneDefinitions](timezonedefinitions.md) <br/> |Contiene una matriz de definiciones de zona horaria.  <br/> |
   
### <a name="parent-elements"></a>Elementos principales

|**Elemento**|**Descripción**|
|:-----|:-----|
|[ResponseMessages](responsemessages.md) <br/> |Contiene los mensajes de respuesta para una solicitud de servicios Web de Exchange (EWS).  <br/> |
   
## <a name="remarks"></a>Comentarios

El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.
  
## <a name="element-information"></a>Información del elemento

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Nombre de esquema  <br/> |Esquema de mensajes  <br/> |
|Archivo de validación  <br/> |Messages. xsd  <br/> |
|Puede estar vacío  <br/> |Falso  <br/> |
   
## <a name="see-also"></a>Vea también

- [Elementos XML de EWS en Exchange](ews-xml-elements-in-exchange.md)

