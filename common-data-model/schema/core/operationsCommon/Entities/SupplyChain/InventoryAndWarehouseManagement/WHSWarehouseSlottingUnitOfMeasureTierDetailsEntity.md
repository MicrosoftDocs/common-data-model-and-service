---
title: WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Slotting unit of measure tier details

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Slotting unit of measure tier details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[UnitSymbol](#UnitSymbol)||<a href="WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity</a>|
|[SlotUOMTier](#SlotUOMTier)||<a href="WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity</a>|
|[WarehouseSlottingUnitTierId](#WarehouseSlottingUnitTierId)||<a href="WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity</a>|
|[BackingTable_WHSSlotUOMTierLineRelationshipId](#BackingTable_WHSSlotUOMTierLineRelationshipId)||<a href="WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity</a>|

### <a href=#UnitSymbol name="UnitSymbol">UnitSymbol</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlotUOMTier name="SlotUOMTier">SlotUOMTier</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlotUOMTier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseSlottingUnitTierId name="WarehouseSlottingUnitTierId">WarehouseSlottingUnitTierId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseSlottingUnitTierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSSlotUOMTierLineRelationshipId name="BackingTable_WHSSlotUOMTierLineRelationshipId">BackingTable_WHSSlotUOMTierLineRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSSlotUOMTierLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSSlotUOMTierLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSSlotUOMTierLine.cdm.json/WHSSlotUOMTierLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSSlotUOMTierLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingUnitOfMeasureTierDetailsEntity (this entity)  

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
