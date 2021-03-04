---
title: Operation Exclude Attributes Usage Guide | Microsoft Docs
description: Usage guide for the Exclude Attributes operation.
author: violivei
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 24/02/2020
ms.author: violivei
---

# Projection - Operation Exclude Attributes

## Overview

ExcludeAttributes is a projection operation that filters out a specified set of attributes from the source, which can either be an entity reference or another projection. This operation will work as follows:

1. All the resolved attributes from the source are provided as input to the operation.
1. Only the attributes that are not listed in the specified set of attributes to exclude are taken from the input and added to the output. If an empty list of attributes to filter is provided, all the attributes from the input will be passed to the output.
1. A filtered set of attributes is returned.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/excludeattributes.md).

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

### I can use a ExcludeAttributes operation on an entity attribute

If we have an entity attribute, we can use ExcludeAttributes to exclude certain attributes we get from the referenced entity.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "excludeAttributes",
                "excludeAttributes": [
                    "address",
                    "phoneNumber",
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
|age|

### I can use an ExcludeAttributes operation when extending an entity

If we have an entity that extends another entity, we can use ExcludeAttributes to filter out certain attributes that are inherited from the entity we are extending from.

Given an entity, Child, that extends from the Person entity:

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "excludeAttributes",
                "excludeAttributes": [
                    "address",
                    "email"
                ]
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
|phoneNumber|

### I can use multiple ExcludeAttributes operations

We can have multiple ExcludeAttributes operations on the same projection.

Given the following nested projection:

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "runSequentially": <bool>,
        "operations": [
            {
                "$type": "excludeAttributes",
                "excludeAttributes": [
                    "address",
                    "email",
                ]
            },
            {
                "$type": "excludeAttributes",
                "excludeAttributes": [
                    "name",
                    "age",
                    "address"
                ]
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute depends on the value set to the `runSequentially` flag on the projection level.

If `runSequentially` is false, all the operations in a single projection are given the same set of inputs, so while the operations are run sequentially, they work independently on the input. This means that if we have two ExcludeAttributes operations in a projection, the final output will be the result of both ExcludeAttributes’ outputs merged together resulting on the entity typed attribute below.

|PersonInfo|
|-|
|name|
|age|
|address|
|phoneNumber|
|email|

If `runSequentially` is false, each operation is given the output of the previous operation resulting on the entity typed attribute below.

|PersonInfo|
|-|
|phoneNumber|
