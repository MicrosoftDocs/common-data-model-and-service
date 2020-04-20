---
title: PurchaseLineDiscountAgreementEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PurchaseLineDiscountAgreementEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AccountCode](#AccountCode)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[AccountRelation](#AccountRelation)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[DiscountCurrencyCode](#DiscountCurrencyCode)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[DiscountApplicableFromDate](#DiscountApplicableFromDate)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[InventDimId](#InventDimId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ItemCode](#ItemCode)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[DiscountPercentage1](#DiscountPercentage1)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[DiscountPercentage2](#DiscountPercentage2)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[FromQuantity](#FromQuantity)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ToQuantity](#ToQuantity)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[WillSearchContinue](#WillSearchContinue)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[DiscountApplicableToDate](#DiscountApplicableToDate)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[QuantityUnitSymbol](#QuantityUnitSymbol)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[RecordId](#RecordId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[LineDiscountVendorGroupCode](#LineDiscountVendorGroupCode)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[LineDiscountProductGroupCode](#LineDiscountProductGroupCode)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[DiscountSiteId](#DiscountSiteId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[DiscountWarehouseId](#DiscountWarehouseId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[ProductNumber](#ProductNumber)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[BackingTable_PriceDiscTableRelationshipId](#BackingTable_PriceDiscTableRelationshipId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchaseLineDiscountAgreementEntity.md" target="_blank">ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity</a>|

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#DiscountCurrencyCode name="DiscountCurrencyCode">DiscountCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountApplicableFromDate name="DiscountApplicableFromDate">DiscountApplicableFromDate</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountApplicableFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage1 name="DiscountPercentage1">DiscountPercentage1</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage2 name="DiscountPercentage2">DiscountPercentage2</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromQuantity name="FromQuantity">FromQuantity</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#ToQuantity name="ToQuantity">ToQuantity</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#WillSearchContinue name="WillSearchContinue">WillSearchContinue</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#DiscountApplicableToDate name="DiscountApplicableToDate">DiscountApplicableToDate</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountApplicableToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityUnitSymbol name="QuantityUnitSymbol">QuantityUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#RecordId name="RecordId">RecordId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#LineDiscountVendorGroupCode name="LineDiscountVendorGroupCode">LineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountProductGroupCode name="LineDiscountProductGroupCode">LineDiscountProductGroupCode</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#DiscountSiteId name="DiscountSiteId">DiscountSiteId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountWarehouseId name="DiscountWarehouseId">DiscountWarehouseId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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

### <a href=#BackingTable_PriceDiscTableRelationshipId name="BackingTable_PriceDiscTableRelationshipId">BackingTable_PriceDiscTableRelationshipId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PriceDiscTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscTable.cdm.json/PriceDiscTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchaseLineDiscountAgreementEntity (this entity)  

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
