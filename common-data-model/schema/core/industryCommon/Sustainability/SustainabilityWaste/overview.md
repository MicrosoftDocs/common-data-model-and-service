---
title: Overview of Cloud for Sustainability waste data model
description: CloudforSustainabilityWasteDataModel is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: anbichse
ms.topic: article
ms.date: 10/24/2023
ms.author: anbichse
---

# Overview of Cloud for Sustainability waste data model

The Cloud for Sustainability waste data model (preview) enables organizations to unify, standardize and prepare waste sustainability data in order to track and achieve their net zero waste sustainability goals. The Cloud for Sustainability waste data model (preview) provides the schema required for storing and integrating waste quality and quantity measurement data with sustainability waste reference data. The schema makes waste sustainability data available for use cases such as regulatory disclosures for waste generated and disposed as well as for compliance monitoring of hazardous/radioactive waste quality characteristics.

For more information, see the [Microsoft Cloud for Sustainability waste data model](/industry/sustainability/waste-data-model-intro) documentation. The documentation includes [introductory information](/industry/sustainability/waste-data-model-intro) about the data model, as well as information about the [required attributes](/industry/sustainability/waste-data-model-required-attributes).

## Entities

|Name|Description|
|---|---|
|[CircularityDesignPrinciple](CircularityDesignPrinciple.md)|Describes the circularity princple followed to produce the finished good such as durability, reusability or repairability.|
|[FacilityItemConsumption](FacilityItemConsumption.md)|Entity used to record the quantity of an item consumed in a facility for a specified period.|
|[ItemBillOfMaterial](ItemBillOfMaterial.md)|Entity which records the Bill Of Material (BOM) used to create the item. The BOM lists the items (materials) that are part of the item.|
|[ItemSustainableContent](ItemSustainableContent.md)|Entity for capturing data on the sustainable content types in the item such as percentage of recycled, reused or renewable content.|
|[WasteCharacteristicType](WasteCharacteristicType.md)|Stores all the different classifications for the waste quality characteristics.|
|[WasteQualityCharacteristic](WasteQualityCharacteristic.md)|Stores information on the characteristics of the contaminant or chemical being tracked.|
|[WasteQualityTestResult](WasteQualityTestResult.md)|Stores information on the result of the tests for tracking chemical/contaminant levels.|
|[WasteQuantity](WasteQuantity.md)|Stores information on the actual waste quantity of the organization.|
|[WasteTestMethod](WasteTestMethod.md)|Stores information on tests performed for the contaminant.|
|[WasteType](WasteType.md)|Stores information on the type of waste generated.|
