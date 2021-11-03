---
title: Operation Alter Traits Usage Guide | Microsoft Docs
description: Usage guide for CdmOperationAlterTraits.
author: llawwaii
ms.service: common-data-model
ms.reviewer: v-iap 
ms.topic: article
ms.date: 09/03/2021
ms.author: weiluo
---

# Projection - Alter Traits operation

## Overview

AlterTraits is a projection operation that alters traits or trait groups for a specified set of attributes from the source, which can either be an entity reference or another projection. This operation will work as follows:  

1. All the attributes from the source that are provided as input to the operation will be added to a list where each attribute's traits will be modified. It is possible to specify a `applyTo` property that is a list of attributes' traits to be changed. The attributes that are in the specified list will be applied the rest of steps and added to the final attribute list. If an attribute is not in the specified list, it is added to the final set of attributes without changes.

1. The traits or trait groups defined in `traitsToAdd` property will be added to each of the pending attributes. If `argumentsContainWildcards` property is defined and set to true, it checks all arguments from all traits and performs replacement. The format supports the wilds cards {a/A}, {m/M}, {mo/Mo}, and {o}.
   * {a} will be replaced with the attribute name of the projection owner (which is the attribute to call the projection operation). If the projection owner is not a type attribute or an entity attribute, it will be replaced with an empty string.
   * {m} will be replaced with the resolved name of the current member attribute without changing the case of the text.
   * {mo} will be replaced with the original name of the current member attribute without changing the case of the text.
   * If {A}, {M}, or {Mo} is used, the first letter of the value will be capitalized.
   * {o} will be replaced with the index of the attribute after an array expansion. If the attribute wasn’t originated from an array expansion, it will be replaced with an empty string.

1. The traits or trait groups indicated in the `traitsToRemove` property will be removed in each of the pending attributes if they are found in the attribute's resolved traits.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/altertraits.md).

## Examples

The examples below refer to the `Person` entity and a few traits as defined here.

```json
{
    "entityName": "Person",
    "hasAttributes": [
        {
            "name": "name",
            "dataType": "string",
            "appliedTraits": [
                {
                    "traitReference": "means.requiredUpdateDate",
                    "arguments": [
                        {
                            "name": "month",
                            "value": "1"
                        }
                    ]
                }
            ]
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
},
{
    "traitName": "means.requiredUpdateAtAge18",
    "extendsTrait": "means"
},
{
    "traitName": "means.requiredUpdateAtAge30",
    "extendsTrait": "means"
},
{
    "traitName": "means.requiredUpdateAtAge45",
    "extendsTrait": "means"
},
{
    "traitName": "means.requiredUpdateAtAge60",
    "extendsTrait": "means"
},
{
    "traitName": "means.requiredUpdateDate",
    "extendsTrait": "means",
    "hasParameters": [
        {
            "name": "month",
            "explanation": "The month of a year",
            "dataType": "integer"
        },
        {
            "name": "day",
            "explanation": "The day of a month",
            "dataType": "integer"
        }
    ]
},
{
    "traitGroupName": "AllRequiredUpdate",
    "explanation": "Trait group that defines traits for updating person info at all ages.",
    "exhibitsTraits": [
        {
            "traitReference": "means.requiredUpdateAtAge18"
        },
        {
            "traitReference": "means.requiredUpdateAtAge30"
        },
        {
            "traitReference": "means.requiredUpdateAtAge45"
        },
        {
            "traitReference": "means.requiredUpdateAtAge60"
        }
    ]
}
```

### Using the AlterTraits operation on a type attribute

We can use the AlterTraits operation to modify traits in a type attribute in an entity. Let us first have a look at the entity definition below.

```json
{
    "entityName": "PersonInfo",
    "extendsEntity": "CdmEntity",
    "hasAttributes": [
        {
            "name": "legalName",
            "dataType": "string"
        },
        {
            "name": "job",
            "dataType": "string",
            "projection": {
                "operations": [
                    {
                        "$type": "alterTraits",
                        "traitsToAdd": [
                            {
                                "traitReference": "means.requiredUpdateAtAge18"
                            },
                            {
                                "traitGroupReference": "AllRequiredUpdate"
                            }
                        ],
                        "traitsToRemove": [
                            "means.requiredUpdateAtAge60"
                        ]
                    }
                ]
            }
        }
    ]
}
```

The resulting resolved PersonInfo entity is:

|PersonInfo|Newly added traits or updated arguments|
|---|---|
|legalName||
|job|means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|

### Using the AlterTraits operation on an entity attribute

If we have an entity attribute, we can use AlterTraits to edit traits in all the attributes we get from the referenced entity.

