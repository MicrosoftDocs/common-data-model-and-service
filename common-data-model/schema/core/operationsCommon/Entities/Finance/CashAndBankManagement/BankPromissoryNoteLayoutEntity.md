---
title: BankPromissoryNoteLayoutEntity in CashAndBankManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Promissory note layout in CashAndBankManagement(BankPromissoryNoteLayoutEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankPromissoryNoteLayoutEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Promissory note layout</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AmountPrefix](#AmountPrefix)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintBankAccount](#PrintBankAccount)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[BankAccountId](#BankAccountId)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintBankCity](#PrintBankCity)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintBankName](#PrintBankName)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintBankNumber](#PrintBankNumber)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintCompanyLogo](#PrintCompanyLogo)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintCompanyName](#PrintCompanyName)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintDueDate](#PrintDueDate)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[FormatNoteNumber](#FormatNoteNumber)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[FormatType](#FormatType)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[NumberMethod](#NumberMethod)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[StartPositionUnit](#StartPositionUnit)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[NumberOfSlipCopies](#NumberOfSlipCopies)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[StartPosition](#StartPosition)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PaperLength](#PaperLength)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PaperLengthUnit](#PaperLengthUnit)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PaperFormat](#PaperFormat)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintFirstSignature](#PrintFirstSignature)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[FirstSignatureAmountLimit](#FirstSignatureAmountLimit)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintSecondSignature](#PrintSecondSignature)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[SecondSignatureAmountLimit](#SecondSignatureAmountLimit)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[PrintTransactionDate](#PrintTransactionDate)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[BackingTable_BankPromissoryNoteLayoutRelationshipId](#BackingTable_BankPromissoryNoteLayoutRelationshipId)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankPromissoryNoteLayoutEntity.md" target="_blank">CashAndBankManagement/BankPromissoryNoteLayoutEntity</a>|

### <a href=#AmountPrefix name="AmountPrefix">AmountPrefix</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBankAccount name="PrintBankAccount">PrintBankAccount</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountId name="BankAccountId">BankAccountId</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

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

### <a href=#PrintBankCity name="PrintBankCity">PrintBankCity</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBankCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBankName name="PrintBankName">PrintBankName</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBankNumber name="PrintBankNumber">PrintBankNumber</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBankNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintCompanyLogo name="PrintCompanyLogo">PrintCompanyLogo</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCompanyLogo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintCompanyName name="PrintCompanyName">PrintCompanyName</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintDueDate name="PrintDueDate">PrintDueDate</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormatNoteNumber name="FormatNoteNumber">FormatNoteNumber</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormatNoteNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormatType name="FormatType">FormatType</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormatType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberMethod name="NumberMethod">NumberMethod</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartPositionUnit name="StartPositionUnit">StartPositionUnit</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartPositionUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfSlipCopies name="NumberOfSlipCopies">NumberOfSlipCopies</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfSlipCopies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartPosition name="StartPosition">StartPosition</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartPosition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperLength name="PaperLength">PaperLength</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaperLength attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperLengthUnit name="PaperLengthUnit">PaperLengthUnit</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaperLengthUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperFormat name="PaperFormat">PaperFormat</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaperFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFirstSignature name="PrintFirstSignature">PrintFirstSignature</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFirstSignature attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstSignatureAmountLimit name="FirstSignatureAmountLimit">FirstSignatureAmountLimit</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstSignatureAmountLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintSecondSignature name="PrintSecondSignature">PrintSecondSignature</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintSecondSignature attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondSignatureAmountLimit name="SecondSignatureAmountLimit">SecondSignatureAmountLimit</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondSignatureAmountLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintTransactionDate name="PrintTransactionDate">PrintTransactionDate</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BankPromissoryNoteLayoutRelationshipId name="BackingTable_BankPromissoryNoteLayoutRelationshipId">BackingTable_BankPromissoryNoteLayoutRelationshipId</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankPromissoryNoteLayoutRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Main/BankPromissoryNoteLayout.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/BankPromissoryNoteLayout.cdm.json/BankPromissoryNoteLayout</a></td><td><a href="../../../Tables/Finance/Bank/Main/BankPromissoryNoteLayout.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankPromissoryNoteLayoutEntity (this entity)  

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
