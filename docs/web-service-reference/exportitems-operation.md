---
title: Operación ExportItems
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ExportItems
api_type:
- schema
ms.assetid: e2846abb-0b16-4732-bbd8-038a674672f6
description: La operación ExportItems exporta elementos fuera de un buzón de correo.
ms.openlocfilehash: 6f0760705c05de2a615544fe52ac50b398be6040
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764499"
---
# <a name="exportitems-operation"></a><span data-ttu-id="d5af3-103">Operación ExportItems</span><span class="sxs-lookup"><span data-stu-id="d5af3-103">ExportItems operation</span></span>

<span data-ttu-id="d5af3-104">La operación **ExportItems** exporta elementos fuera de un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="d5af3-104">The **ExportItems** operation exports items out of a mailbox.</span></span> 
  
## <a name="exportitems-request-example"></a><span data-ttu-id="d5af3-105">Ejemplo de solicitud de ExportItems</span><span class="sxs-lookup"><span data-stu-id="d5af3-105">ExportItems request example</span></span>

### <a name="description"></a><span data-ttu-id="d5af3-106">Descripción</span><span class="sxs-lookup"><span data-stu-id="d5af3-106">Description</span></span>

<span data-ttu-id="d5af3-107">El siguiente ejemplo de una solicitud de **ExportItems** muestra cómo formar una solicitud para obtener tres elementos exportados desde un buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="d5af3-107">The following example of an **ExportItems** request shows how to form a request to get three items exported from a mailbox.</span></span> 
  
### <a name="code"></a><span data-ttu-id="d5af3-108">Código</span><span class="sxs-lookup"><span data-stu-id="d5af3-108">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8" ?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
      xmlns:xsd="http://www.w3.org/2001/XMLSchema"
      xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
      xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
      xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2010_SP1" />
  </soap:Header>
  <soap:Body>
    <m:ExportItems>
      <m:ItemIds>
        <t:ItemId Id="AAMkAGYzZjZmRiUsidkC+NAAAAY89GAAA="/>
        <t:ItemId Id="AAMkAGYzZjZmRiUsidkC+NAAAAY89FAAA="/>
        <t:ItemId Id="AAMkAGYzZjZmRiUsidkC+NAAAAY87NAAA="/>
      </m:ItemIds>
    </m:ExportItems>
  </soap:Body>
