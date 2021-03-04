---
title: Operation Add Count Usage Guide | Microsoft Docs
description: Usage guide for the Add Count Attribute operation.
author: violivei
ms.service: common-data-model
ms.reviewer: v-iap 
ms.topic: article
ms.date: 02/24/2021
ms.author: violivei
---

# Projection - Operation Add Count Attribute

## Overview

AddCountAttribute is a projection operation that adds a user-specified count type attribute to the final resolved entity. It is recommended—but not mandated—to be used with the [ArrayExpansion](arrayexpansion.md) operation to provide an ArrayExpansion a count attribute that represents the total number of expanded elements. AddCountAttribute can also be used by itself.
The created count attribute will have the trait `is.linkedEntity.array.count`. This trait indicates that the attribute holds a count.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/addcountattribute.md).

## Examples

The examples below refer to the `Person` entity as defined here.

```json
{
    "entityName": "Person",
    "hasAttributes": [
        {
            "name": "name",
            "dataType": "string"
        },
        {
            "name": "age",
            "dataType": "integer"
        },
        {
            "name": "address",
            "dataType": "string"
        },
        {
            "name": "phoneNumber",
            "dataType": "string"
        },
        {
            "name": "email",
            "dataType": "string"
        }
    ]
}
```

### I can use a AddTypeAttribute operation on an entity attribute

If we have an entity attribute, we can use AddCountAttribute to add a count attribute.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "addCountAttribute",
                "countAttribute": {
                    "name": "someCount",
                    "dataType": "integer"
                }
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:
|PersonInfo|
|-|
|name|
|age|
|address|
|phoneNumber|
|email|
|someCount|

### I can use an AddTypeAttribute operation when extending an entity

If we have an entity that extends another entity, we can use AddCountAttribute to add a Count attribute.

Given an entity, NewPerson, that extends from the Person entity:

```json
{
    "entityName": "NewPerson",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "addCountAttribute",
                "countAttribute": {
                    "name": "someCount",
                    "dataType": "integer"
                }
            }
        ]
    }
}
```

The resulting resolved NewPerson entity is:
|NewPerson|
|-|
|name|
|age|
|address|
|phoneNumber|
|email|
|someCount|

### I can combine an AddCountAttribute operation with an ArrayExpansion

We can use an AddCountAttribute operation after an ArrayExpansion operation to add a Count attribute alongside the expanded attributes.

```json
{
    "name": "PersonInfo",
    "entity": {
        "operations": [
            {
                "$type": "addCountAttribute",
                "countAttribute": {
                    "name": "personCount",
                    "dataType": "integer",
                    "description": "Person array elements count"
                }
            }
        ],
        "source": {
            "operations": [
                {
                    "$type": "renameAttributes",
                    "renameFormat": "{m}_{o}"
                }
            ],
            "source": {
                "operations": [
                    {
                        "$type": "arrayExpansion",
                        "startOrdinal": 1,
                        "endOrdinal": 2
                    }
                ],
                "source": "Person"
            }
        }
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfo|
|-|
|name_1|
|age_1|
|address_1|
|phoneNumber_1|
|email_1|
|name_2|
|age_2|
|address_2|
|phoneNumber_2|
|email_2|
|personCount|
