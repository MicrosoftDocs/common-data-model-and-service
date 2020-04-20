---
title: RetailTransactionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailTransactionEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Retail/RetailTransactionEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[BatchID](#BatchID)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[Terminal](#Terminal)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[AmountPostedToAccount](#AmountPostedToAccount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[ChannelReferenceId](#ChannelReferenceId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[CostAmount](#CostAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[CreatedOffline](#CreatedOffline)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[Currency](#Currency)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[CustomerDiscountAmount](#CustomerDiscountAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[DiscountAmountWithoutTax](#DiscountAmountWithoutTax)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[DeliveryMode](#DeliveryMode)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TransactionStatus](#TransactionStatus)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[GrossAmount](#GrossAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[IncomeExpenseAmount](#IncomeExpenseAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[InfocodeDiscountGroup](#InfocodeDiscountGroup)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[Warehouse](#Warehouse)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[SiteId](#SiteId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[InvoiceId](#InvoiceId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[ItemsPosted](#ItemsPosted)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LoyaltyCardId](#LoyaltyCardId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[NetAmount](#NetAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[NetPrice](#NetPrice)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[PaymentAmount](#PaymentAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[PostAsShipment](#PostAsShipment)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[RreceiptId](#RreceiptId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[RefundReceiptId](#RefundReceiptId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[SaleIsReturnSale](#SaleIsReturnSale)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[SalesInvoiceAmount](#SalesInvoiceAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[SalesOrderAmount](#SalesOrderAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[SalesOrderId](#SalesOrderId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[SalesPaymentDifference](#SalesPaymentDifference)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[Shift](#Shift)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[ShippingDateRequested](#ShippingDateRequested)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[Staff](#Staff)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[ToAccount](#ToAccount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TotalManualDiscountAmount](#TotalManualDiscountAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TotalManualDiscountPercentage](#TotalManualDiscountPercentage)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TransactionNumber](#TransactionNumber)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TransactionTime](#TransactionTime)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TransactionType](#TransactionType)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsPostalAddressLocation](#LogisticsPostalAddressLocation)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsLocationId](#LogisticsLocationId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsPostalAddress](#LogisticsPostalAddress)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsPostalCity](#LogisticsPostalCity)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsPostalCounty](#LogisticsPostalCounty)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsPostalState](#LogisticsPostalState)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsPostalStreet](#LogisticsPostalStreet)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsPostalZipCode](#LogisticsPostalZipCode)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticsPostalAddressValidFrom](#LogisticsPostalAddressValidFrom)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[LogisticPostalAddressValidTo](#LogisticPostalAddressValidTo)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[RetailChannelTableOMOperatingUnitID](#RetailChannelTableOMOperatingUnitID)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[Comment](#Comment)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TaxCalculationType](#TaxCalculationType)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[SuspendedTransactionId](#SuspendedTransactionId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[GiftCardActiveFrom](#GiftCardActiveFrom)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[GiftCardBalance](#GiftCardBalance)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[GiftCardExpireDate](#GiftCardExpireDate)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[GiftCardHistoryDetails](#GiftCardHistoryDetails)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[GiftCardIssueAmount](#GiftCardIssueAmount)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[GiftCardIdMasked](#GiftCardIdMasked)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[businessDate](#businessDate)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[IsTaxIncludedInPrice](#IsTaxIncludedInPrice)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[RetailTransactionAggregationFieldList](#RetailTransactionAggregationFieldList)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[TransactionOrderType](#TransactionOrderType)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[BeginDateTime](#BeginDateTime)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[NumberOfItemLines](#NumberOfItemLines)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[NumberOfItems](#NumberOfItems)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[NumberOfPaymentLines](#NumberOfPaymentLines)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[BackingTable_RetailTransactionTableRelationshipId](#BackingTable_RetailTransactionTableRelationshipId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionEntity.md" target="_blank">Retail/RetailTransactionEntity</a>|

### <a href=#BatchID name="BatchID">BatchID</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountPostedToAccount name="AmountPostedToAccount">AmountPostedToAccount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountPostedToAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#CostAmount name="CostAmount">CostAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreatedOffline name="CreatedOffline">CreatedOffline</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#Currency name="Currency">Currency</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#CustomerDiscountAmount name="CustomerDiscountAmount">CustomerDiscountAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#DiscountAmountWithoutTax name="DiscountAmountWithoutTax">DiscountAmountWithoutTax</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmountWithoutTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryMode name="DeliveryMode">DeliveryMode</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionStatus name="TransactionStatus">TransactionStatus</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#GrossAmount name="GrossAmount">GrossAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#InfocodeDiscountGroup name="InfocodeDiscountGroup">InfocodeDiscountGroup</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InfocodeDiscountGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Warehouse name="Warehouse">Warehouse</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemsPosted name="ItemsPosted">ItemsPosted</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemsPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyCardId name="LoyaltyCardId">LoyaltyCardId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyCardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#PaymentAmount name="PaymentAmount">PaymentAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#PostAsShipment name="PostAsShipment">PostAsShipment</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostAsShipment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RreceiptId name="RreceiptId">RreceiptId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RreceiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefundReceiptId name="RefundReceiptId">RefundReceiptId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefundReceiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SaleIsReturnSale name="SaleIsReturnSale">SaleIsReturnSale</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#SalesOrderAmount name="SalesOrderAmount">SalesOrderAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderId name="SalesOrderId">SalesOrderId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPaymentDifference name="SalesPaymentDifference">SalesPaymentDifference</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#Shift name="Shift">Shift</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Shift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingDateRequested name="ShippingDateRequested">ShippingDateRequested</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingDateRequested attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Staff name="Staff">Staff</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Staff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToAccount name="ToAccount">ToAccount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#TransactionNumber name="TransactionNumber">TransactionNumber</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#LogisticsPostalAddressLocation name="LogisticsPostalAddressLocation">LogisticsPostalAddressLocation</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddressLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsLocationId name="LogisticsLocationId">LogisticsLocationId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalAddress name="LogisticsPostalAddress">LogisticsPostalAddress</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalCity name="LogisticsPostalCity">LogisticsPostalCity</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalCounty name="LogisticsPostalCounty">LogisticsPostalCounty</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalState name="LogisticsPostalState">LogisticsPostalState</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalStreet name="LogisticsPostalStreet">LogisticsPostalStreet</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalZipCode name="LogisticsPostalZipCode">LogisticsPostalZipCode</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalAddressValidFrom name="LogisticsPostalAddressValidFrom">LogisticsPostalAddressValidFrom</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticPostalAddressValidTo name="LogisticPostalAddressValidTo">LogisticPostalAddressValidTo</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticPostalAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#RetailChannelTableOMOperatingUnitID name="RetailChannelTableOMOperatingUnitID">RetailChannelTableOMOperatingUnitID</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelTableOMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#TaxCalculationType name="TaxCalculationType">TaxCalculationType</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#SuspendedTransactionId name="SuspendedTransactionId">SuspendedTransactionId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#GiftCardBalance name="GiftCardBalance">GiftCardBalance</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#GiftCardExpireDate name="GiftCardExpireDate">GiftCardExpireDate</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#GiftCardHistoryDetails name="GiftCardHistoryDetails">GiftCardHistoryDetails</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#GiftCardIssueAmount name="GiftCardIssueAmount">GiftCardIssueAmount</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#GiftCardIdMasked name="GiftCardIdMasked">GiftCardIdMasked</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#businessDate name="businessDate">businessDate</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the businessDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTaxIncludedInPrice name="IsTaxIncludedInPrice">IsTaxIncludedInPrice</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#RetailTransactionAggregationFieldList name="RetailTransactionAggregationFieldList">RetailTransactionAggregationFieldList</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#BeginDateTime name="BeginDateTime">BeginDateTime</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BeginDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfItemLines name="NumberOfItemLines">NumberOfItemLines</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfItemLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfItems name="NumberOfItems">NumberOfItems</a>

First included in: Retail/RetailTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfPaymentLines name="NumberOfPaymentLines">NumberOfPaymentLines</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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

### <a href=#BackingTable_RetailTransactionTableRelationshipId name="BackingTable_RetailTransactionTableRelationshipId">BackingTable_RetailTransactionTableRelationshipId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Transaction/RetailTransactionTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailTransactionTable.cdm.json/RetailTransactionTable</a></td><td><a href="../../../Tables/Commerce/Retail/Transaction/RetailTransactionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailTransactionEntity (this entity)  

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
