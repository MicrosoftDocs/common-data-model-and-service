---
title: WHSShipConsolidationPolicyV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Shipment consolidation policies V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipment consolidation policies V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ShipConsolidationPolicyName](#ShipConsolidationPolicyName)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|
|[ShipConsolidationPolicyType](#ShipConsolidationPolicyType)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|
|[ShipConsolidationPolicySeqNum](#ShipConsolidationPolicySeqNum)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|
|[ShipConsolidationPolicyQuery](#ShipConsolidationPolicyQuery)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|
|[ShipConsolidationPolicyDesc](#ShipConsolidationPolicyDesc)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|
|[Valid](#Valid)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|
|[ConsolidateWithExistingShipments](#ConsolidateWithExistingShipments)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|
|[BackingTable_WHSShipConsolidationPolicyRelationshipId](#BackingTable_WHSShipConsolidationPolicyRelationshipId)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSShipConsolidationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity</a>|

### <a href=#ShipConsolidationPolicyName name="ShipConsolidationPolicyName">ShipConsolidationPolicyName</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipConsolidationPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipConsolidationPolicyType name="ShipConsolidationPolicyType">ShipConsolidationPolicyType</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipConsolidationPolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipConsolidationPolicySeqNum name="ShipConsolidationPolicySeqNum">ShipConsolidationPolicySeqNum</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipConsolidationPolicySeqNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipConsolidationPolicyQuery name="ShipConsolidationPolicyQuery">ShipConsolidationPolicyQuery</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipConsolidationPolicyQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipConsolidationPolicyDesc name="ShipConsolidationPolicyDesc">ShipConsolidationPolicyDesc</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipConsolidationPolicyDesc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Valid name="Valid">Valid</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Valid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidateWithExistingShipments name="ConsolidateWithExistingShipments">ConsolidateWithExistingShipments</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidateWithExistingShipments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSShipConsolidationPolicyRelationshipId name="BackingTable_WHSShipConsolidationPolicyRelationshipId">BackingTable_WHSShipConsolidationPolicyRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSShipConsolidationPolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSShipConsolidationPolicy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSShipConsolidationPolicy.cdm.json/WHSShipConsolidationPolicy</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSShipConsolidationPolicy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSShipConsolidationPolicyV2Entity (this entity)  

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
