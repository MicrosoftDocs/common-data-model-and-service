---
title: AssetBookTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# AssetBookTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetBookTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[AcquisitionOnFirstDayCheckType_JP](#AcquisitionOnFirstDayCheckType_JP)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[AssetDerogatoryModel_FR](#AssetDerogatoryModel_FR)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[BookId](#BookId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[CurrentOperationsTax](#CurrentOperationsTax)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Depreciation](#Depreciation)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[DepreciationProfile](#DepreciationProfile)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[DepreciationAltProfile](#DepreciationAltProfile)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[DepreciationExtProfile](#DepreciationExtProfile)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[DepreciationAcceleratedProfile_JP](#DepreciationAcceleratedProfile_JP)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Description](#Description)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[ExceedingNetBookValue](#ExceedingNetBookValue)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[ExpectedScrapRate_CN](#ExpectedScrapRate_CN)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[FiscalCalendar](#FiscalCalendar)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[IsDeprecateInDisposal_CN](#IsDeprecateInDisposal_CN)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[IsDerogatoryBook_FR](#IsDerogatoryBook_FR)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[IsTrueUpDepreciation](#IsTrueUpDepreciation)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[LinkedCurrentLayerAssetBookTable_JP](#LinkedCurrentLayerAssetBookTable_JP)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[LowCostAsset_HU](#LowCostAsset_HU)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[NegativeNetBookValue](#NegativeNetBookValue)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[NetBookValueRest](#NetBookValueRest)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[OverRideCalendarDays_IN](#OverRideCalendarDays_IN)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[RoundOffDepreciation](#RoundOffDepreciation)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[RoundOffType_W](#RoundOffType_W)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[TaxCategoryTogether_LV](#TaxCategoryTogether_LV)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[WorkingDays_IN](#WorkingDays_IN)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[CurrencyCode_RU](#CurrencyCode_RU)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[PostingProfile_RU](#PostingProfile_RU)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[PostingProfileShortage_RU](#PostingProfileShortage_RU)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[DefaultDimension_RU](#DefaultDimension_RU)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[RoundOff_RU](#RoundOff_RU)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[RoundOffDepreciationReportingCurrency](#RoundOffDepreciationReportingCurrency)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[NetBookValueRestReportingCurrency](#NetBookValueRestReportingCurrency)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_AssetDepreciationProfileRelationshipId](#Relationship_AssetDepreciationProfileRelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_DepreciationAcceleratedProfile_JPRelationshipId](#Relationship_DepreciationAcceleratedProfile_JPRelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_DepreciationAltProfileRelationshipId](#Relationship_DepreciationAltProfileRelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_DepreciationExtProfileRelationshipId](#Relationship_DepreciationExtProfileRelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_FiscalCalendarRelationshipId](#Relationship_FiscalCalendarRelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_DefaultDimension_RURelationshipId](#Relationship_DefaultDimension_RURelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_Currency_RURelationshipId](#Relationship_Currency_RURelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_AssetLedger_RURelationshipId](#Relationship_AssetLedger_RURelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_AssetLedgerShortage_RURelationshipId](#Relationship_AssetLedgerShortage_RURelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetBookTable.md" target="_blank">Main/AssetBookTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetBookTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcquisitionOnFirstDayCheckType_JP name="AcquisitionOnFirstDayCheckType_JP">AcquisitionOnFirstDayCheckType_JP</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionOnFirstDayCheckType_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetDerogatoryModel_FR name="AssetDerogatoryModel_FR">AssetDerogatoryModel_FR</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDerogatoryModel_FR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookId name="BookId">BookId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentOperationsTax name="CurrentOperationsTax">CurrentOperationsTax</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentOperationsTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Depreciation name="Depreciation">Depreciation</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Depreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DepreciationProfile name="DepreciationProfile">DepreciationProfile</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationAltProfile name="DepreciationAltProfile">DepreciationAltProfile</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAltProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationExtProfile name="DepreciationExtProfile">DepreciationExtProfile</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationExtProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationAcceleratedProfile_JP name="DepreciationAcceleratedProfile_JP">DepreciationAcceleratedProfile_JP</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAcceleratedProfile_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceedingNetBookValue name="ExceedingNetBookValue">ExceedingNetBookValue</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceedingNetBookValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExpectedScrapRate_CN name="ExpectedScrapRate_CN">ExpectedScrapRate_CN</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedScrapRate_CN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FiscalCalendar name="FiscalCalendar">FiscalCalendar</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendar attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsDeprecateInDisposal_CN name="IsDeprecateInDisposal_CN">IsDeprecateInDisposal_CN</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeprecateInDisposal_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsDerogatoryBook_FR name="IsDerogatoryBook_FR">IsDerogatoryBook_FR</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDerogatoryBook_FR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsTrueUpDepreciation name="IsTrueUpDepreciation">IsTrueUpDepreciation</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTrueUpDepreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LinkedCurrentLayerAssetBookTable_JP name="LinkedCurrentLayerAssetBookTable_JP">LinkedCurrentLayerAssetBookTable_JP</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinkedCurrentLayerAssetBookTable_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowCostAsset_HU name="LowCostAsset_HU">LowCostAsset_HU</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowCostAsset_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NegativeNetBookValue name="NegativeNetBookValue">NegativeNetBookValue</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeNetBookValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NetBookValueRest name="NetBookValueRest">NetBookValueRest</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetBookValueRest attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OverRideCalendarDays_IN name="OverRideCalendarDays_IN">OverRideCalendarDays_IN</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverRideCalendarDays_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RoundOffDepreciation name="RoundOffDepreciation">RoundOffDepreciation</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffDepreciation attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RoundOffType_W name="RoundOffType_W">RoundOffType_W</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffType_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxCategoryTogether_LV name="TaxCategoryTogether_LV">TaxCategoryTogether_LV</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCategoryTogether_LV attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WorkingDays_IN name="WorkingDays_IN">WorkingDays_IN</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkingDays_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CurrencyCode_RU name="CurrencyCode_RU">CurrencyCode_RU</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile_RU name="PostingProfile_RU">PostingProfile_RU</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileShortage_RU name="PostingProfileShortage_RU">PostingProfileShortage_RU</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileShortage_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension_RU name="DefaultDimension_RU">DefaultDimension_RU</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RoundOff_RU name="RoundOff_RU">RoundOff_RU</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOff_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RoundOffDepreciationReportingCurrency name="RoundOffDepreciationReportingCurrency">RoundOffDepreciationReportingCurrency</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffDepreciationReportingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NetBookValueRestReportingCurrency name="NetBookValueRestReportingCurrency">NetBookValueRestReportingCurrency</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetBookValueRestReportingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/AssetBookTable (this entity)  

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

