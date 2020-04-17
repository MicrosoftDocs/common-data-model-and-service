---
title: RetailTransactionTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailTransactionTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Transaction/RetailTransactionTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTransactionTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[terminal](#terminal)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[amountToAccount](#amountToAccount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[BatchID](#BatchID)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[BatchTerminalId](#BatchTerminalId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[businessDate](#businessDate)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Channel](#Channel)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[ChannelReferenceId](#ChannelReferenceId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[comment](#comment)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[costAmount](#costAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[counter](#counter)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[CreatedOffline](#CreatedOffline)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[createdOnPosTerminal](#createdOnPosTerminal)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[currency](#currency)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[custAccount](#custAccount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[custDiscAmount](#custDiscAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[CustPurchaseOrder](#CustPurchaseOrder)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Description](#Description)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[discAmount](#discAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[discAmountWithoutTax](#discAmountWithoutTax)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[DlvMode](#DlvMode)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[entryStatus](#entryStatus)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[exchRate](#exchRate)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[FiscalDocumentId](#FiscalDocumentId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[FiscalSerialId](#FiscalSerialId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[grossAmount](#grossAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[includedInStatistics](#includedInStatistics)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[incomeExpenseAmount](#incomeExpenseAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[infocodeDiscGroup](#infocodeDiscGroup)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[InventLocationId](#InventLocationId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[InventSiteId](#InventSiteId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[InvoiceComment](#InvoiceComment)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[invoiceId](#invoiceId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[itemsPosted](#itemsPosted)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[LogisticsPostalAddress](#LogisticsPostalAddress)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[loyaltyCardId](#loyaltyCardId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[LoyaltyDiscAmount_RU](#LoyaltyDiscAmount_RU)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[netAmount](#netAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[netPrice](#netPrice)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[numberOfInvoices](#numberOfInvoices)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[numberOfItemLines](#numberOfItemLines)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[numberOfItems](#numberOfItems)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[numberOfPaymentLines](#numberOfPaymentLines)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[openDrawer](#openDrawer)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Origin](#Origin)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[paymentAmount](#paymentAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[postAsShipment](#postAsShipment)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[ReceiptDateRequested](#ReceiptDateRequested)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[receiptEmail](#receiptEmail)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[receiptEmailSent](#receiptEmailSent)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[receiptId](#receiptId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[refundReceiptId](#refundReceiptId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[replicated](#replicated)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[replicationCounterFromOrigin](#replicationCounterFromOrigin)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[retrievedFromReceiptId](#retrievedFromReceiptId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[roundedAmount](#roundedAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[saleIsReturnSale](#saleIsReturnSale)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[salesInvoiceAmount](#salesInvoiceAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[salesOrderAmount](#salesOrderAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[salesOrderId](#salesOrderId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[salesPaymentDifference](#salesPaymentDifference)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[sellToContactId](#sellToContactId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[shift](#shift)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[shiftDate](#shiftDate)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[ShippingDateRequested](#ShippingDateRequested)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[SkipAggregation](#SkipAggregation)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[staff](#staff)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[statementCode](#statementCode)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[statementId](#statementId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[store](#store)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[timeWhenTotalPressed](#timeWhenTotalPressed)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[timeWhenTransClosed](#timeWhenTransClosed)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[toAccount](#toAccount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[totalDiscAmount](#totalDiscAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[TotalManualDiscountAmount](#TotalManualDiscountAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[TotalManualDiscountPercentage](#TotalManualDiscountPercentage)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[transactionId](#transactionId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[transCode](#transCode)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[transDate](#transDate)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[transTableId](#transTableId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[transTime](#transTime)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[type](#type)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[wrongShift](#wrongShift)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[CustAccountAsync](#CustAccountAsync)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[SourceId](#SourceId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[PriceOverride](#PriceOverride)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[FTCExempt](#FTCExempt)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[CatalogUpSellShown](#CatalogUpSellShown)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[ContinuityOrder](#ContinuityOrder)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[ContinuityChild](#ContinuityChild)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[ContinuityLineEval](#ContinuityLineEval)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[InstallmentOrderSubmitted](#InstallmentOrderSubmitted)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[OutOfBalanceReleaseType](#OutOfBalanceReleaseType)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[PaymOutOfBalanceType](#PaymOutOfBalanceType)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[InstallmentBillingPrompt](#InstallmentBillingPrompt)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[AllocationPriority](#AllocationPriority)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[SalesGroup](#SalesGroup)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[TaxCalculationType](#TaxCalculationType)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[ValidationStatus](#ValidationStatus)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[ValidationDateTime](#ValidationDateTime)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[IsTaxIncludedInPrice](#IsTaxIncludedInPrice)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[SuspendedTransactionId](#SuspendedTransactionId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[GiftCardActiveFrom](#GiftCardActiveFrom)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[GiftCardExpireDate](#GiftCardExpireDate)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[GiftCardIssueAmount](#GiftCardIssueAmount)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[GiftCardBalance](#GiftCardBalance)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[GiftCardHistoryDetails](#GiftCardHistoryDetails)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[GiftCardIdMasked](#GiftCardIdMasked)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[InvoiceRecId](#InvoiceRecId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[RetailTransactionAggregationFieldList](#RetailTransactionAggregationFieldList)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[TransactionOrderType](#TransactionOrderType)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[BeginDateTime](#BeginDateTime)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[DefaultDimensionStamped](#DefaultDimensionStamped)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_DimensionAttributeValueSetRelationshipId](#Relationship_DimensionAttributeValueSetRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_LogisticsPostalAddressRelationshipId](#Relationship_LogisticsPostalAddressRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailChannelTableRelationshipId](#Relationship_RetailChannelTableRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailloyaltycardRelationshipId](#Relationship_RetailloyaltycardRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailPosBatchTableRelationshipId](#Relationship_RetailPosBatchTableRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailStatementTableRelationshipId](#Relationship_RetailStatementTableRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailStoreWorkShiftTableRelationshipId](#Relationship_RetailStoreWorkShiftTableRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailTerminalTable1RelationshipId](#Relationship_RetailTerminalTable1RelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailTerminalTableBatchRelationshipId](#Relationship_RetailTerminalTableBatchRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_CommissionSalesGroupRelationshipId](#Relationship_CommissionSalesGroupRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_CustInvoiceJourRelationshipId](#Relationship_CustInvoiceJourRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_RetailTransactionAggregationFieldListRelationshipId](#Relationship_RetailTransactionAggregationFieldListRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailTransactionTable.md" target="_blank">Transaction/RetailTransactionTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTransactionTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#terminal name="terminal">terminal</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#amountToAccount name="amountToAccount">amountToAccount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountToAccount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BatchID name="BatchID">BatchID</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchTerminalId name="BatchTerminalId">BatchTerminalId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchTerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#businessDate name="businessDate">businessDate</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the businessDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChannelReferenceId name="ChannelReferenceId">ChannelReferenceId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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

### <a href=#comment name="comment">comment</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#costAmount name="costAmount">costAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the costAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#counter name="counter">counter</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the counter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreatedOffline name="CreatedOffline">CreatedOffline</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatedOffline attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#createdOnPosTerminal name="createdOnPosTerminal">createdOnPosTerminal</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOnPosTerminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#currency name="currency">currency</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#custAccount name="custAccount">custAccount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the custAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#custDiscAmount name="custDiscAmount">custDiscAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the custDiscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CustPurchaseOrder name="CustPurchaseOrder">CustPurchaseOrder</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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

### <a href=#discAmount name="discAmount">discAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the discAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#discAmountWithoutTax name="discAmountWithoutTax">discAmountWithoutTax</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the discAmountWithoutTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DlvMode name="DlvMode">DlvMode</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#entryStatus name="entryStatus">entryStatus</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the entryStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#exchRate name="exchRate">exchRate</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the exchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FiscalDocumentId name="FiscalDocumentId">FiscalDocumentId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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

First included in: Transaction/RetailTransactionTable (this entity)  

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

### <a href=#grossAmount name="grossAmount">grossAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the grossAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#includedInStatistics name="includedInStatistics">includedInStatistics</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the includedInStatistics attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#incomeExpenseAmount name="incomeExpenseAmount">incomeExpenseAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the incomeExpenseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#infocodeDiscGroup name="infocodeDiscGroup">infocodeDiscGroup</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the infocodeDiscGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceComment name="InvoiceComment">InvoiceComment</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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

### <a href=#invoiceId name="invoiceId">invoiceId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the invoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#itemsPosted name="itemsPosted">itemsPosted</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the itemsPosted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LogisticsPostalAddress name="LogisticsPostalAddress">LogisticsPostalAddress</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#loyaltyCardId name="loyaltyCardId">loyaltyCardId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the loyaltyCardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyDiscAmount_RU name="LoyaltyDiscAmount_RU">LoyaltyDiscAmount_RU</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyDiscAmount_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#netAmount name="netAmount">netAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the netAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#netPrice name="netPrice">netPrice</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the netPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#numberOfInvoices name="numberOfInvoices">numberOfInvoices</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberOfInvoices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#numberOfItemLines name="numberOfItemLines">numberOfItemLines</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberOfItemLines attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#numberOfItems name="numberOfItems">numberOfItems</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberOfItems attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#numberOfPaymentLines name="numberOfPaymentLines">numberOfPaymentLines</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberOfPaymentLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#openDrawer name="openDrawer">openDrawer</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the openDrawer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Origin name="Origin">Origin</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Origin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#paymentAmount name="paymentAmount">paymentAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the paymentAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#postAsShipment name="postAsShipment">postAsShipment</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the postAsShipment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReceiptDateRequested name="ReceiptDateRequested">ReceiptDateRequested</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptDateRequested attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#receiptEmail name="receiptEmail">receiptEmail</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receiptEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#receiptEmailSent name="receiptEmailSent">receiptEmailSent</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receiptEmailSent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#receiptId name="receiptId">receiptId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#refundReceiptId name="refundReceiptId">refundReceiptId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the refundReceiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#replicated name="replicated">replicated</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#replicationCounterFromOrigin name="replicationCounterFromOrigin">replicationCounterFromOrigin</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#retrievedFromReceiptId name="retrievedFromReceiptId">retrievedFromReceiptId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the retrievedFromReceiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#roundedAmount name="roundedAmount">roundedAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the roundedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#saleIsReturnSale name="saleIsReturnSale">saleIsReturnSale</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saleIsReturnSale attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#salesInvoiceAmount name="salesInvoiceAmount">salesInvoiceAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#salesOrderAmount name="salesOrderAmount">salesOrderAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesOrderAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#salesOrderId name="salesOrderId">salesOrderId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesOrderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#salesPaymentDifference name="salesPaymentDifference">salesPaymentDifference</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesPaymentDifference attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#sellToContactId name="sellToContactId">sellToContactId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sellToContactId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#shift name="shift">shift</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#shiftDate name="shiftDate">shiftDate</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shiftDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ShippingDateRequested name="ShippingDateRequested">ShippingDateRequested</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingDateRequested attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SkipAggregation name="SkipAggregation">SkipAggregation</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipAggregation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#staff name="staff">staff</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the staff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statementCode name="statementCode">statementCode</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statementId name="statementId">statementId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#store name="store">store</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the store attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#timeWhenTotalPressed name="timeWhenTotalPressed">timeWhenTotalPressed</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeWhenTotalPressed attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#timeWhenTransClosed name="timeWhenTransClosed">timeWhenTransClosed</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeWhenTransClosed attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#toAccount name="toAccount">toAccount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the toAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#totalDiscAmount name="totalDiscAmount">totalDiscAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalDiscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalManualDiscountAmount name="TotalManualDiscountAmount">TotalManualDiscountAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalManualDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalManualDiscountPercentage name="TotalManualDiscountPercentage">TotalManualDiscountPercentage</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalManualDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#transactionId name="transactionId">transactionId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transCode name="transCode">transCode</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#transDate name="transDate">transDate</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#transTableId name="transTableId">transTableId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#transTime name="transTime">transTime</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#type name="type">type</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#wrongShift name="wrongShift">wrongShift</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wrongShift attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustAccountAsync name="CustAccountAsync">CustAccountAsync</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountAsync attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceId name="SourceId">SourceId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceOverride name="PriceOverride">PriceOverride</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FTCExempt name="FTCExempt">FTCExempt</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FTCExempt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CatalogUpSellShown name="CatalogUpSellShown">CatalogUpSellShown</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogUpSellShown attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContinuityOrder name="ContinuityOrder">ContinuityOrder</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContinuityChild name="ContinuityChild">ContinuityChild</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityChild attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContinuityLineEval name="ContinuityLineEval">ContinuityLineEval</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityLineEval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InstallmentOrderSubmitted name="InstallmentOrderSubmitted">InstallmentOrderSubmitted</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstallmentOrderSubmitted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OutOfBalanceReleaseType name="OutOfBalanceReleaseType">OutOfBalanceReleaseType</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutOfBalanceReleaseType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymOutOfBalanceType name="PaymOutOfBalanceType">PaymOutOfBalanceType</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymOutOfBalanceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InstallmentBillingPrompt name="InstallmentBillingPrompt">InstallmentBillingPrompt</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstallmentBillingPrompt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllocationPriority name="AllocationPriority">AllocationPriority</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesGroup name="SalesGroup">SalesGroup</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCalculationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidationStatus name="ValidationStatus">ValidationStatus</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidationDateTime name="ValidationDateTime">ValidationDateTime</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#IsTaxIncludedInPrice name="IsTaxIncludedInPrice">IsTaxIncludedInPrice</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxIncludedInPrice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SuspendedTransactionId name="SuspendedTransactionId">SuspendedTransactionId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardActiveFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#GiftCardExpireDate name="GiftCardExpireDate">GiftCardExpireDate</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardExpireDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#GiftCardIssueAmount name="GiftCardIssueAmount">GiftCardIssueAmount</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardIssueAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GiftCardBalance name="GiftCardBalance">GiftCardBalance</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GiftCardHistoryDetails name="GiftCardHistoryDetails">GiftCardHistoryDetails</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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

First included in: Transaction/RetailTransactionTable (this entity)  

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

### <a href=#InvoiceRecId name="InvoiceRecId">InvoiceRecId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailTransactionAggregationFieldList name="RetailTransactionAggregationFieldList">RetailTransactionAggregationFieldList</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTransactionAggregationFieldList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransactionOrderType name="TransactionOrderType">TransactionOrderType</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionOrderType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BeginDateTime name="BeginDateTime">BeginDateTime</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BeginDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DefaultDimensionStamped name="DefaultDimensionStamped">DefaultDimensionStamped</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionStamped attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/erp/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueSetRelationshipId name="Relationship_DimensionAttributeValueSetRelationshipId">Relationship_DimensionAttributeValueSetRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsPostalAddressRelationshipId name="Relationship_LogisticsPostalAddressRelationshipId">Relationship_LogisticsPostalAddressRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsPostalAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/erp/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelTableRelationshipId name="Relationship_RetailChannelTableRelationshipId">Relationship_RetailChannelTableRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailChannelTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="../Main/RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailloyaltycardRelationshipId name="Relationship_RetailloyaltycardRelationshipId">Relationship_RetailloyaltycardRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailloyaltycardRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyCard.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyCard.cdm.json/RetailLoyaltyCard</a></td><td><a href="../Miscellaneous/RetailLoyaltyCard.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailPosBatchTableRelationshipId name="Relationship_RetailPosBatchTableRelationshipId">Relationship_RetailPosBatchTableRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPosBatchTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailPosBatchTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/WorksheetHeader/RetailPosBatchTable.cdm.json/RetailPosBatchTable</a></td><td><a href="../WorksheetHeader/RetailPosBatchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStatementTableRelationshipId name="Relationship_RetailStatementTableRelationshipId">Relationship_RetailStatementTableRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStatementTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailStatementTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/WorksheetHeader/RetailStatementTable.cdm.json/RetailStatementTable</a></td><td><a href="../WorksheetHeader/RetailStatementTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailStoreTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreWorkShiftTableRelationshipId name="Relationship_RetailStoreWorkShiftTableRelationshipId">Relationship_RetailStoreWorkShiftTableRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreWorkShiftTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailStoreWorkShiftTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/WorksheetHeader/RetailStoreWorkShiftTable.cdm.json/RetailStoreWorkShiftTable</a></td><td><a href="../WorksheetHeader/RetailStoreWorkShiftTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTerminalTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTable1RelationshipId name="Relationship_RetailTerminalTable1RelationshipId">Relationship_RetailTerminalTable1RelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTable1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTerminalTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableBatchRelationshipId name="Relationship_RetailTerminalTableBatchRelationshipId">Relationship_RetailTerminalTableBatchRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTableBatchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTerminalTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CommissionSalesGroupRelationshipId name="Relationship_CommissionSalesGroupRelationshipId">Relationship_CommissionSalesGroupRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CommissionSalesGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/CommissionSalesGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/CommissionSalesGroup.cdm.json/CommissionSalesGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/CommissionSalesGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceJourRelationshipId name="Relationship_CustInvoiceJourRelationshipId">Relationship_CustInvoiceJourRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Transaction/CustInvoiceJour.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Transaction/CustInvoiceJour.cdm.json/CustInvoiceJour</a></td><td><a href="../../../Finance/AccountsReceivable/Transaction/CustInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionAggregationFieldListRelationshipId name="Relationship_RetailTransactionAggregationFieldListRelationshipId">Relationship_RetailTransactionAggregationFieldListRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionAggregationFieldListRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTransactionAggregationFieldList.md" target="_blank">/core/erp/Tables/Commerce/Retail/Transaction/RetailTransactionAggregationFieldList.cdm.json/RetailTransactionAggregationFieldList</a></td><td><a href="RetailTransactionAggregationFieldList.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RetailTransactionTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
