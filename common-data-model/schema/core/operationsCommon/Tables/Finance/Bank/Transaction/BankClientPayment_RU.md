---
title: BankClientPayment_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# BankClientPayment_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/Transaction/BankClientPayment_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankClientPayment_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[AccountID](#AccountID)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[AgreementBlocked](#AgreementBlocked)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[AgreementHeaderExt](#AgreementHeaderExt)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[AmountCur](#AmountCur)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[BankCurrencyDealCourse](#BankCurrencyDealCourse)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[BankTransactionType](#BankTransactionType)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[CurrencyCode](#CurrencyCode)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[CustVendAC](#CustVendAC)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[DefaultDimension](#DefaultDimension)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[DocumentDate](#DocumentDate)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[DocumentNumber](#DocumentNumber)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[DocumentTypeId](#DocumentTypeId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[ExchRate](#ExchRate)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Include](#Include)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[JournalNum](#JournalNum)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PartnerType](#PartnerType)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeAccount](#PayeeAccount)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeBankAccount](#PayeeBankAccount)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeBankAddress](#PayeeBankAddress)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeBankBIC](#PayeeBankBIC)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeBankCorrAccount](#PayeeBankCorrAccount)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeBankName](#PayeeBankName)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeINN](#PayeeINN)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeName](#PayeeName)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayeeRRC](#PayeeRRC)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerAccount](#PayerAccount)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerBankAccount](#PayerBankAccount)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerBankAddress](#PayerBankAddress)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerBankBIC](#PayerBankBIC)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerBankCorrAccount](#PayerBankCorrAccount)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerBankName](#PayerBankName)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerINN](#PayerINN)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerName](#PayerName)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PayerRRC](#PayerRRC)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PaymentDirection](#PaymentDirection)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PaymentPurpose](#PaymentPurpose)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Posted](#Posted)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[PostingProfile](#PostingProfile)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Prepayment](#Prepayment)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[ReceiptDate](#ReceiptDate)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[RefRecId](#RefRecId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[RefTableId](#RefTableId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[SlipContents](#SlipContents)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[SlipDate](#SlipDate)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[SlipTime](#SlipTime)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[TaxGroup](#TaxGroup)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[TransDate](#TransDate)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[TransferCurrencyCode](#TransferCurrencyCode)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[UnidentifiedText](#UnidentifiedText)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[UnrecognitionCause](#UnrecognitionCause)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Unrecognized](#Unrecognized)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Voucher](#Voucher)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[WriteoffDate](#WriteoffDate)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[UIN](#UIN)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_AgreementHeaderExtRelationshipId](#Relationship_AgreementHeaderExtRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_BankAccountTableRelationshipId](#Relationship_BankAccountTableRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_BankAccountTransRelationshipId](#Relationship_BankAccountTransRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_BankClientDocumentType_RURelationshipId](#Relationship_BankClientDocumentType_RURelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_BankPaymentOrderJourRelationshipId](#Relationship_BankPaymentOrderJourRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_BankTransTypeRelationshipId](#Relationship_BankTransTypeRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_CustPostingProfileRelationshipId](#Relationship_CustPostingProfileRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_LedgerJournalTableRelationshipId](#Relationship_LedgerJournalTableRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_LedgerJournalTransRefRecRelationshipId](#Relationship_LedgerJournalTransRefRecRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_TaxGroupHeadingRelationshipId](#Relationship_TaxGroupHeadingRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_TaxItemGroupHeadingRelationshipId](#Relationship_TaxItemGroupHeadingRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_TransferCurrencyRelationshipId](#Relationship_TransferCurrencyRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_VendPostingProfileRelationshipId](#Relationship_VendPostingProfileRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BankClientPayment_RU.md" target="_blank">Transaction/BankClientPayment_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankClientPayment_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountID name="AccountID">AccountID</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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

### <a href=#AgreementBlocked name="AgreementBlocked">AgreementBlocked</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AgreementHeaderExt name="AgreementHeaderExt">AgreementHeaderExt</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementHeaderExt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankCurrencyDealCourse name="BankCurrencyDealCourse">BankCurrencyDealCourse</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCurrencyDealCourse attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankTransactionType name="BankTransactionType">BankTransactionType</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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

