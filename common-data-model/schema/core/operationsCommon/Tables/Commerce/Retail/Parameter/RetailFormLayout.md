---
title: RetailFormLayout - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailFormLayout

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailFormLayout.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFormLayout/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[FormLayoutId](#FormLayoutId)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[Description](#Description)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[footerXML](#footerXML)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[headerXML](#headerXML)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[LayoutType](#LayoutType)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[linesXML](#linesXML)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[PrintAsSlip](#PrintAsSlip)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[printBehaviour](#printBehaviour)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[PromptQuestion](#PromptQuestion)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[Title](#Title)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|
|[UpperCase](#UpperCase)||<a href="RetailFormLayout.md" target="_blank">Parameter/RetailFormLayout</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFormLayout/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FormLayoutId name="FormLayoutId">FormLayoutId</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#footerXML name="footerXML">footerXML</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the footerXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#headerXML name="headerXML">headerXML</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the headerXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutType name="LayoutType">LayoutType</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#linesXML name="linesXML">linesXML</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the linesXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintAsSlip name="PrintAsSlip">PrintAsSlip</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintAsSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#printBehaviour name="printBehaviour">printBehaviour</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the printBehaviour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PromptQuestion name="PromptQuestion">PromptQuestion</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptQuestion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Title name="Title">Title</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Title attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpperCase name="UpperCase">UpperCase</a>

First included in: Parameter/RetailFormLayout (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpperCase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
