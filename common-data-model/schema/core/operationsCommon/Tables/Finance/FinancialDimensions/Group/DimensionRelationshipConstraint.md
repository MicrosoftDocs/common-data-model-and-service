---
title: DimensionRelationshipConstraint in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Select relationships in Group(DimensionRelationshipConstraint)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionRelationshipConstraint.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionRelationshipConstraint/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select relationships</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[BackingEntityType](#BackingEntityType)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[Color](#Color)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[DirRelationshipTypeTable](#DirRelationshipTypeTable)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[LeftDimensionHierarchyLevel](#LeftDimensionHierarchyLevel)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[LeftReferenceAttribute](#LeftReferenceAttribute)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[OMHierarchyType](#OMHierarchyType)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[RelationshipConstraintType](#RelationshipConstraintType)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[RightDimensionHierarchyLevel](#RightDimensionHierarchyLevel)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[RightReferenceAttribute](#RightReferenceAttribute)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[Relationship_DirRelationshipTypeTableRelationshipId](#Relationship_DirRelationshipTypeTableRelationshipId)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[Relationship_LeftDimensionHierarchyLevelRelationshipId](#Relationship_LeftDimensionHierarchyLevelRelationshipId)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[Relationship_OMHierarchyTypeRelationshipId](#Relationship_OMHierarchyTypeRelationshipId)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|
|[Relationship_RightDimensionHierarchyLevelRelationshipId](#Relationship_RightDimensionHierarchyLevelRelationshipId)||<a href="DimensionRelationshipConstraint.md" target="_blank">Group/DimensionRelationshipConstraint</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionRelationshipConstraint/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BackingEntityType name="BackingEntityType">BackingEntityType</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingEntityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Color name="Color">Color</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Color attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DirRelationshipTypeTable name="DirRelationshipTypeTable">DirRelationshipTypeTable</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirRelationshipTypeTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeftDimensionHierarchyLevel name="LeftDimensionHierarchyLevel">LeftDimensionHierarchyLevel</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeftDimensionHierarchyLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LeftReferenceAttribute name="LeftReferenceAttribute">LeftReferenceAttribute</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeftReferenceAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OMHierarchyType name="OMHierarchyType">OMHierarchyType</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RelationshipConstraintType name="RelationshipConstraintType">RelationshipConstraintType</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelationshipConstraintType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RightDimensionHierarchyLevel name="RightDimensionHierarchyLevel">RightDimensionHierarchyLevel</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RightDimensionHierarchyLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RightReferenceAttribute name="RightReferenceAttribute">RightReferenceAttribute</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RightReferenceAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_DirRelationshipTypeTableRelationshipId name="Relationship_DirRelationshipTypeTableRelationshipId">Relationship_DirRelationshipTypeTableRelationshipId</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DirRelationshipTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Reference/DirRelationshipTypeTable.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Reference/DirRelationshipTypeTable.cdm.json/DirRelationshipTypeTable</a></td><td><a href="../../../Common/GAB/Reference/DirRelationshipTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LeftDimensionHierarchyLevelRelationshipId name="Relationship_LeftDimensionHierarchyLevelRelationshipId">Relationship_LeftDimensionHierarchyLevelRelationshipId</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LeftDimensionHierarchyLevelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="DimensionHierarchyLevel.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionHierarchyLevel.cdm.json/DimensionHierarchyLevel</a></td><td><a href="DimensionHierarchyLevel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OMHierarchyTypeRelationshipId name="Relationship_OMHierarchyTypeRelationshipId">Relationship_OMHierarchyTypeRelationshipId</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OMHierarchyTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/OMHierarchyType.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/OMHierarchyType.cdm.json/OMHierarchyType</a></td><td><a href="../../../Common/GAB/Main/OMHierarchyType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RightDimensionHierarchyLevelRelationshipId name="Relationship_RightDimensionHierarchyLevelRelationshipId">Relationship_RightDimensionHierarchyLevelRelationshipId</a>

First included in: Group/DimensionRelationshipConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RightDimensionHierarchyLevelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="DimensionHierarchyLevel.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionHierarchyLevel.cdm.json/DimensionHierarchyLevel</a></td><td><a href="DimensionHierarchyLevel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
