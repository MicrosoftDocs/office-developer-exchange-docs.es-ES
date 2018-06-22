---
title: DistinguishedFolderId
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DistinguishedFolderId
api_type:
- schema
ms.assetid: 50018162-2941-4227-8a5b-d6b4686bb32f
description: El elemento DistinguishedFolderId identifica las carpetas que se pueden hacer referencia por su nombre. Si no usa este elemento, debe usar el elemento FolderId para identificar una carpeta.
ms.openlocfilehash: 834166be3d882fa8c0533cfcc2999600430b82ce
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764250"
---
# <a name="distinguishedfolderid"></a><span data-ttu-id="70491-104">DistinguishedFolderId</span><span class="sxs-lookup"><span data-stu-id="70491-104">DistinguishedFolderId</span></span>

<span data-ttu-id="70491-105">El elemento **DistinguishedFolderId** identifica las carpetas que se pueden hacer referencia por su nombre.</span><span class="sxs-lookup"><span data-stu-id="70491-105">The **DistinguishedFolderId** element identifies folders that can be referenced by name.</span></span> <span data-ttu-id="70491-106">Si no usa este elemento, debe usar el elemento [FolderId](folderid.md) para identificar una carpeta.</span><span class="sxs-lookup"><span data-stu-id="70491-106">If you do not use this element, you must use the [FolderId](folderid.md) element to identify a folder.</span></span> 
  
```XML
<DistinguishedFolderId Id="" ChangeKey="">
   <Mailbox/>
</DistinguishedFolderId>
```

 <span data-ttu-id="70491-107">**DistinguishedFolderIdType**</span><span class="sxs-lookup"><span data-stu-id="70491-107">**DistinguishedFolderIdType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="70491-108">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="70491-108">Attributes and elements</span></span>

<span data-ttu-id="70491-109">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="70491-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="70491-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="70491-110">Attributes</span></span>

|<span data-ttu-id="70491-111">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="70491-111">**Attribute**</span></span>|<span data-ttu-id="70491-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="70491-112">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="70491-113">**Id**</span><span class="sxs-lookup"><span data-stu-id="70491-113">**Id**</span></span> <br/> |<span data-ttu-id="70491-114">Contiene una cadena que identifica una carpeta predeterminada.</span><span class="sxs-lookup"><span data-stu-id="70491-114">Contains a string that identifies a default folder.</span></span> <span data-ttu-id="70491-115">Este atributo es necesario.</span><span class="sxs-lookup"><span data-stu-id="70491-115">This attribute is required.</span></span>  <br/> |
|<span data-ttu-id="70491-116">**ChangeKey**</span><span class="sxs-lookup"><span data-stu-id="70491-116">**ChangeKey**</span></span> <br/> |<span data-ttu-id="70491-117">Contiene una cadena que identifica una versión de una carpeta que se identifica con el atributo **Id** .</span><span class="sxs-lookup"><span data-stu-id="70491-117">Contains a string that identifies a version of a folder that is identified by the **Id** attribute.</span></span> <span data-ttu-id="70491-118">Este atributo es opcional.</span><span class="sxs-lookup"><span data-stu-id="70491-118">This attribute is optional.</span></span> <span data-ttu-id="70491-119">Use este atributo para asegurarse de que se usa la versión correcta de una carpeta.</span><span class="sxs-lookup"><span data-stu-id="70491-119">Use this attribute to make sure that the correct version of a folder is used.</span></span>  <br/> |
   
#### <a name="id-attribute-values"></a><span data-ttu-id="70491-120">Valores del atributo ID</span><span class="sxs-lookup"><span data-stu-id="70491-120">Id attribute values</span></span>

