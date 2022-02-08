---
title: RetailStatementTable in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Statements in WorksheetHeader(RetailStatementTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/WorksheetHeader/RetailStatementTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStatementTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Statements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[calculatedDate](#calculatedDate)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[CalculatedLines](#CalculatedLines)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[calculatedTime](#calculatedTime)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[closingMethod](#closingMethod)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[debugMode](#debugMode)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[postedDate](#postedDate)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[postedTime](#postedTime)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[postingDate](#postingDate)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[recalculate](#recalculate)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[replicationCounter](#replicationCounter)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[shiftDate](#shiftDate)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[shiftId](#shiftId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[skipConfirmation](#skipConfirmation)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[staffOrTerminal](#staffOrTerminal)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[statementDate](#statementDate)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[statementId](#statementId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[statementMethod](#statementMethod)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[stmtCalcInfoLog](#stmtCalcInfoLog)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[stmtPostInfoLog](#stmtPostInfoLog)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[storeId](#storeId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[transFromDate](#transFromDate)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[transFromTime](#transFromTime)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[transToDate](#transToDate)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[transToTime](#transToTime)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[PostingStatus](#PostingStatus)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[PostingErrorCode](#PostingErrorCode)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[PostingErrorMessage](#PostingErrorMessage)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[PostingErrorStatus](#PostingErrorStatus)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[EodCodeVersion](#EodCodeVersion)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[PaymentStatus](#PaymentStatus)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[PostingBatchJobId](#PostingBatchJobId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[IgnoreReturnLink](#IgnoreReturnLink)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[StatementType](#StatementType)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[AggregateBeforePosting](#AggregateBeforePosting)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[CreationVersionIndicator](#CreationVersionIndicator)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[startAmountCalculation](#startAmountCalculation)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[oneStatementPerDay](#oneStatementPerDay)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[bankDropCalculation](#bankDropCalculation)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[tenderDeclarationCalculation](#tenderDeclarationCalculation)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[stmtCalcBatchEndTime](#stmtCalcBatchEndTime)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[DisableCountingRequired](#DisableCountingRequired)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[ReserveInventoryDuringStatementCalculation](#ReserveInventoryDuringStatementCalculation)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[SkipAggregationForReturns](#SkipAggregationForReturns)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[UpdateGSTTransactionId_IN](#UpdateGSTTransactionId_IN)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[DisableTransactionConsistencyChecker](#DisableTransactionConsistencyChecker)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[MaxNumberOfThreadsCustomerOrder](#MaxNumberOfThreadsCustomerOrder)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[RecalculateDimensionsOnPostingError](#RecalculateDimensionsOnPostingError)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[OfferLedgerDimension](#OfferLedgerDimension)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[MixMatchLedgerDimension](#MixMatchLedgerDimension)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[MultiBuyLedgerDimension](#MultiBuyLedgerDimension)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[ThresholdLedgerDimension](#ThresholdLedgerDimension)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[autosettle](#autosettle)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[PrepaymentLedgerDimension](#PrepaymentLedgerDimension)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[PrePaymentLedgerJournalName](#PrePaymentLedgerJournalName)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[GiftcardItem](#GiftcardItem)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[ProcessGiftcardsAsPrepayments_RU](#ProcessGiftcardsAsPrepayments_RU)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[TaxOnGiftCards](#TaxOnGiftCards)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[AggregatedTransactionsBundleSize](#AggregatedTransactionsBundleSize)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[UseFinancialDimensionFromReturnStore](#UseFinancialDimensionFromReturnStore)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[StmtAutoSettleCustomerDeposit](#StmtAutoSettleCustomerDeposit)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[UseChannelCashManagementReconciliation](#UseChannelCashManagementReconciliation)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[LastAttemptToClear](#LastAttemptToClear)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_DimensionAttributeValueSetRelationshipId](#Relationship_DimensionAttributeValueSetRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_RetailStaffTableRelationshipId](#Relationship_RetailStaffTableRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_RetailStatementLineRelationshipId](#Relationship_RetailStatementLineRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_RetailStoreWorkShiftTableRelationshipId](#Relationship_RetailStoreWorkShiftTableRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_RetailTransactionTableRelationshipId](#Relationship_RetailTransactionTableRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_BatchJobRelationshipId](#Relationship_BatchJobRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailStatementTable.md" target="_blank">WorksheetHeader/RetailStatementTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStatementTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#calculatedDate name="calculatedDate">calculatedDate</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculated date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the calculatedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#CalculatedLines name="CalculatedLines">CalculatedLines</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculation lines</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculation lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#calculatedTime name="calculatedTime">calculatedTime</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculated time</td></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the calculatedTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#closingMethod name="closingMethod">closingMethod</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the closingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#debugMode name="debugMode">debugMode</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the debugMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#postedDate name="postedDate">postedDate</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posted date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the postedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posted date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#postedTime name="postedTime">postedTime</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posted time</td></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the postedTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posted time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#postingDate name="postingDate">postingDate</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the postingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#recalculate name="recalculate">recalculate</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the recalculate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#replicationCounter name="replicationCounter">replicationCounter</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicationCounter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#shiftDate name="shiftDate">shiftDate</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shiftDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#shiftId name="shiftId">shiftId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shiftId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#skipConfirmation name="skipConfirmation">skipConfirmation</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the skipConfirmation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#staffOrTerminal name="staffOrTerminal">staffOrTerminal</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the staffOrTerminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statementDate name="statementDate">statementDate</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#statementId name="statementId">statementId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statementMethod name="statementMethod">statementMethod</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#stmtCalcInfoLog name="stmtCalcInfoLog">stmtCalcInfoLog</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stmtCalcInfoLog attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#stmtPostInfoLog name="stmtPostInfoLog">stmtPostInfoLog</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stmtPostInfoLog attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#storeId name="storeId">storeId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the storeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transFromDate name="transFromDate">transFromDate</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction from date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transFromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction from date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#transFromTime name="transFromTime">transFromTime</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction from time</td></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transFromTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction from time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#transToDate name="transToDate">transToDate</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction end date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction end date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#transToTime name="transToTime">transToTime</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction end time</td></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transToTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction end time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#PostingStatus name="PostingStatus">PostingStatus</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostingErrorCode name="PostingErrorCode">PostingErrorCode</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingErrorCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostingErrorMessage name="PostingErrorMessage">PostingErrorMessage</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingErrorMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingErrorStatus name="PostingErrorStatus">PostingErrorStatus</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingErrorStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EodCodeVersion name="EodCodeVersion">EodCodeVersion</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EodCodeVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PaymentStatus name="PaymentStatus">PaymentStatus</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostingBatchJobId name="PostingBatchJobId">PostingBatchJobId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Batch job ID</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingBatchJobId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch job ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IgnoreReturnLink name="IgnoreReturnLink">IgnoreReturnLink</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IgnoreReturnLink attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StatementType name="StatementType">StatementType</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AggregateBeforePosting name="AggregateBeforePosting">AggregateBeforePosting</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AggregateBeforePosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CreationVersionIndicator name="CreationVersionIndicator">CreationVersionIndicator</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreationVersionIndicator attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#startAmountCalculation name="startAmountCalculation">startAmountCalculation</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the startAmountCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#oneStatementPerDay name="oneStatementPerDay">oneStatementPerDay</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the oneStatementPerDay attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#bankDropCalculation name="bankDropCalculation">bankDropCalculation</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the bankDropCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#tenderDeclarationCalculation name="tenderDeclarationCalculation">tenderDeclarationCalculation</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tenderDeclarationCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#stmtCalcBatchEndTime name="stmtCalcBatchEndTime">stmtCalcBatchEndTime</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End of business day</td></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stmtCalcBatchEndTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>End of business day</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#DisableCountingRequired name="DisableCountingRequired">DisableCountingRequired</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disable counting required</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisableCountingRequired attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Disable counting required</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReserveInventoryDuringStatementCalculation name="ReserveInventoryDuringStatementCalculation">ReserveInventoryDuringStatementCalculation</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReserveInventoryDuringStatementCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SkipAggregationForReturns name="SkipAggregationForReturns">SkipAggregationForReturns</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipAggregationForReturns attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UpdateGSTTransactionId_IN name="UpdateGSTTransactionId_IN">UpdateGSTTransactionId_IN</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update POS invoice number</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateGSTTransactionId_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update POS invoice number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DisableTransactionConsistencyChecker name="DisableTransactionConsistencyChecker">DisableTransactionConsistencyChecker</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisableTransactionConsistencyChecker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfThreadsCustomerOrder name="MaxNumberOfThreadsCustomerOrder">MaxNumberOfThreadsCustomerOrder</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfThreadsCustomerOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RecalculateDimensionsOnPostingError name="RecalculateDimensionsOnPostingError">RecalculateDimensionsOnPostingError</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecalculateDimensionsOnPostingError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OfferLedgerDimension name="OfferLedgerDimension">OfferLedgerDimension</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfferLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MixMatchLedgerDimension name="MixMatchLedgerDimension">MixMatchLedgerDimension</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixMatchLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MultiBuyLedgerDimension name="MultiBuyLedgerDimension">MultiBuyLedgerDimension</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiBuyLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ThresholdLedgerDimension name="ThresholdLedgerDimension">ThresholdLedgerDimension</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#autosettle name="autosettle">autosettle</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the autosettle attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrepaymentLedgerDimension name="PrepaymentLedgerDimension">PrepaymentLedgerDimension</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrePaymentLedgerJournalName name="PrePaymentLedgerJournalName">PrePaymentLedgerJournalName</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePaymentLedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftcardItem name="GiftcardItem">GiftcardItem</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftcardItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessGiftcardsAsPrepayments_RU name="ProcessGiftcardsAsPrepayments_RU">ProcessGiftcardsAsPrepayments_RU</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process gift card operations as prepayments</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessGiftcardsAsPrepayments_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Process gift card operations as prepayments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxOnGiftCards name="TaxOnGiftCards">TaxOnGiftCards</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax on gift cards</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOnGiftCards attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax on gift cards</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AggregatedTransactionsBundleSize name="AggregatedTransactionsBundleSize">AggregatedTransactionsBundleSize</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AggregatedTransactionsBundleSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseFinancialDimensionFromReturnStore name="UseFinancialDimensionFromReturnStore">UseFinancialDimensionFromReturnStore</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFinancialDimensionFromReturnStore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StmtAutoSettleCustomerDeposit name="StmtAutoSettleCustomerDeposit">StmtAutoSettleCustomerDeposit</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StmtAutoSettleCustomerDeposit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseChannelCashManagementReconciliation name="UseChannelCashManagementReconciliation">UseChannelCashManagementReconciliation</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseChannelCashManagementReconciliation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LastAttemptToClear name="LastAttemptToClear">LastAttemptToClear</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastAttemptToClear attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

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

### <a href=#Relationship_DimensionAttributeValueSetRelationshipId name="Relationship_DimensionAttributeValueSetRelationshipId">Relationship_DimensionAttributeValueSetRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStaffTableRelationshipId name="Relationship_RetailStaffTableRelationshipId">Relationship_RetailStaffTableRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStaffTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../CommerceEmployees/Main/RetailStaffTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceEmployees/Main/RetailStaffTable.cdm.json/RetailStaffTable</a></td><td><a href="../../CommerceEmployees/Main/RetailStaffTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStatementLineRelationshipId name="Relationship_RetailStatementLineRelationshipId">Relationship_RetailStatementLineRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStatementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/RetailStatementLine.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/WorksheetLine/RetailStatementLine.cdm.json/RetailStatementLine</a></td><td><a href="../WorksheetLine/RetailStatementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreWorkShiftTableRelationshipId name="Relationship_RetailStoreWorkShiftTableRelationshipId">Relationship_RetailStoreWorkShiftTableRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreWorkShiftTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../CommerceEmployees/WorksheetHeader/RetailStoreWorkShiftTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceEmployees/WorksheetHeader/RetailStoreWorkShiftTable.cdm.json/RetailStoreWorkShiftTable</a></td><td><a href="../../CommerceEmployees/WorksheetHeader/RetailStoreWorkShiftTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionTableRelationshipId name="Relationship_RetailTransactionTableRelationshipId">Relationship_RetailTransactionTableRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/RetailTransactionTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionTable.cdm.json/RetailTransactionTable</a></td><td><a href="../Transaction/RetailTransactionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BatchJobRelationshipId name="Relationship_BatchJobRelationshipId">Relationship_BatchJobRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BatchJobRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Transaction/BatchJob.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/BatchJob.cdm.json/BatchJob</a></td><td><a href="../../../System/SystemAdministration/Transaction/BatchJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/RetailStatementTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
