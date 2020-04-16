---
title: RetailTransactionSafeTenderTransEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RET4596

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailTransactionSafeTenderTransEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RET4596</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[AmountCurrency](#AmountCurrency)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[AmountCurrencyPOS](#AmountCurrencyPOS)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[AmountMST](#AmountMST)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[AmountMSTPOS](#AmountMSTPOS)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[AmountTendered](#AmountTendered)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[AmountTenderedPOS](#AmountTenderedPOS)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[BusinessDate](#BusinessDate)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[CardOrAccount](#CardOrAccount)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[CardTypeId](#CardTypeId)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[ChangeLine](#ChangeLine)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[Counter](#Counter)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[Currency](#Currency)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[ExchangeRateMST](#ExchangeRateMST)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[ManagersKeyLive](#ManagersKeyLive)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[MessageNumber](#MessageNumber)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[Quantity](#Quantity)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[Replicated](#Replicated)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[Shift](#Shift)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[ShiftDate](#ShiftDate)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[Staff](#Staff)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[StatementCode](#StatementCode)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[StatementId](#StatementId)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[SafeStatusType](#SafeStatusType)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[TenderType](#TenderType)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[Terminal](#Terminal)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[TransactionNumber](#TransactionNumber)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[TransactionStatus](#TransactionStatus)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[TransactionTime](#TransactionTime)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[RetailChannelId](#RetailChannelId)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[BackingTable_RetailTransactionSafeTenderTransRelationshipId](#BackingTable_RetailTransactionSafeTenderTransRelationshipId)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionSafeTenderTransEntity.md" target="_blank">Retail/RetailTransactionSafeTenderTransEntity</a>|

### <a href=#AmountCurrency name="AmountCurrency">AmountCurrency</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountCurrencyPOS name="AmountCurrencyPOS">AmountCurrencyPOS</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCurrencyPOS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountMST name="AmountMST">AmountMST</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountMST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountMSTPOS name="AmountMSTPOS">AmountMSTPOS</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountMSTPOS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountTendered name="AmountTendered">AmountTendered</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountTendered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountTenderedPOS name="AmountTenderedPOS">AmountTenderedPOS</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountTenderedPOS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessDate name="BusinessDate">BusinessDate</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardOrAccount name="CardOrAccount">CardOrAccount</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeLine name="ChangeLine">ChangeLine</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Counter name="Counter">Counter</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Counter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateMST name="ExchangeRateMST">ExchangeRateMST</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateMST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManagersKeyLive name="ManagersKeyLive">ManagersKeyLive</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManagersKeyLive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessageNumber name="MessageNumber">MessageNumber</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Replicated name="Replicated">Replicated</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Replicated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Shift name="Shift">Shift</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Shift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShiftDate name="ShiftDate">ShiftDate</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Staff name="Staff">Staff</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Staff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementCode name="StatementCode">StatementCode</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementId name="StatementId">StatementId</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeStatusType name="SafeStatusType">SafeStatusType</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeStatusType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderType name="TenderType">TenderType</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionTime name="TransactionTime">TransactionTime</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelId name="RetailChannelId">RetailChannelId</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTransactionSafeTenderTransRelationshipId name="BackingTable_RetailTransactionSafeTenderTransRelationshipId">BackingTable_RetailTransactionSafeTenderTransRelationshipId</a>

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionSafeTenderTransRelationshipId attribute are listed below.</summary>

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

First included in: Retail/RetailTransactionSafeTenderTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

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
