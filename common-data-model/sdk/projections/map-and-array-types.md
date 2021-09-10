---
title: Construct map and array types using projection operations | Microsoft Docs
description: Usage guide for construct map and array types using projection operations 
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

## Array Type

There are two ways to indicate the type of array on an item, `array[item]`.

1. Structured Resolution Form

   Apply the trait [is.dataFormat.list](../list-of-traits.md#isdataFormatlist) to the item without making space to hold a fixed number of copies of the item.

2. Non-structured Resolution Form

   Make a certain number of copies of the item, and apply the trait [has.expansionInfo.list](../list-of-traits.md#hasexpansioninfolist) to each item. If multiple attributes are expanded and renamed, we would not able to easily differentiate each expanded attribute; therefore, This trait has parameters `expansionName` and `ordinal` to hold each trait's unique info.

### Constructing an Array of type attributes

The following examples are to define a new `NewPerson` entity which has an array of `email`.

- Structured Resolution Form

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

- Non-structured Resolution Form  

    First, we can use the [ArrayExpansion](../../1.0om/api-reference/cdm/projections/arrayexpansion.md) operation on `email` to expand `email`, the example below makes 2 copies of `email`. Then we can the [RenameAttributes](../../1.0om/api-reference/cdm/projections/renameattributes.md) operation to rename each copy to avoid the expanded emails getting merge to one single attribute due to the same name. Finally, we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [has.expansionInfo.list](../list-of-traits.md#hasexpansionInfolist). In this case, we need to use wildcards to provide values for the parameters `expansionName` and `ordinal`.

    **__Note:__** We can use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to insert a new attribute `emailCount` and use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [indicates.expansionInfo.count](../list-of-traits.md#indicatesexpansioninfocount) on it.

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

### Constructing an Array of entity attributes

The following examples are to define a new `PersonInfo` entity which has an array of `Person`.

- Structured Resolution Form

    We need to use the [AddAttributeGroup](../../1.0om/api-reference/cdm/projections/addattributegroup.md) operation to group all member attributes from the `Person` entity, then we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation on the attribute group to apply the trait [is.dataFormat.list](../list-of-traits.md#isdataFormatlist).

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

- Non-structured Resolution Form  

    First, we can use the [ArrayExpansion](../../1.0om/api-reference/cdm/projections/arrayexpansion.md) operation to expand the entity attribute `Person`, the example below makes 2 copies of `Person`. Then we can the [RenameAttributes](../../1.0om/api-reference/cdm/projections/renameattributes.md) operation to rename each copy of the member attribute to avoid expanded attributes getting merge to one single attribute due to the same name. Finally, we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [has.expansionInfo.list](../list-of-traits.md#hasexpansioninfolist). In this case, we need to use wildcards to provide values for the parameters `expansionName`, `ordinal`, and `memberAttribute`.

    **__Note:__** We can use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to insert a new attribute `peopleCount` and use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [indicates.expansionInfo.count](../list-of-traits.md#indicatesexpansioninfocount) on it.

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

## Map Type

There are two ways to interpret the type of map as mapping keys to items.

1. Structured Resolution Form

   Create a key to map the item, apply the trait [is.dataFormat.mapKey](../list-of-traits.md#isdataFormatmapkey) to the key and the trait [is.dataFormat.mapValue](../list-of-traits.md#isdataFormatmapvalue). Group the key and the item and apply the trait the trait [is.dataFormat.map](../list-of-traits.md#isdataFormatmap) to the group. Do not make space to hold a fixed number of copies of the key-value pair.

2. Non-structured Resolution Form

    Create a key to map the item, make a certain number of copies of the `[key, item]` pair, and apply the trait [indicates.expansionInfo.mapKey](../list-of-traits.md#indicatesexpansioninfomapKey) on keys and the trait [indicates.expansionInfo.mapValue](../list-of-traits.md#hasexpansioninfomapvalue) on the values. If multiple type attributes are expanded and renamed, we would not able to easily differentiate each expanded attribute; therefore, This trait has parameters `expansionName` and `ordinal` to hold each trait's unique info.

### Constructing Map on a type attribute

The following examples are to define a new `NewPerson` entity which has an array of `[key, email]` pairs.

- Structured Resolution Form

    We can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation on `email` to apply the trait [is.dataFormat.mapValue](../list-of-traits.md#isdataFormatmapvalue). Now, we need to use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to create a key for the item `email` with the trait [is.dataFormat.mapKey](../list-of-traits.md#isdataFormatmapKey). Finally, we need to use the [AddAttributeGroup](../../1.0om/api-reference/cdm/projections/addattributegroup.md) operation to group the key and the item `email` to a key-pair pair, then we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation on the attribute group to apply the trait [is.dataFormat.map](../list-of-traits.md#isdataFormatmap).

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
                                "is.dataFormat.mapValue"
                            ]
                        },
                        {
                            "$type": "addArtifactAttribute",
                            "newAttribute": {
                                "name": "keyOfEmail",
                                "dataType": "string",
                                "appliedTraits": [
                                    "is.dataFormat.mapKey"
                                ]
                            },
                            "insertAtTop": true
                        },
                        {
                            "$type": "addAttributeGroup",
                            "attributeGroupName": "favorite Term Group"
                        },
                        {
                            "$type": "alterTraits",
                            "traitsToAdd": [
                                "is.dataFormat.map"
                            ]
                        }
                    ],
                    "runSequentially": true
                }
            }
        ]
    }
    ```

    The resulting resolved NewPerson entity is:

    |NewPerson|Members in Attribute Group Reference|Newly added traits from projection operations|
    |---|---|---|
    |name|||
    |age|||
    |address|||
    |phoneNumber|||
    |emailMap||is.dataFormat.map|
    ||keyOfEmail|is.dataFormat.mapKey|
    ||email|is.dataFormat.mapValue|

- Non-structured Resolution Form  

    First, we need to use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to create a key for the item `email`. Now, we can use the [ArrayExpansion](../../1.0om/api-reference/cdm/projections/arrayexpansion.md) operation to expand the `[key email]` pair, the example below makes 2 copies of `[key, email]` pairs. Then we can the [RenameAttributes](../../1.0om/api-reference/cdm/projections/renameattributes.md) operation to rename each key and value to avoid the expanded attributes getting merge to one single attribute due to the same name. Finally, we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [indicates.expansionInfo.mapKey](../list-of-traits.md#indicatesexpansioninfomapkey) on keys and the trait [has.expansionInfo.mapValue](../list-of-traits.md#hasexpansioninfomapvalue) on the values. In this case, we need to use wildcards to provide values for the parameters `expansionName` and `ordinal`. Also, because of the dynamic argument values, we need to use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait for the newly added key attribute at the end instead of attaching the trait from the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation in the first step.

    **__Note:__** We can use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to insert a new attribute `emailPairCount` and use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [indicates.expansionInfo.count](../list-of-traits.md#indicatesexpansioninfocount) on it.

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
                            "$type": "addArtifactAttribute",
                            "newAttribute": {
                                "name": "keyOfEmail",
                                "dataType": "string"
                            },
                            "insertAtTop": true
                        },
                        {
                            "$type": "arrayExpansion",
                            "startOrdinal": 1,
                            "endOrdinal": 2
                        },
                        {
                            "$type": "renameAttributes",
                            "renameFormat": "{a}_{o}_value",
                            "applyTo": [
                                "email"
                            ]
                        },
                        {
                            "$type": "renameAttributes",
                            "renameFormat": "{a}_{o}_key",
                            "applyTo": [
                                "keyOfEmail"
                            ]
                        },
                        {
                            "$type": "alterTraits",
                            "traitsToAdd": [
                                {
                                    "traitReference": "has.expansionInfo.mapValue",
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
                            "applyTo": [
                                "email"
                            ],
                            "argumentsContainWildcards": true
                        },
                        {
                            "$type": "alterTraits",
                            "condition": "!structured",
                            "traitsToAdd": [
                                {
                                    "traitReference": "indicates.expansionInfo.mapKey",
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
                            "applyTo": [
                                "keyOfEmail"
                            ],
                            "argumentsContainWildcards": true
                        },
                        {
                            "$type": "addArtifactAttribute",
                            "newAttribute": {
                                "name": "emailPairCount",
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
                            "applyTo": "emailPairCount",
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
    |email_1_key|indicates.expansionInfo.mapKey(email, 1)|
    |email_1_value|has.expansionInfo.mapValue(email, 1)|
    |email_2_key|indicates.expansionInfo.mapKey(email, 2)|
    |email_2_value|has.expansionInfo.mapValue(email, 2)|
    |emailPairCount|indicates.expansionInfo.count(email)|

### Constructing a Map on an entity attribute

The following examples are to define a new `PersonInfo` entity which has an array of `[key, Person]` pairs.

- Structured Resolution Form

    We need to use the [AddAttributeGroup](../../1.0om/api-reference/cdm/projections/addattributegroup.md) operation to group all member attributes from the `Person` entity, then we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation on the attribute group to apply the trait [is.dataFormat.mapValue](../list-of-traits.md#isdataFormatmapvalue). Now, we need to use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to create a key for the group `person` and use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [is.dataFormat.mapKey](../list-of-traits.md#isdataFormatmapKey). Finally, we need to use the [AddAttributeGroup](../../1.0om/api-reference/cdm/projections/addattributegroup.md) operation to group the key and the item `person` to a key-pair pair, then we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation on the outer attribute group (key-value pair) to apply the trait [is.dataFormat.map](../list-of-traits.md#isdataFormatmap).

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
                                "attributeGroupName": "person"
                            },
                            {
                                "$type": "alterTraits",
                                "traitsToAdd": [
                                    "is.dataFormat.mapValue"
                                ]
                            },
                            {
                                "$type": "addArtifactAttribute",
                                "newAttribute": {
                                    "name": "keyOfPerson",
                                    "dataType": "string",
                                    "appliedTraits": [
                                        "is.dataFormat.mapKey"
                                    ]
                                },
                                "insertAtTop": true
                            },
                            {
                                "$type": "addAttributeGroup",
                                "attributeGroupName": "personPair"
                            },
                            {
                                "$type": "alterTraits",
                                "traitsToAdd": [
                                    "is.dataFormat.map"
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

    |PersonInfo|Members in Attribute Group Reference|Members in Attribute Group Reference|Newly added traits from projection operations|
    |---|---|---|---|
    |id||||
    |personPair|||is.dataFormat.map|
    ||keyOfPerson||is.dataFormat.mapKey|
    ||personPair||is.dataFormat.mapValue|
    |||name||
    |||age||
    |||address||
    |||phoneNumber||
    |||email||

- Non-structured Resolution Form  

    First, we need to use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to create a key for the entity `Person`. Now, we can use the [ArrayExpansion](../../1.0om/api-reference/cdm/projections/arrayexpansion.md) operation to expand the key and `Person`, the example below makes 2 copies of keys and 2 copies of `Person`. Then we need to use the [RenameAttributes](../../1.0om/api-reference/cdm/projections/renameattributes.md) operation to rename each key and member attribute from the `person` entity to avoid the expanded attributes getting merge to one single attribute due to the same name. Finally, we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [indicates.expansionInfo.mapKey](../list-of-traits.md#indicatesexpansioninfomapkey) on keys and the trait [has.expansionInfo.mapValue](../list-of-traits.md#hasexpansioninfomapvalue) on the member attribute from the `person` entity. In this case, we need to use wildcards to provide values for the parameters `expansionName`, `ordinal`, and `memberAttribute`. Also, because of the dynamic argument values, we need to use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait for the newly added key attribute at the end instead of attaching the trait from the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation in the first step.

    **__Note:__** We can use the [AddArtifactAttribute](../../1.0om/api-reference/cdm/projections/addartifactattribute.md) operation to insert a new attribute `peopleCount` and use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [indicates.expansionInfo.count](../list-of-traits.md#indicatesexpansioninfocount) on it.

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
                            "$type": "addArtifactAttribute",
                            "newAttribute": {
                                "name": "keyOfPerson",
                                "dataType": "string"
                            },
                            "insertAtTop": true
                        },
                        {
                            "$type": "arrayExpansion",
                            "startOrdinal": 1,
                            "endOrdinal": 2
                        },
                        {
                            "$type": "renameAttributes",
                            "renameFormat": "{a}_{o}_key",
                            "applyTo": [
                                "key"
                            ]
                        },
                        {
                            "$type": "renameAttributes",
                            "applyTo": [
                                "age",
                                "name",
                                "address",
                                "email",
                                "phoneNumber"
                            ],
                            "renameFormat": "{a}_{m}_{o}_value"
                        },
                        {
                            "$type": "renameAttributes",
                            "renameFormat": "{a}_{o}_key",
                            "applyTo": [
                                "keyOfPerson"
                            ]
                        },
                        {
                            "$type": "alterTraits",
                            "traitsToAdd": [
                                {
                                    "traitReference": "has.expansionInfo.mapValue",
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
                            "applyTo": [
                                "age",
                                "name",
                                "address",
                                "email",
                                "phoneNumber"
                            ],
                            "argumentsContainWildcards": true
                        },
                        {
                            "$type": "alterTraits",
                            "condition": "!structured",
                            "traitsToAdd": [
                                {
                                    "traitReference": "indicates.expansionInfo.mapKey",
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
                            "applyTo": [
                                "keyOfPerson"
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
    |twoPeople_1_key|indicates.expansionInfo.mapKey(twoPeople, 1)|
    |twoPeople_name_1_value|has.expansionInfo.mapValue(twoPeople, 1, name)|
    |twoPeople_age_1_value|has.expansionInfo.mapValue(twoPeople, 1, age)|
    |twoPeople_address_1_value|has.expansionInfo.mapValue(twoPeople, 1, address)|
    |twoPeople_phoneNumber_1_value|has.expansionInfo.mapValue(twoPeople, 1, phoneNumber)|
    |twoPeople_email_1_key|has.expansionInfo.mapValue(twoPeople, 1, email)|
    |twoPeople_2_value|indicates.expansionInfo.mapKey(twoPeople, 2)|
    |twoPeople_name_2_value|has.expansionInfo.mapValue(twoPeople, 2, name)|
    |twoPeople_age_2_value|has.expansionInfo.mapValue(twoPeople, 2, age)|
    |twoPeople_address_2_value|has.expansionInfo.mapValue(twoPeople, 2, address)|
    |twoPeople_phoneNumber_2_value|has.expansionInfo.mapValue(twoPeople, 2, phoneNumber)|
    |twoPeople_email_2_value|has.expansionInfo.mapValue(twoPeople, 2, email)|
