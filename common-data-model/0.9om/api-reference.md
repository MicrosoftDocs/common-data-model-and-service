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

The hierarchical structure of the CDM object model:

![OM Hierarchy](omhierarchy.png)

The CDM object model (OM) provides two types of classes: definition classes and reference classes. Since the OM is heavily interconnected and different concepts have different interactions among each other, the OM introduces the reference classes in order to be able to easily reference different concepts without actually encapsulating them. Every reference class has its own corresponding definition class, and they are closely correlated. 

## CDM Definitions
TODO: Description

### Argument (CdmArgumentDefinition extends CdmObjectSimple)

An argument exists inside trait references and provides name/value pairs for a specific trait reference. Arguments give life to traits by enabling them to actually contain some specific data.

#### Properties
|Name|Description|
|---|---|
|Explanation|The argument's explanation.|
|Name|The argument's name.|
|Value|The argument's value.|  

### Attribute (CdmAttribute extends CdmObjectDefinitionBase, CdmAttributeItem)  

An attribute is a definition that only occurs inside other definitions. Unlike references, it has applied traits instead of exhibited traits. Attributes can either be entity attributes or data type attributes. Entity attributes have references to another entities, while data type attributes represent a specific data type (see *CdmDataTypeDefinition*).

#### Properties
|Name|Description|
|---|---|
|Name|The attribute's name.|
|Purpose|See *Purpose*.|
|ResolutionGuidance|The properties that guide the resolution of this attribute and interact with directives (see *CdmAttributeResolutionGuidance*).|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**AddAppliedTrait(...):**<br />*traitDef*: The trait definition, either a string representing the name or a CdmTraitReference object.<br/>*implicitRef [optional]*: The boolean that denotes whether the trait is an implicit trait. It is used only if the name is provided as a trait definition. The default value is false.|Adds the specified trait definition to the list of applied traits. Returns the added trait.|CdmTraitReference|
|**RemoveAppliedTrait(...):**<br />*traitDef*: The trait definition, either a string representing the name or a CdmTraitReference object.<br />*onlyFromProperty [optional]*: TODO |Removes the trait definition from the list of applied traits.|void|

### Attribute Context (CdmAttributeContext extends CdmObjectDefinitionBase)

An attribute context provides more insight into an attribute's relationship (child/parent). It is heavily used during the entity's attribute resolution and can contain the history of all changes that lead to an attribute's resolution. Resolved concepts, such as resolved attributes, can contain attribute contexts to provide more insights into the original, non-resolved hierarchic attributes.

#### Properties
|Name|Description|
|---|---|
|Contents|The attribute context's content list.|
|Definition|The reference to the object this attribute context was defined from.|
|Name|The attribute context's name.|
|Parent|The attribute context's parent.|
|Type?|The attribute context's type (can be *Entity, EntityReferenceExtends, AttributeDefinition, EntityReferenceAsAttribute, AttributeGroup, AddedAttributeSupporting, AddedAttributeIdentity,* or *PassThrough*).|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**CopyNode(...):**<br/>*resOpt*: The resolve options.|Returns a copy of the current attribute context node.|CdmObject|

### Attribute Group (CdmAttributeGroupDefinition extends CdmObjectDefinitionBase, CdmReferencesEntities)

An attribute group represents a group of attribute items (see *CdmAttributeItem*) that provide a similar role. 

#### Properties
|Name|Description|
|---|---|
|AttributeContext|The attribute group context.|
|AttributeGroupName|The attribute group's name.
|Members|The list of attribute items for the attribute group.|

### Attribute Item (CdmAttributeItem extends CdmObject, CdmReferencesEntities)

An attribute item is a concept that represents the base class for an attribute.

#### Properties
|Name|Description|
|---|---|
|AppliedTraits|The attribute's applied traits.|

### Attribute Resolution Guidance (CdmAttributeResolutionGuidance extends CdmObjectSimple)

An attribute resolution guidance provides properties that help with the resolution process of entities, attributes, and other resolvable CDM concepts.

