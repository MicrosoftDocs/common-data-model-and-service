---
title: LedgerAccrualSchemesEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# LedgerAccrualSchemesEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Finance/GeneralLedger/LedgerAccrualSchemesEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AccrualIdentification](#AccrualIdentification)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[AccrualSchemeDescription](#AccrualSchemeDescription)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[DebitLedgerDimensionDisplayValue](#DebitLedgerDimensionDisplayValue)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[CreditLedgerDimensionDisplayValue](#CreditLedgerDimensionDisplayValue)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[Voucher](#Voucher)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[CreditLedgerDimension](#CreditLedgerDimension)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[DebitLedgerDimension](#DebitLedgerDimension)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[TransactionDescription](#TransactionDescription)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[AccrualBasis](#AccrualBasis)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberOfOccurrencesPerPeriod](#NumberOfOccurrencesPerPeriod)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[PeriodType](#PeriodType)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[PeriodKey](#PeriodKey)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[PostTransactions](#PostTransactions)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[PostInWeekMonthOrQuarter](#PostInWeekMonthOrQuarter)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[SpreadMonthAndQuarterValues](#SpreadMonthAndQuarterValues)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberSequenceTable_NumberSequence](#NumberSequenceTable_NumberSequence)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberSequenceTable_NumberSequenceScope](#NumberSequenceTable_NumberSequenceScope)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberSequenceScope_DataArea](#NumberSequenceScope_DataArea)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberSequenceScope_FiscalCalendarPeriod](#NumberSequenceScope_FiscalCalendarPeriod)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberSequenceScope_LegalEntity](#NumberSequenceScope_LegalEntity)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberSequenceScope_OperatingUnit](#NumberSequenceScope_OperatingUnit)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberSequenceScope_OperatingUnitType](#NumberSequenceScope_OperatingUnitType)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[FiscalCalendarPeriod_FiscalCalendarYear](#FiscalCalendarPeriod_FiscalCalendarYear)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[FiscalCalendarPeriod_Name](#FiscalCalendarPeriod_Name)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[FiscalCalendarYear_FiscalCalendar](#FiscalCalendarYear_FiscalCalendar)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[FiscalCalendarYear_Name](#FiscalCalendarYear_Name)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[FiscalCalendar_CalendarId](#FiscalCalendar_CalendarId)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[LegalEntity_PartyNumber](#LegalEntity_PartyNumber)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[LegalEntity_DataArea](#LegalEntity_DataArea)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[OperatingUnit_PartyNumber](#OperatingUnit_PartyNumber)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[NumberSequenceTable](#NumberSequenceTable)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[CalendarPeriodFrequency](#CalendarPeriodFrequency)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[FiscalPeriodFrequency](#FiscalPeriodFrequency)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[Relationship_CreditLedgerDimensionCombinationRelationshipId](#Relationship_CreditLedgerDimensionCombinationRelationshipId)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[Relationship_DebitLedgerDimensionCombinationRelationshipId](#Relationship_DebitLedgerDimensionCombinationRelationshipId)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[BackingTable_LedgerAccrualTableRelationshipId](#BackingTable_LedgerAccrualTableRelationshipId)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerAccrualSchemesEntity.md" target="_blank">GeneralLedger/LedgerAccrualSchemesEntity</a>|

### <a href=#AccrualIdentification name="AccrualIdentification">AccrualIdentification</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualIdentification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualSchemeDescription name="AccrualSchemeDescription">AccrualSchemeDescription</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualSchemeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitLedgerDimensionDisplayValue name="DebitLedgerDimensionDisplayValue">DebitLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLedgerDimensionDisplayValue name="CreditLedgerDimensionDisplayValue">CreditLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLedgerDimension name="CreditLedgerDimension">CreditLedgerDimension</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitLedgerDimension name="DebitLedgerDimension">DebitLedgerDimension</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDescription name="TransactionDescription">TransactionDescription</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualBasis name="AccrualBasis">AccrualBasis</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfOccurrencesPerPeriod name="NumberOfOccurrencesPerPeriod">NumberOfOccurrencesPerPeriod</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfOccurrencesPerPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodType name="PeriodType">PeriodType</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodKey name="PeriodKey">PeriodKey</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostTransactions name="PostTransactions">PostTransactions</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostInWeekMonthOrQuarter name="PostInWeekMonthOrQuarter">PostInWeekMonthOrQuarter</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostInWeekMonthOrQuarter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpreadMonthAndQuarterValues name="SpreadMonthAndQuarterValues">SpreadMonthAndQuarterValues</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpreadMonthAndQuarterValues attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceTable_NumberSequence name="NumberSequenceTable_NumberSequence">NumberSequenceTable_NumberSequence</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceTable_NumberSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceTable_NumberSequenceScope name="NumberSequenceTable_NumberSequenceScope">NumberSequenceTable_NumberSequenceScope</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceTable_NumberSequenceScope attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceScope_DataArea name="NumberSequenceScope_DataArea">NumberSequenceScope_DataArea</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceScope_DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceScope_FiscalCalendarPeriod name="NumberSequenceScope_FiscalCalendarPeriod">NumberSequenceScope_FiscalCalendarPeriod</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceScope_FiscalCalendarPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceScope_LegalEntity name="NumberSequenceScope_LegalEntity">NumberSequenceScope_LegalEntity</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceScope_LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceScope_OperatingUnit name="NumberSequenceScope_OperatingUnit">NumberSequenceScope_OperatingUnit</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceScope_OperatingUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceScope_OperatingUnitType name="NumberSequenceScope_OperatingUnitType">NumberSequenceScope_OperatingUnitType</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceScope_OperatingUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarPeriod_FiscalCalendarYear name="FiscalCalendarPeriod_FiscalCalendarYear">FiscalCalendarPeriod_FiscalCalendarYear</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarPeriod_FiscalCalendarYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarPeriod_Name name="FiscalCalendarPeriod_Name">FiscalCalendarPeriod_Name</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarPeriod_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarYear_FiscalCalendar name="FiscalCalendarYear_FiscalCalendar">FiscalCalendarYear_FiscalCalendar</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYear_FiscalCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarYear_Name name="FiscalCalendarYear_Name">FiscalCalendarYear_Name</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYear_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendar_CalendarId name="FiscalCalendar_CalendarId">FiscalCalendar_CalendarId</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendar_CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity_PartyNumber name="LegalEntity_PartyNumber">LegalEntity_PartyNumber</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity_PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity_DataArea name="LegalEntity_DataArea">LegalEntity_DataArea</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity_DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnit_PartyNumber name="OperatingUnit_PartyNumber">OperatingUnit_PartyNumber</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnit_PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceTable name="NumberSequenceTable">NumberSequenceTable</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarPeriodFrequency name="CalendarPeriodFrequency">CalendarPeriodFrequency</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarPeriodFrequency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPeriodFrequency name="FiscalPeriodFrequency">FiscalPeriodFrequency</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPeriodFrequency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CreditLedgerDimensionCombinationRelationshipId name="Relationship_CreditLedgerDimensionCombinationRelationshipId">Relationship_CreditLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CreditLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DebitLedgerDimensionCombinationRelationshipId name="Relationship_DebitLedgerDimensionCombinationRelationshipId">Relationship_DebitLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DebitLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerAccrualTableRelationshipId name="BackingTable_LedgerAccrualTableRelationshipId">BackingTable_LedgerAccrualTableRelationshipId</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerAccrualTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/LedgerAccrualTable.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/LedgerAccrualTable.cdm.json/LedgerAccrualTable</a></td><td><a href="../../../Tables/Finance/Ledger/Main/LedgerAccrualTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerAccrualSchemesEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
