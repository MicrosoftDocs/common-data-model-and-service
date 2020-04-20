---
title: ReleaseUpdateSysDeleted - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ReleaseUpdateSysDeleted

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Framework/ReleaseUpdateSysDeleted.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateSysDeleted/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|
|[Array](#Array)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|
|[Flags](#Flags)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|
|[OldFieldId](#OldFieldId)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|
|[OldFieldName](#OldFieldName)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|
|[OldSqlName](#OldSqlName)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|
|[OldTableId](#OldTableId)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|
|[OldTableName](#OldTableName)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|
|[Shadow](#Shadow)||<a href="ReleaseUpdateSysDeleted.md" target="_blank">Framework/ReleaseUpdateSysDeleted</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateSysDeleted/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Array name="Array">Array</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Array attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Flags name="Flags">Flags</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Flags attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#OldFieldId name="OldFieldId">OldFieldId</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#OldFieldName name="OldFieldName">OldFieldName</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OldSqlName name="OldSqlName">OldSqlName</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldSqlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OldTableId name="OldTableId">OldTableId</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#OldTableName name="OldTableName">OldTableName</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Shadow name="Shadow">Shadow</a>

First included in: Framework/ReleaseUpdateSysDeleted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Shadow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>
