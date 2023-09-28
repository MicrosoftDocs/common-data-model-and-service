---
title: overview of Sustainability water data model - Common Data Model
description: CloudforSustainabilityWaterDataModel is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: anbichse
ms.topic: article
ms.date: 09/29/2023
ms.author: anbichse
---

# Overview of Microsoft Cloud for Sustainability water data model

Microsoft Cloud for Sustainability Water Data Model CDM entity definitions  

## Entities

|Name|Description|
|---|---|
|[Facility](Facility.md)|Basex2dlevel location to attribute activity data. May contain multiple buildings and organizational units.|
|[StoredWater](StoredWater.md)|The entity stores data related to the water stored within a facility.|
|[WaterBasin](WaterBasin.md)|Describes the details of the basin from which water is being withdrawn by an entity.|
|[WaterInstrument](WaterInstrument.md)|Stores the information related to the devices or instruments tracking water in the organization.|
|[WaterQualityAnalysis](WaterQualityAnalysis.md)|Describes the analysis performed to test a water sample for a certain characteristic.|
|[WaterQualityCharacteristic](WaterQualityCharacteristic.md)|Describes the property being evaluated during the analysis of the water sample collected.|
|[WaterQualityCharacteristicType](WaterQualityCharacteristicType.md)|Stores all the different classifications for the water quality characteristics.|
|[WaterQualityTestResult](WaterQualityTestResult.md)|Describes the results coming from the laboratory water quality test for a characteristic in the water sample.|
|[WaterQuantity](WaterQuantity.md)|Stores the actual quantity information from water transactions within the organization.|
|[WaterRiskIndex](WaterRiskIndex.md)|The overall water risk that measures all waterx2drelated risks, by aggregating all selected indicators from the Physical Quantity, Quality and Regulatory & Reputational Risk categories. Higher values indicate higher water risk.|
|[WaterSample](WaterSample.md)|Stores the attributes of the water samples collected for testing water quality.|
|[WaterSource](WaterSource.md)|Entity to store details of sources from/to which water gets withdrawn/discharged.|
