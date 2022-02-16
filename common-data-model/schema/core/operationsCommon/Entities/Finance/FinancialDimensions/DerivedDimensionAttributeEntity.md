---
title: DerivedDimensionAttributeEntity in FinancialDimensions - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Derived dimensions in FinancialDimensions(DerivedDimensionAttributeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FinancialDimensions/DerivedDimensionAttributeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DrivingDimension](#DrivingDimension)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension1](#DerivedDimension1)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges1](#PreventChanges1)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension2](#DerivedDimension2)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges2](#PreventChanges2)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension3](#DerivedDimension3)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges3](#PreventChanges3)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension4](#DerivedDimension4)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges4](#PreventChanges4)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension5](#DerivedDimension5)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges5](#PreventChanges5)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension6](#DerivedDimension6)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges6](#PreventChanges6)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension7](#DerivedDimension7)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges7](#PreventChanges7)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension8](#DerivedDimension8)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges8](#PreventChanges8)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension9](#DerivedDimension9)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges9](#PreventChanges9)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[DerivedDimension10](#DerivedDimension10)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[PreventChanges10](#PreventChanges10)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[HierarchyName](#HierarchyName)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[HierarchyStatus](#HierarchyStatus)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[HierarchyType](#HierarchyType)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|
|[BackingTable_DimensionHierarchyBaseEntityRelationshipId](#BackingTable_DimensionHierarchyBaseEntityRelationshipId)||<a href="DerivedDimensionAttributeEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeEntity</a>|

### <a href=#DrivingDimension name="DrivingDimension">DrivingDimension</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DrivingDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension1 name="DerivedDimension1">DerivedDimension1</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges1 name="PreventChanges1">PreventChanges1</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension2 name="DerivedDimension2">DerivedDimension2</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges2 name="PreventChanges2">PreventChanges2</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension3 name="DerivedDimension3">DerivedDimension3</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges3 name="PreventChanges3">PreventChanges3</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension4 name="DerivedDimension4">DerivedDimension4</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges4 name="PreventChanges4">PreventChanges4</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension5 name="DerivedDimension5">DerivedDimension5</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges5 name="PreventChanges5">PreventChanges5</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension6 name="DerivedDimension6">DerivedDimension6</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges6 name="PreventChanges6">PreventChanges6</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension7 name="DerivedDimension7">DerivedDimension7</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges7 name="PreventChanges7">PreventChanges7</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension8 name="DerivedDimension8">DerivedDimension8</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges8 name="PreventChanges8">PreventChanges8</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension9 name="DerivedDimension9">DerivedDimension9</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges9 name="PreventChanges9">PreventChanges9</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimension10 name="DerivedDimension10">DerivedDimension10</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimension10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreventChanges10 name="PreventChanges10">PreventChanges10</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventChanges10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyName name="HierarchyName">HierarchyName</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyStatus name="HierarchyStatus">HierarchyStatus</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyType name="HierarchyType">HierarchyType</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DimensionHierarchyBaseEntityRelationshipId name="BackingTable_DimensionHierarchyBaseEntityRelationshipId">BackingTable_DimensionHierarchyBaseEntityRelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionHierarchyBaseEntityRelationshipId attribute are listed below.</summary>

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
