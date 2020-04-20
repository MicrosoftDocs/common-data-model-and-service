---
title: RetailMediaGallery - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailMediaGallery

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailMediaGallery.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMediaGallery/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[FileName](#FileName)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[IsDefault](#IsDefault)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[ImageURL](#ImageURL)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[ThumbnailImageURL](#ThumbnailImageURL)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[CustomImageURL](#CustomImageURL)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[ThumbnailImageBlob](#ThumbnailImageBlob)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[CustomImageBlob](#CustomImageBlob)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[SharedStorageRecId](#SharedStorageRecId)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[ThumbnailImageSharedStorageRecId](#ThumbnailImageSharedStorageRecId)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|
|[CustomImageSharedStorageRecId](#CustomImageSharedStorageRecId)||<a href="RetailMediaGallery.md" target="_blank">Miscellaneous/RetailMediaGallery</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMediaGallery/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FileName name="FileName">FileName</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefault name="IsDefault">IsDefault</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefault attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ImageURL name="ImageURL">ImageURL</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImageURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThumbnailImageURL name="ThumbnailImageURL">ThumbnailImageURL</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThumbnailImageURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomImageURL name="CustomImageURL">CustomImageURL</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomImageURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThumbnailImageBlob name="ThumbnailImageBlob">ThumbnailImageBlob</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThumbnailImageBlob attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#CustomImageBlob name="CustomImageBlob">CustomImageBlob</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomImageBlob attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SharedStorageRecId name="SharedStorageRecId">SharedStorageRecId</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedStorageRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThumbnailImageSharedStorageRecId name="ThumbnailImageSharedStorageRecId">ThumbnailImageSharedStorageRecId</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThumbnailImageSharedStorageRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomImageSharedStorageRecId name="CustomImageSharedStorageRecId">CustomImageSharedStorageRecId</a>

First included in: Miscellaneous/RetailMediaGallery (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomImageSharedStorageRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
