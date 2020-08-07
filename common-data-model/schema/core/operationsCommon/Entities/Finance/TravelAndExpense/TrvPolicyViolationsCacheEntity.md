---
title: TrvPolicyViolationsCacheEntity in TravelAndExpense - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Cache table for policy violations on an expense line in TravelAndExpense(TrvPolicyViolationsCacheEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/TravelAndExpense/TrvPolicyViolationsCacheEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cache table for policy violations on an expense line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ViolationsCacheId](#ViolationsCacheId)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[Header](#Header)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[HeaderId](#HeaderId)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[HeaderLegalEntity](#HeaderLegalEntity)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[Line](#Line)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[LineId](#LineId)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[ParentRecId](#ParentRecId)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[ParentId](#ParentId)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PolicyType](#PolicyType)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PolicyViolationLevel](#PolicyViolationLevel)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[Rule](#Rule)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[Policy](#Policy)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PolicyName](#PolicyName)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PolicyPolicyType](#PolicyPolicyType)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PolicyRuleTypeName](#PolicyRuleTypeName)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PolicyRuleTypePolicyType](#PolicyRuleTypePolicyType)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PolicyRuleValidFrom](#PolicyRuleValidFrom)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[SaveDateTime](#SaveDateTime)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[ViolationDate](#ViolationDate)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[Worker](#Worker)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|
|[BackingTable_TrvPolicyViolationsCacheRelationshipId](#BackingTable_TrvPolicyViolationsCacheRelationshipId)||<a href="TrvPolicyViolationsCacheEntity.md" target="_blank">TravelAndExpense/TrvPolicyViolationsCacheEntity</a>|

### <a href=#ViolationsCacheId name="ViolationsCacheId">ViolationsCacheId</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViolationsCacheId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Header name="Header">Header</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Header attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderId name="HeaderId">HeaderId</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Header</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Header</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderLegalEntity name="HeaderLegalEntity">HeaderLegalEntity</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Line name="Line">Line</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Line attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineId name="LineId">LineId</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentRecId name="ParentRecId">ParentRecId</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentId name="ParentId">ParentId</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Parent</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyType name="PolicyType">PolicyType</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyViolationLevel name="PolicyViolationLevel">PolicyViolationLevel</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyViolationLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Rule name="Rule">Rule</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Policy name="Policy">Policy</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Policy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyName name="PolicyName">PolicyName</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyPolicyType name="PolicyPolicyType">PolicyPolicyType</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyPolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleType name="PolicyRuleType">PolicyRuleType</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleTypeName name="PolicyRuleTypeName">PolicyRuleTypeName</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleTypePolicyType name="PolicyRuleTypePolicyType">PolicyRuleTypePolicyType</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleTypePolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleValidFrom name="PolicyRuleValidFrom">PolicyRuleValidFrom</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SaveDateTime name="SaveDateTime">SaveDateTime</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaveDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ViolationDate name="ViolationDate">ViolationDate</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViolationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

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

### <a href=#BackingTable_TrvPolicyViolationsCacheRelationshipId name="BackingTable_TrvPolicyViolationsCacheRelationshipId">BackingTable_TrvPolicyViolationsCacheRelationshipId</a>

First included in: TravelAndExpense/TrvPolicyViolationsCacheEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TrvPolicyViolationsCacheRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Expense/WorksheetLine/TrvPolicyViolationsCache.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/WorksheetLine/TrvPolicyViolationsCache.cdm.json/TrvPolicyViolationsCache</a></td><td><a href="../../../Tables/Finance/Expense/WorksheetLine/TrvPolicyViolationsCache.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
