---
title: AssetDepreciationProfileEntity in FixedAssets - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Fixed asset depreciation profiles in FixedAssets(AssetDepreciationProfileEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetDepreciationProfileEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed asset depreciation profiles</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DepreciationProfileId](#DepreciationProfileId)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[DepreciationYear](#DepreciationYear)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[FullDepreciation](#FullDepreciation)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[Interval](#Interval)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[Name](#Name)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[Method](#Method)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[Percentage](#Percentage)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[PeriodFrequency](#PeriodFrequency)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[CalculationBasis](#CalculationBasis)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[DepreciationRateSchedule](#DepreciationRateSchedule)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[DepreciationRateScheduleDescription](#DepreciationRateScheduleDescription)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[DepreciationRateScheduleName](#DepreciationRateScheduleName)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[EquallySplitDepreciationAmount95PercentOfAcquisitionCost](#EquallySplitDepreciationAmount95PercentOfAcquisitionCost)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[LowValuePoolLowCostValue](#LowValuePoolLowCostValue)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[LowValuePoolPercentage](#LowValuePoolPercentage)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[LowValuePoolPercentFirstYear](#LowValuePoolPercentFirstYear)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[NumberOfYearsToEquallyDivideDepreciationAmounts](#NumberOfYearsToEquallyDivideDepreciationAmounts)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[SpecialDepreciationAccountingMethod](#SpecialDepreciationAccountingMethod)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[SpecialDepreciationApplyNumberOfPeriods](#SpecialDepreciationApplyNumberOfPeriods)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[SpecialDepreciationBaseRatio](#SpecialDepreciationBaseRatio)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[SpecialDepreciationRate](#SpecialDepreciationRate)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[FullYearDepreciationOnAdditionalAcquisitions](#FullYearDepreciationOnAdditionalAcquisitions)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[IsShiftDepreciation](#IsShiftDepreciation)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[BackingTable_AssetDepreciationProfileRelationshipId](#BackingTable_AssetDepreciationProfileRelationshipId)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetDepreciationProfileEntity.md" target="_blank">FixedAssets/AssetDepreciationProfileEntity</a>|

### <a href=#DepreciationProfileId name="DepreciationProfileId">DepreciationProfileId</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationYear name="DepreciationYear">DepreciationYear</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FullDepreciation name="FullDepreciation">FullDepreciation</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Interval name="Interval">Interval</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Interval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Method name="Method">Method</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Method attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percentage name="Percentage">Percentage</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage/Factor</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Percentage/Factor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodFrequency name="PeriodFrequency">PeriodFrequency</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodFrequency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculationBasis name="CalculationBasis">CalculationBasis</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationRateSchedule name="DepreciationRateSchedule">DepreciationRateSchedule</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationRateSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationRateScheduleDescription name="DepreciationRateScheduleDescription">DepreciationRateScheduleDescription</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depreciation rate schedule description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationRateScheduleDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depreciation rate schedule description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationRateScheduleName name="DepreciationRateScheduleName">DepreciationRateScheduleName</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depreciation rate schedule name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationRateScheduleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depreciation rate schedule name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EquallySplitDepreciationAmount95PercentOfAcquisitionCost name="EquallySplitDepreciationAmount95PercentOfAcquisitionCost">EquallySplitDepreciationAmount95PercentOfAcquisitionCost</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EquallySplitDepreciationAmount95PercentOfAcquisitionCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowValuePoolLowCostValue name="LowValuePoolLowCostValue">LowValuePoolLowCostValue</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowValuePoolLowCostValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowValuePoolPercentage name="LowValuePoolPercentage">LowValuePoolPercentage</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowValuePoolPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowValuePoolPercentFirstYear name="LowValuePoolPercentFirstYear">LowValuePoolPercentFirstYear</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowValuePoolPercentFirstYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfYearsToEquallyDivideDepreciationAmounts name="NumberOfYearsToEquallyDivideDepreciationAmounts">NumberOfYearsToEquallyDivideDepreciationAmounts</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfYearsToEquallyDivideDepreciationAmounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAccountingMethod name="SpecialDepreciationAccountingMethod">SpecialDepreciationAccountingMethod</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAccountingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationApplyNumberOfPeriods name="SpecialDepreciationApplyNumberOfPeriods">SpecialDepreciationApplyNumberOfPeriods</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationApplyNumberOfPeriods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationBaseRatio name="SpecialDepreciationBaseRatio">SpecialDepreciationBaseRatio</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationBaseRatio attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationRate name="SpecialDepreciationRate">SpecialDepreciationRate</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FullYearDepreciationOnAdditionalAcquisitions name="FullYearDepreciationOnAdditionalAcquisitions">FullYearDepreciationOnAdditionalAcquisitions</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullYearDepreciationOnAdditionalAcquisitions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsShiftDepreciation name="IsShiftDepreciation">IsShiftDepreciation</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsShiftDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_AssetDepreciationProfileRelationshipId name="BackingTable_AssetDepreciationProfileRelationshipId">BackingTable_AssetDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.cdm.json/AssetDepreciationProfile</a></td><td><a href="../../../Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetDepreciationProfileEntity (this entity)  

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
