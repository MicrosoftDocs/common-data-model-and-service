---
title: overview of MedicationCore - Common Data Model | Microsoft Docs
description: MedicationCore is a folder that contains standard entities related to the Common Data Model.
author: matgos

ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of MedicationCore

CDM standard entities for 'MedicationCore'  

## Entities

|Name|Description|
|---|---|
|[MedicalIdentifier](MedicalIdentifier.md)||
|[MedicationAdministrationDefinition](MedicationAdministrationDefinition.md)|A protocol, guideline, order set or other definition that was adhered to in whole or in part by this event.|
|[MedicationAdministrationDevice](MedicationAdministrationDevice.md)|The device used in administering the medication to the patient. For example, a particular infusion pump.|
|[MedicationAdministrationEventHistory](MedicationAdministrationEventHistory.md)|A summary of the events of interest that have occurred, such as when the administration was verified.|
|[MedicationAdministrationPartOf](MedicationAdministrationPartOf.md)|A larger event of which this particular event is a component or step.|
|[MedicationAdministrationPerformer](MedicationAdministrationPerformer.md)|The individual who was responsible for giving the medication to the patient.|
|[MedicationAdministrationReasonCode](MedicationAdministrationReasonCode.md)|A code indicating why the medication was given.|
|[MedicationAdministrationReasonNotGiven](MedicationAdministrationReasonNotGiven.md)|A code indicating why the administration was not performed.|
|[MedicationAdministrationReasonReference](MedicationAdministrationReasonReference.md)|Condition or observation that supports why the medication was administered.|
|[MedicationAdministrationSupportingInformation](MedicationAdministrationSupportingInformation.md)|Additional information (for example, patient height and weight) that supports the administration of the medication.|
|[MedicationCode](MedicationCode.md)||
|[MedicationForm](MedicationForm.md)|Describes the form of the item. Powder; tablets; capsule.|
|[MedicationImage](MedicationImage.md)|Photo(s) or graphic representation(s) of the medication.|
|[MedicationIngredient](MedicationIngredient.md)|Identifies a particular constituent of interest in the product.|
|[MedicationPackageBatch](MedicationPackageBatch.md)|Information about a group of medication produced or packaged from one production run.|
|[MedicationPackageContent](MedicationPackageContent.md)|A set of components that go to make up the described item.|
|[MedicationRequestBasedOn](MedicationRequestBasedOn.md)|A plan or request that is fulfilled in whole or in part by this medication request.|
|[MedicationRequestDefinition](MedicationRequestDefinition.md)|Protocol or definition followed by this request.|
|[MedicationRequestDetectedIssue](MedicationRequestDetectedIssue.md)|Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, duplicate therapy, dosage alert etc.|
|[MedicationRequestDosageInstruction](MedicationRequestDosageInstruction.md)|Indicates how the medication is to be used by the patient.|
|[MedicationRequestEventHistory](MedicationRequestEventHistory.md)|Links to Provenance records for past versions of this entity that identify key state transitions or updates that are likely to be relevant to user looking at the current version of the entity.|
|[MedicationRequestReasonCode](MedicationRequestReasonCode.md)|The reason or the indication for ordering the medication.|
|[MedicationRequestReasonReference](MedicationRequestReasonReference.md)|Condition or observation that supports why the medication was ordered.|
|[MedicationRequestSupportingInfo](MedicationRequestSupportingInfo.md)|Include additional information (for example, patient height and weight) that supports the ordering of the medication.|
