---
title: HcmBenefitPlanEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# HcmBenefitPlanEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/HumanResources/HRM/HcmBenefitPlanEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[Plan](#Plan)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[Description](#Description)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[Type](#Type)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[TypeId](#TypeId)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[PayrollImpact](#PayrollImpact)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[IsAffordableCareActReportable](#IsAffordableCareActReportable)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[IsPayStatementLineLocked](#IsPayStatementLineLocked)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[IsArrearGenerated](#IsArrearGenerated)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[DeductionMethod](#DeductionMethod)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[DefaultContributionLimitAmount](#DefaultContributionLimitAmount)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[DefaultContributionLimitPeriod](#DefaultContributionLimitPeriod)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[DefaultDeductionLimitAmount](#DefaultDeductionLimitAmount)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[DefaultDeductionLimitPeriod](#DefaultDeductionLimitPeriod)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[DeductionPriority](#DeductionPriority)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[PaymentTypeIsAdditional](#PaymentTypeIsAdditional)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[PaymentTypeIsGrossUp](#PaymentTypeIsGrossUp)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[PaymentTypeIsPrimary](#PaymentTypeIsPrimary)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[ContributionLimitMethod](#ContributionLimitMethod)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[ContributionMethod](#ContributionMethod)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[RetirementType](#RetirementType)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[Relationship_TypeRelationshipId](#Relationship_TypeRelationshipId)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="HcmBenefitPlanEntity.md" target="_blank">HRM/HcmBenefitPlanEntity</a>|

### <a href=#Plan name="Plan">Plan</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Plan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeId name="TypeId">TypeId</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollImpact name="PayrollImpact">PayrollImpact</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollImpact attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAffordableCareActReportable name="IsAffordableCareActReportable">IsAffordableCareActReportable</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAffordableCareActReportable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPayStatementLineLocked name="IsPayStatementLineLocked">IsPayStatementLineLocked</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPayStatementLineLocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsArrearGenerated name="IsArrearGenerated">IsArrearGenerated</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsArrearGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionMethod name="DeductionMethod">DeductionMethod</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultContributionLimitAmount name="DefaultContributionLimitAmount">DefaultContributionLimitAmount</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultContributionLimitAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultContributionLimitPeriod name="DefaultContributionLimitPeriod">DefaultContributionLimitPeriod</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultContributionLimitPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDeductionLimitAmount name="DefaultDeductionLimitAmount">DefaultDeductionLimitAmount</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDeductionLimitAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDeductionLimitPeriod name="DefaultDeductionLimitPeriod">DefaultDeductionLimitPeriod</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDeductionLimitPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionPriority name="DeductionPriority">DeductionPriority</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTypeIsAdditional name="PaymentTypeIsAdditional">PaymentTypeIsAdditional</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTypeIsAdditional attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTypeIsGrossUp name="PaymentTypeIsGrossUp">PaymentTypeIsGrossUp</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTypeIsGrossUp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTypeIsPrimary name="PaymentTypeIsPrimary">PaymentTypeIsPrimary</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTypeIsPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionLimitMethod name="ContributionLimitMethod">ContributionLimitMethod</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

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

First included in: HRM/HcmBenefitPlanEntity (this entity)  

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

First included in: HRM/HcmBenefitPlanEntity (this entity)  

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

### <a href=#Relationship_TypeRelationshipId name="Relationship_TypeRelationshipId">Relationship_TypeRelationshipId</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: HRM/HcmBenefitPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

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
