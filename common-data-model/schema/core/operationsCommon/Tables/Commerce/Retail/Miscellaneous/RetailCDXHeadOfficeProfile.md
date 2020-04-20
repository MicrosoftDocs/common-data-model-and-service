---
title: RetailCDXHeadOfficeProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailCDXHeadOfficeProfile

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailCDXHeadOfficeProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXHeadOfficeProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[ApplicationPoolName](#ApplicationPoolName)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[BaseURL](#BaseURL)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[CertificateRootStore](#CertificateRootStore)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[CertificateStore](#CertificateStore)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[CertificateThumbprint](#CertificateThumbprint)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[ConnectionStringServerName](#ConnectionStringServerName)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[Description](#Description)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[HTTPSPort](#HTTPSPort)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[MessageDBComputer](#MessageDBComputer)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[MessageDBInstanceName](#MessageDBInstanceName)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[MessageDBName](#MessageDBName)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[Name](#Name)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[RetailCDXFileStorageProvider](#RetailCDXFileStorageProvider)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[RetailMachineCluster](#RetailMachineCluster)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[ServiceInstallFolder](#ServiceInstallFolder)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[TCPPort](#TCPPort)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[WebApplicationName](#WebApplicationName)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[WebSiteName](#WebSiteName)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[Relationship_Relation1RelationshipId](#Relationship_Relation1RelationshipId)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[Relationship_RetailCDXFileStorageProviderRelationshipId](#Relationship_RetailCDXFileStorageProviderRelationshipId)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|
|[Relationship_RetailMachineClusterRelationshipId](#Relationship_RetailMachineClusterRelationshipId)||<a href="RetailCDXHeadOfficeProfile.md" target="_blank">Miscellaneous/RetailCDXHeadOfficeProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXHeadOfficeProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApplicationPoolName name="ApplicationPoolName">ApplicationPoolName</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

### <a href=#BaseURL name="BaseURL">BaseURL</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateRootStore name="CertificateRootStore">CertificateRootStore</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

### <a href=#HTTPSPort name="HTTPSPort">HTTPSPort</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HTTPSPort attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MessageDBComputer name="MessageDBComputer">MessageDBComputer</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageDBComputer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MessageDBInstanceName name="MessageDBInstanceName">MessageDBInstanceName</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageDBInstanceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessageDBName name="MessageDBName">MessageDBName</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageDBName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

### <a href=#RetailCDXFileStorageProvider name="RetailCDXFileStorageProvider">RetailCDXFileStorageProvider</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailCDXFileStorageProvider attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailMachineCluster name="RetailMachineCluster">RetailMachineCluster</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

### <a href=#TCPPort name="TCPPort">TCPPort</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCPPort attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WebApplicationName name="WebApplicationName">WebApplicationName</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

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

### <a href=#Relationship_Relation1RelationshipId name="Relationship_Relation1RelationshipId">Relationship_Relation1RelationshipId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Relation1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailMachine.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailMachine.cdm.json/RetailMachine</a></td><td><a href="RetailMachine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailCDXFileStorageProviderRelationshipId name="Relationship_RetailCDXFileStorageProviderRelationshipId">Relationship_RetailCDXFileStorageProviderRelationshipId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCDXFileStorageProviderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailCDXFileStorageProvider.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailCDXFileStorageProvider.cdm.json/RetailCDXFileStorageProvider</a></td><td><a href="../Main/RetailCDXFileStorageProvider.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailMachineClusterRelationshipId name="Relationship_RetailMachineClusterRelationshipId">Relationship_RetailMachineClusterRelationshipId</a>

First included in: Miscellaneous/RetailCDXHeadOfficeProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailMachineClusterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailMachineCluster.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailMachineCluster.cdm.json/RetailMachineCluster</a></td><td><a href="RetailMachineCluster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