### <a href=#Relationship_AssetDepreciationProfileRelationshipId name="Relationship_AssetDepreciationProfileRelationshipId">Relationship_AssetDepreciationProfileRelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetDepreciationProfile.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.cdm.json/AssetDepreciationProfile</a></td><td><a href="../Parameter/AssetDepreciationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DepreciationAcceleratedProfile_JPRelationshipId name="Relationship_DepreciationAcceleratedProfile_JPRelationshipId">Relationship_DepreciationAcceleratedProfile_JPRelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepreciationAcceleratedProfile_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetDepreciationProfile.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.cdm.json/AssetDepreciationProfile</a></td><td><a href="../Parameter/AssetDepreciationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DepreciationAltProfileRelationshipId name="Relationship_DepreciationAltProfileRelationshipId">Relationship_DepreciationAltProfileRelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepreciationAltProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetDepreciationProfile.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.cdm.json/AssetDepreciationProfile</a></td><td><a href="../Parameter/AssetDepreciationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DepreciationExtProfileRelationshipId name="Relationship_DepreciationExtProfileRelationshipId">Relationship_DepreciationExtProfileRelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepreciationExtProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetDepreciationProfile.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.cdm.json/AssetDepreciationProfile</a></td><td><a href="../Parameter/AssetDepreciationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalCalendarRelationshipId name="Relationship_FiscalCalendarRelationshipId">Relationship_FiscalCalendarRelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalCalendarRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Reference/FiscalCalendar.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Reference/FiscalCalendar.cdm.json/FiscalCalendar</a></td><td><a href="../../Ledger/Reference/FiscalCalendar.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimension_RURelationshipId name="Relationship_DefaultDimension_RURelationshipId">Relationship_DefaultDimension_RURelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimension_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Currency_RURelationshipId name="Relationship_Currency_RURelationshipId">Relationship_Currency_RURelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetLedger_RURelationshipId name="Relationship_AssetLedger_RURelationshipId">Relationship_AssetLedger_RURelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetLedger_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetLedger.cdm.json/AssetLedger</a></td><td><a href="../Parameter/AssetLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetLedgerShortage_RURelationshipId name="Relationship_AssetLedgerShortage_RURelationshipId">Relationship_AssetLedgerShortage_RURelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetLedgerShortage_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetLedger.cdm.json/AssetLedger</a></td><td><a href="../Parameter/AssetLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/AssetBookTable (this entity)  

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