</soap:Envelope>
```

### <a name="comment"></a><span data-ttu-id="d5af3-109">Comment</span><span class="sxs-lookup"><span data-stu-id="d5af3-109">Comment</span></span>

<span data-ttu-id="d5af3-110">Los identificadores de elemento en el ejemplo se han abreviado para conservar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="d5af3-110">The item identifiers in the example have been shortened to preserve readability.</span></span>
  
### <a name="request-elements"></a><span data-ttu-id="d5af3-111">Elementos de solicitud</span><span class="sxs-lookup"><span data-stu-id="d5af3-111">Request elements</span></span>

<span data-ttu-id="d5af3-112">En la solicitud se usan los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="d5af3-112">The following elements are used in the request:</span></span>
  
- [<span data-ttu-id="d5af3-113">RequestServerVersion</span><span class="sxs-lookup"><span data-stu-id="d5af3-113">RequestServerVersion</span></span>](requestserverversion.md)
    
- [<span data-ttu-id="d5af3-114">ExportItems</span><span class="sxs-lookup"><span data-stu-id="d5af3-114">ExportItems</span></span>](exportitems.md)
    
- [<span data-ttu-id="d5af3-115">ItemId (NonEmptyArrayOfItemIdsType)</span><span class="sxs-lookup"><span data-stu-id="d5af3-115">ItemIds (NonEmptyArrayOfItemIdsType)</span></span>](itemids-nonemptyarrayofitemidstype.md)
    
- [<span data-ttu-id="d5af3-116">ItemId</span><span class="sxs-lookup"><span data-stu-id="d5af3-116">ItemId</span></span>](itemid.md)
    
## <a name="successful-exportitems-response-example"></a><span data-ttu-id="d5af3-117">Ejemplo de respuesta correcta de ExportItems</span><span class="sxs-lookup"><span data-stu-id="d5af3-117">Successful ExportItems response example</span></span>

### <a name="description"></a><span data-ttu-id="d5af3-118">Descripción</span><span class="sxs-lookup"><span data-stu-id="d5af3-118">Description</span></span>

<span data-ttu-id="d5af3-119">En el ejemplo siguiente se muestra una respuesta a una solicitud **ExportItems** correcta.</span><span class="sxs-lookup"><span data-stu-id="d5af3-119">The following example shows a successful response to an **ExportItems** request.</span></span> 
  
### <a name="code"></a><span data-ttu-id="d5af3-120">Código</span><span class="sxs-lookup"><span data-stu-id="d5af3-120">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <t:ServerVersionInfo MajorVersion="14"
    MinorVersion="1"
    MajorBuildNumber="139"
    MinorBuildNumber="0"
    Version="Exchange2010_SP1"
    xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
    xmlns="http://schemas.microsoft.com/exchange/services/2006/types"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xmlns:xsd="http://www.w3.org/2001/XMLSchema"/>
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:ExportItemsResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
    xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:ExportItemsResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:ItemId Id="AAMkAGYzZjZmRiUsidkC+NAAAAY89GAAA=" ChangeKey="FwAAAA=="/>
          <m:Data>
            AQAAAAgAAAAAAAAALgBlAHgAdABlAHMAdAAuAG0AaQBjAHIAbwBzAG8AZgB0AC4A
            YwBvAG0AAABTAE0AVABQAAAAVQBzAGUAcgAyAEAAYQB1AGoAaQBuAGcALQBkAG8AbQAuAGUA
            eAB0AGUAcwB0AC4AbQBpAGMAcgBvAHMAbwBmAHQALgBjAG8AbQAAALCE/jlMAAAAVQBzAGUA
            cgAyAEAAYQB1AGoAaQBuAGcALQBkAG8AbQAuAGUAeAB0AGUAcwB0AC4AbQBpAGMAcgBvAHMA
            bwBmAHQALgBjAG8AbQAAAAMAADkAAAAAAwD+DwYAAAADAARAAwACQAMADkA=
          </m:Data>
        </m:ExportItemsResponseMessage>
        <m:ExportItemsResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:ItemId Id="AAMkAGYzZjZmRiUsidkC+NAAAAY89FAAA=" ChangeKey="FwAAAA=="/>
          <m:Data>
            AQAAAAgAAAAAAAAAAQAAAAMAAAAYAAAAAQAAAAcDAgAAAAAAwAAAAAAAAEYAJACA
            QAAyAAAh9SpR08oBAwAEQAMAFkANABMOAwAAQAMAIQ4AAAAAsIQSN0oAAAAyAGEAYgAxADYA
            MQA2ADYALQBhAGUANQBkAC0ANAAyAGUAZgAtAGEANQA1ADkALQBjADgAOQAwADgANwBkADIA
            MwBkADgANAAAAAMACzf/////AwAgDmQEAAADAPcPAAAAAEAABzBPMXstUdPKAUAACDBPMXst
            UdPKAQMABTcFAAAAsIQONx4AAABtAGUAcwBzAGEAZwBlAC8AcgBmAGMAOAAyADIAAACwhAEw
            IgAAAE0AbwBzAHQAIABmAGEAcwBjAGkAbgBhAHQAaQBuAGcAAAACAfkPBAAAAAAAAAADAAFA
            FABKZ3QrAAAAZF2mAwAXAAEAAACwhBoAEgAAAEkAUABNAC4ATgBvAHQAZQAAAAMANgAAAAAA
            sIQ3ACIAAABNAG8AcwB0ACAAZgBhAHMAYwBpAG4AYQB0AGkAbgBnAAAAQAA5AACq+za80coB
            AgE7AGUAAABFWDovTz1GSVJTVCBPUkdBTklaQVRJT04vT1U9RVhDSEFOR0UgQURNSU5JU1RS
            QVRJVkUgR1JPVVAgKEZZRElCT0hGMjNTUERMVCkvQ049UkVDSVBJRU5UUy9DTj1VU0VST05F
            ALCEPQACAAAAAAACAUEAfgAAAAAAAADcp0DIwEIQGrS5CAArL+GCAQAAAAAAAAAvTz1GSVJT
            VCBPUkdBTklaQVRJT04vT1U9RVhDSEFOR0UgQURNSU5JU1RSQVRJVkUgR1JPVVAgKEZZRElC
            T0hGMjNTUERMVCkvQ049UkVDSVBJRU5UUy9DTj1VU0VST05FALCEQgAQAAAAVQB
          </m:Data>
        </m:ExportItemsResponseMessage>
        <m:ExportItemsResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:ItemId Id="AAMkAGYzZjZmRiUsidkC+NAAAAY87NAAA=" ChangeKey="CQAAAA=="/>
          <m:Data>
            AQAAAAgAAAAAAAAAAQAAAAMAAAAYAAAAAQAAAAcDAgAAAAAAwAAAAAAAAEYAJACA
            BAAAAAYAAAABDouAAAACAAAAEiAAAOSECEBbAAAAL089RklSU1QgT1JHQU5JWkFUSU9OL09V
            PUVYQ0hBTkdFIEFETUlOSVNUUkFUSVZFIEdST1VQIChGWURJQk9IRjIzU1BETFQpL0NOPVJF
            Q0lQSUVOVFMvQ049AAMAFwABAAAAsIQaABIAAABJAFAATQAuAE4AbwB0AGUAAAALACMAAAAL
            ACkAAAADADYAAAAAALCENwAyAAAASQBuAHQAZQByAGUAcwB0AGkAbgBnACAALQAgAGYAcgBv
            AG0AIABFAFcAUwBNAEEAAABAADkAAHZeFxfRygECATsAZQAAAEVYOi9PPUZJUlNUIE9SR0FO
            SVpBVElPTi9PVT1FWENIQU5HRSBBRE1JTklTVFJBVElWRSBHUk9VUCAoRllESUJPSEYyM1NQ
            RExUKS9DTj1SRUNJUElFTlRTL0NOPVVTRVJPTkUAsIQ9AAIAAAAAAAIBPwB+AAAAAAAAANyn
            QMjAQhAatLkIACsv4YIBAAAAAAAAAC9PPUZJUlNUIE9SR0FOSVpBVElPTi9PVT1FWENIQU5H
          </m:Data>
        </m:ExportItemsResponseMessage>
      </m:ResponseMessages>
    </m:ExportItemsResponse>
  </s:Body>
</s:Envelope>
```

