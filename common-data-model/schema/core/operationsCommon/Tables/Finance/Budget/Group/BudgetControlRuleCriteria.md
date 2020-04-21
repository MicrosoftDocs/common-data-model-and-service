---
title: BudgetControlRuleCriteria - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# BudgetControlRuleCriteria

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Group/BudgetControlRuleCriteria.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetControlRuleCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[BudgetControlDimensionAttribute](#BudgetControlDimensionAttribute)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[BudgetControlRule](#BudgetControlRule)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[IsFromOpen](#IsFromOpen)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[IsToOpen](#IsToOpen)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[RangeFrom](#RangeFrom)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[RangeTo](#RangeTo)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[WildCardString](#WildCardString)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[Relationship_BudgetControlDimensionAttributeRelationshipId](#Relationship_BudgetControlDimensionAttributeRelationshipId)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|
|[Relationship_BudgetControlRuleRelationshipId](#Relationship_BudgetControlRuleRelationshipId)||<a href="BudgetControlRuleCriteria.md" target="_blank">Group/BudgetControlRuleCriteria</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetControlRuleCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetControlDimensionAttribute name="BudgetControlDimensionAttribute">BudgetControlDimensionAttribute</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlDimensionAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetControlRule name="BudgetControlRule">BudgetControlRule</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsFromOpen name="IsFromOpen">IsFromOpen</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFromOpen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsToOpen name="IsToOpen">IsToOpen</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsToOpen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RangeFrom name="RangeFrom">RangeFrom</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RangeFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RangeTo name="RangeTo">RangeTo</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RangeTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WildCardString name="WildCardString">WildCardString</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WildCardString attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetControlDimensionAttributeRelationshipId name="Relationship_BudgetControlDimensionAttributeRelationshipId">Relationship_BudgetControlDimensionAttributeRelationshipId</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetControlDimensionAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetControlDimensionAttribute.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetControlDimensionAttribute.cdm.json/BudgetControlDimensionAttribute</a></td><td><a href="BudgetControlDimensionAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetControlRuleRelationshipId name="Relationship_BudgetControlRuleRelationshipId">Relationship_BudgetControlRuleRelationshipId</a>

First included in: Group/BudgetControlRuleCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetControlRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetControlRule.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetControlRule.cdm.json/BudgetControlRule</a></td><td><a href="BudgetControlRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
