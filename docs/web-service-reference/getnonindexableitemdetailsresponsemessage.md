---
title: GetNonIndexableItemDetailsResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 00566965-6cbd-4f31-9fa9-85b3e5559c0c
description: El elemento GetNonIndexableItemDetailsResponseMessage especifica el mensaje de respuesta para una solicitud de GetNonIndexableItemDetails.
ms.openlocfilehash: 4cf6b422cc29b20b09d05ea45628fa7133b437b2
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/03/2020
ms.locfileid: "44456524"
---
# <a name="getnonindexableitemdetailsresponsemessage"></a>GetNonIndexableItemDetailsResponseMessage

El elemento **GetNonIndexableItemDetailsResponseMessage** especifica el mensaje de respuesta para una solicitud de **GetNonIndexableItemDetails** . 
  
```XML
<GetNonIndexableItemDetailsResponseMessage>
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <NonIndexableItemDetailsResult/>
</GetNonIndexableItemDetailsResponseMessage>
```

 **GetNonIndexableItemDetailsResponseMessageType**
## <a name="attributes-and-elements"></a>Atributos y elementos

En las siguientes secciones se describen los atributos, elementos secundarios y elementos primarios.
  
### <a name="attributes"></a>Atributos

Ninguna.
  
### <a name="child-elements"></a>Elementos secundarios

[MessageText](messagetext.md)  |  [ResponseCode](responsecode.md)  |  [DescriptiveLinkKey](descriptivelinkkey.md)  |  [MessageXml](messagexml.md)  |  [NonIndexableItemDetailsResult](nonindexableitemdetailsresult.md)
  
### <a name="parent-elements"></a>Elementos principales

[ResponseMessages](responsemessages.md)
  
## <a name="remarks"></a>Comentarios

Este elemento se introdujo en Exchange Server 2013.
  
El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.
  
## <a name="element-information"></a>Información del elemento

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Nombre de esquema  <br/> |Esquema de mensajes  <br/> |
|Archivo de validación  <br/> |Messages. xsd  <br/> |
|Puede estar vacío  <br/> |false  <br/> |
   

