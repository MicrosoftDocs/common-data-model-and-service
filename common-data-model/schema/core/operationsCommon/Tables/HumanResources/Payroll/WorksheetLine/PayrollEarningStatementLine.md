---
title: PayrollEarningStatementLine in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Earnings statement lines in WorksheetLine(PayrollEarningStatementLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/HumanResources/Payroll/WorksheetLine/PayrollEarningStatementLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollEarningStatementLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Earnings statement lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[AccountingCurrencyAmount](#AccountingCurrencyAmount)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[AccountingDate](#AccountingDate)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[AccountingDistributionTemplate](#AccountingDistributionTemplate)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[EarningCode](#EarningCode)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[EarningDate](#EarningDate)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[EarningRate](#EarningRate)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[EarningStatement](#EarningStatement)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[GenerationSource](#GenerationSource)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[isEdited](#isEdited)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[IsManual](#IsManual)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Note](#Note)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[PaymentStatus](#PaymentStatus)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[PayStatementEarningLine](#PayStatementEarningLine)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Position](#Position)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[ProjActivityNumber](#ProjActivityNumber)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[ProjCategoryId](#ProjCategoryId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[ProjId](#ProjId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[ProjLinePropertyId](#ProjLinePropertyId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Quantity](#Quantity)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[WorkerCompensationBenefit](#WorkerCompensationBenefit)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[WorkerGLIBenefit](#WorkerGLIBenefit)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[WorkerTaxRegion](#WorkerTaxRegion)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[OriginatingEarningStatementLine](#OriginatingEarningStatementLine)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[PremiumEarningCode](#PremiumEarningCode)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[RetroactivePriorRate](#RetroactivePriorRate)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[WorkPeriod](#WorkPeriod)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[LineNum](#LineNum)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[DataAreaId](#DataAreaId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_AccountingDistributionTemplateRelationshipId](#Relationship_AccountingDistributionTemplateRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_ActivityNumberRelationshipId](#Relationship_ActivityNumberRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_EarningStatementRelationshipId](#Relationship_EarningStatementRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_LinePropertyIdRelationshipId](#Relationship_LinePropertyIdRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_PayStatementEarningLineRelationshipId](#Relationship_PayStatementEarningLineRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_ProjCategoryIdRelationshipId](#Relationship_ProjCategoryIdRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_ProjIdRelationshipId](#Relationship_ProjIdRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_SourceDocumentLineRelationshipId](#Relationship_SourceDocumentLineRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_PremiumEarningCodeRelationshipId](#Relationship_PremiumEarningCodeRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_WorkPeriodRelationshipId](#Relationship_WorkPeriodRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PayrollEarningStatementLine.md" target="_blank">WorksheetLine/PayrollEarningStatementLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollEarningStatementLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingCurrencyAmount name="AccountingCurrencyAmount">AccountingCurrencyAmount</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accounting date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#AccountingDistributionTemplate name="AccountingDistributionTemplate">AccountingDistributionTemplate</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Template ID</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Template ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EarningCode name="EarningCode">EarningCode</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EarningDate name="EarningDate">EarningDate</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Earnings date</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Earnings date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#EarningRate name="EarningRate">EarningRate</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EarningStatement name="EarningStatement">EarningStatement</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningStatement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GenerationSource name="GenerationSource">GenerationSource</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerationSource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#isEdited name="isEdited">isEdited</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line modified</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isEdited attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line modified</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsManual name="IsManual">IsManual</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsManual attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manual</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

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

### <a href=#PaymentStatus name="PaymentStatus">PaymentStatus</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PayStatementEarningLine name="PayStatementEarningLine">PayStatementEarningLine</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatementEarningLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProjActivityNumber name="ProjActivityNumber">ProjActivityNumber</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjCategoryId name="ProjCategoryId">ProjCategoryId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjLinePropertyId name="ProjLinePropertyId">ProjLinePropertyId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjLinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkerCompensationBenefit name="WorkerCompensationBenefit">WorkerCompensationBenefit</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Workers' compensation code</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerCompensationBenefit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workers' compensation code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkerGLIBenefit name="WorkerGLIBenefit">WorkerGLIBenefit</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>General liability insurance</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerGLIBenefit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>General liability insurance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkerTaxRegion name="WorkerTaxRegion">WorkerTaxRegion</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTaxRegion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OriginatingEarningStatementLine name="OriginatingEarningStatementLine">OriginatingEarningStatementLine</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating earning statement line</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingEarningStatementLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Originating earning statement line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PremiumEarningCode name="PremiumEarningCode">PremiumEarningCode</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetroactivePriorRate name="RetroactivePriorRate">RetroactivePriorRate</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original retroactive rate</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetroactivePriorRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original retroactive rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WorkPeriod name="WorkPeriod">WorkPeriod</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccountingDistributionTemplateRelationshipId name="Relationship_AccountingDistributionTemplateRelationshipId">Relationship_AccountingDistributionTemplateRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountingDistributionTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/AccountingDistributionTemplate.cdm.json/AccountingDistributionTemplate</a></td><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ActivityNumberRelationshipId name="Relationship_ActivityNumberRelationshipId">Relationship_ActivityNumberRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ActivityNumberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjActivity.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjActivity.cdm.json/ProjActivity</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjActivity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EarningStatementRelationshipId name="Relationship_EarningStatementRelationshipId">Relationship_EarningStatementRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EarningStatementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PayrollEarningStatement.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/WorksheetHeader/PayrollEarningStatement.cdm.json/PayrollEarningStatement</a></td><td><a href="../WorksheetHeader/PayrollEarningStatement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LinePropertyIdRelationshipId name="Relationship_LinePropertyIdRelationshipId">Relationship_LinePropertyIdRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LinePropertyIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.cdm.json/ProjLineProperty</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayStatementEarningLineRelationshipId name="Relationship_PayStatementEarningLineRelationshipId">Relationship_PayStatementEarningLineRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayStatementEarningLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PayrollPayStatementEarningLine.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementEarningLine.cdm.json/PayrollPayStatementEarningLine</a></td><td><a href="PayrollPayStatementEarningLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategoryIdRelationshipId name="Relationship_ProjCategoryIdRelationshipId">Relationship_ProjCategoryIdRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategoryIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjIdRelationshipId name="Relationship_ProjIdRelationshipId">Relationship_ProjIdRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentLineRelationshipId name="Relationship_SourceDocumentLineRelationshipId">Relationship_SourceDocumentLineRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.cdm.json/SourceDocumentLine</a></td><td><a href="../../../Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PremiumEarningCodeRelationshipId name="Relationship_PremiumEarningCodeRelationshipId">Relationship_PremiumEarningCodeRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PremiumEarningCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/PayrollPremiumEarningCode.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollPremiumEarningCode.cdm.json/PayrollPremiumEarningCode</a></td><td><a href="../Reference/PayrollPremiumEarningCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkPeriodRelationshipId name="Relationship_WorkPeriodRelationshipId">Relationship_WorkPeriodRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkPeriodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/PayrollWorkPeriod.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Miscellaneous/PayrollWorkPeriod.cdm.json/PayrollWorkPeriod</a></td><td><a href="../Miscellaneous/PayrollWorkPeriod.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/PayrollEarningStatementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
