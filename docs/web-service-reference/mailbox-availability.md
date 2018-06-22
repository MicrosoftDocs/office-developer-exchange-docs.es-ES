---
title: Buzón de correo (disponibilidad)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Mailbox
api_type:
- schema
ms.assetid: affd192e-8914-473f-9098-d9bdf898de2c
description: El elemento de buzón de correo representa al usuario de buzón de correo para un SetUserOofSettings o solicitar GetUserOofSettings.
ms.openlocfilehash: 2e901ae0df56542f56f247184254294735018468
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836254"
---
# <a name="mailbox-availability"></a><span data-ttu-id="21afe-103">Buzón de correo (disponibilidad)</span><span class="sxs-lookup"><span data-stu-id="21afe-103">Mailbox (Availability)</span></span>

<span data-ttu-id="21afe-104">El elemento de **buzón de correo** representa al usuario de buzón de correo para un SetUserOofSettings o solicitar GetUserOofSettings.</span><span class="sxs-lookup"><span data-stu-id="21afe-104">The **Mailbox** element represents the mailbox user for a SetUserOofSettings or GetUserOofSettings request.</span></span> 
  
```xml
<Mailbox>
   <Name>...</Name>
   <Address>...</Address>
   <RoutingType>...</RoutingType>
</Mailbox>
```

<span data-ttu-id="21afe-105">**EmailAddressType**</span><span class="sxs-lookup"><span data-stu-id="21afe-105">**EmailAddressType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="21afe-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="21afe-106">Attributes and elements</span></span>

<span data-ttu-id="21afe-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="21afe-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="21afe-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="21afe-108">Attributes</span></span>

<span data-ttu-id="21afe-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="21afe-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="21afe-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="21afe-110">Child elements</span></span>

|<span data-ttu-id="21afe-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="21afe-111">**Element**</span></span>|<span data-ttu-id="21afe-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="21afe-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="21afe-113">Nombre (EmailAddress)</span><span class="sxs-lookup"><span data-stu-id="21afe-113">Name (EmailAddress)</span></span>](name-emailaddress.md) <br/> |<span data-ttu-id="21afe-114">Representa el nombre para mostrar del usuario de buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="21afe-114">Represents the display name of the mailbox user.</span></span> <span data-ttu-id="21afe-115">Este elemento es opcional en el SetUserOofSettingsRequest.</span><span class="sxs-lookup"><span data-stu-id="21afe-115">This element is optional in the SetUserOofSettingsRequest.</span></span> <span data-ttu-id="21afe-116">El GetUserOofSettingsRequest devolverá este elemento.</span><span class="sxs-lookup"><span data-stu-id="21afe-116">The GetUserOofSettingsRequest will return this element.</span></span>  <br/> |
|[<span data-ttu-id="21afe-117">Dirección (cadena)</span><span class="sxs-lookup"><span data-stu-id="21afe-117">Address (string)</span></span>](address-string.md) <br/> |<span data-ttu-id="21afe-118">Representa la dirección de correo electrónico del usuario de buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="21afe-118">Represents the e-mail address of the mailbox user.</span></span> <span data-ttu-id="21afe-119">Se requiere este elemento.</span><span class="sxs-lookup"><span data-stu-id="21afe-119">This element is required.</span></span>  <br/> |
|[<span data-ttu-id="21afe-120">RoutingType (EmailAddress)</span><span class="sxs-lookup"><span data-stu-id="21afe-120">RoutingType (EmailAddress)</span></span>](routingtype-emailaddress.md) <br/> |<span data-ttu-id="21afe-121">Representa el protocolo de enrutamiento para el mensaje.</span><span class="sxs-lookup"><span data-stu-id="21afe-121">Represents the routing protocol for the message.</span></span> <span data-ttu-id="21afe-122">Este elemento es opcional en el SetUserOofSettingsRequest.</span><span class="sxs-lookup"><span data-stu-id="21afe-122">This element is optional in the SetUserOofSettingsRequest.</span></span> <span data-ttu-id="21afe-123">El GetUserOofSettingsRequest devolverá este elemento.</span><span class="sxs-lookup"><span data-stu-id="21afe-123">The GetUserOofSettingsRequest will return this element.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="21afe-124">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="21afe-124">Parent elements</span></span>

