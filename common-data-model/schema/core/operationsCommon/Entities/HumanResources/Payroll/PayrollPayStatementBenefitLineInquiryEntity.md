---
title: PayrollPayStatementBenefitLineInquiryEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Pay statement benefit lines in Payroll(PayrollPayStatementBenefitLineInquiryEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollPayStatementBenefitLineInquiryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay statement benefit lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Worker](#Worker)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[PayStatementNumber](#PayStatementNumber)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[PayCycleId](#PayCycleId)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[PeriodStartDate](#PeriodStartDate)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[PeriodEndDate](#PeriodEndDate)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[BenefitId](#BenefitId)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[Description](#Description)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[AccountingCurrencyAmount](#AccountingCurrencyAmount)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[BaseTimeEarningBaseAmount](#BaseTimeEarningBaseAmount)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[BaseTimeEarningBaseHours](#BaseTimeEarningBaseHours)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[PremiumEarningBaseAmount](#PremiumEarningBaseAmount)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[PremiumEarningBaseHours](#PremiumEarningBaseHours)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[IsEmployer](#IsEmployer)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[PositionId](#PositionId)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[Source](#Source)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[VendorInvoice](#VendorInvoice)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[LineNum](#LineNum)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[Relationship_PayrollPayStatementHeaderEntityRelationshipId](#Relationship_PayrollPayStatementHeaderEntityRelationshipId)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|
|[BackingTable_PayrollPayStatementBenefitLineRelationshipId](#BackingTable_PayrollPayStatementBenefitLineRelationshipId)||<a href="PayrollPayStatementBenefitLineInquiryEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineInquiryEntity</a>|

### <a href=#Worker name="Worker">Worker</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

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

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

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

### <a href=#PayStatementNumber name="PayStatementNumber">PayStatementNumber</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

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

### <a href=#PayCycleId name="PayCycleId">PayCycleId</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayCycleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodStartDate name="PeriodStartDate">PeriodStartDate</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodEndDate name="PeriodEndDate">PeriodEndDate</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

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

### <a href=#Description name="Description">Description</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

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

### <a href=#AccountingCurrencyAmount name="AccountingCurrencyAmount">AccountingCurrencyAmount</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseTimeEarningBaseAmount name="BaseTimeEarningBaseAmount">BaseTimeEarningBaseAmount</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseTimeEarningBaseAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseTimeEarningBaseHours name="BaseTimeEarningBaseHours">BaseTimeEarningBaseHours</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseTimeEarningBaseHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PremiumEarningBaseAmount name="PremiumEarningBaseAmount">PremiumEarningBaseAmount</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningBaseAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PremiumEarningBaseHours name="PremiumEarningBaseHours">PremiumEarningBaseHours</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningBaseHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEmployer name="IsEmployer">IsEmployer</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEmployer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

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

### <a href=#Source name="Source">Source</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Source attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoice name="VendorInvoice">VendorInvoice</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollPayStatementHeaderEntityRelationshipId name="Relationship_PayrollPayStatementHeaderEntityRelationshipId">Relationship_PayrollPayStatementHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

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

### <a href=#BackingTable_PayrollPayStatementBenefitLineRelationshipId name="BackingTable_PayrollPayStatementBenefitLineRelationshipId">BackingTable_PayrollPayStatementBenefitLineRelationshipId</a>

First included in: Payroll/PayrollPayStatementBenefitLineInquiryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollPayStatementBenefitLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementBenefitLine.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementBenefitLine.cdm.json/PayrollPayStatementBenefitLine</a></td><td><a href="../../../Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementBenefitLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
