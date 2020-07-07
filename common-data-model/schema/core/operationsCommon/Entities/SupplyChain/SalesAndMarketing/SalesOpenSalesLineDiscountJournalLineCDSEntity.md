---
title: SalesOpenSalesLineDiscountJournalLineCDSEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# CDS open sales line discount journal lines in SalesAndMarketing

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS open sales line discount journal lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductNumber](#ProductNumber)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[DiscountApplicableFromDate](#DiscountApplicableFromDate)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[DiscountApplicableToDate](#DiscountApplicableToDate)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[DiscountCurrencyCode](#DiscountCurrencyCode)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[DiscountPercentage1](#DiscountPercentage1)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[DiscountPercentage2](#DiscountPercentage2)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[DiscountSiteId](#DiscountSiteId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[DiscountWarehouseId](#DiscountWarehouseId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[FromQuantity](#FromQuantity)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[IsGenericCurrencySearchEnabled](#IsGenericCurrencySearchEnabled)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[LineDiscountCustomerGroupCode](#LineDiscountCustomerGroupCode)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[LineDiscountProductGroupCode](#LineDiscountProductGroupCode)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[LineNumber](#LineNumber)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[ProcessingLog](#ProcessingLog)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[QuantityUnitSymbol](#QuantityUnitSymbol)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[ToQuantity](#ToQuantity)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[TradeAgreementJournalNumber](#TradeAgreementJournalNumber)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[WillSearchContinue](#WillSearchContinue)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[BackingTable_SalesOpenSalesLineDiscountJournalLineEntityRelationshipId](#BackingTable_SalesOpenSalesLineDiscountJournalLineEntityRelationshipId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesOpenSalesLineDiscountJournalLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity</a>|

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

### <a href=#IsGenericCurrencySearchEnabled name="IsGenericCurrencySearchEnabled">IsGenericCurrencySearchEnabled</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGenericCurrencySearchEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountCustomerGroupCode name="LineDiscountCustomerGroupCode">LineDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountProductGroupCode name="LineDiscountProductGroupCode">LineDiscountProductGroupCode</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

### <a href=#WillSearchContinue name="WillSearchContinue">WillSearchContinue</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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

### <a href=#BackingTable_SalesOpenSalesLineDiscountJournalLineEntityRelationshipId name="BackingTable_SalesOpenSalesLineDiscountJournalLineEntityRelationshipId">BackingTable_SalesOpenSalesLineDiscountJournalLineEntityRelationshipId</a>

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesOpenSalesLineDiscountJournalLineEntityRelationshipId attribute are listed below.</summary>

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

First included in: SalesAndMarketing/SalesOpenSalesLineDiscountJournalLineCDSEntity (this entity)  

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
