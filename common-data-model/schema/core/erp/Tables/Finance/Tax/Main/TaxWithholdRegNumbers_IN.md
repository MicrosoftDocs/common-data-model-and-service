---
title: TaxWithholdRegNumbers_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TaxWithholdRegNumbers_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Tax/Main/TaxWithholdRegNumbers_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdRegNumbers_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[IsGlobal](#IsGlobal)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[Name](#Name)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[RefCompanyId](#RefCompanyId)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[RegistrationNumber](#RegistrationNumber)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[RegistrationType](#RegistrationType)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[TANRegistrationNumber](#TANRegistrationNumber)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[TCSAssessingofficer](#TCSAssessingofficer)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[TCSCircleNumber](#TCSCircleNumber)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[TCSWardNumber](#TCSWardNumber)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[TDSAssessingofficer](#TDSAssessingofficer)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[TDSCircleNumber](#TDSCircleNumber)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|
|[TDSWardNumber](#TDSWardNumber)||<a href="TaxWithholdRegNumbers_IN.md" target="_blank">Main/TaxWithholdRegNumbers_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdRegNumbers_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsGlobal name="IsGlobal">IsGlobal</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGlobal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

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

### <a href=#RefCompanyId name="RefCompanyId">RefCompanyId</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationNumber name="RegistrationNumber">RegistrationNumber</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationType name="RegistrationType">RegistrationType</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TANRegistrationNumber name="TANRegistrationNumber">TANRegistrationNumber</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TANRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSAssessingofficer name="TCSAssessingofficer">TCSAssessingofficer</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCSAssessingofficer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSCircleNumber name="TCSCircleNumber">TCSCircleNumber</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCSCircleNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSWardNumber name="TCSWardNumber">TCSWardNumber</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCSWardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TDSAssessingofficer name="TDSAssessingofficer">TDSAssessingofficer</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TDSAssessingofficer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TDSCircleNumber name="TDSCircleNumber">TDSCircleNumber</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TDSCircleNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TDSWardNumber name="TDSWardNumber">TDSWardNumber</a>

First included in: Main/TaxWithholdRegNumbers_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TDSWardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
