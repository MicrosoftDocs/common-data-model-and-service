---
title: RetailOnlineChannelFunctionalityProfileTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailOnlineChannelFunctionalityProfileTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Group/RetailOnlineChannelFunctionalityProfileTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailOnlineChannelFunctionalityProfileTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailOnlineChannelFunctionalityProfileTable.md" target="_blank">Group/RetailOnlineChannelFunctionalityProfileTable</a>|
|[profileId](#profileId)||<a href="RetailOnlineChannelFunctionalityProfileTable.md" target="_blank">Group/RetailOnlineChannelFunctionalityProfileTable</a>|
|[aggregateItems](#aggregateItems)||<a href="RetailOnlineChannelFunctionalityProfileTable.md" target="_blank">Group/RetailOnlineChannelFunctionalityProfileTable</a>|
|[name](#name)||<a href="RetailOnlineChannelFunctionalityProfileTable.md" target="_blank">Group/RetailOnlineChannelFunctionalityProfileTable</a>|
|[CreateAsyncCustomers](#CreateAsyncCustomers)||<a href="RetailOnlineChannelFunctionalityProfileTable.md" target="_blank">Group/RetailOnlineChannelFunctionalityProfileTable</a>|
|[RetailCheckoutAllowNoPayment](#RetailCheckoutAllowNoPayment)||<a href="RetailOnlineChannelFunctionalityProfileTable.md" target="_blank">Group/RetailOnlineChannelFunctionalityProfileTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/RetailOnlineChannelFunctionalityProfileTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailOnlineChannelFunctionalityProfileTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#profileId name="profileId">profileId</a>

First included in: Group/RetailOnlineChannelFunctionalityProfileTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the profileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#aggregateItems name="aggregateItems">aggregateItems</a>

First included in: Group/RetailOnlineChannelFunctionalityProfileTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the aggregateItems attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#name name="name">name</a>

First included in: Group/RetailOnlineChannelFunctionalityProfileTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateAsyncCustomers name="CreateAsyncCustomers">CreateAsyncCustomers</a>

First included in: Group/RetailOnlineChannelFunctionalityProfileTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateAsyncCustomers attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailCheckoutAllowNoPayment name="RetailCheckoutAllowNoPayment">RetailCheckoutAllowNoPayment</a>

First included in: Group/RetailOnlineChannelFunctionalityProfileTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailCheckoutAllowNoPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
