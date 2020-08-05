---
title: DimensionHierarchyConstraintCriteria in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Segments and allowed values in Miscellaneous(DimensionHierarchyConstraintCriteria)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FinancialDimensions/Miscellaneous/DimensionHierarchyConstraintCriteria.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionHierarchyConstraintCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segments and allowed values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[DimensionHierarchy](#DimensionHierarchy)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Ordinal](#Ordinal)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level1](#Level1)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level2](#Level2)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level3](#Level3)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level4](#Level4)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level5](#Level5)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level6](#Level6)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level7](#Level7)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level8](#Level8)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level9](#Level9)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level10](#Level10)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Level11](#Level11)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[ActiveFrom](#ActiveFrom)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[ActiveTo](#ActiveTo)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[IsOverlapping](#IsOverlapping)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|
|[Relationship_DimensionHierarchyRelationshipId](#Relationship_DimensionHierarchyRelationshipId)||<a href="DimensionHierarchyConstraintCriteria.md" target="_blank">Miscellaneous/DimensionHierarchyConstraintCriteria</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionHierarchyConstraintCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DimensionHierarchy name="DimensionHierarchy">DimensionHierarchy</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Ordinal name="Ordinal">Ordinal</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordinal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Level1 name="Level1">Level1</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level2 name="Level2">Level2</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level3 name="Level3">Level3</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level4 name="Level4">Level4</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level5 name="Level5">Level5</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level6 name="Level6">Level6</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level7 name="Level7">Level7</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level8 name="Level8">Level8</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level9 name="Level9">Level9</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level10 name="Level10">Level10</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level11 name="Level11">Level11</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ActiveTo name="ActiveTo">ActiveTo</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#IsOverlapping name="IsOverlapping">IsOverlapping</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is overlapping</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverlapping attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is overlapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_DimensionHierarchyRelationshipId name="Relationship_DimensionHierarchyRelationshipId">Relationship_DimensionHierarchyRelationshipId</a>

First included in: Miscellaneous/DimensionHierarchyConstraintCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionHierarchyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/DimensionHierarchy.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionHierarchy.cdm.json/DimensionHierarchy</a></td><td><a href="../Group/DimensionHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
