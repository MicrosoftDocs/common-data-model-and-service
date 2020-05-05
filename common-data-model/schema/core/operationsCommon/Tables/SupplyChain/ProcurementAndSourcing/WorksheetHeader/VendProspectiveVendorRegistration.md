---
title: VendProspectiveVendorRegistration - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Prospective vendor registration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/VendProspectiveVendorRegistration.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendProspectiveVendorRegistration/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prospective vendor registration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[AcceptChecked](#AcceptChecked)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[DBA](#DBA)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[DoingBusinessCountryRegion](#DoingBusinessCountryRegion)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Email](#Email)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[FemaleOwned](#FemaleOwned)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[LocallyOwned](#LocallyOwned)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[MinorityOwned](#MinorityOwned)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[NumberOfEmployees](#NumberOfEmployees)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[OrganizationNumber](#OrganizationNumber)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[OrganizationType](#OrganizationType)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Phone](#Phone)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[SmallBusiness](#SmallBusiness)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Tax1099Fields](#Tax1099Fields)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Telefax](#Telefax)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[VatNumber](#VatNumber)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Website](#Website)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[CompanyIdSiret](#CompanyIdSiret)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[CompanyNAFCode](#CompanyNAFCode)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Currency](#Currency)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Federal1099Number](#Federal1099Number)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Federal1099NumberType](#Federal1099NumberType)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[FiscalCode](#FiscalCode)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[ForeignOwnership](#ForeignOwnership)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[LineOfBusinessId](#LineOfBusinessId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[OrganizationIdentifier](#OrganizationIdentifier)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[PaymTerm](#PaymTerm)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Tax1099NameChoice](#Tax1099NameChoice)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[TaxState](#TaxState)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[TaxStateIdentifier](#TaxStateIdentifier)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[TaxStateIdentifierType](#TaxStateIdentifierType)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[SameAsCompany](#SameAsCompany)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[IsCompleted](#IsCompleted)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[RegistrationRequest](#RegistrationRequest)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[VendorParty](#VendorParty)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[VendorGroup](#VendorGroup)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[ContactParty](#ContactParty)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[ContactPhone](#ContactPhone)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Name](#Name)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[DataAreaId](#DataAreaId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_Tax1099FieldsRelationshipId](#Relationship_Tax1099FieldsRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_CompanyNAFCodeRelationshipId](#Relationship_CompanyNAFCodeRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_LineOfBusinessRelationshipId](#Relationship_LineOfBusinessRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_PaymTermRelationshipId](#Relationship_PaymTermRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_ProspectiveVendorRegistrationRequestRelationshipId](#Relationship_ProspectiveVendorRegistrationRequestRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_DoingBusinessCountryRegionRelationshipId](#Relationship_DoingBusinessCountryRegionRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_ContactPartyRelationshipId](#Relationship_ContactPartyRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_VendPartyRelationshipId](#Relationship_VendPartyRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendProspectiveVendorRegistration.md" target="_blank">WorksheetHeader/VendProspectiveVendorRegistration</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendProspectiveVendorRegistration/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcceptChecked name="AcceptChecked">AcceptChecked</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accepted terms and conditions</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptChecked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accepted terms and conditions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DBA name="DBA">DBA</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Doing business as</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DBA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Doing business as</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoingBusinessCountryRegion name="DoingBusinessCountryRegion">DoingBusinessCountryRegion</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoingBusinessCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FemaleOwned name="FemaleOwned">FemaleOwned</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FemaleOwned attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LocallyOwned name="LocallyOwned">LocallyOwned</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocallyOwned attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MinorityOwned name="MinorityOwned">MinorityOwned</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinorityOwned attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NumberOfEmployees name="NumberOfEmployees">NumberOfEmployees</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfEmployees attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OrganizationNumber name="OrganizationNumber">OrganizationNumber</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationType name="OrganizationType">OrganizationType</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Phone name="Phone">Phone</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SmallBusiness name="SmallBusiness">SmallBusiness</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SmallBusiness attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Tax1099Fields name="Tax1099Fields">Tax1099Fields</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Fields attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Telefax name="Telefax">Telefax</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Telefax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VatNumber name="VatNumber">VatNumber</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Website name="Website">Website</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Website attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Website</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyIdSiret name="CompanyIdSiret">CompanyIdSiret</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyIdSiret attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyNAFCode name="CompanyNAFCode">CompanyNAFCode</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyNAFCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

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

### <a href=#Federal1099Number name="Federal1099Number">Federal1099Number</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Federal tax ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Federal1099Number attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Federal tax ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Federal1099NumberType name="Federal1099NumberType">Federal1099NumberType</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Federal tax ID type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Federal1099NumberType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Federal tax ID type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FiscalCode name="FiscalCode">FiscalCode</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignOwnership name="ForeignOwnership">ForeignOwnership</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignOwnership attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LineOfBusinessId name="LineOfBusinessId">LineOfBusinessId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineOfBusinessId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationIdentifier name="OrganizationIdentifier">OrganizationIdentifier</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymTerm name="PaymTerm">PaymTerm</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymTerm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099NameChoice name="Tax1099NameChoice">Tax1099NameChoice</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099NameChoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxState name="TaxState">TaxState</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax state</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax state</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxStateIdentifier name="TaxStateIdentifier">TaxStateIdentifier</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStateIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxStateIdentifierType name="TaxStateIdentifierType">TaxStateIdentifierType</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State tax ID type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStateIdentifierType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>State tax ID type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SameAsCompany name="SameAsCompany">SameAsCompany</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Same as company</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SameAsCompany attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Same as company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsCompleted name="IsCompleted">IsCompleted</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCompleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RegistrationRequest name="RegistrationRequest">RegistrationRequest</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationRequest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendorParty name="VendorParty">VendorParty</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorParty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendorGroup name="VendorGroup">VendorGroup</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactParty name="ContactParty">ContactParty</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactParty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ContactPhone name="ContactPhone">ContactPhone</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

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

### <a href=#Relationship_Tax1099FieldsRelationshipId name="Relationship_Tax1099FieldsRelationshipId">Relationship_Tax1099FieldsRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Tax1099FieldsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsPayable/Group/Tax1099Fields.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/Tax1099Fields.cdm.json/Tax1099Fields</a></td><td><a href="../../../Finance/AccountsPayable/Group/Tax1099Fields.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyNAFCodeRelationshipId name="Relationship_CompanyNAFCodeRelationshipId">Relationship_CompanyNAFCodeRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyNAFCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/CompanyNAFCode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/CompanyNAFCode.cdm.json/CompanyNAFCode</a></td><td><a href="../../Inventory/Group/CompanyNAFCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LineOfBusinessRelationshipId name="Relationship_LineOfBusinessRelationshipId">Relationship_LineOfBusinessRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LineOfBusinessRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsPayable/Group/LineOfBusiness.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/LineOfBusiness.cdm.json/LineOfBusiness</a></td><td><a href="../../../Finance/AccountsPayable/Group/LineOfBusiness.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTermRelationshipId name="Relationship_PaymTermRelationshipId">Relationship_PaymTermRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/PaymTerm.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../../Finance/Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProspectiveVendorRegistrationRequestRelationshipId name="Relationship_ProspectiveVendorRegistrationRequestRelationshipId">Relationship_ProspectiveVendorRegistrationRequestRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProspectiveVendorRegistrationRequestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Worksheet/VendProspectiveVendorRegistrationRequest.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Worksheet/VendProspectiveVendorRegistrationRequest.cdm.json/VendProspectiveVendorRegistrationRequest</a></td><td><a href="../Worksheet/VendProspectiveVendorRegistrationRequest.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DoingBusinessCountryRegionRelationshipId name="Relationship_DoingBusinessCountryRegionRelationshipId">Relationship_DoingBusinessCountryRegionRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DoingBusinessCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ContactPartyRelationshipId name="Relationship_ContactPartyRelationshipId">Relationship_ContactPartyRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ContactPartyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/DirPerson.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/DirPerson.cdm.json/DirPerson</a></td><td><a href="../../../Common/GAB/Main/DirPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPartyRelationshipId name="Relationship_VendPartyRelationshipId">Relationship_VendPartyRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPartyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/DirPartyTable.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/DirPartyTable.cdm.json/DirPartyTable</a></td><td><a href="../../../Common/GAB/Main/DirPartyTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/VendProspectiveVendorRegistration (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
