---
title: VendVendorParametersEntity in AccountsPayable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Vendor parameters in AccountsPayable(VendVendorParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendVendorParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RoyaltyAccrualJournalName](#RoyaltyAccrualJournalName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[InvoicingPeriod](#InvoicingPeriod)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PrimaryDiscountPosting](#PrimaryDiscountPosting)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PrimaryReceiptPosting](#PrimaryReceiptPosting)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PrepaymentInvoicePostingProfile](#PrepaymentInvoicePostingProfile)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsAutomaticSettlement](#IsAutomaticSettlement)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AllocationKey](#AllocationKey)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CashDiscountAdministration](#CashDiscountAdministration)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsCashDiscountCalculatedForCreditNotes](#IsCashDiscountCalculatedForCreditNotes)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsCashDiscountCalculatedForPartialPayments](#IsCashDiscountCalculatedForPartialPayments)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsCashDiscountCalculatedOnAmountIncludingSalesTax](#IsCashDiscountCalculatedOnAmountIncludingSalesTax)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsCheckInvoiceNumberUsed](#IsCheckInvoiceNumberUsed)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CheckTheTaxInvoiceNumberUsed](#CheckTheTaxInvoiceNumberUsed)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CreditNoteAsCorrection](#CreditNoteAsCorrection)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CreditMaxCheck](#CreditMaxCheck)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DefaultSettlementTypeForCreditNotes](#DefaultSettlementTypeForCreditNotes)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DefaultVend](#DefaultVend)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DisplayPriceTotalMatchIcon](#DisplayPriceTotalMatchIcon)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DisplayMiscChargeToleranceIcon](#DisplayMiscChargeToleranceIcon)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DisplayPriceMatchIcon](#DisplayPriceMatchIcon)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DisplayInvoiceTotalsMatchIcon](#DisplayInvoiceTotalsMatchIcon)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsPrintTransportationDetails](#IsPrintTransportationDetails)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SettlePeriod](#SettlePeriod)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PurchasePriceTotalTolerance](#PurchasePriceTotalTolerance)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PurchasePriceTotalTolerancePercent](#PurchasePriceTotalTolerancePercent)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[FactureIssuePeriod](#FactureIssuePeriod)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[TermsOfPayment](#TermsOfPayment)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[KeepSalesTaxAdjustmentsForPOInvoices](#KeepSalesTaxAdjustmentsForPOInvoices)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ID](#ID)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[TaxExemptNumberRequirement](#TaxExemptNumberRequirement)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[MandatoryTaxGroup](#MandatoryTaxGroup)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[MandatoryVATNum](#MandatoryVATNum)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[LineMatchingPolicy](#LineMatchingPolicy)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AllowMatchingPolicyOverride](#AllowMatchingPolicyOverride)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[MaximumPennyDifference](#MaximumPennyDifference)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[MaximumOverpaymentOrUnderpayment](#MaximumOverpaymentOrUnderpayment)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DifferentialJournalName](#DifferentialJournalName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ExpenseJournalName](#ExpenseJournalName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ManualPosting](#ManualPosting)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ProcurementCategory](#ProcurementCategory)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AccrualAccount](#AccrualAccount)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[RoyaltyExpenseAccount](#RoyaltyExpenseAccount)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[StartingDayOfWeek](#StartingDayOfWeek)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ChargesTolerancePercentage](#ChargesTolerancePercentage)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[WarnIfPaymentProposalUsesMultipleMethodsOfPayment](#WarnIfPaymentProposalUsesMultipleMethodsOfPayment)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ValidationsOnPromissoryNotesJournals](#ValidationsOnPromissoryNotesJournals)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ResponseToInvoicesThatFailValidation](#ResponseToInvoicesThatFailValidation)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PostToChargeAccountInLedger](#PostToChargeAccountInLedger)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[InvoiceRemit](#InvoiceRemit)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PromissoryNotes](#PromissoryNotes)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[RemitPromissoryNote](#RemitPromissoryNote)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PostInvoiceMatchDiscrepancies](#PostInvoiceMatchDiscrepancies)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PostProductReceiptInLedger](#PostProductReceiptInLedger)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PostingProfileForPaymentJournalWithPrepayment](#PostingProfileForPaymentJournalWithPrepayment)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PrimaryRelationTaxMatrix](#PrimaryRelationTaxMatrix)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AccountStructure](#AccountStructure)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[FinancialDimension](#FinancialDimension)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsShowAmountDebitCredit](#IsShowAmountDebitCredit)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SalesTaxOnPrepaymentInPaymentJournal](#SalesTaxOnPrepaymentInPaymentJournal)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[InvoiceTotalsTolerancePercentage](#InvoiceTotalsTolerancePercentage)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[UseDocumentDate](#UseDocumentDate)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[MatchPriceTotals](#MatchPriceTotals)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[EnableInvoiceMatchingValidation](#EnableInvoiceMatchingValidation)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsMatchCharges](#IsMatchCharges)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsMatchInvoiceTotals](#IsMatchInvoiceTotals)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DiscountOffsetAccounts](#DiscountOffsetAccounts)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DefaultCodeForInvoiceGroups](#DefaultCodeForInvoiceGroups)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[RequireDocumentDateOnVendorInvoice](#RequireDocumentDateOnVendorInvoice)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[UseInvoiceGroupsForThisCompany](#UseInvoiceGroupsForThisCompany)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CustomCodeForInvoiceGroups](#CustomCodeForInvoiceGroups)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ValidateInvoicesInTheJournal](#ValidateInvoicesInTheJournal)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CustomCodeForWebServiceInvoices](#CustomCodeForWebServiceInvoices)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ActivateInvoicePaymentGroups](#ActivateInvoicePaymentGroups)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[TimeOfSalesTaxPosting](#TimeOfSalesTaxPosting)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[IsW9Validation](#IsW9Validation)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[BrokerProcurementCategory](#BrokerProcurementCategory)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AutomaticHeaderMatching](#AutomaticHeaderMatching)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CategoryName](#CategoryName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CategoryHierarchyName](#CategoryHierarchyName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[Draft](#Draft)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DimensionHierarchyIsSystemGenerated](#DimensionHierarchyIsSystemGenerated)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DimensionTreeName](#DimensionTreeName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DimensionHierarchyType](#DimensionHierarchyType)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PurchAgreementDimensionName](#PurchAgreementDimensionName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[BrokerCategoryHierarchy](#BrokerCategoryHierarchy)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[BrokerCategoryName](#BrokerCategoryName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[BrokerCategoryHierarchyName](#BrokerCategoryHierarchyName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AccrualAccountDisplayValue](#AccrualAccountDisplayValue)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[RoyaltyExpenseAccountDisplayValue](#RoyaltyExpenseAccountDisplayValue)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[UseConsolidatedInvoice](#UseConsolidatedInvoice)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[TaxWithholdCalculateCrossCompany](#TaxWithholdCalculateCrossCompany)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[TaxWithholdCompany](#TaxWithholdCompany)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[Include3wayMatching](#Include3wayMatching)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SplitDeliveryInvoice](#SplitDeliveryInvoice)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SplitDeliveryPackingSlip](#SplitDeliveryPackingSlip)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[InvoiceJoiningPreventionOnPromissoryNoteJournals](#InvoiceJoiningPreventionOnPromissoryNoteJournals)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DateTreatmentOnPromissoryNoteJournals](#DateTreatmentOnPromissoryNoteJournals)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[UseFiscalDataFromInvoiceAccount](#UseFiscalDataFromInvoiceAccount)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PurchPrepayApplicationPolicy](#PurchPrepayApplicationPolicy)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CashFlowTimeBetweenDeliveryDateAndInvoiceDate](#CashFlowTimeBetweenDeliveryDateAndInvoiceDate)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CashFlowTermsOfPayment](#CashFlowTermsOfPayment)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CashFlowTimeBetweenInvoiceDueDateAndPaymentDate](#CashFlowTimeBetweenInvoiceDueDateAndPaymentDate)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CashFlowLiquidityAccountForPayments](#CashFlowLiquidityAccountForPayments)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CashFlowLiquidityAccountForPaymentsDisplayValue](#CashFlowLiquidityAccountForPaymentsDisplayValue)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[CashFlowPercentageOfAmountToAllocateToCashFlowForecast](#CashFlowPercentageOfAmountToAllocateToCashFlowForecast)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[EditCashDiscountsWhenDueDateChanged](#EditCashDiscountsWhenDueDateChanged)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DefaultFilterForVendorTransactions](#DefaultFilterForVendorTransactions)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SettlementWriteOffEnabled](#SettlementWriteOffEnabled)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SettlementWriteOffJournalName](#SettlementWriteOffJournalName)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SettlementWriteOffReasonCode](#SettlementWriteOffReasonCode)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ChangeProposalIsEnabled](#ChangeProposalIsEnabled)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ChangeProposalDataEntityBehavior](#ChangeProposalDataEntityBehavior)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[VendInvoiceInUseRecoverEnable](#VendInvoiceInUseRecoverEnable)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[BypassValidationOfAccountingDistributions](#BypassValidationOfAccountingDistributions)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[MaxInvoicesPerBatch](#MaxInvoicesPerBatch)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[MaxWaitTimeForInvoiceScheduledStatus_Hours](#MaxWaitTimeForInvoiceScheduledStatus_Hours)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PollingInterval_Minutes](#PollingInterval_Minutes)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ReversePrepayment](#ReversePrepayment)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[SettlePrepaymentVATType](#SettlePrepaymentVATType)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AdvanceHoldersPostingProfile](#AdvanceHoldersPostingProfile)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AdvanceHoldersAutoSettle](#AdvanceHoldersAutoSettle)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[AdvanceHoldersSettlementByDimension](#AdvanceHoldersSettlementByDimension)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[DisablePaymentIDValidation](#DisablePaymentIDValidation)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[ImportFormatMappingNameQRBill](#ImportFormatMappingNameQRBill)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PSNActivatePurchasingCard](#PSNActivatePurchasingCard)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PSNPostingDefinitionRecId](#PSNPostingDefinitionRecId)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[PSNPostingDefinitionCode](#PSNPostingDefinitionCode)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[Relationship_AccrualAccountCombinationRelationshipId](#Relationship_AccrualAccountCombinationRelationshipId)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[Relationship_RoyaltyExpenseAccountCombinationRelationshipId](#Relationship_RoyaltyExpenseAccountCombinationRelationshipId)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[BackingTable_VendParametersRelationshipId](#BackingTable_VendParametersRelationshipId)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendVendorParametersEntity.md" target="_blank">AccountsPayable/VendVendorParametersEntity</a>|

### <a href=#RoyaltyAccrualJournalName name="RoyaltyAccrualJournalName">RoyaltyAccrualJournalName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyAccrualJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicingPeriod name="InvoicingPeriod">InvoicingPeriod</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicingPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryDiscountPosting name="PrimaryDiscountPosting">PrimaryDiscountPosting</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryDiscountPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryReceiptPosting name="PrimaryReceiptPosting">PrimaryReceiptPosting</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryReceiptPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaymentInvoicePostingProfile name="PrepaymentInvoicePostingProfile">PrepaymentInvoicePostingProfile</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentInvoicePostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutomaticSettlement name="IsAutomaticSettlement">IsAutomaticSettlement</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomaticSettlement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllocationKey name="AllocationKey">AllocationKey</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountAdministration name="CashDiscountAdministration">CashDiscountAdministration</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountAdministration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCashDiscountCalculatedForCreditNotes name="IsCashDiscountCalculatedForCreditNotes">IsCashDiscountCalculatedForCreditNotes</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCashDiscountCalculatedForCreditNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCashDiscountCalculatedForPartialPayments name="IsCashDiscountCalculatedForPartialPayments">IsCashDiscountCalculatedForPartialPayments</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCashDiscountCalculatedForPartialPayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCashDiscountCalculatedOnAmountIncludingSalesTax name="IsCashDiscountCalculatedOnAmountIncludingSalesTax">IsCashDiscountCalculatedOnAmountIncludingSalesTax</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCashDiscountCalculatedOnAmountIncludingSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCheckInvoiceNumberUsed name="IsCheckInvoiceNumberUsed">IsCheckInvoiceNumberUsed</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCheckInvoiceNumberUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckTheTaxInvoiceNumberUsed name="CheckTheTaxInvoiceNumberUsed">CheckTheTaxInvoiceNumberUsed</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckTheTaxInvoiceNumberUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNoteAsCorrection name="CreditNoteAsCorrection">CreditNoteAsCorrection</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteAsCorrection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditMaxCheck name="CreditMaxCheck">CreditMaxCheck</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditMaxCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSettlementTypeForCreditNotes name="DefaultSettlementTypeForCreditNotes">DefaultSettlementTypeForCreditNotes</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSettlementTypeForCreditNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVend name="DefaultVend">DefaultVend</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVend attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayPriceTotalMatchIcon name="DisplayPriceTotalMatchIcon">DisplayPriceTotalMatchIcon</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayPriceTotalMatchIcon attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayMiscChargeToleranceIcon name="DisplayMiscChargeToleranceIcon">DisplayMiscChargeToleranceIcon</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayMiscChargeToleranceIcon attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayPriceMatchIcon name="DisplayPriceMatchIcon">DisplayPriceMatchIcon</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayPriceMatchIcon attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayInvoiceTotalsMatchIcon name="DisplayInvoiceTotalsMatchIcon">DisplayInvoiceTotalsMatchIcon</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayInvoiceTotalsMatchIcon attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrintTransportationDetails name="IsPrintTransportationDetails">IsPrintTransportationDetails</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrintTransportationDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlePeriod name="SettlePeriod">SettlePeriod</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlePeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceTotalTolerance name="PurchasePriceTotalTolerance">PurchasePriceTotalTolerance</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceTotalTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceTotalTolerancePercent name="PurchasePriceTotalTolerancePercent">PurchasePriceTotalTolerancePercent</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceTotalTolerancePercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactureIssuePeriod name="FactureIssuePeriod">FactureIssuePeriod</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureIssuePeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPayment name="TermsOfPayment">TermsOfPayment</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeepSalesTaxAdjustmentsForPOInvoices name="KeepSalesTaxAdjustmentsForPOInvoices">KeepSalesTaxAdjustmentsForPOInvoices</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeepSalesTaxAdjustmentsForPOInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ID name="ID">ID</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

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

### <a href=#TaxExemptNumberRequirement name="TaxExemptNumberRequirement">TaxExemptNumberRequirement</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax Exempt Number Requirement (Invoice)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptNumberRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax Exempt Number Requirement (Invoice)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandatoryTaxGroup name="MandatoryTaxGroup">MandatoryTaxGroup</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandatoryVATNum name="MandatoryVATNum">MandatoryVATNum</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax Exempt Number Requirement (General)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax Exempt Number Requirement (General)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineMatchingPolicy name="LineMatchingPolicy">LineMatchingPolicy</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineMatchingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowMatchingPolicyOverride name="AllowMatchingPolicyOverride">AllowMatchingPolicyOverride</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMatchingPolicyOverride attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumPennyDifference name="MaximumPennyDifference">MaximumPennyDifference</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumPennyDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumOverpaymentOrUnderpayment name="MaximumOverpaymentOrUnderpayment">MaximumOverpaymentOrUnderpayment</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumOverpaymentOrUnderpayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DifferentialJournalName name="DifferentialJournalName">DifferentialJournalName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DifferentialJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseJournalName name="ExpenseJournalName">ExpenseJournalName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualPosting name="ManualPosting">ManualPosting</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategory name="ProcurementCategory">ProcurementCategory</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualAccount name="AccrualAccount">AccrualAccount</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyExpenseAccount name="RoyaltyExpenseAccount">RoyaltyExpenseAccount</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyExpenseAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartingDayOfWeek name="StartingDayOfWeek">StartingDayOfWeek</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartingDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargesTolerancePercentage name="ChargesTolerancePercentage">ChargesTolerancePercentage</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargesTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarnIfPaymentProposalUsesMultipleMethodsOfPayment name="WarnIfPaymentProposalUsesMultipleMethodsOfPayment">WarnIfPaymentProposalUsesMultipleMethodsOfPayment</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarnIfPaymentProposalUsesMultipleMethodsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationsOnPromissoryNotesJournals name="ValidationsOnPromissoryNotesJournals">ValidationsOnPromissoryNotesJournals</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationsOnPromissoryNotesJournals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponseToInvoicesThatFailValidation name="ResponseToInvoicesThatFailValidation">ResponseToInvoicesThatFailValidation</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponseToInvoicesThatFailValidation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostToChargeAccountInLedger name="PostToChargeAccountInLedger">PostToChargeAccountInLedger</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostToChargeAccountInLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceRemit name="InvoiceRemit">InvoiceRemit</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRemit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PromissoryNotes name="PromissoryNotes">PromissoryNotes</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromissoryNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemitPromissoryNote name="RemitPromissoryNote">RemitPromissoryNote</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemitPromissoryNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostInvoiceMatchDiscrepancies name="PostInvoiceMatchDiscrepancies">PostInvoiceMatchDiscrepancies</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostInvoiceMatchDiscrepancies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostProductReceiptInLedger name="PostProductReceiptInLedger">PostProductReceiptInLedger</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostProductReceiptInLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileForPaymentJournalWithPrepayment name="PostingProfileForPaymentJournalWithPrepayment">PostingProfileForPaymentJournalWithPrepayment</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileForPaymentJournalWithPrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryRelationTaxMatrix name="PrimaryRelationTaxMatrix">PrimaryRelationTaxMatrix</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryRelationTaxMatrix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructure name="AccountStructure">AccountStructure</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialDimension name="FinancialDimension">FinancialDimension</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsShowAmountDebitCredit name="IsShowAmountDebitCredit">IsShowAmountDebitCredit</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsShowAmountDebitCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxOnPrepaymentInPaymentJournal name="SalesTaxOnPrepaymentInPaymentJournal">SalesTaxOnPrepaymentInPaymentJournal</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxOnPrepaymentInPaymentJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceTotalsTolerancePercentage name="InvoiceTotalsTolerancePercentage">InvoiceTotalsTolerancePercentage</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTotalsTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseDocumentDate name="UseDocumentDate">UseDocumentDate</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update vendor accounting using the invoice date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update vendor accounting using the invoice date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchPriceTotals name="MatchPriceTotals">MatchPriceTotals</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchPriceTotals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableInvoiceMatchingValidation name="EnableInvoiceMatchingValidation">EnableInvoiceMatchingValidation</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableInvoiceMatchingValidation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMatchCharges name="IsMatchCharges">IsMatchCharges</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMatchCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMatchInvoiceTotals name="IsMatchInvoiceTotals">IsMatchInvoiceTotals</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMatchInvoiceTotals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountOffsetAccounts name="DiscountOffsetAccounts">DiscountOffsetAccounts</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountOffsetAccounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCodeForInvoiceGroups name="DefaultCodeForInvoiceGroups">DefaultCodeForInvoiceGroups</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCodeForInvoiceGroups attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireDocumentDateOnVendorInvoice name="RequireDocumentDateOnVendorInvoice">RequireDocumentDateOnVendorInvoice</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireDocumentDateOnVendorInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseInvoiceGroupsForThisCompany name="UseInvoiceGroupsForThisCompany">UseInvoiceGroupsForThisCompany</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseInvoiceGroupsForThisCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomCodeForInvoiceGroups name="CustomCodeForInvoiceGroups">CustomCodeForInvoiceGroups</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomCodeForInvoiceGroups attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateInvoicesInTheJournal name="ValidateInvoicesInTheJournal">ValidateInvoicesInTheJournal</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateInvoicesInTheJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomCodeForWebServiceInvoices name="CustomCodeForWebServiceInvoices">CustomCodeForWebServiceInvoices</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomCodeForWebServiceInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivateInvoicePaymentGroups name="ActivateInvoicePaymentGroups">ActivateInvoicePaymentGroups</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivateInvoicePaymentGroups attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeOfSalesTaxPosting name="TimeOfSalesTaxPosting">TimeOfSalesTaxPosting</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeOfSalesTaxPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsW9Validation name="IsW9Validation">IsW9Validation</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsW9Validation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrokerProcurementCategory name="BrokerProcurementCategory">BrokerProcurementCategory</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrokerProcurementCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticHeaderMatching name="AutomaticHeaderMatching">AutomaticHeaderMatching</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatically update invoice header status</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticHeaderMatching attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatically update invoice header status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category hierarchy</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category hierarchy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryName name="CategoryName">CategoryName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchyName name="CategoryHierarchyName">CategoryHierarchyName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

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

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Draft name="Draft">Draft</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Draft attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionHierarchyIsSystemGenerated name="DimensionHierarchyIsSystemGenerated">DimensionHierarchyIsSystemGenerated</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionHierarchyIsSystemGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionTreeName name="DimensionTreeName">DimensionTreeName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionTreeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionHierarchyType name="DimensionHierarchyType">DimensionHierarchyType</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionHierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchAgreementDimensionName name="PurchAgreementDimensionName">PurchAgreementDimensionName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAgreementDimensionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrokerCategoryHierarchy name="BrokerCategoryHierarchy">BrokerCategoryHierarchy</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrokerCategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrokerCategoryName name="BrokerCategoryName">BrokerCategoryName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Broker Category Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrokerCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Broker Category Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrokerCategoryHierarchyName name="BrokerCategoryHierarchyName">BrokerCategoryHierarchyName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Broker Category Hierarchy Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrokerCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Broker Category Hierarchy Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualAccountDisplayValue name="AccrualAccountDisplayValue">AccrualAccountDisplayValue</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accrual account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accrual account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyExpenseAccountDisplayValue name="RoyaltyExpenseAccountDisplayValue">RoyaltyExpenseAccountDisplayValue</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Royalty Expense Account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyExpenseAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Royalty Expense Account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseConsolidatedInvoice name="UseConsolidatedInvoice">UseConsolidatedInvoice</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseConsolidatedInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdCalculateCrossCompany name="TaxWithholdCalculateCrossCompany">TaxWithholdCalculateCrossCompany</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCalculateCrossCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdCompany name="TaxWithholdCompany">TaxWithholdCompany</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Include3wayMatching name="Include3wayMatching">Include3wayMatching</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Include3wayMatching attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SplitDeliveryInvoice name="SplitDeliveryInvoice">SplitDeliveryInvoice</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitDeliveryInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SplitDeliveryPackingSlip name="SplitDeliveryPackingSlip">SplitDeliveryPackingSlip</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitDeliveryPackingSlip attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceJoiningPreventionOnPromissoryNoteJournals name="InvoiceJoiningPreventionOnPromissoryNoteJournals">InvoiceJoiningPreventionOnPromissoryNoteJournals</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceJoiningPreventionOnPromissoryNoteJournals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateTreatmentOnPromissoryNoteJournals name="DateTreatmentOnPromissoryNoteJournals">DateTreatmentOnPromissoryNoteJournals</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateTreatmentOnPromissoryNoteJournals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseFiscalDataFromInvoiceAccount name="UseFiscalDataFromInvoiceAccount">UseFiscalDataFromInvoiceAccount</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFiscalDataFromInvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchPrepayApplicationPolicy name="PurchPrepayApplicationPolicy">PurchPrepayApplicationPolicy</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchPrepayApplicationPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowTimeBetweenDeliveryDateAndInvoiceDate name="CashFlowTimeBetweenDeliveryDateAndInvoiceDate">CashFlowTimeBetweenDeliveryDateAndInvoiceDate</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowTimeBetweenDeliveryDateAndInvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowTermsOfPayment name="CashFlowTermsOfPayment">CashFlowTermsOfPayment</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowTermsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowTimeBetweenInvoiceDueDateAndPaymentDate name="CashFlowTimeBetweenInvoiceDueDateAndPaymentDate">CashFlowTimeBetweenInvoiceDueDateAndPaymentDate</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowTimeBetweenInvoiceDueDateAndPaymentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowLiquidityAccountForPayments name="CashFlowLiquidityAccountForPayments">CashFlowLiquidityAccountForPayments</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowLiquidityAccountForPayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowLiquidityAccountForPaymentsDisplayValue name="CashFlowLiquidityAccountForPaymentsDisplayValue">CashFlowLiquidityAccountForPaymentsDisplayValue</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowLiquidityAccountForPaymentsDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowPercentageOfAmountToAllocateToCashFlowForecast name="CashFlowPercentageOfAmountToAllocateToCashFlowForecast">CashFlowPercentageOfAmountToAllocateToCashFlowForecast</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowPercentageOfAmountToAllocateToCashFlowForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EditCashDiscountsWhenDueDateChanged name="EditCashDiscountsWhenDueDateChanged">EditCashDiscountsWhenDueDateChanged</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EditCashDiscountsWhenDueDateChanged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFilterForVendorTransactions name="DefaultFilterForVendorTransactions">DefaultFilterForVendorTransactions</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFilterForVendorTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementWriteOffEnabled name="SettlementWriteOffEnabled">SettlementWriteOffEnabled</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementWriteOffEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementWriteOffJournalName name="SettlementWriteOffJournalName">SettlementWriteOffJournalName</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementWriteOffJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementWriteOffReasonCode name="SettlementWriteOffReasonCode">SettlementWriteOffReasonCode</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementWriteOffReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeProposalIsEnabled name="ChangeProposalIsEnabled">ChangeProposalIsEnabled</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeProposalIsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeProposalDataEntityBehavior name="ChangeProposalDataEntityBehavior">ChangeProposalDataEntityBehavior</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeProposalDataEntityBehavior attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendInvoiceInUseRecoverEnable name="VendInvoiceInUseRecoverEnable">VendInvoiceInUseRecoverEnable</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceInUseRecoverEnable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BypassValidationOfAccountingDistributions name="BypassValidationOfAccountingDistributions">BypassValidationOfAccountingDistributions</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BypassValidationOfAccountingDistributions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxInvoicesPerBatch name="MaxInvoicesPerBatch">MaxInvoicesPerBatch</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxInvoicesPerBatch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxWaitTimeForInvoiceScheduledStatus_Hours name="MaxWaitTimeForInvoiceScheduledStatus_Hours">MaxWaitTimeForInvoiceScheduledStatus_Hours</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxWaitTimeForInvoiceScheduledStatus_Hours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PollingInterval_Minutes name="PollingInterval_Minutes">PollingInterval_Minutes</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PollingInterval_Minutes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversePrepayment name="ReversePrepayment">ReversePrepayment</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversePrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlePrepaymentVATType name="SettlePrepaymentVATType">SettlePrepaymentVATType</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlePrepaymentVATType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceHoldersPostingProfile name="AdvanceHoldersPostingProfile">AdvanceHoldersPostingProfile</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceHoldersPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceHoldersAutoSettle name="AdvanceHoldersAutoSettle">AdvanceHoldersAutoSettle</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceHoldersAutoSettle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceHoldersSettlementByDimension name="AdvanceHoldersSettlementByDimension">AdvanceHoldersSettlementByDimension</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceHoldersSettlementByDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisablePaymentIDValidation name="DisablePaymentIDValidation">DisablePaymentIDValidation</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisablePaymentIDValidation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImportFormatMappingNameQRBill name="ImportFormatMappingNameQRBill">ImportFormatMappingNameQRBill</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>QR-Bill</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImportFormatMappingNameQRBill attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>QR-Bill</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNActivatePurchasingCard name="PSNActivatePurchasingCard">PSNActivatePurchasingCard</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activate purchasing cards</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNActivatePurchasingCard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activate purchasing cards</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNPostingDefinitionRecId name="PSNPostingDefinitionRecId">PSNPostingDefinitionRecId</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNPostingDefinitionRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNPostingDefinitionCode name="PSNPostingDefinitionCode">PSNPostingDefinitionCode</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNPostingDefinitionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccrualAccountCombinationRelationshipId name="Relationship_AccrualAccountCombinationRelationshipId">Relationship_AccrualAccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccrualAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RoyaltyExpenseAccountCombinationRelationshipId name="Relationship_RoyaltyExpenseAccountCombinationRelationshipId">Relationship_RoyaltyExpenseAccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RoyaltyExpenseAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_VendParametersRelationshipId name="BackingTable_VendParametersRelationshipId">BackingTable_VendParametersRelationshipId</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsPayable/Parameter/VendParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Parameter/VendParameters.cdm.json/VendParameters</a></td><td><a href="../../../Tables/Finance/AccountsPayable/Parameter/VendParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendVendorParametersEntity (this entity)  

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
