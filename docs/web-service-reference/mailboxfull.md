---
title: MailboxFull
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- MailboxFull
api_type:
- schema
ms.assetid: 38b28c9b-9da2-4d6a-9cda-9c393986575b
description: El elemento MailboxFull indica si el buzón del destinatario está lleno.
ms.openlocfilehash: 8e2c9e01b93af03e875834724a942cd9b17a73f3
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836286"
---
# <a name="mailboxfull"></a><span data-ttu-id="f294f-103">MailboxFull</span><span class="sxs-lookup"><span data-stu-id="f294f-103">MailboxFull</span></span>

<span data-ttu-id="f294f-104">El elemento **MailboxFull** indica si el buzón del destinatario está lleno.</span><span class="sxs-lookup"><span data-stu-id="f294f-104">The **MailboxFull** element indicates whether the mailbox for the recipient is full.</span></span> 
  
```XML
<MailboxFull>true | false</MailboxFull>
```

<span data-ttu-id="f294f-105">**Boolean**</span><span class="sxs-lookup"><span data-stu-id="f294f-105">**Boolean**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="f294f-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="f294f-106">Attributes and elements</span></span>

<span data-ttu-id="f294f-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="f294f-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="f294f-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="f294f-108">Attributes</span></span>

<span data-ttu-id="f294f-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="f294f-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="f294f-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="f294f-110">Child elements</span></span>

<span data-ttu-id="f294f-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="f294f-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="f294f-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="f294f-112">Parent elements</span></span>

|<span data-ttu-id="f294f-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="f294f-113">**Element**</span></span>|<span data-ttu-id="f294f-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="f294f-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="f294f-115">Sugerencias de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="f294f-115">MailTips</span></span>](mailtips.md) <br/> |<span data-ttu-id="f294f-116">Representa los valores de distintos tipos de sugerencias de correo.</span><span class="sxs-lookup"><span data-stu-id="f294f-116">Represents values for various types of mail tips.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="f294f-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="f294f-117">Text value</span></span>

<span data-ttu-id="f294f-118">Este elemento puede ser **true** o **false**.</span><span class="sxs-lookup"><span data-stu-id="f294f-118">This element can be either **true** or **false**.</span></span> <span data-ttu-id="f294f-119">Un valor de **true** indica que el buzón de correo ha alcanzado su capacidad; un valor de **false** indica que no ha alcanzado la capacidad.</span><span class="sxs-lookup"><span data-stu-id="f294f-119">A value of **true** indicates that the mailbox has reached its capacity; a value of **false** indicates that it has not reached capacity.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="f294f-120">Notas</span><span class="sxs-lookup"><span data-stu-id="f294f-120">Remarks</span></span>

<span data-ttu-id="f294f-121">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="f294f-121">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="f294f-122">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="f294f-122">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="f294f-123">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="f294f-123">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="f294f-124">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="f294f-124">Schema Name</span></span>  <br/> |<span data-ttu-id="f294f-125">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="f294f-125">Types schema</span></span>  <br/> |
|<span data-ttu-id="f294f-126">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="f294f-126">Validation File</span></span>  <br/> |<span data-ttu-id="f294f-127">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="f294f-127">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="f294f-128">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="f294f-128">Can be Empty</span></span>  <br/> |<span data-ttu-id="f294f-129">False</span><span class="sxs-lookup"><span data-stu-id="f294f-129">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="f294f-130">Ver también</span><span class="sxs-lookup"><span data-stu-id="f294f-130">See also</span></span>

- [<span data-ttu-id="f294f-131">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="f294f-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
