---
title: TotalCount
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- TotalCount
api_type:
- schema
ms.assetid: c48c6388-8449-4622-bc38-6f0e84293872
description: El elemento TotalCount representa el recuento total de elementos dentro de una carpeta determinada.
ms.openlocfilehash: e4a7bcb70d04bc5bcf66087c0272732a7be1231a
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19840705"
---
# <a name="totalcount"></a><span data-ttu-id="5eddf-103">TotalCount</span><span class="sxs-lookup"><span data-stu-id="5eddf-103">TotalCount</span></span>

<span data-ttu-id="5eddf-104">El elemento **TotalCount** representa el recuento total de elementos dentro de una carpeta determinada.</span><span class="sxs-lookup"><span data-stu-id="5eddf-104">The **TotalCount** element represents the total count of items within a given folder.</span></span> 
  
```xml
<TotalCount/>
```

 <span data-ttu-id="5eddf-105">**int**</span><span class="sxs-lookup"><span data-stu-id="5eddf-105">**int**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="5eddf-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="5eddf-106">Attributes and elements</span></span>

<span data-ttu-id="5eddf-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="5eddf-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="5eddf-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="5eddf-108">Attributes</span></span>

<span data-ttu-id="5eddf-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="5eddf-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="5eddf-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="5eddf-110">Child elements</span></span>

<span data-ttu-id="5eddf-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="5eddf-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="5eddf-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="5eddf-112">Parent elements</span></span>

|<span data-ttu-id="5eddf-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="5eddf-113">**Element**</span></span>|<span data-ttu-id="5eddf-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="5eddf-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="5eddf-115">Folder</span><span class="sxs-lookup"><span data-stu-id="5eddf-115">Folder</span></span>](folder.md) <br/> |<span data-ttu-id="5eddf-116">Representa una carpeta en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="5eddf-116">Represents a folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="5eddf-117">CalendarFolder</span><span class="sxs-lookup"><span data-stu-id="5eddf-117">CalendarFolder</span></span>](calendarfolder.md) <br/> |<span data-ttu-id="5eddf-118">Representa una carpeta del calendario en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="5eddf-118">Represents a calendar folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="5eddf-119">ContactsFolder</span><span class="sxs-lookup"><span data-stu-id="5eddf-119">ContactsFolder</span></span>](contactsfolder.md) <br/> |<span data-ttu-id="5eddf-120">Representa una carpeta de contactos en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="5eddf-120">Represents a contacts folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="5eddf-121">SearchFolder</span><span class="sxs-lookup"><span data-stu-id="5eddf-121">SearchFolder</span></span>](searchfolder.md) <br/> |<span data-ttu-id="5eddf-122">Representa una carpeta de búsqueda en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="5eddf-122">Represents a search folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="5eddf-123">TasksFolder</span><span class="sxs-lookup"><span data-stu-id="5eddf-123">TasksFolder</span></span>](tasksfolder.md) <br/> |<span data-ttu-id="5eddf-124">Representa una carpeta de tareas en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="5eddf-124">Represents a task folder in a mailbox.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="5eddf-125">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="5eddf-125">Text value</span></span>

<span data-ttu-id="5eddf-126">El valor de texto representa un valor entero.</span><span class="sxs-lookup"><span data-stu-id="5eddf-126">The text value represents an integer value.</span></span> <span data-ttu-id="5eddf-127">Esta propiedad es de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="5eddf-127">This property is read-only.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="5eddf-128">Notas</span><span class="sxs-lookup"><span data-stu-id="5eddf-128">Remarks</span></span>

<span data-ttu-id="5eddf-129">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="5eddf-129">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="5eddf-130">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="5eddf-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5eddf-131">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="5eddf-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="5eddf-132">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="5eddf-132">Schema Name</span></span>  <br/> |<span data-ttu-id="5eddf-133">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="5eddf-133">Types schema</span></span>  <br/> |
|<span data-ttu-id="5eddf-134">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="5eddf-134">Validation File</span></span>  <br/> |<span data-ttu-id="5eddf-135">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="5eddf-135">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="5eddf-136">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="5eddf-136">Can be Empty</span></span>  <br/> |<span data-ttu-id="5eddf-137">False</span><span class="sxs-lookup"><span data-stu-id="5eddf-137">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="5eddf-138">Ver también</span><span class="sxs-lookup"><span data-stu-id="5eddf-138">See also</span></span>



- [<span data-ttu-id="5eddf-139">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="5eddf-139">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
