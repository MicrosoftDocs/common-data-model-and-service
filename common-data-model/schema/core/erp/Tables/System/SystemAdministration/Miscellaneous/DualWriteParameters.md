---
title: DualWriteParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# DualWriteParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Miscellaneous/DualWriteParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DualWriteParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DualWriteParameters.md" target="_blank">Miscellaneous/DualWriteParameters</a>|
|[DualWriteServiceBaseUrl](#DualWriteServiceBaseUrl)||<a href="DualWriteParameters.md" target="_blank">Miscellaneous/DualWriteParameters</a>|
|[MaxTransactionRecords](#MaxTransactionRecords)||<a href="DualWriteParameters.md" target="_blank">Miscellaneous/DualWriteParameters</a>|
|[EnableAutoPause](#EnableAutoPause)||<a href="DualWriteParameters.md" target="_blank">Miscellaneous/DualWriteParameters</a>|
|[ReconciliationBatchJobPollIntervalMinutes](#ReconciliationBatchJobPollIntervalMinutes)||<a href="DualWriteParameters.md" target="_blank">Miscellaneous/DualWriteParameters</a>|
|[LocalCommitTransactionExpirationMinutes](#LocalCommitTransactionExpirationMinutes)||<a href="DualWriteParameters.md" target="_blank">Miscellaneous/DualWriteParameters</a>|
|[Name](#Name)||<a href="DualWriteParameters.md" target="_blank">Miscellaneous/DualWriteParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DualWriteParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DualWriteParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DualWriteServiceBaseUrl name="DualWriteServiceBaseUrl">DualWriteServiceBaseUrl</a>

First included in: Miscellaneous/DualWriteParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DualWriteServiceBaseUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxTransactionRecords name="MaxTransactionRecords">MaxTransactionRecords</a>

First included in: Miscellaneous/DualWriteParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxTransactionRecords attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableAutoPause name="EnableAutoPause">EnableAutoPause</a>

First included in: Miscellaneous/DualWriteParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAutoPause attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReconciliationBatchJobPollIntervalMinutes name="ReconciliationBatchJobPollIntervalMinutes">ReconciliationBatchJobPollIntervalMinutes</a>

First included in: Miscellaneous/DualWriteParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciliationBatchJobPollIntervalMinutes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocalCommitTransactionExpirationMinutes name="LocalCommitTransactionExpirationMinutes">LocalCommitTransactionExpirationMinutes</a>

First included in: Miscellaneous/DualWriteParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocalCommitTransactionExpirationMinutes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/DualWriteParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
