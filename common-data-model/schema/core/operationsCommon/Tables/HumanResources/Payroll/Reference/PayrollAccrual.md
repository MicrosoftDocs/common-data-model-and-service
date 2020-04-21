---
title: PayrollAccrual - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PayrollAccrual

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollAccrual.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollAccrual/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[AccrualId](#AccrualId)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[CanCarryForward](#CanCarryForward)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[Description](#Description)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[IsIncludedInAccrual](#IsIncludedInAccrual)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[StartingDate](#StartingDate)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[AccrualMethod](#AccrualMethod)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[CustomAccrualDate](#CustomAccrualDate)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[Frequency](#Frequency)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|
|[WorkerAccrualDateMethod](#WorkerAccrualDateMethod)||<a href="PayrollAccrual.md" target="_blank">Reference/PayrollAccrual</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollAccrual/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccrualId name="AccrualId">AccrualId</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanCarryForward name="CanCarryForward">CanCarryForward</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanCarryForward attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Reference/PayrollAccrual (this entity)  

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

### <a href=#IsIncludedInAccrual name="IsIncludedInAccrual">IsIncludedInAccrual</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIncludedInAccrual attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartingDate name="StartingDate">StartingDate</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AccrualMethod name="AccrualMethod">AccrualMethod</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomAccrualDate name="CustomAccrualDate">CustomAccrualDate</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomAccrualDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Frequency name="Frequency">Frequency</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Frequency attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkerAccrualDateMethod name="WorkerAccrualDateMethod">WorkerAccrualDateMethod</a>

First included in: Reference/PayrollAccrual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerAccrualDateMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
