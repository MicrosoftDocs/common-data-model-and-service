---
title: RetailTransactionAuditableSafeDropEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailTransactionAuditableSafeDropEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailTransactionAuditableSafeDropEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AmountInTransactionCurrency](#AmountInTransactionCurrency)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[AmountInCompanyCurrency](#AmountInCompanyCurrency)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[AmountInChannelCurrency](#AmountInChannelCurrency)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[BusinessDate](#BusinessDate)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[Currency](#Currency)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[ForeignCurrencyExchangeRate](#ForeignCurrencyExchangeRate)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[CompanyCurrencyExchangeRate](#CompanyCurrencyExchangeRate)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[OperatorID](#OperatorID)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[StatementCode](#StatementCode)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[StatementNumber](#StatementNumber)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[Status](#Status)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[PaymentMethod](#PaymentMethod)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[RegisterNumber](#RegisterNumber)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[TransactionId](#TransactionId)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[TransactionStatus](#TransactionStatus)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[TransactionTime](#TransactionTime)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[OperatingUnitRecId](#OperatingUnitRecId)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[HeaderStoreNumber](#HeaderStoreNumber)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[HeaderStatementNumber](#HeaderStatementNumber)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[BackingTable_RetailTransactionSafeTenderTransRelationshipId](#BackingTable_RetailTransactionSafeTenderTransRelationshipId)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionAuditableSafeDropEntity.md" target="_blank">Retail/RetailTransactionAuditableSafeDropEntity</a>|

### <a href=#AmountInTransactionCurrency name="AmountInTransactionCurrency">AmountInTransactionCurrency</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInCompanyCurrency name="AmountInCompanyCurrency">AmountInCompanyCurrency</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInCompanyCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInChannelCurrency name="AmountInChannelCurrency">AmountInChannelCurrency</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInChannelCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessDate name="BusinessDate">BusinessDate</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

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

### <a href=#Currency name="Currency">Currency</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignCurrencyExchangeRate name="ForeignCurrencyExchangeRate">ForeignCurrencyExchangeRate</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignCurrencyExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCurrencyExchangeRate name="CompanyCurrencyExchangeRate">CompanyCurrencyExchangeRate</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCurrencyExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

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

### <a href=#OperatorID name="OperatorID">OperatorID</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatorID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementCode name="StatementCode">StatementCode</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementNumber name="StatementNumber">StatementNumber</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMethod name="PaymentMethod">PaymentMethod</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegisterNumber name="RegisterNumber">RegisterNumber</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegisterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionStatus name="TransactionStatus">TransactionStatus</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

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

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitRecId name="OperatingUnitRecId">OperatingUnitRecId</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

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

### <a href=#HeaderStoreNumber name="HeaderStoreNumber">HeaderStoreNumber</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderStoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderStatementNumber name="HeaderStatementNumber">HeaderStatementNumber</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTransactionSafeTenderTransRelationshipId name="BackingTable_RetailTransactionSafeTenderTransRelationshipId">BackingTable_RetailTransactionSafeTenderTransRelationshipId</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionSafeTenderTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Transaction/RetailTransactionSafeTenderTrans.md" target="_blank">/core/erp/Tables/Commerce/Retail/Transaction/RetailTransactionSafeTenderTrans.cdm.json/RetailTransactionSafeTenderTrans</a></td><td><a href="../../../Tables/Commerce/Retail/Transaction/RetailTransactionSafeTenderTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailTransactionAuditableSafeDropEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
