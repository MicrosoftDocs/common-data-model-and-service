---
title: ProjectParameterEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Project parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjectParameterEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ItemLumpSumAllocationKey](#ItemLumpSumAllocationKey)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TermsOfPaymentForHours](#TermsOfPaymentForHours)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ActualCostAfterEstimateDate](#ActualCostAfterEstimateDate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CommittedCostAfterEstimateDate](#CommittedCostAfterEstimateDate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CommittedCostUpToEstimateDate](#CommittedCostUpToEstimateDate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsAutoupdateField](#IsAutoupdateField)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsBudgetControlOutsideTheProjectHierarchyAllowed](#IsBudgetControlOutsideTheProjectHierarchyAllowed)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsDateCorrectionsOnTimesheetsAllowed](#IsDateCorrectionsOnTimesheetsAllowed)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsEliminationWithoutPostingEstimatesAllowed](#IsEliminationWithoutPostingEstimatesAllowed)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CanAlwaysCreateAdjustmentTransaction](#CanAlwaysCreateAdjustmentTransaction)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AmountInMillions](#AmountInMillions)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AmountInThousands](#AmountInThousands)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsActive](#IsActive)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[UserGroup](#UserGroup)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsItemConsumption](#IsItemConsumption)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[BeginningBalances](#BeginningBalances)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CommittedCost](#CommittedCost)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[BillingRuleFeeJournal](#BillingRuleFeeJournal)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultCategoryExpense](#DefaultCategoryExpense)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultCostTemplate](#DefaultCostTemplate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsCreateItemRequirement](#IsCreateItemRequirement)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CreditLineError](#CreditLineError)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[SetTheCostPriceAsTheSalesPriceByDefault](#SetTheCostPriceAsTheSalesPriceByDefault)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultItemAllocationKey](#DefaultItemAllocationKey)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultCategory](#DefaultCategory)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultSubprojectIDFormat](#DefaultSubprojectIDFormat)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DisplayTransactions](#DisplayTransactions)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultProjectType](#DefaultProjectType)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Eliminated](#Eliminated)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultCategoryHour](#DefaultCategoryHour)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultJournalNamesHour](#DefaultJournalNamesHour)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CheckBudgetOnDocumentLineSave](#CheckBudgetOnDocumentLineSave)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsIntercompanyResourceSchedulingAndTimesheetsEnabled](#IsIntercompanyResourceSchedulingAndTimesheetsEnabled)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsProcessingInvoiceProposalsInWorkflowEnabled](#IsProcessingInvoiceProposalsInWorkflowEnabled)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Estimated](#Estimated)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseDeleteReducedToZero](#ExpenseDeleteReducedToZero)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseJournalNameId](#ExpenseJournalNameId)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseLumpSumAllocationKey](#ExpenseLumpSumAllocationKey)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseReduceCostPriority1](#ExpenseReduceCostPriority1)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseReduceCostPriority2](#ExpenseReduceCostPriority2)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseReduceCostPriority3](#ExpenseReduceCostPriority3)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseReduceCostPriority4](#ExpenseReduceCostPriority4)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseReduceCostPriority5](#ExpenseReduceCostPriority5)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[MinimumRequirement](#MinimumRequirement)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[GeneralBufferDays](#GeneralBufferDays)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TermsOfPaymentForExpenses](#TermsOfPaymentForExpenses)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TermsOfPaymentForItems](#TermsOfPaymentForItems)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsAllocationSettingsLocked](#IsAllocationSettingsLocked)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ApplyPrioritySettingsFirstOrLastInFundingAllocationOrder](#ApplyPrioritySettingsFirstOrLastInFundingAllocationOrder)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[GrossMarginDecimals](#GrossMarginDecimals)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[GrossMarginRatio](#GrossMarginRatio)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HideActivity](#HideActivity)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HideCategory](#HideCategory)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HideExternalComments](#HideExternalComments)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HideLineProperty](#HideLineProperty)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourDeleteReducedToZero](#HourDeleteReducedToZero)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourQtyDecimals](#HourQtyDecimals)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourReduceCostPriority1](#HourReduceCostPriority1)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourReduceCostPriority2](#HourReduceCostPriority2)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourReduceCostPriority3](#HourReduceCostPriority3)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourReduceCostPriority4](#HourReduceCostPriority4)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourReduceCostPriority5](#HourReduceCostPriority5)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourReducedMinimumRequirement](#HourReducedMinimumRequirement)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultJournalNameItem](#DefaultJournalNameItem)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Invoiced](#Invoiced)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[InvoiceProposal](#InvoiceProposal)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultCategoryItem](#DefaultCategoryItem)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemDeleteReducedToZero](#ItemDeleteReducedToZero)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemNeverLedgerConsum](#ItemNeverLedgerConsum)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsItemNeverLedgerPL](#IsItemNeverLedgerPL)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemReduceCostPriority1](#ItemReduceCostPriority1)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemReduceCostPriority2](#ItemReduceCostPriority2)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemReduceCostPriority3](#ItemReduceCostPriority3)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemReduceCostPriority4](#ItemReduceCostPriority4)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemReduceCostPriority5](#ItemReduceCostPriority5)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemMinimumRequirement](#ItemMinimumRequirement)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ID](#ID)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AccrueRevenue](#AccrueRevenue)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Adjustment](#Adjustment)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Estimate](#Estimate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Invoice](#Invoice)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[PostCosts](#PostCosts)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Subscription](#Subscription)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ApprovedTimesheetPosting](#ApprovedTimesheetPosting)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[MaximumNumberOfTimesheetsPerPeriod](#MaximumNumberOfTimesheetsPerPeriod)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[MethodOfPayment](#MethodOfPayment)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[MinimumTimeIncrement](#MinimumTimeIncrement)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[MissingTimesheetsEmailId](#MissingTimesheetsEmailId)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ForecastModel](#ForecastModel)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[FolderForMicrosoftProjectFiles](#FolderForMicrosoftProjectFiles)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[SaveMicrosoftProjectFilesTo](#SaveMicrosoftProjectFilesTo)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsPaymentCriteria](#IsPaymentCriteria)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[OriginalBudget](#OriginalBudget)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultPostingLevel](#DefaultPostingLevel)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Posted](#Posted)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[PostingMethod](#PostingMethod)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TransactionTypesControlled](#TransactionTypesControlled)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[BudgetControlInterval](#BudgetControlInterval)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ProjectBudgetManagement](#ProjectBudgetManagement)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[BudgetOverrunDefault](#BudgetOverrunDefault)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[NegativeBudgetsToBeCarriedForwardAllowed](#NegativeBudgetsToBeCarriedForwardAllowed)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsCarryForwardRemainingBudgets](#IsCarryForwardRemainingBudgets)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CostControlMethods](#CostControlMethods)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[SetSubproductionToConsumed](#SetSubproductionToConsumed)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[PromptForCustomerInformation](#PromptForCustomerInformation)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[PromptForCustomerInformationOnProject](#PromptForCustomerInformationOnProject)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[RemainingBudget](#RemainingBudget)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsActivityExpenseForecastRequired](#IsActivityExpenseForecastRequired)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsActivityExpenseJournalRequired](#IsActivityExpenseJournalRequired)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsActivityHourForecastRequired](#IsActivityHourForecastRequired)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsActivityHourJournalRequired](#IsActivityHourJournalRequired)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsActivityItemForecastRequired](#IsActivityItemForecastRequired)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsActivityItemJournalRequired](#IsActivityItemJournalRequired)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsStartStopTimeRequired](#IsStartStopTimeRequired)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultCategoryFee](#DefaultCategoryFee)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultJournalNamesFee](#DefaultJournalNamesFee)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HasFinishedProjects](#HasFinishedProjects)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HasInactiveCategories](#HasInactiveCategories)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HasTerminatedWorkers](#HasTerminatedWorkers)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsHourCostInConsumptionStatementIncluded](#IsHourCostInConsumptionStatementIncluded)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsHourQuantityInConsumptionStatementIncluded](#IsHourQuantityInConsumptionStatementIncluded)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsHourCostInProfitLossStatementIncluded](#IsHourCostInProfitLossStatementIncluded)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsHourQuantityInProfitLossStatementIncluded](#IsHourQuantityInProfitLossStatementIncluded)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CalculationDateType](#CalculationDateType)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[SalesTaxGroupMethod](#SalesTaxGroupMethod)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemSalesTaxGroupMethod](#ItemSalesTaxGroupMethod)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TaxItemGroupOnAcc](#TaxItemGroupOnAcc)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimesheetJournal](#TimesheetJournal)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AllowTimeRangeOverlap](#AllowTimeRangeOverlap)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HasTimeRegistration](#HasTimeRegistration)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AbsenceProject](#AbsenceProject)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsTimesheetAuditTrailRequired](#IsTimesheetAuditTrailRequired)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsFutureTimesheetEntriesBlocked](#IsFutureTimesheetEntriesBlocked)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AllowTimesheetChangeReason](#AllowTimesheetChangeReason)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[RequireTimesheetChangeReason](#RequireTimesheetChangeReason)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ValidateAbsence](#ValidateAbsence)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TotalEstimatePostingTolerance](#TotalEstimatePostingTolerance)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TotalBudget](#TotalBudget)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ExpenseReport](#ExpenseReport)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[HourJournal](#HourJournal)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemJournal](#ItemJournal)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ItemRequirement](#ItemRequirement)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Production](#Production)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[PurchaseOrder](#PurchaseOrder)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[PurchaseRequisition](#PurchaseRequisition)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[SalesOrder](#SalesOrder)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Timesheets](#Timesheets)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TravelRequisition](#TravelRequisition)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[VendorInvoice](#VendorInvoice)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AfterEliminationDate](#AfterEliminationDate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[BeforeEliminationDate](#BeforeEliminationDate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[UseAdjustmentDateAsNewProjectDate](#UseAdjustmentDateAsNewProjectDate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[UseBudgetControl](#UseBudgetControl)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[UseFavorites](#UseFavorites)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[UtilizationRate](#UtilizationRate)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ValidationWorkerCategory](#ValidationWorkerCategory)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ValidationWorkerProject](#ValidationWorkerProject)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ValidationProjectCategory](#ValidationProjectCategory)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ValueAddedDecimals](#ValueAddedDecimals)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[ValueAddedDisplay](#ValueAddedDisplay)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[SetVoucherDateTo](#SetVoucherDateTo)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DayWeekStarts](#DayWeekStarts)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AutomaticallySetAccountingDateToOpenLedgerPeriod](#AutomaticallySetAccountingDateToOpenLedgerPeriod)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CategoryName](#CategoryName)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CategoryHierarchyName](#CategoryHierarchyName)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeMaterialBillable](#TimeMaterialBillable)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeMaterialEfficiency](#TimeMaterialEfficiency)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[FixedPriceBillable](#FixedPriceBillable)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[FixedPriceEfficiency](#FixedPriceEfficiency)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[InvestmentBillable](#InvestmentBillable)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[InvestmentEfficiency](#InvestmentEfficiency)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[InternalCostBillable](#InternalCostBillable)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[InternalCostEfficiency](#InternalCostEfficiency)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeProjectsBillable](#TimeProjectsBillable)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeProjectsEfficiency](#TimeProjectsEfficiency)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CapacityPlanningPlannedOrder](#CapacityPlanningPlannedOrder)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CapacityPlanningProduction](#CapacityPlanningProduction)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DefaultWorkingCalendar](#DefaultWorkingCalendar)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsHourSchedulingEnabled](#IsHourSchedulingEnabled)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[EnableCancelSettledProjectInvoice](#EnableCancelSettledProjectInvoice)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsEnableAlternativeAccountForCancellation](#IsEnableAlternativeAccountForCancellation)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AuthorizedSignatory](#AuthorizedSignatory)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[DesignationOfSignatory](#DesignationOfSignatory)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[EnableCancelSettledDebitNote](#EnableCancelSettledDebitNote)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsInvoicePrintingByCategory](#IsInvoicePrintingByCategory)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsInvoicePrintingByTransactionText](#IsInvoicePrintingByTransactionText)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsInvoicePrintingByEmployee](#IsInvoicePrintingByEmployee)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsInvoicePrintingByInvoiceType](#IsInvoicePrintingByInvoiceType)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsInvoicePrintingByLineSpecific](#IsInvoicePrintingByLineSpecific)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CFOPSameState](#CFOPSameState)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CFOPOtherState](#CFOPOtherState)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CFOPOutsideCountryRegion](#CFOPOutsideCountryRegion)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CFOPIdSameState](#CFOPIdSameState)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CFOPIdOtherState](#CFOPIdOtherState)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[CFOPIdOutsideCountryRegion](#CFOPIdOutsideCountryRegion)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[IsSplitInvoiceBasedOnServiceCode](#IsSplitInvoiceBasedOnServiceCode)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[NoOneTimeCustomersForProjectContracts](#NoOneTimeCustomersForProjectContracts)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[GeneralBudgetReservation](#GeneralBudgetReservation)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceEnableService](#TimeServiceEnableService)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceEnableDefaultLineProperty](#TimeServiceEnableDefaultLineProperty)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceVisibilityActivity](#TimeServiceVisibilityActivity)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceVisibilityCategory](#TimeServiceVisibilityCategory)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceVisibilityCustomer](#TimeServiceVisibilityCustomer)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceVisibilityExternalComment](#TimeServiceVisibilityExternalComment)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceVisibilityInternalComment](#TimeServiceVisibilityInternalComment)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceVisibilityItemSalesTaxGroup](#TimeServiceVisibilityItemSalesTaxGroup)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceVisibilityLineProperty](#TimeServiceVisibilityLineProperty)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[TimeServiceVisibilitySalesTaxGroup](#TimeServiceVisibilitySalesTaxGroup)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[AllowSalesOrdersForMultipleFundingSources](#AllowSalesOrdersForMultipleFundingSources)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[BackingTable_ProjParametersRelationshipId](#BackingTable_ProjParametersRelationshipId)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjectParameterEntity.md" target="_blank">ProjectManagementAndAccounting/ProjectParameterEntity</a>|

### <a href=#ItemLumpSumAllocationKey name="ItemLumpSumAllocationKey">ItemLumpSumAllocationKey</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLumpSumAllocationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPaymentForHours name="TermsOfPaymentForHours">TermsOfPaymentForHours</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPaymentForHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualCostAfterEstimateDate name="ActualCostAfterEstimateDate">ActualCostAfterEstimateDate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualCostAfterEstimateDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommittedCostAfterEstimateDate name="CommittedCostAfterEstimateDate">CommittedCostAfterEstimateDate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommittedCostAfterEstimateDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommittedCostUpToEstimateDate name="CommittedCostUpToEstimateDate">CommittedCostUpToEstimateDate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommittedCostUpToEstimateDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutoupdateField name="IsAutoupdateField">IsAutoupdateField</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutoupdateField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBudgetControlOutsideTheProjectHierarchyAllowed name="IsBudgetControlOutsideTheProjectHierarchyAllowed">IsBudgetControlOutsideTheProjectHierarchyAllowed</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBudgetControlOutsideTheProjectHierarchyAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDateCorrectionsOnTimesheetsAllowed name="IsDateCorrectionsOnTimesheetsAllowed">IsDateCorrectionsOnTimesheetsAllowed</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDateCorrectionsOnTimesheetsAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEliminationWithoutPostingEstimatesAllowed name="IsEliminationWithoutPostingEstimatesAllowed">IsEliminationWithoutPostingEstimatesAllowed</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEliminationWithoutPostingEstimatesAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanAlwaysCreateAdjustmentTransaction name="CanAlwaysCreateAdjustmentTransaction">CanAlwaysCreateAdjustmentTransaction</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanAlwaysCreateAdjustmentTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInMillions name="AmountInMillions">AmountInMillions</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInMillions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInThousands name="AmountInThousands">AmountInThousands</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInThousands attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActive name="IsActive">IsActive</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserGroup name="UserGroup">UserGroup</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemConsumption name="IsItemConsumption">IsItemConsumption</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemConsumption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BeginningBalances name="BeginningBalances">BeginningBalances</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BeginningBalances attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommittedCost name="CommittedCost">CommittedCost</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommittedCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingRuleFeeJournal name="BillingRuleFeeJournal">BillingRuleFeeJournal</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingRuleFeeJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCategoryExpense name="DefaultCategoryExpense">DefaultCategoryExpense</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCategoryExpense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCostTemplate name="DefaultCostTemplate">DefaultCostTemplate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCostTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreateItemRequirement name="IsCreateItemRequirement">IsCreateItemRequirement</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreateItemRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLineError name="CreditLineError">CreditLineError</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLineError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetTheCostPriceAsTheSalesPriceByDefault name="SetTheCostPriceAsTheSalesPriceByDefault">SetTheCostPriceAsTheSalesPriceByDefault</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetTheCostPriceAsTheSalesPriceByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultItemAllocationKey name="DefaultItemAllocationKey">DefaultItemAllocationKey</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultItemAllocationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCategory name="DefaultCategory">DefaultCategory</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSubprojectIDFormat name="DefaultSubprojectIDFormat">DefaultSubprojectIDFormat</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSubprojectIDFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayTransactions name="DisplayTransactions">DisplayTransactions</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProjectType name="DefaultProjectType">DefaultProjectType</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProjectType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Eliminated name="Eliminated">Eliminated</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Eliminated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCategoryHour name="DefaultCategoryHour">DefaultCategoryHour</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCategoryHour attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultJournalNamesHour name="DefaultJournalNamesHour">DefaultJournalNamesHour</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultJournalNamesHour attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckBudgetOnDocumentLineSave name="CheckBudgetOnDocumentLineSave">CheckBudgetOnDocumentLineSave</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckBudgetOnDocumentLineSave attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyResourceSchedulingAndTimesheetsEnabled name="IsIntercompanyResourceSchedulingAndTimesheetsEnabled">IsIntercompanyResourceSchedulingAndTimesheetsEnabled</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyResourceSchedulingAndTimesheetsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcessingInvoiceProposalsInWorkflowEnabled name="IsProcessingInvoiceProposalsInWorkflowEnabled">IsProcessingInvoiceProposalsInWorkflowEnabled</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcessingInvoiceProposalsInWorkflowEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Estimated name="Estimated">Estimated</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Estimated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseDeleteReducedToZero name="ExpenseDeleteReducedToZero">ExpenseDeleteReducedToZero</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseDeleteReducedToZero attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseJournalNameId name="ExpenseJournalNameId">ExpenseJournalNameId</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseLumpSumAllocationKey name="ExpenseLumpSumAllocationKey">ExpenseLumpSumAllocationKey</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseLumpSumAllocationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseReduceCostPriority1 name="ExpenseReduceCostPriority1">ExpenseReduceCostPriority1</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseReduceCostPriority1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseReduceCostPriority2 name="ExpenseReduceCostPriority2">ExpenseReduceCostPriority2</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseReduceCostPriority2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseReduceCostPriority3 name="ExpenseReduceCostPriority3">ExpenseReduceCostPriority3</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseReduceCostPriority3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseReduceCostPriority4 name="ExpenseReduceCostPriority4">ExpenseReduceCostPriority4</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseReduceCostPriority4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseReduceCostPriority5 name="ExpenseReduceCostPriority5">ExpenseReduceCostPriority5</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseReduceCostPriority5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumRequirement name="MinimumRequirement">MinimumRequirement</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralBufferDays name="GeneralBufferDays">GeneralBufferDays</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralBufferDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPaymentForExpenses name="TermsOfPaymentForExpenses">TermsOfPaymentForExpenses</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPaymentForExpenses attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPaymentForItems name="TermsOfPaymentForItems">TermsOfPaymentForItems</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPaymentForItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllocationSettingsLocked name="IsAllocationSettingsLocked">IsAllocationSettingsLocked</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllocationSettingsLocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplyPrioritySettingsFirstOrLastInFundingAllocationOrder name="ApplyPrioritySettingsFirstOrLastInFundingAllocationOrder">ApplyPrioritySettingsFirstOrLastInFundingAllocationOrder</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyPrioritySettingsFirstOrLastInFundingAllocationOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossMarginDecimals name="GrossMarginDecimals">GrossMarginDecimals</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossMarginDecimals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossMarginRatio name="GrossMarginRatio">GrossMarginRatio</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossMarginRatio attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideActivity name="HideActivity">HideActivity</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideActivity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideCategory name="HideCategory">HideCategory</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideExternalComments name="HideExternalComments">HideExternalComments</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideExternalComments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideLineProperty name="HideLineProperty">HideLineProperty</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideLineProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourDeleteReducedToZero name="HourDeleteReducedToZero">HourDeleteReducedToZero</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourDeleteReducedToZero attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourQtyDecimals name="HourQtyDecimals">HourQtyDecimals</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourQtyDecimals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourReduceCostPriority1 name="HourReduceCostPriority1">HourReduceCostPriority1</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourReduceCostPriority1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourReduceCostPriority2 name="HourReduceCostPriority2">HourReduceCostPriority2</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourReduceCostPriority2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourReduceCostPriority3 name="HourReduceCostPriority3">HourReduceCostPriority3</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourReduceCostPriority3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourReduceCostPriority4 name="HourReduceCostPriority4">HourReduceCostPriority4</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourReduceCostPriority4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourReduceCostPriority5 name="HourReduceCostPriority5">HourReduceCostPriority5</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourReduceCostPriority5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourReducedMinimumRequirement name="HourReducedMinimumRequirement">HourReducedMinimumRequirement</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourReducedMinimumRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultJournalNameItem name="DefaultJournalNameItem">DefaultJournalNameItem</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultJournalNameItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoiced name="Invoiced">Invoiced</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoiced attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceProposal name="InvoiceProposal">InvoiceProposal</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceProposal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCategoryItem name="DefaultCategoryItem">DefaultCategoryItem</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCategoryItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemDeleteReducedToZero name="ItemDeleteReducedToZero">ItemDeleteReducedToZero</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemDeleteReducedToZero attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNeverLedgerConsum name="ItemNeverLedgerConsum">ItemNeverLedgerConsum</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNeverLedgerConsum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemNeverLedgerPL name="IsItemNeverLedgerPL">IsItemNeverLedgerPL</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemNeverLedgerPL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemReduceCostPriority1 name="ItemReduceCostPriority1">ItemReduceCostPriority1</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemReduceCostPriority1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemReduceCostPriority2 name="ItemReduceCostPriority2">ItemReduceCostPriority2</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemReduceCostPriority2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemReduceCostPriority3 name="ItemReduceCostPriority3">ItemReduceCostPriority3</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemReduceCostPriority3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemReduceCostPriority4 name="ItemReduceCostPriority4">ItemReduceCostPriority4</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemReduceCostPriority4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemReduceCostPriority5 name="ItemReduceCostPriority5">ItemReduceCostPriority5</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemReduceCostPriority5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemMinimumRequirement name="ItemMinimumRequirement">ItemMinimumRequirement</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemMinimumRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ID name="ID">ID</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrueRevenue name="AccrueRevenue">AccrueRevenue</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrueRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Adjustment name="Adjustment">Adjustment</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Adjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Estimate name="Estimate">Estimate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Estimate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostCosts name="PostCosts">PostCosts</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostCosts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Subscription name="Subscription">Subscription</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Subscription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovedTimesheetPosting name="ApprovedTimesheetPosting">ApprovedTimesheetPosting</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovedTimesheetPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumNumberOfTimesheetsPerPeriod name="MaximumNumberOfTimesheetsPerPeriod">MaximumNumberOfTimesheetsPerPeriod</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumNumberOfTimesheetsPerPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MethodOfPayment name="MethodOfPayment">MethodOfPayment</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MethodOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumTimeIncrement name="MinimumTimeIncrement">MinimumTimeIncrement</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumTimeIncrement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MissingTimesheetsEmailId name="MissingTimesheetsEmailId">MissingTimesheetsEmailId</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MissingTimesheetsEmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastModel name="ForecastModel">ForecastModel</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FolderForMicrosoftProjectFiles name="FolderForMicrosoftProjectFiles">FolderForMicrosoftProjectFiles</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FolderForMicrosoftProjectFiles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SaveMicrosoftProjectFilesTo name="SaveMicrosoftProjectFilesTo">SaveMicrosoftProjectFilesTo</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaveMicrosoftProjectFilesTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPaymentCriteria name="IsPaymentCriteria">IsPaymentCriteria</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPaymentCriteria attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalBudget name="OriginalBudget">OriginalBudget</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalBudget attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPostingLevel name="DefaultPostingLevel">DefaultPostingLevel</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPostingLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingMethod name="PostingMethod">PostingMethod</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionTypesControlled name="TransactionTypesControlled">TransactionTypesControlled</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

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

### <a href=#NegativeBudgetsToBeCarriedForwardAllowed name="NegativeBudgetsToBeCarriedForwardAllowed">NegativeBudgetsToBeCarriedForwardAllowed</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeBudgetsToBeCarriedForwardAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCarryForwardRemainingBudgets name="IsCarryForwardRemainingBudgets">IsCarryForwardRemainingBudgets</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCarryForwardRemainingBudgets attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostControlMethods name="CostControlMethods">CostControlMethods</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostControlMethods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetSubproductionToConsumed name="SetSubproductionToConsumed">SetSubproductionToConsumed</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetSubproductionToConsumed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PromptForCustomerInformation name="PromptForCustomerInformation">PromptForCustomerInformation</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptForCustomerInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PromptForCustomerInformationOnProject name="PromptForCustomerInformationOnProject">PromptForCustomerInformationOnProject</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptForCustomerInformationOnProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingBudget name="RemainingBudget">RemainingBudget</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingBudget attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityExpenseForecastRequired name="IsActivityExpenseForecastRequired">IsActivityExpenseForecastRequired</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityExpenseForecastRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityExpenseJournalRequired name="IsActivityExpenseJournalRequired">IsActivityExpenseJournalRequired</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityExpenseJournalRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityHourForecastRequired name="IsActivityHourForecastRequired">IsActivityHourForecastRequired</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityHourForecastRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityHourJournalRequired name="IsActivityHourJournalRequired">IsActivityHourJournalRequired</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityHourJournalRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityItemForecastRequired name="IsActivityItemForecastRequired">IsActivityItemForecastRequired</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityItemForecastRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivityItemJournalRequired name="IsActivityItemJournalRequired">IsActivityItemJournalRequired</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivityItemJournalRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStartStopTimeRequired name="IsStartStopTimeRequired">IsStartStopTimeRequired</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStartStopTimeRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCategoryFee name="DefaultCategoryFee">DefaultCategoryFee</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCategoryFee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultJournalNamesFee name="DefaultJournalNamesFee">DefaultJournalNamesFee</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultJournalNamesFee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasFinishedProjects name="HasFinishedProjects">HasFinishedProjects</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasFinishedProjects attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasInactiveCategories name="HasInactiveCategories">HasInactiveCategories</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasInactiveCategories attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasTerminatedWorkers name="HasTerminatedWorkers">HasTerminatedWorkers</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasTerminatedWorkers attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsHourCostInConsumptionStatementIncluded name="IsHourCostInConsumptionStatementIncluded">IsHourCostInConsumptionStatementIncluded</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsHourCostInConsumptionStatementIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsHourQuantityInConsumptionStatementIncluded name="IsHourQuantityInConsumptionStatementIncluded">IsHourQuantityInConsumptionStatementIncluded</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsHourQuantityInConsumptionStatementIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsHourCostInProfitLossStatementIncluded name="IsHourCostInProfitLossStatementIncluded">IsHourCostInProfitLossStatementIncluded</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsHourCostInProfitLossStatementIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsHourQuantityInProfitLossStatementIncluded name="IsHourQuantityInProfitLossStatementIncluded">IsHourQuantityInProfitLossStatementIncluded</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsHourQuantityInProfitLossStatementIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculationDateType name="CalculationDateType">CalculationDateType</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationDateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupMethod name="SalesTaxGroupMethod">SalesTaxGroupMethod</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroupMethod name="ItemSalesTaxGroupMethod">ItemSalesTaxGroupMethod</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroupMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroupOnAcc name="TaxItemGroupOnAcc">TaxItemGroupOnAcc</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroupOnAcc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimesheetJournal name="TimesheetJournal">TimesheetJournal</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimesheetJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTimeRangeOverlap name="AllowTimeRangeOverlap">AllowTimeRangeOverlap</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTimeRangeOverlap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasTimeRegistration name="HasTimeRegistration">HasTimeRegistration</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasTimeRegistration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AbsenceProject name="AbsenceProject">AbsenceProject</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsenceProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTimesheetAuditTrailRequired name="IsTimesheetAuditTrailRequired">IsTimesheetAuditTrailRequired</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTimesheetAuditTrailRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFutureTimesheetEntriesBlocked name="IsFutureTimesheetEntriesBlocked">IsFutureTimesheetEntriesBlocked</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFutureTimesheetEntriesBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTimesheetChangeReason name="AllowTimesheetChangeReason">AllowTimesheetChangeReason</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTimesheetChangeReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireTimesheetChangeReason name="RequireTimesheetChangeReason">RequireTimesheetChangeReason</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireTimesheetChangeReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateAbsence name="ValidateAbsence">ValidateAbsence</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateAbsence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalEstimatePostingTolerance name="TotalEstimatePostingTolerance">TotalEstimatePostingTolerance</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalEstimatePostingTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalBudget name="TotalBudget">TotalBudget</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalBudget attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseReport name="ExpenseReport">ExpenseReport</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseReport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourJournal name="HourJournal">HourJournal</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemJournal name="ItemJournal">ItemJournal</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRequirement name="ItemRequirement">ItemRequirement</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Production name="Production">Production</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Production attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrder name="PurchaseOrder">PurchaseOrder</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseRequisition name="PurchaseRequisition">PurchaseRequisition</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRequisition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrder name="SalesOrder">SalesOrder</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Timesheets name="Timesheets">Timesheets</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timesheets attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TravelRequisition name="TravelRequisition">TravelRequisition</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelRequisition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoice name="VendorInvoice">VendorInvoice</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AfterEliminationDate name="AfterEliminationDate">AfterEliminationDate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AfterEliminationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BeforeEliminationDate name="BeforeEliminationDate">BeforeEliminationDate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BeforeEliminationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseAdjustmentDateAsNewProjectDate name="UseAdjustmentDateAsNewProjectDate">UseAdjustmentDateAsNewProjectDate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseAdjustmentDateAsNewProjectDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseBudgetControl name="UseBudgetControl">UseBudgetControl</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseBudgetControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseFavorites name="UseFavorites">UseFavorites</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFavorites attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UtilizationRate name="UtilizationRate">UtilizationRate</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UtilizationRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationWorkerCategory name="ValidationWorkerCategory">ValidationWorkerCategory</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationWorkerCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationWorkerProject name="ValidationWorkerProject">ValidationWorkerProject</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationWorkerProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationProjectCategory name="ValidationProjectCategory">ValidationProjectCategory</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationProjectCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueAddedDecimals name="ValueAddedDecimals">ValueAddedDecimals</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueAddedDecimals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueAddedDisplay name="ValueAddedDisplay">ValueAddedDisplay</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueAddedDisplay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetVoucherDateTo name="SetVoucherDateTo">SetVoucherDateTo</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetVoucherDateTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DayWeekStarts name="DayWeekStarts">DayWeekStarts</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DayWeekStarts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticallySetAccountingDateToOpenLedgerPeriod name="AutomaticallySetAccountingDateToOpenLedgerPeriod">AutomaticallySetAccountingDateToOpenLedgerPeriod</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticallySetAccountingDateToOpenLedgerPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryName name="CategoryName">CategoryName</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchyName name="CategoryHierarchyName">CategoryHierarchyName</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeMaterialBillable name="TimeMaterialBillable">TimeMaterialBillable</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeMaterialBillable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeMaterialEfficiency name="TimeMaterialEfficiency">TimeMaterialEfficiency</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeMaterialEfficiency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPriceBillable name="FixedPriceBillable">FixedPriceBillable</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedPriceBillable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPriceEfficiency name="FixedPriceEfficiency">FixedPriceEfficiency</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedPriceEfficiency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvestmentBillable name="InvestmentBillable">InvestmentBillable</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvestmentBillable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvestmentEfficiency name="InvestmentEfficiency">InvestmentEfficiency</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvestmentEfficiency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalCostBillable name="InternalCostBillable">InternalCostBillable</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalCostBillable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalCostEfficiency name="InternalCostEfficiency">InternalCostEfficiency</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalCostEfficiency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProjectsBillable name="TimeProjectsBillable">TimeProjectsBillable</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProjectsBillable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProjectsEfficiency name="TimeProjectsEfficiency">TimeProjectsEfficiency</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProjectsEfficiency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacityPlanningPlannedOrder name="CapacityPlanningPlannedOrder">CapacityPlanningPlannedOrder</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacityPlanningPlannedOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacityPlanningProduction name="CapacityPlanningProduction">CapacityPlanningProduction</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacityPlanningProduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultWorkingCalendar name="DefaultWorkingCalendar">DefaultWorkingCalendar</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultWorkingCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsHourSchedulingEnabled name="IsHourSchedulingEnabled">IsHourSchedulingEnabled</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsHourSchedulingEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableCancelSettledProjectInvoice name="EnableCancelSettledProjectInvoice">EnableCancelSettledProjectInvoice</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableCancelSettledProjectInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEnableAlternativeAccountForCancellation name="IsEnableAlternativeAccountForCancellation">IsEnableAlternativeAccountForCancellation</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable alternative account for cancellation</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEnableAlternativeAccountForCancellation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable alternative account for cancellation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuthorizedSignatory name="AuthorizedSignatory">AuthorizedSignatory</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorizedSignatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DesignationOfSignatory name="DesignationOfSignatory">DesignationOfSignatory</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DesignationOfSignatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableCancelSettledDebitNote name="EnableCancelSettledDebitNote">EnableCancelSettledDebitNote</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableCancelSettledDebitNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoicePrintingByCategory name="IsInvoicePrintingByCategory">IsInvoicePrintingByCategory</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Printing by Category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoicePrintingByCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice Printing by Category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoicePrintingByTransactionText name="IsInvoicePrintingByTransactionText">IsInvoicePrintingByTransactionText</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Printing by Transaction Text</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoicePrintingByTransactionText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice Printing by Transaction Text</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoicePrintingByEmployee name="IsInvoicePrintingByEmployee">IsInvoicePrintingByEmployee</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Printing by Employee</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoicePrintingByEmployee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice Printing by Employee</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoicePrintingByInvoiceType name="IsInvoicePrintingByInvoiceType">IsInvoicePrintingByInvoiceType</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Printing by Invoice Type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoicePrintingByInvoiceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice Printing by Invoice Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoicePrintingByLineSpecific name="IsInvoicePrintingByLineSpecific">IsInvoicePrintingByLineSpecific</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Printing by Line-specific</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoicePrintingByLineSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice Printing by Line-specific</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPSameState name="CFOPSameState">CFOPSameState</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPSameState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPOtherState name="CFOPOtherState">CFOPOtherState</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPOtherState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPOutsideCountryRegion name="CFOPOutsideCountryRegion">CFOPOutsideCountryRegion</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPOutsideCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPIdSameState name="CFOPIdSameState">CFOPIdSameState</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cfop Same State</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPIdSameState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cfop Same State</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPIdOtherState name="CFOPIdOtherState">CFOPIdOtherState</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cfop Other State</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPIdOtherState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cfop Other State</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPIdOutsideCountryRegion name="CFOPIdOutsideCountryRegion">CFOPIdOutsideCountryRegion</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cfop Outside Country/Region</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPIdOutsideCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cfop Outside Country/Region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSplitInvoiceBasedOnServiceCode name="IsSplitInvoiceBasedOnServiceCode">IsSplitInvoiceBasedOnServiceCode</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Split Invoice Based On Service Code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSplitInvoiceBasedOnServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Split Invoice Based On Service Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NoOneTimeCustomersForProjectContracts name="NoOneTimeCustomersForProjectContracts">NoOneTimeCustomersForProjectContracts</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NoOneTimeCustomersForProjectContracts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralBudgetReservation name="GeneralBudgetReservation">GeneralBudgetReservation</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralBudgetReservation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceEnableService name="TimeServiceEnableService">TimeServiceEnableService</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceEnableService attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceEnableDefaultLineProperty name="TimeServiceEnableDefaultLineProperty">TimeServiceEnableDefaultLineProperty</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceEnableDefaultLineProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceVisibilityActivity name="TimeServiceVisibilityActivity">TimeServiceVisibilityActivity</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceVisibilityActivity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceVisibilityCategory name="TimeServiceVisibilityCategory">TimeServiceVisibilityCategory</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceVisibilityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceVisibilityCustomer name="TimeServiceVisibilityCustomer">TimeServiceVisibilityCustomer</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceVisibilityCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceVisibilityExternalComment name="TimeServiceVisibilityExternalComment">TimeServiceVisibilityExternalComment</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceVisibilityExternalComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceVisibilityInternalComment name="TimeServiceVisibilityInternalComment">TimeServiceVisibilityInternalComment</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceVisibilityInternalComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceVisibilityItemSalesTaxGroup name="TimeServiceVisibilityItemSalesTaxGroup">TimeServiceVisibilityItemSalesTaxGroup</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceVisibilityItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceVisibilityLineProperty name="TimeServiceVisibilityLineProperty">TimeServiceVisibilityLineProperty</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceVisibilityLineProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeServiceVisibilitySalesTaxGroup name="TimeServiceVisibilitySalesTaxGroup">TimeServiceVisibilitySalesTaxGroup</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeServiceVisibilitySalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowSalesOrdersForMultipleFundingSources name="AllowSalesOrdersForMultipleFundingSources">AllowSalesOrdersForMultipleFundingSources</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSalesOrdersForMultipleFundingSources attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProjParametersRelationshipId name="BackingTable_ProjParametersRelationshipId">BackingTable_ProjParametersRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Parameter/ProjParameters.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Parameter/ProjParameters.cdm.json/ProjParameters</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Parameter/ProjParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjectParameterEntity (this entity)  

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
