---
title: Overview of Cloud for Sustainability water data model
description: Cloud for Sustainability water data model contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: anbichse
ms.topic: article
ms.date: 10/24/2023
ms.author: anbichse
---

# Overview of Cloud for Sustainability water data model

The Cloud for Sustainability water data model (preview) empowers organizations to unify, store and prepare water measurement data from their facilities into a single data model to help meet water sustainability goals. The Cloud for Sustainability water data model (preview) provides the schema required for storing and linking water quality and quantity measurement data and water sustainability reference data. The schema makes water sustainability data available for use cases such as water sustainability disclosures and regulatory water quality reporting.

For more information, see the [Microsoft Cloud for Sustainability water data model](/industry/sustainability/water-data-model-intro) documentation. The documentation includes [introductory information](/industry/sustainability/water-data-model-intro) about the data model, as well as information about the [required attributes](/industry/sustainability/water-data-model-required-attributes).  

## Entities

|Name|Description|
|---|---|
|[Facility](Facility.md)|Base\x2dlevel location to attribute activity data. May contain multiple buildings and organizational units.|
|[StoredWater](StoredWater.md)|The entity stores data related to the water stored within a facility.|
|[WaterBasin](WaterBasin.md)|Describes the details of the basin from which water is being withdrawn by an entity.|
|[WaterInstrument](WaterInstrument.md)|Stores the information related to the devices or instruments tracking water in the organization.|
|[WaterQualityAnalysis](WaterQualityAnalysis.md)|Describes the analysis performed to test a water sample for a certain characteristic.|
|[WaterQualityCharacteristic](WaterQualityCharacteristic.md)|Describes the property being evaluated during the analysis of the water sample collected.|
|[WaterQualityCharacteristicType](WaterQualityCharacteristicType.md)|Stores all the different classifications for the water quality characteristics.|
|[WaterQualityTestResult](WaterQualityTestResult.md)|Describes the results coming from the laboratory water quality test for a characteristic in the water sample.|
|[WaterQuantity](WaterQuantity.md)|Stores the actual quantity information from water transactions within the organization.|
|[WaterRiskIndex](WaterRiskIndex.md)|The overall water risk that measures all water\x2drelated risks, by aggregating all selected indicators from the Physical Quantity, Quality and Regulatory & Reputational Risk categories. Higher values indicate higher water risk.|
|[WaterSample](WaterSample.md)|Stores the attributes of the water samples collected for testing water quality.|
|[WaterSource](WaterSource.md)|Entity to store details of sources from/to which water gets withdrawn/discharged.|
