---
title: RetailSelfServicePackageInfo - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailSelfServicePackageInfo

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageInfo.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailSelfServicePackageInfo/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailSelfServicePackageInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageInfo</a>|
|[PackageName](#PackageName)||<a href="RetailSelfServicePackageInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageInfo</a>|
|[PackageFriendlyName](#PackageFriendlyName)||<a href="RetailSelfServicePackageInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageInfo</a>|
|[PackageDescription](#PackageDescription)||<a href="RetailSelfServicePackageInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageInfo</a>|
|[PackageStorageUID](#PackageStorageUID)||<a href="RetailSelfServicePackageInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageInfo</a>|
|[PackageVersion](#PackageVersion)||<a href="RetailSelfServicePackageInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageInfo</a>|
|[PackageType](#PackageType)||<a href="RetailSelfServicePackageInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageInfo</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailSelfServicePackageInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailSelfServicePackageInfo/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PackageName name="PackageName">PackageName</a>

First included in: Miscellaneous/RetailSelfServicePackageInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageFriendlyName name="PackageFriendlyName">PackageFriendlyName</a>

First included in: Miscellaneous/RetailSelfServicePackageInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageFriendlyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageDescription name="PackageDescription">PackageDescription</a>

First included in: Miscellaneous/RetailSelfServicePackageInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageStorageUID name="PackageStorageUID">PackageStorageUID</a>

First included in: Miscellaneous/RetailSelfServicePackageInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageStorageUID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageVersion name="PackageVersion">PackageVersion</a>

First included in: Miscellaneous/RetailSelfServicePackageInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageType name="PackageType">PackageType</a>

First included in: Miscellaneous/RetailSelfServicePackageInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
