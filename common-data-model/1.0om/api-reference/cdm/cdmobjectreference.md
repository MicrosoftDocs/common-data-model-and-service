---
title: CdmObject Reference | Microsoft Docs
description: API reference for CdmObjectReference.
author: miroslavplese

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 10/18/2019
ms.author: miplese
---

# CdmObject Reference

This is the base interface for all Common Data Model object references. It's extended by *CdmObjectReferenceBase* (in C#, Java, and TypeScript), *CdmAttributeContextReference, CdmAttributeGroupReference, CdmAttributeReference, CdmDataTypeReference, CdmEntityReference*, and *CdmPurposeReference*.

```csharp
public interface CdmObjectReference extends CdmObject
```
*This interface is substituted with a regular class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|Optional|bool|A boolean that denotes whether the reference is optional or not. This indicates the SDK to not error out in case the definition to which this reference points at can't be resolved.|
|AppliedTraits|[CdmTraitCollection](traitcollection.md)|The collection of applied traits.|
|ExplicitReference|[CdmObjectDefinition](cdmobjectdefinition.md)|The object definition that this reference is referencing.|
|NamedReference|string|The string used to simply reference different concepts just by name without having to include any other extra data.|
|SimpleNamedReference|bool|A boolean that denotes whether the reference is simple named or not. If true, it'll use a named reference, otherwise it'll use an explicit reference.|
