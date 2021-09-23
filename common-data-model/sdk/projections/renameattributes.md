---
title: Operation Rename Attributes Usage Guide | Microsoft Docs
description: Usage guide for the Rename Attributes operation.
author: violivei
ms.service: common-data-model
ms.reviewer: v-iap 
ms.topic: article
ms.date: 02/24/2021
ms.author: violivei
---

# Projection - Operation Rename Attributes

## Overview

RenameAttributes is a projection operation that renames a specified set of attributes from the source, which can either be an entity reference or another projection. This operation will work as follows:  

1. All the resolved attributes from the source that are provided as input to the operation.
1. The attributes are renamed following the “renameFormat” property provided. The format supports the wildcards {a/A}, {m/M}, {mo/Mo}, and {o}.
   * {a} will be replaced with the attribute name of the projection owner (which is the attribute to call the projection operation). If the projection owner is not a type attribute or an entity attribute, it will be replaced with an empty string.
   * {m} will be replaced with the resolved name of the current member attribute without changing the case of the text.
   * {mo} will be replaced with the original name of the current member attribute without changing the case of the text.
   * If {A}, {M}, {Mo} is used the first letter of the value will be capitalized.
   * {o} will be replaced with the index of the attribute after an array expansion. If the attribute wasn’t originated from an array expansion, it will be replaced with an empty string.
1. All the attributes will be renamed following the specified “renameFormat” by default. It is possible to specify a "applyTo" property which is a list of attributes to be renamed. The attributes that are in the specified list are renamed and added to the attribute list. If an attribute is not in the rename list, it is added to the set of attributes without changes.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/renameattributes.md).

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

### Using the RenameAttributes operation on an entity attribute

If we have an entity attribute, we can use RenameAttributes to rename all the attributes we get from the referenced entity. In this example {a} will be replaced with "PersonInfo" and {M} will be replaced with each attribute name with the first letter capitalized.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "renameAttributes",
                "renameFormat": "{a}{M}"
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfo|
|-|
|PersonInfoName|
|PersonInfoAge|
|PersonInfoAddress|
|PersonInfoPhoneNumber|
|PersonInfoEmail|

### Using the RenameAttributes operation when extending an entity

If we have an entity that extends another entity, we can use RenameAttributes to rename all the attributes that are inherited from the entity we are extending from.

Given an entity, Child, that extends from the Person entity:

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "renameAttributes",
                "renameFormat": "child{M}"
            }
        ]
    },
    "hasAttributes": []
}
```

The resulting resolved Child entity is:

|Child|
|-|
|childName|
|childAge|
|childAddress|
|childPhoneNumber|
|childEmail|

### Mixing strings and wildcards in the rename format

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "renameAttributes",
                "renameFormat": "New{M}"
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfo|
|-|
|NewName|
|NewAge|
|NewAddress|
|NewPhoneNumber|
|NewEmail|

### Renaming a specific list of attributes

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "renameAttributes",
                "renameFormat": "{a}{M}",
                "applyTo": [
                    "age",
                    "email"
                ]
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfo|
|-|
|name|
|PersonInfoAge|
|address|
|phoneNumber|
|PersonInfoEmail|

### Using the RenameAttributes operation with a condition

We can have a condition that must evaluate to true in order for the operations in a projection to execute. This means that we can have two different scenarios where a condition is evaluated to true in one (causing the RenameAttributes operation to execute), and the condition is evaluated to false in another (preventing the RenameAttributes operation from executing).
We have the NewPerson entity with an entity attribute definition again. Given the following projection with a condition stating that the RenameAttributes operation should only run when the resolution directives are "referenceOnly":

```json
{
    "name": "PersonInfo",
    "entity": {
        "condition": "referenceOnly",
        "source": "Person",
        "operations": [
            {
                "$type": "renameAttributes",
                "renameFormat": "{a}{M}"
            }
        ]
    }
}
```

We would get either one of the resulting resolved PersonInfo entities, depending on if the condition evaluated to true or not:

|Condition = true <br /> (resolution directive = “referenceOnly”)|Condition = false <br /> (resolution directive != “referenceOnly”)|
|-|-|
|PersonInfoName|name
|PersonInfoAge|age
|PersonInfoAddress|address
|PersonInfoPhoneNumber|phoneNumber
|PersonInfoEmail|email

### Using multiple RenameAttributes operations in a single projection

All the operations in a single projection are given the same set of inputs, so while the operations are run sequentially, they work independently on the input. This means that if we have two RenameAttributes operations in a projection, the final output will be the result of both RenameAttributes’ outputs merged together.
If we want an RenameAttributes to build on top of another RenameAttributes result, we would need to use nested projections like we did in the previous use case. The other option is to set the `runSequentially` flag on the projection.

Given the following projection with two sequential RenameAttributes operations:

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "runSequentially": <bool>,
        "operations": [
            {
                "$type": "renameAttributes",
                "renameFormat": "yearsOld", 
                "applyTo": [ 
                    "age"
                ] 
            },
            {
                "$type": "renameAttributes",
                "renameFormat": "homePlace", 
                "applyTo": [ 
                    "address"
                ] 
            }
        ]
    }
}
```

If `runSequentially = false` (default behavior)

|Input|After operation #1|After operation #2|Output|
|-|-|-|-|
|name|name|name|name
|age|yearsOld|age|yearsOld
|address|address|homePlace|address
|phoneNumber|phoneNumber|phoneNumber|phoneNumber
|email|email|email|email
||||age|
||||homePlace|

If `runSequentially = true`

|Input|After operation #1|After operation #2|Output|
|-|-|-|-|
|name|name|name|name
|age|yearsOld|yearsOld|yearsOld
|address|address|homePlace|homePlace
|phoneNumber|phoneNumber|phoneNumber|phoneNumber
|email|email|email|email

### Using the RenameAttributes operation on an attribute group

If we have an entity that contains an attribute group and we use this entity as an entity attribute, we can then use RenameAttributes on it.

Given the Person entity, now with an attribute group reference:

```json
{
    "entityName": "Person",
    "hasAttributes": [
        {
            "attributeGroupReference": {
                "attributeGroupName": "someGroup",
                "members": [
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
        }
    ]
}
```

We can use an RenameAttributes operation the same way as before.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "renameAttributes",
                "renameFormat": "{a}{M}"
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfo|
|-|
|PersonInfoName|
|PersonInfoAge|
|PersonInfoAddress|
|PersonInfoPhoneNumber|
|PersonInfoEmail|
