---
title: UniqueCertificationVendorDetail_IT in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Unique Certification - Vendor details in Miscellaneous(UniqueCertificationVendorDetail_IT)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/APARShared/Miscellaneous/UniqueCertificationVendorDetail_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[UniqueCertificationVendorDetail_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique Certification - Vendor details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[date](#date)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[ForeignAddressCity](#ForeignAddressCity)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[ForeignAddressing](#ForeignAddressing)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[ForeignResidenceCountryRegionId](#ForeignResidenceCountryRegionId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[ForeignTaxCountryRegionCode](#ForeignTaxCountryRegionCode)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[RefRecId](#RefRecId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[RepresentativeFiscalCode](#RepresentativeFiscalCode)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteAddressCity](#SubstituteAddressCity)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteAddressCountyId](#SubstituteAddressCountyId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteAddressing](#SubstituteAddressing)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteAddressZipCodeId](#SubstituteAddressZipCodeId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteATECOFINCode_IT](#SubstituteATECOFINCode_IT)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteConfirmCertification](#SubstituteConfirmCertification)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteEmail](#SubstituteEmail)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteFiscalCode](#SubstituteFiscalCode)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteHeadquarterCode](#SubstituteHeadquarterCode)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstituteLastNameCompanyName](#SubstituteLastNameCompanyName)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[SubstitutePhone](#SubstitutePhone)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorAddressCity](#VendorAddressCity)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorAddressCountyIdActualYear](#VendorAddressCountyIdActualYear)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorAddressCountyIdNextYear](#VendorAddressCountyIdNextYear)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorBirthDate](#VendorBirthDate)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorFirstName_IT](#VendorFirstName_IT)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorFiscalCode](#VendorFiscalCode)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorGender](#VendorGender)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorLastNameCompanyName](#VendorLastNameCompanyName)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorResidenceAddressCityActualYear](#VendorResidenceAddressCityActualYear)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorResidenceAddressCityNextYear](#VendorResidenceAddressCityNextYear)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorResidenceAddressCountyId](#VendorResidenceAddressCountyId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorResidenceMunicipalitycodeActualYr](#VendorResidenceMunicipalitycodeActualYr)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorResidenceMunicipalitycodeNextYr](#VendorResidenceMunicipalitycodeNextYr)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorSpecialCategories](#VendorSpecialCategories)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[Year](#Year)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[CodeExceptionalEvents](#CodeExceptionalEvents)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[CodeSpecialCategories](#CodeSpecialCategories)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorResidenceUnifiedCountyActualYr](#VendorResidenceUnifiedCountyActualYr)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorResidenceUnifiedCountyNextYr](#VendorResidenceUnifiedCountyNextYr)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[VendorExceptionalEvent](#VendorExceptionalEvent)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[DataAreaId](#DataAreaId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[Relationship_LogisticsAddressCountryRegion_ForeignRelationshipId](#Relationship_LogisticsAddressCountryRegion_ForeignRelationshipId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[Relationship_LogisticsAddressZipCode_SubstituteRelationshipId](#Relationship_LogisticsAddressZipCode_SubstituteRelationshipId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[Relationship_UniqueCertificationVendorListRelationshipId](#Relationship_UniqueCertificationVendorListRelationshipId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="UniqueCertificationVendorDetail_IT.md" target="_blank">Miscellaneous/UniqueCertificationVendorDetail_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[UniqueCertificationVendorDetail_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#date name="date">date</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the date attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ForeignAddressCity name="ForeignAddressCity">ForeignAddressCity</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignAddressing name="ForeignAddressing">ForeignAddressing</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignAddressing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignResidenceCountryRegionId name="ForeignResidenceCountryRegionId">ForeignResidenceCountryRegionId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Residence foreign country/region</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignResidenceCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Residence foreign country/region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignTaxCountryRegionCode name="ForeignTaxCountryRegionCode">ForeignTaxCountryRegionCode</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignTaxCountryRegionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RepresentativeFiscalCode name="RepresentativeFiscalCode">RepresentativeFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Representative fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepresentativeFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Representative fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteAddressCity name="SubstituteAddressCity">SubstituteAddressCity</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteAddressCountyId name="SubstituteAddressCountyId">SubstituteAddressCountyId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteAddressing name="SubstituteAddressing">SubstituteAddressing</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteAddressing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteAddressZipCodeId name="SubstituteAddressZipCodeId">SubstituteAddressZipCodeId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteAddressZipCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteATECOFINCode_IT name="SubstituteATECOFINCode_IT">SubstituteATECOFINCode_IT</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteATECOFINCode_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteConfirmCertification name="SubstituteConfirmCertification">SubstituteConfirmCertification</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteConfirmCertification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SubstituteEmail name="SubstituteEmail">SubstituteEmail</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteFiscalCode name="SubstituteFiscalCode">SubstituteFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Substitute fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Substitute fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteHeadquarterCode name="SubstituteHeadquarterCode">SubstituteHeadquarterCode</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteHeadquarterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstituteLastNameCompanyName name="SubstituteLastNameCompanyName">SubstituteLastNameCompanyName</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstituteLastNameCompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubstitutePhone name="SubstitutePhone">SubstitutePhone</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubstitutePhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAddressCity name="VendorAddressCity">VendorAddressCity</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAddressCountyIdActualYear name="VendorAddressCountyIdActualYear">VendorAddressCountyIdActualYear</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAddressCountyIdActualYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAddressCountyIdNextYear name="VendorAddressCountyIdNextYear">VendorAddressCountyIdNextYear</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAddressCountyIdNextYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorBirthDate name="VendorBirthDate">VendorBirthDate</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorBirthDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#VendorFirstName_IT name="VendorFirstName_IT">VendorFirstName_IT</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorFirstName_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorFiscalCode name="VendorFiscalCode">VendorFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorGender name="VendorGender">VendorGender</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorGender attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VendorLastNameCompanyName name="VendorLastNameCompanyName">VendorLastNameCompanyName</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLastNameCompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorResidenceAddressCityActualYear name="VendorResidenceAddressCityActualYear">VendorResidenceAddressCityActualYear</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorResidenceAddressCityActualYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorResidenceAddressCityNextYear name="VendorResidenceAddressCityNextYear">VendorResidenceAddressCityNextYear</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorResidenceAddressCityNextYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorResidenceAddressCountyId name="VendorResidenceAddressCountyId">VendorResidenceAddressCountyId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorResidenceAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorResidenceMunicipalitycodeActualYr name="VendorResidenceMunicipalitycodeActualYr">VendorResidenceMunicipalitycodeActualYr</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorResidenceMunicipalitycodeActualYr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorResidenceMunicipalitycodeNextYr name="VendorResidenceMunicipalitycodeNextYr">VendorResidenceMunicipalitycodeNextYr</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorResidenceMunicipalitycodeNextYr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorSpecialCategories name="VendorSpecialCategories">VendorSpecialCategories</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorSpecialCategories attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Year name="Year">Year</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Year attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#CodeExceptionalEvents name="CodeExceptionalEvents">CodeExceptionalEvents</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exceptional events</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeExceptionalEvents attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exceptional events</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CodeSpecialCategories name="CodeSpecialCategories">CodeSpecialCategories</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Special categories</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeSpecialCategories attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Special categories</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorResidenceUnifiedCountyActualYr name="VendorResidenceUnifiedCountyActualYr">VendorResidenceUnifiedCountyActualYr</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unified Counties</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorResidenceUnifiedCountyActualYr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unified Counties</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorResidenceUnifiedCountyNextYr name="VendorResidenceUnifiedCountyNextYr">VendorResidenceUnifiedCountyNextYr</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unified Counties</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorResidenceUnifiedCountyNextYr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unified Counties</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorExceptionalEvent name="VendorExceptionalEvent">VendorExceptionalEvent</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorExceptionalEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

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

### <a href=#Relationship_LogisticsAddressCountryRegion_ForeignRelationshipId name="Relationship_LogisticsAddressCountryRegion_ForeignRelationshipId">Relationship_LogisticsAddressCountryRegion_ForeignRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegion_ForeignRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LogisticsAddressZipCode_SubstituteRelationshipId name="Relationship_LogisticsAddressZipCode_SubstituteRelationshipId">Relationship_LogisticsAddressZipCode_SubstituteRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressZipCode_SubstituteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressZipCode.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressZipCode.cdm.json/LogisticsAddressZipCode</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressZipCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UniqueCertificationVendorListRelationshipId name="Relationship_UniqueCertificationVendorListRelationshipId">Relationship_UniqueCertificationVendorListRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UniqueCertificationVendorListRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="UniqueCertificationVendorList_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Miscellaneous/UniqueCertificationVendorList_IT.cdm.json/UniqueCertificationVendorList_IT</a></td><td><a href="UniqueCertificationVendorList_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationVendorDetail_IT (this entity)  

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
