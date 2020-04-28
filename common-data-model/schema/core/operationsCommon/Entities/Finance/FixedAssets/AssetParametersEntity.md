---
title: AssetParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Fixed asset parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed asset parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountForUntransferredReserves](#AccountForUntransferredReserves)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AccountForUntransferredReservesDisplayValue](#AccountForUntransferredReservesDisplayValue)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[Acquisition](#Acquisition)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AcquisitionAdjustment](#AcquisitionAdjustment)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AllowAcquisitionFromPurchasing](#AllowAcquisitionFromPurchasing)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AllowMultipleAcquisitions](#AllowMultipleAcquisitions)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AutoNumberAssets](#AutoNumberAssets)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[BarCodeEqualsFixedAssetNumber](#BarCodeEqualsFixedAssetNumber)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[CalculateProratedDepreciation](#CalculateProratedDepreciation)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[CapitalizationThreshold](#CapitalizationThreshold)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[CheckForAssetCreationDuringLineEntry](#CheckForAssetCreationDuringLineEntry)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[ConsiderCapitalizationThreshold](#ConsiderCapitalizationThreshold)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[CreateAssetDuringReceiptOrInvoicePosting](#CreateAssetDuringReceiptOrInvoicePosting)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DeductCashDiscount](#DeductCashDiscount)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DefaultValueModelId](#DefaultValueModelId)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[Depreciation](#Depreciation)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DepreciationAdjustment](#DepreciationAdjustment)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[CreateDepreciationAdjustmentsWithDisposal](#CreateDepreciationAdjustmentsWithDisposal)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DerogatoryDecrease](#DerogatoryDecrease)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DerogatoryIncrease](#DerogatoryIncrease)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DisposalSale](#DisposalSale)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DisposalScrap](#DisposalScrap)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[ExtraOrdinaryDepreciation](#ExtraOrdinaryDepreciation)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[InventoryJournalId](#InventoryJournalId)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[Key](#Key)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[MinimumDepreciationAmount](#MinimumDepreciationAmount)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[PostingProfileId](#PostingProfileId)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[ProvisionForReserve](#ProvisionForReserve)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[RequireReasonsForAssetChanges](#RequireReasonsForAssetChanges)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[RestrictAssetAcquisitionPostingToUserGroupId](#RestrictAssetAcquisitionPostingToUserGroupId)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[Revaluation](#Revaluation)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[TransferFromReserve](#TransferFromReserve)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[WriteDownAdjustment](#WriteDownAdjustment)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[WriteUpAdjustment](#WriteUpAdjustment)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AccountingStandard](#AccountingStandard)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AcceleratedDepreciationCalculationMethod](#AcceleratedDepreciationCalculationMethod)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AcceleratedDepreciationRateFactor](#AcceleratedDepreciationRateFactor)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AcceleratedDepreciationRateThreshold](#AcceleratedDepreciationRateThreshold)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AllowLocationTransfer](#AllowLocationTransfer)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AllowTheDepreciationMethodToBeManuallyChanged](#AllowTheDepreciationMethodToBeManuallyChanged)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AssemblingReservationType](#AssemblingReservationType)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[CheckMaximumPercentageForReducingBalance](#CheckMaximumPercentageForReducingBalance)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DepreciationCatchUpInterval](#DepreciationCatchUpInterval)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[ImpairmentWarningPeriod](#ImpairmentWarningPeriod)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[InventoryAssembleAndDisassemble](#InventoryAssembleAndDisassemble)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[UseCatchUpMethod](#UseCatchUpMethod)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[ICMSCreditInstallments](#ICMSCreditInstallments)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[UseSpecialDepreciationBalance](#UseSpecialDepreciationBalance)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[DepreciationThresholdPercentage](#DepreciationThresholdPercentage)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[MaxAcquisitionValueToAvailFullDepreciation](#MaxAcquisitionValueToAvailFullDepreciation)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[MinWorkingDaysForNonSeasonalIndustries](#MinWorkingDaysForNonSeasonalIndustries)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[MinWorkingDaysForSeasonalIndustries](#MinWorkingDaysForSeasonalIndustries)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[IsCompaniesActDepreciation](#IsCompaniesActDepreciation)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[IsIncomeTaxActDepreciation](#IsIncomeTaxActDepreciation)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AssetGroupDepreciationThreshold](#AssetGroupDepreciationThreshold)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AssetSaleBasis](#AssetSaleBasis)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[AreDepreciationMethodsEnabled](#AreDepreciationMethodsEnabled)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[IsDepreciationPolicyEnabled](#IsDepreciationPolicyEnabled)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[MinimumDepreciationAmountReportingCurrency](#MinimumDepreciationAmountReportingCurrency)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[Relationship_AccountForRevenueRecognitionOfUntransferredReservesCombinationRelationshipId](#Relationship_AccountForRevenueRecognitionOfUntransferredReservesCombinationRelationshipId)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[Relationship_AssetPostingProfileEntityRelationshipId](#Relationship_AssetPostingProfileEntityRelationshipId)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[BackingTable_AssetParametersRelationshipId](#BackingTable_AssetParametersRelationshipId)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetParametersEntity.md" target="_blank">FixedAssets/AssetParametersEntity</a>|

### <a href=#AccountForUntransferredReserves name="AccountForUntransferredReserves">AccountForUntransferredReserves</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountForUntransferredReserves attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountForUntransferredReservesDisplayValue name="AccountForUntransferredReservesDisplayValue">AccountForUntransferredReservesDisplayValue</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account for revenue recognition of untransferred reseves</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountForUntransferredReservesDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account for revenue recognition of untransferred reseves</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Acquisition name="Acquisition">Acquisition</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Acquisition</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Acquisition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Acquisition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionAdjustment name="AcquisitionAdjustment">AcquisitionAdjustment</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Acquisition adjustment</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionAdjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Acquisition adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowAcquisitionFromPurchasing name="AllowAcquisitionFromPurchasing">AllowAcquisitionFromPurchasing</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowAcquisitionFromPurchasing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowMultipleAcquisitions name="AllowMultipleAcquisitions">AllowMultipleAcquisitions</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMultipleAcquisitions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoNumberAssets name="AutoNumberAssets">AutoNumberAssets</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoNumberAssets attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCodeEqualsFixedAssetNumber name="BarCodeEqualsFixedAssetNumber">BarCodeEqualsFixedAssetNumber</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCodeEqualsFixedAssetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculateProratedDepreciation name="CalculateProratedDepreciation">CalculateProratedDepreciation</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateProratedDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapitalizationThreshold name="CapitalizationThreshold">CapitalizationThreshold</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapitalizationThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckForAssetCreationDuringLineEntry name="CheckForAssetCreationDuringLineEntry">CheckForAssetCreationDuringLineEntry</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckForAssetCreationDuringLineEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsiderCapitalizationThreshold name="ConsiderCapitalizationThreshold">ConsiderCapitalizationThreshold</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsiderCapitalizationThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateAssetDuringReceiptOrInvoicePosting name="CreateAssetDuringReceiptOrInvoicePosting">CreateAssetDuringReceiptOrInvoicePosting</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateAssetDuringReceiptOrInvoicePosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductCashDiscount name="DeductCashDiscount">DeductCashDiscount</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductCashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultValueModelId name="DefaultValueModelId">DefaultValueModelId</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultValueModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Depreciation name="Depreciation">Depreciation</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Depreciation</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Depreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationAdjustment name="DepreciationAdjustment">DepreciationAdjustment</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Depreciation adjustment</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAdjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Depreciation adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateDepreciationAdjustmentsWithDisposal name="CreateDepreciationAdjustmentsWithDisposal">CreateDepreciationAdjustmentsWithDisposal</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateDepreciationAdjustmentsWithDisposal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerogatoryDecrease name="DerogatoryDecrease">DerogatoryDecrease</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Derogatory decrease</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryDecrease attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Derogatory decrease</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerogatoryIncrease name="DerogatoryIncrease">DerogatoryIncrease</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Derogatory increase</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryIncrease attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Derogatory increase</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisposalSale name="DisposalSale">DisposalSale</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Disposal sale</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Disposal sale</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisposalScrap name="DisposalScrap">DisposalScrap</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Disposal scrap</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalScrap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Disposal scrap</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtraOrdinaryDepreciation name="ExtraOrdinaryDepreciation">ExtraOrdinaryDepreciation</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Extraordinary depreciation</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtraOrdinaryDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Extraordinary depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryJournalId name="InventoryJournalId">InventoryJournalId</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryJournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumDepreciationAmount name="MinimumDepreciationAmount">MinimumDepreciationAmount</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumDepreciationAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileId name="PostingProfileId">PostingProfileId</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProvisionForReserve name="ProvisionForReserve">ProvisionForReserve</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Provision for reserve</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProvisionForReserve attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Provision for reserve</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireReasonsForAssetChanges name="RequireReasonsForAssetChanges">RequireReasonsForAssetChanges</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Require reasons for asset changes</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireReasonsForAssetChanges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Require reasons for asset changes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictAssetAcquisitionPostingToUserGroupId name="RestrictAssetAcquisitionPostingToUserGroupId">RestrictAssetAcquisitionPostingToUserGroupId</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictAssetAcquisitionPostingToUserGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Revaluation name="Revaluation">Revaluation</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Revaluation</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Revaluation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Revaluation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferFromReserve name="TransferFromReserve">TransferFromReserve</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Transfer from reserve</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferFromReserve attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Transfer from reserve</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteDownAdjustment name="WriteDownAdjustment">WriteDownAdjustment</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Write down adjustment</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteDownAdjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Write down adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteUpAdjustment name="WriteUpAdjustment">WriteUpAdjustment</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code - Write up adjustment</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteUpAdjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code - Write up adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingStandard name="AccountingStandard">AccountingStandard</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingStandard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepreciationCalculationMethod name="AcceleratedDepreciationCalculationMethod">AcceleratedDepreciationCalculationMethod</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepreciationCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepreciationRateFactor name="AcceleratedDepreciationRateFactor">AcceleratedDepreciationRateFactor</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepreciationRateFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepreciationRateThreshold name="AcceleratedDepreciationRateThreshold">AcceleratedDepreciationRateThreshold</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepreciationRateThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowLocationTransfer name="AllowLocationTransfer">AllowLocationTransfer</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowLocationTransfer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTheDepreciationMethodToBeManuallyChanged name="AllowTheDepreciationMethodToBeManuallyChanged">AllowTheDepreciationMethodToBeManuallyChanged</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTheDepreciationMethodToBeManuallyChanged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssemblingReservationType name="AssemblingReservationType">AssemblingReservationType</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssemblingReservationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckMaximumPercentageForReducingBalance name="CheckMaximumPercentageForReducingBalance">CheckMaximumPercentageForReducingBalance</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckMaximumPercentageForReducingBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationCatchUpInterval name="DepreciationCatchUpInterval">DepreciationCatchUpInterval</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationCatchUpInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImpairmentWarningPeriod name="ImpairmentWarningPeriod">ImpairmentWarningPeriod</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentWarningPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryAssembleAndDisassemble name="InventoryAssembleAndDisassemble">InventoryAssembleAndDisassemble</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAssembleAndDisassemble attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseCatchUpMethod name="UseCatchUpMethod">UseCatchUpMethod</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCatchUpMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ICMSCreditInstallments name="ICMSCreditInstallments">ICMSCreditInstallments</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSCreditInstallments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseSpecialDepreciationBalance name="UseSpecialDepreciationBalance">UseSpecialDepreciationBalance</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSpecialDepreciationBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationThresholdPercentage name="DepreciationThresholdPercentage">DepreciationThresholdPercentage</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationThresholdPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxAcquisitionValueToAvailFullDepreciation name="MaxAcquisitionValueToAvailFullDepreciation">MaxAcquisitionValueToAvailFullDepreciation</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxAcquisitionValueToAvailFullDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinWorkingDaysForNonSeasonalIndustries name="MinWorkingDaysForNonSeasonalIndustries">MinWorkingDaysForNonSeasonalIndustries</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinWorkingDaysForNonSeasonalIndustries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinWorkingDaysForSeasonalIndustries name="MinWorkingDaysForSeasonalIndustries">MinWorkingDaysForSeasonalIndustries</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinWorkingDaysForSeasonalIndustries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCompaniesActDepreciation name="IsCompaniesActDepreciation">IsCompaniesActDepreciation</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCompaniesActDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIncomeTaxActDepreciation name="IsIncomeTaxActDepreciation">IsIncomeTaxActDepreciation</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIncomeTaxActDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetGroupDepreciationThreshold name="AssetGroupDepreciationThreshold">AssetGroupDepreciationThreshold</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroupDepreciationThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetSaleBasis name="AssetSaleBasis">AssetSaleBasis</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetSaleBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreDepreciationMethodsEnabled name="AreDepreciationMethodsEnabled">AreDepreciationMethodsEnabled</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreDepreciationMethodsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDepreciationPolicyEnabled name="IsDepreciationPolicyEnabled">IsDepreciationPolicyEnabled</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDepreciationPolicyEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumDepreciationAmountReportingCurrency name="MinimumDepreciationAmountReportingCurrency">MinimumDepreciationAmountReportingCurrency</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumDepreciationAmountReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccountForRevenueRecognitionOfUntransferredReservesCombinationRelationshipId name="Relationship_AccountForRevenueRecognitionOfUntransferredReservesCombinationRelationshipId">Relationship_AccountForRevenueRecognitionOfUntransferredReservesCombinationRelationshipId</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountForRevenueRecognitionOfUntransferredReservesCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetPostingProfileEntityRelationshipId name="Relationship_AssetPostingProfileEntityRelationshipId">Relationship_AssetPostingProfileEntityRelationshipId</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetPostingProfileEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_AssetParametersRelationshipId name="BackingTable_AssetParametersRelationshipId">BackingTable_AssetParametersRelationshipId</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Parameter/AssetParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetParameters.cdm.json/AssetParameters</a></td><td><a href="../../../Tables/Finance/FixedAssets/Parameter/AssetParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetParametersEntity (this entity)  

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
