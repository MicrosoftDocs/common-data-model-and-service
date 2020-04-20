---
title: RetailTransactionAuditableTenderDeclarationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailTransactionAuditableTenderDeclarationEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Retail/RetailTransactionAuditableTenderDeclarationEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ChannelCurrency](#ChannelCurrency)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[AmountInTransactionCurrency](#AmountInTransactionCurrency)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[AmountInCompanyCurrency](#AmountInCompanyCurrency)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[AmountInChannelCurrency](#AmountInChannelCurrency)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[BusinessDate](#BusinessDate)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[TransactionCurrency](#TransactionCurrency)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[ForeignCurrencyExchangeRate](#ForeignCurrencyExchangeRate)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[CompanyCurrencyExchangeRate](#CompanyCurrencyExchangeRate)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[OperatorID](#OperatorID)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[statementCode](#statementCode)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[StatementNumber](#StatementNumber)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[PaymentMethod](#PaymentMethod)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[RegisterNumber](#RegisterNumber)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[TransactionId](#TransactionId)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[TransactionStatus](#TransactionStatus)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[TransactionTime](#TransactionTime)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[OperatingUnitRecId](#OperatingUnitRecId)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[HeaderStoreNumber](#HeaderStoreNumber)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[HeaderStatementNumber](#HeaderStatementNumber)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[BackingTable_RetailTransactionTenderDeclarationTransRelationshipId](#BackingTable_RetailTransactionTenderDeclarationTransRelationshipId)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionAuditableTenderDeclarationEntity.md" target="_blank">Retail/RetailTransactionAuditableTenderDeclarationEntity</a>|

### <a href=#ChannelCurrency name="ChannelCurrency">ChannelCurrency</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInTransactionCurrency name="AmountInTransactionCurrency">AmountInTransactionCurrency</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

### <a href=#TransactionCurrency name="TransactionCurrency">TransactionCurrency</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignCurrencyExchangeRate name="ForeignCurrencyExchangeRate">ForeignCurrencyExchangeRate</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

### <a href=#statementCode name="statementCode">statementCode</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementNumber name="StatementNumber">StatementNumber</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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

### <a href=#BackingTable_RetailTransactionTenderDeclarationTransRelationshipId name="BackingTable_RetailTransactionTenderDeclarationTransRelationshipId">BackingTable_RetailTransactionTenderDeclarationTransRelationshipId</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionTenderDeclarationTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Transaction/RetailTransactionTenderDeclarationTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailTransactionTenderDeclarationTrans.cdm.json/RetailTransactionTenderDeclarationTrans</a></td><td><a href="../../../Tables/Commerce/Retail/Transaction/RetailTransactionTenderDeclarationTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailTransactionAuditableTenderDeclarationEntity (this entity)  

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
