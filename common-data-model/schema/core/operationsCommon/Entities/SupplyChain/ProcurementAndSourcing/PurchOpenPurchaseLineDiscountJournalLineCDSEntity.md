---
title: PurchOpenPurchaseLineDiscountJournalLineCDSEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# CDS open purchase line discount journal lines in ProcurementAndSourcing(PurchOpenPurchaseLineDiscountJournalLineCDSEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS open purchase line discount journal lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DiscountAmount](#DiscountAmount)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[DiscountApplicableFromDate](#DiscountApplicableFromDate)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[DiscountApplicableToDate](#DiscountApplicableToDate)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[DiscountCurrencyCode](#DiscountCurrencyCode)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[DiscountPercentage1](#DiscountPercentage1)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[DiscountPercentage2](#DiscountPercentage2)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[DiscountSiteId](#DiscountSiteId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[DiscountWarehouseId](#DiscountWarehouseId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[FromQuantity](#FromQuantity)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[LineDiscountProductGroupCode](#LineDiscountProductGroupCode)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[LineDiscountVendorGroupCode](#LineDiscountVendorGroupCode)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[LineNumber](#LineNumber)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ProcessingLog](#ProcessingLog)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[QuantityUnitSymbol](#QuantityUnitSymbol)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ToQuantity](#ToQuantity)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[TradeAgreementJournalNumber](#TradeAgreementJournalNumber)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[WillSearchContinue](#WillSearchContinue)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[ProductNumber](#ProductNumber)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[BackingTable_PurchOpenPurchaseLineDiscountJournalLineEntityRelationshipId](#BackingTable_PurchOpenPurchaseLineDiscountJournalLineEntityRelationshipId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchOpenPurchaseLineDiscountJournalLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity</a>|

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountApplicableFromDate name="DiscountApplicableFromDate">DiscountApplicableFromDate</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountApplicableFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountApplicableToDate name="DiscountApplicableToDate">DiscountApplicableToDate</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountApplicableToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountCurrencyCode name="DiscountCurrencyCode">DiscountCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage1 name="DiscountPercentage1">DiscountPercentage1</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage2 name="DiscountPercentage2">DiscountPercentage2</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountSiteId name="DiscountSiteId">DiscountSiteId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountWarehouseId name="DiscountWarehouseId">DiscountWarehouseId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromQuantity name="FromQuantity">FromQuantity</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountProductGroupCode name="LineDiscountProductGroupCode">LineDiscountProductGroupCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountVendorGroupCode name="LineDiscountVendorGroupCode">LineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

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

### <a href=#ProcessingLog name="ProcessingLog">ProcessingLog</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingLog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityUnitSymbol name="QuantityUnitSymbol">QuantityUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToQuantity name="ToQuantity">ToQuantity</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAgreementJournalNumber name="TradeAgreementJournalNumber">TradeAgreementJournalNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAgreementJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSearchContinue name="WillSearchContinue">WillSearchContinue</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSearchContinue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchOpenPurchaseLineDiscountJournalLineEntityRelationshipId name="BackingTable_PurchOpenPurchaseLineDiscountJournalLineEntityRelationshipId">BackingTable_PurchOpenPurchaseLineDiscountJournalLineEntityRelationshipId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchOpenPurchaseLineDiscountJournalLineEntityRelationshipId attribute are listed below.</summary>

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

First included in: ProcurementAndSourcing/PurchOpenPurchaseLineDiscountJournalLineCDSEntity (this entity)  

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
