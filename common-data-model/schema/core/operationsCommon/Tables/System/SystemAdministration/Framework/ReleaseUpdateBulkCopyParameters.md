---
title: ReleaseUpdateBulkCopyParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ReleaseUpdateBulkCopyParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Framework/ReleaseUpdateBulkCopyParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateBulkCopyParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|
|[Database](#Database)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|
|[ExplicitLevel](#ExplicitLevel)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|
|[Key](#Key)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|
|[ServerName](#ServerName)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|
|[SourceConnectionString](#SourceConnectionString)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|
|[SourceCountryRegionISOcode_RU](#SourceCountryRegionISOcode_RU)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|
|[TargetConnectionString](#TargetConnectionString)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|
|[TopNTables](#TopNTables)||<a href="ReleaseUpdateBulkCopyParameters.md" target="_blank">Framework/ReleaseUpdateBulkCopyParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateBulkCopyParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Database name="Database">Database</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Database attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExplicitLevel name="ExplicitLevel">ExplicitLevel</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExplicitLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ServerName name="ServerName">ServerName</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceConnectionString name="SourceConnectionString">SourceConnectionString</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceConnectionString attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceCountryRegionISOcode_RU name="SourceCountryRegionISOcode_RU">SourceCountryRegionISOcode_RU</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceCountryRegionISOcode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetConnectionString name="TargetConnectionString">TargetConnectionString</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetConnectionString attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TopNTables name="TopNTables">TopNTables</a>

First included in: Framework/ReleaseUpdateBulkCopyParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TopNTables attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
