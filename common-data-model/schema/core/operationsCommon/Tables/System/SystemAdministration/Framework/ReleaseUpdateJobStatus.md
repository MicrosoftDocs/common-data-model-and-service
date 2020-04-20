---
title: ReleaseUpdateJobStatus - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ReleaseUpdateJobStatus

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Framework/ReleaseUpdateJobStatus.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateJobStatus/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[BatchId](#BatchId)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[Changed](#Changed)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[Company](#Company)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[DataPartition](#DataPartition)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[EndDateTime](#EndDateTime)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[JobID](#JobID)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[Mode](#Mode)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[Restarted](#Restarted)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[ScriptID](#ScriptID)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[ScriptStage](#ScriptStage)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[scriptVersion](#scriptVersion)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[StartDateTime](#StartDateTime)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[Status](#Status)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[TimeRunning](#TimeRunning)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[WhenToRun](#WhenToRun)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[WhenToRunEx](#WhenToRunEx)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[Relationship_BatchRelationshipId](#Relationship_BatchRelationshipId)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|
|[Relationship_ReleaseUpdateScriptsRelationshipId](#Relationship_ReleaseUpdateScriptsRelationshipId)||<a href="ReleaseUpdateJobStatus.md" target="_blank">Framework/ReleaseUpdateJobStatus</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateJobStatus/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchId name="BatchId">BatchId</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Changed name="Changed">Changed</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Changed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataPartition name="DataPartition">DataPartition</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataPartition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDateTime name="EndDateTime">EndDateTime</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#JobID name="JobID">JobID</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Mode name="Mode">Mode</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Mode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Restarted name="Restarted">Restarted</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Restarted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ScriptID name="ScriptID">ScriptID</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScriptID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ScriptStage name="ScriptStage">ScriptStage</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScriptStage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#scriptVersion name="scriptVersion">scriptVersion</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the scriptVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartDateTime name="StartDateTime">StartDateTime</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TimeRunning name="TimeRunning">TimeRunning</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeRunning attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WhenToRun name="WhenToRun">WhenToRun</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WhenToRun attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WhenToRunEx name="WhenToRunEx">WhenToRunEx</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WhenToRunEx attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_BatchRelationshipId name="Relationship_BatchRelationshipId">Relationship_BatchRelationshipId</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BatchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/Batch.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/Batch.cdm.json/Batch</a></td><td><a href="../Transaction/Batch.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReleaseUpdateScriptsRelationshipId name="Relationship_ReleaseUpdateScriptsRelationshipId">Relationship_ReleaseUpdateScriptsRelationshipId</a>

First included in: Framework/ReleaseUpdateJobStatus (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReleaseUpdateScriptsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ReleaseUpdateScripts.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/ReleaseUpdateScripts.cdm.json/ReleaseUpdateScripts</a></td><td><a href="ReleaseUpdateScripts.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
