---
title: TrvSharedSubCategoryEntity in TravelAndExpense - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Shared expense subcategory in TravelAndExpense(TrvSharedSubCategoryEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/TravelAndExpense/TrvSharedSubCategoryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shared expense subcategory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChargeType](#ChargeType)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|
|[Description](#Description)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|
|[ExcludeFromRecovery](#ExcludeFromRecovery)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|
|[Name](#Name)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|
|[SharedCategory](#SharedCategory)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|
|[SystemCreated](#SystemCreated)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|
|[SharedCategoryId](#SharedCategoryId)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|
|[Relationship_SharedCategoryEntityRelationshipId](#Relationship_SharedCategoryEntityRelationshipId)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|
|[BackingTable_TrvSharedSubCategoryRelationshipId](#BackingTable_TrvSharedSubCategoryRelationshipId)||<a href="TrvSharedSubCategoryEntity.md" target="_blank">TravelAndExpense/TrvSharedSubCategoryEntity</a>|

### <a href=#ChargeType name="ChargeType">ChargeType</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

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

### <a href=#ExcludeFromRecovery name="ExcludeFromRecovery">ExcludeFromRecovery</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeFromRecovery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SharedCategory name="SharedCategory">SharedCategory</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SystemCreated name="SystemCreated">SystemCreated</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SharedCategoryId name="SharedCategoryId">SharedCategoryId</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SharedCategoryEntityRelationshipId name="Relationship_SharedCategoryEntityRelationshipId">Relationship_SharedCategoryEntityRelationshipId</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SharedCategoryEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TrvSharedSubCategoryRelationshipId name="BackingTable_TrvSharedSubCategoryRelationshipId">BackingTable_TrvSharedSubCategoryRelationshipId</a>

First included in: TravelAndExpense/TrvSharedSubCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TrvSharedSubCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Expense/Reference/TrvSharedSubCategory.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Reference/TrvSharedSubCategory.cdm.json/TrvSharedSubCategory</a></td><td><a href="../../../Tables/Finance/Expense/Reference/TrvSharedSubCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
