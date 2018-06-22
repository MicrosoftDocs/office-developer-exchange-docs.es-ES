---
title: EffectiveRights
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- EffectiveRights
api_type:
- schema
ms.assetid: bf5278eb-3a1a-4d27-9d16-b8be043bb023
description: El elemento EffectiveRights contiene los derechos del cliente en función de la configuración de permisos para el elemento o la carpeta. Este elemento es de sólo lectura.
ms.openlocfilehash: 610d9e214a8de648ece667799bb5e67dfcc358f7
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764320"
---
# <a name="effectiverights"></a><span data-ttu-id="52362-104">EffectiveRights</span><span class="sxs-lookup"><span data-stu-id="52362-104">EffectiveRights</span></span>

<span data-ttu-id="52362-105">El elemento **EffectiveRights** contiene los derechos del cliente en función de la configuración de permisos para el elemento o la carpeta.</span><span class="sxs-lookup"><span data-stu-id="52362-105">The **EffectiveRights** element contains the client's rights based on the permission settings for the item or folder.</span></span> <span data-ttu-id="52362-106">Este elemento es de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="52362-106">This element is read-only.</span></span> 
  
```XML
<EffectiveRights>
   <CreateAssociated/>
   <CreateContents/>
   <CreateHierarchy/>
   <Delete/>
   <Modify/>
   <Read/>
   <ViewPrivateItems/>
</EffectiveRights>
```

 <span data-ttu-id="52362-107">**EffectiveRightsType**</span><span class="sxs-lookup"><span data-stu-id="52362-107">**EffectiveRightsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="52362-108">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="52362-108">Attributes and elements</span></span>

<span data-ttu-id="52362-109">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="52362-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="52362-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="52362-110">Attributes</span></span>

<span data-ttu-id="52362-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="52362-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="52362-112">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="52362-112">Child elements</span></span>

|<span data-ttu-id="52362-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="52362-113">**Element**</span></span>|<span data-ttu-id="52362-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="52362-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="52362-115">CreateAssociated</span><span class="sxs-lookup"><span data-stu-id="52362-115">CreateAssociated</span></span>](createassociated.md) <br/> |<span data-ttu-id="52362-116">Indica si un cliente puede crear una tabla de contenido asociada.</span><span class="sxs-lookup"><span data-stu-id="52362-116">Indicates whether a client can create an associated contents table.</span></span> <span data-ttu-id="52362-117">Esta propiedad sólo se utiliza en objetos folder.</span><span class="sxs-lookup"><span data-stu-id="52362-117">This property is only used on folder objects.</span></span>  <br/> |
|[<span data-ttu-id="52362-118">CreateContents</span><span class="sxs-lookup"><span data-stu-id="52362-118">CreateContents</span></span>](createcontents.md) <br/> |<span data-ttu-id="52362-119">Indica si un cliente puede crear una tabla de contenido.</span><span class="sxs-lookup"><span data-stu-id="52362-119">Indicates whether a client can create a contents table.</span></span> <span data-ttu-id="52362-120">Esta propiedad sólo se utiliza en objetos folder.</span><span class="sxs-lookup"><span data-stu-id="52362-120">This property is only used on folder objects.</span></span>  <br/> |
|[<span data-ttu-id="52362-121">CreateHierarchy</span><span class="sxs-lookup"><span data-stu-id="52362-121">CreateHierarchy</span></span>](createhierarchy.md) <br/> |<span data-ttu-id="52362-122">Indica si un cliente puede crear una tabla de jerarquía.</span><span class="sxs-lookup"><span data-stu-id="52362-122">Indicates whether a client can create a hierarchy table.</span></span> <span data-ttu-id="52362-123">Esta propiedad sólo se utiliza en objetos folder.</span><span class="sxs-lookup"><span data-stu-id="52362-123">This property is only used on folder objects.</span></span>  <br/> |
|[<span data-ttu-id="52362-124">Delete</span><span class="sxs-lookup"><span data-stu-id="52362-124">Delete</span></span>](delete.md) <br/> |<span data-ttu-id="52362-125">Indica si un cliente puede eliminar una carpeta o un elemento.</span><span class="sxs-lookup"><span data-stu-id="52362-125">Indicates whether a client can delete a folder or item.</span></span>  <br/> |
|[<span data-ttu-id="52362-126">Modificar</span><span class="sxs-lookup"><span data-stu-id="52362-126">Modify</span></span>](modify.md) <br/> |<span data-ttu-id="52362-127">Indica si un cliente puede modificar una carpeta o un elemento.</span><span class="sxs-lookup"><span data-stu-id="52362-127">Indicates whether a client can modify a folder or item.</span></span>  <br/> |
|[<span data-ttu-id="52362-128">Read</span><span class="sxs-lookup"><span data-stu-id="52362-128">Read</span></span>](read.md) <br/> |<span data-ttu-id="52362-129">Indica si un cliente puede leer una carpeta o un elemento.</span><span class="sxs-lookup"><span data-stu-id="52362-129">Indicates whether a client can read a folder or item.</span></span>  <br/> |
|[<span data-ttu-id="52362-130">ViewPrivateItems</span><span class="sxs-lookup"><span data-stu-id="52362-130">ViewPrivateItems</span></span>](viewprivateitems.md) <br/> |<span data-ttu-id="52362-131">Indica si se puede ver un elemento privado.</span><span class="sxs-lookup"><span data-stu-id="52362-131">Indicates whether a private item can be viewed.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="52362-132">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="52362-132">Parent elements</span></span>

