---
title: AssetParameters in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Fixed asset parameters in Parameter(AssetParameters)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed asset parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AcceleratedDepCalcMethod_JP](#AcceleratedDepCalcMethod_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AcceleratedDepRateFactor_JP](#AcceleratedDepRateFactor_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AcceleratedDepRateThreshold_JP](#AcceleratedDepRateThreshold_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Acquisition](#Acquisition)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AcquisitionAdj](#AcquisitionAdj)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AllowPreAcquisition_CZ](#AllowPreAcquisition_CZ)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetAccountingStandard_JP](#AssetAccountingStandard_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetAllowAcqPostingPO](#AssetAllowAcqPostingPO)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetAllowAutoCreate](#AssetAllowAutoCreate)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetAllowCreate](#AssetAllowCreate)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetAllowSale_PL](#AssetAllowSale_PL)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetAllowLocationTransfer_JP](#AssetAllowLocationTransfer_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetAssemblingReservation_JP](#AssetAssemblingReservation_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetChanges](#AssetChanges)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetDefaultSaleLedgerDimension_PL](#AssetDefaultSaleLedgerDimension_PL)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetPercentageLevel_PL](#AssetPercentageLevel_PL)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetUserGroupIdPostPO](#AssetUserGroupIdPostPO)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AutoNumber](#AutoNumber)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[BarcodeEqualsAssetNumber](#BarcodeEqualsAssetNumber)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[BookIdDefault](#BookIdDefault)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[CapitalizationThreshold](#CapitalizationThreshold)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[CapitalReserve](#CapitalReserve)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[CapitalReserveTransfer](#CapitalReserveTransfer)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[CheckMaxPercentRB](#CheckMaxPercentRB)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[ConsiderCapitalizationThreshold](#ConsiderCapitalizationThreshold)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DeductCashDisc](#DeductCashDisc)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Depreciation](#Depreciation)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DepreciationAdj](#DepreciationAdj)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DepreciationCompaniesAct_IN](#DepreciationCompaniesAct_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DepreciationIncomeTaxAct_IN](#DepreciationIncomeTaxAct_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DepreciationMin](#DepreciationMin)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DepreciationThreshold_IN](#DepreciationThreshold_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DerogatoryDecrease](#DerogatoryDecrease)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DerogatoryIncrease](#DerogatoryIncrease)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DisposalSale](#DisposalSale)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DisposalScrap](#DisposalScrap)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[EnableDepreciationMethods](#EnableDepreciationMethods)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[EnableDepreciationPolicy](#EnableDepreciationPolicy)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[ExtraOrdinaryDepreciation](#ExtraOrdinaryDepreciation)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[HalfYearDepreciation_AT](#HalfYearDepreciation_AT)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[ICMSCreditInstallments_BR](#ICMSCreditInstallments_BR)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[ImpairmentWarningPeriod_JP](#ImpairmentWarningPeriod_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[InventJournalNameId](#InventJournalNameId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[IsAssemblingEnabled_JP](#IsAssemblingEnabled_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[IsAutomaticPosting](#IsAutomaticPosting)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[IsDisposalSameYear](#IsDisposalSameYear)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[IsProratedDepreciation](#IsProratedDepreciation)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Key](#Key)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[LedgerDimension](#LedgerDimension)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[LowCostAssetThreshold_W](#LowCostAssetThreshold_W)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[ManuallyChangeDepProfileEnable_JP](#ManuallyChangeDepProfileEnable_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[MaxAcquisitionValue_IN](#MaxAcquisitionValue_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[MinNonSeasonalWorkingDays_IN](#MinNonSeasonalWorkingDays_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[MinSeasonalWorkingDays_IN](#MinSeasonalWorkingDays_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[MultiAcquisition](#MultiAcquisition)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[PostingProfile](#PostingProfile)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Revaluation](#Revaluation)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[ThresholdPercentage_IN](#ThresholdPercentage_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[UseCatchUpMethod_JP](#UseCatchUpMethod_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[UseSpecialDepreciatonBalance_IN](#UseSpecialDepreciatonBalance_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[WriteDownAdj](#WriteDownAdj)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[WriteUpAdj](#WriteUpAdj)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DepreciationCatchUpInterval_JP](#DepreciationCatchUpInterval_JP)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssetSaleBasis_IN](#AssetSaleBasis_IN)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AnalysisDimensionAttribute_RU](#AnalysisDimensionAttribute_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssessedRoll_RU](#AssessedRoll_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[AssessedTaxInitDate_RU](#AssessedTaxInitDate_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[CompanyIssue_RU](#CompanyIssue_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[CompanyReceipt_RU](#CompanyReceipt_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Disposal_RU](#Disposal_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Lending_RU](#Lending_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[LendingReturn_RU](#LendingReturn_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Other_RU](#Other_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[PartialTakeDown_RU](#PartialTakeDown_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[CurrencyWriteDownAdj_RU](#CurrencyWriteDownAdj_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[CurrencyWriteUpAdj_RU](#CurrencyWriteUpAdj_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[MajorRepairs_RU](#MajorRepairs_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[LandTaxCode_RU](#LandTaxCode_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[LandTaxRoll_RU](#LandTaxRoll_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[LowCostAssetInventProfileId_RU](#LowCostAssetInventProfileId_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[TaxBookIdDefault_RU](#TaxBookIdDefault_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[TaxCode_RU](#TaxCode_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[TransportTaxCode_RU](#TransportTaxCode_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[TransportTaxRoll_RU](#TransportTaxRoll_RU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[LowCostAssetThreshold_HU](#LowCostAssetThreshold_HU)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DepreciationMinReportingCurrency](#DepreciationMinReportingCurrency)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[ReportingCurrencyAmountUpdatesComplete](#ReportingCurrencyAmountUpdatesComplete)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DefaultMaintenanceFunctionalLocation](#DefaultMaintenanceFunctionalLocation)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_AssetBookTableRelationshipId](#Relationship_AssetBookTableRelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_AssetDefaultSaleDimensionRelationshipId](#Relationship_AssetDefaultSaleDimensionRelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_AssetLedgerRelationshipId](#Relationship_AssetLedgerRelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_InventJournalNameRelationshipId](#Relationship_InventJournalNameRelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_UserGroupInfoRelationshipId](#Relationship_UserGroupInfoRelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_AnalysisDimensionAttribute_RURelationshipId](#Relationship_AnalysisDimensionAttribute_RURelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_LandTaxCode_RURelationshipId](#Relationship_LandTaxCode_RURelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_InventProfile_RURelationshipId](#Relationship_InventProfile_RURelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_AssessedTaxCode_RURelationshipId](#Relationship_AssessedTaxCode_RURelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_AssetBookTableTax_RURelationshipId](#Relationship_AssetBookTableTax_RURelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_TransportTaxCode_RURelationshipId](#Relationship_TransportTaxCode_RURelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetParameters.md" target="_blank">Parameter/AssetParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcceleratedDepCalcMethod_JP name="AcceleratedDepCalcMethod_JP">AcceleratedDepCalcMethod_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepCalcMethod_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AcceleratedDepRateFactor_JP name="AcceleratedDepRateFactor_JP">AcceleratedDepRateFactor_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepRateFactor_JP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AcceleratedDepRateThreshold_JP name="AcceleratedDepRateThreshold_JP">AcceleratedDepRateThreshold_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepRateThreshold_JP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Acquisition name="Acquisition">Acquisition</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Acquisition</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Acquisition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Acquisition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AcquisitionAdj name="AcquisitionAdj">AcquisitionAdj</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Acquisition adjustment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionAdj attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Acquisition adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AllowPreAcquisition_CZ name="AllowPreAcquisition_CZ">AllowPreAcquisition_CZ</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPreAcquisition_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetAccountingStandard_JP name="AssetAccountingStandard_JP">AssetAccountingStandard_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetAccountingStandard_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetAllowAcqPostingPO name="AssetAllowAcqPostingPO">AssetAllowAcqPostingPO</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow asset acquisition from Purchasing</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetAllowAcqPostingPO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow asset acquisition from Purchasing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AssetAllowAutoCreate name="AssetAllowAutoCreate">AssetAllowAutoCreate</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetAllowAutoCreate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetAllowCreate name="AssetAllowCreate">AssetAllowCreate</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create asset during product receipt or invoice posting</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetAllowCreate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create asset during product receipt or invoice posting</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AssetAllowSale_PL name="AssetAllowSale_PL">AssetAllowSale_PL</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check whether asset can be sold</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetAllowSale_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Check whether asset can be sold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AssetAllowLocationTransfer_JP name="AssetAllowLocationTransfer_JP">AssetAllowLocationTransfer_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow location transfer</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetAllowLocationTransfer_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow location transfer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AssetAssemblingReservation_JP name="AssetAssemblingReservation_JP">AssetAssemblingReservation_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetAssemblingReservation_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetChanges name="AssetChanges">AssetChanges</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code requirements for asset changes</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetChanges attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code requirements for asset changes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AssetDefaultSaleLedgerDimension_PL name="AssetDefaultSaleLedgerDimension_PL">AssetDefaultSaleLedgerDimension_PL</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales account</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDefaultSaleLedgerDimension_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetPercentageLevel_PL name="AssetPercentageLevel_PL">AssetPercentageLevel_PL</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetPercentageLevel_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetUserGroupIdPostPO name="AssetUserGroupIdPostPO">AssetUserGroupIdPostPO</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restrict asset acquisition posting to user group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetUserGroupIdPostPO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Restrict asset acquisition posting to user group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoNumber name="AutoNumber">AutoNumber</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BarcodeEqualsAssetNumber name="BarcodeEqualsAssetNumber">BarcodeEqualsAssetNumber</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bar code equals fixed asset number</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarcodeEqualsAssetNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bar code equals fixed asset number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BookIdDefault name="BookIdDefault">BookIdDefault</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookIdDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapitalizationThreshold name="CapitalizationThreshold">CapitalizationThreshold</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapitalizationThreshold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CapitalReserve name="CapitalReserve">CapitalReserve</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provision for reserve</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapitalReserve attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Provision for reserve</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CapitalReserveTransfer name="CapitalReserveTransfer">CapitalReserveTransfer</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transfer from reserve</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapitalReserveTransfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transfer from reserve</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CheckMaxPercentRB name="CheckMaxPercentRB">CheckMaxPercentRB</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckMaxPercentRB attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ConsiderCapitalizationThreshold name="ConsiderCapitalizationThreshold">ConsiderCapitalizationThreshold</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsiderCapitalizationThreshold attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DeductCashDisc name="DeductCashDisc">DeductCashDisc</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductCashDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Depreciation name="Depreciation">Depreciation</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depreciation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Depreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationAdj name="DepreciationAdj">DepreciationAdj</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depreciation adjustment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAdj attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depreciation adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationCompaniesAct_IN name="DepreciationCompaniesAct_IN">DepreciationCompaniesAct_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Companies Act depreciation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationCompaniesAct_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Companies Act depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationIncomeTaxAct_IN name="DepreciationIncomeTaxAct_IN">DepreciationIncomeTaxAct_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Income tax Act depreciation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationIncomeTaxAct_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Income tax Act depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationMin name="DepreciationMin">DepreciationMin</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationMin attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationThreshold_IN name="DepreciationThreshold_IN">DepreciationThreshold_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationThreshold_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DerogatoryDecrease name="DerogatoryDecrease">DerogatoryDecrease</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derogatory decrease</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryDecrease attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derogatory decrease</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DerogatoryIncrease name="DerogatoryIncrease">DerogatoryIncrease</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derogatory increase</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryIncrease attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derogatory increase</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DisposalSale name="DisposalSale">DisposalSale</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disposal - sale</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalSale attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Disposal - sale</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DisposalScrap name="DisposalScrap">DisposalScrap</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disposal - scrap</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalScrap attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Disposal - scrap</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EnableDepreciationMethods name="EnableDepreciationMethods">EnableDepreciationMethods</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableDepreciationMethods attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EnableDepreciationPolicy name="EnableDepreciationPolicy">EnableDepreciationPolicy</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableDepreciationPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExtraOrdinaryDepreciation name="ExtraOrdinaryDepreciation">ExtraOrdinaryDepreciation</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extraordinary depreciation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtraOrdinaryDepreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Extraordinary depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#HalfYearDepreciation_AT name="HalfYearDepreciation_AT">HalfYearDepreciation_AT</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Apply specific rules for half year depreciation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HalfYearDepreciation_AT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Apply specific rules for half year depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ICMSCreditInstallments_BR name="ICMSCreditInstallments_BR">ICMSCreditInstallments_BR</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSCreditInstallments_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ImpairmentWarningPeriod_JP name="ImpairmentWarningPeriod_JP">ImpairmentWarningPeriod_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentWarningPeriod_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventJournalNameId name="InventJournalNameId">InventJournalNameId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAssemblingEnabled_JP name="IsAssemblingEnabled_JP">IsAssemblingEnabled_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory assemble and disassemble</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAssemblingEnabled_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory assemble and disassemble</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsAutomaticPosting name="IsAutomaticPosting">IsAutomaticPosting</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatically create depreciation adjustment amounts with disposal</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomaticPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatically create depreciation adjustment amounts with disposal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsDisposalSameYear name="IsDisposalSameYear">IsDisposalSameYear</a>

First included in: Parameter/AssetParameters (this entity)  

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

### <a href=#IsProratedDepreciation name="IsProratedDepreciation">IsProratedDepreciation</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculate prorated depreciation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProratedDepreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculate prorated depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account for revenue recognition of untransferred reserves</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account for revenue recognition of untransferred reserves</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LowCostAssetThreshold_W name="LowCostAssetThreshold_W">LowCostAssetThreshold_W</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Low-cost asset threshold</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowCostAssetThreshold_W attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Low-cost asset threshold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ManuallyChangeDepProfileEnable_JP name="ManuallyChangeDepProfileEnable_JP">ManuallyChangeDepProfileEnable_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManuallyChangeDepProfileEnable_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MaxAcquisitionValue_IN name="MaxAcquisitionValue_IN">MaxAcquisitionValue_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxAcquisitionValue_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MinNonSeasonalWorkingDays_IN name="MinNonSeasonalWorkingDays_IN">MinNonSeasonalWorkingDays_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Min. working days for non-seasonal industries</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinNonSeasonalWorkingDays_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Min. working days for non-seasonal industries</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MinSeasonalWorkingDays_IN name="MinSeasonalWorkingDays_IN">MinSeasonalWorkingDays_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Min. working days for seasonal industries</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinSeasonalWorkingDays_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Min. working days for seasonal industries</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MultiAcquisition name="MultiAcquisition">MultiAcquisition</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiAcquisition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: Parameter/AssetParameters (this entity)  

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

### <a href=#Revaluation name="Revaluation">Revaluation</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revaluation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Revaluation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Revaluation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ThresholdPercentage_IN name="ThresholdPercentage_IN">ThresholdPercentage_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdPercentage_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UseCatchUpMethod_JP name="UseCatchUpMethod_JP">UseCatchUpMethod_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCatchUpMethod_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseSpecialDepreciatonBalance_IN name="UseSpecialDepreciatonBalance_IN">UseSpecialDepreciatonBalance_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use special depreciation balance</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSpecialDepreciatonBalance_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use special depreciation balance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#WriteDownAdj name="WriteDownAdj">WriteDownAdj</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Write down adjustment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteDownAdj attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Write down adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#WriteUpAdj name="WriteUpAdj">WriteUpAdj</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Write up adjustment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteUpAdj attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Write up adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationCatchUpInterval_JP name="DepreciationCatchUpInterval_JP">DepreciationCatchUpInterval_JP</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationCatchUpInterval_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetSaleBasis_IN name="AssetSaleBasis_IN">AssetSaleBasis_IN</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetSaleBasis_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AnalysisDimensionAttribute_RU name="AnalysisDimensionAttribute_RU">AnalysisDimensionAttribute_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Analysis code</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnalysisDimensionAttribute_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Analysis code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssessedRoll_RU name="AssessedRoll_RU">AssessedRoll_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessedRoll_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssessedTaxInitDate_RU name="AssessedTaxInitDate_RU">AssessedTaxInitDate_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessedTaxInitDate_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CompanyIssue_RU name="CompanyIssue_RU">CompanyIssue_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transference</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyIssue_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CompanyReceipt_RU name="CompanyReceipt_RU">CompanyReceipt_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receipt</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyReceipt_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receipt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Disposal_RU name="Disposal_RU">Disposal_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Writing-off</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Disposal_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Writing-off</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Lending_RU name="Lending_RU">Lending_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lease</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Lending_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lease</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LendingReturn_RU name="LendingReturn_RU">LendingReturn_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return from lease</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LendingReturn_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return from lease</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Other_RU name="Other_RU">Other_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Others</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Other_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Others</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PartialTakeDown_RU name="PartialTakeDown_RU">PartialTakeDown_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partial dismantlement</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartialTakeDown_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Partial dismantlement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CurrencyWriteDownAdj_RU name="CurrencyWriteDownAdj_RU">CurrencyWriteDownAdj_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency depreciation revaluation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyWriteDownAdj_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency depreciation revaluation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CurrencyWriteUpAdj_RU name="CurrencyWriteUpAdj_RU">CurrencyWriteUpAdj_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency cost revaluation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyWriteUpAdj_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency cost revaluation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MajorRepairs_RU name="MajorRepairs_RU">MajorRepairs_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Major repairs</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MajorRepairs_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Major repairs</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LandTaxCode_RU name="LandTaxCode_RU">LandTaxCode_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandTaxCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LandTaxRoll_RU name="LandTaxRoll_RU">LandTaxRoll_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandTaxRoll_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LowCostAssetInventProfileId_RU name="LowCostAssetInventProfileId_RU">LowCostAssetInventProfileId_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>NVFA inventory profile</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowCostAssetInventProfileId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>NVFA inventory profile</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBookIdDefault_RU name="TaxBookIdDefault_RU">TaxBookIdDefault_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax book</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBookIdDefault_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax book</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCode_RU name="TaxCode_RU">TaxCode_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportTaxCode_RU name="TransportTaxCode_RU">TransportTaxCode_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportTaxCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportTaxRoll_RU name="TransportTaxRoll_RU">TransportTaxRoll_RU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportTaxRoll_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LowCostAssetThreshold_HU name="LowCostAssetThreshold_HU">LowCostAssetThreshold_HU</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Low-cost asset threshold</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowCostAssetThreshold_HU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Low-cost asset threshold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationMinReportingCurrency name="DepreciationMinReportingCurrency">DepreciationMinReportingCurrency</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationMinReportingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportingCurrencyAmountUpdatesComplete name="ReportingCurrencyAmountUpdatesComplete">ReportingCurrencyAmountUpdatesComplete</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyAmountUpdatesComplete attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultMaintenanceFunctionalLocation name="DefaultMaintenanceFunctionalLocation">DefaultMaintenanceFunctionalLocation</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Functional location</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultMaintenanceFunctionalLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Functional location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/AssetParameters (this entity)  

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

### <a href=#Relationship_AssetBookTableRelationshipId name="Relationship_AssetBookTableRelationshipId">Relationship_AssetBookTableRelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/AssetBookTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json/AssetBookTable</a></td><td><a href="../Main/AssetBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetDefaultSaleDimensionRelationshipId name="Relationship_AssetDefaultSaleDimensionRelationshipId">Relationship_AssetDefaultSaleDimensionRelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDefaultSaleDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetLedgerRelationshipId name="Relationship_AssetLedgerRelationshipId">Relationship_AssetLedgerRelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetLedger.cdm.json/AssetLedger</a></td><td><a href="AssetLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalNameRelationshipId name="Relationship_InventJournalNameRelationshipId">Relationship_InventJournalNameRelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UserGroupInfoRelationshipId name="Relationship_UserGroupInfoRelationshipId">Relationship_UserGroupInfoRelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UserGroupInfoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/UserGroupInfo.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/UserGroupInfo.cdm.json/UserGroupInfo</a></td><td><a href="../../../System/SystemAdministration/Main/UserGroupInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AnalysisDimensionAttribute_RURelationshipId name="Relationship_AnalysisDimensionAttribute_RURelationshipId">Relationship_AnalysisDimensionAttribute_RURelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AnalysisDimensionAttribute_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Reference/DimensionAttribute.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Reference/DimensionAttribute.cdm.json/DimensionAttribute</a></td><td><a href="../../FinancialDimensions/Reference/DimensionAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LandTaxCode_RURelationshipId name="Relationship_LandTaxCode_RURelationshipId">Relationship_LandTaxCode_RURelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LandTaxCode_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventProfile_RURelationshipId name="Relationship_InventProfile_RURelationshipId">Relationship_InventProfile_RURelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventProfile_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventProfile_RU.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventProfile_RU.cdm.json/InventProfile_RU</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventProfile_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssessedTaxCode_RURelationshipId name="Relationship_AssessedTaxCode_RURelationshipId">Relationship_AssessedTaxCode_RURelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssessedTaxCode_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetBookTableTax_RURelationshipId name="Relationship_AssetBookTableTax_RURelationshipId">Relationship_AssetBookTableTax_RURelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookTableTax_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/AssetBookTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json/AssetBookTable</a></td><td><a href="../Main/AssetBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportTaxCode_RURelationshipId name="Relationship_TransportTaxCode_RURelationshipId">Relationship_TransportTaxCode_RURelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportTaxCode_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/AssetParameters (this entity)  

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
