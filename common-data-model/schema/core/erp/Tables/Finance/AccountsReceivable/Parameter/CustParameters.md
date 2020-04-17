---
title: CustParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# CustParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/AccountsReceivable/Parameter/CustParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PostingProfile](#PostingProfile)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[InvoicePeriod](#InvoicePeriod)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TaxGroup_RU](#TaxGroup_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TaxItemGroup_RU](#TaxItemGroup_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AccountConsumption](#AccountConsumption)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AccountDisc](#AccountDisc)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AccountPositions](#AccountPositions)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AccountRevenue](#AccountRevenue)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdjustmentDateToUse](#AdjustmentDateToUse)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdvanceInvoiceCreditCorrection_W](#AdvanceInvoiceCreditCorrection_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdvanceInvoiceOffsetLedgerDimension_W](#AdvanceInvoiceOffsetLedgerDimension_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdvanceInvoicePostingProfile_W](#AdvanceInvoicePostingProfile_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdvanceInvoiceReversalCorrection_W](#AdvanceInvoiceReversalCorrection_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdvanceInvoiceTaxGroup_W](#AdvanceInvoiceTaxGroup_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdvanceInvoiceTaxItemGroup_W](#AdvanceInvoiceTaxItemGroup_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdvInvAmount_W](#AdvInvAmount_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AdvInvDate_W](#AdvInvDate_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AgreementCreditLine_RU](#AgreementCreditLine_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AutomaticTotalDiscount](#AutomaticTotalDiscount)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AutoSettle](#AutoSettle)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[B2BSchemeBankSubmissionDaysFirst](#B2BSchemeBankSubmissionDaysFirst)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[B2BSchemeBankSubmissionDaysRecurring](#B2BSchemeBankSubmissionDaysRecurring)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[BankCustPaymIdTable](#BankCustPaymIdTable)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[BillsJournalsValidations](#BillsJournalsValidations)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[BudgetSettle](#BudgetSettle)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CancelPaymentReasonReq](#CancelPaymentReasonReq)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CashDisc](#CashDisc)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CashDiscForCreditNote](#CashDiscForCreditNote)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CashDiscForPartialPaym](#CashDiscForPartialPaym)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CashDiscVAT](#CashDiscVAT)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CheckInvoice_W](#CheckInvoice_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[ClearingLedgerDimension](#ClearingLedgerDimension)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionAgencyTaxRate_W](#CollectionAgencyTaxRate_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionGracePeriodForDuesTransfer_W](#CollectionGracePeriodForDuesTransfer_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionLetterCodeUpdate](#CollectionLetterCodeUpdate)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionLetterIgnoreCreditTransactionCodes](#CollectionLetterIgnoreCreditTransactionCodes)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionLetterGenerationLevel](#CollectionLetterGenerationLevel)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsExcludeDisputedTransactions](#CollectionsExcludeDisputedTransactions)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsGeneralSysEmailId](#CollectionsGeneralSysEmailId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsOMTeam](#CollectionsOMTeam)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsSalespersonSysEmailId](#CollectionsSalespersonSysEmailId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsStatementSysEmailId](#CollectionsStatementSysEmailId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsStatRepInterval](#CollectionsStatRepInterval)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsWriteOffLedgerJournalName](#CollectionsWriteOffLedgerJournalName)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsWriteOffReasonTable](#CollectionsWriteOffReasonTable)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CollectionsWriteOffSeparateSalesTax](#CollectionsWriteOffSeparateSalesTax)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CopyInvoiceDimension_RU](#CopyInvoiceDimension_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Cor1SchemeBankSubmissionDaysFirst](#Cor1SchemeBankSubmissionDaysFirst)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Cor1SchemeBankSubmissionDaysRecurring](#Cor1SchemeBankSubmissionDaysRecurring)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CoreSchemeBankSubmissionDaysFirst](#CoreSchemeBankSubmissionDaysFirst)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CoreSchemeBankSubmissionDaysRecurring](#CoreSchemeBankSubmissionDaysRecurring)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardCostCenterDimensionAttribute](#CreditCardCostCenterDimensionAttribute)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardEstShippingChargeMax](#CreditCardEstShippingChargeMax)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardEstShippingChargeType](#CreditCardEstShippingChargeType)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardEstShippingChargeValue](#CreditCardEstShippingChargeValue)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardNotes](#CreditCardNotes)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardPostingAccountType](#CreditCardPostingAccountType)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardPostingBankTransactionType](#CreditCardPostingBankTransactionType)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardPostingLedgerDimension](#CreditCardPostingLedgerDimension)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardPreapprovalLastNoOfDays](#CreditCardPreapprovalLastNoOfDays)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditCardPreAuthorization](#CreditCardPreAuthorization)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditError](#CreditError)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditInvoicingReport](#CreditInvoicingReport)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditLimitCheckFreeInvoice](#CreditLimitCheckFreeInvoice)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditLimitCheckSales](#CreditLimitCheckSales)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditLineError](#CreditLineError)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditMaxCheck](#CreditMaxCheck)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditNoteCashDiscount_CZ](#CreditNoteCashDiscount_CZ)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CreditNoteReasonReq](#CreditNoteReasonReq)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustConsInvoice_JP](#CustConsInvoice_JP)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustInterestCalc](#CustInterestCalc)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustInvoiceRefNum_FI](#CustInvoiceRefNum_FI)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustNameFromVATNum](#CustNameFromVATNum)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustTaxation_RU](#CustTaxation_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustUseBillingClassification_PSN](#CustUseBillingClassification_PSN)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[DefaultCust](#DefaultCust)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[DimSettlementCtrlType_RU](#DimSettlementCtrlType_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[DoPrintTransportationDocument](#DoPrintTransportationDocument)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Due2Payment](#Due2Payment)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[DueToTransDate](#DueToTransDate)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableDateOfVATRegisterChanging_CZ](#EnableDateOfVATRegisterChanging_CZ)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableProject](#EnableProject)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableReferToCollectionAgency_W](#EnableReferToCollectionAgency_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EntryCertificateIssuingEnabled_W](#EntryCertificateIssuingEnabled_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EntryCertificateManagementEnabled_W](#EntryCertificateManagementEnabled_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Invoice2Due](#Invoice2Due)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[InvoiceIdEditing_W](#InvoiceIdEditing_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[InvoiceLinePriority](#InvoiceLinePriority)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[InvoiceReferenceNumberFormula_FI](#InvoiceReferenceNumberFormula_FI)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[InvoiceReferenceNumberSequenceTable](#InvoiceReferenceNumberSequenceTable)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[ItemDimAdjustLineControl_RU](#ItemDimAdjustLineControl_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Key](#Key)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MandateDefaultExpirationMonths](#MandateDefaultExpirationMonths)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MandatoryInvoiceVATNum](#MandatoryInvoiceVATNum)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MandatoryItemTaxGroup](#MandatoryItemTaxGroup)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MandatoryTaxGroup](#MandatoryTaxGroup)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MandatoryVATNum](#MandatoryVATNum)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MarkOpenInvoiceLine](#MarkOpenInvoiceLine)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MatchedPackingSlipsInquiry](#MatchedPackingSlipsInquiry)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MaximumWaiveDays](#MaximumWaiveDays)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MaxMSTDiff](#MaxMSTDiff)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MaxMSTOverUnder](#MaxMSTOverUnder)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MCRDefaultDimensionHierarchy](#MCRDefaultDimensionHierarchy)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MinimumWaiveDays](#MinimumWaiveDays)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MinRefund](#MinRefund)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MixedPayment](#MixedPayment)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PackagingWeightOnInvoice](#PackagingWeightOnInvoice)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PKWiUCodeRequirement](#PKWiUCodeRequirement)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PostingProfileBills](#PostingProfileBills)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PostingProfileBillsEndorsed](#PostingProfileBillsEndorsed)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PostingProfileBillsProtested](#PostingProfileBillsProtested)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PostingProfileBillsRemitCollection](#PostingProfileBillsRemitCollection)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PostingProfileBillsRemitDiscount](#PostingProfileBillsRemitDiscount)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PrenotificationDaysFirst](#PrenotificationDaysFirst)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PrenotificationDaysRecurring](#PrenotificationDaysRecurring)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PrepaymentDate_W](#PrepaymentDate_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PrepaymentFactureAutoCreate_RU](#PrepaymentFactureAutoCreate_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PrepaymentHandlingLayout_W](#PrepaymentHandlingLayout_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PrepaymentLink_W](#PrepaymentLink_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PrepaymentPostingProfile](#PrepaymentPostingProfile)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[PrimaryRelation_BR](#PrimaryRelation_BR)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[ProjLedgerAllowEdit](#ProjLedgerAllowEdit)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[ProrationType](#ProrationType)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[ReasonCodeCashDiscount_CZ](#ReasonCodeCashDiscount_CZ)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[ReturnOrdersReasonReq](#ReturnOrdersReasonReq)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[ReversePrepayment_W](#ReversePrepayment_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[RTax25BadDebtReserveLedgerDimension](#RTax25BadDebtReserveLedgerDimension)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[RTax25ProfitTable](#RTax25ProfitTable)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[RTax25ReceiptPct](#RTax25ReceiptPct)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[RTax25UnrealisedExpenseLedgerDimension](#RTax25UnrealisedExpenseLedgerDimension)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SalesBookFactureProcessingType_RU](#SalesBookFactureProcessingType_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SalesCycle](#SalesCycle)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SettlePrepaymentVATType_RU](#SettlePrepaymentVATType_RU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[ShowAmountDebitCredit_JP](#ShowAmountDebitCredit_JP)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SpanBillingCodeAcrossInvoices](#SpanBillingCodeAcrossInvoices)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TAMDeductionRequireFullSettle](#TAMDeductionRequireFullSettle)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TAMDeductionType](#TAMDeductionType)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TAMRebatePosting](#TAMRebatePosting)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TaxIntegrationSystem_CN](#TaxIntegrationSystem_CN)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TaxOnPrepayment](#TaxOnPrepayment)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TaxPeriodPaymentCode_PL](#TaxPeriodPaymentCode_PL)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TaxReimbursementExchangeRateType_HU](#TaxReimbursementExchangeRateType_HU)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[TransReversalReasonReq](#TransReversalReasonReq)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[UseFiscalInvoiceAccount](#UseFiscalInvoiceAccount)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[UsePriorityOnAutoSettlement](#UsePriorityOnAutoSettlement)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[UseSettlementPriority](#UseSettlementPriority)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[MCREnablePriceDetails](#MCREnablePriceDetails)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[FreeTextInvoiceTimezonePreference](#FreeTextInvoiceTimezonePreference)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableCancelPostingProfiles](#EnableCancelPostingProfiles)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableReturnPostingProfiles](#EnableReturnPostingProfiles)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableChronologicalInvoiceNumbering_W](#EnableChronologicalInvoiceNumbering_W)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustAgingSnapshotBatchLimit](#CustAgingSnapshotBatchLimit)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableSubstitutionInvoices_TH](#EnableSubstitutionInvoices_TH)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableSubstitutionProjectInvoices_TH](#EnableSubstitutionProjectInvoices_TH)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustTableChangeProposalIsEnabled](#CustTableChangeProposalIsEnabled)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustTableChangeProposalDataEntityBehavior](#CustTableChangeProposalDataEntityBehavior)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EditCashDiscountsWhenDueDateChanged](#EditCashDiscountsWhenDueDateChanged)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[DefaultFilterForCustomerTransactions](#DefaultFilterForCustomerTransactions)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SalesBookFormatMappingID](#SalesBookFormatMappingID)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SalesBookAdditionalListFormatMappingID](#SalesBookAdditionalListFormatMappingID)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SettlementWriteOffEnabled](#SettlementWriteOffEnabled)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SettlementWriteOffLedgerDimension](#SettlementWriteOffLedgerDimension)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SettlementWriteOffReasonCode](#SettlementWriteOffReasonCode)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SettlementWriteOffJournalName](#SettlementWriteOffJournalName)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[RTax25DebtModel](#RTax25DebtModel)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[RTax25DebtModelTax](#RTax25DebtModelTax)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[EnableSingleLineTaxAdjustment](#EnableSingleLineTaxAdjustment)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[BypassValidationOfAccountingDistributions](#BypassValidationOfAccountingDistributions)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[SuppressDepreciationOfPaymentSection](#SuppressDepreciationOfPaymentSection)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CheckForOverlapsAndGaps](#CheckForOverlapsAndGaps)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[UsualExporterExemptionTaxGroup_IT](#UsualExporterExemptionTaxGroup_IT)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[AutomaticIntentLetterAssignment_IT](#AutomaticIntentLetterAssignment_IT)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CommissionType_IT](#CommissionType_IT)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[CustCollectionManagerEnablePerfImprove](#CustCollectionManagerEnablePerfImprove)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_AdvanceInvoiceOffsetLedgerDimension_WRelationshipId](#Relationship_AdvanceInvoiceOffsetLedgerDimension_WRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_AdvanceInvoicePostingProfile_WRelationshipId](#Relationship_AdvanceInvoicePostingProfile_WRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_AdvanceInvoiceTaxGroup_WRelationshipId](#Relationship_AdvanceInvoiceTaxGroup_WRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_AdvanceInvoiceTaxItemGroup_WRelationshipId](#Relationship_AdvanceInvoiceTaxItemGroup_WRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_BankCustPaymIdTableRelationshipId](#Relationship_BankCustPaymIdTableRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_BankTransTypeRelationshipId](#Relationship_BankTransTypeRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_ClearingLedgerDimensionRelationshipId](#Relationship_ClearingLedgerDimensionRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CollectionsOMTeamRelationshipId](#Relationship_CollectionsOMTeamRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CreditCardCostCenterDimensionAttributeRelationshipId](#Relationship_CreditCardCostCenterDimensionAttributeRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CreditCardPostingLedgerDimensionRelationshipId](#Relationship_CreditCardPostingLedgerDimensionRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CustLedger_PostingProfileRelationshipId](#Relationship_CustLedger_PostingProfileRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CustLedger_PostingProfileBillsRelationshipId](#Relationship_CustLedger_PostingProfileBillsRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CustLedger_PostingProfileBillsEndorsedRelationshipId](#Relationship_CustLedger_PostingProfileBillsEndorsedRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CustLedger_PostingProfileBillsProtestedRelationshipId](#Relationship_CustLedger_PostingProfileBillsProtestedRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CustLedger_PostingProfileBillsRemitDisRelationshipId](#Relationship_CustLedger_PostingProfileBillsRemitDisRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CustLedger_PostingProfileBillsRemotCollRelationshipId](#Relationship_CustLedger_PostingProfileBillsRemotCollRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CustLedger_PrepaymentPostingProfileRelationshipId](#Relationship_CustLedger_PrepaymentPostingProfileRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_ExchangeRateTypeRelationshipId](#Relationship_ExchangeRateTypeRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_InvoiceReferenceNumberSequenceTableRelationshipId](#Relationship_InvoiceReferenceNumberSequenceTableRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_LedgerAllocateKeyRelationshipId](#Relationship_LedgerAllocateKeyRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_LedgerJournalNameRelationshipId](#Relationship_LedgerJournalNameRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_PaymTerm_Due2PaymentRelationshipId](#Relationship_PaymTerm_Due2PaymentRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_PaymTerm_INvoice2DueRelationshipId](#Relationship_PaymTerm_INvoice2DueRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_PaymTerm_InvoicePeriodRelationshipId](#Relationship_PaymTerm_InvoicePeriodRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_PlTaxDueTableRelationshipId](#Relationship_PlTaxDueTableRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_ReasonCodeCashDiscount_CZRelationshipId](#Relationship_ReasonCodeCashDiscount_CZRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_ReasonTableRelationshipId](#Relationship_ReasonTableRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_RTax25BadDebtReserveLedgerDimensionRelationshipId](#Relationship_RTax25BadDebtReserveLedgerDimensionRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_RTax25ProfitTableRelationshipId](#Relationship_RTax25ProfitTableRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_RTax25UnrealisedExpenseLedgerDimensionRelationshipId](#Relationship_RTax25UnrealisedExpenseLedgerDimensionRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_StatRepIntervalRelationshipId](#Relationship_StatRepIntervalRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_SysEmailTable_CollGenSysEmailIdRelationshipId](#Relationship_SysEmailTable_CollGenSysEmailIdRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_SysEmailTable_CollSalespersonsSysEmailIdRelationshipId](#Relationship_SysEmailTable_CollSalespersonsSysEmailIdRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_SysEmailTable_CollStatementSysEmailIdRelationshipId](#Relationship_SysEmailTable_CollStatementSysEmailIdRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_TaxGroup_RURelationshipId](#Relationship_TaxGroup_RURelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_TaxItemGroup_RURelationshipId](#Relationship_TaxItemGroup_RURelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_SettlementWriteOffLedgerDimRelationshipId](#Relationship_SettlementWriteOffLedgerDimRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_SettlementWriteOffReasonRelationshipId](#Relationship_SettlementWriteOffReasonRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_SettlementWriteOffJournalNameRelationshipId](#Relationship_SettlementWriteOffJournalNameRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_RTax25DebtModelRelationshipId](#Relationship_RTax25DebtModelRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_RTax25DebtModelTaxRelationshipId](#Relationship_RTax25DebtModelTaxRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_TaxGroupHeading_UsualExporterTaxGroup_ITRelationshipId](#Relationship_TaxGroupHeading_UsualExporterTaxGroup_ITRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustParameters.md" target="_blank">Parameter/CustParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicePeriod name="InvoicePeriod">InvoicePeriod</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicePeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup_RU name="TaxGroup_RU">TaxGroup_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup_RU name="TaxItemGroup_RU">TaxItemGroup_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountConsumption name="AccountConsumption">AccountConsumption</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountConsumption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AccountDisc name="AccountDisc">AccountDisc</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AccountPositions name="AccountPositions">AccountPositions</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountPositions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AccountRevenue name="AccountRevenue">AccountRevenue</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRevenue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdjustmentDateToUse name="AdjustmentDateToUse">AdjustmentDateToUse</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentDateToUse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdvanceInvoiceCreditCorrection_W name="AdvanceInvoiceCreditCorrection_W">AdvanceInvoiceCreditCorrection_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceInvoiceCreditCorrection_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdvanceInvoiceOffsetLedgerDimension_W name="AdvanceInvoiceOffsetLedgerDimension_W">AdvanceInvoiceOffsetLedgerDimension_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceInvoiceOffsetLedgerDimension_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdvanceInvoicePostingProfile_W name="AdvanceInvoicePostingProfile_W">AdvanceInvoicePostingProfile_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceInvoicePostingProfile_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceInvoiceReversalCorrection_W name="AdvanceInvoiceReversalCorrection_W">AdvanceInvoiceReversalCorrection_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceInvoiceReversalCorrection_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdvanceInvoiceTaxGroup_W name="AdvanceInvoiceTaxGroup_W">AdvanceInvoiceTaxGroup_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceInvoiceTaxGroup_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceInvoiceTaxItemGroup_W name="AdvanceInvoiceTaxItemGroup_W">AdvanceInvoiceTaxItemGroup_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceInvoiceTaxItemGroup_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvInvAmount_W name="AdvInvAmount_W">AdvInvAmount_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvInvAmount_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdvInvDate_W name="AdvInvDate_W">AdvInvDate_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvInvDate_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AgreementCreditLine_RU name="AgreementCreditLine_RU">AgreementCreditLine_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementCreditLine_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AutomaticTotalDiscount name="AutomaticTotalDiscount">AutomaticTotalDiscount</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticTotalDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AutoSettle name="AutoSettle">AutoSettle</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoSettle attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#B2BSchemeBankSubmissionDaysFirst name="B2BSchemeBankSubmissionDaysFirst">B2BSchemeBankSubmissionDaysFirst</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the B2BSchemeBankSubmissionDaysFirst attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#B2BSchemeBankSubmissionDaysRecurring name="B2BSchemeBankSubmissionDaysRecurring">B2BSchemeBankSubmissionDaysRecurring</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the B2BSchemeBankSubmissionDaysRecurring attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankCustPaymIdTable name="BankCustPaymIdTable">BankCustPaymIdTable</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCustPaymIdTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BillsJournalsValidations name="BillsJournalsValidations">BillsJournalsValidations</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillsJournalsValidations attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetSettle name="BudgetSettle">BudgetSettle</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetSettle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancelPaymentReasonReq name="CancelPaymentReasonReq">CancelPaymentReasonReq</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelPaymentReasonReq attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDisc name="CashDisc">CashDisc</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDiscForCreditNote name="CashDiscForCreditNote">CashDiscForCreditNote</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscForCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDiscForPartialPaym name="CashDiscForPartialPaym">CashDiscForPartialPaym</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscForPartialPaym attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDiscVAT name="CashDiscVAT">CashDiscVAT</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscVAT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckInvoice_W name="CheckInvoice_W">CheckInvoice_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckInvoice_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClearingLedgerDimension name="ClearingLedgerDimension">ClearingLedgerDimension</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClearingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CollectionAgencyTaxRate_W name="CollectionAgencyTaxRate_W">CollectionAgencyTaxRate_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionAgencyTaxRate_W attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CollectionGracePeriodForDuesTransfer_W name="CollectionGracePeriodForDuesTransfer_W">CollectionGracePeriodForDuesTransfer_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionGracePeriodForDuesTransfer_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CollectionLetterCodeUpdate name="CollectionLetterCodeUpdate">CollectionLetterCodeUpdate</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterCodeUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CollectionLetterIgnoreCreditTransactionCodes name="CollectionLetterIgnoreCreditTransactionCodes">CollectionLetterIgnoreCreditTransactionCodes</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterIgnoreCreditTransactionCodes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CollectionLetterGenerationLevel name="CollectionLetterGenerationLevel">CollectionLetterGenerationLevel</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterGenerationLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CollectionsExcludeDisputedTransactions name="CollectionsExcludeDisputedTransactions">CollectionsExcludeDisputedTransactions</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsExcludeDisputedTransactions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CollectionsGeneralSysEmailId name="CollectionsGeneralSysEmailId">CollectionsGeneralSysEmailId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsGeneralSysEmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsOMTeam name="CollectionsOMTeam">CollectionsOMTeam</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsOMTeam attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CollectionsSalespersonSysEmailId name="CollectionsSalespersonSysEmailId">CollectionsSalespersonSysEmailId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsSalespersonSysEmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsStatementSysEmailId name="CollectionsStatementSysEmailId">CollectionsStatementSysEmailId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsStatementSysEmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsStatRepInterval name="CollectionsStatRepInterval">CollectionsStatRepInterval</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsStatRepInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsWriteOffLedgerJournalName name="CollectionsWriteOffLedgerJournalName">CollectionsWriteOffLedgerJournalName</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsWriteOffLedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsWriteOffReasonTable name="CollectionsWriteOffReasonTable">CollectionsWriteOffReasonTable</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsWriteOffReasonTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsWriteOffSeparateSalesTax name="CollectionsWriteOffSeparateSalesTax">CollectionsWriteOffSeparateSalesTax</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsWriteOffSeparateSalesTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CopyInvoiceDimension_RU name="CopyInvoiceDimension_RU">CopyInvoiceDimension_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopyInvoiceDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Cor1SchemeBankSubmissionDaysFirst name="Cor1SchemeBankSubmissionDaysFirst">Cor1SchemeBankSubmissionDaysFirst</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Cor1SchemeBankSubmissionDaysFirst attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Cor1SchemeBankSubmissionDaysRecurring name="Cor1SchemeBankSubmissionDaysRecurring">Cor1SchemeBankSubmissionDaysRecurring</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Cor1SchemeBankSubmissionDaysRecurring attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CoreSchemeBankSubmissionDaysFirst name="CoreSchemeBankSubmissionDaysFirst">CoreSchemeBankSubmissionDaysFirst</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoreSchemeBankSubmissionDaysFirst attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CoreSchemeBankSubmissionDaysRecurring name="CoreSchemeBankSubmissionDaysRecurring">CoreSchemeBankSubmissionDaysRecurring</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoreSchemeBankSubmissionDaysRecurring attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditCardCostCenterDimensionAttribute name="CreditCardCostCenterDimensionAttribute">CreditCardCostCenterDimensionAttribute</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardCostCenterDimensionAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CreditCardEstShippingChargeMax name="CreditCardEstShippingChargeMax">CreditCardEstShippingChargeMax</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardEstShippingChargeMax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CreditCardEstShippingChargeType name="CreditCardEstShippingChargeType">CreditCardEstShippingChargeType</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardEstShippingChargeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditCardEstShippingChargeValue name="CreditCardEstShippingChargeValue">CreditCardEstShippingChargeValue</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardEstShippingChargeValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CreditCardNotes name="CreditCardNotes">CreditCardNotes</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardPostingAccountType name="CreditCardPostingAccountType">CreditCardPostingAccountType</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPostingAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditCardPostingBankTransactionType name="CreditCardPostingBankTransactionType">CreditCardPostingBankTransactionType</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPostingBankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardPostingLedgerDimension name="CreditCardPostingLedgerDimension">CreditCardPostingLedgerDimension</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPostingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CreditCardPreapprovalLastNoOfDays name="CreditCardPreapprovalLastNoOfDays">CreditCardPreapprovalLastNoOfDays</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPreapprovalLastNoOfDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditCardPreAuthorization name="CreditCardPreAuthorization">CreditCardPreAuthorization</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPreAuthorization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditError name="CreditError">CreditError</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditInvoicingReport name="CreditInvoicingReport">CreditInvoicingReport</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditInvoicingReport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditLimitCheckFreeInvoice name="CreditLimitCheckFreeInvoice">CreditLimitCheckFreeInvoice</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitCheckFreeInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditLimitCheckSales name="CreditLimitCheckSales">CreditLimitCheckSales</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitCheckSales attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditLineError name="CreditLineError">CreditLineError</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLineError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditMaxCheck name="CreditMaxCheck">CreditMaxCheck</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditMaxCheck attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditNoteCashDiscount_CZ name="CreditNoteCashDiscount_CZ">CreditNoteCashDiscount_CZ</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteCashDiscount_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditNoteReasonReq name="CreditNoteReasonReq">CreditNoteReasonReq</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteReasonReq attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustConsInvoice_JP name="CustConsInvoice_JP">CustConsInvoice_JP</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustConsInvoice_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustInterestCalc name="CustInterestCalc">CustInterestCalc</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInterestCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustInvoiceRefNum_FI name="CustInvoiceRefNum_FI">CustInvoiceRefNum_FI</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceRefNum_FI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustNameFromVATNum name="CustNameFromVATNum">CustNameFromVATNum</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustNameFromVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustTaxation_RU name="CustTaxation_RU">CustTaxation_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTaxation_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustUseBillingClassification_PSN name="CustUseBillingClassification_PSN">CustUseBillingClassification_PSN</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustUseBillingClassification_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultCust name="DefaultCust">DefaultCust</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCust attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimSettlementCtrlType_RU name="DimSettlementCtrlType_RU">DimSettlementCtrlType_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimSettlementCtrlType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DoPrintTransportationDocument name="DoPrintTransportationDocument">DoPrintTransportationDocument</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoPrintTransportationDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Due2Payment name="Due2Payment">Due2Payment</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Due2Payment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueToTransDate name="DueToTransDate">DueToTransDate</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueToTransDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableDateOfVATRegisterChanging_CZ name="EnableDateOfVATRegisterChanging_CZ">EnableDateOfVATRegisterChanging_CZ</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableDateOfVATRegisterChanging_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableProject name="EnableProject">EnableProject</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableProject attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableReferToCollectionAgency_W name="EnableReferToCollectionAgency_W">EnableReferToCollectionAgency_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableReferToCollectionAgency_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EntryCertificateIssuingEnabled_W name="EntryCertificateIssuingEnabled_W">EntryCertificateIssuingEnabled_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryCertificateIssuingEnabled_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EntryCertificateManagementEnabled_W name="EntryCertificateManagementEnabled_W">EntryCertificateManagementEnabled_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryCertificateManagementEnabled_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Invoice2Due name="Invoice2Due">Invoice2Due</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice2Due attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceIdEditing_W name="InvoiceIdEditing_W">InvoiceIdEditing_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceIdEditing_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceLinePriority name="InvoiceLinePriority">InvoiceLinePriority</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceLinePriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceReferenceNumberFormula_FI name="InvoiceReferenceNumberFormula_FI">InvoiceReferenceNumberFormula_FI</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceReferenceNumberFormula_FI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceReferenceNumberSequenceTable name="InvoiceReferenceNumberSequenceTable">InvoiceReferenceNumberSequenceTable</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceReferenceNumberSequenceTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ItemDimAdjustLineControl_RU name="ItemDimAdjustLineControl_RU">ItemDimAdjustLineControl_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemDimAdjustLineControl_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#MandateDefaultExpirationMonths name="MandateDefaultExpirationMonths">MandateDefaultExpirationMonths</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateDefaultExpirationMonths attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MandatoryInvoiceVATNum name="MandatoryInvoiceVATNum">MandatoryInvoiceVATNum</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryInvoiceVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MandatoryItemTaxGroup name="MandatoryItemTaxGroup">MandatoryItemTaxGroup</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryItemTaxGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MandatoryTaxGroup name="MandatoryTaxGroup">MandatoryTaxGroup</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryTaxGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MandatoryVATNum name="MandatoryVATNum">MandatoryVATNum</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MarkOpenInvoiceLine name="MarkOpenInvoiceLine">MarkOpenInvoiceLine</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkOpenInvoiceLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MatchedPackingSlipsInquiry name="MatchedPackingSlipsInquiry">MatchedPackingSlipsInquiry</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchedPackingSlipsInquiry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaximumWaiveDays name="MaximumWaiveDays">MaximumWaiveDays</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWaiveDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxMSTDiff name="MaxMSTDiff">MaxMSTDiff</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxMSTDiff attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaxMSTOverUnder name="MaxMSTOverUnder">MaxMSTOverUnder</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxMSTOverUnder attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MCRDefaultDimensionHierarchy name="MCRDefaultDimensionHierarchy">MCRDefaultDimensionHierarchy</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRDefaultDimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MinimumWaiveDays name="MinimumWaiveDays">MinimumWaiveDays</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumWaiveDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MinRefund name="MinRefund">MinRefund</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinRefund attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MixedPayment name="MixedPayment">MixedPayment</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixedPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PackagingWeightOnInvoice name="PackagingWeightOnInvoice">PackagingWeightOnInvoice</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackagingWeightOnInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PKWiUCodeRequirement name="PKWiUCodeRequirement">PKWiUCodeRequirement</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PKWiUCodeRequirement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostingProfileBills name="PostingProfileBills">PostingProfileBills</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBills attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileBillsEndorsed name="PostingProfileBillsEndorsed">PostingProfileBillsEndorsed</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBillsEndorsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileBillsProtested name="PostingProfileBillsProtested">PostingProfileBillsProtested</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBillsProtested attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileBillsRemitCollection name="PostingProfileBillsRemitCollection">PostingProfileBillsRemitCollection</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBillsRemitCollection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileBillsRemitDiscount name="PostingProfileBillsRemitDiscount">PostingProfileBillsRemitDiscount</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBillsRemitDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrenotificationDaysFirst name="PrenotificationDaysFirst">PrenotificationDaysFirst</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrenotificationDaysFirst attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrenotificationDaysRecurring name="PrenotificationDaysRecurring">PrenotificationDaysRecurring</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrenotificationDaysRecurring attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrepaymentDate_W name="PrepaymentDate_W">PrepaymentDate_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentDate_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrepaymentFactureAutoCreate_RU name="PrepaymentFactureAutoCreate_RU">PrepaymentFactureAutoCreate_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentFactureAutoCreate_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrepaymentHandlingLayout_W name="PrepaymentHandlingLayout_W">PrepaymentHandlingLayout_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentHandlingLayout_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrepaymentLink_W name="PrepaymentLink_W">PrepaymentLink_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentLink_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrepaymentPostingProfile name="PrepaymentPostingProfile">PrepaymentPostingProfile</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryRelation_BR name="PrimaryRelation_BR">PrimaryRelation_BR</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryRelation_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProjLedgerAllowEdit name="ProjLedgerAllowEdit">ProjLedgerAllowEdit</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjLedgerAllowEdit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProrationType name="ProrationType">ProrationType</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProrationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReasonCodeCashDiscount_CZ name="ReasonCodeCashDiscount_CZ">ReasonCodeCashDiscount_CZ</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonCodeCashDiscount_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnOrdersReasonReq name="ReturnOrdersReasonReq">ReturnOrdersReasonReq</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnOrdersReasonReq attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReversePrepayment_W name="ReversePrepayment_W">ReversePrepayment_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversePrepayment_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RTax25BadDebtReserveLedgerDimension name="RTax25BadDebtReserveLedgerDimension">RTax25BadDebtReserveLedgerDimension</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25BadDebtReserveLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTable name="RTax25ProfitTable">RTax25ProfitTable</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ReceiptPct name="RTax25ReceiptPct">RTax25ReceiptPct</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ReceiptPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RTax25UnrealisedExpenseLedgerDimension name="RTax25UnrealisedExpenseLedgerDimension">RTax25UnrealisedExpenseLedgerDimension</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25UnrealisedExpenseLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesBookFactureProcessingType_RU name="SalesBookFactureProcessingType_RU">SalesBookFactureProcessingType_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBookFactureProcessingType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesCycle name="SalesCycle">SalesCycle</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCycle attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SettlePrepaymentVATType_RU name="SettlePrepaymentVATType_RU">SettlePrepaymentVATType_RU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlePrepaymentVATType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowAmountDebitCredit_JP name="ShowAmountDebitCredit_JP">ShowAmountDebitCredit_JP</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAmountDebitCredit_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpanBillingCodeAcrossInvoices name="SpanBillingCodeAcrossInvoices">SpanBillingCodeAcrossInvoices</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpanBillingCodeAcrossInvoices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TAMDeductionRequireFullSettle name="TAMDeductionRequireFullSettle">TAMDeductionRequireFullSettle</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TAMDeductionRequireFullSettle attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TAMDeductionType name="TAMDeductionType">TAMDeductionType</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TAMDeductionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TAMRebatePosting name="TAMRebatePosting">TAMRebatePosting</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TAMRebatePosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxIntegrationSystem_CN name="TaxIntegrationSystem_CN">TaxIntegrationSystem_CN</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIntegrationSystem_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxOnPrepayment name="TaxOnPrepayment">TaxOnPrepayment</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOnPrepayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxPeriodPaymentCode_PL name="TaxPeriodPaymentCode_PL">TaxPeriodPaymentCode_PL</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriodPaymentCode_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReimbursementExchangeRateType_HU name="TaxReimbursementExchangeRateType_HU">TaxReimbursementExchangeRateType_HU</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReimbursementExchangeRateType_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransReversalReasonReq name="TransReversalReasonReq">TransReversalReasonReq</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransReversalReasonReq attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseFiscalInvoiceAccount name="UseFiscalInvoiceAccount">UseFiscalInvoiceAccount</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFiscalInvoiceAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UsePriorityOnAutoSettlement name="UsePriorityOnAutoSettlement">UsePriorityOnAutoSettlement</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsePriorityOnAutoSettlement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseSettlementPriority name="UseSettlementPriority">UseSettlementPriority</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSettlementPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCREnablePriceDetails name="MCREnablePriceDetails">MCREnablePriceDetails</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnablePriceDetails attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FreeTextInvoiceTimezonePreference name="FreeTextInvoiceTimezonePreference">FreeTextInvoiceTimezonePreference</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeTextInvoiceTimezonePreference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableCancelPostingProfiles name="EnableCancelPostingProfiles">EnableCancelPostingProfiles</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableCancelPostingProfiles attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableReturnPostingProfiles name="EnableReturnPostingProfiles">EnableReturnPostingProfiles</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableReturnPostingProfiles attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableChronologicalInvoiceNumbering_W name="EnableChronologicalInvoiceNumbering_W">EnableChronologicalInvoiceNumbering_W</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableChronologicalInvoiceNumbering_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustAgingSnapshotBatchLimit name="CustAgingSnapshotBatchLimit">CustAgingSnapshotBatchLimit</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAgingSnapshotBatchLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableSubstitutionInvoices_TH name="EnableSubstitutionInvoices_TH">EnableSubstitutionInvoices_TH</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableSubstitutionInvoices_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableSubstitutionProjectInvoices_TH name="EnableSubstitutionProjectInvoices_TH">EnableSubstitutionProjectInvoices_TH</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableSubstitutionProjectInvoices_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustTableChangeProposalIsEnabled name="CustTableChangeProposalIsEnabled">CustTableChangeProposalIsEnabled</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTableChangeProposalIsEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustTableChangeProposalDataEntityBehavior name="CustTableChangeProposalDataEntityBehavior">CustTableChangeProposalDataEntityBehavior</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTableChangeProposalDataEntityBehavior attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EditCashDiscountsWhenDueDateChanged name="EditCashDiscountsWhenDueDateChanged">EditCashDiscountsWhenDueDateChanged</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EditCashDiscountsWhenDueDateChanged attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultFilterForCustomerTransactions name="DefaultFilterForCustomerTransactions">DefaultFilterForCustomerTransactions</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFilterForCustomerTransactions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesBookFormatMappingID name="SalesBookFormatMappingID">SalesBookFormatMappingID</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBookFormatMappingID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesBookAdditionalListFormatMappingID name="SalesBookAdditionalListFormatMappingID">SalesBookAdditionalListFormatMappingID</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBookAdditionalListFormatMappingID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettlementWriteOffEnabled name="SettlementWriteOffEnabled">SettlementWriteOffEnabled</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementWriteOffEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SettlementWriteOffLedgerDimension name="SettlementWriteOffLedgerDimension">SettlementWriteOffLedgerDimension</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementWriteOffLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettlementWriteOffReasonCode name="SettlementWriteOffReasonCode">SettlementWriteOffReasonCode</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementWriteOffReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementWriteOffJournalName name="SettlementWriteOffJournalName">SettlementWriteOffJournalName</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementWriteOffJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25DebtModel name="RTax25DebtModel">RTax25DebtModel</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25DebtModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25DebtModelTax name="RTax25DebtModelTax">RTax25DebtModelTax</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25DebtModelTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EnableSingleLineTaxAdjustment name="EnableSingleLineTaxAdjustment">EnableSingleLineTaxAdjustment</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableSingleLineTaxAdjustment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BypassValidationOfAccountingDistributions name="BypassValidationOfAccountingDistributions">BypassValidationOfAccountingDistributions</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BypassValidationOfAccountingDistributions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SuppressDepreciationOfPaymentSection name="SuppressDepreciationOfPaymentSection">SuppressDepreciationOfPaymentSection</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuppressDepreciationOfPaymentSection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckForOverlapsAndGaps name="CheckForOverlapsAndGaps">CheckForOverlapsAndGaps</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckForOverlapsAndGaps attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UsualExporterExemptionTaxGroup_IT name="UsualExporterExemptionTaxGroup_IT">UsualExporterExemptionTaxGroup_IT</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsualExporterExemptionTaxGroup_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticIntentLetterAssignment_IT name="AutomaticIntentLetterAssignment_IT">AutomaticIntentLetterAssignment_IT</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticIntentLetterAssignment_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CommissionType_IT name="CommissionType_IT">CommissionType_IT</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionType_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustCollectionManagerEnablePerfImprove name="CustCollectionManagerEnablePerfImprove">CustCollectionManagerEnablePerfImprove</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustCollectionManagerEnablePerfImprove attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AdvanceInvoiceOffsetLedgerDimension_WRelationshipId name="Relationship_AdvanceInvoiceOffsetLedgerDimension_WRelationshipId">Relationship_AdvanceInvoiceOffsetLedgerDimension_WRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AdvanceInvoiceOffsetLedgerDimension_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AdvanceInvoicePostingProfile_WRelationshipId name="Relationship_AdvanceInvoicePostingProfile_WRelationshipId">Relationship_AdvanceInvoicePostingProfile_WRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AdvanceInvoicePostingProfile_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AdvanceInvoiceTaxGroup_WRelationshipId name="Relationship_AdvanceInvoiceTaxGroup_WRelationshipId">Relationship_AdvanceInvoiceTaxGroup_WRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AdvanceInvoiceTaxGroup_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AdvanceInvoiceTaxItemGroup_WRelationshipId name="Relationship_AdvanceInvoiceTaxItemGroup_WRelationshipId">Relationship_AdvanceInvoiceTaxItemGroup_WRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AdvanceInvoiceTaxItemGroup_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankCustPaymIdTableRelationshipId name="Relationship_BankCustPaymIdTableRelationshipId">Relationship_BankCustPaymIdTableRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankCustPaymIdTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/BankCustPaymIdTable.md" target="_blank">/core/erp/Tables/Finance/Bank/Main/BankCustPaymIdTable.cdm.json/BankCustPaymIdTable</a></td><td><a href="../../Bank/Main/BankCustPaymIdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankTransTypeRelationshipId name="Relationship_BankTransTypeRelationshipId">Relationship_BankTransTypeRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankTransTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/BankTransType.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/BankTransType.cdm.json/BankTransType</a></td><td><a href="../../Bank/Group/BankTransType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ClearingLedgerDimensionRelationshipId name="Relationship_ClearingLedgerDimensionRelationshipId">Relationship_ClearingLedgerDimensionRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ClearingLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CollectionsOMTeamRelationshipId name="Relationship_CollectionsOMTeamRelationshipId">Relationship_CollectionsOMTeamRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CollectionsOMTeamRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/OMTeam.md" target="_blank">/core/erp/Tables/Common/GAB/Main/OMTeam.cdm.json/OMTeam</a></td><td><a href="../../../Common/GAB/Main/OMTeam.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CreditCardCostCenterDimensionAttributeRelationshipId name="Relationship_CreditCardCostCenterDimensionAttributeRelationshipId">Relationship_CreditCardCostCenterDimensionAttributeRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CreditCardCostCenterDimensionAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Reference/DimensionAttribute.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Reference/DimensionAttribute.cdm.json/DimensionAttribute</a></td><td><a href="../../FinancialDimensions/Reference/DimensionAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CreditCardPostingLedgerDimensionRelationshipId name="Relationship_CreditCardPostingLedgerDimensionRelationshipId">Relationship_CreditCardPostingLedgerDimensionRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CreditCardPostingLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_PostingProfileRelationshipId name="Relationship_CustLedger_PostingProfileRelationshipId">Relationship_CustLedger_PostingProfileRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_PostingProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_PostingProfileBillsRelationshipId name="Relationship_CustLedger_PostingProfileBillsRelationshipId">Relationship_CustLedger_PostingProfileBillsRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_PostingProfileBillsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_PostingProfileBillsEndorsedRelationshipId name="Relationship_CustLedger_PostingProfileBillsEndorsedRelationshipId">Relationship_CustLedger_PostingProfileBillsEndorsedRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_PostingProfileBillsEndorsedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_PostingProfileBillsProtestedRelationshipId name="Relationship_CustLedger_PostingProfileBillsProtestedRelationshipId">Relationship_CustLedger_PostingProfileBillsProtestedRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_PostingProfileBillsProtestedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_PostingProfileBillsRemitDisRelationshipId name="Relationship_CustLedger_PostingProfileBillsRemitDisRelationshipId">Relationship_CustLedger_PostingProfileBillsRemitDisRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_PostingProfileBillsRemitDisRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_PostingProfileBillsRemotCollRelationshipId name="Relationship_CustLedger_PostingProfileBillsRemotCollRelationshipId">Relationship_CustLedger_PostingProfileBillsRemotCollRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_PostingProfileBillsRemotCollRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_PrepaymentPostingProfileRelationshipId name="Relationship_CustLedger_PrepaymentPostingProfileRelationshipId">Relationship_CustLedger_PrepaymentPostingProfileRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_PrepaymentPostingProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/erp/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExchangeRateTypeRelationshipId name="Relationship_ExchangeRateTypeRelationshipId">Relationship_ExchangeRateTypeRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExchangeRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/ExchangeRateType.md" target="_blank">/core/erp/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../../../Common/Currency/Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvoiceReferenceNumberSequenceTableRelationshipId name="Relationship_InvoiceReferenceNumberSequenceTableRelationshipId">Relationship_InvoiceReferenceNumberSequenceTableRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceReferenceNumberSequenceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAllocateKeyRelationshipId name="Relationship_LedgerAllocateKeyRelationshipId">Relationship_LedgerAllocateKeyRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAllocateKeyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Group/LedgerAllocateKey.md" target="_blank">/core/erp/Tables/Finance/Ledger/Group/LedgerAllocateKey.cdm.json/LedgerAllocateKey</a></td><td><a href="../../Ledger/Group/LedgerAllocateKey.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalNameRelationshipId name="Relationship_LedgerJournalNameRelationshipId">Relationship_LedgerJournalNameRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/erp/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTerm_Due2PaymentRelationshipId name="Relationship_PaymTerm_Due2PaymentRelationshipId">Relationship_PaymTerm_Due2PaymentRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTerm_Due2PaymentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/PaymTerm.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTerm_INvoice2DueRelationshipId name="Relationship_PaymTerm_INvoice2DueRelationshipId">Relationship_PaymTerm_INvoice2DueRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTerm_INvoice2DueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/PaymTerm.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTerm_InvoicePeriodRelationshipId name="Relationship_PaymTerm_InvoicePeriodRelationshipId">Relationship_PaymTerm_InvoicePeriodRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTerm_InvoicePeriodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/PaymTerm.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlTaxDueTableRelationshipId name="Relationship_PlTaxDueTableRelationshipId">Relationship_PlTaxDueTableRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlTaxDueTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/PlTaxDueTable.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/PlTaxDueTable.cdm.json/PlTaxDueTable</a></td><td><a href="../../Tax/Group/PlTaxDueTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReasonCodeCashDiscount_CZRelationshipId name="Relationship_ReasonCodeCashDiscount_CZRelationshipId">Relationship_ReasonCodeCashDiscount_CZRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReasonCodeCashDiscount_CZRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Group/ReasonTable.md" target="_blank">/core/erp/Tables/Finance/Ledger/Group/ReasonTable.cdm.json/ReasonTable</a></td><td><a href="../../Ledger/Group/ReasonTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReasonTableRelationshipId name="Relationship_ReasonTableRelationshipId">Relationship_ReasonTableRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReasonTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Group/ReasonTable.md" target="_blank">/core/erp/Tables/Finance/Ledger/Group/ReasonTable.cdm.json/ReasonTable</a></td><td><a href="../../Ledger/Group/ReasonTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25BadDebtReserveLedgerDimensionRelationshipId name="Relationship_RTax25BadDebtReserveLedgerDimensionRelationshipId">Relationship_RTax25BadDebtReserveLedgerDimensionRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25BadDebtReserveLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableRelationshipId name="Relationship_RTax25ProfitTableRelationshipId">Relationship_RTax25ProfitTableRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25UnrealisedExpenseLedgerDimensionRelationshipId name="Relationship_RTax25UnrealisedExpenseLedgerDimensionRelationshipId">Relationship_RTax25UnrealisedExpenseLedgerDimensionRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25UnrealisedExpenseLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StatRepIntervalRelationshipId name="Relationship_StatRepIntervalRelationshipId">Relationship_StatRepIntervalRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StatRepIntervalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/StatRepInterval.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/StatRepInterval.cdm.json/StatRepInterval</a></td><td><a href="../../Ledger/Main/StatRepInterval.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysEmailTable_CollGenSysEmailIdRelationshipId name="Relationship_SysEmailTable_CollGenSysEmailIdRelationshipId">Relationship_SysEmailTable_CollGenSysEmailIdRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysEmailTable_CollGenSysEmailIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysEmailTable_CollSalespersonsSysEmailIdRelationshipId name="Relationship_SysEmailTable_CollSalespersonsSysEmailIdRelationshipId">Relationship_SysEmailTable_CollSalespersonsSysEmailIdRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysEmailTable_CollSalespersonsSysEmailIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysEmailTable_CollStatementSysEmailIdRelationshipId name="Relationship_SysEmailTable_CollStatementSysEmailIdRelationshipId">Relationship_SysEmailTable_CollStatementSysEmailIdRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysEmailTable_CollStatementSysEmailIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroup_RURelationshipId name="Relationship_TaxGroup_RURelationshipId">Relationship_TaxGroup_RURelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroup_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxItemGroup_RURelationshipId name="Relationship_TaxItemGroup_RURelationshipId">Relationship_TaxItemGroup_RURelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroup_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SettlementWriteOffLedgerDimRelationshipId name="Relationship_SettlementWriteOffLedgerDimRelationshipId">Relationship_SettlementWriteOffLedgerDimRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SettlementWriteOffLedgerDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SettlementWriteOffReasonRelationshipId name="Relationship_SettlementWriteOffReasonRelationshipId">Relationship_SettlementWriteOffReasonRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SettlementWriteOffReasonRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/CustWriteOffFinancialReasonsSetup.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Miscellaneous/CustWriteOffFinancialReasonsSetup.cdm.json/CustWriteOffFinancialReasonsSetup</a></td><td><a href="../Miscellaneous/CustWriteOffFinancialReasonsSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SettlementWriteOffJournalNameRelationshipId name="Relationship_SettlementWriteOffJournalNameRelationshipId">Relationship_SettlementWriteOffJournalNameRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SettlementWriteOffJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/erp/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25DebtModelRelationshipId name="Relationship_RTax25DebtModelRelationshipId">Relationship_RTax25DebtModelRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25DebtModelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25DebtModel.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25DebtModel.cdm.json/RTax25DebtModel</a></td><td><a href="../../RTax25/Group/RTax25DebtModel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25DebtModelTaxRelationshipId name="Relationship_RTax25DebtModelTaxRelationshipId">Relationship_RTax25DebtModelTaxRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25DebtModelTaxRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25DebtModel.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25DebtModel.cdm.json/RTax25DebtModel</a></td><td><a href="../../RTax25/Group/RTax25DebtModel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroupHeading_UsualExporterTaxGroup_ITRelationshipId name="Relationship_TaxGroupHeading_UsualExporterTaxGroup_ITRelationshipId">Relationship_TaxGroupHeading_UsualExporterTaxGroup_ITRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupHeading_UsualExporterTaxGroup_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/CustParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
