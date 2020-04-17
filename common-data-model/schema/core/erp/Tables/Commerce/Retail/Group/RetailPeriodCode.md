---
title: RetailPeriodCode - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailPeriodCode

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Group/RetailPeriodCode.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPeriodCode/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[Code](#Code)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[EndChange](#EndChange)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[EndFixedDate](#EndFixedDate)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[EndFunction1](#EndFunction1)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[EndFunction2](#EndFunction2)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[EndPeriod1](#EndPeriod1)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[EndPeriod2](#EndPeriod2)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[EndUnit](#EndUnit)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[StartChange](#StartChange)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[StartFixedDate](#StartFixedDate)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[StartFunction1](#StartFunction1)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[StartFunction2](#StartFunction2)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[StartPeriod1](#StartPeriod1)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[StartPeriod2](#StartPeriod2)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[StartUnit](#StartUnit)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|
|[Txt](#Txt)||<a href="RetailPeriodCode.md" target="_blank">Group/RetailPeriodCode</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPeriodCode/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Code name="Code">Code</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Code attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndChange name="EndChange">EndChange</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EndFixedDate name="EndFixedDate">EndFixedDate</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndFixedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EndFunction1 name="EndFunction1">EndFunction1</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndFunction1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EndFunction2 name="EndFunction2">EndFunction2</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndFunction2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EndPeriod1 name="EndPeriod1">EndPeriod1</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndPeriod1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EndPeriod2 name="EndPeriod2">EndPeriod2</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndPeriod2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EndUnit name="EndUnit">EndUnit</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartChange name="StartChange">StartChange</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartFixedDate name="StartFixedDate">StartFixedDate</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartFixedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#StartFunction1 name="StartFunction1">StartFunction1</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartFunction1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartFunction2 name="StartFunction2">StartFunction2</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartFunction2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartPeriod1 name="StartPeriod1">StartPeriod1</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartPeriod1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartPeriod2 name="StartPeriod2">StartPeriod2</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartPeriod2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartUnit name="StartUnit">StartUnit</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: Group/RetailPeriodCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
