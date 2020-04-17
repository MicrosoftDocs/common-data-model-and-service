---
title: VendParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# VendParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/AccountsPayable/Parameter/VendParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRRoyaltyJournalName](#MCRRoyaltyJournalName)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[InvoicePeriod](#InvoicePeriod)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PostingProfile](#PostingProfile)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AccountDisc](#AccountDisc)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AccountReceipt](#AccountReceipt)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AdvancePostingProfile](#AdvancePostingProfile)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AgreementCreditLine_RU](#AgreementCreditLine_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AmountDiffBookCorrection_RU](#AmountDiffBookCorrection_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AssetPaymentAllocation_RU](#AssetPaymentAllocation_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AutoSettle](#AutoSettle)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[BudgetSettle](#BudgetSettle)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CashDisc](#CashDisc)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CashDiscForCreditNote](#CashDiscForCreditNote)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CashDiscForPartialPaym](#CashDiscForPartialPaym)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CashDiscVAT](#CashDiscVAT)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CheckInvoice](#CheckInvoice)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CheckTaxInvoice](#CheckTaxInvoice)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ClearingLedgerDimension](#ClearingLedgerDimension)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ConfirmingInvoices](#ConfirmingInvoices)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CopyInvoiceDimension_RU](#CopyInvoiceDimension_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CreateFactureUnpostPrepayment_RU](#CreateFactureUnpostPrepayment_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CreditError](#CreditError)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CreditInvoicingReport](#CreditInvoicingReport)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CreditMaxCheck](#CreditMaxCheck)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CreditNoteSettlementType](#CreditNoteSettlementType)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CustomsLandingChargesPct_IN](#CustomsLandingChargesPct_IN)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DebtsTransitLedgerDimension_RU](#DebtsTransitLedgerDimension_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DefaultVend](#DefaultVend)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DimSettlementCtrlType_RU](#DimSettlementCtrlType_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DisplayExtendedPriceToleranceIcon](#DisplayExtendedPriceToleranceIcon)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DisplayMiscChargeToleranceIcon](#DisplayMiscChargeToleranceIcon)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DisplayPriceMatchIcon](#DisplayPriceMatchIcon)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DisplayTotalPriceMatchIcon](#DisplayTotalPriceMatchIcon)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DocumentDateForIntracomVAT_W](#DocumentDateForIntracomVAT_W)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DoPrintTransportationDocument](#DoPrintTransportationDocument)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Due2Payment](#Due2Payment)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DueToTransDate](#DueToTransDate)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ExtendedPriceToleranceAmount](#ExtendedPriceToleranceAmount)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ExtendedPriceTolerancePercentage](#ExtendedPriceTolerancePercentage)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[FactureIssuePeriod_RU](#FactureIssuePeriod_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[IntracomVAT](#IntracomVAT)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Invoice2Due](#Invoice2Due)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ItemDimAdjustLineControl_RU](#ItemDimAdjustLineControl_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[KeepSalesTaxAdjustmentsForPO](#KeepSalesTaxAdjustmentsForPO)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Key](#Key)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MandatoryInvoiceVATNum](#MandatoryInvoiceVATNum)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MandatoryTaxGroup](#MandatoryTaxGroup)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MandatoryVATNum](#MandatoryVATNum)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MatchedPackingSlipsInquiry](#MatchedPackingSlipsInquiry)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MatchingPolicy](#MatchingPolicy)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MatchingPolicyAllowOverride](#MatchingPolicyAllowOverride)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MaxMSTDiff](#MaxMSTDiff)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MaxMSTOverUnder](#MaxMSTOverUnder)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRBrokerDifferentialJournal](#MCRBrokerDifferentialJournal)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRBrokerExpenseJournal](#MCRBrokerExpenseJournal)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRBrokerManualJourPost](#MCRBrokerManualJourPost)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRProcurementCategory](#MCRProcurementCategory)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRRoyaltyLedgerDimension](#MCRRoyaltyLedgerDimension)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRRoyaltyOffsetLedgerDimension](#MCRRoyaltyOffsetLedgerDimension)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRStartingDayOfWeekPeriod](#MCRStartingDayOfWeekPeriod)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MiscChargeTolerancePercentage](#MiscChargeTolerancePercentage)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MixedPayment](#MixedPayment)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[NotesJournalsValidations](#NotesJournalsValidations)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[OverdueCITPITDimensionAttribute_W](#OverdueCITPITDimensionAttribute_W)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PolicyViolationAction](#PolicyViolationAction)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PostChargeAccount](#PostChargeAccount)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PostingProfileInvoiceRemit](#PostingProfileInvoiceRemit)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PostingProfileNotes](#PostingProfileNotes)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PostingProfileRemitNotes](#PostingProfileRemitNotes)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PostInvoiceMatchDiscrepancies](#PostInvoiceMatchDiscrepancies)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PostPackingSlip](#PostPackingSlip)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PrepaymentHandlingLayout_W](#PrepaymentHandlingLayout_W)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PrepaymentPostingProfile](#PrepaymentPostingProfile)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PrimaryRelation_BR](#PrimaryRelation_BR)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ProhibitVATinVendJournal_CZ](#ProhibitVATinVendJournal_CZ)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PurchAgreementAccountStructure_PSN](#PurchAgreementAccountStructure_PSN)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PurchAgreementFinancialDimension_PSN](#PurchAgreementFinancialDimension_PSN)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ReversePrepayment_W](#ReversePrepayment_W)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[RTax25ProfitTable](#RTax25ProfitTable)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[RTax25UnrealisedRevenueLedgerDimension](#RTax25UnrealisedRevenueLedgerDimension)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[SettlePrepaymentVATType_W](#SettlePrepaymentVATType_W)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ShowAmountDebitCredit_JP](#ShowAmountDebitCredit_JP)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[TaxGroup_W](#TaxGroup_W)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[TaxItemGroup_W](#TaxItemGroup_W)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[TaxOnPrepayment](#TaxOnPrepayment)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[TaxPeriodPaymentCode_PL](#TaxPeriodPaymentCode_PL)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[TotalPriceTolerancePercentage](#TotalPriceTolerancePercentage)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[UseDocumentDate](#UseDocumentDate)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[UseExtendedPriceMatching](#UseExtendedPriceMatching)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[UseInvoiceMatching](#UseInvoiceMatching)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[UseMiscChargeMatching](#UseMiscChargeMatching)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[UsePurchConsumpAccount_RU](#UsePurchConsumpAccount_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[UseTotalPriceMatching](#UseTotalPriceMatching)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[UseVendAdvanceInvoice_RU](#UseVendAdvanceInvoice_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VatProcessGroupBy_RU](#VatProcessGroupBy_RU)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendConsInvoice_JP](#VendConsInvoice_JP)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendDiscountOffsetMethod_psn](#VendDiscountOffsetMethod_psn)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendInvoiceDefaultGroupType](#VendInvoiceDefaultGroupType)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendInvoiceDocDate](#VendInvoiceDocDate)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendInvoiceGroupingEnable](#VendInvoiceGroupingEnable)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendInvoiceInternalDefaultGroup](#VendInvoiceInternalDefaultGroup)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendInvoicePolicy](#VendInvoicePolicy)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendInvoiceRefNumValidation_FI](#VendInvoiceRefNumValidation_FI)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendInvoiceWebServiceDefaultGroup](#VendInvoiceWebServiceDefaultGroup)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendNameFromVATNum](#VendNameFromVATNum)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendPaymentGroupingEnable](#VendPaymentGroupingEnable)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendTaxRegisterApproval](#VendTaxRegisterApproval)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[W9Validation](#W9Validation)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MCRBrokerProcurementCategory](#MCRBrokerProcurementCategory)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AutomaticHeaderMatching](#AutomaticHeaderMatching)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[UseFiscalInvoiceAccount](#UseFiscalInvoiceAccount)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PurchPrepayApplicationPolicy](#PurchPrepayApplicationPolicy)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[CalculateInvoiceTotal](#CalculateInvoiceTotal)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ValidateTaxInvoiceDate_TH](#ValidateTaxInvoiceDate_TH)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AllowedTaxInvoicePostingPeriod_TH](#AllowedTaxInvoicePostingPeriod_TH)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendTableChangeProposalIsEnabled](#VendTableChangeProposalIsEnabled)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[ChangeProposalDataEntityBehavior](#ChangeProposalDataEntityBehavior)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[EnableElectronicPaymentNumber](#EnableElectronicPaymentNumber)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[EditCashDiscountsWhenDueDateChanged](#EditCashDiscountsWhenDueDateChanged)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DefaultFilterForVendorTransactions](#DefaultFilterForVendorTransactions)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PurchBookFormatMappingID](#PurchBookFormatMappingID)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PurchBookAdditionalListFormatMappingID](#PurchBookAdditionalListFormatMappingID)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[SettlementWriteOffEnabled](#SettlementWriteOffEnabled)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[SettlementWriteOffLedgerDimension](#SettlementWriteOffLedgerDimension)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[SettlementWriteOffReasonCode](#SettlementWriteOffReasonCode)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[SettlementWriteOffJournalName](#SettlementWriteOffJournalName)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[VendInvoiceInUseRecoverEnable](#VendInvoiceInUseRecoverEnable)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MaxInvoicesPerBatch](#MaxInvoicesPerBatch)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[MaxWaitTimeForInvoiceScheduledStatus_Hours](#MaxWaitTimeForInvoiceScheduledStatus_Hours)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[BypassValidationOfAccountingDistributions](#BypassValidationOfAccountingDistributions)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PollingInterval_Minutes](#PollingInterval_Minutes)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PlafondDateProposal_IT](#PlafondDateProposal_IT)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PlafondAllowNegative_IT](#PlafondAllowNegative_IT)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PlafondTaxGroup_IT](#PlafondTaxGroup_IT)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[IntentLetterERFormatMappingId_IT](#IntentLetterERFormatMappingId_IT)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[AutomaticIntentLetterAssignment_IT](#AutomaticIntentLetterAssignment_IT)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DisablePaymentIDValidation_CH](#DisablePaymentIDValidation_CH)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PreventDuplicateTaxId](#PreventDuplicateTaxId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PSNJournalizingDefinition](#PSNJournalizingDefinition)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[PSNActivatePurchasingCard](#PSNActivatePurchasingCard)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_ClearingLedgerDimensionRelationshipId](#Relationship_ClearingLedgerDimensionRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_DebtsTransitLedgerDimension_RURelationshipId](#Relationship_DebtsTransitLedgerDimension_RURelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_EcoResCategoryRelationshipId](#Relationship_EcoResCategoryRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_LedgerAllocateKeyRelationshipId](#Relationship_LedgerAllocateKeyRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_MCRBrokerDifferentialJournalRelationshipId](#Relationship_MCRBrokerDifferentialJournalRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_MCRBrokerExpenseJournalRelationshipId](#Relationship_MCRBrokerExpenseJournalRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_MCRRoyaltyJournalNameRelationshipId](#Relationship_MCRRoyaltyJournalNameRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_MCRRoyaltyLedgerDimensionRelationshipId](#Relationship_MCRRoyaltyLedgerDimensionRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_MCRRoyaltyOffsetLedgerDimensionRelationshipId](#Relationship_MCRRoyaltyOffsetLedgerDimensionRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_OverdueCITPITDimensionAttribute_WRelationshipId](#Relationship_OverdueCITPITDimensionAttribute_WRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_PaymTerm_Due2PaymentRelationshipId](#Relationship_PaymTerm_Due2PaymentRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_PaymTerm_Invoice2DueRelationshipId](#Relationship_PaymTerm_Invoice2DueRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_PaymTerm_InvoicePeriodRelationshipId](#Relationship_PaymTerm_InvoicePeriodRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_PlTaxDueTableRelationshipId](#Relationship_PlTaxDueTableRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_PurchAgreementAccountStructure_PSNRelationshipId](#Relationship_PurchAgreementAccountStructure_PSNRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_PurchAgreementFinancialDimension_PSNRelationshipId](#Relationship_PurchAgreementFinancialDimension_PSNRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_RTax25ProfitTableRelationshipId](#Relationship_RTax25ProfitTableRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_RTax25UnrealisedRevenueLedgerDimensionRelationshipId](#Relationship_RTax25UnrealisedRevenueLedgerDimensionRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_TaxGroupHeadingRelationshipId](#Relationship_TaxGroupHeadingRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_TaxItemGroupHeadingRelationshipId](#Relationship_TaxItemGroupHeadingRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_VendLedger_AdvancePostingProfileRelationshipId](#Relationship_VendLedger_AdvancePostingProfileRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_VendLedger_PostingProfileRelationshipId](#Relationship_VendLedger_PostingProfileRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_VendLedger_PostingProfileInvoiceRemitRelationshipId](#Relationship_VendLedger_PostingProfileInvoiceRemitRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_VendLedger_PostingProfileNotesRelationshipId](#Relationship_VendLedger_PostingProfileNotesRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_VendLedger_PostingProfileRemitNotesRelationshipId](#Relationship_VendLedger_PostingProfileRemitNotesRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_VendLedger_PrepaymentPostingProfileRelationshipId](#Relationship_VendLedger_PrepaymentPostingProfileRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_EcoResCategory_BrokerProcurementCategoryRelationshipId](#Relationship_EcoResCategory_BrokerProcurementCategoryRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_SettlementWriteOffLedgerDimRelationshipId](#Relationship_SettlementWriteOffLedgerDimRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_SettlementWriteOffReasonRelationshipId](#Relationship_SettlementWriteOffReasonRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_SettlementWriteOffJournalNameRelationshipId](#Relationship_SettlementWriteOffJournalNameRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_TaxGroupHeading_PlafondTaxGroup_ITRelationshipId](#Relationship_TaxGroupHeading_PlafondTaxGroup_ITRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_PSNJournalizingDefinitionRelationshipId](#Relationship_PSNJournalizingDefinitionRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendParameters.md" target="_blank">Parameter/VendParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MCRRoyaltyJournalName name="MCRRoyaltyJournalName">MCRRoyaltyJournalName</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRRoyaltyJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicePeriod name="InvoicePeriod">InvoicePeriod</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#AccountDisc name="AccountDisc">AccountDisc</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AccountReceipt name="AccountReceipt">AccountReceipt</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountReceipt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdvancePostingProfile name="AdvancePostingProfile">AdvancePostingProfile</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancePostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementCreditLine_RU name="AgreementCreditLine_RU">AgreementCreditLine_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementCreditLine_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AmountDiffBookCorrection_RU name="AmountDiffBookCorrection_RU">AmountDiffBookCorrection_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountDiffBookCorrection_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetPaymentAllocation_RU name="AssetPaymentAllocation_RU">AssetPaymentAllocation_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetPaymentAllocation_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AutoSettle name="AutoSettle">AutoSettle</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoSettle attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetSettle name="BudgetSettle">BudgetSettle</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#CashDisc name="CashDisc">CashDisc</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDiscForCreditNote name="CashDiscForCreditNote">CashDiscForCreditNote</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscForCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDiscForPartialPaym name="CashDiscForPartialPaym">CashDiscForPartialPaym</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscForPartialPaym attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDiscVAT name="CashDiscVAT">CashDiscVAT</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscVAT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckInvoice name="CheckInvoice">CheckInvoice</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckTaxInvoice name="CheckTaxInvoice">CheckTaxInvoice</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckTaxInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClearingLedgerDimension name="ClearingLedgerDimension">ClearingLedgerDimension</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#ConfirmingInvoices name="ConfirmingInvoices">ConfirmingInvoices</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmingInvoices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CopyInvoiceDimension_RU name="CopyInvoiceDimension_RU">CopyInvoiceDimension_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopyInvoiceDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreateFactureUnpostPrepayment_RU name="CreateFactureUnpostPrepayment_RU">CreateFactureUnpostPrepayment_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateFactureUnpostPrepayment_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditError name="CreditError">CreditError</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditInvoicingReport name="CreditInvoicingReport">CreditInvoicingReport</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditInvoicingReport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditMaxCheck name="CreditMaxCheck">CreditMaxCheck</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditMaxCheck attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditNoteSettlementType name="CreditNoteSettlementType">CreditNoteSettlementType</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteSettlementType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomsLandingChargesPct_IN name="CustomsLandingChargesPct_IN">CustomsLandingChargesPct_IN</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsLandingChargesPct_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DebtsTransitLedgerDimension_RU name="DebtsTransitLedgerDimension_RU">DebtsTransitLedgerDimension_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebtsTransitLedgerDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultVend name="DefaultVend">DefaultVend</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVend attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimSettlementCtrlType_RU name="DimSettlementCtrlType_RU">DimSettlementCtrlType_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimSettlementCtrlType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisplayExtendedPriceToleranceIcon name="DisplayExtendedPriceToleranceIcon">DisplayExtendedPriceToleranceIcon</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayExtendedPriceToleranceIcon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisplayMiscChargeToleranceIcon name="DisplayMiscChargeToleranceIcon">DisplayMiscChargeToleranceIcon</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayMiscChargeToleranceIcon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisplayPriceMatchIcon name="DisplayPriceMatchIcon">DisplayPriceMatchIcon</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayPriceMatchIcon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisplayTotalPriceMatchIcon name="DisplayTotalPriceMatchIcon">DisplayTotalPriceMatchIcon</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayTotalPriceMatchIcon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentDateForIntracomVAT_W name="DocumentDateForIntracomVAT_W">DocumentDateForIntracomVAT_W</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDateForIntracomVAT_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DoPrintTransportationDocument name="DoPrintTransportationDocument">DoPrintTransportationDocument</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoPrintTransportationDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Due2Payment name="Due2Payment">Due2Payment</a>

