---
title: BankReconciliationMatchingRuleEntity in CashAndBankManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Reconciliation matching rules in CashAndBankManagement(BankReconciliationMatchingRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankReconciliationMatchingRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reconciliation matching rules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[MatchActionType](#MatchActionType)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[Name](#Name)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[MatchingRule](#MatchingRule)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[SearchBankDocuments](#SearchBankDocuments)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[FieldId](#FieldId)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[Value](#Value)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[CompareFieldId](#CompareFieldId)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[LineId](#LineId)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[Operator](#Operator)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[SourceTableId](#SourceTableId)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[Field](#Field)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[CompareField](#CompareField)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[LineType](#LineType)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[CompareFieldExpression](#CompareFieldExpression)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[SystemGeneratedType](#SystemGeneratedType)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|
|[BackingTable_BankReconciliationMatchRuleRelationshipId](#BackingTable_BankReconciliationMatchRuleRelationshipId)||<a href="BankReconciliationMatchingRuleEntity.md" target="_blank">CashAndBankManagement/BankReconciliationMatchingRuleEntity</a>|

### <a href=#MatchActionType name="MatchActionType">MatchActionType</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchActionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchingRule name="MatchingRule">MatchingRule</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SearchBankDocuments name="SearchBankDocuments">SearchBankDocuments</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchBankDocuments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FieldId name="FieldId">FieldId</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareFieldId name="CompareFieldId">CompareFieldId</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareFieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineId name="LineId">LineId</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

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

### <a href=#Operator name="Operator">Operator</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Operator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceTableId name="SourceTableId">SourceTableId</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Field name="Field">Field</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Field attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareField name="CompareField">CompareField</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareFieldExpression name="CompareFieldExpression">CompareFieldExpression</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expression</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareFieldExpression attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expression</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SystemGeneratedType name="SystemGeneratedType">SystemGeneratedType</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemGeneratedType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BankReconciliationMatchRuleRelationshipId name="BackingTable_BankReconciliationMatchRuleRelationshipId">BackingTable_BankReconciliationMatchRuleRelationshipId</a>

First included in: CashAndBankManagement/BankReconciliationMatchingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankReconciliationMatchRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Reference/BankReconciliationMatchRule.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Reference/BankReconciliationMatchRule.cdm.json/BankReconciliationMatchRule</a></td><td><a href="../../../Tables/Finance/Bank/Reference/BankReconciliationMatchRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
