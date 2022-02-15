---
title: overview of DiagnosticCore - Common Data Model | Microsoft Docs
description: DiagnosticCore is a folder that contains standard entities related to the Common Data Model.
author: matgos

ms.reviewer: deonhe
ms.topic: article
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of DiagnosticCore

CDM standard entities for 'DiagnosticCore'  

## Entities

|Name|Description|
|---|---|
|[BodySite](BodySite.md)|Record details about the anatomical location of a specimen or body part. This entity may be used when a coded concept does not provide the necessary detail needed for the use case.|
|[ObservationBasedOn](ObservationBasedOn.md)|A plan, proposal or order that is fulfilled in whole or in part by this event.|
|[ObservationCategory](ObservationCategory.md)|A code that classifies the general type of observation being made.|
|[ObservationCode](ObservationCode.md)|Describes what was observed.|
|[ObservationComponent](ObservationComponent.md)|Some observations have multiple component observations. These component observations are expressed as separate code value pairs that share the same attributes.|
|[ObservationComponentReferenceRange](ObservationComponentReferenceRange.md)|Guidance on how to interpret the value by comparison to a normal or recommended range.|
|[ObservationInterpretation](ObservationInterpretation.md)|The assessment made based on the result of the observation.|
|[ObservationMethod](ObservationMethod.md)|Indicates the mechanism used to perform the observation.|
|[ObservationPerformer](ObservationPerformer.md)|Who was responsible for asserting the observed value as "true".|
|[ObservationReferenceRange](ObservationReferenceRange.md)|Guidance on how to interpret the value by comparison to a normal or recommended range.|
|[ObservationReferenceRangeAppliesTo](ObservationReferenceRangeAppliesTo.md)|Codes to indicate the target population this reference range applies to. For example, a reference range may be based on the normal population or a particular sex or race.|
|[ObservationRelatedResource](ObservationRelatedResource.md)|A reference to another entity(usually another Observation) whose relationship is defined by the relationship type code.|
|[SpecimenContainer](SpecimenContainer.md)|The container holding the specimen. The recursive nature of containers; i.e. blood in tube in tray in rack is not addressed here.|
|[SpecimenParent](SpecimenParent.md)|Reference to the parent (source) specimen which is used when the specimen was either derived from or a component of another specimen.|
|[SpecimenProcessing](SpecimenProcessing.md)|Details concerning processing and processing steps for the specimen.|
|[SpecimenProcessingAdditive](SpecimenProcessingAdditive.md)|Material used in the processing step.|
|[SpecimenRequest](SpecimenRequest.md)|Details concerning a test or procedure request that required a specimen to be collected.|
