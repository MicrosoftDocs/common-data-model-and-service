---
title: Trait concepts and use cases | Microsoft Docs
description: Trait concepts and use cases - a detailed overview of traits for representing dataTypes
author: msftman
ms.service: common-data-model
ms.reviewer: matgos
ms.topic: article
ms.date: 11/16/2020
ms.author: jeffbern
---

# Trait concepts and use cases

Traits are the fundamental mechanism in the Common Data Model metadata grammar for describing the data format, semantic meaning, and specifications for entities, attributes and other objects, such as partitions or manifests. This article explains the following concepts and use cases of Common Data Model traits.

- How Common Data Model standard traits are described
- How Common Data Model standard traits represent the format of stored data values
- Translation using the Common Data Model SDK
- Equivalence of traits when converting to or from the previous representation of Common Data Model folders (referred to as the model.json file format)

For reference, the current form for representing Common Data Model metadata is called the *manifest* format. The Common Data Model manifest format encompasses several critical enhancements over the more limited *model.json* format. For more information, see [Common Data Model Manifest object](https://docs.microsoft.com/common-data-model/sdk/manifest).

For detailed information about the model.json document format, see [Metadata file for the Common Data Model](https://docs.microsoft.com/common-data-model/model-json).

## What are traits

Traits are annotation objects that are an expression of semantic meaning. Traits can hold a set of named argument values. When an entity is in the *resolved* form, that is, when it is being used to map out the specific layout of data records, an entity object can be as little as a named collection of references to traits, along with a list of attributes where each attribute is simply a named collection of references to traits.

For example:

```json
{
  "definitions": [
  {
    "entityName": "Device",
    "displayName": "Device",
    "description": "A device that is an application or browser instance",
    "version": "0.9",
    "hasAttributes": [
      {
        "name": "manufacturer",
        "appliedTraits": [
          "is.dataFormat.character",
          "is.dataFormat.array"
        ],
        "displayName": "Manufacturer",
        "description": "The name of the organization who owns the design and creation…",
        "dataFormat": "String"
      },
      {
```
</br>

Notice that there are some properties on the entity and attributes that do not look like trait references. However, the helper properties such as *displayName*, *description* and *dataFormat*, are representing hidden trait values. These traits still exist in the Common Data Model object model and can be accessed as traits instead of property values.

A string such as "means.measurement.distance.pixels" are referred to as *trait references* because each of them corresponds to a trait object that is defined (perhaps in another document) in the Common Data Model system. Using the Common Data Model object model, these strings are actually TraitReference objects that can be queried to fetch the underlying TraitDefinition.

The example below (using the code example above) shows what trait definitions look like in a Common Data Model definition document.

![Common Data Model definition document](../media/sdk/trait-concepts-and-use-cases/traits-img1.png) 

Note in this example:

1. By convention, trait names describe the meaning and domain of the trait by using a *word.word.word* format. As part of the convention, the first word is either a namespace identifier (for custom extensions) or the verb "is", "does", "has" or "means".

1. A best practice is to give traits an explanation that makes it clear when or where the traits should be applied.

1. Traits can be defined as extensions of a base trait. This creates an inheritance hierarchy that allows for mixing specific and general expressions of meaning. For example, if *means.measurement.distance* extends *means.measurement*, and *means.measurement.temperature* also extends *means.measurement*, then any object that exhibits either of the more specific traits for distance or temperature can also be seen to have the *means.measurement* trait. This is useful for searching or grouping.

1. Traits can define a set of named parameters that give additional details about the trait or a setting.

1. Trait parameters have the following qualities:

    - a name and explanation
    - can be required or optional
    - can have default values
    - have an expected data type

1. The *dataType* for a trait parameter can be any of the data types defined in the Common Data Model system.

1. In this example, because the base trait parameter for "units"' is set to "Meters", when any other object has this *means.measurement.distance.meters* trait applied to it, the units argument will always be "Meters".

1. A defined trait, such as *means.measurement*, can then be applied or used by making a reference to the defined trait.

    - An example of a simple trait reference is the use of *means.measurement* as the base or "extendedTrait" for the *means.measurement.distance* trait.

    - A structured reference to a trait, as in the object shown which describes the base trait for *means.measurement.distance.meters*, allows for the setting of trait arguments for that specific use of the trait.

    - The supplied trait arguments correspond to the defined trait parameters, including the trait parameters that may be inherited from a base trait.

    - A trait argument can be a simple string value. This assumes that values are set on parameters in the order the values are defined, starting from the deepest base trait on up.

    - Another way to specify trait arguments is with name and value pairs in an object.

    - Trait arguments for simple values are always expressed as strings, even if the trait parameter has a dataType such as integer or boolean.

    - Trait argument values for complex types, such as attributes or entities, can be objects.

    - Maintaining a standard naming convention simplifies collections of traits into understandable and standard semantic groups. Standard semantics include: 

        | Trait base collection | Description | Example |
        |-----------------------|-------------|-------------|
        | is | The actual value, format or shape of the data object or attribute. | The *is.dataFormat.array* attribute is a string with an array of characters. |
        | does | How the data object or attribute affects or contributes to another attribute. | The *does.haveDefault* attribute indicates if a default value is required, present or applied. |
        | has | Describes the characteristic or shape of an attribute. | The *has.format("L, F M")* attribute specifies the acceptable data format, in this case **L**astname **,** **F**irstname **M**iddlename. |
        | means | What the data object or attribute relates to or represents. | The *means.location.city* attribute is the location having a city name.|

## Trait specifics

| Property / Method | Description |
|-------------------|-----------------|
| traitName | The name of the trait. |
| extendsTrait | A trait reference to a trait of which this trait extends. This trait will inherit all parameters from the base trait. |
| parameters | A list of parameters (see below) for holding values or settings with the trait. |
| elevated | Beyond the scope of this document. |

## Trait parameters

| Property / Method | Description |
|-------------------|----------------|
| name | A unique name for the parameter. This name can be used to set argument values when referencing traits. |
| defaultValue | A default value for the parameter that is used if no corresponding arguments are set. |
| dataTypeRef | A Common Data Model dataType that describes the meaning and shape of the values that can be represented by this parameter. |
| required | If True, the object model will report an error if a trait is referenced and no value has been set as an argument for this trait. |

## Ascribing traits (overriding exhibited trait behavior)

Traits can be part of the definition of an object or can be attached to a particular reference to an object.

When an entity or other object is defined in Common Data Model, part of its definition can be the set of traits that the object will exhibit. This means that any time the object is used by reference, it will have those traits.

In attribute definitions and in the places where a Common Data Model object is used by reference, additional traits may be applied. These additional traits will sit along with the object's exhibited traits. Applying a trait on an object reference overrides the parameter values of the identically named trait that is exhibited by the object.

## Trait data types and data format

Common Data Model traits have dataTypes, a dataFormat property, and a relationship to the older model.json dataType enumeration.

There are a set of Common Data Model traits that express aspects of the format of a data value in a storage-agnostic way.

| Trait Name | Description |
|------------|---------------|
| is.dataFormat.integer | A whole number |
| is.dataFormat.floatingPoint | An approximation of a number with optional whole, fractional and power of 10 parts |
| is.dataFormat.character | An encoded text character |
| is.dataFormat.byte | A byte of data |
| is.dataFormat.boolean | True or False |
| is.dataFormat.numeric | A fixed precision floating point number that may have precision and scale |
| is.dataFormat.time | A representation of a time of day |
| is.dataFormat.date | A representation of a calendar date |
| is.dataFormat.timeOffset | A representation of a timezone offset |
| is.dataFormat.guid | A representation of a 128 bit globally unique identifier |
| is.dataFormat.big | A modifier, indicates the *doubled* size of some numeric values |
| is.dataFormat.small | A modifier, indicates the *half* size of some numeric values |
| is.dataFormat.array | A modifier, the base format is repeated sequentially |

### dataType

A Common Data Model *dataType* is an object that represents a collection of traits. All dataTypes should indicate the dataFormat traits but can also add additional semantic information.

The primitive dataTypes in Common Data Model are:

| dataType name | Traits |
|---------------|----------|
| integer | is.dataFormat.integer |
| float | is.dataFormat.floatingPoint |
| decimal | is.dataFormat.numeric.shaped (extends is.dataFormat.numeric) |
| boolean | is.dataFormat.boolean |
| byte | is.dataFormat.byte |
| binary | is.dataFormat.byte, is.dataFormat.array |
| char | is.dataFormat.character, is.dataFormat.array |
| string | is.dataFormat.character, is.dataFormat.array |
| smallInteger : extends 'integer' | is.dataFormat.integer, is.dataFormat.small |
| bigInteger : extends 'integer' | is.dataFormat.integer, is.dataFormat.big |
| double : extends 'float' | is.dataFormat.float, is.dataFormat.big |
| guid : extends 'string' | is.dataFormat.guid, is.dataFormat.character, is.dataFormat.array |
| date | is.dataFormat.date |
| time | is.dataFormat.time |
| dateTime | is.dataFormat.date, is.dataFormat.time |
| dateTimeOffset :extends 'dateTime' | is.dataFormat.date, is.dataFormat.time, is.dataFormat.timeOffset |

An example of a more meaningful dataType is "city", which extends "string" and adds the *means.location.city* trait.

### dataFormat

Since dealing with the set of *is.dataFormat* traits that might originate from various semantic dataTypes can be awkward, the Common Data Model system converts these traits into a first class property on the Attribute object called the *dataFormat*. The dataFormat is computed from the traits found on the attribute. dataFormat values correlate with the intrinsic dataTypes listed above.

The best practice is to use a semantically rich dataType in your entity definition. However, it is possible to explicitly set the dataFormat property to one of the enumeration values; doing so will add the associated traits to the attribute.

| dataFormat | Traits |
|------------|----------|
| Unknown | No combination of traits could be recognized |
| Int16 | is.dataFormat.integer, is.dataFormat.small |
| Int32 | is.dataFormat.integer |
| Int64 | is.dataFormat.integer, is.dataFormat.big |
| Float | is.dataFormat.float |
| Double | is.dataFormat.float, is.dataFormat.big |
| Guid | is.dataFormat.character, is.dataFormat.array, is.dataFormat.guid |
| String | is.dataFormat.character, is.dataFormat.array |
| Char | is.dataFormat.character |
| Byte | is.dataFormat.byte |
| Binary | is.dataFormat.byte, is.dataFormat.array |
| Time | is.dataFormat.time |
| Date | is.dataFormat.date |
| DateTime | is.dataFormat.date, is.dataFormat.time |
| DateTimeOffset | is.dataFormat.date, is.dataFormat.time, is.dataFormat.timeOffset |
| Boolean | is.dataFormat.date |
| Decimal | is.dataFormat.date |
| Json | is.dataFormat.character, is.dataFormat.array, means.content.text.JSON |

### model.json types

When converting to and from the model.json persistence format for a Common Data Model entity, the following conversion takes place:

| Source dataFormat | model.json dataType | Destination dataFormat |
|-------------------|---------------------|------------------------|
| Unknown           | unclassified        | Unknown                |
| Byte              | unclassified        | Unknown                |
| Binary            | unclassified        | Unknown                |
| Int16             | int64               | Int64                  |
| Int32             | int64               | Int64                  |
| Int64             | int64               | Int64                  |
| Float             | double              | Double                 |
| Double            | double              | Double                 |
| Guid              | guid                | Guid                   |
| String            | string              | String                 |
| Char              | string              | String                 |
| Time              | time                | Time                   |
| Date              | date                | Date                   |
| DateTime          | dateTime            | DateTime               |
| DateTimeOffset    | dateTimeOffset      | DateTimeOffset         |
| Boolean           | boolean             | Boolean                |
| Decimal           | decimal             | Decimal                |
| Json              | json                | Json                   |

## Standard Traits

The standard definition documents for Common Data Model are *primitives.cdm.json*, *foundations.cdm.json*, and *meanings.cdm.json* (located at https://github.com/microsoft/CDM/tree/master/schemaDocuments). These standard definition documents contain a number of pre-defined standard traits that should be used or extended to help create a shared understanding of metadata from different systems. These standard traits define data formats, data shapes, usage guidance and restrictions, semantic meanings, and structural information about the relationships within the entity itself.

For more explanation, consider the following examples:

| Trait name | Description |
|------------|---------------|
| is.dataFormat.integer | Part of the dataFormat set of traits, indicates that the attribute represents whole numbers. |
| means.identity.entityId | Set for an attribute that holds an identifier (primary key) value for an entity |
| is.required | Specifies that an attribute is required |
| is.CDM.entityVersion | Holds the version number for the schema of an Entity |
| is.localized.displayedAs | The "Display Name" for an attribute or entity. Holds a table of language specifics strings. |
| is.correlatedWith | Indicates that the values found in the tagged attribute are correlated with the values from another indicated attribute. |
| means.calendar.dayOfWeek | Part of the Calendar trait set. Indicates the day of the week. Note that the data values could be "Mon, Tues" or 0,1,2, and this trait is still valid. Another trait like dataFormat.integer indicates the data shape. |
| means.demographic.maritalStatus | Marital status. Such an attribute can also, with other traits, be constrained to a specific list or an enum of possible values. |
| means.formatting.font.size | Could be used in an application to set a standard font size |
| means.idea.product | Could be used on an entity that holds product information. |
| means.location.city | Contains the name of a city. |
| means.measurement.distance.inches | Inches. Also defines measurement and measurement of distance. |
| means.identity.person.fullName | The full name of a person. |

The full set of standard traits can be broken down into the following groups/documents. Note that all of the standard "meanings" documents hold semantic traits and dataTypes.

| Document/Group | Description |
|----------------|------------------|
| primitives.cdm.json | Fundamental traits used by the Common Data Model system internally. Basic building blocks of data formats. |
| foundations.cdm.json | Key concepts that Common Data Model entities use to express ideas such as "localized display names", and "enumerations of values". |
| structural | *is.hidden*, *is.ordered*, *means.content.text.XML* |
| Meanings Concepts<br />(meanings.concepts.cdm.json) | Business concepts and objects: *means.idea.product*,* means.idea.schedule*, *means.category*, *means.relationship* |
| Meanings Identity<br />(meanings.identity.cdm.json) | Semantics about identifying things and people: *means.identity.barCode*, *means.identity.person.fullName*, *means.identity.tickerSymbol* |
| Meanings Calendar<br />(meanings.calendar.cdm.json) | Describing the parts of fiscal and other calendars: *means.calendar.day*, *means.calendar.weekOfYear*, *means.calendar.ISO8601* |
| Meanings Measurement<br />(meanings.measurement.cdm.json) | Measurement of physical and other dimensions: *means.measurement.density*, *means.measurement.sequence*, *means.measurement.currency.revenue*, *means.measurement.duration.hours* |
| Meanings Formats<br />(meanings.formats.cdm.json) | Color, font, ordering. |
| Meanings Demographics<br />(meanings.demographics.cdm.json) | Age, gender, income level: *means.demographics.birthDate* |
| Meanings Location<br />(meanings.location.cdm.json) | Address and locations: *means.location.address.street*, *means.location.latitude*, *means.location.geo.boundary.left* |
| Meanings Privacy<br />(meanings.privacy.cdm.json) | Data Subject actions, Identifiability, category, usage and consent requirements: *privacy.dataCategory.endUser.feedback*, *privacy.dataUsage.research*, *privacy.consent.optIn* |

## Traits in the Common Data Model object model

When working with objects such as entities, attributes, partitions, the Common Data Model object model largely follows the concepts one sees in the persisted JSON documents. The objects have a property of type `CdmCollection<CdmTraitReference>`, called "appliedTraits" or "exhibitedTraits", that contains a set of trait references. A *trait reference* can be queried for the definition object (fetchObjectDefintion) if needed. Each trait reference can contain a collection of arguments. These are the arguments that supply values to any defined trait parameters. An API call using "FetchFinalTraitArguments" will return a map from argument names to the *final* values of each parameter, when considering the inheritance hierarchy of the trait, any default values for parameters, and any argument values that have been set along the way.

Consult the [Common Data Model object model documentation](../1.0om/api-reference/cdm/cdm.md) and sample code projects for details on how to work with traits in code.

## Traits in model.json

The model.json file format was the initial version of the format that describes Common Data Model folders. The Common Data Model manifest format is the new version that accommodates additional requirements and covers a superset of functionality of model.json. The Common Data Model SDK, available in multiple languages, provides automatic forward- (and backward-) translation between the metadata formats. The reference specification for manifest is publicly available [here](https://docs.microsoft.com/common-data-model/sdk/manifest).

When the Common Data Model SDK is used to open a model.json document, the model.json document will be converted into a manifest object with references to EntityDefinitions. When a **pbi:dataCategory** custom extension is encountered on an entity or attribute, it will be automatically translated into the equivalent Common Data Model standard semantic trait and that trait will be attached to the converted Common Data Model entity or attribute.

### Automatic translation to standard traits of specific PBI custom extensions 

A set of PBI custom extensions will be translated into well-known traits. The best way to explain the correlation is to simply describe the traits:

```json
{
    "traitName": "is.extension.pbi:dataCategory",
    "extendsTrait": "is.extension",
    "explanation": "The Power BI data category for the entity or attribute this property is added for.",
    "hasParameters": [
        {
            "name": "is.extension.pbi:dataCategory",
            "dataType": "string",
            "explanation": "Default parameter since extension isn't an object."
        }
    ]
},
{
    "traitName": "is.extension.pbi:mashup",
    "explanation": "The mashup query and properties for the current document.",
    "extendsTrait": "is.extension",
    "hasParameters": [
        {
            "name": "fastCombine",
            "dataType": "boolean",
            "defaultValue": true,
            "explanation": "The fastCombine for the mashup query."
        },
        {
            "name": "allowNativeQueries",
            "dataType": "boolean",
            "defaultValue": false,
            "explanation": "Set if native queries are allowed."
        },
        {
            "name": "document",
            "dataType": "string",
            "explanation": "The mashup query for the current document."
        },
        {
            "name": "queriesMetadata",
            "dataType": "object",
            "explanation": "Dictionary of query name to it's metadata containing query id, name, entity name etc."
        }
    ]
},
{
    "traitName": "is.extension.pbi:refreshPolicy",
    "explanation": "The refresh policy for the entity. Full Refresh and Incremental Refresh are potential examples from Power BI.",
    "extendsTrait": "is.extension",
    "hasParameters": [
        {
            "name": "$type",
            "explanation": "The type of the refresh policy.",
            "dataType": "string"
        },
        {
            "name": "location",
            "explanation": "The root location to use for refresh.",
            "dataType": "string"
        },
        {
            "name": "rollingWindowGranularity",
            "dataType": "string",
            "explanation": "The granularity of the rolling window for the incremental refresh. it can be day, month, quarter or year.",
            "defaultValue": "Invalid"
        },
        {
            "name": "incrementalGranularity",
            "dataType": "string",
            "explanation": "The granularity of the incremental period in the window. it can be day, month, quarter or year.",
            "defaultValue": "Invalid"
        }
    ]
},
{
    "traitName": "is.extension.pbi:partitionDataQuery",
    "extendsTrait": "is.extension",
    "explanation": "Stores the partition query.",
    "hasParameters": [
        {
            "name": "is.extension.pbi:partitionDataQuery",
            "dataType": "string"
        }
    ]
},
{
    "traitName": "is.extension.pbi:refreshBookmark",
    "explanation": "The refresh bookmark for the last refresh of the partition.",
    "extendsTrait": "is.extension",
    "hasParameters": [
        {
            "name": "is.extension.pbi:refreshBookmark",
            "dataType": "string"
        }
    ]
},
{
    "traitName": "is.extension.pbi:source",
    "explanation": "The source for the partition.",
    "extendsTrait": "is.extension",
    "hasParameters": [
        {
            "name": "$type",
            "explanation": "The type of source of the partition.",
            "dataType": "string"
        },
        {
            "name": "start",
            "explanation": "The start date time for the ranged partition.",
            "dataType": "string"
        },
        {
            "name": "end",
            "explanation": "The end date time for the ranged partition.",
            "dataType": "string"
        }
    ]
},
{
    "traitName": "is.extension.pbi:timezone",
    "explanation": "The timezone for which the times specified in the document are valid.",
    "extendsTrait": "is.extension",
    "hasParameters": [
        {
            "name": "is.extension.pbi:timezone",
            "dataType": "string",
            "default value": "Greenwich Mean Time"
        }
    ]
}

```
</br>


### Other custom extensions

Other custom extensions, "pbi" or other prefix, encountered in the model.json are turned into matching traits on the Common Data Model object.

1. The new trait extends from the *is.extension* trait.

1. The trait is named to match the custom extension.

1. If the custom extension has a value that is an intrinsic type, like 'string', then the trait is given one parameter having the same name as the trait and the intrinsic typed value is assigned to that parameter.

1. If the custom extension has a value that is a structured object, then the trait is given one parameter for each named member of the custom extension's object type.

As an example, consider the following custom extension.

```json
{
 "pbi:customThing": "valueFromModel",
}
```
</br>

The custom extension turns into the following trait definition.

```json
            {
              "traitReference": "is.extension.pbi:customThing",
              "arguments": [
                {
                  "name": " is.extension.pbi:customThing",
                  "value": "valueFromModel"
                }
              ]
            },
```
</br>

Now, consider the following custom extension that has a value that is a structured object.

```json
{          "pbi:customThing": {
            "prop": "bet",
            "foo": "valueFromModel"
          }
```
</br>

The custom extension turns into the following trait definition that is given one parameter for each named member of the custom extension's object type.

```json
      {
        "traitReference": "is.extension.pbi:customThing",
          "arguments": [
          {
            "name": "prop",
            "value": "bet"
          },
          {
            "name": "foo",
            "value": "valueFromModel"
          },
       ]
     },

```
</br>

### Translation of annotations

Annotation in the model.json will also be turned into traits.

For example, the model.json form has the following annotation.

```json
{
      "annotations": [
        {
          "name": "pbi:EntityTypeDisplayHint",
          "value": "LinkedEntity"
        }
      ],

```
</br>

The Common Data Model object then exhibits this trait:

```json
{      "exhibitsTraits": [
        {
          "traitReference": "is.modelConversion.otherAnnotations",
          "arguments": [
            {
              "name": "annotations",
              "value": [
                {
                  "name": "pbi:EntityTypeDisplayHint",
                  "value": "LinkedEntity"
                }
              ]
            }
          ]
        },

```
</br>

Note that saving a Common Data Model manifest as a model.json using the SDK will run these trait to extension conversions and trait to annotation conversions in reverse.

However, there will be Common Data Model traits that have no equivalent representation in the model.json form. These traits will show up as Common Data Model custom extensions. For example:

```json
{
   "attributes": [
        {
          "dataType": "dateTimeOffset",
          "name": "createdOn",
          "description": "Date and time when the record was created.",
          "cdm:traits": [
            "is.dataFormat.date",
            "means.measurement.date",
            "is.dataFormat.time",
            "means.measurement.time",
            "means.measurement.date.creation",
            "is.CDS.standard",
            {
              "traitReference": "is.requiredAtLevel",
              "arguments": [
                "none"
              ]
            },
```
</br>

This shows an attribute definition in a model.json that holds a **cdm:traits** custom extension with an array of the persisted trait references that one would also see in the equivalent EntityDefinition.
