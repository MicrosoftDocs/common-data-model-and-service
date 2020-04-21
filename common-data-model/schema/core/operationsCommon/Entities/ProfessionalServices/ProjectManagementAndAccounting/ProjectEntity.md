---
title: ProjectEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# ProjectEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjectEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ProjectID](#ProjectID)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[AlternateProject](#AlternateProject)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[FixedAssetNumber](#FixedAssetNumber)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[BankDocumentType](#BankDocumentType)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[CertifiedPayroll](#CertifiedPayroll)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[CanVerifyCostAgainstRemainingForecast](#CanVerifyCostAgainstRemainingForecast)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[TaskCompletelyScheduled](#TaskCompletelyScheduled)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ZakatContractAmendment](#ZakatContractAmendment)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ZakatContractDate](#ZakatContractDate)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ZakatContractPeriod](#ZakatContractPeriod)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ZakatProjectValue](#ZakatProjectValue)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[DateOfCreation](#DateOfCreation)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Dimension](#Dimension)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Location](#Location)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[DeliveryName](#DeliveryName)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Email](#Email)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ActualEndDate](#ActualEndDate)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ExtensionDate](#ExtensionDate)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[SubprojectIDFormat](#SubprojectIDFormat)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Header](#Header)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[JobIdentification](#JobIdentification)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[JobPayType](#JobPayType)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[MinimumTimeIncrement](#MinimumTimeIncrement)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectName](#ProjectName)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ParentProject](#ParentProject)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[TransactionTypesControlled](#TransactionTypesControlled)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[BudgetControlInterval](#BudgetControlInterval)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectBudgetManagement](#ProjectBudgetManagement)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[BudgetOverrunDefault](#BudgetOverrunDefault)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[AllowNegativeBudgetsToBeCarriedForward](#AllowNegativeBudgetsToBeCarriedForward)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[CanCarryForwardRemainingBudgets](#CanCarryForwardRemainingBudgets)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectedEndDate](#ProjectedEndDate)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectedStartDate](#ProjectedStartDate)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectGroup](#ProjectGroup)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectContractID](#ProjectContractID)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[LedgerPostingSortPriority](#LedgerPostingSortPriority)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[SearchPriority](#SearchPriority)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[SalesPriceGroup](#SalesPriceGroup)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[InvoiceCost](#InvoiceCost)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ActiveRevision](#ActiveRevision)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ExternalRevision](#ExternalRevision)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[InvoicingMethod](#InvoicingMethod)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Status](#Status)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ScheduleStatus](#ScheduleStatus)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Calendar](#Calendar)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[DurationInDays](#DurationInDays)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[TotalEffortInHours](#TotalEffortInHours)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[EndDate1](#EndDate1)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[StartTime](#StartTime)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[PSASchedIgnoreCalendar](#PSASchedIgnoreCalendar)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Scheduled](#Scheduled)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[StartDate1](#StartDate1)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[EndTime](#EndTime)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[DurationDeterminesEndDate](#DurationDeterminesEndDate)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[IsActivityRequiredForExpenseForecast](#IsActivityRequiredForExpenseForecast)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[IsActivityRequiredForExpenseTransaction](#IsActivityRequiredForExpenseTransaction)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[IsActivityRequiredForHourForecast](#IsActivityRequiredForHourForecast)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[IsActivityRequiredForHourTransaction](#IsActivityRequiredForHourTransaction)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[IsActivityRequiredForItemForecast](#IsActivityRequiredForItemForecast)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[IsActivityRequiredForItemTransaction](#IsActivityRequiredForItemTransaction)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ActualStartDate](#ActualStartDate)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectStage](#ProjectStage)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ZakatSubject](#ZakatSubject)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectTemplate](#ProjectTemplate)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[PostingLevel](#PostingLevel)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectType](#ProjectType)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[CanUseAlternateProjectBudget](#CanUseAlternateProjectBudget)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[CanUseBudgetControl](#CanUseBudgetControl)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Category](#Category)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[EstimateProjectID](#EstimateProjectID)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Reference](#Reference)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectManager](#ProjectManager)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[ProjectController](#ProjectController)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[SalesManager](#SalesManager)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Description](#Description)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[TemplateApplied](#TemplateApplied)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[AlertTimeFrameWeeks](#AlertTimeFrameWeeks)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[LocationID](#LocationID)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[WorkerArchitectPersonnelNumber](#WorkerArchitectPersonnelNumber)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[WorkerRespFinancialPersonnelNumber](#WorkerRespFinancialPersonnelNumber)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[WorkerResponsiblePersonnelNumber](#WorkerResponsiblePersonnelNumber)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[WorkerRespSalesPersonnelNumber](#WorkerRespSalesPersonnelNumber)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[SortingId1](#SortingId1)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[SortingId2](#SortingId2)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[SortingId3](#SortingId3)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[BackingTable_ProjTableRelationshipId](#BackingTable_ProjTableRelationshipId)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjectEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectEntity</a>|

