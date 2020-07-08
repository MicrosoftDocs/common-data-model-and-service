---
title: AssetDepreciationProfile in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Fixed asset depreciation profiles in Parameter(AssetDepreciationProfile)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDepreciationProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

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
|[RecId](#RecId)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[Accrual](#Accrual)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[AssetDepRateSchedule_JP](#AssetDepRateSchedule_JP)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[AssetEndDependOnServiceLife](#AssetEndDependOnServiceLife)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[CalculationBase](#CalculationBase)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[DepreciationYear](#DepreciationYear)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[FullYearDepreciation_DE](#FullYearDepreciation_DE)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[HalfYearDepreciation_AT](#HalfYearDepreciation_AT)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[Interval](#Interval)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[LVPFirstYearPercentage_AU](#LVPFirstYearPercentage_AU)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[LVPLowValueCost_AU](#LVPLowValueCost_AU)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[LVPPercentage_AU](#LVPPercentage_AU)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[Method](#Method)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[Name](#Name)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[NumOfYearsEquallyDivided_JP](#NumOfYearsEquallyDivided_JP)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[Percentage](#Percentage)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[Profile](#Profile)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[ShiftDepreciation_IN](#ShiftDepreciation_IN)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[SmoothDepForTheYearOver95_JP](#SmoothDepForTheYearOver95_JP)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[SpecialDepAccountingMethod_JP](#SpecialDepAccountingMethod_JP)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[SpecialDepApplyNumOfPeriods_JP](#SpecialDepApplyNumOfPeriods_JP)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[SpecialDepBaseRatio_JP](#SpecialDepBaseRatio_JP)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[SpecialDepRate_JP](#SpecialDepRate_JP)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[DepreciationBase_RU](#DepreciationBase_RU)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[Relationship_AssetDepRateSchedule_JPRelationshipId](#Relationship_AssetDepRateSchedule_JPRelationshipId)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetDepreciationProfile.md" target="_blank">Parameter/AssetDepreciationProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDepreciationProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Accrual name="Accrual">Accrual</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Accrual attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetDepRateSchedule_JP name="AssetDepRateSchedule_JP">AssetDepRateSchedule_JP</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depreciation rate schedule</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDepRateSchedule_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depreciation rate schedule</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetEndDependOnServiceLife name="AssetEndDependOnServiceLife">AssetEndDependOnServiceLife</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetEndDependOnServiceLife attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CalculationBase name="CalculationBase">CalculationBase</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationBase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationYear name="DepreciationYear">DepreciationYear</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FullYearDepreciation_DE name="FullYearDepreciation_DE">FullYearDepreciation_DE</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullYearDepreciation_DE attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HalfYearDepreciation_AT name="HalfYearDepreciation_AT">HalfYearDepreciation_AT</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HalfYearDepreciation_AT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Interval name="Interval">Interval</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Interval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LVPFirstYearPercentage_AU name="LVPFirstYearPercentage_AU">LVPFirstYearPercentage_AU</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LVPFirstYearPercentage_AU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LVPLowValueCost_AU name="LVPLowValueCost_AU">LVPLowValueCost_AU</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LVPLowValueCost_AU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LVPPercentage_AU name="LVPPercentage_AU">LVPPercentage_AU</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LVPPercentage_AU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Method name="Method">Method</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Method attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

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

### <a href=#NumOfYearsEquallyDivided_JP name="NumOfYearsEquallyDivided_JP">NumOfYearsEquallyDivided_JP</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumOfYearsEquallyDivided_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Percentage name="Percentage">Percentage</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Profile name="Profile">Profile</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Profile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShiftDepreciation_IN name="ShiftDepreciation_IN">ShiftDepreciation_IN</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shift depreciation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftDepreciation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shift depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SmoothDepForTheYearOver95_JP name="SmoothDepForTheYearOver95_JP">SmoothDepForTheYearOver95_JP</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SmoothDepForTheYearOver95_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpecialDepAccountingMethod_JP name="SpecialDepAccountingMethod_JP">SpecialDepAccountingMethod_JP</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepAccountingMethod_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpecialDepApplyNumOfPeriods_JP name="SpecialDepApplyNumOfPeriods_JP">SpecialDepApplyNumOfPeriods_JP</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepApplyNumOfPeriods_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpecialDepBaseRatio_JP name="SpecialDepBaseRatio_JP">SpecialDepBaseRatio_JP</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepBaseRatio_JP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SpecialDepRate_JP name="SpecialDepRate_JP">SpecialDepRate_JP</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepRate_JP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationBase_RU name="DepreciationBase_RU">DepreciationBase_RU</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationBase_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

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

### <a href=#Relationship_AssetDepRateSchedule_JPRelationshipId name="Relationship_AssetDepRateSchedule_JPRelationshipId">Relationship_AssetDepRateSchedule_JPRelationshipId</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDepRateSchedule_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/AssetDepRateSchedule_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Reference/AssetDepRateSchedule_JP.cdm.json/AssetDepRateSchedule_JP</a></td><td><a href="../Reference/AssetDepRateSchedule_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/AssetDepreciationProfile (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
