---
title: PermissionLevel
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- PermissionLevel
api_type:
- schema
ms.assetid: 87978600-3523-451e-a725-ef092c543e2a
description: El elemento PermissionLevel representa el nivel de permisos que un usuario tiene en una carpeta. Este elemento se introdujo en Microsoft Exchange Server 2007 Service Pack 1 (SP1).
ms.openlocfilehash: 7cc734f5807fe039467065315c220341f47d3fb4
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836730"
---
# <a name="permissionlevel"></a><span data-ttu-id="b57ae-104">PermissionLevel</span><span class="sxs-lookup"><span data-stu-id="b57ae-104">PermissionLevel</span></span>

<span data-ttu-id="b57ae-105">El elemento **PermissionLevel** representa el nivel de permisos que un usuario tiene en una carpeta.</span><span class="sxs-lookup"><span data-stu-id="b57ae-105">The **PermissionLevel** element represents the permission level that a user has on a folder.</span></span> <span data-ttu-id="b57ae-106">Este elemento se introdujo en Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="b57ae-106">This element was introduced in Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span></span> 
  
```xml
<PermissionLevel>None or Owner or PublishingEditor or Editor or PublishingAuthor or Author or NoneditingAuthor or Reviewer or Contributor or Custom</PermissionLevel>
```

 <span data-ttu-id="b57ae-107">**PermissionLevelType**</span><span class="sxs-lookup"><span data-stu-id="b57ae-107">**PermissionLevelType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="b57ae-108">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="b57ae-108">Attributes and elements</span></span>

<span data-ttu-id="b57ae-109">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="b57ae-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="b57ae-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="b57ae-110">Attributes</span></span>

<span data-ttu-id="b57ae-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="b57ae-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="b57ae-112">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="b57ae-112">Child elements</span></span>

<span data-ttu-id="b57ae-113">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="b57ae-113">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="b57ae-114">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="b57ae-114">Parent elements</span></span>

|<span data-ttu-id="b57ae-115">**Element**</span><span class="sxs-lookup"><span data-stu-id="b57ae-115">**Element**</span></span>|<span data-ttu-id="b57ae-116">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="b57ae-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="b57ae-117">Permission</span><span class="sxs-lookup"><span data-stu-id="b57ae-117">Permission</span></span>](permission.md) <br/> |<span data-ttu-id="b57ae-118">Define el acceso que tiene un usuario a una carpeta.</span><span class="sxs-lookup"><span data-stu-id="b57ae-118">Defines the access that a user has to a folder.</span></span> <span data-ttu-id="b57ae-119">Este elemento se introdujo en Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="b57ae-119">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="b57ae-120">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="b57ae-120">Text value</span></span>

<span data-ttu-id="b57ae-121">En la siguiente tabla se enumera los valores posibles para el elemento **PermissionLevel** .</span><span class="sxs-lookup"><span data-stu-id="b57ae-121">The following table lists the possible values for the **PermissionLevel** element.</span></span> 
  
<span data-ttu-id="b57ae-122">**Valores de texto de elemento PermissionLevel**</span><span class="sxs-lookup"><span data-stu-id="b57ae-122">**PermissionLevel element text values**</span></span>

