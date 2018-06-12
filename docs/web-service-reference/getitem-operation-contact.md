---
title: Operación GetItem (contacto)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetItem
api_type:
- schema
ms.assetid: 6b96dace-1260-4b83-869a-7c31c5583daa
description: La operación GetItem se usa para obtener elementos de contacto desde el almacén de Exchange.
ms.openlocfilehash: 8d7436421f0c54a49345e8ef6b37cb442bca4277
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19764890"
---
# <a name="getitem-operation-contact"></a><span data-ttu-id="4b091-103">Operación GetItem (contacto)</span><span class="sxs-lookup"><span data-stu-id="4b091-103">GetItem operation (contact)</span></span>

<span data-ttu-id="4b091-104">La operación GetItem se usa para obtener elementos de contacto desde el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="4b091-104">The GetItem operation is used to get contact items from the Exchange store.</span></span>
  
## <a name="getitem-contact-request-example"></a><span data-ttu-id="4b091-105">Ejemplo de solicitud GetItem (contacto)</span><span class="sxs-lookup"><span data-stu-id="4b091-105">GetItem (Contact) request example</span></span>

### <a name="description"></a><span data-ttu-id="4b091-106">Descripción</span><span class="sxs-lookup"><span data-stu-id="4b091-106">Description</span></span>

<span data-ttu-id="4b091-107">En el ejemplo siguiente se muestra cómo obtener un elemento desde el almacén de Exchange.</span><span class="sxs-lookup"><span data-stu-id="4b091-107">The following example shows how to get an item from the Exchange store.</span></span>
  
### <a name="code"></a><span data-ttu-id="4b091-108">Código</span><span class="sxs-lookup"><span data-stu-id="4b091-108">Code</span></span>

