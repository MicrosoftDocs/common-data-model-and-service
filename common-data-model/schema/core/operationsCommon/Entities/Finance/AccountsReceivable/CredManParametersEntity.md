---
title: CredManParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# CredManParametersEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CredManParametersEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AllowBlankCreditLimitExpiryDate](#AllowBlankCreditLimitExpiryDate)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[AllowConfirmation](#AllowConfirmation)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[AllowEditSalesOrder](#AllowEditSalesOrder)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[AutoPost](#AutoPost)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[AvgBalOneMonth](#AvgBalOneMonth)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[AvgBalTwoMonths](#AvgBalTwoMonths)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[AvgCreditLimitPercentMonths](#AvgCreditLimitPercentMonths)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[AvgExposurePercentMonths](#AvgExposurePercentMonths)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[BlockingCalcBase](#BlockingCalcBase)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[CheckAtPickingList](#CheckAtPickingList)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[CheckCashDiscIncrease](#CheckCashDiscIncrease)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[CheckPaymTermIncrease](#CheckPaymTermIncrease)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[CODPaymTerm](#CODPaymTerm)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[CrossCompanyCreditCheck](#CrossCompanyCreditCheck)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[DaySalesOutstandingOne](#DaySalesOutstandingOne)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[DaySalesOutstandingTwo](#DaySalesOutstandingTwo)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[DeleteBlockedLoadLines](#DeleteBlockedLoadLines)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[ExcludeAccountLessThan](#ExcludeAccountLessThan)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[ExcludeCreditBalance](#ExcludeCreditBalance)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[ExcludeOverdueLessThan](#ExcludeOverdueLessThan)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[ExcludeSalesOrderLessThan](#ExcludeSalesOrderLessThan)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[PeriodFrom](#PeriodFrom)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[PeriodId](#PeriodId)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[PeriodTo](#PeriodTo)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[ReleaseReasonCancel](#ReleaseReasonCancel)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[ReleaseReasonOrderModified](#ReleaseReasonOrderModified)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[ReleaseReasonReady](#ReleaseReasonReady)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[SkipCreditCheck](#SkipCreditCheck)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[TargetAgeing](#TargetAgeing)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[TargetDateTransactionDueDate](#TargetDateTransactionDueDate)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[Key](#Key)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[MarginCategoryHierarchyName](#MarginCategoryHierarchyName)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[CreditLimitExchRateTypeName](#CreditLimitExchRateTypeName)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[CreditLimitAllowManualEditing](#CreditLimitAllowManualEditing)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[BackingTable_CredManParametersRelationshipId](#BackingTable_CredManParametersRelationshipId)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CredManParametersEntity.md" target="_blank">AccountsReceivable/CredManParametersEntity</a>|

### <a href=#AllowBlankCreditLimitExpiryDate name="AllowBlankCreditLimitExpiryDate">AllowBlankCreditLimitExpiryDate</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowBlankCreditLimitExpiryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowConfirmation name="AllowConfirmation">AllowConfirmation</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowConfirmation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowEditSalesOrder name="AllowEditSalesOrder">AllowEditSalesOrder</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowEditSalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoPost name="AutoPost">AutoPost</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoPost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvgBalOneMonth name="AvgBalOneMonth">AvgBalOneMonth</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvgBalOneMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvgBalTwoMonths name="AvgBalTwoMonths">AvgBalTwoMonths</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvgBalTwoMonths attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvgCreditLimitPercentMonths name="AvgCreditLimitPercentMonths">AvgCreditLimitPercentMonths</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvgCreditLimitPercentMonths attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvgExposurePercentMonths name="AvgExposurePercentMonths">AvgExposurePercentMonths</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvgExposurePercentMonths attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockingCalcBase name="BlockingCalcBase">BlockingCalcBase</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockingCalcBase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckAtPickingList name="CheckAtPickingList">CheckAtPickingList</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckAtPickingList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckCashDiscIncrease name="CheckCashDiscIncrease">CheckCashDiscIncrease</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckCashDiscIncrease attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckPaymTermIncrease name="CheckPaymTermIncrease">CheckPaymTermIncrease</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckPaymTermIncrease attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CODPaymTerm name="CODPaymTerm">CODPaymTerm</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CODPaymTerm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CrossCompanyCreditCheck name="CrossCompanyCreditCheck">CrossCompanyCreditCheck</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossCompanyCreditCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaySalesOutstandingOne name="DaySalesOutstandingOne">DaySalesOutstandingOne</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaySalesOutstandingOne attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaySalesOutstandingTwo name="DaySalesOutstandingTwo">DaySalesOutstandingTwo</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaySalesOutstandingTwo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeleteBlockedLoadLines name="DeleteBlockedLoadLines">DeleteBlockedLoadLines</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteBlockedLoadLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeAccountLessThan name="ExcludeAccountLessThan">ExcludeAccountLessThan</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeAccountLessThan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeCreditBalance name="ExcludeCreditBalance">ExcludeCreditBalance</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeCreditBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeOverdueLessThan name="ExcludeOverdueLessThan">ExcludeOverdueLessThan</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeOverdueLessThan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeSalesOrderLessThan name="ExcludeSalesOrderLessThan">ExcludeSalesOrderLessThan</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeSalesOrderLessThan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodFrom name="PeriodFrom">PeriodFrom</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodId name="PeriodId">PeriodId</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodTo name="PeriodTo">PeriodTo</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleaseReasonCancel name="ReleaseReasonCancel">ReleaseReasonCancel</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleaseReasonCancel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleaseReasonOrderModified name="ReleaseReasonOrderModified">ReleaseReasonOrderModified</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleaseReasonOrderModified attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleaseReasonReady name="ReleaseReasonReady">ReleaseReasonReady</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleaseReasonReady attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipCreditCheck name="SkipCreditCheck">SkipCreditCheck</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipCreditCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetAgeing name="TargetAgeing">TargetAgeing</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetAgeing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetDateTransactionDueDate name="TargetDateTransactionDueDate">TargetDateTransactionDueDate</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetDateTransactionDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

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

### <a href=#MarginCategoryHierarchyName name="MarginCategoryHierarchyName">MarginCategoryHierarchyName</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimitExchRateTypeName name="CreditLimitExchRateTypeName">CreditLimitExchRateTypeName</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitExchRateTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimitAllowManualEditing name="CreditLimitAllowManualEditing">CreditLimitAllowManualEditing</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitAllowManualEditing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CredManParametersRelationshipId name="BackingTable_CredManParametersRelationshipId">BackingTable_CredManParametersRelationshipId</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CredManParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Parameter/CredManParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Parameter/CredManParameters.cdm.json/CredManParameters</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Parameter/CredManParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CredManParametersEntity (this entity)  

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