```json
{
    "name": "PersonInfo",
    "entity": {
        "operations": [
            {
                "$type": "alterTraits",
                "traitsToAdd": [
                    {
                        "traitReference": "means.requiredUpdateAtAge18"
                    },
                    {
                        "traitGroupReference": "AllRequiredUpdate"
                    }
                ],
                "traitsToRemove": [
                    "means.requiredUpdateAtAge60"
                ]
            }
        ],
        "source": {
            "operations": [
                {
                    "$type": "alterTraits",
                    "traitsToAdd": [
                        {
                            "traitReference": "means.requiredUpdateDate",
                            "arguments": [
                                {
                                    "name": "month",
                                    "value": "5"
                                },
                                {
                                    "name": "day",
                                    "value": "15"
                                }
                            ]
                        }
                    ],
                    "applyTo": [
                        "name"
                    ]
                }
            ],
            "source": "Person"
        }
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfo|Newly added traits or updated arguments|
|---|---|
|name|means.requiredUpdateDate(month: 5, day: 15) <br/>means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|
|address|means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|
|phoneNumber|means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|
|email|means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|

### Using the AlterTraits operation when extending an entity

If we have an entity that extends another entity, we can use AlterTraits to modify traits in the attributes that are inherited from the entity we are extending from.

Given an entity, Child, that extends from the Person entity:

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
                "operations": [
                    {
                        "$type": "alterTraits",
                        "traitsToAdd": [
                            {
                                "traitReference": "means.requiredUpdateAtAge18"
                            },
                            {
                                "traitGroupReference": "AllRequiredUpdate"
                            }
                        ],
                        "traitsToRemove": [
                            "means.requiredUpdateAtAge60"
                        ]
                    },
                    {
                        "$type": "alterTraits",
                        "traitsToAdd": [
                            {
                                "traitReference": "means.requiredUpdateDate",
                                "arguments": [
                                    {
                                        "name": "month",
                                        "value": "5"
                                    },
                                    {
                                        "name": "day",
                                        "value": "15"
                                    }
                                ]
                            }
                        ],
                        "applyTo": [
                            "email"
                        ]
                    }
                ],
                "runSequentially": true
    },
    "hasAttributes": []
}
```

The resulting resolved Child entity is:

|Child|Newly added traits or updated arguments|
|---|---|
|name|means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|
|address|means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|
|phoneNumber|means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|
|email|means.requiredUpdateDate(month: 5, day: 15) <br/>means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|


### Using the AlterTraits operation on an attribute group

We can use the [AddAttributeGroup](../../1.0om/api-reference/cdm/projections/addattributegroup.md) operation to place all the attributes referenced by the source entity attribute into an attribute group, then use the AlterTraits operation.

```json
{
    "name": "PersonInfo",
    "entity": {
        "operations": [
            {
                "$type": "alterTraits",
                "traitsToAdd": [
                    {
                        "traitReference": "means.requiredUpdateAtAge18"
                    },
                    {
                        "traitGroupReference": "AllRequiredUpdate"
                    }
                ],
                "traitsToRemove": [
                    "means.requiredUpdateAtAge60"
                ]
            }
        ],
        "source": {
            "operations": [
                {
                    "$type": "alterTraits",
                    "traitsToAdd": [
                        {
                            "traitReference": "means.requiredUpdateDate",
                            "arguments": [
                                {
                                    "name": "month",
                                    "value": "5"
                                },
                                {
                                    "name": "day",
                                    "value": "15"
                                }
                            ]
                        }
                    ]
                }
            ],
            "source": {
                "source": "Person",
                "operations": [
                    {
                        "$type": "addAttributeGroup",
                        "attributeGroupName": "PersonAttributeGroup"
                    }
                ]
            }
        }
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|Attribute Group Reference|Members in Attribute Group Reference|Newly added traits or updated arguments|
|---|---|---|
|PersonAttributeGroup| |means.requiredUpdateDate(month: 5, day: 15) <br/>means.requiredUpdateAtAge18 <br/>means.requiredUpdateAtAge30 <br/>means.requiredUpdateAtAge45|
||name||
||address||
||phoneNumber||
||email||

### Using the AlterTraits operation with wildcards

Constructing array or map type on an attribute is a good example to show how wildcards are used in arguments of traits. Below is an example of constructing an Array of entity attributes.

Make a certain number of copies of the entity attribute, and apply the trait [has.expansionInfo.list](../list-of-traits.md#hasexpansioninfolist) to each member attributes of the entity attribute. If multiple entity attributes and/or type attributes are expanded and renamed within one single entity, we would not able to easily differentiate each expanded attribute; therefore, This trait has parameters `expansionName`, `ordinal`, and `memberAttribute` to hold each attribute's unique info.

First, we can use the [ArrayExpansion](../../1.0om/api-reference/cdm/projections/arrayexpansion.md) operation to expand the entity attribute `Person`, the example below makes two copies of `Person`. Then we can the [RenameAttributes](../../1.0om/api-reference/cdm/projections/renameattributes.md) operation to rename each copy of the member attribute to avoid expanded attributes getting merge to one single attribute due to the same name. Finally, we can use the [AlterTraits](../../1.0om/api-reference/cdm/projections/altertraits.md) operation to apply the trait [has.expansionInfo.list](../list-of-traits.md#hasexpansioninfolist).

> **__Note:__** For detailed descriptions and use cases for map and array types refer to [this page](./map-and-array-types.md).

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
                                        "value": "{mo}"
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
|address_1|has.expansionInfo.list(twoPeople, 1, address)|
|phoneNumber_1|has.expansionInfo.list(twoPeople, 1, phoneNumber)|
|email_1|has.expansionInfo.list(twoPeople, 1, email)|
|name_2|has.expansionInfo.list(twoPeople, 2, name)|
|address_2|has.expansionInfo.list(twoPeople, 2, address)|
|phoneNumber_2|has.expansionInfo.list(twoPeople, 2, phoneNumber)|
|email_2|has.expansionInfo.list(twoPeople, 2, email)|
