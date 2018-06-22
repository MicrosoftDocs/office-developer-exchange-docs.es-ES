---
title: FieldUri (regla)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: cecdea78-de9c-48be-ae31-03877feafeec
description: El elemento FieldURI especifica el URI para el campo de regla que causó el error de validación.
ms.openlocfilehash: 88ba54994625d3a950b58e900f28c986c31eddac
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764585"
---
# <a name="fielduri-rule"></a><span data-ttu-id="0b615-103">FieldUri (regla)</span><span class="sxs-lookup"><span data-stu-id="0b615-103">FieldUri (Rule)</span></span>

<span data-ttu-id="0b615-104">El elemento **FieldURI** especifica el URI para el campo de regla que causó el error de validación.</span><span class="sxs-lookup"><span data-stu-id="0b615-104">The **FieldURI** element specifies the URI to the rule field that caused the validation error.</span></span> 
  
```XML
<FieldURI/>
```

 <span data-ttu-id="0b615-105">**RuleFieldURIType**</span><span class="sxs-lookup"><span data-stu-id="0b615-105">**RuleFieldURIType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="0b615-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="0b615-106">Attributes and elements</span></span>

<span data-ttu-id="0b615-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="0b615-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="0b615-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="0b615-108">Attributes</span></span>

<span data-ttu-id="0b615-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="0b615-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="0b615-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="0b615-110">Child elements</span></span>

<span data-ttu-id="0b615-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="0b615-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="0b615-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="0b615-112">Parent elements</span></span>

|<span data-ttu-id="0b615-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="0b615-113">**Element**</span></span>|<span data-ttu-id="0b615-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="0b615-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="0b615-115">Error</span><span class="sxs-lookup"><span data-stu-id="0b615-115">Error</span></span>](error.md) <br/> |<span data-ttu-id="0b615-116">Representa un error de validación único en un valor de la propiedad de regla concreto, valor de la propiedad predicado o valor de la propiedad acción.</span><span class="sxs-lookup"><span data-stu-id="0b615-116">Represents a single validation error on a particular rule property value, predicate property value, or action property value.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="0b615-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="0b615-117">Text value</span></span>

<span data-ttu-id="0b615-118">El valor de texto para este elemento está restringido a una de las siguientes cadenas:</span><span class="sxs-lookup"><span data-stu-id="0b615-118">The text value for this element is restricted to one of the following strings:</span></span>
  
- <span data-ttu-id="0b615-119">Identificador de regla</span><span class="sxs-lookup"><span data-stu-id="0b615-119">RuleId</span></span>
    
- <span data-ttu-id="0b615-120">DisplayName</span><span class="sxs-lookup"><span data-stu-id="0b615-120">DisplayName</span></span>
    
- <span data-ttu-id="0b615-121">Prioridad</span><span class="sxs-lookup"><span data-stu-id="0b615-121">Priority</span></span>
    
- <span data-ttu-id="0b615-122">IsNotSupported</span><span class="sxs-lookup"><span data-stu-id="0b615-122">IsNotSupported</span></span>
    
- <span data-ttu-id="0b615-123">Acciones</span><span class="sxs-lookup"><span data-stu-id="0b615-123">Actions</span></span>
    
- <span data-ttu-id="0b615-124">Condición: categorías</span><span class="sxs-lookup"><span data-stu-id="0b615-124">Condition:Categories</span></span>
    
- <span data-ttu-id="0b615-125">Condición: ContainsBodyStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-125">Condition:ContainsBodyStrings</span></span>
    
- <span data-ttu-id="0b615-126">Condición: ContainsHeaderStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-126">Condition:ContainsHeaderStrings</span></span>
    
- <span data-ttu-id="0b615-127">Condición: ContainsRecipientStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-127">Condition:ContainsRecipientStrings</span></span>
    
- <span data-ttu-id="0b615-128">Condición: ContainsSenderStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-128">Condition:ContainsSenderStrings</span></span>
    
