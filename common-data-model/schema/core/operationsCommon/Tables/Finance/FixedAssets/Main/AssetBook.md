---
title: AssetBook in Main - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Fixed asset book in Main(AssetBook)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBook.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetBook/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed asset book</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AcquisitionDate](#AcquisitionDate)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AcquisitionMethod](#AcquisitionMethod)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AcquisitionPrice](#AcquisitionPrice)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AllocationStartDate_JP](#AllocationStartDate_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AllowableLimitForAccumulatedDepType_JP](#AllowableLimitForAccumulatedDepType_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetCostAccountingType_PL](#AssetCostAccountingType_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetDerogatoryModel_FR](#AssetDerogatoryModel_FR)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetFairValue](#AssetFairValue)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetGroup](#AssetGroup)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetGroupDepreciation_IN](#AssetGroupDepreciation_IN)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetId](#AssetId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetPurchaseDate_PL](#AssetPurchaseDate_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetRevisedAcquisitionCost_JP](#AssetRevisedAcquisitionCost_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AssetRevisedAcquisitionCostStartDate_JP](#AssetRevisedAcquisitionCostStartDate_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[BookId](#BookId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[CategorizationDate_CZ](#CategorizationDate_CZ)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[CheckMaxPercentRB](#CheckMaxPercentRB)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ConsumptionFactorId](#ConsumptionFactorId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ConsumptionQtyEstimated](#ConsumptionQtyEstimated)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ConsumptionUnitId](#ConsumptionUnitId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[CustAccount](#CustAccount)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[CustInvoiceId](#CustInvoiceId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DefaultDimension](#DefaultDimension)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Depreciation](#Depreciation)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationAmountUnit](#DepreciationAmountUnit)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationConvention](#DepreciationConvention)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationGroupId_W](#DepreciationGroupId_W)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationStartDate](#DepreciationStartDate)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DeprPrevPeriods_PL](#DeprPrevPeriods_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DeprPrevPeriodsNonCost_PL](#DeprPrevPeriodsNonCost_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DeprPrevPriorCost_PL](#DeprPrevPriorCost_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DeprPrevPriorNonCost_PL](#DeprPrevPriorNonCost_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DisposalDate](#DisposalDate)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DueFrom_PSN](#DueFrom_PSN)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DueTo_PSN](#DueTo_PSN)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[EquallyDividedStartDate_JP](#EquallyDividedStartDate_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ExceedingNetBookValue](#ExceedingNetBookValue)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[IsDerogatoryBook_FR](#IsDerogatoryBook_FR)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[IsDisposalSameYear](#IsDisposalSameYear)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[IsShorteningUsefulLife_JP](#IsShorteningUsefulLife_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[IsTrueUpDepreciation](#IsTrueUpDepreciation)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[LastDepreciationDate](#LastDepreciationDate)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[LastDepreciationDateAccelerated_JP](#LastDepreciationDateAccelerated_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[LastDepreciationDateExtraOrd](#LastDepreciationDateExtraOrd)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[LastReserveAllocationDate_JP](#LastReserveAllocationDate_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[LifeTime](#LifeTime)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[LifeTimeRest](#LifeTimeRest)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[LVPTransferDate_AU](#LVPTransferDate_AU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[LVPTransferId_AU](#LVPTransferId_AU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[MaxPercentRB](#MaxPercentRB)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[NegativeNetBookValue](#NegativeNetBookValue)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[OrigAcquisitionDate_IN](#OrigAcquisitionDate_IN)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Percentage_PL](#Percentage_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[PercentageAlt_PL](#PercentageAlt_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[PercentageExt_PL](#PercentageExt_PL)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[PostingProfile](#PostingProfile)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[PurchId](#PurchId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[RBSLFactor](#RBSLFactor)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ReplacementDate](#ReplacementDate)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ReserveTypeId](#ReserveTypeId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[RevaluationGroupId](#RevaluationGroupId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SaleValue](#SaleValue)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ScrapValue](#ScrapValue)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ServiceLife](#ServiceLife)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ServiceLifeMonths_FR](#ServiceLifeMonths_FR)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ServiceLifeYears_FR](#ServiceLifeYears_FR)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SortingId](#SortingId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SortingId2](#SortingId2)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SortingId3](#SortingId3)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SpecialDepAllocationConvention_JP](#SpecialDepAllocationConvention_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SpecialDepAllocationPeriods_JP](#SpecialDepAllocationPeriods_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SpecialDepAllocationUnit_JP](#SpecialDepAllocationUnit_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SpecialDepLastAllocationDate_JP](#SpecialDepLastAllocationDate_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SpecialDepStartDate_JP](#SpecialDepStartDate_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Status](#Status)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SummarizeByMajorType_JP](#SummarizeByMajorType_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[UsedFromDate](#UsedFromDate)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[VendAccount](#VendAccount)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[VendInvoiceId](#VendInvoiceId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationProfile](#DepreciationProfile)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationAltProfile](#DepreciationAltProfile)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationExtProfile](#DepreciationExtProfile)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationAcceleratedProfile_JP](#DepreciationAcceleratedProfile_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[InventTransId_RU](#InventTransId_RU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[CurrencyCode_RU](#CurrencyCode_RU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SubGroupId_RU](#SubGroupId_RU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Lock_RU](#Lock_RU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[NumberSequenceGroupId_RU](#NumberSequenceGroupId_RU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[PurchInternalInvoiceId_RU](#PurchInternalInvoiceId_RU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[SalesId_RU](#SalesId_RU)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationExtProfile_JP](#DepreciationExtProfile_JP)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[AcquisitionPriceReportingCurrency](#AcquisitionPriceReportingCurrency)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[ScrapValueReportingCurrency](#ScrapValueReportingCurrency)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DepreciationAmountUnitReportingCurrency](#DepreciationAmountUnitReportingCurrency)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetAcquisitionMethodRelationshipId](#Relationship_AssetAcquisitionMethodRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetBookTableRelationshipId](#Relationship_AssetBookTableRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetChangesHistoryRelationshipId](#Relationship_AssetChangesHistoryRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetConsumptionFactorRelationshipId](#Relationship_AssetConsumptionFactorRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetConsumptionUnitRelationshipId](#Relationship_AssetConsumptionUnitRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetGroup_AssetRelationshipId](#Relationship_AssetGroup_AssetRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetLedgerRelationshipId](#Relationship_AssetLedgerRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetReserveTypeRelationshipId](#Relationship_AssetReserveTypeRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetRevaluationGroupRelationshipId](#Relationship_AssetRevaluationGroupRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetSorting_SortingIdRelationshipId](#Relationship_AssetSorting_SortingIdRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetSorting_SortingId2RelationshipId](#Relationship_AssetSorting_SortingId2RelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetSorting_SortingId3RelationshipId](#Relationship_AssetSorting_SortingId3RelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetTable_AssertIdRelationshipId](#Relationship_AssetTable_AssertIdRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_AssetTable_LVPTransferIdRelationshipId](#Relationship_AssetTable_LVPTransferIdRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_assettransRelationshipId](#Relationship_assettransRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_CustInvoiceRelationshipId](#Relationship_CustInvoiceRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_DepreciationGroupRelationshipId](#Relationship_DepreciationGroupRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_DueFrom_PSNRelationshipId](#Relationship_DueFrom_PSNRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_DueTo_PSNRelationshipId](#Relationship_DueTo_PSNRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_PurchTableRelationshipId](#Relationship_PurchTableRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_DepreciationProfileRelationshipId](#Relationship_DepreciationProfileRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_DepreciationAltProfileRelationshipId](#Relationship_DepreciationAltProfileRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_DepreciationExtProfileRelationshipId](#Relationship_DepreciationExtProfileRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_DepreciationAcceleratedProfile_JPRelationshipId](#Relationship_DepreciationAcceleratedProfile_JPRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_InventTransOrigin_RURelationshipId](#Relationship_InventTransOrigin_RURelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_Currency_RURelationshipId](#Relationship_Currency_RURelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_RAssetSubGroup_RURelationshipId](#Relationship_RAssetSubGroup_RURelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_NumberSequenceGroup_RURelationshipId](#Relationship_NumberSequenceGroup_RURelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetBook.md" target="_blank">Main/AssetBook</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetBook/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcquisitionDate name="AcquisitionDate">AcquisitionDate</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#AcquisitionMethod name="AcquisitionMethod">AcquisitionMethod</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionPrice name="AcquisitionPrice">AcquisitionPrice</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AllocationStartDate_JP name="AllocationStartDate_JP">AllocationStartDate_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationStartDate_JP attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#AllowableLimitForAccumulatedDepType_JP name="AllowableLimitForAccumulatedDepType_JP">AllowableLimitForAccumulatedDepType_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowableLimitForAccumulatedDepType_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetCostAccountingType_PL name="AssetCostAccountingType_PL">AssetCostAccountingType_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetCostAccountingType_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetDerogatoryModel_FR name="AssetDerogatoryModel_FR">AssetDerogatoryModel_FR</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDerogatoryModel_FR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetFairValue name="AssetFairValue">AssetFairValue</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetFairValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssetGroup name="AssetGroup">AssetGroup</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetGroupDepreciation_IN name="AssetGroupDepreciation_IN">AssetGroupDepreciation_IN</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroupDepreciation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetPurchaseDate_PL name="AssetPurchaseDate_PL">AssetPurchaseDate_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetPurchaseDate_PL attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#AssetRevisedAcquisitionCost_JP name="AssetRevisedAcquisitionCost_JP">AssetRevisedAcquisitionCost_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetRevisedAcquisitionCost_JP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssetRevisedAcquisitionCostStartDate_JP name="AssetRevisedAcquisitionCostStartDate_JP">AssetRevisedAcquisitionCostStartDate_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetRevisedAcquisitionCostStartDate_JP attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#BookId name="BookId">BookId</a>

First included in: Main/AssetBook (this entity)  

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

### <a href=#CategorizationDate_CZ name="CategorizationDate_CZ">CategorizationDate_CZ</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategorizationDate_CZ attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CheckMaxPercentRB name="CheckMaxPercentRB">CheckMaxPercentRB</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check maximum percent</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckMaxPercentRB attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Check maximum percent</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ConsumptionFactorId name="ConsumptionFactorId">ConsumptionFactorId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionFactorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionQtyEstimated name="ConsumptionQtyEstimated">ConsumptionQtyEstimated</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionQtyEstimated attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumptionUnitId name="ConsumptionUnitId">ConsumptionUnitId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustInvoiceId name="CustInvoiceId">CustInvoiceId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Depreciation name="Depreciation">Depreciation</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Depreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationAmountUnit name="DepreciationAmountUnit">DepreciationAmountUnit</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAmountUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationConvention name="DepreciationConvention">DepreciationConvention</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationConvention attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationGroupId_W name="DepreciationGroupId_W">DepreciationGroupId_W</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationGroupId_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationStartDate name="DepreciationStartDate">DepreciationStartDate</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationStartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DeprPrevPeriods_PL name="DeprPrevPeriods_PL">DeprPrevPeriods_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depreciation amount before registration</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeprPrevPeriods_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depreciation amount before registration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DeprPrevPeriodsNonCost_PL name="DeprPrevPeriodsNonCost_PL">DeprPrevPeriodsNonCost_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Non-cost depreciation amount before registration</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeprPrevPeriodsNonCost_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Non-cost depreciation amount before registration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DeprPrevPriorCost_PL name="DeprPrevPriorCost_PL">DeprPrevPriorCost_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depreciation amount before registration (prior years)</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeprPrevPriorCost_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depreciation amount before registration (prior years)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DeprPrevPriorNonCost_PL name="DeprPrevPriorNonCost_PL">DeprPrevPriorNonCost_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Non-cost depreciation amount before registration (prior years)</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeprPrevPriorNonCost_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Non-cost depreciation amount before registration (prior years)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DisposalDate name="DisposalDate">DisposalDate</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DueFrom_PSN name="DueFrom_PSN">DueFrom_PSN</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transfer from account</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueFrom_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transfer from account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DueTo_PSN name="DueTo_PSN">DueTo_PSN</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transfer to account</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueTo_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transfer to account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EquallyDividedStartDate_JP name="EquallyDividedStartDate_JP">EquallyDividedStartDate_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EquallyDividedStartDate_JP attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ExceedingNetBookValue name="ExceedingNetBookValue">ExceedingNetBookValue</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceedingNetBookValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsDerogatoryBook_FR name="IsDerogatoryBook_FR">IsDerogatoryBook_FR</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDerogatoryBook_FR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsDisposalSameYear name="IsDisposalSameYear">IsDisposalSameYear</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDisposalSameYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsShorteningUsefulLife_JP name="IsShorteningUsefulLife_JP">IsShorteningUsefulLife_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsShorteningUsefulLife_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsTrueUpDepreciation name="IsTrueUpDepreciation">IsTrueUpDepreciation</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTrueUpDepreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LastDepreciationDate name="LastDepreciationDate">LastDepreciationDate</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDepreciationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LastDepreciationDateAccelerated_JP name="LastDepreciationDateAccelerated_JP">LastDepreciationDateAccelerated_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDepreciationDateAccelerated_JP attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LastDepreciationDateExtraOrd name="LastDepreciationDateExtraOrd">LastDepreciationDateExtraOrd</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDepreciationDateExtraOrd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LastReserveAllocationDate_JP name="LastReserveAllocationDate_JP">LastReserveAllocationDate_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastReserveAllocationDate_JP attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LifeTime name="LifeTime">LifeTime</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LifeTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LifeTimeRest name="LifeTimeRest">LifeTimeRest</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LifeTimeRest attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LVPTransferDate_AU name="LVPTransferDate_AU">LVPTransferDate_AU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LVPTransferDate_AU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LVPTransferId_AU name="LVPTransferId_AU">LVPTransferId_AU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LVPTransferId_AU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxPercentRB name="MaxPercentRB">MaxPercentRB</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage after validation</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxPercentRB attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Percentage after validation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NegativeNetBookValue name="NegativeNetBookValue">NegativeNetBookValue</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeNetBookValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OrigAcquisitionDate_IN name="OrigAcquisitionDate_IN">OrigAcquisitionDate_IN</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigAcquisitionDate_IN attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Percentage_PL name="Percentage_PL">Percentage_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percentage_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PercentageAlt_PL name="PercentageAlt_PL">PercentageAlt_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentageAlt_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PercentageExt_PL name="PercentageExt_PL">PercentageExt_PL</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentageExt_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchId name="PurchId">PurchId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RBSLFactor name="RBSLFactor">RBSLFactor</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RBSLFactor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReplacementDate name="ReplacementDate">ReplacementDate</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplacementDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ReserveTypeId name="ReserveTypeId">ReserveTypeId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReserveTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevaluationGroupId name="RevaluationGroupId">RevaluationGroupId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevaluationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SaleValue name="SaleValue">SaleValue</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaleValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ScrapValue name="ScrapValue">ScrapValue</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScrapValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ServiceLife name="ServiceLife">ServiceLife</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLife attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ServiceLifeMonths_FR name="ServiceLifeMonths_FR">ServiceLifeMonths_FR</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLifeMonths_FR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ServiceLifeYears_FR name="ServiceLifeYears_FR">ServiceLifeYears_FR</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLifeYears_FR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SortingId name="SortingId">SortingId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingId2 name="SortingId2">SortingId2</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingId3 name="SortingId3">SortingId3</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepAllocationConvention_JP name="SpecialDepAllocationConvention_JP">SpecialDepAllocationConvention_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepAllocationConvention_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpecialDepAllocationPeriods_JP name="SpecialDepAllocationPeriods_JP">SpecialDepAllocationPeriods_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepAllocationPeriods_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpecialDepAllocationUnit_JP name="SpecialDepAllocationUnit_JP">SpecialDepAllocationUnit_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepAllocationUnit_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpecialDepLastAllocationDate_JP name="SpecialDepLastAllocationDate_JP">SpecialDepLastAllocationDate_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepLastAllocationDate_JP attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SpecialDepStartDate_JP name="SpecialDepStartDate_JP">SpecialDepStartDate_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepStartDate_JP attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SummarizeByMajorType_JP name="SummarizeByMajorType_JP">SummarizeByMajorType_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummarizeByMajorType_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UsedFromDate name="UsedFromDate">UsedFromDate</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsedFromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendInvoiceId name="VendInvoiceId">VendInvoiceId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationProfile name="DepreciationProfile">DepreciationProfile</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationAltProfile name="DepreciationAltProfile">DepreciationAltProfile</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAltProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationExtProfile name="DepreciationExtProfile">DepreciationExtProfile</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationExtProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationAcceleratedProfile_JP name="DepreciationAcceleratedProfile_JP">DepreciationAcceleratedProfile_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAcceleratedProfile_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransId_RU name="InventTransId_RU">InventTransId_RU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode_RU name="CurrencyCode_RU">CurrencyCode_RU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubGroupId_RU name="SubGroupId_RU">SubGroupId_RU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubGroupId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Lock_RU name="Lock_RU">Lock_RU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Lock_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NumberSequenceGroupId_RU name="NumberSequenceGroupId_RU">NumberSequenceGroupId_RU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroupId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchInternalInvoiceId_RU name="PurchInternalInvoiceId_RU">PurchInternalInvoiceId_RU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchInternalInvoiceId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesId_RU name="SalesId_RU">SalesId_RU</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationExtProfile_JP name="DepreciationExtProfile_JP">DepreciationExtProfile_JP</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationExtProfile_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionPriceReportingCurrency name="AcquisitionPriceReportingCurrency">AcquisitionPriceReportingCurrency</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionPriceReportingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ScrapValueReportingCurrency name="ScrapValueReportingCurrency">ScrapValueReportingCurrency</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScrapValueReportingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationAmountUnitReportingCurrency name="DepreciationAmountUnitReportingCurrency">DepreciationAmountUnitReportingCurrency</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAmountUnitReportingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/AssetBook (this entity)  

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

### <a href=#Relationship_AssetAcquisitionMethodRelationshipId name="Relationship_AssetAcquisitionMethodRelationshipId">Relationship_AssetAcquisitionMethodRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetAcquisitionMethodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetAcquisitionMethod.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetAcquisitionMethod.cdm.json/AssetAcquisitionMethod</a></td><td><a href="AssetAcquisitionMethod.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetBookTableRelationshipId name="Relationship_AssetBookTableRelationshipId">Relationship_AssetBookTableRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetBookTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json/AssetBookTable</a></td><td><a href="AssetBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetChangesHistoryRelationshipId name="Relationship_AssetChangesHistoryRelationshipId">Relationship_AssetChangesHistoryRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetChangesHistoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/AssetChangesHistory.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Transaction/AssetChangesHistory.cdm.json/AssetChangesHistory</a></td><td><a href="../Transaction/AssetChangesHistory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetConsumptionFactorRelationshipId name="Relationship_AssetConsumptionFactorRelationshipId">Relationship_AssetConsumptionFactorRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetConsumptionFactorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetConsumptionFactor.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetConsumptionFactor.cdm.json/AssetConsumptionFactor</a></td><td><a href="../Parameter/AssetConsumptionFactor.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetConsumptionUnitRelationshipId name="Relationship_AssetConsumptionUnitRelationshipId">Relationship_AssetConsumptionUnitRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetConsumptionUnitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetConsumptionUnit.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetConsumptionUnit.cdm.json/AssetConsumptionUnit</a></td><td><a href="../Parameter/AssetConsumptionUnit.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetGroup_AssetRelationshipId name="Relationship_AssetGroup_AssetRelationshipId">Relationship_AssetGroup_AssetRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetGroup_AssetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetGroup.cdm.json/AssetGroup</a></td><td><a href="../Group/AssetGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetLedgerRelationshipId name="Relationship_AssetLedgerRelationshipId">Relationship_AssetLedgerRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetLedgerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetReserveTypeRelationshipId name="Relationship_AssetReserveTypeRelationshipId">Relationship_AssetReserveTypeRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetReserveTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetReserveType.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetReserveType.cdm.json/AssetReserveType</a></td><td><a href="../Parameter/AssetReserveType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetRevaluationGroupRelationshipId name="Relationship_AssetRevaluationGroupRelationshipId">Relationship_AssetRevaluationGroupRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetRevaluationGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetRevaluationGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetRevaluationGroup.cdm.json/AssetRevaluationGroup</a></td><td><a href="../Group/AssetRevaluationGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetSorting_SortingIdRelationshipId name="Relationship_AssetSorting_SortingIdRelationshipId">Relationship_AssetSorting_SortingIdRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetSorting_SortingIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetSorting.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetSorting.cdm.json/AssetSorting</a></td><td><a href="../Parameter/AssetSorting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetSorting_SortingId2RelationshipId name="Relationship_AssetSorting_SortingId2RelationshipId">Relationship_AssetSorting_SortingId2RelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetSorting_SortingId2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetSorting.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetSorting.cdm.json/AssetSorting</a></td><td><a href="../Parameter/AssetSorting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetSorting_SortingId3RelationshipId name="Relationship_AssetSorting_SortingId3RelationshipId">Relationship_AssetSorting_SortingId3RelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetSorting_SortingId3RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetSorting.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetSorting.cdm.json/AssetSorting</a></td><td><a href="../Parameter/AssetSorting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetTable_AssertIdRelationshipId name="Relationship_AssetTable_AssertIdRelationshipId">Relationship_AssetTable_AssertIdRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetTable_AssertIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetTable.cdm.json/AssetTable</a></td><td><a href="AssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetTable_LVPTransferIdRelationshipId name="Relationship_AssetTable_LVPTransferIdRelationshipId">Relationship_AssetTable_LVPTransferIdRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetTable_LVPTransferIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetTable.cdm.json/AssetTable</a></td><td><a href="AssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_assettransRelationshipId name="Relationship_assettransRelationshipId">Relationship_assettransRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_assettransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/AssetTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Transaction/AssetTrans.cdm.json/AssetTrans</a></td><td><a href="../Transaction/AssetTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceRelationshipId name="Relationship_CustInvoiceRelationshipId">Relationship_CustInvoiceRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustInvoiceJour.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustInvoiceJour.cdm.json/CustInvoiceJour</a></td><td><a href="../../AccountsReceivable/Transaction/CustInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DepreciationGroupRelationshipId name="Relationship_DepreciationGroupRelationshipId">Relationship_DepreciationGroupRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepreciationGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetDepreciationGroup_W.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetDepreciationGroup_W.cdm.json/AssetDepreciationGroup_W</a></td><td><a href="../Group/AssetDepreciationGroup_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DueFrom_PSNRelationshipId name="Relationship_DueFrom_PSNRelationshipId">Relationship_DueFrom_PSNRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DueFrom_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/MainAccount.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/MainAccount.cdm.json/MainAccount</a></td><td><a href="../../FinancialDimensions/Main/MainAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DueTo_PSNRelationshipId name="Relationship_DueTo_PSNRelationshipId">Relationship_DueTo_PSNRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DueTo_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/MainAccount.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/MainAccount.cdm.json/MainAccount</a></td><td><a href="../../FinancialDimensions/Main/MainAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTableRelationshipId name="Relationship_PurchTableRelationshipId">Relationship_PurchTableRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DepreciationProfileRelationshipId name="Relationship_DepreciationProfileRelationshipId">Relationship_DepreciationProfileRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepreciationProfileRelationshipId attribute are listed below.</summary>

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

First included in: Main/AssetBook (this entity)  

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

First included in: Main/AssetBook (this entity)  

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

### <a href=#Relationship_DepreciationAcceleratedProfile_JPRelationshipId name="Relationship_DepreciationAcceleratedProfile_JPRelationshipId">Relationship_DepreciationAcceleratedProfile_JPRelationshipId</a>

First included in: Main/AssetBook (this entity)  

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

### <a href=#Relationship_InventTransOrigin_RURelationshipId name="Relationship_InventTransOrigin_RURelationshipId">Relationship_InventTransOrigin_RURelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransOrigin_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../../../SupplyChain/Inventory/Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Currency_RURelationshipId name="Relationship_Currency_RURelationshipId">Relationship_Currency_RURelationshipId</a>

First included in: Main/AssetBook (this entity)  

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

### <a href=#Relationship_RAssetSubGroup_RURelationshipId name="Relationship_RAssetSubGroup_RURelationshipId">Relationship_RAssetSubGroup_RURelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetSubGroup_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Group/RAssetSubGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Group/RAssetSubGroup.cdm.json/RAssetSubGroup</a></td><td><a href="../../RAsset/Group/RAssetSubGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceGroup_RURelationshipId name="Relationship_NumberSequenceGroup_RURelationshipId">Relationship_NumberSequenceGroup_RURelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceGroup_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceGroup.cdm.json/NumberSequenceGroup</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: Main/AssetBook (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/AssetBook (this entity)  

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
