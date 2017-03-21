---
title: DELETE Unit of Measure method | Microsoft Docs
description: Deletes an Unit of Measure.
services: project-madeira
documentationcenter: ''
author: SusanneWindfeldPedersen

ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 03/13/2017
ms.author: solsen
---

# DELETE Unit of Measure Method

Delete an unitsOfMeasure from [!INCLUDE[d365fin_long_md](../dynamics-nav/includes/d365fin_long_md.md)].

## Prerequisites

## HTTP request
```
DELETE /financials/companies/{id}/unitsOfMeasure/{id}
```
## Optional query parameters

## Request headers

|Header|Value|
|------|-----|
|Authorization  |Bearer . Required. |

## Request body

Do not supply a request body for this method.

## Response

If successful, this method returns ```204, No Content``` response code. It does not return anything in the response body.

## Example

**Request**

Here is an example of the request.

```json
DELETE https://graph.microsoft.com/beta/financials/companies/{id}/unitsOfMeasure/{id}
```

**Response** 

Here is an example of the response. 

```json
HTTP/1.1 204 No Content
```

## See Also
[Microsoft Graph Reference](graph-reference.md)  