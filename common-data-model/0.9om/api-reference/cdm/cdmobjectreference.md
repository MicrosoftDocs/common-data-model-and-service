---
title: CdmObject Reference | Microsoft Docs
description: API reference for CdmObjectReference.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# CdmObject Reference

This is the base for all Common Data Model object references. It is extended by *CdmObjectReferenceBase* (in C# and Java), *CdmAttributeContextReference, CdmAttributeGroupReference, CdmAttributeReference, CdmDataTypeReference, CdmEntityReference*, and *CdmPurposeReference*.

```
public interface CdmObjectReference extends CdmObject
```
*CdmObjectReference is a class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|AppliedTraits|[CdmTraitCollection](traitcollection.md)|The collection of applied traits.|
|ExplicitReference|[CdmObjectDefinition](cdmobjectdefinition.md)|The object definition that this reference is referencing.|
|NamedReference|string|The string used to simply reference different concepts just by name without having to include any other extra data.|
|SimpleNamedReference|bool|A boolean that denotes whether the reference is simple named or not. If true, it will use a named reference, otherwise it will use an explicit reference.|
