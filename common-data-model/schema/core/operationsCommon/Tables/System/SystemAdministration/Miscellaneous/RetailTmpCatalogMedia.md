---
title: RetailTmpCatalogMedia - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailTmpCatalogMedia

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/RetailTmpCatalogMedia.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTmpCatalogMedia/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|
|[CatalogId](#CatalogId)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|
|[CatalogName](#CatalogName)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|
|[MediaFileName](#MediaFileName)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|
|[MediaUrl](#MediaUrl)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|
|[Description](#Description)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|
|[AssociationStatus](#AssociationStatus)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|
|[AssociatedOn](#AssociatedOn)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|
|[AssociationError](#AssociationError)||<a href="RetailTmpCatalogMedia.md" target="_blank">Miscellaneous/RetailTmpCatalogMedia</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTmpCatalogMedia/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CatalogId name="CatalogId">CatalogId</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CatalogName name="CatalogName">CatalogName</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MediaFileName name="MediaFileName">MediaFileName</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MediaFileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MediaUrl name="MediaUrl">MediaUrl</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MediaUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

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

### <a href=#AssociationStatus name="AssociationStatus">AssociationStatus</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociationStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssociatedOn name="AssociatedOn">AssociatedOn</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociatedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AssociationError name="AssociationError">AssociationError</a>

First included in: Miscellaneous/RetailTmpCatalogMedia (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociationError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
