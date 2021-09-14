---
title: Operation Alter Traits Usage Guide | Microsoft Docs
description: Usage guide for for CdmOperationAlterTraits.
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

1. All the attributes from the source that are provided as input to the operation will be added to a list where each attribute's traits will be modified. It is possible to specify a `applyTo` property which is a list of attributes' traits to be changed. The attributes that are in the specified list will be applied the rest of steps and added to the final attribute list. If an attribute is not in the specified list, it is added to the final set of attributes without changes.

1. The traits or trait groups defined in `traitsToAdd` property will be added to each of the pending attributes. If `argumentsContainWildcards` property is defined and set to true, it checks all arguments from all traits and performs replacement. The format supports the wilds cards {a/A}, {m/M}, and {o}.
   * {a} will be replaced with the entity attribute name. If used in something other than an entity attribute, it will be replaced with an empty string.
   * {m} will be replaced with the current attribute name.
   * If {A} or {M} is used the first letter of the value will be capitalized.
   * {o} will be replaced with the index of the attribute after an array expansion. If the attribute wasn’t originated from an array expansion, it will be replaced with an empty string.

2. The traits or trait groups indicated in the `traitsToRemove` property will be removed in each of the pending attributes if they are found in the attribute's resolved traits.

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
                    "traitReference": "means.TraitG4",
                    "arguments": [
                        {
                            "name": "scale",
                            "value": "20"
                        }
                    ]
                }
            ]
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
},
{
    "traitName": "means.TraitG100",
    "extendsTrait": "means"
},
{
    "traitName": "means.TraitG200",
    "extendsTrait": "means"
},
{
    "traitName": "means.TraitG300",
    "extendsTrait": "means"
},
{
    "traitName": "means.TraitG400",
    "extendsTrait": "means"
},
{
    "traitName": "means.TraitG4",
    "extendsTrait": "means",
    "explanation": "Trait 4 with parameters",
    "hasParameters": [
        {
            "name": "precision",
            "explanation": "the total number of significant digits",
            "dataType": "integer",
            "direction": "both"
        },
        {
            "name": "scale",
            "explanation": "the number of digits to the right of the decimal place",
            "dataType": "integer",
            "direction": "both"
        }
    ]
},
{
    "traitGroupName": "JobTitleBase",
    "explanation": "Trait group that defines JobTitle base traits",
    "exhibitsTraits": [
        {
            "traitReference": "means.TraitG100"
        },
        {
            "traitReference": "means.TraitG200"
        },
        {
            "traitReference": "means.TraitG300"
        },
        {
            "traitReference": "means.TraitG400"
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
                                "traitReference": "means.TraitG100"
                            },
                            {
                                "traitGroupReference": "JobTitleBase"
                            }
                        ],
                        "traitsToRemove": [
                            "means.TraitG300"
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
|job|means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|

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
                        "traitReference": "means.TraitG100"
                    },
                    {
                        "traitGroupReference": "JobTitleBase"
                    }
                ],
                "traitsToRemove": [
                    "means.TraitG300"
                ]
            }
        ],
        "source": {
            "operations": [
                {
                    "$type": "alterTraits",
                    "traitsToAdd": [
                        {
                            "traitReference": "means.TraitG4",
                            "arguments": [
                                {
                                    "name": "precision",
                                    "value": "5"
                                },
                                {
                                    "name": "scale",
                                    "value": "15"
                                }
                            ]
                        }
                    ],
                    "applyTo": [
                        "name",
                        "age"
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
|name|means.TraitG4(precision: 5, scale:15) <br/>means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
|age|means.TraitG4(precision: 5, scale:15) <br/>means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
|address|means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
|phoneNumber|means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
|email|means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|

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
                                "traitReference": "means.TraitG100"
                            },
                            {
                                "traitGroupReference": "JobTitleBase"
                            }
                        ],
                        "traitsToRemove": [
                            "means.TraitG300"
                        ]
                    },
                    {
                        "$type": "alterTraits",
                        "traitsToAdd": [
                            {
                                "traitReference": "means.TraitG4",
                                "arguments": [
                                    {
                                        "name": "precision",
                                        "value": "5"
                                    },
                                    {
                                        "name": "scale",
                                        "value": "15"
                                    }
                                ]
                            }
                        ],
                        "applyTo": [
                            "age"
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
|name|means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
|age|means.TraitG4(precision: 5, scale:15) <br/>means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
|address|means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
|phoneNumber|means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
|email|means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|


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
                        "traitReference": "means.TraitG100"
                    },
                    {
                        "traitGroupReference": "JobTitleBase"
                    }
                ],
                "traitsToRemove": [
                    "means.TraitG300"
                ]
            }
        ],
        "source": {
            "operations": [
                {
                    "$type": "alterTraits",
                    "traitsToAdd": [
                        {
                            "traitReference": "means.TraitG4",
                            "arguments": [
                                {
                                    "name": "precision",
                                    "value": "5"
                                },
                                {
                                    "name": "scale",
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
|PersonAttributeGroup| |means.TraitG4(precision: 5, scale:15) <br/>means.TraitG100 <br/>means.TraitG200 <br/>means.TraitG400|
||name||
||age||
||address||
||phoneNumber||
||email||
