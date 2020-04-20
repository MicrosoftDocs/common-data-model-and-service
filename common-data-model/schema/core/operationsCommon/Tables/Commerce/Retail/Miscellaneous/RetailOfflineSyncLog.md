---
title: RetailOfflineSyncLog - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailOfflineSyncLog

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailOfflineSyncLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailOfflineSyncLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[LogTime](#LogTime)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[ReplicationCounterFromOrigin](#ReplicationCounterFromOrigin)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[ScopeID](#ScopeID)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[SyncStartTime](#SyncStartTime)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[SyncStopTime](#SyncStopTime)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[terminal](#terminal)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[TotalDownloaded](#TotalDownloaded)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[TotalDownloadedERR](#TotalDownloadedERR)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[TotalDownloadedOK](#TotalDownloadedOK)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[TotalUploaded](#TotalUploaded)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[TotalUploadedERR](#TotalUploadedERR)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[TotalUploadedOK](#TotalUploadedOK)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|
|[Relationship_SyncScopeRelationshipId](#Relationship_SyncScopeRelationshipId)||<a href="RetailOfflineSyncLog.md" target="_blank">Miscellaneous/RetailOfflineSyncLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailOfflineSyncLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LogTime name="LogTime">LogTime</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ReplicationCounterFromOrigin name="ReplicationCounterFromOrigin">ReplicationCounterFromOrigin</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ScopeID name="ScopeID">ScopeID</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScopeID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SyncStartTime name="SyncStartTime">SyncStartTime</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SyncStartTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SyncStopTime name="SyncStopTime">SyncStopTime</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SyncStopTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#terminal name="terminal">terminal</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDownloaded name="TotalDownloaded">TotalDownloaded</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDownloaded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TotalDownloadedERR name="TotalDownloadedERR">TotalDownloadedERR</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDownloadedERR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TotalDownloadedOK name="TotalDownloadedOK">TotalDownloadedOK</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDownloadedOK attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TotalUploaded name="TotalUploaded">TotalUploaded</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalUploaded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TotalUploadedERR name="TotalUploadedERR">TotalUploadedERR</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalUploadedERR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TotalUploadedOK name="TotalUploadedOK">TotalUploadedOK</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalUploadedOK attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SyncScopeRelationshipId name="Relationship_SyncScopeRelationshipId">Relationship_SyncScopeRelationshipId</a>

First included in: Miscellaneous/RetailOfflineSyncLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SyncScopeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailOfflineScope.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailOfflineScope.cdm.json/RetailOfflineScope</a></td><td><a href="RetailOfflineScope.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
