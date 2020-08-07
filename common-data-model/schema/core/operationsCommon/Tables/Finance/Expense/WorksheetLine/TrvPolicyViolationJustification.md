---
title: TrvPolicyViolationJustification in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Policy violation justifications in WorksheetLine(TrvPolicyViolationJustification)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Expense/WorksheetLine/TrvPolicyViolationJustification.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TrvPolicyViolationJustification/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Policy violation justifications</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[JustificationId](#JustificationId)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[Action](#Action)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[Justification](#Justification)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[JustifyingWorker](#JustifyingWorker)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[ViolatingRecord](#ViolatingRecord)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[ViolationJustificationType](#ViolationJustificationType)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[Relationship_TrvExpTableRelationshipId](#Relationship_TrvExpTableRelationshipId)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[Relationship_TrvExpTransRelationshipId](#Relationship_TrvExpTransRelationshipId)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[Relationship_TrvRequisitionLineRelationshipId](#Relationship_TrvRequisitionLineRelationshipId)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|
|[Relationship_TrvRequisitionTableRelationshipId](#Relationship_TrvRequisitionTableRelationshipId)||<a href="TrvPolicyViolationJustification.md" target="_blank">WorksheetLine/TrvPolicyViolationJustification</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TrvPolicyViolationJustification/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JustificationId name="JustificationId">JustificationId</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JustificationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Action name="Action">Action</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Action attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Justification name="Justification">Justification</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Justification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JustifyingWorker name="JustifyingWorker">JustifyingWorker</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JustifyingWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ViolatingRecord name="ViolatingRecord">ViolatingRecord</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViolatingRecord attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ViolationJustificationType name="ViolationJustificationType">ViolationJustificationType</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The type of record that this justification belongs to</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViolationJustificationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of record that this justification belongs to</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_TrvExpTableRelationshipId name="Relationship_TrvExpTableRelationshipId">Relationship_TrvExpTableRelationshipId</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrvExpTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/TrvExpTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/WorksheetHeader/TrvExpTable.cdm.json/TrvExpTable</a></td><td><a href="../WorksheetHeader/TrvExpTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TrvExpTransRelationshipId name="Relationship_TrvExpTransRelationshipId">Relationship_TrvExpTransRelationshipId</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrvExpTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TrvExpTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Transaction/TrvExpTrans.cdm.json/TrvExpTrans</a></td><td><a href="../Transaction/TrvExpTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TrvRequisitionLineRelationshipId name="Relationship_TrvRequisitionLineRelationshipId">Relationship_TrvRequisitionLineRelationshipId</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrvRequisitionLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TrvRequisitionLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Transaction/TrvRequisitionLine.cdm.json/TrvRequisitionLine</a></td><td><a href="../Transaction/TrvRequisitionLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TrvRequisitionTableRelationshipId name="Relationship_TrvRequisitionTableRelationshipId">Relationship_TrvRequisitionTableRelationshipId</a>

First included in: WorksheetLine/TrvPolicyViolationJustification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrvRequisitionTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TrvRequisitionTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Transaction/TrvRequisitionTable.cdm.json/TrvRequisitionTable</a></td><td><a href="../Transaction/TrvRequisitionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