### <a name="comment"></a><span data-ttu-id="d5af3-121">Comment</span><span class="sxs-lookup"><span data-stu-id="d5af3-121">Comment</span></span>

<span data-ttu-id="d5af3-122">Los identificadores de elemento y las claves de cambio en el ejemplo se han abreviado para conservar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="d5af3-122">The item identifiers and change keys in the example have been shortened to preserve readability.</span></span>
  
### <a name="response-elements"></a><span data-ttu-id="d5af3-123">Elementos de respuesta</span><span class="sxs-lookup"><span data-stu-id="d5af3-123">Response elements</span></span>

<span data-ttu-id="d5af3-124">En la respuesta se usan los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="d5af3-124">The following elements are used in the response:</span></span>
  
- [<span data-ttu-id="d5af3-125">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="d5af3-125">ServerVersionInfo</span></span>](serverversioninfo.md)
    
- [<span data-ttu-id="d5af3-126">ExportItemsResponse</span><span class="sxs-lookup"><span data-stu-id="d5af3-126">ExportItemsResponse</span></span>](exportitemsresponse.md)
    
- [<span data-ttu-id="d5af3-127">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="d5af3-127">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="d5af3-128">ExportItemsResponseMessage</span><span class="sxs-lookup"><span data-stu-id="d5af3-128">ExportItemsResponseMessage</span></span>](exportitemsresponsemessage.md)
    
- [<span data-ttu-id="d5af3-129">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="d5af3-129">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="d5af3-130">ItemId</span><span class="sxs-lookup"><span data-stu-id="d5af3-130">ItemId</span></span>](itemid.md)
    
