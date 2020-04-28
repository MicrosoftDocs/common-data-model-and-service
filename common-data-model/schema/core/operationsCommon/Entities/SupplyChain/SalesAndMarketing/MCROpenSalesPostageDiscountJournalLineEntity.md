---
title: MCROpenSalesPostageDiscountJournalLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Open sales postage discount journal lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Open sales postage discount journal lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[JournalNumber](#JournalNumber)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[PostageDiscountCustomerGroupCode](#PostageDiscountCustomerGroupCode)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[DiscountSiteId](#DiscountSiteId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[DiscountWarehouseId](#DiscountWarehouseId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[QuantityFrom](#QuantityFrom)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[QuantityTo](#QuantityTo)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[QuantityUnitSymbol](#QuantityUnitSymbol)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[DiscountApplicableFromDate](#DiscountApplicableFromDate)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[DiscountApplicableToDate](#DiscountApplicableToDate)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[DiscountCurrencyCode](#DiscountCurrencyCode)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[DiscountPercentage1](#DiscountPercentage1)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[DiscountPercentage2](#DiscountPercentage2)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[IsContinuedSearchEnabled](#IsContinuedSearchEnabled)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[Log](#Log)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[AccountRelation](#AccountRelation)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[AccountCode](#AccountCode)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[ItemCode](#ItemCode)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[JournalNum](#JournalNum)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[Relationship_SiteRelationshipId](#Relationship_SiteRelationshipId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[Relationship_WarehouseRelationshipId](#Relationship_WarehouseRelationshipId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[BackingTable_PriceDiscAdmTransRelationshipId](#BackingTable_PriceDiscAdmTransRelationshipId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="MCROpenSalesPostageDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity</a>|

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#PostageDiscountCustomerGroupCode name="PostageDiscountCustomerGroupCode">PostageDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostageDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountSiteId name="DiscountSiteId">DiscountSiteId</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#QuantityFrom name="QuantityFrom">QuantityFrom</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityTo name="QuantityTo">QuantityTo</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityUnitSymbol name="QuantityUnitSymbol">QuantityUnitSymbol</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#DiscountApplicableFromDate name="DiscountApplicableFromDate">DiscountApplicableFromDate</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#DiscountApplicableToDate name="DiscountApplicableToDate">DiscountApplicableToDate</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#DiscountPercentage1 name="DiscountPercentage1">DiscountPercentage1</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#IsContinuedSearchEnabled name="IsContinuedSearchEnabled">IsContinuedSearchEnabled</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContinuedSearchEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Log name="Log">Log</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Log attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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

### <a href=#JournalNum name="JournalNum">JournalNum</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SiteRelationshipId name="Relationship_SiteRelationshipId">Relationship_SiteRelationshipId</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseRelationshipId name="Relationship_WarehouseRelationshipId">Relationship_WarehouseRelationshipId</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PriceDiscAdmTransRelationshipId name="BackingTable_PriceDiscAdmTransRelationshipId">BackingTable_PriceDiscAdmTransRelationshipId</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PriceDiscAdmTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.cdm.json/PriceDiscAdmTrans</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/MCROpenSalesPostageDiscountJournalLineEntity (this entity)  

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
