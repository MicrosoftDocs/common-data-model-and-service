---
title: PayrollRetirementBenefitPlanDetailEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PayrollRetirementBenefitPlanDetailEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollRetirementBenefitPlanDetailEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[BenefitPlan](#BenefitPlan)||<a href="PayrollRetirementBenefitPlanDetailEntity.md" target="_blank">Payroll/PayrollRetirementBenefitPlanDetailEntity</a>|
|[ContributionLimitMethod](#ContributionLimitMethod)||<a href="PayrollRetirementBenefitPlanDetailEntity.md" target="_blank">Payroll/PayrollRetirementBenefitPlanDetailEntity</a>|
|[ContributionMethod](#ContributionMethod)||<a href="PayrollRetirementBenefitPlanDetailEntity.md" target="_blank">Payroll/PayrollRetirementBenefitPlanDetailEntity</a>|
|[RetirementType](#RetirementType)||<a href="PayrollRetirementBenefitPlanDetailEntity.md" target="_blank">Payroll/PayrollRetirementBenefitPlanDetailEntity</a>|
|[BenefitPlanID](#BenefitPlanID)||<a href="PayrollRetirementBenefitPlanDetailEntity.md" target="_blank">Payroll/PayrollRetirementBenefitPlanDetailEntity</a>|
|[Relationship_BenefitPlanRelationshipId](#Relationship_BenefitPlanRelationshipId)||<a href="PayrollRetirementBenefitPlanDetailEntity.md" target="_blank">Payroll/PayrollRetirementBenefitPlanDetailEntity</a>|

### <a href=#BenefitPlan name="BenefitPlan">BenefitPlan</a>

First included in: Payroll/PayrollRetirementBenefitPlanDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionLimitMethod name="ContributionLimitMethod">ContributionLimitMethod</a>

First included in: Payroll/PayrollRetirementBenefitPlanDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionLimitMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionMethod name="ContributionMethod">ContributionMethod</a>

First included in: Payroll/PayrollRetirementBenefitPlanDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetirementType name="RetirementType">RetirementType</a>

First included in: Payroll/PayrollRetirementBenefitPlanDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetirementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitPlanID name="BenefitPlanID">BenefitPlanID</a>

First included in: Payroll/PayrollRetirementBenefitPlanDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlanID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BenefitPlanRelationshipId name="Relationship_BenefitPlanRelationshipId">Relationship_BenefitPlanRelationshipId</a>

First included in: Payroll/PayrollRetirementBenefitPlanDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BenefitPlanRelationshipId attribute are listed below.</summary>

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
