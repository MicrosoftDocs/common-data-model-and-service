---
title: LedgerParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# LedgerParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Parameter/LedgerParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[AbortErrorAccount](#AbortErrorAccount)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[AcknowledgementDate_IT](#AcknowledgementDate_IT)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[AdvanceAdjustment_W](#AdvanceAdjustment_W)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[AllowALELedgerDimensionEdit_PSN](#AllowALELedgerDimensionEdit_PSN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[BarSelfApproval_CN](#BarSelfApproval_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[BookDateNumDelimiter_RU](#BookDateNumDelimiter_RU)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[CheckContinuous](#CheckContinuous)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[CheckJournalizing](#CheckJournalizing)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[CheckVoucher](#CheckVoucher)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ChineseVoucher_CN](#ChineseVoucher_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[CommonAccountType_CN](#CommonAccountType_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[CopyReverse_CN](#CopyReverse_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Correspondence_RU](#Correspondence_RU)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[CustVendBalanceInquiry_CN](#CustVendBalanceInquiry_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[DeleteOpening](#DeleteOpening)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[DimensionValuesUsedForSummaryAccount](#DimensionValuesUsedForSummaryAccount)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ExchRateDiffCalcType_W](#ExchRateDiffCalcType_W)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ExcludeUnusedAccounts_CN](#ExcludeUnusedAccounts_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ExpenseAccount_SA](#ExpenseAccount_SA)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[FactureOperationTypeCodesDelimiter_RU](#FactureOperationTypeCodesDelimiter_RU)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Financialstatements_IN](#Financialstatements_IN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[IsBudgetAppropriationEnabled](#IsBudgetAppropriationEnabled)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[IsEncumbranceProcessEnabled](#IsEncumbranceProcessEnabled)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[IsPreEncumbranceProcessEnabled](#IsPreEncumbranceProcessEnabled)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[IsZakatEnabled_SA](#IsZakatEnabled_SA)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[JournalApproval_CN](#JournalApproval_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[JournalizePageOrder](#JournalizePageOrder)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[JournalizeSortorder](#JournalizeSortorder)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[JournalizingDefinitionEnableValue](#JournalizingDefinitionEnableValue)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[key](#key)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[LedgerInquiry_CN](#LedgerInquiry_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[LedgerYearEndClosingEnabled_PSN](#LedgerYearEndClosingEnabled_PSN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[LimitedOpenFiscalPeriods](#LimitedOpenFiscalPeriods)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[MaxRoundingDifferenceMST](#MaxRoundingDifferenceMST)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[MaxRoundingDifferenceMSTSecond](#MaxRoundingDifferenceMSTSecond)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[MCRUploadJournalName](#MCRUploadJournalName)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Miscellaneouscharges_IN](#Miscellaneouscharges_IN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[OpeningVoucher](#OpeningVoucher)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[OpeningWithoutBudget](#OpeningWithoutBudget)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PeriodClosingPosting](#PeriodClosingPosting)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PrecalcDataActual_RU](#PrecalcDataActual_RU)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ProvisionAccount_SA](#ProvisionAccount_SA)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PurchYearEndEnabled_PSN](#PurchYearEndEnabled_PSN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ReExpressionMainAccount_MX](#ReExpressionMainAccount_MX)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[RepomoMainAccount_MX](#RepomoMainAccount_MX)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ReverseOppositeSignAmounts](#ReverseOppositeSignAmounts)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ShowAmountDebitCredit_CN](#ShowAmountDebitCredit_CN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[TAccount_JP](#TAccount_JP)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[TaxImportAlandTax](#TaxImportAlandTax)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[TaxWithholdMinInvoice_TH](#TaxWithholdMinInvoice_TH)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[TransactionReversalCorrection](#TransactionReversalCorrection)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[TransactionReversalNumberOfBatchTasks](#TransactionReversalNumberOfBatchTasks)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[TransactionReversalNumberLinesToForceBatch](#TransactionReversalNumberLinesToForceBatch)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[TransactionReversalNumberOfHoursBeforeReRunProcessingStatus](#TransactionReversalNumberOfHoursBeforeReRunProcessingStatus)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[UsePrecalcData_RU](#UsePrecalcData_RU)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[VATRefundingMethod_RU](#VATRefundingMethod_RU)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[YearClosed](#YearClosed)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[IsSummarizeSettlementEnabled_PSN](#IsSummarizeSettlementEnabled_PSN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[AdvancedLedgerSettlement](#AdvancedLedgerSettlement)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[UniqueCertificationERFormatMappingId_IT](#UniqueCertificationERFormatMappingId_IT)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ERFormatMappingCIS_GB](#ERFormatMappingCIS_GB)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ELedgerAccountingAuxiliaryLedgerFormatMapping](#ELedgerAccountingAuxiliaryLedgerFormatMapping)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ELedgerAccountingLedgerEntriesFormatMapping](#ELedgerAccountingLedgerEntriesFormatMapping)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ELedgerAccountingChartOfAccountsFormatMapping](#ELedgerAccountingChartOfAccountsFormatMapping)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[ELedgerAccountingBalanceSheetFormatMapping](#ELedgerAccountingBalanceSheetFormatMapping)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[SIIIncludeNegativeTax_ES](#SIIIncludeNegativeTax_ES)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[IsBudgetReservationEnabled_PSN](#IsBudgetReservationEnabled_PSN)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[AllowMultipleTransactionsWithinOneVoucher](#AllowMultipleTransactionsWithinOneVoucher)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PSNPriorYearCorrection](#PSNPriorYearCorrection)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PSNLedgerInterestDistributionFundingSourceRules](#PSNLedgerInterestDistributionFundingSourceRules)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PSNLedgerInterestDistributionPostALE](#PSNLedgerInterestDistributionPostALE)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PSNLedgerInterestDistributionEnable](#PSNLedgerInterestDistributionEnable)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PSNCashControlDimensionHierarchy](#PSNCashControlDimensionHierarchy)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[PSNCashControlOverrideGroup](#PSNCashControlOverrideGroup)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[RevRecJournalNameId](#RevRecJournalNameId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[RevRecEnableReallocation](#RevRecEnableReallocation)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[RevRecDisableContractTerms](#RevRecDisableContractTerms)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[RevRecHeaderDiscounts](#RevRecHeaderDiscounts)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[RevRecPostToAccountsReceivable](#RevRecPostToAccountsReceivable)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[BillSchRevRecAccruedRevenueJournalNameId](#BillSchRevRecAccruedRevenueJournalNameId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Relationship_ExpenseAccount_SARelationshipId](#Relationship_ExpenseAccount_SARelationshipId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Relationship_ProvisionAccount_SARelationshipId](#Relationship_ProvisionAccount_SARelationshipId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Relationship_ReExpressionMainAccount_MXRelationshipId](#Relationship_ReExpressionMainAccount_MXRelationshipId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Relationship_RepomoMainAccount_MXRelationshipId](#Relationship_RepomoMainAccount_MXRelationshipId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Relationship_PSNCashControlDimensionHierarchyRelationshipId](#Relationship_PSNCashControlDimensionHierarchyRelationshipId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Relationship_PSNCashControlOverrideGroupRelationshipId](#Relationship_PSNCashControlOverrideGroupRelationshipId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Relationship_RevRecLedgerJournalNameRelationshipId](#Relationship_RevRecLedgerJournalNameRelationshipId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerParameters.md" target="_blank">Parameter/LedgerParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AbortErrorAccount name="AbortErrorAccount">AbortErrorAccount</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbortErrorAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AcknowledgementDate_IT name="AcknowledgementDate_IT">AcknowledgementDate_IT</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcknowledgementDate_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdvanceAdjustment_W name="AdvanceAdjustment_W">AdvanceAdjustment_W</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceAdjustment_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowALELedgerDimensionEdit_PSN name="AllowALELedgerDimensionEdit_PSN">AllowALELedgerDimensionEdit_PSN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowALELedgerDimensionEdit_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BarSelfApproval_CN name="BarSelfApproval_CN">BarSelfApproval_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarSelfApproval_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BookDateNumDelimiter_RU name="BookDateNumDelimiter_RU">BookDateNumDelimiter_RU</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookDateNumDelimiter_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckContinuous name="CheckContinuous">CheckContinuous</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckContinuous attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckJournalizing name="CheckJournalizing">CheckJournalizing</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckJournalizing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckVoucher name="CheckVoucher">CheckVoucher</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckVoucher attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ChineseVoucher_CN name="ChineseVoucher_CN">ChineseVoucher_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChineseVoucher_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CommonAccountType_CN name="CommonAccountType_CN">CommonAccountType_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommonAccountType_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CopyReverse_CN name="CopyReverse_CN">CopyReverse_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopyReverse_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Correspondence_RU name="Correspondence_RU">Correspondence_RU</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Correspondence_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustVendBalanceInquiry_CN name="CustVendBalanceInquiry_CN">CustVendBalanceInquiry_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendBalanceInquiry_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeleteOpening name="DeleteOpening">DeleteOpening</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteOpening attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DimensionValuesUsedForSummaryAccount name="DimensionValuesUsedForSummaryAccount">DimensionValuesUsedForSummaryAccount</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValuesUsedForSummaryAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRateDiffCalcType_W name="ExchRateDiffCalcType_W">ExchRateDiffCalcType_W</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateDiffCalcType_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExcludeUnusedAccounts_CN name="ExcludeUnusedAccounts_CN">ExcludeUnusedAccounts_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeUnusedAccounts_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExpenseAccount_SA name="ExpenseAccount_SA">ExpenseAccount_SA</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseAccount_SA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FactureOperationTypeCodesDelimiter_RU name="FactureOperationTypeCodesDelimiter_RU">FactureOperationTypeCodesDelimiter_RU</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureOperationTypeCodesDelimiter_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Financialstatements_IN name="Financialstatements_IN">Financialstatements_IN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Financialstatements_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsBudgetAppropriationEnabled name="IsBudgetAppropriationEnabled">IsBudgetAppropriationEnabled</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBudgetAppropriationEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsEncumbranceProcessEnabled name="IsEncumbranceProcessEnabled">IsEncumbranceProcessEnabled</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEncumbranceProcessEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsPreEncumbranceProcessEnabled name="IsPreEncumbranceProcessEnabled">IsPreEncumbranceProcessEnabled</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPreEncumbranceProcessEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsZakatEnabled_SA name="IsZakatEnabled_SA">IsZakatEnabled_SA</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsZakatEnabled_SA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalApproval_CN name="JournalApproval_CN">JournalApproval_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalApproval_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalizePageOrder name="JournalizePageOrder">JournalizePageOrder</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizePageOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalizeSortorder name="JournalizeSortorder">JournalizeSortorder</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizeSortorder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalizingDefinitionEnableValue name="JournalizingDefinitionEnableValue">JournalizingDefinitionEnableValue</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizingDefinitionEnableValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#key name="key">key</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerInquiry_CN name="LedgerInquiry_CN">LedgerInquiry_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerInquiry_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerYearEndClosingEnabled_PSN name="LedgerYearEndClosingEnabled_PSN">LedgerYearEndClosingEnabled_PSN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerYearEndClosingEnabled_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LimitedOpenFiscalPeriods name="LimitedOpenFiscalPeriods">LimitedOpenFiscalPeriods</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitedOpenFiscalPeriods attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxRoundingDifferenceMST name="MaxRoundingDifferenceMST">MaxRoundingDifferenceMST</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxRoundingDifferenceMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaxRoundingDifferenceMSTSecond name="MaxRoundingDifferenceMSTSecond">MaxRoundingDifferenceMSTSecond</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxRoundingDifferenceMSTSecond attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MCRUploadJournalName name="MCRUploadJournalName">MCRUploadJournalName</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRUploadJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Miscellaneouscharges_IN name="Miscellaneouscharges_IN">Miscellaneouscharges_IN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Miscellaneouscharges_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OpeningVoucher name="OpeningVoucher">OpeningVoucher</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpeningVoucher attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OpeningWithoutBudget name="OpeningWithoutBudget">OpeningWithoutBudget</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpeningWithoutBudget attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PeriodClosingPosting name="PeriodClosingPosting">PeriodClosingPosting</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodClosingPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrecalcDataActual_RU name="PrecalcDataActual_RU">PrecalcDataActual_RU</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrecalcDataActual_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProvisionAccount_SA name="ProvisionAccount_SA">ProvisionAccount_SA</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProvisionAccount_SA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchYearEndEnabled_PSN name="PurchYearEndEnabled_PSN">PurchYearEndEnabled_PSN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchYearEndEnabled_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReExpressionMainAccount_MX name="ReExpressionMainAccount_MX">ReExpressionMainAccount_MX</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReExpressionMainAccount_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RepomoMainAccount_MX name="RepomoMainAccount_MX">RepomoMainAccount_MX</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepomoMainAccount_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReverseOppositeSignAmounts name="ReverseOppositeSignAmounts">ReverseOppositeSignAmounts</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseOppositeSignAmounts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowAmountDebitCredit_CN name="ShowAmountDebitCredit_CN">ShowAmountDebitCredit_CN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAmountDebitCredit_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TAccount_JP name="TAccount_JP">TAccount_JP</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TAccount_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxImportAlandTax name="TaxImportAlandTax">TaxImportAlandTax</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxImportAlandTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdMinInvoice_TH name="TaxWithholdMinInvoice_TH">TaxWithholdMinInvoice_TH</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdMinInvoice_TH attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransactionReversalCorrection name="TransactionReversalCorrection">TransactionReversalCorrection</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionReversalCorrection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransactionReversalNumberOfBatchTasks name="TransactionReversalNumberOfBatchTasks">TransactionReversalNumberOfBatchTasks</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionReversalNumberOfBatchTasks attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#TransactionReversalNumberLinesToForceBatch name="TransactionReversalNumberLinesToForceBatch">TransactionReversalNumberLinesToForceBatch</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionReversalNumberLinesToForceBatch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#TransactionReversalNumberOfHoursBeforeReRunProcessingStatus name="TransactionReversalNumberOfHoursBeforeReRunProcessingStatus">TransactionReversalNumberOfHoursBeforeReRunProcessingStatus</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionReversalNumberOfHoursBeforeReRunProcessingStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#UsePrecalcData_RU name="UsePrecalcData_RU">UsePrecalcData_RU</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsePrecalcData_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VATRefundingMethod_RU name="VATRefundingMethod_RU">VATRefundingMethod_RU</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATRefundingMethod_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#YearClosed name="YearClosed">YearClosed</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearClosed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsSummarizeSettlementEnabled_PSN name="IsSummarizeSettlementEnabled_PSN">IsSummarizeSettlementEnabled_PSN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSummarizeSettlementEnabled_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdvancedLedgerSettlement name="AdvancedLedgerSettlement">AdvancedLedgerSettlement</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedLedgerSettlement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UniqueCertificationERFormatMappingId_IT name="UniqueCertificationERFormatMappingId_IT">UniqueCertificationERFormatMappingId_IT</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UniqueCertificationERFormatMappingId_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ERFormatMappingCIS_GB name="ERFormatMappingCIS_GB">ERFormatMappingCIS_GB</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingCIS_GB attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ELedgerAccountingAuxiliaryLedgerFormatMapping name="ELedgerAccountingAuxiliaryLedgerFormatMapping">ELedgerAccountingAuxiliaryLedgerFormatMapping</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ELedgerAccountingAuxiliaryLedgerFormatMapping attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ELedgerAccountingLedgerEntriesFormatMapping name="ELedgerAccountingLedgerEntriesFormatMapping">ELedgerAccountingLedgerEntriesFormatMapping</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ELedgerAccountingLedgerEntriesFormatMapping attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ELedgerAccountingChartOfAccountsFormatMapping name="ELedgerAccountingChartOfAccountsFormatMapping">ELedgerAccountingChartOfAccountsFormatMapping</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ELedgerAccountingChartOfAccountsFormatMapping attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ELedgerAccountingBalanceSheetFormatMapping name="ELedgerAccountingBalanceSheetFormatMapping">ELedgerAccountingBalanceSheetFormatMapping</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ELedgerAccountingBalanceSheetFormatMapping attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SIIIncludeNegativeTax_ES name="SIIIncludeNegativeTax_ES">SIIIncludeNegativeTax_ES</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SIIIncludeNegativeTax_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsBudgetReservationEnabled_PSN name="IsBudgetReservationEnabled_PSN">IsBudgetReservationEnabled_PSN</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBudgetReservationEnabled_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowMultipleTransactionsWithinOneVoucher name="AllowMultipleTransactionsWithinOneVoucher">AllowMultipleTransactionsWithinOneVoucher</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMultipleTransactionsWithinOneVoucher attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNPriorYearCorrection name="PSNPriorYearCorrection">PSNPriorYearCorrection</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNPriorYearCorrection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNLedgerInterestDistributionFundingSourceRules name="PSNLedgerInterestDistributionFundingSourceRules">PSNLedgerInterestDistributionFundingSourceRules</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNLedgerInterestDistributionFundingSourceRules attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNLedgerInterestDistributionPostALE name="PSNLedgerInterestDistributionPostALE">PSNLedgerInterestDistributionPostALE</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNLedgerInterestDistributionPostALE attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNLedgerInterestDistributionEnable name="PSNLedgerInterestDistributionEnable">PSNLedgerInterestDistributionEnable</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNLedgerInterestDistributionEnable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNCashControlDimensionHierarchy name="PSNCashControlDimensionHierarchy">PSNCashControlDimensionHierarchy</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNCashControlDimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PSNCashControlOverrideGroup name="PSNCashControlOverrideGroup">PSNCashControlOverrideGroup</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNCashControlOverrideGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RevRecJournalNameId name="RevRecJournalNameId">RevRecJournalNameId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecEnableReallocation name="RevRecEnableReallocation">RevRecEnableReallocation</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecEnableReallocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RevRecDisableContractTerms name="RevRecDisableContractTerms">RevRecDisableContractTerms</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecDisableContractTerms attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RevRecHeaderDiscounts name="RevRecHeaderDiscounts">RevRecHeaderDiscounts</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecHeaderDiscounts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RevRecPostToAccountsReceivable name="RevRecPostToAccountsReceivable">RevRecPostToAccountsReceivable</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecPostToAccountsReceivable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BillSchRevRecAccruedRevenueJournalNameId name="BillSchRevRecAccruedRevenueJournalNameId">BillSchRevRecAccruedRevenueJournalNameId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillSchRevRecAccruedRevenueJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/LedgerParameters (this entity)  

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

