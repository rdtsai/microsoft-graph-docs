---
title: "Delete ipNamedLocation"
description: "Delete an ipNamedLocation object."
localization_priority: Normal
author: "davidmu1"
ms.prod: "microsoft-identity-platform"
doc_type: apiPageType
---

# Delete ipNamedLocation

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Delete an [ipNamedLocation](../resources/ipNamedLocation.md) object.

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

| Permission type                        | Permissions (from least to most privileged) |
|:---------------------------------------|:--------------------------------------------|
| Delegated (work or school account)     | Policy.ReadWrite.ConditionalAccess and Directory.AccessAsUser.All |
| Delegated (personal Microsoft account) | Not supported. |
| Application                            | Not supported. |

>[!NOTE]
>This API requires multiple permissions. For details, see [Known issues](/graph/known-issues#conditional-access-policies-and-named-locations).

## HTTP request

<!-- { "blockType": "ignored" } -->

```http
DELETE /conditionalAccess/namedLocations/{id}
```

## Request headers

| Name          | Description   |
|:--------------|:--------------|
| Authorization | Bearer {token}. Required. |

## Request body

Do not supply a request body for this method.

## Response

If successful, this method returns a `204 No Content` response code. It does not return anything in the response body.

## Examples

### Request

The following is an example of the request.
<!-- {
  "blockType": "request",
  "name": "delete_ipnamedlocation"
}-->

```http
DELETE https://graph.microsoft.com/beta/conditionalAccess/namedLocations/0854951d-5fc0-4eb1-b392-9b2c9d7949c2
```

### Response

The following is an example of the response.

<!-- {
  "blockType": "response",
  "truncated": true
} -->

```http
HTTP/1.1 204 No Content
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Delete ipNamedLocation",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
