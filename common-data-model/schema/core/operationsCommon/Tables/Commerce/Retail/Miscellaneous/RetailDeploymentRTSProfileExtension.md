---
title: RetailDeploymentRTSProfileExtension - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailDeploymentRTSProfileExtension

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentRTSProfileExtension.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDeploymentRTSProfileExtension/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|
|[CertificateId](#CertificateId)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|
|[Name](#Name)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|
|[RetailTransactionServiceProfile](#RetailTransactionServiceProfile)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|
|[ServiceCredentialID](#ServiceCredentialID)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|
|[Relationship_RetailDeploymentCertificateRelationshipId](#Relationship_RetailDeploymentCertificateRelationshipId)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|
|[Relationship_RetailDeploymentRTSProfileRelationshipId](#Relationship_RetailDeploymentRTSProfileRelationshipId)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|
|[Relationship_RetailTransactionServiceProfileRelationshipId](#Relationship_RetailTransactionServiceProfileRelationshipId)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|
|[Relationship_ServiceCredentialIDRelationshipId](#Relationship_ServiceCredentialIDRelationshipId)||<a href="RetailDeploymentRTSProfileExtension.md" target="_blank">Miscellaneous/RetailDeploymentRTSProfileExtension</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDeploymentRTSProfileExtension/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CertificateId name="CertificateId">CertificateId</a>

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

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

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

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

### <a href=#RetailTransactionServiceProfile name="RetailTransactionServiceProfile">RetailTransactionServiceProfile</a>

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTransactionServiceProfile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCredentialID name="ServiceCredentialID">ServiceCredentialID</a>

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

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

### <a href=#Relationship_RetailDeploymentCertificateRelationshipId name="Relationship_RetailDeploymentCertificateRelationshipId">Relationship_RetailDeploymentCertificateRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

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

### <a href=#Relationship_RetailDeploymentRTSProfileRelationshipId name="Relationship_RetailDeploymentRTSProfileRelationshipId">Relationship_RetailDeploymentRTSProfileRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeploymentRTSProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentRTSProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentRTSProfile.cdm.json/RetailDeploymentRTSProfile</a></td><td><a href="RetailDeploymentRTSProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionServiceProfileRelationshipId name="Relationship_RetailTransactionServiceProfileRelationshipId">Relationship_RetailTransactionServiceProfileRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionServiceProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailTransactionServiceProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailTransactionServiceProfile.cdm.json/RetailTransactionServiceProfile</a></td><td><a href="../Parameter/RetailTransactionServiceProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ServiceCredentialIDRelationshipId name="Relationship_ServiceCredentialIDRelationshipId">Relationship_ServiceCredentialIDRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentRTSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ServiceCredentialIDRelationshipId attribute are listed below.</summary>

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
