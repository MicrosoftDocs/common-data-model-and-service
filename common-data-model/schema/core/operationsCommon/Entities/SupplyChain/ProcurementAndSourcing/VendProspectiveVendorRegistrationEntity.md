---
title: VendProspectiveVendorRegistrationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Prospective vendor registrations in ProcurementAndSourcing(VendProspectiveVendorRegistrationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prospective vendor registrations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreTermsAndConditionsAccepted](#AreTermsAndConditionsAccepted)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[DoingBusinessAs](#DoingBusinessAs)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[CompanyEmailAddress](#CompanyEmailAddress)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[IsFemaleOwned](#IsFemaleOwned)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[IsLocallyOwned](#IsLocallyOwned)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[IsMinorityOwned](#IsMinorityOwned)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[NumberOfEmployees](#NumberOfEmployees)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[OrganizationNumber](#OrganizationNumber)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[OrganizationType](#OrganizationType)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[CompanyPhoneNumber](#CompanyPhoneNumber)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[IsSmallBusiness](#IsSmallBusiness)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[Tax1099Fields](#Tax1099Fields)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[CompanyFaxNumber](#CompanyFaxNumber)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[CompanyTaxExemptNumber](#CompanyTaxExemptNumber)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[CompanyWebsiteURL](#CompanyWebsiteURL)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[SiretId](#SiretId)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[NAFCode](#NAFCode)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[Federal1099Number](#Federal1099Number)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[Federal1099NumberType](#Federal1099NumberType)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[FiscalCode](#FiscalCode)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[ForeignOwnershipIndicator](#ForeignOwnershipIndicator)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[LineOfBusiness](#LineOfBusiness)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[NationalRegistryNumber](#NationalRegistryNumber)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[Tax1099NameChoice](#Tax1099NameChoice)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[Tax1099GVendorStateId](#Tax1099GVendorStateId)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[Tax1099GVendorStateTaxId](#Tax1099GVendorStateTaxId)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[TaxStateIdentifierType](#TaxStateIdentifierType)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[IsRegistrationRequestSubmitted](#IsRegistrationRequestSubmitted)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[VendorGroupId](#VendorGroupId)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[ContactPersonPhoneNumber](#ContactPersonPhoneNumber)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[CompanyName](#CompanyName)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[ContactPersonEmailAddress](#ContactPersonEmailAddress)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[VendorRegistrationId](#VendorRegistrationId)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[BackingTable_VendProspectiveVendorRegistrationRelationshipId](#BackingTable_VendProspectiveVendorRegistrationRelationshipId)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendProspectiveVendorRegistrationEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity</a>|

### <a href=#AreTermsAndConditionsAccepted name="AreTermsAndConditionsAccepted">AreTermsAndConditionsAccepted</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTermsAndConditionsAccepted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoingBusinessAs name="DoingBusinessAs">DoingBusinessAs</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoingBusinessAs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

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

### <a href=#CompanyEmailAddress name="CompanyEmailAddress">CompanyEmailAddress</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company email address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyEmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company email address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFemaleOwned name="IsFemaleOwned">IsFemaleOwned</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFemaleOwned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocallyOwned name="IsLocallyOwned">IsLocallyOwned</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocallyOwned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMinorityOwned name="IsMinorityOwned">IsMinorityOwned</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMinorityOwned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfEmployees name="NumberOfEmployees">NumberOfEmployees</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfEmployees attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationNumber name="OrganizationNumber">OrganizationNumber</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

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

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyPhoneNumber name="CompanyPhoneNumber">CompanyPhoneNumber</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company telephone number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyPhoneNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company telephone number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSmallBusiness name="IsSmallBusiness">IsSmallBusiness</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSmallBusiness attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Fields name="Tax1099Fields">Tax1099Fields</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Fields attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyFaxNumber name="CompanyFaxNumber">CompanyFaxNumber</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company fax number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyFaxNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company fax number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyTaxExemptNumber name="CompanyTaxExemptNumber">CompanyTaxExemptNumber</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTaxExemptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyWebsiteURL name="CompanyWebsiteURL">CompanyWebsiteURL</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company website URL</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyWebsiteURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company website URL</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiretId name="SiretId">SiretId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiretId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NAFCode name="NAFCode">NAFCode</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NAFCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

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

### <a href=#Federal1099Number name="Federal1099Number">Federal1099Number</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Federal1099Number attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Federal1099NumberType name="Federal1099NumberType">Federal1099NumberType</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Federal1099NumberType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCode name="FiscalCode">FiscalCode</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

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

### <a href=#ForeignOwnershipIndicator name="ForeignOwnershipIndicator">ForeignOwnershipIndicator</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignOwnershipIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineOfBusiness name="LineOfBusiness">LineOfBusiness</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineOfBusiness attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NationalRegistryNumber name="NationalRegistryNumber">NationalRegistryNumber</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NationalRegistryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099NameChoice name="Tax1099NameChoice">Tax1099NameChoice</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099NameChoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099GVendorStateId name="Tax1099GVendorStateId">Tax1099GVendorStateId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099GVendorStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099GVendorStateTaxId name="Tax1099GVendorStateTaxId">Tax1099GVendorStateTaxId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099GVendorStateTaxId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxStateIdentifierType name="TaxStateIdentifierType">TaxStateIdentifierType</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStateIdentifierType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRegistrationRequestSubmitted name="IsRegistrationRequestSubmitted">IsRegistrationRequestSubmitted</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is registration request submitted</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRegistrationRequestSubmitted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is registration request submitted</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorGroupId name="VendorGroupId">VendorGroupId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonPhoneNumber name="ContactPersonPhoneNumber">ContactPersonPhoneNumber</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact person telephone number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonPhoneNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contact person telephone number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyName name="CompanyName">CompanyName</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonEmailAddress name="ContactPersonEmailAddress">ContactPersonEmailAddress</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact person email address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonEmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contact person email address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorRegistrationId name="VendorRegistrationId">VendorRegistrationId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prospective vendor registration number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRegistrationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prospective vendor registration number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendProspectiveVendorRegistrationRelationshipId name="BackingTable_VendProspectiveVendorRegistrationRelationshipId">BackingTable_VendProspectiveVendorRegistrationRelationshipId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendProspectiveVendorRegistrationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/VendProspectiveVendorRegistration.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/VendProspectiveVendorRegistration.cdm.json/VendProspectiveVendorRegistration</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/VendProspectiveVendorRegistration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationEntity (this entity)  

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
