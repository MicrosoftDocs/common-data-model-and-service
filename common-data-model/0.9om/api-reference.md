---
title: API Reference - Common Data Model | Microsoft Docs
description: API reference for 0.9 OM.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# API Reference

## Resolved Model

Resolved model represents resolved version of CDM classes. Since resolved classes have been flattened out, they don't have base classes.
Examples of resolved classes include ResolvedAttribute, ResolvedAttributeSet, ResolvedEntity, ResolvedEntitySet, ResolvedTrait and ResolvedTraitSet. Please refer to code for further details on implementation and usage of those classes.

## Persistence

The persistence folder contains code which enables persistence of the OM and it contains two main folders: CdmFolders and ModelJson. CdmFolders code can persist code in CDM format as '.folio.json' or 'cdm.json', while ModelJson persists CDM OM into Model.json OM with the '.model.json' extension. The main class that deals with persistence is the static *PersistenceLayer* class:

|Name|Description|Return type|
|---|---|---|
|**ToData<T, U>(...):**<br />*instance (T)*: The CDM object instance.<br/>*resOpt*: The resolve options.<br/>*copyOpt*: The copy options.<br/>*persistenceTypeName*: The persistence type name which needs to be called.|Converts the object from a CDM object type T to the persistent type U.|U|

## References

Please refer to the OM Reference section for information about the references in the OM. All reference objects extend from ICdmObjectRef, and this section will have a list of all references which implement some API.

### ICdmObjectRef extends ICdmObject

