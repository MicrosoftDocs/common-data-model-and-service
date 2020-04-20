---
title: InventSiteGateEntryLine_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# InventSiteGateEntryLine_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventSiteGateEntryLine_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventSiteGateEntryLine_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[ChallanQty](#ChallanQty)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[Description](#Description)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[EntryId](#EntryId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[InventDimId](#InventDimId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[InventoryUnit](#InventoryUnit)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[InventSiteGateEntry](#InventSiteGateEntry)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[ItemId](#ItemId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[LineNum](#LineNum)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[MeasuredQty](#MeasuredQty)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[MeasuringInstrumentId](#MeasuringInstrumentId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[MeasuringRunningNumber](#MeasuringRunningNumber)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[OrderId](#OrderId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[OrderQty](#OrderQty)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[OutwardGateId](#OutwardGateId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[ReceiptShipmentNumber](#ReceiptShipmentNumber)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[RetrunableGatePassNumber](#RetrunableGatePassNumber)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[ReturnableGatePassStatus](#ReturnableGatePassStatus)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[SourceRecId](#SourceRecId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[SourceTableId](#SourceTableId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[TareQty](#TareQty)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[TareWeightUnit](#TareWeightUnit)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[UnitOfMeasurement](#UnitOfMeasurement)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[ChallanDate](#ChallanDate)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[ChallanNumber](#ChallanNumber)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[Relationship_InventSiteGateEntryRelationshipId](#Relationship_InventSiteGateEntryRelationshipId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventSiteGateEntryLine_IN.md" target="_blank">WorksheetLine/InventSiteGateEntryLine_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventSiteGateEntryLine_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChallanQty name="ChallanQty">ChallanQty</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryId name="EntryId">EntryId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryUnit name="InventoryUnit">InventoryUnit</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteGateEntry name="InventSiteGateEntry">InventSiteGateEntry</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteGateEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MeasuredQty name="MeasuredQty">MeasuredQty</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MeasuredQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MeasuringInstrumentId name="MeasuringInstrumentId">MeasuringInstrumentId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MeasuringInstrumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MeasuringRunningNumber name="MeasuringRunningNumber">MeasuringRunningNumber</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MeasuringRunningNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderId name="OrderId">OrderId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderQty name="OrderQty">OrderQty</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OutwardGateId name="OutwardGateId">OutwardGateId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutwardGateId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReceiptShipmentNumber name="ReceiptShipmentNumber">ReceiptShipmentNumber</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptShipmentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetrunableGatePassNumber name="RetrunableGatePassNumber">RetrunableGatePassNumber</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetrunableGatePassNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnableGatePassStatus name="ReturnableGatePassStatus">ReturnableGatePassStatus</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnableGatePassStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceRecId name="SourceRecId">SourceRecId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceTableId name="SourceTableId">SourceTableId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TareQty name="TareQty">TareQty</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TareQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TareWeightUnit name="TareWeightUnit">TareWeightUnit</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TareWeightUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasurement name="UnitOfMeasurement">UnitOfMeasurement</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChallanDate name="ChallanDate">ChallanDate</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ChallanNumber name="ChallanNumber">ChallanNumber</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteGateEntryRelationshipId name="Relationship_InventSiteGateEntryRelationshipId">Relationship_InventSiteGateEntryRelationshipId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSiteGateEntryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventSiteGateEntry_IN.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventSiteGateEntry_IN.cdm.json/InventSiteGateEntry_IN</a></td><td><a href="../WorksheetHeader/InventSiteGateEntry_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/InventSiteGateEntryLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
