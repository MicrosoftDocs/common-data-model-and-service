---
title: GiroReportTmp - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# GIRO report data

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/APARShared/Miscellaneous/GiroReportTmp.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GiroReportTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>GIRO report data</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNo1_CH](#AccountNo1_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNo2_CH](#AccountNo2_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNum](#AccountNum)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNum1_FI](#AccountNum1_FI)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNum2_FI](#AccountNum2_FI)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNum3_FI](#AccountNum3_FI)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNum4_FI](#AccountNum4_FI)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNum5_FI](#AccountNum5_FI)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AccountNum6_FI](#AccountNum6_FI)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AltRecId](#AltRecId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[AmountCheckId](#AmountCheckId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[BankAccountTable_AccountNum_CH](#BankAccountTable_AccountNum_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[BankAccountTable_Clearing_CH](#BankAccountTable_Clearing_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[BankGroupIdName_CH](#BankGroupIdName_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[BankZipCode_CH](#BankZipCode_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[CompanyAddress](#CompanyAddress)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[CompanyGiro](#CompanyGiro)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[CompanyName](#CompanyName)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[CompanyPhone](#CompanyPhone)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[currencyCodeISO_CH](#currencyCodeISO_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[CustAddress_CH](#CustAddress_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[CustName_CH](#CustName_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[Description_CH](#Description_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[DueDate](#DueDate)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[FICreditorID_DK](#FICreditorID_DK)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[GiroType](#GiroType)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceAddress](#InvoiceAddress)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceAmountDecimals](#InvoiceAmountDecimals)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceAmountNODecimals](#InvoiceAmountNODecimals)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceId](#InvoiceId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceName](#InvoiceName)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceReferenceNumberFI](#InvoiceReferenceNumberFI)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[IsInvoiceAmount](#IsInvoiceAmount)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[JournalRecId](#JournalRecId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[LayoutCode_CH](#LayoutCode_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[OcrField](#OcrField)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[OcrLine_CH](#OcrLine_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[OcrLine_FI](#OcrLine_FI)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[PaymentId2_PaymentId3_CH](#PaymentId2_PaymentId3_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[PaymentRef1_CH](#PaymentRef1_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[PaymentRef2_CH](#PaymentRef2_CH)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[RemainAmountToBePaid](#RemainAmountToBePaid)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[QRCode](#QRCode)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[IBAN](#IBAN)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceAddressLine1](#InvoiceAddressLine1)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceAddressLine2](#InvoiceAddressLine2)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceCountryRegionId](#InvoiceCountryRegionId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceDate](#InvoiceDate)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[BillInformation](#BillInformation)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[CompanyAddressLine1](#CompanyAddressLine1)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[CompanyAddressLine2](#CompanyAddressLine2)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[InvoiceAmountTotal](#InvoiceAmountTotal)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[PrintScissorsSymbol](#PrintScissorsSymbol)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[DataAreaId](#DataAreaId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[Relationship_CustInvoiceJourRelationshipId](#Relationship_CustInvoiceJourRelationshipId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[Relationship_CustTable_InvoiceAccountRelationshipId](#Relationship_CustTable_InvoiceAccountRelationshipId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[Relationship_ISOCurrencyCodeRelationshipId](#Relationship_ISOCurrencyCodeRelationshipId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="GiroReportTmp.md" target="_blank">Miscellaneous/GiroReportTmp</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GiroReportTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountNo1_CH name="AccountNo1_CH">AccountNo1_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNo1_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNo2_CH name="AccountNo2_CH">AccountNo2_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNo2_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum1_FI name="AccountNum1_FI">AccountNum1_FI</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum1_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum2_FI name="AccountNum2_FI">AccountNum2_FI</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum2_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum3_FI name="AccountNum3_FI">AccountNum3_FI</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum3_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum4_FI name="AccountNum4_FI">AccountNum4_FI</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum4_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum5_FI name="AccountNum5_FI">AccountNum5_FI</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum5_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum6_FI name="AccountNum6_FI">AccountNum6_FI</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum6_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AltRecId name="AltRecId">AltRecId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AltRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountCheckId name="AmountCheckId">AmountCheckId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCheckId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountTable_AccountNum_CH name="BankAccountTable_AccountNum_CH">BankAccountTable_AccountNum_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountTable_AccountNum_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountTable_Clearing_CH name="BankAccountTable_Clearing_CH">BankAccountTable_Clearing_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountTable_Clearing_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankGroupIdName_CH name="BankGroupIdName_CH">BankGroupIdName_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankGroupIdName_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankZipCode_CH name="BankZipCode_CH">BankZipCode_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankZipCode_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyAddress name="CompanyAddress">CompanyAddress</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyGiro name="CompanyGiro">CompanyGiro</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyGiro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyName name="CompanyName">CompanyName</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyPhone name="CompanyPhone">CompanyPhone</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#currencyCodeISO_CH name="currencyCodeISO_CH">currencyCodeISO_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the currencyCodeISO_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAddress_CH name="CustAddress_CH">CustAddress_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAddress_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustName_CH name="CustName_CH">CustName_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustName_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description_CH name="Description_CH">Description_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FICreditorID_DK name="FICreditorID_DK">FICreditorID_DK</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FICreditorID_DK attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroType name="GiroType">GiroType</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddress name="InvoiceAddress">InvoiceAddress</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceAmountDecimals name="InvoiceAmountDecimals">InvoiceAmountDecimals</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountDecimals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAmountNODecimals name="InvoiceAmountNODecimals">InvoiceAmountNODecimals</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountNODecimals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceName name="InvoiceName">InvoiceName</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceReferenceNumberFI name="InvoiceReferenceNumberFI">InvoiceReferenceNumberFI</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceReferenceNumberFI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoiceAmount name="IsInvoiceAmount">IsInvoiceAmount</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalRecId name="JournalRecId">JournalRecId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LayoutCode_CH name="LayoutCode_CH">LayoutCode_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutCode_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OcrField name="OcrField">OcrField</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OcrField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OcrLine_CH name="OcrLine_CH">OcrLine_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OcrLine_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OcrLine_FI name="OcrLine_FI">OcrLine_FI</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OcrLine_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentId2_PaymentId3_CH name="PaymentId2_PaymentId3_CH">PaymentId2_PaymentId3_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId2_PaymentId3_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentRef1_CH name="PaymentRef1_CH">PaymentRef1_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentRef1_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentRef2_CH name="PaymentRef2_CH">PaymentRef2_CH</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentRef2_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainAmountToBePaid name="RemainAmountToBePaid">RemainAmountToBePaid</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainAmountToBePaid attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QRCode name="QRCode">QRCode</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCode attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#IBAN name="IBAN">IBAN</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IBAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLine1 name="InvoiceAddressLine1">InvoiceAddressLine1</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLine2 name="InvoiceAddressLine2">InvoiceAddressLine2</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCountryRegionId name="InvoiceCountryRegionId">InvoiceCountryRegionId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#BillInformation name="BillInformation">BillInformation</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyAddressLine1 name="CompanyAddressLine1">CompanyAddressLine1</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyAddressLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyAddressLine2 name="CompanyAddressLine2">CompanyAddressLine2</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyAddressLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAmountTotal name="InvoiceAmountTotal">InvoiceAmountTotal</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrintScissorsSymbol name="PrintScissorsSymbol">PrintScissorsSymbol</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintScissorsSymbol attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

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

### <a href=#Relationship_CustInvoiceJourRelationshipId name="Relationship_CustInvoiceJourRelationshipId">Relationship_CustInvoiceJourRelationshipId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustInvoiceJour.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustInvoiceJour.cdm.json/CustInvoiceJour</a></td><td><a href="../../AccountsReceivable/Transaction/CustInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

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

### <a href=#Relationship_CustTable_InvoiceAccountRelationshipId name="Relationship_CustTable_InvoiceAccountRelationshipId">Relationship_CustTable_InvoiceAccountRelationshipId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_InvoiceAccountRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ISOCurrencyCodeRelationshipId name="Relationship_ISOCurrencyCodeRelationshipId">Relationship_ISOCurrencyCodeRelationshipId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ISOCurrencyCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Reference/ISOCurrencyCode.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Reference/ISOCurrencyCode.cdm.json/ISOCurrencyCode</a></td><td><a href="../../../Common/Currency/Reference/ISOCurrencyCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/GiroReportTmp (this entity)  

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
