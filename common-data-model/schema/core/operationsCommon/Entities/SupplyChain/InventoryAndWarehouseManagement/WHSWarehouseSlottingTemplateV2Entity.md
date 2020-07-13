---
title: WHSWarehouseSlottingTemplateV2Entity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Slotting templates V2 in InventoryAndWarehouseManagement(WHSWarehouseSlottingTemplateV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Slotting templates V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarehouseId](#WarehouseId)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|
|[TemplateDescription](#TemplateDescription)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|
|[SlottingStrategy](#SlottingStrategy)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|
|[SlottingSource](#SlottingSource)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|
|[TemplateId](#TemplateId)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|
|[WillCreatedReplenishmentWorkAllowUsingUnreservedQuantities](#WillCreatedReplenishmentWorkAllowUsingUnreservedQuantities)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|
|[TemplateQuery](#TemplateQuery)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|
|[BackingTable_WHSSlotTemplateRelationshipId](#BackingTable_WHSSlotTemplateRelationshipId)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseSlottingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity</a>|

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateDescription name="TemplateDescription">TemplateDescription</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlottingStrategy name="SlottingStrategy">SlottingStrategy</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlottingStrategy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlottingSource name="SlottingSource">SlottingSource</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlottingSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCreatedReplenishmentWorkAllowUsingUnreservedQuantities name="WillCreatedReplenishmentWorkAllowUsingUnreservedQuantities">WillCreatedReplenishmentWorkAllowUsingUnreservedQuantities</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCreatedReplenishmentWorkAllowUsingUnreservedQuantities attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateQuery name="TemplateQuery">TemplateQuery</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSSlotTemplateRelationshipId name="BackingTable_WHSSlotTemplateRelationshipId">BackingTable_WHSSlotTemplateRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSSlotTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSSlotTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSSlotTemplate.cdm.json/WHSSlotTemplate</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSSlotTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateV2Entity (this entity)  

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
