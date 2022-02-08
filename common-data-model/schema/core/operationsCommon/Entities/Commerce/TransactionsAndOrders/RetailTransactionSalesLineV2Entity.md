---
title: RetailTransactionSalesLineV2Entity in TransactionsAndOrders - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales transactions V2 in TransactionsAndOrders(RetailTransactionSalesLineV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/TransactionsAndOrders/RetailTransactionSalesLineV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales transactions V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ItemSalesTaxGroup](#ItemSalesTaxGroup)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[Terminal](#Terminal)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TransactionNumber](#TransactionNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[BarCode](#BarCode)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CatalogId](#CatalogId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CategoryId](#CategoryId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[Channel](#Channel)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CostAmount](#CostAmount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[Currency](#Currency)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CustomerDiscount](#CustomerDiscount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CustomerInvoiceDiscountAmount](#CustomerInvoiceDiscountAmount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CashDiscountAmount](#CashDiscountAmount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[DiscountAmountWithoutTax](#DiscountAmountWithoutTax)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[PriceGroups](#PriceGroups)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[OfferNumber](#OfferNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[DiscountAmountForPrinting](#DiscountAmountForPrinting)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ModeOfDelivery](#ModeOfDelivery)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ElectronicDeliveryEmail](#ElectronicDeliveryEmail)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[RetailEmailAddressContent](#RetailEmailAddressContent)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[GiftCard](#GiftCard)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ReasonCodeDiscount](#ReasonCodeDiscount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[Warehouse](#Warehouse)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[SerialNumber](#SerialNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[SiteId](#SiteId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[InventoryStatus](#InventoryStatus)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LotID](#LotID)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ItemId](#ItemId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ProductScanned](#ProductScanned)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ItemRelation](#ItemRelation)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[KeyboardProductEntry](#KeyboardProductEntry)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LineDiscount](#LineDiscount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LineManualDiscountAmount](#LineManualDiscountAmount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LineManualDiscountPercentage](#LineManualDiscountPercentage)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[IsLineDiscounted](#IsLineDiscounted)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[IsLinkedProductNotOriginal](#IsLinkedProductNotOriginal)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ChannelListingID](#ChannelListingID)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LogisticPostalAddressId](#LogisticPostalAddressId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[NetAmount](#NetAmount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[NetAmountInclusiveTax](#NetAmountInclusiveTax)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[NetPrice](#NetPrice)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[IsOriginalOfLinkedProductList](#IsOriginalOfLinkedProductList)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[OriginalPrice](#OriginalPrice)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[OriginalSalesTaxGroup](#OriginalSalesTaxGroup)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[OriginalItemSalesTaxGroup](#OriginalItemSalesTaxGroup)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[PeriodicDiscountAmount](#PeriodicDiscountAmount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[PeriodicDiscountGroup](#PeriodicDiscountGroup)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[PeriodicDiscountPercentage](#PeriodicDiscountPercentage)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[Price](#Price)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[IsPriceChange](#IsPriceChange)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[PriceInBarCode](#PriceInBarCode)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[Quantity](#Quantity)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[RequestedReceiptDate](#RequestedReceiptDate)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ReturnLineNumber](#ReturnLineNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[IsReturnNoSale](#IsReturnNoSale)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ReturnQuantity](#ReturnQuantity)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ReturnTerminal](#ReturnTerminal)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ReturnTransactionNumber](#ReturnTransactionNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[RFIDTagId](#RFIDTagId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[IsScaleProduct](#IsScaleProduct)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[SectionNumber](#SectionNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ShelfNumber](#ShelfNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[RequestedShipDate](#RequestedShipDate)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[StandardNetPrice](#StandardNetPrice)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[SalesTaxAmount](#SalesTaxAmount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TotalDiscount](#TotalDiscount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TotalDiscountInfoCodeLineNum](#TotalDiscountInfoCodeLineNum)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TransactionCode](#TransactionCode)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TransactionStatus](#TransactionStatus)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[Unit](#Unit)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[UnitPrice](#UnitPrice)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[UnitQuantity](#UnitQuantity)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[VariantNumber](#VariantNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[IsWeightProduct](#IsWeightProduct)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[IsWeightManuallyEntered](#IsWeightManuallyEntered)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CategoryName](#CategoryName)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[CategoryHierarchyName](#CategoryHierarchyName)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LogisticsPostalAddressLocation](#LogisticsPostalAddressLocation)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LogisticsPostalAddressValidFrom](#LogisticsPostalAddressValidFrom)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LogisticLocationId](#LogisticLocationId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[RetailChannelTableOMOperatingUnitID](#RetailChannelTableOMOperatingUnitID)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ReturnOperatingUnitNumber](#ReturnOperatingUnitNumber)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ItemColor](#ItemColor)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ItemSize](#ItemSize)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ItemStyle](#ItemStyle)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[ItemConfigId](#ItemConfigId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[InventDimId](#InventDimId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[SkipReports](#SkipReports)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[LinePercentageDiscount](#LinePercentageDiscount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[BusinessDate](#BusinessDate)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TransactionDate](#TransactionDate)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TaxExemptPriceInclusiveOriginalPrice](#TaxExemptPriceInclusiveOriginalPrice)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[TaxExemptPriceInclusiveReductionAmount](#TaxExemptPriceInclusiveReductionAmount)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[BackingTable_RetailTransactionSalesTransRelationshipId](#BackingTable_RetailTransactionSalesTransRelationshipId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionSalesLineV2Entity.md" target="_blank">TransactionsAndOrders/RetailTransactionSalesLineV2Entity</a>|

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroup name="ItemSalesTaxGroup">ItemSalesTaxGroup</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionNumber name="TransactionNumber">TransactionNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCode name="BarCode">BarCode</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatalogId name="CatalogId">CatalogId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId name="CategoryId">CategoryId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAmount name="CostAmount">CostAmount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

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

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDiscount name="CustomerDiscount">CustomerDiscount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerInvoiceDiscountAmount name="CustomerInvoiceDiscountAmount">CustomerInvoiceDiscountAmount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerInvoiceDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountAmount name="CashDiscountAmount">CashDiscountAmount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmountWithoutTax name="DiscountAmountWithoutTax">DiscountAmountWithoutTax</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmountWithoutTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceGroups name="PriceGroups">PriceGroups</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceGroups attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfferNumber name="OfferNumber">OfferNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfferNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmountForPrinting name="DiscountAmountForPrinting">DiscountAmountForPrinting</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount amount for printing</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmountForPrinting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount amount for printing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModeOfDelivery name="ModeOfDelivery">ModeOfDelivery</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModeOfDelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicDeliveryEmail name="ElectronicDeliveryEmail">ElectronicDeliveryEmail</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicDeliveryEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailEmailAddressContent name="RetailEmailAddressContent">RetailEmailAddressContent</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailEmailAddressContent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCard name="GiftCard">GiftCard</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonCodeDiscount name="ReasonCodeDiscount">ReasonCodeDiscount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonCodeDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Warehouse name="Warehouse">Warehouse</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Warehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerialNumber name="SerialNumber">SerialNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatus name="InventoryStatus">InventoryStatus</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LotID name="LotID">LotID</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LotID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductScanned name="ProductScanned">ProductScanned</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductScanned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyboardProductEntry name="KeyboardProductEntry">KeyboardProductEntry</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyboardProductEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscount name="LineDiscount">LineDiscount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineManualDiscountAmount name="LineManualDiscountAmount">LineManualDiscountAmount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineManualDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineManualDiscountPercentage name="LineManualDiscountPercentage">LineManualDiscountPercentage</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineManualDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

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

### <a href=#IsLineDiscounted name="IsLineDiscounted">IsLineDiscounted</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLineDiscounted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLinkedProductNotOriginal name="IsLinkedProductNotOriginal">IsLinkedProductNotOriginal</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLinkedProductNotOriginal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelListingID name="ChannelListingID">ChannelListingID</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelListingID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticPostalAddressId name="LogisticPostalAddressId">LogisticPostalAddressId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticPostalAddressId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmountInclusiveTax name="NetAmountInclusiveTax">NetAmountInclusiveTax</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmountInclusiveTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetPrice name="NetPrice">NetPrice</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOriginalOfLinkedProductList name="IsOriginalOfLinkedProductList">IsOriginalOfLinkedProductList</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOriginalOfLinkedProductList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalPrice name="OriginalPrice">OriginalPrice</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalSalesTaxGroup name="OriginalSalesTaxGroup">OriginalSalesTaxGroup</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalItemSalesTaxGroup name="OriginalItemSalesTaxGroup">OriginalItemSalesTaxGroup</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodicDiscountAmount name="PeriodicDiscountAmount">PeriodicDiscountAmount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Periodic discount amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Periodic discount amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodicDiscountGroup name="PeriodicDiscountGroup">PeriodicDiscountGroup</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicDiscountGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodicDiscountPercentage name="PeriodicDiscountPercentage">PeriodicDiscountPercentage</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Price name="Price">Price</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Price attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPriceChange name="IsPriceChange">IsPriceChange</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPriceChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceInBarCode name="PriceInBarCode">PriceInBarCode</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceInBarCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedReceiptDate name="RequestedReceiptDate">RequestedReceiptDate</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnLineNumber name="ReturnLineNumber">ReturnLineNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReturnNoSale name="IsReturnNoSale">IsReturnNoSale</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReturnNoSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnQuantity name="ReturnQuantity">ReturnQuantity</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnTerminal name="ReturnTerminal">ReturnTerminal</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnTerminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnTransactionNumber name="ReturnTransactionNumber">ReturnTransactionNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnTransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFIDTagId name="RFIDTagId">RFIDTagId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFIDTagId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsScaleProduct name="IsScaleProduct">IsScaleProduct</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsScaleProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SectionNumber name="SectionNumber">SectionNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SectionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShelfNumber name="ShelfNumber">ShelfNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShelfNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShipDate name="RequestedShipDate">RequestedShipDate</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShipDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardNetPrice name="StandardNetPrice">StandardNetPrice</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardNetPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxAmount name="SalesTaxAmount">SalesTaxAmount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscount name="TotalDiscount">TotalDiscount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountInfoCodeLineNum name="TotalDiscountInfoCodeLineNum">TotalDiscountInfoCodeLineNum</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountInfoCodeLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountPercentage name="TotalDiscountPercentage">TotalDiscountPercentage</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount percentage</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCode name="TransactionCode">TransactionCode</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionStatus name="TransactionStatus">TransactionStatus</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Unit name="Unit">Unit</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Unit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitQuantity name="UnitQuantity">UnitQuantity</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariantNumber name="VariantNumber">VariantNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariantNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWeightProduct name="IsWeightProduct">IsWeightProduct</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWeightProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWeightManuallyEntered name="IsWeightManuallyEntered">IsWeightManuallyEntered</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWeightManuallyEntered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryName name="CategoryName">CategoryName</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchyName name="CategoryHierarchyName">CategoryHierarchyName</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalAddressLocation name="LogisticsPostalAddressLocation">LogisticsPostalAddressLocation</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddressLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalAddressValidFrom name="LogisticsPostalAddressValidFrom">LogisticsPostalAddressValidFrom</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticLocationId name="LogisticLocationId">LogisticLocationId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelTableOMOperatingUnitID name="RetailChannelTableOMOperatingUnitID">RetailChannelTableOMOperatingUnitID</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelTableOMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnOperatingUnitNumber name="ReturnOperatingUnitNumber">ReturnOperatingUnitNumber</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnOperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemColor name="ItemColor">ItemColor</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSize name="ItemSize">ItemSize</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemStyle name="ItemStyle">ItemStyle</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemStyle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemConfigId name="ItemConfigId">ItemConfigId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemConfigId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipReports name="SkipReports">SkipReports</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipReports attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinePercentageDiscount name="LinePercentageDiscount">LinePercentageDiscount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePercentageDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessDate name="BusinessDate">BusinessDate</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptPriceInclusiveOriginalPrice name="TaxExemptPriceInclusiveOriginalPrice">TaxExemptPriceInclusiveOriginalPrice</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptPriceInclusiveOriginalPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptPriceInclusiveReductionAmount name="TaxExemptPriceInclusiveReductionAmount">TaxExemptPriceInclusiveReductionAmount</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptPriceInclusiveReductionAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTransactionSalesTransRelationshipId name="BackingTable_RetailTransactionSalesTransRelationshipId">BackingTable_RetailTransactionSalesTransRelationshipId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionSalesTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionSalesTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionSalesTrans.cdm.json/RetailTransactionSalesTrans</a></td><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionSalesTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TransactionsAndOrders/RetailTransactionSalesLineV2Entity (this entity)  

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
