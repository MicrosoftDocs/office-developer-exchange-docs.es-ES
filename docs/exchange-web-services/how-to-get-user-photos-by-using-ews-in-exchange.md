---
title: Obtener fotografías de usuario mediante el uso de EWS en Exchange
manager: sethgros
ms.date: 03/9/2015
ms.audience: Developer
localization_priority: Normal
ms.assetid: f86d1099-1f57-47dc-abf2-4d5ae4e900a9
description: Obtenga información sobre cómo obtener fotografías de usuario que están asociadas con un buzón de correo o póngase en contacto con mediante el uso de la API administrada de EWS o EWS en Exchange.
ms.openlocfilehash: f0f5cddd41fc563fb9ed38e75b505830a3992411
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19763103"
---
# <a name="get-user-photos-by-using-ews-in-exchange"></a><span data-ttu-id="edd06-103">Obtener fotografías de usuario mediante el uso de EWS en Exchange</span><span class="sxs-lookup"><span data-stu-id="edd06-103">Get user photos by using EWS in Exchange</span></span>

<span data-ttu-id="edd06-104">Obtenga información sobre cómo obtener fotografías de usuario que están asociadas con un buzón de correo o póngase en contacto con mediante el uso de la API administrada de EWS o EWS en Exchange.</span><span class="sxs-lookup"><span data-stu-id="edd06-104">Learn how to get user photos that are associated with a mailbox or contact by using the EWS Managed API or EWS in Exchange.</span></span>
  
<span data-ttu-id="edd06-105">Es interesante poner una cara a un nombre.</span><span class="sxs-lookup"><span data-stu-id="edd06-105">It's nice to put a face to a name.</span></span> <span data-ttu-id="edd06-106">Si le gusta a los usuarios colocar los nombres a las caras, la aplicación puede solicitar una imagen, normalmente una foto, de Exchange que representa una cuenta de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="edd06-106">If your users like to put names to faces, your application can request an image, typically a photo, from Exchange that represents an email account.</span></span> <span data-ttu-id="edd06-107">Puede obtener una foto de usuario almacenada en un servidor de Exchange para un buzón de correo, o puede obtener una foto de contacto de los contactos que se almacenan en su buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="edd06-107">You can get a user photo stored on an Exchange server for a mailbox, or you can get a contact photo from contacts stored in your mailbox.</span></span>
  
<span data-ttu-id="edd06-108">Puede usar varias tecnologías distintas para obtener fotos de los buzones de correo o los servicios de dominio de Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="edd06-108">You can use several different technologies to get photos from mailboxes or Active Directory Domain Services (AD DS).</span></span> <span data-ttu-id="edd06-109">La mejor manera de obtener una foto depende del tipo de contacto que se desea obtener una foto de.</span><span class="sxs-lookup"><span data-stu-id="edd06-109">The best way to get a photo depends on the type of contact that you want to get a photo from.</span></span> 
  
<span data-ttu-id="edd06-110">**La tabla 1. Tecnologías a usar para obtener fotos de usuario según el tipo de contacto**</span><span class="sxs-lookup"><span data-stu-id="edd06-110">**Table 1. Technologies to use to get user photos based on contact type**</span></span>

