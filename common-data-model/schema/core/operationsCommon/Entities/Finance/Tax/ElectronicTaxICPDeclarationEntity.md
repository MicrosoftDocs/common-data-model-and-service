---
title: ElectronicTaxICPDeclarationEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Electronic ICP declaration in Tax(ElectronicTaxICPDeclarationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/ElectronicTaxICPDeclarationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic ICP declaration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ID](#ID)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[ContactID](#ContactID)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Name](#Name)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Telephone](#Telephone)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[ContactType](#ContactType)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Currency](#Currency)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[DateOfCreation](#DateOfCreation)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[FileName](#FileName)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[FiscalGroup](#FiscalGroup)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[RoutingNumber](#RoutingNumber)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[MessageID](#MessageID)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Message](#Message)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[RequestId](#RequestId)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Period](#Period)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Status](#Status)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Version](#Version)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Year](#Year)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[UserId](#UserId)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[ContactInitials](#ContactInitials)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[ContactPrefix](#ContactPrefix)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Company](#Company)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Amount](#Amount)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[ServiceAmount](#ServiceAmount)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[TaxIntraCommTable_NL](#TaxIntraCommTable_NL)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[TriangularTrade](#TriangularTrade)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[VatNum](#VatNum)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[AddressFormat](#AddressFormat)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CountryRegion](#CountryRegion)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[ISOcode](#ISOcode)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[LanguageId](#LanguageId)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[LongName](#LongName)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[ParentCountryRegion](#ParentCountryRegion)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[ShortName](#ShortName)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[TimeZone](#TimeZone)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[UseZipPlus4](#UseZipPlus4)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionAmount](#CorrectionAmount)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionCountryRegionId](#CorrectionCountryRegionId)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionServiceAmount](#CorrectionServiceAmount)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionTaxIntraCommTable_NL](#CorrectionTaxIntraCommTable_NL)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionTaxPeriod](#CorrectionTaxPeriod)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionTriangularTrade](#CorrectionTriangularTrade)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionVatNum](#CorrectionVatNum)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionUseZipPlus4](#CorrectionUseZipPlus4)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionAddressFormat](#CorrectionAddressFormat)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionCountryRegion](#CorrectionCountryRegion)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionCurrencyCode](#CorrectionCurrencyCode)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionISOcode](#CorrectionISOcode)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionLanguageId](#CorrectionLanguageId)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionLongName](#CorrectionLongName)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionParentCountryRegion](#CorrectionParentCountryRegion)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionShortName](#CorrectionShortName)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CorrectionTimeZone](#CorrectionTimeZone)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[CompanyTaxID](#CompanyTaxID)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[BackingTable_TaxIntraCommTable_NLRelationshipId](#BackingTable_TaxIntraCommTable_NLRelationshipId)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ElectronicTaxICPDeclarationEntity.md" target="_blank">Tax/ElectronicTaxICPDeclarationEntity</a>|

### <a href=#ID name="ID">ID</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactID name="ContactID">ContactID</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

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

### <a href=#Telephone name="Telephone">Telephone</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Telephone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactType name="ContactType">ContactType</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

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

### <a href=#DateOfCreation name="DateOfCreation">DateOfCreation</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfCreation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileName name="FileName">FileName</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalGroup name="FiscalGroup">FiscalGroup</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoutingNumber name="RoutingNumber">RoutingNumber</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoutingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessageID name="MessageID">MessageID</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Message name="Message">Message</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Message attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestId name="RequestId">RequestId</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Period name="Period">Period</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Period attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

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

### <a href=#Version name="Version">Version</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Year name="Year">Year</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Year attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactInitials name="ContactInitials">ContactInitials</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactInitials attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPrefix name="ContactPrefix">ContactPrefix</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

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

### <a href=#Amount name="Amount">Amount</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceAmount name="ServiceAmount">ServiceAmount</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIntraCommTable_NL name="TaxIntraCommTable_NL">TaxIntraCommTable_NL</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIntraCommTable_NL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TriangularTrade name="TriangularTrade">TriangularTrade</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TriangularTrade attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VatNum name="VatNum">VatNum</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressFormat name="AddressFormat">AddressFormat</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegion name="CountryRegion">CountryRegion</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

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

### <a href=#ISOcode name="ISOcode">ISOcode</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ISOcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LongName name="LongName">LongName</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LongName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentCountryRegion name="ParentCountryRegion">ParentCountryRegion</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShortName name="ShortName">ShortName</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShortName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeZone name="TimeZone">TimeZone</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseZipPlus4 name="UseZipPlus4">UseZipPlus4</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseZipPlus4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionAmount name="CorrectionAmount">CorrectionAmount</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionCountryRegionId name="CorrectionCountryRegionId">CorrectionCountryRegionId</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionServiceAmount name="CorrectionServiceAmount">CorrectionServiceAmount</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionServiceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionTaxIntraCommTable_NL name="CorrectionTaxIntraCommTable_NL">CorrectionTaxIntraCommTable_NL</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionTaxIntraCommTable_NL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionTaxPeriod name="CorrectionTaxPeriod">CorrectionTaxPeriod</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionTaxPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionTriangularTrade name="CorrectionTriangularTrade">CorrectionTriangularTrade</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionTriangularTrade attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionVatNum name="CorrectionVatNum">CorrectionVatNum</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionVatNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionUseZipPlus4 name="CorrectionUseZipPlus4">CorrectionUseZipPlus4</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionUseZipPlus4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionAddressFormat name="CorrectionAddressFormat">CorrectionAddressFormat</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionAddressFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionCountryRegion name="CorrectionCountryRegion">CorrectionCountryRegion</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionCurrencyCode name="CorrectionCurrencyCode">CorrectionCurrencyCode</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionISOcode name="CorrectionISOcode">CorrectionISOcode</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionISOcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionLanguageId name="CorrectionLanguageId">CorrectionLanguageId</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionLanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionLongName name="CorrectionLongName">CorrectionLongName</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionLongName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionParentCountryRegion name="CorrectionParentCountryRegion">CorrectionParentCountryRegion</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionParentCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionShortName name="CorrectionShortName">CorrectionShortName</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionShortName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionTimeZone name="CorrectionTimeZone">CorrectionTimeZone</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyTaxID name="CompanyTaxID">CompanyTaxID</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTaxID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TaxIntraCommTable_NLRelationshipId name="BackingTable_TaxIntraCommTable_NLRelationshipId">BackingTable_TaxIntraCommTable_NLRelationshipId</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxIntraCommTable_NLRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Transaction/TaxIntraCommTable_NL.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxIntraCommTable_NL.cdm.json/TaxIntraCommTable_NL</a></td><td><a href="../../../Tables/Finance/Tax/Transaction/TaxIntraCommTable_NL.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/ElectronicTaxICPDeclarationEntity (this entity)  

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
