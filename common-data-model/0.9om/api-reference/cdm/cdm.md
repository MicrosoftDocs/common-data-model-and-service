---
title: API reference for the Common Data Model object model | Microsoft Docs
description: API reference for the Common Data Model object model.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Common Data Model Object Model

## Overview

The Common Data Model object model (OM) provides two types of classes: definition classes and reference classes. Since the OM is heavily interconnected and different concepts have different interactions amongst each other, the OM introduces reference classes in order to be able to easily reference different concepts without actually encapsulating them. Every reference class has its own corresponding definition class, and they are closely correlated. 

## Definition Classes

|Name|Description|
|---|---|
|[Argument](argument.md)|Exists inside [trait references](traitreference.md) and provides name/value pairs for a trait reference. With arguments traits can contain data.|
|[Argument Collection](argumentcollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to argument collections. It is used only for the *Arguments* property in [trait references](traitreference.md) and not for any other argument collections because this collection is optimized to handle adjustments to the trait when adding an argument.|
|[Attribute Context](attributecontext.md)|Provides more insight into an attribute's (parent/child) relationship. It is heavily used during an entity's attribute resolution and can contain the history of all changes that led to an attribute's resolution. Resolved concepts, such as resolved attributes, can contain attribute contexts to provide more insight into the original, non-resolved hierarchical attributes.|
|[Attribute Group](attributegroup.md)|Represents a group of [attribute items](attributeitem.md) that provide a similar role.|
|[Attribute Item](attributeitem.md)|Represents the base for a generic attribute that could be a [type attribute](typeattribute.md) or an [entity attribute](entityattribute.md).|
|[Attribute Resolution Guidance](attributeresolutionguidance.md)|Provides properties that help with the resolution process of [entities](entity.md), attributes, and other resolvable Common Data Model concepts.|
|[CdmObject](cdmobject.md)|Represents the base for all Common Data Model objects.|
|[CdmObject Definition](cdmobjectdefinition.md)|Represents the base for all Common Data Model object definitions.|
|[Collection](collection.md)|Holds a set of [Common Data Model objects](cdmobject.md) and provides easier handling of them.|
|[Constant Entity](constantentity.md)|Provides a way of making an [entity](entity.md) with records of data in it and an associated schema in a JSON file. We use these whenever we want to store some table of information inside a parameter of a [trait](trait.md). They show up in the enum definitions, in the localized display text, etc.|
|[Corpus](corpus.md)|Provides the most important basic functionalities to deal with the object model. There will usually only be one corpus when dealing with the OM.|
|[Data Partition](datapartition.md)|Points to a location of entity-related data.|
|[Data Partition Pattern](datapartitionpattern.md)|Provides a way of selecting/generating a set of partitions based on the requirements specified as a regular expression.|
|[Data Type](datatype.md)|Provides the ability to assign different data types to attributes (such as string, boolean, etc).|
|[Document](document.md)|Enables the OM to have a persisted state. Every document can contain different Common Data Model definitions, such as [entities](entity.md), [data partitions](datapartition.md), or attributes.|
|[Document Collection](documentcollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to document collections.|
|[E2E Relationship](e2erelationship.md)|A relationship between two entities' attributes.|
|[Entity](entity.md)|Provides a concrete placeholder for a user to attach certain information to a concept. It is a collection of attributes that creates some semantic meaning of why these attributes exist together. Since entities can inherit from other entities, it is possible for them to represent a hierarchical structure. The hierarchical structure can also be removed from the entities by resolving them.|
|[Entity Attribute](entityattribute.md)|An attribute that also points to an [entity](entity.md).|
|[Entity Collection](entitycollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to entity collections.|
|[Entity Declaration](entitydeclaration.md)|Provides a simple functionality that is extended by a [local entity declaration](localentitydeclaration.md) and a [referenced entity declaration](referencedentitydeclaration.md).|
|[Folder](folder.md)|Provides a hierarchical structure of the OM for organizing documents. Folders can contain other folders or documents.|
|[Folder Collection](foldercollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to folder collections. It is used only for the *ChildFolders* property in [Folder](folder.md) and not for any other folder collections, as this collection copies fields from the parent folder to the children.|
|[Import](import.md)|Used by documents to provide the files and documents that need to be imported first.|
|[Local Entity Declaration](localentitydeclaration.md)|A declaration of an entity that resides locally and has associated [data partitions](datapartition.md).|
|[Manifest](manifest.md)|A top-level document with the extension '.manifest.cdm.json'. A manifest can reference different documents (e.g. reference documents with the extension '.cdm.json' that contain entities).|
|[Manifest Declaration](manifestdeclaration.md)|A declaration for the Common Data Model manifest format.|
|[Parameter](parameter.md)|Provides the ability to specify the parameters that a trait should contain. By providing a name, default values, and supported data types, trait references become restricted by which arguments they can contain. Parameters are defined for traits in the *CDM.SchemaDocuments* repository.|
|[Purpose](purpose.md)|Provides an attribute with what it does for an entity *(e.g. SortedBy, NamedBy)*.|
|[Referenced Entity Declaration](referencedentitydeclaration.md)|A declaration of an entity that resides in a remote location.|
|[Trait](trait.md)|Helps express semantic meaning and structural guidance. Traits are essentially a metadata's metadata. Traits can extend other traits and have a format that is easy to understand and follow.|
|[Trait Collection](traitcollection.md)|Extends [Collection](collection.md) and adds additional behaviors specific to trait collections.|
|[Type Attribute](typeattribute.md)|Defines data type attributes along with supported functionalities, such as custom default values and descriptions. Model.json attributes are converted into CDM type attributes.|
 

## Reference Classes

All reference objects extend from the [CdmObject Reference](cdmobjectreference.md) interface. Many references are just empty interfaces extending from *CdmObjectReferenceBase*. These references are *CdmAttributeContextReference, CdmAttributeGroupReference, CdmAttributeReference, CdmDataTypeReference, CdmEntityReference,* and *CdmPurposeReference*.

|Name|Description|
|---|---|
|[CdmObject Reference](cdmobjectreference.md)|Represents the base for all Common Data Model object references.|
|[Trait Reference](traitreference.md)|The reference class for [traits](trait.md).|


## Enum Classes
|Name|Description|
|---|---|
|[Attribute Context Type](attributecontexttype.md)|The attribute context types.| 
|[CdmObject Type](objecttype.md)|The Common Data Model object types.|
|[Data Format](dataformat.md)|The data formats.|
|[Relationship Discovery Style](relationshipdiscoverystyle.md)|The types of relationships we want populated in a manifest.|
|[Status Level](statuslevel.md)|The status levels that could be reported at.|


