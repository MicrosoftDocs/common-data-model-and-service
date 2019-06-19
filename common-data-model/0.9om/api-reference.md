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
|**Validate()**|Validates the CDM object. Each object that implements an interface inheriting from ICdmObject implements this method in their own way to ensure that each CDM object is in the right form.|bool|
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

### ICdmCollection<T> extends IEnumarable<T>, T extends from ICdmObject

|Name|Description|Return type|
|---|---|---|
|**Add(...):**<br/>*name*: The name of the ICdmObject that is being added to the collection.<br/>*simpleRef*: If we are adding a reference, whether we want that reference to be a simple reference.|Adds an ICdmObject of a default type (default type can be set in the property) with a given name to the collection.|void|
|**Add(...):**<br />*currObject*: The CDM object.|Add an ICdmObject specified in the parameter to the collection.	|void|
|**Remove(...):(...):**<br/>*currObject*: The CDM object.|Removes the specified CDM object from the list.|boolean|
|**Item(...):**<br />*name*: The name of a CDM object.|Fetches a CDM object with the specified name.|T|
|**this(...):**<br/>*index*: The index of an element we want to fetch.|Fetches a CDM object from the collection in the specified index.|T|

### ICdmDocumentDef extends ICdmContainerDef

|Name|Description|Return type|
|---|---|---|
|**AddDefinition(...)<T>:**<br/>*ofType*: The type of an object that gets created. <br/>*name*: The name of the object that gets created.|Adds a definition of an object of a specific type and name (after creating it) and returns back the object of that type.	|T|
|**AddImport(...):**<br />*corpusPath*: The corpus path.<br/>*moniker*: The moniker, it is a nickname used for imports to specify which document to import in the case of duplicate symbols (e.g. we might have multiple Account documents, but by specifying a moniker 'base_Account', we can pinpoint the exact document).|Creates and adds an import object created from corpus path and moniker to the document.|void|
|**Refresh(...):**<br />resOpt: The resolution options.|Updates the indexes in the document. The method is supposed to be called after modifying the objects inside definitions.|Task|
|**SaveAs(...)::**<br />*newName*: The new document's name.<br/>*options*: The copy options.<br/>*saveReferenced*: A boolean which denotes whether we want to save all the references files (linked schema definitions) as well (folio can reference different entity documents).|Saves the document back through the adapter in the requested format. Format is specified via document name/extension based on conventions: '.model.json' for back-compatibility model, '.folio.cdm.json' for folio and '.cdm.json' for CDM definitions. 	|Task|

### ICdmFileStatus extends ICdmObject

|Name|Description|Return type|
|---|---|---|
|**FileStatusCheck()**|Updates the object and any children with the current time. 	|Task|
|**ReportMostRecentTime(...):**<br />*childTime (DateTimeOffet) [optional]*: The biggest child time. This parameter will get updated as a result of the function.|Reports the most recent modified time of the object (or children) to the parent object. It also modified the childTime parameter with the biggest child time.	|Task|

### ICdmFolio extends ICdmObjectDef, ICdmDocumentDef, ICdmFileStatusExtended

|Name|Description|Return type|
|---|---|---|
|**PopulateEntityRelationships()**|Populates the relationships that the entities in the current folio are involved in. This function is used to pre-calculate relationships what leads to optimizations during resolution process.|Task|
|**CreateResolvedFolio(...):**<br />*newFolioName*: The new folio name. <br/>*newEntityDocumentNameFormat*:  Specifies a pattern to use when creating documents for resolved entities. The default is "resolved/{n}.cdm.json" to avoid a document name conflict with documents in the same folder as the folio.|Creates a resolved copy of folio. Every instance of the string {n} from the argument is replaced with the entity name from the source folio and any sub-folders described by the pattern should exist in the corpus prior to calling this function. A folio with all the entities resolved is returned.|Task<ICdmFolioDef>|
|**QueryOnTraits(...):**<br/>*querySpec*: A JSON object (or a string that can be parsed into one) of the form *{"entityName":"", "attributes":[{see QueryOnTraits for ICdmEntityDef for details}]}*|Query the folio for a set of entities that match an input query. Returns null for 0 results or an array of JSON objects, each matching the shape of the input query, with entity and attribute names filled in.	|Task<List<JToken>>|

