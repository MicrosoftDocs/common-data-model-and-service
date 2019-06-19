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

|Function name|Function description|Function return type|
|---|---|---|
|**ToData<T, U>(...):**<br />instance (T): The CDM object instance.<br/>resOpt: The resolve options.<br/>copyOpt: The copy options.<br/>persistenceTypeName: The persistence type name which needs to be called.|Converts the object from a CDM object type T to the persistent type U.|U|
