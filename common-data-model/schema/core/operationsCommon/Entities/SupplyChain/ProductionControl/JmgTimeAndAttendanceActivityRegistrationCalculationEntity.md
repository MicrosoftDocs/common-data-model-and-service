---
title: JmgTimeAndAttendanceActivityRegistrationCalculationEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Time and attendance activity registration calculations in ProductionControl(JmgTimeAndAttendanceActivityRegistrationCalculationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time and attendance activity registration calculations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultDimension](#DefaultDimension)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[ErrorLogText](#ErrorLogText)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[HasErrors](#HasErrors)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[IsApproved](#IsApproved)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[IsCalculated](#IsCalculated)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[IsClockInToleranceDropped](#IsClockInToleranceDropped)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[IsClockOutToleranceDropped](#IsClockOutToleranceDropped)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[IsFlexTimeAllowed](#IsFlexTimeAllowed)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[IsTimeProfileChanged](#IsTimeProfileChanged)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[IsTransferred](#IsTransferred)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[PayAgreementId](#PayAgreementId)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[PayEndDate](#PayEndDate)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[PayEndTime](#PayEndTime)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[PayStartTime](#PayStartTime)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[PayStartDate](#PayStartDate)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeAndAttendanceApprovalGroupId](#TimeAndAttendanceApprovalGroupId)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeAndAttendanceCalculationGroupId](#TimeAndAttendanceCalculationGroupId)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileDate](#TimeProfileDate)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileEndTime](#TimeProfileEndTime)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileEndDate](#TimeProfileEndDate)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileId](#TimeProfileId)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileNormFlexTimeSeconds](#TimeProfileNormFlexTimeSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileNormSeconds](#TimeProfileNormSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileSeconds](#TimeProfileSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileStartTime](#TimeProfileStartTime)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TimeProfileStartDate](#TimeProfileStartDate)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalNonPaidBreakSeconds](#TotalNonPaidBreakSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPaidBreakSeconds](#TotalPaidBreakSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPayAbsenceSeconds](#TotalPayAbsenceSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPayFlexTimeAddSeconds](#TotalPayFlexTimeAddSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPayFlexTimeBalanceSeconds](#TotalPayFlexTimeBalanceSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPayFlexTimeCorrectionSeconds](#TotalPayFlexTimeCorrectionSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPayFlexTimeSubSeconds](#TotalPayFlexTimeSubSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPayIllegalAbsenceSeconds](#TotalPayIllegalAbsenceSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPayLegalAbsenceSeconds](#TotalPayLegalAbsenceSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPayOverTimeSeconds](#TotalPayOverTimeSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalPaySeconds](#TotalPaySeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalWorkSeconds](#TotalWorkSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TotalWorkSecondsNotAllocated](#TotalWorkSecondsNotAllocated)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[WorkEndTime](#WorkEndTime)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[WorkEndDate](#WorkEndDate)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[WorkflowStatus](#WorkflowStatus)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[WorkStartTime](#WorkStartTime)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[WorkStartDate](#WorkStartDate)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[WorkerPersonnelNumber](#WorkerPersonnelNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[ApproverPersonnelNumber](#ApproverPersonnelNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[CalculatorPersonnelNumber](#CalculatorPersonnelNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[TransferrerPeronnelNumber](#TransferrerPeronnelNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[BackingTable_JmgStampJournalTableRelationshipId](#BackingTable_JmgStampJournalTableRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationCalculationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity</a>|

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorLogText name="ErrorLogText">ErrorLogText</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Error log text</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorLogText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Error log text</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasErrors name="HasErrors">HasErrors</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has error</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasErrors attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has error</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsApproved name="IsApproved">IsApproved</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsApproved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCalculated name="IsCalculated">IsCalculated</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsClockInToleranceDropped name="IsClockInToleranceDropped">IsClockInToleranceDropped</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsClockInToleranceDropped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsClockOutToleranceDropped name="IsClockOutToleranceDropped">IsClockOutToleranceDropped</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsClockOutToleranceDropped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlexTimeAllowed name="IsFlexTimeAllowed">IsFlexTimeAllowed</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexTimeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTimeProfileChanged name="IsTimeProfileChanged">IsTimeProfileChanged</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTimeProfileChanged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransferred name="IsTransferred">IsTransferred</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransferred attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayAgreementId name="PayAgreementId">PayAgreementId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayEndDate name="PayEndDate">PayEndDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pay end date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay end date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayEndTime name="PayEndTime">PayEndTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pay end time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay end time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStartTime name="PayStartTime">PayStartTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pay start time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay start time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStartDate name="PayStartDate">PayStartDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pay start date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay start date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceApprovalGroupId name="TimeAndAttendanceApprovalGroupId">TimeAndAttendanceApprovalGroupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceApprovalGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceCalculationGroupId name="TimeAndAttendanceCalculationGroupId">TimeAndAttendanceCalculationGroupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceCalculationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileDate name="TimeProfileDate">TimeProfileDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile date</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileEndTime name="TimeProfileEndTime">TimeProfileEndTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile end time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile end time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileEndDate name="TimeProfileEndDate">TimeProfileEndDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile end date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile end date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileId name="TimeProfileId">TimeProfileId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileNormFlexTimeSeconds name="TimeProfileNormFlexTimeSeconds">TimeProfileNormFlexTimeSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile norm flex time seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileNormFlexTimeSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile norm flex time seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileNormSeconds name="TimeProfileNormSeconds">TimeProfileNormSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile norm seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileNormSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile norm seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileSeconds name="TimeProfileSeconds">TimeProfileSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileStartTime name="TimeProfileStartTime">TimeProfileStartTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile start time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile start time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileStartDate name="TimeProfileStartDate">TimeProfileStartDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time profile start date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time profile start date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalNonPaidBreakSeconds name="TotalNonPaidBreakSeconds">TotalNonPaidBreakSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total non paid break seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalNonPaidBreakSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total non paid break seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPaidBreakSeconds name="TotalPaidBreakSeconds">TotalPaidBreakSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total paid break seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPaidBreakSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total paid break seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayAbsenceSeconds name="TotalPayAbsenceSeconds">TotalPayAbsenceSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay absence seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayAbsenceSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay absence seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayFlexTimeAddSeconds name="TotalPayFlexTimeAddSeconds">TotalPayFlexTimeAddSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay flex time add seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayFlexTimeAddSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay flex time add seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayFlexTimeBalanceSeconds name="TotalPayFlexTimeBalanceSeconds">TotalPayFlexTimeBalanceSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay flex time balance seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayFlexTimeBalanceSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay flex time balance seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayFlexTimeCorrectionSeconds name="TotalPayFlexTimeCorrectionSeconds">TotalPayFlexTimeCorrectionSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay flex time correction seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayFlexTimeCorrectionSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay flex time correction seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayFlexTimeSubSeconds name="TotalPayFlexTimeSubSeconds">TotalPayFlexTimeSubSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay flex time sub seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayFlexTimeSubSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay flex time sub seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayIllegalAbsenceSeconds name="TotalPayIllegalAbsenceSeconds">TotalPayIllegalAbsenceSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay illegal absence seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayIllegalAbsenceSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay illegal absence seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayLegalAbsenceSeconds name="TotalPayLegalAbsenceSeconds">TotalPayLegalAbsenceSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay legal absence seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayLegalAbsenceSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay legal absence seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayOverTimeSeconds name="TotalPayOverTimeSeconds">TotalPayOverTimeSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay overtime seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayOverTimeSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay overtime seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPaySeconds name="TotalPaySeconds">TotalPaySeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total pay seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPaySeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total pay seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalWorkSeconds name="TotalWorkSeconds">TotalWorkSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total work seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalWorkSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total work seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalWorkSecondsNotAllocated name="TotalWorkSecondsNotAllocated">TotalWorkSecondsNotAllocated</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total work seconds not allocated</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalWorkSecondsNotAllocated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total work seconds not allocated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkEndTime name="WorkEndTime">WorkEndTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work end time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Work end time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkEndDate name="WorkEndDate">WorkEndDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work end date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Work end date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowStatus name="WorkflowStatus">WorkflowStatus</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkStartTime name="WorkStartTime">WorkStartTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work start time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Work start time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkStartDate name="WorkStartDate">WorkStartDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work start date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Work start date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerPersonnelNumber name="WorkerPersonnelNumber">WorkerPersonnelNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Worker personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Worker personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApproverPersonnelNumber name="ApproverPersonnelNumber">ApproverPersonnelNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Approver personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproverPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Approver personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculatorPersonnelNumber name="CalculatorPersonnelNumber">CalculatorPersonnelNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculator personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatorPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculator personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferrerPeronnelNumber name="TransferrerPeronnelNumber">TransferrerPeronnelNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transferrer personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferrerPeronnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transferrer personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

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

### <a href=#BackingTable_JmgStampJournalTableRelationshipId name="BackingTable_JmgStampJournalTableRelationshipId">BackingTable_JmgStampJournalTableRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgStampJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetHeader/JmgStampJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetHeader/JmgStampJournalTable.cdm.json/JmgStampJournalTable</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetHeader/JmgStampJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationCalculationEntity (this entity)  

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
