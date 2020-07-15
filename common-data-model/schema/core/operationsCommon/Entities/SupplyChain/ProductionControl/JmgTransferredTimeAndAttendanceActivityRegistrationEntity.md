---
title: JmgTransferredTimeAndAttendanceActivityRegistrationEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Transferred time and attendance activity registrations in ProductionControl(JmgTransferredTimeAndAttendanceActivityRegistrationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transferred time and attendance activity registrations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AbsencePayUnits](#AbsencePayUnits)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[IndirectActivityName](#IndirectActivityName)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[BreakSeconds](#BreakSeconds)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[BreakToleranceSeconds](#BreakToleranceSeconds)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CorrectedStartDate](#CorrectedStartDate)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CorrectedStartTime](#CorrectedStartTime)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CorrectedEndDate](#CorrectedEndDate)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CorrectedEndTime](#CorrectedEndTime)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostAbsenceTime](#CostAbsenceTime)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostBreakTime](#CostBreakTime)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostPriceFactor](#CostPriceFactor)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostFlexTimePlus](#CostFlexTimePlus)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostFlexTimeMinus](#CostFlexTimeMinus)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostNormTime](#CostNormTime)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostOverTime](#CostOverTime)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostAutomaticPremiums](#CostAutomaticPremiums)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostManualPremiums](#CostManualPremiums)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ErrorCause](#ErrorCause)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ErrorSpecification](#ErrorSpecification)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CostPriceHour](#CostPriceHour)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[IsJobFinished](#IsJobFinished)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[TimeAndAttendanceJobId](#TimeAndAttendanceJobId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[AbsenceCodeTimeAndAttendanceJobId](#AbsenceCodeTimeAndAttendanceJobId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[JobPayRateMethod](#JobPayRateMethod)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ActivityType](#ActivityType)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[TimeAllocationType](#TimeAllocationType)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[JournalRegistrationType](#JournalRegistrationType)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[OnCallTimeAndAttendanceJobId](#OnCallTimeAndAttendanceJobId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[OperationNumber](#OperationNumber)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ReportedErrorCatchWeightQuantity](#ReportedErrorCatchWeightQuantity)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ReportedGoodCatchWeightQuantity](#ReportedGoodCatchWeightQuantity)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartedCatchWeightQuantity](#StartedCatchWeightQuantity)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[TimeProfileDate](#TimeProfileDate)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ReportedErrorQuantity](#ReportedErrorQuantity)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ReportedGoodQuantity](#ReportedGoodQuantity)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartedQuantity](#StartedQuantity)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[RouteJobType](#RouteJobType)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CalculatedTimeSeconds](#CalculatedTimeSeconds)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CalculatedTimeBeforeAllocationSeconds](#CalculatedTimeBeforeAllocationSeconds)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[CalculatedTimeAfterAllocationSeconds](#CalculatedTimeAfterAllocationSeconds)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[RegistrationType](#RegistrationType)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[RegistrationSubType](#RegistrationSubType)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartDate](#StartDate)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartTime](#StartTime)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[EndDate](#EndDate)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[EndTime](#EndTime)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[StartRegistrationTerminalId](#StartRegistrationTerminalId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[TransferredActivityRegistrationTransactionId](#TransferredActivityRegistrationTransactionId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[StopRegistrationTerminalId](#StopRegistrationTerminalId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[VoucherNumber](#VoucherNumber)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[WorkflowStatus](#WorkflowStatus)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[OperationsResourceId](#OperationsResourceId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[OperationsResourcePilotId](#OperationsResourcePilotId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[WorkerPersonnelNumber](#WorkerPersonnelNumber)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[PilotPersonnelNumber](#PilotPersonnelNumber)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[TransferredActivityRegistrationEntryNumber](#TransferredActivityRegistrationEntryNumber)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[IndirectActivityCategoryId](#IndirectActivityCategoryId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[ProjectId](#ProjectId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[Relationship_PilotWorkerRelationshipId](#Relationship_PilotWorkerRelationshipId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[BackingTable_JmgStampTransRelationshipId](#BackingTable_JmgStampTransRelationshipId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgTransferredTimeAndAttendanceActivityRegistrationEntity.md" target="_blank">ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity</a>|

### <a href=#AbsencePayUnits name="AbsencePayUnits">AbsencePayUnits</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#IndirectActivityName name="IndirectActivityName">IndirectActivityName</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#CostAbsenceTime name="CostAbsenceTime">CostAbsenceTime</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost absence time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAbsenceTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost absence time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostBreakTime name="CostBreakTime">CostBreakTime</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost break time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostBreakTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost break time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostPriceFactor name="CostPriceFactor">CostPriceFactor</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost price factor</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost price factor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostFlexTimePlus name="CostFlexTimePlus">CostFlexTimePlus</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost flex time plus</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostFlexTimePlus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost flex time plus</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostFlexTimeMinus name="CostFlexTimeMinus">CostFlexTimeMinus</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost flex time minus</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostFlexTimeMinus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost flex time minus</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostNormTime name="CostNormTime">CostNormTime</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost norm time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostNormTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost norm time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostOverTime name="CostOverTime">CostOverTime</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost over time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostOverTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost over time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAutomaticPremiums name="CostAutomaticPremiums">CostAutomaticPremiums</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost automatic premiums</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAutomaticPremiums attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost automatic premiums</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostManualPremiums name="CostManualPremiums">CostManualPremiums</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost manual premiums</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostManualPremiums attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost manual premiums</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#CostPriceHour name="CostPriceHour">CostPriceHour</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceHour attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobFinished name="IsJobFinished">IsJobFinished</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#OnCallTimeAndAttendanceJobId name="OnCallTimeAndAttendanceJobId">OnCallTimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#EndTime name="EndTime">EndTime</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartRegistrationTerminalId name="StartRegistrationTerminalId">StartRegistrationTerminalId</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#TransferredActivityRegistrationTransactionId name="TransferredActivityRegistrationTransactionId">TransferredActivityRegistrationTransactionId</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transferred activity registration transaction Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferredActivityRegistrationTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transferred activity registration transaction Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StopRegistrationTerminalId name="StopRegistrationTerminalId">StopRegistrationTerminalId</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#VoucherNumber name="VoucherNumber">VoucherNumber</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowStatus name="WorkflowStatus">WorkflowStatus</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#TransferredActivityRegistrationEntryNumber name="TransferredActivityRegistrationEntryNumber">TransferredActivityRegistrationEntryNumber</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transferred activity registration entry number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferredActivityRegistrationEntryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transferred activity registration entry number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectActivityCategoryId name="IndirectActivityCategoryId">IndirectActivityCategoryId</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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

### <a href=#BackingTable_JmgStampTransRelationshipId name="BackingTable_JmgStampTransRelationshipId">BackingTable_JmgStampTransRelationshipId</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgStampTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Transaction/JmgStampTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Transaction/JmgStampTrans.cdm.json/JmgStampTrans</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Transaction/JmgStampTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgTransferredTimeAndAttendanceActivityRegistrationEntity (this entity)  

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
