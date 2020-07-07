---
title: PayrollWorkerEnrolledAccrualEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Worker enrolled benefit accrual in Payroll

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollWorkerEnrolledAccrualEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Worker enrolled benefit accrual</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Accrual](#Accrual)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[AccrualDateBasis](#AccrualDateBasis)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[AccrualYearStartDate](#AccrualYearStartDate)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[IsAccrualStopped](#IsAccrualStopped)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[IsUsageStopped](#IsUsageStopped)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[Worker](#Worker)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[CustomAccuralDate](#CustomAccuralDate)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[AccrualId](#AccrualId)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[Relationship_PayrollAccrualPlanRelationshipId](#Relationship_PayrollAccrualPlanRelationshipId)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[Relationship_HcmWorkerRelationshipId](#Relationship_HcmWorkerRelationshipId)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[BackingTable_PayrollWorkerEnrolledAccrualRelationshipId](#BackingTable_PayrollWorkerEnrolledAccrualRelationshipId)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PayrollWorkerEnrolledAccrualEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledAccrualEntity</a>|

### <a href=#Accrual name="Accrual">Accrual</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

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

### <a href=#AccrualDateBasis name="AccrualDateBasis">AccrualDateBasis</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualDateBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualYearStartDate name="AccrualYearStartDate">AccrualYearStartDate</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualYearStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAccrualStopped name="IsAccrualStopped">IsAccrualStopped</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAccrualStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsUsageStopped name="IsUsageStopped">IsUsageStopped</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUsageStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

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

### <a href=#CustomAccuralDate name="CustomAccuralDate">CustomAccuralDate</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomAccuralDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualId name="AccrualId">AccrualId</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

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

### <a href=#Relationship_PayrollAccrualPlanRelationshipId name="Relationship_PayrollAccrualPlanRelationshipId">Relationship_PayrollAccrualPlanRelationshipId</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollAccrualPlanRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmWorkerRelationshipId name="Relationship_HcmWorkerRelationshipId">Relationship_HcmWorkerRelationshipId</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollWorkerEnrolledAccrualRelationshipId name="BackingTable_PayrollWorkerEnrolledAccrualRelationshipId">BackingTable_PayrollWorkerEnrolledAccrualRelationshipId</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollWorkerEnrolledAccrualRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollWorkerEnrolledAccrual.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollWorkerEnrolledAccrual.cdm.json/PayrollWorkerEnrolledAccrual</a></td><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollWorkerEnrolledAccrual.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Payroll/PayrollWorkerEnrolledAccrualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
