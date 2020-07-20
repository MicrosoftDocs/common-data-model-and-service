---
title: JmgTimeAndAttendanceActivityRegistrationEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Time and attendance activity registrations in ProductionControl(JmgTimeAndAttendanceActivityRegistrationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time and attendance activity registrations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AbsencePayUnits](#AbsencePayUnits)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[IsWorkInProgress](#IsWorkInProgress)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[IndirectActivityName](#IndirectActivityName)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[BreakSeconds](#BreakSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[BreakToleranceSeconds](#BreakToleranceSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[CorrectedStartDate](#CorrectedStartDate)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[CorrectedStartTime](#CorrectedStartTime)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[CorrectedEndDate](#CorrectedEndDate)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[CorrectedEndTime](#CorrectedEndTime)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ErrorCause](#ErrorCause)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ErrorSpecification](#ErrorSpecification)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[IsJobFinished](#IsJobFinished)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[TimeAndAttendanceJobId](#TimeAndAttendanceJobId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[AbsenceCodeTimeAndAttendanceJobId](#AbsenceCodeTimeAndAttendanceJobId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[JobPayRateMethod](#JobPayRateMethod)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ActivityType](#ActivityType)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[TimeAllocationType](#TimeAllocationType)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[JournalRegistrationType](#JournalRegistrationType)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ErrorLogText](#ErrorLogText)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[OnCallTimeAndAttendanceJobId](#OnCallTimeAndAttendanceJobId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[OperationNumber](#OperationNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ReportedErrorCatchWeightQuantity](#ReportedErrorCatchWeightQuantity)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ReportedGoodCatchWeightQuantity](#ReportedGoodCatchWeightQuantity)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartedCatchWeightQuantity](#StartedCatchWeightQuantity)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[TimeProfileDate](#TimeProfileDate)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ReportedErrorQuantity](#ReportedErrorQuantity)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ReportedGoodQuantity](#ReportedGoodQuantity)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartedQuantity](#StartedQuantity)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[RouteJobType](#RouteJobType)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[CalculatedTimeSeconds](#CalculatedTimeSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[CalculatedTimeBeforeAllocationSeconds](#CalculatedTimeBeforeAllocationSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[CalculatedTimeAfterAllocationSeconds](#CalculatedTimeAfterAllocationSeconds)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[RegistrationType](#RegistrationType)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[RegistrationSubType](#RegistrationSubType)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartDate](#StartDate)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartTime](#StartTime)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[EndDate](#EndDate)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[EndStopTime](#EndStopTime)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartRegistrationTerminalId](#StartRegistrationTerminalId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[StopRegistrationTerminalId](#StopRegistrationTerminalId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[WorkflowStatus](#WorkflowStatus)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[OperationsResourceId](#OperationsResourceId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[OperationsResourcePilotId](#OperationsResourcePilotId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[WorkerPersonnelNumber](#WorkerPersonnelNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[PilotPersonnelNumber](#PilotPersonnelNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ActivityRegistrationTransactionId](#ActivityRegistrationTransactionId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ActivityRegistrationEntryNumber](#ActivityRegistrationEntryNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[ProjectId](#ProjectId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[IndirectActivityCategoryId](#IndirectActivityCategoryId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[Relationship_PilotWorkerRelationshipId](#Relationship_PilotWorkerRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[BackingTable_JmgStampJournalTransRelationshipId](#BackingTable_JmgStampJournalTransRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity</a>|

### <a href=#AbsencePayUnits name="AbsencePayUnits">AbsencePayUnits</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Absence pay units</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsencePayUnits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Absence pay units</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkInProgress name="IsWorkInProgress">IsWorkInProgress</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkInProgress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectActivityName name="IndirectActivityName">IndirectActivityName</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indirect activity name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectActivityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indirect activity name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BreakSeconds name="BreakSeconds">BreakSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Break seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BreakSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Break seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BreakToleranceSeconds name="BreakToleranceSeconds">BreakToleranceSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Break tolerance seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BreakToleranceSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Break tolerance seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedStartDate name="CorrectedStartDate">CorrectedStartDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedStartTime name="CorrectedStartTime">CorrectedStartTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedEndDate name="CorrectedEndDate">CorrectedEndDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedEndTime name="CorrectedEndTime">CorrectedEndTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#ErrorCause name="ErrorCause">ErrorCause</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorCause attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorSpecification name="ErrorSpecification">ErrorSpecification</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorSpecification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobFinished name="IsJobFinished">IsJobFinished</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobFinished attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceJobId name="TimeAndAttendanceJobId">TimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AbsenceCodeTimeAndAttendanceJobId name="AbsenceCodeTimeAndAttendanceJobId">AbsenceCodeTimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsenceCodeTimeAndAttendanceJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobPayRateMethod name="JobPayRateMethod">JobPayRateMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobPayRateMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityType name="ActivityType">ActivityType</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAllocationType name="TimeAllocationType">TimeAllocationType</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time allocation type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAllocationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time allocation type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalRegistrationType name="JournalRegistrationType">JournalRegistrationType</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalRegistrationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorLogText name="ErrorLogText">ErrorLogText</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#OnCallTimeAndAttendanceJobId name="OnCallTimeAndAttendanceJobId">OnCallTimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnCallTimeAndAttendanceJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationNumber name="OperationNumber">OperationNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operation number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operation number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedErrorCatchWeightQuantity name="ReportedErrorCatchWeightQuantity">ReportedErrorCatchWeightQuantity</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reported error catch weight quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedErrorCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reported error catch weight quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedGoodCatchWeightQuantity name="ReportedGoodCatchWeightQuantity">ReportedGoodCatchWeightQuantity</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reported good catch weight quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedGoodCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reported good catch weight quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedCatchWeightQuantity name="StartedCatchWeightQuantity">StartedCatchWeightQuantity</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Started catch weight quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Started catch weight quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileDate name="TimeProfileDate">TimeProfileDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project category id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project category id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedErrorQuantity name="ReportedErrorQuantity">ReportedErrorQuantity</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reported error quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedErrorQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reported error quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedGoodQuantity name="ReportedGoodQuantity">ReportedGoodQuantity</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reported good quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedGoodQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reported good quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedQuantity name="StartedQuantity">StartedQuantity</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Started quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Started quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteJobType name="RouteJobType">RouteJobType</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Route job type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteJobType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Route job type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculatedTimeSeconds name="CalculatedTimeSeconds">CalculatedTimeSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculated time seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedTimeSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated time seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculatedTimeBeforeAllocationSeconds name="CalculatedTimeBeforeAllocationSeconds">CalculatedTimeBeforeAllocationSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculated time before allocation seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedTimeBeforeAllocationSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated time before allocation seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculatedTimeAfterAllocationSeconds name="CalculatedTimeAfterAllocationSeconds">CalculatedTimeAfterAllocationSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculated time after allocation seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedTimeAfterAllocationSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated time after allocation seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationType name="RegistrationType">RegistrationType</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Registration type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationSubType name="RegistrationSubType">RegistrationSubType</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration sub type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationSubType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Registration sub type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndStopTime name="EndStopTime">EndStopTime</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndStopTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartRegistrationTerminalId name="StartRegistrationTerminalId">StartRegistrationTerminalId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartRegistrationTerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StopRegistrationTerminalId name="StopRegistrationTerminalId">StopRegistrationTerminalId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StopRegistrationTerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowStatus name="WorkflowStatus">WorkflowStatus</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#OperationsResourceId name="OperationsResourceId">OperationsResourceId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operations resource Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operations resource Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourcePilotId name="OperationsResourcePilotId">OperationsResourcePilotId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operations resource pilot Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourcePilotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operations resource pilot Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerPersonnelNumber name="WorkerPersonnelNumber">WorkerPersonnelNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#PilotPersonnelNumber name="PilotPersonnelNumber">PilotPersonnelNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pilot personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PilotPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pilot personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#ActivityRegistrationTransactionId name="ActivityRegistrationTransactionId">ActivityRegistrationTransactionId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity registration transaction Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityRegistrationTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity registration transaction Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityRegistrationEntryNumber name="ActivityRegistrationEntryNumber">ActivityRegistrationEntryNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity registration entry number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityRegistrationEntryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity registration entry number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Production order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectActivityCategoryId name="IndirectActivityCategoryId">IndirectActivityCategoryId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indirect activity category Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectActivityCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indirect activity category Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#Relationship_PilotWorkerRelationshipId name="Relationship_PilotWorkerRelationshipId">Relationship_PilotWorkerRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PilotWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_JmgStampJournalTransRelationshipId name="BackingTable_JmgStampJournalTransRelationshipId">BackingTable_JmgStampJournalTransRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgStampJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/JmgStampJournalTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/JmgStampJournalTrans.cdm.json/JmgStampJournalTrans</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/JmgStampJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceActivityRegistrationEntity (this entity)  

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