### <a href=#ProjectID name="ProjectID">ProjectID</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternateProject name="AlternateProject">AlternateProject</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternateProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetNumber name="FixedAssetNumber">FixedAssetNumber</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankDocumentType name="BankDocumentType">BankDocumentType</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertifiedPayroll name="CertifiedPayroll">CertifiedPayroll</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertifiedPayroll attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanVerifyCostAgainstRemainingForecast name="CanVerifyCostAgainstRemainingForecast">CanVerifyCostAgainstRemainingForecast</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanVerifyCostAgainstRemainingForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaskCompletelyScheduled name="TaskCompletelyScheduled">TaskCompletelyScheduled</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskCompletelyScheduled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatContractAmendment name="ZakatContractAmendment">ZakatContractAmendment</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatContractAmendment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatContractDate name="ZakatContractDate">ZakatContractDate</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatContractDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatContractPeriod name="ZakatContractPeriod">ZakatContractPeriod</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatContractPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatProjectValue name="ZakatProjectValue">ZakatProjectValue</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatProjectValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateOfCreation name="DateOfCreation">DateOfCreation</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfCreation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualEndDate name="ActualEndDate">ActualEndDate</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtensionDate name="ExtensionDate">ExtensionDate</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtensionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubprojectIDFormat name="SubprojectIDFormat">SubprojectIDFormat</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubprojectIDFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Header name="Header">Header</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Header attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobIdentification name="JobIdentification">JobIdentification</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobIdentification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobPayType name="JobPayType">JobPayType</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobPayType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumTimeIncrement name="MinimumTimeIncrement">MinimumTimeIncrement</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumTimeIncrement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectName name="ProjectName">ProjectName</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentProject name="ParentProject">ParentProject</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionTypesControlled name="TransactionTypesControlled">TransactionTypesControlled</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionTypesControlled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetControlInterval name="BudgetControlInterval">BudgetControlInterval</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectBudgetManagement name="ProjectBudgetManagement">ProjectBudgetManagement</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectBudgetManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetOverrunDefault name="BudgetOverrunDefault">BudgetOverrunDefault</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetOverrunDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowNegativeBudgetsToBeCarriedForward name="AllowNegativeBudgetsToBeCarriedForward">AllowNegativeBudgetsToBeCarriedForward</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowNegativeBudgetsToBeCarriedForward attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanCarryForwardRemainingBudgets name="CanCarryForwardRemainingBudgets">CanCarryForwardRemainingBudgets</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanCarryForwardRemainingBudgets attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectedEndDate name="ProjectedEndDate">ProjectedEndDate</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectedEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectedStartDate name="ProjectedStartDate">ProjectedStartDate</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectedStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectGroup name="ProjectGroup">ProjectGroup</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectContractID name="ProjectContractID">ProjectContractID</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectContractID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPostingSortPriority name="LedgerPostingSortPriority">LedgerPostingSortPriority</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingSortPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SearchPriority name="SearchPriority">SearchPriority</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceGroup name="SalesPriceGroup">SalesPriceGroup</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCost name="InvoiceCost">InvoiceCost</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveRevision name="ActiveRevision">ActiveRevision</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveRevision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalRevision name="ExternalRevision">ExternalRevision</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalRevision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicingMethod name="InvoicingMethod">InvoicingMethod</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduleStatus name="ScheduleStatus">ScheduleStatus</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduleStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Calendar name="Calendar">Calendar</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Calendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DurationInDays name="DurationInDays">DurationInDays</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DurationInDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalEffortInHours name="TotalEffortInHours">TotalEffortInHours</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalEffortInHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate1 name="EndDate1">EndDate1</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSASchedIgnoreCalendar name="PSASchedIgnoreCalendar">PSASchedIgnoreCalendar</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSASchedIgnoreCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scheduled name="Scheduled">Scheduled</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scheduled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate1 name="StartDate1">StartDate1</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndTime name="EndTime">EndTime</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DurationDeterminesEndDate name="DurationDeterminesEndDate">DurationDeterminesEndDate</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DurationDeterminesEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForExpenseForecast name="IsActivityRequiredForExpenseForecast">IsActivityRequiredForExpenseForecast</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForExpenseForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForExpenseTransaction name="IsActivityRequiredForExpenseTransaction">IsActivityRequiredForExpenseTransaction</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForExpenseTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForHourForecast name="IsActivityRequiredForHourForecast">IsActivityRequiredForHourForecast</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForHourForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForHourTransaction name="IsActivityRequiredForHourTransaction">IsActivityRequiredForHourTransaction</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForHourTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForItemForecast name="IsActivityRequiredForItemForecast">IsActivityRequiredForItemForecast</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForItemForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForItemTransaction name="IsActivityRequiredForItemTransaction">IsActivityRequiredForItemTransaction</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForItemTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualStartDate name="ActualStartDate">ActualStartDate</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectStage name="ProjectStage">ProjectStage</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectStage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatSubject name="ZakatSubject">ZakatSubject</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatSubject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectTemplate name="ProjectTemplate">ProjectTemplate</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingLevel name="PostingLevel">PostingLevel</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectType name="ProjectType">ProjectType</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanUseAlternateProjectBudget name="CanUseAlternateProjectBudget">CanUseAlternateProjectBudget</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanUseAlternateProjectBudget attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanUseBudgetControl name="CanUseBudgetControl">CanUseBudgetControl</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanUseBudgetControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Category attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimateProjectID name="EstimateProjectID">EstimateProjectID</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimateProjectID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectManager name="ProjectManager">ProjectManager</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectManager attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectController name="ProjectController">ProjectController</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectController attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesManager name="SalesManager">SalesManager</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesManager attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateApplied name="TemplateApplied">TemplateApplied</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateApplied attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlertTimeFrameWeeks name="AlertTimeFrameWeeks">AlertTimeFrameWeeks</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlertTimeFrameWeeks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationID name="LocationID">LocationID</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerArchitectPersonnelNumber name="WorkerArchitectPersonnelNumber">WorkerArchitectPersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerArchitectPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerRespFinancialPersonnelNumber name="WorkerRespFinancialPersonnelNumber">WorkerRespFinancialPersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerRespFinancialPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerResponsiblePersonnelNumber name="WorkerResponsiblePersonnelNumber">WorkerResponsiblePersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerResponsiblePersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerRespSalesPersonnelNumber name="WorkerRespSalesPersonnelNumber">WorkerRespSalesPersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerRespSalesPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingId1 name="SortingId1">SortingId1</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingId2 name="SortingId2">SortingId2</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingId3 name="SortingId3">SortingId3</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProjTableRelationshipId name="BackingTable_ProjTableRelationshipId">BackingTable_ProjTableRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjectEntity (this entity)  

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
