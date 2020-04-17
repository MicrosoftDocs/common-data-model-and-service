---
title: SysFilterTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# SysFilterTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Framework/SysFilterTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysFilterTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|
|[SysFilterStructureId](#SysFilterStructureId)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|
|[FilterItemValueDateTime](#FilterItemValueDateTime)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|
|[FilterItemValueRecord](#FilterItemValueRecord)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|
|[HashKey](#HashKey)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|
|[FilterItemValueResolutionMethod](#FilterItemValueResolutionMethod)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|
|[FilterItemValueInteger](#FilterItemValueInteger)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|
|[FilterItemValueString](#FilterItemValueString)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|
|[FilterItemValueDate](#FilterItemValueDate)||<a href="SysFilterTable.md" target="_blank">Framework/SysFilterTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysFilterTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SysFilterStructureId name="SysFilterStructureId">SysFilterStructureId</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SysFilterStructureId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FilterItemValueDateTime name="FilterItemValueDateTime">FilterItemValueDateTime</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterItemValueDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FilterItemValueRecord name="FilterItemValueRecord">FilterItemValueRecord</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterItemValueRecord attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HashKey name="HashKey">HashKey</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HashKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FilterItemValueResolutionMethod name="FilterItemValueResolutionMethod">FilterItemValueResolutionMethod</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterItemValueResolutionMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FilterItemValueInteger name="FilterItemValueInteger">FilterItemValueInteger</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterItemValueInteger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FilterItemValueString name="FilterItemValueString">FilterItemValueString</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterItemValueString attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FilterItemValueDate name="FilterItemValueDate">FilterItemValueDate</a>

First included in: Framework/SysFilterTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterItemValueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>
