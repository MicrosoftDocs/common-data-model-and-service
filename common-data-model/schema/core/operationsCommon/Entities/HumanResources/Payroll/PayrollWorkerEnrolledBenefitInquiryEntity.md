---
title: PayrollWorkerEnrolledBenefitInquiryEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Worker enrolled benefit in Payroll(PayrollWorkerEnrolledBenefitInquiryEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollWorkerEnrolledBenefitInquiryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Worker enrolled benefit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Worker](#Worker)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[Benefit](#Benefit)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[ValidTo](#ValidTo)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[Name](#Name)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[BenefitTypeId](#BenefitTypeId)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[PayrollCategory](#PayrollCategory)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[BenefitPlanID](#BenefitPlanID)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[BenefitOptionID](#BenefitOptionID)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[DeductionRateSource](#DeductionRateSource)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[DeductionBasis](#DeductionBasis)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[DeductionAmountCur](#DeductionAmountCur)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[ContributionBasis](#ContributionBasis)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[ContributionRateSource](#ContributionRateSource)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[ContributionAmountCur](#ContributionAmountCur)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[BenefitId](#BenefitId)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[BenefitPlanAndOption](#BenefitPlanAndOption)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="PayrollWorkerEnrolledBenefitInquiryEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitInquiryEntity</a>|

### <a href=#Worker name="Worker">Worker</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitTypeId name="BenefitTypeId">BenefitTypeId</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollCategory name="PayrollCategory">PayrollCategory</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitPlanID name="BenefitPlanID">BenefitPlanID</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlanID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitOptionID name="BenefitOptionID">BenefitOptionID</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitOptionID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionRateSource name="DeductionRateSource">DeductionRateSource</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

### <a href=#DeductionBasis name="DeductionBasis">DeductionBasis</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

### <a href=#DeductionAmountCur name="DeductionAmountCur">DeductionAmountCur</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

### <a href=#ContributionBasis name="ContributionBasis">ContributionBasis</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

### <a href=#ContributionAmountCur name="ContributionAmountCur">ContributionAmountCur</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

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

### <a href=#BenefitPlanAndOption name="BenefitPlanAndOption">BenefitPlanAndOption</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Benefit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlanAndOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Benefit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerRelationshipId attribute are listed below.</summary>

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
