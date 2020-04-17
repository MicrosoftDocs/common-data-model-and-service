---
title: RetailModernPOSProfileExtension - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailModernPOSProfileExtension

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailModernPOSProfileExtension.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailModernPOSProfileExtension/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[ConnectionStringServerName](#ConnectionStringServerName)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[Description](#Description)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[Name](#Name)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[offlineDbInstance](#offlineDbInstance)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[offlineDbName](#offlineDbName)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[OfflineDbProvisionCredentialId](#OfflineDbProvisionCredentialId)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[OfflineUserCredentials](#OfflineUserCredentials)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[RetailChannelDatabaseProfiles](#RetailChannelDatabaseProfiles)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[Relationship_DbProvisionCredentialsRelationshipId](#Relationship_DbProvisionCredentialsRelationshipId)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[Relationship_RetailChannelDatabaseProfilesRelationshipId](#Relationship_RetailChannelDatabaseProfilesRelationshipId)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[Relationship_RetailDeploymentCredentialsRelationshipId](#Relationship_RetailDeploymentCredentialsRelationshipId)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|
|[Relationship_RetailModernPOSProfileRelationshipId](#Relationship_RetailModernPOSProfileRelationshipId)||<a href="RetailModernPOSProfileExtension.md" target="_blank">Miscellaneous/RetailModernPOSProfileExtension</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailModernPOSProfileExtension/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConnectionStringServerName name="ConnectionStringServerName">ConnectionStringServerName</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

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

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

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

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

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

### <a href=#offlineDbInstance name="offlineDbInstance">offlineDbInstance</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the offlineDbInstance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#offlineDbName name="offlineDbName">offlineDbName</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the offlineDbName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfflineDbProvisionCredentialId name="OfflineDbProvisionCredentialId">OfflineDbProvisionCredentialId</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfflineDbProvisionCredentialId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OfflineUserCredentials name="OfflineUserCredentials">OfflineUserCredentials</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfflineUserCredentials attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailChannelDatabaseProfiles name="RetailChannelDatabaseProfiles">RetailChannelDatabaseProfiles</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

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

### <a href=#Relationship_DbProvisionCredentialsRelationshipId name="Relationship_DbProvisionCredentialsRelationshipId">Relationship_DbProvisionCredentialsRelationshipId</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DbProvisionCredentialsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentCredentials.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentCredentials.cdm.json/RetailDeploymentCredentials</a></td><td><a href="RetailDeploymentCredentials.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelDatabaseProfilesRelationshipId name="Relationship_RetailChannelDatabaseProfilesRelationshipId">Relationship_RetailChannelDatabaseProfilesRelationshipId</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailChannelDatabaseProfiles.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailChannelDatabaseProfiles.cdm.json/RetailChannelDatabaseProfiles</a></td><td><a href="RetailChannelDatabaseProfiles.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailDeploymentCredentialsRelationshipId name="Relationship_RetailDeploymentCredentialsRelationshipId">Relationship_RetailDeploymentCredentialsRelationshipId</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeploymentCredentialsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentCredentials.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentCredentials.cdm.json/RetailDeploymentCredentials</a></td><td><a href="RetailDeploymentCredentials.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailModernPOSProfileRelationshipId name="Relationship_RetailModernPOSProfileRelationshipId">Relationship_RetailModernPOSProfileRelationshipId</a>

First included in: Miscellaneous/RetailModernPOSProfileExtension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailModernPOSProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailModernPOSProfile.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailModernPOSProfile.cdm.json/RetailModernPOSProfile</a></td><td><a href="RetailModernPOSProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
