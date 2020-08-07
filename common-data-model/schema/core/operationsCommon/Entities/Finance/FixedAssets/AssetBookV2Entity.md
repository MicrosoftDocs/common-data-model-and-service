---
title: AssetBookV2Entity in FixedAssets - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Fixed asset book V2 in FixedAssets(AssetBookV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetBookV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed asset book V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FixedAssetNumber](#FixedAssetNumber)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[BookId](#BookId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[FixedAssetGroupId](#FixedAssetGroupId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AllowNetBookValueHigherThanAcquisitionCosts](#AllowNetBookValueHigherThanAcquisitionCosts)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AllowNegativeNetBookValue](#AllowNegativeNetBookValue)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Status](#Status)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[PostingProfileId](#PostingProfileId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AcquisitionDate](#AcquisitionDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AcquisitionPrice](#AcquisitionPrice)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AcquisitionMethodId](#AcquisitionMethodId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AcquisitionMethodDescription](#AcquisitionMethodDescription)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DisposalDate](#DisposalDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SalesValue](#SalesValue)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ReplacementDate](#ReplacementDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[RevaluationGroupId](#RevaluationGroupId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[FairValue](#FairValue)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ProvisionType](#ProvisionType)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[LowValuePoolTransferId](#LowValuePoolTransferId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[LowValuePoolTransferDate](#LowValuePoolTransferDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SummarizeByMajorType](#SummarizeByMajorType)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ExtraordinaryDepreciationProfileId](#ExtraordinaryDepreciationProfileId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SpecialDepreciationAllocationStartConvention](#SpecialDepreciationAllocationStartConvention)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SpecialDepreciationAllocationUnit](#SpecialDepreciationAllocationUnit)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SpecialDepreciationAllocationPeriods](#SpecialDepreciationAllocationPeriods)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[CalculateDepreciation](#CalculateDepreciation)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DepreciationProfileId](#DepreciationProfileId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[PlacedInService](#PlacedInService)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DepreciationRunDate](#DepreciationRunDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DepreciationLastRunDate](#DepreciationLastRunDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ReducingBalanceCheckMaximumPercent](#ReducingBalanceCheckMaximumPercent)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ReducingBalancePercentageAfterValidation](#ReducingBalancePercentageAfterValidation)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AlternativeDepreciationProfileId](#AlternativeDepreciationProfileId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ServiceLife](#ServiceLife)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DepreciationPeriods](#DepreciationPeriods)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DepreciationPeriodsRemaining](#DepreciationPeriodsRemaining)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ExpectedScrapValue](#ExpectedScrapValue)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[EquallyDividedStartDate](#EquallyDividedStartDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DepreciationConvention](#DepreciationConvention)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AllowDepreciationWhenPlacedInServiceAndDisposalAreInTheSameFiscalYear](#AllowDepreciationWhenPlacedInServiceAndDisposalAreInTheSameFiscalYear)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[CreateDepreciationAdjustmentsWithBasisAdjustments](#CreateDepreciationAdjustmentsWithBasisAdjustments)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AllowableLimitForAccumulatedDepreciation](#AllowableLimitForAccumulatedDepreciation)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[RevisedAcquisitionCost](#RevisedAcquisitionCost)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[RevisedAcquisitionCostStartDate](#RevisedAcquisitionCostStartDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ShortenedUsefulLife](#ShortenedUsefulLife)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ReductionEntryAllocationStartDate](#ReductionEntryAllocationStartDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ReductionEntryAllocationLastRunDate](#ReductionEntryAllocationLastRunDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ServiceLifeMonths](#ServiceLifeMonths)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ServiceLifeYears](#ServiceLifeYears)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ReducingBalanceStraightLineFactor](#ReducingBalanceStraightLineFactor)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ExtraordinaryDepreciationLastRunDate](#ExtraordinaryDepreciationLastRunDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SpecialDepreciationRunDate](#SpecialDepreciationRunDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SpecialDepreciationAllocationLastRunDate](#SpecialDepreciationAllocationLastRunDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AcceleratedDepreciationProfileId](#AcceleratedDepreciationProfileId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AcceleratedDepreciationLastRunDate](#AcceleratedDepreciationLastRunDate)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ConsumptionFactorId](#ConsumptionFactorId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ConsumptionUnitId](#ConsumptionUnitId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ConsumptionUnitDepreciation](#ConsumptionUnitDepreciation)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ConsumptionEstimated](#ConsumptionEstimated)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DerogatoryCalculation](#DerogatoryCalculation)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DerogatoryTaxModel](#DerogatoryTaxModel)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[VendorAccount](#VendorAccount)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[PurchaseOrder](#PurchaseOrder)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[VendorInvoice](#VendorInvoice)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[CustomerInvoice](#CustomerInvoice)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Dimension](#Dimension)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SortField1Id](#SortField1Id)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SortField2Id](#SortField2Id)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[SortField3Id](#SortField3Id)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[IsAssetGroupDepreciation](#IsAssetGroupDepreciation)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[DepreciationGroupId_W](#DepreciationGroupId_W)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[AcquisitionPriceReportingCurrency](#AcquisitionPriceReportingCurrency)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ExpectedScrapValueReportingCurrency](#ExpectedScrapValueReportingCurrency)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[ConsumptionUnitDepreciationReportingCurrency](#ConsumptionUnitDepreciationReportingCurrency)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetAcquisitionMethodRelationshipId](#Relationship_AssetBookV2AssetAcquisitionMethodRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetBookTableRelationshipId](#Relationship_AssetBookV2AssetBookTableRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetReserveTypeRelationshipId](#Relationship_AssetBookV2AssetReserveTypeRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetGroupRelationshipId](#Relationship_AssetBookV2AssetGroupRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetVendorRelationshipId](#Relationship_AssetBookV2AssetVendorRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetCustomerRelationshipId](#Relationship_AssetBookV2AssetCustomerRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetSortField1RelationshipId](#Relationship_AssetBookV2AssetSortField1RelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetSortField2RelationshipId](#Relationship_AssetBookV2AssetSortField2RelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetSortField3RelationshipId](#Relationship_AssetBookV2AssetSortField3RelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetConsumptionUnitRelationshipId](#Relationship_AssetBookV2AssetConsumptionUnitRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetConsumptionFactorRelationshipId](#Relationship_AssetBookV2AssetConsumptionFactorRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetProvisionTypeEntityRelationshipId](#Relationship_AssetProvisionTypeEntityRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetDepreciationProfileRelationshipId](#Relationship_AssetBookV2AssetDepreciationProfileRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetAlternativeDepreciationProfileRelationshipId](#Relationship_AssetBookV2AssetAlternativeDepreciationProfileRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetExtraordinaryDepreciationProfileRelationshipId](#Relationship_AssetBookV2AssetExtraordinaryDepreciationProfileRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_AssetBookV2AssetAcceleratedDepreciationProfileRelationshipId](#Relationship_AssetBookV2AssetAcceleratedDepreciationProfileRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[BackingTable_AssetBookRelationshipId](#BackingTable_AssetBookRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetBookV2Entity.md" target="_blank">FixedAssets/AssetBookV2Entity</a>|

### <a href=#FixedAssetNumber name="FixedAssetNumber">FixedAssetNumber</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookId name="BookId">BookId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetGroupId name="FixedAssetGroupId">FixedAssetGroupId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowNetBookValueHigherThanAcquisitionCosts name="AllowNetBookValueHigherThanAcquisitionCosts">AllowNetBookValueHigherThanAcquisitionCosts</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowNetBookValueHigherThanAcquisitionCosts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowNegativeNetBookValue name="AllowNegativeNetBookValue">AllowNegativeNetBookValue</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowNegativeNetBookValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileId name="PostingProfileId">PostingProfileId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionDate name="AcquisitionDate">AcquisitionDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionPrice name="AcquisitionPrice">AcquisitionPrice</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionMethodId name="AcquisitionMethodId">AcquisitionMethodId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionMethodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionMethodDescription name="AcquisitionMethodDescription">AcquisitionMethodDescription</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Acquisition method description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionMethodDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Acquisition method description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisposalDate name="DisposalDate">DisposalDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesValue name="SalesValue">SalesValue</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplacementDate name="ReplacementDate">ReplacementDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplacementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevaluationGroupId name="RevaluationGroupId">RevaluationGroupId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

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

### <a href=#FairValue name="FairValue">FairValue</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FairValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProvisionType name="ProvisionType">ProvisionType</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provision type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProvisionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Provision type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowValuePoolTransferId name="LowValuePoolTransferId">LowValuePoolTransferId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowValuePoolTransferId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowValuePoolTransferDate name="LowValuePoolTransferDate">LowValuePoolTransferDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowValuePoolTransferDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SummarizeByMajorType name="SummarizeByMajorType">SummarizeByMajorType</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummarizeByMajorType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtraordinaryDepreciationProfileId name="ExtraordinaryDepreciationProfileId">ExtraordinaryDepreciationProfileId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtraordinaryDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAllocationStartConvention name="SpecialDepreciationAllocationStartConvention">SpecialDepreciationAllocationStartConvention</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAllocationStartConvention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAllocationUnit name="SpecialDepreciationAllocationUnit">SpecialDepreciationAllocationUnit</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAllocationUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAllocationPeriods name="SpecialDepreciationAllocationPeriods">SpecialDepreciationAllocationPeriods</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAllocationPeriods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculateDepreciation name="CalculateDepreciation">CalculateDepreciation</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationProfileId name="DepreciationProfileId">DepreciationProfileId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

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

### <a href=#PlacedInService name="PlacedInService">PlacedInService</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlacedInService attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationRunDate name="DepreciationRunDate">DepreciationRunDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationRunDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationLastRunDate name="DepreciationLastRunDate">DepreciationLastRunDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationLastRunDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReducingBalanceCheckMaximumPercent name="ReducingBalanceCheckMaximumPercent">ReducingBalanceCheckMaximumPercent</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReducingBalanceCheckMaximumPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReducingBalancePercentageAfterValidation name="ReducingBalancePercentageAfterValidation">ReducingBalancePercentageAfterValidation</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReducingBalancePercentageAfterValidation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeDepreciationProfileId name="AlternativeDepreciationProfileId">AlternativeDepreciationProfileId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLife name="ServiceLife">ServiceLife</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLife attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationPeriods name="DepreciationPeriods">DepreciationPeriods</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationPeriods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationPeriodsRemaining name="DepreciationPeriodsRemaining">DepreciationPeriodsRemaining</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationPeriodsRemaining attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpectedScrapValue name="ExpectedScrapValue">ExpectedScrapValue</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedScrapValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EquallyDividedStartDate name="EquallyDividedStartDate">EquallyDividedStartDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Equally divided start date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EquallyDividedStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Equally divided start date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationConvention name="DepreciationConvention">DepreciationConvention</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationConvention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowDepreciationWhenPlacedInServiceAndDisposalAreInTheSameFiscalYear name="AllowDepreciationWhenPlacedInServiceAndDisposalAreInTheSameFiscalYear">AllowDepreciationWhenPlacedInServiceAndDisposalAreInTheSameFiscalYear</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowDepreciationWhenPlacedInServiceAndDisposalAreInTheSameFiscalYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateDepreciationAdjustmentsWithBasisAdjustments name="CreateDepreciationAdjustmentsWithBasisAdjustments">CreateDepreciationAdjustmentsWithBasisAdjustments</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateDepreciationAdjustmentsWithBasisAdjustments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowableLimitForAccumulatedDepreciation name="AllowableLimitForAccumulatedDepreciation">AllowableLimitForAccumulatedDepreciation</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowableLimitForAccumulatedDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevisedAcquisitionCost name="RevisedAcquisitionCost">RevisedAcquisitionCost</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevisedAcquisitionCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevisedAcquisitionCostStartDate name="RevisedAcquisitionCostStartDate">RevisedAcquisitionCostStartDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revised acquisition cost date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevisedAcquisitionCostStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Revised acquisition cost date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShortenedUsefulLife name="ShortenedUsefulLife">ShortenedUsefulLife</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShortenedUsefulLife attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReductionEntryAllocationStartDate name="ReductionEntryAllocationStartDate">ReductionEntryAllocationStartDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reduction entry allocation start date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReductionEntryAllocationStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reduction entry allocation start date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReductionEntryAllocationLastRunDate name="ReductionEntryAllocationLastRunDate">ReductionEntryAllocationLastRunDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date when reduction entry allocation last run</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReductionEntryAllocationLastRunDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date when reduction entry allocation last run</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLifeMonths name="ServiceLifeMonths">ServiceLifeMonths</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service life months</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLifeMonths attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service life months</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLifeYears name="ServiceLifeYears">ServiceLifeYears</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service life years</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLifeYears attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service life years</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReducingBalanceStraightLineFactor name="ReducingBalanceStraightLineFactor">ReducingBalanceStraightLineFactor</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReducingBalanceStraightLineFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtraordinaryDepreciationLastRunDate name="ExtraordinaryDepreciationLastRunDate">ExtraordinaryDepreciationLastRunDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date when extraordinary depreciation was last run</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtraordinaryDepreciationLastRunDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date when extraordinary depreciation was last run</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationRunDate name="SpecialDepreciationRunDate">SpecialDepreciationRunDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extraordinary depreciation run date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationRunDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Extraordinary depreciation run date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAllocationLastRunDate name="SpecialDepreciationAllocationLastRunDate">SpecialDepreciationAllocationLastRunDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAllocationLastRunDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepreciationProfileId name="AcceleratedDepreciationProfileId">AcceleratedDepreciationProfileId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepreciationLastRunDate name="AcceleratedDepreciationLastRunDate">AcceleratedDepreciationLastRunDate</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepreciationLastRunDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionFactorId name="ConsumptionFactorId">ConsumptionFactorId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

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

### <a href=#ConsumptionUnitId name="ConsumptionUnitId">ConsumptionUnitId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Consumption unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Consumption unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionUnitDepreciation name="ConsumptionUnitDepreciation">ConsumptionUnitDepreciation</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionUnitDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionEstimated name="ConsumptionEstimated">ConsumptionEstimated</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionEstimated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerogatoryCalculation name="DerogatoryCalculation">DerogatoryCalculation</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerogatoryTaxModel name="DerogatoryTaxModel">DerogatoryTaxModel</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryTaxModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrder name="PurchaseOrder">PurchaseOrder</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoice name="VendorInvoice">VendorInvoice</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor invoice</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerInvoice name="CustomerInvoice">CustomerInvoice</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer invoice</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField1Id name="SortField1Id">SortField1Id</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField1Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField2Id name="SortField2Id">SortField2Id</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField2Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField3Id name="SortField3Id">SortField3Id</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField3Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAssetGroupDepreciation name="IsAssetGroupDepreciation">IsAssetGroupDepreciation</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAssetGroupDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationGroupId_W name="DepreciationGroupId_W">DepreciationGroupId_W</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

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

### <a href=#AcquisitionPriceReportingCurrency name="AcquisitionPriceReportingCurrency">AcquisitionPriceReportingCurrency</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionPriceReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpectedScrapValueReportingCurrency name="ExpectedScrapValueReportingCurrency">ExpectedScrapValueReportingCurrency</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedScrapValueReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionUnitDepreciationReportingCurrency name="ConsumptionUnitDepreciationReportingCurrency">ConsumptionUnitDepreciationReportingCurrency</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionUnitDepreciationReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetAcquisitionMethodRelationshipId name="Relationship_AssetBookV2AssetAcquisitionMethodRelationshipId">Relationship_AssetBookV2AssetAcquisitionMethodRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetAcquisitionMethodRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetBookTableRelationshipId name="Relationship_AssetBookV2AssetBookTableRelationshipId">Relationship_AssetBookV2AssetBookTableRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetBookTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetReserveTypeRelationshipId name="Relationship_AssetBookV2AssetReserveTypeRelationshipId">Relationship_AssetBookV2AssetReserveTypeRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetReserveTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetGroupRelationshipId name="Relationship_AssetBookV2AssetGroupRelationshipId">Relationship_AssetBookV2AssetGroupRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetVendorRelationshipId name="Relationship_AssetBookV2AssetVendorRelationshipId">Relationship_AssetBookV2AssetVendorRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetVendorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetCustomerRelationshipId name="Relationship_AssetBookV2AssetCustomerRelationshipId">Relationship_AssetBookV2AssetCustomerRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetCustomerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetSortField1RelationshipId name="Relationship_AssetBookV2AssetSortField1RelationshipId">Relationship_AssetBookV2AssetSortField1RelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetSortField1RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetSortField2RelationshipId name="Relationship_AssetBookV2AssetSortField2RelationshipId">Relationship_AssetBookV2AssetSortField2RelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetSortField2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetSortField3RelationshipId name="Relationship_AssetBookV2AssetSortField3RelationshipId">Relationship_AssetBookV2AssetSortField3RelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetSortField3RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetConsumptionUnitRelationshipId name="Relationship_AssetBookV2AssetConsumptionUnitRelationshipId">Relationship_AssetBookV2AssetConsumptionUnitRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetConsumptionUnitRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetConsumptionFactorRelationshipId name="Relationship_AssetBookV2AssetConsumptionFactorRelationshipId">Relationship_AssetBookV2AssetConsumptionFactorRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetConsumptionFactorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetProvisionTypeEntityRelationshipId name="Relationship_AssetProvisionTypeEntityRelationshipId">Relationship_AssetProvisionTypeEntityRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetProvisionTypeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetDepreciationProfileRelationshipId name="Relationship_AssetBookV2AssetDepreciationProfileRelationshipId">Relationship_AssetBookV2AssetDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetDepreciationProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetAlternativeDepreciationProfileRelationshipId name="Relationship_AssetBookV2AssetAlternativeDepreciationProfileRelationshipId">Relationship_AssetBookV2AssetAlternativeDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetAlternativeDepreciationProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetExtraordinaryDepreciationProfileRelationshipId name="Relationship_AssetBookV2AssetExtraordinaryDepreciationProfileRelationshipId">Relationship_AssetBookV2AssetExtraordinaryDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetExtraordinaryDepreciationProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetBookV2AssetAcceleratedDepreciationProfileRelationshipId name="Relationship_AssetBookV2AssetAcceleratedDepreciationProfileRelationshipId">Relationship_AssetBookV2AssetAcceleratedDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookV2AssetAcceleratedDepreciationProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_AssetBookRelationshipId name="BackingTable_AssetBookRelationshipId">BackingTable_AssetBookRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetBookRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Main/AssetBook.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBook.cdm.json/AssetBook</a></td><td><a href="../../../Tables/Finance/FixedAssets/Main/AssetBook.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetBookV2Entity (this entity)  

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
