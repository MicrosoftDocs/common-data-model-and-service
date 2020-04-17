---
title: ReleaseUpdateBulkCopyTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ReleaseUpdateBulkCopyTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Framework/ReleaseUpdateBulkCopyTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateBulkCopyTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[directSql](#directSql)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[HasTransformations](#HasTransformations)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[IsPerCompany](#IsPerCompany)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[newtableid](#newtableid)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[newtablename](#newtablename)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[newTableSqlName](#newTableSqlName)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[NumberOfFieldErrors](#NumberOfFieldErrors)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[oldTableId](#oldTableId)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[oldtablename](#oldtablename)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[OldTableSqlName](#OldTableSqlName)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[PerCompanyToGlobal](#PerCompanyToGlobal)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|
|[Status](#Status)||<a href="ReleaseUpdateBulkCopyTable.md" target="_blank">Framework/ReleaseUpdateBulkCopyTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateBulkCopyTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#directSql name="directSql">directSql</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the directSql attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasTransformations name="HasTransformations">HasTransformations</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasTransformations attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsPerCompany name="IsPerCompany">IsPerCompany</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPerCompany attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#newtableid name="newtableid">newtableid</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the newtableid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#newtablename name="newtablename">newtablename</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the newtablename attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#newTableSqlName name="newTableSqlName">newTableSqlName</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the newTableSqlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfFieldErrors name="NumberOfFieldErrors">NumberOfFieldErrors</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfFieldErrors attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#oldTableId name="oldTableId">oldTableId</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the oldTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#oldtablename name="oldtablename">oldtablename</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the oldtablename attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OldTableSqlName name="OldTableSqlName">OldTableSqlName</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldTableSqlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PerCompanyToGlobal name="PerCompanyToGlobal">PerCompanyToGlobal</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PerCompanyToGlobal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Framework/ReleaseUpdateBulkCopyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
