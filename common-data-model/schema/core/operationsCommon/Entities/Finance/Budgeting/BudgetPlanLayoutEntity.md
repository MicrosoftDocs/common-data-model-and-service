---
title: BudgetPlanLayoutEntity in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Budget plan layout elements in Budgeting(BudgetPlanLayoutEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetPlanLayoutEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan layout elements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Layout](#Layout)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[ElementDefinition](#ElementDefinition)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[IsEditable](#IsEditable)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[InWorksheet](#InWorksheet)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[LayoutName](#LayoutName)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[LayoutDescription](#LayoutDescription)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[LayoutDimensionHierarchy](#LayoutDimensionHierarchy)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[DimensionFocusName](#DimensionFocusName)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[DimensionFocusStructureType](#DimensionFocusStructureType)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[ElementDefinitionName](#ElementDefinitionName)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[Ordinal](#Ordinal)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|
|[BackingTable_BudgetPlanLayoutElementRelationshipId](#BackingTable_BudgetPlanLayoutElementRelationshipId)||<a href="BudgetPlanLayoutEntity.md" target="_blank">Budgeting/BudgetPlanLayoutEntity</a>|

### <a href=#Layout name="Layout">Layout</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Layout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElementDefinition name="ElementDefinition">ElementDefinition</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEditable name="IsEditable">IsEditable</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEditable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InWorksheet name="InWorksheet">InWorksheet</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InWorksheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutName name="LayoutName">LayoutName</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Layouts</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Layouts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutDescription name="LayoutDescription">LayoutDescription</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutDimensionHierarchy name="LayoutDimensionHierarchy">LayoutDimensionHierarchy</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutDimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionFocusName name="DimensionFocusName">DimensionFocusName</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionFocusName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionFocusStructureType name="DimensionFocusStructureType">DimensionFocusStructureType</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionFocusStructureType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElementDefinitionName name="ElementDefinitionName">ElementDefinitionName</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Layout elements</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementDefinitionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Layout elements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ordinal name="Ordinal">Ordinal</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordinal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetPlanLayoutElementRelationshipId name="BackingTable_BudgetPlanLayoutElementRelationshipId">BackingTable_BudgetPlanLayoutElementRelationshipId</a>

First included in: Budgeting/BudgetPlanLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetPlanLayoutElementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanLayoutElement.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanLayoutElement.cdm.json/BudgetPlanLayoutElement</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanLayoutElement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
