---
title: IsEnabled
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IsEnabled
api_type:
- schema
ms.assetid: c7e3035e-a4ef-4c11-8cb0-214790a554ff
description: El elemento IsEnabled indica si está habilitada la regla.
ms.openlocfilehash: d0f0a77ec1ec952ac1cd9d9ad686ccfcb8f70c42
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836000"
---
# <a name="isenabled"></a><span data-ttu-id="38e4e-103">IsEnabled</span><span class="sxs-lookup"><span data-stu-id="38e4e-103">IsEnabled</span></span>

<span data-ttu-id="38e4e-104">El elemento **IsEnabled** indica si está habilitada la regla.</span><span class="sxs-lookup"><span data-stu-id="38e4e-104">The **IsEnabled** element indicates whether the rule is enabled.</span></span> 
  
```XML
<IsEnabled/>
```

 <span data-ttu-id="38e4e-105">**Boolean**</span><span class="sxs-lookup"><span data-stu-id="38e4e-105">**Boolean**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="38e4e-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="38e4e-106">Attributes and elements</span></span>

<span data-ttu-id="38e4e-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="38e4e-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="38e4e-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="38e4e-108">Attributes</span></span>

<span data-ttu-id="38e4e-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="38e4e-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="38e4e-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="38e4e-110">Child elements</span></span>

<span data-ttu-id="38e4e-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="38e4e-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="38e4e-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="38e4e-112">Parent elements</span></span>

|<span data-ttu-id="38e4e-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="38e4e-113">**Element**</span></span>|<span data-ttu-id="38e4e-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="38e4e-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="38e4e-115">Regla (RuleType)</span><span class="sxs-lookup"><span data-stu-id="38e4e-115">Rule (RuleType)</span></span>](rule-ruletype.md) <br/> |<span data-ttu-id="38e4e-116">Representa una regla en el buzón del usuario.</span><span class="sxs-lookup"><span data-stu-id="38e4e-116">Represents a rule in the user's mailbox.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="38e4e-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="38e4e-117">Text value</span></span>

<span data-ttu-id="38e4e-118">Un valor de texto de **true** indica que la regla está habilitada y se puede ejecutar.</span><span class="sxs-lookup"><span data-stu-id="38e4e-118">A text value of **true** indicates that the rule is enabled and can be executed.</span></span> <span data-ttu-id="38e4e-119">Un valor de **false** indica que no se puede ejecutar la regla.</span><span class="sxs-lookup"><span data-stu-id="38e4e-119">A value of **false** indicates that the rule cannot be executed.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="38e4e-120">Notas</span><span class="sxs-lookup"><span data-stu-id="38e4e-120">Remarks</span></span>

<span data-ttu-id="38e4e-121">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="38e4e-121">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="38e4e-122">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="38e4e-122">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="38e4e-123">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="38e4e-123">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="38e4e-124">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="38e4e-124">Schema Name</span></span>  <br/> |<span data-ttu-id="38e4e-125">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="38e4e-125">Messages schema</span></span>  <br/> |
|<span data-ttu-id="38e4e-126">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="38e4e-126">Validation File</span></span>  <br/> |<span data-ttu-id="38e4e-127">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="38e4e-127">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="38e4e-128">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="38e4e-128">Can be Empty</span></span>  <br/> |<span data-ttu-id="38e4e-129">Verdadero</span><span class="sxs-lookup"><span data-stu-id="38e4e-129">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="38e4e-130">Ver también</span><span class="sxs-lookup"><span data-stu-id="38e4e-130">See also</span></span>



- [<span data-ttu-id="38e4e-131">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="38e4e-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
