---
title: CustomerParametersEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Customer parameters in AccountsReceivable(CustomerParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustomerParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerDefaultOneTimeAccount](#CustomerDefaultOneTimeAccount)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CustomerIsTaxGroupMandatory](#CustomerIsTaxGroupMandatory)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CustomerMinimumRefund](#CustomerMinimumRefund)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CustomerTaxExemptNumberRequirement](#CustomerTaxExemptNumberRequirement)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CustomerIsConsolidatedInvoiceUsed](#CustomerIsConsolidatedInvoiceUsed)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CustomerIsBillingClassificationUsed](#CustomerIsBillingClassificationUsed)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GeneralLedgerPostingProfile](#GeneralLedgerPostingProfile)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GeneralLedgerPostingAccountForConsumption](#GeneralLedgerPostingAccountForConsumption)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GeneralLedgerPostingAccountForDiscount](#GeneralLedgerPostingAccountForDiscount)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GeneralLedgerPostingAccountForRevenue](#GeneralLedgerPostingAccountForRevenue)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GeneralLedgerDefaultDimensionHierarchy](#GeneralLedgerDefaultDimensionHierarchy)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GeneralLedgerIsAmountDebitCreditShown](#GeneralLedgerIsAmountDebitCreditShown)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GiroAccountPositions](#GiroAccountPositions)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[IsValidationOnBillOfExchangeJournalsEnabled](#IsValidationOnBillOfExchangeJournalsEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[IsDateTreatmentOfBillOfExchangeJournalsEnabled](#IsDateTreatmentOfBillOfExchangeJournalsEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementAutoSettleEnabled](#SettlementAutoSettleEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementMaximumPennyDifference](#SettlementMaximumPennyDifference)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementMaximumOverUnderPayment](#SettlementMaximumOverUnderPayment)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementIsPriorityUsed](#SettlementIsPriorityUsed)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementIsPriorityUsedOnAutoSettlement](#SettlementIsPriorityUsedOnAutoSettlement)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementMarkOpenInvoiceLine](#SettlementMarkOpenInvoiceLine)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementInvoiceLinePrioritizationMethod](#SettlementInvoiceLinePrioritizationMethod)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementSpanBillingCodeAcrossInvoices](#SettlementSpanBillingCodeAcrossInvoices)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementProrationTypeForInvoices](#SettlementProrationTypeForInvoices)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashDiscountAdministration](#CashDiscountAdministration)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashDiscountReasonCode](#CashDiscountReasonCode)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashDiscountIsCreditNotePosted](#CashDiscountIsCreditNotePosted)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashDiscountIsCalculatedForCreditNotes](#CashDiscountIsCalculatedForCreditNotes)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashDiscountIsCalculatedForPartialPayments](#CashDiscountIsCalculatedForPartialPayments)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashDiscountIsCalculatedOnAmountInclSalesTax](#CashDiscountIsCalculatedOnAmountInclSalesTax)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[TotalDiscountIsCalculatedOnPosting](#TotalDiscountIsCalculatedOnPosting)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionLetterCodeUpdate](#CollectionLetterCodeUpdate)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionLetterDisputedTransactionsExcluded](#CollectionLetterDisputedTransactionsExcluded)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionLetterIgnoreCreditTransactionCodes](#CollectionLetterIgnoreCreditTransactionCodes)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionLetterGenerationLevel](#CollectionLetterGenerationLevel)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsAgencyTaxRate](#CollectionsAgencyTaxRate)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsGracePeriodForDuesTransfer](#CollectionsGracePeriodForDuesTransfer)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsIsReferToCollectionAgencyEnabled](#CollectionsIsReferToCollectionAgencyEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsTransactionsToContactEmailTemplateId](#CollectionsTransactionsToContactEmailTemplateId)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsTeamRecId](#CollectionsTeamRecId)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsTeamPartyNumber](#CollectionsTeamPartyNumber)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsTransactionsToSalespersonEmailTemplateId](#CollectionsTransactionsToSalespersonEmailTemplateId)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsStatementToContactEmailTemplateId](#CollectionsStatementToContactEmailTemplateId)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsAgingPeriodDefinition](#CollectionsAgingPeriodDefinition)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsWriteOffLedgerJournalName](#CollectionsWriteOffLedgerJournalName)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsWriteOffIsSalesTaxSeparated](#CollectionsWriteOffIsSalesTaxSeparated)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitDefaultDaysForFirstPrenotification](#DirectDebitDefaultDaysForFirstPrenotification)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitDefaultDaysForRecurringPrenotification](#DirectDebitDefaultDaysForRecurringPrenotification)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitB2BSchemeDefaultDaysForRecurringBankSubmission](#DirectDebitB2BSchemeDefaultDaysForRecurringBankSubmission)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitB2BSchemeDefaultDaysForFirstBankSubmission](#DirectDebitB2BSchemeDefaultDaysForFirstBankSubmission)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitCor1SchemeDefaultDaysForFirstBankSubmission](#DirectDebitCor1SchemeDefaultDaysForFirstBankSubmission)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitCor1SchemeDefaultDaysForRecurringBankSubmission](#DirectDebitCor1SchemeDefaultDaysForRecurringBankSubmission)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitCoreSchemeDefaultDaysForFirstBankSubmission](#DirectDebitCoreSchemeDefaultDaysForFirstBankSubmission)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitCoreSchemeDefaultDaysForRecurringBankSubmission](#DirectDebitCoreSchemeDefaultDaysForRecurringBankSubmission)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DirectDebitMandateDefaultExpirationInMonths](#DirectDebitMandateDefaultExpirationInMonths)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardCostCenterDimensionAttributeRecId](#CreditCardCostCenterDimensionAttributeRecId)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardCostCenterDimensionAttribute](#CreditCardCostCenterDimensionAttribute)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardEstimatedShippingChargeMaximum](#CreditCardEstimatedShippingChargeMaximum)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardEstimatedShippingChargeType](#CreditCardEstimatedShippingChargeType)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardEstimatedShippingChargeValue](#CreditCardEstimatedShippingChargeValue)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardNotes](#CreditCardNotes)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardPostingBankTransactionType](#CreditCardPostingBankTransactionType)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardAuthorization](#CreditCardAuthorization)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardAuthorizationLastNumberOfDays](#CreditCardAuthorizationLastNumberOfDays)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardPostingAccountType](#CreditCardPostingAccountType)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardPostingLedgerDimension](#CreditCardPostingLedgerDimension)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditCardPostingLedgerDimensionDisplayValue](#CreditCardPostingLedgerDimensionDisplayValue)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[InvoiceIsCreditNotePostedAsCorrection](#InvoiceIsCreditNotePostedAsCorrection)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[InvoiceTaxExemptNumberRequirement](#InvoiceTaxExemptNumberRequirement)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[FreeTextInvoiceIsItemTaxGroupMandatory](#FreeTextInvoiceIsItemTaxGroupMandatory)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[FreeTextInvoiceIsProjectEnabled](#FreeTextInvoiceIsProjectEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[FreeTextInvoiceCanEditLedgerAccountForProject](#FreeTextInvoiceCanEditLedgerAccountForProject)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditLimitCheckType](#CreditLimitCheckType)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditLimitIsCheckedOnSalesOrder](#CreditLimitIsCheckedOnSalesOrder)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditLimitIsCheckedOnFreeTextInvoice](#CreditLimitIsCheckedOnFreeTextInvoice)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CreditLimitMessageTypeShownWhenExceeding](#CreditLimitMessageTypeShownWhenExceeding)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[InterestAdjustmentDateToUse](#InterestAdjustmentDateToUse)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[InterestTransactionsToCalculateFor](#InterestTransactionsToCalculateFor)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[InterestMinimumDaysToAllowWaiving](#InterestMinimumDaysToAllowWaiving)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[InterestMaximumDaysAllowedToWaive](#InterestMaximumDaysAllowedToWaive)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[EntryCertificateIsIssuingEnabled](#EntryCertificateIsIssuingEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[EntryCertificateIsManagementEnabled](#EntryCertificateIsManagementEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[InvoicePrintCreditInvoicingLayout](#InvoicePrintCreditInvoicingLayout)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[InvoicePrintPackagingWeight](#InvoicePrintPackagingWeight)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[BillOfExchangePostingProfile](#BillOfExchangePostingProfile)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[BillOfExchangePostingProfileForEndorsed](#BillOfExchangePostingProfileForEndorsed)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[BillOfExchangePostingProfileForProtested](#BillOfExchangePostingProfileForProtested)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[BillOfExchangePostingProfileForRemitCollection](#BillOfExchangePostingProfileForRemitCollection)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[BillOfExchangePostingProfileForRemitDiscount](#BillOfExchangePostingProfileForRemitDiscount)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[PaymentProposalWarnWhenMultipleMethodsOfPayment](#PaymentProposalWarnWhenMultipleMethodsOfPayment)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[PrepaymentPostingProfile](#PrepaymentPostingProfile)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[PrepaymentCalculateTax](#PrepaymentCalculateTax)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[TAMDeductionRequireFullSettle](#TAMDeductionRequireFullSettle)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[TAMDeductionType](#TAMDeductionType)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[TAMRebatePosting](#TAMRebatePosting)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[PriceDetailsEnabledForSalesDocuments](#PriceDetailsEnabledForSalesDocuments)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[ReasonRequirementForCreditNotes](#ReasonRequirementForCreditNotes)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[ReasonRequirementForPaymentCancellation](#ReasonRequirementForPaymentCancellation)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[ReasonRequirementForReturnOrders](#ReasonRequirementForReturnOrders)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[ReasonRequirementForTransactionReversals](#ReasonRequirementForTransactionReversals)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[IsIntegrationWithTaxSystemEnabled](#IsIntegrationWithTaxSystemEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GeneralLedgerEnableCancelPostingProfiles](#GeneralLedgerEnableCancelPostingProfiles)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[GeneralLedgerEnableReturnPostingProfiles](#GeneralLedgerEnableReturnPostingProfiles)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CollectionsWriteOffReasonCode](#CollectionsWriteOffReasonCode)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[EnableDateOfVATRegisterChanging](#EnableDateOfVATRegisterChanging)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[UseFiscalDataFromInvoiceAccount](#UseFiscalDataFromInvoiceAccount)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[PrimaryRelation](#PrimaryRelation)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashFlowTimeBetweenDeliveryDateAndInvoiceDate](#CashFlowTimeBetweenDeliveryDateAndInvoiceDate)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashFlowTermsOfPayment](#CashFlowTermsOfPayment)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashFlowTimeBetweenInvoiceDueDateAndPaymentDate](#CashFlowTimeBetweenInvoiceDueDateAndPaymentDate)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashFlowLiquidityAccountForPayments](#CashFlowLiquidityAccountForPayments)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashFlowLiquidityAccountForPaymentsDisplayValue](#CashFlowLiquidityAccountForPaymentsDisplayValue)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[CashFlowPercentageOfAmountToAllocateToCashFlowForecast](#CashFlowPercentageOfAmountToAllocateToCashFlowForecast)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[EditCashDiscountsWhenDueDateChanged](#EditCashDiscountsWhenDueDateChanged)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DefaultFilterForCustomerTransactions](#DefaultFilterForCustomerTransactions)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementWriteOffEnabled](#SettlementWriteOffEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementWriteOffReasonCode](#SettlementWriteOffReasonCode)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlementWriteOffJournalName](#SettlementWriteOffJournalName)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[ChangeProposalIsEnabled](#ChangeProposalIsEnabled)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[ChangeProposalDataEntityBehavior](#ChangeProposalDataEntityBehavior)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[BypassValidationOfAccountingDistributions](#BypassValidationOfAccountingDistributions)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[DefaultLanguage](#DefaultLanguage)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SuppressDepreciationOfPaymentSection](#SuppressDepreciationOfPaymentSection)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[ReversePrepayment](#ReversePrepayment)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[PrepaymentFactureAutoCreate](#PrepaymentFactureAutoCreate)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[SettlePrepaymentVATType](#SettlePrepaymentVATType)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[Relationship_CreditCardPostingLedgerDimensionCombinationRelationshipId](#Relationship_CreditCardPostingLedgerDimensionCombinationRelationshipId)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[BackingTable_CustParametersRelationshipId](#BackingTable_CustParametersRelationshipId)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustomerParametersEntity.md" target="_blank">AccountsReceivable/CustomerParametersEntity</a>|

### <a href=#CustomerDefaultOneTimeAccount name="CustomerDefaultOneTimeAccount">CustomerDefaultOneTimeAccount</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDefaultOneTimeAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerIsTaxGroupMandatory name="CustomerIsTaxGroupMandatory">CustomerIsTaxGroupMandatory</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerIsTaxGroupMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerMinimumRefund name="CustomerMinimumRefund">CustomerMinimumRefund</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerMinimumRefund attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTaxExemptNumberRequirement name="CustomerTaxExemptNumberRequirement">CustomerTaxExemptNumberRequirement</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTaxExemptNumberRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerIsConsolidatedInvoiceUsed name="CustomerIsConsolidatedInvoiceUsed">CustomerIsConsolidatedInvoiceUsed</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerIsConsolidatedInvoiceUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerIsBillingClassificationUsed name="CustomerIsBillingClassificationUsed">CustomerIsBillingClassificationUsed</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerIsBillingClassificationUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLedgerPostingProfile name="GeneralLedgerPostingProfile">GeneralLedgerPostingProfile</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLedgerPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLedgerPostingAccountForConsumption name="GeneralLedgerPostingAccountForConsumption">GeneralLedgerPostingAccountForConsumption</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLedgerPostingAccountForConsumption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLedgerPostingAccountForDiscount name="GeneralLedgerPostingAccountForDiscount">GeneralLedgerPostingAccountForDiscount</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLedgerPostingAccountForDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLedgerPostingAccountForRevenue name="GeneralLedgerPostingAccountForRevenue">GeneralLedgerPostingAccountForRevenue</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLedgerPostingAccountForRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLedgerDefaultDimensionHierarchy name="GeneralLedgerDefaultDimensionHierarchy">GeneralLedgerDefaultDimensionHierarchy</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLedgerDefaultDimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLedgerIsAmountDebitCreditShown name="GeneralLedgerIsAmountDebitCreditShown">GeneralLedgerIsAmountDebitCreditShown</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLedgerIsAmountDebitCreditShown attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroAccountPositions name="GiroAccountPositions">GiroAccountPositions</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroAccountPositions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsValidationOnBillOfExchangeJournalsEnabled name="IsValidationOnBillOfExchangeJournalsEnabled">IsValidationOnBillOfExchangeJournalsEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsValidationOnBillOfExchangeJournalsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDateTreatmentOfBillOfExchangeJournalsEnabled name="IsDateTreatmentOfBillOfExchangeJournalsEnabled">IsDateTreatmentOfBillOfExchangeJournalsEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDateTreatmentOfBillOfExchangeJournalsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementAutoSettleEnabled name="SettlementAutoSettleEnabled">SettlementAutoSettleEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementAutoSettleEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementMaximumPennyDifference name="SettlementMaximumPennyDifference">SettlementMaximumPennyDifference</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementMaximumPennyDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementMaximumOverUnderPayment name="SettlementMaximumOverUnderPayment">SettlementMaximumOverUnderPayment</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementMaximumOverUnderPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementIsPriorityUsed name="SettlementIsPriorityUsed">SettlementIsPriorityUsed</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementIsPriorityUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementIsPriorityUsedOnAutoSettlement name="SettlementIsPriorityUsedOnAutoSettlement">SettlementIsPriorityUsedOnAutoSettlement</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementIsPriorityUsedOnAutoSettlement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementMarkOpenInvoiceLine name="SettlementMarkOpenInvoiceLine">SettlementMarkOpenInvoiceLine</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementMarkOpenInvoiceLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementInvoiceLinePrioritizationMethod name="SettlementInvoiceLinePrioritizationMethod">SettlementInvoiceLinePrioritizationMethod</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementInvoiceLinePrioritizationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementSpanBillingCodeAcrossInvoices name="SettlementSpanBillingCodeAcrossInvoices">SettlementSpanBillingCodeAcrossInvoices</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementSpanBillingCodeAcrossInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementProrationTypeForInvoices name="SettlementProrationTypeForInvoices">SettlementProrationTypeForInvoices</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementProrationTypeForInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountAdministration name="CashDiscountAdministration">CashDiscountAdministration</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#CashDiscountReasonCode name="CashDiscountReasonCode">CashDiscountReasonCode</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountIsCreditNotePosted name="CashDiscountIsCreditNotePosted">CashDiscountIsCreditNotePosted</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountIsCreditNotePosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountIsCalculatedForCreditNotes name="CashDiscountIsCalculatedForCreditNotes">CashDiscountIsCalculatedForCreditNotes</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountIsCalculatedForCreditNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountIsCalculatedForPartialPayments name="CashDiscountIsCalculatedForPartialPayments">CashDiscountIsCalculatedForPartialPayments</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountIsCalculatedForPartialPayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountIsCalculatedOnAmountInclSalesTax name="CashDiscountIsCalculatedOnAmountInclSalesTax">CashDiscountIsCalculatedOnAmountInclSalesTax</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountIsCalculatedOnAmountInclSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountIsCalculatedOnPosting name="TotalDiscountIsCalculatedOnPosting">TotalDiscountIsCalculatedOnPosting</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountIsCalculatedOnPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionLetterCodeUpdate name="CollectionLetterCodeUpdate">CollectionLetterCodeUpdate</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterCodeUpdate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionLetterDisputedTransactionsExcluded name="CollectionLetterDisputedTransactionsExcluded">CollectionLetterDisputedTransactionsExcluded</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterDisputedTransactionsExcluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionLetterIgnoreCreditTransactionCodes name="CollectionLetterIgnoreCreditTransactionCodes">CollectionLetterIgnoreCreditTransactionCodes</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterIgnoreCreditTransactionCodes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionLetterGenerationLevel name="CollectionLetterGenerationLevel">CollectionLetterGenerationLevel</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterGenerationLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsAgencyTaxRate name="CollectionsAgencyTaxRate">CollectionsAgencyTaxRate</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsAgencyTaxRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsGracePeriodForDuesTransfer name="CollectionsGracePeriodForDuesTransfer">CollectionsGracePeriodForDuesTransfer</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsGracePeriodForDuesTransfer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsIsReferToCollectionAgencyEnabled name="CollectionsIsReferToCollectionAgencyEnabled">CollectionsIsReferToCollectionAgencyEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsIsReferToCollectionAgencyEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsTransactionsToContactEmailTemplateId name="CollectionsTransactionsToContactEmailTemplateId">CollectionsTransactionsToContactEmailTemplateId</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsTransactionsToContactEmailTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsTeamRecId name="CollectionsTeamRecId">CollectionsTeamRecId</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsTeamRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsTeamPartyNumber name="CollectionsTeamPartyNumber">CollectionsTeamPartyNumber</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsTeamPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsTransactionsToSalespersonEmailTemplateId name="CollectionsTransactionsToSalespersonEmailTemplateId">CollectionsTransactionsToSalespersonEmailTemplateId</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsTransactionsToSalespersonEmailTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsStatementToContactEmailTemplateId name="CollectionsStatementToContactEmailTemplateId">CollectionsStatementToContactEmailTemplateId</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsStatementToContactEmailTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsAgingPeriodDefinition name="CollectionsAgingPeriodDefinition">CollectionsAgingPeriodDefinition</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsAgingPeriodDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsWriteOffLedgerJournalName name="CollectionsWriteOffLedgerJournalName">CollectionsWriteOffLedgerJournalName</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsWriteOffLedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsWriteOffIsSalesTaxSeparated name="CollectionsWriteOffIsSalesTaxSeparated">CollectionsWriteOffIsSalesTaxSeparated</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsWriteOffIsSalesTaxSeparated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitDefaultDaysForFirstPrenotification name="DirectDebitDefaultDaysForFirstPrenotification">DirectDebitDefaultDaysForFirstPrenotification</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitDefaultDaysForFirstPrenotification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitDefaultDaysForRecurringPrenotification name="DirectDebitDefaultDaysForRecurringPrenotification">DirectDebitDefaultDaysForRecurringPrenotification</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitDefaultDaysForRecurringPrenotification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitB2BSchemeDefaultDaysForRecurringBankSubmission name="DirectDebitB2BSchemeDefaultDaysForRecurringBankSubmission">DirectDebitB2BSchemeDefaultDaysForRecurringBankSubmission</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitB2BSchemeDefaultDaysForRecurringBankSubmission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitB2BSchemeDefaultDaysForFirstBankSubmission name="DirectDebitB2BSchemeDefaultDaysForFirstBankSubmission">DirectDebitB2BSchemeDefaultDaysForFirstBankSubmission</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitB2BSchemeDefaultDaysForFirstBankSubmission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitCor1SchemeDefaultDaysForFirstBankSubmission name="DirectDebitCor1SchemeDefaultDaysForFirstBankSubmission">DirectDebitCor1SchemeDefaultDaysForFirstBankSubmission</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitCor1SchemeDefaultDaysForFirstBankSubmission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitCor1SchemeDefaultDaysForRecurringBankSubmission name="DirectDebitCor1SchemeDefaultDaysForRecurringBankSubmission">DirectDebitCor1SchemeDefaultDaysForRecurringBankSubmission</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitCor1SchemeDefaultDaysForRecurringBankSubmission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitCoreSchemeDefaultDaysForFirstBankSubmission name="DirectDebitCoreSchemeDefaultDaysForFirstBankSubmission">DirectDebitCoreSchemeDefaultDaysForFirstBankSubmission</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitCoreSchemeDefaultDaysForFirstBankSubmission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitCoreSchemeDefaultDaysForRecurringBankSubmission name="DirectDebitCoreSchemeDefaultDaysForRecurringBankSubmission">DirectDebitCoreSchemeDefaultDaysForRecurringBankSubmission</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitCoreSchemeDefaultDaysForRecurringBankSubmission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitMandateDefaultExpirationInMonths name="DirectDebitMandateDefaultExpirationInMonths">DirectDebitMandateDefaultExpirationInMonths</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitMandateDefaultExpirationInMonths attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardCostCenterDimensionAttributeRecId name="CreditCardCostCenterDimensionAttributeRecId">CreditCardCostCenterDimensionAttributeRecId</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardCostCenterDimensionAttributeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardCostCenterDimensionAttribute name="CreditCardCostCenterDimensionAttribute">CreditCardCostCenterDimensionAttribute</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardCostCenterDimensionAttribute attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardEstimatedShippingChargeMaximum name="CreditCardEstimatedShippingChargeMaximum">CreditCardEstimatedShippingChargeMaximum</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardEstimatedShippingChargeMaximum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardEstimatedShippingChargeType name="CreditCardEstimatedShippingChargeType">CreditCardEstimatedShippingChargeType</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardEstimatedShippingChargeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardEstimatedShippingChargeValue name="CreditCardEstimatedShippingChargeValue">CreditCardEstimatedShippingChargeValue</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardEstimatedShippingChargeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardNotes name="CreditCardNotes">CreditCardNotes</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardPostingBankTransactionType name="CreditCardPostingBankTransactionType">CreditCardPostingBankTransactionType</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPostingBankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardAuthorization name="CreditCardAuthorization">CreditCardAuthorization</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardAuthorization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardAuthorizationLastNumberOfDays name="CreditCardAuthorizationLastNumberOfDays">CreditCardAuthorizationLastNumberOfDays</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardAuthorizationLastNumberOfDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardPostingAccountType name="CreditCardPostingAccountType">CreditCardPostingAccountType</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPostingAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardPostingLedgerDimension name="CreditCardPostingLedgerDimension">CreditCardPostingLedgerDimension</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPostingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardPostingLedgerDimensionDisplayValue name="CreditCardPostingLedgerDimensionDisplayValue">CreditCardPostingLedgerDimensionDisplayValue</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPostingLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceIsCreditNotePostedAsCorrection name="InvoiceIsCreditNotePostedAsCorrection">InvoiceIsCreditNotePostedAsCorrection</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceIsCreditNotePostedAsCorrection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceTaxExemptNumberRequirement name="InvoiceTaxExemptNumberRequirement">InvoiceTaxExemptNumberRequirement</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTaxExemptNumberRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreeTextInvoiceIsItemTaxGroupMandatory name="FreeTextInvoiceIsItemTaxGroupMandatory">FreeTextInvoiceIsItemTaxGroupMandatory</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeTextInvoiceIsItemTaxGroupMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreeTextInvoiceIsProjectEnabled name="FreeTextInvoiceIsProjectEnabled">FreeTextInvoiceIsProjectEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeTextInvoiceIsProjectEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreeTextInvoiceCanEditLedgerAccountForProject name="FreeTextInvoiceCanEditLedgerAccountForProject">FreeTextInvoiceCanEditLedgerAccountForProject</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeTextInvoiceCanEditLedgerAccountForProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimitCheckType name="CreditLimitCheckType">CreditLimitCheckType</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitCheckType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimitIsCheckedOnSalesOrder name="CreditLimitIsCheckedOnSalesOrder">CreditLimitIsCheckedOnSalesOrder</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitIsCheckedOnSalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimitIsCheckedOnFreeTextInvoice name="CreditLimitIsCheckedOnFreeTextInvoice">CreditLimitIsCheckedOnFreeTextInvoice</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitIsCheckedOnFreeTextInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimitMessageTypeShownWhenExceeding name="CreditLimitMessageTypeShownWhenExceeding">CreditLimitMessageTypeShownWhenExceeding</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitMessageTypeShownWhenExceeding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestAdjustmentDateToUse name="InterestAdjustmentDateToUse">InterestAdjustmentDateToUse</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestAdjustmentDateToUse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestTransactionsToCalculateFor name="InterestTransactionsToCalculateFor">InterestTransactionsToCalculateFor</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestTransactionsToCalculateFor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestMinimumDaysToAllowWaiving name="InterestMinimumDaysToAllowWaiving">InterestMinimumDaysToAllowWaiving</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestMinimumDaysToAllowWaiving attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestMaximumDaysAllowedToWaive name="InterestMaximumDaysAllowedToWaive">InterestMaximumDaysAllowedToWaive</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestMaximumDaysAllowedToWaive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryCertificateIsIssuingEnabled name="EntryCertificateIsIssuingEnabled">EntryCertificateIsIssuingEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryCertificateIsIssuingEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryCertificateIsManagementEnabled name="EntryCertificateIsManagementEnabled">EntryCertificateIsManagementEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryCertificateIsManagementEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicePrintCreditInvoicingLayout name="InvoicePrintCreditInvoicingLayout">InvoicePrintCreditInvoicingLayout</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicePrintCreditInvoicingLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicePrintPackagingWeight name="InvoicePrintPackagingWeight">InvoicePrintPackagingWeight</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicePrintPackagingWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfExchangePostingProfile name="BillOfExchangePostingProfile">BillOfExchangePostingProfile</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfExchangePostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfExchangePostingProfileForEndorsed name="BillOfExchangePostingProfileForEndorsed">BillOfExchangePostingProfileForEndorsed</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfExchangePostingProfileForEndorsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfExchangePostingProfileForProtested name="BillOfExchangePostingProfileForProtested">BillOfExchangePostingProfileForProtested</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfExchangePostingProfileForProtested attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfExchangePostingProfileForRemitCollection name="BillOfExchangePostingProfileForRemitCollection">BillOfExchangePostingProfileForRemitCollection</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfExchangePostingProfileForRemitCollection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfExchangePostingProfileForRemitDiscount name="BillOfExchangePostingProfileForRemitDiscount">BillOfExchangePostingProfileForRemitDiscount</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfExchangePostingProfileForRemitDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentProposalWarnWhenMultipleMethodsOfPayment name="PaymentProposalWarnWhenMultipleMethodsOfPayment">PaymentProposalWarnWhenMultipleMethodsOfPayment</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentProposalWarnWhenMultipleMethodsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaymentPostingProfile name="PrepaymentPostingProfile">PrepaymentPostingProfile</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaymentCalculateTax name="PrepaymentCalculateTax">PrepaymentCalculateTax</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentCalculateTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TAMDeductionRequireFullSettle name="TAMDeductionRequireFullSettle">TAMDeductionRequireFullSettle</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TAMDeductionRequireFullSettle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TAMDeductionType name="TAMDeductionType">TAMDeductionType</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TAMDeductionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TAMRebatePosting name="TAMRebatePosting">TAMRebatePosting</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TAMRebatePosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceDetailsEnabledForSalesDocuments name="PriceDetailsEnabledForSalesDocuments">PriceDetailsEnabledForSalesDocuments</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDetailsEnabledForSalesDocuments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonRequirementForCreditNotes name="ReasonRequirementForCreditNotes">ReasonRequirementForCreditNotes</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonRequirementForCreditNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonRequirementForPaymentCancellation name="ReasonRequirementForPaymentCancellation">ReasonRequirementForPaymentCancellation</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonRequirementForPaymentCancellation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonRequirementForReturnOrders name="ReasonRequirementForReturnOrders">ReasonRequirementForReturnOrders</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonRequirementForReturnOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonRequirementForTransactionReversals name="ReasonRequirementForTransactionReversals">ReasonRequirementForTransactionReversals</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonRequirementForTransactionReversals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntegrationWithTaxSystemEnabled name="IsIntegrationWithTaxSystemEnabled">IsIntegrationWithTaxSystemEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntegrationWithTaxSystemEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLedgerEnableCancelPostingProfiles name="GeneralLedgerEnableCancelPostingProfiles">GeneralLedgerEnableCancelPostingProfiles</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLedgerEnableCancelPostingProfiles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLedgerEnableReturnPostingProfiles name="GeneralLedgerEnableReturnPostingProfiles">GeneralLedgerEnableReturnPostingProfiles</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLedgerEnableReturnPostingProfiles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsWriteOffReasonCode name="CollectionsWriteOffReasonCode">CollectionsWriteOffReasonCode</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsWriteOffReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableDateOfVATRegisterChanging name="EnableDateOfVATRegisterChanging">EnableDateOfVATRegisterChanging</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableDateOfVATRegisterChanging attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseFiscalDataFromInvoiceAccount name="UseFiscalDataFromInvoiceAccount">UseFiscalDataFromInvoiceAccount</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#PrimaryRelation name="PrimaryRelation">PrimaryRelation</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowTimeBetweenDeliveryDateAndInvoiceDate name="CashFlowTimeBetweenDeliveryDateAndInvoiceDate">CashFlowTimeBetweenDeliveryDateAndInvoiceDate</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#DefaultFilterForCustomerTransactions name="DefaultFilterForCustomerTransactions">DefaultFilterForCustomerTransactions</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFilterForCustomerTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementWriteOffEnabled name="SettlementWriteOffEnabled">SettlementWriteOffEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#SettlementWriteOffReasonCode name="SettlementWriteOffReasonCode">SettlementWriteOffReasonCode</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#SettlementWriteOffJournalName name="SettlementWriteOffJournalName">SettlementWriteOffJournalName</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#ChangeProposalIsEnabled name="ChangeProposalIsEnabled">ChangeProposalIsEnabled</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#BypassValidationOfAccountingDistributions name="BypassValidationOfAccountingDistributions">BypassValidationOfAccountingDistributions</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#DefaultLanguage name="DefaultLanguage">DefaultLanguage</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLanguage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuppressDepreciationOfPaymentSection name="SuppressDepreciationOfPaymentSection">SuppressDepreciationOfPaymentSection</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuppressDepreciationOfPaymentSection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversePrepayment name="ReversePrepayment">ReversePrepayment</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#PrepaymentFactureAutoCreate name="PrepaymentFactureAutoCreate">PrepaymentFactureAutoCreate</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentFactureAutoCreate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlePrepaymentVATType name="SettlePrepaymentVATType">SettlePrepaymentVATType</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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

### <a href=#Relationship_CreditCardPostingLedgerDimensionCombinationRelationshipId name="Relationship_CreditCardPostingLedgerDimensionCombinationRelationshipId">Relationship_CreditCardPostingLedgerDimensionCombinationRelationshipId</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CreditCardPostingLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CustParametersRelationshipId name="BackingTable_CustParametersRelationshipId">BackingTable_CustParametersRelationshipId</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Parameter/CustParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Parameter/CustParameters.cdm.json/CustParameters</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Parameter/CustParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustomerParametersEntity (this entity)  

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
