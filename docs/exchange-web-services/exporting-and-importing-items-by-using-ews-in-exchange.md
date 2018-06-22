---
title: Exportación e importación de elementos mediante el uso de EWS en Exchange
manager: sethgros
ms.date: 03/9/2015
ms.audience: Developer
localization_priority: Normal
ms.assetid: ad5f75f9-47c3-4f51-a535-80cba4243683
description: Obtenga información acerca de la exportación e importación de citas, mensajes de correo electrónico, contactos, tareas y otros elementos del buzón de correo mediante el uso de la API administrada de EWS o EWS en Exchange.
ms.openlocfilehash: 63ba8807dd63ca2d151b1c2b1277625daeed640c
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19763025"
---
# <a name="exporting-and-importing-items-by-using-ews-in-exchange"></a><span data-ttu-id="4a778-103">Exportación e importación de elementos mediante el uso de EWS en Exchange</span><span class="sxs-lookup"><span data-stu-id="4a778-103">Exporting and importing items by using EWS in Exchange</span></span>

<span data-ttu-id="4a778-104">Obtenga información acerca de la exportación e importación de citas, mensajes de correo electrónico, contactos, tareas y otros elementos del buzón de correo mediante el uso de la API administrada de EWS o EWS en Exchange.</span><span class="sxs-lookup"><span data-stu-id="4a778-104">Learn about exporting and importing appointments, emails, contacts, tasks, and other mailbox items by using the EWS Managed API or EWS in Exchange.</span></span> 
  
<span data-ttu-id="4a778-105">Exchange es una mina de información importante: correo electrónico, contactos, tareas y calendarios son fundamentales para funciones de la organización.</span><span class="sxs-lookup"><span data-stu-id="4a778-105">Exchange is a gold mine of important information: email, contacts, tasks, and calendars are core to an organization's functions.</span></span> <span data-ttu-id="4a778-106">EWS permite exportar e importar tipos básicos de elemento a través de tres métodos diferentes:</span><span class="sxs-lookup"><span data-stu-id="4a778-106">EWS enables you to export and import core item types via three different approaches:</span></span>
  
- <span data-ttu-id="4a778-107">Tipos de elementos de Exchange.</span><span class="sxs-lookup"><span data-stu-id="4a778-107">Exchange item types.</span></span> <span data-ttu-id="4a778-108">Se recomienda este enfoque para importar y exportar los elementos a y desde otros sistemas y los archivos.</span><span class="sxs-lookup"><span data-stu-id="4a778-108">We recommend this approach for importing and exporting items to and from other systems and files.</span></span>
    
- <span data-ttu-id="4a778-109">Capacidad de nivel de elemento (solo EWS).</span><span class="sxs-lookup"><span data-stu-id="4a778-109">Item-level capability (EWS only).</span></span> <span data-ttu-id="4a778-110">Se recomienda esta opción para exportar o copiar de un servidor de Exchange o buzón de correo e importar a otro.</span><span class="sxs-lookup"><span data-stu-id="4a778-110">We recommend this option for exporting or copying from one Exchange server or mailbox and importing to another.</span></span>
    
