---
title: SearchMailboxesResult
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: ddb276c4-6c8a-46ef-a2eb-46b6a0bfce09
description: El elemento SearchMailboxesResult contiene el resultado de la solicitud SearchMailboxes.
ms.openlocfilehash: 79d593d99762aedc6290578b5458f9ac3cad3d26
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/03/2020
ms.locfileid: "44466706"
---
# <a name="searchmailboxesresult"></a>SearchMailboxesResult

El elemento **SearchMailboxesResult** contiene el resultado de la solicitud **SearchMailboxes** . 
  
```XML
<SearchMailboxesResult>
   <SearchQueries/>
   <ResultType/>
   <ItemCount/>
   <Size/>
   <PageItemCount/>
   <PageItemSize/>
   <KeywordStats/>
   <Items/>
   <FailedMailboxes/>
   <Refiners/>
   <MailboxStats/>
</SearchMailboxesResult>
```

 **SearchMailboxesResultType**
## <a name="attributes-and-elements"></a>Atributos y elementos

En las siguientes secciones se describen los atributos, elementos secundarios y elementos primarios.
  
### <a name="attributes"></a>Atributos

Ninguna.
  
### <a name="child-elements"></a>Elementos secundarios

[SearchQueries](searchqueries.md)  |  [ResultType](resulttype.md)  |  [ItemCount](itemcount.md)  |  [Tamaño (largo)](size-long.md)  |  [PageItemCount](pageitemcount.md)  |  [PageItemSize](pageitemsize.md)  |  [KeywordStats](keywordstats.md)  |  [Elementos (ArrayOfSearchPreviewItemsType)](items-arrayofsearchpreviewitemstype.md)  |  [FailedMailboxes](failedmailboxes.md)  |  [Refinadores](refiners.md)  |  [MailboxStats](mailboxstats.md)
  
### <a name="parent-elements"></a>Elementos principales

[SearchMailboxesResponseMessage](searchmailboxesresponsemessage.md)
  
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
   

