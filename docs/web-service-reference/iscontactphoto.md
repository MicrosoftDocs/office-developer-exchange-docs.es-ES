---
title: IsContactPhoto
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IsContactPhoto
api_type:
- schema
ms.assetid: ae36b5f9-a787-4863-9dbc-258ad724801d
description: El elemento IsContactPhoto indica si el archivo adjunto es una imagen del contacto.
ms.openlocfilehash: a015cd9bdb34ea9275952d5fe252a30cacf888ac
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19835999"
---
# <a name="iscontactphoto"></a><span data-ttu-id="64a23-103">IsContactPhoto</span><span class="sxs-lookup"><span data-stu-id="64a23-103">IsContactPhoto</span></span>

<span data-ttu-id="64a23-104">El elemento **IsContactPhoto** indica si el archivo adjunto es una imagen del contacto.</span><span class="sxs-lookup"><span data-stu-id="64a23-104">The **IsContactPhoto** element indicates whether the file attachment is a contact picture.</span></span> 
  
```xml
<IsContactPhoto>true or false</IsContactPhoto>
```

 <span data-ttu-id="64a23-105">**boolean**</span><span class="sxs-lookup"><span data-stu-id="64a23-105">**boolean**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="64a23-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="64a23-106">Attributes and elements</span></span>

<span data-ttu-id="64a23-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="64a23-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="64a23-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="64a23-108">Attributes</span></span>

<span data-ttu-id="64a23-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="64a23-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="64a23-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="64a23-110">Child elements</span></span>

<span data-ttu-id="64a23-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="64a23-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="64a23-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="64a23-112">Parent elements</span></span>

|<span data-ttu-id="64a23-113">**Element**</span><span class="sxs-lookup"><span data-stu-id="64a23-113">**Element**</span></span>|<span data-ttu-id="64a23-114">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="64a23-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="64a23-115">FileAttachment</span><span class="sxs-lookup"><span data-stu-id="64a23-115">FileAttachment</span></span>](fileattachment.md) <br/> |<span data-ttu-id="64a23-116">Representa un archivo que se adjunta a un elemento en el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="64a23-116">Represents a file that is attached to an item in the Exchange store.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="64a23-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="64a23-117">Text value</span></span>

<span data-ttu-id="64a23-118">Este elemento puede ser **true** o **false**.</span><span class="sxs-lookup"><span data-stu-id="64a23-118">This element can be either **true** or **false**.</span></span> <span data-ttu-id="64a23-119">El valor predeterminado es **false**.</span><span class="sxs-lookup"><span data-stu-id="64a23-119">The default value is **false**.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="64a23-120">Notas</span><span class="sxs-lookup"><span data-stu-id="64a23-120">Remarks</span></span>

<span data-ttu-id="64a23-121">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que ejecuta Microsoft Exchange Server que tiene instalada la función del servidor acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="64a23-121">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="64a23-122">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="64a23-122">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="64a23-123">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="64a23-123">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="64a23-124">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="64a23-124">Schema Name</span></span>  <br/> |<span data-ttu-id="64a23-125">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="64a23-125">Types schema</span></span>  <br/> |
|<span data-ttu-id="64a23-126">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="64a23-126">Validation File</span></span>  <br/> |<span data-ttu-id="64a23-127">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="64a23-127">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="64a23-128">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="64a23-128">Can be Empty</span></span>  <br/> |<span data-ttu-id="64a23-129">False</span><span class="sxs-lookup"><span data-stu-id="64a23-129">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="64a23-130">Ver también</span><span class="sxs-lookup"><span data-stu-id="64a23-130">See also</span></span>



- [<span data-ttu-id="64a23-131">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="64a23-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
