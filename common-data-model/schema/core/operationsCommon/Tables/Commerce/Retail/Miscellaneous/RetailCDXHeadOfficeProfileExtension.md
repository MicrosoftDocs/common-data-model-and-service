---
title: RetailCDXHeadOfficeProfileExtension - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailCDXHeadOfficeProfileExtension

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailCDXHeadOfficeProfileExtension.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXHeadOfficeProfileExtension/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[AosServiceUser](#AosServiceUser)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[CertificateId](#CertificateId)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[Name](#Name)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[RetailCDXSchedulerInterval](#RetailCDXSchedulerInterval)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[ServiceCredentialID](#ServiceCredentialID)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[Relationship_RetailCDXHeadOfficeProfileRelationshipId](#Relationship_RetailCDXHeadOfficeProfileRelationshipId)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[Relationship_RetailCDXSchedulerIntervalRelationshipId](#Relationship_RetailCDXSchedulerIntervalRelationshipId)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[Relationship_RetailDeploymentCertificateRelationshipId](#Relationship_RetailDeploymentCertificateRelationshipId)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|
|[Relationship_RetailDeploymentCredentials_ServiceRelationshipId](#Relationship_RetailDeploymentCredentials_ServiceRelationshipId)||<a href="RetailCDXHeadOfficeProfileExtension.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfileExtension</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXHeadOfficeProfileExtension/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AosServiceUser name="AosServiceUser">AosServiceUser</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AosServiceUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateId name="CertificateId">CertificateId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailCDXSchedulerInterval name="RetailCDXSchedulerInterval">RetailCDXSchedulerInterval</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailCDXSchedulerInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCredentialID name="ServiceCredentialID">ServiceCredentialID</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCredentialID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RetailCDXHeadOfficeProfileRelationshipId name="Relationship_RetailCDXHeadOfficeProfileRelationshipId">Relationship_RetailCDXHeadOfficeProfileRelationshipId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCDXHeadOfficeProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailCDXHeadOfficeProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailCDXHeadOfficeProfile.cdm.json/RetailCDXHeadOfficeProfile</a></td><td><a href="RetailCDXHeadOfficeProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailCDXSchedulerIntervalRelationshipId name="Relationship_RetailCDXSchedulerIntervalRelationshipId">Relationship_RetailCDXSchedulerIntervalRelationshipId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCDXSchedulerIntervalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailCDXSchedulerInterval.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailCDXSchedulerInterval.cdm.json/RetailCDXSchedulerInterval</a></td><td><a href="RetailCDXSchedulerInterval.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailDeploymentCertificateRelationshipId name="Relationship_RetailDeploymentCertificateRelationshipId">Relationship_RetailDeploymentCertificateRelationshipId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeploymentCertificateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentCertificates.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentCertificates.cdm.json/RetailDeploymentCertificates</a></td><td><a href="RetailDeploymentCertificates.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailDeploymentCredentials_ServiceRelationshipId name="Relationship_RetailDeploymentCredentials_ServiceRelationshipId">Relationship_RetailDeploymentCredentials_ServiceRelationshipId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeploymentCredentials_ServiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentCredentials.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentCredentials.cdm.json/RetailDeploymentCredentials</a></td><td><a href="RetailDeploymentCredentials.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