|<span data-ttu-id="52362-133">**Element**</span><span class="sxs-lookup"><span data-stu-id="52362-133">**Element**</span></span>|<span data-ttu-id="52362-134">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="52362-134">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="52362-135">Folder</span><span class="sxs-lookup"><span data-stu-id="52362-135">Folder</span></span>](folder.md) <br/> |<span data-ttu-id="52362-136">Representa una carpeta en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="52362-136">Represents a folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="52362-137">TasksFolder</span><span class="sxs-lookup"><span data-stu-id="52362-137">TasksFolder</span></span>](tasksfolder.md) <br/> |<span data-ttu-id="52362-138">Representa una carpeta de tareas en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="52362-138">Represents a tasks folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="52362-139">ContactsFolder</span><span class="sxs-lookup"><span data-stu-id="52362-139">ContactsFolder</span></span>](contactsfolder.md) <br/> |<span data-ttu-id="52362-140">Representa una carpeta de contactos en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="52362-140">Represents a contacts folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="52362-141">CalendarFolder</span><span class="sxs-lookup"><span data-stu-id="52362-141">CalendarFolder</span></span>](calendarfolder.md) <br/> |<span data-ttu-id="52362-142">Representa una carpeta del calendario en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="52362-142">Represents a calendar folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="52362-143">SearchFolder</span><span class="sxs-lookup"><span data-stu-id="52362-143">SearchFolder</span></span>](searchfolder.md) <br/> |<span data-ttu-id="52362-144">Representa una carpeta de búsqueda en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="52362-144">Represents a search folder in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="52362-145">CalendarItem</span><span class="sxs-lookup"><span data-stu-id="52362-145">CalendarItem</span></span>](calendaritem.md) <br/> |<span data-ttu-id="52362-146">Representa un elemento de calendario de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-146">Represents an Exchange calendar item.</span></span>  <br/> |
|[<span data-ttu-id="52362-147">Contact</span><span class="sxs-lookup"><span data-stu-id="52362-147">Contact</span></span>](contact.md) <br/> |<span data-ttu-id="52362-148">Representa un elemento de contacto de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-148">Represents an Exchange contact item.</span></span>  <br/> |
|[<span data-ttu-id="52362-149">DistributionList</span><span class="sxs-lookup"><span data-stu-id="52362-149">DistributionList</span></span>](distributionlist.md) <br/> |<span data-ttu-id="52362-150">Representa una lista de distribución.</span><span class="sxs-lookup"><span data-stu-id="52362-150">Represents a distribution list.</span></span>  <br/> |
|[<span data-ttu-id="52362-151">Item</span><span class="sxs-lookup"><span data-stu-id="52362-151">Item</span></span>](item.md) <br/> |<span data-ttu-id="52362-152">Representa un elemento genérico de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-152">Represents a generic Exchange item.</span></span>  <br/> |
|[<span data-ttu-id="52362-153">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="52362-153">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="52362-154">Representa la cancelación de la reunión en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-154">Represents a meeting cancellation in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="52362-155">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="52362-155">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="52362-156">Representa una reunión en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-156">Represents a meeting in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="52362-157">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="52362-157">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="52362-158">Representa una convocatoria de reunión en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-158">Represents a meeting request in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="52362-159">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="52362-159">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="52362-160">Representa una respuesta a la reunión en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-160">Represents a meeting response in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="52362-161">Message</span><span class="sxs-lookup"><span data-stu-id="52362-161">Message</span></span>](message-ex15websvcsotherref.md) <br/> |<span data-ttu-id="52362-162">Representa un mensaje de correo electrónico de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-162">Represents an Exchange e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="52362-163">Tarea</span><span class="sxs-lookup"><span data-stu-id="52362-163">Task</span></span>](task.md) <br/> |<span data-ttu-id="52362-164">Representa una tarea en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-164">Represents a task in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="52362-165">Objeto postItem</span><span class="sxs-lookup"><span data-stu-id="52362-165">PostItem</span></span>](postitem.md) <br/> |<span data-ttu-id="52362-166">Representa un elemento para exponer en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-166">Represents a post item in the Exchange store.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="52362-167">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="52362-167">Text value</span></span>

