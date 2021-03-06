---
title: Hora
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Time
api_type:
- schema
ms.assetid: c4b98be7-141c-4ba8-97ef-9ad1ed19f61f
description: El elemento Time representa la hora de transición del día a y desde la hora estándar y el horario de verano.
ms.openlocfilehash: 97c89fbcbdb85fcdd4d32a1d44075ac42adef053
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/03/2020
ms.locfileid: "44460298"
---
# <a name="time"></a>Hora

El elemento **Time** representa la hora de transición del día a y desde la hora estándar y el horario de verano. 
  
```xml
<Time>...</Time>
```

 **string**
## <a name="attributes-and-elements"></a>Atributos y elementos

En las siguientes secciones se describen los atributos, elementos secundarios y elementos primarios.
  
### <a name="attributes"></a>Atributos

Ninguna.
  
### <a name="child-elements"></a>Elementos secundarios

Ninguna.
  
### <a name="parent-elements"></a>Elementos principales

|**Elemento**|**Descripción**|
|:-----|:-----|
|[Standardtime Element](standardtime.md) <br/> | Representa un desplazamiento del tiempo con respecto a la hora universal coordinada (UTC) representada por el elemento [Bias (UTC)](bias-utc.md) . Este elemento también contiene información sobre la transición a la hora estándar del horario de verano en regiones en las que se observa el horario de verano.  <br/><br/>  Las siguientes son las expresiones XPath para el elemento [standardtime Element](standardtime.md) : <br/> <br/>  `/GetUserAvailabilityResponse/FreeBusyResponseArray/FreeBusyResponse/FreeBusyView/WorkingHours/TimeZone/StandardTime`<br/> <br/>  `/GetUserAvailabilityRequest/TimeZone/StandardTime` <br/> |
|[DaylightTime](daylighttime.md) <br/> | Representa un desplazamiento del tiempo relativo a la hora UTC representado por el elemento [Bias (UTC)](bias-utc.md) en las regiones en las que se observa el horario de verano. Este elemento también contiene información sobre cuándo se produce la transición al horario de verano desde la hora estándar.  <br/><br/>  Las siguientes son las expresiones XPath para el elemento [DaylightTime](daylighttime.md) :  <br/><br/>  `/GetUserAvailabilityResponse/FreeBusyResponseArray/FreeBusyResponse/FreeBusyView/WorkingHours/TimeZone/DaylightTime` <br/><br/>  `/GetUserAvailabilityRequest/TimeZone/DaylightTime` <br/> |
   
## <a name="text-value"></a>Valor de texto

El valor de texto representa las horas, los minutos y los segundos con el siguiente formato: HH: mm: SS.
  
## <a name="remarks"></a>Comentarios

Cuando se produce el elemento **Time** en el elemento [DaylightTime](daylighttime.md) , representa la hora del día en que se produce la transición del horario de verano a la hora estándar. Cuando se produce el elemento [Time](time.md) en el elemento [standardtime Element](standardtime.md) , representa la hora del día a la que se produce la transición de la hora estándar al horario de verano. 
  
Este elemento tiene una ocurrencia mínima de cero y una ocurrencia máxima de uno.
  
## <a name="example"></a>Ejemplo

La siguiente parte de una solicitud representa un tiempo de transición de 2 A.M. de la hora estándar al horario de verano.
  
```xml
<StandardTime>
   <Bias>0</Bias>
   <Time>02:00:00</Time>
   <DayOrder>5</DayOrder>
   <Month>10</Month>
   <DayOfWeek>Sunday</DayOfWeek>
</StandardTime
```

## <a name="element-information"></a>Información del elemento

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nombre de esquema  <br/> |Esquema de tipos  <br/> |
|Archivo de validación  <br/> |Types. xsd  <br/> |
|Puede estar vacío  <br/> |Falso  <br/> |
   
## <a name="see-also"></a>Vea también

- [Operación GetUserAvailability](getuseravailability-operation.md)
- [Obtener disponibilidad del usuario](https://msdn.microsoft.com/library/d4133fcb-9b0f-4e6b-aadf-a389da83516a%28Office.15%29.aspx)

