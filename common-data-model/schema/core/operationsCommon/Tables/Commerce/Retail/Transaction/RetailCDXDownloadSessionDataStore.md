---
title: RetailCDXDownloadSessionDataStore - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailCDXDownloadSessionDataStore

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailCDXDownloadSessionDataStore.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXDownloadSessionDataStore/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[DataStore](#DataStore)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[DateApplied](#DateApplied)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[DateDownloaded](#DateDownloaded)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[DateRequested](#DateRequested)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[Message](#Message)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[Session](#Session)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[Status](#Status)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[TryCount](#TryCount)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[RowsAffected](#RowsAffected)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[Relationship_RetailCDXDownloadSessionRelationshipId](#Relationship_RetailCDXDownloadSessionRelationshipId)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|
|[Relationship_RetailConnDatabaseProfileRelationshipId](#Relationship_RetailConnDatabaseProfileRelationshipId)||<a href="RetailCDXDownloadSessionDataStore.md" target="_blank">Transaction/RetailCDXDownloadSessionDataStore</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXDownloadSessionDataStore/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataStore name="DataStore">DataStore</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataStore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DateApplied name="DateApplied">DateApplied</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateApplied attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DateDownloaded name="DateDownloaded">DateDownloaded</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateDownloaded attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DateRequested name="DateRequested">DateRequested</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateRequested attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Message name="Message">Message</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Message attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Session name="Session">Session</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Session attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TryCount name="TryCount">TryCount</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TryCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RowsAffected name="RowsAffected">RowsAffected</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RowsAffected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_RetailCDXDownloadSessionRelationshipId name="Relationship_RetailCDXDownloadSessionRelationshipId">Relationship_RetailCDXDownloadSessionRelationshipId</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCDXDownloadSessionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailCDXDownloadSession.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailCDXDownloadSession.cdm.json/RetailCDXDownloadSession</a></td><td><a href="RetailCDXDownloadSession.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnDatabaseProfileRelationshipId name="Relationship_RetailConnDatabaseProfileRelationshipId">Relationship_RetailConnDatabaseProfileRelationshipId</a>

First included in: Transaction/RetailCDXDownloadSessionDataStore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnDatabaseProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailConnDatabaseProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailConnDatabaseProfile.cdm.json/RetailConnDatabaseProfile</a></td><td><a href="../Main/RetailConnDatabaseProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