|<span data-ttu-id="70491-121">**Valor**</span><span class="sxs-lookup"><span data-stu-id="70491-121">**Value**</span></span>|<span data-ttu-id="70491-122">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="70491-122">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="70491-123">calendario</span><span class="sxs-lookup"><span data-stu-id="70491-123">calendar</span></span>  <br/> |<span data-ttu-id="70491-124">Representa la carpeta Calendario.</span><span class="sxs-lookup"><span data-stu-id="70491-124">Represents the Calendar folder.</span></span>  <br/> |
|<span data-ttu-id="70491-125">contactos</span><span class="sxs-lookup"><span data-stu-id="70491-125">contacts</span></span>  <br/> |<span data-ttu-id="70491-126">Representa la carpeta Contactos.</span><span class="sxs-lookup"><span data-stu-id="70491-126">Represents the Contacts folder.</span></span>  <br/> |
|<span data-ttu-id="70491-127">deleteditems</span><span class="sxs-lookup"><span data-stu-id="70491-127">deleteditems</span></span>  <br/> |<span data-ttu-id="70491-128">Representa la carpeta Elementos eliminados.</span><span class="sxs-lookup"><span data-stu-id="70491-128">Represents the Deleted Items folder.</span></span>  <br/> |
|<span data-ttu-id="70491-129">borradores</span><span class="sxs-lookup"><span data-stu-id="70491-129">drafts</span></span>  <br/> |<span data-ttu-id="70491-130">Representa la carpeta Borradores.</span><span class="sxs-lookup"><span data-stu-id="70491-130">Represents the Drafts folder.</span></span>  <br/> |
|<span data-ttu-id="70491-131">Bandeja de entrada</span><span class="sxs-lookup"><span data-stu-id="70491-131">inbox</span></span>  <br/> |<span data-ttu-id="70491-132">Representa la carpeta Bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="70491-132">Represents the Inbox folder.</span></span>  <br/> |
|<span data-ttu-id="70491-133">diario</span><span class="sxs-lookup"><span data-stu-id="70491-133">journal</span></span>  <br/> |<span data-ttu-id="70491-134">Representa la carpeta diario.</span><span class="sxs-lookup"><span data-stu-id="70491-134">Represents the Journal folder.</span></span>  <br/> |
|<span data-ttu-id="70491-135">notas</span><span class="sxs-lookup"><span data-stu-id="70491-135">notes</span></span>  <br/> |<span data-ttu-id="70491-136">Representa la carpeta notas.</span><span class="sxs-lookup"><span data-stu-id="70491-136">Represents the Notes folder.</span></span>  <br/> |
|<span data-ttu-id="70491-137">Bandeja de salida</span><span class="sxs-lookup"><span data-stu-id="70491-137">outbox</span></span>  <br/> |<span data-ttu-id="70491-138">Representa la carpeta Bandeja de salida.</span><span class="sxs-lookup"><span data-stu-id="70491-138">Represents the Outbox folder.</span></span>  <br/> |
|<span data-ttu-id="70491-139">elementos enviados</span><span class="sxs-lookup"><span data-stu-id="70491-139">sentitems</span></span>  <br/> |<span data-ttu-id="70491-140">Representa la carpeta Elementos enviados.</span><span class="sxs-lookup"><span data-stu-id="70491-140">Represents the Sent Items folder.</span></span>  <br/> |
|<span data-ttu-id="70491-141">tasks</span><span class="sxs-lookup"><span data-stu-id="70491-141">tasks</span></span>  <br/> |<span data-ttu-id="70491-142">Representa la carpeta tareas.</span><span class="sxs-lookup"><span data-stu-id="70491-142">Represents the Tasks folder.</span></span>  <br/> |
|<span data-ttu-id="70491-143">msgfolderroot</span><span class="sxs-lookup"><span data-stu-id="70491-143">msgfolderroot</span></span>  <br/> |<span data-ttu-id="70491-144">Representa la raíz de la carpeta de mensaje.</span><span class="sxs-lookup"><span data-stu-id="70491-144">Represents the message folder root.</span></span>  <br/> |
|<span data-ttu-id="70491-145">root</span><span class="sxs-lookup"><span data-stu-id="70491-145">root</span></span>  <br/> |<span data-ttu-id="70491-146">Representa la raíz del buzón.</span><span class="sxs-lookup"><span data-stu-id="70491-146">Represents the root of the mailbox.</span></span>  <br/> |
|<span data-ttu-id="70491-147">junkemail</span><span class="sxs-lookup"><span data-stu-id="70491-147">junkemail</span></span>  <br/> |<span data-ttu-id="70491-148">Representa la carpeta de correo electrónico no deseado.</span><span class="sxs-lookup"><span data-stu-id="70491-148">Represents the Junk Email folder.</span></span>  <br/> |
|<span data-ttu-id="70491-149">SearchFolders</span><span class="sxs-lookup"><span data-stu-id="70491-149">searchfolders</span></span>  <br/> |<span data-ttu-id="70491-150">Representa la carpeta de las carpetas de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="70491-150">Represents the Search Folders folder.</span></span>  <br/> |
|<span data-ttu-id="70491-151">correo de voz</span><span class="sxs-lookup"><span data-stu-id="70491-151">voicemail</span></span>  <br/> |<span data-ttu-id="70491-152">Representa la carpeta de correo de voz.</span><span class="sxs-lookup"><span data-stu-id="70491-152">Represents the Voice Mail folder.</span></span>  <br/> |
|<span data-ttu-id="70491-153">recoverableitemsroot</span><span class="sxs-lookup"><span data-stu-id="70491-153">recoverableitemsroot</span></span>  <br/> |<span data-ttu-id="70491-154">Representa el contenedor de carpeta raíz.</span><span class="sxs-lookup"><span data-stu-id="70491-154">Represents the dumpster root folder.</span></span>  <br/> |
|<span data-ttu-id="70491-155">recoverableitemsdeletions</span><span class="sxs-lookup"><span data-stu-id="70491-155">recoverableitemsdeletions</span></span>  <br/> |<span data-ttu-id="70491-156">Representa el contenedor de carpeta de eliminaciones.</span><span class="sxs-lookup"><span data-stu-id="70491-156">Represents the dumpster deletions folder.</span></span>  <br/> |
|<span data-ttu-id="70491-157">recoverableitemsversions</span><span class="sxs-lookup"><span data-stu-id="70491-157">recoverableitemsversions</span></span>  <br/> |<span data-ttu-id="70491-158">Representa el contenedor de carpeta de versiones.</span><span class="sxs-lookup"><span data-stu-id="70491-158">Represents the dumpster versions folder.</span></span>  <br/> |
|<span data-ttu-id="70491-159">recoverableitemspurges</span><span class="sxs-lookup"><span data-stu-id="70491-159">recoverableitemspurges</span></span>  <br/> |<span data-ttu-id="70491-160">Representa el volcado de archivos purga de la carpeta.</span><span class="sxs-lookup"><span data-stu-id="70491-160">Represents the dumpster purges folder.</span></span>  <br/> |
|<span data-ttu-id="70491-161">archiveroot</span><span class="sxs-lookup"><span data-stu-id="70491-161">archiveroot</span></span>  <br/> |<span data-ttu-id="70491-162">Representa la carpeta raíz del archivo.</span><span class="sxs-lookup"><span data-stu-id="70491-162">Represents the root archive folder.</span></span>  <br/> |
|<span data-ttu-id="70491-163">archivemsgfolderroot</span><span class="sxs-lookup"><span data-stu-id="70491-163">archivemsgfolderroot</span></span>  <br/> |<span data-ttu-id="70491-164">Representa la carpeta raíz archivar los mensajes.</span><span class="sxs-lookup"><span data-stu-id="70491-164">Represents the root archive message folder.</span></span>  <br/> |
|<span data-ttu-id="70491-165">archivedeleteditems</span><span class="sxs-lookup"><span data-stu-id="70491-165">archivedeleteditems</span></span>  <br/> |<span data-ttu-id="70491-166">Representa la carpeta de elementos eliminado del archivo.</span><span class="sxs-lookup"><span data-stu-id="70491-166">Represents the archive deleted items folder.</span></span>  <br/> |
|<span data-ttu-id="70491-167">archiveinbox</span><span class="sxs-lookup"><span data-stu-id="70491-167">archiveinbox</span></span>  <br/> |<span data-ttu-id="70491-168">Representa el archivo de la carpeta Bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="70491-168">Represents the archive Inbox folder.</span></span> <span data-ttu-id="70491-169">Las versiones de Exchange, comenzando por el número de compilación 15.00.0913.09 incluyen este valor.</span><span class="sxs-lookup"><span data-stu-id="70491-169">Versions of Exchange starting with build number 15.00.0913.09 include this value.</span></span>  <br/> |
|<span data-ttu-id="70491-170">archiverecoverableitemsroot</span><span class="sxs-lookup"><span data-stu-id="70491-170">archiverecoverableitemsroot</span></span>  <br/> |<span data-ttu-id="70491-171">Representa la carpeta raíz para archivar elementos recuperables.</span><span class="sxs-lookup"><span data-stu-id="70491-171">Represents the archive recoverable items root folder.</span></span>  <br/> |
|<span data-ttu-id="70491-172">archiverecoverableitemsdeletions</span><span class="sxs-lookup"><span data-stu-id="70491-172">archiverecoverableitemsdeletions</span></span>  <br/> |<span data-ttu-id="70491-173">Representa la carpeta para archivar elementos recuperables eliminaciones.</span><span class="sxs-lookup"><span data-stu-id="70491-173">Represents the archive recoverable items deletions folder.</span></span>  <br/> |
|<span data-ttu-id="70491-174">archiverecoverableitemsversions</span><span class="sxs-lookup"><span data-stu-id="70491-174">archiverecoverableitemsversions</span></span>  <br/> |<span data-ttu-id="70491-175">Representa la carpeta de versiones de los elementos recuperables de archivo.</span><span class="sxs-lookup"><span data-stu-id="70491-175">Represents the archive recoverable items versions folder.</span></span>  <br/> |
|<span data-ttu-id="70491-176">archiverecoverableitemspurges</span><span class="sxs-lookup"><span data-stu-id="70491-176">archiverecoverableitemspurges</span></span>  <br/> |<span data-ttu-id="70491-177">Representa la carpeta para archivar elementos recuperables purga.</span><span class="sxs-lookup"><span data-stu-id="70491-177">Represents the archive recoverable items purges folder.</span></span>  <br/> |
|<span data-ttu-id="70491-178">syncissues</span><span class="sxs-lookup"><span data-stu-id="70491-178">syncissues</span></span>  <br/> |<span data-ttu-id="70491-179">Representa la carpeta problemas de sincronización.</span><span class="sxs-lookup"><span data-stu-id="70491-179">Represents the sync issues folder.</span></span>  <br/> |
|<span data-ttu-id="70491-180">conflictos</span><span class="sxs-lookup"><span data-stu-id="70491-180">conflicts</span></span>  <br/> |<span data-ttu-id="70491-181">Representa la carpeta conflictos.</span><span class="sxs-lookup"><span data-stu-id="70491-181">Represents the conflicts folder.</span></span>  <br/> |
|<span data-ttu-id="70491-182">localfailures</span><span class="sxs-lookup"><span data-stu-id="70491-182">localfailures</span></span>  <br/> |<span data-ttu-id="70491-183">Representa la carpeta errores locales.</span><span class="sxs-lookup"><span data-stu-id="70491-183">Represents the local failures folder.</span></span>  <br/> |
|<span data-ttu-id="70491-184">serverfailures</span><span class="sxs-lookup"><span data-stu-id="70491-184">serverfailures</span></span>  <br/> |<span data-ttu-id="70491-185">Representa la carpeta de errores del servidor.</span><span class="sxs-lookup"><span data-stu-id="70491-185">Represents the server failures folder.</span></span>  <br/> |
|<span data-ttu-id="70491-186">recipientcache</span><span class="sxs-lookup"><span data-stu-id="70491-186">recipientcache</span></span>  <br/> |<span data-ttu-id="70491-187">Representa la carpeta de caché del destinatario.</span><span class="sxs-lookup"><span data-stu-id="70491-187">Represents the recipient cache folder.</span></span>  <br/> |
|<span data-ttu-id="70491-188">QuickContacts</span><span class="sxs-lookup"><span data-stu-id="70491-188">quickcontacts</span></span>  <br/> |<span data-ttu-id="70491-189">Representa la carpeta Contactos rápidos.</span><span class="sxs-lookup"><span data-stu-id="70491-189">Represents the quick contacts folder.</span></span>  <br/> |
|<span data-ttu-id="70491-190">conversationhistory</span><span class="sxs-lookup"><span data-stu-id="70491-190">conversationhistory</span></span>  <br/> |<span data-ttu-id="70491-191">Representa la carpeta Historial de conversaciones.</span><span class="sxs-lookup"><span data-stu-id="70491-191">Represents the conversation history folder.</span></span>  <br/> |
|<span data-ttu-id="70491-192">adminauditlogs</span><span class="sxs-lookup"><span data-stu-id="70491-192">adminauditlogs</span></span>  <br/> |<span data-ttu-id="70491-193">Representa la carpeta de registros de auditoría de administrador.</span><span class="sxs-lookup"><span data-stu-id="70491-193">Represents the admin audit logs folder.</span></span>  <br/> |
|<span data-ttu-id="70491-194">todosearch</span><span class="sxs-lookup"><span data-stu-id="70491-194">todosearch</span></span>  <br/> |<span data-ttu-id="70491-195">Representa la carpeta de búsqueda de tareas pendientes.</span><span class="sxs-lookup"><span data-stu-id="70491-195">Represents the todo search folder.</span></span>  <br/> |
|<span data-ttu-id="70491-196">mycontacts</span><span class="sxs-lookup"><span data-stu-id="70491-196">mycontacts</span></span>  <br/> |<span data-ttu-id="70491-197">Representa la carpeta Mis contactos.</span><span class="sxs-lookup"><span data-stu-id="70491-197">Represents the My Contacts folder.</span></span>  <br/> |
|<span data-ttu-id="70491-198">Active Directory</span><span class="sxs-lookup"><span data-stu-id="70491-198">directory</span></span>  <br/> |<span data-ttu-id="70491-199">Representa la carpeta de Active directory.</span><span class="sxs-lookup"><span data-stu-id="70491-199">Represents the directory folder.</span></span>  <br/> |
|<span data-ttu-id="70491-200">imcontactlist</span><span class="sxs-lookup"><span data-stu-id="70491-200">imcontactlist</span></span>  <br/> |<span data-ttu-id="70491-201">Representa la carpeta de la lista de contactos de mensajería instantánea.</span><span class="sxs-lookup"><span data-stu-id="70491-201">Represents the IM contact list folder.</span></span>  <br/> |
|<span data-ttu-id="70491-202">peopleconnect</span><span class="sxs-lookup"><span data-stu-id="70491-202">peopleconnect</span></span>  <br/> |<span data-ttu-id="70491-203">Representa las personas conectar carpeta.</span><span class="sxs-lookup"><span data-stu-id="70491-203">Represents the people connect folder.</span></span>  <br/> |
|<span data-ttu-id="70491-204">favoritos</span><span class="sxs-lookup"><span data-stu-id="70491-204">favorites</span></span>  <br/> |<span data-ttu-id="70491-205">Representa la carpeta Favoritos.</span><span class="sxs-lookup"><span data-stu-id="70491-205">Represents the Favorites folder.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="70491-206">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="70491-206">Child elements</span></span>

