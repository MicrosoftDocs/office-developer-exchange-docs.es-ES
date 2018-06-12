---
title: SearchItemKind
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 89513c26-b751-4619-a300-0ed8f55b0102
description: El elemento SearchItemKind indica el tipo de elementos que se buscan para una operación de FindMailboxStatisticsByKeyword.
ms.openlocfilehash: 1c099fc49ec882c1672b265ff0e3aa2c71c5f95b
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837298"
---
# <a name="searchitemkind"></a><span data-ttu-id="bcdfc-103">SearchItemKind</span><span class="sxs-lookup"><span data-stu-id="bcdfc-103">SearchItemKind</span></span>

<span data-ttu-id="bcdfc-104">El elemento **SearchItemKind** indica el tipo de elementos que se buscan para una operación de **FindMailboxStatisticsByKeyword** .</span><span class="sxs-lookup"><span data-stu-id="bcdfc-104">The **SearchItemKind** element indicates the type of items that are searched for a **FindMailboxStatisticsByKeyword** operation.</span></span> 
  
```XML
<SearchItemKind>Email | Meetings | Tasks | Notes | Docs | Journals | Contacts | Im | Voicemail | Faxes | Posts | Rssfeeds</SearchItemKind>
```

 <span data-ttu-id="bcdfc-105">**SearchItemKindType**</span><span class="sxs-lookup"><span data-stu-id="bcdfc-105">**SearchItemKindType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="bcdfc-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="bcdfc-106">Attributes and elements</span></span>

<span data-ttu-id="bcdfc-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="bcdfc-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="bcdfc-108">Attributes</span></span>

<span data-ttu-id="bcdfc-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="bcdfc-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="bcdfc-110">Child elements</span></span>

<span data-ttu-id="bcdfc-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="bcdfc-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="bcdfc-112">Parent elements</span></span>

[<span data-ttu-id="bcdfc-113">MessageTypes</span><span class="sxs-lookup"><span data-stu-id="bcdfc-113">MessageTypes</span></span>](messagetypes.md)
  
## <a name="text-value"></a><span data-ttu-id="bcdfc-114">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="bcdfc-114">Text value</span></span>

<span data-ttu-id="bcdfc-115">El valor de texto del elemento **SearchItemKind** es el tipo de elemento que se va a buscar palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-115">The text value of the **SearchItemKind** element is the type of item that is searched for keywords.</span></span> <span data-ttu-id="bcdfc-116">En la lista siguiente contiene los valores de texto que se pueden usar en el elemento **SearchItemKind** .</span><span class="sxs-lookup"><span data-stu-id="bcdfc-116">The following list contains the text values that can be used in the **SearchItemKind** element.</span></span> 
  
- <span data-ttu-id="bcdfc-117">**Correo electrónico** - indica que los mensajes de correo electrónico se buscan las palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-117">**Email** - Indicates that email messages are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-118">**Las reuniones** , indica que las reuniones se buscan las palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-118">**Meetings** - Indicates that meetings are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-119">**Tareas** - indica que las tareas se buscan las palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-119">**Tasks** - Indicates that tasks are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-120">**Notas** - indica que se buscarán palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-120">**Notes** - Indicates that notes are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-121">**Documentos** - indica que se buscan documentos para palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-121">**Docs** - Indicates that documents are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-122">**Diarios** - indica que se buscan diarios para palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-122">**Journals** - Indicates that journals are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-123">**Contactos** - indica que los contactos se buscan las palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-123">**Contacts** - Indicates that contacts are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-124">**Mensajería instantánea** - indica que los mensajes instantáneos se buscan las palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-124">**Im** - Indicates that instant messages are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-125">**Correo de voz** - indica que los correos de voz se buscan las palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-125">**Voicemail** - Indicates that voice mails are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-126">**Faxes** - indica que los faxes se buscan las palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-126">**Faxes** - Indicates that faxes are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-127">**Entradas de** - indica que se desea buscar entradas de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-127">**Posts** - Indicates that posts are searched for keywords.</span></span> 
    
- <span data-ttu-id="bcdfc-128">**Rssfeeds** - indica que se buscan las fuentes RSS para palabras clave.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-128">**Rssfeeds** - Indicates that RSS feeds are searched for keywords.</span></span> 
    
## <a name="remarks"></a><span data-ttu-id="bcdfc-129">Notas</span><span class="sxs-lookup"><span data-stu-id="bcdfc-129">Remarks</span></span>

<span data-ttu-id="bcdfc-130">Este elemento se introdujo en Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-130">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="bcdfc-131">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="bcdfc-131">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="bcdfc-132">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="bcdfc-132">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="bcdfc-133">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="bcdfc-133">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="bcdfc-134">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="bcdfc-134">Schema name</span></span>  <br/> |<span data-ttu-id="bcdfc-135">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="bcdfc-135">Types schema</span></span>  <br/> |
|<span data-ttu-id="bcdfc-136">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="bcdfc-136">Validation file</span></span>  <br/> |<span data-ttu-id="bcdfc-137">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="bcdfc-137">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="bcdfc-138">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="bcdfc-138">Can be empty</span></span>  <br/> ||
   
