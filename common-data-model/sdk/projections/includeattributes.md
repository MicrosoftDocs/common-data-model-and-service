---
title: Operation Include Attributes Usage Guide | Microsoft Docs
description: Usage guide for the Include Attributes operation.
author: violivei
ms.service: common-data-model
ms.reviewer: v-iap 
ms.topic: article
ms.date: 02/24/2021
ms.author: violivei
---

# Projection - Operation Include Attributes

## Overview

IncludeAttributes is a projection operation that selects a specified set of attributes from the source, which can either be an entity reference or another projection. This operation will work as follows:

1. All the resolved attributes from the source are provided as input to the operation.
1. Only the attributes that are listed in the specified set of attributes to include are taken from the input and added to the output. If an empty list of attributes to include is provided, no attribute from the input will be passed to the output resulting in an empty set.
1. A filtered set of attributes is returned.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/includeattributes.md).

> **__Note:__** The selected attributes are ordered as given in the list.

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

### I can use a IncludeAttributes operation on an entity attribute

If we have an entity attribute, we can use IncludeAttributes to include certain attributes we get from the referenced entity.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "includeAttributes",
                "includeAttributes": [
                    "name",
                    "address",
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
|address|
|email|

### I can use an IncludeAttributes operation when extending an entity

If we have an entity that extends another entity, we can use IncludeAttributes to select certain attributes that are inherited from the entity we are extending from.

Given an entity, Child, that extends from the Person entity:

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "includeAttributes",
                "includeAttributes": [
                    "name",
                    "age",
                    "address"
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
|address|

### I can use an IncludeAttributes operation to reorder the source attributes

The order of the attributes in the output is given by the order they are specified on the IncludeAttributes operation. This characteristic can be used to reorder the attributes from the source entity.

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "includeAttributes",
                "includeAttributes": [
                    "address",
                    "phoneNumber",
                    "email",
                    "name",
                    "age"
                ]
            }
        ]
    },
    "hasAttributes": []
}
```

|Child|
|-|
|address|
|phoneNumber|
|email|
|name|
|age|

### I can use multiple IncludeAttributes operations

We can have multiple IncludeAttributes operations on the same projection.

Given the following nested projection:

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "runSequentially": <bool>,
        "operations": [
            {
                "$type": "includeAttributes",
                "includeAttributes": [
                    "address",
                    "email",
                ]
            },
            {
                "$type": "includeAttributes",
                "includeAttributes": [
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

If `runSequentially` is false, all the operations in a single projection are given the same set of inputs, so while the operations are run sequentially, they work independently on the input. This means that if we have two IncludeAttributes operations in a projection, the final output will be the result of both IncludeAttributes’ outputs merged together resulting on the entity typed attribute below.

|Input|After operation #1|Output|
|-|-|-|
|name|address|address|
|age|email|email|
|address||name|
|phoneNumber||age|
|email|

If `runSequentially` is false, each operation is given the output of the previous operation. The second IncludeAttributes operation receives just "address" and "email" as input resulting on the entity typed attribute below.

|Input|After operation #1|Output|
|-|-|-|
|name|address|address|
|age|email|
|address|
|phoneNumber|
|email|
