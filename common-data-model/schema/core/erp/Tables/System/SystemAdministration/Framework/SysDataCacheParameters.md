---
title: SysDataCacheParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# SysDataCacheParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Framework/SysDataCacheParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysDataCacheParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[CacheContextExpirationTime](#CacheContextExpirationTime)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[CacheContextActiveStateTimeout](#CacheContextActiveStateTimeout)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[RefreshBatchJobThreads](#RefreshBatchJobThreads)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[CurrentVersion](#CurrentVersion)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[DefaultBatchGroupId](#DefaultBatchGroupId)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[StopRefreshBatchJob](#StopRefreshBatchJob)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[Enabled](#Enabled)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[ForceRefreshOnCacheMiss](#ForceRefreshOnCacheMiss)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|
|[ForceRefreshOnCacheMissThreshold](#ForceRefreshOnCacheMissThreshold)||<a href="SysDataCacheParameters.md" target="_blank">Framework/SysDataCacheParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysDataCacheParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CacheContextExpirationTime name="CacheContextExpirationTime">CacheContextExpirationTime</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CacheContextExpirationTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CacheContextActiveStateTimeout name="CacheContextActiveStateTimeout">CacheContextActiveStateTimeout</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CacheContextActiveStateTimeout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RefreshBatchJobThreads name="RefreshBatchJobThreads">RefreshBatchJobThreads</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefreshBatchJobThreads attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CurrentVersion name="CurrentVersion">CurrentVersion</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultBatchGroupId name="DefaultBatchGroupId">DefaultBatchGroupId</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBatchGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StopRefreshBatchJob name="StopRefreshBatchJob">StopRefreshBatchJob</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StopRefreshBatchJob attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Enabled name="Enabled">Enabled</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Enabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ForceRefreshOnCacheMiss name="ForceRefreshOnCacheMiss">ForceRefreshOnCacheMiss</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForceRefreshOnCacheMiss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ForceRefreshOnCacheMissThreshold name="ForceRefreshOnCacheMissThreshold">ForceRefreshOnCacheMissThreshold</a>

First included in: Framework/SysDataCacheParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForceRefreshOnCacheMissThreshold attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
