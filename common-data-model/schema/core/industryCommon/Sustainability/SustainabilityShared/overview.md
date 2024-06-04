---
title: overview of CloudforSustainabilitySharedDataModel - Common Data Model | Microsoft Docs
description: CloudforSustainabilitySharedDataModel is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/3/2024
ms.author: anbichse
---

# Overview of CloudforSustainabilitySharedDataModel

Cloud for Sustainability Shared Data Model CDM entity definitions  

## Entities

|Name|Description|
|---|---|
|[Account](Account.md)|Business that represents a customer or potential customer. The company that is billed in business transactions.|
|[Contact](Contact.md)|Person with whom a business unit has a relationship, such as customer, supplier, and colleague.|
|[CountryRegion](CountryRegion.md)|Defines custom country/region codes.|
|[CountryRegionMapping](CountryRegionMapping.md)|Entity storing the region mapping, which is a mapping of a country or region to a user-defined group.|
|[CustomDimensionMetadata](CustomDimensionMetadata.md)|Table holding information about all the custom dimensions available in Microsoft Sustainability Manager|
|[DataSourceType](DataSourceType.md)|The different types of sources for energy data.|
|[DeprecatedProductIdentifier](DeprecatedProductIdentifier.md)|Uniquely identifies a product.|
|[EmissionFactor](EmissionFactor.md)|Conversion factor which takes activity data and converts quantities into greenhouse gas amounts and units.|
|[EnergyProviderType](EnergyProviderType.md)|Categories or classifications of companies or entities that supply energy, such as electricity or gas.|
|[EstimationFactor](EstimationFactor.md)|Entity to store estimation or consumption factors.|
|[Facility](Facility.md)|Base-level location to attribute activity data. May contain multiple buildings and organizational units.|
|[FacilityCapacity](FacilityCapacity.md)|Entity to capture the facility's capacity dimension and measure for a specified time period.|
|[FacilityCapacityDimension](FacilityCapacityDimension.md)|The dimension of the facility based on which the water usage intensity factors are defined such as area.|
|[FacilityItemProduction](FacilityItemProduction.md)|Entity used to record the production quantity of an item in a facility for a specified period.|
|[FacilityType](FacilityType.md)|Entity used for classifying the type of facility, as defined in the reporting company.|
|[FacilityUsageDetail](FacilityUsageDetail.md)|Captures intensity scores for a facility in a given year.|
|[FactorLibrary](FactorLibrary.md)|Repository for emission and estimation factor sets, including both system and user added.|
|[FactorMapping](FactorMapping.md)|Entity which connects reference data to a specific emission factor or estimation factor, which can determine different factors for large sets of activity data.|
|[GeographicArea](GeographicArea.md)|Definition or categorization of a given area on earth|
|[GeographicAreaType](GeographicAreaType.md)|User or industry defined type of geographic area|
|[IndustrialProcessType](IndustrialProcessType.md)|Entity to store process classifications for various industrial processes, such as extraction and manufacturing processes.|
|[Industry](Industry.md)|Parent level of the industry classification which contains an ID and name.|
|[IndustryClassification](IndustryClassification.md)|Combination of the Industry parent-level industry classification and the Subindustry child-level industry classification, both defined on the company profile.|
|[Material](Material.md)|Entity used for classifying the type of material, as defined in the reporting company.|
|[Meter](Meter.md)|An entity that represents meters.|
|[MonthlyRevenue](MonthlyRevenue.md)|Captures revenue of an organizational unit by year and month in the company currency.|
|[OrganizationalHierarchy](OrganizationalHierarchy.md)|The classification that a company or organization uses to categorize its entities such as facilities, departments, divisions and organizational units.|
|[OrganizationalProfile](OrganizationalProfile.md)|The base information of the organization, for which the solution is built.|
|[OrganizationalUnit](OrganizationalUnit.md)|A structural division of a company or organization.|
|[ProductCategory](ProductCategory.md)|Represents category of a product. Can be associated with a parent product category. It is used in reports.|
|[ProductSustainability](ProductSustainability.md)|A product that can be associated with a product carbon footprint.|
|[ReportingPeriod](ReportingPeriod.md)|Entity used to track reporting periods created for each reporting year.|
|[ReportingYear](ReportingYear.md)|Entity which lists reporting years created in the system.|
|[Subindustry](Subindustry.md)|Child-level of the industry classisfication, which contains an ID and name.|
|[SustainabilityDataDefinition](SustainabilityDataDefinition.md)|Entity used to define the data definitions for entities across Carbon, Waste and Water.|
|[SustainabilityDataDefinitionSubcategory](SustainabilityDataDefinitionSubcategory.md)|Stores data definition subcategories and help links|
|[SustainabilityItemCategorySKU](SustainabilityItemCategorySKU.md)|The category of the item such as abrasives, castings or accessories|
|[SustainabilityItemPackaging](SustainabilityItemPackaging.md)|Indicates whether the item is used for packaging when distributing a product.|
|[SustainabilityItemSKU](SustainabilityItemSKU.md)|Entity for capturing data on items/SKU inventoried such as input material and finished goods.|
|[SustainabilityModule](SustainabilityModule.md)|Entity used to classify the data definitions.|
|[Unit](Unit.md)|Unit of measure.|
|[UnitGroup](UnitGroup.md)|Grouping of units.|
|[ValueChainPartner](ValueChainPartner.md)|Entity for value chain partner or supplier.|
