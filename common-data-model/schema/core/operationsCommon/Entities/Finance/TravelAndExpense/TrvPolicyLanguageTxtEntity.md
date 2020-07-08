---
title: TrvPolicyLanguageTxtEntity in TravelAndExpense - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Expense policy translations in TravelAndExpense(TrvPolicyLanguageTxtEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/TravelAndExpense/TrvPolicyLanguageTxtEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expense policy translations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Language](#Language)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[Reference](#Reference)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[Text](#Text)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[PolicyRule_Policy](#PolicyRule_Policy)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[PolicyRule_PolicyRuleType](#PolicyRule_PolicyRuleType)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[PolicyRule_ValidFrom](#PolicyRule_ValidFrom)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[Policy_Name](#Policy_Name)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[Policy_PolicyType](#Policy_PolicyType)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[PolicyTypeRel_PolicyType](#PolicyTypeRel_PolicyType)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[PolicyRuleType_Name](#PolicyRuleType_Name)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[PolicyRuleType_PolicyType](#PolicyRuleType_PolicyType)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[PolicyType_PolicyType](#PolicyType_PolicyType)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|
|[BackingTable_TrvPolicyLanguageTxtRelationshipId](#BackingTable_TrvPolicyLanguageTxtRelationshipId)||<a href="TrvPolicyLanguageTxtEntity.md" target="_blank">TravelAndExpense/TrvPolicyLanguageTxtEntity</a>|

### <a href=#Language name="Language">Language</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Language attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Text name="Text">Text</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Text attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRule_Policy name="PolicyRule_Policy">PolicyRule_Policy</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRule_Policy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRule_PolicyRuleType name="PolicyRule_PolicyRuleType">PolicyRule_PolicyRuleType</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRule_PolicyRuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRule_ValidFrom name="PolicyRule_ValidFrom">PolicyRule_ValidFrom</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRule_ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Policy_Name name="Policy_Name">Policy_Name</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Policy_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Policy_PolicyType name="Policy_PolicyType">Policy_PolicyType</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Policy_PolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyTypeRel_PolicyType name="PolicyTypeRel_PolicyType">PolicyTypeRel_PolicyType</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyTypeRel_PolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleType_Name name="PolicyRuleType_Name">PolicyRuleType_Name</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleType_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleType_PolicyType name="PolicyRuleType_PolicyType">PolicyRuleType_PolicyType</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleType_PolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyType_PolicyType name="PolicyType_PolicyType">PolicyType_PolicyType</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyType_PolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TrvPolicyLanguageTxtRelationshipId name="BackingTable_TrvPolicyLanguageTxtRelationshipId">BackingTable_TrvPolicyLanguageTxtRelationshipId</a>

First included in: TravelAndExpense/TrvPolicyLanguageTxtEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TrvPolicyLanguageTxtRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Expense/Reference/TrvPolicyLanguageTxt.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Reference/TrvPolicyLanguageTxt.cdm.json/TrvPolicyLanguageTxt</a></td><td><a href="../../../Tables/Finance/Expense/Reference/TrvPolicyLanguageTxt.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
