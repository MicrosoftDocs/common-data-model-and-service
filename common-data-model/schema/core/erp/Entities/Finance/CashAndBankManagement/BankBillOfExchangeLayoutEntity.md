---
title: BankBillOfExchangeLayoutEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# BankBillOfExchangeLayoutEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Finance/CashAndBankManagement/BankBillOfExchangeLayoutEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AmountPrefix](#AmountPrefix)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintBankAccount](#PrintBankAccount)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[BankAccountId](#BankAccountId)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintBankCity](#PrintBankCity)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintBankName](#PrintBankName)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintBankNumber](#PrintBankNumber)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintCompanyLogo](#PrintCompanyLogo)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintCompanyName](#PrintCompanyName)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintDueDate](#PrintDueDate)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[FormatType](#FormatType)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[NumberMethod](#NumberMethod)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[StartPositionUnit](#StartPositionUnit)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[NumberOfSlipCopies](#NumberOfSlipCopies)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[StartPosition](#StartPosition)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PaperLength](#PaperLength)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PaperLengthUnit](#PaperLengthUnit)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintFirstSignature](#PrintFirstSignature)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[FirstSignatureAmountLimit](#FirstSignatureAmountLimit)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintSecondSignature](#PrintSecondSignature)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[SecondSignatureAmountLimit](#SecondSignatureAmountLimit)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[PrintTransactionDate](#PrintTransactionDate)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[Relationship_BankAccountRelationshipId](#Relationship_BankAccountRelationshipId)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[BackingTable_BankBillOfExchangeLayoutRelationshipId](#BackingTable_BankBillOfExchangeLayoutRelationshipId)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankBillOfExchangeLayoutEntity.md" target="_blank">CashAndBankManagement/BankBillOfExchangeLayoutEntity</a>|

### <a href=#AmountPrefix name="AmountPrefix">AmountPrefix</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBankAccount name="PrintBankAccount">PrintBankAccount</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountId name="BankAccountId">BankAccountId</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBankCity name="PrintBankCity">PrintBankCity</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBankCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBankName name="PrintBankName">PrintBankName</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBankNumber name="PrintBankNumber">PrintBankNumber</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBankNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintCompanyLogo name="PrintCompanyLogo">PrintCompanyLogo</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCompanyLogo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintCompanyName name="PrintCompanyName">PrintCompanyName</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintDueDate name="PrintDueDate">PrintDueDate</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormatType name="FormatType">FormatType</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormatType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberMethod name="NumberMethod">NumberMethod</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartPositionUnit name="StartPositionUnit">StartPositionUnit</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartPositionUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfSlipCopies name="NumberOfSlipCopies">NumberOfSlipCopies</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfSlipCopies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartPosition name="StartPosition">StartPosition</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartPosition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperLength name="PaperLength">PaperLength</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaperLength attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperLengthUnit name="PaperLengthUnit">PaperLengthUnit</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaperLengthUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFirstSignature name="PrintFirstSignature">PrintFirstSignature</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFirstSignature attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstSignatureAmountLimit name="FirstSignatureAmountLimit">FirstSignatureAmountLimit</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstSignatureAmountLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintSecondSignature name="PrintSecondSignature">PrintSecondSignature</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintSecondSignature attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondSignatureAmountLimit name="SecondSignatureAmountLimit">SecondSignatureAmountLimit</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondSignatureAmountLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintTransactionDate name="PrintTransactionDate">PrintTransactionDate</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankAccountRelationshipId name="Relationship_BankAccountRelationshipId">Relationship_BankAccountRelationshipId</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankAccountRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BankBillOfExchangeLayoutRelationshipId name="BackingTable_BankBillOfExchangeLayoutRelationshipId">BackingTable_BankBillOfExchangeLayoutRelationshipId</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankBillOfExchangeLayoutRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Main/BankBillOfExchangeLayout.md" target="_blank">/core/erp/Tables/Finance/Bank/Main/BankBillOfExchangeLayout.cdm.json/BankBillOfExchangeLayout</a></td><td><a href="../../../Tables/Finance/Bank/Main/BankBillOfExchangeLayout.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankBillOfExchangeLayoutEntity (this entity)  

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
