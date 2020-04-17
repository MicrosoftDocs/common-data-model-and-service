---
title: RetailDocumentOperationGlobalParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailDocumentOperationGlobalParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailDocumentOperationGlobalParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDocumentOperationGlobalParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailDocumentOperationGlobalParameters.md" target="_blank">Miscellaneous/RetailDocumentOperationGlobalParameters</a>|
|[MaxNumThreads](#MaxNumThreads)||<a href="RetailDocumentOperationGlobalParameters.md" target="_blank">Miscellaneous/RetailDocumentOperationGlobalParameters</a>|
|[ProcessingTimeLimitInSeconds](#ProcessingTimeLimitInSeconds)||<a href="RetailDocumentOperationGlobalParameters.md" target="_blank">Miscellaneous/RetailDocumentOperationGlobalParameters</a>|
|[CommittedTimeLimitInSeconds](#CommittedTimeLimitInSeconds)||<a href="RetailDocumentOperationGlobalParameters.md" target="_blank">Miscellaneous/RetailDocumentOperationGlobalParameters</a>|
|[MaxRetryCount](#MaxRetryCount)||<a href="RetailDocumentOperationGlobalParameters.md" target="_blank">Miscellaneous/RetailDocumentOperationGlobalParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailDocumentOperationGlobalParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDocumentOperationGlobalParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MaxNumThreads name="MaxNumThreads">MaxNumThreads</a>

First included in: Miscellaneous/RetailDocumentOperationGlobalParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumThreads attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProcessingTimeLimitInSeconds name="ProcessingTimeLimitInSeconds">ProcessingTimeLimitInSeconds</a>

First included in: Miscellaneous/RetailDocumentOperationGlobalParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingTimeLimitInSeconds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CommittedTimeLimitInSeconds name="CommittedTimeLimitInSeconds">CommittedTimeLimitInSeconds</a>

First included in: Miscellaneous/RetailDocumentOperationGlobalParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommittedTimeLimitInSeconds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxRetryCount name="MaxRetryCount">MaxRetryCount</a>

First included in: Miscellaneous/RetailDocumentOperationGlobalParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxRetryCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