|<span data-ttu-id="edd06-111">**Tipo de contacto**</span><span class="sxs-lookup"><span data-stu-id="edd06-111">**Contact type**</span></span>|<span data-ttu-id="edd06-112">**Para usar las tecnologías**</span><span class="sxs-lookup"><span data-stu-id="edd06-112">**Technologies to use**</span></span>|
|:-----|:-----|
|<span data-ttu-id="edd06-113">Foto de usuario de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="edd06-113">Mailbox user photo</span></span>  <br/> |[<span data-ttu-id="edd06-114">Obtener una foto de usuario de buzón de correo con REST</span><span class="sxs-lookup"><span data-stu-id="edd06-114">Get a mailbox user photo by using REST</span></span>](#bk_REST)<br/><br/> [<span data-ttu-id="edd06-115">Obtener una foto de usuario mediante el uso de EWS</span><span class="sxs-lookup"><span data-stu-id="edd06-115">Get a user photo by using EWS</span></span>](#bk_EWS) <br/> |
|<span data-ttu-id="edd06-116">Foto de contacto de usuario</span><span class="sxs-lookup"><span data-stu-id="edd06-116">Contact user photo</span></span>  <br/> |[<span data-ttu-id="edd06-117">Obtener una foto de usuario de contacto mediante el uso de API administrada de EWS</span><span class="sxs-lookup"><span data-stu-id="edd06-117">Get a contact user photo by using EWS Managed API</span></span>](#bk_EWSMA)<br/><br/> [<span data-ttu-id="edd06-118">Obtener una foto de usuario mediante el uso de EWS</span><span class="sxs-lookup"><span data-stu-id="edd06-118">Get a user photo by using EWS</span></span>](#bk_EWS) <br/> |

<span data-ttu-id="edd06-119"><a name="bk_REST"> </a></span><span class="sxs-lookup"><span data-stu-id="edd06-119"></span></span>

## <a name="get-a-mailbox-user-photo-by-using-rest"></a><span data-ttu-id="edd06-120">Obtener una foto de usuario de buzón de correo con REST</span><span class="sxs-lookup"><span data-stu-id="edd06-120">Get a mailbox user photo by using REST</span></span>

<span data-ttu-id="edd06-121">Puede solicitar fotografías de usuario desde un servidor de Exchange mediante el uso de una solicitud HTTPS **obtener** estándar.</span><span class="sxs-lookup"><span data-stu-id="edd06-121">You can request user photos from an Exchange server by using a standard HTTPS **GET** request.</span></span> <span data-ttu-id="edd06-122">En la solicitud, especifique la dirección de la cuenta de correo electrónico y un código de tamaño de la imagen, tal como se muestra en el siguiente ejemplo.</span><span class="sxs-lookup"><span data-stu-id="edd06-122">In the request, specify the email account address and a size code for the image, as shown in the following example.</span></span> 
  
```HTML
https://Exchange Server/ews/Exchange.asmx/s/GetUserPhoto?email=email address&amp;size=size code
```

<span data-ttu-id="edd06-123">Use la operación de [GetUserSettings](how-to-get-user-settings-from-exchange-by-using-autodiscover.md) del servicio de detección automática para recuperar la configuración de **ExternalEwsUrl** , que contiene la dirección URL del extremo de servicios Web de Exchange (EWS) y la ubicación del controlador **Exchange.asmx** HTTP que devuelve el fotos de usuario.</span><span class="sxs-lookup"><span data-stu-id="edd06-123">Use the Autodiscover service [GetUserSettings](how-to-get-user-settings-from-exchange-by-using-autodiscover.md) operation to retrieve the **ExternalEwsUrl** setting, which contains the URL of the Exchange Web Services (EWS) endpoint and the location of the **Exchange.asmx** HTTP handler that returns the user photos.</span></span> 
  
<span data-ttu-id="edd06-124">Cada código de tamaño indica el alto y el ancho de la imagen en píxeles.</span><span class="sxs-lookup"><span data-stu-id="edd06-124">Each size code indicates the height and width of the image in pixels.</span></span> <span data-ttu-id="edd06-125">Por ejemplo, el código de tamaño **HR48x48** devuelve una imagen que es 48 píxeles de alto por 48 píxeles de ancho.</span><span class="sxs-lookup"><span data-stu-id="edd06-125">For example, the size code **HR48x48** returns an image that is 48 pixels high by 48 pixels wide.</span></span> <span data-ttu-id="edd06-126">Los valores posibles para el parámetro de código de tamaño son los mismos que los valores posibles para el elemento [SizeRequested](http://msdn.microsoft.com/library/e86f98b6-83b5-4530-80eb-dc5df42e2c62%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="edd06-126">The possible values for the size code parameter are the same as the possible values for the [SizeRequested](http://msdn.microsoft.com/library/e86f98b6-83b5-4530-80eb-dc5df42e2c62%28Office.15%29.aspx) element.</span></span> <span data-ttu-id="edd06-127">Si la solicitud especifica un tamaño que no está disponible, se devolverá la foto disponible más grande.</span><span class="sxs-lookup"><span data-stu-id="edd06-127">If the request specifies a size that is not available, the largest available photo will be returned.</span></span> <span data-ttu-id="edd06-128">Si no hay foto se almacena en el servidor de Exchange, se devolverá la imagen en miniatura que se almacena en AD DS para la cuenta.</span><span class="sxs-lookup"><span data-stu-id="edd06-128">If no photo is stored on the Exchange server, the thumbnail image stored in AD DS for the account will be returned.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="edd06-129">El código de tamaño **HR48x48** siempre devuelve la imagen en miniatura de AD DS, si está disponible.</span><span class="sxs-lookup"><span data-stu-id="edd06-129">The **HR48x48** size code always returns the AD DS thumbnail image if it is available.</span></span> 
  
<span data-ttu-id="edd06-130">En el ejemplo siguiente se muestra cómo puede usar la solicitud GET para recuperar la foto de usuario para Sadie y guárdelo en su equipo local.</span><span class="sxs-lookup"><span data-stu-id="edd06-130">The following example shows how you can use the GET request to retrieve the user photo for Sadie and save it to your local computer.</span></span>
  
```cs
// Create the web request with the REST URL.
HttpWebRequest request = 
   WebRequest.Create("https://www.contoso.com/ews/exchange.asmx/s/GetUserPhoto?email=sadie@contoso.com&amp;size=HR240x240") 
   as HttpWebRequest;
// Submit the request.
using (HttpWebResponse resp = request.GetResponse() as HttpWebResponse)
{
   // Take the response and save it as an image.
   Bitmap image = new Bitmap(resp.GetResponseStream());
   image.Save("Sadie.jpg");
}

```

<span data-ttu-id="edd06-131">La solicitud devolverá una respuesta HTTP.</span><span class="sxs-lookup"><span data-stu-id="edd06-131">The request will return an HTTP response.</span></span> 
  
<span data-ttu-id="edd06-132">**Tabla 2. Códigos de respuesta para una solicitud de GetUserPhoto**</span><span class="sxs-lookup"><span data-stu-id="edd06-132">**Table 2. Response codes for a GetUserPhoto request**</span></span>

|<span data-ttu-id="edd06-133">**Código de respuesta**</span><span class="sxs-lookup"><span data-stu-id="edd06-133">**Response code**</span></span>|<span data-ttu-id="edd06-134">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="edd06-134">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="edd06-135">200</span><span class="sxs-lookup"><span data-stu-id="edd06-135">200</span></span>  <br/> |<span data-ttu-id="edd06-136">Una imagen está disponible para la cuenta de correo electrónico especificada y la imagen binaria se encuentra en la respuesta.</span><span class="sxs-lookup"><span data-stu-id="edd06-136">An image is available for the specified email account and the binary image is contained in the response.</span></span>  <br/> |
|<span data-ttu-id="edd06-137">304</span><span class="sxs-lookup"><span data-stu-id="edd06-137">304</span></span>  <br/> |<span data-ttu-id="edd06-138">La imagen no ha cambiado desde la última vez que se devolvió el **ETag** a la aplicación.</span><span class="sxs-lookup"><span data-stu-id="edd06-138">The image has not changed since the last time the **ETag** was returned to the application.</span></span>  <br/> |
|<span data-ttu-id="edd06-139">404</span><span class="sxs-lookup"><span data-stu-id="edd06-139">404</span></span>  <br/> |<span data-ttu-id="edd06-140">No hay ninguna imagen está disponible para la cuenta de correo electrónico especificada.</span><span class="sxs-lookup"><span data-stu-id="edd06-140">No image is available for the specified email account.</span></span>  <br/> |

<span data-ttu-id="edd06-141"><a name="bk_REST"> </a></span><span class="sxs-lookup"><span data-stu-id="edd06-141"></span></span>

## <a name="cache-user-photos"></a><span data-ttu-id="edd06-142">Fotos de usuario de la memoria caché</span><span class="sxs-lookup"><span data-stu-id="edd06-142">Cache user photos</span></span>

<span data-ttu-id="edd06-143">Exchange devuelve los datos con un tipo de contenido de imagen/jpeg, junto con una colección de valores de encabezado.</span><span class="sxs-lookup"><span data-stu-id="edd06-143">Exchange returns the data with a content type of image/jpeg, along with a collection of header values.</span></span> <span data-ttu-id="edd06-144">El encabezado **ETag** es similar a una clave de cambio.</span><span class="sxs-lookup"><span data-stu-id="edd06-144">The **ETag** header is similar to a change key.</span></span> <span data-ttu-id="edd06-145">El valor es una cadena que representa la última vez que se actualizó la foto.</span><span class="sxs-lookup"><span data-stu-id="edd06-145">The value is a string that represents the last time the photo was updated.</span></span> <span data-ttu-id="edd06-146">El **valor ETag** sigue siendo la misma para la foto de usuario hasta que se modifica la foto.</span><span class="sxs-lookup"><span data-stu-id="edd06-146">The **ETag** remains the same for the user photo until the photo is changed.</span></span> <span data-ttu-id="edd06-147">Puede enviar este valor de **ETag** para el servidor en la solicitud HTTPS **obtener** en un encabezado **If--Match** .</span><span class="sxs-lookup"><span data-stu-id="edd06-147">You can send this **ETag** value to the server in the HTTPS **GET** request in an **If-None-Match** header.</span></span> <span data-ttu-id="edd06-148">Si la foto no ha cambiado desde la última solicitud, el servidor responde con una respuesta HTTP 304 que se indica como tales.</span><span class="sxs-lookup"><span data-stu-id="edd06-148">If the photo hasn't changed since the last request, the server will respond with an HTTP 304 response that indicates as such.</span></span> <span data-ttu-id="edd06-149">Esto significa que se puede utilizar la foto de usuario que solicita y guardado previamente en lugar de procesar una nueva.</span><span class="sxs-lookup"><span data-stu-id="edd06-149">This means that you can use the user photo that you previously requested and saved rather than processing a new one.</span></span> 

<span data-ttu-id="edd06-150"><a name="bk_EWSMA"> </a></span><span class="sxs-lookup"><span data-stu-id="edd06-150"></span></span>

## <a name="get-a-contact-user-photo-by-using-ews-managed-api"></a><span data-ttu-id="edd06-151">Obtener una foto de usuario de contacto mediante el uso de API administrada de EWS</span><span class="sxs-lookup"><span data-stu-id="edd06-151">Get a contact user photo by using EWS Managed API</span></span>

<span data-ttu-id="edd06-152">La aplicación puede utilizar la API administrada de EWS para recuperar las fotos de contactos, si el contacto se almacena en una carpeta de contactos en el buzón del usuario.</span><span class="sxs-lookup"><span data-stu-id="edd06-152">Your application can use the EWS Managed API to retrieve photos for contacts, if the contact is stored in a contact folder in the user's mailbox.</span></span> <span data-ttu-id="edd06-153">Para ello, en primer lugar, busque la **ItemId** para el contacto que desee usar.</span><span class="sxs-lookup"><span data-stu-id="edd06-153">To do this, first, find the **ItemId** for the contact you want use.</span></span> <span data-ttu-id="edd06-154">A continuación, después de enlazar a ese contacto, cargarlo a la colección attachments.</span><span class="sxs-lookup"><span data-stu-id="edd06-154">Then, after you bind to that contact, load it to the attachments collection.</span></span> <span data-ttu-id="edd06-155">Si el contacto tiene una foto, la foto será uno de los datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="edd06-155">If the contact has a photo, the photo will be one of the attachments.</span></span> <span data-ttu-id="edd06-156">Recorrer en iteración la colección de datos adjuntos, comprobar el valor de la propiedad **IsContactPhoto** .</span><span class="sxs-lookup"><span data-stu-id="edd06-156">Loop through the attachments collection, checking the value of the **IsContactPhoto** property.</span></span> <span data-ttu-id="edd06-157">Cuando encuentre la foto del contacto, puede guardar en el equipo local y la aplicación puede tener acceso a él.</span><span class="sxs-lookup"><span data-stu-id="edd06-157">When you find the contact photo, you can save it to your local computer, and your application can access it.</span></span> 
  
<span data-ttu-id="edd06-158">En el ejemplo siguiente se muestra este proceso.</span><span class="sxs-lookup"><span data-stu-id="edd06-158">The following example shows this process.</span></span> <span data-ttu-id="edd06-159">En este ejemplo se da por supuesto que **servicio** es un objeto [ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) válido y que se ha autenticado el usuario a un servidor de Exchange.</span><span class="sxs-lookup"><span data-stu-id="edd06-159">This example assumes that **service** is a valid [ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) object and that the user has been authenticated to an Exchange server.</span></span> 
  
```cs
private static void GetContactPhoto(ExchangeService service, string ItemId)
{
   // Bind to an existing contact by using the ItemId passed into this function.
   Contact contact = Contact.Bind(service, ItemId);
   // Load the contact to get access to the collection of attachments.
   contact.Load(new PropertySet(ContactSchema.Attachments));
   // Loop through the attachments looking for a contact photo.
   foreach (Attachment attachment in contact.Attachments)
   {
      if ((attachment as FileAttachment).IsContactPhoto)
      {
         // Load the attachment to access the content.
         attachment.Load();
      }
   }
   FileAttachment photo = contact.GetContactPictureAttachment();
   // Create a file stream and save the contact photo to your computer.
   using (FileStream file = new FileStream(photo.Name, FileMode.Create, System.IO.FileAccess.Write))
   {
      photo.Load(file);
   }
}

```

<span data-ttu-id="edd06-160"><a name="bk_EWS"> </a></span><span class="sxs-lookup"><span data-stu-id="edd06-160"></span></span>

## <a name="get-a-user-photo-by-using-ews"></a><span data-ttu-id="edd06-161">Obtener una foto de usuario mediante el uso de EWS</span><span class="sxs-lookup"><span data-stu-id="edd06-161">Get a user photo by using EWS</span></span>

<span data-ttu-id="edd06-162">Si va a recibir una foto de usuario de AD DS, puede usar la operación de [GetUserPhoto](http://msdn.microsoft.com/library/f6e8143d-4235-428e-8f9c-ab6e9b1cfa6e%28Office.15%29.aspx) (si conoce la dirección de correo electrónico) o la operación [ResolveNames](http://msdn.microsoft.com/library/6b4eb4b3-9ad6-4804-a09f-7e20cfea4dbb%28Office.15%29.aspx) (si no conoce la dirección de correo electrónico).</span><span class="sxs-lookup"><span data-stu-id="edd06-162">If you're getting a user photo from AD DS, you can use the [GetUserPhoto](http://msdn.microsoft.com/library/f6e8143d-4235-428e-8f9c-ab6e9b1cfa6e%28Office.15%29.aspx) operation (if you know the email address) or the [ResolveNames](http://msdn.microsoft.com/library/6b4eb4b3-9ad6-4804-a09f-7e20cfea4dbb%28Office.15%29.aspx) operation (if you don't know the email address).</span></span> <span data-ttu-id="edd06-163">Si va a recibir una foto de usuario desde una carpeta de contactos en el buzón de correo, use la operación de [GetItem](http://msdn.microsoft.com/library/6b96dace-1260-4b83-869a-7c31c5583daa%28Office.15%29.aspx) seguida de la operación [GetAttachment](http://msdn.microsoft.com/library/24d10a15-b942-415e-9024-a6375708f326%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="edd06-163">If you're getting a user photo from a contacts folder in the mailbox, use the [GetItem](http://msdn.microsoft.com/library/6b96dace-1260-4b83-869a-7c31c5583daa%28Office.15%29.aspx) operation followed by the [GetAttachment](http://msdn.microsoft.com/library/24d10a15-b942-415e-9024-a6375708f326%28Office.15%29.aspx) operation.</span></span> <span data-ttu-id="edd06-164">En cualquier caso, la foto se devuelve como una cadena con codificación Base64 en la respuesta XML.</span><span class="sxs-lookup"><span data-stu-id="edd06-164">In either case, the photo is returned as a Base64-encoded string in the XML response.</span></span> 
  
### <a name="get-a-mailbox-user-photo-by-using-the-getuserphoto-operation"></a><span data-ttu-id="edd06-165">Obtener una foto de usuario de buzón de correo mediante el uso de la operación de GetUserPhoto</span><span class="sxs-lookup"><span data-stu-id="edd06-165">Get a mailbox user photo by using the GetUserPhoto operation</span></span>

<span data-ttu-id="edd06-166">Mediante la operación de **GetUserPhoto** es un proceso sencillo.</span><span class="sxs-lookup"><span data-stu-id="edd06-166">Using the **GetUserPhoto** operation is straightforward.</span></span> <span data-ttu-id="edd06-167">En la solicitud XML, especifique la dirección de correo electrónico del usuario y el [tamaño de la foto](http://msdn.microsoft.com/library/e86f98b6-83b5-4530-80eb-dc5df42e2c62%28Office.15%29.aspx) para devolver (en el elemento [SizeRequested](http://msdn.microsoft.com/library/e86f98b6-83b5-4530-80eb-dc5df42e2c62%28Office.15%29.aspx) ).</span><span class="sxs-lookup"><span data-stu-id="edd06-167">In the XML request, specify the email address of the user, and the [size of the photo](http://msdn.microsoft.com/library/e86f98b6-83b5-4530-80eb-dc5df42e2c62%28Office.15%29.aspx) to return (in the [SizeRequested](http://msdn.microsoft.com/library/e86f98b6-83b5-4530-80eb-dc5df42e2c62%28Office.15%29.aspx) element).</span></span> <span data-ttu-id="edd06-168">El siguiente ejemplo de solicitud XML muestra cómo obtener una foto para Sadie Daniels que es 360 píxeles de ancho por 360 píxeles de alto.</span><span class="sxs-lookup"><span data-stu-id="edd06-168">The following XML request example shows how to get a photo for Sadie Daniels that's 360 pixels wide by 360 pixels high.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8" ?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:xsd="http://www.w3.org/2001/XMLSchema"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages">
   <soap:Header>
      <t:RequestServerVersion Version="Exchange2013 "/>
   </soap:Header>
   <soap:Body>
      <m:GetUserPhoto>
         <m:Email>sadie@contoso.com</m:Email>
         <m:SizeRequested>HR360x360</m:SizeRequested>
      </m:GetUserPhoto>
   </soap:Body>
</soap:Envelope>

```

<span data-ttu-id="edd06-169">La siguiente es la respuesta XML.</span><span class="sxs-lookup"><span data-stu-id="edd06-169">The following is the XML response.</span></span> <span data-ttu-id="edd06-170">La foto con codificación Base64 está contenida en el elemento [PictureData](http://msdn.microsoft.com/library/1124eac3-ebf2-4b81-96d3-96838c840433%28Office.15%29.aspx) (el contenido se ha acortado para mejorar la legibilidad).</span><span class="sxs-lookup"><span data-stu-id="edd06-170">The Base64-encoded photo is contained in the [PictureData](http://msdn.microsoft.com/library/1124eac3-ebf2-4b81-96d3-96838c840433%28Office.15%29.aspx) element (the content has been shortened for readability).</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
         xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <GetUserPhotoResponse ResponseClass="Success" 
         xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <ResponseCode>NoError</ResponseCode>
      <HasChanged>true</HasChanged>
      <PictureData>/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAg... wATRRRSuB//2Q==</PictureData>
    </GetUserPhotoResponse>
  </s:Body>
</s:Envelope>

```

### <a name="get-a-mailbox-user-photo-by-using-the-resolvenames-operation"></a><span data-ttu-id="edd06-171">Obtener una foto de usuario de buzón de correo mediante el uso de la operación ResolveNames</span><span class="sxs-lookup"><span data-stu-id="edd06-171">Get a mailbox user photo by using the ResolveNames operation</span></span>

<span data-ttu-id="edd06-172">Si no conoce la dirección de correo electrónico del usuario para el que va a obtener una foto, puede [usar la operación ResolveNames](how-to-resolve-ambiguous-names-by-using-ews-in-exchange-2013.md) para obtener a candidatos para una coincidencia de posible.</span><span class="sxs-lookup"><span data-stu-id="edd06-172">If you don't know the email address of the user for whom you are getting a photo, you can [use the ResolveNames operation](how-to-resolve-ambiguous-names-by-using-ews-in-exchange-2013.md) to get candidates for a possible match.</span></span> <span data-ttu-id="edd06-173">Si se especifica "AllProperties" para el atributo **ContactDataShape** del elemento [ResolveNames](http://msdn.microsoft.com/library/c85207e1-1315-443b-94ec-2b58f405076b%28Office.15%29.aspx) , se devolverá una gran cantidad de datos, incluidas las fotos de usuario, para cada candidato.</span><span class="sxs-lookup"><span data-stu-id="edd06-173">If you specify "AllProperties" for the **ContactDataShape** attribute of the [ResolveNames](http://msdn.microsoft.com/library/c85207e1-1315-443b-94ec-2b58f405076b%28Office.15%29.aspx) element, a lot of data, including user photos, will be returned for each candidate.</span></span> <span data-ttu-id="edd06-174">En el ejemplo siguiente se muestra la solicitud XML para resolver el nombre "Sadie" y devolver todas las propiedades para cada candidato.</span><span class="sxs-lookup"><span data-stu-id="edd06-174">The following example shows the XML request to resolve the name "Sadie" and return all the properties for each candidate.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
<soap:Header>
    <t:RequestServerVersion Version="Exchange2013" />
  </soap:Header>  
<soap:Body>
  <m:ResolveNames ReturnFullContactData="true" ContactDataShape="AllProperties">
      <m:UnresolvedEntry>sadie</m:UnresolvedEntry>
    </m:ResolveNames>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="edd06-175">Se devuelve una gran cantidad de datos en la respuesta.</span><span class="sxs-lookup"><span data-stu-id="edd06-175">A lot of data will be returned in the response.</span></span> <span data-ttu-id="edd06-176">En el ejemplo siguiente se muestra sólo los datos que es relevantes para la foto de usuario.</span><span class="sxs-lookup"><span data-stu-id="edd06-176">The following example shows only the data that is relevant to the user photo.</span></span> <span data-ttu-id="edd06-177">El elemento de **foto** contiene la foto de usuario con codificación Base64 (el contenido se ha acortado para mejorar la legibilidad).</span><span class="sxs-lookup"><span data-stu-id="edd06-177">The **Photo** element contains the Base64-encoded user photo (the content has been shortened for readability).</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
         xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:ResolveNamesResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
         xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:ResolveNamesResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:ResolutionSet TotalItemsInView="1" IncludesLastItemInRange="true">
            <t:Resolution>
              <t:Mailbox>
                <t:Name>Sadie Daniels</t:Name>
                <t:EmailAddress>sadie@contoso.com</t:EmailAddress>
                <t:RoutingType>SMTP</t:RoutingType>
                <t:MailboxType>Mailbox</t:MailboxType>
              </t:Mailbox>
              <t:Contact>
                <t:DisplayName>Sadie Daniels</t:DisplayName>
                <t:GivenName>Sadie</t:GivenName>
                <t:Initials/>
                <t:CompanyName>CONTOSO</t:CompanyName>
......
                <t:Photo>/9j/4AAQSkZJRgABAQE...qKKKAP/2Q==</t:Photo>
......
              </t:Contact>
            </t:Resolution>
          </m:ResolutionSet>
        </m:ResolveNamesResponseMessage>
      </m:ResponseMessages>
    </m:ResolveNamesResponse>
  </s:Body>
</s:Envelope>

```

### <a name="get-a-contact-user-photo-by-using-the-getattachment-operation"></a><span data-ttu-id="edd06-178">Obtener una foto de usuario de contacto mediante el uso de la operación GetAttachment</span><span class="sxs-lookup"><span data-stu-id="edd06-178">Get a contact user photo by using the GetAttachment operation</span></span>

<span data-ttu-id="edd06-179">Puede usar EWS para obtener fotos de contactos almacenados en su buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="edd06-179">You can use EWS to get photos from contacts stored in your mailbox.</span></span> <span data-ttu-id="edd06-180">En primer lugar, use la operación **GetItem** para devolver todas las propiedades, por lo que puede buscar las fotografías.</span><span class="sxs-lookup"><span data-stu-id="edd06-180">First, you use the **GetItem** operation to return all properties so you can look for photos.</span></span> <span data-ttu-id="edd06-181">En el ejemplo siguiente se muestra una solicitud XML para obtener un elemento de contacto.</span><span class="sxs-lookup"><span data-stu-id="edd06-181">The following example shows an XML request to get a contact item.</span></span> <span data-ttu-id="edd06-182">El identificador de elemento se ha acortado para mejorar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="edd06-182">The item ID has been shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
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
        <t:ItemId Id="AAAAGECXAAA=" ChangeKey="EQAAABYAAAD2WuN+TpqwSrNP9JCCMKC0AABLzXRv"/>
      </ItemIds>
    </GetItem>
  </soap:Body>
</soap:Envelope>

```

<span data-ttu-id="edd06-183">Busque el elemento [HasPicture](http://msdn.microsoft.com/library/922a43fe-01bd-49f2-9261-e00e4699b8da%28Office.15%29.aspx) comprobar que el contacto tiene una foto asociada.</span><span class="sxs-lookup"><span data-stu-id="edd06-183">Look for the [HasPicture](http://msdn.microsoft.com/library/922a43fe-01bd-49f2-9261-e00e4699b8da%28Office.15%29.aspx) element to verify that the contact has an associated photo.</span></span> <span data-ttu-id="edd06-184">A continuación, mire a través de la colección de datos adjuntos para uno que tenga el valor true para el elemento [IsContactPhoto](http://msdn.microsoft.com/library/ae36b5f9-a787-4863-9dbc-258ad724801d%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="edd06-184">Then look through the collection of attachments for one that has a value of true for the [IsContactPhoto](http://msdn.microsoft.com/library/ae36b5f9-a787-4863-9dbc-258ad724801d%28Office.15%29.aspx) element.</span></span> <span data-ttu-id="edd06-185">El siguiente ejemplo de respuesta muestra sólo los datos relevantes.</span><span class="sxs-lookup"><span data-stu-id="edd06-185">The following response example shows only the relevant data.</span></span> <span data-ttu-id="edd06-186">Los valores de ID se acortan para mejorar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="edd06-186">The ID values are shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
         xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:GetItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
         xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:GetItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:Contact>
              <t:ItemId Id="AAAAGECXAAA=" ChangeKey="EQAAABYAAAD2WuN+TpqwSrNP9JCCMKC0AABLzXRv"/>
              <t:ParentFolderId Id="nIxIAAA=" ChangeKey="AQAAAA=="/>
              <t:ItemClass>IPM.Contact</t:ItemClass>
              <t:Subject>Hope Gross</t:Subject>
              <t:Sensitivity>Normal</t:Sensitivity>
......
              <t:Attachments>
                <t:FileAttachment>
                  <t:AttachmentId Id="1LGlhgpgoA="/>
                  <t:Name>ContactPicture.jpg</t:Name>
                  <t:Size>6260</t:Size>
                  <t:LastModifiedTime>2011-03-09T16:55:55</t:LastModifiedTime>
                  <t:IsInline>false</t:IsInline>
                  <t:IsContactPhoto>true</t:IsContactPhoto>
                </t:FileAttachment>
              </t:Attachments>
......
              <t:HasPicture>true</t:HasPicture>
            </t:Contact>
          </m:Items>
        </m:GetItemResponseMessage>
      </m:ResponseMessages>
    </m:GetItemResponse>
  </s:Body>
</s:Envelope>

```

A continuación, use la operación **GetAttachment** con el **AttachmentId** para solicitar los datos adjuntos que tiene la foto del contacto. En el ejemplo siguiente se muestra la solicitud XML para obtener los datos adjuntos. <span data-ttu-id="edd06-189">El identificador es más cortos para mejorar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="edd06-189">The ID is shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Body>
    <GetAttachment xmlns="http://schemas.microsoft.com/exchange/services/2006/messages"
    xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <AttachmentShape/>
      <AttachmentIds>
         <t:AttachmentId Id="1LGlhgpgoA="/>
      </AttachmentIds>
    </GetAttachment>
  </soap:Body>
</soap:Envelope>

```

En el ejemplo siguiente se muestra la respuesta XML con la información acerca de los datos adjuntos que ha solicitado. <span data-ttu-id="edd06-191">El elemento de [contenido](http://msdn.microsoft.com/library/24f8c54a-505f-4fc0-b7e7-93ad50b97070%28Office.15%29.aspx) contiene la cadena con codificación Base64 para la foto de usuario más cortos en este ejemplo para mejorar la legibilidad.</span><span class="sxs-lookup"><span data-stu-id="edd06-191">The [Content](http://msdn.microsoft.com/library/24f8c54a-505f-4fc0-b7e7-93ad50b97070%28Office.15%29.aspx) element contains the Base64-encoded string for the user photo, shortened in this example for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
         xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:GetAttachmentResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
         xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:GetAttachmentResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Attachments>
            <t:FileAttachment>
              <t:AttachmentId Id="+KsDBEr1LGlhgpgoA="/>
              <t:Name>ContactPicture.jpg</t:Name>
              <t:Content>/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAg...D//2Q==</t:Content>
            </t:FileAttachment>
          </m:Attachments>
        </m:GetAttachmentResponseMessage>
      </m:ResponseMessages>
    </m:GetAttachmentResponse>
  </s:Body>
</s:Envelope>

```

<span data-ttu-id="edd06-192"><a name="bk_EWS"> </a></span><span class="sxs-lookup"><span data-stu-id="edd06-192"></span></span>

## <a name="decode-a-base64-encoded-string"></a><span data-ttu-id="edd06-193">Descodifica una cadena con codificación Base64</span><span class="sxs-lookup"><span data-stu-id="edd06-193">Decode a Base64-encoded string</span></span>

<span data-ttu-id="edd06-194">Independientemente de la operación que se utiliza para obtener una foto de usuario, debe descodificar dicha cadena, por lo que puede usar en la aplicación.</span><span class="sxs-lookup"><span data-stu-id="edd06-194">Regardless of the operation you use to get a user photo, you'll need to decode that string so you can use it in your application.</span></span> <span data-ttu-id="edd06-195">En el ejemplo siguiente se muestra cómo descodificar la cadena y, a continuación, guárdelo en el equipo local para su aplicación puede tener acceso a él más adelante.</span><span class="sxs-lookup"><span data-stu-id="edd06-195">The following example shows how to decode the string, and then save it to your local computer so you application can access it later.</span></span>
  
```cs
// Convert the encoded string into a byte array.
byte[] data = System.Convert.FromBase64String(Photo);
// Create a memory stream to read the data.
MemoryStream ms = new MemoryStream(data);
// Save the data on your local computer as a JPG image.
using (FileStream file = new FileStream(ContactName + ".jpg", FileMode.Create, System.IO.FileAccess.Write))
{
   byte[] bytes = new byte[ms.Length];
   ms.Read(bytes, 0, (int)ms.Length);
   file.Write(bytes, 0, bytes.Length);
   ms.Close();
}

```

## <a name="see-also"></a><span data-ttu-id="edd06-196">Ver también</span><span class="sxs-lookup"><span data-stu-id="edd06-196">See also</span></span>

- [<span data-ttu-id="edd06-197">Las personas y los contactos de EWS en Exchange</span><span class="sxs-lookup"><span data-stu-id="edd06-197">People and contacts in EWS in Exchange</span></span>](people-and-contacts-in-ews-in-exchange.md)    
- [<span data-ttu-id="edd06-198">Resolver nombres ambiguos mediante el uso de EWS en Exchange 2013</span><span class="sxs-lookup"><span data-stu-id="edd06-198">Resolve ambiguous names by using EWS in Exchange 2013</span></span>](how-to-resolve-ambiguous-names-by-using-ews-in-exchange-2013.md)    
- [<span data-ttu-id="edd06-199">Contactos de proceso por lotes mediante EWS en Exchange</span><span class="sxs-lookup"><span data-stu-id="edd06-199">Process contacts in batches by using EWS in Exchange</span></span>](how-to-process-contacts-in-batches-by-using-ews-in-exchange.md)
    
