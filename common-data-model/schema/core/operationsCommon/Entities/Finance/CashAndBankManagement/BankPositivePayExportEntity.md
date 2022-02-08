---
title: BankPositivePayExportEntity in CashAndBankManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Bank positive pay transaction table in CashAndBankManagement(BankPositivePayExportEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankPositivePayExportEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank positive pay transaction table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CompanyId](#CompanyId)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[PositivePayNumber](#PositivePayNumber)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[VoidedDate](#VoidedDate)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[VoidedUser](#VoidedUser)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[ChequeNum](#ChequeNum)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[AmountCur](#AmountCur)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[TransDate](#TransDate)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[ChequeStatus](#ChequeStatus)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[BankNegInstRecipientName](#BankNegInstRecipientName)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[RecipientAccountNum](#RecipientAccountNum)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[AccountNum](#AccountNum)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[RegistrationNum](#RegistrationNum)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[CompanyPaymId](#CompanyPaymId)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[CustGroup](#CustGroup)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[VendGroup](#VendGroup)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[RecipientType](#RecipientType)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[BankAccountId](#BankAccountId)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|
|[BackingTable_BankPositivePayTransRelationshipId](#BackingTable_BankPositivePayTransRelationshipId)||<a href="BankPositivePayExportEntity.md" target="_blank">CashAndBankManagement/BankPositivePayExportEntity</a>|

### <a href=#CompanyId name="CompanyId">CompanyId</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositivePayNumber name="PositivePayNumber">PositivePayNumber</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositivePayNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoidedDate name="VoidedDate">VoidedDate</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoidedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoidedUser name="VoidedUser">VoidedUser</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoidedUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChequeNum name="ChequeNum">ChequeNum</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChequeNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChequeStatus name="ChequeStatus">ChequeStatus</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChequeStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankNegInstRecipientName name="BankNegInstRecipientName">BankNegInstRecipientName</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankNegInstRecipientName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecipientAccountNum name="RecipientAccountNum">RecipientAccountNum</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecipientAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationNum name="RegistrationNum">RegistrationNum</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyPaymId name="CompanyPaymId">CompanyPaymId</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyPaymId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

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

### <a href=#CustGroup name="CustGroup">CustGroup</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendGroup name="VendGroup">VendGroup</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecipientType name="RecipientType">RecipientType</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecipientType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountId name="BankAccountId">BankAccountId</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BankPositivePayTransRelationshipId name="BackingTable_BankPositivePayTransRelationshipId">BackingTable_BankPositivePayTransRelationshipId</a>

First included in: CashAndBankManagement/BankPositivePayExportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankPositivePayTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Transaction/BankPositivePayTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankPositivePayTrans.cdm.json/BankPositivePayTrans</a></td><td><a href="../../../Tables/Finance/Bank/Transaction/BankPositivePayTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
