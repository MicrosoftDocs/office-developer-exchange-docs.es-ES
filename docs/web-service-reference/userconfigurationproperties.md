---
title: UserConfigurationProperties
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- UserConfigurationProperties
api_type:
- schema
ms.assetid: c143a6ec-62ad-4d48-b844-b1ad88054bc1
description: El elemento UserConfigurationProperties especifica los tipos de propiedad para obtener en una operación de GetUserConfiguration.
ms.openlocfilehash: 4f993765bb7c36f28a41a3f2fa7e28698a3f709e
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19840904"
---
# <a name="userconfigurationproperties"></a><span data-ttu-id="f29fd-103">UserConfigurationProperties</span><span class="sxs-lookup"><span data-stu-id="f29fd-103">UserConfigurationProperties</span></span>

<span data-ttu-id="f29fd-104">El elemento **UserConfigurationProperties** especifica los tipos de propiedad para obtener en una operación de GetUserConfiguration.</span><span class="sxs-lookup"><span data-stu-id="f29fd-104">The **UserConfigurationProperties** element specifies the property types to get in a GetUserConfiguration operation.</span></span> 
  
```xml
<UserConfigurationProperties>Id | Dictionary | XmlData | BinaryData | All</UserConfigurationProperties>
```

 <span data-ttu-id="f29fd-105">**UserConfigurationPropertyType**</span><span class="sxs-lookup"><span data-stu-id="f29fd-105">**UserConfigurationPropertyType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="f29fd-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="f29fd-106">Attributes and elements</span></span>

<span data-ttu-id="f29fd-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="f29fd-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="f29fd-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="f29fd-108">Attributes</span></span>

<span data-ttu-id="f29fd-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="f29fd-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="f29fd-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="f29fd-110">Child elements</span></span>

<span data-ttu-id="f29fd-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="f29fd-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="f29fd-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="f29fd-112">Parent elements</span></span>

|<span data-ttu-id="f29fd-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="f29fd-113">**Element**</span></span>|<span data-ttu-id="f29fd-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="f29fd-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="f29fd-115">GetUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="f29fd-115">GetUserConfiguration</span></span>](getuserconfiguration.md) <br/> |<span data-ttu-id="f29fd-116">Especifica una solicitud para obtener un objeto de configuración de usuario.</span><span class="sxs-lookup"><span data-stu-id="f29fd-116">Specifies a request to get a user configuration object.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="f29fd-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="f29fd-117">Text value</span></span>

<span data-ttu-id="f29fd-118">En la siguiente tabla se enumera los valores posibles para el elemento **UserConfigurationProperties** .</span><span class="sxs-lookup"><span data-stu-id="f29fd-118">The following table lists the possible values for the **UserConfigurationProperties** element.</span></span> 
  
|<span data-ttu-id="f29fd-119">**Valor**</span><span class="sxs-lookup"><span data-stu-id="f29fd-119">**Value**</span></span>|<span data-ttu-id="f29fd-120">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="f29fd-120">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="f29fd-121">Id</span><span class="sxs-lookup"><span data-stu-id="f29fd-121">Id</span></span>  <br/> |<span data-ttu-id="f29fd-122">Especifica la propiedad del identificador.</span><span class="sxs-lookup"><span data-stu-id="f29fd-122">Specifies the identifier property.</span></span>  <br/> |
|<span data-ttu-id="f29fd-123">Dictionary</span><span class="sxs-lookup"><span data-stu-id="f29fd-123">Dictionary</span></span>  <br/> |<span data-ttu-id="f29fd-124">Especifica los tipos de propiedad de diccionario.</span><span class="sxs-lookup"><span data-stu-id="f29fd-124">Specifies dictionary property types.</span></span>  <br/> |
|<span data-ttu-id="f29fd-125">Nota</span><span class="sxs-lookup"><span data-stu-id="f29fd-125">XmlData</span></span>  <br/> |<span data-ttu-id="f29fd-126">Especifica los tipos de propiedad de datos XML.</span><span class="sxs-lookup"><span data-stu-id="f29fd-126">Specifies XML data property types.</span></span>  <br/> |
|<span data-ttu-id="f29fd-127">BinaryData</span><span class="sxs-lookup"><span data-stu-id="f29fd-127">BinaryData</span></span>  <br/> |<span data-ttu-id="f29fd-128">Especifica los tipos de datos binarios (propiedad).</span><span class="sxs-lookup"><span data-stu-id="f29fd-128">Specifies binary data property types.</span></span>  <br/> |
|<span data-ttu-id="f29fd-129">Todos</span><span class="sxs-lookup"><span data-stu-id="f29fd-129">All</span></span>  <br/> |<span data-ttu-id="f29fd-130">Especifica el identificador, diccionario, datos XML y tipos de datos binarios (propiedad).</span><span class="sxs-lookup"><span data-stu-id="f29fd-130">Specifies the identifier, dictionary, XML data, and binary data property types.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="f29fd-131">Notas</span><span class="sxs-lookup"><span data-stu-id="f29fd-131">Remarks</span></span>

<span data-ttu-id="f29fd-132">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="f29fd-132">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="f29fd-133">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="f29fd-133">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="f29fd-134">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="f29fd-134">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="f29fd-135">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="f29fd-135">Schema Name</span></span>  <br/> |<span data-ttu-id="f29fd-136">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="f29fd-136">Messages schema</span></span>  <br/> |
|<span data-ttu-id="f29fd-137">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="f29fd-137">Validation File</span></span>  <br/> |<span data-ttu-id="f29fd-138">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="f29fd-138">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="f29fd-139">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="f29fd-139">Can be Empty</span></span>  <br/> |<span data-ttu-id="f29fd-140">False</span><span class="sxs-lookup"><span data-stu-id="f29fd-140">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="f29fd-141">Ver también</span><span class="sxs-lookup"><span data-stu-id="f29fd-141">See also</span></span>



- [<span data-ttu-id="f29fd-142">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="f29fd-142">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