First included in: Parameter/VendParameters (this entity)  

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

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueToTransDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExtendedPriceToleranceAmount name="ExtendedPriceToleranceAmount">ExtendedPriceToleranceAmount</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtendedPriceToleranceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExtendedPriceTolerancePercentage name="ExtendedPriceTolerancePercentage">ExtendedPriceTolerancePercentage</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtendedPriceTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FactureIssuePeriod_RU name="FactureIssuePeriod_RU">FactureIssuePeriod_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureIssuePeriod_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IntracomVAT name="IntracomVAT">IntracomVAT</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntracomVAT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Invoice2Due name="Invoice2Due">Invoice2Due</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#ItemDimAdjustLineControl_RU name="ItemDimAdjustLineControl_RU">ItemDimAdjustLineControl_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemDimAdjustLineControl_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#KeepSalesTaxAdjustmentsForPO name="KeepSalesTaxAdjustmentsForPO">KeepSalesTaxAdjustmentsForPO</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeepSalesTaxAdjustmentsForPO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#MandatoryInvoiceVATNum name="MandatoryInvoiceVATNum">MandatoryInvoiceVATNum</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryInvoiceVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MandatoryTaxGroup name="MandatoryTaxGroup">MandatoryTaxGroup</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryTaxGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MandatoryVATNum name="MandatoryVATNum">MandatoryVATNum</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MatchedPackingSlipsInquiry name="MatchedPackingSlipsInquiry">MatchedPackingSlipsInquiry</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchedPackingSlipsInquiry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MatchingPolicy name="MatchingPolicy">MatchingPolicy</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MatchingPolicyAllowOverride name="MatchingPolicyAllowOverride">MatchingPolicyAllowOverride</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingPolicyAllowOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxMSTDiff name="MaxMSTDiff">MaxMSTDiff</a>