- <span data-ttu-id="0b615-129">Condición: ContainsSubjectOrBodyStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-129">Condition:ContainsSubjectOrBodyStrings</span></span>
    
- <span data-ttu-id="0b615-130">Condición: ContainsSubjectStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-130">Condition:ContainsSubjectStrings</span></span>
    
- <span data-ttu-id="0b615-131">Condición: FlaggedForAction</span><span class="sxs-lookup"><span data-stu-id="0b615-131">Condition:FlaggedForAction</span></span>
    
- <span data-ttu-id="0b615-132">Condición: FromAddresses</span><span class="sxs-lookup"><span data-stu-id="0b615-132">Condition:FromAddresses</span></span>
    
- <span data-ttu-id="0b615-133">Condición: FromConnectedAccounts</span><span class="sxs-lookup"><span data-stu-id="0b615-133">Condition:FromConnectedAccounts</span></span>
    
- <span data-ttu-id="0b615-134">Condición: HasAttachments</span><span class="sxs-lookup"><span data-stu-id="0b615-134">Condition:HasAttachments</span></span>
    
- <span data-ttu-id="0b615-135">Condición: importancia</span><span class="sxs-lookup"><span data-stu-id="0b615-135">Condition:Importance</span></span>
    
- <span data-ttu-id="0b615-136">Condición: IsApprovalRequest</span><span class="sxs-lookup"><span data-stu-id="0b615-136">Condition:IsApprovalRequest</span></span>
    
- <span data-ttu-id="0b615-137">Condición: IsAutomaticForward</span><span class="sxs-lookup"><span data-stu-id="0b615-137">Condition:IsAutomaticForward</span></span>
    
- <span data-ttu-id="0b615-138">Condición: IsAutomaticReply</span><span class="sxs-lookup"><span data-stu-id="0b615-138">Condition:IsAutomaticReply</span></span>
    
- <span data-ttu-id="0b615-139">Condición: IsEncrypted</span><span class="sxs-lookup"><span data-stu-id="0b615-139">Condition:IsEncrypted</span></span>
    
- <span data-ttu-id="0b615-140">Condición: IsMeetingRequest</span><span class="sxs-lookup"><span data-stu-id="0b615-140">Condition:IsMeetingRequest</span></span>
    
- <span data-ttu-id="0b615-141">Condición: IsMeetingResponse</span><span class="sxs-lookup"><span data-stu-id="0b615-141">Condition:IsMeetingResponse</span></span>
    
- <span data-ttu-id="0b615-142">Condición: IsNDR</span><span class="sxs-lookup"><span data-stu-id="0b615-142">Condition:IsNDR</span></span>
    
- <span data-ttu-id="0b615-143">Condición: IsPermissionControlled</span><span class="sxs-lookup"><span data-stu-id="0b615-143">Condition:IsPermissionControlled</span></span>
    
- <span data-ttu-id="0b615-144">Condición: IsReadReceipt</span><span class="sxs-lookup"><span data-stu-id="0b615-144">Condition:IsReadReceipt</span></span>
    
- <span data-ttu-id="0b615-145">Condición: IsSigned</span><span class="sxs-lookup"><span data-stu-id="0b615-145">Condition:IsSigned</span></span>
    
- <span data-ttu-id="0b615-146">Condición: IsVoicemail</span><span class="sxs-lookup"><span data-stu-id="0b615-146">Condition:IsVoicemail</span></span>
    
- <span data-ttu-id="0b615-147">Condición: ItemClasses</span><span class="sxs-lookup"><span data-stu-id="0b615-147">Condition:ItemClasses</span></span>
    
- <span data-ttu-id="0b615-148">Condición: MessageClassifications</span><span class="sxs-lookup"><span data-stu-id="0b615-148">Condition:MessageClassifications</span></span>
    
- <span data-ttu-id="0b615-149">Condición: NotSentToMe</span><span class="sxs-lookup"><span data-stu-id="0b615-149">Condition:NotSentToMe</span></span>
    
- <span data-ttu-id="0b615-150">Condición: SentCcMe</span><span class="sxs-lookup"><span data-stu-id="0b615-150">Condition:SentCcMe</span></span>
    
