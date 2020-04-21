---
title: BankAccountTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# BankAccountTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/Main/BankAccountTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankAccountTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[NsfLedgerJournalName](#NsfLedgerJournalName)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[AccountID](#AccountID)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[AccountNameKana_JP](#AccountNameKana_JP)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[AccountNum](#AccountNum)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[ActiveFrom](#ActiveFrom)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[ActiveTo](#ActiveTo)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankAccountStatus](#BankAccountStatus)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankCIN](#BankCIN)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankClearingCode](#BankClearingCode)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankCodeType](#BankCodeType)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankCompanyStatementName](#BankCompanyStatementName)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankConstantSymbol](#BankConstantSymbol)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankContractAccount](#BankContractAccount)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankDestinationName](#BankDestinationName)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankGroupId](#BankGroupId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankInterbankClearingCode_BE](#BankInterbankClearingCode_BE)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankMultiCurrency](#BankMultiCurrency)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankPositivePayFormatName](#BankPositivePayFormatName)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankPositivePayStartDate](#BankPositivePayStartDate)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankReconAllowedPennyDifference](#BankReconAllowedPennyDifference)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankReconciliationEnabled](#BankReconciliationEnabled)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankReconciliationMatchRuleSet](#BankReconciliationMatchRuleSet)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankReconciliationStmtAsPaymConfirm](#BankReconciliationStmtAsPaymConfirm)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankReconMatchAutoAfterImport](#BankReconMatchAutoAfterImport)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankReconMatchRuleManualMatch](#BankReconMatchRuleManualMatch)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankReconMatchRuleManualReversal](#BankReconMatchRuleManualReversal)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankSortCode](#BankSortCode)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankStatementFormat](#BankStatementFormat)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankStatementName](#BankStatementName)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankSuffix](#BankSuffix)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankTransferCode](#BankTransferCode)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CellularPhone](#CellularPhone)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CompanyPaymId](#CompanyPaymId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[ContactPerson](#ContactPerson)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CorrAccount_W](#CorrAccount_W)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CurrencyCode](#CurrencyCode)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CurrencyOrder_TemplateName_RU](#CurrencyOrder_TemplateName_RU)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CurrencySellOrder_TemplateName_RU](#CurrencySellOrder_TemplateName_RU)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CustomerPaymentFeeLedgerDimension](#CustomerPaymentFeeLedgerDimension)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CustPaymFeePost](#CustPaymFeePost)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[DebitDirectId](#DebitDirectId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[DiscCreditMaxMST](#DiscCreditMaxMST)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[DivisionPaymId](#DivisionPaymId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Email](#Email)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[FeeContractAccount](#FeeContractAccount)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[GiroContract](#GiroContract)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[GiroContractAccount](#GiroContractAccount)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[IBAN](#IBAN)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[IncludeBankBarCode_FI](#IncludeBankBarCode_FI)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[InvoiceRemitAmount](#InvoiceRemitAmount)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[InvoiceRemittanceLedgerDimension](#InvoiceRemittanceLedgerDimension)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[isBankPrenote](#isBankPrenote)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[LedgerDimension](#LedgerDimension)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[LedgerJournalNameId](#LedgerJournalNameId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Location](#Location)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[LvDefaultBank](#LvDefaultBank)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[LvPayOrderType](#LvPayOrderType)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Name](#Name)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[NsfFeeMarkupGroupId](#NsfFeeMarkupGroupId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[NsfFeeMarkupGroupModule](#NsfFeeMarkupGroupModule)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[OverDraftLimit](#OverDraftLimit)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Pager](#Pager)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PaymForeignExportPath_LT](#PaymForeignExportPath_LT)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PaymLocalExportPath_LT](#PaymLocalExportPath_LT)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PaymOrderNumSeqId_W](#PaymOrderNumSeqId_W)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Phone](#Phone)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PhoneLocal](#PhoneLocal)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PrenoteResponseDays](#PrenoteResponseDays)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PrintGiro_FI](#PrintGiro_FI)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[RegistrationNum](#RegistrationNum)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[RemitCollectionAmount](#RemitCollectionAmount)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[RemitDiscountAmount](#RemitDiscountAmount)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[RemittanceCollectionLedgerDimension](#RemittanceCollectionLedgerDimension)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[RemittanceDiscountLedgerDimension](#RemittanceDiscountLedgerDimension)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Rfc_MX](#Rfc_MX)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[SMS](#SMS)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[SpecificSymbol](#SpecificSymbol)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[SWIFTNo](#SWIFTNo)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[TeleFax](#TeleFax)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Telex](#Telex)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[TemplateFileName_RU](#TemplateFileName_RU)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[TransType_JP](#TransType_JP)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[URL](#URL)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[BankPositivePayFormat](#BankPositivePayFormat)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[IsNACHAFileBlocked](#IsNACHAFileBlocked)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[TemplateRefRecId_RU](#TemplateRefRecId_RU)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CurrencyOrder_TemplateRefRecId_RU](#CurrencyOrder_TemplateRefRecId_RU)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CurrencySellOrder_TemplateRefRecId_RU](#CurrencySellOrder_TemplateRefRecId_RU)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[CFMBankBalanceMinimum](#CFMBankBalanceMinimum)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PostingProfileBillsRemitCollection_IT](#PostingProfileBillsRemitCollection_IT)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PostingProfileBillsRemitDiscount_IT](#PostingProfileBillsRemitDiscount_IT)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[PostingProfileRemitNotes_IT](#PostingProfileRemitNotes_IT)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[QRIBAN_CH](#QRIBAN_CH)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[DataAreaId](#DataAreaId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_BankConstantSymbolRelationshipId](#Relationship_BankConstantSymbolRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_BankGroupRelationshipId](#Relationship_BankGroupRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_BankReconciliationMatchRuleSetRelationshipId](#Relationship_BankReconciliationMatchRuleSetRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_BankStatementFormatRelationshipId](#Relationship_BankStatementFormatRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_CustomerPaymentFeeLedgerDimensionRelationshipId](#Relationship_CustomerPaymentFeeLedgerDimensionRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_InvoiceRemittanceLedgerDimensionRelationshipId](#Relationship_InvoiceRemittanceLedgerDimensionRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_LedgerJournalName_LedJourNameIdRelationshipId](#Relationship_LedgerJournalName_LedJourNameIdRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_LedgerJournalName_NsfLedJourNameRelationshipId](#Relationship_LedgerJournalName_NsfLedJourNameRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_Location_FKRelationshipId](#Relationship_Location_FKRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_MarkupGroupRelationshipId](#Relationship_MarkupGroupRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_NumberSequenceTableRelationshipId](#Relationship_NumberSequenceTableRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_RemittanceCollectionLedgerDimensionRelationshipId](#Relationship_RemittanceCollectionLedgerDimensionRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_RemittanceDiscountLedgerDimensionRelationshipId](#Relationship_RemittanceDiscountLedgerDimensionRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_BankPositivePayFormatRelationshipId](#Relationship_BankPositivePayFormatRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_TemplateDocuRefRelationshipId](#Relationship_TemplateDocuRefRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_CurrencyOrderTemplateDocuRefRelationshipId](#Relationship_CurrencyOrderTemplateDocuRefRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_CurrencySellOrderDocuRefRelationshipId](#Relationship_CurrencySellOrderDocuRefRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_CustLedger_BillsRemitDisc_ITRelationshipId](#Relationship_CustLedger_BillsRemitDisc_ITRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_CustLedger_BillsRemitCollection_ITRelationshipId](#Relationship_CustLedger_BillsRemitCollection_ITRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_VendLedger_RemitNotes_ITRelationshipId](#Relationship_VendLedger_RemitNotes_ITRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BankAccountTable.md" target="_blank">Main/BankAccountTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankAccountTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NsfLedgerJournalName name="NsfLedgerJournalName">NsfLedgerJournalName</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NsfLedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountID name="AccountID">AccountID</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNameKana_JP name="AccountNameKana_JP">AccountNameKana_JP</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNameKana_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ActiveTo name="ActiveTo">ActiveTo</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#BankAccountStatus name="BankAccountStatus">BankAccountStatus</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankCIN name="BankCIN">BankCIN</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCIN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankClearingCode name="BankClearingCode">BankClearingCode</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankClearingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankCodeType name="BankCodeType">BankCodeType</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCodeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankCompanyStatementName name="BankCompanyStatementName">BankCompanyStatementName</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCompanyStatementName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankConstantSymbol name="BankConstantSymbol">BankConstantSymbol</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankConstantSymbol attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankContractAccount name="BankContractAccount">BankContractAccount</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankContractAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankDestinationName name="BankDestinationName">BankDestinationName</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankDestinationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankGroupId name="BankGroupId">BankGroupId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankInterbankClearingCode_BE name="BankInterbankClearingCode_BE">BankInterbankClearingCode_BE</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankInterbankClearingCode_BE attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankMultiCurrency name="BankMultiCurrency">BankMultiCurrency</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankMultiCurrency attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankPositivePayFormatName name="BankPositivePayFormatName">BankPositivePayFormatName</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankPositivePayFormatName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankPositivePayStartDate name="BankPositivePayStartDate">BankPositivePayStartDate</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankPositivePayStartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#BankReconAllowedPennyDifference name="BankReconAllowedPennyDifference">BankReconAllowedPennyDifference</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankReconAllowedPennyDifference attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankReconciliationEnabled name="BankReconciliationEnabled">BankReconciliationEnabled</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankReconciliationEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankReconciliationMatchRuleSet name="BankReconciliationMatchRuleSet">BankReconciliationMatchRuleSet</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankReconciliationMatchRuleSet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankReconciliationStmtAsPaymConfirm name="BankReconciliationStmtAsPaymConfirm">BankReconciliationStmtAsPaymConfirm</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankReconciliationStmtAsPaymConfirm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankReconMatchAutoAfterImport name="BankReconMatchAutoAfterImport">BankReconMatchAutoAfterImport</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankReconMatchAutoAfterImport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankReconMatchRuleManualMatch name="BankReconMatchRuleManualMatch">BankReconMatchRuleManualMatch</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankReconMatchRuleManualMatch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankReconMatchRuleManualReversal name="BankReconMatchRuleManualReversal">BankReconMatchRuleManualReversal</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankReconMatchRuleManualReversal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankSortCode name="BankSortCode">BankSortCode</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankSortCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementFormat name="BankStatementFormat">BankStatementFormat</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementFormat attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankStatementName name="BankStatementName">BankStatementName</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankSuffix name="BankSuffix">BankSuffix</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTransferCode name="BankTransferCode">BankTransferCode</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTransferCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CellularPhone name="CellularPhone">CellularPhone</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CellularPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyPaymId name="CompanyPaymId">CompanyPaymId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyPaymId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPerson name="ContactPerson">ContactPerson</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPerson attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrAccount_W name="CorrAccount_W">CorrAccount_W</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrAccount_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyOrder_TemplateName_RU name="CurrencyOrder_TemplateName_RU">CurrencyOrder_TemplateName_RU</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyOrder_TemplateName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencySellOrder_TemplateName_RU name="CurrencySellOrder_TemplateName_RU">CurrencySellOrder_TemplateName_RU</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencySellOrder_TemplateName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFeeLedgerDimension name="CustomerPaymentFeeLedgerDimension">CustomerPaymentFeeLedgerDimension</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFeeLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustPaymFeePost name="CustPaymFeePost">CustPaymFeePost</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPaymFeePost attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DebitDirectId name="DebitDirectId">DebitDirectId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitDirectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DiscCreditMaxMST name="DiscCreditMaxMST">DiscCreditMaxMST</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscCreditMaxMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DivisionPaymId name="DivisionPaymId">DivisionPaymId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DivisionPaymId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeContractAccount name="FeeContractAccount">FeeContractAccount</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeContractAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroContract name="GiroContract">GiroContract</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroContract attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroContractAccount name="GiroContractAccount">GiroContractAccount</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroContractAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IBAN name="IBAN">IBAN</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IBAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeBankBarCode_FI name="IncludeBankBarCode_FI">IncludeBankBarCode_FI</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeBankBarCode_FI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceRemitAmount name="InvoiceRemitAmount">InvoiceRemitAmount</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRemitAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceRemittanceLedgerDimension name="InvoiceRemittanceLedgerDimension">InvoiceRemittanceLedgerDimension</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRemittanceLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#isBankPrenote name="isBankPrenote">isBankPrenote</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isBankPrenote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerJournalNameId name="LedgerJournalNameId">LedgerJournalNameId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LvDefaultBank name="LvDefaultBank">LvDefaultBank</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LvDefaultBank attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LvPayOrderType name="LvPayOrderType">LvPayOrderType</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LvPayOrderType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NsfFeeMarkupGroupId name="NsfFeeMarkupGroupId">NsfFeeMarkupGroupId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NsfFeeMarkupGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NsfFeeMarkupGroupModule name="NsfFeeMarkupGroupModule">NsfFeeMarkupGroupModule</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NsfFeeMarkupGroupModule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#OverDraftLimit name="OverDraftLimit">OverDraftLimit</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverDraftLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Pager name="Pager">Pager</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Pager attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymForeignExportPath_LT name="PaymForeignExportPath_LT">PaymForeignExportPath_LT</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymForeignExportPath_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymLocalExportPath_LT name="PaymLocalExportPath_LT">PaymLocalExportPath_LT</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymLocalExportPath_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymOrderNumSeqId_W name="PaymOrderNumSeqId_W">PaymOrderNumSeqId_W</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymOrderNumSeqId_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Phone name="Phone">Phone</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneLocal name="PhoneLocal">PhoneLocal</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneLocal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrenoteResponseDays name="PrenoteResponseDays">PrenoteResponseDays</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrenoteResponseDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintGiro_FI name="PrintGiro_FI">PrintGiro_FI</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintGiro_FI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RegistrationNum name="RegistrationNum">RegistrationNum</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemitCollectionAmount name="RemitCollectionAmount">RemitCollectionAmount</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemitCollectionAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemitDiscountAmount name="RemitDiscountAmount">RemitDiscountAmount</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemitDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemittanceCollectionLedgerDimension name="RemittanceCollectionLedgerDimension">RemittanceCollectionLedgerDimension</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceCollectionLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RemittanceDiscountLedgerDimension name="RemittanceDiscountLedgerDimension">RemittanceDiscountLedgerDimension</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceDiscountLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Rfc_MX name="Rfc_MX">Rfc_MX</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rfc_MX attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SMS name="SMS">SMS</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SMS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecificSymbol name="SpecificSymbol">SpecificSymbol</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecificSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SWIFTNo name="SWIFTNo">SWIFTNo</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SWIFTNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TeleFax name="TeleFax">TeleFax</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeleFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Telex name="Telex">Telex</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Telex attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateFileName_RU name="TemplateFileName_RU">TemplateFileName_RU</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateFileName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransType_JP name="TransType_JP">TransType_JP</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransType_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the URL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankPositivePayFormat name="BankPositivePayFormat">BankPositivePayFormat</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankPositivePayFormat attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsNACHAFileBlocked name="IsNACHAFileBlocked">IsNACHAFileBlocked</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNACHAFileBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TemplateRefRecId_RU name="TemplateRefRecId_RU">TemplateRefRecId_RU</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateRefRecId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyOrder_TemplateRefRecId_RU name="CurrencyOrder_TemplateRefRecId_RU">CurrencyOrder_TemplateRefRecId_RU</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyOrder_TemplateRefRecId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencySellOrder_TemplateRefRecId_RU name="CurrencySellOrder_TemplateRefRecId_RU">CurrencySellOrder_TemplateRefRecId_RU</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencySellOrder_TemplateRefRecId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CFMBankBalanceMinimum name="CFMBankBalanceMinimum">CFMBankBalanceMinimum</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFMBankBalanceMinimum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PostingProfileBillsRemitCollection_IT name="PostingProfileBillsRemitCollection_IT">PostingProfileBillsRemitCollection_IT</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBillsRemitCollection_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileBillsRemitDiscount_IT name="PostingProfileBillsRemitDiscount_IT">PostingProfileBillsRemitDiscount_IT</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBillsRemitDiscount_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileRemitNotes_IT name="PostingProfileRemitNotes_IT">PostingProfileRemitNotes_IT</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileRemitNotes_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRIBAN_CH name="QRIBAN_CH">QRIBAN_CH</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRIBAN_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/BankAccountTable (this entity)  

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