First included in: Parameter/VendParameters (this entity)  

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

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#MCRBrokerDifferentialJournal name="MCRBrokerDifferentialJournal">MCRBrokerDifferentialJournal</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRBrokerDifferentialJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRBrokerExpenseJournal name="MCRBrokerExpenseJournal">MCRBrokerExpenseJournal</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRBrokerExpenseJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRBrokerManualJourPost name="MCRBrokerManualJourPost">MCRBrokerManualJourPost</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRBrokerManualJourPost attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRProcurementCategory name="MCRProcurementCategory">MCRProcurementCategory</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRProcurementCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MCRRoyaltyLedgerDimension name="MCRRoyaltyLedgerDimension">MCRRoyaltyLedgerDimension</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRRoyaltyLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MCRRoyaltyOffsetLedgerDimension name="MCRRoyaltyOffsetLedgerDimension">MCRRoyaltyOffsetLedgerDimension</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRRoyaltyOffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MCRStartingDayOfWeekPeriod name="MCRStartingDayOfWeekPeriod">MCRStartingDayOfWeekPeriod</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRStartingDayOfWeekPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MiscChargeTolerancePercentage name="MiscChargeTolerancePercentage">MiscChargeTolerancePercentage</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiscChargeTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MixedPayment name="MixedPayment">MixedPayment</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixedPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NotesJournalsValidations name="NotesJournalsValidations">NotesJournalsValidations</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotesJournalsValidations attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OverdueCITPITDimensionAttribute_W name="OverdueCITPITDimensionAttribute_W">OverdueCITPITDimensionAttribute_W</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverdueCITPITDimensionAttribute_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PolicyViolationAction name="PolicyViolationAction">PolicyViolationAction</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyViolationAction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostChargeAccount name="PostChargeAccount">PostChargeAccount</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostChargeAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostingProfileInvoiceRemit name="PostingProfileInvoiceRemit">PostingProfileInvoiceRemit</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileInvoiceRemit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileNotes name="PostingProfileNotes">PostingProfileNotes</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileRemitNotes name="PostingProfileRemitNotes">PostingProfileRemitNotes</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileRemitNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostInvoiceMatchDiscrepancies name="PostInvoiceMatchDiscrepancies">PostInvoiceMatchDiscrepancies</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostInvoiceMatchDiscrepancies attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostPackingSlip name="PostPackingSlip">PostPackingSlip</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrepaymentHandlingLayout_W name="PrepaymentHandlingLayout_W">PrepaymentHandlingLayout_W</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentHandlingLayout_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrepaymentPostingProfile name="PrepaymentPostingProfile">PrepaymentPostingProfile</a>

