---
title: Operation Replace as Foreign Key Usage Guide | Microsoft Docs
description: Usage guide for the Replace as Foreign Key operation.
author: violivei

ms.reviewer: v-iap 
ms.topic: reference 
ms.date: 02/24/2021
ms.author: violivei
---

# Projection - Operation Replace as Foreign Key

## Overview

ReplaceAsForeignKey is a projection operation that creates a foreign key that references one of the source attributes. This operation receives a set of attributes as input and outputs a single foreign key attribute, which is specified on the `replaceWith` property. A `is.linkedEntity.identifier` trait is added to the resulting attribute. The argument of this trait has information about the source attribute that is referenced by this foreign key.

```json
{
    "traitReference": "is.linkedEntity.identifier",
    "arguments": [
        {
            "entityReference": {
                "entityShape": "entityGroupSet",
                "constantValues": [
                    [
                        "<Path to entity>",
                        "<Attribute name>",
                        "<Relationship name>"
                    ]
                ]
            }
        }
    ]
}
```

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/replaceasforeignkey.md).

> **__Note:__** The foreign key attributes are used by the Object Model to calculate relationships.

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

### Using the ReplaceAsForeignKey operation on an entity attribute

If we have an entity attribute, we can use ReplaceAsForeignKey to create a foreign key attribute.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "replaceAsForeignKey",
                "reference": "name",
                "replaceWith": {
                    "name": "personFK",
                    "dataType": "entityId"
                }
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfo|
|-|
|personFK|

The `is.linkedEntity.identifier` trait on the `personFK` attribute looks like the following:

```json
{
    "traitReference": "is.linkedEntity.identifier",
    "arguments": [
        {
            "entityReference": {
                "entityShape": "entityGroupSet",
                "constantValues": [
                    [
                        "Person.cdm.json/Person",
                        "name",
                        "PersonInfo_Person"
                    ]
                ]
            }
        }
    ]
}
```

### Using the ReplaceAsForeignKey operation when extending an entity

If we have an entity that extends another entity, we can use ReplaceAsForeignKey to create a foreign key attribute.

Given an entity, Child, that extends from the Person entity:

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "replaceAsForeignKey",
                "reference": "name",
                "replaceWith": {
                    "name": "personFK",
                    "dataType": "entityId"
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
|personFK|

### Using the ReplaceAsForeignKey operation to create a multi part foreign key

On the examples above, the foreign keys created are identified by one attribute only. In some cases one attribute alone is not capable of uniquely identifying a relationship, for example there might be multiple people with the same name. For these cases, we can create a relationship that is composed by multiple attributes as below.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "replaceAsForeignKey",
                "reference": "name",
                "replaceWith": {
                    "name": "nameFK",
                    "dataType": "entityId"
                }
            },
            {
                "$type": "replaceAsForeignKey",
                "reference": "address",
                "replaceWith": {
                    "name": "addressFK",
                    "dataType": "entityId"
                }
            }
        ]
    }
}
```

The resulting resolved PersonInfo entity typed attribute is:

|PersonInfo|
|-|
|nameFK|
|addressFK|

Let us have a look at the `is.linkedEntity.identifier` trait on both these resulting attributes.

First `nameFK`:

```json
{
    "traitReference": "is.linkedEntity.identifier",
    "arguments": [
        {
            "entityReference": {
                "entityShape": "entityGroupSet",
                "constantValues": [
                    [
                        "Person.cdm.json/Person",
                        "name",
                        "PersonInfo_Person"
                    ]
                ]
            }
        }
    ]
}
```

Now `addressFK`:

```json
{
    "traitReference": "is.linkedEntity.identifier",
    "arguments": [
        {
            "entityReference": {
                "entityShape": "entityGroupSet",
                "constantValues": [
                    [
                        "Person.cdm.json/Person",
                        "address",
                        "PersonInfo_Person"
                    ]
                ]
            }
        }
    ]
}
```

By looking at the two traits above, you can see that both the relationship names are the same `PersonInfo_Person`. This is an indicator that these attributes combined make up the relationship foreign key.

### Using the ReplaceAsForeignKey operation to create a polymorphic relationship

For this example, we will use another entity called `ContactKinds` that has three entity attributes pointing to `Email`, `Phone` and `Social`.

```json
{
    "entityName": "ContactKinds",
    "hasAttributes": [
        {
            "name": "emailKind",
            "entity": "Email"
        },
        { 
            "name": "phoneKind", 
            "entity": "Phone"
        },
        {
            "name": "socialKind",
            "entity": "Social"
        }
    ]
}
```

|Email|Phone|Social|
|-|-|-|
|emailId|phoneId|socialId|
|address|number|account|
|isPrimary|isPrimary|isPrimary|

This entity defines three different methods that a customer can be contact at. We want to create an entity attribute that is a foreign key to one of email, phone or social. To achieve this goal, we will use the ReplaceAsForeignKey along with [CombineAttributes](combineattributes.md). Note that because `ContactKinds` is a polymorphic entity we need to set the `isPolymorphicSource` property to true.

```json
{
    "name": "ContactAt",
    "isPolymorphicSource": true,
    "entity": {
        "source": "ContactKinds",
        "runSequentially": true,
        "operations": [
            {
                "$type": "combineAttributes",
                "select": [ "emailId", "phoneId", "socialId" ],
                "mergeInto": {
                    "name": "contactAtId",
                    "dataType": "entityId"
                }
            },
            {
                "$type": "replaceAsForeignKey",
                "reference": "contactAtId",
                "replaceWith": {
                    "name": "contactAtFK",
                    "dataType": "entityId"
                }
            },
            {
                "$type": "addTypeAttribute",
                "typeAttribute": {
                    "name": "contactAtType",
                    "dataType": "integer"
                }
            }
        ]
    }
}
```

The resulting resolved ContactAt entity typed attribute is:

|ContactAt|
|-|
|contactAtFK|
|contactAtType|

__**NOTE:**__ in this case the attribute, `contactAtFK` holds a foreign key to email, phone or social. We also used a [AddTypeAttribute](addtypeattribute.md) operation to create an attribute that is used to specify which entity `contactAtFK` is pointing to per-record. Adding the type attribute is not required, but useful.
