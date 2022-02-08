---
title: VendPaymentBIVendorCustomerBalanceEntityV2 in AccountsPayable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Vendors in AccountsPayable(VendPaymentBIVendorCustomerBalanceEntityV2)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendors</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountNum](#AccountNum)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[Party](#Party)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[TotalCustAmountCur](#TotalCustAmountCur)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[TotalVendAmountCur](#TotalVendAmountCur)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[TotalCustAmountMST](#TotalCustAmountMST)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[TotalVendAmountMST](#TotalVendAmountMST)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[AccountingCurrency](#AccountingCurrency)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[TotalCustAmountSystem](#TotalCustAmountSystem)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[TotalVendAmountSystem](#TotalVendAmountSystem)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[SystemCurrencyCode](#SystemCurrencyCode)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[CustAccountNum](#CustAccountNum)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[PartyName](#PartyName)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[Company](#Company)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendPaymentBIVendorCustomerBalanceEntityV2.md" target="_blank">AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2</a>|

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

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

### <a href=#Party name="Party">Party</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Party attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalCustAmountCur name="TotalCustAmountCur">TotalCustAmountCur</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCustAmountCur attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalVendAmountCur name="TotalVendAmountCur">TotalVendAmountCur</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalVendAmountCur attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalCustAmountMST name="TotalCustAmountMST">TotalCustAmountMST</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCustAmountMST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalVendAmountMST name="TotalVendAmountMST">TotalVendAmountMST</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalVendAmountMST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingCurrency name="AccountingCurrency">AccountingCurrency</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalCustAmountSystem name="TotalCustAmountSystem">TotalCustAmountSystem</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCustAmountSystem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalVendAmountSystem name="TotalVendAmountSystem">TotalVendAmountSystem</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalVendAmountSystem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SystemCurrencyCode name="SystemCurrencyCode">SystemCurrencyCode</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccountNum name="CustAccountNum">CustAccountNum</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyName name="PartyName">PartyName</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendPaymentBIVendorCustomerBalanceEntityV2 (this entity)  

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