```XML
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Body>
    <GetItem xmlns='http://schemas.microsoft.com/exchange/services/2006/messages'>
      <ItemShape>
        <t:BaseShape>AllProperties</t:BaseShape>
      </ItemShape>
      <ItemIds>
        <t:ItemId Id="AAAtAE=" ChangeKey="EQAAABY" />
      </ItemIds>
    </GetItem>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="4b091-109">Comentarios</span><span class="sxs-lookup"><span data-stu-id="4b091-109">Comments</span></span>

<span data-ttu-id="4b091-110">La solicitud para obtener un elemento desde el almacén de Exchange adopta el mismo formato para todos los tipos de elemento.</span><span class="sxs-lookup"><span data-stu-id="4b091-110">The request to get an item from the Exchange store takes the same form for all item types.</span></span> <span data-ttu-id="4b091-111">Las respuestas a las solicitudes de elementos diferentes son diferentes porque los elementos diferentes devuelven información diferente en función de las formas de respuesta.</span><span class="sxs-lookup"><span data-stu-id="4b091-111">The responses to requests for different items will be different because different items return different information based on the response shapes.</span></span>
  
> [!NOTE]
> <span data-ttu-id="4b091-112">El identificador del elemento se ha acortado para conservar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="4b091-112">The item identifier has been shortened to preserve readability.</span></span> 
  
### <a name="request-elements"></a><span data-ttu-id="4b091-113">Elementos de solicitud</span><span class="sxs-lookup"><span data-stu-id="4b091-113">Request elements</span></span>

<span data-ttu-id="4b091-114">En la solicitud se usan los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="4b091-114">The following elements are used in the request:</span></span>
  
- [<span data-ttu-id="4b091-115">GetItem</span><span class="sxs-lookup"><span data-stu-id="4b091-115">GetItem</span></span>](getitem.md)
    
- [<span data-ttu-id="4b091-116">ItemShape</span><span class="sxs-lookup"><span data-stu-id="4b091-116">ItemShape</span></span>](itemshape.md)
    
- [<span data-ttu-id="4b091-117">BaseShape</span><span class="sxs-lookup"><span data-stu-id="4b091-117">BaseShape</span></span>](baseshape.md)
    
- [<span data-ttu-id="4b091-118">ItemId</span><span class="sxs-lookup"><span data-stu-id="4b091-118">ItemIds</span></span>](itemids.md)
    
- [<span data-ttu-id="4b091-119">ItemId</span><span class="sxs-lookup"><span data-stu-id="4b091-119">ItemId</span></span>](itemid.md)
    
## <a name="successful-getitem-contact-response"></a><span data-ttu-id="4b091-120">Respuesta correcta GetItem (contacto)</span><span class="sxs-lookup"><span data-stu-id="4b091-120">Successful GetItem (Contact) Response</span></span>

### <a name="description"></a><span data-ttu-id="4b091-121">Descripción</span><span class="sxs-lookup"><span data-stu-id="4b091-121">Description</span></span>

<span data-ttu-id="4b091-122">En el ejemplo de código siguiente se muestra una respuesta GetItem correcta para la **AllProperties**[BaseShape](baseshape.md).</span><span class="sxs-lookup"><span data-stu-id="4b091-122">The following code example shows a successful GetItem response for the **AllProperties**[BaseShape](baseshape.md).</span></span>
  
### <a name="code"></a><span data-ttu-id="4b091-123">Código</span><span class="sxs-lookup"><span data-stu-id="4b091-123">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" MinorVersion="0" MajorBuildNumber="602" MinorBuildNumber="0" 
                         xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <GetItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
                     xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
                     xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseMessages>
        <m:GetItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:Contact>
              <t:ItemId Id="AAAtAEA=" ChangeKey="EQAAABYq" />
              <t:ParentFolderId Id="AQAtAEFk==" ChangeKey="AQAAAA==" />
              <t:ItemClass>IPM.Contact</t:ItemClass>
              <t:Sensitivity>Normal</t:Sensitivity>
              <t:Body BodyType="Text" />
              <t:DateTimeReceived>2006-08-18T17:31:18Z</t:DateTimeReceived>
              <t:Size>382</t:Size>
              <t:Importance>Normal</t:Importance>
              <t:IsSubmitted>false</t:IsSubmitted>
              <t:IsDraft>true</t:IsDraft>
              <t:IsFromMe>false</t:IsFromMe>
              <t:IsResend>false</t:IsResend>
              <t:IsUnmodified>false</t:IsUnmodified>
              <t:DateTimeSent>2006-08-18T17:31:18Z</t:DateTimeSent>
              <t:DateTimeCreated>2006-08-18T17:31:18Z</t:DateTimeCreated>
              <t:HasAttachments>false</t:HasAttachments>
              <t:Culture>en</t:Culture>
              <t:FileAs>SampleContact</t:FileAs>
              <t:FileAsMapping>None</t:FileAsMapping>
              <t:DisplayName>Tanja Plate</t:DisplayName>
              <t:GivenName>Tanja</t:GivenName>
              <t:Initials>T.P.</t:Initials>
              <t:CompleteName>
                <t:FirstName>Tanja</t:FirstName>
                <t:LastName>Plate</t:LastName>
                <t:Initials>T.P.</t:Initials>
                <t:FullName>Tanja Plate</t:FullName>
              </t:CompleteName>
              <t:CompanyName>Northwind Traders</t:CompanyName>
              <t:EmailAddresses>
                <t:Entry Key="EmailAddress1">tplate@example.com</t:Entry>
                <t:Entry Key="EmailAddress2">tplate@example.com</t:Entry>
              </t:EmailAddresses>
              <t:PhysicalAddresses>
                <t:Entry Key="Business">
                  <t:Street>12345 67th Ave</t:Street>
                  <t:City>Whittier</t:City>
                  <t:State>CA</t:State>
                  <t:Country>USA</t:Country>
                </t:Entry>
              </t:PhysicalAddresses>
              <t:PhoneNumbers>
                <t:Entry Key="BusinessPhone">5625550199</t:Entry>
              </t:PhoneNumbers>
              <t:JobTitle>Project Manager</t:JobTitle>
              <t:Surname>Plate</t:Surname>
            </t:Contact>
          </m:Items>
        </m:GetItemResponseMessage>
      </m:ResponseMessages>
    </GetItemResponse>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="4b091-124">Comentarios</span><span class="sxs-lookup"><span data-stu-id="4b091-124">Comments</span></span>

<span data-ttu-id="4b091-125">El identificador del elemento se ha acortado para conservar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="4b091-125">The item identifier has been shortened to preserve readability.</span></span>
  
### <a name="successful-response-elements"></a><span data-ttu-id="4b091-126">Elementos de respuesta correcta</span><span class="sxs-lookup"><span data-stu-id="4b091-126">Successful response elements</span></span>

<span data-ttu-id="4b091-127">Los siguientes elementos se usan en la respuesta de una solicitud de GetItem con una forma de respuesta de **AllProperties** para un elemento de contacto.</span><span class="sxs-lookup"><span data-stu-id="4b091-127">The following elements are used in the response for a GetItem request with a response shape of **AllProperties** for a contact item.</span></span> 
  
- [<span data-ttu-id="4b091-128">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="4b091-128">ServerVersionInfo</span></span>](serverversioninfo.md)
    
- [<span data-ttu-id="4b091-129">GetItemResponse</span><span class="sxs-lookup"><span data-stu-id="4b091-129">GetItemResponse</span></span>](getitemresponse.md)
    
- [<span data-ttu-id="4b091-130">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="4b091-130">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="4b091-131">GetItemResponseMessage</span><span class="sxs-lookup"><span data-stu-id="4b091-131">GetItemResponseMessage</span></span>](getitemresponsemessage.md)
    
- [<span data-ttu-id="4b091-132">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="4b091-132">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="4b091-133">Items</span><span class="sxs-lookup"><span data-stu-id="4b091-133">Items</span></span>](items.md)
    
- [<span data-ttu-id="4b091-134">Contact</span><span class="sxs-lookup"><span data-stu-id="4b091-134">Contact</span></span>](contact.md)
    
- [<span data-ttu-id="4b091-135">ItemId</span><span class="sxs-lookup"><span data-stu-id="4b091-135">ItemId</span></span>](itemid.md)
    
- [<span data-ttu-id="4b091-136">Id</span><span class="sxs-lookup"><span data-stu-id="4b091-136">ParentFolderId</span></span>](parentfolderid.md)
    
- [<span data-ttu-id="4b091-137">ItemClass</span><span class="sxs-lookup"><span data-stu-id="4b091-137">ItemClass</span></span>](itemclass.md)
    
- [<span data-ttu-id="4b091-138">Sensibilidad</span><span class="sxs-lookup"><span data-stu-id="4b091-138">Sensitivity</span></span>](sensitivity.md)
    
- [<span data-ttu-id="4b091-139">Body</span><span class="sxs-lookup"><span data-stu-id="4b091-139">Body</span></span>](body.md)
    
- [<span data-ttu-id="4b091-140">DateTimeReceived</span><span class="sxs-lookup"><span data-stu-id="4b091-140">DateTimeReceived</span></span>](datetimereceived.md)
    
- [<span data-ttu-id="4b091-141">Size</span><span class="sxs-lookup"><span data-stu-id="4b091-141">Size</span></span>](size.md)
    
- [<span data-ttu-id="4b091-142">Importancia</span><span class="sxs-lookup"><span data-stu-id="4b091-142">Importance</span></span>](importance.md)
    
- [<span data-ttu-id="4b091-143">IsSubmitted</span><span class="sxs-lookup"><span data-stu-id="4b091-143">IsSubmitted</span></span>](issubmitted.md)
    
- [<span data-ttu-id="4b091-144">IsDraft</span><span class="sxs-lookup"><span data-stu-id="4b091-144">IsDraft</span></span>](isdraft.md)
    
- [<span data-ttu-id="4b091-145">IsFromMe</span><span class="sxs-lookup"><span data-stu-id="4b091-145">IsFromMe</span></span>](isfromme.md)
    
- [<span data-ttu-id="4b091-146">IsResend</span><span class="sxs-lookup"><span data-stu-id="4b091-146">IsResend</span></span>](isresend.md)
    
- [<span data-ttu-id="4b091-147">IsUnmodified</span><span class="sxs-lookup"><span data-stu-id="4b091-147">IsUnmodified</span></span>](isunmodified.md)
    
- [<span data-ttu-id="4b091-148">DateTimeSent</span><span class="sxs-lookup"><span data-stu-id="4b091-148">DateTimeSent</span></span>](datetimesent.md)
    
- [<span data-ttu-id="4b091-149">DateTimeCreated</span><span class="sxs-lookup"><span data-stu-id="4b091-149">DateTimeCreated</span></span>](datetimecreated.md)
    
- [<span data-ttu-id="4b091-150">HasAttachments</span><span class="sxs-lookup"><span data-stu-id="4b091-150">HasAttachments</span></span>](hasattachments.md)
    
- [<span data-ttu-id="4b091-151">Referencia cultural</span><span class="sxs-lookup"><span data-stu-id="4b091-151">Culture</span></span>](culture.md)
    
- [<span data-ttu-id="4b091-152">Archivar como</span><span class="sxs-lookup"><span data-stu-id="4b091-152">FileAs</span></span>](fileas.md)
    
- [<span data-ttu-id="4b091-153">FileAsMapping</span><span class="sxs-lookup"><span data-stu-id="4b091-153">FileAsMapping</span></span>](fileasmapping.md)
    
- [<span data-ttu-id="4b091-154">DisplayName (cadena)</span><span class="sxs-lookup"><span data-stu-id="4b091-154">DisplayName (string)</span></span>](displayname-string.md)
    
- [<span data-ttu-id="4b091-155">GivenName</span><span class="sxs-lookup"><span data-stu-id="4b091-155">GivenName</span></span>](givenname.md)
    
- [<span data-ttu-id="4b091-156">Iniciales</span><span class="sxs-lookup"><span data-stu-id="4b091-156">Initials</span></span>](initials.md)
    
- [<span data-ttu-id="4b091-157">CompleteName</span><span class="sxs-lookup"><span data-stu-id="4b091-157">CompleteName</span></span>](completename.md)
    
- [<span data-ttu-id="4b091-158">FirstName</span><span class="sxs-lookup"><span data-stu-id="4b091-158">FirstName</span></span>](firstname.md)
    
- [<span data-ttu-id="4b091-159">LastName (apellidos)</span><span class="sxs-lookup"><span data-stu-id="4b091-159">LastName</span></span>](lastname.md)
    
- [<span data-ttu-id="4b091-160">FullName</span><span class="sxs-lookup"><span data-stu-id="4b091-160">FullName</span></span>](fullname.md)
    
- [<span data-ttu-id="4b091-161">CompanyName</span><span class="sxs-lookup"><span data-stu-id="4b091-161">CompanyName</span></span>](companyname.md)
    
- [<span data-ttu-id="4b091-162">EmailAddresses</span><span class="sxs-lookup"><span data-stu-id="4b091-162">EmailAddresses</span></span>](emailaddresses.md)
    
- [<span data-ttu-id="4b091-163">Entrada (EmailAddress)</span><span class="sxs-lookup"><span data-stu-id="4b091-163">Entry (EmailAddress)</span></span>](entry-emailaddress.md)
    
- [<span data-ttu-id="4b091-164">PhysicalAddresses</span><span class="sxs-lookup"><span data-stu-id="4b091-164">PhysicalAddresses</span></span>](physicaladdresses.md)
    
- [<span data-ttu-id="4b091-165">Entrada (PhysicalAddress)</span><span class="sxs-lookup"><span data-stu-id="4b091-165">Entry (PhysicalAddress)</span></span>](entry-physicaladdress.md)
    
- [<span data-ttu-id="4b091-166">Calle</span><span class="sxs-lookup"><span data-stu-id="4b091-166">Street</span></span>](street.md)
    
- [<span data-ttu-id="4b091-167">Ciudad</span><span class="sxs-lookup"><span data-stu-id="4b091-167">City</span></span>](city.md)
    
- [<span data-ttu-id="4b091-168">State</span><span class="sxs-lookup"><span data-stu-id="4b091-168">State</span></span>](state-ex15websvcsotherref.md)
    
- [<span data-ttu-id="4b091-169">CountryOrRegion</span><span class="sxs-lookup"><span data-stu-id="4b091-169">CountryOrRegion</span></span>](countryorregion.md)
    
- [<span data-ttu-id="4b091-170">PhoneNumbers</span><span class="sxs-lookup"><span data-stu-id="4b091-170">PhoneNumbers</span></span>](phonenumbers.md)
    
- [<span data-ttu-id="4b091-171">Entrada (PhoneNumber)</span><span class="sxs-lookup"><span data-stu-id="4b091-171">Entry (PhoneNumber)</span></span>](entry-phonenumber.md)
    
- [<span data-ttu-id="4b091-172">JobTitle</span><span class="sxs-lookup"><span data-stu-id="4b091-172">JobTitle</span></span>](jobtitle.md)
    
- [<span data-ttu-id="4b091-173">Apellido</span><span class="sxs-lookup"><span data-stu-id="4b091-173">Surname</span></span>](surname.md)
    
## <a name="invalid-getitem-contact-request-example"></a><span data-ttu-id="4b091-174">Ejemplo de solicitud GetItem (contactos) no válido</span><span class="sxs-lookup"><span data-stu-id="4b091-174">Invalid GetItem (Contact) request example</span></span>

### <a name="description"></a><span data-ttu-id="4b091-175">Descripción</span><span class="sxs-lookup"><span data-stu-id="4b091-175">Description</span></span>

<span data-ttu-id="4b091-176">En el ejemplo de código siguiente se muestra una solicitud no válida.</span><span class="sxs-lookup"><span data-stu-id="4b091-176">The following code example shows an invalid request.</span></span>
  
### <a name="code"></a><span data-ttu-id="4b091-177">Código</span><span class="sxs-lookup"><span data-stu-id="4b091-177">Code</span></span>

```XML
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Body>
    <GetItem xmlns='http://schemas.microsoft.com/exchange/services/2006/messages'>
      <ItemShape>
        <t:BaseShape>AllProperties</t:BaseShape>
        <t:IncludeMimeContent>true</t:IncludeMimeContent>
      </ItemShape>
      <ItemIds>
        <t:ItemId Id="AAAtAEF=" ChangeKey="EQAAABq" />
      </ItemIds>
    </GetItem>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="4b091-178">Comentarios</span><span class="sxs-lookup"><span data-stu-id="4b091-178">Comments</span></span>

