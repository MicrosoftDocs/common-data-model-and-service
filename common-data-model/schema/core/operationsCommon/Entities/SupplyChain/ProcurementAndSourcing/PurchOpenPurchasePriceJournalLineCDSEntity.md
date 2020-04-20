---
title: PurchOpenPurchasePriceJournalLineCDSEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PurchOpenPurchasePriceJournalLineCDSEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ProductNumber](#ProductNumber)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[AttributeBasedPricingId](#AttributeBasedPricingId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[FixedPriceCharges](#FixedPriceCharges)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[FromQuantity](#FromQuantity)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[IsProcurementLeadTimeUsingWorkingDays](#IsProcurementLeadTimeUsingWorkingDays)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[LineNumber](#LineNumber)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[Price](#Price)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[PriceApplicableFromDate](#PriceApplicableFromDate)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[PriceApplicableToDate](#PriceApplicableToDate)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[PriceCurrencyCode](#PriceCurrencyCode)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[PriceSiteId](#PriceSiteId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[PriceVendorGroupCode](#PriceVendorGroupCode)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[PriceWarehouseId](#PriceWarehouseId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[ProcessingLog](#ProcessingLog)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[ProcurementLeadTimeDays](#ProcurementLeadTimeDays)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[PurchasePriceQuantity](#PurchasePriceQuantity)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[QuantityUnitSymbol](#QuantityUnitSymbol)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[ToQuantity](#ToQuantity)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[TradeAgreementJournalNumber](#TradeAgreementJournalNumber)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[WillDeliveryDateControlDisregardLeadTime](#WillDeliveryDateControlDisregardLeadTime)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[WillSearchContinue](#WillSearchContinue)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[BackingTable_PurchOpenPurchasePriceJournalLineEntityRelationshipId](#BackingTable_PurchOpenPurchasePriceJournalLineEntityRelationshipId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchOpenPurchasePriceJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity</a>|

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeBasedPricingId name="AttributeBasedPricingId">AttributeBasedPricingId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeBasedPricingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPriceCharges name="FixedPriceCharges">FixedPriceCharges</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromQuantity name="FromQuantity">FromQuantity</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcurementLeadTimeUsingWorkingDays name="IsProcurementLeadTimeUsingWorkingDays">IsProcurementLeadTimeUsingWorkingDays</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcurementLeadTimeUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

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

### <a href=#Price name="Price">Price</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Price attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceApplicableFromDate name="PriceApplicableFromDate">PriceApplicableFromDate</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceApplicableFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceApplicableToDate name="PriceApplicableToDate">PriceApplicableToDate</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceApplicableToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceCurrencyCode name="PriceCurrencyCode">PriceCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceSiteId name="PriceSiteId">PriceSiteId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceVendorGroupCode name="PriceVendorGroupCode">PriceVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceWarehouseId name="PriceWarehouseId">PriceWarehouseId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessingLog name="ProcessingLog">ProcessingLog</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingLog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementLeadTimeDays name="ProcurementLeadTimeDays">ProcurementLeadTimeDays</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceQuantity name="PurchasePriceQuantity">PurchasePriceQuantity</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityUnitSymbol name="QuantityUnitSymbol">QuantityUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToQuantity name="ToQuantity">ToQuantity</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAgreementJournalNumber name="TradeAgreementJournalNumber">TradeAgreementJournalNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAgreementJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDeliveryDateControlDisregardLeadTime name="WillDeliveryDateControlDisregardLeadTime">WillDeliveryDateControlDisregardLeadTime</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDeliveryDateControlDisregardLeadTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSearchContinue name="WillSearchContinue">WillSearchContinue</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSearchContinue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchOpenPurchasePriceJournalLineEntityRelationshipId name="BackingTable_PurchOpenPurchasePriceJournalLineEntityRelationshipId">BackingTable_PurchOpenPurchasePriceJournalLineEntityRelationshipId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchOpenPurchasePriceJournalLineEntityRelationshipId attribute are listed below.</summary>

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

First included in: ProcurementAndSourcing/PurchOpenPurchasePriceJournalLineCDSEntity (this entity)  

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