- <span data-ttu-id="4a778-111">Secuencias MIME en el formulario de formatos de archivo estándar comunes como iCalendar y vCard.</span><span class="sxs-lookup"><span data-stu-id="4a778-111">MIME streams in the form of common standard file formats such as iCalendar and vCard.</span></span> <span data-ttu-id="4a778-112">Debido a que el conjunto de propiedades es limitado y conversión de MIME es costosa, se recomienda el enfoque sólo para importar o exportar una pequeña cantidad de datos.</span><span class="sxs-lookup"><span data-stu-id="4a778-112">Because the property set is limited and MIME conversion is costly, we recommend the approach only for importing or exporting a small amount of data.</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="4a778-113">EWS no está diseñado para la restauración y copia de seguridad del buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="4a778-113">EWS is not designed for mailbox backup and restore.</span></span> <span data-ttu-id="4a778-114">Para realizar una copia de y restaurar bases de datos, use la [API de copia de seguridad y restauración](../backup-restore/backup-and-restore-for-exchange-2013.md).</span><span class="sxs-lookup"><span data-stu-id="4a778-114">To back up and restore databases, use the [backup and restore API](../backup-restore/backup-and-restore-for-exchange-2013.md).</span></span> <span data-ttu-id="4a778-115">Vea también [copia de seguridad, restauración y recuperación ante desastres](http://technet.microsoft.com/en-us/library/dd876874%28v=exchg.150%29.aspx) en TechNet.</span><span class="sxs-lookup"><span data-stu-id="4a778-115">See also [Backup, restore, and disaster recovery](http://technet.microsoft.com/en-us/library/dd876874%28v=exchg.150%29.aspx) on TechNet.</span></span> 
  
<span data-ttu-id="4a778-116">**La tabla 1. Exportación e importación de contactos, correo electrónico y elementos de calendario**</span><span class="sxs-lookup"><span data-stu-id="4a778-116">**Table 1. Exporting and importing contact, email, and calendar items**</span></span>

|<span data-ttu-id="4a778-117">**Tarea**</span><span class="sxs-lookup"><span data-stu-id="4a778-117">**Task**</span></span>|<span data-ttu-id="4a778-118">**Método de la API administrada de EWS**</span><span class="sxs-lookup"><span data-stu-id="4a778-118">**EWS Managed API method**</span></span>|<span data-ttu-id="4a778-119">**Operación de EWS**</span><span class="sxs-lookup"><span data-stu-id="4a778-119">**EWS operation**</span></span>|<span data-ttu-id="4a778-120">**Notas**</span><span class="sxs-lookup"><span data-stu-id="4a778-120">**Notes**</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="4a778-121">Exportar una copia de un contacto, el correo electrónico, la tarea o el elemento de calendario con un [conjunto de propiedades especificado](properties-and-extended-properties-in-ews-in-exchange.md).</span><span class="sxs-lookup"><span data-stu-id="4a778-121">Export a copy of a contact, email, task, or calendar item with a [specified property set](properties-and-extended-properties-in-ews-in-exchange.md).</span></span>  <br/> |[<span data-ttu-id="4a778-122">Contact.Bind</span><span class="sxs-lookup"><span data-stu-id="4a778-122">Contact.Bind</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.contact.bind%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-123">EmailMessage.Bind</span><span class="sxs-lookup"><span data-stu-id="4a778-123">EmailMessage.Bind</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.emailmessage.bind%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-124">Appointment.Bind</span><span class="sxs-lookup"><span data-stu-id="4a778-124">Appointment.Bind</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.bind%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-125">Task.Bind</span><span class="sxs-lookup"><span data-stu-id="4a778-125">Task.Bind</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.task.bind%28v=exchg.80%29.aspx) <br/> |[<span data-ttu-id="4a778-126">GetItem</span><span class="sxs-lookup"><span data-stu-id="4a778-126">GetItem</span></span>](http://msdn.microsoft.com/library/e3590b8b-c2a7-4dad-a014-6360197b68e4%28Office.15%29.aspx) <br/> |<span data-ttu-id="4a778-127">Se recomienda esta opción si va a exportar los elementos del buzón a otro sistema que no son de Exchange o archivo (incluidos vCard y tipos de archivo iCalendar).</span><span class="sxs-lookup"><span data-stu-id="4a778-127">We recommend this option if you're exporting mailbox items to another non-Exchange system or file (including vCard and iCal file types).</span></span> <span data-ttu-id="4a778-128">Debido a que tiene control sobre el conjunto de propiedades exportado y debido a que el rendimiento es mejor para el servidor de Exchange, por lo general es la mejor opción.</span><span class="sxs-lookup"><span data-stu-id="4a778-128">Because you have control over the exported property set, and because performance is better for the Exchange server, this is generally the best option.</span></span>  <br/> <span data-ttu-id="4a778-129">Dependiendo de las propiedades establece en un elemento de buzón de correo, y si la aplicación tiene constancia de todos los identificadores de propiedad no encuentra esquematizado (propiedades extendidas) que se pueden establecer en un elemento, esta opción no puede generar una copia de fidelidad.</span><span class="sxs-lookup"><span data-stu-id="4a778-129">Depending on the properties set on a mailbox item, and whether your application is aware of all of the non-schematized property identifiers (extended properties) that might be set on an item, this option might not produce a full-fidelity copy.</span></span>  <br/> <span data-ttu-id="4a778-130">Estos métodos y operación proporcionan el conjunto de propiedades para un elemento además de las propiedades extendidas solicitadas esquematizado.</span><span class="sxs-lookup"><span data-stu-id="4a778-130">These methods and operation provide the schematized set of properties for an item plus any requested extended properties.</span></span> <span data-ttu-id="4a778-131">El método **Bind** o **GetItem** operation sólo puede proporcionar fidelidad exportación de elementos si conoce las propiedades extendidas que se han establecido en un elemento.</span><span class="sxs-lookup"><span data-stu-id="4a778-131">The **Bind** method or **GetItem** operation can only provide full-fidelity export of items if you know the extended properties that are set on an item.</span></span> <span data-ttu-id="4a778-132">Puede solicitar todas las conocidos [Propiedades extendidas](properties-and-extended-properties-in-ews-in-exchange.md) para habilitar plena fidelidad.</span><span class="sxs-lookup"><span data-stu-id="4a778-132">You can request all the known [extended properties](properties-and-extended-properties-in-ews-in-exchange.md) to enable full fidelity.</span></span>  <br/> <span data-ttu-id="4a778-133">> [!TIP]> Se puede usar la característica de seguimiento en la API administrada de EWS para obtener la representación XML de los elementos exportados.</span><span class="sxs-lookup"><span data-stu-id="4a778-133">> [!TIP]> You can use the tracing feature in the EWS Managed API to get the XML representation of exported items.</span></span>           <span data-ttu-id="4a778-134">Para obtener más información, vea [exportar un elemento en un formato personalizado](how-to-export-items-by-using-ews-in-exchange.md#bk_exportcustom).</span><span class="sxs-lookup"><span data-stu-id="4a778-134">For more information, see [Export an item into a custom format](how-to-export-items-by-using-ews-in-exchange.md#bk_exportcustom).</span></span>  <br/> |
|<span data-ttu-id="4a778-135">Importar una copia de un contacto, el correo electrónico, la tarea o el elemento de calendario con un [conjunto de propiedades especificado](properties-and-extended-properties-in-ews-in-exchange.md).</span><span class="sxs-lookup"><span data-stu-id="4a778-135">Import a copy of a contact, email, task, or calendar item with a [specified property set](properties-and-extended-properties-in-ews-in-exchange.md).</span></span>  <br/> |[<span data-ttu-id="4a778-136">Contact.Save</span><span class="sxs-lookup"><span data-stu-id="4a778-136">Contact.Save</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.contact.save%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-137">EmailMessage.Save</span><span class="sxs-lookup"><span data-stu-id="4a778-137">EmailMessage.Save</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.emailmessage.save%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-138">Appointment.Save</span><span class="sxs-lookup"><span data-stu-id="4a778-138">Appointment.Save</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.save%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-139">Task.Save</span><span class="sxs-lookup"><span data-stu-id="4a778-139">Task.Save</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.task.save%28v=exchg.80%29.aspx) <br/> |[<span data-ttu-id="4a778-140">CreateItem</span><span class="sxs-lookup"><span data-stu-id="4a778-140">CreateItem</span></span>](http://msdn.microsoft.com/library/78a52120-f1d0-4ed7-8748-436e554f75b6%28Office.15%29.aspx) <br/> |<span data-ttu-id="4a778-141">Se recomienda esta opción para importar los elementos del buzón en Exchange.</span><span class="sxs-lookup"><span data-stu-id="4a778-141">We recommend this option for importing mailbox items into Exchange.</span></span> <span data-ttu-id="4a778-142">Debe establecer las propiedades especiales en algunos tipos de elementos con el fin de mantener el estado del elemento importado.</span><span class="sxs-lookup"><span data-stu-id="4a778-142">You might have to set special properties on some item types in order to maintain the state of the imported item.</span></span> <span data-ttu-id="4a778-143">Debido a que sólo se establecen algunas propiedades de Exchange y no por los clientes, no siempre es posible tener una importación de fidelidad.</span><span class="sxs-lookup"><span data-stu-id="4a778-143">Because some properties are only set by Exchange and not by clients, it's not always possible to have a full-fidelity import.</span></span>  <br/> <span data-ttu-id="4a778-144">Por ejemplo, no se puede importar una reunión con los asistentes en un buzón de correo porque Exchange establece las relaciones entre el organizador y los asistentes.</span><span class="sxs-lookup"><span data-stu-id="4a778-144">For example, you cannot import a meeting with attendees into a mailbox because Exchange sets the relationships between the organizer and attendees.</span></span> <span data-ttu-id="4a778-145">Sólo se puede establecer esta relación por los organizadores de envío y los asistentes, recibir y responder a la convocatoria de reunión.</span><span class="sxs-lookup"><span data-stu-id="4a778-145">This relationship can only be established by organizers sending and attendees receiving and responding to the meeting request.</span></span>  <br/> <span data-ttu-id="4a778-146">Objetos de **citas** en Exchange pueden tener configuraciones y relaciones complejas.</span><span class="sxs-lookup"><span data-stu-id="4a778-146">**Appointment** objects in Exchange can have complex relationships and settings.</span></span> <span data-ttu-id="4a778-147">Las citas que tienen los asistentes (reuniones) tienen opciones de configuración que unir el organizador de la reunión y los asistentes a la reunión.</span><span class="sxs-lookup"><span data-stu-id="4a778-147">Appointments that have attendees (meetings) have settings that tie together the meeting organizer and meeting attendees.</span></span> <span data-ttu-id="4a778-148">Estas opciones no se conservan al exportar e importar las citas.</span><span class="sxs-lookup"><span data-stu-id="4a778-148">These settings are not maintained when you export and import appointments.</span></span> <span data-ttu-id="4a778-149">No se admite el restablecimiento mediante programación de la reunión relaciones de organizador o asistente directamente en las citas.</span><span class="sxs-lookup"><span data-stu-id="4a778-149">Programmatically reestablishing meeting organizer/attendee relationships directly on the appointments is not supported.</span></span> <span data-ttu-id="4a778-150">Una opción es necesario para volver a establecer esas relaciones es realizar, a continuación, procesamiento posterior después de una importación, tienen un organizador reenviar las reuniones y tienen los asistentes Aceptar las reuniones.</span><span class="sxs-lookup"><span data-stu-id="4a778-150">An option you do have for reestablishing those relationships is to perform post-processing after an import, then have an organizer resend the meetings and have the attendees accept the meetings.</span></span> <span data-ttu-id="4a778-151">Puede usar la suplantación de Exchange para realizar las llamadas para el organizador y los asistentes.</span><span class="sxs-lookup"><span data-stu-id="4a778-151">You can use Exchange impersonation to make the calls for both the organizer and the attendees.</span></span> <span data-ttu-id="4a778-152">Debe cambiar la propiedad UID del objeto **Appointment** antes de importar para evitar tener que las reuniones incorrectamente estar relacionado con otras reuniones en un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="4a778-152">You should change the UID property of the **Appointment** object before you import to avoid having meetings be incorrectly related to other meetings in a mailbox.</span></span>  <br/> |
|<span data-ttu-id="4a778-153">Exportar una copia de un contacto, el correo electrónico, la tarea o el elemento de calendario de fidelidad.</span><span class="sxs-lookup"><span data-stu-id="4a778-153">Export a copy of a contact, email, task, or calendar item in full-fidelity.</span></span>  <br/> |<span data-ttu-id="4a778-154">No disponible</span><span class="sxs-lookup"><span data-stu-id="4a778-154">Not applicable</span></span>  <br/> |[<span data-ttu-id="4a778-155">ExportItems</span><span class="sxs-lookup"><span data-stu-id="4a778-155">ExportItems</span></span>](http://msdn.microsoft.com/library/e2846abb-0b16-4732-bbd8-038a674672f6%28Office.15%29.aspx) <br/> |<span data-ttu-id="4a778-156">Ésta es la mejor opción para la exportación de los elementos del buzón que se desean volver a importar a un buzón de Exchange.</span><span class="sxs-lookup"><span data-stu-id="4a778-156">This is the best option for exporting mailbox items that you want to import back into an Exchange mailbox.</span></span> <span data-ttu-id="4a778-157">También puede usar esta opción para copiar elementos entre buzones de correo.</span><span class="sxs-lookup"><span data-stu-id="4a778-157">You can also use this option to copy items between mailboxes.</span></span> <span data-ttu-id="4a778-158">La operación **ExportItems** proporciona una secuencia opaca que representa el elemento que puede utilizar para mover la información entre los buzones de correo.</span><span class="sxs-lookup"><span data-stu-id="4a778-158">The **ExportItems** operation provides an opaque stream that represents the item that you can use to move information between mailboxes.</span></span> <span data-ttu-id="4a778-159">Puede usar **ExportItems** con la operación [GetItem](http://msdn.microsoft.com/library/e3590b8b-c2a7-4dad-a014-6360197b68e4%28Office.15%29.aspx) para crear un índice de la búsqueda de los elementos en otro sistema.</span><span class="sxs-lookup"><span data-stu-id="4a778-159">You can use **ExportItems** with the [GetItem](http://msdn.microsoft.com/library/e3590b8b-c2a7-4dad-a014-6360197b68e4%28Office.15%29.aspx) operation to make an index for finding the items in another system.</span></span> <span data-ttu-id="4a778-160">No se puede cambiar la secuencia de exportación.</span><span class="sxs-lookup"><span data-stu-id="4a778-160">You cannot change the export stream.</span></span>  <br/> <span data-ttu-id="4a778-161">Para obtener más información, vea [exportar elementos con plena fidelidad](how-to-export-items-by-using-ews-in-exchange.md#bk_exportfullfidelity).</span><span class="sxs-lookup"><span data-stu-id="4a778-161">For more information, see [Export items with full fidelity](how-to-export-items-by-using-ews-in-exchange.md#bk_exportfullfidelity).</span></span>  <br/> |
|<span data-ttu-id="4a778-162">Importar una copia de un contacto, el correo electrónico, la tarea o el elemento de calendario de fidelidad.</span><span class="sxs-lookup"><span data-stu-id="4a778-162">Import a copy of a contact, email, task, or calendar item in full-fidelity.</span></span>  <br/> |<span data-ttu-id="4a778-163">No disponible</span><span class="sxs-lookup"><span data-stu-id="4a778-163">Not applicable</span></span>  <br/> |[<span data-ttu-id="4a778-164">UploadItems</span><span class="sxs-lookup"><span data-stu-id="4a778-164">UploadItems</span></span>](http://msdn.microsoft.com/library/a88cbe99-7968-454d-a545-4f92c330909f%28Office.15%29.aspx) <br/> |<span data-ttu-id="4a778-165">Esta es la única opción para importar los elementos que se han exportado por la operación de **ExportItems** .</span><span class="sxs-lookup"><span data-stu-id="4a778-165">This is the only option for importing items that were exported by the **ExportItems** operation.</span></span>  <br/> |
|<span data-ttu-id="4a778-166">Exportar una copia de un contacto, el correo electrónico o el elemento de calendario como una secuencia MIME para un tipo de archivo comunes.</span><span class="sxs-lookup"><span data-stu-id="4a778-166">Export a copy of a contact, email, or calendar item as a MIME stream for a common file type.</span></span>  <br/> |[<span data-ttu-id="4a778-167">Contact.Bind</span><span class="sxs-lookup"><span data-stu-id="4a778-167">Contact.Bind</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.contact.bind%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-168">EmailMessage.Bind</span><span class="sxs-lookup"><span data-stu-id="4a778-168">EmailMessage.Bind</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.emailmessage.bind%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-169">Appointment.Bind</span><span class="sxs-lookup"><span data-stu-id="4a778-169">Appointment.Bind</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.bind%28v=exchg.80%29.aspx) <br/> |<span data-ttu-id="4a778-170">**GetItem**</span><span class="sxs-lookup"><span data-stu-id="4a778-170">**GetItem**</span></span> <br/> |<span data-ttu-id="4a778-171">Puede usar la propiedad [MimeContent](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.item.mimecontent%28v=exchg.80%29.aspx) para obtener la representación de secuencia MIME de un elemento.</span><span class="sxs-lookup"><span data-stu-id="4a778-171">You can use the [MimeContent](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.item.mimecontent%28v=exchg.80%29.aspx) property to get the MIME stream representation of an item.</span></span>  <br/> <span data-ttu-id="4a778-172">Esto proporcionará un subconjunto básico de todas las propiedades en un elemento.</span><span class="sxs-lookup"><span data-stu-id="4a778-172">This will provide a basic subset of all the properties on an item.</span></span> <span data-ttu-id="4a778-173">Como procedimiento recomendado, use sólo la secuencia MIME para las operaciones de uso único.</span><span class="sxs-lookup"><span data-stu-id="4a778-173">As a best practice, only use the MIME stream for one-off operations.</span></span> <span data-ttu-id="4a778-174">No confíe en MIME para grande y frecuente, importar y exportar de elementos, porque Exchange realiza la conversión de contenido para el MIME y esto puede afectar al rendimiento.</span><span class="sxs-lookup"><span data-stu-id="4a778-174">Do not rely on MIME for large and frequent importing/exporting of items, because Exchange performs content conversion for the MIME and this can affect performance.</span></span>  <br/> <span data-ttu-id="4a778-175">La secuencia MIME del **contacto** es un archivo [vCard](http://www.faqs.org/rfcs/rfc2426.mdl) (.vcf).</span><span class="sxs-lookup"><span data-stu-id="4a778-175">The **Contact** MIME stream is a [vCard](http://www.faqs.org/rfcs/rfc2426.mdl) (.vcf) file.</span></span> <span data-ttu-id="4a778-176">Dependiendo de las propiedades establecidas en un contacto, no esto podría generar una copia de fidelidad.</span><span class="sxs-lookup"><span data-stu-id="4a778-176">Depending on the properties set on a contact, this might not produce a full-fidelity copy.</span></span> <span data-ttu-id="4a778-177">Tenga en cuenta que no se puede importar un contacto mediante el uso de la secuencia MIME vCard.</span><span class="sxs-lookup"><span data-stu-id="4a778-177">Note that you cannot import a contact by using the vCard MIME stream.</span></span> <span data-ttu-id="4a778-178">Para obtener más información, consulte [exportación de un contacto en un archivo vCard](how-to-export-items-by-using-ews-in-exchange.md#bk_exportvcardmime).</span><span class="sxs-lookup"><span data-stu-id="4a778-178">To learn more, see [Export a contact into a vCard file](how-to-export-items-by-using-ews-in-exchange.md#bk_exportvcardmime).</span></span>  <br/> <span data-ttu-id="4a778-179">La secuencia MIME **EmailMessage** es un archivo EML.</span><span class="sxs-lookup"><span data-stu-id="4a778-179">The **EmailMessage** MIME stream is an .eml file.</span></span> <span data-ttu-id="4a778-180">El formato EML es conveniente debido a que Outlook y otros clientes de correo electrónico pueden identificar.</span><span class="sxs-lookup"><span data-stu-id="4a778-180">The .eml format is convenient because Outlook and other email clients can identify it.</span></span> <span data-ttu-id="4a778-181">También puede utilizar la secuencia MIME para crear un archivo .mht, que es conveniente debido a que muchos exploradores pueden usar ese tipo de archivo.</span><span class="sxs-lookup"><span data-stu-id="4a778-181">You can also use the MIME stream to create an .mht file, which is convenient because many browsers can use that file type.</span></span> <span data-ttu-id="4a778-182">EWS no proporciona una secuencia de archivo .msg para exportar un correo electrónico a un archivo .msg.</span><span class="sxs-lookup"><span data-stu-id="4a778-182">EWS doesn't provide a .msg file stream for exporting an email to a .msg file.</span></span> <span data-ttu-id="4a778-183">Las opciones para exportar un archivo .msg son en construcción [una. Archivo MSG](http://msdn.microsoft.com/en-us/library/cc463912%28v=EXCHG.80%29.aspx) desde los resultados de un método **EmailMessage.Bind** o **GetItem** operation llamar, o usar una API de terceros que llama a EWS y construye el archivo .msg de los resultados.</span><span class="sxs-lookup"><span data-stu-id="4a778-183">Your options for exporting an .msg file are to either [construct an .MSG file](http://msdn.microsoft.com/en-us/library/cc463912%28v=EXCHG.80%29.aspx) from the results of an **EmailMessage.Bind** method or **GetItem** operation call, or use a third-party API that calls EWS and constructs the .msg file from the results.</span></span> <span data-ttu-id="4a778-184">Para obtener más información, vea [exportar un correo electrónico como un archivo EML](how-to-export-items-by-using-ews-in-exchange.md#bk_exportemailmime).</span><span class="sxs-lookup"><span data-stu-id="4a778-184">For more information, see [Export an email as an .eml file](how-to-export-items-by-using-ews-in-exchange.md#bk_exportemailmime).</span></span>  <br/> <span data-ttu-id="4a778-185">La secuencia de **cita** MIME es un archivo de iCalendar (.ics).</span><span class="sxs-lookup"><span data-stu-id="4a778-185">The **Appointment** MIME stream is an iCal (.ics) file.</span></span> <span data-ttu-id="4a778-186">El formato .ics es conveniente debido a que Outlook y otros clientes de correo electrónico pueden identificar.</span><span class="sxs-lookup"><span data-stu-id="4a778-186">The .ics format is convenient because Outlook and other email clients can identify it.</span></span> <span data-ttu-id="4a778-187">No es una opción viable para la exportación de las reuniones debido a que no se proporciona información de los asistentes en la secuencia MIME.</span><span class="sxs-lookup"><span data-stu-id="4a778-187">This is not a viable option for exporting meetings because attendee information is not provided in the MIME stream.</span></span> <span data-ttu-id="4a778-188">No es posible que se incluyan los datos adjuntos y otras propiedades en la secuencia MIME.</span><span class="sxs-lookup"><span data-stu-id="4a778-188">Attachments and other properties might not be included in the MIME stream.</span></span> <span data-ttu-id="4a778-189">Considere la posibilidad de construir el formato iCal desde el objeto de [cita](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment%28v=exchg.80%29.aspx) o desde el XML devuelto por la operación **GetItem** .</span><span class="sxs-lookup"><span data-stu-id="4a778-189">Consider constructing the iCal format from either the [Appointment](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment%28v=exchg.80%29.aspx) object or from the XML returned by the **GetItem** operation.</span></span> <span data-ttu-id="4a778-190">De este modo, puede capturar más de las propiedades de Exchange con las propiedades extendidas ("X-' propiedades) en el archivo de iCalendar.</span><span class="sxs-lookup"><span data-stu-id="4a778-190">This way, you can capture more of the Exchange properties with extended properties ("X-' properties) in the iCal file.</span></span> <span data-ttu-id="4a778-191">También puede exportar una cita en formato XML.</span><span class="sxs-lookup"><span data-stu-id="4a778-191">You can also export an appointment in XML form.</span></span> <span data-ttu-id="4a778-192">Llamar a la operación **GetItem** y guardar el XML en el sistema.</span><span class="sxs-lookup"><span data-stu-id="4a778-192">Call the **GetItem** operation and save the XML in your system.</span></span> <span data-ttu-id="4a778-193">También puede usar la [funcionalidad de seguimiento](how-to-trace-requests-responses-to-troubleshoot-ews-managed-api-applications.md) en la API administrada de EWS para capturar el XML para poner en una base de datos XML.</span><span class="sxs-lookup"><span data-stu-id="4a778-193">You can also use the [tracing functionality](how-to-trace-requests-responses-to-troubleshoot-ews-managed-api-applications.md) in the EWS Managed API to capture the XML to put in an XML database.</span></span> <span data-ttu-id="4a778-194">Para obtener más información, consulte [exportación de una cita como un archivo de iCalendar](how-to-export-items-by-using-ews-in-exchange.md#bk_exporticalmime).</span><span class="sxs-lookup"><span data-stu-id="4a778-194">For more information, see [Exporting an appointment as an iCal file](how-to-export-items-by-using-ews-in-exchange.md#bk_exporticalmime).</span></span>  <br/> |
|<span data-ttu-id="4a778-195">Importar una copia de un elemento de correo electrónico o calendario como una secuencia MIME para un tipo de archivo comunes.</span><span class="sxs-lookup"><span data-stu-id="4a778-195">Import a copy of an email or calendar item as a MIME stream for a common file type.</span></span>  <br/> |[<span data-ttu-id="4a778-196">EmailMessage.Save</span><span class="sxs-lookup"><span data-stu-id="4a778-196">EmailMessage.Save</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.emailmessage.save%28v=exchg.80%29.aspx) <br/> [<span data-ttu-id="4a778-197">Appointment.Save</span><span class="sxs-lookup"><span data-stu-id="4a778-197">Appointment.Save</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.save%28v=exchg.80%29.aspx) <br/> |<span data-ttu-id="4a778-198">**CreateItem**</span><span class="sxs-lookup"><span data-stu-id="4a778-198">**CreateItem**</span></span> <br/> |<span data-ttu-id="4a778-199">Puede importar un archivo EML o .ics mediante el uso de la propiedad **MimeContent** en un objeto **EmailMessage** o **una cita** .</span><span class="sxs-lookup"><span data-stu-id="4a778-199">You can import an .eml or .ics file by using the **MimeContent** property on an **EmailMessage** or **Appointment** object.</span></span> <span data-ttu-id="4a778-200">Debe establecer el [PidTagMessageFlags (0x0E07)](http://msdn.microsoft.com/en-us/library/office/cc839733%28v=office.15%29.aspx) propiedad extendida si el correo electrónico no es un borrador.</span><span class="sxs-lookup"><span data-stu-id="4a778-200">You will need to set the [PidTagMessageFlags (0x0E07)](http://msdn.microsoft.com/en-us/library/office/cc839733%28v=office.15%29.aspx) extended property if the email is not a draft.</span></span>  <br/> <span data-ttu-id="4a778-201">No puede usar este enfoque para importar las reuniones.</span><span class="sxs-lookup"><span data-stu-id="4a778-201">You cannot use this approach to import meetings.</span></span>  <br/> |
   
## <a name="alternatives-to-exporting-and-importing-items-by-using-ews"></a><span data-ttu-id="4a778-202">Alternativas para exportar e importar elementos mediante el uso de EWS</span><span class="sxs-lookup"><span data-stu-id="4a778-202">Alternatives to exporting and importing items by using EWS</span></span>
<span data-ttu-id="4a778-203"><a name="alternatives"> </a></span><span class="sxs-lookup"><span data-stu-id="4a778-203"></span></span>

<span data-ttu-id="4a778-204">Otras opciones están disponibles para exporing y elementos de importación a y desde un buzón de Exchange.</span><span class="sxs-lookup"><span data-stu-id="4a778-204">Other options are available for exporing and importing items to and from an Exchange mailbox.</span></span> <span data-ttu-id="4a778-205">Las siguientes son algunas ideas a considerar cuando al diseñar la importación y exportación de estrategia:</span><span class="sxs-lookup"><span data-stu-id="4a778-205">The following are some ideas to consider when you design your import and export strategy:</span></span>
  
- <span data-ttu-id="4a778-206">Usar PowerShell para llamar a EWS y el formato de salida en un archivo .csv.</span><span class="sxs-lookup"><span data-stu-id="4a778-206">Use PowerShell to call EWS and format the output into a .csv file.</span></span>
    
- <span data-ttu-id="4a778-207">Uso de las bibliotecas de terceros que implementan MAPI para exportar e importar elementos.</span><span class="sxs-lookup"><span data-stu-id="4a778-207">Use third-party libraries that implement MAPI to export and import items.</span></span> <span data-ttu-id="4a778-208">Bibliotecas de otros fabricantes que conversión EWS a archivos .msg demasiado están disponibles.</span><span class="sxs-lookup"><span data-stu-id="4a778-208">Third-party libraries that convert EWS to .msg files are available too.</span></span>
    
- <span data-ttu-id="4a778-209">Use los cmdlets del Shell de administración de Exchange y [MailboxImportRequest](http://technet.microsoft.com/en-us/library/ff607310%28v=exchg.150%29.aspx) y [MailboxExportRequest](http://technet.microsoft.com/en-us/library/ff607299%28v=exchg.150%29.aspx) para [satisfacer la importación del buzón de correo y solicitudes de exportación](http://technet.microsoft.com/en-us/library/ee633455%28v=exchg.150%29.aspx).</span><span class="sxs-lookup"><span data-stu-id="4a778-209">Use the Exchange Management Shell and the [MailboxImportRequest](http://technet.microsoft.com/en-us/library/ff607310%28v=exchg.150%29.aspx) and [MailboxExportRequest](http://technet.microsoft.com/en-us/library/ff607299%28v=exchg.150%29.aspx) cmdlets to [fulfill mailbox import and export requests](http://technet.microsoft.com/en-us/library/ee633455%28v=exchg.150%29.aspx).</span></span> 
    
- <span data-ttu-id="4a778-210">Use [las opciones de importación de Outlook](http://office.microsoft.com/en-us/outlook-help/import-outlook-items-from-an-outlook-data-file-pst-HA102505743.aspx) para importar y exportar elementos.</span><span class="sxs-lookup"><span data-stu-id="4a778-210">Use [Outlook's import options](http://office.microsoft.com/en-us/outlook-help/import-outlook-items-from-an-outlook-data-file-pst-HA102505743.aspx) to import and export items.</span></span> 
    
## <a name="in-this-section"></a><span data-ttu-id="4a778-211">En esta sección</span><span class="sxs-lookup"><span data-stu-id="4a778-211">In this section</span></span>
<span data-ttu-id="4a778-212"><a name="alternatives"> </a></span><span class="sxs-lookup"><span data-stu-id="4a778-212"></span></span>

- [<span data-ttu-id="4a778-213">Exportar elementos mediante el uso de EWS en Exchange</span><span class="sxs-lookup"><span data-stu-id="4a778-213">Export items by using EWS in Exchange</span></span>](how-to-export-items-by-using-ews-in-exchange.md)
    
- [<span data-ttu-id="4a778-214">Importar elementos mediante el uso de EWS en Exchange</span><span class="sxs-lookup"><span data-stu-id="4a778-214">Import items by using EWS in Exchange</span></span>](how-to-import-items-by-using-ews-in-exchange.md)
    
## <a name="see-also"></a><span data-ttu-id="4a778-215">Ver también</span><span class="sxs-lookup"><span data-stu-id="4a778-215">See also</span></span>


- [<span data-ttu-id="4a778-216">Copia de seguridad, restauración y recuperación ante desastres</span><span class="sxs-lookup"><span data-stu-id="4a778-216">Backup, Restore, and Disaster Recovery</span></span>](http://technet.microsoft.com/en-us/library/dd876874%28v=exchg.150%29.aspx)
    
- [<span data-ttu-id="4a778-217">Registro en diario</span><span class="sxs-lookup"><span data-stu-id="4a778-217">Journaling</span></span>](http://technet.microsoft.com/en-us/library/aa998649%28v=exchg.150%29.aspx)
    
- [<span data-ttu-id="4a778-218">Especificación del objeto principal (RFC 5545) de programación y calendario de Internet</span><span class="sxs-lookup"><span data-stu-id="4a778-218">Internet Calendaring and Scheduling Core Object Specification (RFC 5545)</span></span>](http://tools.ietf.org/html/rfc5545)
    
- [<span data-ttu-id="4a778-219">Sincronización de buzón de correo y EWS en Exchange</span><span class="sxs-lookup"><span data-stu-id="4a778-219">Mailbox synchronization and EWS in Exchange</span></span>](mailbox-synchronization-and-ews-in-exchange.md)
    
