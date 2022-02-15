---
title: WHSWarehouseLocationDirectiveLineEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Warehouse location directive lines in WMS(WHSWarehouseLocationDirectiveLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseLocationDirectiveLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse location directive lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarehouseLocationDirectiveWorkOrderType](#WarehouseLocationDirectiveWorkOrderType)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[WarehouseLocationDirectiveId](#WarehouseLocationDirectiveId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[WarehouseLocationDirectiveWorkType](#WarehouseLocationDirectiveWorkType)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[WarehouseLocationDirectiveInventorySiteId](#WarehouseLocationDirectiveInventorySiteId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[WarehouseLocationDirectiveWarehouseId](#WarehouseLocationDirectiveWarehouseId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[MinimumWarehouseWorkOrderLineQuantity](#MinimumWarehouseWorkOrderLineQuantity)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[MaximumWarehouseWorkOrderLineQuantity](#MaximumWarehouseWorkOrderLineQuantity)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[WarehouseWorkOrderLineQuantityUnitSymbol](#WarehouseWorkOrderLineQuantityUnitSymbol)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[LocateQuantityMethod](#LocateQuantityMethod)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[IsUnitOfMeasureRestrictionEnabled](#IsUnitOfMeasureRestrictionEnabled)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[IsPackingQuantityLocated](#IsPackingQuantityLocated)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[IsWarehouseWorkOrderLineSplittingAllowed](#IsWarehouseWorkOrderLineSplittingAllowed)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[RefRecId](#RefRecId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[WillRestrictingUnitQuantityCalculationRoundUp](#WillRestrictingUnitQuantityCalculationRoundUp)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[ImmediateWarehouseReplenishmentTemplateId](#ImmediateWarehouseReplenishmentTemplateId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[Relationship_WarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId](#Relationship_WarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[Relationship_ImmediateWarehouseReplenishmentTemplateRelationshipId](#Relationship_ImmediateWarehouseReplenishmentTemplateRelationshipId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[BackingTable_WHSLocDirLineRelationshipId](#BackingTable_WHSLocDirLineRelationshipId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseLocationDirectiveLineEntity.md" target="_blank">WMS/WHSWarehouseLocationDirectiveLineEntity</a>|

### <a href=#WarehouseLocationDirectiveWorkOrderType name="WarehouseLocationDirectiveWorkOrderType">WarehouseLocationDirectiveWorkOrderType</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

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

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

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

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

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

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

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

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

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

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

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

### <a href=#MinimumWarehouseWorkOrderLineQuantity name="MinimumWarehouseWorkOrderLineQuantity">MinimumWarehouseWorkOrderLineQuantity</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumWarehouseWorkOrderLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderLineQuantity name="MaximumWarehouseWorkOrderLineQuantity">MaximumWarehouseWorkOrderLineQuantity</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkOrderLineQuantityUnitSymbol name="WarehouseWorkOrderLineQuantityUnitSymbol">WarehouseWorkOrderLineQuantityUnitSymbol</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkOrderLineQuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocateQuantityMethod name="LocateQuantityMethod">LocateQuantityMethod</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocateQuantityMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsUnitOfMeasureRestrictionEnabled name="IsUnitOfMeasureRestrictionEnabled">IsUnitOfMeasureRestrictionEnabled</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUnitOfMeasureRestrictionEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPackingQuantityLocated name="IsPackingQuantityLocated">IsPackingQuantityLocated</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPackingQuantityLocated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseWorkOrderLineSplittingAllowed name="IsWarehouseWorkOrderLineSplittingAllowed">IsWarehouseWorkOrderLineSplittingAllowed</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseWorkOrderLineSplittingAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRestrictingUnitQuantityCalculationRoundUp name="WillRestrictingUnitQuantityCalculationRoundUp">WillRestrictingUnitQuantityCalculationRoundUp</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRestrictingUnitQuantityCalculationRoundUp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImmediateWarehouseReplenishmentTemplateId name="ImmediateWarehouseReplenishmentTemplateId">ImmediateWarehouseReplenishmentTemplateId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImmediateWarehouseReplenishmentTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId name="Relationship_WarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId">Relationship_WarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ImmediateWarehouseReplenishmentTemplateRelationshipId name="Relationship_ImmediateWarehouseReplenishmentTemplateRelationshipId">Relationship_ImmediateWarehouseReplenishmentTemplateRelationshipId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ImmediateWarehouseReplenishmentTemplateRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSLocDirLineRelationshipId name="BackingTable_WHSLocDirLineRelationshipId">BackingTable_WHSLocDirLineRelationshipId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSLocDirLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLocDirLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLocDirLine.cdm.json/WHSLocDirLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLocDirLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseLocationDirectiveLineEntity (this entity)  

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