### ICdmTypeAttributeDef extends ICdmAttributeDef

|Name|Description|Return type|
|---|---|---|
|**GetProperty(...):**<br/>*propertyName*: The property name.|Returns the value directly assigned to a property (ignore value from traits).	|dynamic|

### ICdmCorpusDef extends ICdmFolderDef

|Name|Description|Return type|
|---|---|---|
|**CreateStorageAdapter(...):**<br/>*config (JToken)*: The configuration.|Creates a storage adapter from configuration (Please refer to samples to find out more about how to specify configuration).	|IStorageAdapter|
|**RegisterStorageAdapter(...):**<br/>*namespace*: The namespace<br/>*adapter*: The storage adapter|Registers the storage adapter with the specified namespace.|void|
|**GetStorageAdapter(...):**<br/>*namespace*: The namespace|Retrieves the storage adapter with the specified namespace.	|IStorageAdapter|
|**GetRootFolder(...):**<br/>*namespace*: The namespace|Given the namespace and a registered storage adapter, returns the root folder containing the sub-folders and documents.	|ICdmFolderDef|
|**CreateRootFolio(...):**<br/>*corpusPath*: The corpus path|Creates a folio from the corpus path that points to a specific document.	|Task<ICdmFolioDef>|
|**MakeRef<T>(...):**<br/>*ofType*: Of what type. <br/>*refObj [optional]*: The reference object. <br/> *simpleNameRef [optional]*: Whether is it a simple name reference.	| Instantiates an OM class reference based on the object type passed as the first parameter.|T|
|**MakeObject<T>(...):**<br/>*ofType*: Of what type. <br/>*nameOrRef*: The name or reference.<br/>*simpleNameRef*: Whether is it simple name reference.	| Instantiates an OM class based on the object type passed as the first parameter.	|T|
|**GetReferenceType(...):**<br/>*ofType*: Of what type. | Gets the reference of a certain object or reference type.	|CdmObjectType|
|**AddDocumentFromContent(...):**<br/>*corpus*: The corpus <br/> *corpusPath*: The corpusPath <br/> *content*: The content <br/> *adapter*: The storage adapter | Adds a document from raw content to the corpus. |Task<ICdmDocumentDef>|
|**MakeAbsoluteCorpusPath(...):**<br/>*objectPath*: The object path <br/> *obj*: The object| Takes the relative or absolute object path and creates a valid absolute path with namespace.	|string|
|**AdapterPathToCorpusPath(...):**<br/>*adapterPath*: The adapter path.| Takes a storage adapter domain path, figures out the right adapter to use and then returns a corpus path.	|string|
|**CorpusPathToAdapterPath(...)**<br/>*corpusPath*: The corpus path | Takes a corpus path, figures out the right adapter to use and then returns an adapter domain path. |string|
|**GetObjectFromCorpusPath(...):**<br/>*objectPath*: The object path of a folder or document.<br/>*forceReload*: If true, reload the object from file and replace the current object with it. | Fetches an object from the corpus path.	|Task<ICdmObject>|
|**SaveDocumentAs(...):**<br/>*doc*: The document implementation.<br/>*options*: The copy options.<br/>*newName*: The new name of the document (ending on either '.model.json' or '.folio.json').<br/>*saveReferenced*: If true, saves the referenced files as well (folio can reference different documents/linked schema definitions).| Saves a document (model.json or cdm.json) in a file/files.	|Task|
|**SetResolutionCallback(...):**<br/>*status*: The callback. <br/>*reportAtLevel*: At which level to report.<br/>*errorAtLevel*: Does it throw an error. | Sets the status and error callback which is getting called for status/warnings/error purposes. The function will be renamed to better match the description.	|void|
|**CheckObjectIntegrity() **| Validates the corpus and checks its integrity and it sets the status in context in the case of not satisfying the integrity conditions. Integrity conditions are conditions which are getting verified in the Validate method of CDM objects.	|void|