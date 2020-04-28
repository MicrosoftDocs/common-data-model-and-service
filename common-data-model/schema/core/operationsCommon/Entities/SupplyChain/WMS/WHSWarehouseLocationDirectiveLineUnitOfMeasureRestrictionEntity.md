---
title: WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Warehouse location directive line unit of measure restrictions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse location directive line unit of measure restrictions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarehouseLocationDirectiveWorkOrderType](#WarehouseLocationDirectiveWorkOrderType)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[WarehouseLocationDirectiveId](#WarehouseLocationDirectiveId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[WarehouseLocationDirectiveWorkType](#WarehouseLocationDirectiveWorkType)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[WarehouseLocationDirectiveInventorySiteId](#WarehouseLocationDirectiveInventorySiteId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[WarehouseLocationDirectiveWarehouseId](#WarehouseLocationDirectiveWarehouseId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[WarehouseLocationDirectiveLineSequenceNumber](#WarehouseLocationDirectiveLineSequenceNumber)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[UnitSymbol](#UnitSymbol)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[RefRecId](#RefRecId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[WHSLocDirLine_RefRecId](#WHSLocDirLine_RefRecId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[LocSeqNum](#LocSeqNum)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[Relationship_UnitOfMeasureRelationshipId](#Relationship_UnitOfMeasureRelationshipId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[Relationship_WarehouseLocationDirectiveLineRelationshipId](#Relationship_WarehouseLocationDirectiveLineRelationshipId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[BackingTable_WHSLocDirLineUOMRelationshipId](#BackingTable_WHSLocDirLineUOMRelationshipId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity</a>|

### <a href=#WarehouseLocationDirectiveWorkOrderType name="WarehouseLocationDirectiveWorkOrderType">WarehouseLocationDirectiveWorkOrderType</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveWorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveId name="WarehouseLocationDirectiveId">WarehouseLocationDirectiveId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveWorkType name="WarehouseLocationDirectiveWorkType">WarehouseLocationDirectiveWorkType</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveWorkType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveInventorySiteId name="WarehouseLocationDirectiveInventorySiteId">WarehouseLocationDirectiveInventorySiteId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveInventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveWarehouseId name="WarehouseLocationDirectiveWarehouseId">WarehouseLocationDirectiveWarehouseId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveLineSequenceNumber name="WarehouseLocationDirectiveLineSequenceNumber">WarehouseLocationDirectiveLineSequenceNumber</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveLineSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitSymbol name="UnitSymbol">UnitSymbol</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

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

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WHSLocDirLine_RefRecId name="WHSLocDirLine_RefRecId">WHSLocDirLine_RefRecId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WHSLocDirLine_RefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocSeqNum name="LocSeqNum">LocSeqNum</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocSeqNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnitOfMeasureRelationshipId name="Relationship_UnitOfMeasureRelationshipId">Relationship_UnitOfMeasureRelationshipId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseLocationDirectiveLineRelationshipId name="Relationship_WarehouseLocationDirectiveLineRelationshipId">Relationship_WarehouseLocationDirectiveLineRelationshipId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseLocationDirectiveLineRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSLocDirLineUOMRelationshipId name="BackingTable_WHSLocDirLineUOMRelationshipId">BackingTable_WHSLocDirLineUOMRelationshipId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSLocDirLineUOMRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLocDirLineUOM.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLocDirLineUOM.cdm.json/WHSLocDirLineUOM</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLocDirLineUOM.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineUnitOfMeasureRestrictionEntity (this entity)  

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
