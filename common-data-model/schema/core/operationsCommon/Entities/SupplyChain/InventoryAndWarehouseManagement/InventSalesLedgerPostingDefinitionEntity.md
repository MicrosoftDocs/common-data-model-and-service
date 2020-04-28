---
title: InventSalesLedgerPostingDefinitionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Ledger posting definition for sales

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger posting definition for sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InventoryAccountType](#InventoryAccountType)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[MainAccountIdDisplayValue](#MainAccountIdDisplayValue)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[ProductCategoryName](#ProductCategoryName)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[CustomerGroupId](#CustomerGroupId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[AccountType](#AccountType)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[ItemCode](#ItemCode)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[CategoryRelation](#CategoryRelation)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[CustVendCode](#CustVendCode)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[CustVendRelation](#CustVendRelation)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[InventoryProfileRelation](#InventoryProfileRelation)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[KindOfActivity](#KindOfActivity)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[InventoryProfileId](#InventoryProfileId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[SiteCode](#SiteCode)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[SiteRelation](#SiteRelation)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[SalesSiteId](#SalesSiteId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[CategoryRecordId](#CategoryRecordId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[Relationship_MainAccountCombinationRelationshipId](#Relationship_MainAccountCombinationRelationshipId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[BackingTable_InventPostingRelationshipId](#BackingTable_InventPostingRelationshipId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventSalesLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity</a>|

### <a href=#InventoryAccountType name="InventoryAccountType">InventoryAccountType</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdDisplayValue name="MainAccountIdDisplayValue">MainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

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

### <a href=#ProductGroupId name="ProductGroupId">ProductGroupId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryName name="ProductCategoryName">ProductCategoryName</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

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

### <a href=#CustomerGroupId name="CustomerGroupId">CustomerGroupId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

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

### <a href=#CategoryRelation name="CategoryRelation">CategoryRelation</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustVendCode name="CustVendCode">CustVendCode</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustVendRelation name="CustVendRelation">CustVendRelation</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryProfileRelation name="InventoryProfileRelation">InventoryProfileRelation</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryProfileRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KindOfActivity name="KindOfActivity">KindOfActivity</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KindOfActivity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryProfileId name="InventoryProfileId">InventoryProfileId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteCode name="SiteCode">SiteCode</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteRelation name="SiteRelation">SiteRelation</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSiteId name="SalesSiteId">SalesSiteId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryRecordId name="CategoryRecordId">CategoryRecordId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountCombinationRelationshipId name="Relationship_MainAccountCombinationRelationshipId">Relationship_MainAccountCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventPostingRelationshipId name="BackingTable_InventPostingRelationshipId">BackingTable_InventPostingRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventPostingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventPosting.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventPosting.cdm.json/InventPosting</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventPosting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventSalesLedgerPostingDefinitionEntity (this entity)  

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
