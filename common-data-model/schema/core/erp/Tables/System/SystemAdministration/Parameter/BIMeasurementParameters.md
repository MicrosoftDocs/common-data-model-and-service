---
title: BIMeasurementParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# BIMeasurementParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Parameter/BIMeasurementParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BIMeasurementParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|
|[Key](#Key)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|
|[CDSAEnabled](#CDSAEnabled)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|
|[KeyVaultDnsName](#KeyVaultDnsName)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|
|[KeyVaultSecretName](#KeyVaultSecretName)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|
|[AzureAppId](#AzureAppId)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|
|[AzureAppSecret](#AzureAppSecret)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|
|[UseNewEntityStoreForm](#UseNewEntityStoreForm)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|
|[IncrementalEnabled](#IncrementalEnabled)||<a href="BIMeasurementParameters.md" target="_blank">Parameter/BIMeasurementParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BIMeasurementParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CDSAEnabled name="CDSAEnabled">CDSAEnabled</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CDSAEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#KeyVaultDnsName name="KeyVaultDnsName">KeyVaultDnsName</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyVaultDnsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyVaultSecretName name="KeyVaultSecretName">KeyVaultSecretName</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyVaultSecretName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AzureAppId name="AzureAppId">AzureAppId</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureAppId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AzureAppSecret name="AzureAppSecret">AzureAppSecret</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureAppSecret attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseNewEntityStoreForm name="UseNewEntityStoreForm">UseNewEntityStoreForm</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseNewEntityStoreForm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncrementalEnabled name="IncrementalEnabled">IncrementalEnabled</a>

First included in: Parameter/BIMeasurementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncrementalEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
