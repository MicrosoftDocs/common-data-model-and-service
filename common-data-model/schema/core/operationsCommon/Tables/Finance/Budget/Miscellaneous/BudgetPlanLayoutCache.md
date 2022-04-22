---
title: BudgetPlanLayoutCache in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Budget plan layout query cache in Miscellaneous(BudgetPlanLayoutCache)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Miscellaneous/BudgetPlanLayoutCache.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanLayoutCache/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan layout query cache</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[Layout](#Layout)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[BudgetCycle](#BudgetCycle)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[SelectActiveView](#SelectActiveView)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[InsertActiveViewDetail](#InsertActiveViewDetail)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[SelectActiveViewDetail](#SelectActiveViewDetail)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[DeleteActiveView](#DeleteActiveView)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[DeleteActiveViewDetail](#DeleteActiveViewDetail)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[SelectCountActiveView](#SelectCountActiveView)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[DeleteActiveViewDetailSpecific](#DeleteActiveViewDetailSpecific)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[SelectCountActiveViewDetailSpecific](#SelectCountActiveViewDetailSpecific)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[SelectActiveViewDetailUnionAll](#SelectActiveViewDetailUnionAll)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[SelectActiveViewDetailUnionAllSpecific](#SelectActiveViewDetailUnionAllSpecific)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[Relationship_LayoutRelationRelationshipId](#Relationship_LayoutRelationRelationshipId)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|
|[Relationship_BudgetCycleRelationshipId](#Relationship_BudgetCycleRelationshipId)||<a href="BudgetPlanLayoutCache.md" target="_blank">Miscellaneous/BudgetPlanLayoutCache</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanLayoutCache/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Layout name="Layout">Layout</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Layout</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Layout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Layout</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetCycle name="BudgetCycle">BudgetCycle</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget cycle record id</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCycle attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget cycle record id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SelectActiveView name="SelectActiveView">SelectActiveView</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelectActiveView attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#InsertActiveViewDetail name="InsertActiveViewDetail">InsertActiveViewDetail</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsertActiveViewDetail attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SelectActiveViewDetail name="SelectActiveViewDetail">SelectActiveViewDetail</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelectActiveViewDetail attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#DeleteActiveView name="DeleteActiveView">DeleteActiveView</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteActiveView attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#DeleteActiveViewDetail name="DeleteActiveViewDetail">DeleteActiveViewDetail</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteActiveViewDetail attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SelectCountActiveView name="SelectCountActiveView">SelectCountActiveView</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelectCountActiveView attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#DeleteActiveViewDetailSpecific name="DeleteActiveViewDetailSpecific">DeleteActiveViewDetailSpecific</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteActiveViewDetailSpecific attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SelectCountActiveViewDetailSpecific name="SelectCountActiveViewDetailSpecific">SelectCountActiveViewDetailSpecific</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelectCountActiveViewDetailSpecific attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SelectActiveViewDetailUnionAll name="SelectActiveViewDetailUnionAll">SelectActiveViewDetailUnionAll</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelectActiveViewDetailUnionAll attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SelectActiveViewDetailUnionAllSpecific name="SelectActiveViewDetailUnionAllSpecific">SelectActiveViewDetailUnionAllSpecific</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelectActiveViewDetailUnionAllSpecific attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LayoutRelationRelationshipId name="Relationship_LayoutRelationRelationshipId">Relationship_LayoutRelationRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LayoutRelationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetPlanLayout.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanLayout.cdm.json/BudgetPlanLayout</a></td><td><a href="../Group/BudgetPlanLayout.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetCycleRelationshipId name="Relationship_BudgetCycleRelationshipId">Relationship_BudgetCycleRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLayoutCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetCycleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetCycle.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetCycle.cdm.json/BudgetCycle</a></td><td><a href="../Group/BudgetCycle.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
