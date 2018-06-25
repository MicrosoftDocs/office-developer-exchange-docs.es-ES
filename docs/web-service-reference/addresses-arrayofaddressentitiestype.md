---
title: Direcciones (ArrayOfAddressEntitiesType)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 0c1f3fd3-1b78-46ee-8dd4-b2aff51e767e
description: El elemento de direcciones especifica una matriz de elementos de AddressEntity.
ms.openlocfilehash: b6fbcc54a016e698bccbe075fd340c0c784f121a
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/25/2018
ms.locfileid: "19763414"
---
# <a name="addresses-arrayofaddressentitiestype"></a><span data-ttu-id="342ed-103">Direcciones (ArrayOfAddressEntitiesType)</span><span class="sxs-lookup"><span data-stu-id="342ed-103">Addresses (ArrayOfAddressEntitiesType)</span></span>

<span data-ttu-id="342ed-104">El elemento de **direcciones** especifica una matriz de elementos de **AddressEntity** .</span><span class="sxs-lookup"><span data-stu-id="342ed-104">The **Addresses** element specifies an array of **AddressEntity** elements.</span></span> 
  
```XML
<Addresses>
   <AddressEntity/>
</Addresses>
```

 <span data-ttu-id="342ed-105">**ArrayOfAddressEntitiesType**</span><span class="sxs-lookup"><span data-stu-id="342ed-105">**ArrayOfAddressEntitiesType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="342ed-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="342ed-106">Attributes and elements</span></span>

<span data-ttu-id="342ed-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="342ed-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="342ed-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="342ed-108">Attributes</span></span>

<span data-ttu-id="342ed-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="342ed-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="342ed-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="342ed-110">Child elements</span></span>

|<span data-ttu-id="342ed-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="342ed-111">**Element**</span></span>|<span data-ttu-id="342ed-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="342ed-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="342ed-113">AddressEntity</span><span class="sxs-lookup"><span data-stu-id="342ed-113">AddressEntity</span></span>](addressentity.md) <br/> |<span data-ttu-id="342ed-114">Especifica una entidad única dirección.</span><span class="sxs-lookup"><span data-stu-id="342ed-114">Specifies a single address entity.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="342ed-115">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="342ed-115">Parent elements</span></span>

|<span data-ttu-id="342ed-116">**Element**</span><span class="sxs-lookup"><span data-stu-id="342ed-116">**Element**</span></span>|<span data-ttu-id="342ed-117">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="342ed-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="342ed-118">EntityExtractionResult</span><span class="sxs-lookup"><span data-stu-id="342ed-118">EntityExtractionResult</span></span>](entityextractionresult.md) <br/> |<span data-ttu-id="342ed-119">Especifica la propiedad **EntityExtractionResult** de un elemento.</span><span class="sxs-lookup"><span data-stu-id="342ed-119">Specifies the **EntityExtractionResult** property of an item.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="342ed-120">Comentarios</span><span class="sxs-lookup"><span data-stu-id="342ed-120">Remarks</span></span>

<span data-ttu-id="342ed-121">Este elemento se introdujo en Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="342ed-121">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="342ed-122">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="342ed-122">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="342ed-123">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="342ed-123">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="342ed-124">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="342ed-124">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="342ed-125">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="342ed-125">Schema Name</span></span>  <br/> |<span data-ttu-id="342ed-126">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="342ed-126">Type schema</span></span>  <br/> |
|<span data-ttu-id="342ed-127">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="342ed-127">Validation File</span></span>  <br/> |<span data-ttu-id="342ed-128">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="342ed-128">types.xsd</span></span>  <br/> |
|<span data-ttu-id="342ed-129">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="342ed-129">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="342ed-130">Vea también</span><span class="sxs-lookup"><span data-stu-id="342ed-130">See also</span></span>

- [<span data-ttu-id="342ed-131">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="342ed-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
