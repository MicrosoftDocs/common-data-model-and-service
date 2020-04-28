---
title: HcmTotalCompStatementSectionEarningEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# The earning codes of the Total compensation statement section

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmTotalCompStatementSectionEarningEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The earning codes of the Total compensation statement section</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[EarningCode](#EarningCode)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[EarningCodeOrGroupType](#EarningCodeOrGroupType)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[EarningCodeGroup](#EarningCodeGroup)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[TotalCompensationStatementSection](#TotalCompensationStatementSection)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[StatementSectionId](#StatementSectionId)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[EarningCodeId](#EarningCodeId)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[NullableEarningCodeId](#NullableEarningCodeId)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[EarningCodeGroupId](#EarningCodeGroupId)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[NullableEarningCodeGroupId](#NullableEarningCodeGroupId)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId](#Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|
|[Relationship_PayrollEarningCodeGroupEntityRelationshipId](#Relationship_PayrollEarningCodeGroupEntityRelationshipId)||<a href="HcmTotalCompStatementSectionEarningEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionEarningEntity</a>|

### <a href=#EarningCode name="EarningCode">EarningCode</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCodeOrGroupType name="EarningCodeOrGroupType">EarningCodeOrGroupType</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCodeOrGroupType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCodeGroup name="EarningCodeGroup">EarningCodeGroup</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCodeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalCompensationStatementSection name="TotalCompensationStatementSection">TotalCompensationStatementSection</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCompensationStatementSection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementSectionId name="StatementSectionId">StatementSectionId</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementSectionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCodeId name="EarningCodeId">EarningCodeId</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NullableEarningCodeId name="NullableEarningCodeId">NullableEarningCodeId</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NullableEarningCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCodeGroupId name="EarningCodeGroupId">EarningCodeGroupId</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCodeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NullableEarningCodeGroupId name="NullableEarningCodeGroupId">NullableEarningCodeGroupId</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NullableEarningCodeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId name="Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId">Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PayrollEarningCodeGroupEntityRelationshipId name="Relationship_PayrollEarningCodeGroupEntityRelationshipId">Relationship_PayrollEarningCodeGroupEntityRelationshipId</a>

First included in: HRM/HcmTotalCompStatementSectionEarningEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollEarningCodeGroupEntityRelationshipId attribute are listed below.</summary>

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
