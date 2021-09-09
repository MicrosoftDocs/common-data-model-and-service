---
title: Construct map and array types using projection operations | Microsoft Docs
description: API reference for CdmOperationAddArtifactAttribute.
author: llawwaii
ms.service: common-data-model
ms.reviewer: v-iap 
ms.topic: article
ms.date: 09/08/2021
ms.author: weiluo
---


# Constructing Array and Map types using Projection operations

## Overview

We can use multiple projection operations to indicate an attribute is a map or an array.

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

### Array Type

There are two ways to indicate the type of array on an item, `array[item]`.

1. Structured resolution form

   Applying the trait [is.dataFormat.list](../list-of-traits.md#isdataFormatlist) to item without making space to hold a fixed number of the item.

2. Non-structured resolution form

   Making a certain number of copies of the item, and applying the trait [has.expansionInfo.list](../list-of-traits.md#hasexpansionInfolist) to each item. If multiple type attributes are expanded and renamed, we would not able to easily differentiate each expanded attribute; therefore, This trait has parameters `expansionName` and `ordinal` to hold each trait's unique info.

#### I can construct a Array of type attributes

The following examples are to define a new `NewPerson` entity which has an array of `email`.

- Structured resolution form

    We can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation on `email` to apply the trait [is.dataFormat.list](../list-of-traits.md#isdataFormatlist).

    ```json
    {
        "entityName": "NewPerson",
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
                "dataType": "string",
                "projection": {
                    "operations": [
                        {
                            "$type": "alterTraits",
                            "traitsToAdd": [
                                "is.dataFormat.list"
                            ]
                        }
                    ]
                }
            }
        ]
    }
    ```

    The resulting resolved NewPerson entity is:

    |NewPerson|Newly added traits from projection operations|
    |---|---|
    |name||
    |age||
    |address||
    |phoneNumber||
    |email|is.dataFormat.list|

- None-structured resolution form  

    First, we can use the [ArrayExpansion](../../1.0om/api-reference/cdm/projections/arrayexpansion.md) operation on `email` to expand `email`, the example below makes 2 copies of `email`. Then we can the [RenameAttributes](../../1.0om/api-reference/cdm/projections/renameattributes.md) operation to rename each copy to avoid expanded emails getting merge to one single attribute due to the same name. Finally, we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [has.expansionInfo.list](../list-of-traits.md#hasexpansionInfolist). In this case, we need to use wildcards to provide values for the parameters `expansionName` and `ordinal`.

    **__Note:__** We can use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to insert a new attribute `emailCount` and use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [has.expansionInfo.count](../list-of-traits.md#hasexpansionInfocount) on it.

    ```json
    {
        "entityName": "NewPerson",
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
                "dataType": "string",
                "projection": {
                    "operations": [
                        {
                            "$type": "arrayExpansion",
                            "startOrdinal": 1,
                            "endOrdinal": 2
                        },
                        {
                            "$type": "renameAttributes",
                            "renameFormat": "email_{o}"
                        },
                        {
                            "$type": "alterTraits",
                            "traitsToAdd": [
                                {
                                    "traitReference": "has.expansionInfo.list",
                                    "arguments": [
                                        {
                                            "name": "expansionName",
                                            "value": "{a}"
                                        },
                                        {
                                            "name": "ordinal",
                                            "value": "{o}"
                                        }
                                    ]
                                }
                            ],
                            "argumentsContainWildcards": true
                        },
                        {
                            "$type": "addArtifactAttribute",
                            "newAttribute": {
                                "name": "emailCount",
                                "dataType": "integer"
                            }
                        },
                        {
                            "$type": "alterTraits",
                            "traitsToAdd": [
                                {
                                    "traitReference": "indicates.expansionInfo.count",
                                    "arguments": [
                                        {
                                            "name": "expansionName",
                                            "value": "{a}"
                                        }
                                    ]
                                }
                            ],
                            "applyTo": "emailCount",
                            "argumentsContainWildcards": true
                        }
                    ],
                    "runSequentially": true
                }
            }
        ]
    }
    ```

    The resulting resolved NewPerson entity is:

    |NewPerson|Newly added traits from projection operations|
    |---|---|
    |name||
    |age||
    |address||
    |phoneNumber||
    |email_1|has.expansionInfo.list(email, 1)|
    |email_2|has.expansionInfo.list(email, 2)|
    |emailCount|indicates.expansionInfo.count(email)|

#### I can construct a Array of entity attributes

The following examples are to define a new `PersonInfo` entity which has an array of `Person`.

- Structured resolution form

    We need to use the [AddAttributeGroup](../../1.0om/api-reference/cdm/projections/addattributegroup.md) operation to group all member attributes from the `Person` entity, then we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation on attribute group to apply the trait [is.dataFormat.list](../list-of-traits.md#isdataFormatlist).

    ```json
    {
        "entityName": "PersonInfo",
        "hasAttributes": [
            {
                "name": "id",
                "dataType": "string"
            },
            {
                "name": "twoPeople",
                "entity": {
                    "source": "Person",
                    "operations": [
                        {
                            "$type": "addAttributeGroup",
                            "attributeGroupName": "musketeers"
                        },
                        {
                            "traitsToAdd": [
                                {
                                    "traitReference": "is.dataFormat.list"
                                }
                            ]
                        }
                    ],
                    "runSequentially": true
                }
            }
        ]
    }
    ```

    The resulting resolved PersonInfo entity is:

    |PersonInfo|Members in Attribute Group Reference|Newly added traits from projection operations|
    |---|---|---|
    |id|||
    |musketeers||is.dataFormat.list|
    ||name||
    ||age||
    ||address||
    ||phoneNumber||
    ||email||

- None-structured resolution form  

    First, we can use the [ArrayExpansion](../../1.0om/api-reference/cdm/projections/arrayexpansion.md) operation to expand the entity attribute `Person`, the example below makes 2 copies of `Person`. Then we can the [RenameAttributes](../../1.0om/api-reference/cdm/projections/renameattributes.md) operation to rename each copy of the member attribute to avoid expanded attributes getting merge to one single attribute due to the same name. Finally, we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [has.expansionInfo.list](../list-of-traits.md#hasexpansionInfolist). In this case, we need to use wildcards to provide values for the parameters `expansionName`, `ordinal`, and `memberAttribute`.

    ```json
    {
        "entityName": "PersonInfo",
        "hasAttributes": [
            {
                "name": "id",
                "dataType": "string"
            },
            {
                "name": "twoPeople",
                "entity": {
                    "source": "Person",
                    "operations": [
                        {
                            "$type": "arrayExpansion",
                            "startOrdinal": 1,
                            "endOrdinal": 2
                        },
                        {
                            "$type": "renameAttributes",
                            "renameFormat": "{m}_{o}"
                        },
                        {
                            "$type": "alterTraits",
                            "traitsToAdd": [
                                {
                                    "traitReference": "has.expansionInfo.list",
                                    "arguments": [
                                        {
                                            "name": "expansionName",
                                            "value": "{a}"
                                        },
                                        {
                                            "name": "ordinal",
                                            "value": "{o}"
                                        },
                                        {
                                            "name": "memberAttribute",
                                            "value": "{m}"
                                        }
                                    ]
                                }
                            ],
                            "argumentsContainWildcards": true
                        }
                    ],
                    "runSequentially": true
                }
            }
        ]
    }
    ```

    The resulting resolved PersonInfo entity is:

    |PersonInfo|Newly added traits from projection operations|
    |---|---|
    |id||
    |name_1|has.expansionInfo.list(twoPeople, 1, name)|
    |age_1|has.expansionInfo.list(twoPeople, 1, age)|
    |address_1|has.expansionInfo.list(twoPeople, 1, address)|
    |phoneNumber_1|has.expansionInfo.list(twoPeople, 1, phoneNumber)|
    |email_1|has.expansionInfo.list(twoPeople, 1, email)|
    |name_2|has.expansionInfo.list(twoPeople, 2, name)|
    |age_2|has.expansionInfo.list(twoPeople, 2, age)|
    |address_2|has.expansionInfo.list(twoPeople, 2, address)|
    |phoneNumber_2|has.expansionInfo.list(twoPeople, 2, phoneNumber)|
    |email_2|has.expansionInfo.list(twoPeople, 2, email)|

### Map Type