First included in: Parameter/VendParameters (this entity)  

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

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryRelation_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProhibitVATinVendJournal_CZ name="ProhibitVATinVendJournal_CZ">ProhibitVATinVendJournal_CZ</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProhibitVATinVendJournal_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchAgreementAccountStructure_PSN name="PurchAgreementAccountStructure_PSN">PurchAgreementAccountStructure_PSN</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAgreementAccountStructure_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchAgreementFinancialDimension_PSN name="PurchAgreementFinancialDimension_PSN">PurchAgreementFinancialDimension_PSN</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAgreementFinancialDimension_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReversePrepayment_W name="ReversePrepayment_W">ReversePrepayment_W</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversePrepayment_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RTax25ProfitTable name="RTax25ProfitTable">RTax25ProfitTable</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#RTax25UnrealisedRevenueLedgerDimension name="RTax25UnrealisedRevenueLedgerDimension">RTax25UnrealisedRevenueLedgerDimension</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25UnrealisedRevenueLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettlePrepaymentVATType_W name="SettlePrepaymentVATType_W">SettlePrepaymentVATType_W</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlePrepaymentVATType_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowAmountDebitCredit_JP name="ShowAmountDebitCredit_JP">ShowAmountDebitCredit_JP</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAmountDebitCredit_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxGroup_W name="TaxGroup_W">TaxGroup_W</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup_W name="TaxItemGroup_W">TaxItemGroup_W</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOnPrepayment name="TaxOnPrepayment">TaxOnPrepayment</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOnPrepayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxPeriodPaymentCode_PL name="TaxPeriodPaymentCode_PL">TaxPeriodPaymentCode_PL</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#TotalPriceTolerancePercentage name="TotalPriceTolerancePercentage">TotalPriceTolerancePercentage</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPriceTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UseDocumentDate name="UseDocumentDate">UseDocumentDate</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDocumentDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseExtendedPriceMatching name="UseExtendedPriceMatching">UseExtendedPriceMatching</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseExtendedPriceMatching attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseInvoiceMatching name="UseInvoiceMatching">UseInvoiceMatching</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseInvoiceMatching attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseMiscChargeMatching name="UseMiscChargeMatching">UseMiscChargeMatching</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseMiscChargeMatching attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UsePurchConsumpAccount_RU name="UsePurchConsumpAccount_RU">UsePurchConsumpAccount_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsePurchConsumpAccount_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseTotalPriceMatching name="UseTotalPriceMatching">UseTotalPriceMatching</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseTotalPriceMatching attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseVendAdvanceInvoice_RU name="UseVendAdvanceInvoice_RU">UseVendAdvanceInvoice_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseVendAdvanceInvoice_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VatProcessGroupBy_RU name="VatProcessGroupBy_RU">VatProcessGroupBy_RU</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatProcessGroupBy_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendConsInvoice_JP name="VendConsInvoice_JP">VendConsInvoice_JP</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendConsInvoice_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendDiscountOffsetMethod_psn name="VendDiscountOffsetMethod_psn">VendDiscountOffsetMethod_psn</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendDiscountOffsetMethod_psn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendInvoiceDefaultGroupType name="VendInvoiceDefaultGroupType">VendInvoiceDefaultGroupType</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceDefaultGroupType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendInvoiceDocDate name="VendInvoiceDocDate">VendInvoiceDocDate</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceDocDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendInvoiceGroupingEnable name="VendInvoiceGroupingEnable">VendInvoiceGroupingEnable</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceGroupingEnable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendInvoiceInternalDefaultGroup name="VendInvoiceInternalDefaultGroup">VendInvoiceInternalDefaultGroup</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceInternalDefaultGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendInvoicePolicy name="VendInvoicePolicy">VendInvoicePolicy</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoicePolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendInvoiceRefNumValidation_FI name="VendInvoiceRefNumValidation_FI">VendInvoiceRefNumValidation_FI</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceRefNumValidation_FI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendInvoiceWebServiceDefaultGroup name="VendInvoiceWebServiceDefaultGroup">VendInvoiceWebServiceDefaultGroup</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceWebServiceDefaultGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendNameFromVATNum name="VendNameFromVATNum">VendNameFromVATNum</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendNameFromVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendPaymentGroupingEnable name="VendPaymentGroupingEnable">VendPaymentGroupingEnable</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPaymentGroupingEnable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendTaxRegisterApproval name="VendTaxRegisterApproval">VendTaxRegisterApproval</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTaxRegisterApproval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#W9Validation name="W9Validation">W9Validation</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the W9Validation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRBrokerProcurementCategory name="MCRBrokerProcurementCategory">MCRBrokerProcurementCategory</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRBrokerProcurementCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutomaticHeaderMatching name="AutomaticHeaderMatching">AutomaticHeaderMatching</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticHeaderMatching attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseFiscalInvoiceAccount name="UseFiscalInvoiceAccount">UseFiscalInvoiceAccount</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFiscalInvoiceAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchPrepayApplicationPolicy name="PurchPrepayApplicationPolicy">PurchPrepayApplicationPolicy</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchPrepayApplicationPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CalculateInvoiceTotal name="CalculateInvoiceTotal">CalculateInvoiceTotal</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateInvoiceTotal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidateTaxInvoiceDate_TH name="ValidateTaxInvoiceDate_TH">ValidateTaxInvoiceDate_TH</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateTaxInvoiceDate_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowedTaxInvoicePostingPeriod_TH name="AllowedTaxInvoicePostingPeriod_TH">AllowedTaxInvoicePostingPeriod_TH</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedTaxInvoicePostingPeriod_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendTableChangeProposalIsEnabled name="VendTableChangeProposalIsEnabled">VendTableChangeProposalIsEnabled</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTableChangeProposalIsEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ChangeProposalDataEntityBehavior name="ChangeProposalDataEntityBehavior">ChangeProposalDataEntityBehavior</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeProposalDataEntityBehavior attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableElectronicPaymentNumber name="EnableElectronicPaymentNumber">EnableElectronicPaymentNumber</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableElectronicPaymentNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EditCashDiscountsWhenDueDateChanged name="EditCashDiscountsWhenDueDateChanged">EditCashDiscountsWhenDueDateChanged</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EditCashDiscountsWhenDueDateChanged attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultFilterForVendorTransactions name="DefaultFilterForVendorTransactions">DefaultFilterForVendorTransactions</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFilterForVendorTransactions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchBookFormatMappingID name="PurchBookFormatMappingID">PurchBookFormatMappingID</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchBookFormatMappingID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchBookAdditionalListFormatMappingID name="PurchBookAdditionalListFormatMappingID">PurchBookAdditionalListFormatMappingID</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchBookAdditionalListFormatMappingID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettlementWriteOffEnabled name="SettlementWriteOffEnabled">SettlementWriteOffEnabled</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementWriteOffEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SettlementWriteOffLedgerDimension name="SettlementWriteOffLedgerDimension">SettlementWriteOffLedgerDimension</a>

