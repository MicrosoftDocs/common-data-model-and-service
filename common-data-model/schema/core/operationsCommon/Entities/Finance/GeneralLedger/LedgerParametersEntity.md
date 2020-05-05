---
title: LedgerParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Ledger parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DoNotUseErrorAccount](#DoNotUseErrorAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RequireContinuousNumberSequences](#RequireContinuousNumberSequences)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RequireJournalizingOnFiscalPeriodClose](#RequireJournalizingOnFiscalPeriodClose)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[DuplicateVoucherOption](#DuplicateVoucherOption)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[DeletePreviousClosingTransactionsDuringFiscalYearClose](#DeletePreviousClosingTransactionsDuringFiscalYearClose)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[DimensionValuesUsedForSummaryAccountOption](#DimensionValuesUsedForSummaryAccountOption)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UseBudgetAppropriation](#UseBudgetAppropriation)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UseBudgetReservationProcess](#UseBudgetReservationProcess)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UseEncumbranceProcess](#UseEncumbranceProcess)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UsePreencumbranceProcess](#UsePreencumbranceProcess)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[StartJournalizeReportOnPageOne](#StartJournalizeReportOnPageOne)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[OrderJournalizingReportByCreatedDateAndTime](#OrderJournalizingReportByCreatedDateAndTime)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UsePostingDefinitions](#UsePostingDefinitions)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[MaximumNumberOfOpenFiscalYears](#MaximumNumberOfOpenFiscalYears)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[MaximumPennyDifferenceInAccountingCurrency](#MaximumPennyDifferenceInAccountingCurrency)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[MaximumPennyDifferenceInReportingCurrency](#MaximumPennyDifferenceInReportingCurrency)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UploadJournalName](#UploadJournalName)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[VoucherNumberRequiredForFiscalYearClose](#VoucherNumberRequiredForFiscalYearClose)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[SkipBudgetTransactionsForFiscalYearClose](#SkipBudgetTransactionsForFiscalYearClose)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[CreateClosingTransactionsDuringFiscalYearClose](#CreateClosingTransactionsDuringFiscalYearClose)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UseFundDimensionToCarryForwardPurchaseOrders](#UseFundDimensionToCarryForwardPurchaseOrders)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ReverseOppositeSignAmounts](#ReverseOppositeSignAmounts)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[CreateReversalsAsCorrections](#CreateReversalsAsCorrections)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[SetFiscalYearToClosedDuringFiscalYearClose](#SetFiscalYearToClosedDuringFiscalYearClose)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[Key](#Key)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[InflationCorrectionAccountDisplayValue](#InflationCorrectionAccountDisplayValue)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[InflationCorrectionAccount](#InflationCorrectionAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[TAccount](#TAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[InflationOffsetAccount](#InflationOffsetAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[InflationOffsetAccountDisplayValue](#InflationOffsetAccountDisplayValue)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[WithholdingTaxMinimumInvoiceAmount](#WithholdingTaxMinimumInvoiceAmount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMappingMexicanBalanceSheet](#ERFormatMappingMexicanBalanceSheet)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMexicanBalanceSheet](#ERFormatMexicanBalanceSheet)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERSolutionMexicanBalanceSheet](#ERSolutionMexicanBalanceSheet)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERProviderMexicanBalanceSheet](#ERProviderMexicanBalanceSheet)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMappingMexicanChartOfAccount](#ERFormatMappingMexicanChartOfAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMexicanChartOfAccount](#ERFormatMexicanChartOfAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERSolutionMexicanChartOfAccount](#ERSolutionMexicanChartOfAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERProviderMexicanChartOfAccount](#ERProviderMexicanChartOfAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMappingMexicanLedgerEntries](#ERFormatMappingMexicanLedgerEntries)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMexicanLedgerEntries](#ERFormatMexicanLedgerEntries)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERSolutionMexicanLedgerEntries](#ERSolutionMexicanLedgerEntries)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERProviderMexicanLedgerEntries](#ERProviderMexicanLedgerEntries)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMappingMexicanAuxiliaryLedger](#ERFormatMappingMexicanAuxiliaryLedger)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMexicanAuxiliaryLedger](#ERFormatMexicanAuxiliaryLedger)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERSolutionMexicanAuxiliaryLedger](#ERSolutionMexicanAuxiliaryLedger)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERProviderMexicanAuxiliaryLedger](#ERProviderMexicanAuxiliaryLedger)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[LimitedOpenFiscalPeriods](#LimitedOpenFiscalPeriods)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ShowAmountDebitCredit](#ShowAmountDebitCredit)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[CISFormatMapping](#CISFormatMapping)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[Financialstatements](#Financialstatements)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[Charges](#Charges)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ZakatExpenseAccount](#ZakatExpenseAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[IsZakatEnabled](#IsZakatEnabled)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ZakatProvisionAccount](#ZakatProvisionAccount)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableSelfApproval](#EnableSelfApproval)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableExtendedCustVendBalanceInquiry](#EnableExtendedCustVendBalanceInquiry)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableShowAmountInDebitCreditColumn](#EnableShowAmountInDebitCreditColumn)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableJournalApprovalStatus](#EnableJournalApprovalStatus)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableCommonAccountType](#EnableCommonAccountType)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableChineseVoucherSystem](#EnableChineseVoucherSystem)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableExcludeUnusedAccounts](#EnableExcludeUnusedAccounts)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableExtendedLedgerInquiry](#EnableExtendedLedgerInquiry)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableAlandTaxRequirements](#EnableAlandTaxRequirements)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[EnableReverseCharge](#EnableReverseCharge)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ReverseChargePurchTaxGroup](#ReverseChargePurchTaxGroup)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ReverseChargeSalesTaxGroup](#ReverseChargeSalesTaxGroup)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ReverseChargeContactName](#ReverseChargeContactName)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ReverseChargeContactPhone](#ReverseChargeContactPhone)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ERFormatMappingSalesListExport_UK](#ERFormatMappingSalesListExport_UK)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UseCorrespondingMechanism](#UseCorrespondingMechanism)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[SalesPurchaseBookDateNumberDelimiter](#SalesPurchaseBookDateNumberDelimiter)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[FactureOperationCodeDelimiter](#FactureOperationCodeDelimiter)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[UsePrecalculatedData](#UsePrecalculatedData)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[AdvanceRevaluationCancelation](#AdvanceRevaluationCancelation)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[AllowMultipleTransactionsWithinOneVoucher](#AllowMultipleTransactionsWithinOneVoucher)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ProcessSourceDocumentLinesInParallel](#ProcessSourceDocumentLinesInParallel)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[AdvancedLedgerSettlement](#AdvancedLedgerSettlement)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RDeferralsPostingProfile](#RDeferralsPostingProfile)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RDeferralsRoundOffOperation](#RDeferralsRoundOffOperation)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RDeferralsBaseValueModel](#RDeferralsBaseValueModel)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[VATRefundingMethod](#VATRefundingMethod)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[ExchRateCalculationMethod](#ExchRateCalculationMethod)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[PSNLedgerInterestDistributionEnable](#PSNLedgerInterestDistributionEnable)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[PSNLedgerInterestDistributionFundingSourceRules](#PSNLedgerInterestDistributionFundingSourceRules)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[PSNLedgerInterestDistributionPostALE](#PSNLedgerInterestDistributionPostALE)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[PSNPriorYearCorrection](#PSNPriorYearCorrection)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[PSNCashControlDimensionHierarchy](#PSNCashControlDimensionHierarchy)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[PSNCashControlOverrideGroup](#PSNCashControlOverrideGroup)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[PSNCashControlDimensionHierarchyName](#PSNCashControlDimensionHierarchyName)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[PSNCashControlOverrideGroupId](#PSNCashControlOverrideGroupId)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RevRecDisableContractTerms](#RevRecDisableContractTerms)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RevRecEnableReallocation](#RevRecEnableReallocation)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RevRecHeaderDiscounts](#RevRecHeaderDiscounts)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RevRecJournalNameId](#RevRecJournalNameId)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[RevRecPostToAccountsReceivable](#RevRecPostToAccountsReceivable)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[BackingTable_LedgerParametersRelationshipId](#BackingTable_LedgerParametersRelationshipId)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerParametersEntity.md" target="_blank">GeneralLedger/LedgerParametersEntity</a>|

### <a href=#DoNotUseErrorAccount name="DoNotUseErrorAccount">DoNotUseErrorAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoNotUseErrorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireContinuousNumberSequences name="RequireContinuousNumberSequences">RequireContinuousNumberSequences</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireContinuousNumberSequences attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireJournalizingOnFiscalPeriodClose name="RequireJournalizingOnFiscalPeriodClose">RequireJournalizingOnFiscalPeriodClose</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireJournalizingOnFiscalPeriodClose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DuplicateVoucherOption name="DuplicateVoucherOption">DuplicateVoucherOption</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DuplicateVoucherOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeletePreviousClosingTransactionsDuringFiscalYearClose name="DeletePreviousClosingTransactionsDuringFiscalYearClose">DeletePreviousClosingTransactionsDuringFiscalYearClose</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeletePreviousClosingTransactionsDuringFiscalYearClose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValuesUsedForSummaryAccountOption name="DimensionValuesUsedForSummaryAccountOption">DimensionValuesUsedForSummaryAccountOption</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValuesUsedForSummaryAccountOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseBudgetAppropriation name="UseBudgetAppropriation">UseBudgetAppropriation</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseBudgetAppropriation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseBudgetReservationProcess name="UseBudgetReservationProcess">UseBudgetReservationProcess</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseBudgetReservationProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseEncumbranceProcess name="UseEncumbranceProcess">UseEncumbranceProcess</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseEncumbranceProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UsePreencumbranceProcess name="UsePreencumbranceProcess">UsePreencumbranceProcess</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsePreencumbranceProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartJournalizeReportOnPageOne name="StartJournalizeReportOnPageOne">StartJournalizeReportOnPageOne</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartJournalizeReportOnPageOne attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderJournalizingReportByCreatedDateAndTime name="OrderJournalizingReportByCreatedDateAndTime">OrderJournalizingReportByCreatedDateAndTime</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderJournalizingReportByCreatedDateAndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UsePostingDefinitions name="UsePostingDefinitions">UsePostingDefinitions</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsePostingDefinitions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumNumberOfOpenFiscalYears name="MaximumNumberOfOpenFiscalYears">MaximumNumberOfOpenFiscalYears</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumNumberOfOpenFiscalYears attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumPennyDifferenceInAccountingCurrency name="MaximumPennyDifferenceInAccountingCurrency">MaximumPennyDifferenceInAccountingCurrency</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumPennyDifferenceInAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumPennyDifferenceInReportingCurrency name="MaximumPennyDifferenceInReportingCurrency">MaximumPennyDifferenceInReportingCurrency</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumPennyDifferenceInReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UploadJournalName name="UploadJournalName">UploadJournalName</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UploadJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumberRequiredForFiscalYearClose name="VoucherNumberRequiredForFiscalYearClose">VoucherNumberRequiredForFiscalYearClose</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumberRequiredForFiscalYearClose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipBudgetTransactionsForFiscalYearClose name="SkipBudgetTransactionsForFiscalYearClose">SkipBudgetTransactionsForFiscalYearClose</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipBudgetTransactionsForFiscalYearClose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateClosingTransactionsDuringFiscalYearClose name="CreateClosingTransactionsDuringFiscalYearClose">CreateClosingTransactionsDuringFiscalYearClose</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateClosingTransactionsDuringFiscalYearClose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseFundDimensionToCarryForwardPurchaseOrders name="UseFundDimensionToCarryForwardPurchaseOrders">UseFundDimensionToCarryForwardPurchaseOrders</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFundDimensionToCarryForwardPurchaseOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReverseOppositeSignAmounts name="ReverseOppositeSignAmounts">ReverseOppositeSignAmounts</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseOppositeSignAmounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateReversalsAsCorrections name="CreateReversalsAsCorrections">CreateReversalsAsCorrections</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateReversalsAsCorrections attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetFiscalYearToClosedDuringFiscalYearClose name="SetFiscalYearToClosedDuringFiscalYearClose">SetFiscalYearToClosedDuringFiscalYearClose</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetFiscalYearToClosedDuringFiscalYearClose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InflationCorrectionAccountDisplayValue name="InflationCorrectionAccountDisplayValue">InflationCorrectionAccountDisplayValue</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account for inflation correction (REPOMO)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InflationCorrectionAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account for inflation correction (REPOMO)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InflationCorrectionAccount name="InflationCorrectionAccount">InflationCorrectionAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InflationCorrectionAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TAccount name="TAccount">TAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InflationOffsetAccount name="InflationOffsetAccount">InflationOffsetAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InflationOffsetAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InflationOffsetAccountDisplayValue name="InflationOffsetAccountDisplayValue">InflationOffsetAccountDisplayValue</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inflation offset account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InflationOffsetAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inflation offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxMinimumInvoiceAmount name="WithholdingTaxMinimumInvoiceAmount">WithholdingTaxMinimumInvoiceAmount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxMinimumInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMappingMexicanBalanceSheet name="ERFormatMappingMexicanBalanceSheet">ERFormatMappingMexicanBalanceSheet</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting trial balance mapping</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingMexicanBalanceSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting trial balance mapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMexicanBalanceSheet name="ERFormatMexicanBalanceSheet">ERFormatMexicanBalanceSheet</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting trial balance format name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMexicanBalanceSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting trial balance format name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERSolutionMexicanBalanceSheet name="ERSolutionMexicanBalanceSheet">ERSolutionMexicanBalanceSheet</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting trial balance solution name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERSolutionMexicanBalanceSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting trial balance solution name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERProviderMexicanBalanceSheet name="ERProviderMexicanBalanceSheet">ERProviderMexicanBalanceSheet</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting trial balance vendor url</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERProviderMexicanBalanceSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting trial balance vendor url</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMappingMexicanChartOfAccount name="ERFormatMappingMexicanChartOfAccount">ERFormatMappingMexicanChartOfAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting chart of accounts mapping</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingMexicanChartOfAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting chart of accounts mapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMexicanChartOfAccount name="ERFormatMexicanChartOfAccount">ERFormatMexicanChartOfAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting chart of accounts format name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMexicanChartOfAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting chart of accounts format name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERSolutionMexicanChartOfAccount name="ERSolutionMexicanChartOfAccount">ERSolutionMexicanChartOfAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting chart of accounts solution name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERSolutionMexicanChartOfAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting chart of accounts solution name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERProviderMexicanChartOfAccount name="ERProviderMexicanChartOfAccount">ERProviderMexicanChartOfAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting chart of accounts vendor url</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERProviderMexicanChartOfAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting chart of accounts vendor url</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMappingMexicanLedgerEntries name="ERFormatMappingMexicanLedgerEntries">ERFormatMappingMexicanLedgerEntries</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting ledger entries mapping</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingMexicanLedgerEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting ledger entries mapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMexicanLedgerEntries name="ERFormatMexicanLedgerEntries">ERFormatMexicanLedgerEntries</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting ledger entries format name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMexicanLedgerEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting ledger entries format name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERSolutionMexicanLedgerEntries name="ERSolutionMexicanLedgerEntries">ERSolutionMexicanLedgerEntries</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting ledger entries solution name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERSolutionMexicanLedgerEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting ledger entries solution name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERProviderMexicanLedgerEntries name="ERProviderMexicanLedgerEntries">ERProviderMexicanLedgerEntries</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting ledger entries vendor url</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERProviderMexicanLedgerEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting ledger entries vendor url</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMappingMexicanAuxiliaryLedger name="ERFormatMappingMexicanAuxiliaryLedger">ERFormatMappingMexicanAuxiliaryLedger</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting auxiliary ledger mapping</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingMexicanAuxiliaryLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting auxiliary ledger mapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMexicanAuxiliaryLedger name="ERFormatMexicanAuxiliaryLedger">ERFormatMexicanAuxiliaryLedger</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting auxiliary ledger format name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMexicanAuxiliaryLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting auxiliary ledger format name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERSolutionMexicanAuxiliaryLedger name="ERSolutionMexicanAuxiliaryLedger">ERSolutionMexicanAuxiliaryLedger</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting auxiliary ledger solution name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERSolutionMexicanAuxiliaryLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting auxiliary ledger solution name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERProviderMexicanAuxiliaryLedger name="ERProviderMexicanAuxiliaryLedger">ERProviderMexicanAuxiliaryLedger</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic reporting auxiliary ledger vendor url</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERProviderMexicanAuxiliaryLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic reporting auxiliary ledger vendor url</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LimitedOpenFiscalPeriods name="LimitedOpenFiscalPeriods">LimitedOpenFiscalPeriods</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitedOpenFiscalPeriods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowAmountDebitCredit name="ShowAmountDebitCredit">ShowAmountDebitCredit</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAmountDebitCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CISFormatMapping name="CISFormatMapping">CISFormatMapping</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Export format configuration</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CISFormatMapping attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Export format configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Financialstatements name="Financialstatements">Financialstatements</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Financialstatements attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Charges name="Charges">Charges</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Charges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatExpenseAccount name="ZakatExpenseAccount">ZakatExpenseAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatExpenseAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsZakatEnabled name="IsZakatEnabled">IsZakatEnabled</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsZakatEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatProvisionAccount name="ZakatProvisionAccount">ZakatProvisionAccount</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatProvisionAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableSelfApproval name="EnableSelfApproval">EnableSelfApproval</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableSelfApproval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableExtendedCustVendBalanceInquiry name="EnableExtendedCustVendBalanceInquiry">EnableExtendedCustVendBalanceInquiry</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableExtendedCustVendBalanceInquiry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableShowAmountInDebitCreditColumn name="EnableShowAmountInDebitCreditColumn">EnableShowAmountInDebitCreditColumn</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableShowAmountInDebitCreditColumn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableJournalApprovalStatus name="EnableJournalApprovalStatus">EnableJournalApprovalStatus</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableJournalApprovalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableCommonAccountType name="EnableCommonAccountType">EnableCommonAccountType</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableCommonAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableChineseVoucherSystem name="EnableChineseVoucherSystem">EnableChineseVoucherSystem</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableChineseVoucherSystem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableExcludeUnusedAccounts name="EnableExcludeUnusedAccounts">EnableExcludeUnusedAccounts</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableExcludeUnusedAccounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableExtendedLedgerInquiry name="EnableExtendedLedgerInquiry">EnableExtendedLedgerInquiry</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableExtendedLedgerInquiry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableAlandTaxRequirements name="EnableAlandTaxRequirements">EnableAlandTaxRequirements</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAlandTaxRequirements attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableReverseCharge name="EnableReverseCharge">EnableReverseCharge</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableReverseCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReverseChargePurchTaxGroup name="ReverseChargePurchTaxGroup">ReverseChargePurchTaxGroup</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseChargePurchTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReverseChargeSalesTaxGroup name="ReverseChargeSalesTaxGroup">ReverseChargeSalesTaxGroup</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseChargeSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReverseChargeContactName name="ReverseChargeContactName">ReverseChargeContactName</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseChargeContactName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReverseChargeContactPhone name="ReverseChargeContactPhone">ReverseChargeContactPhone</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseChargeContactPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMappingSalesListExport_UK name="ERFormatMappingSalesListExport_UK">ERFormatMappingSalesListExport_UK</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingSalesListExport_UK attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseCorrespondingMechanism name="UseCorrespondingMechanism">UseCorrespondingMechanism</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCorrespondingMechanism attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPurchaseBookDateNumberDelimiter name="SalesPurchaseBookDateNumberDelimiter">SalesPurchaseBookDateNumberDelimiter</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPurchaseBookDateNumberDelimiter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactureOperationCodeDelimiter name="FactureOperationCodeDelimiter">FactureOperationCodeDelimiter</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureOperationCodeDelimiter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UsePrecalculatedData name="UsePrecalculatedData">UsePrecalculatedData</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsePrecalculatedData attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceRevaluationCancelation name="AdvanceRevaluationCancelation">AdvanceRevaluationCancelation</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceRevaluationCancelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowMultipleTransactionsWithinOneVoucher name="AllowMultipleTransactionsWithinOneVoucher">AllowMultipleTransactionsWithinOneVoucher</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMultipleTransactionsWithinOneVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessSourceDocumentLinesInParallel name="ProcessSourceDocumentLinesInParallel">ProcessSourceDocumentLinesInParallel</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessSourceDocumentLinesInParallel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvancedLedgerSettlement name="AdvancedLedgerSettlement">AdvancedLedgerSettlement</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedLedgerSettlement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RDeferralsPostingProfile name="RDeferralsPostingProfile">RDeferralsPostingProfile</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RDeferralsPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RDeferralsRoundOffOperation name="RDeferralsRoundOffOperation">RDeferralsRoundOffOperation</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RDeferralsRoundOffOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RDeferralsBaseValueModel name="RDeferralsBaseValueModel">RDeferralsBaseValueModel</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RDeferralsBaseValueModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATRefundingMethod name="VATRefundingMethod">VATRefundingMethod</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATRefundingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRateCalculationMethod name="ExchRateCalculationMethod">ExchRateCalculationMethod</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNLedgerInterestDistributionEnable name="PSNLedgerInterestDistributionEnable">PSNLedgerInterestDistributionEnable</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNLedgerInterestDistributionEnable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNLedgerInterestDistributionFundingSourceRules name="PSNLedgerInterestDistributionFundingSourceRules">PSNLedgerInterestDistributionFundingSourceRules</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNLedgerInterestDistributionFundingSourceRules attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNLedgerInterestDistributionPostALE name="PSNLedgerInterestDistributionPostALE">PSNLedgerInterestDistributionPostALE</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNLedgerInterestDistributionPostALE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNPriorYearCorrection name="PSNPriorYearCorrection">PSNPriorYearCorrection</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNPriorYearCorrection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNCashControlDimensionHierarchy name="PSNCashControlDimensionHierarchy">PSNCashControlDimensionHierarchy</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNCashControlDimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNCashControlOverrideGroup name="PSNCashControlOverrideGroup">PSNCashControlOverrideGroup</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNCashControlOverrideGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNCashControlDimensionHierarchyName name="PSNCashControlDimensionHierarchyName">PSNCashControlDimensionHierarchyName</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension set</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNCashControlDimensionHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension set</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNCashControlOverrideGroupId name="PSNCashControlOverrideGroupId">PSNCashControlOverrideGroupId</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNCashControlOverrideGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecDisableContractTerms name="RevRecDisableContractTerms">RevRecDisableContractTerms</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecDisableContractTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecEnableReallocation name="RevRecEnableReallocation">RevRecEnableReallocation</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecEnableReallocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecHeaderDiscounts name="RevRecHeaderDiscounts">RevRecHeaderDiscounts</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecHeaderDiscounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecJournalNameId name="RevRecJournalNameId">RevRecJournalNameId</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecPostToAccountsReceivable name="RevRecPostToAccountsReceivable">RevRecPostToAccountsReceivable</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecPostToAccountsReceivable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerParametersRelationshipId name="BackingTable_LedgerParametersRelationshipId">BackingTable_LedgerParametersRelationshipId</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Parameter/LedgerParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Parameter/LedgerParameters.cdm.json/LedgerParameters</a></td><td><a href="../../../Tables/Finance/Ledger/Parameter/LedgerParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerParametersEntity (this entity)  

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