### <a href=#Relationship_BankConstantSymbolRelationshipId name="Relationship_BankConstantSymbolRelationshipId">Relationship_BankConstantSymbolRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankConstantSymbolRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/BankConstantSymbol.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Miscellaneous/BankConstantSymbol.cdm.json/BankConstantSymbol</a></td><td><a href="../Miscellaneous/BankConstantSymbol.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankGroupRelationshipId name="Relationship_BankGroupRelationshipId">Relationship_BankGroupRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BankGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankGroup.cdm.json/BankGroup</a></td><td><a href="../Group/BankGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankReconciliationMatchRuleSetRelationshipId name="Relationship_BankReconciliationMatchRuleSetRelationshipId">Relationship_BankReconciliationMatchRuleSetRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankReconciliationMatchRuleSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/BankReconciliationMatchRuleSet.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Reference/BankReconciliationMatchRuleSet.cdm.json/BankReconciliationMatchRuleSet</a></td><td><a href="../Reference/BankReconciliationMatchRuleSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankStatementFormatRelationshipId name="Relationship_BankStatementFormatRelationshipId">Relationship_BankStatementFormatRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankStatementFormatRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/BankStatementFormat.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Reference/BankStatementFormat.cdm.json/BankStatementFormat</a></td><td><a href="../Reference/BankStatementFormat.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomerPaymentFeeLedgerDimensionRelationshipId name="Relationship_CustomerPaymentFeeLedgerDimensionRelationshipId">Relationship_CustomerPaymentFeeLedgerDimensionRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomerPaymentFeeLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvoiceRemittanceLedgerDimensionRelationshipId name="Relationship_InvoiceRemittanceLedgerDimensionRelationshipId">Relationship_InvoiceRemittanceLedgerDimensionRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceRemittanceLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerJournalName_LedJourNameIdRelationshipId name="Relationship_LedgerJournalName_LedJourNameIdRelationshipId">Relationship_LedgerJournalName_LedJourNameIdRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalName_LedJourNameIdRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerJournalName_NsfLedJourNameRelationshipId name="Relationship_LedgerJournalName_NsfLedJourNameRelationshipId">Relationship_LedgerJournalName_NsfLedJourNameRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalName_NsfLedJourNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Location_FKRelationshipId name="Relationship_Location_FKRelationshipId">Relationship_Location_FKRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Location_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsLocation.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsLocation.cdm.json/LogisticsLocation</a></td><td><a href="../../../Common/GAB/Main/LogisticsLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MarkupGroupRelationshipId name="Relationship_MarkupGroupRelationshipId">Relationship_MarkupGroupRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MarkupGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.cdm.json/MarkupGroup</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceTableRelationshipId name="Relationship_NumberSequenceTableRelationshipId">Relationship_NumberSequenceTableRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RemittanceCollectionLedgerDimensionRelationshipId name="Relationship_RemittanceCollectionLedgerDimensionRelationshipId">Relationship_RemittanceCollectionLedgerDimensionRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RemittanceCollectionLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RemittanceDiscountLedgerDimensionRelationshipId name="Relationship_RemittanceDiscountLedgerDimensionRelationshipId">Relationship_RemittanceDiscountLedgerDimensionRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RemittanceDiscountLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BankPositivePayFormatRelationshipId name="Relationship_BankPositivePayFormatRelationshipId">Relationship_BankPositivePayFormatRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankPositivePayFormatRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/BankPositivePayFormat.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Reference/BankPositivePayFormat.cdm.json/BankPositivePayFormat</a></td><td><a href="../Reference/BankPositivePayFormat.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TemplateDocuRefRelationshipId name="Relationship_TemplateDocuRefRelationshipId">Relationship_TemplateDocuRefRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TemplateDocuRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuRef.cdm.json/DocuRef</a></td><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyOrderTemplateDocuRefRelationshipId name="Relationship_CurrencyOrderTemplateDocuRefRelationshipId">Relationship_CurrencyOrderTemplateDocuRefRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyOrderTemplateDocuRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuRef.cdm.json/DocuRef</a></td><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencySellOrderDocuRefRelationshipId name="Relationship_CurrencySellOrderDocuRefRelationshipId">Relationship_CurrencySellOrderDocuRefRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencySellOrderDocuRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuRef.cdm.json/DocuRef</a></td><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_BillsRemitDisc_ITRelationshipId name="Relationship_CustLedger_BillsRemitDisc_ITRelationshipId">Relationship_CustLedger_BillsRemitDisc_ITRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_BillsRemitDisc_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Group/CustLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../../AccountsReceivable/Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_BillsRemitCollection_ITRelationshipId name="Relationship_CustLedger_BillsRemitCollection_ITRelationshipId">Relationship_CustLedger_BillsRemitCollection_ITRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_BillsRemitCollection_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Group/CustLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../../AccountsReceivable/Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedger_RemitNotes_ITRelationshipId name="Relationship_VendLedger_RemitNotes_ITRelationshipId">Relationship_VendLedger_RemitNotes_ITRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedger_RemitNotes_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Group/VendLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../../AccountsPayable/Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/BankAccountTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
