---
title: Operation Add Type Usage Guide | Microsoft Docs
description: Usage guide for the Add Type Attribute operation.
author: violivei

ms.reviewer: v-iap 
ms.topic: article
ms.date: 02/24/2021
ms.author: violivei
---

# Projection - Operation Add Type Attribute

## Overview

AddTypeAttribute is a projection operation that adds a user-specified type attribute to the final resolved entity. It is generally used after a [CombineAttributes](combineattributes.md) operation to create a type attribute that indicates the type that matches one of the entities from a polymorphic source, but can also be used by itself. Think of it like the $type property in a JSON object.

For example:
We have an Account entity with the attribute "accountId" and a Contact entity with the attribute "contactId". Using CombineAttributes, we merge "accountId" and "contactId" into "customerId". We can then use AddTypeAttribute to create a "customerType" type attribute that is used to indicate whether "customerId" is an Account or a Contact type.

Because of this, the created type attribute is often an "entityName" data type. It will also have the trait `is.linkedEntity.name`.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/addtypeattribute.md).

## Examples

The examples below refer to the `ContactKinds` entity as defined here.

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

### Using the AddTypeAttribute operation on an entity attribute

If we have an entity attribute, we can use AddTypeAttribute to add a type attribute. We can have an entity, Customer, that contains the following entity attribute definition (called contactAt) with a CombineAttributes operation (using ContactKinds as the source) that merges "emailId", "phoneId", and "socialId" into "contactId":

```json
{
    "name": "contactAt",
    "isPolymorphicSource": true,
    "entity": {
        "operations": [
            {
                "$type": "addTypeAttribute",
                "typeAttribute": {
                    "name": "contactType",
                    "dataType": "entityName",
                    "appliedTraits": []
                }
            }
        ],
        "source": {
            "operations": [
                {
                    "$type": "combineAttributes",
                    "select": ["emailId", "phoneId", "socialId"],
                    "mergeInto": {
                        "name": "contactId",
                        "dataType": "entityId"
                    }
                }
            ],
            "source": "ContactKinds"
        }
    }
}

```

The resulting resolved contactAt entity typed attribute is:

|contactAt|
|-|
|address|
|isPrimary|
|number|
|account|
|contactId|
|contactType|

### Using the AddTypeAttribute operation when extending an entity

If we have an entity that extends another entity, we can use AddTypeAttribute to add a type attribute.

Given the entity, Customer, that extends from the ContactKinds entity:

```json
{
    "entityName": "Customer",
    "extendsEntity": {
        "operations": [
            {
                "$type": "addTypeAttribute",
                "typeAttribute": {
                    "name": "contactType",
                    "dataType": "entityName",
                    "appliedTraits": []
                }
            }
        ],
        "source": {
            "operations": [
                {
                    "$type": "combineAttributes",
                    "select": [ "emailId", "phoneId", "socialId" ],
                    "mergeInto": {
                        "name": "contactId",
                        "dataType": "entityId"
                    }
                }
            ],
            "source": "ContactKinds"
        }
    },
    "hasAttributes": []
}
```

The resulting resolved Customer entity is:

|Customer|
|-|
|address|
|isPrimary|
|number|
|account|
|contactId|
|contactType|

### Using the AddTypeAttribute operation by itself

```json
{
    "name": "contactAt",
    "entity": {
        "source": "ContactKinds",
        "operations": [
            {
                "$type": "addTypeAttribute",
                "typeAttribute": {
                    "name": "someType",
                    "dataType": "entityName"
                }
            }
        ]
    }
}
```

The resulting resolved contactAt entity typed attribute is:

|contactAt|
|-|
|emailId|
|address|
|isPrimary|
|phoneId|
|number|
|socialId|
|account|
|someType|
