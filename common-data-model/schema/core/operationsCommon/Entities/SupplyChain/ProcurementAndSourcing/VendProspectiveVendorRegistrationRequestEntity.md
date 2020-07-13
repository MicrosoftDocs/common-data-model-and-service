---
title: VendProspectiveVendorRegistrationRequestEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Prospective vendor registration request in ProcurementAndSourcing(VendProspectiveVendorRegistrationRequestEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prospective vendor registration request</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ContactPersonFirstName](#ContactPersonFirstName)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[ContactPersonMiddleName](#ContactPersonMiddleName)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[ContactPersonLastName](#ContactPersonLastName)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[LanguageId](#LanguageId)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[EmailAddress](#EmailAddress)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[CompanyName](#CompanyName)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[OrganizationNumber](#OrganizationNumber)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[OrganizationType](#OrganizationType)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[BusinessLineDescription](#BusinessLineDescription)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[BusinessJustificationDescription](#BusinessJustificationDescription)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[SubmittedDate](#SubmittedDate)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[ProcessedDate](#ProcessedDate)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[RequestState](#RequestState)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[UserRequestId](#UserRequestId)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[RequestCompany](#RequestCompany)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|
|[BackingTable_VendProspectiveVendorRegistrationRequestRelationshipId](#BackingTable_VendProspectiveVendorRegistrationRequestRelationshipId)||<a href="VendProspectiveVendorRegistrationRequestEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity</a>|

### <a href=#ContactPersonFirstName name="ContactPersonFirstName">ContactPersonFirstName</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonMiddleName name="ContactPersonMiddleName">ContactPersonMiddleName</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonLastName name="ContactPersonLastName">ContactPersonLastName</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

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

### <a href=#EmailAddress name="EmailAddress">EmailAddress</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyName name="CompanyName">CompanyName</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

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

### <a href=#OrganizationNumber name="OrganizationNumber">OrganizationNumber</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

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

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

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

### <a href=#BusinessLineDescription name="BusinessLineDescription">BusinessLineDescription</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessLineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessJustificationDescription name="BusinessJustificationDescription">BusinessJustificationDescription</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessJustificationDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubmittedDate name="SubmittedDate">SubmittedDate</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubmittedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessedDate name="ProcessedDate">ProcessedDate</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestState name="RequestState">RequestState</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserRequestId name="UserRequestId">UserRequestId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserRequestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestCompany name="RequestCompany">RequestCompany</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendProspectiveVendorRegistrationRequestRelationshipId name="BackingTable_VendProspectiveVendorRegistrationRequestRelationshipId">BackingTable_VendProspectiveVendorRegistrationRequestRelationshipId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationRequestEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendProspectiveVendorRegistrationRequestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Worksheet/VendProspectiveVendorRegistrationRequest.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Worksheet/VendProspectiveVendorRegistrationRequest.cdm.json/VendProspectiveVendorRegistrationRequest</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Worksheet/VendProspectiveVendorRegistrationRequest.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
