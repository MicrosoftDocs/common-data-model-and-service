---
title: PayrollPremiumEarningCodeEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Premium code in Payroll

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollPremiumEarningCodeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Premium code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CalculationFrequency](#CalculationFrequency)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[Description](#Description)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[EarningCode](#EarningCode)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[PayoutBasis](#PayoutBasis)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[PremiumEarningCode](#PremiumEarningCode)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[CalculationFrequencyId](#CalculationFrequencyId)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[EarningCodeId](#EarningCodeId)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[PolicyRuleTypeId](#PolicyRuleTypeId)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[PolicyType](#PolicyType)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[PolicyTypeId](#PolicyTypeId)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[Relationship_PayrollEarningCodeEntityRelationshipId](#Relationship_PayrollEarningCodeEntityRelationshipId)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|
|[BackingTable_PayrollPremiumEarningCodeRelationshipId](#BackingTable_PayrollPremiumEarningCodeRelationshipId)||<a href="PayrollPremiumEarningCodeEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeEntity</a>|

### <a href=#CalculationFrequency name="CalculationFrequency">CalculationFrequency</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationFrequency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

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

### <a href=#EarningCode name="EarningCode">EarningCode</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayoutBasis name="PayoutBasis">PayoutBasis</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayoutBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleType name="PolicyRuleType">PolicyRuleType</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

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

### <a href=#PremiumEarningCode name="PremiumEarningCode">PremiumEarningCode</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Premium code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Premium code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculationFrequencyId name="CalculationFrequencyId">CalculationFrequencyId</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationFrequencyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCodeId name="EarningCodeId">EarningCodeId</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

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

### <a href=#PolicyRuleTypeId name="PolicyRuleTypeId">PolicyRuleTypeId</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyType name="PolicyType">PolicyType</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

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

### <a href=#PolicyTypeId name="PolicyTypeId">PolicyTypeId</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollEarningCodeEntityRelationshipId name="Relationship_PayrollEarningCodeEntityRelationshipId">Relationship_PayrollEarningCodeEntityRelationshipId</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollEarningCodeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollPremiumEarningCodeRelationshipId name="BackingTable_PayrollPremiumEarningCodeRelationshipId">BackingTable_PayrollPremiumEarningCodeRelationshipId</a>

First included in: Payroll/PayrollPremiumEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollPremiumEarningCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollPremiumEarningCode.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollPremiumEarningCode.cdm.json/PayrollPremiumEarningCode</a></td><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollPremiumEarningCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