|<span data-ttu-id="b57ae-123">**Valor**</span><span class="sxs-lookup"><span data-stu-id="b57ae-123">**Value**</span></span>|<span data-ttu-id="b57ae-124">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="b57ae-124">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="b57ae-125">None</span><span class="sxs-lookup"><span data-stu-id="b57ae-125">None</span></span>  <br/> |<span data-ttu-id="b57ae-126">Indica que el usuario no tiene permisos en la carpeta.</span><span class="sxs-lookup"><span data-stu-id="b57ae-126">Indicates that the user has no permissions on the folder.</span></span>  <br/> |
|<span data-ttu-id="b57ae-127">Owner</span><span class="sxs-lookup"><span data-stu-id="b57ae-127">Owner</span></span>  <br/> |<span data-ttu-id="b57ae-128">Indica que el usuario puede crear, leer, modificar y eliminar todos los elementos de la carpeta y crear subcarpetas.</span><span class="sxs-lookup"><span data-stu-id="b57ae-128">Indicates that the user can create, read, edit, and delete all items in the folder, and create subfolders.</span></span> <span data-ttu-id="b57ae-129">El usuario es el propietario de la carpeta y el contacto de la carpeta.</span><span class="sxs-lookup"><span data-stu-id="b57ae-129">The user is both folder owner and folder contact.</span></span>  <br/> |
|<span data-ttu-id="b57ae-130">PublishingEditor</span><span class="sxs-lookup"><span data-stu-id="b57ae-130">PublishingEditor</span></span>  <br/> |<span data-ttu-id="b57ae-131">Indica que el usuario puede crear, leer, modificar y eliminar todos los elementos de la carpeta y crear subcarpetas.</span><span class="sxs-lookup"><span data-stu-id="b57ae-131">Indicates that the user can create, read, edit, and delete all items in the folder, and create subfolders.</span></span>  <br/> |
|<span data-ttu-id="b57ae-132">Editor</span><span class="sxs-lookup"><span data-stu-id="b57ae-132">Editor</span></span>  <br/> |<span data-ttu-id="b57ae-133">Indica que el usuario puede crear, leer, editar y eliminar todos los elementos de la carpeta.</span><span class="sxs-lookup"><span data-stu-id="b57ae-133">Indicates that the user can create, read, edit, and delete all items in the folder.</span></span>  <br/> |
|<span data-ttu-id="b57ae-134">PublishingAuthor</span><span class="sxs-lookup"><span data-stu-id="b57ae-134">PublishingAuthor</span></span>  <br/> |<span data-ttu-id="b57ae-135">Indica que el usuario puede crear y leer todos los elementos en la carpeta, editar y eliminar sólo los elementos que crea el usuario y crear subcarpetas.</span><span class="sxs-lookup"><span data-stu-id="b57ae-135">Indicates that the user can create and read all items in the folder, edit and delete only items that the user creates, and create subfolders.</span></span>  <br/> |
|<span data-ttu-id="b57ae-136">Autor</span><span class="sxs-lookup"><span data-stu-id="b57ae-136">Author</span></span>  <br/> |<span data-ttu-id="b57ae-137">Indica que el usuario puede crear y leer todos los elementos en la carpeta y editar y eliminar sólo los elementos que crea el usuario.</span><span class="sxs-lookup"><span data-stu-id="b57ae-137">Indicates that the user can create and read all items in the folder, and edit and delete only items that the user creates.</span></span>  <br/> |
|<span data-ttu-id="b57ae-138">NoneditingAuthor</span><span class="sxs-lookup"><span data-stu-id="b57ae-138">NoneditingAuthor</span></span>  <br/> |<span data-ttu-id="b57ae-139">Indica que el usuario puede crear y leer todos los elementos en la carpeta y eliminar sólo los elementos que crea el usuario.</span><span class="sxs-lookup"><span data-stu-id="b57ae-139">Indicates that the user can create and read all items in the folder, and delete only items that the user creates.</span></span>  <br/> |
|<span data-ttu-id="b57ae-140">Reviewer</span><span class="sxs-lookup"><span data-stu-id="b57ae-140">Reviewer</span></span>  <br/> |<span data-ttu-id="b57ae-141">Indica que el usuario puede leer todos los elementos de la carpeta.</span><span class="sxs-lookup"><span data-stu-id="b57ae-141">Indicates that the user can read all items in the folder.</span></span>  <br/> |
|<span data-ttu-id="b57ae-142">Colaborador</span><span class="sxs-lookup"><span data-stu-id="b57ae-142">Contributor</span></span>  <br/> |<span data-ttu-id="b57ae-143">Indica que el usuario puede crear elementos en la carpeta.</span><span class="sxs-lookup"><span data-stu-id="b57ae-143">Indicates that the user can create items in the folder.</span></span> <span data-ttu-id="b57ae-144">El contenido de la carpeta no aparecen.</span><span class="sxs-lookup"><span data-stu-id="b57ae-144">The contents of the folder do not appear.</span></span>  <br/> |
|<span data-ttu-id="b57ae-145">Personalizado</span><span class="sxs-lookup"><span data-stu-id="b57ae-145">Custom</span></span>  <br/> |<span data-ttu-id="b57ae-146">Indica que el usuario tiene permisos de acceso personalizados en la carpeta.</span><span class="sxs-lookup"><span data-stu-id="b57ae-146">Indicates that the user has custom access permissions on the folder.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="b57ae-147">Notas</span><span class="sxs-lookup"><span data-stu-id="b57ae-147">Remarks</span></span>

<span data-ttu-id="b57ae-148">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que ejecuta Microsoft Exchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="b57ae-148">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="b57ae-149">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="b57ae-149">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="b57ae-150">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="b57ae-150">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="b57ae-151">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="b57ae-151">Schema Name</span></span>  <br/> |<span data-ttu-id="b57ae-152">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="b57ae-152">Types schema</span></span>  <br/> |
|<span data-ttu-id="b57ae-153">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="b57ae-153">Validation File</span></span>  <br/> |<span data-ttu-id="b57ae-154">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="b57ae-154">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="b57ae-155">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="b57ae-155">Can be Empty</span></span>  <br/> |<span data-ttu-id="b57ae-156">False</span><span class="sxs-lookup"><span data-stu-id="b57ae-156">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="b57ae-157">Ver también</span><span class="sxs-lookup"><span data-stu-id="b57ae-157">See also</span></span>



- [<span data-ttu-id="b57ae-158">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="b57ae-158">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)


[<span data-ttu-id="b57ae-159">Establecimiento de permisos de nivel de carpeta</span><span class="sxs-lookup"><span data-stu-id="b57ae-159">Setting Folder-Level Permissions</span></span>](http://msdn.microsoft.com/library/c7530e86-5112-401c-b10a-9c054ae59f07%28Office.15%29.aspx)
