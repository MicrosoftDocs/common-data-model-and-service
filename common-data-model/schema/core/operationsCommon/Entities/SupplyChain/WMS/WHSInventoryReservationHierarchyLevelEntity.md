---
title: WHSInventoryReservationHierarchyLevelEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Reservation hierarchy levels in WMS(WHSInventoryReservationHierarchyLevelEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSInventoryReservationHierarchyLevelEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reservation hierarchy levels</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InventoryDimensionFieldId](#InventoryDimensionFieldId)||<a href="WHSInventoryReservationHierarchyLevelEntity.md" target="_blank">WMS/WHSInventoryReservationHierarchyLevelEntity</a>|
|[InventoryDimensionFieldName](#InventoryDimensionFieldName)||<a href="WHSInventoryReservationHierarchyLevelEntity.md" target="_blank">WMS/WHSInventoryReservationHierarchyLevelEntity</a>|
|[InventoryReservationHierarchyRefRecId](#InventoryReservationHierarchyRefRecId)||<a href="WHSInventoryReservationHierarchyLevelEntity.md" target="_blank">WMS/WHSInventoryReservationHierarchyLevelEntity</a>|
|[InventoryReservationHierarchyLevel](#InventoryReservationHierarchyLevel)||<a href="WHSInventoryReservationHierarchyLevelEntity.md" target="_blank">WMS/WHSInventoryReservationHierarchyLevelEntity</a>|
|[InventoryReservationHierarchyName](#InventoryReservationHierarchyName)||<a href="WHSInventoryReservationHierarchyLevelEntity.md" target="_blank">WMS/WHSInventoryReservationHierarchyLevelEntity</a>|
|[DemandOrderReservationPolicy](#DemandOrderReservationPolicy)||<a href="WHSInventoryReservationHierarchyLevelEntity.md" target="_blank">WMS/WHSInventoryReservationHierarchyLevelEntity</a>|
|[Relationship_InventoryReservationHierarchyRelationshipId](#Relationship_InventoryReservationHierarchyRelationshipId)||<a href="WHSInventoryReservationHierarchyLevelEntity.md" target="_blank">WMS/WHSInventoryReservationHierarchyLevelEntity</a>|
|[BackingTable_WHSReservationHierarchyElementRelationshipId](#BackingTable_WHSReservationHierarchyElementRelationshipId)||<a href="WHSInventoryReservationHierarchyLevelEntity.md" target="_blank">WMS/WHSInventoryReservationHierarchyLevelEntity</a>|

### <a href=#InventoryDimensionFieldId name="InventoryDimensionFieldId">InventoryDimensionFieldId</a>

First included in: WMS/WHSInventoryReservationHierarchyLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryDimensionFieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryDimensionFieldName name="InventoryDimensionFieldName">InventoryDimensionFieldName</a>

First included in: WMS/WHSInventoryReservationHierarchyLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryDimensionFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryReservationHierarchyRefRecId name="InventoryReservationHierarchyRefRecId">InventoryReservationHierarchyRefRecId</a>

First included in: WMS/WHSInventoryReservationHierarchyLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryReservationHierarchyRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryReservationHierarchyLevel name="InventoryReservationHierarchyLevel">InventoryReservationHierarchyLevel</a>

First included in: WMS/WHSInventoryReservationHierarchyLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryReservationHierarchyLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryReservationHierarchyName name="InventoryReservationHierarchyName">InventoryReservationHierarchyName</a>

First included in: WMS/WHSInventoryReservationHierarchyLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryReservationHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandOrderReservationPolicy name="DemandOrderReservationPolicy">DemandOrderReservationPolicy</a>

First included in: WMS/WHSInventoryReservationHierarchyLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandOrderReservationPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventoryReservationHierarchyRelationshipId name="Relationship_InventoryReservationHierarchyRelationshipId">Relationship_InventoryReservationHierarchyRelationshipId</a>

First included in: WMS/WHSInventoryReservationHierarchyLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryReservationHierarchyRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSReservationHierarchyElementRelationshipId name="BackingTable_WHSReservationHierarchyElementRelationshipId">BackingTable_WHSReservationHierarchyElementRelationshipId</a>

First included in: WMS/WHSInventoryReservationHierarchyLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSReservationHierarchyElementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSReservationHierarchyElement.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSReservationHierarchyElement.cdm.json/WHSReservationHierarchyElement</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSReservationHierarchyElement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
