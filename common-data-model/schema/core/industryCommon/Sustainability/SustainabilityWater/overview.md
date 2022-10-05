---
title: Overview of Cloud for Sustainability water data model - Common Data Model | Microsoft Docs
description: SustainabilityWater is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 10/5/2022
ms.author: cdmditeam
---

# Overview of Cloud for Sustainability water data model

Microsoft Cloud for Sustainability empowers organizations to accelerate sustainability progress and business growth by integrating environmental, social, and governance (ESG) capabilities across the Microsoft Cloud portfolio and solutions from our global ecosystem of partners.

The Cloud for Sustainability water data model is an addition to the Cloud for Sustainability data model. It is used to import customer activities related to water quality and reporting of analysis impact.

For more information, see the [Microsoft Cloud for Sustainability](https://go.microsoft.com/fwlink/?linkid=2193512) documentation. The documentation includes [introductory information](https://go.microsoft.com/fwlink/?linkid=2194529) about the data model, as well as information about the [required attributes](https://go.microsoft.com/fwlink/?linkid=2194273).

## Entities

|Name|Description|
|---|---|
|[Facility](Facility.md)|Base-level location to attribute activity data. May contain multiple buildings and organizational units.|
|[IndustrialProcessType](IndustrialProcessType.md)|Entity to store process classifications for various industrial processes, such as extraction and manufacturing processes.|
|[OrganizationalUnit](OrganizationalUnit.md)|A structural division of a company or organization.|
|[Unit](Unit.md)|Unit of measure.|
|[UnitGroup](UnitGroup.md)|Grouping of units.|
|[WaterInstrument](WaterInstrument.md)|Stores the information related to the devices or instruments tracking water in the organization.|
|[WaterInstrumentConfiguration](WaterInstrumentConfiguration.md)|Entity to describe the configuration of the water flow through each water instrument present in the organization.|
|[WaterQualityAnalysis](WaterQualityAnalysis.md)|Describes the analysis performed to test a water sample for a certain characteristic|
|[WaterQualityCharacteristic](WaterQualityCharacteristic.md)|Describes the property being evaluated during the analysis of the water sample collected|
|[WaterQualityTestResult](WaterQualityTestResult.md)||
|[WaterQuantity](WaterQuantity.md)|Stores the actual quantity information from water transactions within the organization.|
|[WaterSample](WaterSample.md)|Stores the attributes of the water samples collected for testing water quality|
|[WaterSource](WaterSource.md)|Entity to store details of sources from/to which water gets withdrawn/discharged|
