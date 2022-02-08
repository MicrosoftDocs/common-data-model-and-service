---
title: SlipJournalEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Slip journal in GeneralLedger(SlipJournalEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/SlipJournalEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Slip journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ApprovedBy](#ApprovedBy)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Currency](#Currency)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[PostingLayer](#PostingLayer)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[DetailLevel](#DetailLevel)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Document](#Document)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[SecondaryExchangeRate](#SecondaryExchangeRate)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[FixedRate](#FixedRate)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[PrivateForUserGroup](#PrivateForUserGroup)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[InUseBy](#InUseBy)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[JournalName](#JournalName)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[JournalBatchNumber](#JournalBatchNumber)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[JournalType](#JournalType)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[AmountsIncludeSalesTax](#AmountsIncludeSalesTax)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[LinesLimit](#LinesLimit)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Log](#Log)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Description](#Description)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[AccountType](#AccountType)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[OffsetLedgerDimension](#OffsetLedgerDimension)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[InterCompanyAccounting](#InterCompanyAccounting)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[OriginalJournalNum](#OriginalJournalNum)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Posted](#Posted)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[PostedOn](#PostedOn)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[RejectedBy](#RejectedBy)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[ReportedAsReadyBy](#ReportedAsReadyBy)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[LockedBySystem](#LockedBySystem)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[LegalEntityForIntercompanyTaxPosting](#LegalEntityForIntercompanyTaxPosting)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[NumberAllocatedAtPosting](#NumberAllocatedAtPosting)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[WorkflowApprovalStatus](#WorkflowApprovalStatus)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Approver_FK_PersonnelNumber](#Approver_FK_PersonnelNumber)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[OffsetLedgerDimensionDisplayValue](#OffsetLedgerDimensionDisplayValue)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[DelayTaxCalculation](#DelayTaxCalculation)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[LineNumber](#LineNumber)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CreditAmount](#CreditAmount)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[DebitAmount](#DebitAmount)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[TransAccountType](#TransAccountType)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[OffsetAccountType](#OffsetAccountType)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Qty](#Qty)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[TransDate](#TransDate)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Text](#Text)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Voucher](#Voucher)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashCollBagNum_RU](#CashCollBagNum_RU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashCollBankContributor_RU](#CashCollBankContributor_RU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashCollCreditAccountNum_RU](#CashCollCreditAccountNum_RU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashCollDebitAccountNum_RU](#CashCollDebitAccountNum_RU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashCollStoreId_RU](#CashCollStoreId_RU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashDocId](#CashDocId)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashReceiptNumLV](#CashReceiptNumLV)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashSourceCode_RU](#CashSourceCode_RU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[CashSourceDescription_RU](#CashSourceDescription_RU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[DocType](#DocType)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[ExcludeExchAdj_PL](#ExcludeExchAdj_PL)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[LvCashReceiptTable](#LvCashReceiptTable)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[ManualRounding_HU](#ManualRounding_HU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[RoundOffCashAmount_HU](#RoundOffCashAmount_HU)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[TransRegDate_PL](#TransRegDate_PL)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[RCashTransStatus](#RCashTransStatus)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[ReportingCurrencyExchRate](#ReportingCurrencyExchRate)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[ReportingCurrencyExchRateSecondary](#ReportingCurrencyExchRateSecondary)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Relationship_OffsetLedgerDimensionCombinationRelationshipId](#Relationship_OffsetLedgerDimensionCombinationRelationshipId)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[BackingTable_LedgerJournalTableRelationshipId](#BackingTable_LedgerJournalTableRelationshipId)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SlipJournalEntity.md" target="_blank">GeneralLedger/SlipJournalEntity</a>|

### <a href=#ApprovedBy name="ApprovedBy">ApprovedBy</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

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

First included in: GeneralLedger/SlipJournalEntity (this entity)  

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

### <a href=#DetailLevel name="DetailLevel">DetailLevel</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

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

### <a href=#Document name="Document">Document</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Document attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryExchangeRate name="SecondaryExchangeRate">SecondaryExchangeRate</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedRate name="FixedRate">FixedRate</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrivateForUserGroup name="PrivateForUserGroup">PrivateForUserGroup</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

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

### <a href=#InUseBy name="InUseBy">InUseBy</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InUseBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalName name="JournalName">JournalName</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalBatchNumber name="JournalBatchNumber">JournalBatchNumber</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalType name="JournalType">JournalType</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountsIncludeSalesTax name="AmountsIncludeSalesTax">AmountsIncludeSalesTax</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

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

### <a href=#LinesLimit name="LinesLimit">LinesLimit</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinesLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Log name="Log">Log</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Log attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

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

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetLedgerDimension name="OffsetLedgerDimension">OffsetLedgerDimension</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterCompanyAccounting name="InterCompanyAccounting">InterCompanyAccounting</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterCompanyAccounting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalJournalNum name="OriginalJournalNum">OriginalJournalNum</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalJournalNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedOn name="PostedOn">PostedOn</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedOn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RejectedBy name="RejectedBy">RejectedBy</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RejectedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedAsReadyBy name="ReportedAsReadyBy">ReportedAsReadyBy</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedAsReadyBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LockedBySystem name="LockedBySystem">LockedBySystem</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LockedBySystem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityForIntercompanyTaxPosting name="LegalEntityForIntercompanyTaxPosting">LegalEntityForIntercompanyTaxPosting</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityForIntercompanyTaxPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberAllocatedAtPosting name="NumberAllocatedAtPosting">NumberAllocatedAtPosting</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberAllocatedAtPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowApprovalStatus name="WorkflowApprovalStatus">WorkflowApprovalStatus</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowApprovalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Approver_FK_PersonnelNumber name="Approver_FK_PersonnelNumber">Approver_FK_PersonnelNumber</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Approver_FK_PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetLedgerDimensionDisplayValue name="OffsetLedgerDimensionDisplayValue">OffsetLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DelayTaxCalculation name="DelayTaxCalculation">DelayTaxCalculation</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DelayTaxCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditAmount name="CreditAmount">CreditAmount</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitAmount name="DebitAmount">DebitAmount</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransAccountType name="TransAccountType">TransAccountType</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountType name="OffsetAccountType">OffsetAccountType</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

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

### <a href=#Qty name="Qty">Qty</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Text name="Text">Text</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Text attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollBagNum_RU name="CashCollBagNum_RU">CashCollBagNum_RU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollBagNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollBankContributor_RU name="CashCollBankContributor_RU">CashCollBankContributor_RU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollBankContributor_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollCreditAccountNum_RU name="CashCollCreditAccountNum_RU">CashCollCreditAccountNum_RU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollCreditAccountNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollDebitAccountNum_RU name="CashCollDebitAccountNum_RU">CashCollDebitAccountNum_RU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollDebitAccountNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollStoreId_RU name="CashCollStoreId_RU">CashCollStoreId_RU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollStoreId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDocId name="CashDocId">CashDocId</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDocId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashReceiptNumLV name="CashReceiptNumLV">CashReceiptNumLV</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashReceiptNumLV attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashSourceCode_RU name="CashSourceCode_RU">CashSourceCode_RU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashSourceCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashSourceDescription_RU name="CashSourceDescription_RU">CashSourceDescription_RU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashSourceDescription_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocType name="DocType">DocType</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeExchAdj_PL name="ExcludeExchAdj_PL">ExcludeExchAdj_PL</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeExchAdj_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LvCashReceiptTable name="LvCashReceiptTable">LvCashReceiptTable</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LvCashReceiptTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualRounding_HU name="ManualRounding_HU">ManualRounding_HU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualRounding_HU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundOffCashAmount_HU name="RoundOffCashAmount_HU">RoundOffCashAmount_HU</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffCashAmount_HU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransRegDate_PL name="TransRegDate_PL">TransRegDate_PL</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransRegDate_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RCashTransStatus name="RCashTransStatus">RCashTransStatus</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RCashTransStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyExchRate name="ReportingCurrencyExchRate">ReportingCurrencyExchRate</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyExchRateSecondary name="ReportingCurrencyExchRateSecondary">ReportingCurrencyExchRateSecondary</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchRateSecondary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetLedgerDimensionCombinationRelationshipId name="Relationship_OffsetLedgerDimensionCombinationRelationshipId">Relationship_OffsetLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerJournalTableRelationshipId name="BackingTable_LedgerJournalTableRelationshipId">BackingTable_LedgerJournalTableRelationshipId</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/WorksheetHeader/LedgerJournalTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetHeader/LedgerJournalTable.cdm.json/LedgerJournalTable</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/WorksheetHeader/LedgerJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/SlipJournalEntity (this entity)  

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
