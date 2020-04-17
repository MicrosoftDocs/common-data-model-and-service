---
title: RetailTransactionPaymentLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RET3302

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailTransactionPaymentLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RET3302</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AmountInTenderedCurrency](#AmountInTenderedCurrency)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[AmountInAccountingCurrency](#AmountInAccountingCurrency)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[AmountTendered](#AmountTendered)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[CardOrAccount](#CardOrAccount)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[CardTypeId](#CardTypeId)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[IsChangeLine](#IsChangeLine)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[CreditVoucherId](#CreditVoucherId)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[ExchangeRateInTenderedCurrency](#ExchangeRateInTenderedCurrency)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[ExchangeRateInAccountingCurrency](#ExchangeRateInAccountingCurrency)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[GiftCardId](#GiftCardId)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[IsPrepayment](#IsPrepayment)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[LoyaltyCardId](#LoyaltyCardId)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[Quantity](#Quantity)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[ReceiptId](#ReceiptId)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[TenderType](#TenderType)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[Terminal](#Terminal)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[TransactionNumber](#TransactionNumber)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[TransactionStatus](#TransactionStatus)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[RetailChannelTableOMOperatingUnitID](#RetailChannelTableOMOperatingUnitID)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[CardNumber](#CardNumber)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[AccountNumber](#AccountNumber)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[VoidStatus](#VoidStatus)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[Staff](#Staff)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[AmountTenderedAdjustment](#AmountTenderedAdjustment)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[IsLinkedRefund](#IsLinkedRefund)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[LinkedPaymentStore](#LinkedPaymentStore)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[LinkedPaymentTerminal](#LinkedPaymentTerminal)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[LinkedPaymentTransactionNumber](#LinkedPaymentTransactionNumber)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[LinkedPaymentLineNumber](#LinkedPaymentLineNumber)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[LinkedPaymentCurrency](#LinkedPaymentCurrency)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[RefundableAmount](#RefundableAmount)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[PaymentCaptureToken](#PaymentCaptureToken)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[BackingTable_RetailTransactionPaymentTransRelationshipId](#BackingTable_RetailTransactionPaymentTransRelationshipId)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionPaymentLineEntity.md" target="_blank">Retail/RetailTransactionPaymentLineEntity</a>|

### <a href=#AmountInTenderedCurrency name="AmountInTenderedCurrency">AmountInTenderedCurrency</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInTenderedCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInAccountingCurrency name="AmountInAccountingCurrency">AmountInAccountingCurrency</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountTendered name="AmountTendered">AmountTendered</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountTendered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardOrAccount name="CardOrAccount">CardOrAccount</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardOrAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardTypeId name="CardTypeId">CardTypeId</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsChangeLine name="IsChangeLine">IsChangeLine</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsChangeLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditVoucherId name="CreditVoucherId">CreditVoucherId</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditVoucherId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

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

### <a href=#ExchangeRateInTenderedCurrency name="ExchangeRateInTenderedCurrency">ExchangeRateInTenderedCurrency</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateInTenderedCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateInAccountingCurrency name="ExchangeRateInAccountingCurrency">ExchangeRateInAccountingCurrency</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateInAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardId name="GiftCardId">GiftCardId</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrepayment name="IsPrepayment">IsPrepayment</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

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

### <a href=#LoyaltyCardId name="LoyaltyCardId">LoyaltyCardId</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyCardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptId name="ReceiptId">ReceiptId</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderType name="TenderType">TenderType</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionNumber name="TransactionNumber">TransactionNumber</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionStatus name="TransactionStatus">TransactionStatus</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelTableOMOperatingUnitID name="RetailChannelTableOMOperatingUnitID">RetailChannelTableOMOperatingUnitID</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelTableOMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardNumber name="CardNumber">CardNumber</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNumber name="AccountNumber">AccountNumber</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoidStatus name="VoidStatus">VoidStatus</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoidStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Staff name="Staff">Staff</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Staff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountTenderedAdjustment name="AmountTenderedAdjustment">AmountTenderedAdjustment</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountTenderedAdjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLinkedRefund name="IsLinkedRefund">IsLinkedRefund</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLinkedRefund attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinkedPaymentStore name="LinkedPaymentStore">LinkedPaymentStore</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinkedPaymentStore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinkedPaymentTerminal name="LinkedPaymentTerminal">LinkedPaymentTerminal</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinkedPaymentTerminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinkedPaymentTransactionNumber name="LinkedPaymentTransactionNumber">LinkedPaymentTransactionNumber</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinkedPaymentTransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinkedPaymentLineNumber name="LinkedPaymentLineNumber">LinkedPaymentLineNumber</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinkedPaymentLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinkedPaymentCurrency name="LinkedPaymentCurrency">LinkedPaymentCurrency</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinkedPaymentCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefundableAmount name="RefundableAmount">RefundableAmount</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefundableAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentCaptureToken name="PaymentCaptureToken">PaymentCaptureToken</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentCaptureToken attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTransactionPaymentTransRelationshipId name="BackingTable_RetailTransactionPaymentTransRelationshipId">BackingTable_RetailTransactionPaymentTransRelationshipId</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionPaymentTransRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailTransactionPaymentLineEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
