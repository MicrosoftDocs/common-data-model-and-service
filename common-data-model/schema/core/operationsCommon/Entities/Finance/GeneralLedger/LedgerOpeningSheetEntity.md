---
title: LedgerOpeningSheetEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Opening sheets in GeneralLedger(LedgerOpeningSheetEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerOpeningSheetEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Opening sheets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Sheet](#Sheet)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Name](#Name)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[FromDate](#FromDate)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[ToDate](#ToDate)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[PostDate](#PostDate)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[AcknowledgementDate](#AcknowledgementDate)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[CurrentOperationsTax](#CurrentOperationsTax)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[PeriodCode](#PeriodCode)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[FiscalCalendarPeriodName](#FiscalCalendarPeriodName)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[FiscalCalendarYearName](#FiscalCalendarYearName)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[FiscalCalendarCalendarId](#FiscalCalendarCalendarId)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Voucher](#Voucher)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[SumTrialBalance](#SumTrialBalance)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[SumTransfer](#SumTransfer)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[SumResult](#SumResult)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[SumBalance](#SumBalance)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[SumCapital](#SumCapital)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[AccountType](#AccountType)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[LedgerOpeningTableMainAccountIdDisplayValue](#LedgerOpeningTableMainAccountIdDisplayValue)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[LedgerOpeningTableChartOfAccountsName](#LedgerOpeningTableChartOfAccountsName)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Transfer](#Transfer)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[TrialBalance](#TrialBalance)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Reconciled](#Reconciled)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Result](#Result)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Balance](#Balance)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Capital](#Capital)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[LineNum](#LineNum)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[OperationsTax](#OperationsTax)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Txt](#Txt)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[LedgerOpeningTransMainAccountMainAccountIdDisplayValue](#LedgerOpeningTransMainAccountMainAccountIdDisplayValue)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[LedgerOpeningTransMainAccountChartOfAccountName](#LedgerOpeningTransMainAccountChartOfAccountName)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[LedgerAccountDisplayValue](#LedgerAccountDisplayValue)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Amount](#Amount)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[LedgerOpeningTransOffsetAccountMainAccountId](#LedgerOpeningTransOffsetAccountMainAccountId)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[LedgerOpeningTransOffsetAccountChartOfAccountName](#LedgerOpeningTransOffsetAccountChartOfAccountName)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[OffsetAccountDisplayValue](#OffsetAccountDisplayValue)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[BackingTable_LedgerOpeningSheet_ESRelationshipId](#BackingTable_LedgerOpeningSheet_ESRelationshipId)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerOpeningSheetEntity.md" target="_blank">GeneralLedger/LedgerOpeningSheetEntity</a>|

### <a href=#Sheet name="Sheet">Sheet</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

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

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostDate name="PostDate">PostDate</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcknowledgementDate name="AcknowledgementDate">AcknowledgementDate</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcknowledgementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentOperationsTax name="CurrentOperationsTax">CurrentOperationsTax</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentOperationsTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodCode name="PeriodCode">PeriodCode</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarPeriodName name="FiscalCalendarPeriodName">FiscalCalendarPeriodName</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarPeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarYearName name="FiscalCalendarYearName">FiscalCalendarYearName</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYearName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarCalendarId name="FiscalCalendarCalendarId">FiscalCalendarCalendarId</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumTrialBalance name="SumTrialBalance">SumTrialBalance</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTrialBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumTransfer name="SumTransfer">SumTransfer</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTransfer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumResult name="SumResult">SumResult</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumResult attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumBalance name="SumBalance">SumBalance</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumCapital name="SumCapital">SumCapital</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumCapital attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerOpeningTableMainAccountIdDisplayValue name="LedgerOpeningTableMainAccountIdDisplayValue">LedgerOpeningTableMainAccountIdDisplayValue</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerOpeningTableMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerOpeningTableChartOfAccountsName name="LedgerOpeningTableChartOfAccountsName">LedgerOpeningTableChartOfAccountsName</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerOpeningTableChartOfAccountsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transfer name="Transfer">Transfer</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transfer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrialBalance name="TrialBalance">TrialBalance</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrialBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reconciled name="Reconciled">Reconciled</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reconciled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Result name="Result">Result</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Result attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Balance name="Balance">Balance</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Balance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Capital name="Capital">Capital</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Capital attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

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

### <a href=#OperationsTax name="OperationsTax">OperationsTax</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerOpeningTransMainAccountMainAccountIdDisplayValue name="LedgerOpeningTransMainAccountMainAccountIdDisplayValue">LedgerOpeningTransMainAccountMainAccountIdDisplayValue</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerOpeningTransMainAccountMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerOpeningTransMainAccountChartOfAccountName name="LedgerOpeningTransMainAccountChartOfAccountName">LedgerOpeningTransMainAccountChartOfAccountName</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerOpeningTransMainAccountChartOfAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccountDisplayValue name="LedgerAccountDisplayValue">LedgerAccountDisplayValue</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerOpeningTransOffsetAccountMainAccountId name="LedgerOpeningTransOffsetAccountMainAccountId">LedgerOpeningTransOffsetAccountMainAccountId</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerOpeningTransOffsetAccountMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerOpeningTransOffsetAccountChartOfAccountName name="LedgerOpeningTransOffsetAccountChartOfAccountName">LedgerOpeningTransOffsetAccountChartOfAccountName</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerOpeningTransOffsetAccountChartOfAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountDisplayValue name="OffsetAccountDisplayValue">OffsetAccountDisplayValue</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerOpeningSheet_ESRelationshipId name="BackingTable_LedgerOpeningSheet_ESRelationshipId">BackingTable_LedgerOpeningSheet_ESRelationshipId</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerOpeningSheet_ESRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/WorksheetHeader/LedgerOpeningSheet_ES.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/WorksheetHeader/LedgerOpeningSheet_ES.cdm.json/LedgerOpeningSheet_ES</a></td><td><a href="../../../Tables/Finance/Ledger/WorksheetHeader/LedgerOpeningSheet_ES.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerOpeningSheetEntity (this entity)  

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
