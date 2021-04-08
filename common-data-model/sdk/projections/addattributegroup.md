---
title: Operation Add Attribute Group Usage Guide | Microsoft Docs
description: Usage guide for the Add Attribute Group operation.
author: violivei
ms.service: common-data-model
ms.reviewer: v-iap 
ms.topic: article
ms.date: 02/24/2021
ms.author: violivei
---

# Projection - Operation Add Attribute Group

## Overview

AddAttributeGroup is a projection operation that groups all the attributes from the source into an attribute group. This operation will work as follows:  

1. All the resolved attributes from the source are provided as input to the operation.
1. An attribute group is created with the name supplied by the property "attributeGroupName".
1. The attributes received as input are added to the newly created attribute group.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/addattributegroup.md).

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

### I can use a AddAttributeGroup operation on an entity attribute

We can use the AddAttributeGroup operation to place all the attributes referenced by the source entity attribute into an attribute group.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "addAttributeGroup",
                "attributeGroupName": "PersonInfoGroup"
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfoGroup||
||name|
||age|
||address|
||phoneNumber|
||email|

### I can use an AddAttributeGroup operation when extending an entity

If we have an entity that extends another entity, we can use AddAttributeGroup to add the attributes of the base entity into an attribute group in the extended entity.
Given an entity, Child, that extends the Person entity:

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "addAttributeGroup",
                "attributeGroupName": "ChildGroup"
            }
        ]
    },
    "hasAttributes": []
}
```

The resulting resolved Child entity is:

|ChildGroup||
||name|
||age|
||address|
||phoneNumber|
||email|

### I can use multiple AddAttributeGroup operations

Using multiple addAttributeGroup operations will result in an attribute group being created inside another attribute group.

```json
{
    "name": "PersonInfo",
    "entity": {
        "operations": [
            {
                "$type": " AddAttributeGroup",
                "attributeGroupName": "OuterGroup"
            }
        ],
        "source": {
            "operations": [
                {
                    "$type": " AddAttributeGroup",
                    "attributeGroupName": "InnerGroup"
                }
            ],
            "source": "Person"
        }
    }
}
```

The resulting resolved Child entity is:

|OuterGroup|||
||InnerGroup||
|||name|
|||age|
|||address|
|||phoneNumber|
|||email|
