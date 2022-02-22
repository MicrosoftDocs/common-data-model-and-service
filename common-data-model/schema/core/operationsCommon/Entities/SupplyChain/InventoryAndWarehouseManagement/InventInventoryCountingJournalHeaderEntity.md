---
title: InventInventoryCountingJournalHeaderEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Inventory counting journal headers in InventoryAndWarehouseManagement(InventInventoryCountingJournalHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory counting journal headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreLinesDeletedAfterPosting](#AreLinesDeletedAfterPosting)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[Description](#Description)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[PostingDetailLevel](#PostingDetailLevel)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[DefaultInventorySiteId](#DefaultInventorySiteId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[DefaultWarehouseId](#DefaultWarehouseId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[JournalNumber](#JournalNumber)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[JournalNameId](#JournalNameId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[IsPosted](#IsPosted)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[PostedDateTime](#PostedDateTime)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[PostedUserId](#PostedUserId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[ReservationMode](#ReservationMode)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[VoucherNumberSelectionRule](#VoucherNumberSelectionRule)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[VoucherNumberAllocationRule](#VoucherNumberAllocationRule)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[VoucherNumberSequenceRecId](#VoucherNumberSequenceRecId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[VoucherNumberSequenceCode](#VoucherNumberSequenceCode)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[WorkerRecId](#WorkerRecId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[WorkerPersonnelNumber](#WorkerPersonnelNumber)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[InventDimFixed](#InventDimFixed)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[IsCountingWarehouseSpecific](#IsCountingWarehouseSpecific)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[IsCountingInventoryStatusSpecific](#IsCountingInventoryStatusSpecific)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[IsCountingWarehouseLocationSpecific](#IsCountingWarehouseLocationSpecific)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[IsCountingLicensePlateSpecific](#IsCountingLicensePlateSpecific)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[IsCountingItemBatchSpecific](#IsCountingItemBatchSpecific)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[IsCountingItemSerialNumberSpecific](#IsCountingItemSerialNumberSpecific)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[CountingStatusRegistrationPolicy](#CountingStatusRegistrationPolicy)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[BackingTable_InventJournalTableRelationshipId](#BackingTable_InventJournalTableRelationshipId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryCountingJournalHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity</a>|

### <a href=#AreLinesDeletedAfterPosting name="AreLinesDeletedAfterPosting">AreLinesDeletedAfterPosting</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreLinesDeletedAfterPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

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

### <a href=#PostingDetailLevel name="PostingDetailLevel">PostingDetailLevel</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDetailLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventorySiteId name="DefaultInventorySiteId">DefaultInventorySiteId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultWarehouseId name="DefaultWarehouseId">DefaultWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPosted name="IsPosted">IsPosted</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedDateTime name="PostedDateTime">PostedDateTime</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedUserId name="PostedUserId">PostedUserId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationMode name="ReservationMode">ReservationMode</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumberSelectionRule name="VoucherNumberSelectionRule">VoucherNumberSelectionRule</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumberSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumberAllocationRule name="VoucherNumberAllocationRule">VoucherNumberAllocationRule</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumberAllocationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumberSequenceRecId name="VoucherNumberSequenceRecId">VoucherNumberSequenceRecId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumberSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumberSequenceCode name="VoucherNumberSequenceCode">VoucherNumberSequenceCode</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerRecId name="WorkerRecId">WorkerRecId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerPersonnelNumber name="WorkerPersonnelNumber">WorkerPersonnelNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimFixed name="InventDimFixed">InventDimFixed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimFixed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingWarehouseSpecific name="IsCountingWarehouseSpecific">IsCountingWarehouseSpecific</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingWarehouseSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingInventoryStatusSpecific name="IsCountingInventoryStatusSpecific">IsCountingInventoryStatusSpecific</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingInventoryStatusSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingWarehouseLocationSpecific name="IsCountingWarehouseLocationSpecific">IsCountingWarehouseLocationSpecific</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingWarehouseLocationSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingLicensePlateSpecific name="IsCountingLicensePlateSpecific">IsCountingLicensePlateSpecific</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingLicensePlateSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingItemBatchSpecific name="IsCountingItemBatchSpecific">IsCountingItemBatchSpecific</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingItemBatchSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingItemSerialNumberSpecific name="IsCountingItemSerialNumberSpecific">IsCountingItemSerialNumberSpecific</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingItemSerialNumberSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingStatusRegistrationPolicy name="CountingStatusRegistrationPolicy">CountingStatusRegistrationPolicy</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingStatusRegistrationPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventJournalTableRelationshipId name="BackingTable_InventJournalTableRelationshipId">BackingTable_InventJournalTableRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/InventJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventJournalTable.cdm.json/InventJournalTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/InventJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryCountingJournalHeaderEntity (this entity)  

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
