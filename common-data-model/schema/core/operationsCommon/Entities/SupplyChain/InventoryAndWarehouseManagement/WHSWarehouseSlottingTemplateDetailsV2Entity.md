---
title: WHSWarehouseSlottingTemplateDetailsV2Entity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Lines for slotting templates V2 in InventoryAndWarehouseManagement(WHSWarehouseSlottingTemplateDetailsV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lines for slotting templates V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SlotCriteriaAssignmentRule](#SlotCriteriaAssignmentRule)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[IsLetUpWorkCreationAllowed](#IsLetUpWorkCreationAllowed)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[DetailsDescription](#DetailsDescription)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[MaximumSlottingQuantity](#MaximumSlottingQuantity)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[MinimumSlottingQuantity](#MinimumSlottingQuantity)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[OverflowLocation](#OverflowLocation)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[SlotTemplate](#SlotTemplate)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[WarehouseSlottingUnitTierId](#WarehouseSlottingUnitTierId)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[TemplateDetailsQuery](#TemplateDetailsQuery)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[SlottingUnitSymbol](#SlottingUnitSymbol)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[WarehouseLocationDirectiveCode](#WarehouseLocationDirectiveCode)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[FixedLocationUsageMethod](#FixedLocationUsageMethod)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[WarehouseSlottingTemplateId](#WarehouseSlottingTemplateId)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[OverflowWarehouseId](#OverflowWarehouseId)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[OverflowWarehouseLocationId](#OverflowWarehouseLocationId)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[BackingTable_WHSSlotTemplateLineRelationshipId](#BackingTable_WHSSlotTemplateLineRelationshipId)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseSlottingTemplateDetailsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity</a>|

### <a href=#SlotCriteriaAssignmentRule name="SlotCriteriaAssignmentRule">SlotCriteriaAssignmentRule</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlotCriteriaAssignmentRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLetUpWorkCreationAllowed name="IsLetUpWorkCreationAllowed">IsLetUpWorkCreationAllowed</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLetUpWorkCreationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DetailsDescription name="DetailsDescription">DetailsDescription</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DetailsDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumSlottingQuantity name="MaximumSlottingQuantity">MaximumSlottingQuantity</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumSlottingQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumSlottingQuantity name="MinimumSlottingQuantity">MinimumSlottingQuantity</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumSlottingQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverflowLocation name="OverflowLocation">OverflowLocation</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverflowLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlotTemplate name="SlotTemplate">SlotTemplate</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

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

### <a href=#WarehouseSlottingUnitTierId name="WarehouseSlottingUnitTierId">WarehouseSlottingUnitTierId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseSlottingUnitTierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateDetailsQuery name="TemplateDetailsQuery">TemplateDetailsQuery</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateDetailsQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlottingUnitSymbol name="SlottingUnitSymbol">SlottingUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlottingUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveCode name="WarehouseLocationDirectiveCode">WarehouseLocationDirectiveCode</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedLocationUsageMethod name="FixedLocationUsageMethod">FixedLocationUsageMethod</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedLocationUsageMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseSlottingTemplateId name="WarehouseSlottingTemplateId">WarehouseSlottingTemplateId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

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

### <a href=#OverflowWarehouseId name="OverflowWarehouseId">OverflowWarehouseId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverflowWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverflowWarehouseLocationId name="OverflowWarehouseLocationId">OverflowWarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverflowWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSSlotTemplateLineRelationshipId name="BackingTable_WHSSlotTemplateLineRelationshipId">BackingTable_WHSSlotTemplateLineRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSSlotTemplateLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSSlotTemplateLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSSlotTemplateLine.cdm.json/WHSSlotTemplateLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSSlotTemplateLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseSlottingTemplateDetailsV2Entity (this entity)  

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
