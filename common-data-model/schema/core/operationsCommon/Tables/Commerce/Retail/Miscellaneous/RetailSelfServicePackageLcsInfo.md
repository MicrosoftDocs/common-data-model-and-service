---
title: RetailSelfServicePackageLcsInfo - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailSelfServicePackageLcsInfo

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageLcsInfo.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailSelfServicePackageLcsInfo/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[FileAssetId](#FileAssetId)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[FileAssetName](#FileAssetName)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[PackageType](#PackageType)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[FileAssetFileName](#FileAssetFileName)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[FileAssetDescription](#FileAssetDescription)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[IsCustomizationPackage](#IsCustomizationPackage)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[LcsPackageVersion](#LcsPackageVersion)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[RetailPackageVersion](#RetailPackageVersion)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[CustomizationPackageVersion](#CustomizationPackageVersion)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[Publisher](#Publisher)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|
|[PackageCreatedTime](#PackageCreatedTime)||<a href="RetailSelfServicePackageLcsInfo.md" target="_blank">Miscellaneous/RetailSelfServicePackageLcsInfo</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailSelfServicePackageLcsInfo/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FileAssetId name="FileAssetId">FileAssetId</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileAssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileAssetName name="FileAssetName">FileAssetName</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileAssetName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageType name="PackageType">PackageType</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FileAssetFileName name="FileAssetFileName">FileAssetFileName</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileAssetFileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileAssetDescription name="FileAssetDescription">FileAssetDescription</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileAssetDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCustomizationPackage name="IsCustomizationPackage">IsCustomizationPackage</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCustomizationPackage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LcsPackageVersion name="LcsPackageVersion">LcsPackageVersion</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LcsPackageVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailPackageVersion name="RetailPackageVersion">RetailPackageVersion</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPackageVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomizationPackageVersion name="CustomizationPackageVersion">CustomizationPackageVersion</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomizationPackageVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Publisher name="Publisher">Publisher</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Publisher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageCreatedTime name="PackageCreatedTime">PackageCreatedTime</a>

First included in: Miscellaneous/RetailSelfServicePackageLcsInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageCreatedTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>
