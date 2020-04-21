---
title: HcmCompVarPlanTableEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# HcmCompVarPlanTableEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmCompVarPlanTableEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[VariableAwardBasis](#VariableAwardBasis)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[AwardBasisCalculation](#AwardBasisCalculation)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[CalculationType](#CalculationType)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[Description](#Description)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[EnableEnrollment](#EnableEnrollment)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[EnableLevels](#EnableLevels)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[EnableRecommendation](#EnableRecommendation)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[HireRule](#HireRule)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[Leverage100Percent](#Leverage100Percent)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[LeverageMaximum](#LeverageMaximum)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[LeverageMinimum](#LeverageMinimum)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[LeverageOverObjective](#LeverageOverObjective)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[LeverageToleranceMax](#LeverageToleranceMax)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[LeverageToleranceMin](#LeverageToleranceMin)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[LeverageUnderObjective](#LeverageUnderObjective)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[PercentOfBasis](#PercentOfBasis)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[PlanId](#PlanId)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[VariableCompensationType](#VariableCompensationType)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[UnitCurrencyCode](#UnitCurrencyCode)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[UnitRelationship](#UnitRelationship)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[NumberOfUnits](#NumberOfUnits)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[UnitValue](#UnitValue)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[EffectiveDate](#EffectiveDate)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[ExpirationDate](#ExpirationDate)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[VestingRule](#VestingRule)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[Relationship_CompVarPlanTypeRelationshipId](#Relationship_CompVarPlanTypeRelationshipId)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[Relationship_CompensationVestingRelationshipId](#Relationship_CompensationVestingRelationshipId)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HcmCompVarPlanTableEntity.md" target="_blank">HRM/HcmCompVarPlanTableEntity</a>|

### <a href=#VariableAwardBasis name="VariableAwardBasis">VariableAwardBasis</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableAwardBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AwardBasisCalculation name="AwardBasisCalculation">AwardBasisCalculation</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AwardBasisCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculationType name="CalculationType">CalculationType</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

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

### <a href=#EnableEnrollment name="EnableEnrollment">EnableEnrollment</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableEnrollment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableLevels name="EnableLevels">EnableLevels</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLevels attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableRecommendation name="EnableRecommendation">EnableRecommendation</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableRecommendation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HireRule name="HireRule">HireRule</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HireRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Leverage100Percent name="Leverage100Percent">Leverage100Percent</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Leverage100Percent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeverageMaximum name="LeverageMaximum">LeverageMaximum</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeverageMaximum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeverageMinimum name="LeverageMinimum">LeverageMinimum</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeverageMinimum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeverageOverObjective name="LeverageOverObjective">LeverageOverObjective</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeverageOverObjective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeverageToleranceMax name="LeverageToleranceMax">LeverageToleranceMax</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeverageToleranceMax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeverageToleranceMin name="LeverageToleranceMin">LeverageToleranceMin</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeverageToleranceMin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeverageUnderObjective name="LeverageUnderObjective">LeverageUnderObjective</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeverageUnderObjective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PercentOfBasis name="PercentOfBasis">PercentOfBasis</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentOfBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlanId name="PlanId">PlanId</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariableCompensationType name="VariableCompensationType">VariableCompensationType</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableCompensationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCurrencyCode name="UnitCurrencyCode">UnitCurrencyCode</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitRelationship name="UnitRelationship">UnitRelationship</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitRelationship attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfUnits name="NumberOfUnits">NumberOfUnits</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfUnits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitValue name="UnitValue">UnitValue</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveDate name="EffectiveDate">EffectiveDate</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VestingRule name="VestingRule">VestingRule</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VestingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

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

### <a href=#Relationship_CompVarPlanTypeRelationshipId name="Relationship_CompVarPlanTypeRelationshipId">Relationship_CompVarPlanTypeRelationshipId</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompVarPlanTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompensationVestingRelationshipId name="Relationship_CompensationVestingRelationshipId">Relationship_CompensationVestingRelationshipId</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompensationVestingRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: HRM/HcmCompVarPlanTableEntity (this entity)  

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
