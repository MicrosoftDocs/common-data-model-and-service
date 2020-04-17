---
title: EPDocuParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# EPDocuParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Parameter/EPDocuParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EPDocuParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[Document](#Document)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleActivities](#moduleActivities)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleBusinessRelations](#moduleBusinessRelations)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleCampaigns](#moduleCampaigns)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleContacts](#moduleContacts)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleCust](#moduleCust)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleExpense](#moduleExpense)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleInvent](#moduleInvent)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleLeads](#moduleLeads)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleOpportunities](#moduleOpportunities)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleProject](#moduleProject)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[modulePurch](#modulePurch)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleSales](#moduleSales)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[moduleVend](#moduleVend)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[userCust](#userCust)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[UserVend](#UserVend)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[viewMode](#viewMode)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EPDocuParameters.md" target="_blank">Parameter/EPDocuParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EPDocuParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Document name="Document">Document</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Document attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleActivities name="moduleActivities">moduleActivities</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleActivities attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleBusinessRelations name="moduleBusinessRelations">moduleBusinessRelations</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleBusinessRelations attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleCampaigns name="moduleCampaigns">moduleCampaigns</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleCampaigns attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleContacts name="moduleContacts">moduleContacts</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleContacts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleCust name="moduleCust">moduleCust</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleExpense name="moduleExpense">moduleExpense</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleExpense attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleInvent name="moduleInvent">moduleInvent</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleInvent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleLeads name="moduleLeads">moduleLeads</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleLeads attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleOpportunities name="moduleOpportunities">moduleOpportunities</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleOpportunities attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleProject name="moduleProject">moduleProject</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleProject attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#modulePurch name="modulePurch">modulePurch</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modulePurch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleSales name="moduleSales">moduleSales</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleSales attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#moduleVend name="moduleVend">moduleVend</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the moduleVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#userCust name="userCust">userCust</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the userCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UserVend name="UserVend">UserVend</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#viewMode name="viewMode">viewMode</a>

First included in: Parameter/EPDocuParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the viewMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/EPDocuParameters (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/EPDocuParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
