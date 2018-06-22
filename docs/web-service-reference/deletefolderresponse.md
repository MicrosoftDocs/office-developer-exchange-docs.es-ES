---
title: DeleteFolderResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DeleteFolderResponse
api_type:
- schema
ms.assetid: 27578bda-ef0a-4a33-bccc-2c1bc1735424
description: El elemento DeleteFolderResponse define una respuesta a una solicitud de DeleteFolder.
ms.openlocfilehash: ca6d12c847de4cfb46c4c680558ed7b256f1ecaf
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764093"
---
# <a name="deletefolderresponse"></a><span data-ttu-id="258b5-103">DeleteFolderResponse</span><span class="sxs-lookup"><span data-stu-id="258b5-103">DeleteFolderResponse</span></span>

<span data-ttu-id="258b5-104">El elemento **DeleteFolderResponse** define una respuesta a una solicitud de DeleteFolder.</span><span class="sxs-lookup"><span data-stu-id="258b5-104">The **DeleteFolderResponse** element defines a response to a DeleteFolder request.</span></span> 
  
```xml
<DeleteFolderResponse>
   <ResponseMessages/>
</DeleteFolderResponse>
```

 <span data-ttu-id="258b5-105">**DeleteFolderResponseType**</span><span class="sxs-lookup"><span data-stu-id="258b5-105">**DeleteFolderResponseType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="258b5-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="258b5-106">Attributes and elements</span></span>

<span data-ttu-id="258b5-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="258b5-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="258b5-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="258b5-108">Attributes</span></span>

<span data-ttu-id="258b5-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="258b5-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="258b5-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="258b5-110">Child elements</span></span>

|<span data-ttu-id="258b5-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="258b5-111">**Element**</span></span>|<span data-ttu-id="258b5-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="258b5-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="258b5-113">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="258b5-113">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="258b5-114">Contiene los mensajes de respuesta para una solicitud de servicios Web de Exchange.</span><span class="sxs-lookup"><span data-stu-id="258b5-114">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="258b5-115">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="258b5-115">Parent elements</span></span>

<span data-ttu-id="258b5-116">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="258b5-116">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="258b5-117">Observaciones</span><span class="sxs-lookup"><span data-stu-id="258b5-117">Remarks</span></span>

<span data-ttu-id="258b5-118">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="258b5-118">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="258b5-119">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="258b5-119">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="258b5-120">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="258b5-120">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="258b5-121">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="258b5-121">Schema name</span></span>  <br/> |<span data-ttu-id="258b5-122">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="258b5-122">Messages schema</span></span>  <br/> |
|<span data-ttu-id="258b5-123">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="258b5-123">Validation file</span></span>  <br/> |<span data-ttu-id="258b5-124">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="258b5-124">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="258b5-125">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="258b5-125">Can be empty</span></span>  <br/> |<span data-ttu-id="258b5-126">False</span><span class="sxs-lookup"><span data-stu-id="258b5-126">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="258b5-127">Ver también</span><span class="sxs-lookup"><span data-stu-id="258b5-127">See also</span></span>

- [<span data-ttu-id="258b5-128">Operación DeleteFolder</span><span class="sxs-lookup"><span data-stu-id="258b5-128">DeleteFolder operation</span></span>](deletefolder-operation.md) 
- [<span data-ttu-id="258b5-129">DeleteFolder</span><span class="sxs-lookup"><span data-stu-id="258b5-129">DeleteFolder</span></span>](deletefolder.md)
- [<span data-ttu-id="258b5-130">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="258b5-130">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
