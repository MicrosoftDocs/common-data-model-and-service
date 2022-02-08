---
title: overview of ClinicalReasoningCore - Common Data Model | Microsoft Docs
description: ClinicalReasoningCore is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of ClinicalReasoningCore

CDM standard entities for 'ClinicalReasoningCore'  

## Entities

|Name|Description|
|---|---|
|[DataReqCodeFilterValueCodeableConcept](DataReqCodeFilterValueCodeableConcept.md)|The Codeable Concepts for the code filter.|
|[DataRequirementCodeFilter](DataRequirementCodeFilter.md)|Code filters specify additional constraints on the data, specifying the value set of interest for a particular element of the data.|
|[DataRequirementCodeFilterValueCode](DataRequirementCodeFilterValueCode.md)|The codes for the code filter.|
|[DataRequirementCodeFilterValueCoding](DataRequirementCodeFilterValueCoding.md)|The Coding for the code filter.|
|[DataRequirementDateFilter](DataRequirementDateFilter.md)|Date filters specify additional constraints on the data in terms of the applicable date range for specific elements.|
|[DataRequirementMustSupport](DataRequirementMustSupport.md)|Indicates that specific elements of the type are referenced by the knowledge module and must be supported by the consumer in order to obtain an effective evaluation.|
|[DataRequirementProfile](DataRequirementProfile.md)|If specified, this indicates a profile that the input data must conform to, or that the output data will conform to.|
