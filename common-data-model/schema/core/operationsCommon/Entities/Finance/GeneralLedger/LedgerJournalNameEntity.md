---
title: LedgerJournalNameEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Journal names

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerJournalNameEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal names</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsApprovalActive](#IsApprovalActive)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[ApprovalUserGroup](#ApprovalUserGroup)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[PrivateForUserGroup](#PrivateForUserGroup)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[DefaultCashAccount](#DefaultCashAccount)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[WorkflowId](#WorkflowId)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Currency](#Currency)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[PostingLayer](#PostingLayer)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[PrincipleOfDateInitialization](#PrincipleOfDateInitialization)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[DefaultFinancialDimension](#DefaultFinancialDimension)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[DetailLevel](#DetailLevel)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[DocumentNumber](#DocumentNumber)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[EndBalanceControl](#EndBalanceControl)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[IsFixedExchangeRate](#IsFixedExchangeRate)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[IsFixedOffsetAccount](#IsFixedOffsetAccount)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[GeneratePaymentsBeforePosting](#GeneratePaymentsBeforePosting)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Name](#Name)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Type](#Type)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[FeesPosting](#FeesPosting)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[AmountsIncludeSalesTax](#AmountsIncludeSalesTax)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[PostingLineLimit](#PostingLineLimit)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[PostingDateControl](#PostingDateControl)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Description](#Description)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[NewVoucher](#NewVoucher)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[VoucherSeries](#VoucherSeries)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[OffsetAccountType](#OffsetAccountType)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[OffsetAccount](#OffsetAccount)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[AllowOnlyPositiveDebitsAndCredits](#AllowOnlyPositiveDebitsAndCredits)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[PrepaymentJournalVoucher](#PrepaymentJournalVoucher)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[HideSalesTaxFieldsInJournalEntryForms](#HideSalesTaxFieldsInJournalEntryForms)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[VoucherAllocationAtPosting](#VoucherAllocationAtPosting)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[IsWorkflowApprovalActive](#IsWorkflowApprovalActive)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[VoucherSeriesCode](#VoucherSeriesCode)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[VoucherSeriesCompanyId](#VoucherSeriesCompanyId)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[DefaultFinancialDimensionDisplayValue](#DefaultFinancialDimensionDisplayValue)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[OffsetAccountDisplayValue](#OffsetAccountDisplayValue)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[RequiresSimulationValidation_IT](#RequiresSimulationValidation_IT)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Relationship_DefaultDimensionSetRelationshipId](#Relationship_DefaultDimensionSetRelationshipId)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Relationship_OffsetAccountCombinationRelationshipId](#Relationship_OffsetAccountCombinationRelationshipId)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Relationship_NumberSequenceRelationshipId](#Relationship_NumberSequenceRelationshipId)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[BackingTable_LedgerJournalNameRelationshipId](#BackingTable_LedgerJournalNameRelationshipId)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerJournalNameEntity.md" target="_blank">GeneralLedger/LedgerJournalNameEntity</a>|

### <a href=#IsApprovalActive name="IsApprovalActive">IsApprovalActive</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsApprovalActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovalUserGroup name="ApprovalUserGroup">ApprovalUserGroup</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovalUserGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrivateForUserGroup name="PrivateForUserGroup">PrivateForUserGroup</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrivateForUserGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCashAccount name="DefaultCashAccount">DefaultCashAccount</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCashAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowId name="WorkflowId">WorkflowId</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingLayer name="PostingLayer">PostingLayer</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLayer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrincipleOfDateInitialization name="PrincipleOfDateInitialization">PrincipleOfDateInitialization</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrincipleOfDateInitialization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFinancialDimension name="DefaultFinancialDimension">DefaultFinancialDimension</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFinancialDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DetailLevel name="DetailLevel">DetailLevel</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DetailLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndBalanceControl name="EndBalanceControl">EndBalanceControl</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndBalanceControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFixedExchangeRate name="IsFixedExchangeRate">IsFixedExchangeRate</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFixedExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFixedOffsetAccount name="IsFixedOffsetAccount">IsFixedOffsetAccount</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFixedOffsetAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneratePaymentsBeforePosting name="GeneratePaymentsBeforePosting">GeneratePaymentsBeforePosting</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratePaymentsBeforePosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

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

### <a href=#Type name="Type">Type</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeesPosting name="FeesPosting">FeesPosting</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeesPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountsIncludeSalesTax name="AmountsIncludeSalesTax">AmountsIncludeSalesTax</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountsIncludeSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingLineLimit name="PostingLineLimit">PostingLineLimit</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLineLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDateControl name="PostingDateControl">PostingDateControl</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDateControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewVoucher name="NewVoucher">NewVoucher</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherSeries name="VoucherSeries">VoucherSeries</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountType name="OffsetAccountType">OffsetAccountType</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccount name="OffsetAccount">OffsetAccount</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowOnlyPositiveDebitsAndCredits name="AllowOnlyPositiveDebitsAndCredits">AllowOnlyPositiveDebitsAndCredits</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowOnlyPositiveDebitsAndCredits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaymentJournalVoucher name="PrepaymentJournalVoucher">PrepaymentJournalVoucher</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentJournalVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideSalesTaxFieldsInJournalEntryForms name="HideSalesTaxFieldsInJournalEntryForms">HideSalesTaxFieldsInJournalEntryForms</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideSalesTaxFieldsInJournalEntryForms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherAllocationAtPosting name="VoucherAllocationAtPosting">VoucherAllocationAtPosting</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherAllocationAtPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkflowApprovalActive name="IsWorkflowApprovalActive">IsWorkflowApprovalActive</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkflowApprovalActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherSeriesCode name="VoucherSeriesCode">VoucherSeriesCode</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherSeriesCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherSeriesCompanyId name="VoucherSeriesCompanyId">VoucherSeriesCompanyId</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherSeriesCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFinancialDimensionDisplayValue name="DefaultFinancialDimensionDisplayValue">DefaultFinancialDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFinancialDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountDisplayValue name="OffsetAccountDisplayValue">OffsetAccountDisplayValue</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiresSimulationValidation_IT name="RequiresSimulationValidation_IT">RequiresSimulationValidation_IT</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiresSimulationValidation_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionSetRelationshipId name="Relationship_DefaultDimensionSetRelationshipId">Relationship_DefaultDimensionSetRelationshipId</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OffsetAccountCombinationRelationshipId name="Relationship_OffsetAccountCombinationRelationshipId">Relationship_OffsetAccountCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_NumberSequenceRelationshipId name="Relationship_NumberSequenceRelationshipId">Relationship_NumberSequenceRelationshipId</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerJournalNameRelationshipId name="BackingTable_LedgerJournalNameRelationshipId">BackingTable_LedgerJournalNameRelationshipId</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerJournalNameEntity (this entity)  

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
