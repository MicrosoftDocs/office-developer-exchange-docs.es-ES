---
title: FindFolderResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- FindFolderResponse
api_type:
- schema
ms.assetid: f5dd813c-9698-4a39-8fca-3a825df365ed
description: El elemento FindFolderResponse define una respuesta a una solicitud de FindFolder.
ms.openlocfilehash: 3bf0509acd5a3928eb29015c39c18bb779c1dfce
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764614"
---
# <a name="findfolderresponse"></a><span data-ttu-id="9b3a4-103">FindFolderResponse</span><span class="sxs-lookup"><span data-stu-id="9b3a4-103">FindFolderResponse</span></span>

<span data-ttu-id="9b3a4-104">El elemento **FindFolderResponse** define una respuesta a una solicitud de FindFolder.</span><span class="sxs-lookup"><span data-stu-id="9b3a4-104">The **FindFolderResponse** element defines a response to a FindFolder request.</span></span> 
  
[<span data-ttu-id="9b3a4-105">FindFolderResponse</span><span class="sxs-lookup"><span data-stu-id="9b3a4-105">FindFolderResponse</span></span>](findfolderresponse.md)
  
```xml
<FindFolderResponse>
   <ResponseMessages/>
</FindFolderResponse>
```

 <span data-ttu-id="9b3a4-106">**FindFolderResponseType**</span><span class="sxs-lookup"><span data-stu-id="9b3a4-106">**FindFolderResponseType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="9b3a4-107">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="9b3a4-107">Attributes and elements</span></span>

<span data-ttu-id="9b3a4-108">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="9b3a4-108">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="9b3a4-109">Atributos</span><span class="sxs-lookup"><span data-stu-id="9b3a4-109">Attributes</span></span>

<span data-ttu-id="9b3a4-110">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="9b3a4-110">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="9b3a4-111">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="9b3a4-111">Child elements</span></span>

|<span data-ttu-id="9b3a4-112">**Element**</span><span class="sxs-lookup"><span data-stu-id="9b3a4-112">**Element**</span></span>|<span data-ttu-id="9b3a4-113">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="9b3a4-113">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="9b3a4-114">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="9b3a4-114">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="9b3a4-115">Contiene los mensajes de respuesta para una solicitud de servicios Web de Exchange.</span><span class="sxs-lookup"><span data-stu-id="9b3a4-115">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="9b3a4-116">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="9b3a4-116">Parent elements</span></span>

<span data-ttu-id="9b3a4-117">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="9b3a4-117">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="9b3a4-118">Observaciones</span><span class="sxs-lookup"><span data-stu-id="9b3a4-118">Remarks</span></span>

<span data-ttu-id="9b3a4-119">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="9b3a4-119">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="9b3a4-120">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="9b3a4-120">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="9b3a4-121">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="9b3a4-121">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="9b3a4-122">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="9b3a4-122">Schema name</span></span>  <br/> |<span data-ttu-id="9b3a4-123">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="9b3a4-123">Messages schema</span></span>  <br/> |
|<span data-ttu-id="9b3a4-124">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="9b3a4-124">Validation file</span></span>  <br/> |<span data-ttu-id="9b3a4-125">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="9b3a4-125">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="9b3a4-126">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="9b3a4-126">Can be empty</span></span>  <br/> |<span data-ttu-id="9b3a4-127">False</span><span class="sxs-lookup"><span data-stu-id="9b3a4-127">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="9b3a4-128">Ver también</span><span class="sxs-lookup"><span data-stu-id="9b3a4-128">See also</span></span>



[<span data-ttu-id="9b3a4-129">Operación FindFolder</span><span class="sxs-lookup"><span data-stu-id="9b3a4-129">FindFolder operation</span></span>](findfolder-operation.md)


[<span data-ttu-id="9b3a4-130">Buscar carpetas</span><span class="sxs-lookup"><span data-stu-id="9b3a4-130">Finding Folders</span></span>](http://msdn.microsoft.com/library/9124d868-017a-43f0-b915-5c0082cacec9%28Office.15%29.aspx)
