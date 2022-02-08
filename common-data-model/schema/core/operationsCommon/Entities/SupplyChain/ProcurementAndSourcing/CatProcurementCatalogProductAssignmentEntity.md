---
title: CatProcurementCatalogProductAssignmentEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Procurement catalog products in ProcurementAndSourcing(CatProcurementCatalogProductAssignmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement catalog products</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProcurementCatalogName](#ProcurementCatalogName)||<a href="CatProcurementCatalogProductAssignmentEntity.md" target="_blank">ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity</a>|
|[ProcurementCatalogCategoryName](#ProcurementCatalogCategoryName)||<a href="CatProcurementCatalogProductAssignmentEntity.md" target="_blank">ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity</a>|
|[ProductNumber](#ProductNumber)||<a href="CatProcurementCatalogProductAssignmentEntity.md" target="_blank">ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity</a>|
|[IsDisplayed](#IsDisplayed)||<a href="CatProcurementCatalogProductAssignmentEntity.md" target="_blank">ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity</a>|
|[ProductRecId](#ProductRecId)||<a href="CatProcurementCatalogProductAssignmentEntity.md" target="_blank">ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity</a>|
|[SharedDataRecId](#SharedDataRecId)||<a href="CatProcurementCatalogProductAssignmentEntity.md" target="_blank">ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity</a>|
|[Origin](#Origin)||<a href="CatProcurementCatalogProductAssignmentEntity.md" target="_blank">ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity</a>|

### <a href=#ProcurementCatalogName name="ProcurementCatalogName">ProcurementCatalogName</a>

First included in: ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Procurement catalog name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCatalogName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement catalog name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCatalogCategoryName name="ProcurementCatalogCategoryName">ProcurementCatalogCategoryName</a>

First included in: ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Procurement catalog category name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCatalogCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement catalog category name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDisplayed name="IsDisplayed">IsDisplayed</a>

First included in: ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductRecId name="ProductRecId">ProductRecId</a>

First included in: ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SharedDataRecId name="SharedDataRecId">SharedDataRecId</a>

First included in: ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedDataRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Origin name="Origin">Origin</a>

First included in: ProcurementAndSourcing/CatProcurementCatalogProductAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Origin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
