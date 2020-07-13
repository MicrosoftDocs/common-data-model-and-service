---
title: VendQRBillIntegrationEntity in AccountsPayable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Imported QR-Bills in AccountsPayable(VendQRBillIntegrationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendQRBillIntegrationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Imported QR-Bills</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorAccount](#VendorAccount)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[AmountInTransactionCurrency](#AmountInTransactionCurrency)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[Currency](#Currency)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[PaymId](#PaymId)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorIBAN](#QRCreditorIBAN)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorName](#QRCreditorName)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRAlternativeParameter1](#QRAlternativeParameter1)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRAlternativeParameter2](#QRAlternativeParameter2)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRAmount](#QRAmount)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorAddrLine1](#QRCreditorAddrLine1)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorAddrLine2](#QRCreditorAddrLine2)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRBillInformation](#QRBillInformation)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorAddressType](#QRCreditorAddressType)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorAddrStreet](#QRCreditorAddrStreet)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorBuildingNumber](#QRCreditorBuildingNumber)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorCountry](#QRCreditorCountry)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorPostalCode](#QRCreditorPostalCode)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCreditorTown](#QRCreditorTown)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRCurrency](#QRCurrency)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRReference](#QRReference)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRReferenceType](#QRReferenceType)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[QRUnstructuredMessage](#QRUnstructuredMessage)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[ImportExecutionId](#ImportExecutionId)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[CashDiscCode](#CashDiscCode)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[InvoiceId](#InvoiceId)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[VATNumber](#VATNumber)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[VendorBankAccount](#VendorBankAccount)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[BackingTable_VendQRBillIntegrationTrans_CHRelationshipId](#BackingTable_VendQRBillIntegrationTrans_CHRelationshipId)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendQRBillIntegrationEntity.md" target="_blank">AccountsPayable/VendQRBillIntegrationEntity</a>|

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInTransactionCurrency name="AmountInTransactionCurrency">AmountInTransactionCurrency</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymId name="PaymId">PaymId</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorIBAN name="QRCreditorIBAN">QRCreditorIBAN</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorIBAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorName name="QRCreditorName">QRCreditorName</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRAlternativeParameter1 name="QRAlternativeParameter1">QRAlternativeParameter1</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRAlternativeParameter1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRAlternativeParameter2 name="QRAlternativeParameter2">QRAlternativeParameter2</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRAlternativeParameter2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRAmount name="QRAmount">QRAmount</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorAddrLine1 name="QRCreditorAddrLine1">QRCreditorAddrLine1</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorAddrLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorAddrLine2 name="QRCreditorAddrLine2">QRCreditorAddrLine2</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorAddrLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRBillInformation name="QRBillInformation">QRBillInformation</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRBillInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorAddressType name="QRCreditorAddressType">QRCreditorAddressType</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorAddressType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorAddrStreet name="QRCreditorAddrStreet">QRCreditorAddrStreet</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorAddrStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorBuildingNumber name="QRCreditorBuildingNumber">QRCreditorBuildingNumber</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorBuildingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorCountry name="QRCreditorCountry">QRCreditorCountry</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorCountry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorPostalCode name="QRCreditorPostalCode">QRCreditorPostalCode</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorPostalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCreditorTown name="QRCreditorTown">QRCreditorTown</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCreditorTown attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRCurrency name="QRCurrency">QRCurrency</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRReference name="QRReference">QRReference</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRReferenceType name="QRReferenceType">QRReferenceType</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRReferenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRUnstructuredMessage name="QRUnstructuredMessage">QRUnstructuredMessage</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRUnstructuredMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImportExecutionId name="ImportExecutionId">ImportExecutionId</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImportExecutionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscCode name="CashDiscCode">CashDiscCode</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATNumber name="VATNumber">VATNumber</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorBankAccount name="VendorBankAccount">VendorBankAccount</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendQRBillIntegrationTrans_CHRelationshipId name="BackingTable_VendQRBillIntegrationTrans_CHRelationshipId">BackingTable_VendQRBillIntegrationTrans_CHRelationshipId</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendQRBillIntegrationTrans_CHRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsPayable/Transaction/VendQRBillIntegrationTrans_CH.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendQRBillIntegrationTrans_CH.cdm.json/VendQRBillIntegrationTrans_CH</a></td><td><a href="../../../Tables/Finance/AccountsPayable/Transaction/VendQRBillIntegrationTrans_CH.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendQRBillIntegrationEntity (this entity)  

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
