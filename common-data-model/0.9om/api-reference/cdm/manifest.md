---
title: Manifest - Common Data Model | Microsoft Docs
description: Reference for CdmManifestDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Manifest

A manifest is a top-level document with the extension '.manifest.cdm.json'. A manifest can reference different documents (e.g. reference documents with the extension '.cdm.json' that contain entities).

```
public class CdmManifestDefinition extends CdmDocumentDefinition, CdmObjectDefinition, CdmFileStatus
```

## Constructors
|Name|Description|
|---|---|
|**CdmManifestDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The manifest's name.<br/>|Initializes a new instance of the [CdmManifestDefinition](manifest.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|ManifestName|string|The manifest's name.|
|Explanation|string|The manifest's explanation.|
|ExhibitsTraits|[CdmTraitCollection](traitcollection.md)|The collection of trait references that provide detailed meanings, semantics, usage parameters, or other application specific metadata.|
|SubManifests|[CdmCollection](collection.md)\<[CdmManifestDeclarationDefinition](manifestdeclaration.md)>|The collection of sub-manifests.|
|Entities|[CdmEntityCollection](entitycollection.md)|The entities declared in the manifest (can only be [LocalEntityDeclaration](localentitydeclaration.md) or [ReferencedEntityDeclaration](referencedentitydeclaration.md)).|
|Relationships|[CdmCollection](collection.md)\<[CdmE2ERelationship](e2erelationship.md)>|The collection of references that exist where either the from entity or the to entity is defined in this folder.|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the OM.|
|LastChildFileModifiedTime|DateTimeOffset?|The greatest last time reported by any of the chlidren objects about their file status check times.|


## Methods
|Name|Description|Return Type|
|---|---|---|
|**PopulateManifestRelationshipsAsync([CdmRelationshipDiscoveryStyle](relationshipdiscoverystyle.md))**<br/>*option [optional]*: The type of relationships we want populated in the manifest.|Populates the relationships that the entities in the current manifest are involved in. This function is used to pre-calculate relationships that lead to optimizations during the resolution process.|Task|
|**CreateResolvedManifestAsync(string, string)**<br />*newManifestName*: The corpus path to the name of the new manifest. <br/>*newEntityDocumentNameFormat*:  Specifies a pattern to use when creating documents for resolved entities. The default is "\{f}resolved/\{n}.cdm.json" to avoid a document name conflict with documents in the same folder as the manifest.<br/>|Creates a resolved copy of the manifest. Every instance of the string \{n} from the argument is replaced with the entity name from the source manifest. Every instance of the string \{f} is replaced with the folder path from the source manifest to the source entity (if there is one that is possible as a relative location, else nothing). A manifest with all the entities resolved is returned.|Task\<[CdmManifestDefinition](manifest.md)>|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|

