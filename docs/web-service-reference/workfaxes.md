---
title: WorkFaxes
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 95d115a1-2743-4416-af6f-1ef1be8c4e93
description: El elemento WorkFaxes especifica una matriz de números de fax de trabajo y los identificadores de sus atribuciones de origen para el rol asociado.
ms.openlocfilehash: d0da5fc2e1b26d14ef3c07f876174da6ccacd016
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/03/2020
ms.locfileid: "44459689"
---
# <a name="workfaxes"></a>WorkFaxes

El elemento **WorkFaxes** especifica una matriz de números de fax de trabajo y los identificadores de sus atribuciones de origen para el rol asociado. 
  
```XML
<WorkFaxes>
   <PhoneNumberAttributedValue/>
</WorkFaxes>
```

 **ArrayOfPhoneNumberAttributedValuesType**
## <a name="attributes-and-elements"></a>Atributos y elementos

En las siguientes secciones se describen los atributos, elementos secundarios y elementos primarios.
  
### <a name="attributes"></a>Atributos

Ninguna.
  
### <a name="child-elements"></a>Elementos secundarios

[PhoneNumberAttributedValue](phonenumberattributedvalue.md)
  
### <a name="parent-elements"></a>Elementos principales

[Rol](persona.md)
  
## <a name="remarks"></a>Comentarios

Este elemento se introdujo en Exchange Server 2013.
  
El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.
  
## <a name="element-information"></a>Información del elemento

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nombre de esquema  <br/> |Esquema de tipos  <br/> |
|Archivo de validación  <br/> |Types. xsd  <br/> |
|Puede estar vacío  <br/> ||
   

