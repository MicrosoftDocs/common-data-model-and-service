---
title: Operation Add Supporting Attribute Usage Guide | Microsoft Docs
description: Usage guide for the Add Supporting Attribute operation.
author: violivei

ms.reviewer: deonhe 
ms.topic: article
ms.date: 02/24/2020
ms.author: violivei
---

# Projection - Operation Add Supporting Attribute

## Overview

AddSupportingAttribute is a projection operation that adds a user-specified supporting attribute to the final resolved entity. As the name suggests, the newly created supporting attribute will be added in support of another attribute. The information about which the attribute’s in support of attribute is specified in the argument of the trait `is.addedInSupportOf`.

It is also important to notice that the supporting attribute created will be virtual and it will have the “is.virtual.attribute” applied to it. When working with data, be aware that virtual attributes might never have corresponding data values in an entity's partition or might only have data values if special measures are taken to manifest them.

A new directive `virtual` was introduced to facilitate the modeling of scenarios in which the virtual attributes are not wanted. It is a good practice to add a condition “virtual” when dealing with the add supporting attribute operation so they can be filtered out if not needed.

> **__Note:__** you can access the API reference for this operation on [this link](../../1.0om/api-reference/cdm/projections/addsupportingattribute.md).

> **__Note:__** The argument value of the `is.addedInSupportOf` is currently set to point to the last attribute that came from the source of the projections. This behavior mimics how resolution guidance works but it is likely to be refined in the upcoming releases.

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
            "name": "dateOfBirth",
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

### Using the AddSupportingAttribute operation on a data typed attribute

In some scenarios a data typed attribute can hold a list of constant values to which the attribute value is constrained. Let us first have a look at the attribute definition below.

```json
{
    "name": "priorityCode",
    "purpose": "hasA",
    "dataType": {
        "dataTypeReference": "listLookup",
        "appliedTraits": [
            {
                "traitReference": "does.haveDefault",
                "arguments": [
                    {
                        "entityReference": {
                            "explanation": "The constantValues below correspond to the attributes of the 'listLookupValues' entityShape which are: {languageTag, displayText, attributeValue, displayOrder}",
                            "entityShape": "listLookupValues",
                            "constantValues": [
                                [
                                    "en",
                                    "Low",
                                    "0",
                                    "0"
                                ],
                                [
                                    "en",
                                    "Normal",
                                    "1",
                                    "1"
                                ],
                                [
                                    "en",
                                    "High",
                                    "2",
                                    "2"
                                ]
                            ]
                        }
                    }
                ]
            }
        ]
    },
    "projection": {
        "operations": [
            {
                "$type": "addSupportingAttribute",
                "supportingAttribute": {
                    "explanation": "This attribute 'priorityCode_display' is added to the entity to provide the localized display text for the value of the listLookup attribute 'priorityCode'",
                    "name": "priorityCode_display",
                    "purpose": "hasA",
                    "dataType": "localizedDisplayText",
                    "isReadOnly": true
                }
            }
        ]
    }
}
```

On the example above, the `priorityCode` attribute is constrained to a set of possible values specified by the `listLookup` data type. Each entry on the listLookup table follows the structure `{languageTag, displayText, attributeValue, displayOrder}`. The priorityCode attribute holds the `attributeValue` but it might be also useful to have the `displayText` saved somewhere. For this purpose we can add a support attribute. In this case, we are adding the `priorityCode_display` to hold the display text. 

The resulting resolved priorityCode data typed attribute is:

||
|-|
|priorityCode|
|priorityCode_display|

### Using the AddSupportingAttribute operation on an entity attribute

We can use the AddSupportingAttribute operation to create a supporting attribute.

```json
{
    "name": "PersonInfo",
    "entity": {
        "source": "Person",
        "operations": [
            {
                "$type": "addSupportingAttribute",
                "supportingAttribute": {
                    "name": " age  ",
                    "dataType": "integer"
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
|dateOfBirth|
|address|
|phoneNumber|
|email|
|age|

### Using the AddSupportingAttribute operation when extending an entity

If we have an entity that extends another entity, we can use AddCountAttribute to create a supporting attribute.
Given an entity, NewPerson, that extends from the Person entity:

```json
{
    "entityName": "Child",
    "extendsEntity": {
        "source": "Person",
        "operations": [
            {
                "$type": "addSupportingAttribute",
                "supportingAttribute": {
                    "name": " age",
                    "dataType": "integer"
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
|dateOfBirth|
|address|
|phoneNumber|
|email|
|age|
