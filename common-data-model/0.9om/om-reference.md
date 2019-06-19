---
title: OM Reference - Common Data Model | Microsoft Docs
description: OM reference for 0.9 OM.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 6/18/2019
ms.author: nebanfic
---

# OM Reference

Hierarchical structure of the CDM OM:

![OM Hierarchy](omhierarchy.png)

The CDM object model provides two types of classes - definition classes and reference classes. Since the OM is heavily interconnected and different concepts have different interactions among each other, in order to be able to easily reference different concepts without actually encapsulating them, the OM introduces the reference classes. Every reference class has its own corresponding definition class, and they are closely correlated. 

## Definitions

### Corpus (ICdmCorpusDef extends ICdmFolderDef)

Corpus is a top-level folder which provides the most important basic functionality to deal with the object model. Since there will usually be only one corpus when dealing with the OM, the most important APIs can be found by looking at ICdmCorpusDef in the API Reference section).

|Property|Description|
|---|---|
|DefaultNamespace (getter/setter)|The namespace that will be used when one is not explicitly provided.|