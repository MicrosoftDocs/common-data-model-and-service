---
title: LedgerAdvancedRuleStructureDraftOnlyEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Advanced rule structures - draft only in GeneralLedger(LedgerAdvancedRuleStructureDraftOnlyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advanced rule structures - draft only</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountRuleStructureName](#AccountRuleStructureName)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[Description](#Description)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[Status](#Status)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[StructureType](#StructureType)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName01](#SegmentName01)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName02](#SegmentName02)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName03](#SegmentName03)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName04](#SegmentName04)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName05](#SegmentName05)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName06](#SegmentName06)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName07](#SegmentName07)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName08](#SegmentName08)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName09](#SegmentName09)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName10](#SegmentName10)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[SegmentName11](#SegmentName11)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|
|[BackingTable_LedgerAdvancedRuleStructureEntityRelationshipId](#BackingTable_LedgerAdvancedRuleStructureEntityRelationshipId)||<a href="LedgerAdvancedRuleStructureDraftOnlyEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity</a>|

### <a href=#AccountRuleStructureName name="AccountRuleStructureName">AccountRuleStructureName</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRuleStructureName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

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

### <a href=#Status name="Status">Status</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StructureType name="StructureType">StructureType</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StructureType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName01 name="SegmentName01">SegmentName01</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName01 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName02 name="SegmentName02">SegmentName02</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName02 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName03 name="SegmentName03">SegmentName03</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName03 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName04 name="SegmentName04">SegmentName04</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName04 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName05 name="SegmentName05">SegmentName05</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName05 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName06 name="SegmentName06">SegmentName06</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName06 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName07 name="SegmentName07">SegmentName07</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName07 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName08 name="SegmentName08">SegmentName08</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName08 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName09 name="SegmentName09">SegmentName09</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName09 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName10 name="SegmentName10">SegmentName10</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName11 name="SegmentName11">SegmentName11</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerAdvancedRuleStructureEntityRelationshipId name="BackingTable_LedgerAdvancedRuleStructureEntityRelationshipId">BackingTable_LedgerAdvancedRuleStructureEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureDraftOnlyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerAdvancedRuleStructureEntityRelationshipId attribute are listed below.</summary>

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
