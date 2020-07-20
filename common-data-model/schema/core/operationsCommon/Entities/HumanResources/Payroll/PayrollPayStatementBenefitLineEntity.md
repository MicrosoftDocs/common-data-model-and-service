---
title: PayrollPayStatementBenefitLineEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Pay statement benefit lines in Payroll(PayrollPayStatementBenefitLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollPayStatementBenefitLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay statement benefit lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AmountInTransactionCurrency](#AmountInTransactionCurrency)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[TemplateId](#TemplateId)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[EmployerContribution](#EmployerContribution)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[LineLocked](#LineLocked)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[LineToRemove](#LineToRemove)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[LineOverridden](#LineOverridden)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[PayStatement](#PayStatement)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[Position](#Position)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[ReversedPayStatementLine](#ReversedPayStatementLine)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[PayStatementLineSource](#PayStatementLineSource)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[Company](#Company)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[BaseEarningAmount](#BaseEarningAmount)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[BaseEarningHours](#BaseEarningHours)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[Benefit](#Benefit)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[PremiumEarningAmount](#PremiumEarningAmount)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[PremiumEarningHours](#PremiumEarningHours)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[AccountingDistributionTemplateId](#AccountingDistributionTemplateId)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[AccountingDistributionLegalEntityId](#AccountingDistributionLegalEntityId)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[AccountingDistributionLegalEntity](#AccountingDistributionLegalEntity)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[PayStatementNumber](#PayStatementNumber)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[PositionId](#PositionId)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[BenefitId](#BenefitId)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[ReversedPayStatementNumber](#ReversedPayStatementNumber)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[ReversedPayStatement](#ReversedPayStatement)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[ReversedPayStatementLineNum](#ReversedPayStatementLineNum)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[Relationship_PayrollPayStatementHeaderEntityRelationshipId](#Relationship_PayrollPayStatementHeaderEntityRelationshipId)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|
|[BackingTable_PayrollPayStatementBenefitLineRelationshipId](#BackingTable_PayrollPayStatementBenefitLineRelationshipId)||<a href="PayrollPayStatementBenefitLineEntity.md" target="_blank">Payroll/PayrollPayStatementBenefitLineEntity</a>|

### <a href=#AmountInTransactionCurrency name="AmountInTransactionCurrency">AmountInTransactionCurrency</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

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

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployerContribution name="EmployerContribution">EmployerContribution</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployerContribution attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineLocked name="LineLocked">LineLocked</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineLocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineToRemove name="LineToRemove">LineToRemove</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineToRemove attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineOverridden name="LineOverridden">LineOverridden</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStatement name="PayStatement">PayStatement</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

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

### <a href=#ReversedPayStatementLine name="ReversedPayStatementLine">ReversedPayStatementLine</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversedPayStatementLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStatementLineSource name="PayStatementLineSource">PayStatementLineSource</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatementLineSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseEarningAmount name="BaseEarningAmount">BaseEarningAmount</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseEarningAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseEarningHours name="BaseEarningHours">BaseEarningHours</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseEarningHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

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

### <a href=#PremiumEarningAmount name="PremiumEarningAmount">PremiumEarningAmount</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PremiumEarningHours name="PremiumEarningHours">PremiumEarningHours</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplateId name="AccountingDistributionTemplateId">AccountingDistributionTemplateId</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionLegalEntityId name="AccountingDistributionLegalEntityId">AccountingDistributionLegalEntityId</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionLegalEntity name="AccountingDistributionLegalEntity">AccountingDistributionLegalEntity</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStatementNumber name="PayStatementNumber">PayStatementNumber</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

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

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

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

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

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

### <a href=#ReversedPayStatementNumber name="ReversedPayStatementNumber">ReversedPayStatementNumber</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversedPayStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversedPayStatement name="ReversedPayStatement">ReversedPayStatement</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversedPayStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversedPayStatementLineNum name="ReversedPayStatementLineNum">ReversedPayStatementLineNum</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversedPayStatementLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollPayStatementHeaderEntityRelationshipId name="Relationship_PayrollPayStatementHeaderEntityRelationshipId">Relationship_PayrollPayStatementHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

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

First included in: Payroll/PayrollPayStatementBenefitLineEntity (this entity)  

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
