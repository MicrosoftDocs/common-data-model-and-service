---
title: PayrollPayStatementEarningLineInquiryEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Pay statement earning lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollPayStatementEarningLineInquiryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay statement earning lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LineNum](#LineNum)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[Worker](#Worker)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[PayStatementNumber](#PayStatementNumber)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[PeriodEndDate](#PeriodEndDate)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[PeriodStartDate](#PeriodStartDate)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[PayCycleId](#PayCycleId)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[EarningCode](#EarningCode)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[Description](#Description)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[AccountingCurrencyAmount](#AccountingCurrencyAmount)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[Quantity](#Quantity)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[EarningRate](#EarningRate)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[PositionId](#PositionId)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[TaxRegionDescription](#TaxRegionDescription)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[BenefitPlanIDGLI](#BenefitPlanIDGLI)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[BenefitOptionIDGLI](#BenefitOptionIDGLI)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[GeneralLiabilityInsurance](#GeneralLiabilityInsurance)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[BenefitPlanIDComp](#BenefitPlanIDComp)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[BenefitOptionIDComp](#BenefitOptionIDComp)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[WorkerCompensation](#WorkerCompensation)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[Source](#Source)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[Relationship_PayrollPayStatementHeaderEntityRelationshipId](#Relationship_PayrollPayStatementHeaderEntityRelationshipId)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[Relationship_HcmWorkerEntityRelationshipId](#Relationship_HcmWorkerEntityRelationshipId)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[BackingTable_PayrollPayStatementEarningLineRelationshipId](#BackingTable_PayrollPayStatementEarningLineRelationshipId)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PayrollPayStatementEarningLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineInquiryEntity</a>|

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

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

### <a href=#PayStatementNumber name="PayStatementNumber">PayStatementNumber</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodEndDate name="PeriodEndDate">PeriodEndDate</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodStartDate name="PeriodStartDate">PeriodStartDate</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayCycleId name="PayCycleId">PayCycleId</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayCycleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCode name="EarningCode">EarningCode</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

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

### <a href=#AccountingCurrencyAmount name="AccountingCurrencyAmount">AccountingCurrencyAmount</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningRate name="EarningRate">EarningRate</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRegionDescription name="TaxRegionDescription">TaxRegionDescription</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax region</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitPlanIDGLI name="BenefitPlanIDGLI">BenefitPlanIDGLI</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>@Payroll:GeneralLiabilityInsuranceBenefitPlanId</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlanIDGLI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Payroll:GeneralLiabilityInsuranceBenefitPlanId</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitOptionIDGLI name="BenefitOptionIDGLI">BenefitOptionIDGLI</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>@Payroll:GeneralLiabilityInsuranceBenefitOptionId</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitOptionIDGLI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Payroll:GeneralLiabilityInsuranceBenefitOptionId</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLiabilityInsurance name="GeneralLiabilityInsurance">GeneralLiabilityInsurance</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>General liability insurance</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLiabilityInsurance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>General liability insurance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitPlanIDComp name="BenefitPlanIDComp">BenefitPlanIDComp</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>@Payroll:WorkerCompensationBenefitPlanId</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlanIDComp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Payroll:WorkerCompensationBenefitPlanId</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitOptionIDComp name="BenefitOptionIDComp">BenefitOptionIDComp</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>@Payroll:WorkerCompensationBenefitOptionId</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitOptionIDComp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Payroll:WorkerCompensationBenefitOptionId</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerCompensation name="WorkerCompensation">WorkerCompensation</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Workers' compensation code</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerCompensation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workers' compensation code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Source name="Source">Source</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Source attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollPayStatementHeaderEntityRelationshipId name="Relationship_PayrollPayStatementHeaderEntityRelationshipId">Relationship_PayrollPayStatementHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

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

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

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

### <a href=#BackingTable_PayrollPayStatementEarningLineRelationshipId name="BackingTable_PayrollPayStatementEarningLineRelationshipId">BackingTable_PayrollPayStatementEarningLineRelationshipId</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollPayStatementEarningLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementEarningLine.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementEarningLine.cdm.json/PayrollPayStatementEarningLine</a></td><td><a href="../../../Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementEarningLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Payroll/PayrollPayStatementEarningLineInquiryEntity (this entity)  

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