- <span data-ttu-id="0b615-151">Condición: SentOnlyToMe</span><span class="sxs-lookup"><span data-stu-id="0b615-151">Condition:SentOnlyToMe</span></span>
    
- <span data-ttu-id="0b615-152">Condición: SentToAddresses</span><span class="sxs-lookup"><span data-stu-id="0b615-152">Condition:SentToAddresses</span></span>
    
- <span data-ttu-id="0b615-153">Condición: SentToMe</span><span class="sxs-lookup"><span data-stu-id="0b615-153">Condition:SentToMe</span></span>
    
- <span data-ttu-id="0b615-154">Condición: SentToOrCcMe</span><span class="sxs-lookup"><span data-stu-id="0b615-154">Condition:SentToOrCcMe</span></span>
    
- <span data-ttu-id="0b615-155">Condición: sensibilidad</span><span class="sxs-lookup"><span data-stu-id="0b615-155">Condition:Sensitivity</span></span>
    
- <span data-ttu-id="0b615-156">Condición: WithinDateRange</span><span class="sxs-lookup"><span data-stu-id="0b615-156">Condition:WithinDateRange</span></span>
    
- <span data-ttu-id="0b615-157">Condición: WithinSizeRange</span><span class="sxs-lookup"><span data-stu-id="0b615-157">Condition:WithinSizeRange</span></span>
    
- <span data-ttu-id="0b615-158">Excepción: categorías</span><span class="sxs-lookup"><span data-stu-id="0b615-158">Exception:Categories</span></span>
    
- <span data-ttu-id="0b615-159">Excepción: ContainsBodyStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-159">Exception:ContainsBodyStrings</span></span>
    
- <span data-ttu-id="0b615-160">Excepción: ContainsHeaderStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-160">Exception:ContainsHeaderStrings</span></span>
    
- <span data-ttu-id="0b615-161">Excepción: ContainsRecipientStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-161">Exception:ContainsRecipientStrings</span></span>
    
- <span data-ttu-id="0b615-162">Excepción: ContainsSenderStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-162">Exception:ContainsSenderStrings</span></span>
    
- <span data-ttu-id="0b615-163">Excepción: ContainsSubjectOrBodyStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-163">Exception:ContainsSubjectOrBodyStrings</span></span>
    
- <span data-ttu-id="0b615-164">Excepción: ContainsSubjectStrings</span><span class="sxs-lookup"><span data-stu-id="0b615-164">Exception:ContainsSubjectStrings</span></span>
    
- <span data-ttu-id="0b615-165">Excepción: FlaggedForAction</span><span class="sxs-lookup"><span data-stu-id="0b615-165">Exception:FlaggedForAction</span></span>
    
- <span data-ttu-id="0b615-166">Excepción: FromAddresses</span><span class="sxs-lookup"><span data-stu-id="0b615-166">Exception:FromAddresses</span></span>
    
- <span data-ttu-id="0b615-167">Excepción: FromConnectedAccounts</span><span class="sxs-lookup"><span data-stu-id="0b615-167">Exception:FromConnectedAccounts</span></span>
    
- <span data-ttu-id="0b615-168">Excepción: HasAttachments</span><span class="sxs-lookup"><span data-stu-id="0b615-168">Exception:HasAttachments</span></span>
    
- <span data-ttu-id="0b615-169">Excepción: importancia</span><span class="sxs-lookup"><span data-stu-id="0b615-169">Exception:Importance</span></span>
    
- <span data-ttu-id="0b615-170">Excepción: IsApprovalRequest</span><span class="sxs-lookup"><span data-stu-id="0b615-170">Exception:IsApprovalRequest</span></span>
    
- <span data-ttu-id="0b615-171">Excepción: IsAutomaticForward</span><span class="sxs-lookup"><span data-stu-id="0b615-171">Exception:IsAutomaticForward</span></span>
    
- <span data-ttu-id="0b615-172">Excepción: IsAutomaticReply</span><span class="sxs-lookup"><span data-stu-id="0b615-172">Exception:IsAutomaticReply</span></span>
    
