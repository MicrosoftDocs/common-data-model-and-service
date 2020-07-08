---
title: PayrollAccrualPlanRuleEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Benefit accrual rate in Payroll(PayrollAccrualPlanRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollAccrualPlanRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Benefit accrual rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Accrual](#Accrual)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|
|[CarryForwardLimit](#CarryForwardLimit)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|
|[EmploymentMonths](#EmploymentMonths)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|
|[HourlyRate](#HourlyRate)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|
|[MaximumLimit](#MaximumLimit)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|
|[MinimumLimit](#MinimumLimit)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|
|[AccrualId](#AccrualId)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|
|[Relationship_AccrualPlanRelationshipId](#Relationship_AccrualPlanRelationshipId)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|
|[BackingTable_PayrollAccrualRateRelationshipId](#BackingTable_PayrollAccrualRateRelationshipId)||<a href="PayrollAccrualPlanRuleEntity.md" target="_blank">Payroll/PayrollAccrualPlanRuleEntity</a>|

### <a href=#Accrual name="Accrual">Accrual</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Accrual attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarryForwardLimit name="CarryForwardLimit">CarryForwardLimit</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarryForwardLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentMonths name="EmploymentMonths">EmploymentMonths</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentMonths attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourlyRate name="HourlyRate">HourlyRate</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourlyRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumLimit name="MaximumLimit">MaximumLimit</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumLimit name="MinimumLimit">MinimumLimit</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualId name="AccrualId">AccrualId</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccrualPlanRelationshipId name="Relationship_AccrualPlanRelationshipId">Relationship_AccrualPlanRelationshipId</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccrualPlanRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollAccrualRateRelationshipId name="BackingTable_PayrollAccrualRateRelationshipId">BackingTable_PayrollAccrualRateRelationshipId</a>

First included in: Payroll/PayrollAccrualPlanRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollAccrualRateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollAccrualRate.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollAccrualRate.cdm.json/PayrollAccrualRate</a></td><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollAccrualRate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
