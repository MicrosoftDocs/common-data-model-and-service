---
title: SysIndexDetails - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# SysIndexDetails

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Miscellaneous/SysIndexDetails.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysIndexDetails/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[SchemaName](#SchemaName)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[TableName](#TableName)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[IndexName](#IndexName)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[TableIdNumber](#TableIdNumber)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[IndexIdNumber](#IndexIdNumber)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[IndexType](#IndexType)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[IndexTypeDescription](#IndexTypeDescription)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[IndexLevel](#IndexLevel)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[AllowPageLocks](#AllowPageLocks)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[PartitionNumber](#PartitionNumber)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|
|[RecordCount](#RecordCount)||<a href="SysIndexDetails.md" target="_blank">Miscellaneous/SysIndexDetails</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysIndexDetails/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SchemaName name="SchemaName">SchemaName</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchemaName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TableName name="TableName">TableName</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndexName name="IndexName">IndexName</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndexName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TableIdNumber name="TableIdNumber">TableIdNumber</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableIdNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IndexIdNumber name="IndexIdNumber">IndexIdNumber</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndexIdNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IndexType name="IndexType">IndexType</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndexType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IndexTypeDescription name="IndexTypeDescription">IndexTypeDescription</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndexTypeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndexLevel name="IndexLevel">IndexLevel</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndexLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowPageLocks name="AllowPageLocks">AllowPageLocks</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPageLocks attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PartitionNumber name="PartitionNumber">PartitionNumber</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartitionNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RecordCount name="RecordCount">RecordCount</a>

First included in: Miscellaneous/SysIndexDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>
