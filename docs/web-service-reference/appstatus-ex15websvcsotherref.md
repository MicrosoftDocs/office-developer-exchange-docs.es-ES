---
title: AppStatus
manager: sethgros
ms.date: 03/9/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: f3ab8bf1-abc5-45cf-a2e1-d7602f2c24ec
description: El valor del elemento AppStatus indica el estado de la aplicación de correo.
ms.openlocfilehash: cf213fc3d7be02c411e9c2e83a4ff153dbefe098
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/25/2018
ms.locfileid: "19763543"
---
# <a name="appstatus"></a><span data-ttu-id="235e4-103">AppStatus</span><span class="sxs-lookup"><span data-stu-id="235e4-103">AppStatus</span></span>

<span data-ttu-id="235e4-104">El valor del elemento **AppStatus** indica el estado de la aplicación de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-104">The **AppStatus** element value indicates the status of the mail app.</span></span> 
  
```XML
<AppStatus/>
```

 <span data-ttu-id="235e4-105">**string**</span><span class="sxs-lookup"><span data-stu-id="235e4-105">**string**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="235e4-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="235e4-106">Attributes and elements</span></span>

<span data-ttu-id="235e4-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="235e4-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="235e4-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="235e4-108">Attributes</span></span>

<span data-ttu-id="235e4-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="235e4-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="235e4-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="235e4-110">Child elements</span></span>

<span data-ttu-id="235e4-111">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="235e4-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="235e4-112">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="235e4-112">Parent elements</span></span>

[<span data-ttu-id="235e4-113">Metadatos</span><span class="sxs-lookup"><span data-stu-id="235e4-113">Metadata</span></span>](metadata-ex15websvcsotherref.md)
  
## <a name="text-value"></a><span data-ttu-id="235e4-114">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="235e4-114">Text value</span></span>

<span data-ttu-id="235e4-115">El valor de texto del elemento **AppStatus** indica el estado de la aplicación de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-115">The text value of the **AppStatus** element indicates the status of the mail app.</span></span> <span data-ttu-id="235e4-116">Si el usuario puede corregir un problema relacionado con el estado de la aplicación de correo, el elemento [ActionUrl](actionurl.md) proporciona la dirección URL para realizar la corrección.</span><span class="sxs-lookup"><span data-stu-id="235e4-116">If the user can fix an issue related to the status of the mail app, the [ActionUrl](actionurl.md) element provides the URL to perform the fix.</span></span> 
  
<span data-ttu-id="235e4-117">**La tabla 1. Valores de AppStatus**</span><span class="sxs-lookup"><span data-stu-id="235e4-117">**Table 1. AppStatus values**</span></span>