<span data-ttu-id="52362-168">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="52362-168">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="52362-169">Observaciones</span><span class="sxs-lookup"><span data-stu-id="52362-169">Remarks</span></span>

<span data-ttu-id="52362-170">**EffectiveRights** se admite en las respuestas GetFolder, GetItem, FindFolder, FindItem, SyncFolderHierarchy y SyncFolderItems.</span><span class="sxs-lookup"><span data-stu-id="52362-170">**EffectiveRights** is supported in the GetFolder, GetItem, FindFolder, FindItem, SyncFolderHierarchy, and SyncFolderItems responses.</span></span> <span data-ttu-id="52362-171">La propiedad **EffectiveRights** se expone en la forma **AllProperties** para carpetas y elementos.</span><span class="sxs-lookup"><span data-stu-id="52362-171">The **EffectiveRights** property is exposed in the **AllProperties** shape for folders and items.</span></span> 
  
<span data-ttu-id="52362-172">Esta propiedad **EffectiveRights** proporciona acceso a la misma información que se proporciona en la propiedad **PR_ACCESS MAPI** .</span><span class="sxs-lookup"><span data-stu-id="52362-172">This **EffectiveRights** property provides access to the same information that is provided in the **PR_ACCESS MAPI** property.</span></span> 
  
<span data-ttu-id="52362-173">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="52362-173">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="52362-174">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="52362-174">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="52362-175">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="52362-175">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="52362-176">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="52362-176">Schema Name</span></span>  <br/> |<span data-ttu-id="52362-177">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="52362-177">Types schema</span></span>  <br/> |
|<span data-ttu-id="52362-178">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="52362-178">Validation File</span></span>  <br/> |<span data-ttu-id="52362-179">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="52362-179">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="52362-180">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="52362-180">Can be Empty</span></span>  <br/> |<span data-ttu-id="52362-181">False</span><span class="sxs-lookup"><span data-stu-id="52362-181">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="52362-182">Ver también</span><span class="sxs-lookup"><span data-stu-id="52362-182">See also</span></span>

- [<span data-ttu-id="52362-183">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="52362-183">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
- [<span data-ttu-id="52362-184">Establecimiento de permisos de nivel de carpeta</span><span class="sxs-lookup"><span data-stu-id="52362-184">Setting Folder-Level Permissions</span></span>](http://msdn.microsoft.com/library/c7530e86-5112-401c-b10a-9c054ae59f07%28Office.15%29.aspx)