First included in: Parameter/VendParameters (this entity)  

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

First included in: Parameter/VendParameters (this entity)  

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

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#VendInvoiceInUseRecoverEnable name="VendInvoiceInUseRecoverEnable">VendInvoiceInUseRecoverEnable</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceInUseRecoverEnable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxInvoicesPerBatch name="MaxInvoicesPerBatch">MaxInvoicesPerBatch</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxInvoicesPerBatch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxWaitTimeForInvoiceScheduledStatus_Hours name="MaxWaitTimeForInvoiceScheduledStatus_Hours">MaxWaitTimeForInvoiceScheduledStatus_Hours</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxWaitTimeForInvoiceScheduledStatus_Hours attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BypassValidationOfAccountingDistributions name="BypassValidationOfAccountingDistributions">BypassValidationOfAccountingDistributions</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BypassValidationOfAccountingDistributions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PollingInterval_Minutes name="PollingInterval_Minutes">PollingInterval_Minutes</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PollingInterval_Minutes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PlafondDateProposal_IT name="PlafondDateProposal_IT">PlafondDateProposal_IT</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlafondDateProposal_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PlafondAllowNegative_IT name="PlafondAllowNegative_IT">PlafondAllowNegative_IT</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlafondAllowNegative_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PlafondTaxGroup_IT name="PlafondTaxGroup_IT">PlafondTaxGroup_IT</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlafondTaxGroup_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntentLetterERFormatMappingId_IT name="IntentLetterERFormatMappingId_IT">IntentLetterERFormatMappingId_IT</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntentLetterERFormatMappingId_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutomaticIntentLetterAssignment_IT name="AutomaticIntentLetterAssignment_IT">AutomaticIntentLetterAssignment_IT</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticIntentLetterAssignment_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisablePaymentIDValidation_CH name="DisablePaymentIDValidation_CH">DisablePaymentIDValidation_CH</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisablePaymentIDValidation_CH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreventDuplicateTaxId name="PreventDuplicateTaxId">PreventDuplicateTaxId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventDuplicateTaxId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNJournalizingDefinition name="PSNJournalizingDefinition">PSNJournalizingDefinition</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNJournalizingDefinition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PSNActivatePurchasingCard name="PSNActivatePurchasingCard">PSNActivatePurchasingCard</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNActivatePurchasingCard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#Relationship_ClearingLedgerDimensionRelationshipId name="Relationship_ClearingLedgerDimensionRelationshipId">Relationship_ClearingLedgerDimensionRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#Relationship_DebtsTransitLedgerDimension_RURelationshipId name="Relationship_DebtsTransitLedgerDimension_RURelationshipId">Relationship_DebtsTransitLedgerDimension_RURelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DebtsTransitLedgerDimension_RURelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EcoResCategoryRelationshipId name="Relationship_EcoResCategoryRelationshipId">Relationship_EcoResCategoryRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAllocateKeyRelationshipId name="Relationship_LedgerAllocateKeyRelationshipId">Relationship_LedgerAllocateKeyRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#Relationship_MCRBrokerDifferentialJournalRelationshipId name="Relationship_MCRBrokerDifferentialJournalRelationshipId">Relationship_MCRBrokerDifferentialJournalRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRBrokerDifferentialJournalRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MCRBrokerExpenseJournalRelationshipId name="Relationship_MCRBrokerExpenseJournalRelationshipId">Relationship_MCRBrokerExpenseJournalRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRBrokerExpenseJournalRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MCRRoyaltyJournalNameRelationshipId name="Relationship_MCRRoyaltyJournalNameRelationshipId">Relationship_MCRRoyaltyJournalNameRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRRoyaltyJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MCRRoyaltyLedgerDimensionRelationshipId name="Relationship_MCRRoyaltyLedgerDimensionRelationshipId">Relationship_MCRRoyaltyLedgerDimensionRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRRoyaltyLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MCRRoyaltyOffsetLedgerDimensionRelationshipId name="Relationship_MCRRoyaltyOffsetLedgerDimensionRelationshipId">Relationship_MCRRoyaltyOffsetLedgerDimensionRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRRoyaltyOffsetLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OverdueCITPITDimensionAttribute_WRelationshipId name="Relationship_OverdueCITPITDimensionAttribute_WRelationshipId">Relationship_OverdueCITPITDimensionAttribute_WRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OverdueCITPITDimensionAttribute_WRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymTerm_Due2PaymentRelationshipId name="Relationship_PaymTerm_Due2PaymentRelationshipId">Relationship_PaymTerm_Due2PaymentRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#Relationship_PaymTerm_Invoice2DueRelationshipId name="Relationship_PaymTerm_Invoice2DueRelationshipId">Relationship_PaymTerm_Invoice2DueRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTerm_Invoice2DueRelationshipId attribute are listed below.</summary>

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

