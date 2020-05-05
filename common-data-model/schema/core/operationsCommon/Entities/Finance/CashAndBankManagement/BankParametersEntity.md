---
title: BankParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Bank parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllowChecksForLedgerAccounts](#AllowChecksForLedgerAccounts)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[AllowCheckReuse](#AllowCheckReuse)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[MaxDateDifferenceForReconciliationMatching](#MaxDateDifferenceForReconciliationMatching)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[AllowInactiveBankPrenote](#AllowInactiveBankPrenote)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[AllowPaymentCopies](#AllowPaymentCopies)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[EnableLetterOfCreditExport](#EnableLetterOfCreditExport)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[EnableLetterOfCreditImport](#EnableLetterOfCreditImport)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[EnableLetterOfGuarantee](#EnableLetterOfGuarantee)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[LetterOfGuaranteeJournalName](#LetterOfGuaranteeJournalName)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ShowAmountsInDebitCreditOnBankStatement](#ShowAmountsInDebitCreditOnBankStatement)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ValidateReconciliationMatchingDateDifference](#ValidateReconciliationMatchingDateDifference)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ValidateReconciliationMatchingTransactionType](#ValidateReconciliationMatchingTransactionType)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[CreditLimitTolerance](#CreditLimitTolerance)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[EnablePostdatedChecks](#EnablePostdatedChecks)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[PostdatedChecksJournalName](#PostdatedChecksJournalName)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ClearingMainAccountIdForIssuedPostdatedChecks](#ClearingMainAccountIdForIssuedPostdatedChecks)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[Key](#Key)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[NonsufficientFundsTransactionType](#NonsufficientFundsTransactionType)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[PostJournalEntriesForPostdatedChecks](#PostJournalEntriesForPostdatedChecks)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ClearingMainAccountIdForRecievedPostdatedChecks](#ClearingMainAccountIdForRecievedPostdatedChecks)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[RequireCheckReversalJournal](#RequireCheckReversalJournal)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[RequireCheckReversalReason](#RequireCheckReversalReason)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[RequireDepositCancellationJournal](#RequireDepositCancellationJournal)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[RequireDepositCancellationReason](#RequireDepositCancellationReason)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[PostdatedChecksPaymentJournalName](#PostdatedChecksPaymentJournalName)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[WithholdingTaxMainAccountIdForPostdatedChecks](#WithholdingTaxMainAccountIdForPostdatedChecks)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ClearingMainAccountIdForIssuedPostdatedChecksDisplayValue](#ClearingMainAccountIdForIssuedPostdatedChecksDisplayValue)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ClearingMainAccountIdForRecievedPostdatedChecksDisplayValue](#ClearingMainAccountIdForRecievedPostdatedChecksDisplayValue)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[WithholdingTaxMainAccountIdForPostdatedChecksDisplayValue](#WithholdingTaxMainAccountIdForPostdatedChecksDisplayValue)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[JBAFileKanaNameValidationMethod](#JBAFileKanaNameValidationMethod)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[AllowCommaInBankAccountKanaName](#AllowCommaInBankAccountKanaName)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[IsLetterofCreditChargesPostingEnabled](#IsLetterofCreditChargesPostingEnabled)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ValidationMethod](#ValidationMethod)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[CheckForVoucherUsed](#CheckForVoucherUsed)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[UseConfirmStatus](#UseConfirmStatus)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[Cash](#Cash)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[PostingOnEarlierDate](#PostingOnEarlierDate)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ExchangeDifferencesType](#ExchangeDifferencesType)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[ExchangeRateOnDisbursements](#ExchangeRateOnDisbursements)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[CheckOperationsLimit](#CheckOperationsLimit)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[OperationsLimit](#OperationsLimit)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[QuantityOfDays](#QuantityOfDays)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[DisallowPostingEarlierThanCashReportClosingDate](#DisallowPostingEarlierThanCashReportClosingDate)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[CashPosting](#CashPosting)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[AnalysisCode](#AnalysisCode)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[DepartmentCode](#DepartmentCode)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[PurposeCode](#PurposeCode)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[AllowBankCurrencyReval](#AllowBankCurrencyReval)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[AllowBankAccountStatementEdit](#AllowBankAccountStatementEdit)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[PSNEnableEscheatment](#PSNEnableEscheatment)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[Relationship_ClearingMainAccountIdForIssuedPostdatedChecksCombinationRelationshipId](#Relationship_ClearingMainAccountIdForIssuedPostdatedChecksCombinationRelationshipId)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[Relationship_ClearingMainAccountIdForRecievedPostdatedChecksCombinationRelationshipId](#Relationship_ClearingMainAccountIdForRecievedPostdatedChecksCombinationRelationshipId)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[Relationship_WithholdingTaxMainAccountIdForPostdatedChecksCombinationRelationshipId](#Relationship_WithholdingTaxMainAccountIdForPostdatedChecksCombinationRelationshipId)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[BackingTable_BankParametersRelationshipId](#BackingTable_BankParametersRelationshipId)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankParametersEntity.md" target="_blank">CashAndBankManagement/BankParametersEntity</a>|

### <a href=#AllowChecksForLedgerAccounts name="AllowChecksForLedgerAccounts">AllowChecksForLedgerAccounts</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowChecksForLedgerAccounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowCheckReuse name="AllowCheckReuse">AllowCheckReuse</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowCheckReuse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxDateDifferenceForReconciliationMatching name="MaxDateDifferenceForReconciliationMatching">MaxDateDifferenceForReconciliationMatching</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxDateDifferenceForReconciliationMatching attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowInactiveBankPrenote name="AllowInactiveBankPrenote">AllowInactiveBankPrenote</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowInactiveBankPrenote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowPaymentCopies name="AllowPaymentCopies">AllowPaymentCopies</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPaymentCopies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableLetterOfCreditExport name="EnableLetterOfCreditExport">EnableLetterOfCreditExport</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLetterOfCreditExport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableLetterOfCreditImport name="EnableLetterOfCreditImport">EnableLetterOfCreditImport</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLetterOfCreditImport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableLetterOfGuarantee name="EnableLetterOfGuarantee">EnableLetterOfGuarantee</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLetterOfGuarantee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LetterOfGuaranteeJournalName name="LetterOfGuaranteeJournalName">LetterOfGuaranteeJournalName</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LetterOfGuaranteeJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowAmountsInDebitCreditOnBankStatement name="ShowAmountsInDebitCreditOnBankStatement">ShowAmountsInDebitCreditOnBankStatement</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAmountsInDebitCreditOnBankStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateReconciliationMatchingDateDifference name="ValidateReconciliationMatchingDateDifference">ValidateReconciliationMatchingDateDifference</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateReconciliationMatchingDateDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateReconciliationMatchingTransactionType name="ValidateReconciliationMatchingTransactionType">ValidateReconciliationMatchingTransactionType</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateReconciliationMatchingTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimitTolerance name="CreditLimitTolerance">CreditLimitTolerance</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnablePostdatedChecks name="EnablePostdatedChecks">EnablePostdatedChecks</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnablePostdatedChecks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedChecksJournalName name="PostdatedChecksJournalName">PostdatedChecksJournalName</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedChecksJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClearingMainAccountIdForIssuedPostdatedChecks name="ClearingMainAccountIdForIssuedPostdatedChecks">ClearingMainAccountIdForIssuedPostdatedChecks</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClearingMainAccountIdForIssuedPostdatedChecks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

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

### <a href=#NonsufficientFundsTransactionType name="NonsufficientFundsTransactionType">NonsufficientFundsTransactionType</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonsufficientFundsTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostJournalEntriesForPostdatedChecks name="PostJournalEntriesForPostdatedChecks">PostJournalEntriesForPostdatedChecks</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostJournalEntriesForPostdatedChecks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClearingMainAccountIdForRecievedPostdatedChecks name="ClearingMainAccountIdForRecievedPostdatedChecks">ClearingMainAccountIdForRecievedPostdatedChecks</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClearingMainAccountIdForRecievedPostdatedChecks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireCheckReversalJournal name="RequireCheckReversalJournal">RequireCheckReversalJournal</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireCheckReversalJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireCheckReversalReason name="RequireCheckReversalReason">RequireCheckReversalReason</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireCheckReversalReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireDepositCancellationJournal name="RequireDepositCancellationJournal">RequireDepositCancellationJournal</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireDepositCancellationJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireDepositCancellationReason name="RequireDepositCancellationReason">RequireDepositCancellationReason</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireDepositCancellationReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedChecksPaymentJournalName name="PostdatedChecksPaymentJournalName">PostdatedChecksPaymentJournalName</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedChecksPaymentJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxMainAccountIdForPostdatedChecks name="WithholdingTaxMainAccountIdForPostdatedChecks">WithholdingTaxMainAccountIdForPostdatedChecks</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxMainAccountIdForPostdatedChecks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClearingMainAccountIdForIssuedPostdatedChecksDisplayValue name="ClearingMainAccountIdForIssuedPostdatedChecksDisplayValue">ClearingMainAccountIdForIssuedPostdatedChecksDisplayValue</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Clearing account for issued checks</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClearingMainAccountIdForIssuedPostdatedChecksDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Clearing account for issued checks</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClearingMainAccountIdForRecievedPostdatedChecksDisplayValue name="ClearingMainAccountIdForRecievedPostdatedChecksDisplayValue">ClearingMainAccountIdForRecievedPostdatedChecksDisplayValue</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Clearing account for received checks</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClearingMainAccountIdForRecievedPostdatedChecksDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Clearing account for received checks</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxMainAccountIdForPostdatedChecksDisplayValue name="WithholdingTaxMainAccountIdForPostdatedChecksDisplayValue">WithholdingTaxMainAccountIdForPostdatedChecksDisplayValue</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax clearing account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxMainAccountIdForPostdatedChecksDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax clearing account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JBAFileKanaNameValidationMethod name="JBAFileKanaNameValidationMethod">JBAFileKanaNameValidationMethod</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JBAFileKanaNameValidationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowCommaInBankAccountKanaName name="AllowCommaInBankAccountKanaName">AllowCommaInBankAccountKanaName</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowCommaInBankAccountKanaName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLetterofCreditChargesPostingEnabled name="IsLetterofCreditChargesPostingEnabled">IsLetterofCreditChargesPostingEnabled</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLetterofCreditChargesPostingEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationMethod name="ValidationMethod">ValidationMethod</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckForVoucherUsed name="CheckForVoucherUsed">CheckForVoucherUsed</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckForVoucherUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseConfirmStatus name="UseConfirmStatus">UseConfirmStatus</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseConfirmStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Cash name="Cash">Cash</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Cash attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingOnEarlierDate name="PostingOnEarlierDate">PostingOnEarlierDate</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingOnEarlierDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeDifferencesType name="ExchangeDifferencesType">ExchangeDifferencesType</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeDifferencesType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateOnDisbursements name="ExchangeRateOnDisbursements">ExchangeRateOnDisbursements</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateOnDisbursements attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckOperationsLimit name="CheckOperationsLimit">CheckOperationsLimit</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckOperationsLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsLimit name="OperationsLimit">OperationsLimit</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityOfDays name="QuantityOfDays">QuantityOfDays</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityOfDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisallowPostingEarlierThanCashReportClosingDate name="DisallowPostingEarlierThanCashReportClosingDate">DisallowPostingEarlierThanCashReportClosingDate</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisallowPostingEarlierThanCashReportClosingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashPosting name="CashPosting">CashPosting</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnalysisCode name="AnalysisCode">AnalysisCode</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnalysisCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepartmentCode name="DepartmentCode">DepartmentCode</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepartmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurposeCode name="PurposeCode">PurposeCode</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurposeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowBankCurrencyReval name="AllowBankCurrencyReval">AllowBankCurrencyReval</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowBankCurrencyReval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowBankAccountStatementEdit name="AllowBankAccountStatementEdit">AllowBankAccountStatementEdit</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowBankAccountStatementEdit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNEnableEscheatment name="PSNEnableEscheatment">PSNEnableEscheatment</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNEnableEscheatment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ClearingMainAccountIdForIssuedPostdatedChecksCombinationRelationshipId name="Relationship_ClearingMainAccountIdForIssuedPostdatedChecksCombinationRelationshipId">Relationship_ClearingMainAccountIdForIssuedPostdatedChecksCombinationRelationshipId</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ClearingMainAccountIdForIssuedPostdatedChecksCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ClearingMainAccountIdForRecievedPostdatedChecksCombinationRelationshipId name="Relationship_ClearingMainAccountIdForRecievedPostdatedChecksCombinationRelationshipId">Relationship_ClearingMainAccountIdForRecievedPostdatedChecksCombinationRelationshipId</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ClearingMainAccountIdForRecievedPostdatedChecksCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WithholdingTaxMainAccountIdForPostdatedChecksCombinationRelationshipId name="Relationship_WithholdingTaxMainAccountIdForPostdatedChecksCombinationRelationshipId">Relationship_WithholdingTaxMainAccountIdForPostdatedChecksCombinationRelationshipId</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WithholdingTaxMainAccountIdForPostdatedChecksCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BankParametersRelationshipId name="BackingTable_BankParametersRelationshipId">BackingTable_BankParametersRelationshipId</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Parameter/BankParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Parameter/BankParameters.cdm.json/BankParameters</a></td><td><a href="../../../Tables/Finance/Bank/Parameter/BankParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankParametersEntity (this entity)  

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
