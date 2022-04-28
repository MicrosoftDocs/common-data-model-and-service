---
title: Overview of Sustainability - Common Data Model | Microsoft Docs
description: Sustainability is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2022
ms.author: matgos
---

# Overview of Sustainability

Cloud for Sustainability Data Model CDM entity definitions  

## Entities

|Name|Description|
|---|---|
|[AccommodationType](AccommodationType.md)|Entity used for classifying the type of hotel accommodation, as defined in the reporting company.|
|[BusinessTravel](BusinessTravel.md)|Entity for business travel activity data, including vehicle, train, and air travel, as well as hotel stays.|
|[BusinessTravelType](BusinessTravelType.md)|Entity used for classifying the type of business travel, as defined in the reporting company.|
|[CapitalGood](CapitalGood.md)|Purchased entity that depreciates over time.|
|[ContractualInstrumentType](ContractualInstrumentType.md)|Documented method/approach to confirm and validate source data.|
|[CountryRegionMapping](CountryRegionMapping.md)|Entity storing the region mapping, which is a mapping of a country or region to a user-defined group.|
|[Emission](Emission.md)|Entity which lists the most common greenhouse gases and their quantities as output of calculation or direct measurement.|
|[EmissionFactor](EmissionFactor.md)|Conversion factor which takes activity data and converts quantities into greenhouse gas amounts and units.|
|[EmissionsSource](EmissionsSource.md)|Greenhouse Gas Protocol-defined emissions sources in scopes 1, 2, and 3.|
|[EstimationFactor](EstimationFactor.md)|Entity to store estimation or consumption factors.|
|[Facility](Facility.md)|Base-level location to attribute activity data. May contain multiple buildings and organizational units.|
|[FacilityAnnualDetail](FacilityAnnualDetail.md)|Captures intensity scores for a facility in a given year.|
|[FactorLibrary](FactorLibrary.md)|Repository for emission and estimation factor sets, including both system and user added.|
|[FactorMapping](FactorMapping.md)|Entity which connects reference data to a specific emission factor or estimation factor, which can determine different factors for large sets of activity data.|
|[FuelType](FuelType.md)|List of fuels to be used during combustion, as needed for emissions factor selection.|
|[FugitiveEmission](FugitiveEmission.md)|Greenhouse gas emissions that cannot reasonably be expected to be captured. Typically includes refrigerants.|
|[GreenhouseGas](GreenhouseGas.md)|Entity for greenhouse gases.|
|[IndustrialProcess](IndustrialProcess.md)|Emissions source for scope 1 emissions relating to industrial processes.|
|[IndustrialProcessType](IndustrialProcessType.md)|Entity to store process classifications for various industrial processes, such as extraction and manufacturing processes.|
|[Industry](Industry.md)|Parent level of the industry classification which contains an ID and name.|
|[IndustryClassification](IndustryClassification.md)|Combination of the Industry parent-level industry classification and the Subindustry child-level industry classification, both defined on the company profile.|
|[MobileCombustion](MobileCombustion.md)|Combustion that occurs in a moving vehicle, such as a car or truck.|
|[MonthlyRevenue](MonthlyRevenue.md)|Captures revenue of an organizational unit by year and month in the company currency.|
|[OrganizationalHierarchy](OrganizationalHierarchy.md)|The classification that a company or organization uses to categorize its entities such as facilities, departments, divisions and organizational units.|
|[OrganizationalProfile](OrganizationalProfile.md)|The base information of the organization, for which the solution is built.|
|[OrganizationalUnit](OrganizationalUnit.md)|A structural division of a company or organization.|
|[PurchasedEnergy](PurchasedEnergy.md)|Electric energy, measured in MWh, delivered by the utility to a customer in accordance with the signed agreement.|
|[PurchasedGoodAndService](PurchasedGoodAndService.md)|Entity for purchased goods and services.|
|[SpendType](SpendType.md)|Entity that represents a spend type, as defined in the reporting company. Used for classifying purchases.|
|[StationaryCombustion](StationaryCombustion.md)|Combustion that occurs in a fixed asset, such as a boiler or furnace.|
|[Subindustry](Subindustry.md)|Child-level of the industry classisfication, which contains an ID and name.|
|[TransportationAndDistribution](TransportationAndDistribution.md)|Upstream and downstream transportation and distribution activities.|
|[TransportMode](TransportMode.md)|The mode of transportation or distribution used in an activity, such as air, rail, or storage.|
|[Unit](Unit.md)|Unit of measure.|
|[UnitGroup](UnitGroup.md)|Grouping of units.|
|[ValueChainPartner](ValueChainPartner.md)|Entity for value chain partner or supplier.|
|[VehicleType](VehicleType.md)|Category of vehicle. Used by your organization as reference data to assist with emission factor selection for mobile combustion calculations.|