|Name|Description|Return type|
|---|---|---|
|**AddAppliedTraits(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.<br/>*implicitRef [optional]*: The boolean that denotes is the trait is implicit trait, it is used only if the name is provided as a trait definition.|Adds a trait to the applied trait list. |ICdmTraitRef|
|**RemoveAppliedTrait(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.|Adds a trait to the applied trait list. |ICdmTraitRef|

### ICdmTraitRef extends ICdmObjectRef

|Name|Description|Return type|
|---|---|---|
|**AddArgument(...):**<br />*name*: The name of the argument.<br/>*value*: The value of the argument.|Adds an argument with the specified name and value to the Arguments list. Arguments have to match the parameters format specified in the schema documents.|ICdmArgumentDef|
|**GetArgumentValue(...):**<br />*name*: The name of the argument.|Retrieves the argument value from the arguments list for the specified name.|dynamic|
|**SetArgumentValue(...):**<br /><br />*name*: The name of the argument.<br/>*value*: The value of the argument.|Sets the specified value to the argument with the specified name.|void|

## Definitions

### ICdmArgumentDef extends ICdmObject

|Name|Description|Return type|
|---|---|---|
|**GetParamterDef():**|Returns the resolved parameter (the property on the instance of ICdmArgumentDef). Parameters are bound to arguments in a sense that trait references have arguments which need to match trait definition parameters.|ICdmParameterDef|

### ICdmAttributeContext extends ICdmObjectDef

|Name|Description|Return type|
|---|---|---|
|**CopyNode(...):**<br/>*resOpt*: The resolve options.|Returns a copy of only the current attribute context node.|ICdmObject|
|**CopyAttributeContextTree(...):**<br/>*resOpt*: The resolve options.<br/>newNode: The new root node of the attribute context tree.<br/>*ras*: The resolved attribute set.<br/>*attCtxSet [optional]*: The set of attribute context.|Returns a copy of the attribute context tree.|AttributeContextImpl|

### ICdmAttributeDef extends ICdmAttributeItem

|Name|Description|Return type|
|---|---|---|
|**AddAppliedTraits(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.<br/>*implicitRef [optional]*: The boolean that denotes is the trait is implicit trait, it is used only if the name is provided as a trait definition.|Adds the specified trait definition to the list of applied traits.|CdmObject|
|**RemoveAppliedTrait(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.|Adds a trait to the applied trait list. |ICdmTraitRef|

### ICdmAttributeGroupDef extends ICdmObjectDef, ICdmReferencesEntities

|Name|Description|Return type|
|---|---|---|
|**AddAppliedTraits(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.<br/>*implicitRef [optional]*: The boolean that denotes is the trait is implicit trait, it is used only if the name is provided as a trait definition.|Adds the specified trait definition to the list of applied traits.|CdmObject|

### ICdmEntityDef extends ICdmObjectDef, ICdmReferencesEntities

|Name|Description|Return type|
|---|---|---|
|**CountInheritedAttributes(...):**<br />*resOpt*: The resolve options.|Returns the count of attributes inherited by the entity.|int|
|**CreateResolvedEntity(...):**<br />*resOpt*: The resolve options.<br/>*newDocName*: The new document name.<br/>*folder [optional]*: The folder which will be used as a target corpus path, uses in-document folder (property on the entity) if not specified.|Creates a resolved copy of the entity.|Task<ICdmEntityDef>|
|**GetAttributesWithTraits(...):**<br />*resOpt*: The resolve options.<br/>*queryFor*: The query options, can be specified as a string or list of traits.|Returns a set of the entity attributes that have the specified traits.	|ResolvedAttributeSet|
|**GetProperty(...):**<br />*propertyName*: The property name.|Returns the value directly assigned to the property name (ignores values from traits).|dynamic|
|**QueryOnTraits(...):**<br />*querySpec*: A JSON object or string of the form *{"attributeName":"", "attributeOrdinal" : -1, "traits": {{traitObject}}}*, traitObject has to contain traitName and optionally arguments (each argument has argumentName and value).|Queries the entity for a set of attributes that match an input query.|Task<List<JToken>>, null for 0 results.|

### ICdmObjectDef extends ICdmObject

|Name|Description|Return type|
|---|---|---|
|**AddExhibitedTrait(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.<br/>*implicitRef [optional]*: The boolean that denotes is the trait is implicit trait, it is used only if the name is provided as a trait definition.|Adds the specified trait definition to the list of exhibited traits and clears the trait cache on the object.|CdmObject|
|**RemoveExhibitedTrait(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.|Removes the trait definition from the exhibited trait list.|ICdmTraitRef|

### ICdmObject

|Name|Description|Return type|
|---|---|---|
|**Validate():**|Validates the CDM object. Each object that implements an interface inheriting from ICdmObject implements this method in their own way to ensure that each CDM object is in the right form.|bool|
|**GetObjectDef<T>(...):**<br />*resOpt*: The resolve options.|Returns the resolved object definition when called on a reference.|T|
|**GetObjectDefName()**|Fetches the object definition's name.|string|
|**Copy(...):**<br />*resOpt*: The resolve options.|Returns a copy of the CDM object.|ICdmObject|
|**CopyData(...):**<br />*resOpt*: The resolve options.<br/>*options*: The copy options.|Copies the data based on the copy options and can returns an object.|dynamic|
|**CreateSimpleReference(...):**<br />*resOpt*: The resolve options.|Creates a simple reference to a definition of the current CDM object and returns that reference, simple references are used to refer objects just by name.	|ICdmObjectRef|

### ICdmFolderDef extends ICdmObjectDef, ICdmContainerDef

|Name|Description|Return type|
|---|---|---|
|**AddChildFolder(...):**<br/>*name*: The name of the folder.|Adds a child folder to the current folder and returns the newly added folder.|ICdmFolderDef|
|**AddDocument(...):**<br />name: The name of the document.<br/>*content*: The content of the document.|Adds a child document to the current folder and returns the newly created document.|ICdmDocumentDef|
|**RemoveDocument(...):**<br/>*name*: The name of the document.|Removes a document with the specified name from the folder.|void|
|**GetChildFolderFromPath(...):**<br />*path*: The path.<br/>*adapter*: The storage adapter where the folder can be found.<br/>*makeFolder [optional]*: Whether to create a folder if it doesn't exist.<br/>|Fetches the child folder from the specified corpus path.	|Task<ICdmFolderDef>|
|**GetDocumentFromFolderPath(...):**<br/>*path*: The path.<br/>*adapter*: The storage adapter where the folder can be found.<br/>*forceReload [optional]*: Whether to reload the object from file and replace the current object with it.|Fetches the document from the specified folder path.|Task<ICdmDocumentDef>|
