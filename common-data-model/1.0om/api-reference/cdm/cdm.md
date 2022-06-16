---
title: Common Data Model object model API reference | Microsoft Docs
description: API reference for the Common Data Model object model.
author: jinichu

ms.reviewer: deonhe 
ms.topic: article
ms.date: 02/05/2020
ms.author: jibyun
---

# Object Model

## Overview

The Common Data Model object model provides two main types of classes for Common Data Model objects: definition classes and reference classes. Since the object model is heavily interconnected and the concepts have different interactions amongst each other, the object model introduces reference classes to be able to easily reference different concepts without encapsulating them. Every reference class has its own corresponding definition class, and they are closely related. There are also various enum classes, which you'll find at the end of this article.

The C# code can be found [here](https://github.com/microsoft/CDM/tree/master/objectModel/CSharp/Microsoft.CommonDataModel.ObjectModel/Cdm).

## Definition classes

|Name|Description|
|---|---|
|[Argument](argument.md)|Exists inside [trait references](traitreference.md) and provides name/value pairs for a trait reference. With arguments traits can contain data.|
|[Argument Collection](argumentcollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to argument collections.|
|[Attribute Context](attributecontext.md)|Provides more insight into an attribute's (parent/child) relationship. It's heavily used during an entity's attribute resolution and can contain the history of all changes that led to an attribute's resolution. Resolved concepts, such as resolved attributes, can contain attribute contexts to provide more insight into the original, non-resolved hierarchical attributes.|
|[Attribute Group](attributegroup.md)|Represents a group of [attribute items](attributeitem.md) that provide a similar role.|
|[Attribute Item](attributeitem.md)|Represents the base interface for a generic attribute that could be a [type attribute](typeattribute.md) or an [entity attribute](entityattribute.md).|
|[Attribute Resolution Guidance](attributeresolutionguidance.md)|Provides properties that help with the resolution process of [entities](entity.md), attributes, and other resolvable Common Data Model concepts.|
|[CdmObject](cdmobject.md)|Represents the base interface for all Common Data Model objects.|
|[CdmObject Definition](cdmobjectdefinition.md)|Represents the base interface for all Common Data Model object definitions.|
|[CdmObject Definition Collection](definitioncollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to CdmObject definition collections.|
|[Collection](collection.md)|Holds a set of [Common Data Model objects](cdmobject.md) and provides easy handling of them.|
|[Constant Entity](constantentity.md)|Provides a way of making an [entity](entity.md) with records and an associated schema in a JSON file. We use these whenever we want to store a table of information inside a parameter of a [trait](trait.md). They are used in the enum definitions, in the localized display text, etc.|
|[Corpus](corpus.md)|Provides the most important basic functionalities to deal with the object model. There will usually only be one corpus when dealing with the object model.|
|[Data Partition](datapartition.md)|Points to a location of entity-related data.|
|[Data Partition Pattern](datapartitionpattern.md)|Provides a way of selecting or generating a set of partitions based on the requirements specified as a regular expression.|
|[Data Type](datatype.md)|Provides the ability to assign different data types to attributes (such as string, boolean, etc.).|
|[Document](document.md)|Enables the object model to have a persisted state. Every document can contain different Common Data Model object definitions, such as [entities](entity.md), [data partitions](datapartition.md), or attributes.|
|[Document Collection](documentcollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to document collections.|
|[E2E Relationship](e2erelationship.md)|A relationship between two entity's attributes.|
|[Entity](entity.md)|Provides a concrete placeholder for a user to attach certain information to a concept. It's a collection of attributes that creates a semantic meaning of why these attributes coexist. Since entities can inherit from other entities, it's possible for them to represent a hierarchical structure. The hierarchical structure can also be removed from the entities by resolving them.|
|[Entity Attribute](entityattribute.md)|An attribute that also points to an [entity](entity.md).|
|[Entity Collection](entitycollection.md)|Extends [Collection](collection.md) and adds behaviors specific to entity collections.|
|[Entity Declaration](entitydeclaration.md)|Provides a simple functionality that's extended by a [local entity declaration](localentitydeclaration.md) and a [referenced entity declaration](referencedentitydeclaration.md).|
|[Folder](folder.md)|Provides a hierarchical structure of the object model for organizing [documents](document.md). Folders can contain other folders or documents.|
|[Folder Collection](foldercollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to folder collections. It's used only for the *ChildFolders* property in [Folder](folder.md) and not for any other folder collections, as this collection copies fields from the parent folder to the children.|
|[Import](import.md)|Used by [documents](document.md) to provide the files and documents that need to be imported first.|
|[Import Collection](importcollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to import collections.|
|[Local Entity Declaration](localentitydeclaration.md)|A declaration of an entity that resides locally and has associated [data partitions](datapartition.md).|
|[Manifest](manifest.md)|A top-level document with the extension '.manifest.cdm.json'. A manifest can reference different documents, including documents with the extension '.cdm.json' that contain entities.|
|[Manifest Declaration](manifestdeclaration.md)|A declaration for the Common Data Model manifest format.|
|[Parameter](parameter.md)|Provides the ability to specify the parameters that a [trait](trait.md) should contain. By providing a name, default values, and supported data types, trait references become restricted by which arguments they can contain. Parameters are defined for traits in the [schema documents](https://github.com/microsoft/CDM/tree/master/schemaDocuments) folder.|
|[Purpose](purpose.md)|Provides an attribute with what it does for an entity (for example, *SortedBy* or *NamedBy*).|
|[Referenced Entity Declaration](referencedentitydeclaration.md)|A declaration of an entity that resides in a remote location.|
|[Trait](trait.md)|Helps express the semantic meaning and structural guidance. Traits are essentially a metadata's metadata. Traits can extend other traits and have a format that's easy to understand and follow.|
|[Trait Collection](traitcollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to trait collections.|
|[Type Attribute](typeattribute.md)|Defines data type attributes along with supported functionalities, such as custom default values and descriptions. Model.json attributes are converted into Common Data Model type attributes.|
 

## Reference classes

All reference objects extend from the [CdmObject Reference](cdmobjectreference.md) interface. Many references are empty interfaces extending from *CdmObjectReferenceBase*. These references are *CdmAttributeContextReference, CdmAttributeGroupReference, CdmAttributeReference, CdmDataTypeReference, CdmEntityReference,* and *CdmPurposeReference*.

|Name|Description|
|---|---|
|[CdmObject Reference](cdmobjectreference.md)|Represents the base interface for all Common Data Model object references.|
|[Trait Reference](traitreference.md)|The reference class for [traits](trait.md).|


## Enum classes
|Name|Description|
|---|---|
|[Attribute Context Type](attributecontexttype.md)|The attribute context types.| 
|[CdmObject Type](objecttype.md)|The Common Data Model object types.|
|[Data Format](dataformat.md)|The data formats.|
|[Relationship Discovery Style](relationshipdiscoverystyle.md)|The types of relationships we want populated in a manifest.|
|[Status Level](statuslevel.md)|The status levels that could be reported.|



