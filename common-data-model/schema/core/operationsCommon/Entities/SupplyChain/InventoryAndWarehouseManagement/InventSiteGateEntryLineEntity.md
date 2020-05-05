---
title: InventSiteGateEntryLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Gate entry line

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Gate entry line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChallanQty](#ChallanQty)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[Description](#Description)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[InventoryUnit](#InventoryUnit)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[InventSiteGateEntry](#InventSiteGateEntry)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[LineNum](#LineNum)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[MeasuredQty](#MeasuredQty)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[MeasuringInstrumentId](#MeasuringInstrumentId)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[MeasuringRunningNumber](#MeasuringRunningNumber)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[TareQty](#TareQty)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[TareWeightUnit](#TareWeightUnit)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[UnitOfMeasurement](#UnitOfMeasurement)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[GateEntry](#GateEntry)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[ChallanDate](#ChallanDate)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[ChallanNumber](#ChallanNumber)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[BackingTable_InventSiteGateEntryLine_INRelationshipId](#BackingTable_InventSiteGateEntryLine_INRelationshipId)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventSiteGateEntryLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity</a>|

### <a href=#ChallanQty name="ChallanQty">ChallanQty</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryUnit name="InventoryUnit">InventoryUnit</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteGateEntry name="InventSiteGateEntry">InventSiteGateEntry</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteGateEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

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

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MeasuredQty name="MeasuredQty">MeasuredQty</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MeasuredQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MeasuringInstrumentId name="MeasuringInstrumentId">MeasuringInstrumentId</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MeasuringInstrumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MeasuringRunningNumber name="MeasuringRunningNumber">MeasuringRunningNumber</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MeasuringRunningNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TareQty name="TareQty">TareQty</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TareQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TareWeightUnit name="TareWeightUnit">TareWeightUnit</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TareWeightUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasurement name="UnitOfMeasurement">UnitOfMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GateEntry name="GateEntry">GateEntry</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GateEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChallanDate name="ChallanDate">ChallanDate</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChallanNumber name="ChallanNumber">ChallanNumber</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventSiteGateEntryLine_INRelationshipId name="BackingTable_InventSiteGateEntryLine_INRelationshipId">BackingTable_InventSiteGateEntryLine_INRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventSiteGateEntryLine_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventSiteGateEntryLine_IN.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventSiteGateEntryLine_IN.cdm.json/InventSiteGateEntryLine_IN</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventSiteGateEntryLine_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryLineEntity (this entity)  

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
