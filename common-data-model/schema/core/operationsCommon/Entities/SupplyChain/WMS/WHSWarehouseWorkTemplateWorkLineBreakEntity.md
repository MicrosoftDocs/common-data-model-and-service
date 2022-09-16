---
title: WHSWarehouseWorkTemplateWorkLineBreakEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Warehouse work template work line breaks in WMS(WHSWarehouseWorkTemplateWorkLineBreakEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse work template work line breaks</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarehouseWorkTemplateId](#WarehouseWorkTemplateId)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|
|[WarehouseWorkTemplateWorkOrderType](#WarehouseWorkTemplateWorkOrderType)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|
|[WarehouseWorkTemplateLineRecordId](#WarehouseWorkTemplateLineRecordId)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|
|[WarehouseWorkTemplateLineNumber](#WarehouseWorkTemplateLineNumber)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|
|[WorkLineBreakSequenceNumber](#WorkLineBreakSequenceNumber)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|
|[WorkTemplateWorkLineBreakTableField](#WorkTemplateWorkLineBreakTableField)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|
|[Relationship_WarehouseWorkTemplateLineRelationshipId](#Relationship_WarehouseWorkTemplateLineRelationshipId)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|
|[BackingTable_WHSWorkTemplateLineGroupRelationshipId](#BackingTable_WHSWorkTemplateLineGroupRelationshipId)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWorkTemplateWorkLineBreakEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity</a>|

### <a href=#WarehouseWorkTemplateId name="WarehouseWorkTemplateId">WarehouseWorkTemplateId</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkTemplateWorkOrderType name="WarehouseWorkTemplateWorkOrderType">WarehouseWorkTemplateWorkOrderType</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateWorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkTemplateLineRecordId name="WarehouseWorkTemplateLineRecordId">WarehouseWorkTemplateLineRecordId</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateLineRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkTemplateLineNumber name="WarehouseWorkTemplateLineNumber">WarehouseWorkTemplateLineNumber</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkLineBreakSequenceNumber name="WorkLineBreakSequenceNumber">WorkLineBreakSequenceNumber</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkLineBreakSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkTemplateWorkLineBreakTableField name="WorkTemplateWorkLineBreakTableField">WorkTemplateWorkLineBreakTableField</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkTemplateWorkLineBreakTableField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseWorkTemplateLineRelationshipId name="Relationship_WarehouseWorkTemplateLineRelationshipId">Relationship_WarehouseWorkTemplateLineRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseWorkTemplateLineRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSWorkTemplateLineGroupRelationshipId name="BackingTable_WHSWorkTemplateLineGroupRelationshipId">BackingTable_WHSWorkTemplateLineGroupRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkTemplateLineGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkTemplateLineGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkTemplateLineGroup.cdm.json/WHSWorkTemplateLineGroup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkTemplateLineGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateWorkLineBreakEntity (this entity)  

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