### <a href=#CustVendAC name="CustVendAC">CustVendAC</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendAC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentTypeId name="DocumentTypeId">DocumentTypeId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Include name="Include">Include</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Include attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalNum name="JournalNum">JournalNum</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartnerType name="PartnerType">PartnerType</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartnerType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PayeeAccount name="PayeeAccount">PayeeAccount</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankAccount name="PayeeBankAccount">PayeeBankAccount</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankAddress name="PayeeBankAddress">PayeeBankAddress</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankBIC name="PayeeBankBIC">PayeeBankBIC</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankBIC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankCorrAccount name="PayeeBankCorrAccount">PayeeBankCorrAccount</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankCorrAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankName name="PayeeBankName">PayeeBankName</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeINN name="PayeeINN">PayeeINN</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeINN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeName name="PayeeName">PayeeName</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeRRC name="PayeeRRC">PayeeRRC</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeRRC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerAccount name="PayerAccount">PayerAccount</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankAccount name="PayerBankAccount">PayerBankAccount</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankAddress name="PayerBankAddress">PayerBankAddress</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankBIC name="PayerBankBIC">PayerBankBIC</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankBIC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankCorrAccount name="PayerBankCorrAccount">PayerBankCorrAccount</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankCorrAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankName name="PayerBankName">PayerBankName</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerINN name="PayerINN">PayerINN</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerINN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerName name="PayerName">PayerName</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerRRC name="PayerRRC">PayerRRC</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerRRC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDirection name="PaymentDirection">PaymentDirection</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDirection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymentPurpose name="PaymentPurpose">PaymentPurpose</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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

### <a href=#Prepayment name="Prepayment">Prepayment</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Prepayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReceiptDate name="ReceiptDate">ReceiptDate</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SlipContents name="SlipContents">SlipContents</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlipContents attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlipDate name="SlipDate">SlipDate</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlipDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SlipTime name="SlipTime">SlipTime</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlipTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransferCurrencyCode name="TransferCurrencyCode">TransferCurrencyCode</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnidentifiedText name="UnidentifiedText">UnidentifiedText</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnidentifiedText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrecognitionCause name="UnrecognitionCause">UnrecognitionCause</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrecognitionCause attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Unrecognized name="Unrecognized">Unrecognized</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Unrecognized attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteoffDate name="WriteoffDate">WriteoffDate</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteoffDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#UIN name="UIN">UIN</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UIN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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

### <a href=#Relationship_AgreementHeaderExtRelationshipId name="Relationship_AgreementHeaderExtRelationshipId">Relationship_AgreementHeaderExtRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AgreementHeaderExtRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/TransactionHeader/AgreementHeaderExt_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/TransactionHeader/AgreementHeaderExt_RU.cdm.json/AgreementHeaderExt_RU</a></td><td><a href="../../APARShared/TransactionHeader/AgreementHeaderExt_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankAccountTableRelationshipId name="Relationship_BankAccountTableRelationshipId">Relationship_BankAccountTableRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankAccountTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/BankAccountTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/BankAccountTable.cdm.json/BankAccountTable</a></td><td><a href="../Main/BankAccountTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankAccountTransRelationshipId name="Relationship_BankAccountTransRelationshipId">Relationship_BankAccountTransRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankAccountTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankAccountTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankAccountTrans.cdm.json/BankAccountTrans</a></td><td><a href="BankAccountTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankClientDocumentType_RURelationshipId name="Relationship_BankClientDocumentType_RURelationshipId">Relationship_BankClientDocumentType_RURelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankClientDocumentType_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BankClientDocumentType_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankClientDocumentType_RU.cdm.json/BankClientDocumentType_RU</a></td><td><a href="../Group/BankClientDocumentType_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankPaymentOrderJourRelationshipId name="Relationship_BankPaymentOrderJourRelationshipId">Relationship_BankPaymentOrderJourRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankPaymentOrderJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankPaymentOrderJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankPaymentOrderJour_RU.cdm.json/BankPaymentOrderJour_RU</a></td><td><a href="BankPaymentOrderJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankTransTypeRelationshipId name="Relationship_BankTransTypeRelationshipId">Relationship_BankTransTypeRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BankTransType.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankTransType.cdm.json/BankTransType</a></td><td><a href="../Group/BankTransType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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

### <a href=#Relationship_CustPostingProfileRelationshipId name="Relationship_CustPostingProfileRelationshipId">Relationship_CustPostingProfileRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPostingProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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

### <a href=#Relationship_LedgerJournalTableRelationshipId name="Relationship_LedgerJournalTableRelationshipId">Relationship_LedgerJournalTableRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetHeader/LedgerJournalTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetHeader/LedgerJournalTable.cdm.json/LedgerJournalTable</a></td><td><a href="../../AccountingFoundation/WorksheetHeader/LedgerJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTransRefRecRelationshipId name="Relationship_LedgerJournalTransRefRecRelationshipId">Relationship_LedgerJournalTransRefRecRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTransRefRecRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroupHeadingRelationshipId name="Relationship_TaxGroupHeadingRelationshipId">Relationship_TaxGroupHeadingRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxItemGroupHeadingRelationshipId name="Relationship_TaxItemGroupHeadingRelationshipId">Relationship_TaxItemGroupHeadingRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransferCurrencyRelationshipId name="Relationship_TransferCurrencyRelationshipId">Relationship_TransferCurrencyRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransferCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendPostingProfileRelationshipId name="Relationship_VendPostingProfileRelationshipId">Relationship_VendPostingProfileRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPostingProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/BankClientPayment_RU (this entity)  

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
