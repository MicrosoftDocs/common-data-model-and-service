---
title: VendorPaymentJournalLineEntity in AccountsPayable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Vendor payment journal line in AccountsPayable(VendorPaymentJournalLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendorPaymentJournalLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor payment journal line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Company](#Company)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[AccountType](#AccountType)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[CreditAmount](#CreditAmount)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[DebitAmount](#DebitAmount)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[CentralBankPurposeCode](#CentralBankPurposeCode)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[CentralBankPurposeText](#CentralBankPurposeText)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[CheckNumber](#CheckNumber)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[BankTransactionType](#BankTransactionType)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ThirdPartyBankAccountId](#ThirdPartyBankAccountId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[DefaultDimensionsForAccount](#DefaultDimensionsForAccount)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[CentralBankImportDate](#CentralBankImportDate)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Account](#Account)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[OffsetAccountType](#OffsetAccountType)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[OffsetCompany](#OffsetCompany)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[DefaultDimensionsForOffsetAccount](#DefaultDimensionsForOffsetAccount)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[OffsetAccount](#OffsetAccount)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[OffsetTransactionText](#OffsetTransactionText)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PaymentId](#PaymentId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PaymentMethodName](#PaymentMethodName)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PaymentReference](#PaymentReference)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PaymentSpecification](#PaymentSpecification)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[IsPrepayment](#IsPrepayment)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[UseSalesTaxDirectionFromMainAccount](#UseSalesTaxDirectionFromMainAccount)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[CalculateWithholdingTax](#CalculateWithholdingTax)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[TransactionText](#TransactionText)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Voucher](#Voucher)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[SecondaryExchangeRate](#SecondaryExchangeRate)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[DefaultDimensionsForAccountDisplayValue](#DefaultDimensionsForAccountDisplayValue)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[DefaultDimensionsForOffsetAccountDisplayValue](#DefaultDimensionsForOffsetAccountDisplayValue)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[AccountDisplayValue](#AccountDisplayValue)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[VendorName](#VendorName)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[OffsetAccountDisplayValue](#OffsetAccountDisplayValue)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[JournalBatchNumber](#JournalBatchNumber)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[NACHAIATForeignExchangeIndicator](#NACHAIATForeignExchangeIndicator)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[NACHAIATForeignExchangeReferenceIndicator](#NACHAIATForeignExchangeReferenceIndicator)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[NACHAIATForeignExchangeReference](#NACHAIATForeignExchangeReference)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[NACHAIATOFACScreeningIndicator](#NACHAIATOFACScreeningIndicator)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[NACHAIATOFACSecondaryScreeningIndicator](#NACHAIATOFACSecondaryScreeningIndicator)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[NACHAIATOriginatingDFIQualifier](#NACHAIATOriginatingDFIQualifier)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[NACHAIATReceivingDFIQualifier](#NACHAIATReceivingDFIQualifier)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckMaturityDate](#PostdatedCheckMaturityDate)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckReceivedDate](#PostdatedCheckReceivedDate)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckNumber](#PostdatedCheckNumber)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckStopPayment](#PostdatedCheckStopPayment)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckReasonForStop](#PostdatedCheckReasonForStop)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckBankName](#PostdatedCheckBankName)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckBankBranch](#PostdatedCheckBankBranch)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckIsReplacementCheck](#PostdatedCheckIsReplacementCheck)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckReplacementComments](#PostdatedCheckReplacementComments)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckOriginalCheckNumber](#PostdatedCheckOriginalCheckNumber)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckCashier](#PostdatedCheckCashier)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckCashierDisplayValue](#PostdatedCheckCashierDisplayValue)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckSalesperson](#PostdatedCheckSalesperson)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PostdatedCheckSalespersonDisplayValue](#PostdatedCheckSalespersonDisplayValue)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[FullPrimaryRemittanceAddress](#FullPrimaryRemittanceAddress)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressDescription](#RemittanceAddressDescription)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressCountry](#RemittanceAddressCountry)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressCountryISOCode](#RemittanceAddressCountryISOCode)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressState](#RemittanceAddressState)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressCounty](#RemittanceAddressCounty)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressCity](#RemittanceAddressCity)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressStreet](#RemittanceAddressStreet)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressZipCode](#RemittanceAddressZipCode)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressDistrictName](#RemittanceAddressDistrictName)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressLatitude](#RemittanceAddressLatitude)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressLongitude](#RemittanceAddressLongitude)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressValidTo](#RemittanceAddressValidTo)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressValidFrom](#RemittanceAddressValidFrom)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceAddressTimeZone](#RemittanceAddressTimeZone)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceLocationId](#RemittanceLocationId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RemittanceLocation](#RemittanceLocation)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ItemWithholdingTaxGroupCode](#ItemWithholdingTaxGroupCode)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ChineseVoucherTypeRecId](#ChineseVoucherTypeRecId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ChineseVoucherType](#ChineseVoucherType)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ChineseVoucher](#ChineseVoucher)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[CategoryPurpose](#CategoryPurpose)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ChargeBearer](#ChargeBearer)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[LocalInstrument](#LocalInstrument)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ServiceLevel](#ServiceLevel)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[FeeAccount](#FeeAccount)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ContactPerson](#ContactPerson)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[RestrictedForwarding](#RestrictedForwarding)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[InstructionKey1](#InstructionKey1)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[InstructionKey2](#InstructionKey2)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[InstructionKey3](#InstructionKey3)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[InstructionKey4](#InstructionKey4)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[PaymentStatus](#PaymentStatus)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[DueDate](#DueDate)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[DocumentNumber](#DocumentNumber)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[DateOfImport](#DateOfImport)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[TermsOfPayment](#TermsOfPayment)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[NewJournalBatchNumber](#NewJournalBatchNumber)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ErrorCodePayment](#ErrorCodePayment)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[SettleVoucher](#SettleVoucher)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[MarkedInvoice](#MarkedInvoice)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[MarkedInvoiceCompany](#MarkedInvoiceCompany)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ReportingCurrencyExchRate](#ReportingCurrencyExchRate)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[ReportingCurrencyExchRateSecondary](#ReportingCurrencyExchRateSecondary)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_DefaultDimensionsForAccountDimensionSetRelationshipId](#Relationship_DefaultDimensionsForAccountDimensionSetRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_DefaultDimensionsForOffsetAccountDimensionSetRelationshipId](#Relationship_DefaultDimensionsForOffsetAccountDimensionSetRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_AccountCombinationRelationshipId](#Relationship_AccountCombinationRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_OffsetAccountCombinationRelationshipId](#Relationship_OffsetAccountCombinationRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_TaxGroupRelationshipId](#Relationship_TaxGroupRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_TaxItemGroupRelationshipId](#Relationship_TaxItemGroupRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_PaymentJournalHeaderRelationshipId](#Relationship_PaymentJournalHeaderRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_LedgerVoucherTypeEntityRelationshipId](#Relationship_LedgerVoucherTypeEntityRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_VendorPaymentMethodRelationshipId](#Relationship_VendorPaymentMethodRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[BackingTable_LedgerJournalTransRelationshipId](#BackingTable_LedgerJournalTransRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendorPaymentJournalLineEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineEntity</a>|

### <a href=#Company name="Company">Company</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditAmount name="CreditAmount">CreditAmount</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitAmount name="DebitAmount">DebitAmount</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeCode name="CentralBankPurposeCode">CentralBankPurposeCode</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeText name="CentralBankPurposeText">CentralBankPurposeText</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckNumber name="CheckNumber">CheckNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTransactionType name="BankTransactionType">BankTransactionType</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyBankAccountId name="ThirdPartyBankAccountId">ThirdPartyBankAccountId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyBankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionsForAccount name="DefaultDimensionsForAccount">DefaultDimensionsForAccount</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionsForAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankImportDate name="CentralBankImportDate">CentralBankImportDate</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankImportDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Account name="Account">Account</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Account attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountType name="OffsetAccountType">OffsetAccountType</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetCompany name="OffsetCompany">OffsetCompany</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionsForOffsetAccount name="DefaultDimensionsForOffsetAccount">DefaultDimensionsForOffsetAccount</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionsForOffsetAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccount name="OffsetAccount">OffsetAccount</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetTransactionText name="OffsetTransactionText">OffsetTransactionText</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetTransactionText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentId name="PaymentId">PaymentId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMethodName name="PaymentMethodName">PaymentMethodName</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentReference name="PaymentReference">PaymentReference</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSpecification name="PaymentSpecification">PaymentSpecification</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSpecification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

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

### <a href=#IsPrepayment name="IsPrepayment">IsPrepayment</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseSalesTaxDirectionFromMainAccount name="UseSalesTaxDirectionFromMainAccount">UseSalesTaxDirectionFromMainAccount</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSalesTaxDirectionFromMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

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

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

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

### <a href=#CalculateWithholdingTax name="CalculateWithholdingTax">CalculateWithholdingTax</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateWithholdingTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionText name="TransactionText">TransactionText</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryExchangeRate name="SecondaryExchangeRate">SecondaryExchangeRate</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionsForAccountDisplayValue name="DefaultDimensionsForAccountDisplayValue">DefaultDimensionsForAccountDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionsForAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionsForOffsetAccountDisplayValue name="DefaultDimensionsForOffsetAccountDisplayValue">DefaultDimensionsForOffsetAccountDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionsForOffsetAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountDisplayValue name="AccountDisplayValue">AccountDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorName name="VendorName">VendorName</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountDisplayValue name="OffsetAccountDisplayValue">OffsetAccountDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalBatchNumber name="JournalBatchNumber">JournalBatchNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NACHAIATForeignExchangeIndicator name="NACHAIATForeignExchangeIndicator">NACHAIATForeignExchangeIndicator</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NACHAIATForeignExchangeIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NACHAIATForeignExchangeReferenceIndicator name="NACHAIATForeignExchangeReferenceIndicator">NACHAIATForeignExchangeReferenceIndicator</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NACHAIATForeignExchangeReferenceIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NACHAIATForeignExchangeReference name="NACHAIATForeignExchangeReference">NACHAIATForeignExchangeReference</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NACHAIATForeignExchangeReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NACHAIATOFACScreeningIndicator name="NACHAIATOFACScreeningIndicator">NACHAIATOFACScreeningIndicator</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NACHAIATOFACScreeningIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NACHAIATOFACSecondaryScreeningIndicator name="NACHAIATOFACSecondaryScreeningIndicator">NACHAIATOFACSecondaryScreeningIndicator</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NACHAIATOFACSecondaryScreeningIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NACHAIATOriginatingDFIQualifier name="NACHAIATOriginatingDFIQualifier">NACHAIATOriginatingDFIQualifier</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NACHAIATOriginatingDFIQualifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NACHAIATReceivingDFIQualifier name="NACHAIATReceivingDFIQualifier">NACHAIATReceivingDFIQualifier</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NACHAIATReceivingDFIQualifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckMaturityDate name="PostdatedCheckMaturityDate">PostdatedCheckMaturityDate</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckMaturityDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckReceivedDate name="PostdatedCheckReceivedDate">PostdatedCheckReceivedDate</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckReceivedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckNumber name="PostdatedCheckNumber">PostdatedCheckNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckStopPayment name="PostdatedCheckStopPayment">PostdatedCheckStopPayment</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckStopPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckReasonForStop name="PostdatedCheckReasonForStop">PostdatedCheckReasonForStop</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckReasonForStop attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckBankName name="PostdatedCheckBankName">PostdatedCheckBankName</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckBankBranch name="PostdatedCheckBankBranch">PostdatedCheckBankBranch</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckBankBranch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckIsReplacementCheck name="PostdatedCheckIsReplacementCheck">PostdatedCheckIsReplacementCheck</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckIsReplacementCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckReplacementComments name="PostdatedCheckReplacementComments">PostdatedCheckReplacementComments</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckReplacementComments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckOriginalCheckNumber name="PostdatedCheckOriginalCheckNumber">PostdatedCheckOriginalCheckNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckOriginalCheckNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckCashier name="PostdatedCheckCashier">PostdatedCheckCashier</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckCashier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckCashierDisplayValue name="PostdatedCheckCashierDisplayValue">PostdatedCheckCashierDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckCashierDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckSalesperson name="PostdatedCheckSalesperson">PostdatedCheckSalesperson</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckSalesperson attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostdatedCheckSalespersonDisplayValue name="PostdatedCheckSalespersonDisplayValue">PostdatedCheckSalespersonDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostdatedCheckSalespersonDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FullPrimaryRemittanceAddress name="FullPrimaryRemittanceAddress">FullPrimaryRemittanceAddress</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullPrimaryRemittanceAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressDescription name="RemittanceAddressDescription">RemittanceAddressDescription</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressCountry name="RemittanceAddressCountry">RemittanceAddressCountry</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressCountry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressCountryISOCode name="RemittanceAddressCountryISOCode">RemittanceAddressCountryISOCode</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressCountryISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressState name="RemittanceAddressState">RemittanceAddressState</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressCounty name="RemittanceAddressCounty">RemittanceAddressCounty</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressCity name="RemittanceAddressCity">RemittanceAddressCity</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressStreet name="RemittanceAddressStreet">RemittanceAddressStreet</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressZipCode name="RemittanceAddressZipCode">RemittanceAddressZipCode</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressDistrictName name="RemittanceAddressDistrictName">RemittanceAddressDistrictName</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressLatitude name="RemittanceAddressLatitude">RemittanceAddressLatitude</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressLongitude name="RemittanceAddressLongitude">RemittanceAddressLongitude</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressValidTo name="RemittanceAddressValidTo">RemittanceAddressValidTo</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressValidFrom name="RemittanceAddressValidFrom">RemittanceAddressValidFrom</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceAddressTimeZone name="RemittanceAddressTimeZone">RemittanceAddressTimeZone</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceLocationId name="RemittanceLocationId">RemittanceLocationId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceLocation name="RemittanceLocation">RemittanceLocation</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemWithholdingTaxGroupCode name="ItemWithholdingTaxGroupCode">ItemWithholdingTaxGroupCode</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemWithholdingTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChineseVoucherTypeRecId name="ChineseVoucherTypeRecId">ChineseVoucherTypeRecId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChineseVoucherTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChineseVoucherType name="ChineseVoucherType">ChineseVoucherType</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChineseVoucherType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChineseVoucher name="ChineseVoucher">ChineseVoucher</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChineseVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryPurpose name="CategoryPurpose">CategoryPurpose</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeBearer name="ChargeBearer">ChargeBearer</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeBearer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocalInstrument name="LocalInstrument">LocalInstrument</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocalInstrument attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLevel name="ServiceLevel">ServiceLevel</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeAccount name="FeeAccount">FeeAccount</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPerson name="ContactPerson">ContactPerson</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPerson attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictedForwarding name="RestrictedForwarding">RestrictedForwarding</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictedForwarding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstructionKey1 name="InstructionKey1">InstructionKey1</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstructionKey1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstructionKey2 name="InstructionKey2">InstructionKey2</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstructionKey2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstructionKey3 name="InstructionKey3">InstructionKey3</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstructionKey3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstructionKey4 name="InstructionKey4">InstructionKey4</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstructionKey4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentStatus name="PaymentStatus">PaymentStatus</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateOfImport name="DateOfImport">DateOfImport</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfImport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPayment name="TermsOfPayment">TermsOfPayment</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

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

### <a href=#NewJournalBatchNumber name="NewJournalBatchNumber">NewJournalBatchNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>New Journal Batch Number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewJournalBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>New Journal Batch Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorCodePayment name="ErrorCodePayment">ErrorCodePayment</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorCodePayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettleVoucher name="SettleVoucher">SettleVoucher</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettleVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkedInvoice name="MarkedInvoice">MarkedInvoice</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkedInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkedInvoiceCompany name="MarkedInvoiceCompany">MarkedInvoiceCompany</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkedInvoiceCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyExchRate name="ReportingCurrencyExchRate">ReportingCurrencyExchRate</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyExchRateSecondary name="ReportingCurrencyExchRateSecondary">ReportingCurrencyExchRateSecondary</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchRateSecondary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionsForAccountDimensionSetRelationshipId name="Relationship_DefaultDimensionsForAccountDimensionSetRelationshipId">Relationship_DefaultDimensionsForAccountDimensionSetRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionsForAccountDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultDimensionsForOffsetAccountDimensionSetRelationshipId name="Relationship_DefaultDimensionsForOffsetAccountDimensionSetRelationshipId">Relationship_DefaultDimensionsForOffsetAccountDimensionSetRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionsForOffsetAccountDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AccountCombinationRelationshipId name="Relationship_AccountCombinationRelationshipId">Relationship_AccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OffsetAccountCombinationRelationshipId name="Relationship_OffsetAccountCombinationRelationshipId">Relationship_OffsetAccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroupRelationshipId name="Relationship_TaxGroupRelationshipId">Relationship_TaxGroupRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxItemGroupRelationshipId name="Relationship_TaxItemGroupRelationshipId">Relationship_TaxItemGroupRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentJournalHeaderRelationshipId name="Relationship_PaymentJournalHeaderRelationshipId">Relationship_PaymentJournalHeaderRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentJournalHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerVoucherTypeEntityRelationshipId name="Relationship_LedgerVoucherTypeEntityRelationshipId">Relationship_LedgerVoucherTypeEntityRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerVoucherTypeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendorPaymentMethodRelationshipId name="Relationship_VendorPaymentMethodRelationshipId">Relationship_VendorPaymentMethodRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorPaymentMethodRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerJournalTransRelationshipId name="BackingTable_LedgerJournalTransRelationshipId">BackingTable_LedgerJournalTransRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineEntity (this entity)  

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