First included in: Parameter/VendParameters (this entity)  

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

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#Relationship_PurchAgreementAccountStructure_PSNRelationshipId name="Relationship_PurchAgreementAccountStructure_PSNRelationshipId">Relationship_PurchAgreementAccountStructure_PSNRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchAgreementAccountStructure_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Group/DimensionHierarchy.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Group/DimensionHierarchy.cdm.json/DimensionHierarchy</a></td><td><a href="../../FinancialDimensions/Group/DimensionHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchAgreementFinancialDimension_PSNRelationshipId name="Relationship_PurchAgreementFinancialDimension_PSNRelationshipId">Relationship_PurchAgreementFinancialDimension_PSNRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchAgreementFinancialDimension_PSNRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RTax25ProfitTableRelationshipId name="Relationship_RTax25ProfitTableRelationshipId">Relationship_RTax25ProfitTableRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#Relationship_RTax25UnrealisedRevenueLedgerDimensionRelationshipId name="Relationship_RTax25UnrealisedRevenueLedgerDimensionRelationshipId">Relationship_RTax25UnrealisedRevenueLedgerDimensionRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25UnrealisedRevenueLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxGroupHeadingRelationshipId name="Relationship_TaxGroupHeadingRelationshipId">Relationship_TaxGroupHeadingRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupHeadingRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxItemGroupHeadingRelationshipId name="Relationship_TaxItemGroupHeadingRelationshipId">Relationship_TaxItemGroupHeadingRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroupHeadingRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendLedger_AdvancePostingProfileRelationshipId name="Relationship_VendLedger_AdvancePostingProfileRelationshipId">Relationship_VendLedger_AdvancePostingProfileRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedger_AdvancePostingProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedger_PostingProfileRelationshipId name="Relationship_VendLedger_PostingProfileRelationshipId">Relationship_VendLedger_PostingProfileRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedger_PostingProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedger_PostingProfileInvoiceRemitRelationshipId name="Relationship_VendLedger_PostingProfileInvoiceRemitRelationshipId">Relationship_VendLedger_PostingProfileInvoiceRemitRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedger_PostingProfileInvoiceRemitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedger_PostingProfileNotesRelationshipId name="Relationship_VendLedger_PostingProfileNotesRelationshipId">Relationship_VendLedger_PostingProfileNotesRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedger_PostingProfileNotesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedger_PostingProfileRemitNotesRelationshipId name="Relationship_VendLedger_PostingProfileRemitNotesRelationshipId">Relationship_VendLedger_PostingProfileRemitNotesRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedger_PostingProfileRemitNotesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedger_PrepaymentPostingProfileRelationshipId name="Relationship_VendLedger_PrepaymentPostingProfileRelationshipId">Relationship_VendLedger_PrepaymentPostingProfileRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedger_PrepaymentPostingProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResCategory_BrokerProcurementCategoryRelationshipId name="Relationship_EcoResCategory_BrokerProcurementCategoryRelationshipId">Relationship_EcoResCategory_BrokerProcurementCategoryRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResCategory_BrokerProcurementCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SettlementWriteOffLedgerDimRelationshipId name="Relationship_SettlementWriteOffLedgerDimRelationshipId">Relationship_SettlementWriteOffLedgerDimRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

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