|<span data-ttu-id="21afe-125">**Element**</span><span class="sxs-lookup"><span data-stu-id="21afe-125">**Element**</span></span>|<span data-ttu-id="21afe-126">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="21afe-126">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="21afe-127">GetUserOofSettingsRequest</span><span class="sxs-lookup"><span data-stu-id="21afe-127">GetUserOofSettingsRequest</span></span>](getuseroofsettingsrequest.md) <br/> |<span data-ttu-id="21afe-128">Se usa para obtener la configuración de fuera de oficina (OOF) y los mensajes de un usuario de buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="21afe-128">Used to get a mailbox user's Out of Office (OOF) settings and messages.</span></span>  <br/> <span data-ttu-id="21afe-129">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="21afe-129">The following is the XPath expression to this element:</span></span>  <br/>  `/GetUserOofSettingsRequest` <br/> |
|[<span data-ttu-id="21afe-130">SetUserOofSettingsRequest</span><span class="sxs-lookup"><span data-stu-id="21afe-130">SetUserOofSettingsRequest</span></span>](setuseroofsettingsrequest.md) <br/> |<span data-ttu-id="21afe-131">Se usa para establecer la configuración de fuera de la oficina y los mensajes de un usuario de buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="21afe-131">Used to set a mailbox user's OOF settings and messages.</span></span>  <br/> <span data-ttu-id="21afe-132">La siguiente es la expresión de XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="21afe-132">The following is the XPath expression to this element:</span></span>  <br/>  `/SetUserOofSettingsRequest` <br/> |
   
## <a name="remarks"></a><span data-ttu-id="21afe-133">Notas</span><span class="sxs-lookup"><span data-stu-id="21afe-133">Remarks</span></span>

<span data-ttu-id="21afe-134">La dirección de correo electrónico se usa para identificar la carpeta de calendario que contiene la configuración de fuera de la oficina.</span><span class="sxs-lookup"><span data-stu-id="21afe-134">The e-mail address is used to identify the calendar folder that contains the OOF settings.</span></span> 
  
<span data-ttu-id="21afe-135">El esquema que describe este elemento se encuentra en el directorio virtual de EWS del equipo que está ejecutando MicrosoftExchange Server 2007 que tenga instalado el rol de servidor de acceso de cliente.</span><span class="sxs-lookup"><span data-stu-id="21afe-135">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="21afe-136">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="21afe-136">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="21afe-137">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="21afe-137">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="21afe-138">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="21afe-138">Schema Name</span></span>  <br/> |<span data-ttu-id="21afe-139">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="21afe-139">Types schema</span></span>  <br/> |
|<span data-ttu-id="21afe-140">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="21afe-140">Validation File</span></span>  <br/> |<span data-ttu-id="21afe-141">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="21afe-141">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="21afe-142">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="21afe-142">Can be Empty</span></span>  <br/> |<span data-ttu-id="21afe-143">False</span><span class="sxs-lookup"><span data-stu-id="21afe-143">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="21afe-144">Ver también</span><span class="sxs-lookup"><span data-stu-id="21afe-144">See also</span></span>

- [<span data-ttu-id="21afe-145">Operación GetUserOofSettings</span><span class="sxs-lookup"><span data-stu-id="21afe-145">GetUserOofSettings operation</span></span>](getuseroofsettings-operation.md)
- [<span data-ttu-id="21afe-146">Operación SetUserOofSettings</span><span class="sxs-lookup"><span data-stu-id="21afe-146">SetUserOofSettings operation</span></span>](setuseroofsettings-operation.md)
