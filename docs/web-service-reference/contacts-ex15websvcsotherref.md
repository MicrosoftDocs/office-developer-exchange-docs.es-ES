---
title: Contactos
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Contacts
api_type:
- schema
ms.assetid: 0cc67cdf-9707-45e7-92c6-fa83a016cdbe
description: El elemento de contactos contiene una lista de contactos que están asociados con una tarea.
ms.openlocfilehash: da7963d30f58f7da52e76e3f7f1d0f7fd68abf74
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19763788"
---
# <a name="contacts"></a><span data-ttu-id="f1cd9-103">Contacts</span><span class="sxs-lookup"><span data-stu-id="f1cd9-103">Contacts</span></span>

<span data-ttu-id="f1cd9-104">El elemento de **contactos** contiene una lista de contactos que están asociados con una tarea.</span><span class="sxs-lookup"><span data-stu-id="f1cd9-104">The **Contacts** element contains a list of contacts that are associated with a task.</span></span> 
  
```xml
<Contacts>
   <String/>
</Contacts>
```

 <span data-ttu-id="f1cd9-105">**ArrayOfStringsType**</span><span class="sxs-lookup"><span data-stu-id="f1cd9-105">**ArrayOfStringsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="f1cd9-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="f1cd9-106">Attributes and elements</span></span>

<span data-ttu-id="f1cd9-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="f1cd9-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="f1cd9-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="f1cd9-108">Attributes</span></span>

<span data-ttu-id="f1cd9-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="f1cd9-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="f1cd9-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="f1cd9-110">Child elements</span></span>

|<span data-ttu-id="f1cd9-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="f1cd9-111">**Element**</span></span>|<span data-ttu-id="f1cd9-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="f1cd9-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="f1cd9-113">String</span><span class="sxs-lookup"><span data-stu-id="f1cd9-113">String</span></span>](string.md) <br/> |<span data-ttu-id="f1cd9-114">Representa una lista separada por comas de nombres de los contactos.</span><span class="sxs-lookup"><span data-stu-id="f1cd9-114">Represents a comma-separated list of contact names.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="f1cd9-115">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="f1cd9-115">Parent elements</span></span>

|<span data-ttu-id="f1cd9-116">**Element**</span><span class="sxs-lookup"><span data-stu-id="f1cd9-116">**Element**</span></span>|<span data-ttu-id="f1cd9-117">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="f1cd9-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="f1cd9-118">Tarea</span><span class="sxs-lookup"><span data-stu-id="f1cd9-118">Task</span></span>](task.md) <br/> |<span data-ttu-id="f1cd9-119">Representa una tarea en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="f1cd9-119">Represents a task in the Exchange store.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="f1cd9-120">Notas</span><span class="sxs-lookup"><span data-stu-id="f1cd9-120">Remarks</span></span>

<span data-ttu-id="f1cd9-121">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="f1cd9-121">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="f1cd9-122">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="f1cd9-122">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="f1cd9-123">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="f1cd9-123">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="f1cd9-124">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="f1cd9-124">Schema name</span></span>  <br/> |<span data-ttu-id="f1cd9-125">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="f1cd9-125">Types schema</span></span>  <br/> |
|<span data-ttu-id="f1cd9-126">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="f1cd9-126">Validation file</span></span>  <br/> |<span data-ttu-id="f1cd9-127">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="f1cd9-127">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="f1cd9-128">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="f1cd9-128">Can be empty</span></span>  <br/> |<span data-ttu-id="f1cd9-129">False</span><span class="sxs-lookup"><span data-stu-id="f1cd9-129">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="f1cd9-130">Ver también</span><span class="sxs-lookup"><span data-stu-id="f1cd9-130">See also</span></span>



- [<span data-ttu-id="f1cd9-131">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="f1cd9-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