- [<span data-ttu-id="d5af3-131">Datos (base64Binary)</span><span class="sxs-lookup"><span data-stu-id="d5af3-131">Data (base64Binary)</span></span>](data-base64binary.md)
    
## <a name="exportitems-error-response-example"></a><span data-ttu-id="d5af3-132">Ejemplo de respuesta de ExportItems Error</span><span class="sxs-lookup"><span data-stu-id="d5af3-132">ExportItems Error response example</span></span>

### <a name="description"></a><span data-ttu-id="d5af3-133">Descripción</span><span class="sxs-lookup"><span data-stu-id="d5af3-133">Description</span></span>

<span data-ttu-id="d5af3-134">En el ejemplo siguiente se muestra una respuesta a la solicitud de **ExportItems** que contiene dos errores y un elemento se exportó correctamente.</span><span class="sxs-lookup"><span data-stu-id="d5af3-134">The following example shows a response to the **ExportItems** request that contains two errors and one successfully exported item.</span></span> <span data-ttu-id="d5af3-135">El primer elemento en el ejemplo se exportó correctamente.</span><span class="sxs-lookup"><span data-stu-id="d5af3-135">The first item in the example is successfully exported.</span></span> <span data-ttu-id="d5af3-136">El segundo elemento contiene una clave de cambio incorrecto.</span><span class="sxs-lookup"><span data-stu-id="d5af3-136">The second item contains an incorrect change key.</span></span> <span data-ttu-id="d5af3-137">El tercer elemento representa un intento para exportar un elemento desde el buzón de correo incorrecto.</span><span class="sxs-lookup"><span data-stu-id="d5af3-137">The third item represents an attempt to export an item from the wrong mailbox.</span></span> 
  
### <a name="code"></a><span data-ttu-id="d5af3-138">Código</span><span class="sxs-lookup"><span data-stu-id="d5af3-138">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="14" 
                         MinorVersion="1" 
                         MajorBuildNumber="164" 
                         MinorBuildNumber="0" 
                         Version="Exchange2010_SP1" 
                         xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
                         xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
                         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
                         xmlns:xsd="http://www.w3.org/2001/XMLSchema"/>
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
          xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:ExportItemsResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
                           xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:ExportItemsResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:ItemId Id="AAMkADhhOGU0oMf0GPIQeAAAAUC8iAABseAAAAUFZ7AAA=" ChangeKey="CQAAAA=="/>
          <m:Data>
            AQAAAAgAAAAAAAAALgBlAHgAdABlAHMAdAAuAG0AaQBjAHIAbwBzAG8AZgB0AC4A
            YwBvAG0AAABTAE0AVABQAAAAVQBzAGUAcgAyAEAAYQB1AGoAaQBuAGcALQBkAG8AbQAuAGUA
            eAB0AGUAcwB0AC4AbQBpAGMAcgBvAHMAbwBmAHQALgBjAG8AbQAAALCE/jlMAAAAVQBzAGUA
            cgAyAEAAYQB1AGoAaQBuAGcALQBkAG8AbQAuAGUAeAB0AGUAcwB0AC4AbQBpAGMAcgBvAHMA
            bwBmAHQALgBjAG8AbQAAAAMAADkAAAAAAwD+DwYAAAADAARAAwACQAMADkA=
          </m:Data>
        </m:ExportItemsResponseMessage>
        <m:ExportItemsResponseMessage ResponseClass="Error">
          <m:MessageText>The change key is invalid.</m:MessageText>
          <m:ResponseCode>ErrorInvalidChangeKey</m:ResponseCode>
          <m:DescriptiveLinkKey>0</m:DescriptiveLinkKey>
        </m:ExportItemsResponseMessage>
        <m:ExportItemsResponseMessage ResponseClass="Error">
          <m:MessageText>No mailbox with such guid.</m:MessageText>
          <m:ResponseCode>ErrorNonExistentMailbox</m:ResponseCode>
          <m:DescriptiveLinkKey>0</m:DescriptiveLinkKey>
          <m:MessageXml>
            <t:Value Name="MailboxGuid">f3f6f699-2254-40ce-9994-388d9d98419e</t:Value>
          </m:MessageXml>
        </m:ExportItemsResponseMessage>
      </m:ResponseMessages>
    </m:ExportItemsResponse>
  </s:Body>
