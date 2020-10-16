---
title: Resolve Options | Microsoft Docs
description: API reference for ResolveOptions.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 08/20/2020
ms.author: jibyun
---

# Resolve Options

Resolve options are options to be used for resolution. If it's an optional argument to a method, it's safe to leave it null because default resolve options would just be created and used instead. 

```csharp
public class ResolveOptions
```

## Constructors
|Name|Description|
|---|---|
|**ResolveOptions()**|Initializes a new instance of the [ResolveOptions](resolveoptions.md) class.|
|**ResolveOptions([CdmDocumentDefinition](../cdm/document.md), AttributeResolutionDirectiveSet)**<br/>*cdmDocument*: The document to use as the point of reference when resolving relative paths and symbol names.<br/>*directives [optional]*: The set of string flags that direct how attribute-resolving traits should behave.|
|**ResolveOptions([CdmObject](../cdm/cdmobject.md), AttributeResolutionDirectiveSet)**<br/>*cdmObject*: The object to use to fetch the document that contains the owner of this object. The fetched document is then used as the point of reference when resolving relative paths and symbol names.<br/>*directives [optional]*: The set of string flags that direct how attribute resolving traits should behave.|Initializes a new instance of the [ResolveOptions](resolveoptions.md) class using the most common parameters.|

## Properties
|Name|Type|Description|
|---|---|---|
|WrtDoc|[CdmDocumentDefinition](../cdm/document.md)|The document to use as the point of reference when resolving relative paths and symbol names.|
|Directives|AttributeResolutionDirectiveSet|The set of string flags that direct how attribute resolving traits should behave (for example, *normalized*, *structured*, etc.).|
|ShallowValidation|bool|When enabled, errors regarding object references being unable to load or resolve are suppressed and logged as warnings instead. This resolve option is enabled through the *shallowValidation* parameter in [CdmCorpusDefinition.FetchObjectAsync(...)](../cdm/corpus.md#methods) and is used only during loading.<br/><br/>A use case for this resolve option is when loading a resolved schema without its referenced schemas being present. This may be acceptable behavior if you're not interested in *how* the schema was resolved (for example, where its attributes originated) and you're just concerned with reading the contents inside the resolved schema.<br/><br/>**Note:** By enabling shallow validation, you may be suppressing important errors about the validity of your schemas. Use caution when using this resolve option.|
|ImportsLoadStrategy|[ImportsLoadStrategy](../cdm/importsloadstrategy.md)|It instructs the object model when to load all the imports associated with the file being fetched and validates all the references in the documents in [CdmCorpusDefinition.FetchObjectAsync(...)](../cdm/corpus.md#methods). If no value is supplied, the imports and references are loaded when they are required during an operation. <br/><br/>This flag is especially useful when dealing with resolved entities since it will reduce the load time of the document.|
|ResolvedAttributeLimit|int?|The maximum number of resolved attributes allowed for an entity. The default limit is 4000 attributes. This limit is only checked when [CdmEntityDefinition.CreateResolvedEntityAsync(...)](../cdm/entity.md#methods) is called. If this limit is exceeded, resolution will fail, an error message will be logged, and *CreateResolvedEntityAsync(...)* will return null. If you wish to get rid of this limit, set this resolve option to null.
