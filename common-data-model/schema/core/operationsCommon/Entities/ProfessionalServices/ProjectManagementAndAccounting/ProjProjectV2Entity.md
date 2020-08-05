---
title: ProjProjectV2Entity in ProjectManagementAndAccounting - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Projects V2 in ProjectManagementAndAccounting(ProjProjectV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjProjectV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Projects V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProjectId](#ProjectId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[AlternateProjectId](#AlternateProjectId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[BankDocumentType](#BankDocumentType)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsCertifiedPayroll](#IsCertifiedPayroll)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[CanVerifyCostAgainstRemainingForecast](#CanVerifyCostAgainstRemainingForecast)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ZakatContractAmendment](#ZakatContractAmendment)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ZakatContractDate](#ZakatContractDate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ZakatContractPeriod](#ZakatContractPeriod)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ZakatProjectValue](#ZakatProjectValue)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[DateOfCreation](#DateOfCreation)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[DeliveryLocation](#DeliveryLocation)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[DeliveryName](#DeliveryName)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[Email](#Email)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ActualEndDate](#ActualEndDate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ExtensionDate](#ExtensionDate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SubprojectIdFormat](#SubprojectIdFormat)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsHeader](#IsHeader)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[JobIdentification](#JobIdentification)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectName](#ProjectName)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsOCIPWorkerCompensation](#IsOCIPWorkerCompensation)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsOCIPGeneralLiability](#IsOCIPGeneralLiability)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ParentProjectId](#ParentProjectId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[TransactionTypesControlled](#TransactionTypesControlled)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[BudgetControlInterval](#BudgetControlInterval)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectBudgetManagement](#ProjectBudgetManagement)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[BudgetOverrunDefault](#BudgetOverrunDefault)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[AllowNegativeBudgetsToBeCarriedForward](#AllowNegativeBudgetsToBeCarriedForward)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[CanCarryForwardRemainingBudgets](#CanCarryForwardRemainingBudgets)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectedEndDate](#ProjectedEndDate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectedStartDate](#ProjectedStartDate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectGroupId](#ProjectGroupId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectContractId](#ProjectContractId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[LedgerPostingSortPriority](#LedgerPostingSortPriority)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[LinePropertySearchPriority](#LinePropertySearchPriority)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SalesPriceGroupId](#SalesPriceGroupId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SchedulingCalendarId](#SchedulingCalendarId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ScheduleDurationInDays](#ScheduleDurationInDays)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[TotalPlannedEffortInHours](#TotalPlannedEffortInHours)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ScheduleEndDate](#ScheduleEndDate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsResourceCalendarIgnored](#IsResourceCalendarIgnored)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ScheduleStartDate](#ScheduleStartDate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsActivityRequiredForExpenseForecast](#IsActivityRequiredForExpenseForecast)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsActivityRequiredForExpenseTransaction](#IsActivityRequiredForExpenseTransaction)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsActivityRequiredForHourForecast](#IsActivityRequiredForHourForecast)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsActivityRequiredForHourTransaction](#IsActivityRequiredForHourTransaction)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsActivityRequiredForItemForecast](#IsActivityRequiredForItemForecast)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsActivityRequiredForItemTransaction](#IsActivityRequiredForItemTransaction)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ActualStartDate](#ActualStartDate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectStage](#ProjectStage)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ZakatSubject](#ZakatSubject)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SalesTaxGroupId](#SalesTaxGroupId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsProjectTemplate](#IsProjectTemplate)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[PostingLevel](#PostingLevel)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[CanUseAlternateProjectBudget](#CanUseAlternateProjectBudget)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsBudgetControlEnabled](#IsBudgetControlEnabled)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsProjectCategoryValidationEnabled](#IsProjectCategoryValidationEnabled)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[EstimateProjectId](#EstimateProjectId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ArchitectRecId](#ArchitectRecId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectManagerRecId](#ProjectManagerRecId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectControllerRecId](#ProjectControllerRecId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SalesManagerRecId](#SalesManagerRecId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[Description](#Description)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IsTemplateApplied](#IsTemplateApplied)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ArchitectPersonnelNumber](#ArchitectPersonnelNumber)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectControllerPersonnelNumber](#ProjectControllerPersonnelNumber)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[ProjectManagerPersonnelNumber](#ProjectManagerPersonnelNumber)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SalesManagerPersonnelNumber](#SalesManagerPersonnelNumber)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SortingField1](#SortingField1)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SortingField2](#SortingField2)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[SortingField3](#SortingField3)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[IntegrationSourceDataId](#IntegrationSourceDataId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[BackingTable_ProjTableRelationshipId](#BackingTable_ProjTableRelationshipId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjProjectV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectV2Entity</a>|

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternateProjectId name="AlternateProjectId">AlternateProjectId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternateProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankDocumentType name="BankDocumentType">BankDocumentType</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCertifiedPayroll name="IsCertifiedPayroll">IsCertifiedPayroll</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCertifiedPayroll attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanVerifyCostAgainstRemainingForecast name="CanVerifyCostAgainstRemainingForecast">CanVerifyCostAgainstRemainingForecast</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanVerifyCostAgainstRemainingForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatContractAmendment name="ZakatContractAmendment">ZakatContractAmendment</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatContractAmendment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatContractDate name="ZakatContractDate">ZakatContractDate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatContractDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatContractPeriod name="ZakatContractPeriod">ZakatContractPeriod</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatContractPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatProjectValue name="ZakatProjectValue">ZakatProjectValue</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatProjectValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateOfCreation name="DateOfCreation">DateOfCreation</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfCreation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryLocation name="DeliveryLocation">DeliveryLocation</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualEndDate name="ActualEndDate">ActualEndDate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtensionDate name="ExtensionDate">ExtensionDate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtensionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubprojectIdFormat name="SubprojectIdFormat">SubprojectIdFormat</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubprojectIdFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsHeader name="IsHeader">IsHeader</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobIdentification name="JobIdentification">JobIdentification</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobIdentification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectName name="ProjectName">ProjectName</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOCIPWorkerCompensation name="IsOCIPWorkerCompensation">IsOCIPWorkerCompensation</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOCIPWorkerCompensation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOCIPGeneralLiability name="IsOCIPGeneralLiability">IsOCIPGeneralLiability</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOCIPGeneralLiability attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentProjectId name="ParentProjectId">ParentProjectId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionTypesControlled name="TransactionTypesControlled">TransactionTypesControlled</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionTypesControlled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetControlInterval name="BudgetControlInterval">BudgetControlInterval</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectBudgetManagement name="ProjectBudgetManagement">ProjectBudgetManagement</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectBudgetManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetOverrunDefault name="BudgetOverrunDefault">BudgetOverrunDefault</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetOverrunDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowNegativeBudgetsToBeCarriedForward name="AllowNegativeBudgetsToBeCarriedForward">AllowNegativeBudgetsToBeCarriedForward</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowNegativeBudgetsToBeCarriedForward attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanCarryForwardRemainingBudgets name="CanCarryForwardRemainingBudgets">CanCarryForwardRemainingBudgets</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanCarryForwardRemainingBudgets attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectedEndDate name="ProjectedEndDate">ProjectedEndDate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectedEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectedStartDate name="ProjectedStartDate">ProjectedStartDate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectedStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectGroupId name="ProjectGroupId">ProjectGroupId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectContractId name="ProjectContractId">ProjectContractId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPostingSortPriority name="LedgerPostingSortPriority">LedgerPostingSortPriority</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingSortPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinePropertySearchPriority name="LinePropertySearchPriority">LinePropertySearchPriority</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePropertySearchPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceGroupId name="SalesPriceGroupId">SalesPriceGroupId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchedulingCalendarId name="SchedulingCalendarId">SchedulingCalendarId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedulingCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduleDurationInDays name="ScheduleDurationInDays">ScheduleDurationInDays</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduleDurationInDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPlannedEffortInHours name="TotalPlannedEffortInHours">TotalPlannedEffortInHours</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPlannedEffortInHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduleEndDate name="ScheduleEndDate">ScheduleEndDate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduleEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsResourceCalendarIgnored name="IsResourceCalendarIgnored">IsResourceCalendarIgnored</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsResourceCalendarIgnored attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduleStartDate name="ScheduleStartDate">ScheduleStartDate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduleStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForExpenseForecast name="IsActivityRequiredForExpenseForecast">IsActivityRequiredForExpenseForecast</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForExpenseForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForExpenseTransaction name="IsActivityRequiredForExpenseTransaction">IsActivityRequiredForExpenseTransaction</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForExpenseTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForHourForecast name="IsActivityRequiredForHourForecast">IsActivityRequiredForHourForecast</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForHourForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForHourTransaction name="IsActivityRequiredForHourTransaction">IsActivityRequiredForHourTransaction</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForHourTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForItemForecast name="IsActivityRequiredForItemForecast">IsActivityRequiredForItemForecast</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForItemForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityRequiredForItemTransaction name="IsActivityRequiredForItemTransaction">IsActivityRequiredForItemTransaction</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityRequiredForItemTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualStartDate name="ActualStartDate">ActualStartDate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectStage name="ProjectStage">ProjectStage</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectStage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatSubject name="ZakatSubject">ZakatSubject</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatSubject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupId name="SalesTaxGroupId">SalesTaxGroupId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectTemplate name="IsProjectTemplate">IsProjectTemplate</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingLevel name="PostingLevel">PostingLevel</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanUseAlternateProjectBudget name="CanUseAlternateProjectBudget">CanUseAlternateProjectBudget</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanUseAlternateProjectBudget attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBudgetControlEnabled name="IsBudgetControlEnabled">IsBudgetControlEnabled</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBudgetControlEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectCategoryValidationEnabled name="IsProjectCategoryValidationEnabled">IsProjectCategoryValidationEnabled</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectCategoryValidationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimateProjectId name="EstimateProjectId">EstimateProjectId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimateProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArchitectRecId name="ArchitectRecId">ArchitectRecId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArchitectRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectManagerRecId name="ProjectManagerRecId">ProjectManagerRecId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectManagerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectControllerRecId name="ProjectControllerRecId">ProjectControllerRecId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectControllerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesManagerRecId name="SalesManagerRecId">SalesManagerRecId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesManagerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTemplateApplied name="IsTemplateApplied">IsTemplateApplied</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTemplateApplied attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArchitectPersonnelNumber name="ArchitectPersonnelNumber">ArchitectPersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArchitectPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectControllerPersonnelNumber name="ProjectControllerPersonnelNumber">ProjectControllerPersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project controller</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectControllerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project controller</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectManagerPersonnelNumber name="ProjectManagerPersonnelNumber">ProjectManagerPersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project manager</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectManagerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project manager</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesManagerPersonnelNumber name="SalesManagerPersonnelNumber">SalesManagerPersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales manager</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesManagerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales manager</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingField1 name="SortingField1">SortingField1</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort field 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingField1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sort field 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingField2 name="SortingField2">SortingField2</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort field 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingField2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sort field 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingField3 name="SortingField3">SortingField3</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort field 3</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingField3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sort field 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntegrationSourceDataId name="IntegrationSourceDataId">IntegrationSourceDataId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntegrationSourceDataId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjProjectV2Entity (this entity)  

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
