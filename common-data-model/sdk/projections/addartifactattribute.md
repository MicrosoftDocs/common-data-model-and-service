---
title: Operation Add Artifact Attribute Usage Guide | Microsoft Docs
description: Usage guide for CdmOperationAddArtifactAttribute.
author: llawwaii

ms.reviewer: v-iap 
ms.topic: reference 
ms.date: 09/03/2021
ms.author: weiluo
---

# Projection - Operation Add Artifact Attribute

## Overview

AddArtifactAttribute is a projection operation that adds a user-specified attribute (currently, only supports type attribute) to the final resolved entity. This operation will work as follows:  

1. All the resolved attributes from the source that are provided as input to the operation.
1. The attribute received as argument to the operation are added to the input attribute list. If the property "insertAtTop" is not set, or it is false, the attribute will be added at the bottom of the list. Otherwise, it is added at the top of the list.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/addartifactattribute.md).

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

### Using the AddArtifactAttribute operation on an entity attribute

If we have an entity attribute, we can use AddArtifactAttribute to insert a type attribute to the attribute list that we get from the referenced entity.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "addArtifactAttribute",
                "newAttribute": {
                    "name": "newName",
                    "dataType": "string"
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
|newName|

### Using the AddArtifactAttribute operation when extending an entity

If we have an entity that extends another entity, we can use AddArtifactAttribute to insert a type attribute to the attribute list that are inherited from the entity we are extending from.

Given an entity, Child, that extends from the Person entity:

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "addArtifactAttribute",
                "newAttribute": {
                    "name": "newName",
                    "dataType": "string"
                }
            }
        ]
    },
    "hasAttributes": []
}
```

The resulting resolved Child entity is:

|Child|
|-|
|name|
|age|
|address|
|phoneNumber|
|email|
|newName|

### Using the AddArtifactAttribute operation on a type attribute

We can use the AddArtifactAttribute operation to insert an attribute in an entity. Let us first have a look at the entity definition below.

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
            "name": "nickname",
            "dataType": "string",
            "projection": {
                "operations": [
                    {
                        "$type": "addArtifactAttribute",
                        "newAttribute": {
                            "name": "newNickname",
                            "dataType": "string"
                        },
                        "insertAtTop": true
                    }
                ]
            }
        }
    ]
}
```

On the example above, the `nickname` attribute is the second attribute in the entity. When the `newNickname` attribute is added to the attribute list by the AddArtifactAttribute operation, it is placed before `nickname` and becomes the new second attribute because the `insertAtTop` flag is set to true.

The resulting resolved PersonInfo entity is:

|PersonInfo|
|-|
|legalName|
|newNickname|
|nickname|

