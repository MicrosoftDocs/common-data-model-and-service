---
title: Referenced Entity Declaration - Common Data Model | Microsoft Docs
description: Reference for CdmReferencedEntityDeclarationDefinition .
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Referenced Entity Declaration

A referenced entity declaration is a declaration of an entity that resides in a remote location.

```
public class CdmReferencedEntityDeclarationDefinition extends CdmObjectDefinitionBase, CdmEntityDeclarationDefinition
```

## Constructors
|Name|Description|
|---|---|
|**CdmReferencedEntityDeclarationDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*entityName*: The entity's name.|Initializes a new instance of the [CdmReferencedEntityDeclarationDefinition](referencedentitydeclaration.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|EntityName|string|The entity's name.|
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