</s:Envelope>

```

### <a name="comments"></a><span data-ttu-id="d5af3-139">Comentarios</span><span class="sxs-lookup"><span data-stu-id="d5af3-139">Comments</span></span>

<span data-ttu-id="d5af3-140">Los identificadores de elemento, cambie las claves y datos en el ejemplo se han abreviado para conservar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="d5af3-140">The item identifiers, change keys, and data in the example have been shortened to preserve readability.</span></span>
  
### <a name="error-response-elements"></a><span data-ttu-id="d5af3-141">Elementos de respuesta de error</span><span class="sxs-lookup"><span data-stu-id="d5af3-141">Error response elements</span></span>

<span data-ttu-id="d5af3-142">En la respuesta de error, se usan los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="d5af3-142">The following elements are used in the error response:</span></span>
  
- [<span data-ttu-id="d5af3-143">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="d5af3-143">ServerVersionInfo</span></span>](serverversioninfo.md)
    
- [<span data-ttu-id="d5af3-144">ExportItemsResponse</span><span class="sxs-lookup"><span data-stu-id="d5af3-144">ExportItemsResponse</span></span>](exportitemsresponse.md)
    
- [<span data-ttu-id="d5af3-145">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="d5af3-145">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="d5af3-146">ExportItemsResponseMessage</span><span class="sxs-lookup"><span data-stu-id="d5af3-146">ExportItemsResponseMessage</span></span>](exportitemsresponsemessage.md)
    
- [<span data-ttu-id="d5af3-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="d5af3-147">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="d5af3-148">ItemId</span><span class="sxs-lookup"><span data-stu-id="d5af3-148">ItemId</span></span>](itemid.md)
    
- [<span data-ttu-id="d5af3-149">Datos (base64Binary)</span><span class="sxs-lookup"><span data-stu-id="d5af3-149">Data (base64Binary)</span></span>](data-base64binary.md)
    
- [<span data-ttu-id="d5af3-150">MessageText</span><span class="sxs-lookup"><span data-stu-id="d5af3-150">MessageText</span></span>](messagetext.md)
    
- [<span data-ttu-id="d5af3-151">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="d5af3-151">DescriptiveLinkKey</span></span>](descriptivelinkkey.md)
    
- [<span data-ttu-id="d5af3-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="d5af3-152">MessageXml</span></span>](messagexml.md)
    
- <span data-ttu-id="d5af3-153">**Valor**</span><span class="sxs-lookup"><span data-stu-id="d5af3-153">**Value**</span></span>
    
> [!NOTE]
> <span data-ttu-id="d5af3-154">El elemento de **valor** no existe en el esquema.</span><span class="sxs-lookup"><span data-stu-id="d5af3-154">The **Value** element does not exist in the schema.</span></span> <span data-ttu-id="d5af3-155">Este elemento es válido porque el elemento de [MessageXml](messagexml.md) , en el que se produce el elemento de instancia de **valor** , puede contener cualquier XML correcto.</span><span class="sxs-lookup"><span data-stu-id="d5af3-155">This element is valid because the [MessageXml](messagexml.md) element, in which the **Value** instance element occurs, can contain any well-formed XML.</span></span> 
  
## <a name="see-also"></a><span data-ttu-id="d5af3-156">Ver también</span><span class="sxs-lookup"><span data-stu-id="d5af3-156">See also</span></span>



[<span data-ttu-id="d5af3-157">Operación UploadItems</span><span class="sxs-lookup"><span data-stu-id="d5af3-157">UploadItems operation</span></span>](uploaditems-operation.md)


[<span data-ttu-id="d5af3-158">Operaciones de EWS en Exchange</span><span class="sxs-lookup"><span data-stu-id="d5af3-158">EWS operations in Exchange</span></span>](ews-operations-in-exchange.md)
  
- [<span data-ttu-id="d5af3-159">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="d5af3-159">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
