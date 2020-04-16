---
title: RetailTransactionAuditableSalesLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RetailAudit:RetailTransactionSalesTransAuditableEntityLabel

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailTransactionAuditableSalesLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RetailAudit:RetailTransactionSalesTransAuditableEntityLabel</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ItemSalesTaxGroup](#ItemSalesTaxGroup)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[RegisterNumber](#RegisterNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[TransactionId](#TransactionId)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Barcode](#Barcode)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[BusinessDate](#BusinessDate)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Comment](#Comment)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[CostAmount](#CostAmount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Currency](#Currency)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Dimension](#Dimension)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[DiscountAmountExcludingTax](#DiscountAmountExcludingTax)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ModeOfDelivery](#ModeOfDelivery)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Email](#Email)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[RetailEmailAddressContent](#RetailEmailAddressContent)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Giftcard](#Giftcard)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[BatchNumber](#BatchNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[InventoryDimensionNumber](#InventoryDimensionNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Warehouse](#Warehouse)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[SerialNumber](#SerialNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Site](#Site)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[InventoryStatusSales](#InventoryStatusSales)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[LotID](#LotID)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ProductScanned](#ProductScanned)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[KeyboardProductEntry](#KeyboardProductEntry)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[LineDiscountAmount](#LineDiscountAmount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[LineManualDiscountAmount](#LineManualDiscountAmount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[LineManualDiscountPercentage](#LineManualDiscountPercentage)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[LinkedProductNotOriginal](#LinkedProductNotOriginal)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[NetAmount](#NetAmount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[NetAmountIncludingTax](#NetAmountIncludingTax)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[OriginalOfLinkedProductList](#OriginalOfLinkedProductList)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[OriginalPrice](#OriginalPrice)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[OriginalSalesTaxGroup](#OriginalSalesTaxGroup)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[OriginalItemSalesTaxGroup](#OriginalItemSalesTaxGroup)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[PeriodicDiscountAmount](#PeriodicDiscountAmount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[PeriodicDiscountPercentage](#PeriodicDiscountPercentage)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Price](#Price)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[PriceChange](#PriceChange)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[PriceInBarcode](#PriceInBarcode)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Quantity](#Quantity)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[RequestedReceiptDate](#RequestedReceiptDate)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ReturnLineNumber](#ReturnLineNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ReturnQuantity](#ReturnQuantity)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ReturnStore](#ReturnStore)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ReturnRegisterNumber](#ReturnRegisterNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[ReturnTransactionNumber](#ReturnTransactionNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[RequestedShipDate](#RequestedShipDate)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[SalesStaff](#SalesStaff)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[StatementCode](#StatementCode)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[StatementNumber](#StatementNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[SalesTaxAmount](#SalesTaxAmount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[TransactionCode](#TransactionCode)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[TransactionStatus](#TransactionStatus)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[TransactionTime](#TransactionTime)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Unit](#Unit)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[VariantNumber](#VariantNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[FulfillmentStoreNumber](#FulfillmentStoreNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[GiftCardNumber](#GiftCardNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[SalesGroup](#SalesGroup)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[GiftCardBalance](#GiftCardBalance)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[LineDiscountPercentage](#LineDiscountPercentage)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[InventoryDimensionForReturn](#InventoryDimensionForReturn)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[SalesTaxOverride](#SalesTaxOverride)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[IsTaxExemptByTaxOverride](#IsTaxExemptByTaxOverride)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[GiftCardOperation](#GiftCardOperation)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[GiftCardType](#GiftCardType)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Company](#Company)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[OperatingUnitRecId](#OperatingUnitRecId)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[HeaderTransactionType](#HeaderTransactionType)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[HeaderValidationStatus](#HeaderValidationStatus)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[HeaderAsynchronousOrderStatus](#HeaderAsynchronousOrderStatus)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Relationship_RetailTransactionRelationshipId](#Relationship_RetailTransactionRelationshipId)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[BackingTable_RetailTransactionSalesTransRelationshipId](#BackingTable_RetailTransactionSalesTransRelationshipId)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionAuditableSalesLineEntity.md" target="_blank">Retail/RetailTransactionAuditableSalesLineEntity</a>|

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroup name="ItemSalesTaxGroup">ItemSalesTaxGroup</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegisterNumber name="RegisterNumber">RegisterNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegisterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Barcode name="Barcode">Barcode</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Barcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessDate name="BusinessDate">BusinessDate</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAmount name="CostAmount">CostAmount</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModeOfDelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailEmailAddressContent name="RetailEmailAddressContent">RetailEmailAddressContent</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailEmailAddressContent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Giftcard name="Giftcard">Giftcard</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Giftcard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchNumber name="BatchNumber">BatchNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryDimensionNumber name="InventoryDimensionNumber">InventoryDimensionNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryDimensionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Warehouse name="Warehouse">Warehouse</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Warehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerialNumber name="SerialNumber">SerialNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Site name="Site">Site</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Site attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatusSales name="InventoryStatusSales">InventoryStatusSales</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryStatusSales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LotID name="LotID">LotID</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LotID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductScanned name="ProductScanned">ProductScanned</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductScanned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyboardProductEntry name="KeyboardProductEntry">KeyboardProductEntry</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyboardProductEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountAmount name="LineDiscountAmount">LineDiscountAmount</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineManualDiscountAmount name="LineManualDiscountAmount">LineManualDiscountAmount</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineManualDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineManualDiscountPercentage name="LineManualDiscountPercentage">LineManualDiscountPercentage</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineManualDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinkedProductNotOriginal name="LinkedProductNotOriginal">LinkedProductNotOriginal</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinkedProductNotOriginal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmountIncludingTax name="NetAmountIncludingTax">NetAmountIncludingTax</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmountIncludingTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalOfLinkedProductList name="OriginalOfLinkedProductList">OriginalOfLinkedProductList</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalOfLinkedProductList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalPrice name="OriginalPrice">OriginalPrice</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalSalesTaxGroup name="OriginalSalesTaxGroup">OriginalSalesTaxGroup</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalItemSalesTaxGroup name="OriginalItemSalesTaxGroup">OriginalItemSalesTaxGroup</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodicDiscountAmount name="PeriodicDiscountAmount">PeriodicDiscountAmount</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodicDiscountPercentage name="PeriodicDiscountPercentage">PeriodicDiscountPercentage</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Price name="Price">Price</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Price attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceChange name="PriceChange">PriceChange</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceInBarcode name="PriceInBarcode">PriceInBarcode</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceInBarcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedReceiptDate name="RequestedReceiptDate">RequestedReceiptDate</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnLineNumber name="ReturnLineNumber">ReturnLineNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnQuantity name="ReturnQuantity">ReturnQuantity</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnStore name="ReturnStore">ReturnStore</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnStore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnRegisterNumber name="ReturnRegisterNumber">ReturnRegisterNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnRegisterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnTransactionNumber name="ReturnTransactionNumber">ReturnTransactionNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnTransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShipDate name="RequestedShipDate">RequestedShipDate</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShipDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesStaff name="SalesStaff">SalesStaff</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesStaff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementCode name="StatementCode">StatementCode</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxAmount name="SalesTaxAmount">SalesTaxAmount</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountPercentage name="TotalDiscountPercentage">TotalDiscountPercentage</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCode name="TransactionCode">TransactionCode</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionStatus name="TransactionStatus">TransactionStatus</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Unit name="Unit">Unit</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Unit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariantNumber name="VariantNumber">VariantNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariantNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FulfillmentStoreNumber name="FulfillmentStoreNumber">FulfillmentStoreNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfillmentStoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardNumber name="GiftCardNumber">GiftCardNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesGroup name="SalesGroup">SalesGroup</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardBalance name="GiftCardBalance">GiftCardBalance</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountPercentage name="LineDiscountPercentage">LineDiscountPercentage</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryDimensionForReturn name="InventoryDimensionForReturn">InventoryDimensionForReturn</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryDimensionForReturn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxOverride name="SalesTaxOverride">SalesTaxOverride</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxOverride attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTaxExemptByTaxOverride name="IsTaxExemptByTaxOverride">IsTaxExemptByTaxOverride</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxExemptByTaxOverride attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardOperation name="GiftCardOperation">GiftCardOperation</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardType name="GiftCardType">GiftCardType</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitRecId name="OperatingUnitRecId">OperatingUnitRecId</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderTransactionType name="HeaderTransactionType">HeaderTransactionType</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderValidationStatus name="HeaderValidationStatus">HeaderValidationStatus</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderValidationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderAsynchronousOrderStatus name="HeaderAsynchronousOrderStatus">HeaderAsynchronousOrderStatus</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderAsynchronousOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailTransactionRelationshipId name="Relationship_RetailTransactionRelationshipId">Relationship_RetailTransactionRelationshipId</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailTransactionSalesTransRelationshipId name="BackingTable_RetailTransactionSalesTransRelationshipId">BackingTable_RetailTransactionSalesTransRelationshipId</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionSalesTransRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailTransactionAuditableSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

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
