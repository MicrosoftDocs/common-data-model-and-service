---
title: MCRReqPlanContinuityEntity in TransactionsAndOrders - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Continuity plan setup in TransactionsAndOrders(MCRReqPlanContinuityEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/TransactionsAndOrders/MCRReqPlanContinuityEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Continuity plan setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IssueMargin](#IssueMargin)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[Name](#Name)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[OrderingMargin](#OrderingMargin)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderSequenceRecId](#PlannedOrderSequenceRecId)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[ReceiptMargin](#ReceiptMargin)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredPlanIdContinuity](#RequiredPlanIdContinuity)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredPlanSequenceRecId](#RequiredPlanSequenceRecId)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[SkipCoverageCalculations](#SkipCoverageCalculations)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[TimeFenceCapacity](#TimeFenceCapacity)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[TimeFenceCoverage](#TimeFenceCoverage)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[TimeFenceExplosion](#TimeFenceExplosion)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[UseProbabalisticContinuity](#UseProbabalisticContinuity)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderNumberSequence](#PlannedOrderNumberSequence)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderTableNumberSequenceScope](#PlannedOrderTableNumberSequenceScope)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderScopeDataArea](#PlannedOrderScopeDataArea)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderScopeFiscalCalendarPeriod](#PlannedOrderScopeFiscalCalendarPeriod)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderScopeLegalEntity](#PlannedOrderScopeLegalEntity)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderScopeOperatingUnit](#PlannedOrderScopeOperatingUnit)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderScopeOperatingUnitType](#PlannedOrderScopeOperatingUnitType)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderPeriodFiscalCalendarYear](#PlannedOrderPeriodFiscalCalendarYear)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderPeriodName](#PlannedOrderPeriodName)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderYearFiscalCalendar](#PlannedOrderYearFiscalCalendar)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderYearName](#PlannedOrderYearName)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderCalendarId](#PlannedOrderCalendarId)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderCompanyInfoPartyNumber](#PlannedOrderCompanyInfoPartyNumber)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderCompanyInfoDataArea](#PlannedOrderCompanyInfoDataArea)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[PlannedOrderOMOperatingUnitPartyNumber](#PlannedOrderOMOperatingUnitPartyNumber)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogNumberSequence](#RequiredLogNumberSequence)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogNumberSequenceScope](#RequiredLogNumberSequenceScope)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogDataArea](#RequiredLogDataArea)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogFiscalCalendarPeriod](#RequiredLogFiscalCalendarPeriod)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogLegalEntity](#RequiredLogLegalEntity)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogOperatingUnit](#RequiredLogOperatingUnit)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogOperatingUnitType](#RequiredLogOperatingUnitType)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogPeriodFiscalCalendarYear](#RequiredLogPeriodFiscalCalendarYear)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogPeriodName](#RequiredLogPeriodName)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogYearFiscalCalendar](#RequiredLogYearFiscalCalendar)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogYearName](#RequiredLogYearName)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogCalendarId](#RequiredLogCalendarId)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogCompanyInfoPartyNumber](#RequiredLogCompanyInfoPartyNumber)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogCompanyInfoDataArea](#RequiredLogCompanyInfoDataArea)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[RequiredLogOMOperatingUnitPartyNumber](#RequiredLogOMOperatingUnitPartyNumber)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[BackingTable_MCRReqPlanContinuityRelationshipId](#BackingTable_MCRReqPlanContinuityRelationshipId)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="MCRReqPlanContinuityEntity.md" target="_blank">TransactionsAndOrders/MCRReqPlanContinuityEntity</a>|

### <a href=#IssueMargin name="IssueMargin">IssueMargin</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueMargin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

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

### <a href=#OrderingMargin name="OrderingMargin">OrderingMargin</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingMargin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderSequenceRecId name="PlannedOrderSequenceRecId">PlannedOrderSequenceRecId</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptMargin name="ReceiptMargin">ReceiptMargin</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptMargin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredPlanIdContinuity name="RequiredPlanIdContinuity">RequiredPlanIdContinuity</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredPlanIdContinuity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredPlanSequenceRecId name="RequiredPlanSequenceRecId">RequiredPlanSequenceRecId</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredPlanSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipCoverageCalculations name="SkipCoverageCalculations">SkipCoverageCalculations</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipCoverageCalculations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeFenceCapacity name="TimeFenceCapacity">TimeFenceCapacity</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceCapacity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeFenceCoverage name="TimeFenceCoverage">TimeFenceCoverage</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceCoverage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeFenceExplosion name="TimeFenceExplosion">TimeFenceExplosion</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceExplosion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseProbabalisticContinuity name="UseProbabalisticContinuity">UseProbabalisticContinuity</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseProbabalisticContinuity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderNumberSequence name="PlannedOrderNumberSequence">PlannedOrderNumberSequence</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderNumberSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderTableNumberSequenceScope name="PlannedOrderTableNumberSequenceScope">PlannedOrderTableNumberSequenceScope</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderTableNumberSequenceScope attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderScopeDataArea name="PlannedOrderScopeDataArea">PlannedOrderScopeDataArea</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderScopeDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderScopeFiscalCalendarPeriod name="PlannedOrderScopeFiscalCalendarPeriod">PlannedOrderScopeFiscalCalendarPeriod</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderScopeFiscalCalendarPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderScopeLegalEntity name="PlannedOrderScopeLegalEntity">PlannedOrderScopeLegalEntity</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderScopeLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderScopeOperatingUnit name="PlannedOrderScopeOperatingUnit">PlannedOrderScopeOperatingUnit</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderScopeOperatingUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderScopeOperatingUnitType name="PlannedOrderScopeOperatingUnitType">PlannedOrderScopeOperatingUnitType</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderScopeOperatingUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderPeriodFiscalCalendarYear name="PlannedOrderPeriodFiscalCalendarYear">PlannedOrderPeriodFiscalCalendarYear</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderPeriodFiscalCalendarYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderPeriodName name="PlannedOrderPeriodName">PlannedOrderPeriodName</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderPeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderYearFiscalCalendar name="PlannedOrderYearFiscalCalendar">PlannedOrderYearFiscalCalendar</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderYearFiscalCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderYearName name="PlannedOrderYearName">PlannedOrderYearName</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderYearName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderCalendarId name="PlannedOrderCalendarId">PlannedOrderCalendarId</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderCompanyInfoPartyNumber name="PlannedOrderCompanyInfoPartyNumber">PlannedOrderCompanyInfoPartyNumber</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderCompanyInfoPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderCompanyInfoDataArea name="PlannedOrderCompanyInfoDataArea">PlannedOrderCompanyInfoDataArea</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderCompanyInfoDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderOMOperatingUnitPartyNumber name="PlannedOrderOMOperatingUnitPartyNumber">PlannedOrderOMOperatingUnitPartyNumber</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderOMOperatingUnitPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogNumberSequence name="RequiredLogNumberSequence">RequiredLogNumberSequence</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogNumberSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogNumberSequenceScope name="RequiredLogNumberSequenceScope">RequiredLogNumberSequenceScope</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogNumberSequenceScope attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogDataArea name="RequiredLogDataArea">RequiredLogDataArea</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogFiscalCalendarPeriod name="RequiredLogFiscalCalendarPeriod">RequiredLogFiscalCalendarPeriod</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogFiscalCalendarPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogLegalEntity name="RequiredLogLegalEntity">RequiredLogLegalEntity</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogOperatingUnit name="RequiredLogOperatingUnit">RequiredLogOperatingUnit</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogOperatingUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogOperatingUnitType name="RequiredLogOperatingUnitType">RequiredLogOperatingUnitType</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogOperatingUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogPeriodFiscalCalendarYear name="RequiredLogPeriodFiscalCalendarYear">RequiredLogPeriodFiscalCalendarYear</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogPeriodFiscalCalendarYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogPeriodName name="RequiredLogPeriodName">RequiredLogPeriodName</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogPeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogYearFiscalCalendar name="RequiredLogYearFiscalCalendar">RequiredLogYearFiscalCalendar</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogYearFiscalCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogYearName name="RequiredLogYearName">RequiredLogYearName</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogYearName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogCalendarId name="RequiredLogCalendarId">RequiredLogCalendarId</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogCompanyInfoPartyNumber name="RequiredLogCompanyInfoPartyNumber">RequiredLogCompanyInfoPartyNumber</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogCompanyInfoPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogCompanyInfoDataArea name="RequiredLogCompanyInfoDataArea">RequiredLogCompanyInfoDataArea</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogCompanyInfoDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredLogOMOperatingUnitPartyNumber name="RequiredLogOMOperatingUnitPartyNumber">RequiredLogOMOperatingUnitPartyNumber</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredLogOMOperatingUnitPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_MCRReqPlanContinuityRelationshipId name="BackingTable_MCRReqPlanContinuityRelationshipId">BackingTable_MCRReqPlanContinuityRelationshipId</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MCRReqPlanContinuityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Main/MCRReqPlanContinuity.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/MCRReqPlanContinuity.cdm.json/MCRReqPlanContinuity</a></td><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Main/MCRReqPlanContinuity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TransactionsAndOrders/MCRReqPlanContinuityEntity (this entity)  

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
