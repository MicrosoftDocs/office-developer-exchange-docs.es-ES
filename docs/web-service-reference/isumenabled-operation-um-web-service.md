---
title: Operación IsUMEnabled (servicio Web de mensajería unificada)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_name:
- IsUMEnabled
api_type:
- schema
ms.assetid: fbe6cd95-f7a5-42b9-8a9d-b6159a269d55
description: La operación IsUMEnabled determina si un buzón de correo está habilitado para mensajería unificada.
ms.openlocfilehash: b1478f5a113059251fe1b036ac7d77e5a4ab4f50
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/03/2020
ms.locfileid: "44458239"
---
# <a name="isumenabled-operation-um-web-service"></a>Operación IsUMEnabled (servicio Web de mensajería unificada)

La operación IsUMEnabled determina si un buzón de correo está habilitado para mensajería unificada.
  
## <a name="isumenabled-request-example"></a>Ejemplo de solicitud IsUMEnabled

### <a name="description"></a>Description

El siguiente ejemplo de una solicitud IsUMEnabled muestra cómo crear una solicitud para determinar si un buzón está habilitado para mensajería unificada.
  
### <a name="code"></a>Código

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Body>
    <IsUMEnabled xmlns="https://schemas.microsoft.com/exchange/services/2006/messages" />
  </soap:Body>
</soap:Envelope>
```

## <a name="successful-isumenabled-response-example"></a>Ejemplo de respuesta IsUMEnabled correcta

### <a name="description"></a>Description

En el ejemplo siguiente se muestra una respuesta correcta a una solicitud IsUMEnabled.
  
### <a name="code"></a>Código

```XML
<?xml version="1.0" encoding="utf-8" ?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Body>
    <IsUMEnabledResponse xmlns="https://schemas.microsoft.com/exchange/services/2006/messages">
      <IsUMEnabledResponse>true</IsUMEnabledResponse> 
    </IsUMEnabledResponse>
  </soap:Body>
</soap:Envelope>
```

## <a name="see-also"></a>Vea también



[IsUMEnabled (servicio Web de mensajería unificada)](isumenabled-um-web-service.md)
  
[IsUMEnabledResponse (servicio Web de mensajería unificada)](isumenabledresponse-um-web-service.md)


[Elementos XML de servicio Web de mensajería unificada para Exchange](unified-messaging-web-service-xml-elements-for-exchange.md)

