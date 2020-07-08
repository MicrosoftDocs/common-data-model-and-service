---
title: PayrollUSTaxTransactionHistoryDetailEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Payroll US Tax Transaction History in Payroll(PayrollUSTaxTransactionHistoryDetailEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollUSTaxTransactionHistoryDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payroll US Tax Transaction History</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Worker](#Worker)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[TransDate](#TransDate)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[PayStatementNumber](#PayStatementNumber)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Code](#Code)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Description](#Description)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Type](#Type)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[GrossWages](#GrossWages)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[GrossSubjectWages](#GrossSubjectWages)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[SubjectWages](#SubjectWages)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Hours](#Hours)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Rate](#Rate)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[ExcessWages](#ExcessWages)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[PriorState](#PriorState)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[PriorStateWageAmount](#PriorStateWageAmount)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[WageBase](#WageBase)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[CalculatedTaxAmount](#CalculatedTaxAmount)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Invoice](#Invoice)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Relationship_PayrollPayStatementHeaderEntityRelationshipId](#Relationship_PayrollPayStatementHeaderEntityRelationshipId)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Relationship_HcmWorkerEntityRelationshipId](#Relationship_HcmWorkerEntityRelationshipId)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Relationship_PayrollTaxCodeHeaderEntityRelationshipId](#Relationship_PayrollTaxCodeHeaderEntityRelationshipId)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[BackingTable_PayrollUSTaxTransactionHistoryRelationshipId](#BackingTable_PayrollUSTaxTransactionHistoryRelationshipId)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PayrollUSTaxTransactionHistoryDetailEntity.md" target="_blank">Payroll/PayrollUSTaxTransactionHistoryDetailEntity</a>|

### <a href=#Worker name="Worker">Worker</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

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

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

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

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStatementNumber name="PayStatementNumber">PayStatementNumber</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Code name="Code">Code</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Code attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

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

### <a href=#Type name="Type">Type</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossWages name="GrossWages">GrossWages</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossWages attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossSubjectWages name="GrossSubjectWages">GrossSubjectWages</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossSubjectWages attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubjectWages name="SubjectWages">SubjectWages</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubjectWages attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hours name="Hours">Hours</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Rate name="Rate">Rate</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcessWages name="ExcessWages">ExcessWages</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcessWages attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriorState name="PriorState">PriorState</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriorState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriorStateWageAmount name="PriorStateWageAmount">PriorStateWageAmount</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriorStateWageAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WageBase name="WageBase">WageBase</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WageBase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculatedTaxAmount name="CalculatedTaxAmount">CalculatedTaxAmount</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollPayStatementHeaderEntityRelationshipId name="Relationship_PayrollPayStatementHeaderEntityRelationshipId">Relationship_PayrollPayStatementHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollPayStatementHeaderEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmWorkerEntityRelationshipId name="Relationship_HcmWorkerEntityRelationshipId">Relationship_HcmWorkerEntityRelationshipId</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PayrollTaxCodeHeaderEntityRelationshipId name="Relationship_PayrollTaxCodeHeaderEntityRelationshipId">Relationship_PayrollTaxCodeHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollTaxCodeHeaderEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollUSTaxTransactionHistoryRelationshipId name="BackingTable_PayrollUSTaxTransactionHistoryRelationshipId">BackingTable_PayrollUSTaxTransactionHistoryRelationshipId</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollUSTaxTransactionHistoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Transaction/PayrollUSTaxTransactionHistory.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Transaction/PayrollUSTaxTransactionHistory.cdm.json/PayrollUSTaxTransactionHistory</a></td><td><a href="../../../Tables/HumanResources/Payroll/Transaction/PayrollUSTaxTransactionHistory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Payroll/PayrollUSTaxTransactionHistoryDetailEntity (this entity)  

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