### <a href=#Relationship_ExpenseAccount_SARelationshipId name="Relationship_ExpenseAccount_SARelationshipId">Relationship_ExpenseAccount_SARelationshipId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExpenseAccount_SARelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProvisionAccount_SARelationshipId name="Relationship_ProvisionAccount_SARelationshipId">Relationship_ProvisionAccount_SARelationshipId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProvisionAccount_SARelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReExpressionMainAccount_MXRelationshipId name="Relationship_ReExpressionMainAccount_MXRelationshipId">Relationship_ReExpressionMainAccount_MXRelationshipId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReExpressionMainAccount_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RepomoMainAccount_MXRelationshipId name="Relationship_RepomoMainAccount_MXRelationshipId">Relationship_RepomoMainAccount_MXRelationshipId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RepomoMainAccount_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PSNCashControlDimensionHierarchyRelationshipId name="Relationship_PSNCashControlDimensionHierarchyRelationshipId">Relationship_PSNCashControlDimensionHierarchyRelationshipId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PSNCashControlDimensionHierarchyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Group/DimensionHierarchy.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionHierarchy.cdm.json/DimensionHierarchy</a></td><td><a href="../../FinancialDimensions/Group/DimensionHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PSNCashControlOverrideGroupRelationshipId name="Relationship_PSNCashControlOverrideGroupRelationshipId">Relationship_PSNCashControlOverrideGroupRelationshipId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PSNCashControlOverrideGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/UserGroupInfo.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/UserGroupInfo.cdm.json/UserGroupInfo</a></td><td><a href="../../../System/SystemAdministration/Main/UserGroupInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RevRecLedgerJournalNameRelationshipId name="Relationship_RevRecLedgerJournalNameRelationshipId">Relationship_RevRecLedgerJournalNameRelationshipId</a>

First included in: Parameter/LedgerParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RevRecLedgerJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/LedgerParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
