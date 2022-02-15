---
title: RetailTmpCatalogProductMediaEntity in Merchandising - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# RetailTmpCatalogProductMediaEntity in Merchandising

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Merchandising/RetailTmpCatalogProductMediaEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Catalog](#Catalog)||<a href="RetailTmpCatalogProductMediaEntity.md" target="_blank">Merchandising/RetailTmpCatalogProductMediaEntity</a>|
|[Product](#Product)||<a href="RetailTmpCatalogProductMediaEntity.md" target="_blank">Merchandising/RetailTmpCatalogProductMediaEntity</a>|
|[FileName](#FileName)||<a href="RetailTmpCatalogProductMediaEntity.md" target="_blank">Merchandising/RetailTmpCatalogProductMediaEntity</a>|
|[Url](#Url)||<a href="RetailTmpCatalogProductMediaEntity.md" target="_blank">Merchandising/RetailTmpCatalogProductMediaEntity</a>|
|[Description](#Description)||<a href="RetailTmpCatalogProductMediaEntity.md" target="_blank">Merchandising/RetailTmpCatalogProductMediaEntity</a>|
|[AssociationStatus](#AssociationStatus)||<a href="RetailTmpCatalogProductMediaEntity.md" target="_blank">Merchandising/RetailTmpCatalogProductMediaEntity</a>|
|[BackingTable_RetailTmpCatalogProductMediaRelationshipId](#BackingTable_RetailTmpCatalogProductMediaRelationshipId)||<a href="RetailTmpCatalogProductMediaEntity.md" target="_blank">Merchandising/RetailTmpCatalogProductMediaEntity</a>|

### <a href=#Catalog name="Catalog">Catalog</a>

First included in: Merchandising/RetailTmpCatalogProductMediaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Catalog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Product name="Product">Product</a>

First included in: Merchandising/RetailTmpCatalogProductMediaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Product attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileName name="FileName">FileName</a>

First included in: Merchandising/RetailTmpCatalogProductMediaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Url name="Url">Url</a>

First included in: Merchandising/RetailTmpCatalogProductMediaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Url attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Merchandising/RetailTmpCatalogProductMediaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociationStatus name="AssociationStatus">AssociationStatus</a>

First included in: Merchandising/RetailTmpCatalogProductMediaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTmpCatalogProductMediaRelationshipId name="BackingTable_RetailTmpCatalogProductMediaRelationshipId">BackingTable_RetailTmpCatalogProductMediaRelationshipId</a>

First included in: Merchandising/RetailTmpCatalogProductMediaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTmpCatalogProductMediaRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/SystemAdministration/Miscellaneous/RetailTmpCatalogProductMedia.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/RetailTmpCatalogProductMedia.cdm.json/RetailTmpCatalogProductMedia</a></td><td><a href="../../../Tables/System/SystemAdministration/Miscellaneous/RetailTmpCatalogProductMedia.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
