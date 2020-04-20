---
title: LedgerJournalLineCDSEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# LedgerJournalLineCDSEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerJournalLineCDSEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AccountType](#AccountType)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[CreditAmount](#CreditAmount)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[DebitAmount](#DebitAmount)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[JournalBatchNumber](#JournalBatchNumber)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Account](#Account)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[AccountDisplayValue](#AccountDisplayValue)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[LineNumber](#LineNumber)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[OffsetAccountType](#OffsetAccountType)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[OffsetAccount](#OffsetAccount)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[OffsetAccountDisplayValue](#OffsetAccountDisplayValue)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[OffsetText](#OffsetText)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Quantity](#Quantity)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[TransDate](#TransDate)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Text](#Text)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Voucher](#Voucher)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[DelayTaxCalculation](#DelayTaxCalculation)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Company](#Company)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[OffsetCompany](#OffsetCompany)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[DiscountPercentage](#DiscountPercentage)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[CashDiscountAmount](#CashDiscountAmount)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Invoice](#Invoice)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[DueDate](#DueDate)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[PaymentId](#PaymentId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[SalesTaxCode](#SalesTaxCode)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[ItemSalesTaxGroup](#ItemSalesTaxGroup)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[CashDiscount](#CashDiscount)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[CashDiscountDate](#CashDiscountDate)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Document](#Document)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[PaymentMethod](#PaymentMethod)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[PaymentReference](#PaymentReference)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[OffsetDefaultDimension](#OffsetDefaultDimension)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[OffsetDefaultDimensionDisplayValue](#OffsetDefaultDimensionDisplayValue)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[ReverseDate](#ReverseDate)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[ReverseEntry](#ReverseEntry)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[ExchRate](#ExchRate)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[ExchRateSecond](#ExchRateSecond)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[ReportingCurrencyExchRate](#ReportingCurrencyExchRate)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[ReportingCurrencyExchRateSecondary](#ReportingCurrencyExchRateSecondary)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[IntegrationComputedKey](#IntegrationComputedKey)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_LedgerJournalHeaderRelationshipId](#Relationship_LedgerJournalHeaderRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_LegalEntityRelationshipId](#Relationship_LegalEntityRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_OffsetLedgerDimensionRelationshipId](#Relationship_OffsetLedgerDimensionRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_CompanyLegalEntityRelationshipId](#Relationship_CompanyLegalEntityRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_OffsetCompanyLegalEntityRelationshipId](#Relationship_OffsetCompanyLegalEntityRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_OffsetDefaultDimensionRelationshipId](#Relationship_OffsetDefaultDimensionRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_SalesTaxGroupRelationshipId](#Relationship_SalesTaxGroupRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_ItemSalesTaxGroupRelationshipId](#Relationship_ItemSalesTaxGroupRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[BackingTable_LedgerJournalTransRelationshipId](#BackingTable_LedgerJournalTransRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerJournalLineCDSEntity.md" target="_blank">GeneralLedger/LedgerJournalLineCDSEntity</a>|

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditAmount name="CreditAmount">CreditAmount</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitAmount name="DebitAmount">DebitAmount</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalBatchNumber name="JournalBatchNumber">JournalBatchNumber</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Account name="Account">Account</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Account attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountDisplayValue name="AccountDisplayValue">AccountDisplayValue</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountType name="OffsetAccountType">OffsetAccountType</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccount name="OffsetAccount">OffsetAccount</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountDisplayValue name="OffsetAccountDisplayValue">OffsetAccountDisplayValue</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetText name="OffsetText">OffsetText</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Text name="Text">Text</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Text attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DelayTaxCalculation name="DelayTaxCalculation">DelayTaxCalculation</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DelayTaxCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetCompany name="OffsetCompany">OffsetCompany</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage name="DiscountPercentage">DiscountPercentage</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountAmount name="CashDiscountAmount">CashDiscountAmount</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentId name="PaymentId">PaymentId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxCode name="SalesTaxCode">SalesTaxCode</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroup name="ItemSalesTaxGroup">ItemSalesTaxGroup</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscount name="CashDiscount">CashDiscount</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountDate name="CashDiscountDate">CashDiscountDate</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Document name="Document">Document</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Document attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMethod name="PaymentMethod">PaymentMethod</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentReference name="PaymentReference">PaymentReference</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetDefaultDimension name="OffsetDefaultDimension">OffsetDefaultDimension</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetDefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetDefaultDimensionDisplayValue name="OffsetDefaultDimensionDisplayValue">OffsetDefaultDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetDefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReverseDate name="ReverseDate">ReverseDate</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReverseEntry name="ReverseEntry">ReverseEntry</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRateSecond name="ExchRateSecond">ExchRateSecond</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateSecond attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyExchRate name="ReportingCurrencyExchRate">ReportingCurrencyExchRate</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyExchRateSecondary name="ReportingCurrencyExchRateSecondary">ReportingCurrencyExchRateSecondary</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchRateSecondary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntegrationComputedKey name="IntegrationComputedKey">IntegrationComputedKey</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntegrationComputedKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalHeaderRelationshipId name="Relationship_LedgerJournalHeaderRelationshipId">Relationship_LedgerJournalHeaderRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LegalEntityRelationshipId name="Relationship_LegalEntityRelationshipId">Relationship_LegalEntityRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LegalEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetLedgerDimensionRelationshipId name="Relationship_OffsetLedgerDimensionRelationshipId">Relationship_OffsetLedgerDimensionRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionRelationshipId attribute are listed below.</summary>

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

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

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

### <a href=#Relationship_CompanyLegalEntityRelationshipId name="Relationship_CompanyLegalEntityRelationshipId">Relationship_CompanyLegalEntityRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyLegalEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OffsetCompanyLegalEntityRelationshipId name="Relationship_OffsetCompanyLegalEntityRelationshipId">Relationship_OffsetCompanyLegalEntityRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetCompanyLegalEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetDefaultDimensionRelationshipId name="Relationship_OffsetDefaultDimensionRelationshipId">Relationship_OffsetDefaultDimensionRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetDefaultDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesTaxGroupRelationshipId name="Relationship_SalesTaxGroupRelationshipId">Relationship_SalesTaxGroupRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTaxGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ItemSalesTaxGroupRelationshipId name="Relationship_ItemSalesTaxGroupRelationshipId">Relationship_ItemSalesTaxGroupRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemSalesTaxGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerJournalTransRelationshipId name="BackingTable_LedgerJournalTransRelationshipId">BackingTable_LedgerJournalTransRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerJournalLineCDSEntity (this entity)  

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
