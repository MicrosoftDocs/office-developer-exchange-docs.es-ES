---
title: MessageTrackingSearchResults
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- MessageTrackingSearchResults
api_type:
- schema
ms.assetid: 6bf36f37-c2b3-40c1-a4df-31573ed8642a
description: El elemento MessageTrackingSearchResults contiene una lista de registros que coinciden con los criterios de búsqueda.
ms.openlocfilehash: 866cc8d4e9afa8347eb7bd0d9e9acaddc616c396
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/11/2018
ms.locfileid: "19836454"
---
# <a name="messagetrackingsearchresults"></a><span data-ttu-id="b9267-103">MessageTrackingSearchResults</span><span class="sxs-lookup"><span data-stu-id="b9267-103">MessageTrackingSearchResults</span></span>

<span data-ttu-id="b9267-104">El elemento **MessageTrackingSearchResults** contiene una lista de registros que coinciden con los criterios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="b9267-104">The **MessageTrackingSearchResults** element contains a list of records that match the search criteria.</span></span> 
  
```XML
<MessageTrackingSearchResults>
   <MessageTrackingSearchResult/>
</MessageTrackingSearchResults>
```

 <span data-ttu-id="b9267-105">**ArrayOfFindMessageTrackingSearchResultType**</span><span class="sxs-lookup"><span data-stu-id="b9267-105">**ArrayOfFindMessageTrackingSearchResultType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="b9267-106">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="b9267-106">Attributes and elements</span></span>

<span data-ttu-id="b9267-107">Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios.</span><span class="sxs-lookup"><span data-stu-id="b9267-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="b9267-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="b9267-108">Attributes</span></span>

<span data-ttu-id="b9267-109">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="b9267-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="b9267-110">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="b9267-110">Child elements</span></span>

|<span data-ttu-id="b9267-111">**Element**</span><span class="sxs-lookup"><span data-stu-id="b9267-111">**Element**</span></span>|<span data-ttu-id="b9267-112">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="b9267-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="b9267-113">MessageTrackingSearchResult</span><span class="sxs-lookup"><span data-stu-id="b9267-113">MessageTrackingSearchResult</span></span>](messagetrackingsearchresult.md) <br/> |<span data-ttu-id="b9267-114">Contiene un resultado de mensaje único para un elemento [FindMessageTrackingReportResponse](findmessagetrackingreportresponse.md) .</span><span class="sxs-lookup"><span data-stu-id="b9267-114">Contains a single message result for a [FindMessageTrackingReportResponse](findmessagetrackingreportresponse.md) element.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="b9267-115">Elementos principales</span><span class="sxs-lookup"><span data-stu-id="b9267-115">Parent elements</span></span>

|<span data-ttu-id="b9267-116">**Element**</span><span class="sxs-lookup"><span data-stu-id="b9267-116">**Element**</span></span>|<span data-ttu-id="b9267-117">**Descripción**</span><span class="sxs-lookup"><span data-stu-id="b9267-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="b9267-118">FindMessageTrackingReportResponse</span><span class="sxs-lookup"><span data-stu-id="b9267-118">FindMessageTrackingReportResponse</span></span>](findmessagetrackingreportresponse.md) <br/> |<span data-ttu-id="b9267-119">Contiene el estado y el resultado de una única solicitud de [operación FindMessageTrackingReport](findmessagetrackingreport-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="b9267-119">Contains the status and result of a single [FindMessageTrackingReport operation](findmessagetrackingreport-operation.md) request.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="b9267-120">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="b9267-120">Text value</span></span>

<span data-ttu-id="b9267-121">Ninguno.</span><span class="sxs-lookup"><span data-stu-id="b9267-121">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="b9267-122">Observaciones</span><span class="sxs-lookup"><span data-stu-id="b9267-122">Remarks</span></span>

<span data-ttu-id="b9267-123">El esquema que describe este elemento se encuentra en el directorio virtual IIS que hospeda los servicios Web Exchange.</span><span class="sxs-lookup"><span data-stu-id="b9267-123">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="b9267-124">Información del elemento</span><span class="sxs-lookup"><span data-stu-id="b9267-124">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="b9267-125">Espacio de nombres</span><span class="sxs-lookup"><span data-stu-id="b9267-125">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="b9267-126">Nombre de esquema</span><span class="sxs-lookup"><span data-stu-id="b9267-126">Schema Name</span></span>  <br/> |<span data-ttu-id="b9267-127">Esquema de mensajes</span><span class="sxs-lookup"><span data-stu-id="b9267-127">Messages schema</span></span>  <br/> |
|<span data-ttu-id="b9267-128">Archivo de validación</span><span class="sxs-lookup"><span data-stu-id="b9267-128">Validation File</span></span>  <br/> |<span data-ttu-id="b9267-129">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="b9267-129">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="b9267-130">Puede estar vacío</span><span class="sxs-lookup"><span data-stu-id="b9267-130">Can be Empty</span></span>  <br/> |<span data-ttu-id="b9267-131">False</span><span class="sxs-lookup"><span data-stu-id="b9267-131">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="b9267-132">Ver también</span><span class="sxs-lookup"><span data-stu-id="b9267-132">See also</span></span>



- [<span data-ttu-id="b9267-133">Elementos XML de EWS de Exchange</span><span class="sxs-lookup"><span data-stu-id="b9267-133">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
