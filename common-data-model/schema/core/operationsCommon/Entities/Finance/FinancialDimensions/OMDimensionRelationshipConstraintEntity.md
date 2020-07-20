---
title: OMDimensionRelationshipConstraintEntity in FinancialDimensions - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Account structure relationships in FinancialDimensions(OMDimensionRelationshipConstraintEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FinancialDimensions/OMDimensionRelationshipConstraintEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account structure relationships</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LeftSegment](#LeftSegment)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[LeftDimensionHierarchyLevel](#LeftDimensionHierarchyLevel)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[LeftAccountStructureName](#LeftAccountStructureName)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[LeftAccountStructureStatus](#LeftAccountStructureStatus)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[LeftReferenceFieldName](#LeftReferenceFieldName)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[OrganizationHierarchyName](#OrganizationHierarchyName)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[RightSegment](#RightSegment)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[RightDimensionHierarchyLevel](#RightDimensionHierarchyLevel)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[RightAccountStructureName](#RightAccountStructureName)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[RightAccountStructureStatus](#RightAccountStructureStatus)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[RightReferenceFieldName](#RightReferenceFieldName)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|
|[BackingTable_DimensionRelationshipConstraintRelationshipId](#BackingTable_DimensionRelationshipConstraintRelationshipId)||<a href="OMDimensionRelationshipConstraintEntity.md" target="_blank">FinancialDimensions/OMDimensionRelationshipConstraintEntity</a>|

### <a href=#LeftSegment name="LeftSegment">LeftSegment</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeftSegment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeftDimensionHierarchyLevel name="LeftDimensionHierarchyLevel">LeftDimensionHierarchyLevel</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeftDimensionHierarchyLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeftAccountStructureName name="LeftAccountStructureName">LeftAccountStructureName</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeftAccountStructureName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeftAccountStructureStatus name="LeftAccountStructureStatus">LeftAccountStructureStatus</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeftAccountStructureStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeftReferenceFieldName name="LeftReferenceFieldName">LeftReferenceFieldName</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeftReferenceFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationHierarchyName name="OrganizationHierarchyName">OrganizationHierarchyName</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RightSegment name="RightSegment">RightSegment</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RightSegment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RightDimensionHierarchyLevel name="RightDimensionHierarchyLevel">RightDimensionHierarchyLevel</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RightDimensionHierarchyLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RightAccountStructureName name="RightAccountStructureName">RightAccountStructureName</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RightAccountStructureName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RightAccountStructureStatus name="RightAccountStructureStatus">RightAccountStructureStatus</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RightAccountStructureStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RightReferenceFieldName name="RightReferenceFieldName">RightReferenceFieldName</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RightReferenceFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DimensionRelationshipConstraintRelationshipId name="BackingTable_DimensionRelationshipConstraintRelationshipId">BackingTable_DimensionRelationshipConstraintRelationshipId</a>

First included in: FinancialDimensions/OMDimensionRelationshipConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionRelationshipConstraintRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Group/DimensionRelationshipConstraint.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionRelationshipConstraint.cdm.json/DimensionRelationshipConstraint</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Group/DimensionRelationshipConstraint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
