---
title: WHSLoadMixGroupConstraintEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Load mix group constraints

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Load mix group constraints</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LoadBuildAction](#LoadBuildAction)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|
|[LoadMixGroupCriteria](#LoadMixGroupCriteria)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|
|[ConstrainingProductGroupId](#ConstrainingProductGroupId)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|
|[ConstrainingWarehouseFilterCode](#ConstrainingWarehouseFilterCode)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|
|[LoadMixGroupId](#LoadMixGroupId)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|
|[LoadMixGroupCriterionProductGroupId](#LoadMixGroupCriterionProductGroupId)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|
|[LoadMixGroupCriterionWarehouseFilterCode](#LoadMixGroupCriterionWarehouseFilterCode)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|
|[BackingTable_WHSLoadMixGroupConstraintRelationshipId](#BackingTable_WHSLoadMixGroupConstraintRelationshipId)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSLoadMixGroupConstraintEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity</a>|

### <a href=#LoadBuildAction name="LoadBuildAction">LoadBuildAction</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadBuildAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadMixGroupCriteria name="LoadMixGroupCriteria">LoadMixGroupCriteria</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadMixGroupCriteria attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstrainingProductGroupId name="ConstrainingProductGroupId">ConstrainingProductGroupId</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstrainingProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstrainingWarehouseFilterCode name="ConstrainingWarehouseFilterCode">ConstrainingWarehouseFilterCode</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstrainingWarehouseFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadMixGroupId name="LoadMixGroupId">LoadMixGroupId</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadMixGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadMixGroupCriterionProductGroupId name="LoadMixGroupCriterionProductGroupId">LoadMixGroupCriterionProductGroupId</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadMixGroupCriterionProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadMixGroupCriterionWarehouseFilterCode name="LoadMixGroupCriterionWarehouseFilterCode">LoadMixGroupCriterionWarehouseFilterCode</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadMixGroupCriterionWarehouseFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSLoadMixGroupConstraintRelationshipId name="BackingTable_WHSLoadMixGroupConstraintRelationshipId">BackingTable_WHSLoadMixGroupConstraintRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSLoadMixGroupConstraintRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLoadMixGroupConstraint.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLoadMixGroupConstraint.cdm.json/WHSLoadMixGroupConstraint</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLoadMixGroupConstraint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSLoadMixGroupConstraintEntity (this entity)  

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
