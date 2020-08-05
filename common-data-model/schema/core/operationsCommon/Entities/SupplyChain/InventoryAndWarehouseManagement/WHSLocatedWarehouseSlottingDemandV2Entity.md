---
title: WHSLocatedWarehouseSlottingDemandV2Entity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Slot demand located V2 in InventoryAndWarehouseManagement(WHSLocatedWarehouseSlottingDemandV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Slot demand located V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillDemandCreateLetUpWork](#WillDemandCreateLetUpWork)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[WillDemandUseOverflowLocation](#WillDemandUseOverflowLocation)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[SlotTemplateLine](#SlotTemplateLine)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[SlotTemplate](#SlotTemplate)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ProductName](#ProductName)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[WarehouseId](#WarehouseId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[LocatedUnitSymbol](#LocatedUnitSymbol)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[WarehouseLocationId](#WarehouseLocationId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[LocatedQuantity](#LocatedQuantity)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[WarehouseSlottingTemplateDetailsSequenceNumber](#WarehouseSlottingTemplateDetailsSequenceNumber)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[WarehouseSlottingTemplateId](#WarehouseSlottingTemplateId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[DemandSiteId](#DemandSiteId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[InventoryStatus](#InventoryStatus)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[BackingTable_WHSSlotDemandLocatedRelationshipId](#BackingTable_WHSSlotDemandLocatedRelationshipId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSLocatedWarehouseSlottingDemandV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity</a>|

### <a href=#WillDemandCreateLetUpWork name="WillDemandCreateLetUpWork">WillDemandCreateLetUpWork</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDemandCreateLetUpWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDemandUseOverflowLocation name="WillDemandUseOverflowLocation">WillDemandUseOverflowLocation</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDemandUseOverflowLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlotTemplateLine name="SlotTemplateLine">SlotTemplateLine</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlotTemplateLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlotTemplate name="SlotTemplate">SlotTemplate</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlotTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

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

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

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

### <a href=#LocatedUnitSymbol name="LocatedUnitSymbol">LocatedUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocatedUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationId name="WarehouseLocationId">WarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocatedQuantity name="LocatedQuantity">LocatedQuantity</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocatedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseSlottingTemplateDetailsSequenceNumber name="WarehouseSlottingTemplateDetailsSequenceNumber">WarehouseSlottingTemplateDetailsSequenceNumber</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseSlottingTemplateDetailsSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseSlottingTemplateId name="WarehouseSlottingTemplateId">WarehouseSlottingTemplateId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseSlottingTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

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

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

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

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

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

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSiteId name="DemandSiteId">DemandSiteId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatus name="InventoryStatus">InventoryStatus</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSSlotDemandLocatedRelationshipId name="BackingTable_WHSSlotDemandLocatedRelationshipId">BackingTable_WHSSlotDemandLocatedRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSSlotDemandLocatedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/WHSSlotDemandLocated.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSSlotDemandLocated.cdm.json/WHSSlotDemandLocated</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/WHSSlotDemandLocated.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSLocatedWarehouseSlottingDemandV2Entity (this entity)  

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