- <span data-ttu-id="0b615-173">Excepción: IsEncrypted</span><span class="sxs-lookup"><span data-stu-id="0b615-173">Exception:IsEncrypted</span></span>
    
- <span data-ttu-id="0b615-174">Excepción: IsMeetingRequest</span><span class="sxs-lookup"><span data-stu-id="0b615-174">Exception:IsMeetingRequest</span></span>
    
- <span data-ttu-id="0b615-175">Excepción: IsMeetingResponse</span><span class="sxs-lookup"><span data-stu-id="0b615-175">Exception:IsMeetingResponse</span></span>
    
- <span data-ttu-id="0b615-176">Excepción: IsNDR</span><span class="sxs-lookup"><span data-stu-id="0b615-176">Exception:IsNDR</span></span>
    
- <span data-ttu-id="0b615-177">Excepción: IsPermissionControlled</span><span class="sxs-lookup"><span data-stu-id="0b615-177">Exception:IsPermissionControlled</span></span>
    
- <span data-ttu-id="0b615-178">Excepción: IsReadReceipt</span><span class="sxs-lookup"><span data-stu-id="0b615-178">Exception:IsReadReceipt</span></span>
    
- <span data-ttu-id="0b615-179">Excepción: IsSigned</span><span class="sxs-lookup"><span data-stu-id="0b615-179">Exception:IsSigned</span></span>
    
- <span data-ttu-id="0b615-180">Excepción: IsVoicemail</span><span class="sxs-lookup"><span data-stu-id="0b615-180">Exception:IsVoicemail</span></span>
    
- <span data-ttu-id="0b615-181">Excepción: ItemClasses</span><span class="sxs-lookup"><span data-stu-id="0b615-181">Exception:ItemClasses</span></span>
    
- <span data-ttu-id="0b615-182">Excepción: MessageClassifications</span><span class="sxs-lookup"><span data-stu-id="0b615-182">Exception:MessageClassifications</span></span>
    
- <span data-ttu-id="0b615-183">Excepción: NotSentToMe</span><span class="sxs-lookup"><span data-stu-id="0b615-183">Exception:NotSentToMe</span></span>
    
- <span data-ttu-id="0b615-184">Excepción: SentCcMe</span><span class="sxs-lookup"><span data-stu-id="0b615-184">Exception:SentCcMe</span></span>
    
- <span data-ttu-id="0b615-185">Excepción: SentOnlyToMe</span><span class="sxs-lookup"><span data-stu-id="0b615-185">Exception:SentOnlyToMe</span></span>
    
- <span data-ttu-id="0b615-186">Excepción: SentToAddresses</span><span class="sxs-lookup"><span data-stu-id="0b615-186">Exception:SentToAddresses</span></span>
    
- <span data-ttu-id="0b615-187">Excepción: SentToMe</span><span class="sxs-lookup"><span data-stu-id="0b615-187">Exception:SentToMe</span></span>
    
- <span data-ttu-id="0b615-188">Excepción: SentToOrCcMe</span><span class="sxs-lookup"><span data-stu-id="0b615-188">Exception:SentToOrCcMe</span></span>
    
- <span data-ttu-id="0b615-189">Excepción: sensibilidad</span><span class="sxs-lookup"><span data-stu-id="0b615-189">Exception:Sensitivity</span></span>
    
- <span data-ttu-id="0b615-190">Excepción: WithinDateRange</span><span class="sxs-lookup"><span data-stu-id="0b615-190">Exception:WithinDateRange</span></span>
    
- <span data-ttu-id="0b615-191">Excepción: WithinSizeRange</span><span class="sxs-lookup"><span data-stu-id="0b615-191">Exception:WithinSizeRange</span></span>
    
- <span data-ttu-id="0b615-192">Acción: AssignCategories</span><span class="sxs-lookup"><span data-stu-id="0b615-192">Action:AssignCategories</span></span>
    
