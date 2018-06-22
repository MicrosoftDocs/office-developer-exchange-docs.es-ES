---
title: GlobalParentFolderIds
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 8f5fcbcb-05ed-462a-99cf-a6b112a4aef6
description: El elemento GlobalParentFolderIds especifica los identificadores de las carpetas primarias global.
ms.openlocfilehash: b0ff9ab00f3e46351b5a2db9bc4b6282fa4385cd
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19835747"
---
# <a name="globalparentfolderids"></a><span data-ttu-id="8dc9d-103">GlobalParentFolderIds</span><span class="sxs-lookup"><span data-stu-id="8dc9d-103">GlobalParentFolderIds</span></span>

<span data-ttu-id="8dc9d-104">El elemento **GlobalParentFolderIds** especifica los identificadores de las carpetas primarias global.</span><span class="sxs-lookup"><span data-stu-id="8dc9d-104">The **GlobalParentFolderIds** element specifies the identifiers of the global parent folders.</span></span> 
  
```XML
<GlobalParentFolderIds>
    <FolderId/>
    <DistinguishedFolderId/>
</GlobalParentFolderIds>
```

 <span data-ttu-id="8dc9d-105">**NonEmptyArrayOfBaseFolderIdsType**</span><span class="sxs-lookup"><span data-stu-id="8dc9d-105">**NonEmptyArrayOfBaseFolderIdsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="8dc9d-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="8dc9d-106">Attributes and elements</span></span>

<span data-ttu-id="8dc9d-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="8dc9d-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="8dc9d-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="8dc9d-108">Attributes</span></span>

<span data-ttu-id="8dc9d-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="8dc9d-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="8dc9d-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="8dc9d-110">Child elements</span></span>

|<span data-ttu-id="8dc9d-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="8dc9d-111">**Element**</span></span>|<span data-ttu-id="8dc9d-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="8dc9d-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="8dc9d-113">FolderId</span><span class="sxs-lookup"><span data-stu-id="8dc9d-113">FolderId</span></span>](folderid.md) <br/> |<span data-ttu-id="8dc9d-114">Contiene el identificador y cambiar la clave de una carpeta.</span><span class="sxs-lookup"><span data-stu-id="8dc9d-114">Contains the identifier and change key of a folder.</span></span>  <br/> |
|[<span data-ttu-id="8dc9d-115">DistinguishedFolderId</span><span class="sxs-lookup"><span data-stu-id="8dc9d-115">DistinguishedFolderId</span></span>](distinguishedfolderid.md) <br/> |<span data-ttu-id="8dc9d-116">Identifica las carpetas que se pueden hacer referencia por su nombre.</span><span class="sxs-lookup"><span data-stu-id="8dc9d-116">Identifies folders that can be referenced by name.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="8dc9d-117">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="8dc9d-117">Parent elements</span></span>

|<span data-ttu-id="8dc9d-118">**Element**</span><span class="sxs-lookup"><span data-stu-id="8dc9d-118">**Element**</span></span>|<span data-ttu-id="8dc9d-119">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="8dc9d-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="8dc9d-120">Conversación (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="8dc9d-120">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="8dc9d-121">Representa una sola conversación.</span><span class="sxs-lookup"><span data-stu-id="8dc9d-121">Represents a single conversation.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="8dc9d-122">Notas</span><span class="sxs-lookup"><span data-stu-id="8dc9d-122">Remarks</span></span>

<span data-ttu-id="8dc9d-123">Este elemento se introdujo en Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="8dc9d-123">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="8dc9d-124">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="8dc9d-124">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="8dc9d-125">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="8dc9d-125">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="8dc9d-126">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="8dc9d-126">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="8dc9d-127">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="8dc9d-127">Schema Name</span></span>  <br/> |<span data-ttu-id="8dc9d-128">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="8dc9d-128">Type schema</span></span>  <br/> |
|<span data-ttu-id="8dc9d-129">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="8dc9d-129">Validation File</span></span>  <br/> |<span data-ttu-id="8dc9d-130">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="8dc9d-130">types.xsd</span></span>  <br/> |
|<span data-ttu-id="8dc9d-131">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="8dc9d-131">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="8dc9d-132">Ver también</span><span class="sxs-lookup"><span data-stu-id="8dc9d-132">See also</span></span>



- [<span data-ttu-id="8dc9d-133">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="8dc9d-133">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