<span data-ttu-id="4b091-179">Identificadores de elemento se han abreviado para conservar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="4b091-179">Item identifiers have been shortened to preserve readability.</span></span>
  
## <a name="getitem-contact-error-response"></a><span data-ttu-id="4b091-180">Respuesta de error GetItem (contacto)</span><span class="sxs-lookup"><span data-stu-id="4b091-180">GetItem (Contact) error response</span></span>

### <a name="description"></a><span data-ttu-id="4b091-181">Descripción</span><span class="sxs-lookup"><span data-stu-id="4b091-181">Description</span></span>

<span data-ttu-id="4b091-182">En el ejemplo de código siguiente se muestra una respuesta de error a una solicitud de GetItem (contactos).</span><span class="sxs-lookup"><span data-stu-id="4b091-182">The following code example shows an error response to a GetItem (Contact) request.</span></span>
  
### <a name="code"></a><span data-ttu-id="4b091-183">Código</span><span class="sxs-lookup"><span data-stu-id="4b091-183">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" MinorVersion="0" MajorBuildNumber="602" MinorBuildNumber="0" 
                         xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <GetItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
                     xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
                     xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseMessages>
        <m:GetItemResponseMessage ResponseClass="Error">
          <m:MessageText>Mime conversion is not supported for this item type.</m:MessageText>
          <m:ResponseCode>ErrorUnsupportedMimeConversion</m:ResponseCode>
          <m:DescriptiveLinkKey>0</m:DescriptiveLinkKey>
          <m:Items />
        </m:GetItemResponseMessage>
      </m:ResponseMessages>
    </GetItemResponse>
  </soap:Body>
