---
title: PayrollDisposableIncomeBenefitEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PayrollDisposableIncomeBenefitEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollDisposableIncomeBenefitEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Name](#Name)||<a href="PayrollDisposableIncomeBenefitEntity.md" target="_blank">Payroll/PayrollDisposableIncomeBenefitEntity</a>|
|[BenefitId](#BenefitId)||<a href="PayrollDisposableIncomeBenefitEntity.md" target="_blank">Payroll/PayrollDisposableIncomeBenefitEntity</a>|
|[DisposableIncome](#DisposableIncome)||<a href="PayrollDisposableIncomeBenefitEntity.md" target="_blank">Payroll/PayrollDisposableIncomeBenefitEntity</a>|
|[Benefit](#Benefit)||<a href="PayrollDisposableIncomeBenefitEntity.md" target="_blank">Payroll/PayrollDisposableIncomeBenefitEntity</a>|
|[Relationship_PayrollDisposableIncomeEntityRelationshipId](#Relationship_PayrollDisposableIncomeEntityRelationshipId)||<a href="PayrollDisposableIncomeBenefitEntity.md" target="_blank">Payroll/PayrollDisposableIncomeBenefitEntity</a>|
|[Relationship_HcmBenefitEntityRelationshipId](#Relationship_HcmBenefitEntityRelationshipId)||<a href="PayrollDisposableIncomeBenefitEntity.md" target="_blank">Payroll/PayrollDisposableIncomeBenefitEntity</a>|

### <a href=#Name name="Name">Name</a>

First included in: Payroll/PayrollDisposableIncomeBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: Payroll/PayrollDisposableIncomeBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisposableIncome name="DisposableIncome">DisposableIncome</a>

First included in: Payroll/PayrollDisposableIncomeBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposableIncome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: Payroll/PayrollDisposableIncomeBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Benefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollDisposableIncomeEntityRelationshipId name="Relationship_PayrollDisposableIncomeEntityRelationshipId">Relationship_PayrollDisposableIncomeEntityRelationshipId</a>

First included in: Payroll/PayrollDisposableIncomeBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollDisposableIncomeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmBenefitEntityRelationshipId name="Relationship_HcmBenefitEntityRelationshipId">Relationship_HcmBenefitEntityRelationshipId</a>

First included in: Payroll/PayrollDisposableIncomeBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmBenefitEntityRelationshipId attribute are listed below.</summary>

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
