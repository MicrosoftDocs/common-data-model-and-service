---
title: Operation Combine Attributes Usage Guide | Microsoft Docs
description: Usage guide for the Combine Attributes operation.
author: violivei

ms.reviewer: v-iap 
ms.topic: reference 
ms.date: 02/24/2021
ms.author: violivei
---

# Projection - Operation Combine Attributes

## Overview

CombineAttributes is a projection operation that allows you to merge multiple input attribute into one. This operation takes a list of attributes on the `select` property and replace them with the data typed attribute supplied on the `mergeInto` property. If the list of attributes to be merged is empty, this operation does not have any effect.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/combineattributes.md).

## Examples

The examples below refer to the `ContactKinds` entity as defined here.

```json
{
    "entityName": "ContactKinds",
    "hasAttributes": [
        {
            "name": "emailKind",
            "entity": "Email"
        },
        { 
            "name": "phoneKind", 
            "entity": "Phone"
        },
        {
            "name": "socialKind",
            "entity": "Social"
        }
    ]
}
```

|Email|Phone|Social|
|-|-|-|
|emailId|phoneId|socialId|
|address|number|account|
|isPrimary|isPrimary|isPrimary|

### Using the CombineAttributes operation on an entity attribute

If we have an entity attribute, we can use CombineAttributes to merge certain attributes we get from the referenced entity.

```json
{
    "name": "contactAt",
    "isPolymorphicSource": true,
    "entity": {
        "operations": [
            {
                "$type": "combineAttributes",
                "select": ["emailId", "phoneId", "socialId"],
                "mergeInto": {
                    "name": "contactId",
                    "dataType": "entityId"
                }
            }
        ],
        "source": "ContactKinds"
    }
}
```

The resulting resolved contactAt entity typed attribute is:

|contactAt|
|-|
|address|
|isPrimary|
|number|
|account|
|contactId|
|contactType|

### Using the CombineAttributes operation when extending an entity

If we have an entity that extends another entity, we can use CombineAttributes to merge certain attributes that are inherited from the entity we are extending from.

Given an entity, Child, that extends from the Person entity:

```json
{
    "entityName": "Customer",
    "extendsEntity": {
        "operations": [
            {
                "$type": "combineAttributes",
                "select": [ "emailId", "phoneId", "socialId" ],
                "mergeInto": {
                    "name": "contactId",
                    "dataType": "entityId"
                }
            }
        ],
        "source": "ContactKinds"
    },
    "hasAttributes": []
}
```

The resulting resolved Customer entity is:

|Customer|
|-|
|address|
|isPrimary|
|number|
|account|
|contactId|
