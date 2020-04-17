---
title: SysDataCacheConfigurationTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# SysDataCacheConfigurationTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Framework/SysDataCacheConfigurationTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysDataCacheConfigurationTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[ConsumerIdentifier](#ConsumerIdentifier)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[ConsumerType](#ConsumerType)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[RefreshFrequency](#RefreshFrequency)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[ManualRefreshEnabled](#ManualRefreshEnabled)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[FilteringEnabled](#FilteringEnabled)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[Enabled](#Enabled)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[ContextGroupingEnabled](#ContextGroupingEnabled)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[QueryableType](#QueryableType)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[QueryableIdentifier](#QueryableIdentifier)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[ChangeDetectionMethod](#ChangeDetectionMethod)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[BatchGroupId](#BatchGroupId)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[ChangeDetectionPackedDependencySet](#ChangeDetectionPackedDependencySet)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|
|[QueryablePacked](#QueryablePacked)||<a href="SysDataCacheConfigurationTable.md" target="_blank">Framework/SysDataCacheConfigurationTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysDataCacheConfigurationTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConsumerIdentifier name="ConsumerIdentifier">ConsumerIdentifier</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumerType name="ConsumerType">ConsumerType</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RefreshFrequency name="RefreshFrequency">RefreshFrequency</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefreshFrequency attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ManualRefreshEnabled name="ManualRefreshEnabled">ManualRefreshEnabled</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualRefreshEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FilteringEnabled name="FilteringEnabled">FilteringEnabled</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilteringEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Enabled name="Enabled">Enabled</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Enabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContextGroupingEnabled name="ContextGroupingEnabled">ContextGroupingEnabled</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContextGroupingEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#QueryableType name="QueryableType">QueryableType</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueryableType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#QueryableIdentifier name="QueryableIdentifier">QueryableIdentifier</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueryableIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeDetectionMethod name="ChangeDetectionMethod">ChangeDetectionMethod</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeDetectionMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#BatchGroupId name="BatchGroupId">BatchGroupId</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChangeDetectionPackedDependencySet name="ChangeDetectionPackedDependencySet">ChangeDetectionPackedDependencySet</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeDetectionPackedDependencySet attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#QueryablePacked name="QueryablePacked">QueryablePacked</a>

First included in: Framework/SysDataCacheConfigurationTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueryablePacked attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>
