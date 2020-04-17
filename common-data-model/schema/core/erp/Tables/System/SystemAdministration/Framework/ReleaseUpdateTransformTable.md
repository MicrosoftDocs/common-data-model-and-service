---
title: ReleaseUpdateTransformTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ReleaseUpdateTransformTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Framework/ReleaseUpdateTransformTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateTransformTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[Description](#Description)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[DictionaryTableName](#DictionaryTableName)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[IsPerCompany](#IsPerCompany)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[JoinType](#JoinType)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[PerCompanyToGlobal](#PerCompanyToGlobal)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[ReadyToBeCopied](#ReadyToBeCopied)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[ShadowTableName](#ShadowTableName)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[SourceTableId](#SourceTableId)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|
|[SourceTableName](#SourceTableName)||<a href="ReleaseUpdateTransformTable.md" target="_blank">Framework/ReleaseUpdateTransformTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateTransformTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

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

### <a href=#DictionaryTableName name="DictionaryTableName">DictionaryTableName</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DictionaryTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPerCompany name="IsPerCompany">IsPerCompany</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPerCompany attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JoinType name="JoinType">JoinType</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JoinType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PerCompanyToGlobal name="PerCompanyToGlobal">PerCompanyToGlobal</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PerCompanyToGlobal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReadyToBeCopied name="ReadyToBeCopied">ReadyToBeCopied</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReadyToBeCopied attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShadowTableName name="ShadowTableName">ShadowTableName</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShadowTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceTableId name="SourceTableId">SourceTableId</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceTableName name="SourceTableName">SourceTableName</a>

First included in: Framework/ReleaseUpdateTransformTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
