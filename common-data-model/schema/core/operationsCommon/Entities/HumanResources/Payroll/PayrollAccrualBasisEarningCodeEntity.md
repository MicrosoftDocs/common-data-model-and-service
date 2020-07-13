---
title: PayrollAccrualBasisEarningCodeEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Accrual basis earnings in Payroll(PayrollAccrualBasisEarningCodeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollAccrualBasisEarningCodeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accrual basis earnings</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Accrual](#Accrual)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[AccrualRate](#AccrualRate)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[AccrualType](#AccrualType)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[EarningCode](#EarningCode)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[EarningCodeGroup](#EarningCodeGroup)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[AccrualId](#AccrualId)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[EarningCodeId](#EarningCodeId)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[EarningCodeGroupId](#EarningCodeGroupId)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[Relationship_AccrualPlanRelationshipId](#Relationship_AccrualPlanRelationshipId)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[Relationship_EarningCodeGroupRelationshipId](#Relationship_EarningCodeGroupRelationshipId)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|
|[BackingTable_PayrollAccrualBasisEarningcodeRelationshipId](#BackingTable_PayrollAccrualBasisEarningcodeRelationshipId)||<a href="PayrollAccrualBasisEarningCodeEntity.md" target="_blank">Payroll/PayrollAccrualBasisEarningCodeEntity</a>|

### <a href=#Accrual name="Accrual">Accrual</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

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

### <a href=#AccrualRate name="AccrualRate">AccrualRate</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualType name="AccrualType">AccrualType</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCode name="EarningCode">EarningCode</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

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

### <a href=#EarningCodeGroup name="EarningCodeGroup">EarningCodeGroup</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCodeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualId name="AccrualId">AccrualId</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

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

### <a href=#EarningCodeId name="EarningCodeId">EarningCodeId</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCodeGroupId name="EarningCodeGroupId">EarningCodeGroupId</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCodeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccrualPlanRelationshipId name="Relationship_AccrualPlanRelationshipId">Relationship_AccrualPlanRelationshipId</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

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

### <a href=#Relationship_EarningCodeGroupRelationshipId name="Relationship_EarningCodeGroupRelationshipId">Relationship_EarningCodeGroupRelationshipId</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EarningCodeGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollAccrualBasisEarningcodeRelationshipId name="BackingTable_PayrollAccrualBasisEarningcodeRelationshipId">BackingTable_PayrollAccrualBasisEarningcodeRelationshipId</a>

First included in: Payroll/PayrollAccrualBasisEarningCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollAccrualBasisEarningcodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollAccrualBasisEarningcode.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollAccrualBasisEarningcode.cdm.json/PayrollAccrualBasisEarningcode</a></td><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollAccrualBasisEarningcode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
