---
title: JmgTimeAndAttendanceParametersEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Time and attendance and manufacturing execution parameters in ProductionControl(JmgTimeAndAttendanceParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgTimeAndAttendanceParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time and attendance and manufacturing execution parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AutomaticAbsenceRegistrationAbsenceCodeJobId](#AutomaticAbsenceRegistrationAbsenceCodeJobId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[WillReachingMaximumWorkingMinutesAutomaticallyRegisterClockOut](#WillReachingMaximumWorkingMinutesAutomaticallyRegisterClockOut)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[BarcodeSetupId](#BarcodeSetupId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[AbsencePayrollCostInclusionMethod](#AbsencePayrollCostInclusionMethod)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[PaidBreakPayrollCostInclusionMethod](#PaidBreakPayrollCostInclusionMethod)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[PayrollCostCalculationFactor](#PayrollCostCalculationFactor)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[FlextimeDirectPayrollCostInclusionMethod](#FlextimeDirectPayrollCostInclusionMethod)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[FlextimeIndirectPayrollCostInclusionMethod](#FlextimeIndirectPayrollCostInclusionMethod)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[StandardTimePayrollCostInclusionMethod](#StandardTimePayrollCostInclusionMethod)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[OvertimePayrollCostInclusionMethod](#OvertimePayrollCostInclusionMethod)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[AutomaticPremiumsPayrollCostInclusionMethod](#AutomaticPremiumsPayrollCostInclusionMethod)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[ManualPremiumsPayrollCostInclusionMethod](#ManualPremiumsPayrollCostInclusionMethod)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[WillIndirectActivityCostCalculationUseIndirectActivityCostCategory](#WillIndirectActivityCostCalculationUseIndirectActivityCostCategory)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[WillProjectCostCalculationUseProjectCostCategory](#WillProjectCostCalculationUseProjectCostCategory)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[DefaultRegistrationJobFeedbackStatus](#DefaultRegistrationJobFeedbackStatus)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[PayrollExportRollbackErrorLevel](#PayrollExportRollbackErrorLevel)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[RegistrationTimeOrigin](#RegistrationTimeOrigin)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[MaterialConsumptionInventoryAdjustmentJournalNameId](#MaterialConsumptionInventoryAdjustmentJournalNameId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[AbsenceRegistrationLedgerDimensionSelectionRule](#AbsenceRegistrationLedgerDimensionSelectionRule)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[BreakRegistrationLedgerDimensionSelectionRule](#BreakRegistrationLedgerDimensionSelectionRule)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[IndirectActivityRegistrationLedgerDimensionSelectionRule](#IndirectActivityRegistrationLedgerDimensionSelectionRule)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[TimeAndAttendanceJobsSynchronizationMode](#TimeAndAttendanceJobsSynchronizationMode)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[IndirectActivitiesHoursLedgerJournalNameId](#IndirectActivitiesHoursLedgerJournalNameId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[ArePilotAndAssistantTeamRelationsPreserved](#ArePilotAndAssistantTeamRelationsPreserved)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[MaximumWorkingMinutes](#MaximumWorkingMinutes)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[AutomaticFlextimeRegistrationAbsenceCodeJobId](#AutomaticFlextimeRegistrationAbsenceCodeJobId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[PayrollExportFileFormat](#PayrollExportFileFormat)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[WillRegistrationTransferPostProjectHourJournal](#WillRegistrationTransferPostProjectHourJournal)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[ProjectRegistrationLedgerDimensionSelectionRule](#ProjectRegistrationLedgerDimensionSelectionRule)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[FeeProjectJournalNameId](#FeeProjectJournalNameId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[ProjectMaterialConsumptionInventoryJournalNameId](#ProjectMaterialConsumptionInventoryJournalNameId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[HoursProjectJournalNameId](#HoursProjectJournalNameId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[ProjectStatusUpdateMode](#ProjectStatusUpdateMode)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[RegistrationErrorHandlingRule](#RegistrationErrorHandlingRule)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[WillClockInRestartUnfinishedJob](#WillClockInRestartUnfinishedJob)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[TimeDisplayMode](#TimeDisplayMode)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[ElectronicTimecardPageInputMode](#ElectronicTimecardPageInputMode)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[WillElectronicTimecardPageDisplayStartDate](#WillElectronicTimecardPageDisplayStartDate)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[WillElectronicTimecardPageDisplayEndDate](#WillElectronicTimecardPageDisplayEndDate)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[AreAbsenceRegistrationsTransferredToHRM](#AreAbsenceRegistrationsTransferredToHRM)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[IsBadgeIdUsedAsIdentification](#IsBadgeIdUsedAsIdentification)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[IsPasswordIdentificationRequired](#IsPasswordIdentificationRequired)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[BackingTable_JmgParametersRelationshipId](#BackingTable_JmgParametersRelationshipId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgTimeAndAttendanceParametersEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceParametersEntity</a>|

### <a href=#AutomaticAbsenceRegistrationAbsenceCodeJobId name="AutomaticAbsenceRegistrationAbsenceCodeJobId">AutomaticAbsenceRegistrationAbsenceCodeJobId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticAbsenceRegistrationAbsenceCodeJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReachingMaximumWorkingMinutesAutomaticallyRegisterClockOut name="WillReachingMaximumWorkingMinutesAutomaticallyRegisterClockOut">WillReachingMaximumWorkingMinutesAutomaticallyRegisterClockOut</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReachingMaximumWorkingMinutesAutomaticallyRegisterClockOut attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarcodeSetupId name="BarcodeSetupId">BarcodeSetupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarcodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AbsencePayrollCostInclusionMethod name="AbsencePayrollCostInclusionMethod">AbsencePayrollCostInclusionMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsencePayrollCostInclusionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaidBreakPayrollCostInclusionMethod name="PaidBreakPayrollCostInclusionMethod">PaidBreakPayrollCostInclusionMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaidBreakPayrollCostInclusionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollCostCalculationFactor name="PayrollCostCalculationFactor">PayrollCostCalculationFactor</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollCostCalculationFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlextimeDirectPayrollCostInclusionMethod name="FlextimeDirectPayrollCostInclusionMethod">FlextimeDirectPayrollCostInclusionMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlextimeDirectPayrollCostInclusionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlextimeIndirectPayrollCostInclusionMethod name="FlextimeIndirectPayrollCostInclusionMethod">FlextimeIndirectPayrollCostInclusionMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlextimeIndirectPayrollCostInclusionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardTimePayrollCostInclusionMethod name="StandardTimePayrollCostInclusionMethod">StandardTimePayrollCostInclusionMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardTimePayrollCostInclusionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OvertimePayrollCostInclusionMethod name="OvertimePayrollCostInclusionMethod">OvertimePayrollCostInclusionMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OvertimePayrollCostInclusionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticPremiumsPayrollCostInclusionMethod name="AutomaticPremiumsPayrollCostInclusionMethod">AutomaticPremiumsPayrollCostInclusionMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticPremiumsPayrollCostInclusionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualPremiumsPayrollCostInclusionMethod name="ManualPremiumsPayrollCostInclusionMethod">ManualPremiumsPayrollCostInclusionMethod</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualPremiumsPayrollCostInclusionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillIndirectActivityCostCalculationUseIndirectActivityCostCategory name="WillIndirectActivityCostCalculationUseIndirectActivityCostCategory">WillIndirectActivityCostCalculationUseIndirectActivityCostCategory</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillIndirectActivityCostCalculationUseIndirectActivityCostCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProjectCostCalculationUseProjectCostCategory name="WillProjectCostCalculationUseProjectCostCategory">WillProjectCostCalculationUseProjectCostCategory</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProjectCostCalculationUseProjectCostCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRegistrationJobFeedbackStatus name="DefaultRegistrationJobFeedbackStatus">DefaultRegistrationJobFeedbackStatus</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRegistrationJobFeedbackStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollExportRollbackErrorLevel name="PayrollExportRollbackErrorLevel">PayrollExportRollbackErrorLevel</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollExportRollbackErrorLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationTimeOrigin name="RegistrationTimeOrigin">RegistrationTimeOrigin</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationTimeOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaterialConsumptionInventoryAdjustmentJournalNameId name="MaterialConsumptionInventoryAdjustmentJournalNameId">MaterialConsumptionInventoryAdjustmentJournalNameId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaterialConsumptionInventoryAdjustmentJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AbsenceRegistrationLedgerDimensionSelectionRule name="AbsenceRegistrationLedgerDimensionSelectionRule">AbsenceRegistrationLedgerDimensionSelectionRule</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsenceRegistrationLedgerDimensionSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BreakRegistrationLedgerDimensionSelectionRule name="BreakRegistrationLedgerDimensionSelectionRule">BreakRegistrationLedgerDimensionSelectionRule</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BreakRegistrationLedgerDimensionSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectActivityRegistrationLedgerDimensionSelectionRule name="IndirectActivityRegistrationLedgerDimensionSelectionRule">IndirectActivityRegistrationLedgerDimensionSelectionRule</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectActivityRegistrationLedgerDimensionSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceJobsSynchronizationMode name="TimeAndAttendanceJobsSynchronizationMode">TimeAndAttendanceJobsSynchronizationMode</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceJobsSynchronizationMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectActivitiesHoursLedgerJournalNameId name="IndirectActivitiesHoursLedgerJournalNameId">IndirectActivitiesHoursLedgerJournalNameId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectActivitiesHoursLedgerJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePilotAndAssistantTeamRelationsPreserved name="ArePilotAndAssistantTeamRelationsPreserved">ArePilotAndAssistantTeamRelationsPreserved</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePilotAndAssistantTeamRelationsPreserved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWorkingMinutes name="MaximumWorkingMinutes">MaximumWorkingMinutes</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWorkingMinutes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticFlextimeRegistrationAbsenceCodeJobId name="AutomaticFlextimeRegistrationAbsenceCodeJobId">AutomaticFlextimeRegistrationAbsenceCodeJobId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticFlextimeRegistrationAbsenceCodeJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollExportFileFormat name="PayrollExportFileFormat">PayrollExportFileFormat</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollExportFileFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRegistrationTransferPostProjectHourJournal name="WillRegistrationTransferPostProjectHourJournal">WillRegistrationTransferPostProjectHourJournal</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRegistrationTransferPostProjectHourJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectRegistrationLedgerDimensionSelectionRule name="ProjectRegistrationLedgerDimensionSelectionRule">ProjectRegistrationLedgerDimensionSelectionRule</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectRegistrationLedgerDimensionSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeProjectJournalNameId name="FeeProjectJournalNameId">FeeProjectJournalNameId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeProjectJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectMaterialConsumptionInventoryJournalNameId name="ProjectMaterialConsumptionInventoryJournalNameId">ProjectMaterialConsumptionInventoryJournalNameId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectMaterialConsumptionInventoryJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HoursProjectJournalNameId name="HoursProjectJournalNameId">HoursProjectJournalNameId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HoursProjectJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectStatusUpdateMode name="ProjectStatusUpdateMode">ProjectStatusUpdateMode</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectStatusUpdateMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationErrorHandlingRule name="RegistrationErrorHandlingRule">RegistrationErrorHandlingRule</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationErrorHandlingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillClockInRestartUnfinishedJob name="WillClockInRestartUnfinishedJob">WillClockInRestartUnfinishedJob</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillClockInRestartUnfinishedJob attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeDisplayMode name="TimeDisplayMode">TimeDisplayMode</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeDisplayMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicTimecardPageInputMode name="ElectronicTimecardPageInputMode">ElectronicTimecardPageInputMode</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicTimecardPageInputMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillElectronicTimecardPageDisplayStartDate name="WillElectronicTimecardPageDisplayStartDate">WillElectronicTimecardPageDisplayStartDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillElectronicTimecardPageDisplayStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillElectronicTimecardPageDisplayEndDate name="WillElectronicTimecardPageDisplayEndDate">WillElectronicTimecardPageDisplayEndDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillElectronicTimecardPageDisplayEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreAbsenceRegistrationsTransferredToHRM name="AreAbsenceRegistrationsTransferredToHRM">AreAbsenceRegistrationsTransferredToHRM</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreAbsenceRegistrationsTransferredToHRM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBadgeIdUsedAsIdentification name="IsBadgeIdUsedAsIdentification">IsBadgeIdUsedAsIdentification</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBadgeIdUsedAsIdentification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPasswordIdentificationRequired name="IsPasswordIdentificationRequired">IsPasswordIdentificationRequired</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPasswordIdentificationRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JmgParametersRelationshipId name="BackingTable_JmgParametersRelationshipId">BackingTable_JmgParametersRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/JmgParameters.cdm.json/JmgParameters</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceParametersEntity (this entity)  

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
