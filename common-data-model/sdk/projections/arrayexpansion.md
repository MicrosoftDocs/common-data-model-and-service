---
title: Operation Array Expansion Usage Guide | Microsoft Docs
description: Usage guide for the Array Expansion operation.
author: violivei
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 24/02/2020
ms.author: violivei
---

# Projection - Operation Array Expansion

## Overview

ArrayExpansion is a projection operation that makes n copies of every input attribute and marks each temporarily with an ordinal. This operation has two required properties that are `StartOrdinal` and `EndOrdinal`. Based on these two values, the operation will make copies of the input attributes starting at index `StartOrdinal` and going until `EndOrdinal`.

1. startOrdinal < 0:
Round 0 of an array expansion starts at ordinal 0 or startOrdinal, whichever is larger. Ordinals less than 0 will be skipped by the array expansion. <br>
Ex. startOrdinal = -2, endOrdinal = 2 will result in an expansion of a[0], a[1], a[2]

1. startOrdinal > endOrdinal:
No array expansion occurs. A warning is logged and the input resolved attributes just pass through.

1. startOrdinal == endOrdinal:
The array expansion goes through a single round.

1. endOrdinal > maxOrdinalForArrayExpansion:
maxOrdinalForArrayExpansion is a configurable value in ResolveOptions for setting the maximum ending ordinal value. The default value is 20. If endOrdinal is greater than maxOrdinalForArrayExpansion, then maxOrdinalForArrayExpansion is used instead.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/arrayexpansion.md).

> **__Note__** Doing an ArrayExpansion without a [RenameAttributes](renameattributes.md) afterwards will result in the expanded attributes being merged in the final resolved entity. This is because ArrayExpansion does not rename the attributes it expands by default. The expanded attributes end up with the same name and gets merged. <br>
> Ex. We expand A to A[1], A[2], A[3], but A[1], A[2], A[3] are still named “A”.<br><br>
> We must chain a RenameAttributes operation after an ArrayExpansion if we wish to see the expanded attributes (with the ordinal in their attribute name) in the final output. We do this by nesting projections, where the inner projection contains the ArrayExpansion and the outer projection contains the RenameAttributes. <br>
> Ex. We expand A to A[1], A[2], A[3], and then rename to {m}_{o}, to get A_1, A_2, A_3

> **__Note:__** The ArrayExpansion operation is commonly used alongside the [AddCountAttribute](addcountattribute.md) operation. Although not required, the count attribute is useful to hold the number of elements in the array that have data.

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

### I can use a ArrayExpansion operation on an entity attribute

If we have an entity attribute, we can use ArrayExpansion to expand each attribute.

```json
{
    "name": "ThreeMusketeers",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "arrayExpansion",
                "startOrdinal": 1,
                "endOrdinal": 3,
            }
        ]
    }
}
```

The resulting resolved ThreeMusketeers entity typed attribute is:
|ThreeMusketeers|
|-|
|name|
|age|
|address|
|phoneNumber|
|email|

**Note:** Since we did not use a RenameAttributes operation after the ArrayExpansion, the expanded attributes are merged in the final resolved attributes due to having the same name.

Adding a RenameAttributes operations:

```json
{ 
    "name": "ThreeMusketeers",
    "entity": {
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
                    "endOrdinal": 3,
                }
            ],
            "source": "Person"
        }
    } 
}
```

The resulting resolved ThreeMusketeers entity typed attribute is:
|ThreeMusketeers|
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
|name_3|
|age_3|
|address_3|
|phoneNumber_3|
|email_3|

### I can use an ArrayExpansion operation when extending an entity

If we have an entity that extends another entity, we can use ArrayExpansion to expand the attributes inherited from the base entity.
Given an entity, ThreeMusketeers, that extends from the Person entity:

```json
{
    "entityName": "ThreeMusketeers",
    "extendsEntity": {
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
                    "endOrdinal": 3,
                }
            ],
            "source": "Person"
        }
    },
    "hasAttributes": []
}
```

The resulting resolved ThreeMusketeers entity is:
|ThreeMusketeers|
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
|name_3|
|age_3|
|address_3|
|phoneNumber_3|
|email_3|

### I can use multiple ArrayExpansion operations

We can nest projections if we want an ArrayExpansion operation to use another ArrayExpansion operation’s output as its source.

Given the following nested projection:

```json
{ 
    "name": "ThreePeople",
    "entity": {
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
                    "endOrdinal": 3,
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
                            "endOrdinal": 3,
                        }
                    ],
                    "source": "Person"
                }
            }
        }
    } 
}
```

The resulting resolved ThreeMusketeers entity typed attribute is:
|Input|After inner projection|Output|
|-|-|-|
|name|name_1|name_1_1
|age|age_1|age_1_1
|address|address_1|address_1_1
|phoneNumber|phoneNumber_1|…
|email|email_1|name_2_1
||name_2|age_2_1
||age_2|…
||...|…
||name_3|name_2_2
||age_3|age_2_2
||address_3|…
||...|email_3_3
