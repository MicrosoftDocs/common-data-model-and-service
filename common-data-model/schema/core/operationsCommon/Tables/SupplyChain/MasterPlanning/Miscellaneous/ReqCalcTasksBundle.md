---
title: ReqCalcTasksBundle - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ReqCalcTasksBundle

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Miscellaneous/ReqCalcTasksBundle.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqCalcTasksBundle/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[EndTime](#EndTime)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[Level](#Level)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[LevelState](#LevelState)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[ListNum](#ListNum)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[ProcessDataAreaId](#ProcessDataAreaId)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[ProcessId](#ProcessId)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[ProcessingState](#ProcessingState)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[StartTime](#StartTime)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[Status](#Status)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|
|[ThreadId](#ThreadId)||<a href="ReqCalcTasksBundle.md" target="_blank">Miscellaneous/ReqCalcTasksBundle</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqCalcTasksBundle/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EndTime name="EndTime">EndTime</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LevelState name="LevelState">LevelState</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LevelState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ListNum name="ListNum">ListNum</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ListNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProcessDataAreaId name="ProcessDataAreaId">ProcessDataAreaId</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessId name="ProcessId">ProcessId</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessingState name="ProcessingState">ProcessingState</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ThreadId name="ThreadId">ThreadId</a>

First included in: Miscellaneous/ReqCalcTasksBundle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThreadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
