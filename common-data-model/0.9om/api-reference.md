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

|Method name|Method description|Method return type|
|---|---|---|
|**ToData<T, U>(...):**<br />*instance (T)*: The CDM object instance.<br/>*resOpt*: The resolve options.<br/>*copyOpt*: The copy options.<br/>*persistenceTypeName*: The persistence type name which needs to be called.|Converts the object from a CDM object type T to the persistent type U.|U|

# References

Please refer to the OM Reference section for information about the references in the OM. All reference objects extend from ICdmObjectRef, and this section will have a list of all references which implement some API.

## ICdmObjectRef extends ICdmObject

|Method name|Method description|Method return type|
|---|---|---|
|**AddAppliedTraits(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.<br/>*implicitRef [optional]*: The boolean that denotes is the trait is implicit trait, it is used only if the name is provided as a trait definition.|Adds a trait to the applied trait list. |ICdmTraitRef|
|**RemoveAppliedTrait(...):**<br />*traitDef*: The trait definition, either string representing the name or ICdmTraitRef object.|Adds a trait to the applied trait list. |ICdmTraitRef|