|<span data-ttu-id="235e4-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="235e4-118">**Value**</span></span>|<span data-ttu-id="235e4-119">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="235e4-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="235e4-120">Null o 0</span><span class="sxs-lookup"><span data-stu-id="235e4-120">Null or 0</span></span>  <br/> |<span data-ttu-id="235e4-121">La aplicación de correo tiene un estado correcto.</span><span class="sxs-lookup"><span data-stu-id="235e4-121">The mail app has a healthy status.</span></span>  <br/> |
|<span data-ttu-id="235e4-122">1.0</span><span class="sxs-lookup"><span data-stu-id="235e4-122">1.0</span></span>  <br/> |<span data-ttu-id="235e4-123">No se pudo actualizar automáticamente la aplicación de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-123">The mail app could not be automatically updated.</span></span> <span data-ttu-id="235e4-124">La aplicación de correo debe estar instalado volver a desde el almacén de Office.</span><span class="sxs-lookup"><span data-stu-id="235e4-124">The mail app needs to be re-installed from the Office Store.</span></span>  <br/> |
|<span data-ttu-id="235e4-125">1.1</span><span class="sxs-lookup"><span data-stu-id="235e4-125">1.1</span></span>  <br/> |<span data-ttu-id="235e4-126">No se pudo actualizar automáticamente la aplicación de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-126">The mail app could not be automatically updated.</span></span> <span data-ttu-id="235e4-127">La aplicación de correo requiere permisos mayor, y esto requiere la revisión y la confirmación para instalar.</span><span class="sxs-lookup"><span data-stu-id="235e4-127">The mail app requires increased permissions, and this requires your review and confirmation to install.</span></span>  <br/> |
|<span data-ttu-id="235e4-128">1.2</span><span class="sxs-lookup"><span data-stu-id="235e4-128">1.2</span></span>  <br/> |<span data-ttu-id="235e4-129">La aplicación de correo no se ha podido actualizarse automáticamente.</span><span class="sxs-lookup"><span data-stu-id="235e4-129">The mail app couldn't be updated automatically.</span></span> <span data-ttu-id="235e4-130">La licencia actual ha expirado o no es válida.</span><span class="sxs-lookup"><span data-stu-id="235e4-130">The current license has expired or is invalid.</span></span> <span data-ttu-id="235e4-131">Por favor, actualice la aplicación de correo desde la tienda de Office.</span><span class="sxs-lookup"><span data-stu-id="235e4-131">Please update the mail app from the Office Store.</span></span>  <br/> |
|<span data-ttu-id="235e4-132">2.0</span><span class="sxs-lookup"><span data-stu-id="235e4-132">2.0</span></span>  <br/> |<span data-ttu-id="235e4-133">No se pudo actualizar automáticamente la licencia de la aplicación de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-133">The mail app license could not be automatically updated.</span></span> <span data-ttu-id="235e4-134">Se necesita la licencia para la aplicación de correo que se va a recuperar de la tienda Office.</span><span class="sxs-lookup"><span data-stu-id="235e4-134">The license for the mail app needs to be recovered from the Office Store.</span></span>  <br/> |
|<span data-ttu-id="235e4-135">2.1</span><span class="sxs-lookup"><span data-stu-id="235e4-135">2.1</span></span>  <br/> |<span data-ttu-id="235e4-136">No se pudo actualizar automáticamente la licencia de la aplicación de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-136">The mail app license could not be automatically updated.</span></span> <span data-ttu-id="235e4-137">La licencia actual ha caducado.</span><span class="sxs-lookup"><span data-stu-id="235e4-137">The current license has expired.</span></span> <span data-ttu-id="235e4-138">Una nueva licencia para esta aplicación debe instalarse desde la tienda de Office.</span><span class="sxs-lookup"><span data-stu-id="235e4-138">A new license for this app needs to be installed from the Office Store.</span></span>  <br/> |
|<span data-ttu-id="235e4-139">3.0</span><span class="sxs-lookup"><span data-stu-id="235e4-139">3.0</span></span>  <br/> |<span data-ttu-id="235e4-140">Ha cambiado el estado del almacén de Office para la aplicación de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-140">The Office Store status for the mail app has changed.</span></span> <span data-ttu-id="235e4-141">Esto puede indicar que hay un problema con la aplicación de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-141">This may indicate that there is a problem with the mail app.</span></span> <span data-ttu-id="235e4-142">Vaya a la página de la aplicación de correo en la tienda de Office para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="235e4-142">Go to the mail app page in the Office Store for more information.</span></span>  <br/> |
|<span data-ttu-id="235e4-143">3.1</span><span class="sxs-lookup"><span data-stu-id="235e4-143">3.1</span></span>  <br/> |<span data-ttu-id="235e4-144">La aplicación de correo se ha quitado de la tienda de Office.</span><span class="sxs-lookup"><span data-stu-id="235e4-144">The mail app has been removed from the Office Store.</span></span>  <br/> |
|<span data-ttu-id="235e4-145">3.2</span><span class="sxs-lookup"><span data-stu-id="235e4-145">3.2</span></span>  <br/> |<span data-ttu-id="235e4-146">Se ha detectado un problema con la aplicación de correo y temporalmente haya sido retirado de la tienda Office.</span><span class="sxs-lookup"><span data-stu-id="235e4-146">A problem has been discovered with the mail app and it has temporarily been withdrawn from the Office Store.</span></span>  <br/> |
|<span data-ttu-id="235e4-147">3.3</span><span class="sxs-lookup"><span data-stu-id="235e4-147">3.3</span></span>  <br/> |<span data-ttu-id="235e4-148">La aplicación de correo se quitarán de la tienda Office dentro de 30 días.</span><span class="sxs-lookup"><span data-stu-id="235e4-148">The mail app will be removed from the Office Store within 30 days.</span></span>  <br/> |
|<span data-ttu-id="235e4-149">4.0</span><span class="sxs-lookup"><span data-stu-id="235e4-149">4.0</span></span>  <br/> |<span data-ttu-id="235e4-150">La aplicación de correo está deshabilitada automáticamente por el cliente de correo.</span><span class="sxs-lookup"><span data-stu-id="235e4-150">The mail app has been automatically disabled by your mail client.</span></span>  <br/> |
|<span data-ttu-id="235e4-151">4.1</span><span class="sxs-lookup"><span data-stu-id="235e4-151">4.1</span></span>  <br/> |<span data-ttu-id="235e4-152">La aplicación de correo está deshabilitada por Outlook por motivos de rendimiento.</span><span class="sxs-lookup"><span data-stu-id="235e4-152">The mail app has been disabled by Outlook for performance reasons.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="235e4-153">Comentarios</span><span class="sxs-lookup"><span data-stu-id="235e4-153">Remarks</span></span>

<span data-ttu-id="235e4-154">Este elemento se incorporó en Exchange Server 2013 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="235e4-154">This element was introduced in Exchange Server 2013 Service Pack 1 (SP1).</span></span>
  
<span data-ttu-id="235e4-155">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="235e4-155">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="235e4-156">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="235e4-156">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="235e4-157">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="235e4-157">Namespace</span></span>  <br/> | http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="235e4-158">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="235e4-158">Schema Name</span></span>  <br/> |<span data-ttu-id="235e4-159">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="235e4-159">Types schema</span></span>  <br/> |
|<span data-ttu-id="235e4-160">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="235e4-160">Validation File</span></span>  <br/> |<span data-ttu-id="235e4-161">No disponible</span><span class="sxs-lookup"><span data-stu-id="235e4-161">Not applicable</span></span>  <br/> |
|<span data-ttu-id="235e4-162">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="235e4-162">Can be Empty</span></span>  <br/> |<span data-ttu-id="235e4-163">False</span><span class="sxs-lookup"><span data-stu-id="235e4-163">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="235e4-164">Vea también</span><span class="sxs-lookup"><span data-stu-id="235e4-164">See also</span></span>

- [<span data-ttu-id="235e4-165">Metadatos</span><span class="sxs-lookup"><span data-stu-id="235e4-165">Metadata</span></span>](metadata-ex15websvcsotherref.md)
- [<span data-ttu-id="235e4-166">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="235e4-166">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
