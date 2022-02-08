---
title: LedgerAdvancedRuleStructureEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Advanced rule structures in GeneralLedger(LedgerAdvancedRuleStructureEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerAdvancedRuleStructureEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advanced rule structures</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountRuleStructureName](#AccountRuleStructureName)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Description](#Description)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Status](#Status)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[StructureType](#StructureType)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName01](#SegmentName01)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName02](#SegmentName02)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName03](#SegmentName03)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName04](#SegmentName04)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName05](#SegmentName05)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName06](#SegmentName06)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName07](#SegmentName07)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName08](#SegmentName08)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName09](#SegmentName09)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName10](#SegmentName10)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[SegmentName11](#SegmentName11)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName01RelationshipId](#Relationship_SegmentName01RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName02RelationshipId](#Relationship_SegmentName02RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName03RelationshipId](#Relationship_SegmentName03RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName04RelationshipId](#Relationship_SegmentName04RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName05RelationshipId](#Relationship_SegmentName05RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName06RelationshipId](#Relationship_SegmentName06RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName07RelationshipId](#Relationship_SegmentName07RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName08RelationshipId](#Relationship_SegmentName08RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName09RelationshipId](#Relationship_SegmentName09RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName10RelationshipId](#Relationship_SegmentName10RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[Relationship_SegmentName11RelationshipId](#Relationship_SegmentName11RelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|
|[BackingTable_DimensionHierarchyBaseEntityRelationshipId](#BackingTable_DimensionHierarchyBaseEntityRelationshipId)||<a href="LedgerAdvancedRuleStructureEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureEntity</a>|

### <a href=#AccountRuleStructureName name="AccountRuleStructureName">AccountRuleStructureName</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

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

### <a href=#Relationship_SegmentName01RelationshipId name="Relationship_SegmentName01RelationshipId">Relationship_SegmentName01RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName01RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName02RelationshipId name="Relationship_SegmentName02RelationshipId">Relationship_SegmentName02RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName02RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName03RelationshipId name="Relationship_SegmentName03RelationshipId">Relationship_SegmentName03RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName03RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName04RelationshipId name="Relationship_SegmentName04RelationshipId">Relationship_SegmentName04RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName04RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName05RelationshipId name="Relationship_SegmentName05RelationshipId">Relationship_SegmentName05RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName05RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName06RelationshipId name="Relationship_SegmentName06RelationshipId">Relationship_SegmentName06RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName06RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName07RelationshipId name="Relationship_SegmentName07RelationshipId">Relationship_SegmentName07RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName07RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName08RelationshipId name="Relationship_SegmentName08RelationshipId">Relationship_SegmentName08RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName08RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName09RelationshipId name="Relationship_SegmentName09RelationshipId">Relationship_SegmentName09RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName09RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName10RelationshipId name="Relationship_SegmentName10RelationshipId">Relationship_SegmentName10RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName10RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SegmentName11RelationshipId name="Relationship_SegmentName11RelationshipId">Relationship_SegmentName11RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SegmentName11RelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_DimensionHierarchyBaseEntityRelationshipId name="BackingTable_DimensionHierarchyBaseEntityRelationshipId">BackingTable_DimensionHierarchyBaseEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionHierarchyBaseEntityRelationshipId attribute are listed below.</summary>

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
