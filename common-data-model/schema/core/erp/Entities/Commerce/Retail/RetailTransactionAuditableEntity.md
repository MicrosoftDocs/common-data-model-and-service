---
title: RetailTransactionAuditableEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailTransactionAuditableEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailTransactionAuditableEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[RegisterNumber](#RegisterNumber)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[ShiftID](#ShiftID)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[ShiftRegisterID](#ShiftRegisterID)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[BusinessDate](#BusinessDate)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[ChannelReferenceId](#ChannelReferenceId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Comment](#Comment)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[CreatedOffline](#CreatedOffline)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[CreatedAtRegister](#CreatedAtRegister)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Currency](#Currency)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[CustomerDiscount](#CustomerDiscount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[FinancialDimension](#FinancialDimension)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Description](#Description)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[DiscountAmountExcludingTax](#DiscountAmountExcludingTax)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[ModeOfDelivery](#ModeOfDelivery)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[EntryStatus](#EntryStatus)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[FiscalDocumentId](#FiscalDocumentId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[FiscalSerialId](#FiscalSerialId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[GrossAmount](#GrossAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[IncomeExpenseAmount](#IncomeExpenseAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Warehouse](#Warehouse)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Site](#Site)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[InvoiceComment](#InvoiceComment)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Invoice](#Invoice)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[LoyaltyCardNumber](#LoyaltyCardNumber)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[NetAmount](#NetAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[NetPrice](#NetPrice)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[NumberOfProductLines](#NumberOfProductLines)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[NumberOfProducts](#NumberOfProducts)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[NumberOfPaymentLines](#NumberOfPaymentLines)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[PaymentAmount](#PaymentAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[RequestedReceiptDate](#RequestedReceiptDate)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[ReceiptEmail](#ReceiptEmail)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[SaleIsReturnSale](#SaleIsReturnSale)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[SalesInvoiceAmount](#SalesInvoiceAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[SalesOrder](#SalesOrder)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[SalesPaymentDifference](#SalesPaymentDifference)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[RequestedShipDate](#RequestedShipDate)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[SkipAggregation](#SkipAggregation)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[OperatorID](#OperatorID)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[StatementCode](#StatementCode)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[StatementNumber](#StatementNumber)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TimeWhenTransactionClosed](#TimeWhenTransactionClosed)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TotalManualDiscountAmount](#TotalManualDiscountAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TotalManualDiscountPercentage](#TotalManualDiscountPercentage)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TransactionId](#TransactionId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TransCode](#TransCode)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TransactionTime](#TransactionTime)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TransactionType](#TransactionType)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[CustomerAccountAsync](#CustomerAccountAsync)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[SalesGroup](#SalesGroup)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TaxCalculationType](#TaxCalculationType)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[ValidationStatus](#ValidationStatus)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[LastValidationTime](#LastValidationTime)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[IsTaxIncludedInPrice](#IsTaxIncludedInPrice)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[SuspendedTransactionId](#SuspendedTransactionId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[GiftCardActiveFrom](#GiftCardActiveFrom)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[GiftCardExpireDate](#GiftCardExpireDate)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[GiftCardIssueAmount](#GiftCardIssueAmount)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[GiftCardBalance](#GiftCardBalance)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[GiftCardHistoryDetails](#GiftCardHistoryDetails)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[GiftCardIdMasked](#GiftCardIdMasked)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[RetailTransactionAggregationFieldList](#RetailTransactionAggregationFieldList)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[TransactionOrderType](#TransactionOrderType)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[OperatingUnitRecId](#OperatingUnitRecId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[FinancialDimensionDisplayValue](#FinancialDimensionDisplayValue)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[AsynchronousOrderStatus](#AsynchronousOrderStatus)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Relationship_FinancialDimensionDimensionSetRelationshipId](#Relationship_FinancialDimensionDimensionSetRelationshipId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[BackingTable_RetailTransactionTableRelationshipId](#BackingTable_RetailTransactionTableRelationshipId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionAuditableEntity.md" target="_blank">Retail/RetailTransactionAuditableEntity</a>|

### <a href=#RegisterNumber name="RegisterNumber">RegisterNumber</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegisterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShiftID name="ShiftID">ShiftID</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShiftRegisterID name="ShiftRegisterID">ShiftRegisterID</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftRegisterID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessDate name="BusinessDate">BusinessDate</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelReferenceId name="ChannelReferenceId">ChannelReferenceId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelReferenceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreatedOffline name="CreatedOffline">CreatedOffline</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatedOffline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreatedAtRegister name="CreatedAtRegister">CreatedAtRegister</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatedAtRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDiscount name="CustomerDiscount">CustomerDiscount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialDimension name="FinancialDimension">FinancialDimension</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

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

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmountExcludingTax name="DiscountAmountExcludingTax">DiscountAmountExcludingTax</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmountExcludingTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModeOfDelivery name="ModeOfDelivery">ModeOfDelivery</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModeOfDelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryStatus name="EntryStatus">EntryStatus</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentId name="FiscalDocumentId">FiscalDocumentId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalSerialId name="FiscalSerialId">FiscalSerialId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalSerialId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossAmount name="GrossAmount">GrossAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncomeExpenseAmount name="IncomeExpenseAmount">IncomeExpenseAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomeExpenseAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Warehouse name="Warehouse">Warehouse</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Warehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Site name="Site">Site</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Site attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceComment name="InvoiceComment">InvoiceComment</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

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

### <a href=#LoyaltyCardNumber name="LoyaltyCardNumber">LoyaltyCardNumber</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyCardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetPrice name="NetPrice">NetPrice</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfProductLines name="NumberOfProductLines">NumberOfProductLines</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfProductLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfProducts name="NumberOfProducts">NumberOfProducts</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfProducts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfPaymentLines name="NumberOfPaymentLines">NumberOfPaymentLines</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfPaymentLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentAmount name="PaymentAmount">PaymentAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedReceiptDate name="RequestedReceiptDate">RequestedReceiptDate</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptEmail name="ReceiptEmail">ReceiptEmail</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SaleIsReturnSale name="SaleIsReturnSale">SaleIsReturnSale</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaleIsReturnSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesInvoiceAmount name="SalesInvoiceAmount">SalesInvoiceAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrder name="SalesOrder">SalesOrder</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPaymentDifference name="SalesPaymentDifference">SalesPaymentDifference</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPaymentDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShipDate name="RequestedShipDate">RequestedShipDate</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShipDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipAggregation name="SkipAggregation">SkipAggregation</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipAggregation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatorID name="OperatorID">OperatorID</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatorID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementCode name="StatementCode">StatementCode</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementNumber name="StatementNumber">StatementNumber</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeWhenTransactionClosed name="TimeWhenTransactionClosed">TimeWhenTransactionClosed</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeWhenTransactionClosed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalManualDiscountAmount name="TotalManualDiscountAmount">TotalManualDiscountAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalManualDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalManualDiscountPercentage name="TotalManualDiscountPercentage">TotalManualDiscountPercentage</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalManualDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransCode name="TransCode">TransCode</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionTime name="TransactionTime">TransactionTime</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionType name="TransactionType">TransactionType</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountAsync name="CustomerAccountAsync">CustomerAccountAsync</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountAsync attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesGroup name="SalesGroup">SalesGroup</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCalculationType name="TaxCalculationType">TaxCalculationType</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCalculationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationStatus name="ValidationStatus">ValidationStatus</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastValidationTime name="LastValidationTime">LastValidationTime</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastValidationTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTaxIncludedInPrice name="IsTaxIncludedInPrice">IsTaxIncludedInPrice</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxIncludedInPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuspendedTransactionId name="SuspendedTransactionId">SuspendedTransactionId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuspendedTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardActiveFrom name="GiftCardActiveFrom">GiftCardActiveFrom</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardActiveFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardExpireDate name="GiftCardExpireDate">GiftCardExpireDate</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardExpireDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardIssueAmount name="GiftCardIssueAmount">GiftCardIssueAmount</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardIssueAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardBalance name="GiftCardBalance">GiftCardBalance</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardHistoryDetails name="GiftCardHistoryDetails">GiftCardHistoryDetails</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardHistoryDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardIdMasked name="GiftCardIdMasked">GiftCardIdMasked</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardIdMasked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTransactionAggregationFieldList name="RetailTransactionAggregationFieldList">RetailTransactionAggregationFieldList</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTransactionAggregationFieldList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionOrderType name="TransactionOrderType">TransactionOrderType</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitRecId name="OperatingUnitRecId">OperatingUnitRecId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialDimensionDisplayValue name="FinancialDimensionDisplayValue">FinancialDimensionDisplayValue</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AsynchronousOrderStatus name="AsynchronousOrderStatus">AsynchronousOrderStatus</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AsynchronousOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FinancialDimensionDimensionSetRelationshipId name="Relationship_FinancialDimensionDimensionSetRelationshipId">Relationship_FinancialDimensionDimensionSetRelationshipId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FinancialDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailTransactionTableRelationshipId name="BackingTable_RetailTransactionTableRelationshipId">BackingTable_RetailTransactionTableRelationshipId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Transaction/RetailTransactionTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Transaction/RetailTransactionTable.cdm.json/RetailTransactionTable</a></td><td><a href="../../../Tables/Commerce/Retail/Transaction/RetailTransactionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailTransactionAuditableEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
