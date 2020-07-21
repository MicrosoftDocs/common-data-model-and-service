---
title: ConsignmentDraftReplenishmentOrderJournalLine in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Replenishment order lines - update table in WorksheetLine(ConsignmentDraftReplenishmentOrderJournalLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ConsignmentDraftReplenishmentOrderJournalLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Replenishment order lines - update table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Closed](#Closed)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[InventDimId](#InventDimId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ItemId](#ItemId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ReplenishmentOrderLineNumber](#ReplenishmentOrderLineNumber)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ParmId](#ParmId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ReceiveReplenishmentQuantityNow](#ReceiveReplenishmentQuantityNow)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[RemainingInventoryQuantityAfter](#RemainingInventoryQuantityAfter)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[RemainingReplenishmentQuantityAfter](#RemainingReplenishmentQuantityAfter)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ReplenishmentOrderLine](#ReplenishmentOrderLine)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ReplenishmentOrderNumber](#ReplenishmentOrderNumber)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ReplenishmentQuantity](#ReplenishmentQuantity)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ReceiveInventoryQuantityNow](#ReceiveInventoryQuantityNow)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[DocumentStatus](#DocumentStatus)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[ReplenishmentUnitId](#ReplenishmentUnitId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[InventTransId](#InventTransId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[PdsCountryOfOrigin1](#PdsCountryOfOrigin1)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[PdsCountryOfOrigin2](#PdsCountryOfOrigin2)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[PdsUseVendBatchDate](#PdsUseVendBatchDate)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[PdsUseVendBatchExp](#PdsUseVendBatchExp)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[PdsVendBatchDate](#PdsVendBatchDate)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[PdsVendBatchId](#PdsVendBatchId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[PdsVendExpiryDate](#PdsVendExpiryDate)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[DataAreaId](#DataAreaId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_ConsignmentDraftReplenishmentOrderJournalHeaderRelationshipId](#Relationship_ConsignmentDraftReplenishmentOrderJournalHeaderRelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_ConsignmentReplenishmentOrderHeaderRelationshipId](#Relationship_ConsignmentReplenishmentOrderHeaderRelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_ConsignmentReplenishmentOrderLineRelationshipId](#Relationship_ConsignmentReplenishmentOrderLineRelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_ItemRelationshipId](#Relationship_ItemRelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_InventoryDimensionRelationshipId](#Relationship_InventoryDimensionRelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_InventTransOriginRelationshipId](#Relationship_InventTransOriginRelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_PdsCountryOfOrigin1RelationshipId](#Relationship_PdsCountryOfOrigin1RelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_PdsCountryOfOrigin2RelationshipId](#Relationship_PdsCountryOfOrigin2RelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ConsignmentDraftReplenishmentOrderJournalLine.md" target="_blank">WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ConsignmentDraftReplenishmentOrderJournalLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Closed name="Closed">Closed</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Closed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentOrderLineNumber name="ReplenishmentOrderLineNumber">ReplenishmentOrderLineNumber</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOrderLineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ParmId name="ParmId">ParmId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiveReplenishmentQuantityNow name="ReceiveReplenishmentQuantityNow">ReceiveReplenishmentQuantityNow</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveReplenishmentQuantityNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainingInventoryQuantityAfter name="RemainingInventoryQuantityAfter">RemainingInventoryQuantityAfter</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingInventoryQuantityAfter attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainingReplenishmentQuantityAfter name="RemainingReplenishmentQuantityAfter">RemainingReplenishmentQuantityAfter</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingReplenishmentQuantityAfter attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReplenishmentOrderLine name="ReplenishmentOrderLine">ReplenishmentOrderLine</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOrderLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReplenishmentOrderNumber name="ReplenishmentOrderNumber">ReplenishmentOrderNumber</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentQuantity name="ReplenishmentQuantity">ReplenishmentQuantity</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReceiveInventoryQuantityNow name="ReceiveInventoryQuantityNow">ReceiveInventoryQuantityNow</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveInventoryQuantityNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DocumentStatus name="DocumentStatus">DocumentStatus</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReplenishmentUnitId name="ReplenishmentUnitId">ReplenishmentUnitId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsCountryOfOrigin1 name="PdsCountryOfOrigin1">PdsCountryOfOrigin1</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCountryOfOrigin1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsCountryOfOrigin2 name="PdsCountryOfOrigin2">PdsCountryOfOrigin2</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCountryOfOrigin2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsUseVendBatchDate name="PdsUseVendBatchDate">PdsUseVendBatchDate</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsUseVendBatchDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PdsUseVendBatchExp name="PdsUseVendBatchExp">PdsUseVendBatchExp</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsUseVendBatchExp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PdsVendBatchDate name="PdsVendBatchDate">PdsVendBatchDate</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsVendBatchDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PdsVendBatchId name="PdsVendBatchId">PdsVendBatchId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsVendBatchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsVendExpiryDate name="PdsVendExpiryDate">PdsVendExpiryDate</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsVendExpiryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

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

### <a href=#Relationship_ConsignmentDraftReplenishmentOrderJournalHeaderRelationshipId name="Relationship_ConsignmentDraftReplenishmentOrderJournalHeaderRelationshipId">Relationship_ConsignmentDraftReplenishmentOrderJournalHeaderRelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsignmentDraftReplenishmentOrderJournalHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ConsignmentDraftReplenishmentOrderJournalHeader.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/ConsignmentDraftReplenishmentOrderJournalHeader.cdm.json/ConsignmentDraftReplenishmentOrderJournalHeader</a></td><td><a href="../WorksheetHeader/ConsignmentDraftReplenishmentOrderJournalHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConsignmentReplenishmentOrderHeaderRelationshipId name="Relationship_ConsignmentReplenishmentOrderHeaderRelationshipId">Relationship_ConsignmentReplenishmentOrderHeaderRelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsignmentReplenishmentOrderHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ConsignmentReplenishmentOrderHeader.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/ConsignmentReplenishmentOrderHeader.cdm.json/ConsignmentReplenishmentOrderHeader</a></td><td><a href="../WorksheetHeader/ConsignmentReplenishmentOrderHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConsignmentReplenishmentOrderLineRelationshipId name="Relationship_ConsignmentReplenishmentOrderLineRelationshipId">Relationship_ConsignmentReplenishmentOrderLineRelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsignmentReplenishmentOrderLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ConsignmentReplenishmentOrderLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/ConsignmentReplenishmentOrderLine.cdm.json/ConsignmentReplenishmentOrderLine</a></td><td><a href="ConsignmentReplenishmentOrderLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemRelationshipId name="Relationship_ItemRelationshipId">Relationship_ItemRelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryDimensionRelationshipId name="Relationship_InventoryDimensionRelationshipId">Relationship_InventoryDimensionRelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../../Inventory/Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransOriginRelationshipId name="Relationship_InventTransOriginRelationshipId">Relationship_InventTransOriginRelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../../Inventory/Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsCountryOfOrigin1RelationshipId name="Relationship_PdsCountryOfOrigin1RelationshipId">Relationship_PdsCountryOfOrigin1RelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsCountryOfOrigin1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsCountryOfOrigin2RelationshipId name="Relationship_PdsCountryOfOrigin2RelationshipId">Relationship_PdsCountryOfOrigin2RelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsCountryOfOrigin2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/ConsignmentDraftReplenishmentOrderJournalLine (this entity)  

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
