---
title: IsPermanentFailure
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 18dc3a97-cc0a-4092-934e-a6e86f52e668
description: El elemento IsPermanentFailure indica si un intento anterior de índice del elemento se ha realizado correctamente.
ms.openlocfilehash: 39592c15394a57e1c6aa1183ed0ccedeb085e6ea
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836085"
---
# <a name="ispermanentfailure"></a><span data-ttu-id="bd958-103">IsPermanentFailure</span><span class="sxs-lookup"><span data-stu-id="bd958-103">IsPermanentFailure</span></span>

<span data-ttu-id="bd958-104">El elemento **IsPermanentFailure** indica si un intento anterior de índice del elemento se ha realizado correctamente.</span><span class="sxs-lookup"><span data-stu-id="bd958-104">The **IsPermanentFailure** element indicates whether a previous attempt to index the item was unsuccessful.</span></span> 
  
```XML
<IsPermanentFailure>true | false</IsPermanentFailure>
```

 <span data-ttu-id="bd958-105">**Boolean**</span><span class="sxs-lookup"><span data-stu-id="bd958-105">**Boolean**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="bd958-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="bd958-106">Attributes and elements</span></span>

<span data-ttu-id="bd958-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="bd958-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="bd958-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="bd958-108">Attributes</span></span>

<span data-ttu-id="bd958-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="bd958-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="bd958-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="bd958-110">Child elements</span></span>

<span data-ttu-id="bd958-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="bd958-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="bd958-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="bd958-112">Parent elements</span></span>

[<span data-ttu-id="bd958-113">NonIndexableItemDetail</span><span class="sxs-lookup"><span data-stu-id="bd958-113">NonIndexableItemDetail</span></span>](nonindexableitemdetail.md)
  
## <a name="text-value"></a><span data-ttu-id="bd958-114">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="bd958-114">Text value</span></span>

<span data-ttu-id="bd958-115">Un valor de texto de **true** para el elemento **IsPermanentFailure** indica que un intento anterior de índice del elemento de buzón de correo ha podido realizar.</span><span class="sxs-lookup"><span data-stu-id="bd958-115">A text value of **true** for the **IsPermanentFailure** element indicates that a previous attempt to index the mailbox item was unsuccessful.</span></span> <span data-ttu-id="bd958-116">Un valor de **false** indica que un intento anterior de índice del elemento de buzón de correo se realizó correctamente.</span><span class="sxs-lookup"><span data-stu-id="bd958-116">A value of **false** indicates that a previous attempt to index the mailbox item was successful.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="bd958-117">Notas</span><span class="sxs-lookup"><span data-stu-id="bd958-117">Remarks</span></span>

<span data-ttu-id="bd958-118">Este elemento se introdujo en Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="bd958-118">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="bd958-119">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="bd958-119">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="bd958-120">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="bd958-120">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="bd958-121">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="bd958-121">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="bd958-122">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="bd958-122">Schema name</span></span>  <br/> |<span data-ttu-id="bd958-123">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="bd958-123">Types schema</span></span>  <br/> |
|<span data-ttu-id="bd958-124">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="bd958-124">Validation file</span></span>  <br/> |<span data-ttu-id="bd958-125">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="bd958-125">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="bd958-126">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="bd958-126">Can be empty</span></span>  <br/> |<span data-ttu-id="bd958-127">falso</span><span class="sxs-lookup"><span data-stu-id="bd958-127">false</span></span>  <br/> |
   
