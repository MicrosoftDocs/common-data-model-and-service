---
title: BankCheckLayoutEntity in CashAndBankManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Check layout in CashAndBankManagement(BankCheckLayoutEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankCheckLayoutEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Check layout</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BankAccountId](#BankAccountId)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[AmountPrefix](#AmountPrefix)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintBankAccount](#PrintBankAccount)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[CustomWatermark](#CustomWatermark)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintBankName](#PrintBankName)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintBankNumber](#PrintBankNumber)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[ACode](#ACode)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[BCode](#BCode)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[CCode](#CCode)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[DateFormat](#DateFormat)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[DateSeparator](#DateSeparator)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[FormatType](#FormatType)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[CheckNumberMethod](#CheckNumberMethod)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[StartPositionUnit](#StartPositionUnit)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[NumberOfSlipCopies](#NumberOfSlipCopies)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[StartPosition](#StartPosition)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintCompanyLogo](#PrintCompanyLogo)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintCompanyName](#PrintCompanyName)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[CopySignatureType](#CopySignatureType)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[CopyWatermarkType](#CopyWatermarkType)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[FooterText](#FooterText)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[HeaderText](#HeaderText)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintMICRLine](#PrintMICRLine)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[MICRLine](#MICRLine)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[CheckNumberLength](#CheckNumberLength)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintLeadingZerosOnMICRLine](#PrintLeadingZerosOnMICRLine)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[AllowOtherCurrencies](#AllowOtherCurrencies)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PaperLength](#PaperLength)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PaperLengthUnit](#PaperLengthUnit)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintFirstSignature](#PrintFirstSignature)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[FirstSignatureAmountLimit](#FirstSignatureAmountLimit)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintSecondSignature](#PrintSecondSignature)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[SecondSignatureAmountLimit](#SecondSignatureAmountLimit)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintACode](#PrintACode)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintBCode](#PrintBCode)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[PrintCCode](#PrintCCode)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[CustomChequeLayout](#CustomChequeLayout)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[CustomChequeLayoutId](#CustomChequeLayoutId)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[Relationship_BankAccountRelationshipId](#Relationship_BankAccountRelationshipId)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[BackingTable_BankChequeLayoutRelationshipId](#BackingTable_BankChequeLayoutRelationshipId)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankCheckLayoutEntity.md" target="_blank">CashAndBankManagement/BankCheckLayoutEntity</a>|

### <a href=#BankAccountId name="BankAccountId">BankAccountId</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#AmountPrefix name="AmountPrefix">AmountPrefix</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#CustomWatermark name="CustomWatermark">CustomWatermark</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomWatermark attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBankName name="PrintBankName">PrintBankName</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#ACode name="ACode">ACode</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ACode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BCode name="BCode">BCode</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CCode name="CCode">CCode</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateFormat name="DateFormat">DateFormat</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateSeparator name="DateSeparator">DateSeparator</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateSeparator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormatType name="FormatType">FormatType</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#CheckNumberMethod name="CheckNumberMethod">CheckNumberMethod</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckNumberMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartPositionUnit name="StartPositionUnit">StartPositionUnit</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#PrintCompanyLogo name="PrintCompanyLogo">PrintCompanyLogo</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#CopySignatureType name="CopySignatureType">CopySignatureType</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopySignatureType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CopyWatermarkType name="CopyWatermarkType">CopyWatermarkType</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopyWatermarkType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FooterText name="FooterText">FooterText</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FooterText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderText name="HeaderText">HeaderText</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintMICRLine name="PrintMICRLine">PrintMICRLine</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintMICRLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MICRLine name="MICRLine">MICRLine</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MICRLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckNumberLength name="CheckNumberLength">CheckNumberLength</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckNumberLength attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintLeadingZerosOnMICRLine name="PrintLeadingZerosOnMICRLine">PrintLeadingZerosOnMICRLine</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintLeadingZerosOnMICRLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowOtherCurrencies name="AllowOtherCurrencies">AllowOtherCurrencies</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowOtherCurrencies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperLength name="PaperLength">PaperLength</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#PrintFirstSignature name="PrintFirstSignature">PrintFirstSignature</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#PrintACode name="PrintACode">PrintACode</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintACode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBCode name="PrintBCode">PrintBCode</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintCCode name="PrintCCode">PrintCCode</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomChequeLayout name="CustomChequeLayout">CustomChequeLayout</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomChequeLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomChequeLayoutId name="CustomChequeLayoutId">CustomChequeLayoutId</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomChequeLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankAccountRelationshipId name="Relationship_BankAccountRelationshipId">Relationship_BankAccountRelationshipId</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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

### <a href=#BackingTable_BankChequeLayoutRelationshipId name="BackingTable_BankChequeLayoutRelationshipId">BackingTable_BankChequeLayoutRelationshipId</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankChequeLayoutRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Main/BankChequeLayout.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/BankChequeLayout.cdm.json/BankChequeLayout</a></td><td><a href="../../../Tables/Finance/Bank/Main/BankChequeLayout.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankCheckLayoutEntity (this entity)  

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
