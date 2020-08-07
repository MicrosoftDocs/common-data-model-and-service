---
title: SystemJobParameters in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# System job parameters in Parameter(SystemJobParameters)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Parameter/SystemJobParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SystemJobParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>System job parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[Key](#Key)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[DefragMaxExecutionTime](#DefragMaxExecutionTime)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[DefragTopNSqlIndex](#DefragTopNSqlIndex)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[DefragDtuThreshold](#DefragDtuThreshold)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[DefragOfflineMode](#DefragOfflineMode)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[CompressionMaxExecutionTime](#CompressionMaxExecutionTime)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[CryptoCrawlerMaxExecutionTime](#CryptoCrawlerMaxExecutionTime)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[EncryptedDataRotationMaxExecutionTimeInMins](#EncryptedDataRotationMaxExecutionTimeInMins)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[PBSMigrationLastProcBatchJobId](#PBSMigrationLastProcBatchJobId)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[SignatureCrawlerMaxExecutionTimeInMins](#SignatureCrawlerMaxExecutionTimeInMins)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|
|[SignatureRotationMaxExecutionTimeInMins](#SignatureRotationMaxExecutionTimeInMins)||<a href="SystemJobParameters.md" target="_blank">Parameter/SystemJobParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SystemJobParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefragMaxExecutionTime name="DefragMaxExecutionTime">DefragMaxExecutionTime</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefragMaxExecutionTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefragTopNSqlIndex name="DefragTopNSqlIndex">DefragTopNSqlIndex</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefragTopNSqlIndex attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefragDtuThreshold name="DefragDtuThreshold">DefragDtuThreshold</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefragDtuThreshold attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefragOfflineMode name="DefragOfflineMode">DefragOfflineMode</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefragOfflineMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CompressionMaxExecutionTime name="CompressionMaxExecutionTime">CompressionMaxExecutionTime</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompressionMaxExecutionTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CryptoCrawlerMaxExecutionTime name="CryptoCrawlerMaxExecutionTime">CryptoCrawlerMaxExecutionTime</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CryptoCrawlerMaxExecutionTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EncryptedDataRotationMaxExecutionTimeInMins name="EncryptedDataRotationMaxExecutionTimeInMins">EncryptedDataRotationMaxExecutionTimeInMins</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EncryptedDataRotationMaxExecutionTimeInMins attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PBSMigrationLastProcBatchJobId name="PBSMigrationLastProcBatchJobId">PBSMigrationLastProcBatchJobId</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PBSMigrationLastProcBatchJobId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SignatureCrawlerMaxExecutionTimeInMins name="SignatureCrawlerMaxExecutionTimeInMins">SignatureCrawlerMaxExecutionTimeInMins</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureCrawlerMaxExecutionTimeInMins attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SignatureRotationMaxExecutionTimeInMins name="SignatureRotationMaxExecutionTimeInMins">SignatureRotationMaxExecutionTimeInMins</a>

First included in: Parameter/SystemJobParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureRotationMaxExecutionTimeInMins attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>
