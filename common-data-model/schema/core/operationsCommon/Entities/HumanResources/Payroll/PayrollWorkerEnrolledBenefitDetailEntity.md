---
title: PayrollWorkerEnrolledBenefitDetailEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Worker benefit enrolled detail in Payroll(PayrollWorkerEnrolledBenefitDetailEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollWorkerEnrolledBenefitDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Worker benefit enrolled detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CalculationPriorityNumber](#CalculationPriorityNumber)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[ContributionAmountCur](#ContributionAmountCur)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[ContributionBasis](#ContributionBasis)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[ContributionRateSource](#ContributionRateSource)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[DeductionAmountCur](#DeductionAmountCur)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[DeductionBasis](#DeductionBasis)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[DeductionPriorityNumber](#DeductionPriorityNumber)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[DeductionRateSource](#DeductionRateSource)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[IsRetirementCatchUp](#IsRetirementCatchUp)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[Note](#Note)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[OverrideLimit](#OverrideLimit)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[Position](#Position)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[BenefitDetailValidFrom](#BenefitDetailValidFrom)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[BenefitDetailValidTo](#BenefitDetailValidTo)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[WorkerEnrolledBenefit](#WorkerEnrolledBenefit)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[DataArea](#DataArea)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[PartyNumber](#PartyNumber)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[PositionId](#PositionId)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[Benefit](#Benefit)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[EnrollmentStart](#EnrollmentStart)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[EnrollmentEnd](#EnrollmentEnd)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[Worker](#Worker)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[BenefitId](#BenefitId)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[VendDataAreaId](#VendDataAreaId)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[VendAccountNum](#VendAccountNum)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|
|[Relationship_PositionRelationshipId](#Relationship_PositionRelationshipId)||<a href="PayrollWorkerEnrolledBenefitDetailEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitDetailEntity</a>|

### <a href=#CalculationPriorityNumber name="CalculationPriorityNumber">CalculationPriorityNumber</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationPriorityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionAmountCur name="ContributionAmountCur">ContributionAmountCur</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionAmountCur attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionBasis name="ContributionBasis">ContributionBasis</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionRateSource name="ContributionRateSource">ContributionRateSource</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionRateSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionAmountCur name="DeductionAmountCur">DeductionAmountCur</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionAmountCur attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionBasis name="DeductionBasis">DeductionBasis</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionPriorityNumber name="DeductionPriorityNumber">DeductionPriorityNumber</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionPriorityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionRateSource name="DeductionRateSource">DeductionRateSource</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionRateSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRetirementCatchUp name="IsRetirementCatchUp">IsRetirementCatchUp</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRetirementCatchUp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Note attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverrideLimit name="OverrideLimit">OverrideLimit</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitDetailValidFrom name="BenefitDetailValidFrom">BenefitDetailValidFrom</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitDetailValidTo name="BenefitDetailValidTo">BenefitDetailValidTo</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerEnrolledBenefit name="WorkerEnrolledBenefit">WorkerEnrolledBenefit</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerEnrolledBenefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataArea name="DataArea">DataArea</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Benefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnrollmentStart name="EnrollmentStart">EnrollmentStart</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnrollmentStart attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnrollmentEnd name="EnrollmentEnd">EnrollmentEnd</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnrollmentEnd attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

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

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

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

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

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

### <a href=#VendDataAreaId name="VendDataAreaId">VendDataAreaId</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendAccountNum name="VendAccountNum">VendAccountNum</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PositionRelationshipId name="Relationship_PositionRelationshipId">Relationship_PositionRelationshipId</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PositionRelationshipId attribute are listed below.</summary>

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
