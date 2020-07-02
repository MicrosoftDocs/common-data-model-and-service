---
title: PriceDiscPurchaseTradeAgreementActivationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Activate purchase prices and discounts

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activate purchase prices and discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsSpecificProductSpecificVendorPriceCombinationActive](#IsSpecificProductSpecificVendorPriceCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductSpecificVendorGroupPriceCombinationActive](#IsSpecificProductSpecificVendorGroupPriceCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductAllVendorsPriceCombinationActive](#IsSpecificProductAllVendorsPriceCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductSpecificVendorLineDiscountCombinationActive](#IsSpecificProductSpecificVendorLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductSpecificVendorGroupLineDiscountCombinationActive](#IsSpecificProductSpecificVendorGroupLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductAllVendorsLineDiscountCombinationActive](#IsSpecificProductAllVendorsLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductGroupSpecificVendorLineDiscountCombinationActive](#IsSpecificProductGroupSpecificVendorLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductGroupSpecificVendorGroupLineDiscountCombinationActive](#IsSpecificProductGroupSpecificVendorGroupLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductGroupAllVendorsLineDiscountCombinationActive](#IsSpecificProductGroupAllVendorsLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsSpecificVendorLineDiscountCombinationActive](#IsAllProductsSpecificVendorLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsSpecificVendorGroupLineDiscountCombinationActive](#IsAllProductsSpecificVendorGroupLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsAllVendorsLineDiscountCombinationActive](#IsAllProductsAllVendorsLineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductGroupSpecificVendorMultilineDiscountCombinationActive](#IsSpecificProductGroupSpecificVendorMultilineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductGroupSpecificVendorGroupMultilineDiscountCombinationActive](#IsSpecificProductGroupSpecificVendorGroupMultilineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsSpecificProductGroupAllVendorsMultilineDiscountCombinationActive](#IsSpecificProductGroupAllVendorsMultilineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsSpecificVendorMultilineDiscountCombinationActive](#IsAllProductsSpecificVendorMultilineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsSpecificVendorGroupMultilineDiscountCombinationActive](#IsAllProductsSpecificVendorGroupMultilineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsAllVendorsMultilineDiscountCombinationActive](#IsAllProductsAllVendorsMultilineDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsSpecificVendorTotalDiscountCombinationActive](#IsAllProductsSpecificVendorTotalDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsSpecificVendorGroupTotalDiscountCombinationActive](#IsAllProductsSpecificVendorGroupTotalDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAllProductsAllVendorsTotalDiscountCombinationActive](#IsAllProductsAllVendorsTotalDiscountCombinationActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[IsAgreementDiscountActive](#IsAgreementDiscountActive)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[BackingTable_PriceParametersRelationshipId](#BackingTable_PriceParametersRelationshipId)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PriceDiscPurchaseTradeAgreementActivationEntity.md" target="_blank">ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity</a>|

### <a href=#IsSpecificProductSpecificVendorPriceCombinationActive name="IsSpecificProductSpecificVendorPriceCombinationActive">IsSpecificProductSpecificVendorPriceCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductSpecificVendorPriceCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductSpecificVendorGroupPriceCombinationActive name="IsSpecificProductSpecificVendorGroupPriceCombinationActive">IsSpecificProductSpecificVendorGroupPriceCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductSpecificVendorGroupPriceCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductAllVendorsPriceCombinationActive name="IsSpecificProductAllVendorsPriceCombinationActive">IsSpecificProductAllVendorsPriceCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductAllVendorsPriceCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductSpecificVendorLineDiscountCombinationActive name="IsSpecificProductSpecificVendorLineDiscountCombinationActive">IsSpecificProductSpecificVendorLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductSpecificVendorLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductSpecificVendorGroupLineDiscountCombinationActive name="IsSpecificProductSpecificVendorGroupLineDiscountCombinationActive">IsSpecificProductSpecificVendorGroupLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductSpecificVendorGroupLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductAllVendorsLineDiscountCombinationActive name="IsSpecificProductAllVendorsLineDiscountCombinationActive">IsSpecificProductAllVendorsLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductAllVendorsLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductGroupSpecificVendorLineDiscountCombinationActive name="IsSpecificProductGroupSpecificVendorLineDiscountCombinationActive">IsSpecificProductGroupSpecificVendorLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductGroupSpecificVendorLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductGroupSpecificVendorGroupLineDiscountCombinationActive name="IsSpecificProductGroupSpecificVendorGroupLineDiscountCombinationActive">IsSpecificProductGroupSpecificVendorGroupLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductGroupSpecificVendorGroupLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductGroupAllVendorsLineDiscountCombinationActive name="IsSpecificProductGroupAllVendorsLineDiscountCombinationActive">IsSpecificProductGroupAllVendorsLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductGroupAllVendorsLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsSpecificVendorLineDiscountCombinationActive name="IsAllProductsSpecificVendorLineDiscountCombinationActive">IsAllProductsSpecificVendorLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsSpecificVendorLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsSpecificVendorGroupLineDiscountCombinationActive name="IsAllProductsSpecificVendorGroupLineDiscountCombinationActive">IsAllProductsSpecificVendorGroupLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsSpecificVendorGroupLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsAllVendorsLineDiscountCombinationActive name="IsAllProductsAllVendorsLineDiscountCombinationActive">IsAllProductsAllVendorsLineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsAllVendorsLineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductGroupSpecificVendorMultilineDiscountCombinationActive name="IsSpecificProductGroupSpecificVendorMultilineDiscountCombinationActive">IsSpecificProductGroupSpecificVendorMultilineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductGroupSpecificVendorMultilineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductGroupSpecificVendorGroupMultilineDiscountCombinationActive name="IsSpecificProductGroupSpecificVendorGroupMultilineDiscountCombinationActive">IsSpecificProductGroupSpecificVendorGroupMultilineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductGroupSpecificVendorGroupMultilineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificProductGroupAllVendorsMultilineDiscountCombinationActive name="IsSpecificProductGroupAllVendorsMultilineDiscountCombinationActive">IsSpecificProductGroupAllVendorsMultilineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificProductGroupAllVendorsMultilineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsSpecificVendorMultilineDiscountCombinationActive name="IsAllProductsSpecificVendorMultilineDiscountCombinationActive">IsAllProductsSpecificVendorMultilineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsSpecificVendorMultilineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsSpecificVendorGroupMultilineDiscountCombinationActive name="IsAllProductsSpecificVendorGroupMultilineDiscountCombinationActive">IsAllProductsSpecificVendorGroupMultilineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsSpecificVendorGroupMultilineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsAllVendorsMultilineDiscountCombinationActive name="IsAllProductsAllVendorsMultilineDiscountCombinationActive">IsAllProductsAllVendorsMultilineDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsAllVendorsMultilineDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsSpecificVendorTotalDiscountCombinationActive name="IsAllProductsSpecificVendorTotalDiscountCombinationActive">IsAllProductsSpecificVendorTotalDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsSpecificVendorTotalDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsSpecificVendorGroupTotalDiscountCombinationActive name="IsAllProductsSpecificVendorGroupTotalDiscountCombinationActive">IsAllProductsSpecificVendorGroupTotalDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsSpecificVendorGroupTotalDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllProductsAllVendorsTotalDiscountCombinationActive name="IsAllProductsAllVendorsTotalDiscountCombinationActive">IsAllProductsAllVendorsTotalDiscountCombinationActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllProductsAllVendorsTotalDiscountCombinationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAgreementDiscountActive name="IsAgreementDiscountActive">IsAgreementDiscountActive</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAgreementDiscountActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PriceParametersRelationshipId name="BackingTable_PriceParametersRelationshipId">BackingTable_PriceParametersRelationshipId</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PriceParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/PriceParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/PriceParameters.cdm.json/PriceParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/PriceParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PriceDiscPurchaseTradeAgreementActivationEntity (this entity)  

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
