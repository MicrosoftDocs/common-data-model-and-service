---
title: RetailExternalIdToCustomerLinkActivationTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailExternalIdToCustomerLinkActivationTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailExternalIdToCustomerLinkActivationTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailExternalIdToCustomerLinkActivationTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[ExternalIdentityId](#ExternalIdentityId)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[IdentityProviderId](#IdentityProviderId)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[IsActivated](#IsActivated)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[ActivationToken](#ActivationToken)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[EmailAddress](#EmailAddress)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[LastModifiedDateTime](#LastModifiedDateTime)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[Relationship_FK_RetailIdentityProviderRelationshipId](#Relationship_FK_RetailIdentityProviderRelationshipId)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[Relationship_FK_CustTableRelationshipId](#Relationship_FK_CustTableRelationshipId)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailExternalIdToCustomerLinkActivationTable.md" target="_blank">Miscellaneous/RetailExternalIdToCustomerLinkActivationTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailExternalIdToCustomerLinkActivationTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExternalIdentityId name="ExternalIdentityId">ExternalIdentityId</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalIdentityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentityProviderId name="IdentityProviderId">IdentityProviderId</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityProviderId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivated name="IsActivated">IsActivated</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActivationToken name="ActivationToken">ActivationToken</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivationToken attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailAddress name="EmailAddress">EmailAddress</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastModifiedDateTime name="LastModifiedDateTime">LastModifiedDateTime</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastModifiedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

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

### <a href=#Relationship_FK_RetailIdentityProviderRelationshipId name="Relationship_FK_RetailIdentityProviderRelationshipId">Relationship_FK_RetailIdentityProviderRelationshipId</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FK_RetailIdentityProviderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailIdentityProvider.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailIdentityProvider.cdm.json/RetailIdentityProvider</a></td><td><a href="RetailIdentityProvider.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FK_CustTableRelationshipId name="Relationship_FK_CustTableRelationshipId">Relationship_FK_CustTableRelationshipId</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FK_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/erp/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/RetailExternalIdToCustomerLinkActivationTable (this entity)  

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
