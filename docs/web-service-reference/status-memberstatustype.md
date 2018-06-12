---
title: Estado (MemberStatusType)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Status
api_type:
- schema
ms.assetid: 4f8a860b-0a48-4a0d-9a7a-69a0304aa747
description: El elemento de estado proporciona información sobre el estado de un miembro de la lista de distribución en el servidor.
ms.openlocfilehash: ef062433c80f0cca413c33012e1164b17e226faf
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837580"
---
# <a name="status-memberstatustype"></a><span data-ttu-id="5c35a-103">Estado (MemberStatusType)</span><span class="sxs-lookup"><span data-stu-id="5c35a-103">Status (MemberStatusType)</span></span>

<span data-ttu-id="5c35a-104">El elemento de **estado** proporciona información sobre el estado de un miembro de la lista de distribución en el servidor.</span><span class="sxs-lookup"><span data-stu-id="5c35a-104">The **Status** element provides information about the status of a distribution list member on the server.</span></span> 
  
```
<Status>Unrecognized or Normal or Demoted</Status>
```

 <span data-ttu-id="5c35a-105">**MemberStatusType**</span><span class="sxs-lookup"><span data-stu-id="5c35a-105">**MemberStatusType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="5c35a-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="5c35a-106">Attributes and elements</span></span>

<span data-ttu-id="5c35a-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="5c35a-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="5c35a-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="5c35a-108">Attributes</span></span>

<span data-ttu-id="5c35a-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="5c35a-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="5c35a-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="5c35a-110">Child elements</span></span>

<span data-ttu-id="5c35a-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="5c35a-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="5c35a-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="5c35a-112">Parent elements</span></span>

|<span data-ttu-id="5c35a-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="5c35a-113">**Element**</span></span>|<span data-ttu-id="5c35a-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="5c35a-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="5c35a-115">Elemento</span><span class="sxs-lookup"><span data-stu-id="5c35a-115">Member</span></span>](member-ex15websvcsotherref.md) <br/> |<span data-ttu-id="5c35a-116">Representa a un miembro de una lista de distribución.</span><span class="sxs-lookup"><span data-stu-id="5c35a-116">Represents a member of a distribution list.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="5c35a-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="5c35a-117">Text value</span></span>

<span data-ttu-id="5c35a-118">En la siguiente tabla se enumera los valores posibles para el elemento **Status** .</span><span class="sxs-lookup"><span data-stu-id="5c35a-118">The following table lists the possible values for the **Status** element.</span></span> 
  
<span data-ttu-id="5c35a-119">**Valores de estado de elemento**</span><span class="sxs-lookup"><span data-stu-id="5c35a-119">**Status element values**</span></span>

|<span data-ttu-id="5c35a-120">**Valor**</span><span class="sxs-lookup"><span data-stu-id="5c35a-120">**Value**</span></span>|<span data-ttu-id="5c35a-121">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="5c35a-121">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="5c35a-122">No reconocido</span><span class="sxs-lookup"><span data-stu-id="5c35a-122">Unrecognized</span></span>  <br/> |<span data-ttu-id="5c35a-123">Información de miembro no es válido o no reconocido.</span><span class="sxs-lookup"><span data-stu-id="5c35a-123">Member information is invalid or unrecognized.</span></span>  <br/> |
|<span data-ttu-id="5c35a-124">Importance</span><span class="sxs-lookup"><span data-stu-id="5c35a-124">Normal</span></span>  <br/> |<span data-ttu-id="5c35a-125">Información de miembros en una lista de distribución está sincronizada con el objeto de referencia.</span><span class="sxs-lookup"><span data-stu-id="5c35a-125">Member information in a distribution list is in sync with the referenced object.</span></span>  <br/> |
|<span data-ttu-id="5c35a-126">Cuyo nivel ha disminuido</span><span class="sxs-lookup"><span data-stu-id="5c35a-126">Demoted</span></span>  <br/> |<span data-ttu-id="5c35a-127">Objeto que se hace referencia no está disponible.</span><span class="sxs-lookup"><span data-stu-id="5c35a-127">Referenced object is not available.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="5c35a-128">Notas</span><span class="sxs-lookup"><span data-stu-id="5c35a-128">Remarks</span></span>

<span data-ttu-id="5c35a-129">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que ejecuta Microsoft Exchange Server que tiene instalada la función del servidor acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="5c35a-129">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="5c35a-130">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="5c35a-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5c35a-131">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="5c35a-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="5c35a-132">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="5c35a-132">Schema Name</span></span>  <br/> |<span data-ttu-id="5c35a-133">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="5c35a-133">Types schema</span></span>  <br/> |
|<span data-ttu-id="5c35a-134">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="5c35a-134">Validation File</span></span>  <br/> |<span data-ttu-id="5c35a-135">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="5c35a-135">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="5c35a-136">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="5c35a-136">Can be Empty</span></span>  <br/> |<span data-ttu-id="5c35a-137">False</span><span class="sxs-lookup"><span data-stu-id="5c35a-137">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="5c35a-138">Ver también</span><span class="sxs-lookup"><span data-stu-id="5c35a-138">See also</span></span>



- [<span data-ttu-id="5c35a-139">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="5c35a-139">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
