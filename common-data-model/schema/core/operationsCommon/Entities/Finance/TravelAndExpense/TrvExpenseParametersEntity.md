---
title: TrvExpenseParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# TrvExpenseParametersEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/TravelAndExpense/TrvExpenseParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllowEditDistributions](#AllowEditDistributions)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[BarCodeSetupId](#BarCodeSetupId)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[ConvertPBSExchToInternal](#ConvertPBSExchToInternal)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[DeductBreakf](#DeductBreakf)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[DeductDinner](#DeductDinner)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[DeductLunch](#DeductLunch)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[DisplayEntireExpenseOnDrillBack](#DisplayEntireExpenseOnDrillBack)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[EnableTaxRecovery](#EnableTaxRecovery)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[GlWorkSheet](#GlWorkSheet)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[HotelReductionDef](#HotelReductionDef)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[IncludeOverviewInCoverPage](#IncludeOverviewInCoverPage)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[IncludeUserIDInBarcode](#IncludeUserIDInBarcode)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[IsAllowApproveExpenseOnBudgetFail](#IsAllowApproveExpenseOnBudgetFail)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[IsAllowSubmitExpenseOnBudgetFail](#IsAllowSubmitExpenseOnBudgetFail)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[IsAllowSubmitRequisitionOnBudgetFail](#IsAllowSubmitRequisitionOnBudgetFail)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[IsAllowUpdateAccountingDate](#IsAllowUpdateAccountingDate)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[IsReleaseEncumbrancesOnCloseRequisition](#IsReleaseEncumbrancesOnCloseRequisition)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[IsTravelRequisitionMandatoryForExpense](#IsTravelRequisitionMandatoryForExpense)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[KeyId](#KeyId)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[KmPrice](#KmPrice)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[MealReductionDef](#MealReductionDef)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[MinHours](#MinHours)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[OtherReductionDef](#OtherReductionDef)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[PerDiemCalculation](#PerDiemCalculation)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[PerDiemRounding](#PerDiemRounding)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[PersonalPaidBy](#PersonalPaidBy)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[PostImmediately](#PostImmediately)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[TaxIncluded](#TaxIncluded)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[UseInterCompanyExpense](#UseInterCompanyExpense)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[ValidateTravelPurpose](#ValidateTravelPurpose)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[WhenToEvaluatePolicy](#WhenToEvaluatePolicy)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[AllowEditCreditCardExchRate](#AllowEditCreditCardExchRate)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[UseAntiCorruption](#UseAntiCorruption)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[MealReductionType](#MealReductionType)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[BackingTable_TrvParametersRelationshipId](#BackingTable_TrvParametersRelationshipId)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TrvExpenseParametersEntity.md" target="_blank">TravelAndExpense/TrvExpenseParametersEntity</a>|

### <a href=#AllowEditDistributions name="AllowEditDistributions">AllowEditDistributions</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowEditDistributions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCodeSetupId name="BarCodeSetupId">BarCodeSetupId</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConvertPBSExchToInternal name="ConvertPBSExchToInternal">ConvertPBSExchToInternal</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConvertPBSExchToInternal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductBreakf name="DeductBreakf">DeductBreakf</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductBreakf attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductDinner name="DeductDinner">DeductDinner</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductDinner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductLunch name="DeductLunch">DeductLunch</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductLunch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayEntireExpenseOnDrillBack name="DisplayEntireExpenseOnDrillBack">DisplayEntireExpenseOnDrillBack</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayEntireExpenseOnDrillBack attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableTaxRecovery name="EnableTaxRecovery">EnableTaxRecovery</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableTaxRecovery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GlWorkSheet name="GlWorkSheet">GlWorkSheet</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GlWorkSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HotelReductionDef name="HotelReductionDef">HotelReductionDef</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HotelReductionDef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeOverviewInCoverPage name="IncludeOverviewInCoverPage">IncludeOverviewInCoverPage</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeOverviewInCoverPage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeUserIDInBarcode name="IncludeUserIDInBarcode">IncludeUserIDInBarcode</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeUserIDInBarcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllowApproveExpenseOnBudgetFail name="IsAllowApproveExpenseOnBudgetFail">IsAllowApproveExpenseOnBudgetFail</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowApproveExpenseOnBudgetFail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllowSubmitExpenseOnBudgetFail name="IsAllowSubmitExpenseOnBudgetFail">IsAllowSubmitExpenseOnBudgetFail</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowSubmitExpenseOnBudgetFail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllowSubmitRequisitionOnBudgetFail name="IsAllowSubmitRequisitionOnBudgetFail">IsAllowSubmitRequisitionOnBudgetFail</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowSubmitRequisitionOnBudgetFail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllowUpdateAccountingDate name="IsAllowUpdateAccountingDate">IsAllowUpdateAccountingDate</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowUpdateAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReleaseEncumbrancesOnCloseRequisition name="IsReleaseEncumbrancesOnCloseRequisition">IsReleaseEncumbrancesOnCloseRequisition</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReleaseEncumbrancesOnCloseRequisition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTravelRequisitionMandatoryForExpense name="IsTravelRequisitionMandatoryForExpense">IsTravelRequisitionMandatoryForExpense</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTravelRequisitionMandatoryForExpense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyId name="KeyId">KeyId</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KmPrice name="KmPrice">KmPrice</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KmPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MealReductionDef name="MealReductionDef">MealReductionDef</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MealReductionDef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinHours name="MinHours">MinHours</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OtherReductionDef name="OtherReductionDef">OtherReductionDef</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherReductionDef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PerDiemCalculation name="PerDiemCalculation">PerDiemCalculation</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PerDiemCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PerDiemRounding name="PerDiemRounding">PerDiemRounding</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PerDiemRounding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonalPaidBy name="PersonalPaidBy">PersonalPaidBy</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonalPaidBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostImmediately name="PostImmediately">PostImmediately</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostImmediately attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIncluded name="TaxIncluded">TaxIncluded</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseInterCompanyExpense name="UseInterCompanyExpense">UseInterCompanyExpense</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseInterCompanyExpense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateTravelPurpose name="ValidateTravelPurpose">ValidateTravelPurpose</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateTravelPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WhenToEvaluatePolicy name="WhenToEvaluatePolicy">WhenToEvaluatePolicy</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WhenToEvaluatePolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowEditCreditCardExchRate name="AllowEditCreditCardExchRate">AllowEditCreditCardExchRate</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowEditCreditCardExchRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseAntiCorruption name="UseAntiCorruption">UseAntiCorruption</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseAntiCorruption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MealReductionType name="MealReductionType">MealReductionType</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MealReductionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TrvParametersRelationshipId name="BackingTable_TrvParametersRelationshipId">BackingTable_TrvParametersRelationshipId</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TrvParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Expense/Parameter/TrvParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Parameter/TrvParameters.cdm.json/TrvParameters</a></td><td><a href="../../../Tables/Finance/Expense/Parameter/TrvParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TravelAndExpense/TrvExpenseParametersEntity (this entity)  

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
