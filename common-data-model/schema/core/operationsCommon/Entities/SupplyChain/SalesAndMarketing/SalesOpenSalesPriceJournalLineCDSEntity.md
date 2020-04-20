---
title: SalesOpenSalesPriceJournalLineCDSEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# SalesOpenSalesPriceJournalLineCDSEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ProductNumber](#ProductNumber)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[AttributeBasedPricingId](#AttributeBasedPricingId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[FixedPriceCharges](#FixedPriceCharges)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[FromQuantity](#FromQuantity)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[IsGenericCurrencySearchEnabled](#IsGenericCurrencySearchEnabled)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[LineNumber](#LineNumber)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[Price](#Price)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[PriceApplicableFromDate](#PriceApplicableFromDate)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[PriceApplicableToDate](#PriceApplicableToDate)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[PriceCurrencyCode](#PriceCurrencyCode)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[PriceCustomerGroupCode](#PriceCustomerGroupCode)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[PriceSiteId](#PriceSiteId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[PriceWarehouseId](#PriceWarehouseId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[ProcessingLog](#ProcessingLog)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[QuantityUnitSymbol](#QuantityUnitSymbol)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[SalesLeadTimeDays](#SalesLeadTimeDays)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[SalesPriceQuantity](#SalesPriceQuantity)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[ToQuantity](#ToQuantity)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[TradeAgreementJournalNumber](#TradeAgreementJournalNumber)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[WillDeliveryDateControlDisregardLeadTime](#WillDeliveryDateControlDisregardLeadTime)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[WillSearchContinue](#WillSearchContinue)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[BackingTable_SalesOpenSalesPriceJournalLineEntityRelationshipId](#BackingTable_SalesOpenSalesPriceJournalLineEntityRelationshipId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesOpenSalesPriceJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity</a>|

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPriceCharges name="FixedPriceCharges">FixedPriceCharges</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#IsGenericCurrencySearchEnabled name="IsGenericCurrencySearchEnabled">IsGenericCurrencySearchEnabled</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGenericCurrencySearchEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#PriceCustomerGroupCode name="PriceCustomerGroupCode">PriceCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceSiteId name="PriceSiteId">PriceSiteId</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#PriceWarehouseId name="PriceWarehouseId">PriceWarehouseId</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#QuantityUnitSymbol name="QuantityUnitSymbol">QuantityUnitSymbol</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#SalesLeadTimeDays name="SalesLeadTimeDays">SalesLeadTimeDays</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceQuantity name="SalesPriceQuantity">SalesPriceQuantity</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToQuantity name="ToQuantity">ToQuantity</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#WillDeliveryDateControlDisregardLeadTime name="WillDeliveryDateControlDisregardLeadTime">WillDeliveryDateControlDisregardLeadTime</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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

### <a href=#BackingTable_SalesOpenSalesPriceJournalLineEntityRelationshipId name="BackingTable_SalesOpenSalesPriceJournalLineEntityRelationshipId">BackingTable_SalesOpenSalesPriceJournalLineEntityRelationshipId</a>

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesOpenSalesPriceJournalLineEntityRelationshipId attribute are listed below.</summary>

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

First included in: SalesAndMarketing/SalesOpenSalesPriceJournalLineCDSEntity (this entity)  

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
