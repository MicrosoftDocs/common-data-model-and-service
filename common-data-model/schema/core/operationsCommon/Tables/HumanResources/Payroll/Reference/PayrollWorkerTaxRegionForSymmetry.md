---
title: PayrollWorkerTaxRegionForSymmetry - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PayrollWorkerTaxRegionForSymmetry

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollWorkerTaxRegionForSymmetry.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollWorkerTaxRegionForSymmetry/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PayrollWorkerTaxRegionForSymmetry.md" target="_blank">Reference/PayrollWorkerTaxRegionForSymmetry</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="PayrollWorkerTaxRegionForSymmetry.md" target="_blank">Reference/PayrollWorkerTaxRegionForSymmetry</a>|
|[WorkerTaxRegion](#WorkerTaxRegion)||<a href="PayrollWorkerTaxRegionForSymmetry.md" target="_blank">Reference/PayrollWorkerTaxRegionForSymmetry</a>|
|[MunicipalityId](#MunicipalityId)||<a href="PayrollWorkerTaxRegionForSymmetry.md" target="_blank">Reference/PayrollWorkerTaxRegionForSymmetry</a>|
|[SchoolDistrictId](#SchoolDistrictId)||<a href="PayrollWorkerTaxRegionForSymmetry.md" target="_blank">Reference/PayrollWorkerTaxRegionForSymmetry</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Reference/PayrollWorkerTaxRegionForSymmetry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollWorkerTaxRegionForSymmetry/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Reference/PayrollWorkerTaxRegionForSymmetry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#WorkerTaxRegion name="WorkerTaxRegion">WorkerTaxRegion</a>

First included in: Reference/PayrollWorkerTaxRegionForSymmetry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTaxRegion attribute are listed below.</summary>

</details>

### <a href=#MunicipalityId name="MunicipalityId">MunicipalityId</a>

First included in: Reference/PayrollWorkerTaxRegionForSymmetry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MunicipalityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchoolDistrictId name="SchoolDistrictId">SchoolDistrictId</a>

First included in: Reference/PayrollWorkerTaxRegionForSymmetry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchoolDistrictId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
