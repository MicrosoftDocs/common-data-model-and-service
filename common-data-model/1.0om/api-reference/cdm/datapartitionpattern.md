---
title: Data Partition Pattern | Microsoft Docs
description: API reference for CdmDataPartitionPatternDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Data Partition Pattern

A data partition pattern provides a way of selecting or generating a set of partitions based on the requirements specified as a regular expression.

```csharp
public class CdmDataPartitionPatternDefinition extends CdmObjectDefinitionBase, CdmFileStatus
```
*CdmDataPartitionPatternDefinition extends CdmObjectDefinition, CdmFileStatus in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmDataPartitionPatternDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The data partition pattern's name.|Initializes a new instance of the [CdmDataPartitionPatternDefinition](datapartitionpattern.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The data partition pattern's name.|
|RootLocation|string|The starting location's corpus path to use to search for inferred data partitions.|
|RegularExpression|string|The regular expression string to use to search for data partitions.|
|GlobPattern|string|The glob pattern string to use to search for data partitions. If a glob pattern and regular expression are both present, the glob pattern will be used instead. The following special characters are supported:<br/><table><thead><tr><th>Character</th><th>Explanation</th></tr></thead><tbody><tr><td>*</td><td>A single star matches zero or more of any character except path separators (/ or \\).</td></tr><tr><td>**</td><td>Two stars (globstar) matches zero or more directories or files.</td></tr><tr><td>?</td><td>A question mark matches any single character that isn't a path separator.</td></tr><tr><td>'/' or '\\'</td><td>Slash and backslash are interchangable, so a pattern that includes '\\' will match a '/' character and vice versa.</td></tr></tbody></table>
|Parameters|List\<string>|The names for the replacement values extracted from the regular expression.|
|SpecializedSchema|string|The corpus path of the specialized schema to use for the matched data partitions (for example, *CSV*).|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the object model.|
|LastChildFileModifiedTime|DateTimeOffset?|The greatest last time reported by any of the children objects about their file status check times. This property only exists because this class extends CdmFileStatus and will throw a *NotImplementedException* because a data partition pattern object doesn't contain any children.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

