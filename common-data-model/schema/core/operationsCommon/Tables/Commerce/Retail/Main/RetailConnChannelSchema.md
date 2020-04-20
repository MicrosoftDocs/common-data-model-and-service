---
title: RetailConnChannelSchema - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailConnChannelSchema

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Main/RetailConnChannelSchema.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnChannelSchema/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[ChannelSpecificDataClass](#ChannelSpecificDataClass)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[DataOutputClass](#DataOutputClass)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[DataOutputFormat](#DataOutputFormat)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[DataTranslationClass](#DataTranslationClass)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[DataUploadClass](#DataUploadClass)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[SchemaName](#SchemaName)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[SchemaType](#SchemaType)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[TableDistributionXML](#TableDistributionXML)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[UseLegacyTransport](#UseLegacyTransport)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|
|[IsWorkloadSchema](#IsWorkloadSchema)||<a href="RetailConnChannelSchema.md" target="_blank">Main/RetailConnChannelSchema</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnChannelSchema/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChannelSpecificDataClass name="ChannelSpecificDataClass">ChannelSpecificDataClass</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelSpecificDataClass attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataOutputClass name="DataOutputClass">DataOutputClass</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataOutputClass attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataOutputFormat name="DataOutputFormat">DataOutputFormat</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataOutputFormat attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataTranslationClass name="DataTranslationClass">DataTranslationClass</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataTranslationClass attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataUploadClass name="DataUploadClass">DataUploadClass</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataUploadClass attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchemaName name="SchemaName">SchemaName</a>

First included in: Main/RetailConnChannelSchema (this entity)  

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

### <a href=#SchemaType name="SchemaType">SchemaType</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchemaType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TableDistributionXML name="TableDistributionXML">TableDistributionXML</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableDistributionXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseLegacyTransport name="UseLegacyTransport">UseLegacyTransport</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseLegacyTransport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsWorkloadSchema name="IsWorkloadSchema">IsWorkloadSchema</a>

First included in: Main/RetailConnChannelSchema (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkloadSchema attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
