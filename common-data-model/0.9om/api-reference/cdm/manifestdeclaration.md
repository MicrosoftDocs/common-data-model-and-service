---
title: Manifest Declaration - Common Data Model | Microsoft Docs
description: Reference for CdmManifestDeclarationDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Manifest Declaration

A manifest declaration is a declaration for the CDM manifest format.

```
public class CdmManifestDeclarationDefinition extends CdmObjectDefinitionBase, CdmFileStatus
```

## Constructors
|Name|Description|
|---|---|
|**CdmManifestDeclarationDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The name of the manifest declared.|Initializes a new instance of the [CdmManifestDeclarationDefinition](manifestdeclaration.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|ManifestName|string|The name of the manifest declared.|
|Definition|string|The corpus path to the definition of the sub-folder.|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the OM.|
|LastChildFileModifiedTime|DateTimeOffset?|The last time a child file was modified according to the OM.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

