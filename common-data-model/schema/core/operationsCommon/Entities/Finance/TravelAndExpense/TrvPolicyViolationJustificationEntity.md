---
title: TrvPolicyViolationJustificationEntity in TravelAndExpense - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Policy violation justifications in TravelAndExpense(TrvPolicyViolationJustificationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/TravelAndExpense/TrvPolicyViolationJustificationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

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
|[JustificationId](#JustificationId)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|
|[Action](#Action)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|
|[JustificationText](#JustificationText)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|
|[JustifyingWorker](#JustifyingWorker)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|
|[ViolatingRecord](#ViolatingRecord)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|
|[ViolatingRecordId](#ViolatingRecordId)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|
|[ViolationJustificationType](#ViolationJustificationType)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|
|[BackingTable_TrvPolicyViolationJustificationRelationshipId](#BackingTable_TrvPolicyViolationJustificationRelationshipId)||<a href="TrvPolicyViolationJustificationEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationJustificationEntity</a>|

### <a href=#JustificationId name="JustificationId">JustificationId</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JustificationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Action name="Action">Action</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Action attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JustificationText name="JustificationText">JustificationText</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JustificationText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JustifyingWorker name="JustifyingWorker">JustifyingWorker</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JustifyingWorker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ViolatingRecord name="ViolatingRecord">ViolatingRecord</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViolatingRecord attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ViolatingRecordId name="ViolatingRecordId">ViolatingRecordId</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Violating record</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViolatingRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Violating record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ViolationJustificationType name="ViolationJustificationType">ViolationJustificationType</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViolationJustificationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TrvPolicyViolationJustificationRelationshipId name="BackingTable_TrvPolicyViolationJustificationRelationshipId">BackingTable_TrvPolicyViolationJustificationRelationshipId</a>

First included in: TravelAndExpense/TrvPolicyViolationJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TrvPolicyViolationJustificationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Expense/WorksheetLine/TrvPolicyViolationJustification.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/WorksheetLine/TrvPolicyViolationJustification.cdm.json/TrvPolicyViolationJustification</a></td><td><a href="../../../Tables/Finance/Expense/WorksheetLine/TrvPolicyViolationJustification.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
