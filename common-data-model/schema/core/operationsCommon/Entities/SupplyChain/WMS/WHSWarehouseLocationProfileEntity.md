---
title: WHSWarehouseLocationProfileEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Warehouse location profiles in WMS(WHSWarehouseLocationProfileEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseLocationProfileEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse location profiles</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsLocationAllowingMixedItemBatches](#IsLocationAllowingMixedItemBatches)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsLocationAllowingMixedItems](#IsLocationAllowingMixedItems)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsLocationAllowingMixedItemStatuses](#IsLocationAllowingMixedItemStatuses)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsLocationAllowingNegativeInventory](#IsLocationAllowingNegativeInventory)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsLocationAllowingCycleCounting](#IsLocationAllowingCycleCounting)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ActualLocationDepth](#ActualLocationDepth)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[WarehouseLocationVolumetricMethod](#WarehouseLocationVolumetricMethod)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[DockManagementProfileId](#DockManagementProfileId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[VolumeUtilizationPercentage](#VolumeUtilizationPercentage)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[GenerateCheckDigit](#GenerateCheckDigit)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ActualLocationHeight](#ActualLocationHeight)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[OverrideRulesForBatchDays](#OverrideRulesForBatchDays)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[WarehouseLocationFormatId](#WarehouseLocationFormatId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ProfileId](#ProfileId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ProfileName](#ProfileName)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[WarehouseLocationTypeId](#WarehouseLocationTypeId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[UseLicensePlateTracking](#UseLicensePlateTracking)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[MaximumLocationWeight](#MaximumLocationWeight)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[StorageUnitSymbol](#StorageUnitSymbol)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ActualLocationVolume](#ActualLocationVolume)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[UsableLocationDepth](#UsableLocationDepth)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[UsableLocationHeight](#UsableLocationHeight)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[UsableLocationVolume](#UsableLocationVolume)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[UsableLocationWidth](#UsableLocationWidth)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ActualLocationWidth](#ActualLocationWidth)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[AllowedContainerTypeGroupId](#AllowedContainerTypeGroupId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[AllowedContainerTypeGroupName](#AllowedContainerTypeGroupName)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsItemInLocationUpdateEnabled](#IsItemInLocationUpdateEnabled)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsLocationActivityDateTimeUpdateEnabled](#IsLocationActivityDateTimeUpdateEnabled)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsLocationStatusUpdateEnabled](#IsLocationStatusUpdateEnabled)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[CanReplenishmentExceedLocationCapacity](#CanReplenishmentExceedLocationCapacity)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ReplenishmentOverflowCapacityPercentage](#ReplenishmentOverflowCapacityPercentage)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ReplenishmentOverflowCapacityQuantity](#ReplenishmentOverflowCapacityQuantity)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ReplenishmentOverflowCapacityUnitSymbol](#ReplenishmentOverflowCapacityUnitSymbol)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[WorkAvailabilityThresholdType](#WorkAvailabilityThresholdType)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsWarehouseLocationAllowingMixingProductStyles](#IsWarehouseLocationAllowingMixingProductStyles)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsWarehouseLocationAllowingMixingProductVersions](#IsWarehouseLocationAllowingMixingProductVersions)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsWarehouseLocationAllowingMixingProductSizes](#IsWarehouseLocationAllowingMixingProductSizes)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsWarehouseLocationAllowingMixingProductConfigurations](#IsWarehouseLocationAllowingMixingProductConfigurations)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsWarehouseLocationAllowingMixingProductColors](#IsWarehouseLocationAllowingMixingProductColors)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[ProductDimFixed](#ProductDimFixed)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsWarehouseLocationEnablingMixingProductDimensions](#IsWarehouseLocationEnablingMixingProductDimensions)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[IsLocationLicensePlatePositioningEnabled](#IsLocationLicensePlatePositioningEnabled)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[WillMobileDeviceDisplayLicensePlatePosition](#WillMobileDeviceDisplayLicensePlatePosition)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[Relationship_StorageUnitOfMeasureRelationshipId](#Relationship_StorageUnitOfMeasureRelationshipId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[Relationship_WarehouseLocationFormatRelationshipId](#Relationship_WarehouseLocationFormatRelationshipId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[Relationship_WarehouseLocationTypeRelationshipId](#Relationship_WarehouseLocationTypeRelationshipId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[Relationship_AllowedContainerTypeGroupRelationshipId](#Relationship_AllowedContainerTypeGroupRelationshipId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[Relationship_DockManagementProfileRelationshipId](#Relationship_DockManagementProfileRelationshipId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[BackingTable_WHSLocationProfileRelationshipId](#BackingTable_WHSLocationProfileRelationshipId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseLocationProfileEntity.md" target="_blank">WMS/WHSWarehouseLocationProfileEntity</a>|

### <a href=#IsLocationAllowingMixedItemBatches name="IsLocationAllowingMixedItemBatches">IsLocationAllowingMixedItemBatches</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationAllowingMixedItemBatches attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationAllowingMixedItems name="IsLocationAllowingMixedItems">IsLocationAllowingMixedItems</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationAllowingMixedItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationAllowingMixedItemStatuses name="IsLocationAllowingMixedItemStatuses">IsLocationAllowingMixedItemStatuses</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationAllowingMixedItemStatuses attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationAllowingNegativeInventory name="IsLocationAllowingNegativeInventory">IsLocationAllowingNegativeInventory</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationAllowingNegativeInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationAllowingCycleCounting name="IsLocationAllowingCycleCounting">IsLocationAllowingCycleCounting</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationAllowingCycleCounting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualLocationDepth name="ActualLocationDepth">ActualLocationDepth</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualLocationDepth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationVolumetricMethod name="WarehouseLocationVolumetricMethod">WarehouseLocationVolumetricMethod</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationVolumetricMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DockManagementProfileId name="DockManagementProfileId">DockManagementProfileId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DockManagementProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VolumeUtilizationPercentage name="VolumeUtilizationPercentage">VolumeUtilizationPercentage</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VolumeUtilizationPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GenerateCheckDigit name="GenerateCheckDigit">GenerateCheckDigit</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateCheckDigit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualLocationHeight name="ActualLocationHeight">ActualLocationHeight</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualLocationHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverrideRulesForBatchDays name="OverrideRulesForBatchDays">OverrideRulesForBatchDays</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideRulesForBatchDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationFormatId name="WarehouseLocationFormatId">WarehouseLocationFormatId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationFormatId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileId name="ProfileId">ProfileId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileName name="ProfileName">ProfileName</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationTypeId name="WarehouseLocationTypeId">WarehouseLocationTypeId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseLicensePlateTracking name="UseLicensePlateTracking">UseLicensePlateTracking</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseLicensePlateTracking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumLocationWeight name="MaximumLocationWeight">MaximumLocationWeight</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumLocationWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StorageUnitSymbol name="StorageUnitSymbol">StorageUnitSymbol</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualLocationVolume name="ActualLocationVolume">ActualLocationVolume</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualLocationVolume attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UsableLocationDepth name="UsableLocationDepth">UsableLocationDepth</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsableLocationDepth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UsableLocationHeight name="UsableLocationHeight">UsableLocationHeight</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsableLocationHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UsableLocationVolume name="UsableLocationVolume">UsableLocationVolume</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsableLocationVolume attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UsableLocationWidth name="UsableLocationWidth">UsableLocationWidth</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsableLocationWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualLocationWidth name="ActualLocationWidth">ActualLocationWidth</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualLocationWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedContainerTypeGroupId name="AllowedContainerTypeGroupId">AllowedContainerTypeGroupId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedContainerTypeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedContainerTypeGroupName name="AllowedContainerTypeGroupName">AllowedContainerTypeGroupName</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedContainerTypeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemInLocationUpdateEnabled name="IsItemInLocationUpdateEnabled">IsItemInLocationUpdateEnabled</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemInLocationUpdateEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationActivityDateTimeUpdateEnabled name="IsLocationActivityDateTimeUpdateEnabled">IsLocationActivityDateTimeUpdateEnabled</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationActivityDateTimeUpdateEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationStatusUpdateEnabled name="IsLocationStatusUpdateEnabled">IsLocationStatusUpdateEnabled</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationStatusUpdateEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanReplenishmentExceedLocationCapacity name="CanReplenishmentExceedLocationCapacity">CanReplenishmentExceedLocationCapacity</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanReplenishmentExceedLocationCapacity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentOverflowCapacityPercentage name="ReplenishmentOverflowCapacityPercentage">ReplenishmentOverflowCapacityPercentage</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOverflowCapacityPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentOverflowCapacityQuantity name="ReplenishmentOverflowCapacityQuantity">ReplenishmentOverflowCapacityQuantity</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOverflowCapacityQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentOverflowCapacityUnitSymbol name="ReplenishmentOverflowCapacityUnitSymbol">ReplenishmentOverflowCapacityUnitSymbol</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOverflowCapacityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkAvailabilityThresholdType name="WorkAvailabilityThresholdType">WorkAvailabilityThresholdType</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkAvailabilityThresholdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationAllowingMixingProductStyles name="IsWarehouseLocationAllowingMixingProductStyles">IsWarehouseLocationAllowingMixingProductStyles</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationAllowingMixingProductStyles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationAllowingMixingProductVersions name="IsWarehouseLocationAllowingMixingProductVersions">IsWarehouseLocationAllowingMixingProductVersions</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationAllowingMixingProductVersions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationAllowingMixingProductSizes name="IsWarehouseLocationAllowingMixingProductSizes">IsWarehouseLocationAllowingMixingProductSizes</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationAllowingMixingProductSizes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationAllowingMixingProductConfigurations name="IsWarehouseLocationAllowingMixingProductConfigurations">IsWarehouseLocationAllowingMixingProductConfigurations</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationAllowingMixingProductConfigurations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationAllowingMixingProductColors name="IsWarehouseLocationAllowingMixingProductColors">IsWarehouseLocationAllowingMixingProductColors</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationAllowingMixingProductColors attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDimFixed name="ProductDimFixed">ProductDimFixed</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimFixed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationEnablingMixingProductDimensions name="IsWarehouseLocationEnablingMixingProductDimensions">IsWarehouseLocationEnablingMixingProductDimensions</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationEnablingMixingProductDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationLicensePlatePositioningEnabled name="IsLocationLicensePlatePositioningEnabled">IsLocationLicensePlatePositioningEnabled</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationLicensePlatePositioningEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMobileDeviceDisplayLicensePlatePosition name="WillMobileDeviceDisplayLicensePlatePosition">WillMobileDeviceDisplayLicensePlatePosition</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMobileDeviceDisplayLicensePlatePosition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StorageUnitOfMeasureRelationshipId name="Relationship_StorageUnitOfMeasureRelationshipId">Relationship_StorageUnitOfMeasureRelationshipId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StorageUnitOfMeasureRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseLocationFormatRelationshipId name="Relationship_WarehouseLocationFormatRelationshipId">Relationship_WarehouseLocationFormatRelationshipId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseLocationFormatRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseLocationTypeRelationshipId name="Relationship_WarehouseLocationTypeRelationshipId">Relationship_WarehouseLocationTypeRelationshipId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseLocationTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AllowedContainerTypeGroupRelationshipId name="Relationship_AllowedContainerTypeGroupRelationshipId">Relationship_AllowedContainerTypeGroupRelationshipId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AllowedContainerTypeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DockManagementProfileRelationshipId name="Relationship_DockManagementProfileRelationshipId">Relationship_DockManagementProfileRelationshipId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DockManagementProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSLocationProfileRelationshipId name="BackingTable_WHSLocationProfileRelationshipId">BackingTable_WHSLocationProfileRelationshipId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSLocationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLocationProfile.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLocationProfile.cdm.json/WHSLocationProfile</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLocationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseLocationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
