---
title: DeleteUserConfiguration
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DeleteUserConfiguration
api_type:
- schema
ms.assetid: 91b18b6a-d904-476c-996d-b041e859da1e
description: El elemento DeleteUserConfiguration representa una solicitud para eliminar un objeto de configuración de usuario.
ms.openlocfilehash: e357c32f95cddc866b77b6f1172ab260837b061b
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764105"
---
# <a name="deleteuserconfiguration"></a><span data-ttu-id="484fd-103">DeleteUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="484fd-103">DeleteUserConfiguration</span></span>

<span data-ttu-id="484fd-104">El elemento **DeleteUserConfiguration** representa una solicitud para eliminar un objeto de configuración de usuario.</span><span class="sxs-lookup"><span data-stu-id="484fd-104">The **DeleteUserConfiguration** element represents a request to delete a user configuration object.</span></span> 
  
```xml
<DeleteUserConfiguration>
   <UserConfigurationName/>
</DeleteUserConfiguration>
```

 <span data-ttu-id="484fd-105">**DeleteUserConfigurationType**</span><span class="sxs-lookup"><span data-stu-id="484fd-105">**DeleteUserConfigurationType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="484fd-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="484fd-106">Attributes and elements</span></span>

<span data-ttu-id="484fd-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="484fd-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="484fd-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="484fd-108">Attributes</span></span>

<span data-ttu-id="484fd-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="484fd-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="484fd-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="484fd-110">Child elements</span></span>

|<span data-ttu-id="484fd-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="484fd-111">**Element**</span></span>|<span data-ttu-id="484fd-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="484fd-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="484fd-113">UserConfigurationName</span><span class="sxs-lookup"><span data-stu-id="484fd-113">UserConfigurationName</span></span>](userconfigurationname.md) <br/> |<span data-ttu-id="484fd-114">Representa el nombre del objeto de configuración de usuario para eliminar.</span><span class="sxs-lookup"><span data-stu-id="484fd-114">Represents the name of the user configuration object to delete.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="484fd-115">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="484fd-115">Parent elements</span></span>

<span data-ttu-id="484fd-116">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="484fd-116">None.</span></span>
  
## <a name="text-value"></a><span data-ttu-id="484fd-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="484fd-117">Text value</span></span>

<span data-ttu-id="484fd-118">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="484fd-118">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="484fd-119">Observaciones</span><span class="sxs-lookup"><span data-stu-id="484fd-119">Remarks</span></span>

<span data-ttu-id="484fd-120">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="484fd-120">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="484fd-121">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="484fd-121">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="484fd-122">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="484fd-122">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="484fd-123">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="484fd-123">Schema Name</span></span>  <br/> |<span data-ttu-id="484fd-124">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="484fd-124">Messages schema</span></span>  <br/> |
|<span data-ttu-id="484fd-125">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="484fd-125">Validation File</span></span>  <br/> |<span data-ttu-id="484fd-126">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="484fd-126">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="484fd-127">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="484fd-127">Can be Empty</span></span>  <br/> |<span data-ttu-id="484fd-128">False</span><span class="sxs-lookup"><span data-stu-id="484fd-128">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="484fd-129">Ver también</span><span class="sxs-lookup"><span data-stu-id="484fd-129">See also</span></span>

- [<span data-ttu-id="484fd-130">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="484fd-130">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