- <span data-ttu-id="0b615-193">Acción: CopyToFolder</span><span class="sxs-lookup"><span data-stu-id="0b615-193">Action:CopyToFolder</span></span>
    
- <span data-ttu-id="0b615-194">Eliminación de la acción:</span><span class="sxs-lookup"><span data-stu-id="0b615-194">Action:Delete</span></span>
    
- <span data-ttu-id="0b615-195">Acción: ForwardAsAttachmentToRecipients</span><span class="sxs-lookup"><span data-stu-id="0b615-195">Action:ForwardAsAttachmentToRecipients</span></span>
    
- <span data-ttu-id="0b615-196">Acción: ForwardToRecipients</span><span class="sxs-lookup"><span data-stu-id="0b615-196">Action:ForwardToRecipients</span></span>
    
- <span data-ttu-id="0b615-197">Acción: MarkImportance</span><span class="sxs-lookup"><span data-stu-id="0b615-197">Action:MarkImportance</span></span>
    
- <span data-ttu-id="0b615-198">Acción: MarkAsRead</span><span class="sxs-lookup"><span data-stu-id="0b615-198">Action:MarkAsRead</span></span>
    
- <span data-ttu-id="0b615-199">Acción: MoveToFolder</span><span class="sxs-lookup"><span data-stu-id="0b615-199">Action:MoveToFolder</span></span>
    
- <span data-ttu-id="0b615-200">Acción: PermanentDelete</span><span class="sxs-lookup"><span data-stu-id="0b615-200">Action:PermanentDelete</span></span>
    
- <span data-ttu-id="0b615-201">Acción: RedirectToRecipients</span><span class="sxs-lookup"><span data-stu-id="0b615-201">Action:RedirectToRecipients</span></span>
    
- <span data-ttu-id="0b615-202">Acción: SendSMSAlertToRecipients</span><span class="sxs-lookup"><span data-stu-id="0b615-202">Action:SendSMSAlertToRecipients</span></span>
    
- <span data-ttu-id="0b615-203">Acción: ServerReplyWithMessage</span><span class="sxs-lookup"><span data-stu-id="0b615-203">Action:ServerReplyWithMessage</span></span>
    
- <span data-ttu-id="0b615-204">Acción: StopProcessingRules</span><span class="sxs-lookup"><span data-stu-id="0b615-204">Action:StopProcessingRules</span></span>
    
- <span data-ttu-id="0b615-205">IsEnabled</span><span class="sxs-lookup"><span data-stu-id="0b615-205">IsEnabled</span></span>
    
- <span data-ttu-id="0b615-206">IsInError</span><span class="sxs-lookup"><span data-stu-id="0b615-206">IsInError</span></span>
    
- <span data-ttu-id="0b615-207">Condiciones</span><span class="sxs-lookup"><span data-stu-id="0b615-207">Conditions</span></span>
    
- <span data-ttu-id="0b615-208">Excepciones</span><span class="sxs-lookup"><span data-stu-id="0b615-208">Exceptions</span></span>
    
## <a name="remarks"></a><span data-ttu-id="0b615-209">Notas</span><span class="sxs-lookup"><span data-stu-id="0b615-209">Remarks</span></span>

<span data-ttu-id="0b615-210">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="0b615-210">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="0b615-211">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="0b615-211">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0b615-212">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="0b615-212">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="0b615-213">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="0b615-213">Schema Name</span></span>  <br/> |<span data-ttu-id="0b615-214">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="0b615-214">Messages schema</span></span>  <br/> |
|<span data-ttu-id="0b615-215">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="0b615-215">Validation File</span></span>  <br/> |<span data-ttu-id="0b615-216">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="0b615-216">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="0b615-217">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="0b615-217">Can be Empty</span></span>  <br/> |<span data-ttu-id="0b615-218">False</span><span class="sxs-lookup"><span data-stu-id="0b615-218">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="0b615-219">Ver también</span><span class="sxs-lookup"><span data-stu-id="0b615-219">See also</span></span>



- [<span data-ttu-id="0b615-220">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="0b615-220">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
