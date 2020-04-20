---
title: RetailInventAvailabilityLastTransDateTime - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailInventAvailabilityLastTransDateTime

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailInventAvailabilityLastTransDateTime.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailInventAvailabilityLastTransDateTime/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailInventAvailabilityLastTransDateTime.md" target="_blank">Miscellaneous/RetailInventAvailabilityLastTransDateTime</a>|
|[ChannelId](#ChannelId)||<a href="RetailInventAvailabilityLastTransDateTime.md" target="_blank">Miscellaneous/RetailInventAvailabilityLastTransDateTime</a>|
|[LastTransDate](#LastTransDate)||<a href="RetailInventAvailabilityLastTransDateTime.md" target="_blank">Miscellaneous/RetailInventAvailabilityLastTransDateTime</a>|
|[LastTransTime](#LastTransTime)||<a href="RetailInventAvailabilityLastTransDateTime.md" target="_blank">Miscellaneous/RetailInventAvailabilityLastTransDateTime</a>|
|[UnprocessedStartTransDate](#UnprocessedStartTransDate)||<a href="RetailInventAvailabilityLastTransDateTime.md" target="_blank">Miscellaneous/RetailInventAvailabilityLastTransDateTime</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailInventAvailabilityLastTransDateTime (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailInventAvailabilityLastTransDateTime/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChannelId name="ChannelId">ChannelId</a>

First included in: Miscellaneous/RetailInventAvailabilityLastTransDateTime (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LastTransDate name="LastTransDate">LastTransDate</a>

First included in: Miscellaneous/RetailInventAvailabilityLastTransDateTime (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LastTransTime name="LastTransTime">LastTransTime</a>

First included in: Miscellaneous/RetailInventAvailabilityLastTransDateTime (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastTransTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#UnprocessedStartTransDate name="UnprocessedStartTransDate">UnprocessedStartTransDate</a>

First included in: Miscellaneous/RetailInventAvailabilityLastTransDateTime (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnprocessedStartTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>
