---
title: RetailServerServiceProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailServerServiceProfile

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Main/RetailServerServiceProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailServerServiceProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[ApplicationPoolName](#ApplicationPoolName)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[CertificateRootStore](#CertificateRootStore)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[CertificateStore](#CertificateStore)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[CertificateThumbprint](#CertificateThumbprint)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[ConnectionStringServerName](#ConnectionStringServerName)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[Description](#Description)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[HTTPPort](#HTTPPort)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[HTTPSPort](#HTTPSPort)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[Name](#Name)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[RetailChannelDatabaseProfiles](#RetailChannelDatabaseProfiles)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[RetailDeploymentRTSProfile](#RetailDeploymentRTSProfile)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[RetailMachineCluster](#RetailMachineCluster)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[ServiceInstallFolder](#ServiceInstallFolder)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[WebApplicationName](#WebApplicationName)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[WebSiteName](#WebSiteName)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[CertificateId](#CertificateId)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[Relationship_MachineClusterRelationshipId](#Relationship_MachineClusterRelationshipId)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[Relationship_RealTimeServiceProfileRelationshipId](#Relationship_RealTimeServiceProfileRelationshipId)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[Relationship_RetailChannelDatabaseProfilesRelationshipId](#Relationship_RetailChannelDatabaseProfilesRelationshipId)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|
|[Relationship_RetailDeploymentCertificateRelationshipId](#Relationship_RetailDeploymentCertificateRelationshipId)||<a href="RetailServerServiceProfile.md" target="_blank">Main/RetailServerServiceProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailServerServiceProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApplicationPoolName name="ApplicationPoolName">ApplicationPoolName</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationPoolName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateRootStore name="CertificateRootStore">CertificateRootStore</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateRootStore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateStore name="CertificateStore">CertificateStore</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateStore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateThumbprint name="CertificateThumbprint">CertificateThumbprint</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateThumbprint attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConnectionStringServerName name="ConnectionStringServerName">ConnectionStringServerName</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConnectionStringServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HTTPPort name="HTTPPort">HTTPPort</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HTTPPort attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HTTPSPort name="HTTPSPort">HTTPSPort</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HTTPSPort attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/RetailServerServiceProfile (this entity)  

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

### <a href=#RetailChannelDatabaseProfiles name="RetailChannelDatabaseProfiles">RetailChannelDatabaseProfiles</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelDatabaseProfiles attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailDeploymentRTSProfile name="RetailDeploymentRTSProfile">RetailDeploymentRTSProfile</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDeploymentRTSProfile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailMachineCluster name="RetailMachineCluster">RetailMachineCluster</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailMachineCluster attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceInstallFolder name="ServiceInstallFolder">ServiceInstallFolder</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceInstallFolder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WebApplicationName name="WebApplicationName">WebApplicationName</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WebApplicationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WebSiteName name="WebSiteName">WebSiteName</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WebSiteName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateId name="CertificateId">CertificateId</a>

First included in: Main/RetailServerServiceProfile (this entity)  

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

### <a href=#Relationship_MachineClusterRelationshipId name="Relationship_MachineClusterRelationshipId">Relationship_MachineClusterRelationshipId</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MachineClusterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailMachineCluster.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailMachineCluster.cdm.json/RetailMachineCluster</a></td><td><a href="../Miscellaneous/RetailMachineCluster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealTimeServiceProfileRelationshipId name="Relationship_RealTimeServiceProfileRelationshipId">Relationship_RealTimeServiceProfileRelationshipId</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealTimeServiceProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailDeploymentRTSProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentRTSProfile.cdm.json/RetailDeploymentRTSProfile</a></td><td><a href="../Miscellaneous/RetailDeploymentRTSProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelDatabaseProfilesRelationshipId name="Relationship_RetailChannelDatabaseProfilesRelationshipId">Relationship_RetailChannelDatabaseProfilesRelationshipId</a>

First included in: Main/RetailServerServiceProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelDatabaseProfilesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailChannelDatabaseProfiles.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailChannelDatabaseProfiles.cdm.json/RetailChannelDatabaseProfiles</a></td><td><a href="../Miscellaneous/RetailChannelDatabaseProfiles.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailDeploymentCertificateRelationshipId name="Relationship_RetailDeploymentCertificateRelationshipId">Relationship_RetailDeploymentCertificateRelationshipId</a>

First included in: Main/RetailServerServiceProfile (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailDeploymentCertificates.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentCertificates.cdm.json/RetailDeploymentCertificates</a></td><td><a href="../Miscellaneous/RetailDeploymentCertificates.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
