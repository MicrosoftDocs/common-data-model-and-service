---
title: UniqueCertificationHeader_IT - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Unique Certification - Header

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/APARShared/Miscellaneous/UniqueCertificationHeader_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[UniqueCertificationHeader_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique Certification - Header</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[Cancellation](#Cancellation)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[CompanyEmail](#CompanyEmail)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[CompanyFiscalCode](#CompanyFiscalCode)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[CompanyName](#CompanyName)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[CompanyPhone](#CompanyPhone)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[DeclarerFiscalCode](#DeclarerFiscalCode)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[DeclarerType](#DeclarerType)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[IntermediaryComunicationdate](#IntermediaryComunicationdate)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[IntermediaryFiscalCode](#IntermediaryFiscalCode)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[IntermediarySignature](#IntermediarySignature)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[RefRecId](#RefRecId)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[Replacement](#Replacement)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[SignatureDeclarerFiscalCode](#SignatureDeclarerFiscalCode)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[SignatureFirstName](#SignatureFirstName)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[SignatureFiscalCode](#SignatureFiscalCode)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[SignatureLastName](#SignatureLastName)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[SignaturePosition](#SignaturePosition)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[TaxReportDomesticOriginalReportNumber_IT](#TaxReportDomesticOriginalReportNumber_IT)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[TaxReportDomesticOrigReportDocNumber_IT](#TaxReportDomesticOrigReportDocNumber_IT)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[TelematicForward](#TelematicForward)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[CompanyExceptionalEvents](#CompanyExceptionalEvents)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[CodeCompanyExceptionalEvents](#CodeCompanyExceptionalEvents)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[DataAreaId](#DataAreaId)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[Relationship_UniqueCertificationExtractionRelationshipId](#Relationship_UniqueCertificationExtractionRelationshipId)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="UniqueCertificationHeader_IT.md" target="_blank">Miscellaneous/UniqueCertificationHeader_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[UniqueCertificationHeader_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Cancellation name="Cancellation">Cancellation</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Cancellation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CompanyEmail name="CompanyEmail">CompanyEmail</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyFiscalCode name="CompanyFiscalCode">CompanyFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyName name="CompanyName">CompanyName</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyPhone name="CompanyPhone">CompanyPhone</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeclarerFiscalCode name="DeclarerFiscalCode">DeclarerFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Writer fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeclarerFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Writer fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeclarerType name="DeclarerType">DeclarerType</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeclarerType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IntermediaryComunicationdate name="IntermediaryComunicationdate">IntermediaryComunicationdate</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermediaryComunicationdate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#IntermediaryFiscalCode name="IntermediaryFiscalCode">IntermediaryFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Intermediary fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermediaryFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intermediary fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntermediarySignature name="IntermediarySignature">IntermediarySignature</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermediarySignature attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Replacement name="Replacement">Replacement</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Replacement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SignatureDeclarerFiscalCode name="SignatureDeclarerFiscalCode">SignatureDeclarerFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company fiscal code/declarer fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureDeclarerFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company fiscal code/declarer fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureFirstName name="SignatureFirstName">SignatureFirstName</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureFiscalCode name="SignatureFiscalCode">SignatureFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Signatory fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Signatory fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureLastName name="SignatureLastName">SignatureLastName</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignaturePosition name="SignaturePosition">SignaturePosition</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignaturePosition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxReportDomesticOriginalReportNumber_IT name="TaxReportDomesticOriginalReportNumber_IT">TaxReportDomesticOriginalReportNumber_IT</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportDomesticOriginalReportNumber_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReportDomesticOrigReportDocNumber_IT name="TaxReportDomesticOrigReportDocNumber_IT">TaxReportDomesticOrigReportDocNumber_IT</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportDomesticOrigReportDocNumber_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TelematicForward name="TelematicForward">TelematicForward</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelematicForward attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CompanyExceptionalEvents name="CompanyExceptionalEvents">CompanyExceptionalEvents</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyExceptionalEvents attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CodeCompanyExceptionalEvents name="CodeCompanyExceptionalEvents">CodeCompanyExceptionalEvents</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exceptional events</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeCompanyExceptionalEvents attribute are listed below.</summary>

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

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

### <a href=#Relationship_UniqueCertificationExtractionRelationshipId name="Relationship_UniqueCertificationExtractionRelationshipId">Relationship_UniqueCertificationExtractionRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UniqueCertificationExtractionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="UniqueCertificationExtraction_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Miscellaneous/UniqueCertificationExtraction_IT.cdm.json/UniqueCertificationExtraction_IT</a></td><td><a href="UniqueCertificationExtraction_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationHeader_IT (this entity)  

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
