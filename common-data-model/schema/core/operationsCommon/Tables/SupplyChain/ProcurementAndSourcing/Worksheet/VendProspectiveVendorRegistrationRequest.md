---
title: VendProspectiveVendorRegistrationRequest - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# VendProspectiveVendorRegistrationRequest

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Worksheet/VendProspectiveVendorRegistrationRequest.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendProspectiveVendorRegistrationRequest/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[FirstName](#FirstName)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[LastName](#LastName)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[MiddleName](#MiddleName)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[LanguageId](#LanguageId)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[Email](#Email)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[CompanyName](#CompanyName)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[OrganizationNumber](#OrganizationNumber)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[OrganizationType](#OrganizationType)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[BusinessLine](#BusinessLine)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[BusinessJustification](#BusinessJustification)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[SubmittedDate](#SubmittedDate)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[ProcessedDate](#ProcessedDate)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[RequestState](#RequestState)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[UserRequestId](#UserRequestId)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[RequestCompany](#RequestCompany)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|
|[Relationship_VendorPortalUserRequestRelationshipId](#Relationship_VendorPortalUserRequestRelationshipId)||<a href="VendProspectiveVendorRegistrationRequest.md" target="_blank">Worksheet/VendProspectiveVendorRegistrationRequest</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendProspectiveVendorRegistrationRequest/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FirstName name="FirstName">FirstName</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastName name="LastName">LastName</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MiddleName name="MiddleName">MiddleName</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyName name="CompanyName">CompanyName</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

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

### <a href=#OrganizationNumber name="OrganizationNumber">OrganizationNumber</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationType name="OrganizationType">OrganizationType</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BusinessLine name="BusinessLine">BusinessLine</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessJustification name="BusinessJustification">BusinessJustification</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessJustification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubmittedDate name="SubmittedDate">SubmittedDate</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubmittedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ProcessedDate name="ProcessedDate">ProcessedDate</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#RequestState name="RequestState">RequestState</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#UserRequestId name="UserRequestId">UserRequestId</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserRequestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestCompany name="RequestCompany">RequestCompany</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/LanguageTable.cdm.json/LanguageTable</a></td><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendorPortalUserRequestRelationshipId name="Relationship_VendorPortalUserRequestRelationshipId">Relationship_VendorPortalUserRequestRelationshipId</a>

First included in: Worksheet/VendProspectiveVendorRegistrationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorPortalUserRequestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Transaction/SysUserRequest.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/SysUserRequest.cdm.json/SysUserRequest</a></td><td><a href="../../../System/SystemAdministration/Transaction/SysUserRequest.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