|<span data-ttu-id="70491-207">**Element**</span><span class="sxs-lookup"><span data-stu-id="70491-207">**Element**</span></span>|<span data-ttu-id="70491-208">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="70491-208">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="70491-209">Buzón de correo</span><span class="sxs-lookup"><span data-stu-id="70491-209">Mailbox</span></span>](mailbox.md) <br/> |<span data-ttu-id="70491-210">Identifica una dirección SMTP principal.</span><span class="sxs-lookup"><span data-stu-id="70491-210">Identifies a primary SMTP address.</span></span> <span data-ttu-id="70491-211">No se permiten las direcciones proxy.</span><span class="sxs-lookup"><span data-stu-id="70491-211">Proxy addresses are not allowed.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="70491-212">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="70491-212">Parent elements</span></span>

|<span data-ttu-id="70491-213">**Element**</span><span class="sxs-lookup"><span data-stu-id="70491-213">**Element**</span></span>|<span data-ttu-id="70491-214">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="70491-214">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="70491-215">ContextFolderId</span><span class="sxs-lookup"><span data-stu-id="70491-215">ContextFolderId</span></span>](contextfolderid.md) <br/> |<span data-ttu-id="70491-216">Indica la carpeta que está destinada a las acciones de conversación que utilizan carpetas.</span><span class="sxs-lookup"><span data-stu-id="70491-216">Indicates the folder that is targeted for conversation actions that use folders.</span></span>  <br/> |
|[<span data-ttu-id="70491-217">DestinationFolderId</span><span class="sxs-lookup"><span data-stu-id="70491-217">DestinationFolderId</span></span>](destinationfolderid.md) <br/> |<span data-ttu-id="70491-218">Indica la carpeta de destino para copiar y mover acciones de conversación.</span><span class="sxs-lookup"><span data-stu-id="70491-218">Indicates the destination folder for copy and move conversation actions.</span></span>  <br/> |
|[<span data-ttu-id="70491-219">ID (TargetFolderIdType)</span><span class="sxs-lookup"><span data-stu-id="70491-219">ParentFolderId (TargetFolderIdType)</span></span>](parentfolderid-targetfolderidtype.md) <br/> | <span data-ttu-id="70491-220">Identifica la carpeta en la que se crea una nueva carpeta o elemento.</span><span class="sxs-lookup"><span data-stu-id="70491-220">Identifies the folder in which a new folder or item is created.</span></span>  <br/><br/><span data-ttu-id="70491-221">Los siguientes son las expresiones de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="70491-221">The following are the XPath expressions to this element:</span></span><br/><br/>  `/CreateItem/ParentFolderId` <br/><br/>`/CreateFolder/ParentFolderId` <br/> |
|[<span data-ttu-id="70491-222">ParentFolderIds</span><span class="sxs-lookup"><span data-stu-id="70491-222">ParentFolderIds</span></span>](parentfolderids.md) <br/> |<span data-ttu-id="70491-223">Identifica las carpetas de búsqueda de la [operación FindItem](finditem-operation.md) y la [operación FindFolder](findfolder-operation.md).</span><span class="sxs-lookup"><span data-stu-id="70491-223">Identifies folders to search for the [FindItem operation](finditem-operation.md) and the [FindFolder operation](findfolder-operation.md).</span></span>  <br/> |
|[<span data-ttu-id="70491-224">BaseFolderIds</span><span class="sxs-lookup"><span data-stu-id="70491-224">BaseFolderIds</span></span>](basefolderids.md) <br/> |<span data-ttu-id="70491-225">Representa la colección de carpetas que se buscarán para determinar el contenido de una carpeta de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="70491-225">Represents the collection of folders that will be searched to determine the contents of a search folder.</span></span>  <br/> |
|[<span data-ttu-id="70491-226">FolderIds</span><span class="sxs-lookup"><span data-stu-id="70491-226">FolderIds</span></span>](folderids.md) <br/> |<span data-ttu-id="70491-227">Contiene una matriz de identificadores de carpeta que se usa para identificar las carpetas para copiar, mover, obtener, eliminar o supervisar para las notificaciones de eventos.</span><span class="sxs-lookup"><span data-stu-id="70491-227">Contains an array of folder identifiers that are used to identify folders to copy, move, get, delete, or monitor for event notifications.</span></span>  <br/> |
|[<span data-ttu-id="70491-228">FolderChange</span><span class="sxs-lookup"><span data-stu-id="70491-228">FolderChange</span></span>](folderchange.md) <br/> |<span data-ttu-id="70491-229">Representa una colección de los cambios que se debe realizar en una sola carpeta.</span><span class="sxs-lookup"><span data-stu-id="70491-229">Represents a collection of changes to be performed on a single folder.</span></span>  <br/> <br/><span data-ttu-id="70491-230">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="70491-230">The following is the XPath expression to this element:</span></span><br/><br/>`/UpdateFolder/FolderChanges/FolderChange`<br/> |
|[<span data-ttu-id="70491-231">ToFolderId</span><span class="sxs-lookup"><span data-stu-id="70491-231">ToFolderId</span></span>](tofolderid.md) <br/> | <span data-ttu-id="70491-232">Representa la carpeta de destino para un elemento que se ha movido o copiado o una carpeta.</span><span class="sxs-lookup"><span data-stu-id="70491-232">Represents the destination folder for a copied or moved item or folder.</span></span><br/><br/><span data-ttu-id="70491-233">Los siguientes son las expresiones de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="70491-233">The following are the XPath expressions to this element:</span></span><br/><br/>`/MoveFolder/ToFolderId`<br/><br/>`/CopyFolder/ToFolderId`<br/><br/>`/MoveItem/ToFolderId`<br/><br/>`/CopyItem/ToFolderId` <br/> |
|[<span data-ttu-id="70491-234">SavedItemFolderId</span><span class="sxs-lookup"><span data-stu-id="70491-234">SavedItemFolderId</span></span>](saveditemfolderid.md) <br/> | <span data-ttu-id="70491-235">Identifica la carpeta de destino para las operaciones que actualizar, enviar y crear elementos en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="70491-235">Identifies the target folder for operations that update, send, and create items in the Exchange store.</span></span><br/><br/><span data-ttu-id="70491-236">Los siguientes son las expresiones de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="70491-236">The following are the XPath expressions to this element:</span></span><br/><br/>`/CreateItem/SavedItemFolderId`<br/><br/>`/UpdateItem/SavedItemFolderId`<br/><br/>`/SendItem/SavedItemFolderId` <br/> |
|[<span data-ttu-id="70491-237">SyncFolderId</span><span class="sxs-lookup"><span data-stu-id="70491-237">SyncFolderId</span></span>](syncfolderid.md) <br/> |<span data-ttu-id="70491-238">Representa la carpeta que contiene los elementos para sincronizar.</span><span class="sxs-lookup"><span data-stu-id="70491-238">Represents the folder that contains the items to synchronize.</span></span>  <br/> |
|[<span data-ttu-id="70491-239">UserConfigurationName</span><span class="sxs-lookup"><span data-stu-id="70491-239">UserConfigurationName</span></span>](userconfigurationname.md) <br/> |<span data-ttu-id="70491-240">Representa el nombre de un objeto de configuración de usuario.</span><span class="sxs-lookup"><span data-stu-id="70491-240">Represents the name of a user configuration object.</span></span> <span data-ttu-id="70491-241">El nombre del objeto de configuración de usuario es el identificador de un objeto de configuración de usuario.</span><span class="sxs-lookup"><span data-stu-id="70491-241">The user configuration object name is the identifier for a user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="70491-242">CopyToFolder</span><span class="sxs-lookup"><span data-stu-id="70491-242">CopyToFolder</span></span>](copytofolder.md) <br/> |<span data-ttu-id="70491-243">Representa el identificador de la carpeta de ese correo electrónico elementos se copiarán a.</span><span class="sxs-lookup"><span data-stu-id="70491-243">Represents the ID of the folder that email items will be copied to.</span></span>  <br/> |
|[<span data-ttu-id="70491-244">MoveToFolder</span><span class="sxs-lookup"><span data-stu-id="70491-244">MoveToFolder</span></span>](movetofolder.md) <br/> |<span data-ttu-id="70491-245">Representa el identificador de la carpeta de ese correo electrónico que se moverán los elementos a.</span><span class="sxs-lookup"><span data-stu-id="70491-245">Represents the ID of the folder that email items will be moved to.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="70491-246">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="70491-246">Text value</span></span>