First included in: Parameter/VendParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/VendWriteOffFinancialReasonsSetup.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Miscellaneous/VendWriteOffFinancialReasonsSetup.cdm.json/VendWriteOffFinancialReasonsSetup</a></td><td><a href="../Miscellaneous/VendWriteOffFinancialReasonsSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SettlementWriteOffJournalNameRelationshipId name="Relationship_SettlementWriteOffJournalNameRelationshipId">Relationship_SettlementWriteOffJournalNameRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

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

### <a href=#Relationship_TaxGroupHeading_PlafondTaxGroup_ITRelationshipId name="Relationship_TaxGroupHeading_PlafondTaxGroup_ITRelationshipId">Relationship_TaxGroupHeading_PlafondTaxGroup_ITRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupHeading_PlafondTaxGroup_ITRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PSNJournalizingDefinitionRelationshipId name="Relationship_PSNJournalizingDefinitionRelationshipId">Relationship_PSNJournalizingDefinitionRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PSNJournalizingDefinitionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/Main/JournalizingDefinition.md" target="_blank">/core/erp/Tables/Finance/AccountingFoundation/Main/JournalizingDefinition.cdm.json/JournalizingDefinition</a></td><td><a href="../../AccountingFoundation/Main/JournalizingDefinition.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/VendParameters (this entity)  

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
