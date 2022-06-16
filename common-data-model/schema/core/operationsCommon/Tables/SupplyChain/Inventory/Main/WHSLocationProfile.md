---
title: WHSLocationProfile in Main - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Location profiles in Main(WHSLocationProfile)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLocationProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSLocationProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Location profiles</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[AllowMixedBatches](#AllowMixedBatches)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[AllowMixedItems](#AllowMixedItems)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[AllowMixedStatus](#AllowMixedStatus)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[AllowNegative](#AllowNegative)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[CycleCountable](#CycleCountable)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[Depth](#Depth)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[DimensionFillPCT](#DimensionFillPCT)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[DockMgmtProfileId](#DockMgmtProfileId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[FillPercentage](#FillPercentage)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[GenCheckDigit](#GenCheckDigit)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[Height](#Height)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[IgnoreBatchDates](#IgnoreBatchDates)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[LocFormatId](#LocFormatId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[LocProfileId](#LocProfileId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[LocProfileName](#LocProfileName)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[LocType](#LocType)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[LPControlled](#LPControlled)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[MaxWeight](#MaxWeight)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[StorageUnit](#StorageUnit)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[TotalVolume](#TotalVolume)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[UsableDepth](#UsableDepth)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[UsableHeight](#UsableHeight)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[UsableVolume](#UsableVolume)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[UsableWidth](#UsableWidth)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[Width](#Width)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[AllowedContainerTypeGroup](#AllowedContainerTypeGroup)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[EnableLocationActivityDateTimeUpdate](#EnableLocationActivityDateTimeUpdate)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[EnableItemInLocationUpdate](#EnableItemInLocationUpdate)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[EnableLocationStatusUpdate](#EnableLocationStatusUpdate)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[WorkAvailabilityThresholdType](#WorkAvailabilityThresholdType)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[ReplenishmentExceedLocationCapacity](#ReplenishmentExceedLocationCapacity)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[ReplenishmentOverflowCapacityPercent](#ReplenishmentOverflowCapacityPercent)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[ReplenishmentOverflowCapacityQty](#ReplenishmentOverflowCapacityQty)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[ReplenishmentOverflowCapacityUnit](#ReplenishmentOverflowCapacityUnit)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[EnableLocationLicensePlatePositioning](#EnableLocationLicensePlatePositioning)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[DisplayMobileDeviceLocationLicensePlatePositioning](#DisplayMobileDeviceLocationLicensePlatePositioning)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[ProductDimFixed](#ProductDimFixed)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[EnableLocationProductDimensionSpecificMixing](#EnableLocationProductDimensionSpecificMixing)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[Relationship_WHSDocMgmtProfileRelationshipId](#Relationship_WHSDocMgmtProfileRelationshipId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[Relationship_WHSLocationFormatRelationshipId](#Relationship_WHSLocationFormatRelationshipId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[Relationship_WHSLocationTypeRelationshipId](#Relationship_WHSLocationTypeRelationshipId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[Relationship_WHSAllowedContainerTypeGroupRelationshipId](#Relationship_WHSAllowedContainerTypeGroupRelationshipId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSLocationProfile.md" target="_blank">Main/WHSLocationProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSLocationProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllowMixedBatches name="AllowMixedBatches">AllowMixedBatches</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMixedBatches attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowMixedItems name="AllowMixedItems">AllowMixedItems</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMixedItems attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowMixedStatus name="AllowMixedStatus">AllowMixedStatus</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMixedStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowNegative name="AllowNegative">AllowNegative</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowNegative attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CycleCountable name="CycleCountable">CycleCountable</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CycleCountable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Depth name="Depth">Depth</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual location depth</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Depth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual location depth</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DimensionFillPCT name="DimensionFillPCT">DimensionFillPCT</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionFillPCT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DockMgmtProfileId name="DockMgmtProfileId">DockMgmtProfileId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DockMgmtProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FillPercentage name="FillPercentage">FillPercentage</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Volume utilization percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FillPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Volume utilization percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GenCheckDigit name="GenCheckDigit">GenCheckDigit</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenCheckDigit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Height name="Height">Height</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual location height</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Height attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual location height</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IgnoreBatchDates name="IgnoreBatchDates">IgnoreBatchDates</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IgnoreBatchDates attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LocFormatId name="LocFormatId">LocFormatId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocFormatId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocProfileId name="LocProfileId">LocProfileId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocProfileName name="LocProfileName">LocProfileName</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocType name="LocType">LocType</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LPControlled name="LPControlled">LPControlled</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LPControlled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MaxWeight name="MaxWeight">MaxWeight</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StorageUnit name="StorageUnit">StorageUnit</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalVolume name="TotalVolume">TotalVolume</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual location volume</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalVolume attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual location volume</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UsableDepth name="UsableDepth">UsableDepth</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsableDepth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UsableHeight name="UsableHeight">UsableHeight</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsableHeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UsableVolume name="UsableVolume">UsableVolume</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsableVolume attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UsableWidth name="UsableWidth">UsableWidth</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsableWidth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Width name="Width">Width</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual location width</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Width attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual location width</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AllowedContainerTypeGroup name="AllowedContainerTypeGroup">AllowedContainerTypeGroup</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowed container type group</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedContainerTypeGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowed container type group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EnableLocationActivityDateTimeUpdate name="EnableLocationActivityDateTimeUpdate">EnableLocationActivityDateTimeUpdate</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLocationActivityDateTimeUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EnableItemInLocationUpdate name="EnableItemInLocationUpdate">EnableItemInLocationUpdate</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableItemInLocationUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EnableLocationStatusUpdate name="EnableLocationStatusUpdate">EnableLocationStatusUpdate</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLocationStatusUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WorkAvailabilityThresholdType name="WorkAvailabilityThresholdType">WorkAvailabilityThresholdType</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkAvailabilityThresholdType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReplenishmentExceedLocationCapacity name="ReplenishmentExceedLocationCapacity">ReplenishmentExceedLocationCapacity</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentExceedLocationCapacity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReplenishmentOverflowCapacityPercent name="ReplenishmentOverflowCapacityPercent">ReplenishmentOverflowCapacityPercent</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOverflowCapacityPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReplenishmentOverflowCapacityQty name="ReplenishmentOverflowCapacityQty">ReplenishmentOverflowCapacityQty</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOverflowCapacityQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReplenishmentOverflowCapacityUnit name="ReplenishmentOverflowCapacityUnit">ReplenishmentOverflowCapacityUnit</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOverflowCapacityUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableLocationLicensePlatePositioning name="EnableLocationLicensePlatePositioning">EnableLocationLicensePlatePositioning</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLocationLicensePlatePositioning attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DisplayMobileDeviceLocationLicensePlatePositioning name="DisplayMobileDeviceLocationLicensePlatePositioning">DisplayMobileDeviceLocationLicensePlatePositioning</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayMobileDeviceLocationLicensePlatePositioning attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProductDimFixed name="ProductDimFixed">ProductDimFixed</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EnableLocationProductDimensionSpecificMixing name="EnableLocationProductDimensionSpecificMixing">EnableLocationProductDimensionSpecificMixing</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLocationProductDimensionSpecificMixing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSDocMgmtProfileRelationshipId name="Relationship_WHSDocMgmtProfileRelationshipId">Relationship_WHSDocMgmtProfileRelationshipId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSDocMgmtProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WHSDockMgmtProfile.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSDockMgmtProfile.cdm.json/WHSDockMgmtProfile</a></td><td><a href="../Group/WHSDockMgmtProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLocationFormatRelationshipId name="Relationship_WHSLocationFormatRelationshipId">Relationship_WHSLocationFormatRelationshipId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLocationFormatRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WHSLocationFormat.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSLocationFormat.cdm.json/WHSLocationFormat</a></td><td><a href="../Group/WHSLocationFormat.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLocationTypeRelationshipId name="Relationship_WHSLocationTypeRelationshipId">Relationship_WHSLocationTypeRelationshipId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLocationTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WHSLocationType.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSLocationType.cdm.json/WHSLocationType</a></td><td><a href="../Group/WHSLocationType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSAllowedContainerTypeGroupRelationshipId name="Relationship_WHSAllowedContainerTypeGroupRelationshipId">Relationship_WHSAllowedContainerTypeGroupRelationshipId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSAllowedContainerTypeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/WHSAllowedContainerTypeGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSAllowedContainerTypeGroup.cdm.json/WHSAllowedContainerTypeGroup</a></td><td><a href="../WorksheetHeader/WHSAllowedContainerTypeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/WHSLocationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
