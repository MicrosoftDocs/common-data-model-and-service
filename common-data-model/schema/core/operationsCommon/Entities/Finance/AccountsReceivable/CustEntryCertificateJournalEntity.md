---
title: CustEntryCertificateJournalEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Entry certificate journal

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustEntryCertificateJournalEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Entry certificate journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerAccount](#CustomerAccount)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[Description](#Description)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[EntryCertificate](#EntryCertificate)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[Invoice](#Invoice)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[IsThirdParty](#IsThirdParty)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[Language](#Language)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[PackingSlip](#PackingSlip)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[SalesOrder](#SalesOrder)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[SourceRecId](#SourceRecId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[SourceTableId](#SourceTableId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[Status](#Status)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[Company](#Company)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryCity](#DeliveryCity)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryCountry](#DeliveryCountry)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryCountryISOCode](#DeliveryCountryISOCode)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryCounty](#DeliveryCounty)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryDistrictName](#DeliveryDistrictName)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryLatitude](#DeliveryLatitude)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryLocationId](#DeliveryLocationId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryLongitude](#DeliveryLongitude)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryPostBox](#DeliveryPostBox)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryState](#DeliveryState)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryStreet](#DeliveryStreet)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryStreetNumber](#DeliveryStreetNumber)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryTimeZone](#DeliveryTimeZone)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryValidFrom](#DeliveryValidFrom)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryValidTo](#DeliveryValidTo)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryZipCode](#DeliveryZipCode)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DeliveryDescription](#DeliveryDescription)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[ItemId](#ItemId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[Name](#Name)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[SalesUnit](#SalesUnit)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[Quantity](#Quantity)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[LotId](#LotId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DocumentInvoiceId](#DocumentInvoiceId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DocumentInvoiceDate](#DocumentInvoiceDate)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[DocumentInvoiceRecId](#DocumentInvoiceRecId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[BackingTable_CustEntryCertificateJour_WRelationshipId](#BackingTable_CustEntryCertificateJour_WRelationshipId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustEntryCertificateJournalEntity.md" target="_blank">AccountsReceivable/CustEntryCertificateJournalEntity</a>|

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryCertificate name="EntryCertificate">EntryCertificate</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryCertificate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsThirdParty name="IsThirdParty">IsThirdParty</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsThirdParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Language name="Language">Language</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Language attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingSlip name="PackingSlip">PackingSlip</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlip attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrder name="SalesOrder">SalesOrder</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceRecId name="SourceRecId">SourceRecId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceTableId name="SourceTableId">SourceTableId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

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

### <a href=#DeliveryPostalAddress name="DeliveryPostalAddress">DeliveryPostalAddress</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCity name="DeliveryCity">DeliveryCity</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCountry name="DeliveryCountry">DeliveryCountry</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCountry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCountryISOCode name="DeliveryCountryISOCode">DeliveryCountryISOCode</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCountryISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCounty name="DeliveryCounty">DeliveryCounty</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDistrictName name="DeliveryDistrictName">DeliveryDistrictName</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryLatitude name="DeliveryLatitude">DeliveryLatitude</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryLocationId name="DeliveryLocationId">DeliveryLocationId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryLongitude name="DeliveryLongitude">DeliveryLongitude</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostBox name="DeliveryPostBox">DeliveryPostBox</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryState name="DeliveryState">DeliveryState</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryStreet name="DeliveryStreet">DeliveryStreet</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryStreetNumber name="DeliveryStreetNumber">DeliveryStreetNumber</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTimeZone name="DeliveryTimeZone">DeliveryTimeZone</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidFrom name="DeliveryValidFrom">DeliveryValidFrom</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidTo name="DeliveryValidTo">DeliveryValidTo</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryZipCode name="DeliveryZipCode">DeliveryZipCode</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDescription name="DeliveryDescription">DeliveryDescription</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnit name="SalesUnit">SalesUnit</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LotId name="LotId">LotId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentInvoiceId name="DocumentInvoiceId">DocumentInvoiceId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentInvoiceDate name="DocumentInvoiceDate">DocumentInvoiceDate</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentInvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentInvoiceRecId name="DocumentInvoiceRecId">DocumentInvoiceRecId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentInvoiceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustEntryCertificateJour_WRelationshipId name="BackingTable_CustEntryCertificateJour_WRelationshipId">BackingTable_CustEntryCertificateJour_WRelationshipId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustEntryCertificateJour_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Transaction/CustEntryCertificateJour_W.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustEntryCertificateJour_W.cdm.json/CustEntryCertificateJour_W</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Transaction/CustEntryCertificateJour_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustEntryCertificateJournalEntity (this entity)  

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
