---
title: UpdateUserConfiguration
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- UpdateUserConfiguration
api_type:
- schema
ms.assetid: ccf7c577-f882-477e-9f6f-2f56729f7d77
description: El elemento UpdateUserConfiguration representa una solicitud para actualizar un objeto de configuración de usuario.
ms.openlocfilehash: 54415677786d8d5b6579f42e6d384c087099ce03
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19840864"
---
# <a name="updateuserconfiguration"></a><span data-ttu-id="39f40-103">UpdateUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="39f40-103">UpdateUserConfiguration</span></span>

<span data-ttu-id="39f40-104">El elemento **UpdateUserConfiguration** representa una solicitud para actualizar un objeto de configuración de usuario.</span><span class="sxs-lookup"><span data-stu-id="39f40-104">The **UpdateUserConfiguration** element represents a request to update a user configuration object.</span></span> 
  
```XML
<UpdateUserConfiguration>
   <UserConfiguration/>
</UpdateUserConfiguration>
```

 <span data-ttu-id="39f40-105">**UpdateUserConfigurationType**</span><span class="sxs-lookup"><span data-stu-id="39f40-105">**UpdateUserConfigurationType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="39f40-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="39f40-106">Attributes and elements</span></span>

<span data-ttu-id="39f40-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="39f40-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="39f40-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="39f40-108">Attributes</span></span>

<span data-ttu-id="39f40-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="39f40-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="39f40-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="39f40-110">Child elements</span></span>

|<span data-ttu-id="39f40-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="39f40-111">**Element**</span></span>|<span data-ttu-id="39f40-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="39f40-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="39f40-113">UserConfiguration</span><span class="sxs-lookup"><span data-stu-id="39f40-113">UserConfiguration</span></span>](userconfiguration.md) <br/> |<span data-ttu-id="39f40-114">Define un objeto de configuración de usuario único.</span><span class="sxs-lookup"><span data-stu-id="39f40-114">Defines a single user configuration object.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="39f40-115">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="39f40-115">Parent elements</span></span>

<span data-ttu-id="39f40-116">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="39f40-116">None.</span></span>
  
## <a name="text-value"></a><span data-ttu-id="39f40-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="39f40-117">Text value</span></span>

<span data-ttu-id="39f40-118">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="39f40-118">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="39f40-119">Observaciones</span><span class="sxs-lookup"><span data-stu-id="39f40-119">Remarks</span></span>

<span data-ttu-id="39f40-120">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="39f40-120">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="39f40-121">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="39f40-121">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="39f40-122">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="39f40-122">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="39f40-123">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="39f40-123">Schema Name</span></span>  <br/> |<span data-ttu-id="39f40-124">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="39f40-124">Messages schema</span></span>  <br/> |
|<span data-ttu-id="39f40-125">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="39f40-125">Validation File</span></span>  <br/> |<span data-ttu-id="39f40-126">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="39f40-126">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="39f40-127">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="39f40-127">Can be Empty</span></span>  <br/> |<span data-ttu-id="39f40-128">False</span><span class="sxs-lookup"><span data-stu-id="39f40-128">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="39f40-129">Ver también</span><span class="sxs-lookup"><span data-stu-id="39f40-129">See also</span></span>



- [<span data-ttu-id="39f40-130">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="39f40-130">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
