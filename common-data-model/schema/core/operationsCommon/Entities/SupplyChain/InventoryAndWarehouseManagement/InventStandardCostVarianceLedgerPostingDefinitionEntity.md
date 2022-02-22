---
title: InventStandardCostVarianceLedgerPostingDefinitionEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Ledger posting definition for standard cost variance in InventoryAndWarehouseManagement(InventStandardCostVarianceLedgerPostingDefinitionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger posting definition for standard cost variance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InventoryAccountType](#InventoryAccountType)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[MainAccountIdDisplayValue](#MainAccountIdDisplayValue)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[CostGroupId](#CostGroupId)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[AccountType](#AccountType)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[ItemCode](#ItemCode)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[CostCode](#CostCode)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[CostRelation](#CostRelation)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[CostGroupType](#CostGroupType)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[SiteCode](#SiteCode)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[SiteRelation](#SiteRelation)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[CostingSiteId](#CostingSiteId)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[Relationship_MainAccountCombinationRelationshipId](#Relationship_MainAccountCombinationRelationshipId)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[BackingTable_InventPostingRelationshipId](#BackingTable_InventPostingRelationshipId)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventStandardCostVarianceLedgerPostingDefinitionEntity.md" target="_blank">InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity</a>|

### <a href=#InventoryAccountType name="InventoryAccountType">InventoryAccountType</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdDisplayValue name="MainAccountIdDisplayValue">MainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

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

### <a href=#ProductGroupId name="ProductGroupId">ProductGroupId</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostGroupId name="CostGroupId">CostGroupId</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

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

### <a href=#CostCode name="CostCode">CostCode</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostRelation name="CostRelation">CostRelation</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostGroupType name="CostGroupType">CostGroupType</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostGroupType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteCode name="SiteCode">SiteCode</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteRelation name="SiteRelation">SiteRelation</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostingSiteId name="CostingSiteId">CostingSiteId</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountCombinationRelationshipId name="Relationship_MainAccountCombinationRelationshipId">Relationship_MainAccountCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventStandardCostVarianceLedgerPostingDefinitionEntity (this entity)  

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