<span data-ttu-id="70491-247">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="70491-247">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="70491-248">Observaciones</span><span class="sxs-lookup"><span data-stu-id="70491-248">Remarks</span></span>

<span data-ttu-id="70491-249">Una **DistinguishedFolderId** se resuelve en un **FolderId**.</span><span class="sxs-lookup"><span data-stu-id="70491-249">A **DistinguishedFolderId** resolves to a **FolderId**.</span></span> 
  
<span data-ttu-id="70491-250">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="70491-250">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="70491-251">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="70491-251">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="70491-252">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="70491-252">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="70491-253">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="70491-253">Schema Name</span></span>  <br/> |<span data-ttu-id="70491-254">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="70491-254">Types schema</span></span>  <br/> |
|<span data-ttu-id="70491-255">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="70491-255">Validation File</span></span>  <br/> |<span data-ttu-id="70491-256">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="70491-256">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="70491-257">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="70491-257">Can be Empty</span></span>  <br/> |<span data-ttu-id="70491-258">False</span><span class="sxs-lookup"><span data-stu-id="70491-258">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="70491-259">Ver también</span><span class="sxs-lookup"><span data-stu-id="70491-259">See also</span></span>

- [<span data-ttu-id="70491-260">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="70491-260">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
- [<span data-ttu-id="70491-261">Creación de carpetas (servicios Web de Exchange)</span><span class="sxs-lookup"><span data-stu-id="70491-261">Creating Folders (Exchange Web Services)</span></span>](http://msdn.microsoft.com/library/3b15b0ec-8691-45ed-9a24-a91ff732d6cf%28Office.15%29.aspx)