#### Properties
|Name|Description|
|---|---|
|removeAttribute?|If true, this attribute definition will be removed from the entity's final resolved attribute list.|
|imposedDirectives|A list of strings, one for each 'directive' that should always be imposed at this attribute definition.|
|removedDirectives|A list of strings, one for each 'directive' that should be removed if previously imposed.|
|addSupportingAttribute|The supplied attribute definition that will be added to the entity.|
|cardinality|If 'one', then there is a single instance of the attribute or entity used. 'many' indicates multiple instances, and the 'expansion' properties will describe the array enumeration to use when needed.|
|renameFormat|The format specifier for generated attribute names. May contain a single occurence of ('\{a} or 'A'), ('\{m}' or '\{M}') and '\{o}' for the base (a/A)ttribute name, any (m/M)ember attributes from entities, and array (o)rdinal. For example, '\{a}\{o}.\{m}' could produce 'address2.city', and '\{a}\{o}' gives 'city1'. Using '\{A}' or '\{M}' will uppercase the first letter of the name portion.|
|expansion|The parameters that control array expansion if inline repeating of attributes is needed.|
|entityByReference |The parameters that control the use of foreign keys to reference entity instances instead of embedding the entity in a nested way.|
|selectsSubAttribute|Indicates that this attribute selects either 'one' or 'all' of the sub-attributes from an entity. If the 'structured' directive is set, this trait causes resolved attributes to end up in groups rather than a flattened list.|

### Collection (CdmCollection extends IList\<CdmObject>\)

A collection holds a set of CDM objects (see *CdmObject*) and provides easier handling of them.

#### Properties
|Name|Description|
|---|---|
|Count|The number of items in the CDM collection.|
|AllItems|The list of all items.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**Add(...):**<br/>*name*: The name of the CdmObject that is being added to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether we want a reference to be a simple reference, if we are adding one. The default value is false.|Adds a CdmObject of a default type (default type can be set in the property) with the given name to the collection.|void|
|**Add(...):**<br />*currObject*: The CDM object.|Add the CdmObject specified in the parameter to the collection.	|void|
|**Remove(...):**<br/>*currObject*: The CDM object.|Removes the specified CDM object from the collection.|boolean|
|**Item(...):**<br />*name*: The name of a CDM object.|Fetches the CDM object with the specified name.|T|
|**this[...]:**<br/>*index*: The index of the element we want to fetch.|Fetches the CDM object from the collection in the specified index.|T|

### Constant Entity (CdmConstantEntityDefinition extends CdmObjectDefinitionBase)

A constant entity provides a way of making an entity with records of data in it and an associated schema in a JSON file. We use these whenever we want to store some table of information inside a parameter of a trait. They show up in the enum definitions, in the localized display text, etc.

#### Properties
|Name|Description|
|---|---|
|ConstantEntityName|The constant entity's name.|
|ConstantValues|The list of constant string values.|
|EntityShape|The entity shape (see *CdmEntityReference*).|

### Container (CdmContainerDefinition extends CdmObject)

A container describes the placement of the CDM object. Both folders and documents, along with the corpus, extend the container interface in order to encapsulate the namespace and folder path.

#### Properties
|Name|Description|
|---|---|
|Namespace|The namespace where this object can be found.|
|FolderPath|The path to a folder where this object exists.|

### Corpus (CdmCorpusDefinition extends CdmFolderDefinition)

The corpus is a top-level folder that provides the most important basic functionality to deal with the object model. There will usually be only one corpus when dealing with the OM.

#### Properties
|Name|Description|
|---|---|
|RootPath|The root path of the corpus.|
|DefaultNamespace|The namespace that will be used when one is not explicitly provided.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**MakeRef\<T>(...):**<br/>*ofType*: The CDM object type. <br/>*refObj*: The reference object. <br/> *simpleNameRef*: The boolean that denotes whether it is a simple name reference.	| Instantiates an OM class reference based on the object type passed as the first parameter.|T, where T : CdmObjectReference|
|**MakeObject\<T>(...):**<br/>*ofType*: The CDM object type. <br/>*nameOrRef [optional]*: The name or reference.<br/>*simpleNameRef [optional]*: The boolean that denotes whether it is a simple name reference. The default value is false.	| Instantiates an OM class based on the object type passed as the first parameter.	|T, where T : CdmObject|
|**FetchObjectAsync\<T>(...):**<br/>*objectPath*: The object path of a folder or document.<br/>*obj [optional]*: TODO | Fetches an object from the corpus path.	|Task\<T>|
|**SetEventCallback(...):**<br/>*status*: The callback. <br/>*reportAtLevel*: At which status level to report.| Sets the status and error callback that is getting called for status/warning/error purposes.|void|
|**GenerateWarningsAsync():**|Generates warnings into the status report.|Task|
|**ResolveReferencesAndValidateAsync(...)**:<br/>*stage*: TODO<br/>*stageThrough*: TODO<br/>*resOpt*: The resolve options.|Resolve the references and validate if all documents are ready.|Task\<CdmValidationStep>|
|**CalculateEntityGraphAsync(...):**<br/>*currManifest*: The manifest (and any sub-manifests it contains) that we want to calculate relationships for.|Calculates the entity to entity relationships for all the entities present in the manifest and its sub-manifests.|Task|
|**FetchIncomingRelationships(...):**<br/>*entity*: The entity that we want to get relationships for.|Returns a list of relationships where the input entity is the incoming entity.|List\<CdmE2ERelationship>|
|**FetchOutgoingRelationships(...):**<br/>*entity*: The entity that we want to get relationships for.|Returns a list of relationships where the input entity is the outgoing entity.|List\<CdmE2ERelationship>|

### Data Partition (CdmDataPartitionDefinition extends CdmObjectDefinitionBase, CdmFileStatus)

A data partition is an object pointing to a location of entity-related data.

#### Properties
|Name|Description|
|---|---|
|Name|The partition's name.|
|Location|The partition's location.|
|Inferred|A boolean denoting whether the partition was created from a data partition pattern.|
|Arguments|The list of key-value pairs to give names for the replacement values from the regex.|
|SpecializedSchema|The path for the specialized schema to use specifically for the partitions generated (e.g. *CSV*).|
|Description|The partition's description.|
|RefreshTime?|The partition's refresh time.|

### Data Partition Pattern (CdmDataPartitionPatternDefinition extends CdmObjectDefinitionBase, CdmFileStatus)

A data partition pattern is a concept that provides a way of selecting/generating a set of partitions based on requirements specified as a regular expression.

#### Properties
|Name|Description|
|---|---|
|Name|The partition pattern's name.|
|RootLocation|The starting location's corpus path for searching inferred data partitions.|
|RegularExpression|The regular expression string to use for searching partitions.|
|Parameters|The names for replacement values from the regular expression.|
|SpecializedSchema|The corpus path for the specialized schema to use for matched pattern partitions (e.g. *CSV*).|

### Data Type (CdmDataTypeDefinition extends CdmObjectDefinitionBase)

A data type provides the ability to assign different data types to attributes, such as string, boolean, etc.

#### Properties
|Name|Description|
|---|---|
|DataTypeName|The data type's name.|
|ExtendsDataType|The data type extended by this data type.|

### Document  (CdmDocumentDefinition extends CdmObjectSimple, CdmContainerDefinition)

A document enables the OM to have a persisted state. Every document can contain different CDM definitions, such as entities, data partitions, or attributes.

#### Properties
|Name|Description|
|---|---|
|Definitions|The document's definitions - can be any object that implements *CdmObjectDefinition*.|
|Folder|The document's folder. This property will eventually be replaced by *CdmObject*'s *Owner* property.|
|Imports|The list of corpus paths/monikers that denote the CDM objects that need to be imported in order to use the document.|
|Name|The document's name.|
|Schema|The schema link that points to a validating schema.|
|JsonSchemaSemanticVersion|Identifies the version of the OM that supports this file shape.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**AddDefinition\<T>(...):**<br/>*ofType*: The type of the object to create. <br/>*name*: The name of the object to create.|Adds a definition of an object of the given type and name (after creating it) to the document and returns back the newly created object. |T|
|**AddImport(...):**<br />*corpusPath*: The corpus path.<br/>*moniker*: The nickname used for imports to specify which document to import in the case of duplicate symbols (e.g. we might have multiple Account documents, but by specifying a moniker 'base_Account', we can pinpoint the exact document).|Creates an import object from the corpus path and moniker and adds it to the document.|void|
|**RefreshAsync(...):**<br />*resOpt*: The resolution options.|Updates the indexes in the document. The method is supposed to be called after modifying the objects in the document.|Task\<bool>|
|**SaveAsAsync(...):**<br />*newName*: The new document's name.<br/>*saveReferenced [optional]*: A boolean that denotes whether we want to save all the references files (schema definition documents that are linked from the source document that have been modified) as well since the manifest can reference different entity documents. The default value is false.<br/>*options [optional]*: The copy options.|Saves the document back through the adapter in the requested format. The format is specified via the document name/extension based on conventions: '.model.json' for the backwards-compatible model, 'manifest.cdm.json' for manifest, '.folio.cdm.json' for folio, and '.cdm.json' for CDM definitions. Returns false on any failure.|Task\<bool>|

### E2E Relationship (CdmE2ERelationship extends CdmObjectDefinitionBase)

An E2E relationship is a relationship between two entities' attributes.

#### Properties
|Name|Description|
|---|---|
|Name|The relationship's name.|
|FromEntity|The entity the relationship is pointing from.|
|FromEntityAttribute|The entity attribute the relationship is pointing from.|
|ToEntity|The entity the relationship is pointing to.|
|ToEntityAttribute|The entity attribute the relationship is pointing to.|

### Entity Attribute (CdmEntityAttributeDefinition extends CdmAttribute)

An entity attribute is an attribute that also points to an entity (see *CdmEntityReference*).

#### Properties
|Name|Description|
|---|---|
|Entity|The entity attribute's entity reference.|

### Entity Declaration (CdmEntityDeclarationDefinition extends CdmObjectDefinition, CdmFileStatus)

An entity declaration provides a simple functionality that is extended by a local entity declaration (see *CdmLocalEntityDeclarationDefinition*) and a reference entity declaration (see *CdmReferencedEntityDeclarationDefinition*).

#### Properties
|Name|Description|
|---|---|
|EntityName|The entity's name.|

### Entity (CdmEntityDefinition extends CdmObjectDefinitionBase, CdmReferencesEntities)

An entity is the basic building block of the OM. It provides a concrete placeholder for a user to attach certain information to a concept. It is a collection of attributes that creates some semantic meaning of why these attributes exist together. Since entities can inherit from other entities, it is possible for entities to represent a hierarchical structure. The hierarchical structure can be removed from the entities by resolving them.

#### Properties
|Name|Description|
|---|---|
|AttributeContext|The entity's attribute context (see *AttributeContext*).|
|CdmSchemas|The list of CDM entities that the entity "contains" or implements (a set of contracts or interfaces).|
|Description|The entity's description.|
|DisplayName|The entity's display name.|
|EntityName|The entity's name.|
|ExtendsEntity|The entity extended by this entity.|
|Attributes|The list of attributes for this entity.|
|SourceName|The entity's source name - the original entity name from another source system (e.g. *Dynamics*).|
|Version|The entity's version.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**CreateResolvedEntityAsync(...):**<br />*resOpt*: The resolve options.<br/>*newEntName*: The new entity name.<br/>*folder [optional]*: The folder that will be used as a target corpus path. If not specified, in-document folder (a property on the entity) is used.<br/>*newDocName [optional]*: The new document name.|Creates a resolved copy of the entity.|Task\<CdmEntityDefinition>|
|**GetProperty(...):**<br />*propertyName*: The property name.|Returns the value directly assigned to the property name (ignores values from traits).|dynamic|

### File Status (CdmFileStatus extends CdmObject)

A file status describes concepts based on the status of a file, such as data partitions since they reside in files (see *CdmDataPartitionDefinition*).

#### Properties
|Name|Description|
|---|---|
|LastFileStatusCheckTime?|The last time the modified time was checked for the file.|
|LastFileModifiedTime?|The last time the file was modified according to the OM.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and any children with the current time. |Task|
|**ReportMostRecentTimeAsync(...):**<br />*childTime (DateTimeOffset) [optional]*: The biggest child time. This parameter will get updated as a result of the function.|Reports the most recent modified time of the object (or children objects) to the parent object. Also modifies the childTime parameter with the biggest child time. |Task|

### Folder (CdmFolderDefinition extends CdmObjectDefinitionBase, CdmContainerDefinition)

A folder  provides a hierarchical structure of the OM for organizing documents. Folders can contain other folders or documents.

#### Properties
|Name|Description|
|---|---|
|Schema|The schema link that points to a validating schema.|
|JsonSchemaSemanticVersion|Identifies the version of the OM that supports the file shape.|
|LastModifiedTime|An ISO date-time-offset value to indicate the last time the folder's content was modified and persisted.|
|Name|The name of the folder.|
|Imports|The list of imports (see *Imports*).|
|FolderPath|The corpus path for the folder.|
|ChildFolders|The direct children for the directory folder.|
|Documents|The child documents for the directory folder.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**AddChildFolder(...):**<br/>*name*: The name of the folder.|Adds a child folder to the current folder and returns the newly added folder.|CdmFolderDefinition|
|**AddDocument(...):**<br />*name*: The name of the document.<br/>*doc*: The document to add.|Adds a child document to the current folder and returns the newly created document.|CdmDocumentDefinition|
|**RemoveDocument(...):**<br/>*name*: The name of the document.|Removes a document with the specified name from the folder.|void|
|**FetchChildFolderFromPathAsync(...):**<br />*path*: The corpus path.<br/>*makeFolder [optional]*: The boolean that denotes whether to create a folder if it doesn't exist. The default value is false.<br/>|Retrieves the child folder from the specified corpus path.	|Task\<CdmFolderDefinition>|
|**FetchDocumentFromFolderPathAsync(...):**<br/>*objectPath*: The folder path.<br/>*adapter*: The storage adapter where the folder can be found.<br/>*forceReload [optional]*: The boolean that denotes whether to reload the object from file and replace the current object with it. The default value is false.|Retrieves the document from the specified folder path.|Task\<CdmDocumentDefinition>|

### Import (CdmImport extends CdmObjectSimple)

An import is used by documents to provide files/documents that need to be imported first.

#### Properties
|Name|Description|
|---|---|
|CorpusPath|The import's corpus path.|
|Moniker|A nickname used for imports to specify which document to import in the case of duplicate symbols (e.g. we might have multiple Account documents, but by specifying a moniker 'base_Account', we can pinpoint the exact document).|
|ResolvedDocument|The document that has been resolved for this import.|

### Local Entity Declaration (CdmLocalEntityDeclarationDefinition extends CdmObjectDefinitionBase, CdmEntityDeclarationDefinition)

A local entity declaration is a declaration for an entity that resides locally and has associated data partitions.

#### Properties
|Name|Description|
|---|---|
|DataPartitions|The list of data partitions for the entity (see *Data Partition*).|
|DataPartitionPatterns|The list of data partition patterns for the entity (see *Data Partition Pattern*).|

### Manifest Declaration (CdmManifestDeclarationDefinition extends CdmObjectDefinitionBase, CdmFileStatus)

A manifest declaration is a declaration for the CDM manifest format.

#### Properties
|Name|Description|
|---|---|
|ManifestName|The manifest's name.|
|Definition|The corpus path to the definition of the sub-folder.|

### Manifest (CdmManifestDefinition extends CdmDocumentDefinition, CdmObjectDefinition, CdmFileStatus)

A manifest is a top-level document with the new extension '.manifest.cdm.json'. A manifest can reference different documents (e.g. reference documents with the extension '.cdm.json' that contain entities).

#### Properties
|Name|Description|
|---|---|
|ManifestName|The manifest's name.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**PopulateManifestRelationshipsAsync(...):**<br/>*option*: TODO|Populates the relationships that the entities in the current manifest are involved in. This function is used to pre-calculate relationships that lead to optimizations during the resolution process.|Task|
|**CreateResolvedManifestAsync(...):**<br />*newManifestName*: The new manifest name. <br/>*newEntityDocumentNameFormat*:  Specifies a pattern to use when creating documents for resolved entities. The default is "\{f}resolved/\{n}.cdm.json" to avoid a document name conflict with documents in the same folder as the manifest.<br/>|Creates a resolved copy of the manifest. Every instance of the string \{n} from the argument is replaced with the entity name from the source manifest. Every instance of the string \{f} is replaced with the folder path from the source manifest to the source entity (if there is one that is possible as a relative location, else nothing). A manifest with all the entities resolved is returned.|Task\<CdmManifestDefinition>

### CdmObject

This is the base interface for all other CDM interfaces.

#### Properties
|Name|Description|
|---|---|
|Id|The object's ID.|
|Ctx|The object's corpus context.|
|InDocument|The declaration document of the object.|
|AtCorpusPath|The object's declared corpus path.|
|ObjectType|The object's type.|
|Owner|The object that owns or contains this object.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**FetchObjectDefinition\<T>(...):**<br />*resOpt [optional]*: The resolve options.|Returns the resolved object reference.|T, where T : CdmObjectDefinition|
|**FetchObjectDefinitionName():**|Retrieves the name of the object if this is an object definition, or the name of the referenced object if this is an object reference.|string|
|**IsDerivedFrom(...):**<br />*baseDef*: The base definition name.<br />*resOpt*: The resolve options.|Returns true if the object (or the referenced object) is an extension of the specified symbol name in some way.|bool|

### CdmObjectDefinition extends CdmObject

This is the base interface for all CDM object definitions.

#### Methods
|Name|Description|Return type|
|---|---|---|
|**AddExhibitedTrait(...):**<br />*traitDef*: The trait definition, either a string representing the name or a CdmTraitReference object.<br/>*implicitRef [optional]*: The boolean that denotes whether the trait is an implicit trait. It is used only if the name is provided as a trait definition. The default value is false.|Adds the specified trait definition to the list of exhibited traits. Returns the added trait.|CdmTraitReference|
|**RemoveExhibitedTrait(...):**<br />*traitDef*: The trait definition, either a string representing the name or a CdmTraitReference object.<br />*onlyFromProperty [optional]*: TODO|Removes the trait definition from the exhibited trait list.|void|
|**GetName():**|All object definitions have some kind of name, so this method returns the name independent of the name from the name property.|string|

### Parameter (CdmParameterDefinition extends CdmObjectDefinitionBase)

A parameter provides the ability to specify parameters that a trait should contain. By providing a name, default values, and supported data types, trait references become restricted by which arguments they can contain. Parameters are defined for traits in the *CDM.SchemaDocuments* repository.

#### Properties
|Name|Description|
|---|---|
|Name|The parameter's name.|
|DefaultValue |The parameter's default value.|
|Required|Denotes whether the parameter is required.|
|Direction|The parameter direction.|
|DataTypeRef|The parameter's data type reference.|

### Purpose (CdmPurposeDefinition extends CdmObjectDefinitionBase)

A purpose provides an attribute of what it does for an entity (e.g. *SortedBy*, *NamedBy*). 

#### Properties
|Name|Description|
|---|---|
|ExtendsPurpose|The reference to the purpose extended by this purpose.|
|PurposeName|The purpose's name.|

### Reference Entity Declaration (CdmReferencedEntityDeclarationDefinition extends CdmObjectDefinitionBase, CdmEntityDeclarationDefinition)

A reference entity declaration is a declaration for an entity that resides in a remote location.

#### Properties
|Name|Description|
|---|---|

### Trait (CdmTraitDefinition extends CdmObjectDefinitionBase)

A trait helps express semantic meaning and structural guidance. Traits are essentially a metadata's metadata. Traits can extend other traits and have a format that is easy to understand and follow. (E.g. The trait *is.partition.format.CSV* describes a data partition in CSV format and has parameters that can provide additional information, such as which character to use as a delimiter). 

#### Properties
|Name|Description|
|---|---|
|AssociatedProperties|The properties for the entity or attribute that the trait contributes to (using trait2propertyMap).|
|Elevated?|Denotes whether a trait is elevated (e.g. if an attribute has an elevated trait, then that trait should also be applied to the outer entity).|
|ExtendsTrait|The trait extended by this trait.|
|Parameters|The trait's parameters.|
|ModifiesAttributes?|Denotes whether a trait modifies attributes.|
|TraitName|The trait's name.|
|Ugly?|Denotes whether the trait is user facing (false if it is user facing, true otherwise).|

### Type Attribute (CdmTypeAttributeDefinition extends CdmAttribute)

A type attribute defines data type attributes along with supported functionality, such as custom default values and descriptions. Model.JSON attributes are converted into CDM type attributes.

#### Properties
|Name|Description|
|---|---|
|AttributeContext|The attribute context of the attribute.|
|DataFormat|The type attribute's data format, in a string format derived from traits (string, int, etc).|
|DataType|The type attribute's data type, a CDM reference object (see *CdmDataTypeReference*).|
|DefaultValue|The type attribute's default value.|
|Description|The type attribute's description.|
|DisplayName|The type attribute's display name.|
|IsNullable?|Denotes whether the type attribute can be null or not.|
|IsPrimaryKey?|Denotes whether the type attribute is the primary key.|
|IsReadOnly?|Denotes whether the type attribute is read only.|
|MaximumLength?|The type attribute's maximum length.|
|MaximumValue|The type attribute's maximum value (for data types that this can apply to, like integers).|
|MinimumValue|The type attribute's minimum value (for data types that this can apply to, like integers).|
|SourceName|The type attribute's source name.|
|SourceOrdering?|Denotes the order attributes exist in some underlying source system.|
|ValueConstrainedToList?|Denotes whether the type attribute's value is constrained to a list. The values can only be from enums.|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**GetProperty(...):**<br/>*propertyName*: The property name.|Returns the value directly assigned to a property (ignores value from traits).	|dynamic|

## CDM References

All reference objects extend from the *CdmObjectReference* interface. Many references are just empty interfaces extending from *CdmObjectReferenceBase*. These references are *CdmAttributeContextReference, CdmAttributeReference, CdmDataTypeReference, CdmEntityReference,* and *CdmPurposeReference*.

### CdmObjectReference extends CdmObject

This is the base interface for all CDM object references.

|Name|Description|Return type|
|---|---|---|
|**AddAppliedTrait(...):**<br />*traitDef*: The trait definition, either a string representing the name or a CdmTraitReference object.<br/>*implicitRef [optional]*: The boolean that denotes whether the trait is an implicit trait. It is used only if the name is provided as a trait definition. The default value is false.|Adds the specified trait definition to the list of applied traits. Returns the added trait.|CdmTraitReference|
|**RemoveAppliedTrait(...):**<br />*traitDef*: The trait definition, either a string representing the name or a CdmTraitReference object.<br/>*onlyFromProperty [optional]*: TODO |Removes the trait definition from the list of applied traits. |void|

### CdmTraitReference extends CdmObjectReferenceBase

|Name|Description|Return type|
|---|---|---|
|**AddArgument(...):**<br />*name*: The name of the argument.<br/>*value*: The value of the argument.|Adds an argument with the specified name and value to the Arguments list. Arguments have to match the parameters format specified in the schema documents.|CdmArgumentDefinition|
|**FetchArgumentValue(...):**<br />*name*: The name of the argument.|Retrieves the value for the specified argument name from the arguments list.|dynamic|
|**UpdateArgumentValue(...):**<br />*name*: The name of the argument.<br/>*value*: The value of the argument.|Sets the specified value to the argument with the specified name.|void|

## Storage

TODO: Description

### StorageManager 

TODO: Description

#### Properties
|Name|Description|
|---|---|

#### Methods
|Name|Description|Return type|
|---|---|---| 
|**Mount(...):**<br/>*nameSpace*: The namespace.<br/>*adapter*: The storage adapter.|Mounts a namespace to the specified adapter.|void|
|**Unmount(...)**<br/>*nameSpace*: The namespace.|Unmounts a namespace. Returns true if the unmount is successful, false otherwise.|boolean|
|**SetAdapter(...):**<br/>*nameSpace*: The namespace.<br/>*adapter*: The storage adapter to set.|Allows the replacement of a storage adapter with another one for testing, leaving folders intact.|void|
|**FetchAdapter(...):**<br/>*nameSpace*: The namespace.|Retrieves the adapter for the specified namespace.|StorageAdapter|
|**SplitNamespacePath(...):**<br/>*objectPath*: The corpus path.|Splits the corpus path into the namespace and object path. Returns the namespace and the object path.|Tuple\<string, string>|
|**FetchRootFolder(...):**<br/>*nameSpace*: The namespace.|Given the namespace of a registered stoarge adapter, returns the root folder containing the sub-folders and documents.|CdmFolderDefinition|
|**AdapterPathToCorpusPath(...):**<br/>*adapterPath*: The path.|Takes the specified storage adapter domain path, figures out the right adapter to use, and then returns a corpus path.|string|
|**CorpusPathToAdapterPath(...):**<br/>*adapterPath*: The path.|Takes the specified corpus path, figures out the right adapter to use, and then returns a storage adapter domain path.|string|
|**CreateAbsoluteCorpusPath(...):**<br/>*objectPath*: The corpus path.<br/>*obj [optional]*: TODO|Takes the specified corpus path (relative or absolute) and creates a valid absolute path with the namespace. Returns the created path.|string|
|**CreateRelativeCorpusPath(...):**<br/>*objectPath*: The corpus path.<br/>*relativeTo [optional]*: The object that the path should be made relative to.|Takes the specified corpus path (relative or absolute) and creates a valid relative corpus path with the namespace. Returns the created path.|string|

### StorageAdapter

TODO: Description

#### Properties
|Name|Description|
|---|---|

#### Methods
|Name|Description|Return type|
|---|---|---| 
|**CanRead():**|Returns true if the adapter can read data, false otherwise.|boolean|
|**CanWrite():**|Returns true if the adapter can write data to its source, false otherwise.|boolean|
|**ReadAsync(...):**<br/>*corpusPath*: The corpus path.|Returns the object data that exists at the specified path as a string.|Task\<string>|
|**WriteAsync(...):**<br/>*corpusPath*: The corpus path.<br/>*data*: The object data.|Writes the object data to the specified document path.|Task|
|**CreateAdapterPath(...):**<br/>*corpusPath*: The corpus path.|Converts the specified corpus path into a path in the domain of this adapter. Returns the adapter path.|string|
|**CreateCorpusPath(...):**<br/>*adapterPath*: The adapter path.|Converts the specified path in the domain of this adapter into a corpus path. Returns the corpus path.|string|
|**ClearCache():**|Empties the cache of files and folders if the storage adapter uses a cache.|void|
|**ComputeLastModifiedTimeAsync(...):**<br/>*adapterPath*: The adapter path to a document.|Returns the last modified time of the specified document.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(...):**<br/>*folderCorpusPath*: The corpus path to a folder.|Returns a list of corpus paths to all files and folders at or under the specified corpus path to a folder.|Task\<List\<string>>|

### NetworkAdapter extends IDisposable

TODO: Description 

#### Properties
|Name|Description|
|---|---|

#### Methods
|Name|Description|Return type|
|---|---|---| 
|**ExecuteRequest(...):**<br/>*httpRequest*: The HTTP request to execute.|Executes an HTTP request and returns the response of the request.|Task\<CdmHttpResponse>|

### LocalAdapter extends StorageAdapter

TODO: Description 

#### Properties
|Name|Description|
|---|---|

#### Methods
|Name|Description|Return type|
|---|---|---|
|**CanRead():**|Returns true, since the LocalAdapter can read data.|boolean|
|**CanWrite():**|Returns true, since the LocalAdapter can write data to its source.|boolean|
|**ReadAsync(...):**<br/>*corpusPath*: The corpus path.|See *StorageAdapter.ReadAsync(...)*.|Task\<string>|
|**WriteAsync(...):**<br/>*corpusPath*: The corpus path.<br/>*data*: The object data.|See *StorageAdapter.WriteAsync(...)*.|Task|
|**CreateAdapterPath(...):**<br/>*corpusPath*: The corpus path.|See *StorageAdapter.CreateAdapterPath(...)*.|string|
|**CreateCorpusPath(...):**<br/>*adapterPath*: The adapter path.|See *StorageAdapter.CreateCorpusPath(...)*.|string|
|**ClearCache():**|See *StorageAdapter.ClearCache()*.|void|
|**ComputeLastModifiedTimeAsync(...):**<br/>*adapterPath*: The adapter path to a document.|See *StorageAdapter.ComputeLastModifiedTimeAsync(...)*.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(...):**<br/>*folderCorpusPath*: The corpus path to a folder.|See *StorageAdapter.FetchAllFilesAsync(...)*.|Task\<List\<string>>|

### GithubAdapter extends NetworkAdapter, StorageAdapter

TODO: Description 

#### Properties
|Name|Description|
|---|---|

#### Methods
|Name|Description|Return type|
|---|---|---| 
|**CanRead():**|Returns true, since the GithubAdapter can read data.|boolean|
|**CanWrite():**|Returns false, since the GithubAdapter cannot write data to its source.|boolean|
|**ReadAsync(...):**<br/>*corpusPath*: The corpus path.|See *StorageAdapter.ReadAsync(...)*.|Task\<string>|
|**ClearCache():**|See *StorageAdapter.ClearCache()*.|void|
|**ComputeLastModifiedTimeAsync(...):**<br/>*adapterPath*: The adapter path to a document.|See *StorageAdapter.ComputeLastModifiedTimeAsync(...)*.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(...):**<br/>*folderCorpusPath*: The corpus path to a folder.|See *StorageAdapter.FetchAllFilesAsync(...)*.|Task\<List\<string>>|

### ADLSAdapter extends NetworkAdapter, StorageAdapter

TODO: Description 

#### Properties
|Name|Description|
|---|---|

#### Methods
|Name|Description|Return type|
|---|---|---| 
|**CanRead():**|Returns true, since the ADLSAdapter can read data.|boolean|
|**CanWrite():**|Returns true, since the ADLSAdapter can write data to its source.|boolean|
|**ReadAsync(...):**<br/>*corpusPath*: The corpus path.|See *StorageAdapter.ReadAsync(...)*.|Task\<string>|
|**WriteAsync(...):**<br/>*corpusPath*: The corpus path.<br/>*data*: The object data.|See *StorageAdapter.WriteAsync(...)*.|Task|
|**CreateAdapterPath(...):**<br/>*corpusPath*: The corpus path.|See *StorageAdapter.CreateAdapterPath(...)*.|string|
|**CreateCorpusPath(...):**<br/>*adapterPath*: The adapter path.|See *StorageAdapter.CreateCorpusPath(...)*.|string|
|**ClearCache():**|See *StorageAdapter.ClearCache()*.|void|
|**ComputeLastModifiedTimeAsync(...):**<br/>*adapterPath*: The adapter path to a document.|See *StorageAdapter.ComputeLastModifiedTimeAsync(...)*.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(...):**<br/>*folderCorpusPath*: The corpus path to a folder.|See *StorageAdapter.FetchAllFilesAsync(...)*.|Task\<List\<string>>|

### RemoteAdapter extends NetworkAdapter, StorageAdapter 

TODO: Description 

#### Properties
|Name|Description|
|---|---|

#### Methods
|Name|Description|Return type|
|---|---|---| 
|**CanRead():**|Returns true, since the RemoteAdapter can read data.|boolean|
|**CanWrite():**|Returns false, since the RemoteAdapter cannot write data to its source.|boolean|
|**ReadAsync(...):**<br/>*corpusPath*: The corpus path.|See *StorageAdapter.ReadAsync(...)*.|Task\<string>|
|**CreateAdapterPath(...):**<br/>*corpusPath*: The corpus path.|See *StorageAdapter.CreateAdapterPath(...)*.|string|
|**CreateCorpusPath(...):**<br/>*adapterPath*: The adapter path.|See *StorageAdapter.CreateCorpusPath(...)*.|string|
|**ClearCache():**|See *StorageAdapter.ClearCache()*.|void|
|**ComputeLastModifiedTimeAsync(...):**<br/>*adapterPath*: The adapter path to a document.|See *StorageAdapter.ComputeLastModifiedTimeAsync(...)*.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(...):**<br/>*folderCorpusPath*: The corpus path to a folder.|See *StorageAdapter.FetchAllFilesAsync(...)*.|Task\<List\<string>>|

## Utilities
TODO: Description

### Resolve Options

#### Properties
|Name|Description|
|---|---|
|WrtDoc *(getters/setter)*|The document to use as a point of reference when resolving relative paths and symbol names.|
|Directives |A set of string flags that direct how attribute resolving traits should behave (e.g. *normalized*, *structured*, etc).|
|RelationshipDepth? |Tracks the number of entity attributes that have been traversed when collecting resolved traits or attributes. Prevents run away loops.|
|SaveResolutionOnCopy |A boolean that denotes whether to save references upon copy. When references get copied, use previous resolution results if available. Used with the copy method.|
|SymbolRefSet |The set of symbols that the current chain of resolution depends upon. Used with importPriority to find which docs and versions of symbols to use.
|LocalizeReferencesFor |Forces symbolic references to be re-written to be the precisely located reference based on the wrtDoc.|
|IndexingDoc |The document currently being indexed.|
|FromMoniker |The moniker that was found on the reference.

### Copy Options

#### Properties
|Name|Description|
|---|---|
|StringRefs? |A boolean that denotes whether to turn simple named string object references into objects with a relative path.|
|RemoveSingleRowLocalizedTableTraits?  |A boolean that, if true, keeps us from serializing the displayText and descriptions traits as stand-alone traits with just one record in them to make the JSON look better.|