</soap:Envelope>
```

### <a name="error-response-elements"></a><span data-ttu-id="4b091-184">Elementos de respuesta de error</span><span class="sxs-lookup"><span data-stu-id="4b091-184">Error response elements</span></span>

<span data-ttu-id="4b091-185">En la respuesta de error, se usan los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="4b091-185">The following elements are used in the error response:</span></span>
  
- [<span data-ttu-id="4b091-186">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="4b091-186">ServerVersionInfo</span></span>](serverversioninfo.md)
    
- [<span data-ttu-id="4b091-187">GetItemResponse</span><span class="sxs-lookup"><span data-stu-id="4b091-187">GetItemResponse</span></span>](getitemresponse.md)
    
- [<span data-ttu-id="4b091-188">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="4b091-188">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="4b091-189">GetItemResponseMessage</span><span class="sxs-lookup"><span data-stu-id="4b091-189">GetItemResponseMessage</span></span>](getitemresponsemessage.md)
    
- [<span data-ttu-id="4b091-190">MessageText</span><span class="sxs-lookup"><span data-stu-id="4b091-190">MessageText</span></span>](messagetext.md)
    
- [<span data-ttu-id="4b091-191">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="4b091-191">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="4b091-192">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="4b091-192">DescriptiveLinkKey</span></span>](descriptivelinkkey.md)
    
- [<span data-ttu-id="4b091-193">Items</span><span class="sxs-lookup"><span data-stu-id="4b091-193">Items</span></span>](items.md)
    
## <a name="see-also"></a><span data-ttu-id="4b091-194">Ver también</span><span class="sxs-lookup"><span data-stu-id="4b091-194">See also</span></span>



[<span data-ttu-id="4b091-195">Operación GetItem</span><span class="sxs-lookup"><span data-stu-id="4b091-195">GetItem operation</span></span>](getitem-operation.md)


- [<span data-ttu-id="4b091-196">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="4b091-196">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
